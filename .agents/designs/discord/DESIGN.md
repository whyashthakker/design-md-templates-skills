---
name: Discord
colors:
  background: "#313338" # background-primary
  foreground: "#dbdee1" # text-normal
  brand: "#5865f2"      # Blurple
  muted: "#949ba4"      # text-muted
  border: "#1e1f22"     # background-tertiary (used as border/divider)
  card: "#2b2d31"       # background-secondary
  accent: "#5865f2"
  success: "#23a55a"
  warning: "#f0b232"
  danger: "#f23f43"
  
  # Discord is dark-first, but has a light mode
  light:
    background: "#ffffff"
    foreground: "#313338"
    muted: "#4e5058"
    border: "#e3e5e8"
    card: "#f2f3f5"
    accent: "#5865f2"

typography:
  fontFamily:
    sans: "gg sans, Segoe UI, Helvetica Neue, Helvetica, Arial, sans-serif"
    mono: "Consolas, Andale Mono WT, Courier New, monospace"
  body:
    fontSize: "16px"
    lineHeight: "1.375" # Tight leading for chat
  heading:
    fontWeight: "700"

rounded:
  default: "8px"
  md: "8px"
  lg: "16px"
  full: "9999px"
---

# Design System: Discord

## Overview
Discord's design system is built for the "always-on" gamer and community member. It prioritizes comfort during long sessions, high-density chat readability, and a playful, vibrant brand voice.

## Design Philosophy
1. **Community Centric:** Design elements are built to foster interaction—mentions, reactions, and roles are visually distinct.
2. **Comfortable Dark Mode:** Uses specific dark grays (`#313338`) rather than pure black to reduce eye strain over time.
3. **The "Blurple" Energy:** The signature Blurple (`#5865f2`) acts as the anchor for the brand, representing a bridge between professional tools and gaming energy.
4. **Playful Precision:** Combines tight, efficient chat layouts with friendly, rounded components and quirky icons.

## Colors
- **Blurple (#5865F2):** The primary interactive color. High saturation ensures it stands out against both dark and light backgrounds.
- **Status Indicators:** Green (Online), Yellow (Idle), Red (DND), and Grey (Offline) are core semantic tokens.
- **Layered Greys:** Uses a 3-tier background system (`#1E1F22` -> `#2B2D31` -> `#313338`) to create depth and focus in the app.

## Typography
- **gg sans:** Discord's custom font designed for high legibility in dense chat logs. It has a slightly rounded, friendly character.
- **Chat Density:** Uses a tight line-height to allow more messages on screen without sacrificing legibility.

## Components
- **The Channel List:** Uses `#2B2D31` with a hover state that highlights the channel in `#35373C` and rounds the text area.
- **User Popouts:** Compact, card-like overlays with a dark background and high-contrast user information.
- **The "Pill":** Used for server icons and mention badges, often morphing from a circle to a rounded-square on hover.

## Visual Effects
- **Hover Micro-interactions:** Buttons and list items often shift subtly in color or size to provide immediate feedback.
- **Squircle/Circle Morph:** Server icons use a signature transition between circular and rounded-square forms.
- **Minimal Shadows:** Relies on color contrast between background layers rather than heavy drop shadows.
