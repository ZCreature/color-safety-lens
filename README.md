# Color Safety Lens Package

This folder contains two standalone HTML prototypes.

## Files

- `color-safety-lens.html`  
  Brand color tint matrix, WCAG contrast checker, heatmap divergence, color-blindness simulation, and SVG/FIGMA/JSON exports.

- `color-safety-lens-live.html`  
  Live camera prototype for previewing color-blindness simulations through a camera feed. Includes split lens, freeze frame, tap-to-sample, HEX, and contrast ratio readout.

## Opening

The static color checker can be opened directly in a browser.

For the live camera prototype, run a local server from this folder:

```bash
python3 -m http.server 8765
```

Then open:

```text
http://localhost:8765/color-safety-lens-live.html
```

Browsers usually require `localhost` or HTTPS for camera access.
