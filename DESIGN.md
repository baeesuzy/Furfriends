---
name: Vibrant Paws
colors:
  surface: '#f4fafd'
  surface-dim: '#d4dbdd'
  surface-bright: '#f4fafd'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eef5f7'
  surface-container: '#e8eff1'
  surface-container-high: '#e2e9ec'
  surface-container-highest: '#dde4e6'
  on-surface: '#161d1f'
  on-surface-variant: '#3c4a46'
  inverse-surface: '#2b3234'
  inverse-on-surface: '#ebf2f4'
  outline: '#6c7a76'
  outline-variant: '#bbcac4'
  surface-tint: '#006b5c'
  primary: '#006b5c'
  on-primary: '#ffffff'
  primary-container: '#00bfa5'
  on-primary-container: '#00473c'
  inverse-primary: '#44ddc1'
  secondary: '#ac332a'
  on-secondary: '#ffffff'
  secondary-container: '#fd6e60'
  on-secondary-container: '#6d0005'
  tertiary: '#735c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#cca620'
  on-tertiary-container: '#4d3d00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#68fadd'
  primary-fixed-dim: '#44ddc1'
  on-primary-fixed: '#00201a'
  on-primary-fixed-variant: '#005145'
  secondary-fixed: '#ffdad5'
  secondary-fixed-dim: '#ffb4aa'
  on-secondary-fixed: '#410001'
  on-secondary-fixed-variant: '#8b1a16'
  tertiary-fixed: '#ffe087'
  tertiary-fixed-dim: '#ebc23e'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#f4fafd'
  on-background: '#161d1f'
  surface-variant: '#dde4e6'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.2'
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  xxl: 64px
  container-max: 1200px
  gutter: 20px
---

## Brand & Style
The design system is built to reflect the joy and energy of pet ownership while maintaining the reliability of a high-tech tracking platform. The brand personality is "The Playful Guardian"—secure and sophisticated in its technology, but warm and spirited in its delivery. 

The visual style leverages **Soft Minimalism mixed with Tactile elements**. It avoids the coldness of traditional tech by using high-energy colors and organic shapes, ensuring the interface feels like an extension of a pet's world rather than a clinical dashboard. The emotional response should be one of optimism, safety, and delight.

## Colors
The palette is dominated by **Energetic Teal**, used for primary actions and brand presence to signal health and vitality. **Cheerful Coral** serves as the accent for secondary interactions and notifications, providing a warm contrast that draws the eye. **Sunny Yellow** is used sparingly for highlights, achievements, and "delight" moments. 

The neutral palette shifts away from pure blacks to a deep charcoal, maintaining high legibility while appearing softer. The background is a tinted off-white to reduce eye strain and allow the vibrant primary colors to pop without feeling harsh.

## Typography
This design system utilizes **Plus Jakarta Sans** across all levels to maintain a cohesive, friendly, and contemporary aesthetic. The typeface's naturally open apertures and organic curves reinforce the "welcoming" brand pillar.

Headlines use a heavy weight with slight negative letter-spacing to create a bold, "hug-like" impact. Body text maintains generous line heights to ensure maximum readability for users who may be glancing at their phones while on the go with their pets. Label styles utilize semi-bold and bold weights to ensure hierarchy is clear even at small scales.

## Layout & Spacing
The system follows a **Fluid Grid** model with an 8px base rhythm. Layouts should feel breathable and airy, using "xl" and "xxl" spacing to separate major content blocks. 

For mobile views, a 16px side margin is the standard, while desktop views utilize a 12-column grid with 20px gutters. Elements should be grouped within soft-edged containers to create a sense of organized playfulness. Avoid dense information clusters; prioritize "one thought per section" to maintain the clean tech aesthetic.

## Elevation & Depth
Depth is conveyed through **Ambient Shadows** and **Tonal Layering**. Surfaces do not use harsh black shadows; instead, they use a soft, diffused drop shadow tinted with the primary Teal or a deep Navy (e.g., `rgba(0, 191, 165, 0.08)`).

- **Level 0 (Base):** The main background color.
- **Level 1 (Cards/Containers):** White surfaces with a very soft, large-radius shadow.
- **Level 2 (Interactive/Floating):** Higher elevation with a slightly tighter, more pronounced shadow to indicate "pressability."
- **Overlays:** Use a subtle backdrop blur (10px) behind modals to maintain context without visual clutter.

## Shapes
The shape language is defined by **Pill-shaped (Level 3)** geometry. This is the core of the "friendly" aesthetic. There are no sharp corners in this design system. 

Small elements like checkboxes and tags use a minimum of 8px radius, while primary buttons and image containers should utilize full "pill" rounding or significant 2rem+ corner radii. This mimicry of organic, soft shapes makes the digital interface feel as approachable as a physical pet accessory.

## Components
- **Buttons:** Primary buttons are pill-shaped, using the Teal background with white text. Secondary buttons use a Teal border with a subtle 5% Teal fill.
- **Chips/Tags:** Used for pet traits or status (e.g., "Active," "Sleeping"). These should be fully rounded and use light pastel versions of the brand colors with dark text.
- **Cards:** Large 2rem corner radius. Cards should have a thin 1px border in a pale gray-teal to define edges without adding visual weight.
- **Input Fields:** Soft gray backgrounds with 1rem rounded corners. Focus states transition the border to Primary Teal with a subtle glow.
- **Checkboxes & Radios:** Should be oversized and use the Primary Teal for the checked state. Checkboxes have a 4px radius; radios are circular.
- **Pet Status Indicators:** Custom components like a "Vitals Ring" using the Sunny Yellow and Coral to show activity levels.
- **Progress Bars:** Thick, pill-shaped tracks with high-contrast fills to show tracking progress or battery life.