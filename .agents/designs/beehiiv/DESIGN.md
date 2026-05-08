---
name: Beehiiv
colors:
  background: "#f9f9f1" # Background Cream
  foreground: "#000000"
  brand: "#f5ff00"      # Beehiiv Yellow
  muted: "#666666"
  border: "#000000"     # Uses bold black borders
  card: "#ffffff"
  accent: "#ff6b00"     # Accent Orange
  
  dark:
    background: "#000000"
    foreground: "#f9f9f1"
    muted: "#a1a1a1"
    border: "#f5ff00"
    card: "#121212"
    accent: "#f5ff00"

typography:
  fontFamily:
    sans: "Inter, system-ui, -apple-system, sans-serif"
  body:
    fontSize: "15px"
    lineHeight: "1.5"
  heading:
    fontWeight: "800" # Extra bold for "neon" look
    letterSpacing: "-0.02em"

rounded:
  default: "0px" # Beehiiv often uses sharp, high-contrast edges
  md: "4px"
  full: "9999px"
---

# Design System: Beehiiv

## Overview
Beehiiv's design system is "The Newsletter Engine." It is a high-energy, "neon-noir" environment that uses its signature vibrant yellow and bold black borders to create a disruptive, tool-forward feel.

## Design Philosophy
1. **Neon Precision:** Uses a "Neon Yellow" (#F5FF00) to represent speed, growth, and the brand's digital energy.
2. **High-Contrast Brutalism:** Employs bold 1px or 2px black borders and zero-radius corners to create a strong, graphic look.
3. **Data-Dense Productivity:** The dashboard is built to manage massive amounts of subscriber data and analytics with extreme clarity.
4. **The Creator's Cockpit:** The UI feels like a command center for publishers, prioritizing metrics and growth tools.

## Colors
- **Beehiiv Yellow (#F5FF00):** The soul of the brand. It is high-visibility and used for primary conversion points.
- **Background Cream (#F9F9F1):** A warm, soft alternative to pure white that reduces eye strain during long writing sessions.
- **Bold Black:** Primarily uses absolute Black (#000000) for borders and text to create a high-impact contrast.

## Typography
- **Inter:** Ensures that analytics and post drafts are perfectly legible across all devices.
- **Extra Bold Hierarchy:** Uses heavy weights for headers and "Big Numbers" (subscriber counts, open rates) to create a sense of achievement.

## Components
- **The Post Editor:** A clean, high-density environment with integrated "Insert" menus and a bold yellow "Publish" button.
- **Analytics Cards:** White surfaces with bold black borders and integrated multi-colored line charts.
- **Subscriber Lists:** Structured, high-contrast tables with clear status pills and growth indicators.

## Visual Effects
- **Hard Borders:** Uses `border: 1px solid #000000` as the primary way to define structure.
- **Solid Shadows:** Occasionally uses solid yellow or black shadows to create a 3D-graphic feel.
- **Neon Hover States:** Buttons and links often feature a high-vibrancy color shift or solid background fill on hover.
