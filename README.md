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

## Usage & Exploration
All figures in the report are contained within Jupyter Notebook: ```Photon_Isolation_Techniques_Ehliz.ipynb```

This notebook is designed to be a user-friendly sandbox. You can produce new results and test theoretical limits by adjusting the following physical parameters:
- **Cross-Section Dynamics (Figure 2)**: Play with the energy fraction $z$ and the emission angle $\theta$ between the daughter quark and the photon to visualize how the cross-section diverges in the soft and collinear limits.

- **Isolation Profile Transitions (Figure 4):** Play with the smoothing parameter $n$ to observe the transition from Frixione (Smooth) Cone to the Hard Cone limit ($n \to 0$). You can also play with the cone radius $\delta_{0}$​ to see its effect on the overall isolation tightness.

- **Democratic vs. Static Boundaries (Figure 5):** Play with the photon transverse momentum $p_T$​, the cone radius $R_0$​, and the energy fraction $z_{cut}$ to observe how the Soft Drop boundary differs from Frixione at high angles due to the photon-hadron system's unified treatment.

- **Factorization Validation (Figure 6):** Play with the cone radius $R_0$, the minimum resolution angle $θ_ {min}$​, and the soft drop threshold $z_cut$​ to check if the Monte Carlo integration remains proportional to the theoretical QED splitting function $P(z)$.

- **Background Kinematics (Figure 7):** Examine the $\pi^0 \to \gamma \gamma$ background by focusing the pion energy and detector granularity limits and consider how other neutral meson backgrounds (like the $\eta$ meson) might behave under similar angular cut-offs.

## Contact
If you have any questions or suggestions regarding the implementation or the numerical results of this study, feel free to reach out.
- Author: Mehmet Ehliz
- LinkedIn: https://www.linkedin.com/in/ehliz/
- Email: imi.ehliz@gmail.com







