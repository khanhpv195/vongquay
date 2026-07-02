---
name: Vibrant Fortune
colors:
  surface: '#fff8f6'
  surface-dim: '#f8d1cb'
  surface-bright: '#fff8f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff0ee'
  surface-container: '#ffe9e5'
  surface-container-high: '#ffe2dd'
  surface-container-highest: '#ffdad4'
  on-surface: '#2b1613'
  on-surface-variant: '#5b403d'
  inverse-surface: '#422a26'
  inverse-on-surface: '#ffedea'
  outline: '#8f6f6c'
  outline-variant: '#e4beba'
  surface-tint: '#ba1a20'
  primary: '#af101a'
  on-primary: '#ffffff'
  primary-container: '#d32f2f'
  on-primary-container: '#fff2f0'
  inverse-primary: '#ffb3ac'
  secondary: '#785900'
  on-secondary: '#ffffff'
  secondary-container: '#fdc003'
  on-secondary-container: '#6c5000'
  tertiary: '#005a98'
  on-tertiary: '#ffffff'
  tertiary-container: '#0073c0'
  on-tertiary-container: '#f0f5ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb3ac'
  on-primary-fixed: '#410003'
  on-primary-fixed-variant: '#930010'
  secondary-fixed: '#ffdf9e'
  secondary-fixed-dim: '#fabd00'
  on-secondary-fixed: '#261a00'
  on-secondary-fixed-variant: '#5b4300'
  tertiary-fixed: '#d1e4ff'
  tertiary-fixed-dim: '#9ecaff'
  on-tertiary-fixed: '#001d36'
  on-tertiary-fixed-variant: '#00497d'
  background: '#fff8f6'
  on-background: '#2b1613'
  surface-variant: '#ffdad4'
typography:
  display-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-bold:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  unit: 4px
  container-padding: 24px
  gutter-md: 16px
  component-gap: 12px
---

## Brand & Style

The design system centers on a **Modern-Vibrant** aesthetic, blending the excitement of carnival gaming with high-fidelity digital polish. The narrative is one of high-energy anticipation, luck, and reward. 

The style utilizes **Skeuomorphic-Modernism**: a mix of 3D-depth effects (soft gradients, inner glows, and realistic shadows) and clean, geometric layouts. It aims to evoke a festive and celebratory atmosphere through high-contrast colors and dynamic visual layers, ensuring the "Lucky Wheel" feels like a premium, physical object within a digital space.

## Colors

The palette is anchored by traditional festive tones, elevated with saturation for digital impact.

- **Primary (Prosperity Red):** Used for key call-to-action buttons, high-value wheel segments, and critical alerts. It signifies energy and urgency.
- **Secondary (Golden Luck):** A vibrant gold used for rewards, highlights, and "premium" borders. It provides a warm, glow-like effect.
- **Tertiary (Dynamic Blue & Teal):** Used for contrast within the wheel segments and secondary informational UI to balance the warmth of red/gold.
- **Neutrals:** Deep chocolate browns and off-whites provide a more sophisticated grounding than pure black or white, maintaining the "festive" warmth.

## Typography

Typography is used to drive hierarchy and "win" excitement. 

- **Display & Headlines:** Use **Plus Jakarta Sans** for its friendly yet geometric structure. Tighten letter-spacing on larger sizes to create a "locked-in" headline feel.
- **Body & Labels:** **Be Vietnam Pro** offers excellent legibility for instructional text and prize descriptions, maintaining a contemporary Vietnamese typographic standard.
- **Style Note:** For the Lucky Wheel itself, use bold, uppercase weights with slight text-shadows to ensure readability against multi-colored backgrounds.

## Layout & Spacing

The system follows a **Center-Focus Fluid Layout**. The Wheel is the primary anchor, always occupying the optical center of the screen.

- **Grid:** A 12-column grid is used for surrounding content (leaderboards, prize lists), but the main game stage uses dynamic margins to keep the Wheel at a maximum of 90% viewport width on mobile and 600px on desktop.
- **Rhythm:** An 8px linear scale (4px units) ensures tight alignment. 
- **Z-Space:** Elements closer to the user (like the "Spin Now" button) use more aggressive padding and larger scale than background decorative elements.

## Elevation & Depth

Visual hierarchy is achieved through **Tactile Layering**:

- **Wheel Base:** Features a deep "well" effect using inner shadows and multi-layered strokes to look like a physical machine.
- **Interactive Layers:** Buttons and prize cards use **Ambient Shadows** (Y: 8px, Blur: 16px, Opacity: 15% with a Red/Gold tint) to appear lifted off the background.
- **Backdrop Effects:** Use a light 4px blur for modals or prize announcements to keep the festive background visible while focusing the user's attention.

## Shapes

The shape language is primarily **Pill-shaped and Circular** to mirror the geometry of the wheel and evoke a friendly, safe gaming environment.

- **Buttons:** Fully rounded (pill) to maximize tap-friendliness.
- **Cards/Modals:** Use `rounded-xl` (1.5rem) to maintain a soft, approachable feel while allowing for structured content layouts.
- **Wheel Segments:** Sharp at the center, radiating outwards into the circular outer rim, creating a starburst effect.

## Components

### Spin Button (Call to Action)
The "Spin" button is the most prominent element. It should be a large circle or pill with a golden gradient, an inner "shine" light-leak, and a subtle pulse animation when idle.

### Prize Chips
Small, rounded-pill indicators that show remaining spins or current currency. Use a semi-transparent dark background with high-contrast white text.

### Reward Cards
When a user wins, the reward is presented in a card with a "sunburst" background effect behind the prize icon. Use `rounded-xl` corners and a bold `headline-lg` for the prize name.

### Segment Items
Text and icons within the wheel must be rotated to face the center. Use high-contrast colors (white text on dark segments, dark brown text on light segments).

### Input Fields (Phone/Name)
For lead generation, use clean, `rounded-lg` inputs with a soft 1px border that glows Golden Luck when focused.