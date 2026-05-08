---
name: Tally
colors:
  background: "#ffffff"
  foreground: "#000000"
  brand: "#008080"      # Tally Teal
  muted: "#757575"
  border: "#000000"     # Uses simple black borders
  card: "#d6f6d6"       # Nyanza (Soft Green)
  accent: "#008080"
  
  dark:
    background: "#0a0a0a"
    foreground: "#f5f5f5"
    muted: "#a1a1a1"
    border: "#ffffff"
    card: "#121212"
    accent: "#008080"

typography:
  fontFamily:
    sans: "Inter, system-ui, -apple-system, sans-serif"
  body:
    fontSize: "16px"
    lineHeight: "1.5"
  heading:
    fontWeight: "700"

rounded:
  default: "4px"
  md: "8px"
  full: "9999px"
---

# Design System: Tally

## Overview
Tally's design system is "The Minimalist Builder." Often compared to Notion, it uses a clean, text-first environment with simple teal accents and pastel backgrounds to make form building feel like writing a document.

## Design Philosophy
1. **Writing as Building:** The UI is designed to be a blank canvas where users type to create form fields, using a "slash-command" interface.
2. **Frictionless Simplicity:** Rejects the "blocky" and complex drag-and-drop builders for a clean, editorial experience.
3. **The "Teal" Anchor:** Uses a professional teal (#008080) for its logo and primary actions to establish a sense of calm and reliability.
4. **Pastel Friendliness:** Uses soft green (#D6F6D6) for secondary backgrounds to create a friendly, approachable feel.

## Colors
- **Tally Teal (#008080):** The primary identifier, representing the brand's balance of creativity and utility.
- **Nyanza (#D6F6D6):** A soft, pastel green used for success messages, "Start" buttons, and highlights.
- **Simple Contrast:** Relies heavily on Black and White with 1px borders to define structure without visual weight.

## Typography
- **Inter:** The backbone of the builder, providing a neutral, high-legibility voice for both the creator and the form-filler.
- **Hierarchy:** Uses bold headers and generous line-height to create an airy, readable document feel.

## Components
- **The Builder Canvas:** A simple, white vertical space where fields appear as text blocks.
- **Slash Menu:** A minimalist, text-first popup for inserting form elements (e.g., /text, /email, /dropdown).
- **Form Preview Card:** A clean, highly-rounded or sharp-edged card that shows how the final form will look.

## Visual Effects
- **Border-based Separation:** Uses 1px solid black borders for inputs and containers.
- **Subtle Row Highlights:** Uses the soft green background to indicate the currently active block or field.
- **Fast Content Fades:** Smooth, simple transitions as elements are added or the form is saved.
