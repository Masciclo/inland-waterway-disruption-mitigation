## Hybrid RWS Terminal Cartography & FIS Structural Routing Benchmark
[![DOI](https://zenodo.org/badge/1465250770.svg)](https://doi.org/10.5281/zenodo.24397032)

This milestone advances the simulation framework from idealized distance-based shortest paths to operational real-world logistics by integrating official RWS terminal infrastructure polygons with a dual-graph structural heuristic routing engine.

### Connected Interactive Map Suite
The repository includes a unified, connected MapLibre suite with a glassmorphic top-left navigation switcher (`#global-map-switcher`) allowing 1-click seamless switching between all analytical stages:

1. **[Limitations (`map_5_obstructions.html`)](./map_5_obstructions.html)**
   * Empirical RWS Notice to Skippers (NtS) active waterway obstruction and operational limitation register.
   * Dual-severity hierarchy: green closures (`OBSTRU`) and blue cautions (`CAUTIO`).
   * Four duration size tiers with interactive hover HUD cards detailing infrastructure objects, fairway names, and bulletin notices.

2. **[Traffic (`map_4_0_fleet.html`)](./map_4_0_fleet.html)**
   * National baseline freight assignment across **90,373 active voyages** (Summer 2026).
   * Fleet-adaptive 6-tier classification scales tailored specifically for All Fleet, Dry Cargo, Tankers, Push Tows, and Other craft.
   * Floating HUD card with corridor-level traffic volumes, average cargo payload, standard deviation, and NSTR commodity shares.

3. **[Mitigation (`index.html`)](./index.html)**
   * Strategic disruption mitigation sequencing comparing $\pi^*_{\text{distance}}$ vs. $\pi^*_{\text{hours}}$ optimal recovery curves.
   * Corridor-level traffic restoration, vessel class equity impact, and terminal resilience.
   * Morphed donut micro-charts and dynamic mitigation chains.

### Key Highlights
* **Empirical Evaluation:** Assessed across **707 empirical voyages** under compound disruption along the **Waal**, **Gelderse IJssel**, and **Twentekanaal**.
* **Physical Infrastructure Constraints:** Enforces physical lock chamber widths and vessel-beam clearance limits to eliminate infeasible push-tow convoy detours.
* **Routing Benchmark:** Quantifies structural route divergence against the baseline crawler.
* **Mitigation Scheduling:** Demonstrates authoritative mitigation scheduling optimized directly for cumulative fleet delay hours saved (recovering over **811 hours** of systemic delay).
* **Visualization Export:** Exports the complete analytical pipeline directly to GPU-accelerated standalone visualizers with sub-2ms client hydration.
