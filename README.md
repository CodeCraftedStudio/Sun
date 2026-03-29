# ☀️ Solar Phoenix: SDO Spectral Simulation

A high-fidelity, interactive 3D simulation of the Sun built with **Three.js** and advanced **GLSL shaders**. This project brings NASA's Solar Dynamics Observatory (SDO) experience directly to your browser, featuring real-time procedural granulation, interactive coronal mass ejections (CMEs), and multiple scientific spectral wavelength filters.

![Sun Visualizer Preview](https://img.shields.io/badge/Status-Production--Ready-brightgreen)
![Three.js](https://img.shields.io/badge/Powered%20by-Three.js-orange)
![GLSL](https://img.shields.io/badge/Shaders-GLSL-yellow)

## 🚀 Ultimate Features

### 🔹 SDO Spectral Simulation Filters
Experience the Sun across multiple wavelengths of light, calculating completely different planetary textures in real-time via fragment shaders:
- **VISUAL (Photosphere)**: True-color optical simulation with deep sunspots and boiling plasma.
- **AIA 171Å (Quiet Corona)**: Golden emissions from Iron (Fe IX) ions, highlighting magnetic loops.
- **AIA 304Å (Chromosphere)**: Deep crimson emissions from Helium (He II) ions, visualizing the solar transition region.
- **MAGNETOGRAM**: A polarized map visualizing complex magnetic fields with intense black/white poles. UI and rendering dynamically adapt to this grayscale mode.

### 🔹 Advanced Solar Surface & Plasma
- **Interactive Solar Flares**: **Click anywhere on the sun's surface** to instantly generate an interactive shockwave and arcing magnetic plasma loops precisely at the intersection point.
- **Magnetic Corona**: A real-time vertex displacement shell simulating writhing, turbulent coronal arcs.
- **Prominence Loops**: Volumetric, curved plasma structures extending deep into space along magnetic field lines.
- **Deep Sunspots & Granulation**: Multi-octave 3D Simplex noise governing the procedural convection cells and cooler active sunspot regions.

### 🔹 Immersive Environment
- **Twinkling Starfield**: A dense background of 12,000+ stars with a custom shader calculating magnitude, depth mapping, and twinkle frequency.
- **Dynamic Solar Wind Audio**: An interactive procedural audio synthesizer (Web Audio API). The low-frequency rumble dynamically scales based on your camera's distance to the Sun.
- **Cinematic Camera Drift**: An automated smooth orbital drift mode mimicking real spacecraft observational patterns.

### 🔹 High-End Rendering
- **ACES Filmic ToneMapping**: Cinema-grade HDR color mapping and tone exposure control.
- **Post-Processing HDR Bloom**: UnrealBloomPass dynamically scaling the photon emission of the photosphere.

## 🛠️ Technology Stack
- **Core**: HTML5, CSS3, JavaScript (ES6 Modules)
- **Graphics Graphics Engine**: [Three.js r128](https://threejs.org/)
- **Shaders/Math**: GLSL for real-time procedural noise textures and vertex displacements.
- **Audio Engine**: Native Web Audio API (`AudioContext`, `BiquadFilter`, `OscillatorNode`)

## 📖 How to Run
1. Simply open `sun.html` in any modern web browser (Chrome, Firefox, Edge, Safari).
2. No installation, compilation, or local server is required.
3. Use your mouse/touch to rotate, scroll to zoom, and **click on the sun** to trigger flares.

## 🎮 UI Dashboard
- **Top Left**: Simulation status and active Spectral Mode.
- **Bottom Left**: High-precision simulated telemetry (Surface Temp over time, Emission Bloom strength).
- **Bottom Right**: Interactive command dashboard to toggle wavelengths, photon bloom, rotation speed, coronal visibility, and solar wind audio.

---

*"The Sun, with all those planets revolving around it and dependent on it, can still ripen a bunch of grapes as if it had nothing else in the universe to do."* — **Galileo Galilei**
