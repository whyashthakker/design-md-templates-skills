---
name: Linear
colors:
  background: "#010102" # The "Linear Black"
  foreground: "#eeeeee"
  brand: "#5e6ad2"      # Linear Purple
  muted: "#8a8f98"
  border: "#222326"
  card: "#0b0c0d"
  accent: "#5e6ad2"
  
  # Linear is "dark-first", but has a light mode
  light:
    background: "#ffffff"
    foreground: "#111111"
    muted: "#6b7280"
    border: "#e5e7eb"
    card: "#f9fafb"

typography:
  fontFamily:
    sans: "Inter, system-ui, sans-serif"
    mono: "JetBrains Mono, SF Mono, monospace"
  body:
    fontSize: "14px"
    lineHeight: "1.5"
  heading:
    fontWeight: "600"
    letterSpacing: "-0.02em"

rounded:
  default: "4px" # Sharp, precise edges
  md: "6px"
---

# Design System: Linear

## Overview
Linear is the pinnacle of "high-performance" developer tool design. It is built for speed, focus, and precision, using a "no-distraction" aesthetic that favors keyboard-first workflows.

## Design Philosophy
1. **Focus & Speed:** The UI is designed to be felt, not seen. Every element is optimized for zero-latency interaction.
2. **The "Void" Aesthetic:** Uses an almost-pure black background (`#010102`) to make content and status indicators pop.
3. **Mechanical Precision:** Uses tight spacing, small border radii (4px), and monospace accents to feel like a high-end physical tool.
4. **Purposeful Glow:** Uses subtle purple glows and gradients sparingly to indicate primary actions and focus.

## Colors
- **Linear Purple (#5E6AD2):** The single point of brand energy. Used for focus states, primary buttons, and the iconic "active" glow.
- **Neutrals:** A vast scale of greys from almost-black to muted slate, used to create hierarchy without color.
- **Status Colors:** Precise, vibrant colors for issue states (Backlog: grey, Todo: white, In Progress: yellow, Done: purple).

## Typography
- **Utility First:** Uses Inter for its high legibility at small sizes.
- **Monospace Integration:** Keyboard shortcuts and technical metadata are always rendered in a high-quality Mono font.

## Components
- **Command Menu:** The heart of the app. A floating, translucent overlay with a search-first interface.
- **The "Linear Card":** Deep black with a thin, 1px border. Often features a very subtle top-light highlight.
- **Sidebar:** Minimalist and collapsable, using icons and hotkeys rather than labels.

## Visual Effects
- **Glows:** Used on text and icons to indicate "Active" or "Unread" states.
- **Motion Blur:** Uses subtle CSS blurs and fast transitions to imply performance.
- **Reflective Accents:** Uses 1px "inner borders" on the top edge of cards to simulate light hitting a physical edge.
