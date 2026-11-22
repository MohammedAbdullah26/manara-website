# Manara download page

A one-page static website where people can download the Manara Android app (APK). It's plain
HTML and CSS with no build step.

## Files

| Path | What it is |
| --- | --- |
| `index.html` | The page: download button, install steps, notes |
| `logo.png` | App icon, also used as the favicon |
| `screenshots/` | The two phone screenshots on the page |
| `Manara.apk` | **Not in git.** Put the APK here before you upload the site |

The APK isn't committed: it's about 164 MB, and GitHub rejects files over 100 MB.

## Publish it

1. Build the APK in Android Studio (or run `./gradlew assembleDebug` in the app repo), then copy
   `app/build/outputs/apk/debug/app-debug.apk` here as `Manara.apk`.
2. Upload the whole folder (`index.html`, `logo.png`, `screenshots/`, `Manara.apk`) to any static
   web host.

If your host has a lower file-size limit than the APK, upload the APK somewhere else and put
its full URL in the download link in `index.html`.

## Releasing a new version

In `index.html`, update the three places marked `UPDATE`: the download link (only if the APK
isn't next to the page), the version and the file size.

## Preview it on your computer

```powershell
python -m http.server 8090
```

Then open http://localhost:8090.
