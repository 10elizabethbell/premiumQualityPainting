---
name: Premium Quality Painting
description: Monmouth County cabinets, beautifully repainted. A calm navy-and-paper one-pager with one flyer gold, for a cabinet painter.
colors:
  gold: "#e4b95c"
  gold-2: "#efca7a"
  gold-ink: "#7a5812"
  ink: "#0f1d38"
  deep: "#0f1d38"
  navy: "#1c3157"
  paper: "#f4f6fb"
  light: "#e9eef6"
  card: "#ffffff"
  field: "#e6ecf5"
  body: "#26324a"
  soft: "#4b5872"
  on-dark: "#f4f7fb"
  on-dark-soft: "#c9d3e6"
  line: "rgba(15,29,56,.12)"
  focus: "#1f5fbf"
  error: "#b3261e"
typography:
  display:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(40px, 11.4vw, 80px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.005em"
  headline:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 7.6vw, 48px)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.005em"
  title:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(20px, 5.4vw, 26px)"
    fontWeight: 400
    lineHeight: 1.15
  title-sm:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1.2
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 19px)"
    fontWeight: 400
    lineHeight: 1.7
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.7
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "13px"
    fontWeight: 600
    lineHeight: 1
    letterSpacing: "0.03em"
  small:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.4
rounded:
  tag: "6px"
  field: "10px"
  thumb: "16px"
  card: "24px"
  pill: "999px"
spacing:
  gutter-mobile: "20px"
  gutter-desktop: "40px"
  section-mobile: "64px"
  section-desktop: "96px"
  stack: "16px"
  form-gap: "22px"
  column-gap: "64px"
  container: "1160px"
components:
  button-primary:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.ink}"
    typography: "{typography.title-sm}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.gold-2}"
    textColor: "{colors.ink}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-soft:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 14px"
    height: "56px"
  input-text:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "13px 14px"
    height: "52px"
  chip:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.card}"
  form-card:
    backgroundColor: "{colors.card}"
    rounded: "{rounded.card}"
    padding: "clamp(20px, 5vw, 32px)"
  link-banner:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.card}"
    padding: "16px 16px 16px 22px"
    height: "80px"
  photo-tag:
    backgroundColor: "rgba(15,29,56,.74)"
    textColor: "{colors.card}"
    typography: "{typography.label}"
    rounded: "{rounded.tag}"
    padding: "7px 10px"
  swap-thumb:
    backgroundColor: "{colors.field}"
    rounded: "{rounded.thumb}"
    width: "32%"
  swap-thumb-label:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.ink}"
    padding: "7px 6px"
  arrow-disc:
    backgroundColor: "rgba(255,255,255,.1)"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.pill}"
    size: "44px"
  arrow-disc-hover:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.ink}"
  step-disc:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: "48px"
  float-circle:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: "60px"
---

# Design System: Premium Quality Painting

## Overview

**Creative North Star: "Gold Lettering on a Navy Door"**

The system is the client's flyer translated into Ellie's calm band style: their gold lettering colour set against navy rather than the flyer's black (navy is the wall colour in their own job photos), laid out as full-bleed horizontal bands of off-white paper, a pale blue-grey band, a mid navy band and a deep navy band with a faint diagonal line texture. Each band holds one idea, set in Cal Sans headings over a plain system body. One warm flyer gold does all the pointing: it fills the primary button, the arrow discs on hover, the step numbers, the before/after thumbnail label and the floating text circle, and it never covers a large surface. The craft is carried by the client's own photographs: the hero is their finished deep-green room under a navy wash, and the work band shows wood-to-green transformations you flip with a tap.

Density is low and phone-first. Content stacks in a single 20px-gutter column with 64px band padding and splits into two columns at 760px and two or three at 1024px. Forms are soft: a white 24px card, pill buttons, pill chips, 10px fields filled rather than outlined. Motion is short: the hero headline's letters bounce in once, blocks below the first screen rise 12px as they arrive, the floating circle slides up after the hero, and before/after photos cross-fade on swap. All of it switches off under reduced motion.

**Key Characteristics:**
- Full-bleed colour bands alternating light (paper, light band) and dark (navy, deep navy); no borders between them.
- One gold accent, used as a fill; gold as text only on dark grounds, and in its darkened ink form on light ground.
- Cal Sans at weight 400 for every heading, label, button, row and phone number; system sans for running text.
- Pills, circles and 24px cards; no sharp corners on interactive elements.
- Flat surfaces; the only shadows sit under elements that float over content (the floating circle and the before/after thumbnail).
- A distinct focus blue for keyboard and form-hover states, kept apart from the gold fill.

## Colors

A cool navy-and-paper palette with a single warm flyer gold.

### Primary
- **Flyer Gold** (gold): the action colour, sampled from the client's flyer lettering. Fills the primary button, arrow discs on hover and focus, numbered step discs, the before/after thumbnail label, the floating text circle, the text selection and the gold logo in the close band. On dark grounds it is also the accent phrase in headings and the phone and Facebook icons. Text on it is always Ink Navy.
- **Pale Gold** (gold-2): hover fill of the primary button only.
- **Gold Ink** (gold-ink): gold darkened to about 5.6:1 on paper, for gold used as text or line icons on light ground (the header phone icon and its hover, the care-claim icons).

### Neutral
- **Ink Navy** (ink): every heading and input text on light ground, text on gold, the selected chip fill and the Facebook link banner.
- **Deep Navy** (deep): same value as Ink Navy, used as a surface: the hero base, the "how it works" band and the footer, both of the latter with the diagonal line texture. The hero photo wash is this navy at 72 to 90%.
- **Mid Navy** (navy): the services and close bands; also the text caret in fields and the hover colour of the fallback phone link.
- **Paper** (paper): page ground, header, care and form bands; also the browser theme colour.
- **Light Band** (light): the work band, one step cooler and darker than paper.
- **White Card** (card): the form card surface; white also carries text on photo tags, the selected chip and the hero H1.
- **Field Blue** (field): input, chip and soft-button fill on the white card; also the placeholder behind loading photos.
- **Body Slate** (body): running text on light bands.
- **Soft Slate** (soft): ledes, hints, placeholders and helper text on light bands.
- **Mist** (on-dark): headings, step titles, row text and links on navy bands.
- **Soft Mist** (on-dark-soft): running text on navy bands.
- **Hairline** (line): 1px dividers between care claims on light ground; on navy the equivalent is white at 14%.
- **Focus Blue** (focus): focus outlines, field and chip borders on focus and hover, and the hover outline on form buttons. On navy bands, the hero and the footer, focus outlines switch to gold.
- **Error Red** (error): the invalid field border and its message.

### Named Rules
**The Gold Is a Fill Rule.** Gold appears as a fill on small elements (buttons, discs, the thumbnail label, the floating circle), never as a band, card or large background, and never as text on light ground; for that use Gold Ink.

**The Two Signals Rule.** Gold means "act here"; Focus Blue means "you are here". Keyboard focus and form hover use Focus Blue on light ground so a focused gold button stays readable.

**The Dark-Band Accent Rule.** A heading's last phrase may take the gold accent ("beautifully repainted.", "What we *paint.*", "How it *works.*") only on dark grounds: the hero, navy and deep navy bands. Headings on light bands stay all Ink Navy.

## Typography

**Display Font:** Cal Sans (with Avenir Next, Segoe UI, system-ui)
**Body Font:** the system sans stack (-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial)

**Character:** Cal Sans gives the headings a round, friendly geometric weight; the system body keeps running text fast in the Facebook in-app browser, where most visitors arrive. Cal Sans is only ever set at 400 and also carries the "spoken" UI: buttons, field labels and legends, service rows, care claims, the phone numbers.

### Hierarchy
- **Display** (400, clamp 40 to 80px, 1.02): the hero H1 only, in white with the last phrase in gold, max 11ch on phone and 14ch from 760px.
- **Headline** (400, clamp 30 to 48px, 1.08): section H2s, balanced wrapping.
- **Title** (400, clamp 20 to 26px, 1.15): service rows (up to 26px) and care claims (up to 24px); the Facebook banner (19 to 22px) and step titles (21px) sit at its low end. The close band's phone number is the one oversize exception (clamp 30 to 52px).
- **Title small** (400, 18px, 1.2): buttons, field labels and legends; the header phone sits at 17px (20px from 760px) and soft buttons at 17px.
- **Lede** (system, clamp 17 to 19px): section introductions, max 40ch, in Soft Slate (Soft Mist on navy). The hero promise is the same role at 17 to 20px, line height 1.5, max 32ch (40ch from 760px), in Mist.
- **Body** (system, 16px, 1.7): running text and field input text (16px keeps iOS from zooming).
- **Small** (system, 14px): the "(optional)" notes, the "opens your messages" note and error text; the green-colour hint sits at 15px.
- **Label** (system, 600, 13px, +0.03em): the Before / After photo tag.

### Named Rules
**The One Weight Rule.** Cal Sans is set at 400 everywhere; emphasis comes from size and colour, not boldness.

## Layout

A single centred container (max 1160px) with a 20px gutter on phone and 40px from 760px. Every section is a full-bleed band with 64px vertical padding, 96px from 760px. Section heads are a left-aligned stack (16px gap, max 640px). Content is left-aligned throughout; nothing is centred.

Band order: paper header, photo hero, paper (care), navy (services), light (work), deep navy (how it works), paper (form), navy (close), deep navy footer.

Breakpoints: below 380px chips tighten their side padding to 14px. From 760px the gutter widens, the header grows to 88px with a 180px logo, the hero buttons sit in a row (min 240px each), services become two columns (48px gap), and the work band becomes a two-column grid (24px gap, max 880px) with the Facebook banner at half width beneath. From 1024px the care and form bands split into two columns (64px gap; the form band 1fr / 1.2fr with a sticky heading), services become three columns, the three steps sit in a row (40px gap), the close band puts the big phone number bottom right, and the hero wash turns from an even vertical wash into a left-to-right fade so the green room shows beside the copy.

The header is a plain paper bar (76px, 88px from 760px) with the navy logo left and the tap-to-call number right; it is not sticky. The footer leaves 96px plus the safe area at the bottom so the floating circle never covers its links.

**The Phone-First Rule.** Design every band as a single column first; add columns only at 760px and 1024px.

**The Photo Shows Through Rule.** On wide screens the hero wash fades from 90% navy behind the copy to 30% at the far edge; on phones it stays even (72 to 90%) because the copy covers the whole photo.

## Elevation & Depth

Flat by default. Depth comes from the band sequence and from photography under a navy wash, not from shadows. Cards and banners sit on bands as flat colour. Exactly two elements cast shadows, both of which float over other content.

### Shadow Vocabulary
- **Thumb lift** (`box-shadow: 0 4px 12px rgba(0,0,0,.22)`): the before/after thumbnail tucked into the corner of each photo, so it reads as a separate picture on top; it also lifts 2px on hover.
- **Float lift** (`box-shadow: 0 10px 28px rgba(0,0,0,.28)`): the fixed floating text circle.

### Named Rules
**The Only Floaters Cast Shadows Rule.** A shadow means the element floats over other content. Cards, buttons, chips, banners and bands stay flat.

## Shapes

Soft and round. Large containers use 24px corners (the form card, before/after photos, the Facebook banner). The before/after thumbnail uses 16px with a 3px white frame. Fields use 10px; photo tags 6px. Every button and chip is a full pill, and every icon holder (arrow discs, step numbers, the floating circle, colour swatches in chips) is a perfect circle. Borders are rare: 1px hairlines separate care claims and service rows, and 2px transparent borders on buttons, chips and fields exist so hover and focus can colour them without shifting layout. Line icons are drawn at a 2.2 to 2.6 stroke with round caps and joins. The deep bands carry a faint 135-degree line texture (1px white at 3.5% every 23px), the one surface pattern in the system.

## Components

### Buttons
- **Primary:** Flyer Gold pill, Ink Navy Cal Sans 18px, 56px tall, 26px side padding, optional 20px leading icon. Hover to Pale Gold; press scales to 0.98 over 0.12s. Full width inside the form, where hover adds a Focus Blue outline.
- **Ghost:** transparent pill with a 2px border of Mist at 70%, on dark grounds only (the hero). Hover brings the border to full white and a 10% white wash.
- **Soft:** Field Blue fill, Ink Navy text, 17px, 14px side padding; the paired fallback actions (Open in Messages, Copy message) after the form is sent. Hover shows the Focus Blue outline.
- **Focus:** 3px outline, 3px offset; Focus Blue on light, gold on dark.

### Chips
- **Style:** pill, 48px tall, Field Blue fill, system 16px Ink Navy text, wrapping row with 10px gaps. They are visually hidden checkboxes or radios with styled labels.
- **Colour chips** carry a 20px paint swatch circle before the label, ringed by a 1.5px inset line (navy at 25%, white at 60% when selected). The swatch colours are content (the client's three paint colours), not palette tokens.
- **State:** selected turns Ink Navy with white text; hover shows a Focus Blue border; keyboard focus a Focus Blue outline.

### Cards / Containers
- **Form card:** White Card on Paper, 24px corners, padding 20 to 32px, 22px gap between fields, max 600px.
- **Link banner:** Ink Navy block, 24px corners, min 80px tall, Cal Sans text with a 30px gold icon left and an arrow disc right. Only the disc changes on hover or focus.
- **Shadow strategy:** none (see Elevation & Depth).

### Inputs / Fields
- **Style:** Field Blue fill, 2px transparent border, 10px corners, min 52px tall (textareas 120px, vertical resize), system 16px Ink Navy text, Soft Slate placeholder, Cal Sans 18px label above with an optional 14px "(optional)" note.
- **Focus / hover:** border turns Focus Blue; no glow.
- **Error:** border and a 14px message in Error Red, cleared as soon as the field has a value.

### Navigation
There is no nav menu. The header holds the logo and a tap-to-call number (Cal Sans, Gold Ink phone icon, hover to Gold Ink). Footer links are 44px-tall Mist text that turns gold on hover.

### Link Rows
Services are a list of full-width links on a navy band: Cal Sans 20 to 26px, min 76px tall, separated by 14% white hairlines, each ending in a 44px arrow disc. The row itself never changes; only the disc turns gold on hover or focus. Tapping a row pre-ticks the matching chip in the form.

### Before/After Swap
The signature component, used where the before and after are not shot from the same spot (so no drag slider). A 24px-cornered photo shows the "after" with a navy "After" tag top left; the "before" sits as a framed thumbnail (32% wide, 16px corners, 3px white border, thumb lift shadow) in the bottom-left corner with a gold Cal Sans "Before" label and swap icon along its foot. Tapping the thumbnail or the big photo cross-fades the two (0.35s ease-out) and swaps the tag, label and thumbnail. The thumbnail presses to 0.97 and lifts 2px on hover.

### Numbered Steps
An ordered list where each item has a 48px gold circle with its Cal Sans 20px number, a Cal Sans 21px title in Mist and a body line. One column on phone (24px gap), three from 1024px.

### Floating Text Circle
A single 60px gold circle fixed 16px from the bottom-right safe area, holding a chat icon that opens a pre-written text. It slides up 120px into view (0.35s, cubic-bezier(.2,.8,.2,1)) once the hero has scrolled away, and steps aside while the form is on screen or while a row arrow or the banner arrow is in the bottom strip it covers. It is removed from the tab order while hidden.

### Motion
- **Letter bounce-in:** the hero H1 only. Each letter slides in from 50px right and fades in over 1s with a slight overshoot (cubic-bezier(.34,1.56,.64,1)), 20ms apart; afterwards the plain heading is restored so kerning and selection return. Runs only with JavaScript and without reduced motion.
- **Rise:** blocks that start below the first screen fade up 12px over 0.4s ease-out when they enter view. Anything visible at load never animates.
- **Swap fade:** before/after photos cross-fade over 0.35s ease-out.
- **State transitions:** colours 0.15 to 0.2s; button press 0.12s.

**The Visible At Rest Rule.** Content is visible without JavaScript and under reduced motion; motion only ever adds an entrance, never gates content.

### Owner-exception element (not part of this system)
The build carries three small eyebrow pills (14px, with a gold dot) above the hero headline, the work heading and the form heading. They are kept by Ellie's explicit house-style choice (calm-photo-style.md item 5) and recorded in HANDOFF.md as a conflict with the craft floor. This file does not adopt them as a component: new surfaces should not add more, and they must stay quiet (no arrow, no hover, no shadow, no gold fill).

## Do's and Don'ts

### Do:
- **Do** fill actions with Flyer Gold and set Ink Navy text on it.
- **Do** use Gold Ink, not gold, whenever the accent is text or a line icon on paper or the light band.
- **Do** alternate light and dark bands, and keep the diagonal line texture to deep navy bands.
- **Do** keep tap targets at least 44px (buttons 56px, chips 48px, rows 76px, banner 80px).
- **Do** gate hover styles behind a real pointer (`hover: hover`) so taps don't leave them stuck.
- **Do** switch focus outlines to gold on navy, hero and footer grounds.
- **Do** let the client's own photos carry the proof, under a navy wash when text sits on them.

### Don't:
- **Don't** use gold as a band, card or large background.
- **Don't** use black as a ground; dark grounds are navy.
- **Don't** use Focus Blue as a decorative colour; it is reserved for focus and form hover.
- **Don't** add shadows to cards, buttons, banners or bands; only floating elements cast them.
- **Don't** set Cal Sans bold or add a second display face.
- **Don't** add a sticky bottom bar; the floating circle is the one persistent action.
- **Don't** animate content that is visible on first load, beyond the hero letter bounce-in.
