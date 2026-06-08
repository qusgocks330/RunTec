---
name: Kinetic Slate
colors:
  surface: '#111316'
  surface-dim: '#111316'
  surface-bright: '#37393d'
  surface-container-lowest: '#0c0e11'
  surface-container-low: '#1a1c1f'
  surface-container: '#1e2023'
  surface-container-high: '#282a2d'
  surface-container-highest: '#333538'
  on-surface: '#e2e2e6'
  on-surface-variant: '#c5c9ac'
  inverse-surface: '#e2e2e6'
  inverse-on-surface: '#2f3034'
  outline: '#8e9378'
  outline-variant: '#444933'
  surface-tint: '#aed500'
  primary: '#ffffff'
  on-primary: '#293500'
  primary-container: '#c7f300'
  on-primary-container: '#576c00'
  inverse-primary: '#526600'
  secondary: '#ffb59a'
  on-secondary: '#5a1b00'
  secondary-container: '#ff5e07'
  on-secondary-container: '#531900'
  tertiary: '#ffffff'
  on-tertiary: '#2e3135'
  tertiary-container: '#e1e2e7'
  on-tertiary-container: '#626469'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c7f300'
  primary-fixed-dim: '#aed500'
  on-primary-fixed: '#171e00'
  on-primary-fixed-variant: '#3d4d00'
  secondary-fixed: '#ffdbce'
  secondary-fixed-dim: '#ffb59a'
  on-secondary-fixed: '#370e00'
  on-secondary-fixed-variant: '#802a00'
  tertiary-fixed: '#e1e2e7'
  tertiary-fixed-dim: '#c4c6cb'
  on-tertiary-fixed: '#191c20'
  on-tertiary-fixed-variant: '#44474b'
  background: '#111316'
  on-background: '#e2e2e6'
  surface-variant: '#333538'
typography:
  display-hero:
    fontFamily: Anybody
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Anybody
    fontSize: 32px
    fontWeight: '800'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Anybody
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.2'
  body-lg:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Space Mono
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.1em
  metric-xl:
    fontFamily: Anybody
    fontSize: 64px
    fontWeight: '900'
    lineHeight: '1'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 16px
  margin-mobile: 20px
  margin-desktop: 40px
  stack-sm: 8px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style

The design system is engineered for the high-performance athlete. It draws inspiration from the raw, unyielding nature of stone and the aerodynamic precision of professional sports gear. The aesthetic is a hybrid of **Minimalism** and **Glassmorphism**, designed to feel both grounded and technologically advanced.

The visual narrative focuses on "Speed through Friction"—using the dark, textured slate background to represent the track and the "Electric Lime" accents to represent the athlete's energy. Surfaces are treated with semi-transparent, frosted finishes to maintain a sense of depth while allowing the rugged background texture to remain a constant visual anchor. The overall mood is serious, competitive, and highly focused.

## Colors

The palette is built upon a high-contrast foundation to ensure maximum legibility during movement.

- **Primary (Electric Lime):** Used exclusively for critical action points, progress indicators, and performance metrics. It represents peak "go" energy.
- **Secondary (Vibrant Orange):** Reserved for alerts, competition status changes, and secondary highlights to distinguish from the primary flow.
- **Neutral / Slate:** A range of deep charcoals and muted slates derived from the reference stone texture. 
- **Glass Surfaces:** Components utilize a `rgba(44, 47, 51, 0.6)` fill with a 20px backdrop blur to create a high-tech, layered appearance without obscuring the organic background.

## Typography

Typography is used to convey momentum. All headlines and display metrics utilize **Anybody** with a forced italic slant and heavy weights to mimic the "high-speed" athletic character found in performance branding.

- **Anybody (Display/Headlines):** High-impact, bold, and italicized. Used for race times, rank, and headers.
- **Geist (Body):** A technical, precise sans-serif used for readability in descriptions and settings.
- **Space Mono (Labels/Data):** Used for micro-copy and technical data points (e.g., GPS coordinates, heart rate labels) to emphasize the "Tec" aspect of the app.

## Layout & Spacing

The layout employs a **Fluid Grid** with a tight, disciplined 4px baseline shift. 

- **Mobile:** A 4-column layout with 20px side margins. Elements are primarily stacked to allow for easy one-handed thumb interactions while running.
- **Desktop/Tablet:** A 12-column grid. Information density increases, with secondary metrics moving to side rails.
- **Visual Rhythm:** Large vertical gaps (`stack-lg`) are used to separate distinct training phases or race data blocks, ensuring the UI feels "breathable" even with high-contrast elements.

## Elevation & Depth

Depth is achieved through **Glassmorphism** and subtle **Tonal Layers** rather than traditional shadows.

1.  **Level 0 (Base):** The stone/slate texture background.
2.  **Level 1 (Cards/Containers):** Semi-transparent charcoal fills (`#2C2F33` at 60% opacity) with a 1px inner border of white at 10% opacity to define the edge.
3.  **Level 2 (Modals/Popovers):** Higher opacity (`80%`) with a more pronounced backdrop blur (40px) to pull focus.

Shadows, when used, are "Ambient Glows"—using the Primary Electric Lime color at very low opacity (10-15%) to make active elements appear as if they are radiating energy onto the stone surface.

## Shapes

The design system uses a **Soft (0.25rem)** roundedness. While the brand is aggressive, slightly softened corners on containers and buttons prevent the UI from feeling "sharp" or "hostile." 

- **Buttons:** Use the standard `rounded` (4px) setting.
- **Input Fields:** Maintain the 4px radius for a structured, professional look.
- **Data Chips:** Use `rounded-xl` (12px) to create a pill-like distinction for status tags or category markers.

## Components

- **Primary Action Buttons:** Solid Electric Lime fill with black bold italic text. No shadows. High-speed aesthetic.
- **Glass Cards:** Used for statistics and leaderboards. They must feature a subtle 1px border to separate them from the dark stone background.
- **Performance Chips:** Small, high-contrast markers using the Secondary Orange or Electric Lime for status (e.g., "LIVE", "PR", "FASTEST").
- **Segmented Controls:** Designed to look like athletic gear toggles—flat, matte charcoal backgrounds with a sliding Electric Lime indicator.
- **Input Fields:** Ghost-style inputs with only a bottom border or a very faint semi-transparent background fill. Focus states should trigger an Electric Lime bottom-glow.
- **Progress Bars:** Thick, 8px tracks with the textured background visible inside the "empty" portion, and a solid Electric Lime "fill" representing progress.