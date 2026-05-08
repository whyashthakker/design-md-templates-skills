---
name: Substack
colors:
  background: "#ffffff"
  foreground: "#2b2823" # Dune
  brand: "#ff7731"      # Substack Orange
  muted: "#71717a"      # Muted grey for metadata
  border: "#e5e5e7"
  card: "#ffffff"
  accent: "#ff7731"
  
  dark:
    background: "#1a1a1a"
    foreground: "#f2f2f2"
    muted: "#a1a1aa"
    border: "#2d2d2d"
    card: "#212121"
    accent: "#ff7731"

typography:
  fontFamily:
    serif: "Spectral, Georgia, serif"
    sans: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica, Arial, sans-serif"
  body:
    fontFamily: serif
    fontSize: "18px"
    lineHeight: "1.6"
  heading:
    fontFamily: sans
    fontWeight: "700"
    letterSpacing: "-0.02em"

rounded:
  default: "4px" # Substack uses relatively sharp/minimal rounding
  full: "9999px"
---

# Design System: Substack

## Overview
Substack's design system is "infrastructure for writers." It prioritizes long-form readability, high contrast, and a clean, editorial aesthetic that allows the writer's content to take center stage.

## Design Philosophy
1. **Readability First:** Typography is optimized for deep focus and long-form consumption. Generous line-height and high-quality serifs are standard.
2. **Minimalist Utility:** UI elements (navigation, sidebars, metadata) are secondary to the content. They are often kept small, muted, and out of the way.
3. **Editorial Heritage:** The system feels like a modern evolution of traditional newspaper and magazine layouts—clean grids, bold headlines, and classic serif body text.
4. **Platform as Infrastructure:** The design is intentionally "un-styled" in parts to act as a canvas for the writer's personal brand (logos, accent colors).

## Colors
- **Substack Orange (#FF7731):** Used for primary actions (Subscribe), brand presence (Logo), and highlights. It is high-energy and serves as the signature call-to-action color.
- **Dune (#2B2823):** An earthy, deep off-black used for primary text to reduce eye strain compared to pure black.
- **Whitespace:** Essential to the Substack aesthetic. Generous padding and margins "let the words breathe."

## Typography
- **Primary Serif (Spectral):** Used for the core reading experience. It provides a sophisticated, literary feel.
- **System Sans:** Used for the interface and utility elements to ensure speed, familiarity, and clarity on all platforms.
- **Hierarchy:** High contrast between large, bold sans-serif headlines and elegant serif body text.

## Components
- **The "Subscribe" Button:** Usually a solid "Substack Orange" rectangle or pill with high-contrast text. It is the most prominent interactive element.
- **Feed Cards:** Minimalist cards with a strong focus on the headline and a short excerpt. Separated by subtle borders or generous whitespace rather than heavy shadows.
- **Writer Wordmark:** Placed prominently at the top of publications, often the only large brand element on the page.

## Visual Effects
- **Minimal Decoration:** Avoids heavy gradients, complex shadows, or flashy animations.
- **Border-based Separation:** Uses 1px borders (`#e5e5e7`) to define layout sections without adding visual weight.
- **Focus States:** Simple, high-contrast outlines or color shifts using the brand orange.
