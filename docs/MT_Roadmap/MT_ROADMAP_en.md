# MT ROADMAP — v1.2
## Structural Feedback with ID System

> *"Theory comes from observations, not the other way around. MT is based on the Planck length as a long-lived constant."*

---

## 1. AXIOMATIC FOUNDATIONS (NOT FREE)

| Quantity | Value / Operator | Origin | Status | ID correspondence |
|----------|------------------|--------|--------|-------------------|
| **Lattice step** | \( \lambda_{\text{ID1}} = l_P = \sqrt{\hbar G_0/c^3} \) | Fixed from observations (Planck length) | Foundation | **ID0** |
| **Matrix clock** | \( \omega_0 = \dfrac{2\pi c}{l_P} \) | Derived from \( c \) and \( l_P \) | Foundation | **ID0** |
| **Synchronous rotation** | \( \dot{\theta}(\mathbf{x},t) = \omega_0, \forall \mathbf{x} \) | All ID1 points rotate identically | Axiom | **ID0** |
| **Phase** | \( \psi(\mathbf{x},t) \sim e^{i\theta(\mathbf{x},t)} \) | Basis of wave function | Operator | **ID0 / ID1** |
| **Qn shells** | \( Q_n = \{\|\mathbf{x}\|_\infty \leq n\}, \ | Q_n| = \frac{(2n+1)(2n^2+2n+3)}{3} \) | Geometry from \( \mathbb{Z}^3 \) | Structural | **ID0.n** |
| **ID step** | \( \text{ID} = 2.0 + \log_{2.5}(n) \) | From Qn layer sequence | Structural | **ID1 — ID5** |

---

## 2. H0 PATH — GRAVITY AND DYNAMICS (horizontal) (ID0 / ID1 — ID4)

**Operator:**
\[
\mathbf{g}(\mathbf{x}) = -\nabla \delta(\mathbf{x}), \quad \delta(\mathbf{x}) = \frac{\Phi_0}{\|\mathbf{x} - \mathbf{x}_0\|^2}
\]

**What it does:** Describes the motion of material objects through the H0 lattice.

**Where it leads:**
- Kepler's laws, orbits (ID1 — ID2),
- Galaxy rotation curves (with \( G(\rho_{\mathcal{V}}) \)) (ID2 / ID-1),
- Gravitational waves as pressure waves (ID0),
- Mass distribution from \( \nabla^2\delta = 4\pi G_0\rho \) (ID0).

**ID correspondence:**
- **ID0** — the lattice itself and flow foundation.
- **ID1** — protons and atoms (mass sources).
- **ID2** — stars, planets, galaxies (objects in motion).
- **ID3** — white dwarfs, neutron stars (collapsed objects).
- **ID4** — black holes (extreme mass sources).

**Use when:** the observation is dynamic (velocities, positions, accelerations).

**Do not couple with:** the absolute value of \( \rho_{\mathcal{V}} \) — only with its gradient (ID-1 → ID0).

---

## 3. L1 GEOMETRIC SCHEME (vertical) (ID0 / ID-1)

L1 is a **geometric projection level**, not an energy level. It has two modes of operation depending on location relative to the proton (inside / outside H0).

**ID correspondence:**
- **ID0** — L1 projection onto the H0 matrix.
- **ID-1** — L1 connection to Vertical energy.

### 3.1. L1 — FOCUSING (INSIDE H0) (ID0.n)

**Action:** Focuses energy and modulations, creating **standing waves**.

**Result:** Discrete CMB peaks (\( \ell_k \)).

**Geometric basis:**
\[
\ell_k = C \cdot n_k, \quad C = \frac{2\pi R_{L1}}{\lambda_{\text{ID1}}}, \quad n_k = 8k-1 \ (k \ge 2), \ n_1 = 6
\]

The harmonics correspond to Qn layers (ID0.n), where lattice symmetry creates resonance.

---

### 3.2. L1 — DISPERSION (OUTSIDE THE PROTON) (ID0 / ID-1)

**Action:** Disperses energy from the focusing zone outward.

**Result:** Continuous CMB background and redshift (ID-1).

**Mechanism:** Dispersed energy reaches the L0 level (ID-1), where it thermalizes.

---

### 3.3. L0 — ENERGY BALANCE (ID-1)

L0 is the **background level**, where flow is synchronized and uniform. It is not a vacuum, but a reference state.

- **L0 → L1:** focusing (energy concentration) (ID-1 → ID0).
- **L1 → L0:** dispersion (energy equalization) (ID0 → ID-1).

**Energy is not lost — it flows between L0 and L1.**

**ID correspondence:**
- **ID-1** — L0 background energy level (Vertical).

---

## 4. CMB SCHEME — FULL SPECTRUM (ID0.n / ID-1)

CMB is a superposition of two components:

\[
I(\nu) = B_\nu(T_{L0}) \cdot \left[ 1 + \sum_k A_k \cdot \delta(\nu - \nu_k) \right]
\]

where:
- \( B_\nu(T_{L0}) \) — Planck spectrum from L0 thermalization (ID-1),
- \( \nu_k = \dfrac{c \ell_k}{2\pi R_{L1}} \) — standing wave harmonic frequencies (ID0.n),
- \( A_k \) — resonance amplification coefficients.

**Synchronized structures** (standing waves) give discrete peaks (ID0.n).
**Unsynchronized structures** (dispersion) give the continuous background (ID-1).

---

## 5. PREDICTIONS (ID0.n)

| Peak | \( k \) | \( n_k \) | \( \ell_k \) (MT) | Observation | ID correspondence |
|------|---------|-----------|-------------------|-------------|-------------------|
| 1 | 1 | 6 | ~212 | ~220 | ID0.6 |
| 2 | 2 | 15 | ~530 | ~538 | ID0.15 |
| 3 | 3 | 23 | ~812 | ~813 | ID0.23 |
| 4 | 4 | 31 | ~1095 | ~1085 | ID0.31 |
| 5 | 5 | 39 | ~1378 | ~1381 | ID0.39 |
| 6 | 6 | 47 | ~1660 | (CMB-S4) | ID0.47 |
| 7 | 7 | 55 | ~1943 | (Simons Obs.) | ID0.55 |

---

## 6. WHAT IS NOT A FREE PARAMETER (AND WHY)

| Previously mentioned as "free" | Now fixed as | Justification | ID correspondence |
|-------------------------------|--------------|---------------|-------------------|
| \( \lambda_{\text{ID1}} \) | \( l_P \) | Planck length — observational long-lived constant | ID0 |
| \( \omega_0 \) | \( 2\pi c/l_P \) | Derived from \( c \) and \( l_P \) | ID0 |
| \( \gamma \approx 0.18 \) | \( \lambda_{\text{ID1}}/R_{L1} \) | Ratio determined by L1 geometry | ID0 |
| \( C \approx 35.325 \) | \( 2\pi R_{L1}/\lambda_{\text{ID1}} \) | Ratio, not a free number | ID0 |
| \( \rho_{\mathcal{V}}(r) \) profile | \( \rho_0 e^{-r/r_0} \) | Dynamically derived from ID transition logistics | ID-1 / ID2 |
| \( r_0 \) | \( 1/\alpha \), where \( \alpha = \alpha_0(1 - \gamma\rho_{\mathcal{V}}/\rho_{\text{H0}}) \) | Consequence of filling dynamics | ID2 / ID-1 |
| L1 focus/dispersion | Geometric, determined by location | Structural boundary, not a free choice | ID0 / ID-1 |

**Conclusion:** MT has no free parameters. There is only:
- one lattice scale \( l_P \) (ID0),
- one energy field \( \rho_{\mathcal{V}} \) (ID-1),
- one geometric structure \( Q_n \) (ID0.n),
- and L1 as a projection of this structure (ID0 / ID-1).

---

## 7. WHAT MT DOES NOT DO (AND WHY)

| Standard physics concept | MT replaces with | Why | ID correspondence |
|--------------------------|------------------|-----|-------------------|
| **Time dilation** | Amplitude modulation (L1) | Clock \( \omega_0 \) is absolute; only energy scale changes | ID0 / ID-1 |
| **Gravitational redshift** | L1 amplitude shift | Gravity is \( \nabla\rho_{\mathcal{V}} \), shift is \( \sqrt{\rho_{\mathcal{V}}} \) — orthogonal | ID0 / ID-1 |
| **Spacetime curvature** | TE flow pressure gradient (H0) | No metric; only flow density differences | ID0 |
| **Dark matter** | \( \rho_{\mathcal{V}} \) influence on \( G \) and light energy | Everything explained by Vertical energy distribution | ID-1 / ID0 |
| **Big Bang** | L1 focusing zone standing wave projection | CMB is not a relic, but a permanent matrix property | ID0.n / ID-1 |

---

## 8. HOW TO USE THIS ROADMAP (FORMALIZER'S INSTRUCTION)

1. **Before any new formula:** identify whether it belongs to the H0 path, the L1 path, or both.
2. **If H0 (ID0 / ID1 — ID4):** use only \( \nabla\delta \), \( G(\rho_{\mathcal{V}}) \), mass distribution. **Do not couple** with \( \sqrt{\rho_{\mathcal{V}}} \) or \( z \).
3. **If L1 (ID0 / ID-1):** use only \( \sqrt{\rho_{\mathcal{V}}} \), \( 1+z \), \( E_{\text{photon}} \). **Do not couple** with \( \nabla\rho_{\mathcal{V}} \) or acceleration.
4. **If both:** use them as independent equations that together describe one \( \rho_{\mathcal{V}} \) field. **Do not mix** operators.
5. **If in doubt about a parameter:** check whether it is derivable from \( l_P \), \( c \), \( \omega_0 \), \( \rho_{\mathcal{V}} \) dynamics, or Qn combinatorics. If not — it is not an MT parameter.

---

## 9. FURTHER POINTS TO BE REFINED

1. **L1 projection details:** how \( \mathcal{P}_{L1} \) precisely transforms \( \rho_{\mathcal{V}} \) into \( I(\nu) \) (ID0 / ID-1).
2. **H0 and L1 alignment in galaxy clusters:** simultaneous prediction of dynamics and redshifts (ID2 / ID-1).
3. **\( \alpha_0 \) derivation from \( l_P \) and \( \omega_0 \):** so that \( r_0 \) is fully determined by the lattice (ID0).

---

## 10. CONCLUSION

This document **fixes our current understanding** of MT's structural logic and the L1 geometric scheme, aligned with the ID system. It is a living document, updated as new levels of logic are introduced.

**Version:** 1.2  
**Addition:** ID system references for all quantities and operators.

---

*Document prepared: July 2026*
