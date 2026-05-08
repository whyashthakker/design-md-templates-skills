---
name: Family
colors:
  background: "#ffffff"
  foreground: "#111111"
  brand: "#0062ff"      # Family Blue
  muted: "#888888"
  border: "#f0f0f0"
  card: "#ffffff"
  accent: "#0062ff"
  
  dark:
    background: "#111111" # Midnight
    foreground: "#ffffff"
    muted: "#666666"
    border: "#222222"
    card: "#1a1a1a"
    accent: "#0062ff"

typography:
  fontFamily:
    sans: "Inter, system-ui, -apple-system, sans-serif"
  body:
    fontSize: "15px"
    lineHeight: "1.5"
    fontWeight: "400"
  heading:
    fontWeight: "600"
    letterSpacing: "-0.01em"

rounded:
  default: "16px" # Family is known for very soft, premium rounding
  md: "20px"
  lg: "32px"
  full: "9999px"
---

# Design System: Family

## Overview
Family's design system is "The Delightful Wallet." It brings a high-fidelity, consumer-grade polish to the crypto space, focusing on fluid motion, glass-like materials, and intuitive security.

## Design Philosophy
1. **Digital Craftsmanship:** Every detail—from the corner smoothing to the shadow depth—is tuned to a level of "perfect" polish.
2. **Trust through Delight:** Uses friendly, colorful UI and smooth animations to reduce the anxiety associated with financial transactions.
3. **Material Depth:** Heavy use of translucency and multi-layered shadows to create a sense of physical layering.
4. **Mobile-First Luxury:** Designed for touch, with large interactive targets and high-contrast feedback.

## Colors
- **Family Blue (#0062FF):** A vibrant, modern blue that represents trust and the brand's digital identity.
- **Midnight (#111111):** The signature dark mode foundation, providing a premium, "OLED-friendly" canvas.
- **Soft Aqua (#D5F3FE):** Used for "Connect" buttons and secondary highlights to create a friendly, approachable feel.

## Typography
- **Inter:** Provides a clean, neutral voice that supports the brand's high-fidelity visuals.
- **Hierarchy:** Uses font weights and subtle color shifts (Grey to Black) to guide the user through complex transaction data.

## Components
- **ConnectKit Modal:** A signature, highly-polished overlay with rounded corners (`20px`) and integrated wallet options.
- **Transaction Cards:** Feature high-radius rounding and large, colorful icons for different assets and tokens.
- **The "Pill" Status:** Large, rounded status badges for "Success," "Pending," or "Error" with vibrant background glows.

## Visual Effects
- **Glassmorphism:** Uses `backdrop-filter: blur(20px)` and translucent white/black for modals and menus.
- **Inner Glows:** Uses subtle 1px inner shadows to simulate light hitting the edge of a physical device.
- **Fluid Motion:** Interactions feature spring-based animations that feel organic and responsive.
