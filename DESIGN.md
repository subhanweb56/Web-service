---
name: Nocturnal Elegance
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#d0c5b5'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#998f81'
  outline-variant: '#4d463a'
  surface-tint: '#e2c284'
  primary: '#f3d393'
  on-primary: '#402d00'
  primary-container: '#d6b77a'
  on-primary-container: '#5d4715'
  inverse-primary: '#735b27'
  secondary: '#c9c6c5'
  on-secondary: '#313030'
  secondary-container: '#4a4949'
  on-secondary-container: '#bab8b7'
  tertiary: '#ebd4a1'
  on-tertiary: '#3c2f09'
  tertiary-container: '#ceb987'
  on-tertiary-container: '#584921'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdea0'
  primary-fixed-dim: '#e2c284'
  on-primary-fixed: '#261a00'
  on-primary-fixed-variant: '#594311'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c9c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474646'
  tertiary-fixed: '#f8e0ac'
  tertiary-fixed-dim: '#dac492'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#54451e'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  caption:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  margin-mobile: 24px
  gutter-mobile: 16px
  safe-area-bottom: 32px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  stack-xl: 64px
---

## Brand & Style
The design system embodies a premium, high-end editorial aesthetic tailored for a luxury hospitality experience. The target audience is the discerning traveler who values discretion, sophistication, and seamless service. 

The visual style is a fusion of **Glassmorphism** and **Minimalism**, set against a deep, immersive dark mode. It utilizes translucent layers to create a sense of physical depth and atmospheric perspective, mimicking the play of light in a dim, well-lit hotel lounge. The emotional response should be one of calm, exclusivity, and effortless prestige.

## Colors
The palette is rooted in deep obsidian and charcoal tones to establish a "midnight" luxury feel. 

- **Primary & Tertiary (Champagne/Gold):** Used sparingly for high-intent actions, active states, and premium highlights. 
- **Secondary & Neutral:** Define the structural foundation, creating subtle separation between the background and container elements.
- **Glass Surfaces:** Employed for floating headers, navigation bars, and over-image cards to maintain a sense of lightness and depth.
- **Soft Ivory:** All typography should avoid pure white (#FFFFFF) in favor of soft ivory to reduce eye strain and enhance the premium feel.

## Typography
The typographic hierarchy creates an editorial rhythm. **Playfair Display** provides the "voice" of the brand—authoritative, classic, and elegant. It is reserved for headings and display moments. **Manrope** handles the "utility" of the app—ensuring high legibility for booking details, descriptions, and UI controls. 

Use uppercase styling for labels and small buttons to inject a sense of structured, architectural refinement.

## Layout & Spacing
The layout follows an Android-native fluid grid with generous margins to evoke a sense of space and luxury. 

- **Vertical Rhythm:** Use larger gaps (`stack-xl`) between major sections to prevent a cluttered "utility" feel.
- **Safe Areas:** Adhere strictly to the Android system bars. The bottom navigation bar should be elevated with a glass effect, ensuring content scrolls behind it.
- **Photography:** Use full-bleed or wide-margin cinematic imagery. Photos should have a subtle dark gradient overlay at the bottom to ensure white/ivory text remains legible.

## Elevation & Depth
Hierarchy is established through **Tonal Layering** and **Glassmorphism** rather than traditional heavy shadows.

1. **Level 0 (Base):** Deep Charcoal (#0B0B0B).
2. **Level 1 (Cards):** Secondary Dark Grey (#151515).
3. **Level 2 (Overlays):** Dark Glass (7% White opacity) with a 20px backdrop blur and a 0.5px white border at 10% opacity to define the edge.
4. **Shadows:** When used for floating buttons, shadows should be ultra-diffused: `0 20px 40px rgba(0,0,0,0.5)`.

## Shapes
The shape language is sophisticated and soft. Standard UI elements (inputs, small buttons) use a 0.5rem (8px) radius. However, primary containers, luxury cards, and modal sheets utilize a much larger radius (24px to 32px) to create a friendly yet modern "nested" appearance. 

Buttons should remain slightly more structured (8px) to maintain a professional edge, while image containers should favor the larger 24px radius.

## Components
- **Primary Button:** Solid Champagne (#D6B77A) with Dark Charcoal text. High contrast, 8px radius.
- **Glass Card:** Used for room details or "quick actions." 7% white fill, 20px backdrop blur, 24px corner radius.
- **Input Fields:** Bottom-border only or very subtle #151515 fills. Focused state transitions the border to Champagne.
- **Bottom Navigation:** A floating glass bar with 24px radius. Active icons use the Gold/Champagne color with a subtle outer glow.
- **Chips:** Low-contrast dark grey backgrounds with ivory text, used for amenities (e.g., "WiFi", "Pool").
- **Lists:** High-density list items are avoided. Every list item should have ample padding (20px vertical) and a subtle separator line `rgba(255,255,255,0.05)`.
- **Carousel Indicators:** Slim, champagne-colored pill-shaped dots for high-end photography galleries.