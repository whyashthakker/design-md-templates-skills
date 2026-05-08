---
name: Netflix
colors:
  background: "#000000"
  foreground: "#ffffff"
  brand: "#e50914"      # Netflix Red
  muted: "#a8a8a8"
  border: "#333333"
  card: "#141414"
  accent: "#e50914"
  
  # Netflix is strictly dark-first
  dark:
    background: "#000000"
    foreground: "#ffffff"
    muted: "#808080"
    border: "#2f2f2f"
    card: "#181818"
    accent: "#e50914"

typography:
  fontFamily:
    sans: "Netflix Sans, Inter, system-ui, sans-serif"
  body:
    fontSize: "16px"
    lineHeight: "1.4"
  heading:
    fontWeight: "700"
    letterSpacing: "-0.01em"

rounded:
  default: "4px"
  md: "8px"
  lg: "12px"
---

# Design System: Netflix

## Overview
Netflix's design system is "The Cinema in your Pocket." It is a content-first, dark-room environment where the interface is secondary to the immersive imagery of films and shows.

## Design Philosophy
1. **Content-First:** The UI is a stage. Every button, label, and grid line exists only to help the user find their next favorite story.
2. **The Dark Room:** Uses a pure black background (`#000000`) to maximize the perceived contrast and color of thumbnails and video content.
3. **The "N" Momentum:** The signature Red (`#e50914`) represents the "Red Carpet"—it is high-energy, premium, and calls the user to action.
4. **Cinemascopic Flow:** Uses horizontal "rows" and smooth "Billboard" transitions to mimic the movement of a film strip.

## Colors
- **Netflix Red (#E50914):** Used for the most critical actions (Play, Join) and brand identifiers. It is designed to "pop" aggressively against black.
- **Symbol Dark Red (#B20710):** Used within the "N" symbol to create a 3D "folding ribbon" effect.
- **Layered Blacks:** Uses `#141414` for cards and overlays to create a subtle hierarchy without breaking the "Dark Room" immersion.

## Typography
- **Netflix Sans:** A proprietary geometric sans-serif. Headings are bold and cinematic; UI text is compact and efficient for cross-device legibility.
- **Lowercase Efficiency:** UI labels often use lowercase to feel more approachable and fit more text into small components.

## Components
- **The Billboard:** A massive, full-screen hero area that showcases a single high-impact title with auto-playing video.
- **Content Rows:** Horizontal scrolling containers that use adaptive artwork to catch the user's eye.
- **Progress Bars:** Thin, high-contrast red bars that indicate viewing progress without distracting from the artwork.

## Visual Effects
- **Adaptive Artwork:** The design system dynamically changes thumbnails based on user preferences.
- **The "N" Ribbon:** A folding, 3D animation style used for the brand's mobile and social symbol.
- **Smooth Scaling:** Hovering over a content card expands it with a smooth transition, revealing more details and a preview.
