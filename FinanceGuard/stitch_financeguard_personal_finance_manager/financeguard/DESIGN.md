---
name: FinanceGuard
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#44474c'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#74777d'
  outline-variant: '#c4c6cc'
  surface-tint: '#525f71'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#0f1c2c'
  on-primary-container: '#778598'
  inverse-primary: '#bac8dc'
  secondary: '#006a62'
  on-secondary: '#ffffff'
  secondary-container: '#70f8e8'
  on-secondary-container: '#007168'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#281804'
  on-tertiary-container: '#9a7f61'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e4f9'
  primary-fixed-dim: '#bac8dc'
  on-primary-fixed: '#0f1c2c'
  on-primary-fixed-variant: '#3a4859'
  secondary-fixed: '#70f8e8'
  secondary-fixed-dim: '#4fdbcc'
  on-secondary-fixed: '#00201d'
  on-secondary-fixed-variant: '#005049'
  tertiary-fixed: '#feddba'
  tertiary-fixed-dim: '#e0c1a0'
  on-tertiary-fixed: '#281804'
  on-tertiary-fixed-variant: '#584329'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
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
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  numeric-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  gutter: 16px
  margin-mobile: 20px
  margin-tablet: 32px
---

## Brand & Style
The design system is engineered for high-stakes financial environments where trust, precision, and security are paramount. The brand personality is authoritative yet accessible, positioning itself as a reliable guardian of the user's fiscal health. 

The aesthetic follows a **Corporate / Modern** style, emphasizing clarity and systematic organization. It leverages a rigorous grid, generous whitespace to reduce cognitive load during complex tasks, and high-quality micro-interactions that provide immediate feedback. The visual language avoids unnecessary decoration, opting instead for functional elegance that mirrors premium global banking standards.

## Colors
The palette is built on a foundation of "Deep Blue" to evoke stability and institutional strength. "Vibrant Green" is utilized strategically for growth indicators, primary actions, and success states, providing a high-energy contrast against the darker base.

In **Light Mode**, the interface uses "Pure White" for primary surfaces with subtle light gray shifts for background containment. In **Dark Mode**, the "Deep Blue" shifts to a slightly lighter "Surface Dark" (#1B263B) to maintain depth perception and ensure the "Vibrant Green" remains accessible and legible without causing eye strain. Semantic colors (Red for alerts, Amber for warnings) should be desaturated slightly in dark mode.

## Typography
This design system utilizes **Inter** for its exceptional legibility and neutral, systematic tone. The type scale is optimized for data density.

A critical requirement is the use of **Tabular Figures** (tnum) for all balance displays and transaction amounts to ensure vertical alignment in lists and tables. Headlines use tighter letter spacing to maintain a "locked-in" professional feel, while small labels use increased tracking for better legibility on mobile displays.

## Layout & Spacing
The system employs an **8px linear scale** for all spacing decisions, ensuring a mathematical rhythm across the UI. 

For mobile, a **4-column fluid grid** is used with 20px side margins and 16px gutters. Elements should snap to the grid to maintain a disciplined, "secure" appearance. Vertical rhythm is maintained by stacking components in multiples of 8px. On larger screens (Tablet), the grid expands to 8 columns, and margins increase to 32px to prevent content from feeling overly stretched.

## Elevation & Depth
Hierarchy is conveyed through **Tonal Layers** combined with **Ambient Shadows**. Instead of high-contrast black shadows, this design system uses "Deep Blue" tinted shadows to maintain color harmony.

- **Level 0 (Base):** The main background color.
- **Level 1 (Cards):** Low elevation. 1px stroke (10% opacity primary color) and a soft 4px blur shadow.
- **Level 2 (Modals/Dropdowns):** Medium elevation. 12px blur shadow with 8% opacity.
- **Level 3 (Sticky Nav):** High elevation. Distinct shadow to separate from scrolling content, using a 20px blur.

In dark mode, shadows are replaced by subtle border highlights (top-inner edge) to simulate light hitting the edge of a surface.

## Shapes
The shape language uses **Rounded (level 2)** corners to soften the professional tone, making the app feel modern and user-friendly rather than rigid. 

Standard components (Inputs, Buttons) use a **8px (0.5rem)** radius. Larger containers like Dashboard cards use **16px (1rem)**, while decorative elements or secondary tags may use "full" rounding (pill-shaped) to distinguish them from actionable primary buttons.

## Components
- **Buttons:** Primary buttons are solid "Vibrant Green" with white text. Secondary buttons use a "Deep Blue" outline or ghost style. All buttons have a height of 48px for optimal touch targets.
- **Input Fields:** Use a 1px border. On focus, the border transitions to "Vibrant Green" with a subtle outer glow. Labels are always persistent (never disappearing on focus).
- **Cards:** Transaction cards utilize a horizontal layout with an icon on the left, primary text in the center, and tabular-num balances on the right.
- **Lists:** Clean dividers (1px, 5% opacity) separate items. High touch-area padding (16px vertical) is required.
- **Chips/Badges:** Small, low-saturation backgrounds with high-contrast text used for status (e.g., "Pending," "Cleared").
- **Key Metric Displays:** Large, bold font weights for account balances, paired with "Vibrant Green" micro-sparklines to indicate trend direction.