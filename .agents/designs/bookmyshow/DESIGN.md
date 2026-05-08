---
name: BookMyShow
colors:
  background: "#ffffff"
  foreground: "#121212"
  brand: "#df1827"      # Primary Red
  muted: "#757575"
  border: "#eeeeee"
  card: "#ffffff"
  accent: "#333290"     # Cosmic Cobalt
  secondary: "#522b86"  # Spanish Violet
  
  dark:
    background: "#000000"
    foreground: "#ffffff"
    muted: "#a1a1a1"
    border: "#1f1f1f"
    card: "#121212"
    accent: "#df1827"

typography:
  fontFamily:
    sans: "Inter, system-ui, -apple-system, sans-serif"
  body:
    fontSize: "14px"
    lineHeight: "1.4"
  heading:
    fontWeight: "700"

rounded:
  default: "4px"
  md: "8px"
  lg: "12px"
  full: "9999px"
---

# Design System: BookMyShow

## Overview
BookMyShow's design system is "The Ticket to Entertainment." It uses a high-contrast red-and-white palette for utility, transitioning into rich, cosmic gradients for discovery and mood.

## Design Philosophy
1. **Entertainment First:** The UI acts as a digital lobby—clean, exciting, and ready to transport the user to an event.
2. **Contextual Immersion:** Uses dark themes and cinematic gradients for movie browsing, while keeping light themes for ticket management.
3. **Seamless Flow:** Designed to move the user from "Interest" to "Seat Selection" to "Payment" with minimal distraction.
4. **Vibrant Urgency:** The brand red (`#DF1827`) is used for "Book Now" and other time-sensitive calls to action.

## Colors
- **Real Red (#DF1827):** The signature brand color used for primary CTAs and status identifiers.
- **Cosmic Gradient:** A mix of Cosmic Cobalt (`#333290`), Spanish Violet (`#522B86`), and Ruby (`#E7165A`) used for headers and premium event discovery.
- **Cinema Black:** Pure black used in movie-specific sections to simulate the theater experience.

## Typography
- **Inter:** Ensures that movie titles, timings, and prices are always perfectly legible.
- **Scale:** Uses large, bold headers for movie titles and vibrant weights for "Special Offers."

## Components
- **The Movie Card:** A vertical poster format with integrated ratings and "Book" button.
- **Seat Selection Grid:** A high-density, interactive grid with clear status colors (Available, Selected, Sold Out).
- **Ticket Stub:** A unique, skeuomorphic-inspired component that mimics a physical ticket for successful bookings.

## Visual Effects
- **Cinematic Overlays:** Uses `backdrop-filter: blur` and translucent dark backgrounds for movie trailers and details.
- **Hover Poster Lift:** Movie posters lift and show a subtle shadow when hovered.
- **Glow Accents:** Uses red or violet glows to indicate high-demand "Filling Fast" shows.
