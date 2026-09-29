---
name: Namshy Landing
description: Egypt is the track. The public landing page, set in the app's own night, walks the visitor from Cairo to Luxor.
colors:
  ground: "#0e121e"
  ground-2: "#111827"
  card: "#1c252e"
  card-2: "#232d37"
  line: "#27313c"
  line-2: "#36424f"
  land: "#161e29"
  river: "#2c5660"
  green: "#00ff85"
  green-hover: "#5cffae"
  green-ink: "#03140b"
  green-deep: "#0d2a28"
  green-edge: "#17784a"
  ink: "#eef1f5"
  ink-dim: "#a6afb9"
  ink-faint: "#8d97a3"
  amber: "#f5a524"
  coral: "#ff8f63"
typography:
  display:
    fontFamily: "Alexandria, Readex Pro, system-ui, sans-serif"
    fontSize: "clamp(2.4rem, 4.2vw, 4rem)"
    fontWeight: 800
    lineHeight: 1.22
    letterSpacing: "normal"
  headline:
    fontFamily: "Alexandria, Readex Pro, system-ui, sans-serif"
    fontSize: "clamp(2rem, 3.6vw, 3.25rem)"
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: "normal"
  title:
    fontFamily: "Alexandria, Readex Pro, system-ui, sans-serif"
    fontSize: "clamp(1.4rem, 2vw, 1.75rem)"
    fontWeight: 700
    lineHeight: 1.35
  statement:
    fontFamily: "Alexandria, Readex Pro, system-ui, sans-serif"
    fontSize: "clamp(1.35rem, 2.4vw, 2.1rem)"
    fontWeight: 500
    lineHeight: 1.7
  figure:
    fontFamily: "Alexandria, Readex Pro, system-ui, sans-serif"
    fontWeight: 700
    fontFeature: "tnum"
  figure-hero:
    fontFamily: "Alexandria, Readex Pro, system-ui, sans-serif"
    fontSize: "clamp(3.6rem, 12vw, 10rem)"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "-0.02em"
  body:
    fontFamily: "Readex Pro, Alexandria, system-ui, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.75
    fontFeature: "tnum"
  lead:
    fontFamily: "Readex Pro, Alexandria, system-ui, sans-serif"
    fontSize: "clamp(1.1rem, 1.5vw, 1.3rem)"
    fontWeight: 400
    lineHeight: 1.75
  label:
    fontFamily: "Readex Pro, Alexandria, system-ui, sans-serif"
    fontSize: "0.9rem"
    fontWeight: 400
    lineHeight: 1.3
rounded:
  tile: "12px"
  md: "16px"
  dock: "20px"
  card: "24px"
  frame: "32px"
  pill: "999px"
spacing:
  gutter: "clamp(16px, 4vw, 48px)"
  max: "1240px"
  nav-h: "72px"
  column-gap: "clamp(32px, 5vw, 80px)"
  section: "clamp(72px, 9vw, 128px)"
  station: "clamp(72px, 10vw, 120px)"
components:
  store-button:
    backgroundColor: "{colors.card}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
    padding: "8px 22px 8px 16px"
    height: "60px"
  store-button-hover:
    backgroundColor: "{colors.card-2}"
  store-button-primary:
    backgroundColor: "{colors.green}"
    textColor: "{colors.green-ink}"
    rounded: "{rounded.md}"
    padding: "8px 22px 8px 16px"
    height: "60px"
  store-button-primary-hover:
    backgroundColor: "{colors.green-hover}"
  button-install:
    backgroundColor: "{colors.green}"
    textColor: "{colors.green-ink}"
    rounded: "{rounded.pill}"
    padding: "0 22px"
    height: "48px"
  button-install-hover:
    backgroundColor: "{colors.green-hover}"
  nav:
    backgroundColor: "{colors.ground}"
    textColor: "{colors.ink}"
    height: "{spacing.nav-h}"
  nav-link:
    textColor: "{colors.ink-dim}"
    rounded: "{rounded.pill}"
    padding: "8px 14px"
  nav-link-hover:
    backgroundColor: "{colors.card}"
    textColor: "{colors.ink}"
  lang-toggle:
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 14px"
    height: "44px"
  station-dot:
    backgroundColor: "{colors.ground}"
    rounded: "{rounded.pill}"
    size: "25px"
  station-dot-reached:
    backgroundColor: "{colors.green}"
  app-card:
    backgroundColor: "{colors.card}"
    textColor: "{colors.ink}"
    rounded: "{rounded.card}"
    padding: "24px"
    width: "400px"
  person-row:
    backgroundColor: "{colors.card-2}"
    rounded: "{rounded.md}"
    padding: "14px 16px"
  person-row-you:
    backgroundColor: "{colors.green-deep}"
  progress-track:
    backgroundColor: "{colors.ground}"
    rounded: "9px"
    height: "12px"
  progress-fill:
    backgroundColor: "{colors.green}"
  badge:
    backgroundColor: "{colors.card-2}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
    padding: "8px"
  badge-locked:
    textColor: "{colors.ink-faint}"
  odometer:
    backgroundColor: "{colors.card}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
    padding: "16px 20px"
  mobile-dock:
    backgroundColor: "{colors.card}"
    textColor: "{colors.ink}"
    rounded: "{rounded.dock}"
    padding: "10px 16px 10px 10px"
  statement:
    textColor: "{colors.ink-dim}"
    typography: "{typography.statement}"
    width: "38ch"
  faq-summary:
    textColor: "{colors.ink}"
    padding: "22px 4px"
---

# Design System: Namshy Landing

## Overview

**Creative North Star: "The Nile at Night"**

The landing page lives in the participant app's own night: a navy-black ground, slate cards with generous 24px corners, and a single vivid green that only ever means *you moved* or *get the app*. The page's spine is one traced route line, Cairo to Luxor along the Nile, drawn as the visitor scrolls. A step odometer counts along it from 0 to 1,000,000. Every other element is set at the side of that line: stations with a dot on the rail, app screens re-drawn as cards, and figures that grow as the route fills.

Density is low and the page reads as a journey, not a brochure. Each section opens with a plain display headline and nothing above it. Big figures carry the argument in Alexandria, and Readex Pro carries the explanation. Arabic RTL is the default and English is a toggle. Both directions are built from one layout with logical properties. Numbers stay in Western digits in both languages, to match the app's screens.

Depth comes from tone, not shadow. Surfaces step up from ground to card to card-2, hairline strokes (`line`, `line-2`) separate them, and there is no `box-shadow` anywhere in the build. The one glow in the world is the translucent green halo under the drawn route.

**Key Characteristics:**
- Navy-black ground with slate cards stepped up in tone; flat, with no shadows.
- One vivid green, spent on progress and on install.
- Amber only for rank, coral only for "ahead of you".
- Alexandria for display and figures, Readex Pro for text; tabular Western digits everywhere.
- A single traced route line (the Nile, Cairo to Luxor) is the page's spine, drawn by scroll.
- The layout is Arabic-first and built with logical properties. Arabic is never letterspaced.

## Colors

A night palette of blue-black and slate, with one electric green for progress and two warm signals held back for competition.

### Primary
- **Nile Signal Green** (`green`): Progress and install only. It fills the drawn route and its head, reached stations and the rail, today's day bar, the goal ring, person and challenge progress bars, the streak count, earned badge icons, the week's headline figures and the 1,000,000 finale. On the install side it fills the primary store button, the nav and dock "Get the app" pill, and the arrival link at Luxor. It also serves as the focus ring, selection and caret color, which are system states and not decoration.
- **Green Lift** (`green-hover`): Hover state of green fills only.
- **Green Ink** (`green-ink`): Text and glyphs set on a green fill. It is never plain white.
- **Deep Reed** (`green-deep`) with **Reed Edge** (`green-edge`): The quiet green register. It marks the "you" row, the app's Start button, the edges of earned badges, and past day bars. Past days use `green-edge` so that only today's bar is at full green.

### Secondary
- **Podium Amber** (`amber`): Rank, and nothing else. It colors the gold #1 rank numeral and the competition standing ("#3").

### Tertiary
- **Pace Coral** (`coral`): "Ahead of you". It colors the step gap in "Karim is ahead of you by 2,479 steps" and the rival's avatar initials (on a one-off `#3b2419` tint).

### Neutral
- **Night Ground** (`ground`): Page background, the nav at 94% opacity, progress tracks, and the station-dot interior.
- **Deeper Ground** (`ground-2`): The film frame's backing.
- **Slate Card** (`card`): App replicas, the odometer, the dock, store buttons at rest, and nav hover pills.
- **Raised Slate** (`card-2`): Rows and tiles inside a card (person rows, badges, the rankline, the streak pill) and store hover.
- **Hairline** (`line`) / **Strong Hairline** (`line-2`): Section dividers, card borders, button outlines, the dashed rail and unreached station rings.
- **Delta Land** (`land`) / **Night River** (`river`): Map layers only. `land` fills Egypt and `river` strokes the Nile, the lakes and the canal.
- **Moon Ink** (`ink`): Primary text and reached labels.
- **Dim Ink** (`ink-dim`): Secondary text, leads, the statement's resting voice, and nav links.
- **Faint Ink** (`ink-faint`): Captions, basis notes, legends, locked badges, and unreached station strokes.

### Named Rules
**The Spent Green Rule.** Green is spent only on progress (steps, route, rings, bars, reached stations, earned badges, the week's totals) and on install (store and "Get the app" actions). The only exceptions are system states (focus ring, selection, caret) and the temporary brand tile. If a green element is neither something that moved nor a way to get the app, it is wrong.

**The Podium Rule.** Amber is used only for rank. Coral is used only for "ahead of you". Neither appears on a surface, border or button.

## Typography

**Display Font:** Alexandria (with Readex Pro, system-ui)
**Body Font:** Readex Pro (with Alexandria, system-ui)

**Character:** Alexandria is an Egyptian geometric face with Arabic and Latin that match. It carries headlines and every figure, and its heavy weights make numbers read as trophies. Readex Pro is the calm, open text voice beside it. Both are loaded from Google Fonts: Alexandria at weights 500 to 800 and Readex Pro at 300 to 600.

### Hierarchy
- **Display** (800, clamp(2.4rem, 4.2vw, 4rem), 1.22): The hero h1 only. Inside the hero column it is container-sized (clamp(2.3rem, 9.6cqi, 3.9rem)). In English it tightens to -0.03em and 1.05.
- **Headline** (700, clamp(2rem, 3.6vw, 3.25rem), 1.25): Section h2s, with `text-wrap: balance`. In English it tightens to -0.02em and 1.1.
- **Title** (700, clamp(1.4rem, 2vw, 1.75rem), 1.35): Station h3s, each followed by a trailing faint tag giving the city and step count.
- **Statement / Bulletin** (Alexandria 500, clamp(1.35rem, 2.4vw, 2.1rem), 1.7): Display-face paragraphs that carry an argument. The bulletin is the same register at up to 2.3rem, with its figures in green 800.
- **Figure** (Alexandria 700–800, tabular, `direction: ltr`, isolated, no wrap): Every count. The odometer uses clamp(1.8rem, 2.6vw, 2.4rem). The finale's 1,000,000 uses clamp(3.6rem, 12vw, 10rem).
- **Body** (Readex Pro 400, 1.0625rem, 1.75; 1.6 in English): Station copy, capped at about 46ch, and FAQ answers, capped at about 60ch.
- **Lead** (Readex Pro 400, clamp(1.1rem, 1.5vw, 1.3rem)): The hero and finale subheads, capped at 36ch, in `ink-dim`.
- **Label** (Readex Pro 400, 0.8–0.95rem): Unit labels, captions, day names and legends, in `ink-dim` or `ink-faint`.

### Named Rules
**The Unletterspaced Arabic Rule.** Arabic is never letterspaced. Tracking appears only under `html[lang="en"]`, on the h1, h2 and bulletin, and on the Latin-digit finale figure. Arabic keeps its looser 1.7–1.75 line-height, and English tightens.

**The Western Digit Rule.** All figures use Western digits, comma-grouped and tabular, set LTR and bidi-isolated inside RTL text, matching the app screens.

## Layout

The page uses a single centered column capped at 1240px, with a fluid gutter of clamp(16px, 4vw, 48px). Sections are separated by a 1px `line` top border and padded clamp(72px, 9vw, 128px) top and bottom. The finale gets more room, up to 160px. Two-column grids use a column gap of clamp(32px, 5vw, 80px). The hero splits 1.08fr to 0.92fr between text and a square film. The FAQ splits 0.8fr to 1.2fr between its heading and the list.

The walk section is the spine. On desktop, a two-column grid pairs "This week" and the journey stations in one column with a sticky map of Egypt in the other. The map is pinned under the nav at a full viewport height minus the nav. Stations are spaced clamp(72px, 10vw, 120px) apart, so that scrolling between them reads as walking. At 960px and below, the grid stacks as week, then map, then journey. The map turns static and the odometer is removed, and the mobile dock takes over the running count. At 900px the nav links drop, and at 560px the nav install pill drops (the dock carries it) and the two store buttons sit in a 1fr 1fr grid.

Every inline offset is logical (`margin-inline`, `padding-inline-start`, `inset-inline-start`, `text-align: start`). Directional arrows mirror under `dir="rtl"`. The map SVG is pinned `direction: ltr`, because geography does not flip.

## Elevation & Depth

The build is flat, with tonal layering and no shadows. Depth is shown by stepping surfaces from `ground` to `card` to `card-2`, and a card can hold a raised row, but nothing floats on a drop shadow. Hairline borders carry separation: `line` on cards, sections and the film frame, and `line-2` on buttons, the dock and the dashed rail. The sticky nav sits on 94% ground and gains a `line` bottom border once the page scrolls. The only luminous effect is the route's glow, a 22px-wide green stroke at 0.18 opacity under the 7px route.

**The Tone-Not-Shadow Rule.** Surfaces lift by tone and hairline. Nothing in this world casts a shadow.

## Shapes

The form language is soft and app-like. Cards use 24px corners (`card`) and rows, tiles, store buttons and the odometer use 16px (`md`). Small tiles use 12px: the brand mark, day bars and the skip link. The dock uses 20px, and the film frame uses a larger 32px. Every action that is not a store button is a full pill (999px): the install button, nav links, the language toggle, the streak and the app's Start button. Dots are true circles, including station dots, walkers on the map, the live pulse and avatars. Line work has round caps and joins throughout: the route, the river, progress fills, and the stroked 24px SVG icons at a 1.8 stroke. Dashed strokes always mean "not yet": the unwalked rail, future day bars, the QR placeholder and the ghost route.

## Components

### Buttons
The buttons are confident and rounded, and green only when the button installs.
- **Store button (default):** A two-line lockup (small "Get it on" above the bold LTR store name) with a 28px store glyph. It is 60px tall, with `md` corners, a `card` fill and a `line-2` border. On hover it steps to `card-2` with an `ink-faint` border, and it presses to scale(0.97).
- **Store button (primary):** The same shape, filled `green` with `green-ink` text, and hovering to `green-hover`. The primary is chosen at runtime: the visitor's own store leads (Play by default, App Store on iOS), and only one store button is ever primary.
- **Install pill:** A 48px pill with a `green` fill, Alexandria 600 at 1rem, and hover to `green-hover`. It appears in the nav and the dock.
- **Focus:** Every interactive element gets a 2px `green` outline at a 3px offset with a 6px radius.

### Navigation
The nav is sticky and 72px tall, with the brand lockup (a green tile with the walker glyph, then the wordmark in Alexandria 700) at the start. Section links are `ink-dim` pills that turn `ink` on a `card` fill on hover. The end group holds a 44px outlined language pill with a globe glyph, and the install pill. The nav's bottom hairline appears only after scroll.

### Station on the rail
Each station is a list item on a vertical rail at the inline-start edge. The rail is a 2px dashed `line-2` track, and a 3px `green` fill grows down it following the reading line at 50% of the viewport. The station dot is a 25px circle with a `ground` fill and a 3px `line-2` ring, and it fills solid green when reached. The h3 is followed by a faint tag giving the city and the step count at that point. The city name turns green on arrival.

### App replica card
These are the participant app's own screens, redrawn in CSS rather than shown in a phone mockup. The card has a `card` fill, `card` corners, a `line` border, 24px padding and a maximum width of 400px, and it is `aria-hidden`.
- **Person row:** A `card-2` row at `md` corners with a 40px round avatar, the name in Alexandria 600, a 5px progress bar on `ground`, and the step count in Alexandria 700. The "you" row switches to `green-deep` with a `green-edge` border. A team row leads with a rank numeral, `ink-dim` by default and `amber` for #1.
- **Ring:** A 200px goal ring with two tracks and a green arc, holding the count and a "of 10,000" label.
- **Progress bar:** A 12px track on `ground` with a green fill at 9px radius, and the percentage right-aligned beneath it.
- **Badge:** A `card-2` tile at 0.92 aspect with a 30px glyph and a label. Earned badges have a `green-edge` border and a green glyph, and locked badges fade to `ink-faint` with no border.

### Map layers
The map is stacked from the bottom up: `land` fill with a 2px `line-2` coast, the `river` Nile at 4px (lakes at 11px, the canal dashed), twinkling green walker dots at 0.5 opacity, the dotted `ink-faint` ghost route, the green route glow, the 7px green route, and the 11px green head. Station circles are hollow `ink-faint` rings that fill green when reached, and their labels are Alexandria 600. The map has two states. In the week state, walker dots twinkle and a legend explains them. In the journey state, walkers dim to 0.16 and the route, stations and odometer take over.

### Odometer
A `card` strip at `md` corners with 16px/20px padding. At the start is a two-line label ("Steps so far" over the current city), and at the end is the count in Alexandria 800, running from 0 to 1,000,000 at Luxor. It is shown only in the journey state on desktop.

### Mobile dock
A fixed bar at 12px from the viewport edges on screens up to 960px, with a `card` fill, `dock` corners and a `line-2` border. It slides up once the hero has passed and hides at the finale. The dock holds a label, a figure and the install pill. During the journey it swaps to the walk's own count and shows a 34×52 mini route: a `line-2` track, a green walked segment, and a green dot outlined in `card`.

### Statement paragraph
A display-face paragraph in Alexandria 500 at up to 2.1rem, capped at 38ch, resting in `ink-dim`. Its key phrases step up to `ink` at weight 700 through non-italic `em`. It states commitments as sentences, not a grid of icon cards.

### FAQ disclosure
Native `details` elements between `line` hairlines. The summary is Alexandria 600 at 1.15rem, with a plus glyph at the end that rotates 45° when open (240ms, ease-out). Answers are `ink-dim` and capped at 60ch.

### Motion
Motion adds to content that is already visible. Reveal (`.rise`) hides content only when JS has loaded and `prefers-reduced-motion: no-preference`. It then rises 24px over 700–900ms on `cubic-bezier(0.16, 1, 0.3, 1)`. Under reduced motion, smooth scroll, the live pulse, walker twinkle, the live ticker and the finale count-up are all disabled, and the film starts paused. The route, rail, odometer and dock stay scroll-linked, because they are position, not animation.

## Do's and Don'ts

### Do:
- **Do** spend `green` only on progress and install, with `green-ink` text on every green fill.
- **Do** reserve `amber` for rank and `coral` for "ahead of you".
- **Do** give every figure its label: a unit or caption ("steps", "people", "of 10,000", "Steps so far · Cairo"). Mark any sample or illustrative figure as such, next to the figure.
- **Do** set figures in Alexandria with tabular Western digits, LTR and bidi-isolated.
- **Do** lay out with logical properties, and mirror directional glyphs under RTL.
- **Do** lift surfaces by tone (`ground` to `card` to `card-2`) and separate them with `line` / `line-2` hairlines.
- **Do** keep content visible without JS, and let motion only add to it. Honor `prefers-reduced-motion`.
- **Do** show the app by redrawing its screens as cards (rings, rows, bars, badges).

### Don't:
- **Don't** put a kicker or eyebrow line above a heading. Headings open their sections directly.
- **Don't** letterspace Arabic. Tracking belongs to `html[lang="en"]` headings and the Latin-digit finale figure only.
- **Don't** use `box-shadow` for depth.
- **Don't** use green for links, headline accents or hover states that are neither progress nor install.
- **Don't** use Arabic-Indic digits in figures.
