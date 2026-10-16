# 🌆 PIXEL DRIFT // 2049

An endless cyberpunk runner crafted with **Blade Runner** neon-purple aesthetics, built strictly in a single, self-contained `index.html` file using only standard **HTML5**, **Vanilla CSS**, and **Vanilla JavaScript** (Zero frameworks, zero external image/sound dependencies).

---

## 🎮 Features

- **Blade Runner Aesthetics**:
  - Dark, rain-soaked cyberpunk cityscape with parallax glowing neon skyscrapers and Japanese signage.
  - Perspective neon retro grid floor with horizon glow.
  - CRT scanline emulation, vignette shadow, and neon pulse glows.
  - Cyber-spinner hover-car with dynamic thruster particle trails, headlights, and ground underglow.
- **Responsive Controls**:
  - **Keyboard**: <kbd>Space</kbd>, <kbd>W</kbd>, or <kbd>↑</kbd> to jump (supports air-drift double jump!).
  - **Mouse**: Click anywhere inside the display to jump.
  - **Touch / Mobile**: Tap anywhere on screen or use the on-screen **JUMP** touch button.
- **Procedural Obstacles & Collectibles**:
  - Neon police barricades with flashing beacons.
  - High-voltage EMP spike pylons.
  - Tyrell surveillance drones with downward search cones.
  - Floating golden data chips for bonus multiplier score.
- **Precise AABB Collision Detection**:
  - Pixel-forgiving bounding boxes to ensure tight, satisfying arcade dodging.
- **Dynamic Difficulty**:
  - Speed scales smoothly from 240 KM/H up to maximum velocity as score increases.
  - Obstacle frequency and spacing adjust in real-time.
- **Persistent High Scores**:
  - Automatically records and preserves your best score across sessions using `localStorage`.
- **Integrated 8-Bit Web Audio Synthesizer**:
  - 100% pure vanilla Web Audio API sound synthesis (retro jump pitch slides, pickup chimes, and crash explosion noise).
  - Sound effect toggle button on HUD.

---

## 🚀 How to Run in VS Code

You can run **PIXEL DRIFT** in VS Code in two quick ways:

### Method 1: Using the "Live Server" Extension (Recommended)
1. Open the `PIXEL-DRIFT` folder in VS Code.
2. Install the **Live Server** extension (by *Ritwick Dey*) from the VS Code Extensions tab (`Ctrl+Shift+X`).
3. Right-click on [`index.html`](./index.html) in the file explorer.
4. Select **"Open with Live Server"** (or click **"Go Live"** in the bottom status bar).
5. The game will automatically launch in your default browser at `http://127.0.0.1:5500/index.html`.

### Method 2: Direct Browser Launch (No Extensions Needed)
1. In the VS Code file explorer, right-click [`index.html`](./index.html).
2. Select **"Reveal in File Explorer"** (or press `Alt+Shift+R` on Windows).
3. Double-click [`index.html`](./index.html) to open it directly in Chrome, Edge, Firefox, or Brave.
4. Alternatively, drag and drop [`index.html`](./index.html) into any browser window.

---

## 🕹️ Controls Quick Reference

| Action | Control |
|---|---|
| **Jump / Air-Drift** | <kbd>Space</kbd>, <kbd>W</kbd>, <kbd>↑</kbd>, Mouse Click, or Screen Tap |
| **Double Jump** | Press Jump again while airborne |
| **Restart Game** | Press <kbd>Space</kbd>, <kbd>Enter</kbd>, or click **REBOOT SYSTEM** |
| **Toggle Audio** | Click the **SFX ON / OFF** button in top-right header |

---

*Enjoy drifting through Sector 09!*