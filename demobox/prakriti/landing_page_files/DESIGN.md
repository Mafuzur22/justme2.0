---
name: Prakriti
colors:
  surface: '#fef9f1'
  surface-dim: '#ded9d2'
  surface-bright: '#fef9f1'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f8f3eb'
  surface-container: '#f3ede5'
  surface-container-high: '#ede7e0'
  surface-container-highest: '#e7e2da'
  on-surface: '#1d1b17'
  on-surface-variant: '#434843'
  inverse-surface: '#32302b'
  inverse-on-surface: '#f5f0e8'
  outline: '#747872'
  outline-variant: '#c3c8c1'
  surface-tint: '#536254'
  primary: '#455547'
  on-primary: '#ffffff'
  primary-container: '#5d6d5e'
  on-primary-container: '#ddeedb'
  inverse-primary: '#bacbb9'
  secondary: '#924b26'
  on-secondary: '#ffffff'
  secondary-container: '#fea276'
  on-secondary-container: '#783613'
  tertiary: '#52514b'
  on-tertiary: '#ffffff'
  tertiary-container: '#6a6963'
  on-tertiary-container: '#ece9e1'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e7d5'
  primary-fixed-dim: '#bacbb9'
  on-primary-fixed: '#111f13'
  on-primary-fixed-variant: '#3b4a3d'
  secondary-fixed: '#ffdbcc'
  secondary-fixed-dim: '#ffb694'
  on-secondary-fixed: '#351000'
  on-secondary-fixed-variant: '#753411'
  tertiary-fixed: '#e5e2da'
  tertiary-fixed-dim: '#c9c6bf'
  on-tertiary-fixed: '#1c1c17'
  on-tertiary-fixed-variant: '#474741'
  background: '#fef9f1'
  on-background: '#1d1b17'
  surface-variant: '#e7e2da'
typography:
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
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
  label-sm:
    fontFamily: Manrope
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
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
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style

This design system embodies the intersection of Scandinavian functionalism and Bengali heritage. It is designed for a conscious, premium audience seeking tranquility and authenticity in their lifestyle choices. The aesthetic is "Organic Zen"—a philosophy that prioritizes breathability, tactile warmth, and cultural resonance.

The visual style is a hybrid of **Minimalism** and **Tactile Skeuomorphism**. While the layout remains strictly minimal with generous whitespace, the surfaces utilize subtle "linen" textures and soft depth to mimic natural materials. Every interaction should feel intentional and calm, evoking the sensory experience of a high-end boutique tucked away in a quiet, sun-drenched corner.

## Colors

The palette is rooted in the earth, using low-saturation tones to maintain a premium, quiet feel.

*   **Primary (Muted Sage):** Used for navigation, primary actions, and success states. It represents growth and balance.
*   **Secondary (Clay Orange):** Reserved for subtle accents, CTA highlights, and special indicators. It provides a warm, artisanal contrast.
*   **Background (Creamy Beige):** The canvas of the system. Never use pure white (#FFFFFF); instead, use this warm neutral to reduce eye strain and feel more "organic."
*   **Text (Charcoal Olive):** A deep, off-black used for readability without the harshness of true black.

Linen-like textures should be applied as a subtle noise overlay (2-3% opacity) on the primary background color to give surfaces a physical quality.

## Typography

The typography strategy balances the editorial elegance of **Playfair Display** with the functional clarity of **Manrope**.

*   **Headings:** Use the high-contrast serif for all primary storytelling and product names. This font scales beautifully and supports the sophisticated character required for both Latin and Bengali-inspired aesthetics.
*   **Body:** The sans-serif is used for all descriptive text and functional elements to ensure a modern, clean readability that contrasts with the decorative headings.
*   **Calligraphy Accents:** Select Bengali glyphs or short words (e.g., "shanti" for peace) can be used as large, low-opacity background watermarks or as illustrative elements near product imagery.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop to ensure a curated, "gallery" feel, transitioning to a flexible fluid model on smaller screens. 

*   **Rhythm:** Use an 8px base unit. Generous whitespace is the most critical "component" of the design; when in doubt, increase the margin.
*   **Desktop:** 12-column grid with wide margins (64px+) to frame the content like a piece of art.
*   **Mobile:** 4-column grid with 20px margins. 
*   **Photography:** Images should dominate the layout. Use varying aspect ratios (e.g., 4:5 for product listings) to create a rhythmic, non-repetitive flow.

## Elevation & Depth

Depth in this system is conveyed through **Tonal Layers** and **Ambient Shadows**. 

*   **Shadows:** Shadows are extremely soft and tinted with the primary sage or clay colors (e.g., 4% opacity, 20px blur, 4px offset). They should look like a soft shadow cast on a textured wall, not a digital drop-shadow.
*   **Layering:** Elements "sit" on the background rather than floating high above it. Use subtle shifts in the cream/beige saturation to distinguish between the background and elevated cards.
*   **Glassmorphism:** Use sparingly for navigation overlays. A heavy backdrop-blur (20px) with a semi-transparent creamy beige tint allows the photography to bleed through while maintaining legibility.

## Shapes

The shape language is "Organic Geometric." We avoid clinical sharp corners in favor of **Rounded** (0.5rem) corners that feel soft to the touch, echoing the curves of clay pottery or smoothed river stones. 

*   **Standard Elements:** 8px (0.5rem) corner radius.
*   **Large Cards/Containers:** 16px (1rem) corner radius.
*   **Icons:** Use a medium stroke weight (1.5px to 2px) with rounded caps and joins to match the soft UI edges.

## Components

*   **Buttons:** Primary buttons use the Muted Sage background with white or cream text. Secondary buttons are "ghost" style with a 1px border. All buttons should have generous horizontal padding (32px+) to feel "spacious."
*   **Cards:** Product cards are borderless with a very soft ambient shadow on hover. The image occupies 80% of the card area, with the product name in Playfair Display below.
*   **Chips/Tags:** Used for "Organic," "Handmade," or "Limited" labels. These should have a Clay Orange background at 10% opacity with a solid Clay Orange text for a "stamp" effect.
*   **Inputs:** Minimalist bottom-border only or very light tonal backgrounds. Focus states are indicated by a gentle color shift to Sage, never a heavy outline.
*   **Calligraphy Accents:** Non-functional decorative elements. These are SVG assets of hand-drawn Bengali script, placed behind photography or at the end of long-form articles as a digital "seal."
*   **Navigation:** A centered, minimal top bar with high transparency and an elegant serif logo.