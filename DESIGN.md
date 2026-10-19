---
name: Obsidian & Iris Auth
colors:
  surface: '#111319'
  surface-dim: '#111319'
  surface-bright: '#373940'
  surface-container-lowest: '#0c0e14'
  surface-container-low: '#191b22'
  surface-container: '#1e1f26'
  surface-container-high: '#282a30'
  surface-container-highest: '#33343b'
  on-surface: '#e2e2eb'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#e2e2eb'
  inverse-on-surface: '#2e3037'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#ddb7ff'
  on-secondary: '#490080'
  secondary-container: '#6f00be'
  on-secondary-container: '#d6a9ff'
  tertiary: '#4edea3'
  on-tertiary: '#003824'
  tertiary-container: '#00885d'
  on-tertiary-container: '#000703'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#f0dbff'
  secondary-fixed-dim: '#ddb7ff'
  on-secondary-fixed: '#2c0051'
  on-secondary-fixed-variant: '#6900b3'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#111319'
  on-background: '#e2e2eb'
  surface-variant: '#33343b'
typography:
  headline-xl:
    fontFamily: Geist
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Geist
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Geist
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Geist
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '400'
    lineHeight: 14px
    letterSpacing: 0.05em
  code-token:
    fontFamily: JetBrains Mono
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: 0.2em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-tablet: 2rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

The design system projects uncompromised security, precision engineering, and effortless executive elegance. Built for modern identity orchestration, zero-trust authentication, and secure client portals, the aesthetic balances deep optical blacks with a vibrant, razor-sharp electric iris gradient. 

The aesthetic fuses modern minimalism with dark-mode structural glass and directional luminosity:
- **Atmosphere:** Deep, ink-toned backgrounds anchored by quiet, ultra-subtle ambient indigo and violet lighting along focal axes.
- **Confidence:** Pin-sharp vector framing, clean borders, crisp typography, and restrained tactile feedback to reassure users that their credentials are safe.
- **Tone:** Technical, institutional, yet fluid and frictionless. Micro-interactions are deliberate, swift (150–200ms cubic-bezier), and never theatrical.

## Colors

The palette is engineered around dark-mode clarity with high luminance contrast for input validation, brand framing, and status feedback.

- **Primary (`#6366F1` - Electric Indigo):** The focal anchor for primary authentication actions, active input rings, and active state transitions.
- **Secondary (`#A855F7` - Vivid Violet):** Used to produce dynamic linear gradients paired with the primary color, imparting depth to hero action buttons and identity card borders.
- **Tertiary (`#10B981` - Emerald Matrix):** Reserved strictly for successful states, password strength verification indicators, and verified passkey markers.
- **Neutral (`#0B0D13` - Obsidian Canvas):** The foundational substrate. Supports surface layers:
  - Surface Tier 1 (Background): `#0B0D13`
  - Surface Tier 2 (Auth Card): `#12151F` with 80% opacity
  - Surface Tier 3 (Input & Interactive Wells): `#1A1E2C`
  - Border Tier (Subtle strokes): `rgba(255, 255, 255, 0.08)`
  - Active Border: `rgba(99, 102, 241, 0.5)`
  - Text Primary: `#FFFFFF`
  - Text Secondary: `#94A3B8`
  - Text Muted: `#64748B`

## Typography

The type hierarchy pairs **Geist**—an ultra-clean, proportional grotesque with high horizontal efficiency—with **JetBrains Mono** for technical micro-copy, MFA/TOTP codes, biometric prompts, and form labels.

- **Display & Headlines:** Set tight with negative tracking (`-0.02em` to `-0.03em`) to create a compact, confident posture suited for identity banners and modal titles.
- **Labels & Micro-copy:** Form labels, validation rules, token indicators, and helper strings adopt `JetBrains Mono` with uppercase tracking (`+0.04em`) to simulate high-security operational instruments.
- **Scale Optimization:** On viewports below 640px, headlines scale down automatically via the `-mobile` tokens to prevent line wraps on identity terms (e.g., "Two-Factor Authentication").

## Layout & Spacing

Authentication experiences require strict visual anchoring. The system relies on a centered single-card module across mobile/tablet, expanding into an asymmetric split-canvas on wide viewports (left: decorative brand glow and value proposition; right: focused auth flow).

- **Grid Model:** 12-column fluid grid on desktop (max width `1280px`), adapting to 8 columns on tablet, and a 4-column container on mobile.
- **Card Constraints:** The central auth card has a strict horizontal clamp: `min(100%, 440px)` for single-column flows (sign-in, MFA verification) and `min(100%, 520px)` for multi-step onboarding/registration.
- **Form Rhythm:** Stack fields strictly using `space-md` (`16px`) between standard elements and `space-xl` (`40px`) between logical groups (e.g., identity inputs vs. social OAuth options).

## Elevation & Depth

Visual hierarchy uses **tonal layering and glassmorphism** backed by directional specular lighting:

1. **Canvas (Level 0):** Deep void (`#0B0D13`) accented by an organic, fixed radial gradient positioned top-center (`radial-gradient(ellipse at 50% -20%, rgba(99, 102, 241, 0.15), transparent 70%)`).
2. **Auth Card (Level 1):** Semi-transparent obsidian layer (`#12151F` at 85% opacity) with a `24px` backdrop-filter blur. Edges are articulated by an inset `1px` gradient border (`linear-gradient(180deg, rgba(255, 255, 255, 0.12), rgba(255, 255, 255, 0.02))`).
3. **Interactive Recesses (Level 2):** Input fields and token cells sit inverted within the surface using a darker fill (`#1A1E2C` at 60% opacity) and a crisp outline (`1px solid rgba(255, 255, 255, 0.06)`).
4. **Active Lift (Level 3):** Dropdown menus, tooltips, and credential status sheets cast an ambient shadow: `0 20px 40px -15px rgba(0, 0, 0, 0.7)`, with an indigo-tinted ambient glow: `0 0 24px -4px rgba(99, 102, 241, 0.15)`.

## Shapes

The design system embraces a **Soft (Level 1)** geometry, establishing an engineered, architectural precision:

- **Base Corner Radius (`0.25rem` / `4px`):** Used for micro-badges, checkbox nodes, and progress indicators.
- **Component Medium (`0.5rem` / `8px`):** Applied to input fields, social auth buttons, action CTAs, and MFA single-digit boxes.
- **Container Large (`0.75rem` / `12px`):** The primary radius for authentication cards, segmented control bars, and floating modal panels.
- **Special Elements:** Avatar and biometric passkey scanners employ explicit circles (`50%`), contrasting sharp input rectangles with organic biometric cues.

## Components

### Buttons
- **Primary Auth CTA:** Gradient fill (`linear-gradient(135deg, #6366F1 0%, #A855F7 100%)`) over a white label. Hover accelerates the gradient angle and triggers an outer glow (`0 0 20px rgba(99, 102, 241, 0.4)`). Active state applies a slight scale down (`scale(0.98)`).
- **Secondary / Social OAuth Buttons:** Glass surface (`rgba(255, 255, 255, 0.03)`), border `1px solid rgba(255, 255, 255, 0.08)`. Layout is icon left, centered mono/sans text. Hover raises the surface luminosity (`rgba(255, 255, 255, 0.06)`) and transitions border to `rgba(255, 255, 255, 0.18)`.

### Input Fields
- **Container:** Minimum height `48px`, background `rgba(26, 30, 44, 0.6)`, corner radius `8px`, border `1px solid rgba(255, 255, 255, 0.08)`.
- **Text:** Input values render in Geist `14px` (`#FFFFFF`), with placeholder text in `#64748B`.
- **Labeling:** Floating or top-aligned `JetBrains Mono` label at `11px`, `#94A3B8`, tracked out `+0.05em`.
- **Focus State:** Border shifts cleanly to `#6366F1`, coupled with a soft focus ring (`box-shadow: 0 0 0 3px rgba(99, 102, 241, 0.2)`). No default browser outlines.
- **Action Trailing:** Password reveals and copy triggers use monochrome icons that shift to white on hover.

### MFA / OTP Code Cells
- Set of 6 segmented input wells with dimension `48px` wide by `56px` tall.
- Center-aligned display using `code-token` typography. Filled boxes transition border to `#6366F1` with an inner caret pulse.

### Checkboxes & Segmented Controls
- **Checkbox:** `18px × 18px` square with `4px` radius. Border `1px solid rgba(255, 255, 255, 0.15)`. Checked state displays a solid `#6366F1` fill with an inset white checkmark vector.
- **Remember Me / Session Row:** Flex alignment with label, supporting subtle inline link ("Forgot password?") aligned right with primary color hover.

### Auth Cards & Separators
- **Dividers ("or continue with"):** Thin `1px` rule using `rgba(255, 255, 255, 0.08)` split by centered `11px` uppercase JetBrains Mono label on background `#12151F`.
- **Card Shell:** Features a hairline top border highlight representing an ambient rim light: `linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.2), transparent)`.

### Password Strength Meter
- 4 segmented micro-bars (`3px` height, `2px` radius) transitioning in real-time:
  - Weak: `#EF4444` (1 bar)
  - Medium: `#F59E0B` (2-3 bars)
  - Strong: `#10B981` (4 bars with subtle green glow)