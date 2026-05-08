---
name: Google (Material 3)
colors:
  background: "#fef7ff"
  foreground: "#1d1b20"
  brand: "#6750a4"      # Primary
  muted: "#49454f"      # Outline/Muted
  border: "#79747e"     # Outline
  card: "#f3edf7"       # Surface Variant
  accent: "#625b71"     # Secondary
  success: "#24a148"
  danger: "#b3261e"     # Error
  
  dark:
    background: "#141218"
    foreground: "#e6e1e5"
    muted: "#cac4d0"
    border: "#938f99"
    card: "#211f26"
    accent: "#ccc2dc"

typography:
  fontFamily:
    sans: "Roboto, system-ui, -apple-system, sans-serif"
    mono: "Roboto Mono, monospace"
  body:
    fontSize: "16px"
    lineHeight: "1.5"
    fontWeight: "400"
  heading:
    fontWeight: "500"
    letterSpacing: "0"

rounded:
  default: "12px" # M3 uses 12px for cards/buttons by default
  md: "12px"
  lg: "16px"
  full: "9999px"
---

# Design System: Google (Material 3)

## Overview
Material 3 (Material You) is Google’s latest evolution of its design language. It is defined by personalization, accessibility, and an adaptive color system that responds to the user's environment.

## Design Philosophy
1. **Material You:** The brand is the user. The system uses dynamic color extraction to create a unique tonal palette based on the user's wallpaper.
2. **Adaptive Accessibility:** Uses a tonal palette system (0–100) to guarantee contrast ratios across any color combination.
3. **Personal & Expressive:** Moves away from the rigid grid of Material 2 toward softer shapes, larger interactive targets, and playful motion.
4. **Coherent Hierarchy:** Uses three tiers of tokens (Reference, System, Component) to manage complexity across platforms.

## Colors
- **The Tonal System:** Colors are defined by their luminance rather than just hue. Primary, Secondary, and Tertiary roles each have their own tonal range.
- **Surface Variant:** Used for secondary containers and cards to create subtle depth without relying on heavy shadows.
- **On-Colors:** A strict system where every background color has a corresponding "On" color (e.g., `On Primary`) for high-contrast text and icons.

## Typography
- **Roboto & Roboto Flex:** The primary font family, engineered for maximum legibility and flexibility in both digital and print.
- **Variable Weights:** Uses variable font technology to subtly shift weights based on the user's device or environment.

## Components
- **FAB (Floating Action Button):** Now often larger and square-rounded (`16px`) rather than a perfect circle.
- **Navigation Bar:** A horizontal bottom bar with large, rounded pill-shaped indicators for the active state.
- **Cards:** Feature a standard `12px` rounding and often use the "Surface Variant" color instead of a border.

## Visual Effects
- **Dynamic Color:** The primary visual flourish. The entire UI shifts its hue to match the user's context.
- **Soft Shadows:** Uses very subtle, multi-layered shadows that feel more like "ambient occlusion" than traditional drop shadows.
- **State Layers:** Interactive elements use an overlay (usually `8%` to `12%` opacity) to indicate hover and focus states.
