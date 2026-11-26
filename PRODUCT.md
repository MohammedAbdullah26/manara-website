# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

The general public: people who want to check a Wi-Fi network before they join it, many of them
Arabic speakers. They reach the site from a shared link, usually on the Android phone they will
install Manara on, sometimes on a computer first. Their job on the site is to understand what
Manara does, trust it enough to install an app from outside the Play Store, and get it running.

## Product Purpose

The site is where Manara is downloaded. Manara is a Wi-Fi security scanner for Android that
checks a network before you trust it. The app is not on the Play Store: the site serves the APK
and walks people through installing it. Success is a visitor who downloads the APK, installs it,
and allows precise location so the first scan works.

## Positioning

Manara does its work on the phone. It flags fake copies of networks (evil twins) and risky
hotspots before you join them, checks the connected network in five stages, and explains each
finding in plain language. It is honest about what it couldn't check: a quiet result from a thin
check is shown as Unknown, never as safe.

## Operating Context

- Android 7.0 or later. The APK is a debug build of version 1.0, about 164 MB, installed by
  sideloading: the browser needs "install unknown apps" permission, and Play Protect may warn
  about an unknown app.
- The app needs precise location (Android only gives Wi-Fi scan results to apps that have it).
- The APK is attached to this repo's GitHub Release as `Manara.apk`; the download link is
  `https://github.com/MohammedAbdullah26/manara-website/releases/latest/download/Manara.apk`.
- The site is static and hosted on Vercel, which redeploys on every push to `main`.
- The site opens in the visitor's phone language (Arabic or English), with a switch on every page.

## Capabilities and Constraints

What the app does (from the app's README, WSS2):
- Scans nearby networks and scores each 0 to 100 before you connect: Secure (75+), Moderate
  (40 to 74), Vulnerable (below 40), or Unknown.
- Detects evil twins and fake hotspots: an open copy of a protected network, a router address used
  by two devices or with different hardware, phone hotspots named like an organisation.
- Checks the connected network in five stages, including an optional 30-second traffic test with
  an on-device AI model.
- Access point radar (Locate) that guides you to the router.
- Nearby warnings between Manara phones, and online dangerous-network reports (signed-in users).
- Saved networks (encrypted on the device), accounts with cloud backup, background checks and
  alerts, History and Settings tabs, Advanced Detection.
- Arabic and English, and day, night or system theme.

Privacy facts: scanning, scoring, the five-stage check and the AI model run on the phone. The
traffic test counts packets and builds flow statistics; payloads aren't stored. Nearby warnings,
online reports and cloud backup are off until the user turns them on (reports and backup need an
account).

Terminology: Manara (منارة, Arabic for lighthouse), evil twin (توأم شرير), hotspot (نقطة اتصال),
router (راوتر), precise location (الموقع الدقيق), Wi-Fi (واي فاي), Android (أندرويد). In Arabic,
Manara is grammatically feminine ("تحتاج منارة").

## Brand Commitments

- Name: Manara / منارة. Lockup: the navy tile mark + "Manara" in Fraunces 500 + "منارة" in
  Aref Ruqaa 400.
- The site keeps the app's whole lighthouse world (confirmed by the user): its night and day
  palettes, its fonts (Fraunces for titles, El Messiri for Arabic text, Aref Ruqaa for the Arabic
  wordmark), and its nautical vocabulary: the tower and its bands, buoyage topmarks for verdicts,
  light characteristics, the lantern, the beam and the boats. Source of truth: the app's
  `ui/theme/Color.kt` and `docs/design/README.md` in WSS2.
- Voice: plain, calm and honest. Say what Manara found and what to do; never promise "safe".

## Evidence on Hand

- Logo: `logo.png`. App screenshots: `screenshots/scan-limit.png`, `screenshots/settings-tab.png`.
  More are in WSS2 `docs/screenshots/`, but most show a personal network name and must not be
  published.
- Team (for the About section): SDP-G25, Senior Design Project 2026, Qatar University, Department
  of Computer Science and Engineering, College of Engineering. Supervisor: Dr. Mucahid Kutlu.
  Members: Mohammed Abdullah, Elfadil Ahmed, Ahmed Laghdaf, Faisal Bu-Shawareb.
- Absent, and not to be invented: user counts, ratings, reviews, testimonials, press, store
  listings, detection-rate or accuracy figures.

## Product Principles

1. The download is the job: every section helps a visitor install Manara or trust it enough to.
2. Honest over reassuring: never call a network or the app "safe"; say what it checks and what it
   can't.
3. The phone does the work: privacy is a fact to state plainly, not a slogan.
4. Arabic and English are equals: same content, same care, right to left done properly.

## Accessibility & Inclusion

- Full parity between the Arabic (right to left) and English pages.
- Follows the phone's light or dark mode, like the app's System theme.
