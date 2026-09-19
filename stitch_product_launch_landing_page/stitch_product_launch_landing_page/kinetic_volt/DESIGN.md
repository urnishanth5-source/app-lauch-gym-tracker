---
name: Kinetic Volt
colors:
  surface: '#111412'
  surface-dim: '#111412'
  surface-bright: '#373a37'
  surface-container-lowest: '#0c0f0d'
  surface-container-low: '#191c1a'
  surface-container: '#1d201e'
  surface-container-high: '#282b28'
  surface-container-highest: '#323533'
  on-surface: '#e1e3df'
  on-surface-variant: '#bccbb9'
  inverse-surface: '#e1e3df'
  inverse-on-surface: '#2e312f'
  outline: '#869585'
  outline-variant: '#3d4a3d'
  surface-tint: '#4ae176'
  primary: '#4be277'
  on-primary: '#003915'
  primary-container: '#22c55e'
  on-primary-container: '#004b1e'
  inverse-primary: '#006e2f'
  secondary: '#7dffa2'
  on-secondary: '#003918'
  secondary-container: '#05e777'
  on-secondary-container: '#00622e'
  tertiary: '#50dfa4'
  on-tertiary: '#003824'
  tertiary-container: '#28c38a'
  on-tertiary-container: '#004a31'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6bff8f'
  primary-fixed-dim: '#4ae176'
  on-primary-fixed: '#002109'
  on-primary-fixed-variant: '#005321'
  secondary-fixed: '#62ff96'
  secondary-fixed-dim: '#00e475'
  on-secondary-fixed: '#00210b'
  on-secondary-fixed-variant: '#005226'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#111412'
  on-background: '#e1e3df'
  surface-variant: '#323533'
typography:
  display-lg:
    fontFamily: Lexend
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
  display-lg-mobile:
    fontFamily: Lexend
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
  headline-xl:
    fontFamily: Lexend
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-xl-mobile:
    fontFamily: Lexend
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
  headline-md:
    fontFamily: Lexend
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Lexend
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Inter
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 12px
  stat-counter:
    fontFamily: Lexend
    fontSize: 28px
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
  gutter: 1rem
  gutter-md: 1.5rem
  gutter-lg: 2rem
  margin: 1rem
  margin-md: 2rem
  margin-lg: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

The design system projects high-octane performance, clinical precision, and athletic vitality. It targets dedicated athletes, bodybuilders, and nutrition-focused fitness enthusiasts who demand instant, unambiguous data feedback during intense workouts or strict dietary logging.

The aesthetic fuses **Athletic High-Contrast Dark Mode** with **Precision Performance Minimalism**. A deep, pitch-black slate base creates an infinite-depth canvas where vibrant neon green kinetic accents ignite crucial metrics, action items, and biometric progress. Sleek structural cards with razor-thin luminescence replace bulky skeuomorphism, driving focus toward typography and vital metrics. The visual tone is commanding, disciplined, and technologically superior—evoking the atmosphere of a professional training facility equipped with telemetry and biometric tracking.

## Colors

The color palette centers on intense contrast between an ultra-dark athletic arena canvas and high-voltage biological greens:

- **Primary (`#22C55E`)**: High-voltage athletic green used for key actions, confirmed states, progress meters, and dominant calls-to-action (e.g., Direct APK Download).
- **Secondary (`#00E676`)**: Electric hyper-neon green reserved for high-impact metric counters, interactive highlights, active states, and energetic telemetry pulses.
- **Tertiary (`#10B981`)**: Deep jade green serving as a supportive tonal layer for secondary graphs, safe zones, and subtle gradient stops.
- **Neutral Surface Ecosystem**:
  - `Canvas Background`: `#0A0D0B` (Near-pitch carbon black for total eye comfort in low-light gym environments).
  - `Surface Tier 1`: `#121614` (Elevated cards, modals, and navigation shelves).
  - `Surface Tier 2`: `#181E1B` (Interactive elements, input backgrounds, active pills).
  - `Border / Hairline`: `rgba(34, 197, 94, 0.15)` or `rgba(255, 255, 255, 0.08)` for crisp edge demarcation.
- **Typography & Content**:
  - `Primary Text`: `#FFFFFF` for sharp display titles and key metrics.
  - `Secondary Text`: `#94A3B8` (Slate) for subheadings, captions, and nutritional unit labels.
  - `Muted Text`: `#475569` (Dark Slate) for disabled states, structural rules, and peripheral guidance.

## Typography

The typographic hierarchy combines **Lexend** for display titles and numeric telemetry with **Inter** for dense, rapid nutritional tracking and body text. 

- **Lexend (Headlines & Performance Data)**: Optimized for fast visual processing. Headlines must always project authority and dynamism. For numeric values (macros, calorie counters, workout reps), Lexend's wide apertures and deliberate geometry prevent ambiguity in high-movement workout contexts.
- **Inter (Body, Labels & Technical Documentation)**: Delivers surgical legibility across step-by-step installation guides, ingredient lists, download disclosures, and security metadata.
- **Uppercase Usage**: Applied selectively to small metadata, chip labels (`label-sm`), step indicators (`STEP 01`), and trust badge verification tags with loose tracking (`letter-spacing: 0.08em`) to mimic sports timing electronics.

## Layout & Spacing

The layout implements a responsive 12-column grid system built on an 8-point structural cadence:

- **Mobile Viewports (<640px)**: 4-column layout, `margin: 1rem`, `gutter: 1rem`. Full-width modular cards with high edge proximity maximize screen estate for thumb interactions.
- **Tablet Viewports (640px - 1024px)**: 8-column layout, `margin-md: 2rem`, `gutter-md: 1.5rem`. Split layouts for QR display alongside installation instructions.
- **Desktop & Wide Displays (>1024px)**: 12-column fixed-max layout (`max-width: 1280px`), `margin-lg: 3rem`, `gutter-lg: 2rem`. Dual-pane composition pairing interactive acquisition cards with rich telemetry previews.

Vertical rhythm relies on tight grouping: related components (e.g., download buttons and security badges) are bound by `space-sm` or `space-md`, while major thematic clusters are partitioned by `space-xl`.

## Elevation & Depth

Rather than conventional drop shadows that muddy deep dark backgrounds, the elevation model employs **luminescent edge tracing** and **tonal stacking**:

- **Ground Level (Canvas)**: `#0A0D0B`. Flat, absolute backdrop.
- **Level 1 (Card & Module Layer)**: `#121614` with a 1px perimeter border of `rgba(255, 255, 255, 0.06)`. On hover or active states, the border softly shifts to `rgba(34, 197, 94, 0.3)`.
- **Level 2 (Modals, Download Sheets & Floating Toolbars)**: `#181E1B` surface layered over a backdrop-filter blur (`backdrop-blur-md`, `rgba(10, 13, 11, 0.85)`). Outlined with `rgba(34, 197, 94, 0.25)`.
- **Level 3 (Neon Glows & Visual Accent Highlights)**: Reserved strictly for high-priority elements (e.g., Primary Download Action, QR Code Frame). Achieved via `box-shadow: 0 0 24px rgba(34, 197, 94, 0.25), 0 0 4px rgba(0, 230, 118, 0.5)`.

## Shapes

With `roundedness: 2`, structural surfaces incorporate moderate, athletic curves that eliminate harshness while maintaining mechanical precision:

- **Standard Elements (Buttons, Inputs, Small Badges)**: `0.5rem` (8px). Clean and tactile under finger touch.
- **Containers & Cards (`rounded-lg`)**: `1.0rem` (16px). Encloses data blocks, nutrition statistics, and step items.
- **Modals & Elevated Flyouts (`rounded-xl`)**: `1.5rem` (24px). Defines sheet dialogues, download containers, and hero QR presentation modules.
- **Pill Accents**: Full circular radii (`9999px`) are strictly applied to dynamic status chips, verification checkmarks, and trust indicators.

## Components

### Buttons
- **Primary Athletic Button (Direct APK Download)**: Solid `#22C55E` fill with `#0A0D0B` text in Lexend Semibold. Features a subtle radial highlight effect and an icon-left download glyph. Focus/Hover initiates a kinetic energy glow: `box-shadow: 0 0 20px rgba(34, 197, 94, 0.4)`.
- **Secondary Store Button (Google Play / App Store)**: Background `#181E1B`, 1px border of `rgba(255, 255, 255, 0.15)`, `#FFFFFF` text. Icon styled in native or monochrome neon green.
- **Ghost / Tertiary Button**: Transparent background, text `#94A3B8`, hover transition to `#00E676` with zero background shift.

### Download Modal & Screen Modules
- **Modal Wrapper**: Center-anchored or mobile-bottom sheet with `#121614` background, 1px perimeter border in `rgba(34, 197, 94, 0.2)`, and a heavy dark backdrop blur.
- **QR Code Frame**: A high-contrast crisp `#FFFFFF` substrate wrapped in a sleek `#181E1B` bezel with corner registration marks tinted `#22C55E`. Paired with a micro-label: "SCAN TO INSTALL DIRECTLY".
- **Installation Timeline / Steps**: Numbered steps (1 to 3) utilizing circular badges (`24px` diameter) with green borders and `Lexend` numeric fonts. Step descriptions use `Inter` with muted slate subtext detailing browser permission overrides ("Allow unknown sources").
- **Trust Badges & Security Proof**: Inline pill badges composed of `#181E1B` background, a vibrant `#10B981` shield or lock glyph, and text: "SHA-256 Verified", "VirusTotal Clean", or "Direct Official Build".

### Cards & Telemetry Blocks
- **Card**: Surface `#121614`, 1px hairline border, containing bold metric headers in `Lexend` alongside slate body descriptions.
- **Interactive State**: Border transitions to primary green with a delicate internal gradient trace on hover.

### Inputs & Selectors
- **Input Fields**: `#0A0D0B` base, `#181E1B` border, transitioning to `#22C55E` border on focus. Text `#FFFFFF`, placeholder `#475569`.
- **Checkboxes & Radios**: 20px square/circle with `rgba(255, 255, 255, 0.1)` border. Checked state snaps to `#22C55E` with an absolute dark checkmark icon.

### Status Chips & Progress Indicators
- **Macro Chips**: Compact pills featuring high-contrast numeric values (e.g., "180g Protein") with deep green tinted backgrounds (`rgba(34, 197, 94, 0.1)`) and `#00E676` typography.
- **Linear Progress Bars**: Track in `#181E1B`, bar fill powered by a linear gradient from `#10B981` to `#22C55E`.