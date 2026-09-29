---
name: Namshi Landing v2
description: The cinema poster. A golden-age Egyptian film programme for a walking app, Arabic first.
colors:
  projection-black: "#120d0b"
  projection-black-raised: "#1c1512"
  sprocket-brown: "#2a201b"
  strip-base: "#070504"
  frame-rule: "#4a3d35"
  bone: "#f1e6d2"
  bone-dim: "#bdb2a0"
  bone-faint: "#9d9282"
  poster-vermilion: "#d8362b"
  saffron: "#f2a93b"
  saffron-lit: "#ffc164"
  paper-ink: "#1c1411"
  paper-dim: "#5a4c42"
  programme-red: "#a8241b"
  paper-rule: "#cdbfa7"
typography:
  display:
    fontFamily: "Rakkas, 'Noto Naskh Arabic', serif"
    fontSize: "clamp(3rem, 8.4vw, 7.4rem)"
    fontWeight: 400
    lineHeight: 1.12
  display-latin:
    fontFamily: "Rakkas, 'Noto Naskh Arabic', serif"
    fontSize: "clamp(2.6rem, 6.6vw, 6rem)"
    fontWeight: 400
    lineHeight: 1.02
  display-finale:
    fontFamily: "Rakkas, 'Noto Naskh Arabic', serif"
    fontSize: "clamp(3.4rem, 11vw, 9rem)"
    fontWeight: 400
    lineHeight: 1.05
  headline:
    fontFamily: "Rakkas, 'Noto Naskh Arabic', serif"
    fontSize: "clamp(2.4rem, 5vw, 4.4rem)"
    fontWeight: 400
    lineHeight: 1.15
  title:
    fontFamily: "Rakkas, 'Noto Naskh Arabic', serif"
    fontSize: "clamp(1.6rem, 2.4vw, 2.1rem)"
    fontWeight: 400
    lineHeight: 1.2
  body:
    fontFamily: "'Noto Naskh Arabic', 'Source Serif 4', serif"
    fontSize: "1.125rem"
    fontWeight: 400
    lineHeight: 1.8
  body-latin:
    fontFamily: "'Source Serif 4', 'Noto Naskh Arabic', serif"
    fontSize: "1.125rem"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "'Noto Naskh Arabic', 'Source Serif 4', serif"
    fontSize: "0.98rem"
    fontWeight: 700
    lineHeight: 1.2
  edge-print:
    fontFamily: "'Source Serif 4', serif"
    fontSize: "0.78rem"
    fontWeight: 700
    lineHeight: 1
    letterSpacing: "0.18em"
  figure:
    fontFamily: "'Source Serif 4', serif"
    fontSize: "1.1rem"
    fontWeight: 600
    lineHeight: 1.5
    fontFeature: "tnum"
rounded:
  slot: "3px"
  frame: "4px"
  control: "6px"
spacing:
  gutter: "clamp(16px, 4vw, 56px)"
  section: "clamp(72px, 9vw, 128px)"
  container: "1280px"
  control-gap: "12px"
components:
  button-primary:
    backgroundColor: "{colors.saffron}"
    textColor: "{colors.projection-black}"
    rounded: "{rounded.control}"
    padding: "0 18px"
    height: "44px"
    typography: "{typography.label}"
  button-primary-hover:
    backgroundColor: "{colors.saffron-lit}"
    textColor: "{colors.projection-black}"
  button-line:
    backgroundColor: "rgba(18, 13, 11, 0.4)"
    textColor: "{colors.bone}"
    rounded: "{rounded.control}"
    padding: "0 18px"
    height: "44px"
    typography: "{typography.label}"
  button-line-hover:
    backgroundColor: "{colors.bone}"
    textColor: "{colors.projection-black}"
  store-badge:
    backgroundColor: "rgba(18, 13, 11, 0.55)"
    textColor: "{colors.bone}"
    rounded: "{rounded.control}"
    padding: "8px 22px 8px 16px"
    height: "60px"
  store-badge-primary:
    backgroundColor: "{colors.saffron}"
    textColor: "{colors.projection-black}"
    rounded: "{rounded.control}"
    padding: "8px 22px 8px 16px"
    height: "60px"
  letterboard-slot:
    backgroundColor: "{colors.projection-black-raised}"
    textColor: "{colors.bone}"
    rounded: "{rounded.slot}"
    width: "1.02em"
    height: "1.4em"
  letterboard-slot-paper:
    backgroundColor: "{colors.paper-ink}"
    textColor: "{colors.bone}"
    rounded: "{rounded.slot}"
    width: "1.02em"
    height: "1.4em"
  ticket:
    backgroundColor: "{colors.bone}"
    textColor: "{colors.paper-ink}"
    rounded: "{rounded.control}"
    padding: "14px 18px"
---

# Design System: Namshi Landing v2

## Overview

**Creative North Star: "The Picture Palace Programme"**

The surface is a golden-age Egyptian cinema poster and its printed programme. A full-bleed, graded live-action film opens the page; the line is set over it as the hand-lettered title; the week's figures play the cast and the box office; the app's features run past as scenes on a sprocketed strip. Everything reads as projected light on a warm black room, or as ink on a bone programme sheet handed out at the door. There are exactly two grounds, the projection room and the paper, and the page moves between them like turning from the screen to the programme in your hand.

Density is theatrical, not dashboard: one big title per view, generous bands of dark, figures presented as event rather than data. Arabic is the default reading direction and the default voice; English is a full mirror, not a translation layer. Material comes from print and film stock (grain and dust, gate weave in the film, double-rule frames, sprocket holes, dotted leaders, a torn-stub ticket), never from glass or gradients-as-decoration.

The film and the page are one world. The film (Remotion source) shares the palette, the Rakkas title with its vermilion shade, the letter-spaced title card, and the warm print grade (sepia, lifted blacks, vignette, weave, flicker). The page's hero is a text-free plate of that film with all type set in HTML over it.

**Key Characteristics:**
- Two grounds only: warm projection-room black and bone programme paper.
- Rakkas display in both scripts with an opaque vermilion spot-colour shade on the biggest titles.
- Figures on a marquee letterboard, one fixed slot per character, Western digits.
- Grain on every surface, tuned per ground so neither ground's mean shifts.
- Saffron is the only action colour.
- The scene strip is the signature: real app screens on sprocketed film, run by scroll.

## Colors

A four-colour poster palette (warm black, bone, vermilion, saffron) with a small set of tints derived for legibility on each ground.

### Primary
- **Saffron** (#f2a93b): the action and arrival colour. Fills the primary store badge and the nav call to action, colours the second line of the hero title, the finale's sub-line, edge print, the strip progress bar, focus rings and selection. **Saffron Lit** (#ffc164) is its hover only.

### Secondary
- **Poster Vermilion** (#d8362b): the spot-colour shade behind display titles on the dark ground. It is a printing ink, not a surface or text colour on dark.
- **Programme Red** (#a8241b): vermilion deepened for text on paper: the emphasised word in the week heading, the cast figures, today's row in the screening schedule, and the focus ring inside the paper section.

### Neutral
- **Projection Black** (#120d0b): the room. Page background, text on saffron and on bone hover fills, the tint for all scrims and translucent control grounds.
- **Projection Black Raised** (#1c1512): letterboard slots on the dark ground.
- **Sprocket Brown** (#2a201b) on **Strip Base** (#070504): the film strip's sprocket holes and its stock.
- **Frame Rule** (#4a3d35): hairline section dividers, FAQ row rules, letterboard slot borders, the idle progress track, the scrollbar thumb.
- **Bone** (#f1e6d2): primary text on dark and, as a ground, the programme paper sheet and the ticket.
- **Bone Dim** (#bdb2a0): secondary copy on dark (scene captions, subtitles, answers).
- **Bone Faint** (#9d9282): tertiary notes on dark (footer, "sample figures" tags, scene notes).
- **Paper Ink** (#1c1411), **Paper Dim** (#5a4c42), **Paper Rule** (#cdbfa7): text, secondary text and rules on the paper sheet.

### Named Rules
**The Saffron Acts Rule.** Saffron is the only filled action colour. Vermilion is never a button fill or a large fill of any kind: bone on vermilion is 3.79:1 and fails small text.

**The Spot Ink Rule.** Vermilion appears in exactly two ways: as the opaque offset shade behind display titles on dark, and (as Programme Red) as the red text on paper. Nowhere else.

**The Two Grounds Rule.** Every section is either projection black or bone paper. No third surface colour, no mid-grey panels, no coloured section bands.

## Typography

**Display Font:** Rakkas (with Noto Naskh Arabic, serif)
**Body Font:** Noto Naskh Arabic in Arabic, Source Serif 4 in English (each falls back to the other)
**Label/Mono Font:** Source Serif 4 bold for edge print and tabular figures

**Character:** Rakkas is the hand-lettered poster title, heavy and brushy in both scripts; Naskh and Source Serif are the programme's book text, calm and literary against it.

### Hierarchy
- **Display** (400, clamp(3rem, 8.4vw, 7.4rem), 1.12): the hero title over the film, two lines, the second in saffron. English uses **Display Latin** (clamp(2.6rem, 6.6vw, 6rem), 1.02).
- **Display Finale** (400, clamp(3.4rem, 11vw, 9rem), 1.05): the closing "Now showing" title, with a smaller saffron line beneath.
- **Headline** (400, clamp(2.4rem, 5vw, 4.4rem), 1.15): section titles (the week, the scenes); FAQ and the privacy card step down (to 3.8rem and 3.3rem maxima).
- **Title** (400, clamp(1.6rem, 2.4vw, 2.1rem), 1.2; up to 2.6rem when the strip is scroll-driven): scene titles and the programme's schedule head.
- **Body** (400, 1.125rem, 1.8 Arabic / 1.6 English): all running copy, capped at 48ch for leads and 60ch for answers.
- **Label** (700, ~0.95-0.98rem): button and control text.
- **Edge Print** (Source Serif 4 700, 0.78rem, 0.18em tracking, saffron): the "NAMSHI · 0N" print on the strip's margin.
- **Figure** (Source Serif 4 600, tabular): schedule values; inline figures elsewhere are isolated LTR and never wrap.

### Named Rules
**The Open Spaces Rule.** Rakkas collapses Arabic word spaces at display size. Arabic display titles set word-spacing 0.22em, Arabic headlines 0.06em, and film titles 0.28em. Latin display text gets none.

**The Western Digits Rule.** All figures use Western digits, set left to right in an isolated run inside Arabic text, with tabular spacing wherever they update.

**The Shade Is Ink Rule.** The display shade is an opaque vermilion offset, 3px 2px on the hero title and 4px 3px on the finale (film: 3u 2u), with zero blur. It is a second printed colour slightly out of register, never a translucent or blurred shadow, and it only goes on Rakkas display titles on the dark ground.

## Layout

A single centred column, 1280px max, with a fluid gutter (clamp(16px, 4vw, 56px)). Sections breathe with a fluid block padding of clamp(72px, 9vw, 128px) (the finale opens further, to 150px) and are divided by a single Frame Rule hairline on dark.

The hero is a full-viewport (100svh) film with content anchored to the bottom: title, subtitle in the other script, store badges, "now showing" line and credit on one side; the letterboard reel and film controls on the other. It stacks to one column under 860px. The week section is a two-column programme page (1.1fr / 0.9fr) that stacks under 900px; FAQ is a 0.8fr / 1.2fr split that stacks under 860px. Nav links drop under 900px, the nav call to action under 560px, and the ticket under 760px.

**The Scroll Runs The Film Rule.** At 900px and wider, with motion allowed, the scene strip pins to the viewport and vertical scroll drives it horizontally (rail height = viewport + strip travel), in reading direction. Below 900px or with reduced motion it is a native horizontal swipe with mandatory snap. Content never depends on the scroll-driven mode.

## Elevation & Depth

Flat. There are no box shadows anywhere. Depth comes from the film itself, from scrims (a bottom-weighted Projection Black gradient under the hero type, 0.96 at the foot to 0.1 mid-frame), from translucent black control grounds over footage (0.4-0.55 alpha), and from grain.

**The Grain Per Ground Rule.** Dark fields carry sparse bone dust as a fixed full-page layer at normal blend (opacity 0.14), kept sparse enough that the black's mean stays within about two levels of #120d0b. The paper sheet carries desaturated grain through soft-light (opacity 0.3), so its mean stays #f1e6d2. Never tint a ground by adding grain.

**The Scrim Not Burn Rule.** Type over footage reads because of a scrim, never because text was burned into the video. The hero plate is text-free.

## Shapes

Printed and cut, not moulded. Corners are barely softened: 3px on letterboard slots, 4px on screen stills and small hit areas, 6px on buttons, badges, the ticket and the theatre dialog. Nothing is pill-shaped except the scrollbar thumb.

The recurring frame is the **double rule** from printed programmes: a 1.5px outer rule top and bottom with a 1px inner rule 3px inside at 55% strength, in the current text colour. It frames the "now showing" line, the programme's schedule head and the privacy card. Other print devices: dotted leaders between a day and its figure, a dashed tear line on the ticket stub, sprocket holes along the strip's top and bottom edges.

## Components

### Buttons
Direct and printed: solid saffron for the one action, bone outline for everything else.
- **Shape:** gently squared (6px).
- **Primary:** saffron fill, projection black text, bold, 44px minimum height, 0 18px padding. Hover lifts to Saffron Lit.
- **Line (secondary):** 1.5px bone border over translucent black; hover fills bone with black text. Used for the language switch, film controls and the dialog close.
- **Focus:** 2px saffron outline, 3px offset (Programme Red inside the paper section).
- **Motion:** colour transitions at 160ms; store badges press to scale 0.97.

### Store Badges
Paired store buttons, 60px tall, glyph plus a two-line label (small Arabic or English prefix, bold Latin store name). The visitor's own platform becomes the saffron primary and leads the pair; the other stays a bone-line badge. Under 860px the pair becomes an equal two-column grid.

### Navigation
Absolute over the hero film, 84px tall: temporary mark (bone roundel with a walking figure plus the Rakkas wordmark), three section links in bone with a soft legibility halo and underline on hover, then the language switch and the saffron call to action.

### Letterboard
The marquee board for live figures. Every character sits in its own fixed slot (1.02em by 1.4em, 3px corners) so a changing number never reflows; separators take a narrow empty slot. On dark: raised black slots with Frame Rule borders. On paper: paper-ink slots with bone figures. Rakkas, always LTR.

### Programme Schedule
The week's screenings as a printed list: day name, dotted leader, tabular figure. Today's row goes Programme Red and reads "showing"; later days go Paper Dim and read "not yet".

### Scene Strip (signature)
A sprocketed strip of real app screens on Strip Base stock, each frame a still (9:13, or 9:16 when scroll-driven, 4px corners, a light sepia 0.12 grade) beside its Rakkas title and caption. The scene number is edge print on the film's own margin ("NAMSHI · 01"), in saffron. A footer shows "n / 6" in Rakkas and a saffron progress bar on a Frame Rule track.

### Ticket
An admit-one stub in bone with paper-ink text, a Rakkas line, and a dashed tear between stub and QR panel. Decorative; hidden under 760px.

### Theatre Dialog
The full film with sound opens in a modal on pure black with a 0.9 warm-black backdrop and a bone-line close button; the hero plate pauses while it plays.

### Motion
One easing, cubic-bezier(0.16, 1, 0.3, 1). Section content rises 22px and fades in once (800-1000ms). The hero title stamps in line by line from scale 1.06 (900ms, second line 220ms later). Everything is visible by default and all motion is gated on prefers-reduced-motion; the letterboard stops ticking under reduced motion.

## Do's and Don'ts

### Do:
- **Do** keep every section on one of two grounds: projection black (#120d0b) or bone paper (#f1e6d2).
- **Do** use saffron (#f2a93b) as the only action fill, with projection black text.
- **Do** set Arabic display type in Rakkas with word-spacing opened (0.22em display, 0.06em headline, 0.28em film titles).
- **Do** give display titles on dark an opaque vermilion offset shade with zero blur.
- **Do** put live figures on the letterboard, one fixed slot per character, Western digits, LTR.
- **Do** carry numbering as edge print on the film margin ("NAMSHI · 0N").
- **Do** keep the hero film free of text and set all type in HTML over a bottom scrim.
- **Do** frame programme elements with the double rule rather than boxes.

### Don't:
- **Don't** fill a button or any large area with vermilion; bone on vermilion fails small-text contrast.
- **Don't** use vermilion (#d8362b) as text on paper; use Programme Red (#a8241b).
- **Don't** make the display shade translucent, blurred, or apply it to boxes.
- **Don't** put kickers or eyebrow labels above headings.
- **Don't** burn titles into the hero plate.
- **Don't** add grain that shifts a ground's mean colour: bone dust at normal blend on dark, grey grain through soft-light on paper.
- **Don't** add box shadows or glass effects; depth comes from film, scrim and grain.
