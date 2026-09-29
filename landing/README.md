# Namshy landing page and film

A design build of the public site that gets people to install Namshy. Arabic (RTL) is the
default, and English is one tap away. Open `index.html` through any static server (the film
will not load over `file://` in some browsers), e.g. `npx serve landing`.

## What is here

| Path | What it is |
| --- | --- |
| `index.html` | The whole site in one file: hero film, "this week in Egypt", the Nile journey (scroll-linked map and odometer), privacy statement, FAQ, download close. |
| `video/namshy-hero-{ar,en}-1080.mp4` | Square hero cut used on the page (1080×1080, 30 fps, ~2 MB). Posters sit beside them. |
| `video/namshy-film-{ar,en}-1920x1080.mp4` | 16:9 master for YouTube, presentations and ads (60 fps). |
| `video/namshy-reel-{ar,en}-1080x1920.mp4` | 9:16 cut for Reels, TikTok and Stories (60 fps). |
| `video-src/` | The film's source (Remotion). `npm run studio` to preview, `node render-all.mjs` to re-render every cut. |
| `map-data.json` | Egypt outline, Nile and the Cairo-to-Luxor route, generated from `video-src/src/egypt-data.json` by `video-src/gen-map.mjs`. Film and site share it. |

## Placeholders to replace before launch

- **Logo.** The green tile with the walking figure is a stand-in copied from the current app
  icon. Replace it in three places: the `.brand-mark` in the nav and footer, the favicon data
  URI in `<head>`, and `video-src/src/Brand.tsx` (then re-render).
- **Store links.** `STORE` near the top of the script in `index.html` holds the placeholder
  Google Play and App Store URLs. The button that matches the visitor's phone is put first
  and filled green automatically.
- **QR code.** The dashed box in the closing section. Generate it from the final download link.
- **Footer links.** Privacy policy, terms and contact point to `#`.

## Numbers on the page are sample data

"This week" (walkers, steps, the per-day bars, Cairo-to-Luxor trips, laps around the Earth) is
illustrative and labelled so on the page. To make it real, the gateway needs one public,
unauthenticated, cached route. None exists among the current 59 routes. For example:

```
GET /public/weekly-pulse
{ "week_start": "2026-09-26", "walkers": 18426, "steps_by_day": [118240110, 124905332, ...], "updated_at": "..." }
```

Aggregate only: no per-user rows. Cache it for a few minutes. The page derives the rest itself.
A million steps is treated as Cairo to Luxor, assuming an average step of about 65 cm.
That assumption is stated on the page.

## Facts the copy relies on (from `docs/SRS.md`)

- Offline recording that syncs later.
- Passive steps from Health Connect / HealthKit.
- Teams joined by code (one team per class or department).
- Challenges and competitions count recorded sessions only; passive steps do not.
- Friends never see route geometry, start or end points.
- Location is used only during a session.
- Every activity is validated, with human review.

The page does not name reward partners, prices or store ratings. Add those only once they are
real.
