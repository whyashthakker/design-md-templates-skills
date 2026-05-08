---
name: Medium
colors:
  background: "#ffffff"
  foreground: "#000000"
  brand: "#15693b"      # Medium Green
  muted: "#757575"
  border: "#e6e6e6"
  card: "#ffffff"
  accent: "#15693b"
  
  dark:
    background: "#000000"
    foreground: "#ffffff"
    muted: "#a8a8a8"
    border: "#292929"
    card: "#000000"
    accent: "#15693b"

typography:
  fontFamily:
    serif: "Charter, Georgia, serif"
    display: "Noe Display, serif"
    sans: "Inter, system-ui, sans-serif"
  body:
    fontFamily: serif
    fontSize: "20px" # Large, comfortable reading size
    lineHeight: "1.6"
  heading:
    fontFamily: display
    fontWeight: "700"
    letterSpacing: "-0.02em"

rounded:
  default: "4px"
  full: "9999px"
---

# Design System: Medium

## Overview
Medium's design system is a "Masterclass in Reading." It is an elegant, editorial environment that prioritizes the written word through high-quality typography and a monochrome-first aesthetic.

## Design Philosophy
1. **Readability above All:** Every design choice—from font selection to line length—is optimized for deep, focused reading.
2. **Editorial Sophistication:** Uses high-contrast serifs to evoke the feeling of a premium physical magazine or literary journal.
3. **Monochrome Restraint:** Primarily uses Black and White to reduce visual noise, with Green as the single point of brand focus.
4. **The Writer as Hero:** The UI is a canvas for the writer's ideas, featuring minimal decoration and a focus on clean metadata.

## Colors
- **Medium Green (#15693B):** A deep, organic green used for primary actions (Follow, Sign Up) and brand identity. It represents growth and knowledge.
- **Pure Monochrome:** Uses absolute Black (#000000) for text and absolute White (#FFFFFF) for the canvas to ensure maximum contrast.
- **Subtle Overlays:** Uses very light grey overlays for metadata and secondary navigation.

## Typography
- **Noe Display:** A high-contrast, elegant serif used for impactful headlines. It provides the "editorial" voice.
- **Charter:** A workhorse serif designed for reading on screens. It is warm, balanced, and reduces eye fatigue.
- **Inter:** A clean, neutral sans-serif used for the "plumbing" of the site (menus, buttons, metadata).

## Components
- **The Article Feed:** A minimalist vertical list with large, bold headlines and small, muted metadata.
- **Subscribe/CTA:** Usually a simple, green outlined button or a solid green pill.
- **Clap Button:** A playful, interactive icon that represents social engagement without the weight of a traditional "Like" button.

## Visual Effects
- **Generous Leading:** High line-height (1.6x) to create a relaxed, airy reading experience.
- **Drop Caps:** Used occasionally at the start of articles to add a classic editorial flourish.
- **Smooth Image Loading:** Uses a blurred-to-sharp "progressive" image loading effect to maintain the feeling of speed.
