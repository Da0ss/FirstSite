---
name: Precision Industrial
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#3d4a3a'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#6d7b69'
  outline-variant: '#bccbb6'
  surface-tint: '#006e1f'
  primary: '#006e1f'
  on-primary: '#ffffff'
  primary-container: '#2cd14c'
  on-primary-container: '#005315'
  inverse-primary: '#44e35b'
  secondary: '#595e6d'
  on-secondary: '#ffffff'
  secondary-container: '#dee2f4'
  on-secondary-container: '#5f6473'
  tertiary: '#635d5c'
  on-tertiary: '#ffffff'
  tertiary-container: '#bcb4b2'
  on-tertiary-container: '#4b4645'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#6fff7a'
  primary-fixed-dim: '#44e35b'
  on-primary-fixed: '#002204'
  on-primary-fixed-variant: '#005315'
  secondary-fixed: '#dee2f4'
  secondary-fixed-dim: '#c2c6d7'
  on-secondary-fixed: '#161b28'
  on-secondary-fixed-variant: '#424654'
  tertiary-fixed: '#e9e1df'
  tertiary-fixed-dim: '#cdc5c3'
  on-tertiary-fixed: '#1e1b1a'
  on-tertiary-fixed-variant: '#4b4644'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
  action-green: '#2CD14C'
  deep-navy: '#0C111D'
  industrial-gray: '#292524'
  pure-white: '#FFFFFF'
  surface-charcoal: '#111827'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
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
  label-bold:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  section-gap: 80px
  component-gap: 16px
---

## Brand & Style

This design system is built for the industrial heavy-machinery sector, specifically targeting warehouse managers and logistics directors. The brand personality is authoritative, precise, and high-performance. It balances the rugged nature of heavy equipment with the high-tech precision of digital metrology.

The visual style is **Corporate / Modern** with a lean toward **Minimalism**. It uses a high-contrast foundation to ensure readability in high-glare warehouse environments. The aesthetic relies on crisp lines, generous whitespace to denote organization, and a specific "Action Green" to guide users through technical workflows. Imagery should be high-resolution, featuring industrial textures, machinery, and warehouse logistics to ground the digital experience in the physical world.

## Colors

The palette is dominated by a stark contrast between **Deep Navy** (#0C111D) and **Pure White** (#FFFFFF). This creates a professional, blueprint-like clarity. 

- **Primary (Action Green):** Reserved exclusively for conversion points, progress indicators, and successful status states. It must be used sparingly to maintain its "signal" value.
- **Secondary (Deep Navy):** Used for primary text, headers, and dark-themed section backgrounds. It provides a more sophisticated alternative to pure black.
- **Tertiary (Industrial Gray):** A warm-toned charcoal used for borders, secondary buttons, and subtle textural elements.
- **Neutral:** Pure white is the primary canvas, ensuring the "industrial" feel remains clean rather than gritty.

## Typography

This design system uses **Inter** exclusively to maintain a utilitarian, highly legible, and professional appearance. The type scale is aggressive in its hierarchy to ensure that technical specifications are never lost.

- **Headlines:** Set with tight letter-spacing and heavy weights (600-700). Large display sizes are used for hero sections to convey industry leadership.
- **Body Text:** Uses a standard 16px or 18px base for maximum readability. Line height is kept generous (1.5x+) to prevent dense blocks of technical text from becoming fatiguing.
- **Labels:** Small caps or bold weights are used for technical data points and status badges to differentiate them from narrative copy.

## Layout & Spacing

The layout follows a **12-column fluid grid** for desktop, transitioning to a **4-column grid** for mobile. 

- **Modular Spacing:** All spacing is based on an 8px base unit. 
- **Sectioning:** Large vertical gaps (80px - 120px) are used to separate distinct service offerings or technical categories, creating a sense of "breathing room" in an otherwise data-heavy environment.
- **Data Grids:** For technical specs, use a compact 16px gutter to keep related information visually grouped.
- **Margins:** Desktop margins are flexible but constrained by a 1280px max-width container to prevent line lengths from becoming unreadable on ultra-wide monitors.

## Elevation & Depth

This design system utilizes **Tonal Layers** and **Low-Contrast Outlines** rather than heavy shadows. The goal is to feel like a modern software interface used on a rugged tablet.

- **Surfaces:** Use flat white or off-white backgrounds. Elevated elements like cards use a subtle 1px border (#E5E7EB) instead of a shadow.
- **Active States:** When an element is focused or active, it may use a very soft, diffused ambient shadow (Color: Deep Navy, Opacity: 4%, Blur: 12px) to provide a tactile "lift."
- **Dark Mode Surfaces:** In dark sections, use "Surface-Container" tiers where the background is #0C111D and cards are slightly lighter at #111827.

## Shapes

The shape language is **Soft (0.25rem)**. This provides a subtle nod to precision engineering and machined parts, which often have slightly eased edges for safety and durability, but avoids the "playfulness" of fully rounded or pill-shaped designs.

- **Primary Buttons:** Use 4px (0.25rem) radius for a sharp, professional look.
- **Cards and Containers:** Use 8px (0.5rem) radius to define clear boundaries for content groups.
- **Inputs:** Maintain a consistent 4px radius to match buttons.

## Components

- **Buttons:** 
    - *Primary:* Action Green background with Deep Navy text for maximum contrast. No border.
    - *Secondary:* Transparent background with Deep Navy border and text.
    - *Iconography:* Use 20px icons aligned to the left of the text.
- **Cards:** 
    - Minimalist style. Use a white background, 1px light gray border, and a 16px padding.
    - Images within cards should be top-aligned with no border radius on the top corners.
- **Input Fields:** 
    - Standardized height of 48px. 
    - Focus state uses a 2px Action Green border.
- **Chips / Badges:** 
    - Used for "In Stock" or "Certified" statuses.
    - Background color should be a 10% opacity version of the status color (e.g., 10% Action Green).
- **Process Indicators:** 
    - Use large, circular numbered badges (Deep Navy background, White text) to guide users through the Diagnostic -> Solution -> Launch phases.
- **Data Tables:**
    - Clean, no vertical borders. Use 1px horizontal dividers. Header row should be Deep Navy with White text.