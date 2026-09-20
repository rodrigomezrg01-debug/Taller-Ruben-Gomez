---
name: Taller Rubén Gómez Precision Industrial
colors:
  surface: '#11131c'
  surface-dim: '#11131c'
  surface-bright: '#373943'
  surface-container-lowest: '#0c0e17'
  surface-container-low: '#191b25'
  surface-container: '#1d1f29'
  surface-container-high: '#282933'
  surface-container-highest: '#33343f'
  on-surface: '#e1e1ef'
  on-surface-variant: '#c3c5d8'
  inverse-surface: '#e1e1ef'
  inverse-on-surface: '#2e303a'
  outline: '#8d90a2'
  outline-variant: '#424656'
  surface-tint: '#b5c4ff'
  primary: '#b5c4ff'
  on-primary: '#00297a'
  primary-container: '#005bf7'
  on-primary-container: '#e6e9ff'
  inverse-primary: '#0051df'
  secondary: '#b5c4ff'
  on-secondary: '#102b6f'
  secondary-container: '#2b4387'
  on-secondary-container: '#9cb2fe'
  tertiary: '#ffb59e'
  on-tertiary: '#5d1800'
  tertiary-container: '#c03a00'
  on-tertiary-container: '#ffe5dd'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b5c4ff'
  on-primary-fixed: '#00174c'
  on-primary-fixed-variant: '#003dab'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b5c4ff'
  on-secondary-fixed: '#00174d'
  on-secondary-fixed-variant: '#2b4387'
  tertiary-fixed: '#ffdbd0'
  tertiary-fixed-dim: '#ffb59e'
  on-tertiary-fixed: '#390b00'
  on-tertiary-fixed-variant: '#842500'
  background: '#11131c'
  on-background: '#e1e1ef'
  surface-variant: '#33343f'
spacing:
  gutter: 1.25rem
  gutter-desktop: 2rem
  margin: 1rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style
The visual identity is forged around automotive mechanical precision, workshop grit, and uncompromising professional reliability. Grounded in Rosario’s heavy automotive and industrial heritage, the experience speaks directly to vehicle owners, fleet managers, and private motorists needing immediate, dependable mechanical solutions.

The aesthetic blends **Industrial Brutalism** with **High-Contrast Modern Utility**:
- **Rugged Honesty:** Raw workshop textures, cool cast concrete, and dark machinery steel avoid corporate sterility while highlighting mechanical mastery.
- **Precision Engineering:** Sharp chamfers, angled cuts, dynamic speed lines, and technical metric callouts.
- **Conversion-Centric Urgency:** High contrast, zero-fluff architecture prioritizing direct mobile interaction via WhatsApp, phone access, and immediate diagnostic booking.
- **Atmosphere:** Deep electric blue tool cabinets, polished hydraulic lifts, matte dark chassis steel, and vibrant safety accents.

## Colors
The palette balances industrial dark metal foundations with vivid electric blues and deliberate conversion-oriented signals.

- **Primary Electric Blue (`#1662FE`):** Represents structural mastery, authority, and mechanical discipline. Secondary tints handle hover depth and pressed surface feedback.
- **Secondary Steel Blue (`#5E74BB`):** Reserved for supporting UI elements, secondary action highlights, and technical accents.
- **Tertiary Accent (`#C03A00`):** Dedicated to urgent status indicators, warnings, and diagnostic alert notices.
- **Neutral Industrial Chassis (`#757682`):** Structural canvas surfaces providing cold metallic depth.

## Typography
The system enforces a dual-typeface protocol:

1. **Barlow Condensed (Display & Impact Labels):**
   - Rendered in uppercase with slight tracking (`0.02em` to `0.08em`) to mirror stamped VIN plates, industrial warning stencils, and automotive signage.
   - High vertical posture delivers visual torque and density without sacrificing legibility on constrained mobile viewports.

2. **Inter (Body & Technical Data):**
   - Provides clear legibility for repair diagnostics, cost breakdowns, technical explanations, and customer reviews.
   - Strict adherence to regular (`400`) and medium (`500`) weights prevents visual clutter on dark textured surfaces.

## Layout & Spacing
The layout adheres to a rigid 12-column grid on desktop screens, transitioning to 6 columns on tablets and 4 columns on mobile devices.

- **Vertical Rhythm:** Content follows an 8px base unit. Component interiors favor dense, compact spacing (`space-sm` to `space-md`) to echo mechanical tooling dashboards, while major sectional separations use `space-xl` and `space-2xl` for stark visual separation.
- **Conversion Zones:** Diagnostic quick-selectors, WhatsApp contact prompts, and review proofs maintain sticky or thumb-zone placement on mobile viewports.
- **Texture Overlays:** Background subtle tire tread vector paths and concrete grain textures are pinned as fixed or low-opacity relative layers (`mix-blend-mode: overlay`, `opacity: 0.04` to `0.07`), preventing interference with readability.

## Elevation & Depth
Depth mimics physical mechanical hardware and structural workshop architecture:

- **Tonal Layers:** Base canvas sits at deep dark tones. Cards, service bay sections, and dialog drawers elevate through subtle surface tiers.
- **Hard Chiseled Inset & Edge Borders:** Replaces soft diffuse drop shadows with 1px structural outlines: `border: 1px solid rgba(255, 255, 255, 0.08)`.
- **Machined Inset Shadows:** Form inputs and service status gauges leverage subtle inner shadows (`box-shadow: inset 0 2px 4px rgba(0, 0, 0, 0.6)`) to convey pressed metal switchboards.
- **Conversion Elevation:** Primary conversion components utilize crisp hard offsets rather than soft ambient blur.

## Shapes
Sharp industrial geometry dominates. Curves are avoided in favor of raw angles and chamfered edges:

- **Zero Standard Radii:** Standard corners are hard 90-degree angles (`border-radius: 0px`).
- **Chamfered / Beveled Cuts:** Primary CTA buttons, badge containers, and hero card frames feature diagonal corner clips.
- **Dividers:** Thick chevron or hazard 45-degree striped diagonal lines deployed sparingly for service division dividers.

## Components

### 1. Angled Action Buttons (CTAs)
- **Primary Mechanic CTA:** Electric Blue `#1662FE` fill with chamfered top-right and bottom-left corners (12px diagonal cut). Text styled in `Barlow Condensed`, bold, uppercase, tracked `0.06em`. On hover, background shifts with a 2px offset right-downward push.
- **Secondary CTA:** `#5E74BB` fill for supporting operational actions and sub-flows.
- **Outline Work-Order Button:** Transparent fill, 2px border, sharp 90-degree corners.

### 2. Floating Badges & Sticky Triggers
- **Trust & Review Badges:** Semi-floating container locked to hero corners containing solid ratings and professional service indicators.
- **Persistent Floating WhatsApp CTA:** Fixed to the bottom-right viewport (24px margin desktop, 16px mobile). High-visibility housing with a pulsed ring alert indicator.

### 3. Service & Diagnostic Cards
- **Construction:** Dark chassis background with 1px border `rgba(255, 255, 255, 0.08)`. Subtle dark tire track SVG watermark in bottom corner at 4% opacity.
- **Card Header:** Heavy condensed headline with an industrial icon framed inside a chiseled square.

### 4. Input Fields & Form Controls
- **Workshop Intake Inputs:** Dark background, inset shadow, border 1px solid. Focused state highlights border in intense `#1662FE` without soft outer glow rings.
- **Plate / Car Selector:** Monospaced or bold uppercase Barlow condensed inputs mimicking license plate formatting.

### 5. Checkboxes, Radios & Switches
- **Custom Industrial Check:** 18x18px squared box, zero radius, 2px border. Checked state fills `#1662FE` with a heavy, sharp white checkmark.

### 6. Chips & Service Badges
- **Status Tags:** Compact, all-caps, 0px border-radius tags utilizing core palette contrasts.