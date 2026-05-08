---
name: Zomato
colors:
  background: "#ffffff"
  foreground: "#2d2d2d" # Zomato Mine Shaft
  brand: "#cb202d"      # Primary Red
  muted: "#828282"
  border: "#f4f4f2"     # Desert Storm
  card: "#ffffff"
  accent: "#cb202d"
  
  dark:
    background: "#0a0a0a"
    foreground: "#f4f4f2"
    muted: "#828282"
    border: "#2d2d2d"
    card: "#1a1a1a"
    accent: "#cb202d"

typography:
  fontFamily:
    sans: "Okra, Inter, system-ui, sans-serif"
  body:
    fontSize: "14px"
    lineHeight: "1.5"
  heading:
    fontWeight: "600"
    letterSpacing: "-0.01em"

rounded:
  default: "8px"
  md: "12px"
  lg: "16px"
---

# Design System: Zomato

## Overview
Zomato's design system is built for appetite and speed. It uses a high-energy red and clean, food-first layouts to guide users toward their next meal.

## Design Philosophy
1. **Appetite First:** The UI recedes to make food photography the primary focus.
2. **High-Energy Action:** The "Zomato Red" is used for all primary conversion points, creating a sense of urgency and excitement.
3. **Clean Density:** Information about ratings, prices, and delivery times is presented in a highly structured, scannable format.
4. **Reliability:** Clear, consistent iconography and status updates build trust throughout the ordering process.

## Colors
- **Zomato Red (#CB202D):** The signature "Fire Engine Red" that represents the brand's energy and passion for food.
- **Desert Storm (#F4F4F2):** A subtle off-white used for backgrounds and borders to provide a clean, "fresh" feel.
- **Mine Shaft (#2D2D2D):** A deep grey used for text and secondary headers to ensure high legibility without the harshness of pure black.

## Typography
- **Okra:** Zomato's custom typeface, designed to be friendly yet professional, with high legibility for small UI text.
- **Visual Hierarchy:** Uses bold weights for restaurant names and ratings to create clear entry points for the eye.

## Components
- **The Rating Chip:** A small, high-contrast box (usually Green, Yellow, or Red) that is the most looked-at element in the UI.
- **Restaurant Cards:** Feature large, bleed-edge photography and integrated delivery status markers.
- **Filter Pills:** Rounded pills used for quick category selection, using subtle grey backgrounds and bold active states.

## Visual Effects
- **Soft Shadows:** Uses very subtle shadows to lift cards off the background without creating visual clutter.
- **Progressive Disclosure:** Hides secondary information (like detailed reviews) until the user expresses interest.
- **Fast Transitions:** Uses snappy animations to mimic the speed of delivery and service.
