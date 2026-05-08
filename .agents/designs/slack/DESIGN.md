---
name: Slack
colors:
  background: "#ffffff"
  foreground: "#1d1c1d" # Brand Black
  brand: "#4a154b"      # Aubergine
  muted: "#616061"      # Grey text
  border: "#dddddd"
  card: "#f8f8f8"
  accent: "#1264a3"     # Accessible Blue
  success: "#007a5a"
  danger: "#e01e5a"
  warning: "#ecb22e"
  
  dark:
    background: "#1a1d21"
    foreground: "#d1d2d3"
    muted: "#ababad"
    border: "#35373b"
    card: "#222529"
    accent: "#36c5f0"

typography:
  fontFamily:
    sans: "Lato, Helvetica Neue, Helvetica, Arial, sans-serif"
    heading: "Larsseit, sans-serif"
  body:
    fontSize: "15px"
    lineHeight: "1.46"
  heading:
    fontWeight: "700"

rounded:
  default: "4px"
  md: "8px"
  lg: "12px"
---

# Design System: Slack

## Overview
Slack's design system is a "digital headquarters." It balances professional productivity with a friendly, conversational humanism. It is characterized by its iconic Aubergine sidebar and vibrant, multi-colored accents.

## Design Philosophy
1. **Conversational Humanism:** The UI should feel friendly and approachable, like a conversation with a teammate.
2. **The Power of the Sidebar:** The Aubergine sidebar is the anchor of the brand—it provides a stable environment for navigation and focus.
3. **Clarity over Flash:** Prioritizes high legibility and fast information scanning over decorative elements.
4. **Vibrant Precision:** Uses a limited set of high-energy "pop" colors (Blue, Green, Red, Yellow) derived from the logo for semantic meaning.

## Colors
- **Aubergine (#4A154B):** The soul of the Slack interface. It represents trust, stability, and focus.
- **The Logo Palette:** Four specific colors used for reactions, mentions, and notifications to create a "celebratory" feel.
- **Accessible Neutrals:** Uses `#1D1C1D` for text and `#DDDDDD` for borders to ensure high contrast and a clean workspace.

## Typography
- **Larsseit (Marketing):** A contemporary grotesque sans-serif used for bold, confident headlines.
- **Lato (Product):** Chosen for its exceptional legibility at small sizes, making it perfect for dense chat threads.

## Components
- **The "Octo" (Octothorpe):** The Slack logo symbol, used as a shorthand for the brand and community.
- **Message Rows:** Clean, separated by whitespace rather than lines. Hovering reveals a hidden "reaction" bar.
- **Mentions:** Highlighted with a subtle yellow background and a bold vertical bar to ensure they aren't missed.

## Visual Effects
- **Reaction Glow:** Emojis and reactions use subtle color shifts and "pop" animations when clicked.
- **Sidebar Highlighting:** The active channel is highlighted with a saturated "Aubergine Active" bar.
- **Translucent Overlays:** Menus and popovers use `backdrop-filter` to maintain a sense of space and context.
