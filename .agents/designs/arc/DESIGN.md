---
name: Arc
colors:
  background: "transparent" # Arc uses translucency
  foreground: "#ffffff"
  brand: "#ffffff"
  muted: "rgba(255, 255, 255, 0.6)"
  border: "rgba(255, 255, 255, 0.1)"
  card: "rgba(255, 255, 255, 0.05)"
  accent: "variable"      # Based on Space theme
  
  dark:
    background: "rgba(0, 0, 0, 0.4)"
    foreground: "#ffffff"
    muted: "rgba(255, 255, 255, 0.5)"
    border: "rgba(255, 255, 255, 0.1)"
    card: "rgba(255, 255, 255, 0.05)"

typography:
  fontFamily:
    sans: "Inter, system-ui, -apple-system, sans-serif"
  body:
    fontSize: "13px"
    lineHeight: "1.4"
  heading:
    fontWeight: "600"

rounded:
  default: "10px"
  md: "12px"
  lg: "20px"
---

# Design System: Arc

## Overview
Arc's design system is "The Internet's Sidebar." It is a translucent, material-first environment that emphasizes customization, focus, and a "sampling" of the user's desktop context.

## Design Philosophy
1. **Translucency & Materials:** The UI is not a solid color; it uses `backdrop-filter: blur` and transparency to feel integrated with the OS and the user's wallpaper.
2. **Sidebar-Centric:** All navigation is vertical and tucked away, maximizing the real estate for the web content itself.
3. **Personal Spaces:** Uses "Themes" where users can define a color temperature and gradient for each Space, making the UI feel personal.
4. **Subtractive Chrome:** Removes traditional browser elements (URL bar, tabs at top) to create a clean, "framed" window look.

## Colors
- **Dynamic Accents:** The UI hue is defined by the "Space" theme. It often uses rich, vibrant gradients (e.g., Sunset, Forest, Ocean).
- **Translucent Neutrals:** Uses varying opacities of white and black to create layers without adding heavy solid colors.
- **Vibrancy:** The primary "color" is the background wallpaper sampled through a high-blur filter.

## Typography
- **Inter:** Used for its neutrality and high legibility at small sizes (13px) required for a dense sidebar.
- **Lowercase Utility:** Many labels in the sidebar use lowercase to feel more informal and tool-like.

## Components
- **The Sidebar:** A vertical, translucent container with `10px` rounding and integrated tab management.
- **The "Command T" Bar:** A center-focused, floating search bar with a high-blur background and zero-latency feedback.
- **Site Frames:** Web content is "framed" within a rounded container (`10px`), separating the browser UI from the website.

## Visual Effects
- **Backdrop Blur:** Heavy use of `blur(20px)` to create a sense of glass and depth.
- **Glassmorphism:** Relies on 1px translucent borders (`rgba(255,255,255,0.1)`) to define edges.
- **Fluid Layout:** The sidebar slides and morphs smoothly based on user interaction (hover to expand).
