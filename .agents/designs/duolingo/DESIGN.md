---
name: Duolingo
colors:
  background: "#ffffff"
  foreground: "#4b4b4b"
  brand: "#58cc02"      # Duo Green
  muted: "#afafaf"
  border: "#e5e5e5"
  card: "#ffffff"
  accent: "#1cb0f6"     # Duo Blue
  secondary: "#ffc800"  # Duo Yellow
  error: "#ff4b4b"      # Duo Red
  
  dark:
    background: "#131f24"
    foreground: "#ffffff"
    muted: "#52656d"
    border: "#37464f"
    card: "#131f24"
    accent: "#1cb0f6"

typography:
  fontFamily:
    sans: "Feather, 'Din Next Rounded', system-ui, sans-serif"
  body:
    fontSize: "17px"
    lineHeight: "1.4"
    fontWeight: "700" # Duolingo loves bold body text
  heading:
    fontWeight: "800"
    letterSpacing: "0.02em"

rounded:
  default: "12px"
  md: "16px"
  lg: "20px"
  full: "9999px"
---

# Design System: Duolingo

## Overview
Duolingo's design system is "The World's Most Playful Classroom." It is a high-energy, gamified environment that uses vibrant colors and rounded, friendly shapes to make learning feel like a game.

## Design Philosophy
1. **Gamification as Standard:** Every UI element is designed to feel like a "level" or a "reward."
2. **Bold & Friendly:** Uses massive, rounded typography and a "super-saturated" color palette to maintain a high-energy, positive vibe.
3. **The Duo Voice:** The brand's mascot, Duo the Owl, is the primary guide, and the UI reflects his personality—playful, persistent, and occasionally sassy.
4. **Instant Feedback:** Uses vibrant semantic colors (Green for correct, Red for incorrect) and playful animations to keep learners engaged.

## Colors
- **Duo Green (#58CC02):** The signature brand color. It represents growth, energy, and success.
- **The 16-Color Palette:** Uses a wide range of saturated secondary colors (Yellow, Blue, Red, Purple) to represent different languages and achievement levels.
- **3D Depth:** Buttons often use a darker "bottom border" to simulate a physical, pressable button.

## Typography
- **Feather:** A custom, highly-rounded sans-serif that is the primary voice of the brand. It is designed to be friendly and approachable.
- **Bold Hierarchy:** Heavily relies on Extra Bold weights to create a sense of confidence and excitement.

## Components
- **The "Big" Button:** A standard `16px` rounded button with a `4px` darker bottom border that "depresses" when clicked.
- **Progress Rings:** Large, colorful rings that provide a visual representation of the user's daily goals.
- **Character Cards:** Feature Duo and his friends with speech bubbles, making the learning experience feel conversational.

## Visual Effects
- **Bouncy Animations:** Every transition has a subtle "bounce" to maintain the playful character.
- **Confetti:** Used as a celebratory effect for completing lessons or reaching milestones.
- **Isometric Icons:** Uses 3D-inspired icons for badges and streaks to create a sense of value and achievement.
