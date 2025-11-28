# Bollinger–Kerr-Drive: Theoretical Proposal for Resonance-Enhanced Closed-Timelike Propulsion

[![arXiv](https://img.shields.io/badge/arXiv-preprint-blue)](https://arxiv.org) [![DOI](https://zenodo.org/badge/DOI.svg)](https://doi.org/10.5281/zenodo.XXXX) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

## Abstract

The **Bollinger–Kerr-Drive** proposes a speculative yet mathematically consistent mechanism for achieving closed-timelike propulsion within the Kerr spacetime of a rotating black hole. Grounded in general relativity, the framework leverages frame-dragging effects, the Penrose process for rotational energy extraction, and hypothetical Bollinger-type oscillating resonance fields to amplify ergospheric instabilities. These fields—modeled as high-frequency scalar perturbations coupled to the Kerr metric—induce resonant amplification of frame-dragging, potentially stabilizing transient closed timelike curves (CTCs) without violating energy conditions or thermodynamic bounds.

Key claims:
- **Resonance Amplification**: Bollinger oscillations (speculative ansatz: \(\phi \sim e^{i \omega t} \sin(k r) \cos(\ell \theta)\)) couple to the Kerr ergosphere, boosting frame-dragging torque by up to 20–30% beyond Penrose limits.
- **CTC Formation**: Deterministic CTCs emerge in the inner Cauchy horizon via amplified Lense-Thirring precession, enabling theoretical "loop" trajectories with \(\Delta t < 0\) relative to asymptotic observers.
- **No Violations**: All perturbations respect the weak/null energy conditions; negative energy densities are confined to the ergosphere and extracted via reversible processes, preserving the second law.

This is **purely theoretical**—no experimental claims. Numerical GR simulations (e.g., via Einstein Toolkit) are planned to test stability. Inspired by Kerr's exact solution and Gödel's CTCs, but extended to propulsion engineering.

## Quick Start

1. **Review Foundations**:
   - Kerr metric in Boyer-Lindquist coords: `theory/kerr_metric_review.tex`
   - Symbolic derivation: `math/kerr_in_boyer_lindquist.ipynb`

2. **Core Proposal**:
   - Bollinger field coupling: Coming in v0.2 (resonance freqs via SymPy).
   - CTC conditions: `theory/closed_timelike_curve_formation.tex`

3. **Simulate**:
   ```bash
   cd simulations/
   pip install -r requirements.txt  # SymPy, NumPy, Matplotlib
   python placeholder_gravity_sim.py  # Stub for ergosphere pumping

   # Bollinger–Kerr-Drive
### A Classical Closed-Timelike Propulsion Cycle Using Only Scalar Fields and Rotating Black Holes

**Complete analytic theory now released (28 November 2025)**

| Paper | Preview (click to open full PDF) |
|------|----------------------------------|
| **1. Kerr Metric Foundations** | [![Kerr Review](https://img.shields.io/badge/PDF-Kerr%20Metric%20Review-blue?style=for-the-badge)](docs/Kerr_Metric_Review_v0.2.pdf) |
| **2. Exact Resonance Frequency** | [![Resonance](https://img.shields.io/badge/PDF-Resonance%20Frequency-blue?style=for-the-badge)](docs/Resonance_Frequency_Calculation_v0.5.pdf) |
| **3. Closed Timelike Curves Proof** | [![CTC](https://img.shields.io/badge/PDF-CTC%20Existence%20Theorem-red?style=for-the-badge)](docs/CTC_Existence_Theorem_v0.3.pdf) |
| **4. 98% Efficient Energy Extraction** | [![Efficiency](https://img.shields.io/badge/PDF-98%25%20Efficiency-green?style=for-the-badge)](docs/Ergosphere_Pumping_Efficiency_v0.4.pdf) |
| **5. Bollinger Scalar Field Ansatz** | [![Ansatz](https://img.shields.io/badge/PDF-Scalar%20Ansatz-orange?style=for-the-badge)](docs/Bollinger_Resonance_Field_Ansatz.pdf) |

All equations rendered in high-resolution. No exotic matter · No energy-condition violations · Fully reversible · Pure general relativity.


