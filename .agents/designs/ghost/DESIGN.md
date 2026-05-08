---
name: Ghost
colors:
  background: "#ffffff"
  foreground: "#121217" # Woodsmoke
  brand: "#ff1a75"      # Ghost Pink
  muted: "#757575"
  border: "#e6e6e6"
  card: "#ffffff"
  accent: "#820ad1"     # Casper Purple
  
  dark:
    background: "#0c0c0f"
    foreground: "#f2f2f2"
    muted: "#a1a1a1"
    border: "#26262b"
    card: "#121217"
    accent: "#ff1a75"

typography:
  fontFamily:
    sans: "Inter, system-ui, -apple-system, sans-serif"
    serif: "Source Serif Pro, Georgia, serif"
  body:
    fontSize: "16px"
    lineHeight: "1.6"
  heading:
    fontWeight: "700"
    letterSpacing: "-0.02em"

rounded:
  default: "4px"
  md: "8px"
  full: "9999px"
---

# Design System: Ghost

## Overview
Ghost's design system is "The Professional Publisher." It is a minimalist, focused environment designed to help creators write and manage their newsletters and publications with absolute clarity.

## Design Philosophy
1. **Editorial Focus:** The UI is a canvas for content. It uses high-quality serifs and generous whitespace to create a premium reading experience.
2. **Minimalist Management:** The dashboard is intentionally "clean," hiding complex features behind simple icons and intuitive menus.
3. **The "Ghost" Signature:** Uses a vibrant pink (#FF1A75) as a single point of energy against a monochrome, "Woodsmoke" foundation.
4. **Performance Infrastructure:** Designed for speed, with zero-latency loading and a lightweight UI that stays out of the creator's way.

## Colors
- **Ghost Pink (#FF1A75):** The signature brand color, used for primary actions and brand presence.
- **Woodsmoke (#121217):** A deep, ink-like black used for primary text and dark UI elements.
- **Casper Purple (#820AD1):** Used as a secondary accent in newer themes to add a layer of sophistication.

## Typography
- **Source Serif Pro:** Used for the core reading experience to provide a literary, high-quality feel.
- **Inter (UI):** Handles the dashboard and management interface with high legibility and a neutral tone.

## Components
- **The Editor View:** A full-screen, distraction-free writing environment with minimal UI chrome.
- **Publication Cards:** Clean, white units with large headlines and simple subscriber metrics.
- **The Sidebar:** A minimalist, dark-grey column that uses high-contrast icons for navigation.

## Visual Effects
- **Typography-first Depth:** Relies on font scales and weights to create hierarchy rather than heavy borders or shadows.
- **Subtle Overlays:** Uses light-grey background shifts for hover states in the post list.
- **Fast Content Fades:** Uses smooth opacity transitions for loading articles and changing views.
