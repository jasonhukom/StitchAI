---
name: Executive Precision
colors:
  surface: '#f8f9ff'
  surface-dim: '#cedbf0'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dde9ff'
  surface-container-highest: '#d7e3f9'
  on-surface: '#101c2c'
  on-surface-variant: '#44474d'
  inverse-surface: '#253141'
  inverse-on-surface: '#eaf1ff'
  outline: '#75777e'
  outline-variant: '#c4c6ce'
  surface-tint: '#4d5f7d'
  primary: '#000615'
  on-primary: '#ffffff'
  primary-container: '#0b1f3a'
  on-primary-container: '#7587a7'
  inverse-primary: '#b5c7ea'
  secondary: '#765b00'
  on-secondary: '#ffffff'
  secondary-container: '#fece4b'
  on-secondary-container: '#725800'
  tertiary: '#755b00'
  on-tertiary: '#ffffff'
  tertiary-container: '#cea72c'
  on-tertiary-container: '#503d00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#b5c7ea'
  on-primary-fixed: '#071c36'
  on-primary-fixed-variant: '#364764'
  secondary-fixed: '#ffdf94'
  secondary-fixed-dim: '#efc13e'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#594400'
  tertiary-fixed: '#ffe08e'
  tertiary-fixed-dim: '#ecc246'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#584400'
  background: '#f8f9ff'
  on-background: '#101c2c'
  surface-variant: '#d7e3f9'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.005em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
  code-snippet:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
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

This design system is tailored for an ambitious Junior Backend and DevOps Engineer aiming to project architectural maturity, absolute reliability, and understated luxury. Departing from typical dark hacker terminal tropes, it bridges rigorous infrastructure engineering with executive-tier craftsmanship. The aesthetic merges contemporary minimalism with bespoke luxury publishing: deep navy structure, warm tactile paper whites, and micro-calibrated gold accents.

### Visual Style
- **Minimalist Structuralism:** Generous whitespace, razor-sharp architectural layout lines, structured metadata grids, and disciplined restraint.
- **Material Warmth:** Grounded on pure white canvas with stacked warm cream and paper surfaces, rejecting sterile pure grays in favor of warm, tactile, high-end editorial substrates.
- **Precious Accents:** Restrained metallic gold accents used solely for critical focus indicators, active states, key metric highlights, and refined edge borders.

## Colors

The palette establishes an immediate sensation of executive stability, combining naval authority with the bespoke refinement of gold leaf detailing.

### Roles & Semantic Applications
- **Primary (`#0B1F3A` - Dark Navy):** The structural anchor. Applied to dominant headers, navigation bars, primary CTA button fills, terminal headers, and high-impact structural blocks.
- **Deep Navy (`#07162A`):** Used for deep contrast contexts such as DevOps architecture diagrams, embedded live code consoles, dark terminal surfaces, and footer regions.
- **Secondary (`#F4C542` - Bright Gold Yellow):** The primary focus and signature accent. Used sparingly for interactive focus rings, metric badges, brand insignias, commit graphs, and high-priority status indicators.
- **Tertiary (`#C9A227` - Gold Border):** Subtle, refined luxury framing. Reserved for deliberate hairline borders, active card strokes, tab underlines, and timeline connectors.
- **Soft Gold (`#E4C96A`):** Low-contrast gold tint. Applied to tag badge backgrounds (with alpha), icon hover washes, and secondary subtle markers.
- **Neutral (`#1D2939` - Dark Charcoal):** Primary typographic color. Offers high legibility without the jarring starkness of pure `#000000`.
- **Secondary Text (`#667085` - Muted Gray):** Applied to secondary descriptions, timestamps, pipeline execution runtimes, and metadata.
- **Canvas (`#FFFFFF` - Pure White):** Root viewport background for crisp negative space.
- **Card Surface (`#FCFAF5` - Warm White):** Elevated container backgrounds, project cards, and reading planes.
- **Secondary Background (`#F5F0E6` - Soft Cream):** Section alternation, code block surroundings, metric highlight panels, and structural sidebars.

## Typography

The typography leverages **Plus Jakarta Sans** across all primary hierarchies, providing clean modernist geometric forms tempered by humanist warmth. When presenting technical DevOps specifications, terminal output, CI/CD telemetry, or backend configurations, an auxiliary monospaced font (**JetBrains Mono**) is deployed to maintain technical credibility.

### Typographic Guidelines
- **Hero & Section Headlines:** Use tight negative letter spacing (`-0.03em` to `-0.015em`) with deep navy (`#0B1F3A`) to impart editorial gravitas.
- **Eyebrow Headers & Badges:** Utilize `label-sm` set in all-caps with generous letter-spacing (`0.08em`) to delineate system architecture modules and project types.
- **Technical Metrics & Code:** All runtime logs, latency measurements, uptime percentages, and environment variables strictly use `code-snippet`.

## Layout & Spacing

The layout is built upon a 12-column responsive fluid grid system designed with structured mathematical rhythm. Generous vertical breathing room signals technical clarity and confidence.

### Grid & Breakpoints
- **Desktop (1200px+):** 12-column grid, `margin: 3rem`, `gutter: 1.5rem`. Max container bound: 1280px.
- **Tablet (768px - 1199px):** 8-column grid, `margin: 2rem`, `gutter: 1.25rem`.
- **Mobile (< 768px):** 4-column grid, `margin: 1.25rem`, `gutter: 1rem`.

### Vertical Rhythm
- Architecture schematics, system performance cards, and repository overviews maintain a consistent `space-lg` gap on desktop and `space-md` on mobile.
- Section-to-section transitions utilize large architectural clearances of `5rem` to `7rem`, maintaining the spacious luxury tone.

## Elevation & Depth

Depth is established primarily through **tactile paper layering and gold hairline borders** rather than thick drop shadows, creating an ultra-clean, high-craft physical presence.

### Layering Model
1. **Base Plane (0dp):** Pure White (`#FFFFFF`).
2. **Substrate Section Layer (1dp):** Soft Cream (`#F5F0E6`) utilized for background alternation.
3. **Elevated Card Layer (2dp):** Warm White (`#FCFAF5`) enclosed in a crisp 1px gold border (`#C9A227` at 20% opacity: `rgba(201, 162, 39, 0.2)`). Shadows are ultra-diffuse and warm-tinted: `0px 4px 24px -2px rgba(11, 31, 58, 0.04)`.
4. **Interactive Hover & Modal Tier (3dp):** Elevated cards subtly shift upwards by `-2px`, and the border shifts to active gold (`#C9A227` at 60% opacity) with shadow `0px 12px 32px -4px rgba(11, 31, 58, 0.08)`.
5. **Console & Deep Tech Inset Layer:** Deep Navy (`#07162A`) card planes embedded with a 1px border of `#0B1F3A` and inner hairline stroke of `rgba(244, 197, 66, 0.15)`.

## Shapes

The design system incorporates geometric balance: confident, spacious containers counterbalanced by softened radii. Per the design specification, project cards and prominent panels utilize `rounded-xl` (`1.5rem` / `24px`) to establish a relaxed, premium silhouette.

### Component Radii Mapping
- **Project Cards & Console Enclosures:** `rounded-xl` (`1.5rem` / `24px`).
- **Interactive Controls & Input Fields:** `rounded-lg` (`1rem` / `16px`).
- **Pills, Badges & Micro Chips:** `rounded-full` (`9999px`) for tech stacks, uptime indicators, and status tags.

## Components

### Buttons
- **Primary Button:** Dark Navy (`#0B1F3A`) fill, pure white text, `label-md`. Border: 1px solid transparent. Hover: Background lifts to `#152E52` with subtle bottom border highlight of Bright Gold (`#F4C542`). Focus: 2px ring in Bright Gold (`#F4C542`) offset by 2px.
- **Secondary / Outline Button:** Transparent fill, Dark Navy text (`#0B1F3A`), 1.5px border of Gold (`#C9A227`). Hover: Warm White (`#FCFAF5`) fill with Soft Gold (`#E4C96A`) border.
- **Tech Action (Terminal/CLI):** Deep Navy (`#07162A`) fill, Monospace JetBrains Mono text, Bright Gold (`#F4C542`) leading cursor icon `$` or `>`.

### Cards & Project Showcases
- Background: Warm White (`#FCFAF5`).
- Border: 1px solid `rgba(201, 162, 39, 0.25)`.
- Border Radius: `rounded-xl` (`1.5rem`).
- Internal Padding: `space-xl` (`2.5rem`) on desktop; `space-lg` (`1.5rem`) on mobile.
- Features: Integrated metric tags, backend architecture badges, and subtle gold accent bar (`2px` height) across top edge upon hover.

### Chips & Badges
- **Skill / Tech Stack Chip (Kubernetes, Go, AWS, Docker):** Soft Cream background (`#F5F0E6`), Dark Charcoal (`#1D2939`) text, 1px hairline border of `rgba(201, 162, 39, 0.3)`.
- **Status / Health Badge:** `rounded-full` pill with a 6px glowing dot in Bright Gold (`#F4C542`) and text in Dark Navy (`#0B1F3A`).

### Form Elements & Inputs
- Background: Pure White (`#FFFFFF`).
- Border: 1.5px solid `rgba(102, 112, 133, 0.3)`.
- Active / Focus: Border transitions smoothly to Gold Border (`#C9A227`), ringed with `4px rgba(244, 197, 66, 0.15)`.

### Architecture & Infrastructure Components
- **System Architecture Visualizer Block:** Deep Navy (`#07162A`) canvas enclosed with `rounded-xl`, populated with glowing micro-diagrams, gold connection paths (`#C9A227`), and JetBrains Mono latency counters.
- **CI/CD Pipeline Tracker:** Horizontal flow diagram with Warm White nodes connected by Gold hairlines, displaying micro-indicators for build phases, latency metrics, and test coverage ratios.