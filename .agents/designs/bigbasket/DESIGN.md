---
name: BigBasket
colors:
  background: "#ffffff"
  foreground: "#231f20" # Attractive Black
  brand: "#a0cd4a"      # Guacamole Green
  muted: "#7c7c7c"
  border: "#f0f0f0"
  card: "#ffffff"
  accent: "#1268b3"     # Reliability Blue
  secondary: "#f61b2c"  # Sporty Red
  
  dark:
    background: "#0a0a0a"
    foreground: "#f5f5f5"
    muted: "#a1a1a1"
    border: "#231f20"
    card: "#121212"
    accent: "#a0cd4a"

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
  lg: "16px"
  full: "9999px"
---

# Design System: BigBasket

## Overview
BigBasket's design system is built for "Freshness and Reliability." It uses a multi-color palette (Green, Red, Blue) to represent the diversity of its grocery catalog and its commitment to quality.

## Design Philosophy
1. **The Modern Mandi:** Designed to feel as vibrant and diverse as a traditional Indian market, but with digital precision.
2. **Freshness Indicator:** Uses "Guacamole Green" (`#A0CD4A`) as the primary brand color to represent health and fresh produce.
3. **Trust & Scale:** Uses "Reliability Blue" (`#1268B3`) for sub-brands and institutional trust.
4. **Efficiency for Grocery:** Prioritizes "Add to Cart" speed, smart search, and easy multi-item management.

## Colors
- **Guacamole Green (#A0CD4A):** The signature brand color representing freshness and health.
- **Reliability Blue (#1268B3):** Used for "BB Instant," "BB Daily," and general corporate trust.
- **Sporty Red (#F61B2C):** Used for "Hot" deals and time-sensitive delivery options.

## Typography
- **Inter:** Ensures that product names, weights, and per-unit prices are legible for fast scanning.
- **Compact Hierarchy:** Uses a condensed scale to manage large grocery lists in a single view.

## Components
- **The "Smart Basket" Chip:** A prominent card or floating action area showing the current count of items in the cart.
- **Product Cards:** Dense units with 4px rounding, featuring integrated weight pickers and "Stock Out" status.
- **Delivery Slots Grid:** A highly structured, interactive area for choosing delivery times with clear status indicators.

## Visual Effects
- **Vibrant Iconography:** Uses highly detailed, colorful icons for sub-categories (Fruits, Vegetables, Meat).
- **Offer Highlighting:** Uses bright red and yellow tags for "BOGO" or "Percentage Off" deals.
- **Fast Cart Transitions:** Seamlessly updates totals and counts as items are added or removed.
