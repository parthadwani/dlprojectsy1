---
name: Collegiate Pulse
colors:
  surface: '#031427'
  surface-dim: '#031427'
  surface-bright: '#2a3a4f'
  surface-container-lowest: '#000f21'
  surface-container-low: '#0b1c30'
  surface-container: '#102034'
  surface-container-high: '#1b2b3f'
  surface-container-highest: '#26364a'
  on-surface: '#d3e4fe'
  on-surface-variant: '#e6bdb8'
  inverse-surface: '#d3e4fe'
  inverse-on-surface: '#213145'
  outline: '#ac8884'
  outline-variant: '#5c403c'
  surface-tint: '#ffb4ab'
  primary: '#ffb4ab'
  on-primary: '#690005'
  primary-container: '#dc2626'
  on-primary-container: '#fff6f5'
  inverse-primary: '#bf0715'
  secondary: '#bec6e0'
  on-secondary: '#283044'
  secondary-container: '#3f465c'
  on-secondary-container: '#adb4ce'
  tertiary: '#ffb95f'
  on-tertiary: '#472a00'
  tertiary-container: '#a06500'
  on-tertiary-container: '#fff7f1'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb4ab'
  on-primary-fixed: '#410002'
  on-primary-fixed-variant: '#93000b'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#031427'
  on-background: '#d3e4fe'
  surface-variant: '#26364a'
typography:
  display-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.01em
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
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.06em
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
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
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system balances institutional prestige with high-octane collegiate vibrancy for university student life, hackathons, and cultural fests. The design language marries architectural modernism with festival-grade energy, creating an authoritative yet electric digital commons for engineering, technology, and arts campuses.

The visual style blends crisp minimalism with subtle glassmorphic depth and selective high-contrast focal points. Precision typography, razor-sharp information density, and structured badge hierarchies ground the academic legitimacy of the institution, while luminous accent washes, radiant status tags, and tactile pass tokens evoke the excitement of live campus experiences.

## Colors

The system uses a dark-first color scheme anchored by deep collegiate slate-navies, delivering rich contrast against campus festival artwork and dynamic category colors.

- **Primary (`#DC2626` / Crimson Red):** High-energy academic crimson used for critical actions, live countdowns, primary registration CTAs, and university heritage highlights.
- **Secondary (`#0F172A` / Collegiate Deep Navy):** The structural backbone, used for base canvas backgrounds, high-level navigation chrome, and rich surface boundaries. Mid-tone navy (`#1E293B`) forms elevated surface card tiers.
- **Tertiary (`#F59E0B` / Varsity Gold):** Spotlights hackathon prizes, featured badges, star-performer showcases, and alert notices.
- **Category Accents:**
  - *Technical / Hackathon:* Electric Violet/Indigo (`#6366F1`)
  - *Cultural & Fest:* Sunset Vermillion (`#E11D48`)
  - *Sports & Athletics:* Electric Emerald (`#10B981`)
  - *Workshops & Seminars:* Cyan / Sky (`#06B6D4`)
- **Neutrals:** Balanced slate palette transitioning from pure text white (`#F8FAFC`), muted captions (`#94A3B8`), structural borders (`#334155`), down to midnight surface fills (`#020617`).

## Typography

The typography pairs the expressive, geometric momentum of **Plus Jakarta Sans** for headlines, ticket titles, and badge classifications with the unmatched legibility and neutral clarity of **Inter** for descriptions, metadata lists, rules, and timetable schedules. Monospace ticketing tokens and QR validation codes rely on **JetBrains Mono**.

Headings use tight letter-spacing to reinforce authority and density, while labels and category badges feature uppercase styling with expanded letter spacing for immediate scanning in crowded schedule streams.

## Layout & Spacing

The portal is built on a responsive 12-column fluid grid system on desktop (max container width 1440px), stepping down to an 8-column layout on tablet (640px - 1024px), and a 4-column stack on mobile devices (<640px).

- **Margins and Gutters:** Wide margins ensure breathing room on larger monitors, scaling down dynamically on mobile screens to preserve ticket readouts.
- **Rhythm:** Spacing follows a modular 8px base rhythm. Micro alignments (text to icon pairings, badge internals) utilize `space-xs` (4px) and `space-sm` (8px). Structural groupings (event item metadata blocks, card padding) utilize `space-md` (16px) and `space-lg` (24px). Section dividers and masthead offsets utilize `space-xl` (40px).

## Elevation & Depth

Visual hierarchy uses layered surface containers tinted with navy slate, backed by frosted glassmorphism and subtle directional glows rather than generic drop shadows.

- **Level 0 (Canvas Base):** Solid `#090D16` deep void.
- **Level 1 (Card & Modular Tier):** `#111827` at 70% opacity with a `backdrop-blur(12px)` and a crisp `1px` translucent border (`rgba(255, 255, 255, 0.08)`).
- **Level 2 (Hover & Active Modals):** `#1E293B` at 90% opacity with ambient crimson or indigo perimeter flares (`0 8px 30px rgba(220, 38, 38, 0.15)` or `0 8px 30px rgba(99, 102, 241, 0.15)`).
- **Level 3 (Floating Bars, Digital Event Passes, & Overlays):** `#0F172A` with `backdrop-blur(20px)`, outer glow, and a high-definition inner hairline border `inset 0 1px 0 rgba(255, 255, 255, 0.15)`.

## Shapes

The roundedness language is set to `2` (Rounded), providing a confident 0.5rem (8px) baseline corner radius for inputs, micro-tags, and buttons, extending to 1rem (16px) for cards, and 1.5rem (24px) for prominent hero banners and mobile action sheets.

- Ticket and Event Pass components employ specialized cut-out notch geometries on left and right edge dividers (`mask-image: radial-gradient(...)`) accompanied by dashed separation strokes to mimic physical event access passes.

## Components

### Buttons
- **Primary Action (Register / Claim Ticket):** Solid Crimson (`#DC2626`) fill, white text, bold weight (`Plus Jakarta Sans`), subtle top-edge highlight, glowing shadow on hover (`0 4px 14px rgba(220, 38, 38, 0.4)`).
- **Secondary / Ghost:** Translucent navy container (`rgba(30, 41, 59, 0.6)`), 1px slate border (`#334155`), white text, hover transitions to solid slate background.
- **Accent Interactive:** Used exclusively for live/streaming events; deep purple/indigo gradients with energetic pulse animations.

### Event Category Badges & Chips
- High-contrast, pill-shaped tags featuring solid 1px borders and 15% opacity fills matched to the event category:
  - Technical: `#6366F1` text with `rgba(99, 102, 241, 0.12)` background.
  - Cultural: `#E11D48` text with `rgba(225, 29, 72, 0.12)` background.
  - Sports: `#10B981` text with `rgba(16, 185, 129, 0.12)` background.
  - Workshops: `#06B6D4` text with `rgba(6, 182, 212, 0.12)` background.
- Micro dot indicator prepended for "Live Now" or "Fast Filling" alerts.

### Event Cards & Tabular Grids
- **Grid Cards:** Rounded-lg surfaces topped with an aspect-ratio-locked visual canvas, gradient scrim overlays, floating category pill, and anchored venue/time stamp row. Hover lifts card -4px with dynamic accent glow.
- **Tabular Agenda View:** Alternating row hover states with strict vertical alignments, monospaced timestamp columns, expandable drill-down drawers for speakers, rules, and registration caps.

### Digital Event Pass & Ticket Patterns
- Multi-segment passes featuring a perforated separator line, barcode/QR validation sector, university seal watermarking, and dynamic holographic rim lighting.

### Form Inputs & Filters
- Inset slate fills (`#0B1120`), razor-thin borders (`#334155`), bright white focused text, and high-visibility crimson focus rings (`0 0 0 2px rgba(220, 38, 38, 0.3)`).