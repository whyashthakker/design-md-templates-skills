---
name: Cloudflare Cloud Identity
version: 1.2.0
colors:
  primary: "#F38020"           # Cloudflare Orange (Brand Heritage)
  secondary: "#0051C3"         # Deep Sea Blue (Primary Links/Actions)
  background:
    dark: "#09090b"            # Surface-Deep (Dark Theme)
    light: "#ffffff"           # Surface-Base (Light Theme)
  brand:
    300: "#FFC28C"
    400: "#F6994F"
    500: "#F38020"             # Core Brand Token
    600: "#D36610"
    700: "#A85100"
  status:
    success: "#059669"         # Emerald Green
    warning: "#FFAC00"         # Amber
    danger: "#D6001B"          # Ruby Red
  text:
    base: "#071428"            # High-emphasis Navy-Black
    muted: "#52525b"           # Mid-emphasis Grey
    on-brand: "#ffffff"        # Text on Orange/Blue backgrounds
  video-bg: "#181818"          # RTC/Meeting Canvas Black
typography:
  fontFamily: "Inter, system-ui, -apple-system, sans-serif"
  googleFont: "Inter"
  baseSize: "16px"
  scales:
    h1: { size: "2.25rem", weight: "700", leading: "2.75rem" }
    h2: { size: "1.75rem", weight: "600", leading: "2.25rem" }
    body: { size: "1rem", weight: "400", leading: "1.5rem" }
    code: { size: "0.875rem", family: "JetBrains Mono, monospace" }
spacing:
  base: 4                      # --rtk-space-1 = 4px
  scale: [0, 4, 8, 12, 16, 24, 32, 48, 64, 96]
borders:
  width: "thin"                # Options: none, thin, fat
  radius: "rounded"            # Options: sharp, rounded, extra-rounded, circular
---

# Design System: Cloudflare Cloud Identity

## Overview
A high-performance, developer-centric aesthetic that balances utility with speed. The system is designed to provide maximum clarity for data-heavy dashboards, realtime collaboration, and infrastructure management.

## Visual Philosophy
- **Speed by Design**: Minimal use of heavy assets; reliance on CSS-based tokens and system fonts.
- **Translucency & Layering**: Use of backdrop-blur and 82% opacity overlays (`rgba(0, 0, 0, 0.82)`) for sidebars and modals.
- **Developer First**: Monospace fonts (`JetBrains Mono`) prioritized for technical data points and code blocks.

## Color Strategy
- **The Orange Thread**: Use `#F38020` sparingly for brand moments, active progress indicators, and primary navigation highlights.
- **The Neutral Palette**: 
  - For **Darkest Theme**: Background-1000 is `#080808`.
  - For **Light Theme**: Background-1000 is `#ffffff` with Surface-900 at `#fafafa`.
- **RTC Constraints**: Video backgrounds (`video-bg`) should always be `#181818` to ensure participant video frames pop without distraction.

## Typography Hierarchy
- **Headings**: Use `Inter` with tight tracking (-0.02em) for high-impact headlines.
- **Interface Labels**: 11px semi-bold, all-caps for section headers in sidebars to maintain a "technical tool" feel.
- **Readability**: Prose text should maintain a line-height of 1.58x with a base size of 15px for long-form documentation.

## Components & Tokens
- **Buttons**:
  - **Action**: Blue (#0051C3) or Orange (#F38020) with `rounded` corners (8px).
  - **Ghost**: Transparent background, `thin` border (#27272a), accent-color text.
- **Sidebars**: Fixed at `min(420px, 100vw)` with a `-10px 0 40px` shadow for depth.
- **Interactive Elements**: All interactive components (inputs/chips) must show a 2px focus ring (`#059669` or `#0a66c2`) on keyboard navigation.

## Spacing & Grid
- **Scale**: Calculated as `base * increment`.
- **Gutter**: 24px (space-6) between main layout sections.
- **Padding**: 14px 16px (header) and 18px 16px (content) for sidebars to optimize vertical scrolling density.

## Do's and Don'ts
- **DO**: Use `googleFont: "Inter"` for automatic font loading via the `provideRtkDesignSystem` utility.
- **DO**: Use `theme: "darkest"` for high-stakes infrastructure environments.
- **DON'T**: Use absolute black (#000000) for surfaces; use Background-1000 (#080808) for a more premium OLED-friendly feel.
- **DON'T**: Mix `sharp` and `extra-rounded` border radii in the same view.