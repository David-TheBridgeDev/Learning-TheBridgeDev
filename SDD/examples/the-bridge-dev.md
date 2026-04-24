# Application Blueprint: "Techno-Retro OS" Style

This blueprint defines the aesthetic, technical stack, and interaction patterns of the current application. Use this guide to replicate the "TheBridgeDev" look and feel for other products (e.g., a Marketplace).

## 1. Technical Stack

- **Framework:** Angular (v18+) - Standalone Components architecture.
- **Styling:** SCSS (Modular) with CSS Variables for Theme support.
- **State Management:** RxJS BehaviorSubjects for global UI state (Theme, Window State).
- **Interactive Elements:**
  - **Three.js:** For 3D product visualization (GLB models, HDR environments).
  - **Echarts:** For data visualization/analytics.
- **Utilities:**
  - `ngx-translate`: Full i18n support.
  - `Angular Animations`: For smooth transitions and OS-like effects.
  - `Capacitor`: For multi-platform support (Web, Android, Desktop).

## 2. Visual Identity & Aesthetic

The style is a "Cyber-Technical Retro OS" hybrid. It combines vintage terminal/operating system elements with modern smooth animations and high-quality visuals.

### Color Palette

- **Accent:** `#efbc21` (Vivid Yellow/Gold) - Used for buttons, active states, and highlights.
- **Backgrounds:**
  - **Light:** `#eeeeee` (Base), `#ffffff` (Surface).
  - **Dark:** `#121212` (Base), `#1e1e1e` (Surface).
- **Typography Colors:**
  - **Primary Text:** `#777` (Light Mode), `#bbbbbb` (Dark Mode).
  - **Headings:** `#444` (Light Mode), `#eeeeee` (Dark Mode).

### Typography

- **Primary Sans:** "Source Sans Pro" (Clean, readable).
- **Technical/Stats:** "IBM Plex Mono" (Monospaced, technical feel).
- **Elegant Accents:** "Birthstone" (Cursive, used sparingly for personality).

## 3. UI Patterns & Components

### The "OS Window" Wrapper

Every main section is treated as an OS window component.

- **Title Bar:** Contains window controls (Close/Minimize/Maximize), window name (e.g., `MARKETPLACE_OS`), and real-time "system stats" (CPU/MEM simulation).
- **Window Controls Logic:**
  - **Minimize:** Toggles the visibility of the window body.
  - **Maximize:** Triggers Fullscreen API.
  - **Close:** Triggers a "System Crash" animation effect followed by a recovery/reload.

### Layout Structure

- **Global Header:** Fixed/Sticky OS-like bar with Logo, Brand, and Quick Actions (Language, Theme Toggle, External Links).
- **Content Container:** Central area that hosts independent "Window-styled" cards or sections.
- **Footer:** Minimalist, often integrated into the OS frame.

### Interactive Elements

- **Spinners:** Complex CSS-animated spheres (multiple layers of rotating borders).
- **Expanding Cards:** Smooth accordion-like expansion for lists (e.g., product details, experience items).
- **3D Interaction:** Integration of `Three.js` canvas for interactive product 3D previews.

## 4. Replicating for a Marketplace (Example)

### Concept Transformation

- **Product Listing:** Displayed as "Files" or "Applications" inside an OS window.
- **Shopping Cart:** A "System Tray" notification or a "Disk Storage" bar indicating capacity.
- **Checkout:** A "System Update" or "Transaction Terminal" wizard.

### Styling Application

1. **Global Styles:** Import `_variables.scss` and `_animations.scss`.
2. **Product Cards:** Use the `experience-card` pattern (Header with title/price, expandable body with description and technical specs).
3. **Visuals:** Use UnDraw-style SVGs for category illustrations and Three.js for a "3D Product Viewer" on the product detail page.
4. **Tone:** Use technical jargon mixed with the OS theme (e.g., "Scanning for products...", "Compiling your order...").

## 5. Project-Specific Specifications Template

Use this section to define the unique requirements for the new application.

- **App Name/ID:** (e.g., MARKET_OS)
- **Primary Goal:** (e.g., Sell electronic components with a technical interface)
- **Target Platform:** (Web, Android, Desktop via Capacitor)
- **Core Modules & Routes:**
  - `[Name]`: [Description/Route]
  - `[Name]`: [Description/Route]
- **Key Features:**
  - [Feature 1]: [Interaction details]
  - [Feature 2]: [Interaction details]
- **Specific Visuals:**
  - [Asset Type]: [Source or Style preference]
- **Custom System Stats:** (Which mock metrics to show in the OS bar, e.g., "Network Latency", "Stock Sync")

---
