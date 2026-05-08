---
name: Kagi
colors:
  background: "#f2f0e7" # Kagi Cream
  foreground: "#191919" # Graphite
  brand: "#fd6820"      # Kagi Orange
  muted: "#666666"
  border: "#dcdace"
  card: "#ffffff"
  accent: "#4835bc"     # Purple
  secondary: "#9debfe"  # Sky
  
  dark:
    background: "#191919"
    foreground: "#f2f0e7"
    muted: "#888888"
    border: "#2b2b2b"
    card: "#121212"
    accent: "#fd6820"

typography:
  fontFamily:
    sans: "Inter, system-ui, -apple-system, sans-serif"
  body:
    fontSize: "16px"
    lineHeight: "1.5"
  heading:
    fontWeight: "600"
    letterSpacing: "-0.01em"

rounded:
  default: "4px"
  md: "8px"
---

# Design System: Kagi

## Overview
Kagi's design system is "The Human-Centric Search." It rejects the ads and clutter of traditional search engines for a clean, "natural" aesthetic that prioritizes high-quality information and user privacy.

## Design Philosophy
1. **Natural Utility:** Uses a warm "Cream" background to reduce eye strain and feel more like a physical book or paper.
2. **Focus on the Result:** The UI is designed to get out of the way, presenting search results with extreme clarity and zero sponsored distraction.
3. **High Signal, No Noise:** Uses a diverse yet muted palette of "nature" colors (Sky, Grass, Orange) for tags and categories.
4. **Transparent Intelligence:** Provides clear data on why results were ranked, using small metadata icons and badges.

## Colors
- **Kagi Cream (#F2F0E7):** A soft, parchment-like background that is the signature of the Kagi experience.
- **Kagi Orange (#FD6820):** Used for primary highlights and the brand's small "spark" of energy.
- **Graphite (#191919):** A deep grey used for text to ensure high contrast without the harshness of pure black.

## Typography
- **Inter:** Provides a neutral, highly readable voice for search results and documentation.
- **Hierarchy:** Uses standard search engine patterns (large blue links, small green URLs) but refined for modern aesthetics.

## Components
- **The Search Bar:** A clean, centered bar with 4px rounding and a prominent "Orange" search icon.
- **Result Cards:** Minimalist blocks with integrated "Upvote/Downvote" markers and domain badges.
- **Filter Tags:** Small, rounded pills using the nature palette for quick category switching.

## Visual Effects
- **Minimalist Depth:** Relies on color shifts and thin borders rather than shadows.
- **Soft Hover Highlights:** Search results use a very subtle background shift to indicate interactivity.
- **Instant Result Loading:** Designed for zero-latency, with UI elements appearing instantly without heavy animations.
