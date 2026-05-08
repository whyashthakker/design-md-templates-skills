---
name: Loom
colors:
  background: "#ffffff"
  foreground: "#111111"
  brand: "#0052cc"      # Loom Blue (Atlassian Blue)
  muted: "#6b778c"
  border: "#ebecf0"
  card: "#f4f5f7"       # Athens Gray
  accent: "#c2493d"     # Mojo (Red)
  
  dark:
    background: "#091e42" # Atlassian Deep Blue
    foreground: "#ffffff"
    muted: "#a5adba"
    border: "#172b4d"
    card: "#102a43"
    accent: "#ff5630"

typography:
  fontFamily:
    sans: "Inter, system-ui, -apple-system, sans-serif"
  body:
    fontSize: "14px"
    lineHeight: "1.5"
  heading:
    fontWeight: "700"

rounded:
  default: "4px"
  md: "8px"
  full: "9999px"
---

# Design System: Loom

## Overview
Loom's design system is "The Communication Bridge." Recently updated to align with Atlassian's design language, it uses a professional blue palette and friendly, approachable components to make video messaging effortless.

## Design Philosophy
1. **Communication Clarity:** The UI is designed to get the user from "Record" to "Send" in the shortest possible time.
2. **Professional Trust:** Uses a deep "Atlassian Blue" to establish credibility within the enterprise workspace.
3. **Friendly Presence:** Integrates avatars and recording bubbles to maintain a human connection in asynchronous video.
4. **Focused Recording:** During capture, the UI recedes, leaving only the signature "recording bubble" and a few essential controls.

## Colors
- **Loom Blue (#0052CC):** The core brand color, representing stability and collaborative intelligence.
- **Athens Gray (#F4F5F7):** A cool, light grey used for secondary backgrounds and card surfaces.
- **Mojo Red (#C2493D):** The "Recording" color. It is used for the active record button and status indicators.

## Typography
- **Inter:** Ensures that video comments, transcripts, and titles are legible and professional.
- **Compact Scales:** Uses a tight typographic hierarchy to manage video metadata and user notifications.

## Components
- **The Recording Bubble:** A signature circular overlay showing the user's camera during screen recording.
- **Video Library Card:** A structured unit with a large thumbnail, time stamp, and integrated "Share" action.
- **Comment Sidebar:** A clean, vertical list of timestamped comments integrated directly into the video player.

## Visual Effects
- **Pulse Indicators:** The red record button pulses to indicate active capture.
- **Soft Overlays:** Uses light-blue translucent backgrounds for hover states on video cards.
- **Smooth Expansion:** Hovering over the recording bubble reveals a set of fast, professional controls.
