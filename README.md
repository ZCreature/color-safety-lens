# Color Safety Lens Package

This folder contains two standalone HTML prototypes.

## Files

- `color-safety-lens.html`  
  Brand color tint matrix, WCAG contrast checker, heatmap divergence, color-blindness simulation, and SVG/FIGMA/JSON exports.

- `color-safety-lens-live.html`  
  Live prototype that screen-captures a window or display (`getDisplayMedia`) and previews color-blindness simulations over it in real time. Includes split lens, freeze frame, tap-to-sample, HEX and contrast ratio readout, and a WCAG alarm overlay.

## Opening

The static color checker can be opened directly in a browser.

For the live prototype, run a local server from this folder:

```bash
python3 -m http.server 8765
```

Then open:

```text
http://localhost:8765/color-safety-lens-live.html
```

Browsers usually require `localhost` or HTTPS for screen capture.
