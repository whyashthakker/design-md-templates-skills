---
name: Spotify
colors:
  background: "#121212" # Spotify Black
  foreground: "#ffffff"
  brand: "#1db954"      # Spotify Green
  muted: "#b3b3b3"      # Secondary text
  border: "#282828"
  card: "#181818"
  accent: "#1db954"
  
  # Spotify is strictly "dark-first"
  dark:
    background: "#121212"
    foreground: "#ffffff"
    muted: "#a7a7a7"
    border: "#282828"
    card: "#181818"
    accent: "#1db954"

typography:
  fontFamily:
    sans: "Circular, Helvetica Neue, Helvetica, Arial, sans-serif"
  body:
    fontSize: "14px"
    lineHeight: "1.5"
    fontWeight: "400"
  heading:
    fontWeight: "700"
    letterSpacing: "-0.04em"

rounded:
  default: "4px"
  md: "8px"
  full: "9999px"
---

# Design System: Spotify

## Overview
Spotify's design system is an immersive, nocturnal "cocoon" for music discovery. It is a dark-first environment where the interface recedes to make album art and artist imagery the primary focal points.

## Design Philosophy
1. **The Immersive Dark:** Uses a hierarchy of near-blacks (`#121212` to `#282828`) to create a cinematic, focus-driven environment.
2. **Circular Typography:** The custom "Circular" font is friendly, geometric, and bold, giving the brand a distinct "pop" voice.
3. **Album Art Centric:** UI elements are often designed to inherit or complement the colors of the current album art (adaptive UI).
4. **Tactile Simplicity:** Buttons are large, round, and highly "pressable," reflecting the physical nature of a music player.

## Colors
- **Spotify Green (#1DB954):** The signature brand "voltage." It is vibrant and neon-like, representing energy, growth, and the "Play" action.
- **The Near-Black Palette:** Uses deep charcoal surfaces to prevent eye strain and allow the vibrant colors of album art to dominate.
- **Status Accents:** Uses blues and purples sparingly for secondary features like "Enhance" or "Wrapped."

## Typography
- **Geometric Boldness:** Headlines are often very large and heavy (Bold/Black weight) with tight letter spacing.
- **Readability:** Body text uses a slightly lighter grey (`#b3b3b3`) to ensure it doesn't compete with the bold headlines.

## Components
- **The "Play" Button:** A large, round green circle with a black "Play" icon—the most recognizable component in the app.
- **Cards:** Featured with `8px` rounding, using a subtle hover state that lifts the card with a light grey background shift.
- **Sidebars:** Fixed and dark, using high-contrast icons to provide quick navigation.

## Visual Effects
- **Gradients:** Uses large, soft radial gradients behind album art to create "mood lighting" in the background.
- **Cover Art Hover:** Subtle "lift" and "glow" effects on album covers when hovered.
- **Smooth Transitions:** Cross-fading and sliding transitions that mirror the fluid nature of music.
