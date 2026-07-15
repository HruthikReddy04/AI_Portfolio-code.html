---
name: Architect Portfolio
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
  on-surface-variant: '#584237'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#8c7164'
  outline-variant: '#e0c0b1'
  surface-tint: '#9d4300'
  primary: '#9d4300'
  on-primary: '#ffffff'
  primary-container: '#f97316'
  on-primary-container: '#582200'
  inverse-primary: '#ffb690'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#006398'
  on-tertiary: '#ffffff'
  tertiary-container: '#00a2f4'
  on-tertiary-container: '#003554'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbca'
  primary-fixed-dim: '#ffb690'
  on-primary-fixed: '#341100'
  on-primary-fixed-variant: '#783200'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#cde5ff'
  tertiary-fixed-dim: '#93ccff'
  on-tertiary-fixed: '#001d32'
  on-tertiary-fixed-variant: '#004b74'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display:
    fontFamily: Plus Jakarta Sans
    fontSize: 64px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.7'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1200px
  gutter: 24px
  margin-mobile: 20px
  section-gap: 120px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

This design system is built for a senior software engineer portfolio, emphasizing technical precision and professional maturity. The aesthetic is rooted in **Minimalism** with a **Corporate/Modern** influence, prioritizing content clarity over decorative elements.

The target audience includes hiring managers, technical recruiters, and potential collaborators who value structured thinking and clean execution. The UI should evoke a sense of calm confidence through generous whitespace, high contrast, and a systematic approach to component layout. By removing visual noise, the design allows the engineer's work and technical stack to become the primary focus.

## Colors

The palette is anchored by a high-contrast foundation of **Deep Navy (#0F172A)** and **White (#FFFFFF)**. This pairing establishes an immediate sense of authority and readability.

- **Primary Action**: The **Warm Orange (#F97316)** is used sparingly for call-to-action buttons, active states, and critical highlights. Its warmth offsets the cool navy tones, drawing the eye to conversion points.
- **Surface Strategy**: Use the neutral slate shades for secondary text and background containers to create subtle separation without breaking the minimalist aesthetic.
- **Hierarchy**: Navy is reserved for headings and primary text; Orange for interactive elements; Slate for metadata and secondary body text.

## Typography

This design system employs a dual-font strategy. **Plus Jakarta Sans** is used for headlines to provide a modern, slightly geometric character that feels approachable yet professional. **Inter** is utilized for all body copy and UI labels to ensure maximum legibility and a systematic, clean feel.

- **Scale**: Large display sizes use tight line-heights and negative letter-spacing to create a "premium editorial" look.
- **Rhythm**: Body text utilizes a relaxed line-height (1.6 - 1.7) to improve long-form reading comfort in project descriptions and blog posts.
- **Contrast**: Use font weight (SemiBold/Bold) rather than color alone to distinguish information hierarchy.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop, centering content within a 1200px container to maintain control over line lengths. 

- **Grid**: A 12-column grid is used for desktop project galleries, while a single-column focused layout is used for deep-dive case studies.
- **Whitespace**: Utilize a generous "Section Gap" (120px) to clearly demarcate different parts of the portfolio (e.g., separating Work from About).
- **Mobile Adaptation**: On mobile, margins shrink to 20px, and the 12-column grid collapses into a single vertical stack. Padding within cards should remain consistent (24px or 32px) to maintain the premium feel.

## Elevation & Depth

To maintain a modern, "flat-plus" aesthetic, this design system uses **Ambient Shadows** and **Tonal Layers** rather than heavy skeuomorphism.

- **Base Level**: The primary background is pure white.
- **Card Level**: Project cards and containers use a subtle, extra-diffused shadow (`0 10px 40px rgba(15, 23, 42, 0.05)`) to lift them slightly off the background.
- **Hover State**: Interactive cards should subtly lift on hover, increasing shadow spread and adding a 1px border in the primary orange color or a slightly darker navy to indicate focus.
- **Depth Cues**: Use very light grey backgrounds (`#F8FAFC`) for secondary sections (like a "Tech Stack" marquee) to create depth without adding shadows.

## Shapes

The shape language is consistently **Rounded**, striking a balance between technical rigidity and modern friendliness.

- **Standard Elements**: Buttons and input fields use a 0.5rem (8px) radius.
- **Containers**: Project cards and large image containers use a 1rem (16px) radius (`rounded-lg`) to create a softer, more premium look.
- **Accents**: Small tags or chips for "Tech Stack" labels should use a fully rounded (pill) shape to distinguish them from functional buttons.

## Components

### Buttons
- **Primary**: Solid Warm Orange background with White text. Bold weight. Minimal 8px rounding.
- **Secondary**: Deep Navy outline (1.5px) with Navy text. Transitions to a light Navy tint on hover.
- **Ghost**: No border, Slate text. Transitions to Navy text on hover.

### Cards
Project cards are the core of this system. They feature a white background, the defined "Card Level" ambient shadow, and a 16px corner radius. Images within cards should be flush to the top or have a consistent inner padding of 24px.

### Chips / Tags
Small, pill-shaped indicators for technologies (e.g., "React", "TypeScript"). Use a light Slate background (`#F1F5F9`) with dark Slate text. Keep font size small (12-14px).

### Input Fields
Clean, 1.5px bordered boxes using a light grey border. On focus, the border transitions to Deep Navy with a soft orange glow (ring shadow).

### Lists & Navigation
Navigation links should use `label-md` styling. Active states are indicated by a small orange dot below the text or a change in weight to SemiBold. Use horizontal spacing of 32px between nav items.