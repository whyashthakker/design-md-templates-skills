---
name: Twitch
colors:
  background: "#000000"
  foreground: "#ffffff"
  brand: "#9146ff"      # Twitch Purple (Ultraviolet)
  muted: "#adadb8"
  border: "#1f1f23"
  card: "#18181b"
  accent: "#9146ff"
  
  light:
    background: "#ffffff"
    foreground: "#000000"
    muted: "#53535f"
    border: "#e5e5e7"
    card: "#f7f7f8"
    accent: "#9146ff"

typography:
  fontFamily:
    sans: "Roobert, Inter, system-ui, sans-serif"
    mono: "ui-monospace, SFMono-Regular, monospace"
  body:
    fontSize: "13px" # Chat-first density
    lineHeight: "1.5"
  heading:
    fontWeight: "700"
    letterSpacing: "-0.02em"

rounded:
  default: "4px"
  md: "8px"
  full: "9999px"
---

# Design System: Twitch

## Overview
Twitch's "Core UI" is a hyper-digital, high-energy design system for the streaming age. It is defined by its vibrant "Ultraviolet" purple, 3D-inspired motifs, and high-density chat-first layouts.

## Design Philosophy
1. **Hyper-Digital Energy:** Uses saturated colors and "glossy" 3D effects to represent the live, "powered-on" nature of streaming.
2. **Gamer-Centric Functionality:** Prioritizes screen real estate for video and fast-moving chat, using compact typography and minimal margins.
3. **The "Glitch" Spirit:** Embraces a "digital-first" aesthetic with blocky typography and high-contrast "neon" accents.
4. **Live Feedback:** UI elements are designed to react instantly—toggles, sliders, and chat messages feel "alive" through fast animations and vibrant colors.

## Colors
- **Ultraviolet Purple (#9146FF):** The core of Twitch. It is high-saturation and represents the "vibe" of the community.
- **The Black Canvas:** Dark mode uses pure black (`#000000`) and near-black (`#18181B`) to make the video and purple accents feel like they are "glowing" on screen.
- **Turbo Accents:** Uses secondary "neon" colors like Electric Blue and Spring Green for specific highlights and status states.

## Typography
- **Roobert Twitch:** A geometric sans-serif with a technical, "blocky" feel. It is designed to be readable even in fast-scrolling chat at small sizes.
- **High Density:** Uses a 13px base for chat to maximize information density while maintaining legibility through high contrast.

## Components
- **The "Glitch" Icon:** The primary brand mark, often used as a home button or status indicator.
- **Pill Tags:** Stream tags and categories are rendered as small, high-radius pills with bold, high-contrast text.
- **Chat Container:** A distinct, dark-grey column that uses high-contrast text and colorful usernames to create a vibrant "social" space.

## Visual Effects
- **3D "Plastic" Style:** Recent updates use subtle gradients and shadows to make the logo and buttons feel like glossy 3D objects.
- **Neon Glow:** Text and icons often use the brand purple or Turbo colors with a subtle `box-shadow` to simulate an LED display.
- **Glitch Animations:** Subtle, fast "glitch" or "shake" effects used during transitions or high-engagement moments.
