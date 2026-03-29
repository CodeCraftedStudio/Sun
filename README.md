# ☀️ Ultra-Realistic 3D Sun Visualizer

A high-fidelity, interactive 3D simulation of the Sun built with **Three.js**. This project features advanced GLSL shaders, procedural granulation, dynamic solar flares, and a multi-layered corona to create a stunningly realistic solar experience.

![Sun Visualizer Preview](https://img.shields.io/badge/Status-Production--Ready-brightgreen)
![Three.js](https://img.shields.io/badge/Powered%20by-Three.js-orange)
![GLSL](https://img.shields.io/badge/Shaders-GLSL-yellow)

## 🚀 Live Features

### 🔹 Advanced Solar Surface
- **Granulation Engine**: Simulates the convection cells on the solar surface using multi-octave Simplex noise.
- **Active Regions/Sunspots**: Procedurally generated high-activity zones with specialized color shifting.
- **Differential Rotation**: Realistic rotation physics where the equator rotates at a different speed than the poles.
- **Limb Darkening**: Accurate atmospheric absorption modeling for a realistic spherical appearance.

### 🔹 Atmospheric Dynamics
- **Pulsating Corona**: Multi-layered volumetric corona (Inner, Outer, and Wisps) that reacts to "solar activity" cycles.
- **Heat Distortion**: Vertex-shader based displacement that simulates the intense heat and plasma fluctuations.
- **Solar Flares**: Thousands of dynamic particles simulating continuous plasma ejection and high-energy bursts.

### 🔹 Immersive Environment
- **Deep Space Backdrop**: A dense starfield with varying magnitudes and color tints.
- **Nebulae & Dust**: Procedural gas clouds and cosmic dust to provide depth and parallax.
- **Solar Wind Audio**: An interactive synthesizer (AudioContext) that generates a low-frequency hum representing solar wind.

### 🔹 Interactive Controls
- **Bloom Intensity**: Adjust the blinding intensity of the sun's glow.
- **Rotation Speed**: Control the temporal scale of solar dynamics.
- **Orbit Controls**: Full 360-degree navigation with smooth navigation damping and zoom.

## 🛠️ Technology Stack
- **Core**: HTML5, CSS3, JavaScript (ES6+)
- **Graphics**: [Three.js r128](https://threejs.org/)
- **Post-Processing**: UnrealBloomPass for high-quality glow effects.
- **Math**: GLSL (Simplex Noise) for procedural generation.

## 📖 How to Run
1. Simply open `sun.html` in any modern web browser (Chrome, Firefox, Edge, Safari).
2. No installation or local server is required.
3. Use your mouse/touch to rotate, zoom, and explore the solar surface.

## 🎮 UI Breakdown
- **Top Left**: Current status and feature highlights.
- **Bottom Right**: Custom control panel for real-time visualization tweaks.
- **Solar Wind Button**: Toggle the immersive ambient sound.

---

*“The Sun, with all those planets revolving around it and dependent on it, can still ripen a bunch of grapes as if it had nothing else in the universe to do.”* — **Galileo Galilei**
