# 3D Solar System Simulation

[![Live Demo](https://img.shields.io/badge/Live-Demo-7ab4ff?style=for-the-badge)](https://prog-yousef.github.io/solar-system-3d/)
[![Simulation](https://img.shields.io/badge/Launch-Simulation-6ee7b7?style=for-the-badge)](https://prog-yousef.github.io/solar-system-3d/simulation.html)
[![Three.js](https://img.shields.io/badge/Three.js-r160-000000?style=for-the-badge&logo=threedotjs)](https://threejs.org/)
[![GitHub](https://img.shields.io/badge/GitHub-Repo-181717?style=for-the-badge&logo=github)](https://github.com/prog-Yousef/solar-system-3d)

An interactive 3D solar system simulation built with **Three.js** — explore all 8 planets with orbital mechanics, procedural textures, and bloom post-processing.

---

## 🚀 Quick Links

| | |
|---|---|
| 🌐 **Landing Page** | [https://prog-yousef.github.io/solar-system-3d/](https://prog-yousef.github.io/solar-system-3d/) |
| 🪐 **Full Simulation** | [https://prog-yousef.github.io/solar-system-3d/simulation.html](https://prog-yousef.github.io/solar-system-3d/simulation.html) |
| 📦 **GitHub Repo** | [https://github.com/prog-Yousef/solar-system-3d](https://github.com/prog-Yousef/solar-system-3d) |

---

## ✨ Features

| Feature | Description |
|---|---|
| **8 Planets** | Mercury, Venus, Earth, Mars, Jupiter, Saturn, Uranus, Neptune with realistic relative sizes and colors |
| **Kepler Orbits** | Eccentric and inclined orbital paths for each planet |
| **Procedural Textures** | All planet surfaces generated with Canvas 2D — zero external images |
| **Saturn's Rings** | Textured ring system with Cassini division gap |
| **Earth's Moon** | Small moon orbiting Earth |
| **12,000-Star Field** | Randomized star distribution with warm/cool color temperature |
| **Bloom Effect** | UnrealBloomPass post-processing for glowing highlights |
| **Interactive** | Click any planet to view detailed stats (mass, gravity, temperature, moons, etc.) |
| **Info Panel** | In-depth planetary data on click — 10+ facts per planet |
| **Speed Controls** | ×0.25 to ×100 simulation speed via UI buttons or keyboard (1-5) |
| **Pause/Resume** | Press Space to freeze the simulation |
| **Orbit & Zoom** | Drag to orbit, scroll to zoom — full camera control |

---

## 🎮 Controls

| Input | Action |
|---|---|
| 🖱 **Click planet** | Show detailed info panel |
| 🖱 **Drag** | Orbit camera around the scene |
| 🔍 **Scroll** | Zoom in / out |
| **1** | Speed ×0.25 |
| **2** | Speed ×1 |
| **3** | Speed ×5 |
| **4** | Speed ×20 |
| **5** | Speed ×100 |
| **Space** | Pause / Resume |
| **Escape** | Close info panel |

---

## 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| [Three.js r160](https://threejs.org/) | 3D rendering engine |
| [OrbitControls](https://threejs.org/docs/#examples/en/controls/OrbitControls) | Camera interaction |
| [EffectComposer](https://threejs.org/docs/#examples/en/postprocessing/EffectComposer) | Post-processing pipeline |
| [UnrealBloomPass](https://threejs.org/docs/#examples/en/postprocessing/UnrealBloomPass) | Bloom / glow effect |
| Canvas 2D API | Procedural texture generation |
| ES Modules | JavaScript module system |
| GitHub Pages | Hosting & deployment |

---

## 📁 Project Structure

```
/
├── index.html          # Landing page (3D hero scene + info)
├── simulation.html     # Full solar system simulation
└── README.md           # This file
```

---

## 🚦 Run Locally

No build step needed — just serve the files:

```bash
# Clone the repo
git clone https://github.com/prog-Yousef/solar-system-3d.git
cd solar-system-3d

# Serve with any HTTP server (e.g. Python)
python -m http.server 8000
# or with Node
npx serve .

# Open http://localhost:8000 in your browser
```

> **Note:** The HTML files use ES modules via `<script type="importmap">` and require an HTTP server (not `file://` protocol).

---

## 📊 Planet Data

Each planet includes detailed information accessible by clicking it in the simulation:

| Planet | Diameter | Distance from Sun | Orbital Period | Moons |
|---|---|---|---|---|
| Mercury | 4,879 km | 0.39 AU | 88 days | 0 |
| Venus | 12,104 km | 0.72 AU | 225 days | 0 |
| Earth | 12,742 km | 1.00 AU | 365.25 days | 1 |
| Mars | 6,779 km | 1.52 AU | 687 days | 2 |
| Jupiter | 139,820 km | 5.20 AU | 11.86 years | 95 |
| Saturn | 116,460 km | 9.54 AU | 29.46 years | 146 |
| Uranus | 50,724 km | 19.19 AU | 84 years | 27 |
| Neptune | 49,244 km | 30.07 AU | 164.8 years | 16 |

---

Built with ❤️ using [Three.js](https://threejs.org/)
