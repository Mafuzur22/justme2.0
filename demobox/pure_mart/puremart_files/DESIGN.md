---
name: PureMart
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#c1c8c1'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8b938c'
  outline-variant: '#414843'
  surface-tint: '#a8d0b6'
  primary: '#a8d0b6'
  on-primary: '#133725'
  primary-container: '#062c1b'
  on-primary-container: '#70957e'
  inverse-primary: '#426651'
  secondary: '#e9c349'
  on-secondary: '#3c2f00'
  secondary-container: '#af8d11'
  on-secondary-container: '#342800'
  tertiary: '#bdce89'
  on-tertiary: '#283501'
  tertiary-container: '#1f2a00'
  on-tertiary-container: '#849456'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c4ecd1'
  primary-fixed-dim: '#a8d0b6'
  on-primary-fixed: '#002112'
  on-primary-fixed-variant: '#2a4e3a'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#d9eaa3'
  tertiary-fixed-dim: '#bdce89'
  on-tertiary-fixed: '#161f00'
  on-tertiary-fixed-variant: '#3e4c16'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
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
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  section-gap: 80px
---

## Brand & Style

This design system centers on a "Cradle-to-Table" luxury narrative, blending the organic purity of Whole Foods with the obsessive precision of Apple. The brand personality is one of quiet confidence, environmental stewardship, and uncompromising quality. The UI must feel like a high-end editorial gallery rather than a standard marketplace.

The design style is a sophisticated blend of **Minimalism** and **Glassmorphism**. By using heavy whitespace (or "dark-space"), cinematic photography of produce, and translucent surfaces, the design system creates a sense of depth and exclusivity. For the affluent Bangladeshi market, the aesthetic avoids cluttered "superstore" visuals in favor of a curated, boutique experience. Motion should be slow and intentional, mimicking the unhurried pace of luxury.

## Colors

The palette is rooted in the "Midnight Garden" concept. The primary color, **Deep Forest Green (#062C1B)**, provides an organic yet regal foundation. This is contrasted against **Midnight Black (#0A0A0A)** to ensure a cinematic, high-contrast background that makes product photography pop.

**Gold (#D4AF37)** is used sparingly for primary actions, badges of authenticity, and premium membership indicators. **Soft Sage (#8A9A5B)** acts as a functional secondary accent for success states, labels, and softer UI elements. Typography should primarily use a "Paper White" (#F5F5F5) for maximum legibility against the dark backgrounds, while secondary text should utilize a muted "Stone" (#A0A0A0).

## Typography

Typography serves as the primary bridge between the English and Bengali languages. **Playfair Display** provides an elegant, editorial feel for headlines, evoking the sophistication of luxury magazines. For the Bengali script, use a serif alternative with high-contrast strokes that mirror Playfair's elegance to maintain visual harmony.

**Inter** is the workhorse for the UI, chosen for its exceptional legibility in both languages at small sizes. The typographic hierarchy is strictly enforced: large, high-contrast headings for storytelling, and clean, generous line-heights for body text to ensure a comfortable reading experience for the affluent target audience. Labels and UI metadata should utilize increased letter-spacing and uppercase styling where appropriate to denote "premium" status.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** system for desktop to maintain a curated, "framed" look, and a fluid layout for mobile. A 12-column grid is used for desktop (1280px max-width), while a 4-column grid is utilized for mobile devices.

Spacing is generous to communicate luxury—this design system prioritizes "breathing room" over information density. Section gaps are intentionally large (80px+) to allow the eye to focus on one product category or brand story at a time. Gutters are kept wide (24px) to prevent the high-contrast elements from feeling cramped. Padding within cards and containers should follow an 8px rhythmic scale, typically starting at 24px for standard containers.

## Elevation & Depth

In this dark-mode-first system, depth is conveyed through **Glassmorphism** and **Tonal Layers** rather than heavy shadows. 

1.  **Base Layer:** Midnight Black (#0A0A0A) acts as the canvas.
2.  **Surface Layer:** Deep Forest Green (#062C1B) at low opacity (60-80%) with a backdrop blur (20px-40px) is used for cards and navigation bars.
3.  **Accent Layer:** Subtle 1px inner borders in Soft Sage or Gold (at 10-15% opacity) provide "edge-lighting," making elements appear as if they are etched glass.

Shadows, when used, are extra-diffused and tinted with the primary green to prevent a "muddy" appearance. This creates a luminous, atmospheric glow that feels affluent and modern.

## Shapes

The shape language is defined by **Rounded (0.5rem base)** geometry. This level of roundedness balances the "organic" nature of the products with the "precision" of a premium tech-driven brand. 

-   **Standard Elements:** Buttons and input fields use a 0.5rem (8px) radius.
-   **Containers:** Product cards and modals use 1rem (16px) to feel substantial and soft.
-   **Feature Elements:** High-profile promotions or "Add to Cart" buttons may use 1.5rem (24px) or full pill-shapes to draw the eye. 

Icons should follow a medium-stroke weight with slightly rounded terminals to match the font weight of Inter.

## Components

### Buttons
Primary buttons are solid Forest Green with Gold text or solid Gold with Black text for high-importance actions like "Checkout." Secondary buttons use a "Ghost" style with a 1px Gold or Sage border.

### Product Cards
Cards feature a "Glass" background with a subtle inner border. The product image is the hero, often breaking the top boundary slightly to create 3D depth. Titles are in Playfair Display (18px-20px) with prices in Inter.

### Input Fields
Inputs are minimal, featuring only a bottom border in Soft Sage that transitions to Gold on focus. Placeholder text is "Stone" grey, and error states utilize a muted coral rather than a bright red to maintain the premium feel.

### Chips & Tags
Used for "Organic," "Local," or "Premium" certifications. These are small, pill-shaped elements with low-opacity background fills of Sage or Forest Green and high-contrast text.

### Language Switcher
A prominent, elegant toggle (English | বাংলা) located in the utility nav, utilizing Playfair Display for the Bengali script to signify respect for the local heritage.

### Luxury Cart
The cart is a slide-out "drawer" using a high-blur glass effect, treating the items like a curated list of investments rather than a simple shopping list.