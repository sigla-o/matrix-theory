# MT ROADMAP — v2.0

## Structural Scheme with Cyclicity Principle and P_L1 Operator

> *"MT does not claim to determine the size of the Universe. It uses cyclicity as its structural principle."*

---

## 1. MT AS A COMPLEMENTARY FRAMEWORK (METHODOLOGICAL PREREQUISITE)

MT is not designed to replace General Relativity, Quantum Electrodynamics, or the Lambda-CDM cosmological model. Its aim is to provide a **deeper mechanical foundation** for the phenomenological successes of these theories.

- Existing theories remain valid within their operational domains (L1, H0, ID1 — ID4).
- MT offers a description of the "territory" (ID0 lattice and the Vertical) that explains *why* these "maps" (classical equations) work.

---

## 2. AXIOMATIC FOUNDATIONS (NOT FREE)

| Quantity | Value / Operator | Origin | ID correspondence |
|----------|------------------|--------|-------------------|
| Lattice step | \( \lambda_{\text{ID0}} = l_P \) | Fixed from observations | ID0 |
| Matrix clock | \( \omega_0 = 2\pi c/l_P \) | Derived from \( c \) and \( l_P \) | ID0 |
| Maximum transfer quantum | \( \phi_0 = \hbar c/l_P \) | From \( \omega_0 \) and \( \hbar \) | ID0 |
| Elasticity | \( \alpha_0 = 6\omega_0/7 \) | From Q1 combinatorics | ID0 |
| Gravitational constant | \( G_0 = 6\omega_0\phi_0/49 \) | From Q1 combinatorics | ID0 |
| Cyclicity constant | \( C = \ell_k/n_k \approx 35.325 \) | From observations | ID0.n |
| Cyclicity inverse scale | \( \gamma = 2\pi/C \approx 0.18 \) | Derived from \( C \) | ID0 |

---

## 3. H0 PATH — GRAVITY AND DYNAMICS (ID0 / ID1 — ID4)

**Operator:**
$$
\mathbf{g}(\mathbf{x}) = -\nabla \delta(\mathbf{x}), \quad \delta(\mathbf{x}) = \frac{\phi_0}{\|\mathbf{x} - \mathbf{x}_0\|^2}
$$

**What it does:** Describes the motion of material objects on the H0 lattice.

**Where it leads:**
- Kepler's laws, orbits (ID1 — ID2),
- Galaxy rotation curves (with \( G(\rho_{\mathcal{V}}) \)) (ID2 / ID-1),
- Gravitational waves as deficit oscillations (ID0).

**Use when:** observation is dynamic (velocities, positions, accelerations).

**Do not mix with:** absolute value of \( \rho_{\mathcal{V}} \) — only its gradient (ID-1 → ID0).

---

## 4. L1 PATH — REDSHIFT AND CMB (ID0 / ID-1)

L1 is a **mathematical structure of cyclicity**, manifesting as the harmonic sequence in the CMB spectrum.

### 4.1. \( \mathcal{P}_{L1} \) — L1 projection operator

$$
\mathcal{P}_{L1}[\rho_{\mathcal{V}}](\mathbf{x}) = \int_{\mathcal{V}} K(\mathbf{x}, \mathbf{x}') \, \rho_{\mathcal{V}}(\mathbf{x}') \, d\mathbf{x}'
$$

with kernel:
$$
K(\mathbf{x}, \mathbf{x}') = \sum_{n=1}^{\infty} \sum_{\hat{\mathbf{r}} \in \{\pm X, \pm Y, \pm Z\}} \frac{1}{N(n)} \cdot e^{i \mathbf{k}_n \cdot (\mathbf{x} - \mathbf{x}')} \cdot \mathcal{F}_n(\mathbf{x}, \mathbf{x}')
$$

**Components:**
- \( \mathbf{k}_n = \frac{2\pi n}{\lambda_{\text{ID0}}} \hat{\mathbf{r}} \) — wave vector (from Qn periodicity),
- \( \mathcal{F}_n = \begin{cases} 1, & n \leq C/(2\pi) \\ e^{-\gamma (n - C/(2\pi))}, & n > C/(2\pi) \end{cases} \) — focusing/dispersion transition.

### 4.2. CMB spectrum

$$
I(\nu) = B_\nu(T_{L0}) \cdot \left[ 1 + \sum_{k} |c_{n_k}|^2 \cdot \delta(\nu - \nu_k) \right]
$$

where \( c_n = \frac{n^3}{6\phi_0} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \cdot \frac{4\pi^2}{C^2} \).

---

## 5. PREDICTIONS (ID0.n)

| Peak | \( k \) | \( n_k \) | \( \ell_k \) (MT) | ID correspondence |
|------|---------|-----------|-------------------|-------------------|
| 1 | 1 | 6 | ~212 | ID0.6 |
| 2 | 2 | 15 | ~530 | ID0.15 |
| 3 | 3 | 23 | ~812 | ID0.23 |
| 4 | 4 | 31 | ~1095 | ID0.31 |
| 5 | 5 | 39 | ~1378 | ID0.39 |
| 6 | 6 | 47 | ~1660 | ID0.47 |
| 7 | 7 | 55 | ~1943 | ID0.55 |

---

## 6. WHAT IS NOT A FREE PARAMETER (AND WHY)

| Previously called "free" | Now fixed as | Justification | ID correspondence |
|--------------------------|--------------|---------------|-------------------|
| \( \lambda_{\text{ID0}} \) | \( l_P \) | Planck length | ID0 |
| \( \omega_0 \) | \( 2\pi c/l_P \) | Derived from \( c \) and \( l_P \) | ID0 |
| \( \phi_0 \) | \( \hbar c/l_P \) | Maximum transfer quantum | ID0 |
| \( \gamma \approx 0.18 \) | \( 2\pi/C \) | From cyclicity constant | ID0 |
| \( C \approx 35.325 \) | \( \ell_k/n_k \) | From observations | ID0.n |
| \( \rho_{\mathcal{V}}(r) \) profile | \( \rho_0 e^{-r/r_0} \) | Dynamically derived | ID-1 / ID2 |
| \( c_n \) | \( \frac{n^3}{6\phi_0} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \cdot \frac{4\pi^2}{C^2} \) | Derived from \( \mathcal{P}_{L1} \) | ID0.n / ID-1 |

---

## 7. HOW TO USE THIS ROADMAP

1. **Before any new formula:** identify whether it belongs to the H0 path, L1 path, or both.
2. **If H0 (ID0 / ID1 — ID4):** use only \( \nabla\delta \), \( G(\rho_{\mathcal{V}}) \), mass distribution.
3. **If L1 (ID0 / ID-1):** use only \( \mathcal{P}_{L1} \), \( C \), \( \gamma \), \( \rho_{\mathcal{V}} \).
4. **If both:** use as independent operators that together describe one \( \rho_{\mathcal{V}} \) field. **Do not mix** operators.
5. **If in doubt about a parameter:** check whether it can be derived from \( l_P \), \( c \), \( \omega_0 \), \( \phi_0 \), Q1 combinatorics, or cyclicity. If not — it is not an MT parameter.

---

## 8. CONCLUSION

This document **fixes MT's structural logic** with the cyclicity principle and the fully defined \( \mathcal{P}_{L1} \) operator. All quantities are now derived or determined from observations — no free parameters remain.

**Version:** 2.0  
**Addition:** cyclicity principle, \( \mathcal{P}_{L1} \) operator, charge redefinition

---

*Document prepared: July 2026*
