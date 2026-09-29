# Namshi landing, version 3: the sports weekly

A third, alternative design built beside `../landing/` (v1) and `../landing-v2/` (v2),
which are unchanged. The manager picks one of the three.

The site is one issue of a sports weekly, "نمشي الأسبوعية / Namshi Weekly". Walking in
Egypt is the week's big match. The issue runs in this order:

1. **Cover**: the headline, the week's figures, and a "Free" flash beside the store buttons.
2. **Results spread** (black): Egypt vs the couch, the governorate table, the day-by-day
   fixtures, and the team of the week.
3. **Match report** (white): how the app plays, minute by minute, on its real screens.
4. **Highlights**: the film.
5. **Fair play** (yellow): privacy.
6. **Readers' letters**: the FAQ.
7. **Back cover** (yellow): "Next issue, you're on the cover."

The whole issue is printed in three inks only: masthead yellow, black and white.

A white walk line draws itself down the issue as you scroll. It threads each page number
and ends at the download buttons.

Arabic (RTL) is the default and English is one tap away. The Latin name is **Namshi**.

Serve it over HTTP (`npx serve landing-v3`) so the videos stream.

## Files

| Path | What it is |
| --- | --- |
| `index.html` | The whole site in one file. |
| `video/namshi-weekly-hero-{ar,en}-1280x720.mp4` | The cover's looping video: the drawn runner crossing Egypt at night, no type, no sound. One per language, so the runner keeps to the side opposite the headline. |
| `video/namshi-weekly-hero-{ar,en}-poster.jpg` | The cover and highlights posters. |
| `video/namshi-weekly-{ar,en}-1920x1080.mp4` | 16:9 masters with titles and music, for YouTube and ads. |
| `video/namshi-weekly-{ar,en}-1080x1920.mp4` | 9:16 cuts for Reels, TikTok and Stories. The page links to the one in the current language. |
| `video/namshi-weekly-{ar,en}-web-1280x720.mp4` | The copies the highlights player streams. |
| `video/*.json`, `stills/*.webp.json` | Provenance for every shipped file. |
| `stills/*.webp` | The app screens in the match report, cropped from `../ui images/`. |
| `../landing/video-src/src/sport/Sport.tsx` | Film source (Remotion). Re-render with `node render-sport.mjs` from `landing/video-src`. |

## The film

The film is 24 seconds of original motion graphics, drawn and animated in code in the issue's
three inks. It uses no stock footage.

- **The masthead** stays on screen throughout.
- **Before the music hits**, a colour panel counts the steps beside each shot:
  - a sneaker laces itself
  - the first step lands with dust and an impact ring
  - a woman in a sports hijab walks through old Cairo (minarets, domes, Cairo Tower), then
    along the Nile
- **On the hit (8 s)** she breaks into a run under "مصر كلها ماشية / All of Egypt is
  walking", past:
  - Alexandria and Qaitbay at night
  - the Giza pyramids
  - a crowd walking together (a man, a man in a galabiya, a child, women)
  - Luxor's columns and sphinxes
  - Aswan's feluccas
  - Mount Sinai

  The score strip climbs as she goes.
- **At 15.3 s** the cover lands: the runner at the pyramids, 1,000,000, the stacked headline,
  "On the cover: you", the store line, and the "Free" flash.

The site's cover loop is the same runner crossing Cairo, the Nile, Giza, Luxor and Sinai at
night, with no type.

Everything is drawn in `../landing/video-src/src/sport/Illustrated.tsx`:

- **The walker** (`Walker`) is a procedural gait. The pose is solved so a foot always rests on
  the ground, and the ground scrolls at stride speed so the feet never slide.
- **The landmarks** are vector kits: minaret, dome, Cairo Tower, felucca, pyramid, papyrus
  column, sphinx, Qaitbay, mountains.
- **Palettes:** each scene uses one of three palettes (day, night, paper), all built from
  yellow, ink and newsprint.

**Music:** "Trap Electro Vibes" (Mixkit 126, Mixkit Free License). It enters at 40 s so the
first hit lands on the run.

## Placeholders before launch

- **Logo.** The yellow-on-ink walker roundel is a stand-in. Replace it in:
  - the masthead `.mark`
  - the colophon `.mark`
  - the favicon
  - `Mark` in `Sport.tsx`
- **Store links:** `STORE` in the script.
- **QR:** on the back cover.
- **Footer links.**
- **Sample figures, labelled on the page.** All of these need wiring to the app's real totals
  (see `../landing/README.md` for the endpoint the backend needs):
  - the week's steps and walkers
  - the daily fixtures
  - the governorate table
  - the team of the week
- **Match-report screens.** They come from a test build: English, with sample names. The page
  says so under the section intro. Two are cropped:
  - The badges screen drops a "Redeem a Coffee" reward card.
  - The challenge screen drops a paragraph promising store credit.

  Re-shoot all six from the Arabic build once it ships.
