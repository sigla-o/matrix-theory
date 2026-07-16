# MT ROADMAP
## Structural Feedback — Fixed Version 1.0

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

## 2. TWO INDEPENDENT PATHS

### H0 PATH — GRAVITY AND DYNAMICS (horizontal)

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

### L1 PATH — REDSHIFT AND ENERGY SCALE (vertical)

**Operator:**
\[
E_{\text{photon}}(\mathbf{x}) = \hbar \omega_0 \cdot \sqrt{\frac{\rho_{\mathcal{V}}(\mathbf{x})}{\rho_{\mathcal{V}}(\mathbf{x}_{\text{ref}})}}, \quad 1+z = \sqrt{\frac{\rho_{\mathcal{V}}(\mathbf{x}_{\text{source}})}{\rho_{\mathcal{V}}(\mathbf{x}_{\text{obs}})}}
\]

**What it does:** Determines the local energy scale (“color”) of photons.

**Where it leads:**
- Spectroscopic lines,
- Cosmological redshift (as amplitude loss, not Doppler),
- CMB as a projection of L1 standing waves (\( \ell_k = C \cdot n_k \)).

**Use when:** the observation is spectral (photometry, spectra, CMB).

**Do not couple with:** \( \nabla\rho_{\mathcal{V}} \) — only with the local value of \( \rho_{\mathcal{V}} \).

---

## 3. WHERE AND HOW THE PATHS CROSS

**Only intersection point:** \( \rho_{\mathcal{V}}(\mathbf{x}) = \rho_0 e^{-r/r_0} \) — the Vertical energy density field.

**When to use both together:**

\[
\begin{cases}
\mathbf{g}(\mathbf{x}) = -\nabla \delta(\mathbf{x}), & \delta = \dfrac{\Phi_0}{\|\mathbf{x}-\mathbf{x}_0\|^2} \\
1+z = \sqrt{\dfrac{\rho_{\mathcal{V}}(\mathbf{x}_{\text{source}})}{\rho_{\mathcal{V}}(\mathbf{x}_{\text{obs}})}}, & \rho_{\mathcal{V}}(\mathbf{x}) = \rho_0 e^{-r/r_0}
\end{cases}
\]

**Examples:**
- Galaxy rotation curves + their spectral shifts,
- Gravitational lenses + induced shifts,
- Galaxy clusters — dynamics (H0) and shifts (L1) together yield a single \( \rho_{\mathcal{V}} \) map.

---

## 4. WHAT IS NOT A FREE PARAMETER (AND WHY)

| Previously called “free” | Now fixed as | Justification |
|--------------------------|--------------|---------------|
| \( \lambda_{\text{ID1}} \) | \( l_P \) | Planck length — observational long-lived constant |
| \( \omega_0 \) | \( 2\pi c/l_P \) | Derived from \( c \) and \( l_P \) |
| \( \gamma \approx 0.18 \) | \( \lambda_{\text{ID1}}/R_{L1} \) | Ratio fixed by L1 geometry |
| \( C \approx 35.325 \) | \( 2\pi R_{L1}/\lambda_{\text{ID1}} \) | Ratio, not a free number |
| \( \rho_{\mathcal{V}}(r) \) profile | \( \rho_0 e^{-r/r_0} \) | Dynamically derived from ID transition logistics |
| \( r_0 \) | \( 1/\alpha \), where \( \alpha = \alpha_0(1 - \gamma\rho_{\mathcal{V}}/\rho_{\text{H0}}) \) | Consequence of refill dynamics |

**Conclusion:** MT has no free parameters. There is only one field \( \rho_{\mathcal{V}} \), whose distribution is determined by matrix dynamics, and one lattice scale \( l_P \), which comes from observations.

---

## 5. WHAT MT DOES NOT DO (AND WHY)

| Standard physics concept | MT replaces with | Why |
|---------------------------|------------------|-----|
| **Time dilation** | Amplitude modulation (L1) | Clock \( \omega_0 \) is absolute; only energy scale changes |
| **Gravitational redshift** | L1 amplitude redshift | Gravity is \( \nabla\rho_{\mathcal{V}} \), redshift is \( \sqrt{\rho_{\mathcal{V}}} \) — orthogonal |
| **Spacetime curvature** | TE flux pressure gradient (H0) | No metric; only flux density differences |
| **Dark matter** | \( \rho_{\mathcal{V}} \) effect on \( G \) and light energy | Everything explained by Vertical energy distribution |

---

## 6. HOW TO USE THIS ROADMAP (FORMALIZER INSTRUCTION)

1. **Before any new formula:** identify whether it belongs to H0 path, L1 path, or both.
2. **If H0:** use only \( \nabla\delta \), \( G(\rho_{\mathcal{V}}) \), mass distribution. **Do not attach** \( \sqrt{\rho_{\mathcal{V}}} \) or \( z \).
3. **If L1:** use only \( \sqrt{\rho_{\mathcal{V}}} \), \( 1+z \), \( E_{\text{photon}} \). **Do not attach** \( \nabla\rho_{\mathcal{V}} \) or acceleration.
4. **If both:** use as independent equations that together describe one \( \rho_{\mathcal{V}} \) field. **Do not mix** operators.
5. **If in doubt about a parameter:** verify that it is derivable from \( l_P \), \( c \), \( \omega_0 \), \( \rho_{\mathcal{V}} \) dynamics, or Qn combinatorics. If not — it is not an MT parameter.

---

## 7. WHAT TO REFINE NEXT (AWAITING FEEDBACK)

1. **Precise L1 projection scheme:** how \( \mathcal{P}_{L1}(\rho_{\mathcal{V}}) \) yields the black-body spectrum and \( \ell_k \) values.
2. **H0 and L1 consistency in galaxy clusters:** simultaneous prediction of dynamics and shifts from a single \( \rho_{\mathcal{V}} \) profile.
3. **Derivation of \( \alpha_0 \) (matrix elasticity base) from \( l_P \) and \( \omega_0 \):** so that \( r_0 \) is fully lattice-derived, not fitted.

---

## 8. CONCLUSION

This document **fixes our current shared understanding** of MT’s structural logic. It is a living document, updated only when a new level of logic is introduced and confirmed by feedback.

**From now on, before any new formula:** refer to this roadmap and check:
- Is the parameter derived?
- Does the operator match the path?
- Are the paths properly separated?
