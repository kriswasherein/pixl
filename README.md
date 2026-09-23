# Fluid Mechanics Image Analyzer

Browser-only, ImageJ-inspired image analysis for experimental fluid mechanics.

## Features in v0.2
- Upload BMP, PNG, JPG/JPEG, TIFF and WebP sequences.
- First image can be used for calibration and measurement definitions.
- Draw:
  - line
  - rectangle
  - square
  - circle
  - ellipse
  - angle (3 points)
  - polygon / area
  - point
  - pixel profile definition
- Mouse-wheel zoom with cursor-centered zoom.
- Fit, 1:1 and reset view.
- Exact source-image pixel coordinates: the canvas backing resolution stays equal to the original image resolution while zoom changes only display size.
- Live RGB/alpha pixel readout.
- Length, radius, diameter, angle and area calculations.
- Batch tracking assist for later frames.
- CSV and JSON project export.

## GitHub Pages
This is a static browser application. Put `index.html`, `app.js` and `style.css` in the repository root and publish `main` / root with GitHub Pages.
