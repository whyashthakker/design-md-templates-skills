---
name: Reddit
colors:
  background: "#ffffff"
  foreground: "#1c1c1c"
  brand: "#ff4500"      # OrangeRed
  muted: "#7c7c7c"
  border: "#edeff1"
  card: "#ffffff"
  accent: "#0079d3"     # Reddit Blue
  
  dark:
    background: "#030303"
    foreground: "#d7dadc"
    muted: "#818384"
    border: "#343536"
    card: "#1a1a1b"
    accent: "#d7dadc"

typography:
  fontFamily:
    sans: "Reddit Sans, system-ui, sans-serif"
    mono: "Reddit Mono, monospace"
  body:
    fontSize: "14px"
    lineHeight: "1.5"
  heading:
    fontWeight: "700"
    letterSpacing: "-0.01em"

rounded:
  default: "4px"
  md: "12px" # Used for cards and main containers
  full: "9999px"
---

# Design System: Reddit

## Overview
Reddit's design system is built for the "front page of the internet." It prioritizes community discourse, content density, and a vibrant, "meme-ready" brand voice.

## Design Philosophy
1. **Content First, Community Second:** The UI is designed to handle high volumes of text and media, with a strong emphasis on voting and threading.
2. **The "OrangeRed" Energy:** The signature brand color (`#FF4500`) represents the heat of discussion and the brand's playful origins.
3. **Inclusive Discourse:** Typography is designed to be highly legible for fast-moving comment sections.
4. **Internet Native:** Embraces a "digital-first" aesthetic with bold colors, custom icons (Snoomoji), and a high-density layout.

## Colors
- **OrangeRed (#FF4500):** Used for primary actions (Upvote, Post) and brand highlights.
- **Neutral Grays:** Uses a range of subtle grays to create hierarchy in nested comment threads.
- **Dark Mode (#030303):** A deep, near-black canvas that makes vibrant content and the brand orange pop.

## Typography
- **Reddit Sans:** A custom humanist sans-serif. It features unique details like the 67.5° slashes to give it a technical yet friendly character.
- **Monospace for Context:** Reddit Mono is used for technical data, code snippets, and specific moderator tools.

## Components
- **The "Card":** A standard content unit with `12px` rounding, featuring integrated voting buttons and metadata.
- **Threaded Comments:** Uses vertical lines and whitespace to guide the user through deep conversations.
- **Pill Tags:** Subreddit names and flairs are rendered as high-radius pills for quick scanning.

## Visual Effects
- **The "Snoo" Mascot:** Integrated throughout the UI to provide personality and status feedback.
- **Micro-interactions:** Upvoting and downvoting feature fast, colorful animations to provide immediate social feedback.
- **Subreddit Styling:** The system allows for custom "theming" where individual communities can override brand colors with their own accents.
