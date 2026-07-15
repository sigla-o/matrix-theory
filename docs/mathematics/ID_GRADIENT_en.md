# ID GRADIENT — MATRIX THEORY FORMAL MODEL (MT)
## Strict Academic Version

This document defines the ID (integration depth) scalar field, its dependence on Qn structure and Vertical energy density, and the transition conditions between ID levels.

---

## 1. CONNECTION TO MATHEMATICS FORMALISM

From MATHEMATICS_lv.md:

| Operator / quantity | Definition | Physical meaning |
|---------------------|------------|------------------|
| \( \mathcal{L} \) | \( \mathbb{Z}^3 \) | H0 cubic lattice |
| \( Q_n \) | \( \{\mathbf{x}: \|\mathbf{x}\|_\infty \leq n\} \) | Shell structure |
| \( N(n) \) | \( \frac{(2n+1)(2n^2+2n+3)}{3} \) | Point count in Qn layer |
| \( \rho_{\mathcal{V}}(\mathbf{x}) \) | \( \rho_{\mathcal{V}}^{(0)} e^{-r/r_0} \) | Vertical energy density |
| \( \mathcal{T} \) | \( \mathcal{L} \to \mathcal{V} \) | Transformation operator |
| \( \mathcal{P}_{L1} \) | \( \mathcal{V} \to \mathcal{L} \) | L1 projection operator |

**ID definition:** ID is a scalar field:
\[
\text{ID} = f(n, \rho_{\mathcal{V}}, \mathbf{M}, \mathbf{V}_{\text{loc}})
\]
where \( n \) is Qn index, \( \rho_{\mathcal{V}} \) is Vertical energy density, \( \mathbf{M} \) is modulation vector, \( \mathbf{V}_{\text{loc}} \) are local matrix state parameters.

---

## 2. ID STEP — QUANTITATIVE MODEL

### 2.1. ID step and Qn structure

\[
\text{ID} = 2.0 + \log_{S} \left( \frac{R}{R_{\text{proton}}} \right)
\]
where \( R \) is the characteristic linear scale (Qn radius), \( R_{\text{proton}} \approx 10^{-10} \) m. From Qn, \( S \approx 2.5 \). Hence:
\[
\boxed{\text{ID} = 2.0 + \log_{2.5}(n)}
\]

### 2.2. ID for monolithic objects

| Object | \( n \) | ID | Result |
|--------|---------|----|--------|
| Proton | 1 | \( 2.0 + \log_{2.5}(1) \) | ID2,0 |
| Stellar BH | ~10² | \( 2.0 + \log_{2.5}(100) \approx 2.0 + 5.0 \) | ID3,0 |
| Supermassive BH | ~10⁴ | \( 2.0 + \log_{2.5}(10^4) \approx 2.0 + 10.0 \) | ID3,5 |
| Galactic BH | ~10⁶ | \( 2.0 + \log_{2.5}(10^6) \approx 2.0 + 15.0 \) | ID3,9 |

### 2.3. Vertical energy effect

\[
\text{ID}(n, \rho_{\mathcal{V}}) = 2.0 + \log_{2.5}(n) + 0.05 \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}
\]

---

## 3. COLLECTIVE OBJECTS — ID2,n CLASS

For collective objects (stars, galaxies, clusters):
\[
\text{ID2,n} = 2.0 + \log_{2.5} \left( \frac{N_{\text{cells}}}{N_{\text{proton}}} \right)
\]

| Object | ID2,n |
|--------|-------|
| Atom | ID2,0 |
| Molecule | ID2,1 |
| Star | ID2,2 |
| Star cluster | ID2,3 |
| Galaxy | ID2,4 |
| Galaxy cluster | ID2,5 |

---

## 4. ID TRANSITIONS — CONDITIONS AND TIME SCALE

Transition occurs when:
1. \( \rho_{\mathcal{V}} > \rho_{\text{krit}} \)
2. Next Qn layer is available
3. Modulations activate the transition

Transition time:
\[
t_{\text{transition}} \propto \frac{1}{\rho_{\mathcal{V}} - \rho_{\text{krit}}}
\]

Examples:

| Transition | From | To | Trigger process |
|------------|------|----|-----------------|
| ID2,0 → ID2,1 | Atom | Molecule | Chemical bond |
| ID2,1 → ID2,2 | Molecule | Star | Gravitational collapse |
| ID2,4 → ID2,5 | Galaxy | Galaxy cluster | Gravitational interaction |
| ID3,0 → ID3,1 | BH | AGN | Vertical overflow |

---

## 5. TESTABLE PREDICTIONS

| Prediction | Equation | Test method |
|------------|----------|-------------|
| ID dependence on \( \rho_{\mathcal{V}} \) | \( \text{ID} = 2.0 + \log_{2.5}(n) + 0.05 \rho_{\mathcal{V}}/\rho_{\text{H0}} \) | BH mass comparison |
| Transition time | \( t_{\text{transition}} \propto 1/(\rho_{\mathcal{V}} - \rho_{\text{krit}}) \) | AGN periodicity |
| ID2,n vs galaxy type | \( \text{ID2,n} = 2.0 + \log_{2.5}(N_{\text{stars}}/N_{\text{proton}}) \) | Galaxy morphology |
| Max ID3,n | \( n_{\text{max}} \propto \rho_{\mathcal{V}}^{(0)}/\rho_{\text{H0}} \) | Max BH mass |

---

## 6. COMPARISON WITH CLASSICAL HIERARCHY

| Classical | MT ID | Note |
|-----------|-------|------|
| Elementary particle | ID2,0 | Proton reference |
| Atom | ID2,0 | Proton + electron |
| Molecule | ID2,1 | Multiple atoms |
| Star | ID2,2 | Collective TE organization |
| Galaxy | ID2,4 | Highest collective |
| Black hole | ID3,0+ | Monolithic, finer than proton |

---

## 7. CONCLUSIONS

1. ID is a scalar field determined by \( n \) and \( \rho_{\mathcal{V}} \):
   \[
   \text{ID} = 2.0 + \log_{2.5}(n) + 0.05 \cdot \rho_{\mathcal{V}}/\rho_{\text{H0}}
   \]
2. ID steps are discrete, with \( S \approx 2.5 \).
3. Higher \( \rho_{\mathcal{V}} \) accelerates ID transitions.
4. Collective objects belong to ID2,n class, determined by organizational level.
5. ID transitions are quantifiable and testable.
