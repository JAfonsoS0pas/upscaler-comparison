# Upscaler Model Comparison

Interactive comparison of AI image-upscaling models for product photography, to help decide
whether a model/service would improve quality over our current production setup (**AuraSR v2**).

## ▶ Live viewer

**https://jafonsos0pas.github.io/upscaler-comparison/**

No install or login needed — opens straight into the gallery.

## How to view

- **Live:** use the link above.
- **Locally:** clone the repo and open `viewer.html` in a browser — no server or build needed.

### Using the viewer
- **Gallery** (default): every model's result for the selected image. Use the top chips to filter models.
- **Compare slider**: click **two tiles** (Original counts as a tile) to open a side-by-side wipe slider
  — covers *original-vs-model* and *model-vs-model*. Drag the divider; zoom with the slider / ⌘-scroll /
  Fit / 1:1; drag to pan. `Esc` returns to the gallery.
- **💲 Pricing**: per-image fal costs and a fal-vs-direct comparison.

## What's included

- **14 upscalers** across the original 8 (ESRGAN ×5, AuraSR v1/v2, Clarity) plus added faithful models:
  Topaz High-Fidelity / Standard / Standard MAX, DRCT, Recraft Crisp, SeedVR2 — all run via fal.ai.
- **33 product test images** across fabric, apparel, fashion, home, appliances, tech, and lifestyle.

## Notes

- **Image quality:** results here are re-encoded to **2048², JPEG q82** (~376 MB total) so the package is
  small enough to host and share for free. The original runs are **4096²** (~6.5 GB) and can be provided
  separately if pixel-exact 4× detail is needed.
- A few cells show **"not yet run"** — three images (`wearing_sweater_1/2`, `wearing_jacket_textured`)
  weren't finished for the newest models when the fal balance ran out.
- The **pricing figures** are mostly estimates (fal bills by GPU-time); only the Topaz tier is a published number.
