---
name: Humane
colors:
  background: "#000000"
  foreground: "#ffffff"
  brand: "#ffffff"
  muted: "#333333"
  border: "#1a1a1a"
  card: "#0a0a0a"
  accent: "#ff0000"     # Laser Red
  
  dark:
    background: "#000000"
    foreground: "#ffffff"
    muted: "#444444"
    border: "#1a1a1a"
    card: "#0a0a0a"
    accent: "#ff0000"

typography:
  fontFamily:
    sans: "Inter, system-ui, -apple-system, sans-serif"
  body:
    fontSize: "14px"
    lineHeight: "1.4"
  heading:
    fontWeight: "600"
    letterSpacing: "0.05em" # Wide tracking for "cosmic" feel

rounded:
  default: "0px" # Humane hardware/UI is very sharp or uses perfect circles
  md: "4px"
  full: "9999px"
---

# Design System: Humane

## Overview
Humane's design system is "The Invisible Interface." Designed for the AI Pin, it focuses on projection-based interactions, cosmic black foundations, and a "laser-sharp" visual language that prioritizes voice and gesture.

## Design Philosophy
1. **Presence over Screens:** The UI is designed to exist in the real world (via projection) rather than on a traditional screen, requiring high-contrast, simple graphics.
2. **Cosmic Minimalism:** Uses a "Void" black foundation and pure white elements to create a futuristic, "out-of-this-world" feel.
3. **Laser Precision:** Employs "Laser Red" (#FF0000) sparingly as a signal for recording, focus, and critical status.
4. **Gesture-Friendly:** Components are large, circular, or center-aligned to be easily readable and interactable via hand gestures.

## Colors
- **Cosmic Black (#000000):** The primary canvas, representing the "hidden" nature of the device.
- **Laser Red (#FF0000):** The only high-saturation accent, used for the recording indicator and focus states.
- **Lunar White (#FFFFFF):** Used for all primary text and iconography to ensure maximum visibility during projection.

## Typography
- **Inter:** A neutral, clean sans-serif that ensures clarity even when projected onto varying surfaces.
- **Wide Tracking:** Uses generous letter-spacing in headers to create a "premium," futuristic voice.

## Components
- **The Laser Canvas:** A center-focused area for projected graphics, featuring large icons and minimal text.
- **The "Trust Light":** A signature, multi-colored LED indicator on the hardware that is reflected in UI status bars.
- **Circular Menu:** A gesture-based menu that appears as a ring of icons around the center of the palm.

## Visual Effects
- **Glow & Diffraction:** Projected elements often feature a subtle "diffraction" or "halo" effect to simulate light.
- **Slow Pulses:** Uses calm, slow animations for "Processing" or "Thinking" to reduce user anxiety.
- **Stark Transitions:** Interactions are binary and fast—elements either exist or they don't, mimicking the behavior of a laser.
