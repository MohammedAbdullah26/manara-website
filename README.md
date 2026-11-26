# Manara download page

A static website where people can download the Manara Android app (APK), in English and Arabic.
It's plain HTML and CSS with no build step. It's hosted on Vercel at
https://manara-sooty-xi.vercel.app, which redeploys every time `main` is pushed.

The page is drawn in the app's own lighthouse world: it opens on the lantern room, where
Manara's beam sweeps a night sea and each network, drawn as a boat, carries its verdict mark.

## Files

| Path | What it is |
| --- | --- |
| `index.html` | The English page |
| `ar.html` | The same page in Arabic, right to left |
| `style.css` | Styles for both pages, with the app's night and day colours |
| `fonts/` | The app's fonts as web fonts (Fraunces, El Messiri, and Aref Ruqaa cut down to "منارة"), with their SIL OFL licences |
| `logo.png` | App icon, used in the lockup and as the favicon |
| `PRODUCT.md` | What Manara is and who the site is for (design notes, not served) |
| `.impeccable/` | Design notes from the Impeccable skill (not served) |
| `.vercelignore` | Keeps the design notes and any local APK out of the deployed site |

The site opens in the visitor's phone language: `index.html` sends Arabic phones to `ar.html`.
Once someone uses the language switch, their choice is remembered on that phone.

## Where the APK lives

The APK isn't in git: it's about 164 MB, and GitHub rejects files over 100 MB. It's attached to
this repo's [GitHub Releases](https://github.com/MohammedAbdullah26/manara-website/releases)
instead, as `Manara.apk`. All the download buttons link to

```
https://github.com/MohammedAbdullah26/manara-website/releases/latest/download/Manara.apk
```

which always gives the newest release's `Manara.apk`, so the link never needs changing.

## Releasing a new version

1. Build the APK in Android Studio (or run `./gradlew assembleDebug` in the app repo), then copy
   `app/build/outputs/apk/debug/app-debug.apk` into this folder as `Manara.apk`. The file must be
   named exactly `Manara.apk`, or the download link won't find it.
2. Create a release with the APK attached (change the version):

   ```powershell
   gh release create v1.1 Manara.apk --title "Manara 1.1" --notes "What changed in this version."
   ```

3. In both `index.html` and `ar.html`, update the version and the file size under the download
   button (marked `UPDATE`) and the version in the footer. Commit and push, and Vercel updates
   the site.

## Preview it on your computer

```powershell
python -m http.server 8090
```

Then open http://localhost:8090.
