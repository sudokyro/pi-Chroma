<div align="center">

# π C H R O M A
### *A Study of the Infinite*

[![Architecture: Single File](https://img.shields.io/badge/Architecture-Single_File_HTML5-cfb27a?style=for-the-badge)](./index.html)
[![Engine: WebGL / Canvas2D](https://img.shields.io/badge/Rendering-60_FPS_Canvas-111116?style=for-the-badge)](./index.html)
[![Compute: Web Workers](https://img.shields.io/badge/Compute-Web_Workers-cfb27a?style=for-the-badge)](./index.html)
[![Precision: Chudnovsky](https://img.shields.io/badge/Math-Chudnovsky_Algorithm-111116?style=for-the-badge)](./index.html)
[![License: MIT](https://img.shields.io/badge/License-MIT-cfb27a?style=for-the-badge)](./LICENSE)

<br />

<p align="center">
  <strong>An art-gallery visualizer and mathematical pattern hunter for the decimal expansion of π.</strong><br />
  Translating the infinite, non-repeating stream of π into living fields of color, and hunting for where your own artwork already exists inside the sequence.
</p>

<p align="center">
  <a href="#-key-features">Features</a> •
  <a href="#-the-exhibition-rooms">Exhibition Rooms</a> •
  <a href="#-search-engine-modes">Search Engine</a> •
  <a href="#-controls--shortcuts">Controls</a> •
  <a href="#-color-systems">Color Systems</a> •
  <a href="#-quick-start">Quick Start</a>
</p>

---

</div>

## ✦ The Philosophy

Every rational or irrational sequence tells a story, but **π (pi)** holds a special place in the human imagination: an infinite, non-repeating decimal expansion conjectured to be normal—containing every birthdate, every thought, and every image ever drawn.

**π Chroma** gives physical, aesthetic form to that infinity. It replaces raw terminal digits with curated, museum-grade color geometries, turning mathematical contemplation into a sensory experience and letting you discover your visual creations hidden in the numbers.

---

## ✦ Key Features

- **🏛️ Museum-Grade Aesthetic:** Minimalist Swiss typography, generous negative space, butter-smooth 60 FPS transitions, and dual gallery lighting modes (**Dark Exhibition Room** and **Pristine White Gallery**).
- **🗺️ Triple-Geometry Explorer:** Traverse millions of digits across three distinct mathematical perspectives: **Continuous Tapestry**, **Archimedean Galaxy Spiral**, and **Uncapped Deep Zoom**.
- **🎨 The Studio (Hunter Canvas):** Paint on a pixel grid, sketch with a freehand brush that quantizes to palette tones in real time, or import external images that downscale into mathematical search grids.
- **🔍 3 Search Engines:**
  - **Strict Match:** Uncompromising mathematical verification (100% exact match or *"does not exist in loaded range"*).
  - **Best Match (Proximity Scan):** Identifies the closest mathematical twin and maps pixel-by-pixel similarity percentage.
  - **Scanline:** Deconstructs art into horizontal rows, discovering each independent coordinate across the digits.
- **⚡ Non-Blocking Architecture:** All heavy search loops and on-the-fly digit generations run in background **Web Workers** so the UI never freezes or stutters.
- **🔬 Dynamic Memory & Chudnovsky Engine:** Launches instantly with **2,000,000 pre-cached digits**, with an in-browser Chudnovsky BigInt engine to calculate millions more on demand, complete with an instant memory purge.
- **🖼️ High-Res Wall Plaque Exports:** One-click generation of $2000 \times 2500$ (4:5 ratio) exhibition prints featuring the artwork alongside an archival provenance plaque detailing the discovery's exact coordinate, date, and palette.

---

## ✦ The Exhibition Rooms

### `01` The Explorer
A viewport into the endless sequence of $\pi$, starting from $3.14159...$ at index `0`:

- **Continuous 2D Tapestry:** The decimal stream woven row-by-row like an endless fabric.
- **Archimedean Galaxy Spiral:** Numbers coiling outward from the center into deep space.
- **Uncapped Deep Zoom:** A 1,024-digit wide plane with unrestricted zoom depth—glide seamlessly between macro color nebulae down to single numeric tiles.
- **Tactile Inspector Plaque:** Click any tile to inspect its exact index (e.g. `#1,840,291`), digit value, and local numerical sequence.
- **Fluid Transport:** Variable-speed auto-scroll with adjustable slider and direct numeric speed input.

### `02` The Studio
The creative workspace where you design the signal to search for in $\pi$:

- **Pixel Pen:** Discrete grid painting with active palette swatches.
- **Freehand Brush:** Natural digital sketching that dynamically snaps to the nearest color index.
- **Image Import:** Upload any photo or icon; the engine automatically crops, downscales, and color-quantizes it into search cells.
- **Unlocked Grid Slider:** Defaults to small dimensions for instant matching, but includes unlocked sliders to push grid boundaries as high as you want.

---

## ✦ Search Engine Modes

| Mode | Algorithmic Behavior | Outcome |
| :--- | :--- | :--- |
| **Strict Match** | Scans for the exact sequential digit string of your drawing. | **100% or Nothing.** Pinpoints the exact coordinate in $\pi$ where your drawing lives, or explicitly reports it does not exist in the loaded range. |
| **Best Match** | Evaluates color distance and identifies the nearest passage. | Returns the highest percentage match (e.g. `84.2%`), highlighting which pixels matched and which differed. |
| **Scanline** | Breaks 2D art into individual horizontal lines. | Finds each row independently in $\pi$, generating an interactive line-by-line ledger. |

---

## ✦ Curated Color Systems

Toggle between **Discrete 10-Color Palettes** (where each digit $0-9$ is permanently bound to a specific hue) and **Stepped Gradient Ramps**:

- **Neon Cyber:** High-voltage phosphors, neon pinks, cybernetic blues, and electric yellows.
- **Muted Pastel:** Warm chalk, soft sage, slate blue, and architectural gray.
- **Thermal Study:** Infrared spectrum moving from deep violet-blacks to searing yellow-whites.
- **Monochrome Obsidian:** Fine graphite, raw bone, and deep shadow.
- **Celadon & Clay:** Glazed porcelain greens, terracotta, and fired earth.

---

## ✦ Controls & Shortcuts

| Action | Input | Description |
| :--- | :--- | :--- |
| **Pan Map** | `Hold Right-Click + Drag` | Fluidly travel across the canvas without dragging collisions |
| **Inspect Tile** | `Left-Click` | Reveals and pins the museum-grade Inspector Plaque |
| **Zoom Map** | `Mousewheel` | Zoom in to individual digits or out to macro fields |
| **Auto-Scroll** | `Spacebar` or Play Button | Toggle autonomous camera flight along $\pi$ |
| **Room Select** | `1` / `2` or Topbar Tabs | Instantly switch between **Explorer** and **Studio** |
| **Gallery Light** | `T` or Sun / Moon Icon | Switch between Dark Exhibition and White Gallery |
| **Sound Toggle** | `M` or Volume Icon | Mute or unmute synthesized tactile micro-clicks |
| **Export Plaque** | `E` or Export Button | Download a high-res $2000 \times 2500$ gallery print (PNG) |
| **Extend Archive**| `X` or Horizon Modal | Compute deeper digits using the local Chudnovsky worker |
| **Undo / Redo** | `Ctrl/Cmd + Z` / `Shift + Z` | Undo and redo brush and pixel strokes in the Studio |

---

## ✦ Quick Start

`pi-Chroma` is completely self-contained in a single file with **zero build steps, zero dependencies, and zero setup**.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sudokyro/pi-Chroma.git
   cd pi-Chroma
