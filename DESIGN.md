---
name: Obsidian Studio
colors:
  surface: '#101319'
  surface-dim: '#101319'
  surface-bright: '#363940'
  surface-container-lowest: '#0b0e14'
  surface-container-low: '#191c22'
  surface-container: '#1d2026'
  surface-container-high: '#272a30'
  surface-container-highest: '#32353b'
  on-surface: '#e1e2eb'
  on-surface-variant: '#bbc9cf'
  inverse-surface: '#e1e2eb'
  inverse-on-surface: '#2d3037'
  outline: '#859399'
  outline-variant: '#3c494e'
  surface-tint: '#47d6ff'
  primary: '#a5e7ff'
  on-primary: '#003543'
  primary-container: '#00d2ff'
  on-primary-container: '#00566a'
  inverse-primary: '#00677f'
  secondary: '#adc6ff'
  on-secondary: '#002e6a'
  secondary-container: '#0566d9'
  on-secondary-container: '#e6ecff'
  tertiary: '#ffd6ae'
  on-tertiary: '#492900'
  tertiary-container: '#ffb159'
  on-tertiary-container: '#734400'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#b6ebff'
  primary-fixed-dim: '#47d6ff'
  on-primary-fixed: '#001f28'
  on-primary-fixed-variant: '#004e60'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#004395'
  tertiary-fixed: '#ffdcbc'
  tertiary-fixed-dim: '#ffb86b'
  on-tertiary-fixed: '#2c1700'
  on-tertiary-fixed-variant: '#683d00'
  background: '#101319'
  on-background: '#e1e2eb'
  surface-variant: '#32353b'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0em
  body-lg:
    fontFamily: Noto Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0.01em
  body-md:
    fontFamily: Noto Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.01em
  body-sm:
    fontFamily: Noto Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-lg:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
  metric-lg:
    fontFamily: JetBrains Mono
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: -0.02em
  metric-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0em
  metric-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '400'
    lineHeight: 12px
    letterSpacing: 0.02em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  space-2xs: 0.125rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.25rem
  space-2xl: 1.5rem
  space-3xl: 2rem
  touch-target-min: 3rem
  control-bar-height: 4.5rem
  tool-strip-height: 3.5rem
---

## Brand & Style

This design system delivers a high-precision, tactile digital darkroom tailored for demanding mobile photographers, retouchers, and visual creators on Android. The aesthetic fuses Material 3 Expressive mechanics with the restrained utility of professional studio hardware. It respects the image canvas above all else: chrome recedes into deep obsidian layers, while fine optical accents provide instant orientation and state recognition without causing perceptual color pollution.

### Personality Archetypes
- **Precision Engineered:** Every control prioritizes pixel-accurate tactile engagement, calibrated zero-detents, and immediate visual verification.
- **Atmospheric & Immersive:** Deep obsidian and cold charcoal tonal tiers prevent eye fatigue in low-light environments and allow accurate evaluation of exposure and chromatic balance.
- **Tactile & Responsive:** Controls behave like physical studio consoles—subtle luminous micro-states, calibrated friction, and snappy spring curves.

### Design Movement & Core Expression
The system adopts an **Engineered Studio Dark** style: ultra-crisp hairline dividers (0.5dp to 1dp at 8–12% opacity), 16px to 24px surface-reactive backdrops, pill-shaped tool nodes, and luminescent optical badges. Heavy skeuomorphism is avoided; instead, physical mechanical feel is achieved via dual-track zero-centered sliders, luminous color wheels, and monospaced diagnostic telemetry.

## Colors

The palette is engineered specifically for darkroom image editing. Neutral backgrounds sit below 18% luminance to ensure natural color adaptation when grading photos.

### Surfaces & Neutral Architecture
- **Surface 00 (Canvas Void):** `#0B0D11` — The infinite viewport background behind the active photo canvas.
- **Surface 01 (Base Chrome):** `#12151B` — Bottom tool docks, full-height inspectors, and navigation rails.
- **Surface 02 (Container / Cards):** `#1A1E26` — Tool drawers, floating control shelves, tool options sheets.
- **Surface 03 (Elevated / Flyout):** `#242933` — Floating HUDs, active control pills, popovers, and menu cards.
- **Surface 04 (Interactive Component):** `#2E3644` — Inactive track backgrounds, pill chips, segmented switch containers.

### Accent & Functional Energy
- **Primary Cyan (`#00D2FF`):** Indicates active tool selection, high-precision slider fills, active crop bounds, and primary export actions. Emits a 6px `rgba(0, 210, 255, 0.25)` ambient edge bloom when dragging.
- **Secondary Cobalt (`#3B82F6`):** Secondary interactive nodes, brush size anchors, selection rings, and multi-state selection chips.
- **Adjustment Warmth (`#FF9F1C`):** Dedicated to destructive or warm adjustments (Color Temperature, Kelvin counters, highlights, split-toning highlights, and exposure clipping alerts).
- **Critical & Negative (`#EF4444`):** Mask deletion, reset history branch, clipping alerts for blacks/shadows.
- **Confirmed & Neutral Active (`#10B981`):** Non-destructive snapshot saved, lossless metadata sync.

### Boundaries & Ghost Outlines
- **Hairline Border:** `rgba(255, 255, 255, 0.08)` on Surface 01 and 02.
- **Focused Hairline:** `rgba(0, 210, 255, 0.50)` for selected parameter tiers.
- **Subtle Divider:** `#1F242E` for structural separations in complex tool sheets.

## Typography

Typography balances global Latin readability with native Hindi typographic rhythm.

- **Primary Interface (Inter):** Applied across all high-level headers, modes, action buttons, tool categories, and primary prompts. Tightly kerned at display sizes to ensure compact density.
- **Content & Localization (Noto Sans):** Powers all descriptive labels, tool explanations, toast notifications, metadata displays, and full Hindi script strings. Noto Sans guarantees that complex Hindi conjuncts and matras render clearly without vertical clipping in constrained Android containers.
- **Telemetry & Metrics (JetBrains Mono):** Critical for real-time photo metrics: Kelvin readouts (e.g., `5600 K`), RGB/HSL coordinates (`#FF9F1C`, `H:38° S:100% L:55%`), EV stops (`+0.65 EV`), exposure histograms, and aspect ratios (`16:9`, `4:5`). Tabular lining numerals prevent UI jittering when sliding adjustments.

## Layout & Spacing

The layout is built around an edge-to-edge hardware visualizer philosophy. The image canvas remains in a flexible, isolated viewport while control strips hover or dock with thumb-driven reachability.

### Grid & Ergonomics
- **Vertical Tool Docks (Phone Portrait):** 
  - Primary bottom command strip: `control-bar-height` (72dp) pinned directly above the gesture navigation bar with dynamic inset handling (`windowInsets.navigationBars`).
  - Secondary adjustment shelf: `tool-strip-height` (56dp) stacked immediately above the command strip.
- **Horizontal Landscape & Tablet Foldable:** The viewport flips to a split-stage paradigm: 75% unoccluded photo preview on the left; a 320dp or 360dp docked vertical inspector palette pinned to the right edge.
- **Touch Target Integrity:** All sliders, nodes, adjustment dials, and pill switches maintain an absolute touch envelope of at least 48dp (`touch-target-min`), even if visual indicators measure only 4dp to 24dp.
- **Rhythm:** An 8dp structural grid with 4dp sub-step intervals for tight diagnostic readouts. Margin gutters are locked at 16dp on mobile and 24dp on tablets.

## Elevation & Depth

This system avoids diffuse drop shadows, which obscure contrast and degrade color fidelity in dark environments. Depth is established through **calibrated surface luminescence, backdrop refraction, and luminous active states.**

### The 4-Tier Surface Stack
1. **Tier 0 (Root Base - `#0B0D11`):** Completely flat. Non-interactive backdrop that absorbs light.
2. **Tier 1 (Structural Toolbars - `#12151B`):** 1dp top hairline of `rgba(255, 255, 255, 0.08)`. No directional shadow.
3. **Tier 2 (Floating Adjusters & Overlays - `rgba(26, 30, 38, 0.82)`):** Employs hardware-accelerated `backdrop-filter: blur(16px)`. Border is an all-around 1dp stroke of `rgba(255, 255, 255, 0.10)`. Gives the impression of precision optical glass hovering over the image canvas.
4. **Tier 3 (Modals, Color Wheels & Diagnostic Flyouts - `#242933`):** 1dp border of `rgba(255, 255, 255, 0.14)`. Enhanced with an ambient ground contact glow: `0 8px 32px rgba(0, 0, 0, 0.65)`.

### Optical Active Glow
When controls are actively engaged by touch:
- Sliders and focal rings cast an inner and outer optical glow: `box-shadow: 0 0 12px rgba(0, 210, 255, 0.35)`.
- Orange/Warm adjustment nodes cast: `box-shadow: 0 0 12px rgba(255, 159, 28, 0.35)`.

## Shapes

The shape system blends high-precision pill contours with ergonomic rounded cards, ensuring tactile feel and clean separation from the rectangular photo frame.

- **Interactive Buttons & Filter Chips (Pill / Full Stadium):** Tool nodes, state chips, comparison toggles, and parameter badges use full pill radius (9999dp). This distinguishes tools from the rectangular photo canvas.
- **Adjustment Drawers & Sheets (`rounded-2xl` / 24dp):** Top corners of bottom sheets use 24dp smooth squircle curves.
- **Floating HUDs & Tool Palettes (`rounded-xl` / 16dp):** Floating parameter overlays utilize 16dp radius for balanced compactness.
- **Segmented Control Segments (`rounded-lg` / 8dp):** Inner segments inside pill containers nest with 8dp radii to maintain balanced spacing.
- **Slider Thumbs:** Perfectly circular 20dp thumb elements with a 3dp concentric core ring.

## Components

### 1. Dual-Track Zero-Point Centered Sliders
- **Visual Design:** 4dp thick inactive track in `#242933` with a 1dp center notch indicator (`rgba(255, 255, 255, 0.40)`). 
- **Active Behavior:** The active fill originates from the exact 0 center point and extends left or right according to value. Negative values use Primary Cyan (`#00D2FF`) or muted cool tones; positive values use Adjustment Warmth (`#FF9F1C`) or Primary Cyan depending on the parameter.
- **Thumb Element:** 20dp circular node filled with `#FFFFFF` and backed by a 2dp `#12151B` inner border. On active drag, the thumb scales to 24dp with an accent bloom (`0 0 14px rgba(0, 210, 255, 0.40)`).
- **Telemetry Readout:** A floating pill HUD floats 32dp above the thumb displaying parameter and metric (e.g., `Exposure  +0.45 EV` or `Tint  -12`) using `metric-md` in JetBrains Mono.

### 2. Segmented Circular Hue & Saturation Wheel
- **Structure:** 220dp circular module with an outer 24dp continuous radial spectrum band and a deep dark interior field (`#12151B`).
- **Reticle:** A floating 18dp crosshair ring that glides within the gamut. The reticle ring has a 2dp white stroke with an outer dark drop outline to maintain visibility against bright hues.
- **Segmented Pips:** 8 equidistant quick-select pips (R, O, Y, G, C, B, P, M) positioned along the perimeter for instant channel isolation.

### 3. Non-Destructive History Chips
- **Geometry:** 32dp high pill-shaped chips (`rounded-full`). Inactive state: `#1A1E26` background, 1dp border `rgba(255, 255, 255, 0.08)`, text in `label-md`.
- **Active State:** Cyan surface tint `rgba(0, 210, 255, 0.12)`, 1dp border `#00D2FF`, text in `#00D2FF`.
- **Branching Indicator:** A trailing 6dp dot indicates if subsequent edits exist downstream from that history state.

### 4. Split-View Comparison Toggle
- **Control Element:** Pinned floating pill button at top center or top right of the canvas viewport.
- **Interaction Model:**
  - *Hold down (Press & Hold):* Instantly swaps preview canvas to original unedited RAW buffer; releases back to current pipeline.
  - *Swipe horizontally:* Drops a vertical hairline divider across the photo that users drag left and right to inspect a real-time before/after wipe.

### 5. Input Fields & Metric Steppers
- **Geometry:** 40dp height, dark surface `#1A1E26` with 1dp border `rgba(255, 255, 255, 0.10)`.
- **Typographic Treatment:** Numerical values use `metric-md` (JetBrains Mono). Labels sit above or inline in `label-sm` (Inter).
- **Focused State:** Border brightens to `#00D2FF` with an inner 1dp glow. Inline stepper increments (`+` / `-`) have distinct 32dp touch squares with haptic feedback on actuation.

### 6. Modal Bottom Sheets & Tool Drawers
- **Shell:** Background `#12151B` with `backdrop-filter: blur(24px)` where transparency is permitted.
- **Drag Handle:** 36dp wide, 4dp thick pill in `rgba(255, 255, 255, 0.20)`, 8dp from top edge.
- **Header:** Sticky row with secondary dismiss (`✕`) and confirmation (`✓`) iconography in high-contrast white and cyan. Bilingual labels provide clean paired English and Hindi script titles without vertical truncation.