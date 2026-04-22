---
name: The Catalyst
description: Marketing Due Diligence — AI-powered diagnostic sprint for B2B service companies
tone: Bold editorial confidence. Premium, warm, direct. Not McKinsey-grey, not SaaS-pastel, not neo-brutalism.
audience: CEO/Owners of B2B service companies, age 40-55, marketing spend $8K+/mo, high deal size

colors:
  bg-primary: "#FEFAEF"
  bg-accent: "#93D1F7"
  bg-accent-soft: "#C4E8FE"
  bg-dark: "#282828"
  bg-card: "#FFFFFF"
  brand-primary: "#198ED5"
  brand-deep: "#0265A1"
  cta: "#FCD84D"
  black: "#000000"
  text-secondary: "#565656"
  muted: "#989898"
  divider: "#EBEBEB"
  white: "#FFFFFF"
  success: "#00B176"
  error: "#FD4E2C"
  warning: "#FCD84D"

typography:
  heading:
    family: "Neutro, sans-serif"
    weight: 700
    note: "Neutro is Latin-only. No Cyrillic glyphs."
  body:
    family: "Inter, sans-serif"
    weight: 400
  body-emphasis:
    family: "Inter, sans-serif"
    weight: 600
  scale:
    h1: { size: "64-80px", weight: 700, lineHeight: 1.0, letterSpacing: "-0.02em" }
    h2: { size: "48-56px", weight: 700, lineHeight: 1.1, letterSpacing: "-0.01em" }
    h3: { size: "32-36px", weight: 700, lineHeight: 1.1 }
    h4: { size: "22-24px", weight: 700, lineHeight: 1.2 }
    body-lg: { size: "20-22px", weight: 400, lineHeight: 1.5 }
    body: { size: "16-18px", weight: 400, lineHeight: 1.6 }
    caption: { size: "13-14px", weight: 400 }
    section-label: { size: "14-16px", weight: 600, transform: "uppercase", letterSpacing: "0.08em" }
    button: { size: "16-18px", weight: 700, transform: "uppercase", letterSpacing: "0.04em" }
    tag: { size: "13-14px", weight: 700, transform: "uppercase" }

spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "32px"
  2xl: "48px"
  3xl: "64px"
  4xl: "96px"
  section: "120px"

radius:
  default: "0px"
  pill: "999px"

borders:
  width: "3px"
  color: "#000000"
  divider: "1px solid #989898"
  divider-light: "1px solid #EBEBEB"

shadows:
  hard: "6px 6px 0px #000000"
  hard-hover: "3px 3px 0px #000000"

buttons:
  primary:
    background: "#FCD84D"
    color: "#000000"
    border: "3px solid #000000"
    radius: "0px"
    shadow: "6px 6px 0 #000000"
    padding: "18px 32px"
    minHeight: "56px"
    font: "Neutro, sans-serif"
    weight: 700
    transform: "uppercase"
  secondary:
    background: "#FFFFFF"
    color: "#000000"
    border: "3px solid #000000"
    radius: "0px"
    shadow: "none"
    padding: "18px 32px"
    minHeight: "56px"
  ghost:
    background: "transparent"
    border: "none"
    color: "#000000"
    hoverDecoration: "underline"
---

# The Catalyst — Design System

## Overview

The Catalyst is a $9,500 marketing due diligence product for B2B service company owners aged 40–55. The design must feel trustworthy, precise, and quietly powerful — never loud or trendy.

**Core principle:** Editorial confidence on warm background. Sharp geometry, disciplined color, premium restraint. Heavy where it matters, quiet everywhere else.

**Brand architecture:** Catalyst is an independent brand identity, endorsed by Wonderflow. Wonderflow appears only in the footer ("Delivered by Wonderflow FZ-LLC"). Catalyst does NOT inherit Wonderflow's visual identity (unicorns, punk elements) — only shares the primary blue `#198ED5`.

---

## Colors

### Backgrounds
- **Cream `#FEFAEF`** — Primary background. 60–70% of the page. This is NOT white — it's a warm cream.
- **Light Blue `#93D1F7`** — 1–2 accent sections per page (proof, testimonials).
- **Pale Blue `#C4E8FE`** — Secondary accent, softer alternative.
- **Dark `#282828`** — 1–2 dark sectors per page maximum (guarantee, hero CTA). Premium accent.
- **White `#FFFFFF`** — Cards on dark or colored backgrounds only.

### Brand & Action
- **Primary Blue `#198ED5`** — Main brand color. Section labels, links, emphasis.
- **Deep Blue `#0265A1`** — Charts, data visualization, deep emphasis.
- **Yellow `#FCD84D`** — **CTA buttons ONLY.** Never use decoratively. Never as a background section color.

### Neutrals
- **Black `#000000`** — Headings and borders.
- **Mid Grey `#565656`** — Secondary body text (default paragraph color).
- **Muted `#989898`** — Dividers, muted UI elements, helper text.
- **Light `#EBEBEB`** — Light dividers only.

### Semantic (states only)
- **Success `#00B176`**, **Error `#FD4E2C`**, **Warning `#FCD84D`** (same as CTA — use contextually, never both in same block).

---

## Typography

### Font Stack
- **Headings, buttons, tags:** Neutro Bold 700 (Latin only — no Cyrillic support)
- **Body text:** Inter Regular 400
- **UI emphasis, labels:** Inter SemiBold 600

### Anti-brutalism Rule ⚠️
Hero at 120px + thick borders on everything = youthful startup / punk aesthetic.
Hero at 64–80px + selective borders = **editorial confidence.** We stay here.

**Maximum hero headline size: 80px.** Do not exceed this.

### Line Height
- Headings: 1.0–1.1 (tight, impactful)
- Body text: 1.5–1.6 (comfortable reading)

---

## Shapes & Radius

**Border-radius: 0px everywhere.** All cards, blocks, buttons, inputs, images — sharp corners.

**Exception:** Pill shape (`border-radius: 999px`) for tags, badges, and chips only.

Do not use "slightly rounded" corners (4px, 8px). This is a signature of the system — commit fully.

---

## Borders

- **Width:** 3px
- **Color:** `#000000`
- **Usage:** Selective, NOT default

### Where to use 3px borders:
- ✅ Hero container
- ✅ CTA button (always)
- ✅ Guarantee block
- ✅ 1–2 key proof/artifact blocks per page

### Where NOT to use:
- ❌ Every feature card, FAQ item, or small card
- ❌ Elements inside an already-bordered container (no nesting)
- ❌ Dividers between sections (use `1px solid #989898` instead)

### Screen limit: maximum 2–3 bordered blocks visible in one viewport.

On dark sectors (`#282828`), invert border color to `#FFFFFF`.

---

## Shadows

- **Hard shadow:** `6px 6px 0px #000000` — **CTA buttons ONLY.** Nothing else.
- **Hover state:** Shadow shifts to `3px 3px 0px #000000` with `transform: translate(3px, 3px)` (press effect).
- **No soft shadows, blur, or glassmorphism** anywhere in the system.
- Regular cards and blocks: separation through background color and spacing only.

---

## Buttons

### Primary CTA
- Background: `#FCD84D` (yellow)
- Text: `#000000`, uppercase, Neutro 700
- Border: `3px solid #000000`
- Shadow: `6px 6px 0 #000000`
- Radius: `0px`
- Padding: `18px 32px`
- Min-height: `56px`
- Hover: shadow → `3px 3px`, translate `(3px, 3px)` — button "presses down"

### Secondary Button
- Background: `#FFFFFF` or transparent
- Text: `#000000`, uppercase, Neutro 700
- Border: `3px solid #000000`
- **No shadow** (shadow is CTA-exclusive)

### Ghost / Text Link
- No border, no background
- Color: `#000000` or `#198ED5`
- Underline on hover

---

## Page Rhythm

The page alternates 3 background types to create visual rhythm:

1. **Cream `#FEFAEF`** — 60–70% of the page. Most content sections.
2. **Blue accent `#93D1F7` / `#C4E8FE`** — 1–2 sections. Proof, testimonials, methodology.
3. **Dark sector `#282828`** — 1–2 sections maximum. Guarantee, final CTA, or hero.

### Dark Sector Rules
- Text: `#FFFFFF` (headings) and `#FEFAEF` (body)
- Section labels: `#93D1F7` (light blue)
- Yellow CTA and blue brand colors keep their original hex values
- Borders: `#FFFFFF` (inverted from black)

### Do not:
- Stack two dark sectors adjacent to each other
- Use dark sector for more than 2 sections on a page
- Put cream text on cream background (obvious but important)

---

## Illustrations

### Allowed
- Isometric / line-art stylized product artifacts
- Visualizations of real deliverables: Leak Map, Funnel Map, Initiative Card, Action Tracker
- Color scheme: blue `#198ED5` + black + accent from palette (cream/yellow)
- Style: technical, information-forward, not decorative

### Forbidden
- Characters, mascots, cartoon people
- Abstract blobs, organic shapes, gradients, 3D spheres
- Stock photos of people in offices
- Emoji-style icons
- Wonderflow unicorns or punk elements

### Limit: 2–3 key illustrations per page (hero, proof section, deliverable preview).

---

## Components

### Tags / Badges
- Font: Neutro 700, 13px, uppercase
- Border: `3px solid #000000`
- Radius: `999px` (pill)
- Padding: `6px 18px`
- Background: `#C4E8FE` or `#93D1F7`

### Section Labels (Eyebrow)
- Font: Inter 600, 14–16px, uppercase
- Letter-spacing: `0.08em`
- Color: `#198ED5`
- No border, no background

### Cards (on cream background)
- Background: cream (`#FEFAEF`) — no separate card background needed
- Separation through spacing only (no border, no shadow)
- If on dark/blue background: white (`#FFFFFF`) card background

### Section Dividers
- `1px solid #989898` between sections on cream
- `1px solid #EBEBEB` between sections on dark

---

## Guidelines — Do's and Don'ts

### DO:
- Use cream `#FEFAEF` as the primary background — NOT white
- Keep borders selective (2–3 per viewport)
- Keep hero headline between 64–80px
- Use yellow exclusively for CTA buttons
- Alternate section backgrounds for rhythm
- Use Inter for all body text and UI labels
- Use Neutro for all headings, buttons, and tags (Latin text only)

### DON'T:
- Use rounded corners anywhere except pill tags
- Add gradients — everything is flat fill
- Use glassmorphism, soft shadows, or blur effects
- Put hard shadows on cards — shadow is CTA-only
- Put borders on every card — max 2–3 per screen
- Make hero text larger than 80px
- Use more than 1 accent color per block (except CTA)
- Use Wonderflow mascots, unicorns, or punk aesthetics
- Add a dark mode toggle for v1
- Use stock photography of any kind
