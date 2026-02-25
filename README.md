# U(N) Det-Phase on Lifted Branch

**ID:** `eq-un-det-phase`  
**Tier:** derived  
**Score:** 59  
**Units:** WARN  
**Theory:** PASS-WITH-ASSUMPTIONS  

## Equation

$$
\theta_R=\mathrm{unwrap}(\arg\det U;\theta_{\rm ref},\pi_a),\qquad w_{\det}=\frac{\Delta\theta_R}{2\pi_a},\qquad b(\gamma)=(-1)^{w_{\det}}
$$

## Description

Same Phase-Lift bookkeeping (integer winding + ℤ₂ shadow) applied to the determinant phase of U(N) holonomy. Bridges the U(1) parity framework to non-abelian gauge systems.

## Assumptions

- det U is nonzero (no degenerate holonomy).
- Adaptive πₐ sets the winding period instead of fixed π.
- Physical interpretation of w_det depends on the specific gauge theory.

## Repository Structure

```
images/       # Visualizations, plots, diagrams
derivations/  # Step-by-step derivations and proofs
simulations/  # Computational models and code
data/         # Numerical data, experimental results
notes/        # Research notes and references
```

## Links

- [TopEquations Leaderboard](https://rdm3dc.github.io/TopEquations/leaderboard.html)
- [TopEquations Main Repo](https://github.com/RDM3DC/TopEquations)
- [Certificates](https://rdm3dc.github.io/TopEquations/certificates.html)

---
*Part of the [TopEquations](https://github.com/RDM3DC/TopEquations) project.*
