# Photon Isolation Techniques: From Frixione to Soft Drop

## Project Overview
This project presents a phenomenological study of photon isolation techniques in high-energy physics, focusing on the transition from foundational methods like Hard Cone and Frixione (Smooth) Cone to modern Soft Drop Isolation (SDI). The work demonstrates the infrared (IR) safety of these methods and establishes a numerical and theoretical equivalence between SDI and Frixione isolation at small angles.

## Physics Context
Distinguishing prompt photons from background (such as $\pi \to \gamma \gamma$ decay) is a critical challenge in LHC physics, especially for channels like $H \to \gamma\gamma$

This repository contains the numerical work used to:
- Analyze the differential cross-section for single quark-to-photon branching.
- Validate the equivalence between Soft Drop and Frixione parameters ($z_{cut} = \epsilon_{\gamma}$ and $\beta = 2n$)
- Recover the QED splitting function $P(z)$ from isolated photon subjets.
- Calculate the necessary angular cut-off ($\theta_{min}$​) to suppress neutral pion backgrounds.

## Methodology & Numerical Implementation
I use numerical integration and 3D surface mapping to visualize the behavior of isolation boundaries.
- Numerical Analysis: Profiling the energy threshold function $\chi(\delta)$.
- Monte Carlo Integration: Validating the factorization of the isolated photon subjet distribution.
- 3D Visualization: Mapping the probability density of soft and collinear emissions.

## Prerequisites
I design the project to be user-friendly.

Required Libraries:
```pip install numpy matplotlib scipy```

- **NumPy**: Coordinate grids for cross-section surfaces.
- **Matplotlib**: 2D profiles and 3D surface plots.
- **SciPy**: Numerical integration of splitting functions and isolation thresholds


