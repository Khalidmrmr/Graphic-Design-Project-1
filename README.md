Project for creating Pinhole camera, rasterized display


# Project 1: Retro Raster Run (Infinite)

**Authors:** Rehman Khalid, Jace Schubert

An infinite procedural 3D retro raster runner built entirely with vanilla JavaScript and the HTML5 `<canvas>` API. Manage your oxygen supply, dodge moving hazards, and collect crystals as you race through procedural geometry.

---

## Controls

| Key | Action |
| :--- | :--- |
| <kbd>←</kbd> <kbd>→</kbd> <kbd>↑</kbd> <kbd>↓</kbd> | Move / Steer |
| <kbd>Space</kbd> | Collect nearby crystal (refills oxygen) |
| <kbd>R</kbd> | Reset / Reboot system (after game over) |
| <kbd>1</kbd> | Switch to High-Res Wireframe mode |
| <kbd>2</kbd> | Switch to Low-Res Retro Pixel mode |
| <kbd>3</kbd> | Switch to Filled Triangles (Rasterized) mode |

---

## How to Run

Because this project is a standalone, single-file web application, you do not need to install any complex build tools, Node modules, or dependencies. 

### Method 1: Open Directly in Your Browser (Easiest)
1. Save the code into a file named `game.html`.
2. Double-click the `game.html` file, or drag and drop it into any modern web browser (Google Chrome, Firefox, Safari, Edge).

### Method 2: Run via a Local Development Server (Recommended)
Running through a local server prevents any potential browser restrictions with local file loading.

1. Open your terminal or command prompt in the folder containing your `game.html` file.
2. If you have **Node.js** installed, you can run:
   ```bash
   npx serve
