# CSE 5280 — Multiple Particles (Social Interaction)

**Nick Speranza**

This project studies multi-agent motion generated purely through
continuous cost-function minimization.

Agents navigate using gradient descent on a shared objective containing:

- goal attraction
- wall avoidance
- social interaction terms

No discrete collision checking or path planning algorithms are used.

---

## 📄 View Report (Recommended)

Open the fully rendered notebook:

https://nbviewer.org/github/nicolas-speranza/cse5280-multiple-particles-nicolas-speranza/blob/main/multiple_particles.ipynb

---

## Contents

- Theoretical formulation
- Gradient-descent multi-agent model
- Isotropic and anisotropic interaction models
- Quantitative experiments
- Trajectory visualizations
- Animations and video evidence
- Discussion and conclusions

---

## Models Compared

- **none** — no social interaction
- **iso_quad** — quadratic personal space
- **iso_inv** — inverse-distance repulsion
- **aniso** — directionally weighted interaction

---

## Key Result

Complex crowd behavior emerges **only from optimization** —
not from explicit collision rules or planning algorithms.
