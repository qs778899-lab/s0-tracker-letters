# S0 Tracker browser demo

Public static release: 26 single letters, seven preset motions, full BrainCo G1 visuals, MuJoCo WASM and test052 20k. Simulation, policy inference and actual right-wrist ink run on each visitor’s computer. No inference backend.

Use `?letter=A` to open single-letter mode. There is no lateral transfer or word composition. Native validation, raw NPZ files, recordings and internal reports are excluded. See release.json and the included licenses.

Rebuild in the canonical project: `npm ci`, `npm run build`, `node tools/prepare-pages.mjs /absolute/path/to/this-checkout`. Commit and push this generated repository to update GitHub Pages.
