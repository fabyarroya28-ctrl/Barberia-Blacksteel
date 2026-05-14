---
name: Steel & Shadow
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
  on-surface-variant: '#c4c7c7'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c7c6c6'
  primary: '#c7c6c6'
  on-primary: '#2f3131'
  primary-container: '#a0a0a0'
  on-primary-container: '#363737'
  inverse-primary: '#5e5e5f'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#c8c6c5'
  on-tertiary: '#313030'
  tertiary-container: '#a2a09f'
  on-tertiary-container: '#373737'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e3e2e2'
  primary-fixed-dim: '#c7c6c6'
  on-primary-fixed: '#1a1c1c'
  on-primary-fixed-variant: '#464747'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1b1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  headline-xl:
    fontFamily: Bebas Neue
    fontSize: 72px
    fontWeight: '400'
    lineHeight: 72px
    letterSpacing: 0.05em
  headline-lg:
    fontFamily: Bebas Neue
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: 0.02em
  headline-lg-mobile:
    fontFamily: Bebas Neue
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 36px
  headline-md:
    fontFamily: Bebas Neue
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.1em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
spacing:
  unit: 4px
  gutter: 16px
  margin-mobile: 20px
  margin-desktop: 64px
  max-width: 1280px
---

## Brand & Style

The design system is engineered to evoke the precision of a master barber’s blade. It targets a discerning clientele that values tradition fused with modern industrial luxury. The aesthetic is rooted in **Industrial Minimalism**, prioritizing high-contrast visuals, raw textures, and an uncompromising sense of order.

The emotional response should be one of confidence and reliability. By utilizing a "dark mode" first approach, we create an intimate, premium environment that mirrors the atmosphere of a high-end grooming lounge. Every element is designed to feel "machined"—precise, sturdy, and purposeful.

## Colors

The palette is strictly monochromatic to emphasize form and texture over hue. 

- **Primary (Steel):** A metallic silver used for key actions, dividers, and accents. It represents the tools of the trade.
- **Background (Deep Black):** The foundation of the UI, providing a high-contrast canvas that allows photography and typography to pop.
- **Surface (Charcoal):** Used for cards, navigation bars, and secondary containers to create subtle depth without relying on shadows.
- **Text:** Pure white for maximum legibility in primary roles, and a muted grey (#999999) for supporting information to maintain hierarchy.

Gradients should be used sparingly, mimicking the "brushed metal" look (e.g., a subtle linear gradient from #A0A0A0 to #D4D4D4 at a 45-degree angle).

## Typography

This design system employs a high-impact typographic pairing. **Bebas Neue** is the voice of the brand—tall, condensed, and authoritative. It is used exclusively for headlines and impactful callouts. Because of its condensed nature, it should always be used with generous leading and occasional tracking adjustments for a premium editorial feel.

**Inter** provides a functional, modern counterpoint for body copy and UI labels. It ensures that technical details (prices, times, services) remain crystal clear. 

All labels and sub-headers should use uppercase styling with increased letter spacing to reinforce the "engineered" aesthetic.

## Layout & Spacing

The layout philosophy is a **Rigid Grid** system. To mirror the precision of a haircut, the spacing is mathematical and tight. 

- **Desktop:** A 12-column grid with 16px gutters. Content is often contained within "Steel" borders rather than floating freely.
- **Mobile:** A 4-column grid with 20px side margins. 
- **Spacing Rhythm:** Based on a 4px baseline. Use 16px (4 units) for standard grouping and 32px (8 units) for section separation.

Layouts should favor asymmetry in imagery but maintain strict alignment in text and UI controls. Heavy use of vertical and horizontal lines (1px width) should be used to separate content blocks, simulating the layout of a blueprint or technical manual.

## Elevation & Depth

In this design system, depth is achieved through **Tonal Layering** and **High-Contrast Outlines** rather than traditional shadows. 

1.  **Level 0 (Base):** #0D0D0D.
2.  **Level 1 (Cards/Surfaces):** #1C1C1C.
3.  **Accents:** 1px solid borders using the Primary Steel color (#A0A0A0) at 30% opacity for inactive states and 100% for active states.

Shadows are almost entirely avoided. If a popover or modal requires separation, use a solid 2px Steel border and a heavy backdrop blur (20px) on the background to pull the element forward. This maintains the "Steel" feel without introducing soft, organic shapes that contradict the brand's sharpness.

## Shapes

The shape language is strictly **Sharp (0px)**. There are no rounded corners in the design system. Every button, input field, card, and image container must have 90-degree angles. 

This lack of curvature reinforces the "Steel" identity—it is cold, hard, and precise. Interactive elements distinguish themselves through hover states (e.g., filling a bordered box with a metallic gradient) rather than physical "lift" or rounding.

## Components

### Buttons
- **Primary:** Solid Steel (#A0A0A0) background with Black text. 0px border-radius.
- **Secondary:** Transparent background with a 1px Steel border. Text in White.
- **Interaction:** On hover, primary buttons should shift to a subtle metallic gradient; secondary buttons should fill with a 10% Steel opacity.

### Input Fields
- Dark backgrounds (#0D0D0D) with a bottom-only 1px Steel border. 
- Floating labels using Inter Label-sm. 
- Focus state: The bottom border increases to 2px and 100% opacity.

### Cards
- Background: #1C1C1C. 
- Border: Optional 1px Steel border at 20% opacity.
- Layout: Use for service menus, barber profiles, or gallery items. Images within cards should have a slight desaturation (80%) until hovered.

### Lists & Dividers
- Lists should be separated by 1px Steel lines. 
- Use "Steel" chevron icons (sharp angles) for navigation items.

### Chips/Tags
- Rectangular, sharp edges. 
- Background #1C1C1C with 1px border. 
- Used for "Available Today" or "Master Barber" status indicators.

### Booking Calendar
- High contrast. Selected dates are filled Steel squares with black text. Current date is outlined in White. No rounded circles.