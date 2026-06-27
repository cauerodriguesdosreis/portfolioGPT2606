---
name: Obsidian Flux
colors:
  surface: '#121414'
  surface-dim: '#121414'
  surface-bright: '#38393a'
  surface-container-lowest: '#0c0f0f'
  surface-container-low: '#1a1c1c'
  surface-container: '#1e2020'
  surface-container-high: '#282a2b'
  surface-container-highest: '#333535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#b9cacb'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#2f3131'
  outline: '#849495'
  outline-variant: '#3b494b'
  surface-tint: '#00dbe9'
  primary: '#dbfcff'
  on-primary: '#00363a'
  primary-container: '#00f0ff'
  on-primary-container: '#006970'
  inverse-primary: '#006970'
  secondary: '#d0bcff'
  on-secondary: '#3c0091'
  secondary-container: '#571bc1'
  on-secondary-container: '#c4abff'
  tertiary: '#f9f5f5'
  on-tertiary: '#313030'
  tertiary-container: '#dcd9d8'
  on-tertiary-container: '#605e5e'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#7df4ff'
  primary-fixed-dim: '#00dbe9'
  on-primary-fixed: '#002022'
  on-primary-fixed-variant: '#004f54'
  secondary-fixed: '#e9ddff'
  secondary-fixed-dim: '#d0bcff'
  on-secondary-fixed: '#23005c'
  on-secondary-fixed-variant: '#5516be'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c9c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474646'
  background: '#121414'
  on-background: '#e2e2e2'
  surface-variant: '#333535'
typography:
  display:
    fontFamily: Geist
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Geist
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1200px
  gutter: 24px
---

## Brand & Style

The design system is engineered for high-end developer portfolios and technical showcases. It prioritizes a **Sophisticated Minimalist** aesthetic, merging the precision of developer tools like Linear with the premium editorial feel of Stripe. 

The brand personality is high-competence, visionary, and precise. It utilizes a "Dark Mode First" philosophy to evoke a sense of focus and depth. Visual interest is generated not through heavy imagery, but through technical craft: micro-interactions, subtle glowing edges, and a rigorous adherence to a geometric grid. The emotional response should be one of trust in the developer's technical mastery and attention to detail.

## Colors

This design system utilizes a deep, monochromatic base to allow content and accents to recede and emerge with high intent.

- **Background & Surface:** Absolute black (`#000000`) is the primary canvas. Elevated surfaces use a graphite gradient or solid `#0A0A0A` to create a "layered" look.
- **Accents:** Vibrant Cyan serves as the primary "action" color for links and success states. Deep Purple provides a sophisticated secondary accent, often used in gradients to soften the clinical feel of the cyan.
- **Borders:** Subtle, low-contrast borders (`#1F1F1F`) are essential for defining sections without adding visual noise.
- **Gradients:** Use linear gradients from Purple to Cyan at 45-degree angles for high-impact headers or primary buttons.

## Typography

Typography is the cornerstone of this system. It uses **Geist** for its technical, sharp geometric qualities in headings, and **Inter** for its unparalleled legibility in body copy. 

- **Hierarchy:** High contrast in weight is encouraged. Pair `display` titles with `body-md` descriptions for a premium, spacious feel.
- **Monospace:** **JetBrains Mono** is reserved for metadata, labels, and code snippets, grounding the design in a developer-centric context.
- **Rhythm:** Line heights are kept generous (1.6) for body text to ensure readability against the dark background, while headlines are tight (1.1 - 1.2) to feel impactful.

## Layout & Spacing

The layout follows a strict **8px grid system**. This mathematical precision ensures a harmonious alignment across all components.

- **Bento Grid:** For portfolios and stats, use a multi-column grid where items span varying column widths (e.g., 1/3, 2/3, or full width). Every "box" in the bento grid should have equal internal padding (`24px`).
- **Margins:** Desktop layouts should maintain a maximum container width of `1200px` with generous `80px` vertical section spacing to allow the design to "breathe."
- **Mobile:** Reflow 3-column bento grids into a single vertical stack. Reduce section spacing to `48px` to maintain momentum.

## Elevation & Depth

Depth is conveyed through **Tonal Layering** and **Glassmorphism**, avoiding traditional heavy shadows.

- **Surface Layers:**
  - Base: `#000000` (Background)
  - Level 1: `#0A0A0A` (Cards, Bento items)
  - Level 2: `#111111` (Hover states, Modals)
- **Glassmorphism:** Navigation bars and floating menus should use a background blur (12px to 20px) with a semi-transparent surface (`rgba(0,0,0,0.7)`).
- **Subtle Glows:** Use "Inner Glows" (1px white/cyan borders with 0.1 opacity) on top-level cards to simulate a light source from above.
- **Outer Shadows:** If used, shadows must be extremely soft, large-radius, and tinted with the primary Cyan or Purple at 5-10% opacity.

## Shapes

The shape language combines the structural rigidity of the grid with organic, large-radius corners.

- **Primary Radius:** Use `0.5rem` (8px) for small components like buttons and inputs.
- **Container Radius:** Use `1.5rem` (24px) for cards, bento boxes, and main sections to create a high-end, friendly feel that offsets the technicality of the dark theme.
- **Pills:** Use full rounded corners for tags and status indicators to differentiate them from functional buttons.

## Components

- **Buttons:** 
  - *Primary:* Solid Cyan to Purple gradient text on a black background with a gradient border. 
  - *Secondary:* Ghost style with `#1F1F1F` borders. 
  - *Interaction:* Subtle scale-down effect (0.98) on click.
- **Cards (Bento Box):** 
  - Background: `#0A0A0A`. 
  - Border: 1px solid `#1F1F1F`. 
  - Hover: Border changes to `#333333` and a faint top-left cyan glow appears.
- **Chips/Tags:** Small, monospace font, using `rgba(0, 240, 255, 0.1)` background with Cyan text.
- **Input Fields:** 
  - Dark background, 1px border. 
  - On focus: Border glows Cyan with a 4px outer blur.
- **Progress Bars:** Use high-contrast gradients (Purple to Cyan) against a dark grey track.
- **Code Blocks:** Syntax highlighting using a customized "Night Owl" or "One Dark" theme that complements the Cyan/Purple accent palette.