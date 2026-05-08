---
name: Notion
colors:
  background: "#ffffff"
  foreground: "#37352f" # Notion Dark Grey
  brand: "#000000"
  muted: "#787774"
  border: "#e1e1e0"
  card: "#ffffff"
  accent: "#2383e2" # Notion Blue
  surface: "#f7f6f3" # Notion Off-white/Beige
  
  dark:
    background: "#191919"
    foreground: "#d1d1d1"
    muted: "#9b9b9b"
    border: "#2f2f2f"
    card: "#202020"
    accent: "#2383e2"

typography:
  fontFamily:
    sans: "Inter, system-ui, sans-serif"
    serif: "Lyon-Text, Georgia, serif"
    mono: "SF Mono, ui-monospace, monospace"
  body:
    fontSize: "16px"
    lineHeight: "1.5"
    fontWeight: "400"
  heading:
    fontFamily: serif
    fontWeight: "600"
    letterSpacing: "-0.01em"

rounded:
  default: "3px" # Sharp yet subtly rounded
  md: "4px"
  lg: "8px"
---

# Design System: Notion

## Overview
Notion's design system is a "warm minimalist" workspace for the mind. It is designed to feel like a high-quality digital notebook—clean, flexible, and deeply structured, yet humanized through soft tones and sophisticated typography.

## Design Philosophy
1. **Warm Minimalism:** Rejects cold, clinical whites in favor of soft parchment tones (`#f7f6f3`) that reduce eye strain and feel more organic.
2. **The Power of the Block:** Everything is a block. The UI is designed to be decomposed and recomposed by the user, requiring a highly modular and consistent layout system.
3. **Editorial Sophistication:** Uses high-quality serif typography (Lyon) for headings to create a literary, thoughtful atmosphere.
4. **Illustration-Rich:** Uses hand-drawn, black-and-white icons and illustrations to add a human, playful touch to a highly functional tool.

## Colors
- **Notion Dark Grey (#37352F):** Used instead of pure black for primary text. It is softer and more "ink-like," enhancing the notebook feel.
- **The Parchment Surface:** The signature light-beige background (`#f7f6f3`) used for sidebars and callout blocks.
- **Subtle Highlighting:** Uses a soft palette of background colors (Pastel Yellow, Blue, Green, etc.) for text highlighting and block backgrounds.

## Typography
- **The Serif/Sans Duality:** Lyon (Serif) is used for "Big Ideas" and headers, while Inter (Sans) handles the day-to-day utility and interface text.
- **Monospace for Data:** Code blocks and technical metadata use SF Mono to maintain a clean, developer-friendly structure.

## Components
- **The Callout Block:** A rounded box (`3px`) with a subtle background color and a large emoji—the most recognizable "Notion" component.
- **Sidebars:** Clean and vertical, using the parchment surface to separate the navigation from the primary workspace.
- **Slash Menu:** A minimal, text-first popup that serves as the primary entry point for all functionality.

## Visual Effects
- **Minimalist Depth:** Relies on thin borders (`1px`) and subtle background shifts rather than drop shadows.
- **Emoji as Brand:** Employs system emojis as first-class visual elements for icons, page headers, and status markers.
- **Translucent Overlays:** Uses subtle `rgba` backgrounds for menus and modals to maintain a sense of context.
