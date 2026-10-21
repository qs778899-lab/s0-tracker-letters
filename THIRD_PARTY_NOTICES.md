# Third-party notices

This demo uses the following packages; pinned versions are recorded in package-lock.json.

Runtime license texts are included in `public/licenses/` and copied to `dist/licenses/`, including ONNX Runtime's third-party notices.

| Package | Version | License | Source |
| --- | --- | --- | --- |
| MuJoCo JavaScript / WASM | 3.9.0 | Apache-2.0 | https://github.com/google-deepmind/mujoco/tree/3.9.0/wasm |
| ONNX Runtime Web | 1.26.0 | MIT | https://github.com/microsoft/onnxruntime |
| Three.js | 0.181.0 | MIT | https://github.com/mrdoob/three.js |
| Vite (build only) | 7.3.7 | MIT | https://github.com/vitejs/vite |
| TypeScript (build only) | 5.9.3 | Apache-2.0 | https://github.com/microsoft/TypeScript |
| Playwright (test only) | 1.62.1 | Apache-2.0 | https://github.com/microsoft/playwright |

Perceptive BFM (https://acodedog.github.io/perceptive-bfm/) inspired the client-side simulation and inference architecture. The PHP demo (https://github.com/php-parkour/php-parkour.github.io/tree/3898564255525f2a72dbbfb1d190b48a230435ab/mujoco_wasm) was studied as an engineering reference. No PBFM/PHP policy weights, motion data, or renderer source have been copied into this project.

The S0 model, robot assets and motion references retain their existing ownership and licensing. This notice does not relicense them or grant additional redistribution rights.
