---
name: Verdant Heritage
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
  on-surface-variant: '#414844'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#717973'
  outline-variant: '#c1c8c2'
  surface-tint: '#3f6653'
  primary: '#012d1d'
  on-primary: '#ffffff'
  primary-container: '#1b4332'
  on-primary-container: '#86af99'
  inverse-primary: '#a5d0b9'
  secondary: '#7d562d'
  on-secondary: '#ffffff'
  secondary-container: '#ffca98'
  on-secondary-container: '#7a532a'
  tertiary: '#002d1c'
  on-tertiary: '#ffffff'
  tertiary-container: '#00452d'
  on-tertiary-container: '#64b68e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c1ecd4'
  primary-fixed-dim: '#a5d0b9'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#274e3d'
  secondary-fixed: '#ffdcbd'
  secondary-fixed-dim: '#f0bd8b'
  on-secondary-fixed: '#2c1600'
  on-secondary-fixed-variant: '#623f18'
  tertiary-fixed: '#a0f4c8'
  tertiary-fixed-dim: '#85d7ad'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  headline-xl:
    fontFamily: Work Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
  headline-lg:
    fontFamily: Work Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Work Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-md:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.02em
  data-tabular:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  container-margin: 32px
  gutter: 20px
---

## Brand & Style

This design system establishes a visual language of "Agricultural Precision." It blends the organic warmth of a family-operated dairy farm with the rigorous professionalism of a modern supply chain enterprise. The aesthetic is rooted in **Corporate Minimalism**, utilizing heavy whitespace to symbolize the cleanliness and purity essential to dairy production.

The target audience ranges from logistics managers tracking milk yields to premium retail customers seeking transparency in their food source. To serve both, the UI prioritizes clarity, structural integrity, and a sense of "quiet quality." Every element is designed to evoke trust, suggesting that the farm’s operations are as disciplined as they are natural.

## Colors

The palette is a curated reflection of the farm environment, optimized for digital legibility.

*   **Primary (Forest Green):** A deep, authoritative green used for headers, primary actions, and brand identification. It represents growth and stability.
*   **Secondary (Earthy Clay):** A warm, muted tone used for accents and highlighting "heritage" elements. It provides a human, grounded contrast to the technical greens.
*   **Tertiary (Fresh Mint):** A vibrant, lighter green reserved for success states, trend indicators (positive yield), and active statuses.
*   **Neutral (Alpine White & Slate):** The "Crisp White" serves as the primary canvas, ensuring the interface feels hygienic. Neutrals are tiered from cool grays for data grids to deep charcoals for body text.

## Typography

**Work Sans** is the sole typeface for this design system, chosen for its exceptional performance in both brand storytelling and dense data management. Its slightly wider apertures and grounded letterforms ensure that logistics tables and supply metrics remain legible even on mobile devices.

For data-heavy views (milk yield, fat content, temperature logs), use the `data-tabular` style to ensure numbers align vertically for easy comparison. Headlines should use tight tracking and heavier weights to project confidence, while body text uses a generous line-height to maintain a "clean" and airy feel.

## Layout & Spacing

The design system employs a **Fixed-Fluid Hybrid Grid**. Content is housed in a 12-column system with a maximum width of 1440px for desktop to prevent line lengths from becoming unreadable. 

The spacing rhythm is based on a 4px baseline, but defaults to 16px (md) for standard padding and 24px (lg) for component separation. Information density should be "Comfortable" for customer-facing pages and "Compact" for internal management dashboards. High-priority farm data should be grouped in 4-column cards to allow for rapid scanning of multiple metrics.

## Elevation & Depth

To maintain a "High-Quality" and "Modern" feel, the system avoids heavy drop shadows in favor of **Tonal Layers** and **Soft Ambient Shadows**.

*   **Layering:** The background uses the neutral `#F8F9FA`. Cards and primary containers use absolute `#FFFFFF` to "pop" without needing dark borders.
*   **Shadows:** When depth is required (e.g., for modals or floating action buttons), use a very soft, diffused shadow with a hint of the primary green: `rgba(27, 67, 50, 0.08)`.
*   **Separation:** Use thin 1px borders in a light gray (`#E9ECEF`) for data tables and list items to keep the UI structured but unobtrusive.

## Shapes

The shape language is **Rounded (Level 2)**. A border-radius of 0.5rem (8px) is applied to standard components like buttons and input fields. Larger containers, such as dashboard cards and featured images, utilize 1rem (16px) to soften the professional tone with an approachable, organic feel. 

This rounding mimics the soft lines found in nature and dairy products, moving away from the "harshness" of industrial agriculture toward a more holistic farm-to-table narrative.

## Components

*   **Buttons:** Primary buttons feature the Forest Green background with White text. Secondary buttons use an Earthy Clay outline. All buttons should have a subtle hover transition that deepens the color slightly.
*   **Cards:** Use a white background, 1px light gray border, and 16px padding. For farm data, cards should include a "status indicator" (a small dot) in the top right: Fresh (Green), Processing (Clay), or Alert (Red).
*   **Input Fields:** Use a 1px border that turns Forest Green on focus. Labels should always be visible above the field in `label-md` for accessibility.
*   **Chips/Badges:** Used for milk grades (e.g., "Grade A") or livestock status. These use low-saturation versions of the primary/tertiary colors with dark text to ensure high contrast.
*   **Data Visualization:** Graphs and charts should use the Green-to-Clay spectrum. Line charts for yield data should be smoothed (spline) rather than jagged to reinforce the organic brand feel.
*   **Inventory Lists:** Use zebra-striping with the neutral `#F8F9FA` for long lists of supply data to prevent eye fatigue.