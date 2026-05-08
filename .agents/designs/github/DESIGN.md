---
name: GitHub (Primer)
colors:
  background: "#ffffff"
  foreground: "#1f2328"
  brand: "#0969da"      # accent.fg
  muted: "#636c76"      # fg.muted
  border: "#d0d7de"     # border.default
  card: "#ffffff"
  accent: "#0969da"
  success: "#1a7f37"
  attention: "#9a6700"
  danger: "#d1242f"
  
  dark:
    background: "#0d1117" # canvas.default
    foreground: "#e6edf3" # fg.default
    muted: "#848d97"      # fg.muted
    border: "#30363d"     # border.default
    card: "#161b22"      # canvas.overlay
    accent: "#2f81f7"     # accent.fg
    success: "#3fb950"
    attention: "#d29922"
    danger: "#f85149"

typography:
  fontFamily:
    sans: "-apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji'"
    mono: "ui-monospace, SFMono-Regular, 'SF Mono', Menlo, Consolas, 'Liberation Mono', monospace"
  body:
    fontFamily: sans
    fontSize: "14px"
    lineHeight: "1.5"
  code:
    fontFamily: mono
    fontSize: "12px"

rounded:
  default: "6px"
  md: "6px"
  lg: "10px"
---

# Design System: GitHub (Primer)

## Overview
Primer is the open-source design system that powers GitHub. It is built to be accessible, consistent, and efficient, focusing on developer productivity and complex information density.

## Design Philosophy
1. **Productive Complexity:** Designed to handle high-density information (code, timelines, grids) without overwhelming the user.
2. **Accessibility-First:** Color scales and contrast ratios are strictly enforced to meet WCAG standards.
3. **Pragmatic Visuals:** Uses system fonts and minimal decorative elements to maximize performance and platform familiarity.
4. **Consistency through Primitives:** Relying on a robust set of "primitives" (spacing, color, typography) to ensure a cohesive experience across all GitHub features.

## Colors
- **Functional Palettes:** Colors are assigned "functional" roles (e.g., `accent.fg`, `success.fg`, `danger.fg`) rather than just being chosen by hue.
- **The GitHub Blue:** `#0969da` (Light) and `#2f81f7` (Dark) are the core interactive accents used for links and primary actions.
- **Canvas System:** Uses a layered canvas approach (`default`, `overlay`, `inset`, `subtle`) to create depth without relying on heavy shadows.

## Typography
- **System Stack:** Prioritizes the user's operating system fonts for maximum legibility and zero-latency loading.
- **Code as a First-Class Citizen:** Monospace fonts are treated with equal importance to sans-serif fonts, ensuring code readability is never compromised.
- **Scale:** Uses a 14px base for body text to balance information density with readability.

## Components
- **The "Box":** The fundamental layout unit. Often featured with a 1px border (`#d0d7de`) and `6px` rounding.
- **Buttons:** Available in "Default," "Primary," and "Danger" variants, each with specific hover and active states defined by functional tokens.
- **Octicons:** GitHub's bespoke icon set, used to provide semantic meaning and visual cues.
- **Timelines:** A specific pattern used for activity feeds and pull request conversations, emphasizing sequential flow.

## Visual Effects
- **Subtle Depth:** Uses thin borders and very soft shadows (`0 1px 0 rgba(27,31,35,0.04)`) rather than large drop shadows.
- **High Contrast Focus:** Focus states are highly visible, usually using a 2px blue ring.
- **Hover States:** Most interactive elements use a subtle background color shift (e.g., `bgColor-muted`) to indicate interactivity.
