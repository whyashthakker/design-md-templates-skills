---
name: Bento
colors:
  background: "#1d1d1d" # Cod Gray
  foreground: "#ffffff"
  brand: "#5aff88"      # Screamin' Green
  muted: "#8a8f98"
  border: "#2b2b2b"
  card: "#262626"
  accent: "#5aff88"
  
  light:
    background: "#ffffff"
    foreground: "#111111"
    muted: "#6b7280"
    border: "#e5e7eb"
    card: "#f9fafb"
    accent: "#5aff88"

typography:
  fontFamily:
    sans: "Inter, system-ui, sans-serif"
  body:
    fontSize: "15px"
    lineHeight: "1.5"
  heading:
    fontWeight: "700"
    letterSpacing: "-0.02em"

rounded:
  default: "24px" # Bento is known for very large, soft rounding
  md: "32px"
  lg: "40px"
  full: "9999px"
---

# Design System: Bento

## Overview
Bento's design system is "The Grid of You." It is a playful, personal environment centered around the "Bento Box" pattern—organizing life and links into a beautiful, highly-rounded grid.

## Design Philosophy
1. **The Modern Grid:** Every element is a tile in a perfectly aligned, responsive grid.
2. **Extreme Rounding:** Uses very large border radii (24px to 40px) to create a soft, friendly, and tactile feel.
3. **Vibrant Signals:** Uses "Screamin' Green" as a signature brand voltage against a dark, minimalist canvas.
4. **Personal Expression:** The UI is designed to be a canvas for the user, supporting diverse colors, images, and links in a coherent frame.

## Colors
- **Screamin' Green (#5AFF88):** A vibrant, digital green that represents the "online" personal brand.
- **Cod Gray (#1D1D1D):** The primary background that makes the colorful bento tiles pop.
- **Soft Accents:** Uses a secondary palette of Peach, Coral, and Muted Blue for individual tile backgrounds.

## Typography
- **Inter:** Ensures that personal bios and link labels are highly legible across different tile sizes.
- **Bold Headers:** Uses heavy weights and tight tracking for a modern, "poster-like" editorial feel.

## Components
- **The Bento Tile:** The fundamental unit. A highly-rounded rectangle (`24px+`) with integrated links, images, or status.
- **The Header Card:** A larger, full-width tile at the top containing the user's profile and bio.
- **Link Pills:** Small, high-radius buttons within tiles for social media or personal links.

## Visual Effects
- **Tile Hover:** Tiles subtly scale up and show a soft glow when hovered.
- **Smooth Sorting:** Drag-and-drop interactions feature fluid, physics-based motion.
- **Mesh Gradients:** Marketing headers often use soft, multi-colored mesh gradients to add depth.
