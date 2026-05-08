---
name: Descript
colors:
  background: "#ffffff"
  foreground: "#1a1a1a" # Woodsmoke
  brand: "#0062ff"      # Descript Blue
  muted: "#888888"
  border: "#e5e5e5"
  card: "#f4f4f4"
  accent: "#0062ff"
  
  dark:
    background: "#121212"
    foreground: "#ffffff"
    muted: "#666666"
    border: "#262626"
    card: "#1a1a1a"
    accent: "#0062ff"

typography:
  fontFamily:
    sans: "Inter, system-ui, -apple-system, sans-serif"
    mono: "JetBrains Mono, Courier New, monospace"
  body:
    fontSize: "15px"
    lineHeight: "1.5"
  heading:
    fontWeight: "700"
    letterSpacing: "-0.01em"

rounded:
  default: "4px"
  md: "8px"
  lg: "12px"
  full: "9999px"
---

# Design System: Descript

## Overview
Descript's design system is "Media Editing for the Post-Text World." It is a high-contrast, energetic environment that combines the precision of a video editor with the clarity of a modern text processor.

## Design Philosophy
1. **Text-First Editing:** The UI is anchored on a transcript-style view, where editing text edits the video/audio. This requires a typography-centric layout.
2. **Vibrant Precision:** Uses a "Vibrant Blue" (#0062FF) to represent the "active" state of creation and the brand's digital energy.
3. **High Signal Grays:** Uses a meticulously defined scale of light and dark greys to manage the complexity of layers, timelines, and tools.
4. **Seamless Transition:** Designed to move the user effortlessly between the script (Text) and the scene (Visual).

## Colors
- **Descript Blue (#0062FF):** The primary identifier, used for playback controls, primary buttons, and the brand's digital identity.
- **Woodsmoke (#1A1A1A):** A professional, deep grey used for text and secondary headers to ensure high legibility.
- **The "Tool" Palette:** Uses subtle greens and purples for different media tracks (Audio vs. Video).

## Typography
- **Inter:** The workhorse of the interface, providing exceptional clarity for the transcript-based editor.
- **Monospace for Time:** Uses Mono fonts for timestamps, frame counts, and technical metadata.

## Components
- **The Script Editor:** A clean, white vertical space with integrated speaker labels and word-level selection.
- **The Timeline:** A horizontal, multi-track container with 1px markers and colorful "clip" pills.
- **Scene Rail:** A vertical or horizontal list of thumbnails representing the visual structure of the project.

## Visual Effects
- **Word-level Highlighting:** Uses a subtle blue background to indicate the currently playing word in the script.
- **Spring-based Scrubbing:** The playhead and timeline movements feature high-fidelity, spring-based motion.
- **Translucent Overlays:** Uses subtle `rgba` backgrounds for toolbars to maintain context with the media preview.
