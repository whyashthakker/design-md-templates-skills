---
name: Rabbit
colors:
  background: "#000000"
  foreground: "#ffffff"
  brand: "#ff5722"      # Rabbit Orange
  muted: "#333333"
  border: "#222222"
  card: "#111111"
  accent: "#ff5722"
  
  dark:
    background: "#000000"
    foreground: "#ffffff"
    muted: "#444444"
    border: "#222222"
    card: "#111111"
    accent: "#ff5722"

typography:
  fontFamily:
    sans: "Inter, system-ui, sans-serif"
    mono: "JetBrains Mono, Courier New, monospace"
  body:
    fontSize: "14px"
    lineHeight: "1.4"
  heading:
    fontWeight: "700"

rounded:
  default: "0px" # Rabbit hardware/UI is often quite sharp or uses perfect circles
  md: "4px"
  full: "9999px"
---

# Design System: Rabbit

## Overview
Rabbit's design system is "The AI Companion." It is characterized by its iconic fluorescent orange color, a high-tech-meets-lo-fi aesthetic, and a focus on speech-to-action interactions.

## Design Philosophy
1. **The Orange Beacon:** The Rabbit Orange (#ff5722) is the single brand signal, representing energy, intelligence, and the "R1" device.
2. **Lo-Fi High-Tech:** Combines pixel-art elements and monospace fonts with cutting-edge AI features, creating a "retro-futuristic" vibe.
3. **Modal Simplicity:** The UI is designed to be experienced in small bursts—cards, voice snippets, and focused status screens.
4. **The Mascot Voice:** Integrated animations of the Rabbit mascot provide a human-like feedback loop for AI processing.

## Colors
- **Fluorescent Orange (#FF5722):** Used for the primary device chassis and all critical UI actions.
- **Stark Monochrome:** Uses pure Black and White to ensure the Orange remains the absolute hero.
- **Dark Void:** Backgrounds are almost always pure black to minimize eye strain and save power on OLED screens.

## Typography
- **Geometric Sans:** Used for the primary interface to provide a clean, modern look.
- **Monospace Accents:** Uses Mono fonts for "Terminal" or "Processing" states to reinforce the technical nature of the AI.

## Components
- **The PTT (Push-To-Talk) Ring:** A large, circular orange indicator that pulses when the AI is listening.
- **LAM (Large Action Model) Cards:** Simple, monochrome cards that display the result of an action (e.g., booking a ride, ordering food).
- **The Scrolling Carousel:** A vertical or horizontal list of focused interactions, often controlled by a scroll wheel.

## Visual Effects
- **Pulse & Glow:** The Rabbit Orange often features a subtle glow or pulse to indicate "thinking" or "listening."
- **Scanlines:** Subtle horizontal lines in the background to simulate a terminal or CRT display.
- **Snappy Transitions:** Animations are fast and mechanical, mimicking the speed of a hardware device.
