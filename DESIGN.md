---
name: Design Knowledge Base
description: A curated, practical library for design teams.
colors:
  ink: "#0b0f14"
  ink-raised: "#0f1724"
  slate-panel: "#121a26"
  cabinet: "#162131"
  cabinet-hover: "#1d2b40"
  divider-low: "#1f2a3a"
  divider-mid: "#253247"
  divider-high: "#2b3a4f"
  lab-blue: "#4b8cff"
  lab-blue-hover: "#6aa2ff"
  reference-blue: "#8fc5ff"
  reference-blue-hover: "#b4d9ff"
  paper: "#e6e9ee"
  paper-bright: "#f4f6f9"
  chalk: "#c9d4e2"
  ash: "#8fa2b8"
  footer-ink: "#0f1520"
typography:
  display:
    fontFamily: "Poppins, sans-serif"
    fontSize: "40px"
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "normal"
  headline:
    fontFamily: "Poppins, sans-serif"
    fontSize: "36px"
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "normal"
  title:
    fontFamily: "Poppins, sans-serif"
    fontSize: "28px"
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: "normal"
  subtitle:
    fontFamily: "Poppins, sans-serif"
    fontSize: "24px"
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: "normal"
  body:
    fontFamily: "Roboto, Arial, Helvetica, sans-serif"
    fontSize: "20px"
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: "normal"
  lead:
    fontFamily: "Roboto, Arial, Helvetica, sans-serif"
    fontSize: "22px"
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: "normal"
  label:
    fontFamily: "Roboto, Arial, Helvetica, sans-serif"
    fontSize: "16px"
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: "normal"
  eyebrow:
    fontFamily: "Roboto, Arial, Helvetica, sans-serif"
    fontSize: "12px"
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "0.18em"
rounded:
  sm: "8px"
  md: "10px"
  lg: "12px"
  xl: "18px"
  xxl: "22px"
spacing:
  xs: "8px"
  sm: "12px"
  md: "16px"
  lg: "24px"
  xl: "32px"
  xxl: "48px"
  xxxl: "80px"
components:
  button-primary:
    backgroundColor: "{colors.lab-blue}"
    textColor: "{colors.ink}"
    rounded: "{rounded.lg}"
    padding: "14px 28px"
  button-primary-hover:
    backgroundColor: "{colors.lab-blue-hover}"
    textColor: "{colors.ink}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.paper}"
    rounded: "{rounded.lg}"
    padding: "14px 28px"
  button-ghost-hover:
    backgroundColor: "{colors.cabinet}"
    textColor: "{colors.paper}"
  card-project:
    backgroundColor: "{colors.slate-panel}"
    textColor: "{colors.chalk}"
    rounded: "{rounded.xl}"
    padding: "24px"
  pill-link:
    backgroundColor: "{colors.cabinet}"
    textColor: "{colors.reference-blue-hover}"
    rounded: "{rounded.md}"
    padding: "8px 14px"
  pill-link-hover:
    backgroundColor: "{colors.cabinet-hover}"
    textColor: "{colors.reference-blue-hover}"
---

# Design System: Design Knowledge Base

## 1. Overview

**Creative North Star: "The Lab Notebook"**

The system is a working notebook, not a polished portfolio. Pages of dark paper, a single working blue for marks and references, captions written in a neutral hand. Tools and ideas get logged side-by-side; some entries are finished, others are stubs marked TBD on purpose. The site is a frame around things worth reading and using; the things themselves are the content. Curiosity over polish, structure over decoration, honesty over showmanship.

The aesthetic is academic and a little plain in the right way: laboratory-issue, like a research index or museum object catalogue, where the typography does the speaking and the color does the indexing. The system rejects SaaS landing-page chrome, influencer-portfolio centerpieces, generic teal-on-white design-system look, and performative brutalism. Restraint here is genuine, not a trend.

**Key Characteristics:**
- Dark by default. Tonal layering builds depth before any shadow is reached for.
- Single load-bearing accent (Lab Blue) used as a working mark, not decoration.
- Typography pairing splits labor cleanly: Poppins names things, Roboto reads things.
- Asymmetric spacing scale (8 / 12 / 16 / 24 / 32 / 48 / 80) for rhythm, not metronome regularity.
- Cards are flat panels with full borders, never side-stripes or floating gradients.

## 2. Colors: The Lab Notebook Palette

A nearly-monochrome dark palette anchored by tonal layering, with one working blue carrying every interactive signal. Color is information, not decoration.

### Primary
- **Lab Blue** (`#4b8cff`): The single working accent. Used on primary action buttons (filled), and as the load-bearing brand color whenever something needs to *do* something. Never decorative.
- **Lab Blue Hover** (`#6aa2ff`): Hover state for primary buttons.

### Secondary
- **Reference Blue** (`#8fc5ff`): Inline link color across body copy. Lighter, paler, less dense than Lab Blue. The distinction matters: Lab Blue is the *call*, Reference Blue is the *citation*.
- **Reference Blue Hover** (`#b4d9ff`): Hover state for inline links.

### Neutral
- **Ink** (`#0b0f14`): Page background. Tinted toward the brand hue, never `#000`. The paper of the notebook.
- **Ink Raised** (`#0f1724`): Sticky header band. One step lighter than Ink to lift it off the page.
- **Slate Panel** (`#121a26`): Card surfaces. The next step up the tonal ladder.
- **Cabinet** (`#162131`): Interactive pill surfaces (track-list links, project-card link, ghost button hover).
- **Cabinet Hover** (`#1d2b40`): Cabinet hover state.
- **Footer Ink** (`#0f1520`): Footer band. Sits between Ink and Ink Raised on the value scale.
- **Divider Low / Mid / High** (`#1f2a3a` / `#253247` / `#2b3a4f`): Three border weights for layered surfaces. Low for cards, Mid for pills, High for ghost buttons. Never colored stripes; always full borders.
- **Paper** (`#e6e9ee`): Default body text on dark surfaces.
- **Paper Bright** (`#f4f6f9`): Heading text. One step brighter than Paper to lift hierarchy.
- **Chalk** (`#c9d4e2`): Body copy inside cards and panels. Slightly muted vs. Paper.
- **Ash** (`#8fa2b8`): Eyebrow labels and tertiary text. The most reduced step before contrast fails.

### Named Rules
**The One Voice Rule.** Lab Blue carries every primary action and brand emphasis on a given screen. Used on roughly 5 to 10 percent of any visible surface. Its rarity is the point. Never used decoratively, never as a gradient, never as section-divider chrome.

**The Tonal Ladder Rule.** Depth on dark surfaces is built by stepping the background lightness, not by shadow. Page → Header → Card → Pill is a four-step ladder (Ink, Ink Raised, Slate Panel, Cabinet). Shadows only appear in response to interaction state.

**The Citation Rule.** Inline body links use Reference Blue. Action buttons use Lab Blue. The same color in two roles would erase the distinction between "go read this" and "press this".

## 3. Typography

**Display Font:** Poppins (with sans-serif fallback). Loaded via Google Fonts at weights 400, 500, 600, 700.
**Body Font:** Roboto (with Arial, Helvetica, sans-serif fallback). Loaded at default weight.

**Character:** Poppins is the curator's hand: geometric, even, confident in titles and section labels. Roboto is the reader's hand: neutral, transparent, gets out of the way. The pairing is institutional rather than expressive on purpose. The notebook does not need a voice; the entries do.

### Hierarchy
- **Display** (Poppins, 700, 40px, line-height 1.2): Page titles. One per page, top of hero.
- **Headline** (Poppins, 600, 36px, line-height 1.2): Major section openers. 64px top margin, 24px bottom.
- **Title** (Poppins, 600, 28px, line-height 1.25): Subsection headers and card titles inside sections.
- **Subtitle** (Poppins, 600, 24px, line-height 1.3): Card titles on home; small headers in long-form pages.
- **Body** (Roboto, 400, 20px, line-height 1.6): Default running text. Cap line length at 65 to 75 characters.
- **Lead** (Roboto, 400, 22px, line-height 1.55): Hero subhead and section intros. One paragraph max.
- **Label** (Roboto, 600, 16px): Pill links, project-card link buttons, navigation items.
- **Eyebrow** (Roboto, 600, 12px, letter-spacing 0.18em, uppercase): Section pre-headers, category tags. Used sparingly.

### Named Rules
**The Two-Hand Rule.** Poppins names; Roboto reads. Headings, labels, eyebrows, button text, captions go to Poppins. Body, lead, paragraph copy go to Roboto. Mixing them within a role erases the split.

**The Step Ratio Rule.** The hierarchy steps at roughly 1.25 to 1.4 between adjacent levels (40 → 36 → 28 → 24 → 20). Never collapse two steps to within 10 percent of each other; the scale stops reading.

## 4. Elevation

The system is **flat by tonal layering** at rest, with shadows reserved as interaction signals. Depth is built primarily by stepping background lightness across a four-step ladder (Ink → Ink Raised → Slate Panel → Cabinet). Borders are the second depth tool: full 1px borders on dividers Low / Mid / High mark surface boundaries cleanly. Shadows are the third tool, used only on hover, focus, and the sticky header.

### Shadow Vocabulary
- **Sticky Header Shadow** (`box-shadow: 0 12px 30px rgba(0, 0, 0, 0.25)`): Anchors the sticky header above page content as it scrolls. Applied at rest because the header is structurally elevated.
- **Hover Lift** (`box-shadow: 0 8px 24px rgba(0, 0, 0, 0.35)`): Optional addition for project-card hover. Pairs with a 1px border brightening to indicate the card is a link target.
- **Focus Ring** (`box-shadow: 0 0 0 3px rgba(75, 140, 255, 0.4)`): Focus-visible state on interactive elements. Lab Blue at low opacity, no border shift.

### Named Rules
**The Tonal-First Rule.** Depth is built by background steps before shadows are reached for. If a card looks flat against its parent, raise its background one step on the ladder before adding shadow.

**The Shadow-As-Verb Rule.** Shadows describe an action (hovering, focusing, sticking). Surfaces at rest do not have shadows. A decorative drop shadow on a static card is forbidden.

## 5. Components

### Buttons
- **Shape:** Gently rounded corners (12px radius / `{rounded.lg}`).
- **Primary:** Lab Blue (`#4b8cff`) background, Ink (`#0b0f14`) text. Padding 14px / 28px. Font: Poppins-adjacent label weight, 18px. Border 1px transparent.
- **Hover / Focus:** Background shifts to Lab Blue Hover (`#6aa2ff`). Focus adds the focus ring shadow. No transform, no scale.
- **Ghost:** Transparent background, Paper text, 1px Divider High (`#2b3a4f`) border. Hover shifts background to Cabinet (`#162131`).

### Cards (Project)
- **Corner Style:** 18px radius (`{rounded.xl}`).
- **Background:** Slate Panel (`#121a26`).
- **Border:** 1px solid Divider Low (`#1f2a3a`). Full border, never side-stripe.
- **Shadow Strategy:** None at rest. Hover Lift on hover only.
- **Internal Padding:** 24px.
- **Layout:** Flex column, 12px gap. Heading (Paper Bright), description (Chalk), trailing pill link aligned to flex-start.

### Pill Links
- **Style:** Cabinet (`#162131`) background, Reference Blue Hover (`#b4d9ff`) text, 1px Divider Mid border, 10px radius.
- **Padding:** 8px / 14px (project link), 10px / 14px (track-list).
- **Hover:** Background → Cabinet Hover (`#1d2b40`). No underline.
- **Use:** "View project" affordance on cards; learning-track entries on home.

### Sticky Header
- **Background:** Ink Raised (`#0f1724`).
- **Shadow:** Sticky Header Shadow (always on).
- **Layout:** Two-column grid, 24px gap, 24px padding, sticky at top: 0.
- **Type:** H1 at 24px Poppins 700 (institutional, not promotional). Nav links inline, Paper text, no underline at rest.
- **Mobile (≤1024px):** Collapses to single column, becomes non-sticky.

### Hero Panel (Home)
- **Layout:** Two-column grid (1.2fr / 0.8fr), 48px gap, vertically centered.
- **Right-side Panel:** Slate Panel background, 1px Divider Low border, 20px radius, 32px internal padding. Carries supporting content (track list, side reference).

### Hero CTA Panel
- **Background:** Linear gradient `linear-gradient(120deg, #1a2640 0%, #131b2b 60%, #0f1522 100%)`. The single permitted gradient surface, used only as a section-closer, never on cards or text. Full border `1px solid #243148`.
- **Shape:** 22px radius.
- **Layout:** Flex row, content on left, action group on right. Collapses to column on narrow viewports.

### Project Card Grid
- **Layout:** `grid-template-columns: repeat(3, minmax(0, 1fr))` desktop; 2-up at 1024px; 1-up at 720px.
- **Gap:** 24px.
- **TBD entries:** First-class. Render with same card frame, "TBD" prefix in title, neutral description, link href "#" or stub URL. The grid does not hide unfinished work.

## 6. Do's and Don'ts

### Do:
- **Do** use Lab Blue (`#4b8cff`) as the single primary accent, on roughly 5 to 10 percent of any visible surface. Reserve it for actions and brand identity.
- **Do** build depth by stepping background lightness across the tonal ladder (Ink → Ink Raised → Slate Panel → Cabinet) before reaching for shadows.
- **Do** keep TBD project cards visible and labeled. Works in progress are part of the brand.
- **Do** use full 1px borders (Divider Low / Mid / High) to mark card and panel edges. Always full perimeter.
- **Do** split type duty cleanly: Poppins for headings and labels, Roboto for body and lead.
- **Do** cap body line length at 65 to 75 characters.
- **Do** use Reference Blue (`#8fc5ff`) for inline links inside body copy, distinct from Lab Blue actions.
- **Do** respect `prefers-reduced-motion`. Disable hover lift and gradient transitions when set.

### Don't:
- **Don't** build a polished SaaS landing-page hero with gradient text, a hero-metric block, or a "trusted by" logo bar. PRODUCT.md names this anti-reference by name.
- **Don't** stage influencer-portfolio centerpieces. The work is the point, not the author.
- **Don't** drift into the generic design-system look (white background, teal accent, Inter, identical rounded card grid). PRODUCT.md flags this directly.
- **Don't** stage performative brutalism. The academic register is genuine, not costume.
- **Don't** use side-stripe borders (`border-left` greater than 1px as a colored accent). Use full borders or background tonal shifts instead.
- **Don't** apply gradient text via `background-clip: text`. Gradients are reserved to the single Hero CTA panel surface.
- **Don't** use shadows decoratively on resting cards. Shadows describe actions (hover, focus, sticky elevation).
- **Don't** reuse the same color in two roles (Lab Blue as both action and link, or Reference Blue on a button). The split is the system.
- **Don't** stack identical icon-title-text cards in endless rows. The home grid is curated, not a template.
- **Don't** introduce a third type family. Poppins and Roboto are committed.
- **Don't** use em dashes in copy. Use commas, colons, semicolons, periods, or parentheses.
