---
name: Ola
colors:
  background: "#ffffff"
  foreground: "#000000"
  brand: "#d6df22"      # Sporty Green (Lime)
  muted: "#7c7c7c"
  border: "#eeeeee"
  card: "#ffffff"
  accent: "#d6df22"
  
  dark:
    background: "#000000"
    foreground: "#ffffff"
    muted: "#888888"
    border: "#222222"
    card: "#121212"
    accent: "#d6df22"

typography:
  fontFamily:
    sans: "Inter, system-ui, -apple-system, sans-serif"
  body:
    fontSize: "14px"
    lineHeight: "1.4"
  heading:
    fontWeight: "700"
    letterSpacing: "-0.01em"

rounded:
  default: "4px"
  md: "8px"
  lg: "16px"
  full: "9999px"
---

# Design System: Ola

## Overview
Ola's design system is "Sporty and Efficient." It uses a high-contrast pairing of black and lime green to communicate movement, technology, and electric energy.

## Design Philosophy
1. **Dynamic Mobility:** The UI is designed to feel fast and reactive, mirroring the speed of urban transport.
2. **High-Contrast Clarity:** Uses Sporty Green (`#D6DF22`) against deep black to ensure critical information (ETA, Price) is visible in all lighting conditions.
3. **Electric Transition:** Recent designs (Ola Electric) emphasize sleek, futuristic minimalism with large typography and clean surfaces.
4. **Platform Familiarity:** Uses standard map-based patterns to ensure zero-friction booking.

## Colors
- **Sporty Green (#D6DF22):** A vibrant lime green that represents the brand's shift toward sustainable, electric mobility.
- **Ola Black (#000000):** Used for primary backgrounds and headers to create a premium, high-tech feel.
- **Silver Cloud:** Subtle greys used for map overlays and secondary UI elements.

## Typography
- **Inter:** A clean, functional sans-serif that ensures map labels and trip details are always legible.
- **Bold Metrics:** ETA and trip costs are rendered in large, bold typography for immediate scanning.

## Components
- **The Booking Sheet:** A bottom-anchored, rounded sheet (`16px`) that contains all trip options and pricing.
- **Vehicle Icons:** Minimalist, top-down icons of cabs, autos, and scooters that move smoothly across the map.
- **Ride Status Bar:** A high-contrast bar at the top or bottom that provides real-time updates on the driver's location.

## Visual Effects
- **Pulse Animations:** Used on the map to indicate the user's location and active search areas.
- **Smooth Map Transitions:** Fast, fluid zooming and panning as the user switches between services.
- **Neon Highlights:** Uses the brand green as a glow or outline for active state buttons.
