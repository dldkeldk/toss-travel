---
name: Clarity & Trust
colors:
  surface: '#f8f9ff'
  surface-dim: '#d5dae7'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e9eefb'
  surface-container-high: '#e3e8f5'
  surface-container-highest: '#dde3ef'
  on-surface: '#161c25'
  on-surface-variant: '#424656'
  inverse-surface: '#2b313a'
  inverse-on-surface: '#ebf1fe'
  outline: '#737687'
  outline-variant: '#c2c6d8'
  surface-tint: '#0054d8'
  primary: '#004ecb'
  on-primary: '#ffffff'
  primary-container: '#0064ff'
  on-primary-container: '#f5f5ff'
  inverse-primary: '#b3c5ff'
  secondary: '#5c5f61'
  on-secondary: '#ffffff'
  secondary-container: '#e0e3e5'
  on-secondary-container: '#626567'
  tertiary: '#a03200'
  on-tertiary: '#ffffff'
  tertiary-container: '#ca4101'
  on-tertiary-container: '#fff4f0'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b3c5ff'
  on-primary-fixed: '#00174a'
  on-primary-fixed-variant: '#003ea6'
  secondary-fixed: '#e0e3e5'
  secondary-fixed-dim: '#c4c7c9'
  on-secondary-fixed: '#191c1e'
  on-secondary-fixed-variant: '#444749'
  tertiary-fixed: '#ffdbd0'
  tertiary-fixed-dim: '#ffb59c'
  on-tertiary-fixed: '#390c00'
  on-tertiary-fixed-variant: '#832700'
  background: '#f8f9ff'
  on-background: '#161c25'
  surface-variant: '#dde3ef'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Manrope
    fontSize: 22px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 17px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: '0'
  label-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.02em
  button:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: -0.01em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  container-margin: 20px
  gutter: 12px
---

## Brand & Style

This design system is anchored in a philosophy of "Radical Simplicity." It prioritizes high-velocity task completion through a reductionist aesthetic that removes all non-essential visual noise. The brand personality is approachable yet authoritative, combining the friendly nature of consumer-grade apps with the reliability expected of financial services.

The design movement is **Minimalism** infused with **Modern Corporate** sensibilities. By utilizing generous whitespace (negative space), the interface directs focus toward a single primary action per screen. The emotional response is intended to be one of "financial zen"—calm, organized, and transparent.

## Colors

The palette is dominated by a high-contrast pairing of pure white and a vibrant, "Electric Blue" primary. 

- **Primary Blue (#0064ff):** Reserved for primary call-to-actions, active states, and essential brand moments.
- **Surface Neutrals:** We use a specific scale of cool greys. `#f2f4f6` is the standard background for grouping elements (secondary), while `#ffffff` remains the primary canvas.
- **Text & Content:** Pure black is avoided to reduce eye strain; instead, `#191f28` is used for high-contrast headlines to maintain a premium feel.
- **Semantic Colors:** Success and Error states are saturated and bright, ensuring they are instantly recognizable against the clean white background.

## Typography

The system utilizes **Manrope** for headlines to provide a modern, slightly geometric character that feels friendly. **Inter** is used for body copy and UI labels due to its exceptional legibility at small sizes and its neutral, systematic tone.

Text hierarchy is enforced through weight rather than just size. Headlines are bold and tight, while body text is given ample line-height to improve readability across long lists or financial statements.

## Layout & Spacing

This design system uses a **Fluid Grid** model with a focus on vertical rhythm. The spacing scale is based on a 4px baseline, but defaults to 16px (md) and 24px (lg) for most component spacing to ensure an "airy" feel.

- **Margins:** Standard mobile views use a 20px side margin to provide content with breathing room.
- **Sectioning:** Vertical gaps between logical groups of content (cards) should be 12px to 16px.
- **Padding:** Internal card padding is consistently 24px to emphasize the "clean and spacious" brand pillars.

## Elevation & Depth

Hierarchy is established primarily through **Tonal Layers** and **Ambient Shadows**. 

1.  **Level 0 (Base):** The main background, usually `#ffffff`.
2.  **Level 1 (Secondary):** Large containers or background sections using `#f2f4f6` without shadows.
3.  **Level 2 (Raised):** Cards and primary interactive elements. These use extremely soft, diffused shadows: `0px 4px 20px rgba(0, 0, 0, 0.04)`. The shadow should be barely perceptible, feeling like a natural lift rather than a floating object.

Avoid heavy borders. Depth is created by the subtle contrast between white surfaces and the light grey background.

## Shapes

The shape language is defined by large, "squircle"-like radii. This softness is key to the "friendly" aspect of the design system.

- **Buttons & Cards:** Use a 16px to 24px radius (`rounded-lg` or `rounded-xl`).
- **Input Fields:** Use a 12px radius to maintain a distinct but cohesive look with cards.
- **Small Elements:** Chips and badges use a fully rounded (pill) shape to distinguish them from actionable containers.

## Components

**Buttons**
- **Primary:** Full-width, #0064ff background, white text, 18px height padding, 20px border-radius. No gradients.
- **Secondary:** Light grey background (#f2f4f6) with primary blue text. Flat, no shadow.

**Cards**
- White background, 24px internal padding, 24px corner radius. Used for grouping related financial data or menu options.

**Input Fields**
- Borderless by default, using a light grey (#f9fafb) fill. On focus, the background remains the same but a 2px primary blue stroke is added.

**Lists**
- "Clean Lists" with no horizontal dividers. Separated by whitespace or very subtle 1px lines that do not touch the edges of the screen.

**Icons**
- Linear, 24px bounding box, 2px stroke width. Use rounded caps and joins to match the UI's radius.

**Bottom Sheets**
- Frequently used for secondary actions. Use a large 28px top corner radius and a subtle "grabber" bar at the top.