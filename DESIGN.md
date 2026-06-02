---
name: Hype-Drop
description: Ultra-minimalist luxury streetwear storefront
colors:
  primary: "#121212"
  neutral-bg: "#ffffff"
  accent-gray: "#f3f3f3"
  text-light: "#ffffff"
typography:
  display:
    fontFamily: "Helvetica Neue, Inter, sans-serif"
    fontSize: "clamp(2rem, 5vw, 4.5rem)"
    fontWeight: 900
    lineHeight: 1.1
    letterSpacing: "-0.02em"
  body:
    fontFamily: "Helvetica Neue, Inter, sans-serif"
    fontSize: "1.6rem"
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: "0.06rem"
rounded:
  none: "0px"
spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "48px"
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.neutral-bg}"
    rounded: "{rounded.none}"
    padding: "16px 48px"
  button-primary-hover:
    backgroundColor: "{colors.neutral-bg}"
    textColor: "{colors.primary}"
  input-field:
    backgroundColor: "{colors.neutral-bg}"
    textColor: "{colors.primary}"
    rounded: "{rounded.none}"
    padding: "12px 16px"
---

# Design System: Hype-Drop

## 1. Overview

**Creative North Star: "Swiss Editorial Monolith"**

The Hype-Drop design system is built on Swiss-style modernist typography and raw, uncompromising editorial restraint. The canvas relies entirely on contrast, typography, and precise spatial layout rather than decorative gradients, shadows, or rounded elements. It is clean, bold, cold, and highly confident—positioning the storefront as a high-end streetwear editorial catalog.

### Key Characteristics:
- **Pure Monochromatic Palette:** Dominated by pure white (#FFFFFF) and solid black (#121212), with light-gray fills (#F3F3F3) used strictly for UI backgrounds.
- **Zero Radii Geometry:** Every input, button, card, image, and popup has a sharp 0px border-radius.
- **Flat Elevation:** No drop-shadows are used. Surfaces are layered strictly through solid borders and high contrast.

## 2. Colors

The color palette is strictly restrained to create an expensive, editorial feeling.

### Primary
- **Matte Onyx** (#121212): Used for primary text, buttons, borders, and active/focus states. It acts as the anchor color.

### Neutral
- **Pure Canvas White** (#FFFFFF): The dominant page background, presenting a clean, museum-like canvas for editorial photography.
- **Technical Gray** (#F3F3F3): Used for minor background fills, secondary buttons, and section dividers to establish visual grids.

### Named Rules
**The 10% Contrast Rule.** Saturated colors are entirely banned. Pure black must carry at least 90% of the text and active state fills. Gray is reserved strictly for minor containers and borders.

## 3. Typography

**Display Font:** Helvetica Neue (with fallbacks: Inter, Arial, sans-serif)
**Body Font:** Helvetica Neue (with fallbacks: Inter, Arial, sans-serif)

The typeface selection uses a single geometric sans-serif family, achieving hierarchy strictly through extreme weight variations and tracked all-caps sizing contrast.

### Hierarchy
- **Display:** (Bold 900, clamp(2rem, 5vw, 4.5rem), line-height 1.1, letter-spacing -0.02em): Used for large hero headings and drop headlines.
- **Headline:** (Bold 900, 2.4rem, line-height 1.2): Used for section titles.
- **Title:** (Bold 900, 1.8rem, line-height 1.2, uppercase): Used for navigation items, labels, and product titles.
- **Body:** (Regular 400, 1.6rem, line-height 1.6): Used for product descriptions and editorial copy. Cap line length at 70ch.
- **Label:** (Bold 900, 1.2rem, letter-spacing 0.05em, uppercase): Used for tags, small details, and badges.

## 4. Elevation

The storefront is entirely flat. Depth is conveyed strictly through spatial layout and crisp, solid borders.

### Named Rules
**The Flat-By-Default Rule.** Shadows, blurs, and glassmorphism are strictly prohibited. Visual depth is established by solid black boundaries and flat background changes.

## 5. Components

### Buttons
- **Shape:** Sharp corners (0px border-radius)
- **Primary:** Solid Matte Onyx (#121212) fill, white text (#FFFFFF), bold uppercase type.
- **Hover / Focus:** Invert style on hover (Solid white background, matte onyx text, solid black 1px border).

### Cards / Containers
- **Corner Style:** Sharp (0px border-radius)
- **Background:** Technical Gray (#F3F3F3) or Pure White (#FFFFFF)
- **Border:** Solid 1px Matte Onyx (#121212) border or border-less. No shadows.

### Inputs / Fields
- **Style:** Solid 1px Matte Onyx (#121212) border, pure white background, sharp corners.
- **Focus:** Bold 2px Matte Onyx border outline on focus.

## 6. Do's and Don'ts

### Do:
- **Do** use exact 0px border-radius globally on every interface element.
- **Do** use high typographic weight contrast (e.g. Extra Bold Display next to Light Body).
- **Do** use solid black 1px borders to separate content blocks instead of shadows.

### Don't:
- **Don't** use any rounded corners (e.g., border-radius greater than 0px).
- **Don't** use drop-shadows or gradients on buttons, cards, images, or sections.
- **Don't** use marketing buzzwords like 'unleash', 'supercharge', or 'leverage'.
