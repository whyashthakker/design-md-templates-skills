---
name: explainx.ai
colors:
  background: "#fafafa"
  foreground: "#141418"
  muted: "#52525b"
  border: "#d4d4d8"
  card: "#f4f4f5"
  accent: "#ededf0"
  brand: "#0f766e"
  brand-hover: "#115e59"
  
  dark:
    background: "#09090b"
    foreground: "#fafafa"
    muted: "#71717a"
    border: "#27272a"
    card: "#111113"
    accent: "#18181b"
    brand: "#00ff88"
    brand-hover: "#5dffc4"

typography:
  fontFamily:
    mono: 'var(--font-geist-mono), "Fira Mono", "Courier New", monospace'
    sans: 'var(--font-geist-sans), ui-sans-serif, system-ui'
  body:
    fontFamily: mono
    fontSize: 14px
  heading:
    fontFamily: mono
    fontWeight: 700

rounded:
  default: 4px
  md: 6px
  lg: 8px
---

# Design System: explainx.ai

## Overview
explainx.ai is a terminal-inspired, clean, and highly functional registry for AI agents and skills. The aesthetic is "Modern Terminal" — combining the precision of developer tools with modern web clarity.

## Design Philosophy
1. **Developer First:** Prioritize monospace fonts, code-like structures, and keyboard-centric metaphors.
2. **High Signal, Low Noise:** Use borders instead of shadows for separation. Maintain high contrast.
3. **Reactive Feedback:** Use glowing effects (box-shadows with low opacity) for primary interactive elements and focus states.

## Colors
- **Brand Green:** The signature color. In light mode, it's a deep teal (`#0f766e`). In dark mode, it's a vibrant neon mint (`#00ff88`). This color represents "active" or "powered-on" states.
- **Surface Colors:** Backgrounds and cards use a very clean, near-neutral palette. Dark mode uses a deep "near-black" (`#09090b`) to make green accents pop.

## Typography
- **Primary (Mono):** Geist Mono is the primary font for everything—body, headers, buttons. It reinforces the technical, terminal-like nature of the platform.
- **Secondary (Sans):** Geist Sans is used sparingly for long-form marketing content or specific UI where high-density mono text might become fatiguing.

## Components

### Buttons
- **Primary (`.btn-green`):** Solid brand green background. Text color should be dark (`#09090b`) for high contrast. In dark mode, it features a `0 0 20px var(--green-glow)` hover effect.
- **Ghost/Outline:** Transparent or subtle background with a 1px border.

### Inputs (`.input-terminal`)
- Monospace font.
- Subtle background contrast.
- Focus state: Brand green border with a glow effect (`0 0 12px var(--green-glow)`).

### Cards
- No elevation or drop shadows.
- 1px border (`var(--border)`).
- Card background (`var(--card)`).

## Visual Effects
- **Terminal Grid:** A subtle 40px linear gradient grid used for hero backgrounds (`.grid-bg`).
- **Glows:** Used on text, borders, and buttons to simulate a CRT or LED display.
- **Scanlines:** A vertical translation animation used on large containers for aesthetic flair.
- **Animations:** Prefer "Fade Up" entries and "Cursor Blink" for interactive text to simulate terminal loading.
