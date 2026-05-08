---
name: CRED
colors:
  background: "#0d0d0d"
  foreground: "#ffffff"
  brand: "#e5fe40"      # Neo Paccha (Green)
  muted: "#8a8a8a"
  border: "#3d3d3d"
  card: "#121212"
  accent: "#6a35ff"     # Poli Purple
  secondary: "#ff8744"  # Orange Sunshine
  
  # CRED is strictly dark-first
  dark:
    background: "#0d0d0d"
    foreground: "#ffffff"
    muted: "#8a8a8a"
    border: "#3d3d3d"
    card: "#121212"
    accent: "#6a35ff"

typography:
  fontFamily:
    sans: "Gilroy, Inter, system-ui, sans-serif"
  body:
    fontSize: "14px"
    lineHeight: "1.6"
    fontWeight: "500"
  heading:
    fontWeight: "800"
    letterSpacing: "0.02em"

rounded:
  default: "0px" # NeoPOP philosophy uses sharp, rigid geometry
  md: "0px"
  full: "9999px"
---

# Design System: CRED (NeoPOP)

## Overview
CRED's design system, NeoPOP, is a fusion of Neomorphism and Pop Art. It is a luxury-first, high-contrast environment designed to make financial management feel like a high-stakes game.

## Design Philosophy
1. **The Art of Finance:** Rejects the "boring" look of traditional banking for a retro-futuristic, pop-art aesthetic.
2. **Hard Geometry:** Intentionally avoids border-radius (0px) to create a sense of rigid, "engineered" precision.
3. **High Elevation:** Uses hard, non-blurred shadows to create 3D depth, making components feel like physical "blocks" on a screen.
4. **Vibrant Voltage:** Uses neon-like "voltage" colors (Purple, Green, Orange) against a deep black canvas to create visual "pop."

## Colors
- **Neo Paccha (#E5FE40):** A vibrant, neon-green used for primary status indicators and brand energy.
- **Poli Purple (#6A35FF):** A deep, saturated purple used for primary actions and CTA highlights.
- **Pop Black (#0D0D0D):** The signature "pure" background that provides the foundation for the high-contrast elements.

## Typography
- **Gilroy:** A geometric sans-serif that provides a clean, premium, and confident voice.
- **Extreme Contrast:** Uses Heavy/Black weights for numbers and headers to create a "monumental" feel.

## Components
- **The Neomorphic Card:** Hard-edged blocks with distinct "light" and "shadow" sides to simulate physical depth.
- **Credit Score Meter:** A signature, multi-colored arc with hard shadows and vibrant gradients.
- **Action Buttons:** Large, rectangular blocks with solid color fills and zero rounding.

## Visual Effects
- **Hard Shadows:** Uses `4px 4px 0px #000000` or similar hard shadows rather than soft blurs.
- **Mesh Gradients:** Backgrounds often feature slow-moving, dark mesh gradients to add depth to the black canvas.
- **Tactile Feedback:** Every interaction is accompanied by a fast, precise animation and haptic-like visual response.
