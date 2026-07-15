---
name: Obsidian Reserve
colors:
  surface: '#0c141f'
  surface-dim: '#0c141f'
  surface-bright: '#323a46'
  surface-container-lowest: '#070f19'
  surface-container-low: '#141c27'
  surface-container: '#18202b'
  surface-container-high: '#232a36'
  surface-container-highest: '#2d3541'
  on-surface: '#dbe3f3'
  on-surface-variant: '#bbcabf'
  inverse-surface: '#dbe3f3'
  inverse-on-surface: '#29313d'
  outline: '#86948a'
  outline-variant: '#3c4a42'
  surface-tint: '#4edea3'
  primary: '#4edea3'
  on-primary: '#003824'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#006c49'
  secondary: '#b9c7e0'
  on-secondary: '#233144'
  secondary-container: '#3c4a5e'
  on-secondary-container: '#abb9d2'
  tertiary: '#ffb3af'
  on-tertiary: '#650911'
  tertiary-container: '#fc7c78'
  on-tertiary-container: '#711419'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#d5e3fd'
  secondary-fixed-dim: '#b9c7e0'
  on-secondary-fixed: '#0d1c2f'
  on-secondary-fixed-variant: '#3a485c'
  tertiary-fixed: '#ffdad7'
  tertiary-fixed-dim: '#ffb3af'
  on-tertiary-fixed: '#410005'
  on-tertiary-fixed-variant: '#842225'
  background: '#0c141f'
  on-background: '#dbe3f3'
  surface-variant: '#2d3541'
typography:
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
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
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: JetBrains Mono
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
  base: 8px
  container-padding: 24px
  gutter: 16px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style
The brand personality for the design system is authoritative, secure, and technologically advanced. It is tailored for high-stakes financial environments where precision and trust are paramount. The aesthetic combines **Modern Corporate** reliability with a **High-Contrast Dark** interface to reduce eye strain during prolonged analysis while highlighting critical data points.

The design evokes a sense of "digital vault" security. It uses deep, monochromatic surfaces to create a background of stability, allowing the vibrant emerald accents to guide the user's attention toward actions and growth indicators. The emotional response is one of calm control and professional confidence.

## Colors
The color palette is anchored by the core surface color, **Deep Navy (#0B131E)**, which provides a sophisticated, low-light foundation. The primary accent is a vibrant **Emerald Green (#10B981)**, used strategically for primary actions, success states, and brand reinforcement.

Secondary elements utilize a muted slate to differentiate between functional areas without competing with the primary emerald. Status indicators (Success, Warning, Error) are tuned for high luminosity against the dark background, ensuring accessibility and immediate recognition of financial health or system alerts. Text colors are strictly controlled: Pure White for headings, and a high-contrast Silver-Grey for body copy to maintain readability.

## Typography
The typography strategy employs **Manrope** for headlines to provide a modern, balanced, and premium feel. Its geometric nature reflects the precision of the financial sector. 

For body text, **Inter** is used for its exceptional legibility and neutral systematic feel, ensuring that dense financial data is easy to parse. **JetBrains Mono** is introduced for labels, data values, and transaction IDs to emphasize the technical, "banking-level" accuracy of the platform. Type scales are tight and purposeful, utilizing negative letter spacing on larger headings to maintain a compact, high-density professional appearance.

## Layout & Spacing
This design system utilizes a **12-column fluid grid** for desktop and a **4-column grid** for mobile. The spacing rhythm is strictly based on an **8px linear scale**, ensuring mathematical harmony across all components.

Layouts should prioritize data density while maintaining clear visual grouping. Use larger 48px vertical stacks to separate distinct modules (e.g., Portfolio Summary vs. Transaction History), and tighter 12px or 24px spacing for internal element relationships. Margins on mobile are reduced to 16px to maximize screen real estate for charts and tables, while desktop margins are set at a generous 24px to maintain a premium feel.

## Elevation & Depth
Depth in the dark mode environment is achieved through **Tonal Layers** rather than heavy shadows. The base surface is `#0B131E`. Elements that sit "above" the base, such as cards or navigation bars, use a slightly lighter surface color (`#161F2C`) to create a perceived lift.

Where shadows are necessary for high-priority modals or dropdowns, use an **Ambient Shadow**: a deep, low-opacity black (`rgba(0, 0, 0, 0.4)`) with a large 16px - 32px blur radius. To reinforce the emerald brand, high-elevation elements may feature a subtle 1px border using a low-opacity emerald tint (`#10B981` at 10%) to "catch the light" and define the edges of the container against the dark backdrop.

## Shapes
The shape language follows a **Rounded** philosophy. This softens the intensity of the dark mode and provides a more approachable, modern fintech experience. 

Standard components (inputs, buttons, cards) use a **0.5rem (8px)** corner radius. Large containers like main dashboard panels or modals use **1rem (16px)** to emphasize their structural importance. This level of roundedness balances the "sturdy" professional aesthetic with contemporary UI trends, avoiding the harshness of sharp corners or the playfulness of full-pill shapes.

## Components
- **Buttons**: Primary buttons are solid Emerald with high-contrast dark text. Secondary buttons use a slate outline or a subtle ghost style. All buttons use 8px rounded corners and Medium-weight text.
- **Inputs**: Field backgrounds use the elevated surface color (`#161F2C`) with a subtle 1px slate border. Upon focus, the border transitions to Emerald.
- **Cards**: Cards are the primary container for financial data. They use the elevated surface tint, no stroke (unless active), and a consistent 16px internal padding.
- **Chips**: Used for status or categories. They should use a low-opacity background of the status color (e.g., 15% Emerald for "Complete") with a 100% opacity text color for maximum readability.
- **Data Tables**: Use subtle 1px horizontal dividers in slate. Header cells use the **label-sm** monospaced font for a technical appearance.
- **Progress Indicators**: Gauges and bars use a high-vibrancy Emerald against a deep slate track to ensure the "growth" metrics are the most luminous elements on the screen.