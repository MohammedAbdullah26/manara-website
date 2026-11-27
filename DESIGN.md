---
name: Manara
description: The download page for Manara, a Wi-Fi security scanner for Android, drawn as the app's own lighthouse.
colors:
  amber: "#EF9F27"
  gold: "#FAC775"
  dark-amber: "#854F0B"
  amber-ink: "#412402"
  sky-blue: "#85B7EB"
  deep-blue: "#185FA5"
  cream: "#F1EFE8"
  brick: "#A32D2D"
  navy: "#0B1A2E"
  navy-deep: "#071222"
  sea: "#0E2742"
  navy-raised: "#1B2F4A"
  ghost-band: "#13263F"
  porthole-rim: "#24405F"
  warm-white: "#FAEEDA"
  day-sky: "#E6F1FB"
  day-sea: "#D6E7F7"
  day-hair: "#B9D3EE"
  white: "#FFFFFF"
  mark-secure: "#5DCAA5"
  pennant: "#E24B4A"
  mark-unknown: "#B4B2A9"
  pale-red: "#F7C1C1"
  verdict-secure-day: "#0F6E56"
  verdict-vulnerable-night: "#F09595"
  stone: "#5F5E5A"
typography:
  display:
    fontFamily: "Fraunces, Georgia, serif"
    fontSize: "clamp(26px, 7vw, 40px)"
    fontWeight: 500
    lineHeight: 1.12
    letterSpacing: "-0.01em"
  display-arabic:
    fontFamily: "El Messiri, Tahoma, serif"
    fontSize: "clamp(26px, 7vw, 40px)"
    fontWeight: 500
    lineHeight: 1.45
    letterSpacing: "0em"
  headline:
    fontFamily: "Fraunces, Georgia, serif"
    fontSize: "clamp(26px, 6vw, 34px)"
    fontWeight: 500
    lineHeight: 1.15
  headline-arabic:
    fontFamily: "El Messiri, Tahoma, serif"
    fontSize: "clamp(26px, 6vw, 34px)"
    fontWeight: 500
    lineHeight: 1.5
  title:
    fontFamily: "Fraunces, Georgia, serif"
    fontSize: "22px"
    fontWeight: 500
    lineHeight: 1.2
  title-band:
    fontFamily: "Fraunces, Georgia, serif"
    fontSize: "20px"
    fontWeight: 500
    lineHeight: 1.25
  wordmark:
    fontFamily: "Fraunces, Georgia, serif"
    fontSize: "26px"
    fontWeight: 500
    lineHeight: 1
  wordmark-arabic:
    fontFamily: "Aref Ruqaa, serif"
    fontSize: "24px"
    fontWeight: 400
    lineHeight: 1
  lede:
    fontFamily: "system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.5
  body:
    fontFamily: "system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.6
  body-arabic:
    fontFamily: "El Messiri, system-ui, Tahoma, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.8
  button:
    fontFamily: "system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "18px"
    fontWeight: 700
    lineHeight: 1.6
  label:
    fontFamily: "system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.6
    fontFeature: "\"tnum\""
  caption:
    fontFamily: "system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "12.5px"
    fontWeight: 400
    lineHeight: 1.3
  display-wide:
    fontFamily: "Fraunces, Georgia, serif"
    fontSize: "clamp(40px, 3.4vw, 54px)"
    fontWeight: 500
    lineHeight: 1.12
    letterSpacing: "-0.01em"
  headline-wide:
    fontFamily: "Fraunces, Georgia, serif"
    fontSize: "36px"
    fontWeight: 500
    lineHeight: 1.15
  wordmark-wide:
    fontFamily: "Fraunces, Georgia, serif"
    fontSize: "30px"
    fontWeight: 500
    lineHeight: 1
  wordmark-arabic-lead:
    fontFamily: "Aref Ruqaa, serif"
    fontSize: "32px"
    fontWeight: 400
    lineHeight: 1
  wordmark-latin-follow:
    fontFamily: "Fraunces, Georgia, serif"
    fontSize: "19px"
    fontWeight: 500
    lineHeight: 1
  switch:
    fontFamily: "system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 600
    lineHeight: 1.6
rounded:
  pill: "999px"
  gallery-card: "18px"
  fog: "16px"
  note: "14px"
  tile: "11px"
  tile-wide: "14px"
  base: "6px"
  band-cap: "4px"
  porthole: "50%"
spacing:
  gutter: "16px"
  row: "16px"
  card: "20px"
  card-wide: "40px"
  list-lead: "26px"
  step-indent: "56px"
  section: "64px"
  fog-lead: "72px"
  section-wide: "88px"
components:
  download-button:
    backgroundColor: "{colors.amber}"
    textColor: "{colors.amber-ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "14px 28px"
    height: "56px"
  download-button-night:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.amber-ink}"
  download-button-wide:
    width: "320px"
  language-switch:
    backgroundColor: "rgba(11, 26, 46, 0.8)"
    textColor: "{colors.sky-blue}"
    rounded: "{rounded.pill}"
    padding: "5px 15px"
  language-switch-hover:
    textColor: "{colors.warm-white}"
  gallery-card:
    backgroundColor: "{colors.white}"
    textColor: "{colors.navy}"
    rounded: "{rounded.gallery-card}"
    padding: "20px 20px 24px"
  gallery-card-night:
    backgroundColor: "{colors.navy-raised}"
    textColor: "{colors.warm-white}"
  gallery-card-wide:
    padding: "26px 40px 34px"
  tower-band-cream:
    backgroundColor: "{colors.cream}"
    textColor: "{colors.navy}"
    typography: "{typography.title-band}"
    padding: "18px calc(16px + 2.5%) 20px"
  tower-band-brick:
    backgroundColor: "{colors.brick}"
    textColor: "{colors.warm-white}"
    typography: "{typography.title-band}"
    padding: "18px calc(16px + 2.5%) 20px"
  tower-base:
    backgroundColor: "{colors.navy-raised}"
    rounded: "{rounded.base}"
    height: "16px"
  verdict-porthole:
    backgroundColor: "{colors.navy}"
    rounded: "{rounded.porthole}"
    size: "44px"
  step-marker:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.gold}"
    rounded: "{rounded.porthole}"
    size: "36px"
  note:
    backgroundColor: "{colors.day-sea}"
    textColor: "{colors.navy}"
    rounded: "{rounded.note}"
    padding: "16px 18px"
  note-night:
    backgroundColor: "{colors.sea}"
    textColor: "{colors.warm-white}"
  fog-band:
    backgroundColor: "{colors.day-sea}"
    textColor: "{colors.deep-blue}"
    rounded: "{rounded.fog}"
    padding: "18px 20px"
  fog-band-night:
    backgroundColor: "{colors.ghost-band}"
    textColor: "{colors.sky-blue}"
  scene:
    backgroundColor: "{colors.navy-deep}"
    textColor: "{colors.warm-white}"
    height: "clamp(320px, 52svh, 460px)"
  scene-wide:
    height: "clamp(400px, 53svh, 560px)"
  scene-tag:
    textColor: "{colors.sky-blue}"
    typography: "{typography.caption}"
---

# Design System: Manara

## Overview

**Creative North Star: "The Working Lighthouse"**

The site is the Manara app's own lighthouse, drawn for the web, and it is read from the top of the tower to its foot. It opens on the lantern room, an always-night scene where one gold beam sweeps a navy sea and lights networks drawn as boats. Under it, a railing runs across the page and the gallery card hangs from it, holding the lockup and the download. The tower follows as stacked cream and brick bands, and a fog band waits closed at the foot. Every figure is a working signal rather than an ornament: verdicts are buoyage topmarks, the lantern is amber, and the beam is gold. The source of truth for every colour and font is the app itself (`ui/theme/Color.kt` and `docs/design/README.md` in WSS2).

The world has two lights, as the app does. When the phone is in dark mode, the page is lit by the lighthouse: navy water, lamplit white text, and gold for the button and the accent. When the phone is in light mode, the page is known by its painted daymark: a pale sky page, navy text and rules, amber for the button and a darker amber for the accent. The signal code turns round between the two, so the strong colour is dark by day and bright by night. A few things never change: the lantern room stays night, the portholes stay navy, and the tower keeps its cream and brick paint.

The page is calm and single-column, one measure wide, with generous breaks between sections. Content takes the lighthouse's own forms (bands, ruled rows, portholes and waypoints) instead of a grid of feature cards, and the beam is the only thing that moves on its own. Arabic and English are equals: the Arabic page is the same system set right to left, with its own faces and taller lines.

**Key Characteristics:**
- Read from the lantern down: the night scene, the railing and gallery card, the tower bands, and the fog band at the foot.
- Two lights: the daymark palette in light mode and the lantern palette in dark mode, while the lantern room stays night.
- Verdicts are buoyage topmarks in navy portholes, never colour alone.
- Fraunces 500 for titles, the phone's own sans for English text, El Messiri for Arabic, and Aref Ruqaa for the Arabic wordmark only.
- Flat surfaces with two hanging navy shadows, pills for actions, trapezoid bands and round portholes.
- One ambient motion: the beam.

## Colors

A night-sea palette of navies lit by amber and gold, with cream and brick tower paint and four buoyage signal colours, mirrored into a pale daymark palette by day.

### Primary
- **Lantern Amber** (#EF9F27): the download button's fill by day, the lantern in the lighthouse drawing, the masthead light on the connected boat, the dot inside each privacy porthole, and the Moderate cone. It is the colour of the light itself.
- **Beam Gold** (#FAC775): the download button's fill and the accent text by night, the beam and the lantern's glow, the numerals in the install steps, the focus ring, and text selection (Gold behind Navy text).
- **Daymark Amber** (#854F0B): accent text by day (the Arabic half of the lockup, emphasised control names in Arabic, the note's lead-in) and the Moderate verdict word by day.
- **Amber Ink** (#412402): the label on the download button in both modes.

### Secondary
- **Signal Sky Blue** (#85B7EB): secondary text by night, the scene's labels and caption, the language switch label, and the faint swell lines and horizon of the sea.
- **Daymark Blue** (#185FA5): secondary text by day (ledes, intros, meta lines, score ranges, the footer and links) and the scrollbar thumb.

### Tertiary
- **Tower Cream** (#F1EFE8): the light tower bands and the lighthouse's light bands and gallery rail. It is also the Rail colour by night, so the railing, list rules and step rings turn cream after dark.
- **Tower Brick** (#A32D2D): the dark tower bands, the lighthouse cap, and the Vulnerable verdict word by day.

### Neutral
- **Night Navy** (#0B1A2E): the page by night, text and rails by day, every porthole and step disc in both modes, and the glass of the lantern.
- **Deep Night** (#071222): the lantern room's sky and the browser's theme colour. It never changes with the phone's mode.
- **Night Sea** (#0E2742): the top of the sea gradient in the scene, and the note's band by night.
- **Raised Navy** (#1B2F4A): the gallery card by night, the boats' hulls, the lighthouse's rock, and the tower base in both modes.
- **Night Fog** (#13263F): the About band by night (the app's ghost band colour).
- **Porthole Rim** (#24405F): the edge of every porthole and the language switch, the hairlines between rows by night, and the body text on cream bands.
- **Lamplit White** (#FAEEDA): text by night, the boats' sails, the scene's network names, and text on brick bands.
- **Day Sky** (#E6F1FB): the page by day.
- **Day Sea** (#D6E7F7): the note and the About band by day.
- **Haze Line** (#B9D3EE): the hairlines between rows and the install course line by day.
- **Gallery White** (#FFFFFF): the gallery card by day.

### Verdict
The four verdicts each have a fixed mark colour, used inside navy portholes, and a verdict-word colour that follows the mode.
- **Safe Water Green** (#5DCAA5): the Secure mark (one ball) in both modes, and the Secure word by night.
- **Deep Safe Water** (#0F6E56): the Secure word by day.
- **Pennant Red** (#E24B4A): the Vulnerable mark (two stacked balls), the pennant on the open copy's mast, and the body of the isolated-danger buoy.
- **Night Pennant** (#F09595): the Vulnerable word by night and in the scene's labels.
- **Buoy Pale Red** (#F7C1C1): the two balls on top of the isolated-danger buoy.
- **Unlit Grey** (#B4B2A9): the Unknown mark (an unlit ring) in both modes, and the Unknown word by night.
- **Stone** (#5F5E5A): the Unknown word by day.
- The Moderate mark is Lantern Amber; the Moderate word is Beam Gold by night and Daymark Amber by day.

| Role | Day (daymark) | Night (lantern) |
| --- | --- | --- |
| Page | Day Sky | Night Navy |
| Gallery card | Gallery White | Raised Navy |
| Note band | Day Sea | Night Sea |
| About (fog) band | Day Sea | Night Fog |
| Text | Night Navy | Lamplit White |
| Secondary text | Daymark Blue | Signal Sky Blue |
| Accent text | Daymark Amber | Beam Gold |
| Button / on button | Lantern Amber / Amber Ink | Beam Gold / Amber Ink |
| Rail (railing, list rules, step rings) | Night Navy | Tower Cream |
| Hairline | Haze Line | Porthole Rim |
| Secure / Moderate / Vulnerable / Unknown words | Deep Safe Water / Daymark Amber / Tower Brick / Stone | Safe Water Green / Beam Gold / Night Pennant / Unlit Grey |

### Named Rules
**The Daymark Rule.** Every role has a day value and a night value, and the page follows the phone's light or dark mode. Strong is dark by day and bright by night: text and rails are Night Navy by day, and Lamplit White and Tower Cream by night.

**The Navy Porthole Rule.** Verdict marks and the lantern dot in the privacy list sit in Night Navy portholes edged in Porthole Rim, and the install step numbers sit in Night Navy discs, in both modes. Mark colours therefore never change between day and night.

**The Always Night Rule.** The lantern room keeps Deep Night, Night Sea and Lamplit White whatever the phone's mode. Only the page below the railing changes with the light.

**The One Amber Action Rule.** The filled amber pill (Lantern Amber by day, Beam Gold by night) is the download and nothing else. Every other control is a ghost pill, a link or a band.

## Typography

**Display Font:** Fraunces 500 (with Georgia, serif)
**Body Font:** the phone's own sans (system-ui, with -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial) in English; El Messiri 400 and 500 (with system-ui, Tahoma) in Arabic, for titles and text alike
**Wordmark Font:** Aref Ruqaa 400, for منارة in the lockup only

**Character:** A soft, old-style serif for every title, set over the phone's own interface sans, so the page reads like the app it serves. In Arabic, El Messiri carries both titles and text, and the Ruqaa wordmark gives the name its hand.

### Hierarchy
- **Display** (Fraunces 500, clamp(26px, 7vw, 40px), line height 1.12, tracking -0.01em): the one headline in the gallery card. In Arabic it is El Messiri 500 at line height 1.45 with no tracking.
- **Headline** (Fraunces 500, clamp(26px, 6vw, 34px), line height 1.15): section titles. In Arabic, El Messiri 500 at line height 1.5. Headings use balanced wrapping.
- **Title** (Fraunces 500, 22px, line height 1.2): the verdict words in the legend, in their verdict colours. Tower band titles use the same face at 20px and line height 1.25 (1.5 in Arabic).
- **Wordmark** (Fraunces 500, 26px, rising to 30px at 760px and above, line height 1): "Manara" in the lockup. The Arabic wordmark is Aref Ruqaa 400 at 24px in accent beside it. On the Arabic page the order turns round: منارة leads at 32px and "Manara" follows at 19px in accent.
- **Body** (400, 16px, line height 1.6; El Messiri at 1.8 in Arabic): all running text. Ledes are 16px at line height 1.5 (17.5px at 760px and above, 1.75 in Arabic) in secondary text, capped at 34em. Intros are capped at 36em, and lists at 64ch on wide screens.
- **Button** (700, 18px): the download label.
- **Label** (400, 14px, tabular figures): the version and size line, the score ranges beside the verdict words, the install hint and the footer, in secondary text.
- **Caption** (400, 12.5px, line height 1.3, rising to 13.5px at 760px and above): the scene's labels and "An example scan". Network names inside the labels are 600 at 13px (14.5px wide) in Lamplit White.

### Named Rules
**The Medium Weight Rule.** Titles are set at 500 only, in Fraunces for English and El Messiri for Arabic, because the build ships no other title weight. Hierarchy comes from size and colour. El Messiri's 500 file also answers requests for 600 and 700, so Arabic is never synthetically bolded, and Arabic emphasis (control names in the install steps) is 500 plus accent colour.

**The Wordmark-Only Rule.** Aref Ruqaa sets only the word منارة. The shipped file holds those five letters and nothing else, so it cannot set any other text.

**The Tabular Numbers Rule.** Scores, score ranges, versions, sizes, years and step numbers are set in tabular figures.

## Layout

Below 1100px the page is a single column one measure wide: 680px, centred, with 16px gutters on each side (the column is the smaller of the full width less 32px and 680px). The lantern room is the only full-bleed element. Its height is clamp(320px, 52svh, 460px) on phones and clamp(300px, 44svh, 560px) from 760px, so the scene keeps about half of the first screen and the gallery card, with the download, follows directly beneath it.

Vertical rhythm is set by sections, not by a fixed grid. Each section starts 64px below the last (88px at 760px and above). An intro sits 12px under its headline, and the list it introduces starts 26px to 28px further down. Rows inside ruled lists have 16px to 18px of padding top and bottom. The About band sits 72px below the install section, and the footer closes the page with 32px above and 44px below, its two items spread to the ends.

There are two breakpoints.

- **760px:** the boats spread out, with their labels moving beside them instead of under them. The gallery card's padding grows from 20px to 26px 40px 34px, and the download button becomes inline at a 320px minimum width. The verdict legend splits into two columns with a 32px gap, and the tower's taper widens.
- **1100px (laptops and up):** the lantern room fills the first screen, at clamp(600px, 100svh, 980px) tall.
  - **Lighthouse and boats:** the lighthouse rises to 80% of the scene, 5vw from the leading edge, and the boats ride the sea between it and the copy. The beam sweeps from 2° to 70° below the horizon, so it lights the far boat first and the fake copy last.
  - **Copy in the sky:** the gallery card leaves the flow, losing its railing, panel and shadow. The lockup, headline (display-wide), full lede, download button and version are set straight into the night sky at the scene's inline end: 12% down, 6vw in, min(600px, 42vw) wide. They keep the night colours in both modes. The horizon's pale line fades out before it reaches them.
  - **Sections:** the measure widens to 1120px. Each section becomes two columns: its head (headline-wide, 36px, and intro) in a 240-320px column, sticky 48px from the top, and its content in the rest, with a clamp(48px, 6vw, 96px) gap. Sections start 128px apart, and the About band sits in the content column.

Right to left is built in, not patched. Spacing and placement use logical properties (inline start and end), the scene's drawing is mirrored so the lighthouse stays at the leading edge, and Latin runs inside Arabic (network names, people's names, Manara.apk) are isolated. Every boat and its label are placed from the same custom properties, so the two cannot drift apart.

## Elevation & Depth

The system is flat and tonal. Depth comes from mode-aware surfaces stacked on the page (the gallery card, the note band, the fog band) and from the scene's own layers: sky, sea, lighthouse, boats, beam, then labels on top so they stay readable while the beam passes. Only two components are lifted by a shadow, the gallery card and the download pill, and both shadows are navy-tinted with a negative spread, so they fall below the element without a halo. The other shadows in the build draw edges rather than lift.

### Shadow Vocabulary
- **Hanging card** (`box-shadow: 0 18px 36px -18px rgba(7, 18, 34, 0.45)`): the gallery card, as it hangs from the railing.
- **Hanging button** (`box-shadow: 0 8px 18px -8px rgba(7, 18, 34, 0.55)`): the download pill.
- **Day tower edge** (`filter: drop-shadow(0 0 0.75px rgba(11, 26, 46, 0.6)) drop-shadow(0 10px 14px rgba(11, 26, 46, 0.12))`): light mode only. The cream bands would vanish into the pale sky, and the bands' clip path drops borders, so the tower gets a fine navy edge and a soft fall instead.
- **Horizon** (`box-shadow: 0 -1px 0 rgba(133, 183, 235, 0.28)`): the line where the scene's sea meets its sky.
- **Label lift** (`text-shadow: 0 1px 3px #071222`): the scene's labels, to hold them clear of the beam.

### Named Rules
**The Hanging Shadow Rule.** A lifting shadow means something hangs below the railing or waits to be pressed, so only the gallery card and the download pill carry one. The tower's day edge only outlines cream against a pale sky. Every shadow is navy, never neutral black.

## Shapes

Actions are full pills (999px): the download button and the language switch. The gallery card is square at the top, where it meets the railing, and rounded 18px at the bottom. The note (14px) and the About band (16px) are soft rectangles. Portholes, the privacy dots and the step discs are circles. The lockup's navy tile is rounded at a quarter of its size: 11px on a 44px tile, 14px on a 56px tile.

The tower is the recurring silhouette. Each band is a slight trapezoid (its top edge inset 2.2% on each side), and each band is indented by (7 minus its position) steps of 0.9% on phones and 2.2% wide, so the stack widens toward the foot like the lighthouse drawing. The top band takes 4px corners at the top, and the 16px Raised Navy base below the stack takes 6px corners at the bottom. The railing is a 14px band of 2px rules above and below with 2px balusters every 15px.

## Components

### Buttons
Tactile and quiet: one strong pill for the job, and nothing competing with it.
- **Shape:** full pill (999px).
- **Primary (Download for Android):** Lantern Amber by day and Beam Gold by night, with an Amber Ink label at 18px and 700. A 22px download glyph (an inline SVG arrow into a tray, 2.2 stroke, round caps) leads the label with a 12px gap. Minimum height 56px, padding 14px 28px, hanging button shadow. Full width on phones, inline at a 320px minimum width at 760px and above. It appears twice: in the gallery card and at the end of the install steps.
- **Hover / Active:** brightness rises to 1.06 and the pill lifts 1px; pressing moves it 1px down. Transitions run 0.25s on cubic-bezier(0.16, 1, 0.3, 1) and are removed under reduced motion.
- **Focus:** every focusable element takes a 3px outline, offset 3px, with 6px corners, in the accent colour: Beam Gold by night and Dark Amber (#854F0B) by day, which clears 3:1 against Day Sky and Gallery White. Inside the always-night hero (the lantern room and its language switch) the ring stays Beam Gold in both modes.
- **Language switch (ghost pill):** sits in the scene's top inline-end corner, 16px in. Night Navy glass at 80% opacity, a 1px Porthole Rim edge, padding 5px 15px, a Signal Sky Blue label at 15px and 600, set in the target language's own face (El Messiri for العربية, the system sans for English). On hover the label turns Lamplit White and the edge Signal Sky Blue.

### Links
- **Style:** secondary text colour with a 1px underline offset 0.22em. On hover they take the text colour.

### Gallery Card and Railing
- **Railing:** the 14px rail band in the Rail colour (Night Navy by day, Tower Cream by night), running the width of the column directly above the card.
- **Corner Style:** square top, 18px bottom corners.
- **Background:** Gallery White by day, Raised Navy by night.
- **Shadow Strategy:** the hanging card shadow (see Elevation & Depth).
- **Internal Padding:** 20px 20px 24px on phones, 26px 40px 34px at 760px and above.
- **Contents, in order:** the lockup (the navy tile mark, 44px on phones and 56px wide, with a 12px gap to the wordmarks), the display headline, the lede in secondary text (one line on phones, the full sentence wide), the download pill, the version and size line, and, on devices that are not Android, a hint to open the page on the phone.

### Verdict Legend
The buoyage key: each verdict as its topmark, word, range and meaning.
- **Structure:** a ruled list. A 2px Rail rule opens it, and each row closes with a 1px hairline. Each row is a 48px column holding a 44px porthole mark, then the text, with 16px to 18px of row padding.
- **Marks:** each mark is a Night Navy porthole edged in Porthole Rim, holding one ball (Secure), a cone (Moderate), two stacked balls (Vulnerable) or an unlit ring (Unknown) in its fixed mark colour.
- **Type:** the verdict word in the title style and its verdict colour, followed by the score range as a label in secondary text and the body face; the explanation is body text in the text colour.
- **Wide:** two columns with a 32px gap.

### Tower Bands
The page's list of what Manara catches, drawn as the lighthouse's painted tower.
- **Bands:** stacked flush with no gap, alternating Tower Cream (Night Navy title, Porthole Rim text) and Tower Brick (Lamplit White title and text) by position, never by meaning.
- **Shape:** trapezoids that widen toward the foot (see Shapes), padding 18px plus a proportional inline inset (20px plus 3% wide).
- **Type:** the band title at 20px, the body at 15.5px, 6px apart.
- **Base:** the 16px Raised Navy slab with 6px bottom corners.
- **Day:** the day tower edge shadow outlines the stack. On this site the tower lists capabilities rather than networks, so its bands carry no portholes.

### Privacy Facts
- **Structure:** the same ruled list as the legend: a 2px Rail rule above and a hairline under each row, with 16px row padding and a 34px inline-start indent.
- **Marker:** a 21px porthole holding the lantern's light: Night Navy, a 1px Porthole Rim edge, and a Lantern Amber dot at its centre.

### Install Steps
A course of numbered waypoints.
- **Waypoint:** a 36px Night Navy disc with a 2px Rail ring and a Beam Gold numeral at 700 in tabular figures.
- **Course line:** a 2px hairline runs from each disc down to the next, stopping at the last step.
- **Text:** indented 56px from the inline start, 22px between steps. Control names are emphasised (in accent colour on the Arabic page).

### Note
- **Style:** the Note band colour (Day Sea by day, Night Sea by night), 14px corners, 16px 18px padding, with its lead-in in accent. Consecutive notes sit 10px apart.

### Fog Band (About)
The band at the foot of the tower, closed until tapped.
- **Style:** the Fog colour (Day Sea by day, Night Fog by night), 16px corners, 72px below the content above.
- **Summary row:** padding 18px 20px, secondary text at 600, with a 20px chevron at the inline end that turns 180 degrees over 0.3s on cubic-bezier(0.16, 1, 0.3, 1) when the band opens. The disclosure triangle is hidden.
- **Body:** padding 0 20px 22px, paragraphs 10px apart.

### Lantern Room (Signature)
The opening scene, always at night.
- **Sky and sea:** Deep Night above; from 46% down, a Night Sea to Night Navy gradient crossed by faint Signal Sky Blue swell lines (1px every 16px at 7% opacity), with the horizon line on top.
- **Lighthouse:** an inline drawing at 70% of the scene's height, set 4vw (at least 14px) from the leading edge on phones and 7vw wide: cream and brick bands, a brick cap, a navy lantern room with an amber lantern and a soft gold glow, a cream gallery rail, and a Raised Navy rock.
- **Boats:** networks are sailboats with Lamplit White sails and Raised Navy hulls. Far boats sit at 45% opacity and middle boats at 75%. The connected boat carries a lit amber masthead lantern; the open copy flies a Pennant Red pennant, and an isolated-danger buoy (Pennant Red body, a navy band, two pale red balls) floats beside it.
- **Beam:** a 14-degree Beam Gold wedge, at most 62% opaque, fading out radially and blended in screen mode, turning on the lantern. It sweeps once every 9s, linear, from just above the horizon down to the nearest boat, fading in over the first 7% of the cycle and out after 68%. Under reduced motion it rests on the open copy.
- **Labels:** above the beam, an 18px porthole mark with 7px to the text, then the network name, and the verdict word in its night verdict colour (Unknown stays Signal Sky Blue), the rest in Signal Sky Blue, at most 13.5em wide, with the label lift shadow. On phones they sit under their boats; at 760px and above they move beside them.
- **Caption:** "An example scan" in caption type and Signal Sky Blue at the bottom inline-end corner.

## Do's and Don'ts

### Do:
- **Do** take every colour from the brand and the day and night roles above; the source of truth is the app's `ui/theme/Color.kt`.
- **Do** give every verdict its buoyage shape and its word as well as its colour: one ball for Secure, a cone for Moderate, two stacked balls for Vulnerable, and an unlit ring for Unknown.
- **Do** keep verdict marks and the lantern dot in Night Navy portholes edged in Porthole Rim, and step numbers in Night Navy discs, in both modes.
- **Do** open ruled lists with a 2px Rail rule and close each row with a 1px hairline, as the legend and the privacy facts do.
- **Do** set titles at 500 only, in Fraunces for English and El Messiri for Arabic, and set numbers in tabular figures.
- **Do** build right to left with logical properties, mirror the scene's drawing so the lighthouse stays at the leading edge, and isolate Latin runs inside Arabic.
- **Do** let the beam be the only ambient motion, keep state transitions to 0.25s to 0.3s on cubic-bezier(0.16, 1, 0.3, 1), and remove them under reduced motion, where the beam rests on the fake copy.

### Don't:
- **Don't** draw Unknown in green or with a safe-looking mark; it is an unlit grey ring.
- **Don't** let a tower band's colour carry meaning; cream and brick alternate by position, and danger is told by the Pennant Red mark in its porthole and the Vulnerable word.
- **Don't** put the lantern room on the day palette; it stays night in both modes.
- **Don't** set any text but منارة in Aref Ruqaa, or ask Fraunces for a weight other than 500.
- **Don't** add a second filled amber button; the amber pill is the download.
- **Don't** use neutral black shadows, or lift anything but the gallery card and the download pill.
