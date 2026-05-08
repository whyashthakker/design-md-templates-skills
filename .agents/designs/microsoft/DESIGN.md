---
name: Microsoft (Fluent)
colors:
  background: "#ffffff"
  foreground: "#242424" # colorNeutralForeground1
  brand: "#0078d4"      # colorBrandBackground
  muted: "#616161"      # colorNeutralForeground2
  border: "#e0e0e0"     # colorNeutralStroke1
  card: "#ffffff"
  accent: "#0078d4"
  
  dark:
    background: "#1f1f1f" # colorNeutralBackground1
    foreground: "#ffffff"
    muted: "#d1d1d1"
    border: "#444444"
    card: "#292929"
    accent: "#479ef5"

typography:
  fontFamily:
    sans: "Segoe UI, system-ui, -apple-system, sans-serif"
    mono: "Cascadia Code, Consolas, monospace"
  body:
    fontSize: "14px"
    lineHeight: "1.42"
    fontWeight: "400"
  heading:
    fontWeight: "600"
    letterSpacing: "-0.01em"

rounded:
  default: "4px"
  md: "6px"
  lg: "8px"
---

# Design System: Microsoft (Fluent)

## Overview
Fluent 2 is Microsoft's cross-platform design system. It is built on the principles of Light, Depth, Motion, Material, and Scale, aiming to create a natural and intuitive user experience that feels native on every device.

## Design Philosophy
1. **Depth & Layering:** Uses elevation (shadows) and "Materials" (Mica, Acrylic) to create a clear sense of hierarchy and focus.
2. **Adaptive & Coherent:** Designed to feel at home on Windows, iOS, Android, and the Web while maintaining a recognizable Microsoft identity.
3. **Inclusive by Default:** Accessibility (contrast, focus states, screen reader support) is baked into every primitive and token.
4. **Productive Elegance:** Focuses on clear typography and consistent spacing to handle professional, data-dense applications.

## Colors
- **The Microsoft Blue (#0078D4):** A versatile, professional blue used for primary actions and brand presence.
- **Semantic Tokens:** Relies heavily on "Alias" tokens (e.g., `colorNeutralBackground1`) to ensure colors adapt perfectly between Light, Dark, and High Contrast modes.
- **Subtle Layering:** Dark mode uses high-tier grays (`#1F1F1F` to `#292929`) rather than pure black to allow for soft depth and shadow effects.

## Typography
- **Segoe UI:** The cornerstone of the Microsoft experience. It is a humanist sans-serif designed for high legibility and a friendly, open feel.
- **Predictable Scales:** Uses a standardized "Type Ramp" from Caption to Display, ensuring consistency in hierarchy.

## Components
- **Cards & Surfaces:** Often feature "Depth 4" or "Depth 8" shadows to pop against the background.
- **Buttons:** Rounded (4px to 6px) with clear interaction states (Hover, Pressed) defined by specific token shifts.
- **The Navigation Rail:** A minimalist vertical navigation pattern used for high-level app switching.

## Visual Effects
- **Acrylic & Mica:** Uses semi-transparent, blurred backgrounds (Acrylic) and "Mica" (a desktop-specific material that samples the wallpaper) to create a premium, OS-integrated feel.
- **Soft Shadows:** Multi-layered, soft shadows that simulate physical light sources.
- **Motion:** Purposeful, fast transitions (usually 150-250ms) that provide feedback without slowing down the user.
