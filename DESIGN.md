---
name: Telemetry Precision
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
  on-surface-variant: '#40484d'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#70787e'
  outline-variant: '#bfc8ce'
  surface-tint: '#096686'
  primary: '#00516b'
  on-primary: '#ffffff'
  primary-container: '#136a8a'
  on-primary-container: '#b8e5ff'
  inverse-primary: '#89d0f4'
  secondary: '#b41765'
  on-secondary: '#ffffff'
  secondary-container: '#fe579d'
  on-secondary-container: '#610032'
  tertiary: '#2f4d66'
  on-tertiary: '#ffffff'
  tertiary-container: '#47657f'
  on-tertiary-container: '#c4e2ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c0e8ff'
  primary-fixed-dim: '#89d0f4'
  on-primary-fixed: '#001e2b'
  on-primary-fixed-variant: '#004d66'
  secondary-fixed: '#ffd9e3'
  secondary-fixed-dim: '#ffb0c9'
  on-secondary-fixed: '#3e001e'
  on-secondary-fixed-variant: '#8e004c'
  tertiary-fixed: '#cce5ff'
  tertiary-fixed-dim: '#abcae7'
  on-tertiary-fixed: '#001e31'
  on-tertiary-fixed-variant: '#2b4a62'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  headline-xl:
    fontFamily: Chivo
    fontSize: 56px
    fontWeight: '900'
    lineHeight: 64px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Chivo
    fontSize: 36px
    fontWeight: '900'
    lineHeight: 42px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Chivo
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Chivo
    fontSize: 28px
    fontWeight: '800'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Chivo
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Chivo
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: 0em
  body-lg:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0em
  body-md:
    fontFamily: Space Grotesk
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Space Grotesk
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.05em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes an uncompromising, high-performance automotive engineering visual identity tailored for an elite motorsport workshop. The visual language bridges pit-lane telemetry diagnostics, ECU flashing interfaces, and precision mechanical craftsmanship.

### Aesthetic Foundation
- **Style:** Technical Motorsport Minimalism combined with High-Contrast Telemetry. Crisp structural surfaces, fine structural outlines, and rapid visual hierarchies prioritize tactical data legibility and mechanical authority.
- **Tone & Mood:** Surgical, assertive, unyielding, and technologically advanced. The aesthetic avoids generic automotive tropes (like tire treads or carbon fiber faux skeuomorphism) in favor of authentic dyno-readout precision, anodized finishes, and race-grade telemetry cues.
- **Audience:** Track enthusiasts, Subaru performance owners, professional racing teams, and high-spec automotive builders demanding uncompromising dyno verification and engineering excellence.

## Colors

The color palette is engineered specifically for bright, high-clarity daylight environments, evoking professional dynamometer control rooms and chassis dyno heads-up displays under high-illumination workshop conditions.

### Palette Architecture
- **Primary (`#136A8A`):** Petroleum cyan. Applied to structural highlights, telemetry tracks, verified metrics, and active technical selectors. It bridges deep automotive hydraulics with cold digital readout interfaces.
- **Secondary (`#FF589E`):** High-rpm sport fuchsia. Reserved strictly for peak-value callouts, primary conversion triggers (e.g., Dyno Booking, Urgent Alerts, Rev Limit Indicators), and active racing states.
- **Tertiary (`#0E3047`):** Dark celestial blue. Serves as container borders, elevated card fills, and secondary state surfaces, providing layered atmospheric depth.
- **Neutral Canvas (`#FFFFFF`):** Machined alloy chassis. Anchors all backgrounds with balanced light mode integrity, supplemented by elevated panel overlays.
- **Text & Foreground:** Crisp dark slate for primary typography, with high-contrast technical specs and telemetry metadata.

## Typography

The typography system pairs high-velocity display mechanics with computational precision:
- **Headlines (Chivo):** Set with a pronounced italic slant (`font-style: italic`) and heavy weights (700–900) on key hero headers and category dividers to project forward momentum and aerodynamic drive.
- **Body (Space Grotesk):** Provides structured geometric readability for technical explanations, service write-ups, and diagnostic summaries.
- **Labels & Telemetry (JetBrains Mono):** Monospaced, tabular-numeral execution for power runs (WHP/TQ), boost pressures (PSI/BAR), air-fuel ratios, VIN codes, and status tags. All telemetry markers must be rendered in uppercase.

## Layout & Spacing

A 12-column fluid grid defines layout consistency across desktop and tablet, collapsing to a 4-column structured grid on mobile. 

### Grid & Density Rules
- **Desktop (1024px+):** 12 columns, 24px (`1.5rem`) gutters, 48px (`3rem`) margins. Content containers max out at 1280px to maintain tight data density.
- **Tablet (768px – 1023px):** 8 columns, 16px (`1rem`) gutters, 32px (`2rem`) margins.
- **Mobile (< 768px):** 4 columns, 16px (`1rem`) gutters, 20px (`1.25rem`) margins.
- **Rhythm:** Layout distances follow strict 8pt step increments. Component internals utilize tight padding (`space-xs` to `space-md`) to emulate condensed instrumentation panels. Section dividers utilize razor-thin single-pixel layout rules rather than broad empty gaps.

## Elevation & Depth

Visual depth is achieved through structural light surface layering and hairline technical borders rather than soft, diffuse drop shadows.

### Elevation Hierarchy
- **Base Surface (`#FFFFFF`):** Ground level. Zero elevation.
- **Chassis Level 1 (`#F8FAFC`):** Standard cards and interactive segments. Outlined with a 1px solid `#0E3047` border.
- **Cockpit Level 2 (`#F1F5F9`):** Flyouts, dropdown overlays, active telemetry modules, and modals. Outlined with a 1px solid `#136A8A` border.
- **Aura & Focus Glows:** High-priority elements (such as dyno run status and live diagnostic warnings) employ directional cyan or fuchsia neon bloom shadows:
  - Cyan Glow: `0 0 16px -2px rgba(19, 106, 138, 0.25)`
  - Fuchsia Peak Glow: `0 0 20px -2px rgba(255, 88, 158, 0.30)`

## Shapes

The shape system utilizes deliberate, industrial corners with `0.25rem` (4px) radii. Soft curves are prohibited to preserve an instrument-grade, CNC-machined character.

### Shape Characteristics
- **Standard Corners:** 4px radius across buttons, inputs, tags, and cards.
- **Technical Chamfer:** High-order display cards and hero banners utilize a subtle 45-degree corner cut (clipped corner of 8px to 12px) on top-right edges via CSS `clip-path` to evoke lightweight aero fairings and race-spec chassis plates.

## Components

### Buttons
- **Primary (Action / Booking):** `#FF589E` background with `#FFFFFF` bold text. Upper-case italicized Chivo. Hover state transitions to `#E11D48` with a sport fuchsia aura glow.
- **Secondary (Telemetry / Tech Specs):** `#F8FAFC` background with a 1px `#136A8A` solid border. Text in dark slate with monospaced label prefix. Hover fills surface to `#0E3047` with white text.
- **Destructive / Abort:** Flat `#F8FAFC` background, 1px `#FF589E` border, text `#FF589E`.

### Dyno & Telemetry Badges (Chips)
- Structured with an integrated 2-part block: a 6px status pill light (`#FF589E` for live, `#136A8A` for calibrated) paired with monospaced JetBrains Mono uppercase metadata (e.g., `AWD-DYNO // RUN 04`). Background `#F8FAFC`, border 1px `#0E3047`.

### Precision Engineered Cards
- Clean light background (`#F8FAFC`) encased in a subtle 1px border (`#0E3047`).
- Top header features a technical sub-label in `#136A8A` (JetBrains Mono, 10px uppercase), followed by an italicized Chivo title.
- Metric display blocks inside cards utilize large tabular mono numerals flanked by unit indicators (e.g., `542.8` `WHP`).

### Input Fields
- Fill: `#FFFFFF`. Border: 1px `#0E3047`. Text: dark slate. Monospaced helper/label annotations positioned above.
- Focus: Border snaps instantly to `#136A8A` accompanied by an inner hairline glow.

### Checkboxes & Segmented Controls
- Checkboxes: 16x16px square with 2px radius, `#FFFFFF` interior, 1px `#0E3047` boundary. Checked state fills `#FF589E` with a crisp white tick.
- Drivetrain Selector (AWD / 2WD): Segmented metal rocker switch styled container. Selected state lights up `#136A8A` with pure white bold mono typography.