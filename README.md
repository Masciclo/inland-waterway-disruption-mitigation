## Hybrid RWS Terminal Cartography & FIS Structural Routing Benchmark
[![DOI](https://zenodo.org/badge/1465250770.svg)](https://doi.org/10.5281/zenodo.24397032)

This milestone advances the simulation framework from idealized distance-based shortest paths to operational real-world logistics by integrating official RWS terminal infrastructure polygons with a dual-graph structural heuristic routing engine.

### Key Highlights
* **Empirical Evaluation:** Assessed across **707 empirical voyages** under compound disruption along the **Waal**, **Gelderse IJssel**, and **Twentekanaal**.
* **Physical Infrastructure Constraints:** Enforces physical lock chamber widths and vessel-beam clearance limits to eliminate infeasible push-tow convoy detours.
* **Routing Benchmark:** Quantifies structural route divergence against the baseline crawler.
* **Mitigation Scheduling:** Demonstrates authoritative mitigation scheduling optimized directly for cumulative fleet delay hours saved ($\pi_{\text{hours}}^*$, recovering over **811 hours** of systemic delay) alongside classic spatial metrics ($\pi_{\text{dist}}^*$).
* **Visualization Export:** Exports the complete analytical pipeline directly to the GPU-accelerated standalone visualizer.
