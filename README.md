# The Elysia Mechanism for Neutron Star Cooling

**Bridging a Twenty-Year Gap: The Cassiopeia A Neutron Star Cooling Anomaly — with a Unified Model of Dynamic Redshift and Neutron Star Cooling**

This repository contains the full numerical code, data, and supplementary materials for our paper (Zhao & Chen, 2026). We show that the observed cooling rate of the Cassiopeia A neutron star (-3.9%/dec) is naturally explained by a dynamic gravitational redshift effect coupled with a hadron–quark phase transition – without any free parameters or new physics beyond GR+QCD.

## Key Features
- First self‑consistent framework that includes time‑dependent redshift in neutron star cooling.
- Phase‑transition‑driven contraction rate (`~6500 m/century`) from independent TOV simulations.
- Quantitative exclusion of all alternative mechanisms (superfluid PBF, quark direct Urca, magnetic decay, accretion, dark matter, torsion, tides).
- Testable predictions: increasing redshift, cooling deceleration (already tentatively seen in 2025 Chandra data), similar anomalies in other young neutron stars, and a gravitational wave memory signal.
- Universal extension to all cooling neutron stars.

## Contents
- `/code`: Python scripts for TOV solvers, thermal evolution, dynamic redshift calculation, and figure generation.
- `/data`: Raw cooling curves, contraction rate simulation outputs, and Cas A observational data.
- `/paper`: LaTeX source of the main text and supplemental material.

## Requirements
- Python 3.9+
- NumPy, SciPy, Matplotlib

## Reproduction
Run `python run_all.py` to regenerate all figures in the paper. See `README_technical.md` for detailed instructions.

## Citation
If you use this code or data in your research, please cite our paper:

> W. Zhao and Y. Chen, *Bridging a Twenty-Year Gap: The Elysia Mechanism for the Cassiopeia A Neutron Star Cooling Anomaly*, (2026), [journal ref. to be added].

## License
MIT
