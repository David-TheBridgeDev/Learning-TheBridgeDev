# CineShader - Web DNA & Aesthetic BluePrint

## 1. Technical Stack

* **Core Engine:** `Three.js` (used for 3D stage and environment rendering).
* **Shader Engine:** WebGL 2 (with WebGL 1 fallback).
* **Shader Integration:** `Shadertoy.com API` for fetching community content.
* **Code Editor:** `CodeMirror` with GLSL syntax highlighting and helpers.
* **Animation Engine:** `GSAP` (GreenSock) for UI transitions and camera movement.
* **Extended Reality:** `WebXR API` for VR/AR immersion.

## 2. Visual Identity

* **Aesthetic Style:** **Cinematic Minimalist / Media Cathedral**. Inspired by Refik Anadol's digital installations.
* **Color Palette:**
  * **Primary:** `#000000` (Deep Black for the "Infinite Stage").
  * **Surface:** Translucent overlays with glassmorphism (backdrops for UI).
  * **Accent:** Dynamic (usually driven by the shader colors themselves).
* **Typography:**
  * **UI:** High-legibility Sans-serif (Inter or system-stack) for controls.
  * **Editor:** Monospaced (Source Code Pro or similar) for GLSL coding.
* **Atmosphere:** Immersive, high-contrast, professional, and experimental.

## 3. UI Patterns & Layout

* **The "3D Stage":** The main canvas is a full-screen 3D scene where shaders are projected onto geometry (Person, Car, or Plane).
* **Floating Control Panels:** Minimalist, translucent panels for settings (Quality, Navigation, Model selection).
* **Slot-Based Workflow:** A "1-2-3" tab system at the bottom for managing different shader drafts locally.
* **Quality Selector:** Granular toggles (Minimal, Low, Mid, Full) to manage WebGL performance.
* **Contextual Overlays:** Minimalist FPS and resolution indicators that stay out of the way of the artwork.

## 4. Implementation Strategy

1. **Scene Setup:** Initialize a `Three.js` scene with a black background and a camera system that supports both static and "free-nav" (orbital) modes.
2. **Shader Projection:** Instead of a standard 2D quad, project GLSL output onto a 3D mesh. Use the `fragColor.a` channel to drive depth or transparency in the 3D space.
3. **Real-time Compiler:** Integrate `CodeMirror` and create a bridge to update `THREE.ShaderMaterial` uniforms (`iTime`, `iResolution`, `iMouse`) and the `fragmentShader` code on the fly.
4. **Cinematic Feel:** Use `GSAP` to animate camera transitions between "Static" and "Free" modes, creating a professional presentation feel.
5. **VR Integration:** Utilize `THREE.WebXRManager` to allow users to enter the "Shader Cathedral" in a VR environment.

## 5. [Your Product Name] - Implementation Template
>
> [!NOTE]
> Use this section to define how to apply the CineShader DNA to a new project.

* **Product Goal:** [Describe what you are building]
* **Core DNA Adoption:** [Which elements from CineShader will be used?]
* **Custom Twist:** [What will make this product unique?]
