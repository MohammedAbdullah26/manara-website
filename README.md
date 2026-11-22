# Manara download page

A static website where people can download the Manara Android app (APK), in English and Arabic.
It's plain HTML and CSS with no build step.

## Files

| Path | What it is |
| --- | --- |
| `index.html` | The English page: download button, install steps, notes |
| `ar.html` | The same page in Arabic, right to left |
| `style.css` | Styles for both pages |
| `logo.png` | App icon, also used as the favicon |
| `screenshots/` | The two phone screenshots on the page |
| `Manara.apk` | **Not in git.** Put the APK here before you upload the site |

The APK isn't committed: it's about 164 MB, and GitHub rejects files over 100 MB.

## Publish it

1. Build the APK in Android Studio (or run `./gradlew assembleDebug` in the app repo), then copy
   `app/build/outputs/apk/debug/app-debug.apk` here as `Manara.apk`.
2. Upload the whole folder (`index.html`, `ar.html`, `style.css`, `logo.png`, `screenshots/`,
   `Manara.apk`) to any static web host.

If your host has a lower file-size limit than the APK, upload the APK somewhere else and put
its full URL in the download link in both pages.

## Releasing a new version

In both `index.html` and `ar.html`, update the places marked `UPDATE`: the download link
(only if the APK isn't next to the page), the version and the file size.

## Preview it on your computer

```powershell
python -m http.server 8090
```

Then open http://localhost:8090.
