---
name: Organic Vitality
colors:
  surface: '#f9faf1'
  surface-dim: '#d9dbd2'
  surface-bright: '#f9faf1'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4eb'
  surface-container: '#edefe5'
  surface-container-high: '#e7e9e0'
  surface-container-highest: '#e2e3da'
  on-surface: '#191c17'
  on-surface-variant: '#43493c'
  inverse-surface: '#2e312b'
  inverse-on-surface: '#f0f2e8'
  outline: '#73796b'
  outline-variant: '#c3c9b8'
  surface-tint: '#436823'
  primary: '#426723'
  on-primary: '#ffffff'
  primary-container: '#5a8139'
  on-primary-container: '#ffffff'
  inverse-primary: '#a8d381'
  secondary: '#8d4f11'
  on-secondary: '#ffffff'
  secondary-container: '#feac67'
  on-secondary-container: '#773e00'
  tertiary: '#605d57'
  on-tertiary: '#ffffff'
  tertiary-container: '#79766f'
  on-tertiary-container: '#ffffff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c3f09b'
  primary-fixed-dim: '#a8d381'
  on-primary-fixed: '#0c2000'
  on-primary-fixed-variant: '#2c500c'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#e7e2d9'
  tertiary-fixed-dim: '#cbc6bd'
  on-tertiary-fixed: '#1d1b16'
  on-tertiary-fixed-variant: '#494640'
  background: '#f9faf1'
  on-background: '#191c17'
  surface-variant: '#e2e3da'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
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
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.03em
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
  margin-desktop: 40px
---

## Brand & Style
The design system embodies a "Nourished Premium" aesthetic, blending the reliability of health-tech with the warmth of high-end wellness. It targets health-conscious individuals who value clarity and approachable luxury. 

The style is **Corporate Modern** with a **Tactile** twist—utilizing generous whitespace and structured layouts balanced by organic color transitions and soft, welcoming surfaces. It avoids the clinical coldness of traditional health apps by leaning into a "warm-minimalist" philosophy, ensuring the user feels supported and revitalized rather than scrutinized.

## Colors
The palette is rooted in an "Earth & Sun" harmony. The core **Vitality Green** (#5A8139) remains the anchor, symbolizing growth and health. To elevate the premium feel, we introduce **Soft Amber** (#F4A460) as a secondary accent for energetic highlights and **Warm Cream** (#FFF9F0) as a primary background surface to reduce eye strain and add a sophisticated, organic texture.

- **Primary:** Vitality Green. Use for primary actions and brand identifiers.
- **Secondary:** Soft Amber. Use for high-visibility highlights, progress indicators, and seasonal accents.
- **Surface:** Warm Cream. Use for large background areas to provide a softer alternative to pure white.
- **Typography/Ink:** Deep Moss (#2D302A). A high-contrast, near-black green that ensures maximum readability while feeling more natural than pure black.

## Typography
Manrope is the sole typeface, chosen for its modern geometric foundation and humanist warmth. 

- **Hierarchy:** Use extra-bold weights for display sizes to create a confident, premium editorial feel. 
- **Readability:** Body text should maintain a generous line height (1.5x) to ensure the interface feels airy and accessible.
- **Case:** Use sentence case for headlines to maintain an approachable tone. Labels may use all-caps with slight letter spacing only at the smallest sizes (label-sm) for metadata.

## Layout & Spacing
The design system utilizes a **12-column fluid grid** for desktop and a **4-column grid** for mobile. 

The spacing philosophy is "Breathable Structure." We rely on an 8px incremental scale. Padding within cards and containers should lean towards larger values (24px or 32px) to reinforce the premium, unhurried brand personality. 

- **Desktop:** 40px outer margins to frame the content like a high-end magazine.
- **Mobile:** 16px outer margins with 16px gutters to maximize horizontal space for health data and imagery.

## Elevation & Depth
Depth is conveyed through **Tonal Layers** rather than heavy shadows. 

1. **Base:** Warm Cream (#FFF9F0) serves as the canvas.
2. **Cards:** Elevated surfaces use pure White (#FFFFFF) with a very soft, diffused ambient shadow (10% opacity of the primary green) to create a subtle lift.
3. **Overlays:** Use a subtle "Glassmorphism" effect for navigation bars—a background blur (12px) combined with a high-transparency white fill (80%) to maintain context of the content beneath.
4. **Interaction:** Hover states should involve a slight vertical lift (2px) and a softening of the shadow, rather than a color change, to feel more tactile and physical.

## Shapes
Shapes are defined by "Natural Curvature." Following the `rounded-md` (0.5rem) standard, the UI feels soft and organic without becoming juvenile.

- **Standard Elements:** Buttons and input fields use a 0.5rem radius.
- **Large Containers:** Cards and modals use `rounded-xl` (1.5rem) to emphasize the welcoming, premium nature of the container.
- **Special Elements:** Progress bars and tags should use a fully rounded (pill) style to distinguish them as secondary, more fluid elements.

## Components
- **Buttons:** Primary buttons use a solid Vitality Green with white text. Secondary buttons use a Warm Cream fill with a thin Moss Green border.
- **Cards:** White backgrounds, 1.5rem corner radius, and 24px internal padding. Use a subtle 1px border in a slightly darker cream to define edges on desktop.
- **Inputs:** Use a soft cream background instead of white. On focus, the border transitions to Vitality Green with a subtle outer glow.
- **Chips/Badges:** Use Soft Amber for motivational "milestone" chips and light tints of Green for status indicators.
- **Selection Controls:** Checkboxes and Radio buttons should be slightly oversized (20px) to enhance the tactile feel, using the Primary Green for the active state.
- **Progress Indicators:** Use thick, rounded tracks. The track should be a very pale version of the Green, while the indicator is the solid Green or Soft Amber for "extra effort" metrics.