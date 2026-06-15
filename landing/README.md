# SKYMINT landing — image assets

Drop your landing images **in this folder** (`public/landing/`). They'll be served at
`/neva-telegram/landing/<name>` and I'll wire them into `src/landing/SkymintLanding.tsx`.

## Specs (so they look crisp + load fast on phones)
- **Floating pieces** (clouds, the engine, the coin, islands, characters) →
  **PNG with a TRANSPARENT background**, so they layer over the sky.
- **Backgrounds** (the sky / dawn scene) → PNG or JPG, **wide (≥ 1600px)** so it covers
  desktop too. JPG is fine for a smooth gradient sky.
- **Export at 2× the display size** (retina/phone crispness). e.g. a cloud shown ~300px
  → export ~600px wide.
- **Compress** every file (squoosh.app or tinypng.com) → aim **< 300 KB each**. Mobile
  load speed matters.
- **Name them clearly**, e.g.:
  - `sky-bg.jpg` (the dawn sky background)
  - `engine.png` (the hero sky engine, transparent)
  - `coin.png` (the SMINT coin, transparent)
  - `cloud-1.png`, `cloud-2.png`, `cloud-3.png` (transparent puffs)
  - `island.png`, `character.png`, etc.

## When they're ready
Drop them here and tell me the filenames + (optionally) where each should sit (e.g.
"engine front and center in the hero", "clouds drifting behind"). I'll rebuild the
landing around them.
