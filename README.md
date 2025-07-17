# Jacobian Analysis of a Parameter Aware Reservoir Computing ML Algorithim

This repository contains the code and supplementary material for my **Master’s thesis**, where I explore a **parameter-aware reservoir computing (RC)** algorithm to learn and mimic the bifurcation behavior of nonlinear dynamical systems across varying parameter regimes.

📄 The full thesis document is available in this repository for detailed explanation, theoretical background, and results.

---

## Overview

In this work, I developed a custom **Parameter-Aware Reservoir Computing (PARASPY)** framework that learns to **predict the future behavior** of different nonlinear systems **across parameter values**—not just at fixed settings.

### Key contributions:

* ✅ Implemented **reservoir computing from scratch** with parameter-awareness built into the architecture.
* ✅ Applied the framework to classic nonlinear systems:

  * **Logistic Map**
  * **Kuramoto Oscillators**
  * **Stuart-Landau Oscillators**
* ✅ Modeled the trained reservoir system as a **network of coupled map equations** to extract its internal dynamics.
* ✅ Performed **Jacobian analysis** on the reservoir network to study how its **eigenvalue spectra evolve with parameters**.
* ✅ Showed that the trained reservoir system undergoes **bifurcations** similar to the original dynamical system:

  * Saddle-node bifurcation
  * Neimark–Sacker bifurcation
  * Period-doubling bifurcation

This suggests that the **reservoir model internalizes the bifurcation structure** of the system it's trained on — a striking result connecting machine learning with nonlinear dynamics.

## ⚠️ Note on Code Availability

While this repository shows how to use the two main frameworks developed:

- PARASPY (Parameter-Aware Reservoir Computing)

- Eigenvalue Analysis & Jacobian Framework

…the core implementation code of these frameworks is not included due to sharing restrictions.

However, their usage and behavior are clearly demonstrated in the included notebooks, and all results can be understood in context via the thesis.

Thank you for visiting, and happy coding!
