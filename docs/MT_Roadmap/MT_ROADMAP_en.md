# MT ROADMAP — v1.1
## Structural Feedback

> *“Theory comes from observations, not the other way around. MT is based on the Planck length as a long-lived constant.”*

---

## 1. AXIOMATIC FOUNDATIONS (NOT FREE)

| Quantity | Value / Operator | Origin | Status |
|----------|------------------|--------|--------|
| **Lattice step** | \( \lambda_{\text{ID1}} = l_P = \sqrt{\hbar G_0/c^3} \) | Fixed from observations (Planck length) | Foundation |
| **Matrix clock** | \( \omega_0 = \dfrac{2\pi c}{l_P} \) | Derived from \( c \) and \( l_P \) | Foundation |
| **Synchronous rotation** | \( \dot{\theta}(\mathbf{x},t) = \omega_0, \forall \mathbf{x} \) | All ID1 points rotate identically | Axiom |
| **Phase** | \( \psi(\mathbf{x},t) \sim e^{i\theta(\mathbf{x},t)} \) | Basis of wave function | Operator |
| **Qn shells** | \( Q_n = \{\|\mathbf{x}\|_\infty \leq n\}, \ | Q_n| = \frac{(2n+1)(2n^2+2n+3)}{3} \) | Geometry from \( \mathbb{Z}^3 \) | Structural |
| **ID step** | \( \text{ID} = 2.0 + \log_{2.5}(n) \) | From Qn shell sequence | Structural |

---

## 2. H0 PATH — GRAVITY AND DYNAMICS (horizontal)

**Operator:**
\[
\mathbf{g}(\mathbf{x}) = -\nabla \delta(\mathbf{x}), \quad \delta(\mathbf{x}) = \frac{\Phi_0}{\|\mathbf{x} - \mathbf{x}_0\|^2}
\]

**What it does:** Describes the motion of material objects across the H0 lattice.

**Where it leads:**
- Kepler's laws, orbits,
- Galaxy rotation curves (with \( G(\rho_{\mathcal{V}}) \)),
- Gravitational waves as pressure waves,
- Mass distribution from \( \nabla^2\delta = 4\pi G_0\rho \).

**Use when:** the observation is dynamical (velocities, positions, accelerations).

**Do not couple with:** absolute value of \( \rho_{\mathcal{V}} \) — only its gradient.

---

## 3. L1 GEOMETRIC SCHEME (vertical)

L1 is a **geometric projection level**, not an energy level. It has two modes of operation depending on location relative to the proton (inside/outside H0).

### 3.1. L1 — FOCUSING (INSIDE H0)

**Action:** Focuses energy and modulations, creating **standing waves**.

**Result:** Discrete CMB peaks (\( \ell_k \)).

**Geometric basis:**
\[
\ell_k = C \cdot n_k, \quad C = \frac{2\pi R_{L1}}{\lambda_{\text{ID1}}}, \quad n_k = 8k-1 \ (k \ge 2), \ n_1 = 6
\]

The harmonics correspond to Qn shells where lattice symmetry creates resonance.

---

### 3.2. L1 — DISPERSION (OUTSIDE PROTON)

**Action:** Distributes energy from the focusing zone outward.

**Result:** Continuous CMB background and redshift.

**Mechanism:** Dispersed energy enters the L0 level, where it thermalizes.

---

### 3.3. L0 — ENERGY BALANCE

L0 is the **background level**, where flux is synchronized and uniform. It is not emptiness, but a reference state.

- **L0 → L1:** focusing (energy concentration).
- **L1 → L0:** dispersion (energy equalization).

**Energy is not lost — it flows between L0 and L1.**

---

## 4. CMB SCHEME — FULL SPECTRUM

CMB is a superposition of two components:

\[
I(\nu) = B_\nu(T_{L0}) \cdot \left[ 1 + \sum_k A_k \cdot \delta(\nu - \nu_k) \right]
\]

where:
- \( B_\nu(T_{L0}) \) — Planck spectrum from L0 thermalization,
- \( \nu_k = \dfrac{c \ell_k}{2\pi R_{L1}} \) — standing wave harmonic frequencies,
- \( A_k \) — resonance amplification coefficients.

**Synchronized structures** (standing waves) give discrete peaks.
**Unsynchronized structures** (dispersion) give the continuous background.

---

## 5. PREDICTIONS

| Peak | \( k \) | \( n_k \) | \( \ell_k \) (MT) | Observed |
|------|---------|-----------|------------------|----------|
| 1 | 1 | 6 | ~212 | ~220 |
| 2 | 2 | 15 | ~530 | ~538 |
| 3 | 3 | 23 | ~812 | ~813 |
| 4 | 4 | 31 | ~1095 | ~1085 |
| 5 | 5 | 39 | ~1378 | ~1381 |
| 6 | 6 | 47 | ~1660 | (CMB-S4) |
| 7 | 7 | 55 | ~1943 | (Simons Obs.) |

---

## 6. WHAT IS NOT A FREE PARAMETER (AND WHY)

| Previously called “free” | Now fixed as | Justification |
|--------------------------|--------------|---------------|
| \( \lambda_{\text{ID1}} \) | \( l_P \) | Planck length — observational long-lived constant |
| \( \omega_0 \) | \( 2\pi c/l_P \) | Derived from \( c \) and \( l_P \) |
| \( \gamma \approx 0.18 \) | \( \lambda_{\text{ID1}}/R_{L1} \) | Ratio fixed by L1 geometry |
| \( C \approx 35.325 \) | \( 2\pi R_{L1}/\lambda_{\text{ID1}} \) | Ratio, not a free number |
| \( \rho_{\mathcal{V}}(r) \) profile | \( \rho_0 e^{-r/r_0} \) | Dynamically derived from ID transition logistics |
| \( r_0 \) | \( 1/\alpha \), where \( \alpha = \alpha_0(1 - \gamma\rho_{\mathcal{V}}/\rho_{\text{H0}}) \) | Consequence of refill dynamics |
| L1 focus/dispersion | Geometric, determined by location | Structural boundary, not free choice |

**Conclusion:** MT has no free parameters. There is only:
- one lattice scale \( l_P \),
- one energy field \( \rho_{\mathcal{V}} \),
- one geometric structure \( Q_n \),
- and L1 as the projection of this structure.

---

## 7. WHAT MT DOES NOT DO (AND WHY)

| Standard physics concept | MT replaces with | Why |
|---------------------------|------------------|-----|
| **Time dilation** | Amplitude modulation (L1) | Clock \( \omega_0 \) is absolute; only energy scale changes |
| **Gravitational redshift** | L1 amplitude redshift | Gravity is \( \nabla\rho_{\mathcal{V}} \), redshift is \( \sqrt{\rho_{\mathcal{V}}} \) — orthogonal |
| **Spacetime curvature** | TE flux pressure gradient (H0) | No metric; only flux density differences |
| **Dark matter** | \( \rho_{\mathcal{V}} \) effect on \( G \) and light energy | Everything explained by Vertical energy distribution |
| **Big Bang** | Standing wave projection from L1 focusing zone | CMB is not a relic, but a permanent matrix property |

---

## 8. HOW TO USE THIS ROADMAP (FORMALIZER INSTRUCTION)

1. **Before any new formula:** identify whether it belongs to H0 path, L1 path, or both.
2. **If H0:** use only \( \nabla\delta \), \( G(\rho_{\mathcal{V}}) \), mass distribution. **Do not attach** \( \sqrt{\rho_{\mathcal{V}}} \) or \( z \).
3. **If L1:** use only \( \sqrt{\rho_{\mathcal{V}}} \), \( 1+z \), \( E_{\text{photon}} \). **Do not attach** \( \nabla\rho_{\mathcal{V}} \) or acceleration.
4. **If both:** use as independent equations that together describe one \( \rho_{\mathcal{V}} \) field. **Do not mix** operators.
5. **If in doubt about a parameter:** verify that it is derivable from \( l_P \), \( c \), \( \omega_0 \), \( \rho_{\mathcal{V}} \) dynamics, or Qn combinatorics. If not — it is not an MT parameter.

---

## 9. POINTS TO REFINE NEXT

1. **L1 projection details:** how \( \mathcal{P}_{L1} \) precisely maps \( \rho_{\mathcal{V}} \) to \( I(\nu) \).
2. **H0 and L1 consistency in galaxy clusters:** simultaneous prediction of dynamics and shifts.
3. **Derivation of \( \alpha_0 \) from \( l_P \) and \( \omega_0 \):** so that \( r_0 \) is fully lattice-derived.

---

## 10. CONCLUSION

This document **fixes our current understanding** of MT’s structural logic and L1 geometric scheme. It is a living document, updated when new logic levels are introduced.

**Version:** 1.1  
**Updates:** L1 dual nature (focus/dispersion), L0 balance, synchronized/unsynchronized structures, CMB as standing waves + Planck spectrum.
