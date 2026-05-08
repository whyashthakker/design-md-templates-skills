---
name: Cron (Notion Calendar)
colors:
  background: "#000000"
  foreground: "#ffffff"
  brand: "#ffffff"
  muted: "#666666"
  border: "#222222"
  card: "#111111"
  accent: "#2483e2"     # Cron Blue
  
  light:
    background: "#ffffff"
    foreground: "#111111"
    muted: "#888888"
    border: "#f0f0f0"
    card: "#f9fafb"

typography:
  fontFamily:
    sans: "Inter, system-ui, -apple-system, sans-serif"
  body:
    fontSize: "13px"
    lineHeight: "1.4"
  heading:
    fontWeight: "600"

rounded:
  default: "4px" # Cron is very precise and relatively sharp
  md: "6px"
  full: "9999px"
---

# Design System: Cron (Notion Calendar)

## Overview
Cron's design system is "The Masterpiece of Time." It is a precision-engineered, dark-first environment that prioritizes speed, density, and zero-distraction scheduling for power users.

## Design Philosophy
1. **Mechanical Precision:** The UI is designed to feel like a high-end digital clock—precise, fast, and impeccably aligned.
2. **The "Black Box":** Dark mode is the primary experience, using deep blacks (`#000000`) and thin grey lines to minimize visual noise.
3. **Density for Power:** Packs a full week of events, meetings, and overlaps into a single view without feeling cluttered.
4. **Keyboard-First:** Every element is reachable via hotkey, and the UI reacts instantly to user commands.

## Colors
- **Pure Dark (#000000):** The foundation of the Cron aesthetic, creating a high-contrast canvas for colorful events.
- **Cron Blue (#2483E2):** Used for primary highlights, the current time indicator, and brand presence.
- **Vibrant Event Palette:** Uses a curated set of colors (Sage, Lavender, Flamingo) for different calendars, ensuring they remain legible on dark backgrounds.

## Typography
- **Inter:** Chosen for its neutrality and precision, ensuring that calendar event titles are readable even when truncated.
- **Tight Hierarchy:** Uses condensed scales to fit more data into the time grid.

## Components
- **The Time Grid:** A highly-structured area with 1px borders and a prominent red "current time" line.
- **The Mini-Month Sidebar:** A compact, high-density calendar for fast date jumping.
- **Command Palette:** A center-focused, floating bar with a minimalist list of actions and shortcuts.

## Visual Effects
- **Snap-to-Grid:** Dragging events features a high-fidelity "snapping" animation that reinforces the precision feel.
- **Subtle Glows:** The current day or time often features a very subtle glow to draw the user's eye.
- **Fast Transitions:** View switches (Day to Week) are snappy and use minimal motion to maintain focus.
