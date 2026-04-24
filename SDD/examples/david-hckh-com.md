# Application Blueprint: "Creative Developer" Style

This blueprint defines the aesthetic, technical stack, and interaction patterns
inspired by david-hckh.com. Use this guide to replicate a high-end,
motion-focused "Creative Portfolio" look for other products.

## 1. Technical Stack

- **Framework:** ReactJS (TypeScript-driven).
- **Animation:** GSAP (GreenSock Animation Platform) - Primary engine for
  scroll-triggered and complex motion.
- **3D/Graphics:** Three.js & WebGL - For immersive backgrounds, interactive
  heroes, and particle systems.
- **Styling:** CSS-in-JS (Styled Components) or high-performance modular SCSS.
- **State:** Lightweight state management (Zustand or context) to sync
  animations with UI logic.

## 2. Visual Identity & Aesthetic

The style is "Immersive Modern Creative," focusing on the boundary between art
and code.

### Color Palette

- **Base:** Deep Black (`#0a0a0a`) or dark charcoal for high-contrast
  backgrounds.
- **Accents:** High-vibrancy gradients (e.g., Electric Blue to Neon Pink) used
  in WebGL elements and highlight text.
- **Neutral:** Pure White (`#ffffff`) for body text and bold headers.

### Typography

- **Primary:** Bold, oversized Display Typefaces (e.g., Helvetica Now, Neue
  Montreal).
- **Hierarchy:** Extreme contrast between massive hero headers and small,
  monospaced metadata/captions.
- **Interaction:** Typography often responds to scroll or cursor movements
  (skewing, masking, or color shifting).

## 3. UI Patterns & Components

### The "Immersive Hero"

- **WebGL Background:** A fluid, interactive 3D scene (particles, distorted
  meshes, or shaders) that reacts to cursor position.
- **Floating HUD:** Minimalist navigation and social links that feel like an
  overlay on the 3D scene.

### Scroll-Triggered Narratives

- **Pinning & Scrubbing:** Components that stay pinned while the internal
  content (text/images) animates in/out based on scroll progress.
- **Layered Transitions:** Background colors and typography "swapping"
  seamlessly as the user scrolls through different narrative sections.

### Interactive Cursor

- **Custom Pointer:** A "blob" or "circle" cursor that morphs, scales, or
  changes color when hovering over interactive elements.
- **Magnetic Elements:** Buttons and links that "pull" the cursor towards them
  when nearby.

## 4. Replicating for a Product (e.g., High-End E-Commerce)

### Concept Transformation

- **Product Presentation:** Instead of static images, use Three.js to show the
  product in a 3D space with cinematic camera movements on scroll.
- **Feature Highlights:** Use GSAP to "explode" the product into parts or
  highlight specific specs as they scroll into view.
- **Checkout Experience:** A sleek, minimal overlay that maintains the dark
  aesthetic and high-motion feel.

### Styling Application

1. **Motion First:** Define the "Timeline" of the user experience before layout.
2. **3D Integration:** Use `react-three-fiber` for React-native 3D scene
   management.
3. **Smooth Scroll:** Implement a smooth-scrolling library (like Lenis) to
   ensure GSAP animations feel buttery smooth.
4. **Performance:** Optimize shader code and GSAP timelines to maintain 60fps
   across devices.

## 5. Project-Specific Specifications Template

Use this section to define the unique requirements for the new application.

- **App Name/ID:** (e.g., LUX_MARKET)
- **Primary Goal:** (e.g., Showcase high-end fashion with immersive motion)
- **Target Platform:** Web (Desktop-first optimized for high-performance GPUs)
- **Core Modules & Routes:**
  - `Hero/Intro`: [Interactive 3D Intro]
  - `Collection`: [Scroll-animated grid]
- **Key Features:**
  - [Feature 1]: [Interaction details, e.g., 3D Product Zoom]
  - [Feature 2]: [Interaction details, e.g., GSAP Scroll Story]
- **Specific Visuals:**
  - [WebGL Effect]: (e.g., Noise shaders, Liquid distortion)
- **Custom Cursor Behavior:** (e.g., Cursor reveals hidden details behind a
  mask)

---
