---
name: PropertyShield Narrative
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#45464d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#515f74'
  on-secondary: '#ffffff'
  secondary-container: '#d5e3fd'
  on-secondary-container: '#57657b'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#271901'
  on-tertiary-container: '#98805d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#d5e3fd'
  secondary-fixed-dim: '#b9c7e0'
  on-secondary-fixed: '#0d1c2f'
  on-secondary-fixed-variant: '#3a485c'
  tertiary-fixed: '#fcdeb5'
  tertiary-fixed-dim: '#dec29a'
  on-tertiary-fixed: '#271901'
  on-tertiary-fixed-variant: '#574425'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  title-lg:
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
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  2xl: 48px
  3xl: 64px
  container-max: 1200px
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 32px
---

## Brand & Style

This design system is built on the pillars of authority, reliability, and precision. It avoids the visual noise of traditional real-estate listings to focus on risk assessment and security. The aesthetic is **Corporate / Modern**, emphasizing clarity over decoration. It utilizes a structured, systematic approach to information density, ensuring that users feel a sense of calm and control when navigating complex property data. The emotional response should be one of "certainty"—transforming anxiety about property investment into informed confidence.

## Colors

The palette is anchored by "Trust Blue" (#0F172A), a deep, authoritative navy that provides a strong foundation for the brand. 

- **Primary & Neutrals:** Use a sophisticated Slate scale for text and borders to maintain a professional, high-contrast environment.
- **Verdict System:** These are functional colors used to indicate property status. They must always be accompanied by icons to ensure accessibility for color-blind users.
- **Severity Palette:** Used specifically for 'Flag' chips and risk indicators. "Critical" uses a near-black red to denote extreme urgency, while "Low" remains neutral to avoid unnecessary alarm.

## Typography

The design system utilizes **Inter** exclusively to leverage its exceptional legibility and systematic feel. 

- **Scale:** A conservative type scale is used to prevent the UI from feeling "loud." 
- **Readability:** Generous line heights (1.5x for body text) are mandated to ensure reports and legal data are easy to digest. 
- **Emphasis:** Use font weight rather than size or color to create hierarchy. Labels should use the `label-md` style with slight letter spacing and uppercase styling to denote metadata or category headers.

## Layout & Spacing

The layout is built on a rigorous **8px grid system**. This mathematical precision reinforces the brand's message of accuracy and order.

- **Grid:** A 12-column fluid grid is used for desktop, collapsing to a single column for mobile. 
- **Mobile-First:** Prioritize vertical stacking. On mobile, margins are set to 16px to maximize content area, while desktop expands to 32px to allow for a more airy, premium feel.
- **Rhythm:** Consistent use of `md` (16px) and `lg` (24px) spacing between related components creates a clear grouping of information. Use `2xl` (48px) to separate major sections.

## Elevation & Depth

To maintain a grounded and professional appearance, this design system uses **Tonal Layers** and **Low-contrast outlines** instead of heavy shadows.

- **Surfaces:** Use subtle background shifts (e.g., White to Slate-50) to differentiate sections.
- **Borders:** 1px solid borders in a light gray (#E2E8F0) are the primary method of containment.
- **Shadows:** Only used for interactive elements like dropdowns or modals. When used, shadows must be "Ambient"—highly diffused, low-opacity (10% or less), and tinted with the Primary Trust Blue to maintain color harmony.

## Shapes

The shape language is **Soft (0.25rem)**. This provides a subtle modern touch without sacrificing the professional "sturdy" feel required by a security product. 

- **Standard Elements:** Buttons, input fields, and small cards use a 4px (0.25rem) radius.
- **Large Containers:** Section containers or large property cards can use a 8px (0.5rem) radius to feel slightly more approachable on larger screens.
- **Interactive States:** Avoid "Pill" shapes for buttons; stick to the Soft radius to maintain the corporate aesthetic.

## Components

- **Buttons:** Primary buttons use the Trust Blue background with White text. Secondary buttons use a Slate-100 background or a simple 1px border. No gradients or "squishy" effects.
- **Verdict Indicators:** Large, clear banners or cards. "Proceed" uses Emerald-50 background with an Emerald-700 border and the Check icon.
- **Risk Flag Chips:** These are small, high-visibility badges. 
    - *Critical:* Dark Red background, White text, Bold weight.
    - *High:* Red-100 background, Red-800 text.
    - *Medium:* Orange-100 background, Orange-800 text.
    - *Low:* Slate-100 background, Slate-700 text.
- **Input Fields:** 1px Slate-200 border, 4px corner radius. Focused state uses a 2px Trust Blue ring with a subtle 2px offset.
- **Data Lists:** Use clean horizontal dividers (1px) with no borders on the left/right to keep the UI open. Use the `label-md` typography for column headers.
- **Security Scorecard:** A specialized card component featuring a large numerical value and the verdict color-coding to summarize a property's risk at a glance.