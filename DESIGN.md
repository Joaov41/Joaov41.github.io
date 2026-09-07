---
name: Joao Valente — Independent Apple Developer
description: A personal portfolio set in the grammar of an Apple developer documentation page — white paper, near-black ink, one blue, hairlines, system sans in two weights.
colors:
  paper: "#ffffff"
  ink: "#1d1d1f"
  ink-secondary: "#6e6e73"
  rule: "#d2d2d7"
  well: "#f5f5f7"
  link: "#0066cc"
  link-hover: "#0077ed"
  focus: "#0071e3"
  selection: "#b4d5fe"
  code-keyword: "#ad3da4"
  code-type: "#3f6e74"
  code-string: "#d12f1b"
  code-attribute: "#947100"
  code-comment: "#707f8c"
  paper-dark: "#000000"
  ink-dark: "#f5f5f7"
  ink-secondary-dark: "#a1a1a6"
  rule-dark: "#424245"
  well-dark: "#161617"
  link-dark: "#2997ff"
  link-hover-dark: "#4fadff"
  focus-dark: "#2997ff"
  selection-dark: "#1f4e84"
  code-keyword-dark: "#ff7ab2"
  code-type-dark: "#78c2b3"
  code-string-dark: "#ff8170"
  code-attribute-dark: "#d9c97c"
  code-comment-dark: "#7f8c98"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, system-ui, 'Helvetica Neue', Helvetica, Arial, sans-serif"
    fontSize: "clamp(34px, 3.4vw, 44px)"
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: "-0.015em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, system-ui, 'Helvetica Neue', Helvetica, Arial, sans-serif"
    fontSize: "28px"
    fontWeight: 600
    lineHeight: 1.15
    letterSpacing: "-0.012em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, system-ui, 'Helvetica Neue', Helvetica, Arial, sans-serif"
    fontSize: "22px"
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "-0.01em"
  abstract:
    fontFamily: "-apple-system, BlinkMacSystemFont, system-ui, 'Helvetica Neue', Helvetica, Arial, sans-serif"
    fontSize: "21px"
    fontWeight: 400
    lineHeight: 1.38
    letterSpacing: "normal"
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, system-ui, 'Helvetica Neue', Helvetica, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.47
    letterSpacing: "normal"
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, system-ui, 'Helvetica Neue', Helvetica, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: "normal"
  caption:
    fontFamily: "-apple-system, BlinkMacSystemFont, system-ui, 'Helvetica Neue', Helvetica, Arial, sans-serif"
    fontSize: "13px"
    fontWeight: 400
    lineHeight: 1.3
    letterSpacing: "normal"
  code:
    fontFamily: "ui-monospace, 'SF Mono', Menlo, Consolas, monospace"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: "normal"
rounded:
  focus: "2px"
  sm: "6px"
  md: "10px"
  icon: "22%"
spacing:
  xs: "4px"
  sm: "8px"
  md: "12px"
  base: "16px"
  lg: "20px"
  xl: "28px"
  2xl: "40px"
  3xl: "48px"
  4xl: "64px"
components:
  link:
    textColor: "{colors.link}"
  link-hover:
    textColor: "{colors.link-hover}"
  globalnav:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    height: "48px"
  globalnav-link:
    textColor: "{colors.ink}"
    typography: "{typography.label}"
  globalnav-link-hover:
    textColor: "{colors.link}"
  nav-row:
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.sm}"
    padding: "5px 8px"
  nav-row-hover:
    backgroundColor: "{colors.well}"
    textColor: "{colors.ink}"
  nav-row-current:
    backgroundColor: "{colors.well}"
    textColor: "{colors.link}"
  on-this-page-row:
    textColor: "{colors.ink-secondary}"
    typography: "{typography.label}"
    rounded: "{rounded.sm}"
    padding: "5px 8px"
  breadcrumb:
    textColor: "{colors.ink-secondary}"
    typography: "{typography.label}"
  availability-badge:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    typography: "{typography.caption}"
    rounded: "{rounded.sm}"
    padding: "3px 9px"
  declaration-well:
    backgroundColor: "{colors.well}"
    textColor: "{colors.ink}"
    typography: "{typography.code}"
    rounded: "{rounded.md}"
    padding: "16px 20px"
  declaration-inline:
    backgroundColor: "{colors.well}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
    padding: "10px 14px"
  app-icon:
    rounded: "{rounded.icon}"
    size: "72px"
  symbol-row:
    backgroundColor: "{colors.paper}"
    padding: "28px 0"
  topic-row:
    backgroundColor: "{colors.paper}"
    padding: "22px 0"
  topic-name:
    textColor: "{colors.link}"
    typography: "{typography.body}"
  footer:
    textColor: "{colors.ink-secondary}"
    typography: "{typography.caption}"
---

# Design System: Joao Valente — Independent Apple Developer

## Overview

**Creative North Star: "The Symbol Reference"**

The portfolio is written as a developer documentation page about the developer himself. It borrows the grammar of Apple's developer documentation wholesale: a hairline-bounded navigator on the left, a breadcrumb, a large plain title, a grey abstract, an Availability row, a Declaration well set in mono, and then each app as a documented symbol with its own icon, `@available` declaration, overview paragraph and See Also links. The interface recedes so completely that the work is the only thing with colour on the page.

The material is paper and ink. White (or, in dark mode, true black) carries a single near-black text colour, a single secondary grey, one blue that means "you can go here", and 1px hairlines that do all of the structural work: column boundaries, section underlines, row separators, the badge outline. The only filled surface is a whisper-grey well, used for code and for the active navigator row. There are no cards, no shadows, no gradients, no pills, no eyebrows or kickers, no italic display and no icons other than the four real app icons and the portrait.

Type is the platform's own system sans in exactly two weights: 400 for reading, 600 for anything that names something. Hierarchy is carried by size, tightening letter-spacing on larger sizes, and the grey secondary colour; never by a third weight, a second face, or uppercase tracking. Mono appears only inside declaration wells. Motion is nearly absent: 120ms colour transitions on navigator rows and a scroll-spy that moves the current-row highlight, both of which collapse under `prefers-reduced-motion`.

**Key Characteristics:**
- Documentation-page grammar: navigator / content / On This Page in a three-column grid on a 1440px frame.
- True-black paper and light ink palette with one blue; the dark scheme is the only scheme (user preference), not a `prefers-color-scheme` swap.
- Hairlines (1px `rule`) are the only structural device; the grey `well` is the only fill.
- System sans, two weights (400 / 600); mono for declarations only.
- Six-step size ramp from 44px display down to 13px caption, negative tracking above 20px.
- Flat, shadowless, unanimated at rest; 120ms colour transitions and scroll-spy highlight are the whole motion vocabulary.

## Colors

A monochrome paper-and-ink page with a single blue reserved for navigation, and a five-colour syntax set that lives only inside code wells.

### Primary
- **Documentation Blue** (`link`, `#0066cc`; dark `link-dark`, `#2997ff`): the only chromatic colour outside code. Every anchor, the current navigator row's label, topic names, and the h3 hover state. It always means "this goes somewhere".
- **Documentation Blue, lifted** (`link-hover`, `#0077ed`; dark `#4fadff`): hover colour for anchors, paired with a 1px underline offset 0.18em.
- **Focus Blue** (`focus`, `#0071e3`; dark `#2997ff`): 2px solid outline, offset 2px, on `:focus-visible` only.
- **Selection Blue** (`selection`, `#b4d5fe`; dark `#1f4e84`): text selection background, with ink kept as the selected text colour.

### Neutral
- **Paper** (`paper`, `#ffffff`; dark `#000000`): page, global nav, sticky navigator, and the availability badge fill. Dark mode is true black, not a dark grey, matching the `theme-color` meta.
- **Ink** (`ink`, `#1d1d1f`; dark `#f5f5f7`): all headings, body copy, navigator rows, global nav links, availability badge text, and code that isn't a token.
- **Secondary Ink** (`ink-secondary`, `#6e6e73`; dark `#a1a1a6`): the abstract under the H1, breadcrumbs, On This Page rows and title, topic meta lines, portrait caption, footer. Everything that describes rather than names.
- **Rule** (`rule`, `#d2d2d7`; dark `#424245`): every 1px hairline: global nav bottom, navigator right edge, tree indent line, symbol-header and h2 underlines, symbol and topic row separators, availability badge border, footer top, the breadcrumb `/` glyph, and the 1px vertical dividers between See Also links and meta spans.
- **Well** (`well`, `#f5f5f7`; dark `#161617`): the only filled surface. Declaration blocks, and the hover / current background of navigator and On This Page rows.

### Code Tokens (declaration wells only)
- **Keyword** (`code-keyword`, `#ad3da4`; dark `#ff7ab2`): `struct`, `let`.
- **Type** (`code-type`, `#3f6e74`; dark `#78c2b3`): type and protocol names.
- **String** (`code-string`, `#d12f1b`; dark `#ff8170`): string literals.
- **Attribute** (`code-attribute`, `#947100`; dark `#d9c97c`): `@available`.
- **Comment** (`code-comment`, `#707f8c`; dark `#7f8c98`): trailing `//` comments.

### Named Rules
**The One Blue Rule.** Outside a declaration well, the only chromatic colour on the page is `link`. If something is blue it is a destination; if it is a destination it is blue (or ink that turns blue on hover). No second accent, no coloured badges, no tinted sections.

**The Hairline Rule.** Structure is drawn with 1px `rule` lines, never with fills, shadows or spacing alone. A new region gets a hairline above or beside it; a filled panel is not an option.

**The Well Is For Code Rule.** `well` fills exactly two things: declaration wells and the hover / current state of a navigator row. It is not a card background, not a section tint, not a callout.

**The One Scheme Rule.** The site is dark by default and only dark: `color-scheme: dark` is set on `:root` and no `prefers-color-scheme` media query exists. The former light tokens (`#ffffff` paper, `#1d1d1f` ink, `#6e6e73` secondary, `#d2d2d7` hairline, `#f5f5f7` well, `#0066cc` link) are retired; do not reintroduce a light scheme without the owner's decision.

## Typography

**Display Font:** System sans (`-apple-system, BlinkMacSystemFont, system-ui`, with Helvetica Neue / Helvetica / Arial fallback)
**Body Font:** The same system sans
**Label/Mono Font:** System mono (`ui-monospace, "SF Mono", Menlo, Consolas`), declarations only

**Character:** One face, two weights. The platform's own UI sans renders the page as if it were part of the operating system's documentation; nothing is loaded, nothing is decorative. Large sizes tighten slightly (−0.010 to −0.015em); small sizes are left at natural tracking. Weight 600 names things (titles, nav root, row labels, badge keys, current nav row); weight 400 reads.

### Hierarchy
- **Display** (600, `clamp(34px, 3.4vw, 44px)`, 1.1, −0.015em): the page H1 only. `text-wrap: balance`.
- **Headline** (600, 28px → 24px at ≤480px, 1.15, −0.012em): section h2s, each underlined with a hairline and 12px of padding.
- **Title** (600, 22px, 1.2, −0.01em): app symbol h3s. Ink, turning blue on hover.
- **Abstract** (400, 21px → 19px at ≤480px, 1.38, secondary ink): the one-paragraph summary under the H1, capped at 62ch, `text-wrap: pretty`.
- **Body** (400, 17px → 16px at ≤480px, 1.47): overview paragraphs, capped at 68ch, `text-wrap: pretty`. Topic names use body size at 600 in blue.
- **Label** (400, 14px, 1.4): navigator rows, On This Page rows, breadcrumbs, global nav links, availability key, topic-level See Also rows. See Also rows inside app symbols sit one step up at 15px.
- **Caption** (400, 13px, 1.3): availability badge text, topic meta lines, portrait caption, footer.
- **Code** (400, mono 14px, 1.6; 13px in inline declarations): declaration wells only, `tab-size: 4`.

### Named Rules
**The Two Weights Rule.** 400 and 600 are the only weights on the page. Emphasis is never italic, never uppercase, never a third weight; it is size, 600, or secondary grey.

**The Mono Is Declaration Rule.** The mono stack appears only inside a `well`. Never for labels, eyebrows, meta lines or numerals in running copy.

**The Tightening Rule.** Letter-spacing goes negative only above 20px (−0.01em at 19–22px, −0.012em at 28px, −0.015em at the H1). Nothing below 19px is tracked.

## Layout

A 1440px documentation frame, centred, with a fluid gutter (`clamp(20px, 3vw, 40px)`). Above it a 48px sticky global nav with a hairline bottom edge. Below it a three-column grid: a 260px navigator (hairline right edge, 20px inner right padding), a fluid content column capped at 820px, and a 200px On This Page rail, separated by 48px column gaps. Both rails are sticky at `top: 48px`, scroll independently within `calc(100vh − 48px)`, and share a 28px top / 40px bottom inset with the content column's 28px top / 64px bottom.

Vertical rhythm inside the content column is a small, hairline-punctuated scale: 8px for inline gaps and meta lines, 12px under h2s and inside symbol bodies, 14px between paragraphs, 16px above abstracts and declarations, 20px above availability rows and the footer's inner padding, 28px around the symbol header and each app symbol row, 40px above every section, 56px above the footer. App symbols are a two-column grid (72px icon, 22px gap); the About block is a two-column grid (240px portrait, 28px gap).

Reading measures are enforced: 62ch on the abstract, 68ch on body paragraphs, both with `text-wrap: pretty`. Anchored scrolling is offset by `48px + 16px` so headings clear the sticky nav.

**Responsive:**
- **≤1199px:** the On This Page rail is removed; the grid becomes 240px navigator + fluid content.
- **≤899px:** single column, no outer gutter on the frame. The navigator turns into a sticky horizontal scroller under the global nav (hairline bottom, no scrollbar, root and third-level items hidden, rows padded 6px 12px). Content takes the fluid gutter and 20px / 48px vertical insets. Global nav collapses to title + last link (GitHub). App icons drop to 56px with a 16px gap; the hairline dividers between See Also links and meta spans are replaced by 16px gaps. The About grid stacks and the portrait shrinks to 200px.
- **≤480px:** body 16px, abstract 19px, h2 24px; the footer stacks vertically.

**The Rail Rule.** The three-column frame is the desktop truth; rails are dropped right-to-left as width shrinks (On This Page first, then the navigator flattens). Content never reflows into a card grid.

## Elevation & Depth

There are no shadows. The page is flat at every state: depth is conveyed by hairlines (`rule`), by the single grey `well` fill for code and the active navigator row, and by the sticky positioning of the global nav and rails, each sealed with a 1px hairline. The one `box-shadow` in the stylesheet is an inset 1px ring on app icons (`inset 0 0 0 1px rgba(0,0,0,0.08)`, `rgba(255,255,255,0.12)` in dark), which is a hairline drawn by other means rather than an elevation.

**The Flat Paper Rule.** No drop shadows, no glows, no gradients, no blur. If something needs to read as separate, give it a hairline; if it needs to read as recessed, give it the `well`.

## Shapes

Corners are soft but unremarkable. Small interactive rectangles (navigator rows, availability badges, the skip link) round at 6px; larger surfaces (declaration wells, the portrait) round at 10px. App icons take a 22% radius to approximate the platform squircle and carry the inset hairline ring. The focus outline rounds at 2px. Nothing is fully rounded: availability badges are rectangles with 6px corners and a hairline border, not pills. Hairlines are always 1px, square-ended, in `rule`; vertical dividers between inline links are 1px × 0.9em.

## Components

### Global Nav
- **Style:** 48px tall, sticky, `paper` background, hairline bottom. Inner frame 1440px with the fluid gutter.
- **Title:** ink, 19px / 600 / −0.01em; no hover change.
- **Links:** ink, 14px, 28px apart; hover turns them `link` blue with no underline. On ≤899px only the last link (GitHub) survives.

### Navigator (left rail)
- **Style:** sticky, 14px / 1.4, hairline right edge. Nested `ul`s indent 14px + 12px with a 1px vertical `rule` line drawn 4px shy of the top and bottom.
- **Row:** block link, 5px 8px padding, 1px vertical margin, 6px radius, ink.
- **Hover:** `well` background, ink, no underline; 120ms ease-out on background and colour.
- **Current (`aria-current`, set by scroll-spy):** `well` background, `link` blue, weight 600. The root row is always 600.
- **Mobile (≤899px):** flattens to one horizontal scroller of second-level rows (6px 12px padding, 2px horizontal margin), sticky under the global nav.

### On This Page (right rail)
- **Style:** sticky, 14px, rows in secondary ink with the same 5px 8px / 6px-radius row shape. Title "On This Page" at 12px / 600 / secondary ink. Hover and current states are identical to the navigator. Hidden below 1200px.

### Breadcrumbs
- **Style:** 14px, secondary ink, items 8px apart, separated by a `/` in `rule` colour. Links are secondary ink and take the standard blue-underline hover.

### Symbol Header
- **Structure:** H1 (display) → abstract (21px secondary, 16px above) → availability row (20px above). Closed by a hairline with 28px padding below, 28px above the whole block.

### Availability Badges
- **Style:** `dl` row, 8px gaps; key "Availability" at 14px / 600 with 6px right margin; each value a hairline-bordered rectangle, 3px 9px padding, 6px radius, 13px / 1.3, ink on paper. Static; no hover.

### Declaration Wells
- **Block:** `well` background, 10px radius, 16px 20px padding, mono 14px / 1.6, ink, horizontal overflow scrolls. Syntax tokens use the five code colours.
- **Inline (per app):** same well at 13px, 10px 14px padding, `display: inline-block` so it hugs the declaration; 10px above.

### App Symbol Rows
- **Structure:** two-column grid, 72px icon (22% radius, inset hairline ring) + body; 28px vertical padding; hairline below each except the last.
- **Title:** h3 at 22px / 600, ink; hover blue. Followed by the inline declaration, a body paragraph (12px above), then a See Also row (14px above).
- **Mobile:** icon 56px, 16px gap.

### See Also Rows
- **Style:** "See Also" label at 600 in ink, then a wrapping list of links at 15px separated by 1px × 0.9em `rule` dividers with 12px margins. The first link (the primary destination) is 600. Inside topic rows the row drops to 14px and the first link is 400. On ≤899px dividers are removed in favour of 16px gaps.

### Topic List (projects, See Also section)
- **Row:** 22px vertical padding, hairline below except the last; 8px above the list.
- **Name:** 17px / 600 in `link` blue (ink when it is a plain span, not a link).
- **Meta:** 13px secondary ink, spans separated by hairline dividers with 10px margins; 6px above the name.
- **Description:** 16px ink, 8px above.

### Portrait Figure
- **Style:** 240px square image, `object-fit: cover`, 10px radius; caption 13px secondary ink 8px below. 200px on ≤899px.

### Footer
- **Style:** hairline top, 20px top padding, 56px above; 13px secondary ink; text left, "Back to top" link right; stacks vertically on ≤480px.

### Links (global)
- **Default:** `link` blue, no underline.
- **Hover:** `link-hover` blue, 1px underline offset 0.18em.
- **Focus:** 2px solid `focus` outline, 2px offset, 2px radius, on `:focus-visible` only.

### Motion
- 120ms `ease-out` on `background-color` and `color` for navigator and On This Page rows; nothing else transitions.
- `scroll-behavior: smooth` with a `48px + 16px` scroll padding.
- Scroll-spy: an `IntersectionObserver` (`rootMargin: -64px 0px -60% 0px`) sets `aria-current="location"` on the navigator and On This Page links for the topmost visible section; the highlight is the `nav-row-current` style, no animation beyond the 120ms colour change.
- `prefers-reduced-motion: reduce` sets `scroll-behavior: auto` and collapses all transition durations to 0.01ms.

## Do's and Don'ts

### Do:
- **Do** draw every boundary as a 1px `rule` hairline (column edges, h2 underlines, row separators, badge borders) and nothing else.
- **Do** keep `link` blue as the only chromatic colour outside code wells; blue always means a destination.
- **Do** use exactly two weights: 600 to name (titles, labels, current nav row, primary See Also link), 400 to read.
- **Do** define new colours against the single dark scheme: true black paper with `#f5f5f7` ink.
- **Do** cap reading measures at 62ch (abstract) and 68ch (body) with `text-wrap: pretty`.
- **Do** add a new app as one `.symbol` block and a new project as one `.topic` block; the row grammar (icon / title / declaration / paragraph / See Also) is the unit of growth.
- **Do** keep functional text at 13px or above and body at 17px (16px at ≤480px).

### Don't:
- **Don't** add cards, panels, tinted sections or any filled container other than a declaration well.
- **Don't** use shadows, gradients, blur or glows anywhere; the inset hairline ring on app icons is the only permitted `box-shadow`.
- **Don't** introduce a second accent, coloured badges, or platform-coloured tags; availability badges are ink on paper with a hairline border.
- **Don't** use mono outside a `well`, and don't use eyebrows, kickers, uppercase tracked labels, italic display or a third weight.
- **Don't** make availability badges or nav rows pill-shaped; corners stay at 6px, wells at 10px.
- **Don't** add motion beyond 120ms colour transitions and the scroll-spy highlight; anything animated must collapse under `prefers-reduced-motion`.
- **Don't** replace the documentation frame with a hero, a bento grid or a card grid at any breakpoint; rails drop, content never reflows into cards.
