# plants-growing

A project about growing plants.

## Parts

The project is built in parts, each in its own numbered folder.

| Part | Folder | Status |
|---|---|---|
| 1. Loading page | [`01-loading-page/`](01-loading-page/index.html) | Done |
| 2+ | — | Not started |

### Part 1 — Loading page

Black particles drift like wind in the center of the screen, gather into a rotating 3D plant, hold for a moment, then scatter back into the flow. Some particles always stay outside the plant.

- Open `01-loading-page/index.html` in a browser.
- Move the mouse to sweep nearby particles along; particles gathering into a plant ignore the mouse. Double-click a plant to blow it apart.
- Call `window.plantLoader.setProgress(0..1)` to drive the progress bar; without it, progress is simulated.
