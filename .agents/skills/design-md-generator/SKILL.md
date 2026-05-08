# Skill: design-md

A specialized skill for creating and maintaining `DESIGN.md` files—a machine-readable design system specification that enables AI agents to generate consistent UI.

## Goal
To translate a project's visual identity, brand guidelines, or existing UI patterns into a structured `DESIGN.md` file containing both YAML design tokens and Markdown rationale.

## Instructions

### 1. Research Phase
- **Extract Tokens:** Identify primary, secondary, and accent colors (Hex codes).
- **Dark Mode:** Determine if a dark mode exists and identify its specific tokens.
- **Typography:** Identify font families (Sans, Mono, Serif), font sizes for body/headings, and font weights.
- **Layout & Components:** Identify border radius scales, spacing scales, and specific component patterns (buttons, inputs, cards).
- **Philosophy:** Understand the "vibe" (e.g., "Modern Terminal", "Enterprise Minimal", "Playful Creative").

### 2. File Structure
The `DESIGN.md` must follow this structure:

```markdown
---
name: [Project Name]
colors:
  background: "#[HEX]"
  foreground: "#[HEX]"
  brand: "#[HEX]"
  # ... other tokens
  dark:
    background: "#[HEX]"
    # ... dark mode overrides
typography:
  fontFamily:
    sans: "[Font Name], [Fallbacks]"
    mono: "[Font Name], [Fallbacks]"
  # ... size/weight tokens
rounded:
  default: "[px/rem]"
---

# Design System: [Project Name]

## Overview
Short description of the aesthetic and goals.

## Design Philosophy
Bullet points explaining the "why" behind the design.

## Colors
Detailed explanation of color usage.

## Typography
Guidance on font selection and hierarchy.

## Components
Specific rules for common UI elements (Buttons, Inputs, Cards).

## Visual Effects
Optional section for gradients, glows, or animations.
```

### 3. Standards
- **Surgical Precision:** Use exact Hex values from source code (e.g., `tailwind.config.ts`, `globals.css`).
- **Machine Readable:** Ensure the YAML front matter is valid and uses consistent keys (`colors`, `typography`, `rounded`).
- **Human Centric:** The Markdown body should provide clear rationale so developers understand the *intent*.
- **Syncing:** When the codebase changes (e.g., new Tailwind colors), update `DESIGN.md` to match.

## Available Resources
- `tailwind.config.ts`: Primary source for colors and themes.
- `globals.css`: Source for CSS variables and global component styles.
- Brand Assets: Logos, style guides, or reference URLs.
