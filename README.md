# ASCII Art Creator

Standalone, client-side web application for converting images, animated GIFs, and videos into ASCII art in real time.

Live Demo: https://skbwastaken.github.io/ASCIICreator/

---

## Features

- **Client-Side & Offline First**: Runs entirely in the browser using HTML5 Canvas. Zero server uploads, zero external dependencies or CDNs.
- **Pure Black & White (1-Bit Binary)**: Strict binary ON/OFF cutoff with zero grayscale, guaranteed single-color symbol rendering, custom threshold controls, and symbol density options.
- **Dual-Axis Spacing & Aspect Control**: Independent horizontal (X) and vertical (Y) character spacing sliders with an aspect ratio link toggle and precision numeric inputs.
- **ASCII Conversion Toggle & Example Image**: Instantly switch between ASCII art and original raw media with a single click in the top toolbar, plus a 1-click sample image loader in the central drop zone.
- **Video & GIF Support**:
  - Drag-and-drop support for animated GIFs, MP4, WebM, and MOV.
  - Real-time ASCII playback with interactive seekbar, timestamp display, and mouse wheel frame scrubbing.
  - Offline frame-by-frame video export: High-bitrate MP4 (H.264/AVC) and WebM export up to 75 Mbps without playback recording.
  - Direct frame export: Export any paused video or GIF frame as high-resolution PNG.
- **Resolution Presets**: Full HD (1080p) and 4K UHD (2160p, default).
- **Visual Controls & Palettes**:
  - Cyber Blue accent (`#4788ff`) with frosted glass UI.
  - Color palettes: Pure Black & White, Original (Solid & Average), Monochrome, Matrix Green, Cyberpunk, CGA, ZX Spectrum, and Custom Colors.
  - Custom font support (.ttf, .otf, .woff, Goliath Encrypted, and system monospace fonts).
  - Background transparency cutoff and shadow fill controls.
- **Flexible Workspace**:
  - Sidebar position toggle (Left / Right) with persistent preference storage.
  - Canvas pan and cursor-centered zoom.
  - Custom user preset saving via `localStorage`.
- **Changelog Modal**: Displays recent updates and version info on first visit after an update.

---

## Usage

### Online
https://skbwastaken.github.io/ASCIICreator/

### Local
```bash
git clone https://github.com/SKBwastaken/ASCIICreator.git
cd ASCIICreator
# Open index.html in any modern browser
```

---

## Credits
- Author: SKB (https://discord.com/users/289503943409664000)
- Flexible sidebar contribution: @stillabstract
