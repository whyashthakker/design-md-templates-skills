---
name: Height
colors:
  background: "#ffffff"
  foreground: "#111111"
  brand: "#000000"
  muted: "#888888"
  border: "#f0f0f0"
  card: "#ffffff"
  accent: "#2483e2"     # Height Blue
  
  dark:
    background: "#0a0a0a"
    foreground: "#eff3f4"
    muted: "#666666"
    border: "#1f1f1f"
    card: "#121212"
    accent: "#2483e2"

typography:
  fontFamily:
    sans: "Inter, system-ui, -apple-system, sans-serif"
  body:
    fontSize: "13px" # High density
    lineHeight: "1.5"
    fontWeight: "400"
  heading:
    fontWeight: "600"
    letterSpacing: "-0.01em"

rounded:
  default: "6px"
  md: "8px"
  full: "9999px"
---

# Design System: Height

## Overview
Height's design system is "Task Management as Art." It is known for its extreme level of UI polish, high information density, and a "mechanical" precision that makes project management feel fast and responsive.

## Design Philosophy
1. **Precision First:** Every border, shadow, and icon is tuned to the pixel. The UI feels like a high-end physical tool.
2. **High Information Density:** Designed for power users, using small font sizes (13px) and tight spacing to fit a massive amount of data on screen.
3. **Dynamic Interactivity:** Every interaction—from dragging a task to renaming a project—is accompanied by a smooth, high-fidelity animation.
4. **Subtle Materiality:** Uses translucent sidebars and multi-layered shadows to create a clear sense of space and focus.

## Colors
- **Absolute Neutrals:** Uses a strict scale of Greys, Blacks, and Whites to create a distraction-free environment.
- **Vibrant Accents:** Uses a set of specific colors (Blue, Purple, Green) for task statuses and user avatars, ensuring they pop against the neutral canvas.
- **Height Blue (#2483E2):** Used sparingly for primary highlights and focus states.

## Typography
- **Inter:** The only typeface in the app, used for its exceptional clarity at very small sizes and high density.
- **Micro-Hierarchy:** Uses font weights (400 to 600) and grey levels to create a clear path through complex task lists.

## Components
- **The Task List:** A precision-engineered grid with integrated checkboxes, tags, and assignee icons.
- **Floating Command Bar:** A center-focused, translucent search bar for fast navigation.
- **Status Pills:** Small, highly-rounded pills with vibrant background colors and high-contrast text.

## Visual Effects
- **Layered Shadows:** Uses multiple shadow steps to create "real" depth for modals and overlays.
- **Spring Animations:** Every movement in the UI uses spring-based physics to feel organic and responsive.
- **Translucency:** Uses `backdrop-filter` for sidebars and menus to maintain context with the main task view.
