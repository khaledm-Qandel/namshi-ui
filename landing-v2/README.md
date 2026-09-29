# Namshi landing, version 2: the cinema poster

A second, alternative design built beside `../landing/`, which is unchanged. The site is a
golden-age Egyptian cinema poster. A live-action film fills the whole hero, with "مشوار
المليون خطوة بيبدأ بخطوة / A million-step journey starts with one step" over it. The week's
figures read like the cast and the box office, and the app's real screens run as a film
strip. Arabic (RTL) is the default; English is one tap away. The Latin name is **Namshi**.

Serve it over HTTP (`npx serve landing-v2`) so the video streams.

## Files

| Path | What it is |
| --- | --- |
| `index.html` | The whole site in one file. |
| `video/namshi-hero-plate-1280x720.mp4` | The hero film with no text, graded, looping, no sound (~5 MB). The page sets its own type over it. |
| `video/namshi-cinema-{ar,en}-1920x1080.mp4` | 16:9 masters with titles and music. They open from "Watch with sound" and are for YouTube and ads. |
| `video/namshi-cinema-{ar,en}-1080x1920.mp4` | 9:16 poster cuts for Reels, TikTok and Stories. |
| `stills/*.webp` | The app screens in the film strip, cropped from `../ui images/`. |
| `../landing/video-src/src/cinema/Cinema.tsx` | Film source (Remotion). Re-render with `node render-cinema.mjs` from `landing/video-src`. |

## Footage and music

The film is about walking. It keeps the shape of the first cut: the first step, lacing up,
people walking, a crowd of feet, the Nile, and a walker under the title. Every shot with a
recognisable setting is filmed in Egypt; I checked each against the clip's own frames. The
close-ups of feet show no location and are kept from the first cut. The footage comes from
**Pexels** (Pexels License) and **Mixkit** (Mixkit Free License). Both allow free commercial
use with no attribution required.

| # | Shot | Where | Source id |
| --- | --- | --- | --- |
| 1 | The first step, close on the shoes | No visible location | Mixkit 23410 |
| 2 | Lacing up | No visible location | Mixkit 15059 |
| 3 | A couple walking towards the Muhammad Ali Mosque | Cairo | Pexels 37728586 |
| 4 | A crowd walking up to the Citadel mosque | Cairo | Pexels 4174560 |
| 5 | Sultan Hassan and the city | Cairo | Mixkit 45410 |
| 6 | A man walking across the terrace of Hatshepsut's temple | Luxor | Pexels 30843329 |
| 7 | Hikers on the path at Saint Catherine | South Sinai | Pexels 4173982 |
| 8 | Many feet on a pavement | No visible location | Mixkit 15997 |
| 9 | Feluccas on the Nile | Aswan | Mixkit 45393 |
| 10 | A woman in an abaya steps past and walks into the desert, under the title | Sinai | Pexels 5973746 |

The shots that were not Egyptian are gone: the European street, the city plaza, the joggers on
a bridge and the sunset silhouette. Pexels clips live in `public/footage/px<id>.mp4`,
transcoded to 1920×1080 at 30 fps. To swap in your own footage, for example walkers on the
Alexandria Corniche, drop the file in `public/footage/` and change its id in `SHOTS` in
`Cinema.tsx`.

**Music:** "Feast From The East" (Mixkit 829). It enters at 13.8 s so its drop lands on the
title.

## Placeholders before launch

- **Logo.** The bone roundel with the walking figure is a stand-in. Replace it in:
  - the nav `.mark`
  - the footer `.mark`
  - the favicon
  - `Mark` in `Cinema.tsx`
- **Store links:** `STORE` in the script.
- **QR:** the ticket stub in the closing section.
- **Footer links.**
- **Weekly figures are sample data.** They are labelled on the page. See `../landing/README.md` for the endpoint the backend needs.
- **Strip screenshots.** The app screenshots still say "Namshy" in places. Re-shoot them once the app uses "Namshi".
