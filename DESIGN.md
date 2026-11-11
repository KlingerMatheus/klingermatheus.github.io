---
name: Klinger Matheus Portfolio
description: A single static page in Apple's design language where measurements, shown as before and after, carry the proof.
colors:
  bg: "#ffffff"
  panel: "#f5f5f7"
  text: "#1d1d1f"
  text-2: "#6e6e73"
  line: "#d2d2d7"
  link: "#0066cc"
  action: "#0071e3"
  action-hover: "#0062c3"
  on-action: "#ffffff"
  bar: "rgba(255, 255, 255, 0.72)"
  select: "rgba(0, 113, 227, 0.2)"
  bg-dark: "#000000"
  panel-dark: "#1d1d1f"
  text-dark: "#f5f5f7"
  text-2-dark: "#a1a1a6"
  line-dark: "#424245"
  link-dark: "#2997ff"
  bar-dark: "rgba(0, 0, 0, 0.72)"
  select-dark: "rgba(41, 151, 255, 0.35)"
typography:
  display:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', 'Noto Sans', 'Liberation Sans', Arial, sans-serif"
    fontSize: "clamp(2.75rem, 10.5vw, 6rem)"
    fontWeight: 600
    lineHeight: 1.04
    letterSpacing: "-0.035em"
  headline:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', 'Noto Sans', 'Liberation Sans', Arial, sans-serif"
    fontSize: "clamp(2rem, 5.4vw, 3.5rem)"
    fontWeight: 600
    lineHeight: 1.07
    letterSpacing: "-0.03em"
  title:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', 'Noto Sans', 'Liberation Sans', Arial, sans-serif"
    fontSize: "clamp(1.75rem, 4vw, 2.5rem)"
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: "-0.03em"
  figure:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', 'Noto Sans', 'Liberation Sans', Arial, sans-serif"
    fontSize: "clamp(1.5rem, 3vw, 2.25rem)"
    fontWeight: 600
    lineHeight: 1.15
    letterSpacing: "-0.03em"
    fontFeature: "'tnum'"
  subhead:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', 'Noto Sans', 'Liberation Sans', Arial, sans-serif"
    fontSize: "clamp(1.375rem, 3.6vw, 2rem)"
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "-0.02em"
  title-sm:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', 'Noto Sans', 'Liberation Sans', Arial, sans-serif"
    fontSize: "1.3125rem"
    fontWeight: 600
    lineHeight: 1.47
    letterSpacing: "-0.02em"
  lead:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', 'Noto Sans', 'Liberation Sans', Arial, sans-serif"
    fontSize: "clamp(1.0625rem, 2vw, 1.3125rem)"
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: "-0.01em"
  body:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', 'Noto Sans', 'Liberation Sans', Arial, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.47
    letterSpacing: "-0.01em"
  label:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', 'Noto Sans', 'Liberation Sans', Arial, sans-serif"
    fontSize: "0.875rem"
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: "-0.01em"
  nav:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', 'Noto Sans', 'Liberation Sans', Arial, sans-serif"
    fontSize: "0.8125rem"
    fontWeight: 400
    lineHeight: 1.47
    letterSpacing: "-0.01em"
rounded:
  panel: "28px"
  pill: "999px"
spacing:
  gutter: "clamp(20px, 5vw, 44px)"
  page: "1024px"
  section: "clamp(72px, 11vw, 136px)"
  panel-pad: "clamp(28px, 5vw, 56px)"
  panel-gap: "clamp(16px, 2vw, 24px)"
  column-gap: "clamp(24px, 5vw, 64px)"
  heading-gap: "clamp(28px, 4vw, 48px)"
  row: "18px"
  target: "44px"
components:
  button-pill:
    backgroundColor: "{colors.action}"
    textColor: "{colors.on-action}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: "0 22px"
    height: "{spacing.target}"
  button-pill-hover:
    backgroundColor: "{colors.action-hover}"
  link-inline:
    textColor: "{colors.link}"
    typography: "{typography.body}"
    height: "{spacing.target}"
  panel:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.text}"
    rounded: "{rounded.panel}"
    padding: "{spacing.panel-pad}"
  bar:
    backgroundColor: "{colors.bar}"
    textColor: "{colors.text}"
    typography: "{typography.nav}"
    height: "48px"
  measure-row:
    textColor: "{colors.text}"
    typography: "{typography.figure}"
    padding: "14px 0"
  table-row:
    textColor: "{colors.text}"
    typography: "{typography.body}"
    padding: "18px 0"
---

# Design System: Klinger Matheus Portfolio

## Overview

**Creative North Star: "The Measured Page"**

The owner pinned this system to Apple's design language: a white or true-black ground, one grey panel tone, near-black text, one grey for secondary text, and one blue reserved for things you can press. The system sans is set large and tight for statements and at a comfortable reading size for everything else. Nothing decorates. Structure comes from generous vertical rhythm, hairline rules, and rounded grey panels.

The page is static HTML and CSS with no JavaScript and no web font, which is itself part of the design: it renders instantly, in both light and dark by system preference, and holds WCAG AA contrast in each. Numbers are the proof material, so they get display-weight type with tabular figures, and a measured change is always shown as a quiet "was" value, an arrow, and a strong "now" value.

Density is low at the top (a centered name, role, summary, and a full-width portrait) and tighter below, where hairline-separated rows carry lists of facts. Motion is limited to a single settle on first load.

**Key Characteristics:**
- Two grounds only: page and one panel tone, swapped as a pair between light and dark.
- One blue, used only for links, the single filled pill, focus rings and selection.
- Two weights (400 and 600) of one system sans; tracking tightens as size grows.
- Hairline rules for rows; no shadows; frosted glass only on the sticky bar.
- Large rounded panels (28px) and fully round pills; nothing in between.
- Measurements as before-and-after pairs with tabular figures.
- No JavaScript; one load animation; reduced motion respected.

## Colors

A neutral palette taken from Apple's greys, with a single blue. Dark mode is a token swap under `prefers-color-scheme: dark`, not a separate design: the same roles, re-valued.

### Primary
- **Action Blue** (`action`, hover `action-hover`): the fill of the one pill button, the skip link, and the focus ring. It is the same value in both themes. White text on it (`on-action`) measures 4.7:1, and 5.9:1 on hover.
- **Link Blue** (`link` in light, `link-dark` in dark): text links, including the large email address in the contact section. Darker than Action Blue in light mode and lighter in dark mode so that link text clears AA on both the page and the panel ground (5.1:1 at worst in light, 5.6:1 in dark).

### Neutral
- **Page** (`bg` / `bg-dark`): pure white, pure black. The default ground.
- **Panel Grey** (`panel` / `panel-dark`): the only raised tone. Fills project panels and sits behind the portrait while it loads.
- **Ink** (`text` / `text-dark`): all primary text and headings. Never pure black on white or pure white on black.
- **Secondary Ink** (`text-2` / `text-2-dark`): role line, captions, technology lists, dates, "was" values, list bullets, footer. Measures 4.66:1 on Panel Grey in light mode, its tightest pairing; do not lighten it.
- **Hairline** (`line` / `line-dark`): 1px rules between rows and above the footer. Decorative separation only, never the sole carrier of meaning.
- **Bar Glass** (`bar` / `bar-dark`): the page ground at 72% opacity, used only for the sticky bar over a backdrop blur.
- **Selection** (`select` / `select-dark`): translucent blue behind selected text.

### Named Rules
**The One Blue Rule.** Blue means "you can act on this". It appears on links, the filled pill, focus rings and text selection, and nowhere else. No blue headings, icons, rules or backgrounds.

**The Paired Ground Rule.** There are two surface tones per theme, page and panel. A third tone, a tinted section, or a panel inside a panel is a system change, not an extension.

## Typography

**Display Font:** the system UI face (`system-ui`, then `-apple-system`, `BlinkMacSystemFont`, `Segoe UI`, `Roboto`, `Helvetica Neue`, `Noto Sans`, `Liberation Sans`, `Arial`)
**Body Font:** the same stack

**Character:** One family at two weights. This is the owner's decision: it renders as San Francisco on Apple devices, which is the reference, and costs nothing to load anywhere else. Hierarchy comes from size, weight and tracking alone.

### Hierarchy
- **Display** (600, `clamp(2.75rem, 10.5vw, 6rem)`, 1.04, -0.035em): the name in the hero. One per page.
- **Headline** (600, `clamp(2rem, 5.4vw, 3.5rem)`, 1.07, -0.03em): section headings.
- **Title** (600, `clamp(1.75rem, 4vw, 2.5rem)`, 1.1, -0.03em): project names inside panels. The contact email address is set at the same top size.
- **Figure** (600, `clamp(1.5rem, 3vw, 2.25rem)`, 1.15, -0.03em, tabular figures): measured values in panels. The hero figures strip runs one step larger, `clamp(1.75rem, 3.3vw, 2.5rem)` at 1.1.
- **Subhead** (600, `clamp(1.375rem, 3.6vw, 2rem)`, 1.2, -0.02em): the role line under the name, in Secondary Ink.
- **Small Title** (600, 1.3125rem, -0.02em): row headings and short principle headings. Role headings in the experience list scale it up to 1.5rem.
- **Lead** (400, `clamp(1.0625rem, 2vw, 1.3125rem)`, 1.45): the hero summary and contact lede. Capped at 36 to 43rem.
- **Body** (400, 1.0625rem, 1.47, -0.01em): everything else. Capped at 28 to 41rem depending on the column.
- **Label** (400, 0.875rem, 1.4): captions under figures, measurement names, technology lists, location line. In Secondary Ink, sentence case. 0.9375rem is used for dates and secondary row lines.
- **Nav** (400, 0.8125rem): bar links and footer.

### Named Rules
**The Two Weights Rule.** Regular (400) and semibold (600). Headings, figures and row terms are 600; everything else is 400. No light, medium or bold.

**The Tightening Rule.** Tracking follows size: -0.01em at body, -0.02em from about 1.3 to 2rem, -0.03em from 2 to 3.5rem, -0.035em at display. Small text is never tracked tighter than body, and nothing is tracked wide or set in capitals.

**The Tabular Rule.** Any number meant to be compared (measurements, dates) uses tabular figures.

Headings use `text-wrap: balance`; paragraphs and list items use `text-wrap: pretty`.

## Layout

One centered column: `min(100% - 2 × gutter, 1024px)`, with a fluid gutter (`gutter`). Every section sits in that column and is separated from the previous one by a single fluid top padding (`section`); the heading then clears its content by `heading-gap`. Spacing is fluid by `clamp()` rather than stepped, so there is no fixed spacing scale beyond these named tokens.

The hero is centered down to 640px and left-aligned below it; the contact section stays centered. Everything between is left-aligned.

Three recurring grids:
- **Label and content:** a fixed-max first column (15rem) and a flexible second, with `column-gap` between. Used for experience entries and definition tables. Collapses to one column at 720px.
- **Two equal columns:** project panels (collapse at 820px) and the principles grid (collapse at 640px).
- **Figures strip:** five equal columns; three plus two at 860px; two columns with the last spanning at 520px.

Rows inside lists are padded 14 to 22px top and bottom between hairlines; text aligns to the column edge, with no side padding. Reading widths are capped in rem, not left to fill the column.

Interactive targets hold a 44px minimum height (`target`), and the bar holds 48px. The bar hides its two secondary links below 560px rather than wrapping or adding a menu. Anchor jumps reserve 72px for the sticky bar.

## Elevation & Depth

The system is flat. The build ships no shadows. Depth comes from two things only: the tonal step from page to panel, and the sticky bar, which is the page colour at 72% opacity over `saturate(180%) blur(20px)` with a 1px hairline at 60% strength beneath it.

### Named Rules
**The One Glass Rule.** Backdrop blur belongs to the sticky bar and nothing else. Panels, buttons and overlays stay opaque.

## Shapes

Two radii with nothing between them: a large, soft corner (28px) on panels and the portrait, and a full round (999px) on the pill button and skip link. The focus ring carries its own small 6px corner. Panels have no border; rows have no background. Bullets are 5px round dots in Secondary Ink.

Icons are two inline SVG strokes drawn for this page: an outbound arrow after external links and a right arrow between "was" and "now". Both are stroke-only, round caps and joins, about 1.5 to 1.6 wide, sized in em so they scale with their text, and coloured by `currentColor` or Secondary Ink.

The portrait is cropped by ratio per viewport (2:1 wide, 3:2 mid, 4:5 narrow) and clipped to the panel radius.

## Components

Restrained and quiet: one filled control, text links for everything else.

### Buttons
- **Shape:** fully round pill (999px), 44px tall, 22px side padding.
- **Primary:** Action Blue fill, white body-size text at regular weight. One per view; in the build it is the email action in the hero.
- **Hover / Focus:** fill shifts to the darker blue over 0.2s on the system ease (`cubic-bezier(0.16, 1, 0.3, 1)`), with no movement or shadow. Focus is the global ring: 2px Action Blue outline, 3px offset.
- **Secondary:** there is no secondary button. Lesser actions are text links placed beside the pill.

### Links
- **Style:** Link Blue, no underline at rest, a 1px underline on hover, offset 0.18em. External links end with the outbound arrow icon.
- **Standalone links** (beside a pill, or closing a block) are inline-flex with a 44px minimum height.
- **Quiet links** (bar, footer) take the surrounding text colour instead of blue.

### Cards / Containers
- **Corner Style:** 28px.
- **Background:** Panel Grey. No border, no shadow.
- **Internal Padding:** `panel-pad`, with two equal columns separated by a wide fluid gap; stacked panels are `panel-gap` apart.
- **Use:** only for featured work. Lists of lesser items are hairline rows on the page ground, not cards.

### Navigation
- **Style:** sticky frosted bar, 48px, name at left in 1rem semibold, links at right in 0.8125rem.
- **States:** links rest at 82% opacity and go to full on hover, with no underline. There is no active state; the links are in-page anchors.
- **Mobile:** secondary links are hidden below 560px. No menu.

### Before-and-after rows (signature)
A list of measurements separated by hairlines, 14px above and below each. The measurement name sits on top in Label style; the value sits below in Figure style. A changed value is written as the old number in Secondary Ink at regular weight, the right-arrow icon (with an accessible "to" label), then the new number in Ink at semibold. A value with no "before" is the new number alone.

### Figures strip
A row of headline numbers, each topped by a hairline with 18px clearance, the number in Figure style and a Label caption beneath.

### Definition tables and rows
Term at left in semibold with an optional small note beneath in Label style; description at right in body. Hairline above each row and below the last, 18px padding. A row can be quieted by setting its description in Secondary Ink.

### Motion
One load sequence on the hero only, and only when the visitor has not asked for reduced motion. Each hero element settles in (fade, 14px rise, 6px blur clearing) over 0.9s, staggered by about 0.07s; the portrait instead unveils (fade, scale from 0.975, inset clip opening to the panel radius) over 1.2s. Everything uses the one ease, `cubic-bezier(0.16, 1, 0.3, 1)`. Nothing animates on scroll.

## Do's and Don'ts

### Do:
- **Do** keep blue for actions: links, the one filled pill, focus rings, selection.
- **Do** swap colours through the theme tokens so every surface works in light and dark, and check Secondary Ink on Panel Grey (4.66:1) whenever either value changes.
- **Do** set comparable numbers in semibold with tabular figures, and show a change as old value, arrow, new value.
- **Do** separate list rows with 1px hairlines on the page ground, and reserve Panel Grey panels (28px radius) for featured content.
- **Do** tighten tracking as type grows, following the Tightening Rule, and cap reading widths in rem.
- **Do** hold 44px minimum height on every standalone link and button, and keep the 2px blue focus ring visible.
- **Do** draw new icons as em-sized inline SVG strokes with round caps, matching the two that exist.
- **Do** wrap any motion in `prefers-reduced-motion: no-preference` and use the one ease.

### Don't:
- **Don't** introduce a second accent hue, or use blue for decoration.
- **Don't** add a third surface tone or nest a panel inside a panel.
- **Don't** add a third font weight, uppercase text, or wide tracking.
- **Don't** add a radius between 28px and the full pill for containers or controls.
- **Don't** put backdrop blur on anything but the sticky bar.
- **Don't** animate on scroll; the page has one load sequence and then stays still.
- **Don't** make any content or layout depend on JavaScript.
