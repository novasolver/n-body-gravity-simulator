# N-Body Gravity Simulator

[![Live demo](https://img.shields.io/badge/live-demo-blue)](https://novasolver.jp/tools/n-body-gravity.html)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Newtonian gravity for N point masses. Solar system presets, three-body chaos, custom configurations.

🌐 **[Try it live](https://novasolver.jp/tools/n-body-gravity.html)** · 🌍 [EN](https://novasolver.jp/en/tools/n-body-gravity.html) · 🌏 [ZH](https://novasolver.jp/zh/tools/n-body-gravity.html)

---

## Why

Newtonian gravity for N point masses. Solar system presets, three-body chaos, custom configurations. Built as part of **[NovaSolver](https://novasolver.jp)** — 1600+ interactive physics & engineering simulators.

## Tech

- **Vanilla JavaScript** — no build step, no framework lock-in
- **Canvas / Chart.js** rendering
- **MathJax** for equations
- **Self-contained** — drop `index.html` anywhere and it runs

## Run locally

```bash
git clone https://github.com/novasolver/n-body-gravity-simulator
cd n-body-gravity-simulator
python -m http.server 8000
# open http://localhost:8000
```

## Use it in your project

The `index.html` is self-contained and MIT-licensed. Take it, fork it, embed it.

## Part of NovaSolver

This repo is a "flagship" version of one simulator from the [physics-simulators monorepo](https://github.com/novasolver/physics-simulators). The monorepo has 1600+ more tools across:

- Structural mechanics (beam, buckling, fatigue, FEM)
- Fluid dynamics (Reynolds, Bernoulli, potential flow, CFD basics)
- Heat transfer (1D/2D conduction, fins, radiation)
- Electromagnetics (RC/RL, Bode, antennas, FDTD)
- Multi-physics & math fun (Lorenz, boids, Lissajous, n-body)

→ **[novasolver.jp/tools/](https://novasolver.jp/tools/)** for the full catalog.

## License

[MIT](LICENSE)
