---
name: Namshi Landing v3
description: The sports weekly. One issue of an Egyptian sports magazine covering walking as this week's big match, printed in three inks, Arabic first.
colors:
  ink: "#111317"
  paper: "#f4f5f0"
  masthead-yellow: "#ffd21f"
  yellow-hi: "#ffe066"
  paper-dim: "#555a52"
  grey-on-ink: "#c9ccc3"
  ink-2: "#24272c"
  ink-3: "#3a3d42"
  paper-2: "#e2e3dc"
  yellow-2: "#f0bf00"
  yellow-3: "#d6a600"
  yellow-pale: "#ffe46b"
typography:
  display:
    fontFamily: "Lalezar, Changa, sans-serif"
    fontSize: "clamp(2.8rem, 6.2vw, 6.4rem)"
    fontWeight: 400
    lineHeight: 1.12
  display-latin:
    fontFamily: "'Big Shoulders', Changa, sans-serif"
    fontSize: "clamp(2.6rem, 5.4vw, 5.6rem)"
    fontWeight: 900
    lineHeight: 0.95
    letterSpacing: "-0.005em"
  display-back:
    fontFamily: "Lalezar, Changa, sans-serif"
    fontSize: "clamp(3.2rem, 9vw, 8.4rem)"
    fontWeight: 400
    lineHeight: 1.02
  headline:
    fontFamily: "Lalezar, Changa, sans-serif"
    fontSize: "clamp(2.9rem, 7vw, 6rem)"
    fontWeight: 400
    lineHeight: 1.12
  headline-latin:
    fontFamily: "'Big Shoulders', Changa, sans-serif"
    fontSize: "clamp(2.9rem, 7vw, 6rem)"
    fontWeight: 900
    lineHeight: 0.95
    letterSpacing: "-0.005em"
  title:
    fontFamily: "Lalezar, Changa, sans-serif"
    fontSize: "clamp(1.9rem, 3.2vw, 2.7rem)"
    fontWeight: 400
    lineHeight: 1.15
  title-latin:
    fontFamily: "Changa, sans-serif"
    fontSize: "clamp(1.9rem, 3.2vw, 2.7rem)"
    fontWeight: 800
    lineHeight: 1.15
  body:
    fontFamily: "Changa, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.75
  body-latin:
    fontFamily: "Changa, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.6
  lead:
    fontFamily: "Changa, sans-serif"
    fontSize: "1.2rem"
    fontWeight: 400
    lineHeight: 1.75
  label:
    fontFamily: "Changa, sans-serif"
    fontSize: "1rem"
    fontWeight: 800
    lineHeight: 1
  label-small:
    fontFamily: "Changa, sans-serif"
    fontSize: "0.92rem"
    fontWeight: 700
    lineHeight: 1.2
  figure-display:
    fontFamily: "'Big Shoulders', Changa, sans-serif"
    fontSize: "clamp(2.6rem, 8.4vw, 8.2rem)"
    fontWeight: 900
    lineHeight: 0.9
    fontFeature: "tnum"
  figure:
    fontFamily: "'Big Shoulders', Changa, sans-serif"
    fontSize: "1.2rem"
    fontWeight: 800
    lineHeight: 1.2
    fontFeature: "tnum"
rounded:
  none: "0"
  round: "50%"
spacing:
  bar: "4px"
  rule: "2px"
  gutter: "clamp(16px, 4vw, 56px)"
  page: "clamp(84px, 10vw, 140px)"
  container: "1320px"
  control-gap: "10px"
  control: "46px"
components:
  button-primary:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
    rounded: "{rounded.none}"
    padding: "0 18px"
    height: "46px"
    typography: "{typography.label}"
  button-primary-hover:
    backgroundColor: "{colors.masthead-yellow}"
    textColor: "{colors.ink}"
  store-badge:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
    rounded: "{rounded.none}"
    padding: "8px 20px 8px 14px"
    height: "62px"
  store-badge-hover:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
  store-badge-primary:
    backgroundColor: "{colors.masthead-yellow}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    padding: "8px 20px 8px 14px"
    height: "62px"
  store-badge-primary-hover:
    backgroundColor: "{colors.yellow-hi}"
    textColor: "{colors.ink}"
  lang-switch:
    backgroundColor: "{colors.masthead-yellow}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    padding: "0 12px"
    height: "46px"
    typography: "{typography.label}"
  lang-switch-hover:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.masthead-yellow}"
  film-control:
    backgroundColor: "rgba(17, 19, 23, 0.35)"
    textColor: "{colors.paper}"
    rounded: "{rounded.none}"
    padding: "0 14px"
    height: "46px"
    typography: "{typography.label}"
  film-control-hover:
    backgroundColor: "{colors.masthead-yellow}"
    textColor: "{colors.ink}"
  masthead:
    backgroundColor: "{colors.masthead-yellow}"
    textColor: "{colors.ink}"
    height: "68px"
  price-flash:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.masthead-yellow}"
    rounded: "{rounded.round}"
    size: "128px"
  price-flash-back:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.masthead-yellow}"
    rounded: "{rounded.round}"
    size: "160px"
  price-flash-compact:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.masthead-yellow}"
    rounded: "{rounded.round}"
    size: "88px"
  folio-number:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.round}"
    size: "40px"
  minute-ball:
    backgroundColor: "{colors.masthead-yellow}"
    textColor: "{colors.ink}"
    rounded: "{rounded.round}"
    size: "124px"
  cover-ticker:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
    rounded: "{rounded.none}"
    padding: "12px 20px"
    height: "64px"
  cover-ticker-figure:
    textColor: "{colors.masthead-yellow}"
    typography: "{typography.figure-display}"
  league-row-top:
    backgroundColor: "{colors.masthead-yellow}"
    textColor: "{colors.ink}"
  tag-on-yellow:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.masthead-yellow}"
    rounded: "{rounded.none}"
    padding: "1px 7px"
  team-card:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    padding: "18px 20px 20px"
  player-bar:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.masthead-yellow}"
    rounded: "{rounded.none}"
    padding: "10px"
  player-button:
    backgroundColor: "{colors.masthead-yellow}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    size: "44px"
  player-button-hover:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
---

# Design System: Namshi Landing v3

## Overview

**Creative North Star: "The Sports Weekly"**

The surface is one printed issue of an Egyptian sports weekly, and walking in Egypt is this week's big match. It reads front to back like the magazine: a cover, a results spread, the match report, the highlights, the fair-play page, the letters page and the back cover. The issue is printed in three inks only (ink, cool newsprint and masthead yellow), and every spread takes one of them as its ground, alternating so no two neighbours match. Each spread carries a folio in its top corner and is joined to the next by a heavy ink bar. The week's figures are set like a scoreboard that never reflows, printed yellow wherever they sit on ink, and a white route (the walk line) draws itself down the issue as the visitor reads, threading every folio and ending at the download.

Density is tabloid-sports, not dashboard: one giant headline per spread, big numerals, league tables and fixtures lists that read like the back pages. Arabic is the default reading direction and voice; English is a full mirror with its own display face. Material is print: flat ink at full strength, solid ink bars, stickers, emphasis set on printed slabs. There are no photographs anywhere: the cover loop and every film shot are original motion graphics, flat vector scenes drawn in the three inks and their depth tints, with a walker crossing Egypt's landmarks. The real app screens in the match report are the only raster images, and they appear bare in ink frames, never inside device mockups.

The film is the same world in motion. Its type palette (W3 in the Remotion source) holds exactly the same three inks, and its drawn scenes (INK in Illustrated.tsx) add only tints of those inks for depth. It sets Arabic heads in Lalezar and Latin heads and every count in Big Shoulders 900 with Changa for text, runs the yellow masthead with an ink bar, prints its counts in slot numerals (yellow on ink panels and blocks, ink elsewhere), and ends on the cover with the ink price flash. The page's cover loop is a text-free render of the same scenes, in an Arabic and an English cut; all type is HTML.

The build departs from the direction contract in two places, and the build is the record: the contract's four spot colours were cut to three inks at the user's request, and its strict 12-column grid was built as simple fractional two-column grids.

**Key Characteristics:**
- Three inks only: ink, cool newsprint, masthead yellow.
- Spreads alternate grounds: drawn-scene cover, ink results, paper report, ink highlights, yellow fair play, paper letters, yellow back cover, ink colophon.
- Figures on ink print in yellow; everything on yellow or paper prints in ink.
- A 4px ink bar on every control, card, frame and spread seam; square corners, and full circles as the only curves.
- Lalezar for Arabic headlines, Big Shoulders for Latin headlines and every numeral, Changa for text and UI.
- Live figures in fixed slots so a climbing count never reflows, running in a broadcast ticker along the foot of the cover.
- Folios in alternating corners, threaded by the scroll-drawn walk line.
- A rotated ink price flash with a yellow ring stuck beside the store buttons.
- Flat print and drawn scenes: no shadows, no photographs, no stock footage.

## Colors

Three inks at full strength: near-black ink, cool newsprint and one masthead yellow, with two dimmed greys that exist only for secondary text.

### Primary
- **Masthead Yellow** (#ffd21f): the issue's only colour. The sticky masthead, the fair-play and back-cover spreads, the second line of the cover headline, the cover ticker's top bar, the visitor's own store badge, the language switch, hover fills (buttons, film controls, letter questions), the governorate table's top row and today's fixture, every figure on ink (the scoreline, the cover ticker, the player timecode), the highlights title, the price flash's type and ring, minute balls, the walk head, the whole highlights player, the letters' answer signature highlight, the theme colour and the scrollbar track. **Yellow Hi** (#ffe066) is its hover only (primary store badge, big play button).

### Neutral
- **Ink** (#111317): the results, highlights and colophon grounds; all text on yellow and paper; every bar, border and frame; the cover ticker band, the price flash disc, tags on yellow rows, the fair-play highlighter; primary buttons and store badges; the dark stroke of the walk line; selection ground.
- **Paper** (#f4f5f0): cool newsprint. Page ground, the report and letters spreads, text on ink, the first line of the cover headline, folio discs, film-control outlines, the team-of-the-week card, the light stroke of the walk line.
- **Paper Dim** (#555a52): secondary text on paper (report lead and captions, letter senders, card notes, the QR placeholder).
- **Grey On Ink** (#c9ccc3): secondary text on ink (the cover's sample-figures tag, team sub-lines, basis line, notes, table heads, later fixtures, highlights lead and meta, colophon).

### Named Rules
**The Three Inks Rule.** The palette is ink, newsprint and masthead yellow. There is no fourth hue on the page or in the film; Yellow Hi is a hover state and the two greys are secondary text, never grounds.

**The Alternating Grounds Rule.** Each spread's ground is exactly one of ink, paper or yellow, and adjacent spreads never share a ground: drawn-scene cover, ink results, paper report, ink highlights, yellow fair play, paper letters, yellow back cover, ink colophon.

**The Yellow Figures On Ink Rule.** On ink, figures print in yellow (12.8:1) and text prints in paper. On yellow and on paper, everything prints in ink.

**The Yellow Is A Fill On Paper Rule.** Yellow on paper is about 1.3:1, so on paper and yellow grounds yellow appears only as a filled block behind ink type (a top row, a highlight, a hover fill, a minute ball), never as text or a thin line.

### Illustration Depth Tints
The drawn scenes add a small set of tints, each a step of one of the three inks, never a new hue. They appear only inside the scenes (cover loop and film), as far and mid layers, water, ripples and ground lines:
- **Ink 2** (#24272c) and **Ink 3** (#3a3d42): far and mid layers in the night palette. Ink 3 is also the page's hard-coded dark rule (ticker dividers, player track).
- **Paper 2** (#e2e3dc) and Paper 3 (the same value as Grey On Ink): far and mid layers and water in the paper palette.
- **Yellow 2** (#f0bf00), **Yellow 3** (#d6a600) and **Yellow Pale** (#ffe46b): far and mid layers, ground lines and ripples, and water in the day palette.

**The Tints Not Hues Rule.** A depth tint is always a lighter or darker step of ink, paper or yellow. The tints stay inside drawn scenes; page UI and type use only the three inks and the two text greys.

**The Dim Rule.** Secondary text is Paper Dim on paper and Grey On Ink on ink, never an opacity fade. On yellow there is no secondary grey: everything prints in full ink, with weight doing the ranking.

## Typography

**Display Font:** Lalezar for Arabic (with Changa, sans-serif); Big Shoulders for Latin (with Changa)
**Body Font:** Changa in both scripts
**Label/Mono Font:** Big Shoulders 800-900 for every numeral, tabular

**Character:** Lalezar is the loud, heavy Arabic tabloid head; Big Shoulders is the condensed stadium-scoreboard face for Latin heads and every figure in both languages; Changa is the square, sporty text face that keeps UI and copy compact under them.

### Hierarchy
- **Display** (Lalezar 400, clamp(2.8rem, 6.2vw, 6.4rem), 1.12): the cover headline, two lines set straight on the moving scene, the first in paper and the second in yellow, with a soft ink halo. English uses **Display Latin** (Big Shoulders 900, uppercase, clamp(2.6rem, 5.4vw, 5.6rem), 0.95). Under 560px it steps to clamp(2.5rem, 11.5vw, 3.6rem) (English clamp(2.3rem, 10.5vw, 3.2rem)). The sub-line in the other script follows in plain paper Changa 600 1.05rem.
- **Display Back** (Lalezar 400, clamp(3.2rem, 9vw, 8.4rem), 1.02; English 0.9): the back-cover headline, second line on an ink slab in yellow.
- **Headline** (Lalezar 400, clamp(2.9rem, 7vw, 6rem), 1.12): every spread title. English uses **Headline Latin** (Big Shoulders 900, uppercase, 0.95).
- **Title** (Lalezar 400, clamp(1.9rem, 3.2vw, 2.7rem), 1.15): play titles in the match report; the results block titles and team names sit close to it (clamp(1.7-1.8rem ... 2.4-2.8rem)). English titles switch to **Title Latin** (Changa 800), except team names which use Big Shoulders 900 uppercase.
- **Body** (Changa 400, 1.0625rem, 1.75 Arabic / 1.6 English): running copy, capped at 42-64ch.
- **Lead** (Changa, ~1.2rem): the paragraph under a spread title (1.15-1.3rem in practice; the back cover's is 600).
- **Label** (Changa 800, 1rem): buttons, language switch, film controls, letter questions (1.18rem).
- **Label Small** (Changa 700, 0.9-0.92rem): masthead issue and dates, folio running head, table heads (0.85rem), notes.
- **Figure Display** (Big Shoulders 900, 0.9, tabular): slot numerals and hero counts: score up to 8.2rem, minute balls 3.4rem, team stats 2.2rem, the cover ticker 1.9rem (1.5rem on phones).
- **Figure** (Big Shoulders 800, ~1.2rem, tabular, LTR): table values, fixture values, the player's timecode; ranks are 900 at 1.35rem.

### Named Rules
**The Two Faces Per Script Rule.** Arabic headlines are Lalezar 400, never faux-bold. Latin headlines are Big Shoulders 900 uppercase with -0.005em tracking. Every numeral in either language is Big Shoulders, and Changa carries everything else.

**The Slot Rule.** Live figures sit in fixed cells: each character 0.56em wide and centred, comma separators 0.22em, line-height 0.9, left to right, tabular. A climbing count only changes the glyph inside a cell, so nothing around it ever reflows.

**The Isolated Figure Rule.** All figures use Western digits formatted en-US, set left to right in an isolated, non-wrapping, tabular run inside Arabic text.

## Layout

A centred column of 1320px maximum with a fluid gutter of clamp(16px, 4vw, 56px). Each spread is a full-bleed band with block padding of clamp(84px, 10vw, 140px), separated from the next by a 4px ink bar. The masthead is sticky (68px) and the page scroll-pads 80px beneath it.

The cover fills the viewport under the masthead (100svh minus 72px): a full-bleed looping drawn scene (Arabic and English cuts, swapped with the language), kept clean in its top two-thirds, with the content anchored to the bottom (120px top padding, 28px foot). The headline, sub-line, store buttons and price flash sit at the bottom-start; the film controls and the "sample figures" tag sit at the bottom-end; the cover ticker runs full width along the foot. The runner in the loop keeps to the side opposite the headline (30% of the width in Arabic, 70% in English). Under 960px it becomes one column (headline block, then controls), the video's crop follows the runner (object-position 30% in Arabic, 70% in English), and the ticker wraps with its link on its own row. Under 560px the store buttons stack full width with the flash pinned to them.

Spreads use simple two-column splits: results 1.25fr / 0.75fr (stacks under 960px), highlights 0.8fr / 1.2fr (under 900px), letters 0.8fr / 1.2fr (under 860px), back cover content / side (under 860px, the side then runs as a row). The match report is a centre rail: plays alternate screen and text on either side of a 4px ink spine with the minute ball on it (1fr / 150px / 1fr); under 820px the spine moves to 38px from the start edge, balls shrink to 76px, and the screen drops under the text.

The masthead drops its section links under 1100px, the issue and dates under 760px, and its button under 520px.

**The Walk Line Rule.** A single route runs down the whole issue, behind content and over the spread grounds: from the foot of the cover, down each spread's folio edge, crossing sides only in the top margin of the next spread on a smooth curve, through every folio number, and ending just past the start of the back-cover store buttons. It draws itself to 62% of the viewport height as the visitor scrolls. With reduced motion it is drawn complete. It relayouts on resize, font load, language switch and FAQ toggle.

**The Folio Alternation Rule.** Folios sit 22px from the top of each spread and alternate corners: even pages at the end edge, odd pages at the start edge, so the walk line zig-zags down the issue like a route across the pitch.

## Elevation & Depth

Flat print. There are no box shadows anywhere, and the only text shadow is the cover headline's soft legibility halo over the moving scene (0 2px 28px, ink at 0.45). Depth is made by heavy ink bars, by overlap (the cover type over the scene, the walk line passing under content, the minute balls over the spine), and on the cover only by a shade: a bottom-only ink gradient (0.9 at the foot, 0.62 at 30%, 0.3 at 52%, clear by 74%) that leaves the top of the scene clean. Under 960px, where the type covers most of the frame, the whole scene takes a light shade instead (0.9 at the foot, 0.6 at 45%, 0.42 at the top).

### Named Rules
**The Flat Print Rule.** Surfaces are flat ink at full strength. Separation comes from a 4px ink bar, never from a shadow, blur, glass or gradient fill. The one soft shadow in the system is the halo behind cover type on the moving scene, and it is never offset hard or put on a box.

**The Drawn Scene Rule.** Every moving picture is an original flat vector scene drawn only in the three inks and their depth tints, in one of three palettes: day (yellow sky, ink ground and figure, paper sun), night (ink sky, yellow ground, paper figure) and paper (newsprint sky, yellow ground, ink figure). Depth inside a scene comes from far and mid layers in stepped tints of the sky's ink and from looping parallax, never from gradients, texture or shading. No photographs, no stock footage, no halftone, and no colour blocks laid over the scene; the cover shade darkens only the foot where the type sits. App screens are the only raster images, framed only by a 4px ink border.

## Shapes

Cut square and printed heavy. Every rectangle has square corners: buttons, badges, the ticker, cards, frames, the player, the range thumb. The only curves are full circles, and circles mark the issue's stickers and checkpoints: the mark roundel, the price flash, folio discs, minute balls, the big play button and the walk head.

**The Heavy Bar Rule.** The 4px ink bar is the system's stroke: on every button, badge, card, frame, the masthead's foot, the report spine, headline rules and every spread seam. Inner row rules step down to 2px (letters, table heads) and hairlines to 1px at 28% paper on ink. On ink, the stroke that has to read turns yellow: the cover ticker's top bar, the highlights screen and player frame, and the price flash's ring. Over footage, the film controls use a lighter 2px paper outline.

**The Slab Headline Rule.** On printed grounds, emphasis is a solid fit-content slab behind the words, not a colour change of the type: the back cover's second line on ink in yellow; fair-play emphases as an ink highlighter with yellow type, cloned across line breaks; the letters' "Namshi:" signature as ink on a yellow highlight. Over the moving scene there are no slabs: the cover headline sits straight on the picture, with emphasis carried by yellow type on its second line. (The film's cover, printed on a yellow panel, keeps an ink slab with yellow type for its third line.)

## Components

### Buttons
Blunt and printed: solid ink with a 4px ink border, square.
- **Shape:** square corners, 4px ink border, 46px minimum height, 0 18px padding, Changa 800 1rem.
- **Primary:** ink fill with paper text; hover fills yellow with ink text.
- **Press:** drops 2px (translateY) on active; colour transitions at 140ms.
- **Language switch:** yellow with ink border and globe icon; hover inverts to ink with yellow text.
- **Film controls:** outline squares over the cover video, a 2px paper border on 35% ink with paper icons and text; hover fills yellow (border too) with ink.
- **Focus:** 3px ink outline at 3px offset; yellow on ink grounds and on the cover.

### Store Badges
Paired, 62px tall, 4px ink border, square: store glyph, a small Changa 600 prefix and the store name in Big Shoulders 900 1.45rem LTR. The visitor's platform becomes the yellow primary and leads the pair (default Google Play); the other stays ink with paper text and inverts to paper on hover. Under 560px they become an equal grid, full width and start-aligned on the cover.

### Masthead (navigation)
A sticky yellow band with a 4px ink foot: the temporary mark (40px ink roundel with a yellow walker plus the Lalezar wordmark), "الأسبوعية" in Lalezar (English "WEEKLY" in Big Shoulders 900 at 0.08em), then the issue number and the week's dates behind a 2px ink rule. Section links in Changa 700 invert to ink with yellow type on hover; the language switch and "Get it free" button close the row.

### Price Flash (signature)
The round sticker every cover carries: an ink disc with a 4px yellow ring, rotated -9deg, reading "مجاناً" in yellow Lalezar 2.1rem (English "FREE", Big Shoulders 900 2.4rem) over "Android & iPhone" in Changa 700 0.78rem. 128px beside the cover store buttons, 160px on the back cover; under 560px it shrinks to 88px and pins to the end of the stacked store buttons, vertically centred. Decorative (aria-hidden); "free" is also said in the button copy. The film lands the same sticker (ink, yellow ring and type) on its cover.

### Slot Numerals (signature)
The week's step count in the cover ticker, the scoreboard and the film, set per the Slot Rule and ticking every 900ms. On ink they print yellow. Screen readers get a separate live text; under reduced motion the count does not tick.

### Folio and Walk Line (signature)
- **Folio:** a 40px paper disc with a 4px ink border holding the page number in Big Shoulders 900 1.15rem, beside the running head "نمشي الأسبوعية / Namshi Weekly" in Changa 700 0.9rem. Under 600px the disc is 24px with a 3px border, the running head hides, and it sits at the spread's edge.
- **Walk line:** two round-capped strokes on one path, a 12px ink under-stroke and a 5px paper over-stroke (8px and 3px under 600px), so the route reads as an ink-edged white road on every ground. It is led by a walk head: a 17px-radius yellow disc with a 4px ink ring and the walker glyph. The head hides until the line has started.

### Cover Ticker
The week's figures run along the foot of the cover like a match broadcast: a full-width ink band, 64px minimum, under a 4px yellow top bar. Items sit in a row divided by 2px dark-grey rules (#3a3d42): the walkers figure, then the live step count in slot numerals, each in yellow Big Shoulders 900 1.9rem beside Changa 700 1rem paper text, with 12px by 20px padding. The last item, "Inside, p. 2: the governorate table", is pushed to the end edge; it turns yellow on hover and its arrow nudges 4px toward reading direction. Under 960px the band wraps and the link takes its own row under a 2px rule; under 560px items tighten to 12px padding, 0.92rem text and 1.5rem figures.

### Scoreboard and League Table
- **Scoreboard:** on the ink results spread, Egypt vs "the couch" between two 4px paper bars; team names in Lalezar with Grey On Ink sub-lines, the score in yellow slot numerals up to 8.2rem with an en dash in paper.
- **League table:** Changa 700 0.85rem heads in Grey On Ink over a 2px 40% paper rule, rows on 1px 28% paper rules, ranks in Big Shoulders 900, values in Big Shoulders 800 end-aligned LTR. The leader's row fills yellow with an ink "TOP" tag in yellow type; the closing row runs in Grey On Ink.
- **Fixtures:** day, then value in Big Shoulders 800. Today's row fills yellow with an ink "LIVE" tag in yellow type; later days go Grey On Ink and read "to play".
- **Team of the week:** a paper card with a 4px ink border, Lalezar title, stats in Big Shoulders 900 2.2rem over Paper Dim captions.

### Match Report Feed
On the paper report spread, plays hang off a 4px ink spine: a 124px yellow minute ball with an ink ring (Big Shoulders 900 3.4rem, "1'" to "90'"), the app screen in a bare 4px ink frame up to 300px wide (9:15, cropped from the top unless the screen is short), and the ink title and Paper Dim caption on the other side, alternating each play. Short notes print in ink 700.

### Themed Player (signature)
The highlights film plays in place, in the page's language, in yellow on ink.
- **Screen:** 16:9 video on black inside a 4px yellow frame; a 104px yellow big-play disc with an ink ring centred on it (hover scales 1.06 and lifts to Yellow Hi), hidden while playing.
- **Control bar:** ink, 4px yellow border without a top edge, always LTR: 44px square yellow buttons with ink icons (play/pause, mute, full screen; hover paper), a Big Shoulders 800 1.2rem yellow tabular timecode, and a range with an 8px track filled yellow to the playhead over dark grey, with a square 20px paper thumb ringed 3px yellow.
- **Behaviour:** the source loads only on first interaction; playing it pauses the cover video. Full screen hides under 420px. A meta line below offers the vertical cut for Reels.

### Letters (FAQ)
On paper: a 4px ink top bar, then questions divided by 2px ink rows: Changa 800 1.18rem with the sender ("from a reader in Mansoura") in Paper Dim 0.88rem below; hovering a question fills its row yellow; the plus rotates 45deg over 220ms when open. Answers cap at 62ch and open with "Namshi:" in bold ink on a yellow highlight.

### Film
Remotion source, same three inks, every shot a drawn scene. Before the hit, a spot panel beside each scene (the sneaker lacing, the first step, Cairo, the Nile) carries the shot's headline and the climbing count; the panels cycle yellow, ink, paper, yellow, with paper headlines and yellow figures on ink and ink everywhere else. On the hit the montage runs full-bleed through Alexandria, Giza, a crowd, Luxor, Aswan and Sinai, cycling the day, night and paper palettes, under a yellow headline tag with ink type and over a score strip in the shot's ink. The cover lands on a day scene at Giza with yellow headline slabs (third on ink in yellow), an ink count block with a yellow border and yellow figures, and the ink price flash.

### Drawn Scenes (signature)
The illustration kit behind the cover loop and the film (Illustrated.tsx), drawn at 1600 by 900 on a fixed ground line.
- **The walker:** a procedural gait that blends a walk into a run, solved so the lowest foot always rests on the ground line; the ground scrolls at stride speed so feet never skate, and the stride clock carries across cuts. Variants: hero (with a hijab drape that trails and lifts with speed), man, galabiya (a robe to the shin) and kid.
- **Landmark kit:** minaret, dome, Cairo Tower, palm, felucca, pyramid, papyrus column, sphinx, Qaitbay citadel and mountains, tiled in far, mid and near layers that loop with parallax.
- **Close-ups:** a sneaker whose laces draw themselves eyelet to eyelet before the bow springs tight, and a first step that drops, squashes and shakes on landing with an ink impact ring and dust.
- **Palettes:** day, night and paper, per the Drawn Scene Rule. The figure is always the palette's highest-contrast ink against the sky.

### Motion
One easing, cubic-bezier(0.16, 1, 0.3, 1). Controls transition at 140ms and press down 2px. The cover headline lands once, each of its two lines slamming in from scale 1.14 over 520ms, anchored at its bottom-start corner, the second 110ms later. The cover video pauses when off screen and on request. Everything is visible without motion; under prefers-reduced-motion there is no slam, no ticking count, no smooth scroll, and the walk line is drawn in full. The film uses the same slam as a harder, faster landing (from 1.25 over 220ms with overshoot). In the drawn scenes, motion is physical: the walker's gait blends from walk to run with speed, the ground scrolls at stride speed, and landmark layers loop with parallax.

## Do's and Don'ts

### Do:
- **Do** print everything in three inks: ink (#111317), newsprint (#f4f5f0) and masthead yellow (#ffd21f).
- **Do** give every spread one of those three grounds and never repeat it on the next spread.
- **Do** print figures on ink in yellow, text on ink in paper, and everything on yellow or paper in ink.
- **Do** set secondary text in Paper Dim on paper and Grey On Ink on ink.
- **Do** join spreads with a 4px ink bar and put the same 4px ink border on every control, card and frame.
- **Do** set Arabic headlines in Lalezar 400, Latin headlines in Big Shoulders 900 uppercase, and every numeral in Big Shoulders.
- **Do** put live figures in fixed slot cells (0.56em digits, 0.22em separators), Western digits, LTR.
- **Do** give each spread a folio disc in alternating corners and let the walk line thread them to the download.
- **Do** print emphasis on printed grounds as a solid slab behind the words, and set cover type straight on the moving scene with yellow for its second line.
- **Do** stick the ink price flash with its yellow ring, rotated, beside the store buttons on the cover and back cover.
- **Do** draw every moving picture as an original flat scene in the three inks and their depth tints, and frame app screens in a bare 4px ink border.

### Don't:
- **Don't** add a fourth hue, on the page or in the film; depth tints stay inside drawn scenes.
- **Don't** set yellow as text or thin lines on paper or yellow; on light grounds yellow is only a fill behind ink.
- **Don't** round corners; the only curves are full circles for stickers and checkpoints.
- **Don't** add box shadows, hard offset shadows, blur or glass; depth is ink bars and overlap, and the only text shadow is the soft halo on cover type over the moving scene.
- **Don't** use photographs or stock footage, or put halftone, texture, gradients or colour blocks over the scenes.
- **Don't** use a dark app UI, neon rings, phone mockups or feature-card grids.
- **Don't** fade secondary text with opacity.
- **Don't** put kickers or eyebrow labels above headings.
- **Don't** burn type into the cover loop; it is a text-free render under an ink shade.
