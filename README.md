# HaloBook 3D

A 3D laptop that lives in your browser. Open the lid, orbit around it, and use it like a real computer, with its own desktop OS, apps and games.

**[Open the live demo](https://aakkshhayy.github.io/HaloBook-3D/)**

## What you can do

- **Hardware you can handle.** Drag to orbit, flick it to spin, and grab the lid to open or close it. The keys press down as you type on your real keyboard and glow with the backlight.
- **A working trackpad.** Move over it to steer the pointer on screen and tap to click.
- **Use it full size.** Press *Use it* for a sharp, full-screen view of the desktop.
- **Nimbus OS.** Draggable, resizable and snappable windows, three desktops, an overview of all windows, a window switcher, search, a control center, notifications and a working menu bar.
- **Apps.** Terminal, Files, Explorer, Notes, Markdown, Code (runs JavaScript), Calculator, Paint, Photos, Camera, Calendar, Clock, Sound Waves, Snake and 2048.
- **It remembers.** Files, notes, photos, settings and open windows are saved in your browser.

## Keyboard shortcuts

| Shortcut | Action |
| --- | --- |
| ⌘K / Ctrl+K | Search apps, files and settings |
| ⌥Tab | Switch windows (macOS) |
| ⌥↑ | Show all windows |
| ⌥← / ⌥→ | Switch desktops |
| ⌘W / Ctrl+W | Close window |
| F1 / F2 | Brightness |
| F10 / F11 / F12 | Mute, volume down, volume up |

## Run it locally

It is a single HTML file with no build step.

```bash
git clone https://github.com/aakkshhayy/HaloBook-3D.git
cd HaloBook-3D
npx serve .
```

Then open the address it prints. Opening `index.html` directly also works, but the camera needs a local server or HTTPS.

## Built with

- [three.js](https://threejs.org/) for the 3D laptop, lighting and shadows
- [html2canvas](https://html2canvas.hertzen.com/) for screenshots
- Fonts from Google Fonts: Bricolage Grotesque, Figtree and JetBrains Mono

If a browser can't run WebGL, HaloBook falls back to a CSS 3D version with every feature still working.

## License

MIT, see [LICENSE](LICENSE).
