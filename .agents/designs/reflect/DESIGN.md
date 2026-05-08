---
name: Reflect
colors:
  background: "#ffffff"
  foreground: "#111111"
  brand: "#000000"
  muted: "#888888"
  border: "#f0f0f0"
  card: "#ffffff"
  accent: "#2483e2"
  
  dark:
    background: "#0d0e10"
    foreground: "#eff3f4"
    muted: "#666666"
    border: "#1f1f1f"
    card: "#121417"
    accent: "#2483e2"

typography:
  fontFamily:
    sans: "Inter, system-ui, -apple-system, sans-serif"
    serif: "Lyon-Text, Georgia, serif"
  body:
    fontSize: "16px"
    lineHeight: "1.6"
    fontWeight: "400"
  heading:
    fontFamily: serif
    fontWeight: "600"
    letterSpacing: "-0.01em"

rounded:
  default: "4px"
  md: "8px"
  full: "9999px"
---

# Design System: Reflect

## Overview
Reflect's design system is "The Minimalist Second Brain." It is an elegant, typography-first environment designed for deep focus, structured notes, and frictionless data recall.

## Design Philosophy
1. **Typography as Interface:** The UI is almost entirely defined by the relationship between its serif headings and sans-serif body text.
2. **Restrained Minimalism:** Rejects decorative elements for a clean, monochrome-first aesthetic that minimizes cognitive load.
3. **The "Daily" Focus:** The UI is built around a daily note, prioritizing the "Now" while making the "Past" easily reachable through back-links.
4. **Quiet Intelligence:** Uses subtle icons and thin lines to guide the user without distracting from the content.

## Colors
- **Pure Monochrome:** Primarily uses absolute Black and White, with a deep "Hunter Black" for dark mode.
- **Subtle Highlights:** Uses very soft, tinted backgrounds (Pastel Blue, Green) for back-links and highlighted text.
- **Functional Accents:** A single professional blue is used sparingly for primary interactive states.

## Typography
- **Lyon (Serif):** Used for headings to create a literary, thoughtful, and high-quality "notebook" feel.
- **Inter (Sans):** Handles the day-to-day writing and interface utility with exceptional clarity.

## Components
- **The Graph View:** A signature, minimalist visualization of notes as nodes and links in a 2D space.
- **The Daily Note:** A full-screen, distraction-free writing environment with integrated "Backlinks" and "Incoming" sections.
- **Command Palette:** A center-focused, minimalist search bar that is the primary way to jump between notes.

## Visual Effects
- **Airy White Space:** High use of padding and margins to "let the thoughts breathe."
- **Minimalist Depth:** Relies on thin borders and subtle background shifts rather than shadows.
- **Fast Content Search:** Designed for instant result appearing as the user types in the search bar.
