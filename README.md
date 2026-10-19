# Hawk-Dove Evolutionary Stable Strategy Simulator

Interactive simulation of the Hawk-Dove ESS model from evolutionary biology and game theory.

## Features
- Adjustable Resource Value (V) and Injury Cost (C) sliders (range 1–20)
- Live payoff matrix: Hawk-Hawk, Hawk-Dove, Dove-Hawk, Dove-Dove (calculated from V and C)
- ESS detection: pure Hawk ESS when V ≥ C; mixed ESS of V/C Hawks when V < C
- 50-generation fitness-proportionate selection simulation
- Canvas chart showing Hawk/Dove population trajectories with ESS equilibrium line
- Starting Hawk % slider to explore convergence from any initial condition
- Educational panel with biological examples

## How to Use
1. Open `index.html` in any modern browser
2. Adjust V and C sliders — payoff matrix and ESS update instantly
3. Set starting Hawk % to explore different trajectories
4. Click "Run 50-Generation Simulation" to re-run
5. Observe population converging to the ESS equilibrium

## Tech
- Static HTML/CSS/JS — no server needed
- Tailwind CSS via CDN
- No persistence (no localStorage)
