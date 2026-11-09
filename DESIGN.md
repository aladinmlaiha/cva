---
name: CVA Centros Veterinarios Antúnez
colors:
  surface: '#f2fcf5'
  surface-dim: '#d3dcd6'
  surface-bright: '#f2fcf5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#ecf6f0'
  surface-container: '#e6f0ea'
  surface-container-high: '#e1eae4'
  surface-container-highest: '#dbe5df'
  on-surface: '#151d1a'
  on-surface-variant: '#404943'
  inverse-surface: '#29322e'
  inverse-on-surface: '#e9f3ed'
  outline: '#707972'
  outline-variant: '#c0c9c1'
  surface-tint: '#30694c'
  primary: '#2d674a'
  on-primary: '#ffffff'
  primary-container: '#478061'
  on-primary-container: '#f6fff6'
  inverse-primary: '#98d4b0'
  secondary: '#436370'
  on-secondary: '#ffffff'
  secondary-container: '#c6e8f8'
  on-secondary-container: '#496977'
  tertiary: '#a03b21'
  on-tertiary: '#ffffff'
  tertiary-container: '#c05237'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#b3f0cb'
  primary-fixed-dim: '#98d4b0'
  on-primary-fixed: '#002112'
  on-primary-fixed-variant: '#145136'
  secondary-fixed: '#c6e8f8'
  secondary-fixed-dim: '#abcbdb'
  on-secondary-fixed: '#001f29'
  on-secondary-fixed-variant: '#2b4b58'
  tertiary-fixed: '#ffdad2'
  tertiary-fixed-dim: '#ffb4a2'
  on-tertiary-fixed: '#3c0700'
  on-tertiary-fixed-variant: '#83260e'
  background: '#f2fcf5'
  on-background: '#151d1a'
  surface-variant: '#dbe5df'
typography:
  display-lg:
    fontFamily: Nunito Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Nunito Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Nunito Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Nunito Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Nunito Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: 0em
  headline-sm:
    fontFamily: Nunito Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: 0em
  title-md:
    fontFamily: Nunito Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.03em
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
  space-2xl: 4rem
---

## Brand & Style

The brand personality balances clinical excellence with deep empathy and warmth. Located in Huelva, Spain, the visual character avoids sterile clinical tropes in favor of an organic, Mediterranean-informed reassurance. The interface communicates high-tier veterinary medicine through clear structure, while soft geometry and natural tones reassure pet owners during stressful moments.

The design movement is **Organic Modernism**:
- Natural, warm undertones across all surfaces to eliminate sterile clinical harshness.
- Generous micro-spacing and friendly curvatures that communicate safety and care.
- Crisp utilitarian structure in data displays (medical records, booking steps, prescriptions).
- Subtle, ambient light diffusion that elevates tactile components without looking artificial.

## Colors

The palette directly reflects life, trust, and empathetic action:
- **Primary (`#4E8768` - Sage Green)**: Represents restorative health, natural balance, and calm assurance. Used for brand markers, successful confirmations, standard active states, and reassurance highlights.
- **Secondary (`#264653` - Deep Petrol Blue)**: Adds grounded medical authority, stability, and high-contrast structural framing. Used for dense navigation, primary data labels, and deep header bars.
- **Tertiary / Accent (`#E76F51` - Soft Coral Terracotta)**: An energetic, warm beacon. Strictly reserved for primary conversion points, emergencies, and prominent action triggers (e.g., "Pedir Cita", "Urgencias 24h").
- **Neutral Surface Palette**: The base canvas is built on warm off-white (`#FAFAF7`) and soft linen tinted neutrals (`#F4F6F0`), ensuring zero visual glare while keeping contrast comfortable for stressed or outdoor users.

## Typography

The typographic hierarchy pairs **Nunito Sans** for expressive, humanized headings with **Inter** for clinical clarity.

- **Nunito Sans** introduces soft terminal curvature and open counters, giving medical headers an inviting, welcoming tone that reduces apprehension.
- **Inter** handles clinical data, diagnostic charts, appointments, and long-form advice with neutral precision and high legibility at dense scales.
- Uppercase transformations are strictly avoided except in micro-labels (`label-sm`) and status pills to preserve a calm, conversational voice.

## Layout & Spacing

The layout is grounded in a responsive 12-column grid on desktop and tablet, collapsing to a 4-column system on mobile devices.

- **Desktop (min-width: 1024px)**: 12-column fluid grid, centered inside a max-width container of `1280px`. Margins maintain `3rem` (`space-xl` to `margin`), gutters fixed at `1.5rem`.
- **Tablet (640px to 1023px)**: 8-column layout, `2rem` outer margins, `1.25rem` gutters.
- **Mobile (< 640px)**: 4 columns with `1.25rem` margins and `1rem` gutters. Interactive targets maintain at least 48px tactile touch boundaries.
- **Vertical Spacing**: Section dividers use `space-2xl` (`4rem`) to promote serene breathing room, avoiding information crowding in sensitive clinical contexts.

## Elevation & Depth

Visual hierarchy relies on soft surface stratification combined with warm, diffused drop shadows rather than heavy borders.

- **Surfaces**: Canvas begins at warm tinted linen `#FAFAF7`. Cards and raised surfaces sit on pure `#FFFFFF` or pale sage-tinted panels (`#F4F6F0`).
- **Ambient Shadows**: Shadows use a warm petrol tint (`#264653` at 4% to 8% opacity) rather than pure black, imparting organic depth:
  - *Subtle Card*: `0 2px 8px -2px rgba(38, 70, 83, 0.05), 0 1px 3px rgba(38, 70, 83, 0.04)`
  - *Floating / Hover*: `0 12px 24px -6px rgba(38, 70, 83, 0.08), 0 4px 8px -2px rgba(38, 70, 83, 0.04)`
  - *Modal / Popover*: `0 24px 48px -12px rgba(38, 70, 83, 0.12), 0 8px 16px -4px rgba(38, 70, 83, 0.06)`
- **Border Treatment**: Hairline outlines (`1px solid rgba(38, 70, 83, 0.08)`) define boundaries on flat elements without breaking the tactile softness.

## Shapes

The design system adopts level `2` (Rounded) geometry:
- Standard elements (inputs, secondary buttons, notification banners) feature `0.5rem` (8px) corners.
- Content cards, medical summary panels, and dialog sheets use `1rem` (16px) for a soft, friendly silhouette.
- Modals, prominent hero modules, and image enclosures scale to `1.5rem` (24px).
- Action pills, active status indicators, and pet badge tags use full curvature (`9999px`) to create playful, tactile anchors.

## Components

### Buttons
- **Primary Urgent / CTA (Pedir Cita / Emergencia)**: Background `#E76F51`, text `#FFFFFF`, rounded `0.5rem`. On hover, smooth shift to `#DE5D3D` with subtle glow elevation.
- **Secondary Medical (Servicios / Especialidades)**: Background `#4E8768`, text `#FFFFFF`, rounded `0.5rem`. Hover shifts to `#3F7356`.
- **Tertiary / Neutral**: Background transparent, border `1px solid rgba(38, 70, 83, 0.2)`, text `#264653`.
- **Height & Padding**: 48px height for desktop/touch comfort (`space-md` horizontal padding).

### Chips & Badges
- **Pet Status & Species Chips**: Rounded full (`9999px`), padding `0.25rem 0.75rem`.
- **Success / Healthy**: Background `#EBF3EE`, text `#326147`.
- **Pending / In Treatment**: Background `#FDF1ED`, text `#B84A2E`.
- **General Tag**: Background `#E9EEF0`, text `#264653`.

### Input Fields & Controls
- **Text Inputs**: Height 48px, background `#FFFFFF`, border `1px solid rgba(38, 70, 83, 0.15)`, radius `0.5rem`. Placeholder text in warm gray. On focus: border becomes `#4E8768` with a 3px outer ring tinted at `rgba(78, 135, 104, 0.20)`.
- **Checkboxes & Radios**: 20px size, rounded `4px` (checkbox) or circular (radio), active fill `#4E8768` with a crisp white checkmark or dot.

### Cards
- **Medical / Appointment Card**: Background `#FFFFFF`, rounded `1rem`, border `1px solid rgba(38, 70, 83, 0.06)`, shadow *Subtle Card*. Features an inner warm accent bar on the left edge denoting appointment status or pet type.
- **Info Panels**: Background `#F4F6F0` (soft linen sage), borderless, padding `1.5rem`.

### Specialized Veterinary Components
- **Pet Profile Header**: Avatar enclosure with a 3px border in `#4E8768`, pairing pet name in `title-md` (`Nunito Sans`) and medical chip tags underneath.
- **Vaccination / Timeline Track**: Vertical line in `#E0E7E3` with soft nodes filled in `#4E8768` for completed treatments and `#E76F51` for upcoming boosters.