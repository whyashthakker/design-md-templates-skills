---
name: Flipkart
colors:
  background: "#ffffff"
  foreground: "#212121"
  brand: "#2874f0"      # Primary Blue
  muted: "#878787"
  border: "#f0f0f0"
  card: "#ffffff"
  accent: "#fb641b"     # Action Orange
  secondary: "#ffe000"  # Primary Yellow
  
  dark:
    background: "#0a0a0a"
    foreground: "#f0f0f0"
    muted: "#878787"
    border: "#212121"
    card: "#1a1a1a"
    accent: "#fb641b"

typography:
  fontFamily:
    sans: "Roboto, Inter, system-ui, sans-serif"
  body:
    fontSize: "14px"
    lineHeight: "1.4"
  heading:
    fontWeight: "500"

rounded:
  default: "2px" # Flipkart uses very sharp/minimalist rounding
  md: "4px"
  full: "9999px"
---

# Design System: Flipkart

## Overview
Flipkart's design system is built for massive scale and high conversion. It is characterized by its high-contrast "Blue and Yellow" palette and a layout optimized for scanning thousands of products.

## Design Philosophy
1. **High-Speed Commerce:** The UI is designed to minimize friction between discovery and purchase.
2. **Trust & Familiarity:** Uses standard e-commerce patterns and a professional blue to build trust with a diverse user base.
3. **Incentive-Driven:** Highlights discounts, offers, and "SuperCoins" using high-contrast colors (Yellow and Orange).
4. **Information Density:** Packs a lot of product data (Price, Discount, Rating, Delivery) into small cards for mobile-first efficiency.

## Colors
- **Flipkart Blue (#2874F0):** Represents trust, stability, and the brand's digital identity.
- **Flipkart Yellow (#FFE000):** Used for the primary logo and "Plus" membership, representing value and excitement.
- **Action Orange (#FB641B):** The "Conversion Color" used for "Buy Now" and "Add to Cart" buttons.

## Typography
- **Roboto:** The workhorse of the interface, providing zero-latency legibility across all Android and Web platforms.
- **Compact Scales:** Uses a tight typographic scale to fit more information into mobile viewports.

## Components
- **The Search Bar:** A prominent white bar at the top, usually anchored within a Blue header.
- **Product Cards:** Dense units with 2px rounding, featuring integrated "Assured" badges and multi-color price highlights.
- **Offer Banners:** High-impact, multi-colored strips that scroll horizontally at the top of the feed.

## Visual Effects
- **Minimalist Depth:** Relies on color blocks and thin borders rather than complex shadows or blurs.
- **Highlight Glows:** Uses subtle yellow glows for "Flipkart Plus" and other premium membership elements.
- **State Feedback:** Simple background color shifts on hover or press for immediate feedback.
