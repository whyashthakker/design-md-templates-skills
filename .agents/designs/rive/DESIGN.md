---
name: Rive
colors:
  background: "#000000"
  foreground: "#ffffff"
  brand: "#00ff77"      # Rive Green (Spring Green)
  muted: "#666666"
  border: "#222222"
  card: "#111111"
  accent: "#ff0077"     # Rive Pink (Rose)
  
  light:
    background: "#ffffff"
    foreground: "#111111"
    muted: "#888888"
    border: "#e5e5e5"
    card: "#f9fafb"

typography:
  fontFamily:
    sans: "Inter, system-ui, -apple-system, sans-serif"
    mono: "JetBrains Mono, SF Mono, monospace"
  body:
    fontSize: "13px" # Tool-first density
    lineHeight: "1.4"
  heading:
    fontWeight: "700"
    letterSpacing: "-0.02em"

rounded:
  default: "4px"
  md: "6px"
  full: "9999px"
---

# Design System: Rive

## Overview
Rive's design system is "The Engine of Motion." It is a dark-first, technical environment designed for high-performance animation and real-time interaction. It uses high-vibrancy "neon" accents against a deep black canvas.

## Design Philosophy
1. **Motion-Native:** The UI is built to showcase movement. Buttons, sliders, and timelines feature fluid, high-fidelity animations.
2. **High-Signal Accents:** Uses "Spring Green" (#00FF77) for primary tools and "Rose Pink" (#FF0077) for secondary actions, ensuring they pop in a dark UI.
3. **The Power of the Canvas:** The primary workspace is an infinite canvas, and the surrounding UI is designed to be minimal and tool-like.
4. **Professional Precision:** Relies on tight spacing, small fonts (13px), and monospace accents to feel like a high-end creative tool.

## Colors
- **Rive Green (#00FF77):** The signature brand color, representing the "Play" button and active state of animation.
- **Deep Void:** Primarily uses pure Black (#000000) for the workspace to maximize the perceived color of animations.
- **Industrial Greys:** Uses a scale of deep charcoal greys for panels, toolbars, and borders.

## Typography
- **Inter:** Handles the complex tool labels and menu items with exceptional clarity.
- **Monospace for Motion:** Uses Mono fonts for coordinates, keyframe values, and code snippets to ensure technical precision.

## Components
- **The State Machine:** A unique, node-based layout for managing animation logic with high-contrast lines and pills.
- **Timeline Rails:** Highly-structured horizontal containers with 1px markers and colorful keyframe icons.
- **The Toolbar:** A vertical or horizontal list of minimalist icons with high-vibrancy active states.

## Visual Effects
- **Neon Glows:** Active tools and buttons often feature a subtle glow in the brand green or pink.
- **Translucent Overlays:** Uses subtle `rgba` backgrounds for property panels to maintain focus on the canvas.
- **Zero-Latency Response:** Every slider movement and keyframe adjustment is reflected instantly in the UI.
