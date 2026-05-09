---
name: Shobuj Bazar
colors:
  surface: '#faf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#faf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f1'
  surface-container: '#efeeeb'
  surface-container-high: '#e9e8e5'
  surface-container-highest: '#e3e2e0'
  on-surface: '#1a1c1a'
  on-surface-variant: '#42493e'
  inverse-surface: '#2f312f'
  inverse-on-surface: '#f2f1ee'
  outline: '#72796e'
  outline-variant: '#c2c9bb'
  surface-tint: '#3b6934'
  primary: '#154212'
  on-primary: '#ffffff'
  primary-container: '#2d5a27'
  on-primary-container: '#9dd090'
  inverse-primary: '#a1d494'
  secondary: '#605f54'
  on-secondary: '#ffffff'
  secondary-container: '#e3e0d2'
  on-secondary-container: '#656358'
  tertiary: '#4e332a'
  on-tertiary: '#ffffff'
  tertiary-container: '#674940'
  on-tertiary-container: '#e3baae'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bcf0ae'
  primary-fixed-dim: '#a1d494'
  on-primary-fixed: '#002201'
  on-primary-fixed-variant: '#23501e'
  secondary-fixed: '#e6e2d5'
  secondary-fixed-dim: '#cac7b9'
  on-secondary-fixed: '#1d1c14'
  on-secondary-fixed-variant: '#48473d'
  tertiary-fixed: '#ffdbd0'
  tertiary-fixed-dim: '#e7bdb1'
  on-tertiary-fixed: '#2c160e'
  on-tertiary-fixed-variant: '#5d4037'
  background: '#faf9f6'
  on-background: '#1a1c1a'
  surface-variant: '#e3e2e0'
typography:
  headline-xl:
    fontFamily: Hind Siliguri
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 52px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hind Siliguri
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Hind Siliguri
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
  headline-md:
    fontFamily: Hind Siliguri
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: Hind Siliguri
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hind Siliguri
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

The design system for Shobuj Bazar is built on the philosophy of "Ethical Elegance." It serves the discerning urban Bangladeshi family by bridging the gap between traditional organic markets and a high-end digital lifestyle. The visual language is a blend of **Minimalism** and **Modern Glassmorphism**, emphasizing transparency (trust) and freshness (quality).

The atmosphere should feel like a serene morning in a high-end garden conservatory. We utilize floating leaf patterns as organic motifs that break the rigid grid, adding a sense of movement and natural growth. The interface must remain quiet and sophisticated, allowing the vibrant colors of fresh produce to act as the primary visual hero.

## Colors

The palette is rooted in the natural landscapes of Bangladesh, refined for a premium digital context.

- **Primary (Forest Green):** A deep, sophisticated green used for primary actions, branding, and high-level navigation. It represents health and vitality.
- **Secondary (Cream):** A warm, soft cream used for container backgrounds and to reduce the starkness of pure white, providing a tactile, "paper-like" feel.
- **Tertiary (Earthy Brown):** Used sparingly for typography and decorative accents to provide grounding and a connection to the soil.
- **Warm White:** The base background color, ensuring the interface feels airy and spacious.
- **Glass Accents:** Translucent white layers with high blur values are used for overlay elements to maintain a modern, high-end aesthetic.

## Typography

This design system prioritizes Bengali readability using **Hind Siliguri** for all primary text. The font's clean terminals and balanced x-height ensure that even complex Bengali glyphs remain legible at smaller sizes. 

For English labels, numbers, and technical metadata, **Plus Jakarta Sans** is used to provide a modern, geometric contrast that complements the organic curves of the Bengali script. Headlines should utilize tighter tracking and generous line heights to maintain a premium editorial feel.

## Layout & Spacing

The layout follows a **Fixed Grid** model on desktop to maintain an "exclusive boutique" feel, while transitioning to a fluid model on mobile devices. 

- **Desktop (1280px+):** 12-column grid with 24px gutters and 64px outer margins.
- **Tablet (768px - 1279px):** 8-column grid with 20px gutters and 32px margins.
- **Mobile (Up to 767px):** 4-column grid with 16px gutters and 16px margins.

Spacing should favor "Large" and "Extra Large" increments (32px, 48px, 64px) between sections to prevent the UI from feeling cluttered, emphasizing the "Premium Marketplace" positioning.

## Elevation & Depth

Depth is achieved through **Glassmorphism** and **Ambient Shadows** rather than traditional heavy dropshadows. 

1.  **Level 0 (Base):** Warm White or Cream solid surfaces.
2.  **Level 1 (Cards):** Modern glassmorphism panels. These feature a `backdrop-filter: blur(12px)`, a `1px` stroke in `rgba(255, 255, 255, 0.4)`, and a subtle 20% opacity tint of the primary green.
3.  **Level 2 (Floating/Modals):** Elements use extra-diffused shadows with a slight brown tint (`rgba(93, 64, 55, 0.08)`) to mimic natural sunlight casting shadows on earth.

Layering leaf patterns behind Level 1 glass panels creates a parallax depth effect that feels fresh and immersive.

## Shapes

The design system utilizes **Rounded** geometry (0.5rem base) to evoke a sense of friendliness and organic growth. 

- **Standard Components:** 8px (0.5rem) radius for buttons and input fields.
- **Product Cards:** 16px (1rem) radius to feel substantial and high-end.
- **Promotional Banners:** 24px (1.5rem) radius for a softer, more inviting appearance.
- **Decorative Leaf Patterns:** These are organic, non-geometric SVGs that should always be clipped or masked within rounded containers.

## Components

- **Buttons:** Primary buttons use a solid Forest Green with white Hind Siliguri text. Secondary buttons use a "Ghost" style with a 1.5px border in Earthy Brown.
- **Glass Cards:** The signature component. Used for product listings and category highlights. They must include a subtle inner glow on the top-left edge to simulate light hitting glass.
- **Floating Leaf Patterns:** Decorative SVG elements placed at the corners of sections. They should have a slight rotation (5-15 degrees) and use a varied opacity (20%-40%) to create rhythm.
- **Input Fields:** Minimalist design with a bottom-border only or a very light Cream fill. Focus states should transition the border to Forest Green with a subtle outer glow.
- **Chips/Badges:** Used for "Organic," "Fresh Today," or "Bestseller." These use a semi-transparent Forest Green background with dark green text, featuring a Pill-shape (rounded-full).
- **Elegant Bengali Lists:** Custom iconography for bullet points using small leaf icons or minimalist earthy-toned dots.