---
name: Apple
colors:
  background: "#ffffff"
  foreground: "#1d1d1f"
  brand: "#000000"
  muted: "#86868b"
  border: "#d2d2d7"
  card: "#f5f5f7"
  accent: "#0066cc" # Apple Blue
  
  dark:
    background: "#000000"
    foreground: "#f5f5f7"
    muted: "#86868b"
    border: "#424245"
    card: "#1d1d1f"
    accent: "#2997ff"

typography:
  fontFamily:
    sans: "SF Pro, SF Pro Display, system-ui, sans-serif"
    mono: "SF Mono, ui-monospace, monospace"
  body:
    fontSize: "17px"
    lineHeight: "1.47"
    fontWeight: "400"
    letterSpacing: "-0.022em"
  heading:
    fontWeight: "600"
    letterSpacing: "-0.015em"

rounded:
  default: "12px"
  lg: "20px"
  full: "9999px"
---

# Design System: Apple

## Overview
Apple's design system is a "museum gallery" for products. It is defined by its extreme use of whitespace, premium photography, and a "subtractive" approach where the interface disappears to let the content shine.

## Design Philosophy
1. **Museum-like Presentation:** Every product is presented as a piece of art. Huge margins and edge-to-edge imagery are standard.
2. **SF Pro Typography:** The San Francisco typeface is the backbone of the brand—highly legible, neutral, and engineered for high-resolution displays.
3. **Materials over Colors:** Uses "Gaussian Blur" and "Vibrancy" (translucency) to create depth rather than traditional drop shadows.
4. **Physicality:** Components (like the "Dynamic Island" or iOS buttons) often follow physical metaphors of squishing, bouncing, and layering.

## Colors
- **The Binary Palette:** Primarily pure White and pure Black. This creates the highest possible contrast for product photography.
- **Off-white Backgrounds:** Uses a very subtle light grey (`#f5f5f7`) to differentiate sections without losing the "clean" feel.
- **Functional Accents:** The "Apple Blue" is used sparingly for links and interactive states.

## Typography
- **Precision Tracking:** Uses custom tracking (letter-spacing) tables for every font size to ensure perfect balance.
- **Typographic Hierarchy:** Massive headings (often 56px+) paired with relatively large body text (17px) to create a "bold yet readable" editorial feel.

## Components
- **The "Bento" Grid:** Organizing complex features into a clean grid of rounded rectangles (12px to 20px radius).
- **Cards:** Usually flat white or light grey with no border, relying on background contrast and subtle corner smoothing (Squircle).
- **Buttons:** Simple, rounded-pill shapes with high-contrast text or translucent "glassmorphism" backgrounds.

## Visual Effects
- **Corner Smoothing:** Uses "Squircles" (superellipses) rather than simple circular radii for a more organic, premium feel.
- **Glassmorphism:** Heavy use of `backdrop-filter: blur(20px)` for overlays, sidebars, and navigation.
- **High-Dynamic Range (HDR) Imagery:** Photography is the primary "color" of the system.
