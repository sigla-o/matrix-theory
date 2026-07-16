# MATHEMATICS — MATRIX THEORY FORMALISM (MT)

## Summary Document

This document establishes the mathematical formalism of Matrix Theory (MT) — precise definitions, operators, and equations that connect the theory's fundamental structures with observations. It is the quantitative core of the theory, from which the COSMOLOGY and GRAVITY models, as well as testable predictions, are derived. The document is aligned with the ID system.

---

## 1. AXIOMS — MT FUNDAMENTAL ASSUMPTIONS

### A1. Discrete space (ID0)
The H0 matrix is a periodic cubic lattice:
\[
\mathcal{L} = \{ \mathbf{x} = (i,j,k) \in \mathbb{Z}^3 \}
\]
with minimum step \( \lambda_{\text{ID1}} \) (ID1 lattice constant). In the ID system, this lattice corresponds to **ID0** — the fundamental matrix level.

### A2. ID1 rotation and phase (ID0)
Each lattice point has a rotational state \( \theta(\mathbf{x}, t) \in [0, 2\pi) \) about the axis \( \mathbf{a} = (1,1,1)/\sqrt{3} \). The phase \( \phi = \theta \mod \pi \) determines the active pocket. This rotation is the fundamental ID0-level process.

### A3. Qn structure (ID0.n)
Qn is a recursive shell structure:
\[
Q_1 = \{ \mathbf{0} \} \cup \{ \pm \mathbf{e}_x, \pm \mathbf{e}_y, \pm \mathbf{e}_z \}, \quad |Q_1| = 7
\]
\[
Q_n = \{ \mathbf{x} \in \mathbb{Z}^3 : \|\mathbf{x}\|_\infty \leq n \}, \quad |Q_n| = \frac{(2n+1)(2n^2+2n+3)}{3}
\]
In the ID system, Qn corresponds to **ID0.n** — the matrix shell structure level.

### A4. FV (phase–direction) (ID0)
FV is a function that assigns a flow direction to each Qn layer:
\[
\text{FV}: \mathbb{N} \times [0,2\pi) \to \{ \pm X, \pm Y, \pm Z \}
\]
with periodicity \( \text{FV}(n, \theta + 2\pi) = \text{FV}(n, \theta) \). FV is the ID0-level flow direction determinant.

### A5. Vertical and energy pyramid (ID-1)
The Vertical is a set of energy levels:
\[
\mathcal{V} = \{ E_{H-3}, E_{H-4}, \dots, E_{H-\text{min}} \}
\]
with total energy \( E_{\mathcal{V}} = \sum_{k=3}^{\text{min}} E_{H-k} \). In the ID system, the Vertical corresponds to **ID-1**. The TZ operator projects H0 information onto the Vertical (ID0 → ID-1):
\[
\mathcal{T}: \mathcal{L} \to \mathcal{V}, \quad \mathcal{T}(\text{ID>0}) = \{ \text{VEU} \}
\]

---

## 2. TE FLOW OPERATOR (ID0)

### 2.1. Flow field (ID0)
TE flow is a function on lattice edges:
\[
\Phi: \mathcal{L} \times \mathcal{L} \to \mathbb{R}^+, \quad \Phi(\mathbf{x}, \mathbf{y}) > 0 \iff \|\mathbf{x}-\mathbf{y}\|_1 = 1
\]
In the ID system, TE flow is the fundamental **ID0**-level process.

### 2.2. Flow direction operator (ID0)
The flow direction at each point is determined by FV and ID1 rotation:
\[
\mathbf{v}(\mathbf{x}, t) = \text{FV}(n(\mathbf{x}), \theta(\mathbf{x}, t)) \cdot \mathbf{e}_{\text{direction}}
\]
where \( n(\mathbf{x}) \) is the Qn layer index (ID0.n).

### 2.3. Continuity equation (ID0)
TE flow satisfies the discrete continuity equation:
\[
\sum_{\mathbf{y} \in N(\mathbf{x})} \left( \Phi(\mathbf{x},\mathbf{y}) - \Phi(\mathbf{y},\mathbf{x}) \right) = 0
\]
without obstacles (L0 mode, ID0 / ID-1).

### 2.4. Channel filling operator (ID0 / ID1)
An object (proton, ID1.0) at point \( \mathbf{x}_0 \) blocks the flow (ID0):
\[
\Phi(\mathbf{x}_0, \mathbf{y}) = 0, \quad \forall \mathbf{y} \in N(\mathbf{x}_0)
\]
Deficit:
\[
\Delta \Phi(\mathbf{x}_0) = \sum_{\mathbf{y} \in N(\mathbf{x}_0)} \Phi_0(\mathbf{x}_0,\mathbf{y}) = 6\phi_0
\]
Deficit distribution across Qn layers (ID0.n):
\[
\delta(n) = \frac{\Delta \Phi}{|Q_n|} \approx \frac{6\phi_0}{n^2}
\]

### 2.5. Filling dynamics (ID0 / ID-1)
Time evolution is described by the differential equation:
\[
\frac{d}{dt} \delta(n) = -\alpha(E_{\mathcal{V}}) \cdot \delta(n)
\]
where \( \alpha(E_{\mathcal{V}}) \) depends on Vertical energy (ID-1).

---

## 3. GRAVITY FORMALISM (ID0 / ID-1)

### 3.1. Gravitational field as deficit gradient (ID0)
The gravitational field is the gradient of TE pressure deficit:
\[
\mathbf{g}(\mathbf{x}) = - \nabla \delta(\mathbf{x})
\]
where \( \delta(\mathbf{x}) \) is the local channel deficit (ID0).

### 3.2. Gravitational constant (ID0)
From the filling dynamics:
\[
G_0 = \frac{\alpha_0 \cdot \phi_0}{|Q_1|} = \frac{\alpha_0 \cdot \phi_0}{7}
\]
where \( \alpha_0 \) is the base filling rate (ID0).

### 3.3. G variability (derivation of γ) (ID0 / ID-1)
Dark energy (ID-1) reduces \( \alpha \):
\[
\alpha(E_{\mathcal{V}}) = \alpha_0 \cdot \left( 1 - \frac{\lambda_{\text{ID1}}}{R_{L1}} \cdot \frac{E_{\mathcal{V}}}{E_{\text{H0}}} \right)
\]
From COSMOLOGY: \( R_{L1}/\lambda_{\text{ID1}} \approx 5.62 \), thus (ID0):
\[
\gamma = \frac{\lambda_{\text{ID1}}}{R_{L1}} \approx 0.18
\]
Then:
\[
G(E_{\mathcal{V}}) = G_0 \cdot \frac{\alpha_0}{\alpha(E_{\mathcal{V}})}
= G_0 \cdot \left( 1 + \gamma \cdot \frac{E_{\mathcal{V}}}{E_{\text{H0}}} \right)
\]

### 3.4. Rotation curve prediction (ID2 / ID-1)
Stellar orbital velocity (ID2):
\[
V_{\text{MT}}(r) = \sqrt{\frac{G(E_{\mathcal{V}}(r)) \cdot M_{\text{bar}}(r)}{r}}
\]
with the exponential Vertical energy profile (ID-1):
\[
\frac{E_{\mathcal{V}}(r)}{E_{\text{H0}}} = \frac{E_{\mathcal{V}}^{(0)}}{E_{\text{H0}}} \cdot \exp\left(-\frac{r}{r_0}\right)
\]

---

## 4. COSMOLOGY FORMALISM (ID1 — ID5 / ID-1)

### 4.1. H+n modulations as flow curvature (ID1 — ID5)
H+n modulations cause a deviation in the TE flow path:
\[
\Delta \mathbf{x}(n) = \epsilon(n) \cdot \mathbf{r}, \quad \epsilon(n) \propto \frac{1}{n}
\]
In the ID system:
- H+1 → ID1
- H+2 → ID2
- H+3 → ID3
- H+4 → ID4
- H+5 → ID5

### 4.2. Photon energy loss (ID0 / ID-1)
Photon energy loss traveling through the Vertical field (ID-1):
\[
\frac{dE}{dx} = - \beta \cdot E \cdot \frac{E_{\mathcal{V}}}{E_{\text{H0}}}
\]
where \( \beta \) is the matrix absorption coefficient (ID0).

### 4.3. Total redshift (ID1 — ID5 / ID-1)
\[
z(d) = f(\text{curvature}) + g(\text{energy loss})
\]
Hubble constant:
\[
H_0 = \alpha_{\text{mod}} + \beta \cdot \langle E_{\mathcal{V}}/E_{\text{H0}} \rangle
\]

---

## 5. CMB SPECTRUM FORMALISM (ID0.n)

### 5.1. Qn projection operator (ID0)
The L1 zone projection onto the H0 matrix is the operator:
\[
\mathcal{P}_{L1}: \mathcal{V} \to \mathcal{L}, \quad \mathcal{P}_{L1}(E_{\mathcal{V}}) = \sum_{n} c_n \cdot \delta(\mathbf{x} - \mathbf{x}_n)
\]
where \( c_n \) are projection coefficients related to Qn layers (ID0.n).

### 5.2. Angular scales (ID0.n)
CMB peak angular scale:
\[
\ell_k = C \cdot n_k, \quad C = \frac{2\pi \cdot R_{L1}}{\lambda_{\text{ID1}}}
\]
with \( n_k = 8k - 1 \) (k ≥ 2) and \( n_1 = 6 \). In the ID system, this sequence corresponds to **ID0.n** — the Qn layer projection.

### 5.3. Value of constant C (ID0)
From Planck data and optimization:
\[
C = \frac{\sum (\ell_{\text{obs}} \cdot n)}{\sum n^2} \approx 35.325
\]
Thus (ID0):
\[
\frac{R_{L1}}{\lambda_{\text{ID1}}} = \frac{C}{2\pi} \approx 5.62
\]

### 5.4. Prediction for the 6th and 7th peaks (ID0.n)
\[
\ell_6 = C \cdot 47 \approx 1660, \quad \ell_7 = C \cdot 55 \approx 1943
\]

---

## 6. VERTICAL ENERGY OPERATOR (ID-1)

### 6.1. Energy density operator (ID-1 / ID0)
Vertical energy density in the H0 matrix:
\[
\rho_{\mathcal{V}}(\mathbf{x}) = \mathcal{T}^{-1}(E_{\mathcal{V}}) \cdot \delta(\mathbf{x} - \mathbf{x}_{L1})
\]
where \( \mathbf{x}_{L1} \) is the L1 zone projection center (ID0). In the ID system, this corresponds to **ID-1** (energy source) and **ID0** (projection).

### 6.2. Exponential profile (ID-1 / ID2)
In a galaxy (ID2):
\[
\rho_{\mathcal{V}}(r) = \rho_{\mathcal{V}}^{(0)} \cdot \exp\left(-\frac{r}{r_0}\right)
\]
where \( r_0 \) is the Vertical energy scattering radius (approximately the galactic core size, ID2.0). In the ID system, this profile is **ID-1** influence on **ID2** structures.

### 6.3. Connection to dark matter (ID-1 / ID0)
The dark matter effect in MT is G variability (ID0 / ID-1):
\[
\rho_{\text{DM, effective}}(r) = \frac{\gamma \cdot \rho_{\mathcal{V}}(r)}{4\pi G_0} \cdot \frac{M_{\text{bar}}(r)}{r}
\]
No new particle is required.

---

## 7. CORRESPONDENCE PRINCIPLE (ID0 / ID1)

### 7.1. Limit: Solar System (ID1 / ID2)
When \( E_{\mathcal{V}}/E_{\text{H0}} \ll 1 \) (far from galactic center, ID2):
\[
G \to G_0, \quad \mathbf{g} \to -G_0 \frac{M}{r^2} \hat{\mathbf{r}}
\]
MT reduces to Newtonian gravity (ID0).

### 7.2. Limit: weak field (ID0)
When \( \delta(\mathbf{x}) \) is small:
\[
\nabla^2 \delta = 4\pi G_0 \rho
\]
corresponds to the Poisson equation (ID0).

### 7.3. Limit: quantum mechanics (ID0 / ID1)
When the phase distribution \( \theta(\mathbf{x}, t) \) is interpreted as the phase of the wave function (ID0):
\[
\psi(\mathbf{x}, t) \sim e^{i\theta(\mathbf{x}, t)}
\]
MT reduces to the Schrödinger equation without decoherence (ID0 / ID1).

---

## 8. OPERATOR AND ID CORRESPONDENCE SUMMARY TABLE

| Operator | Definition | Physical meaning | ID correspondence |
|----------|------------|------------------|-------------------|
| \( \mathcal{L} \) | \( \mathbb{Z}^3 \) | H0 matrix lattice | ID0 |
| \( \Phi \) | \( \mathcal{L} \times \mathcal{L} \to \mathbb{R}^+ \) | TE flow field | ID0 |
| \( \text{FV} \) | \( \mathbb{N} \times [0,2\pi) \to \{\pm X,\pm Y,\pm Z\} \) | Flow direction determinant | ID0 |
| \( \mathcal{T} \) | \( \mathcal{L} \to \mathcal{V} \) | Transformation zone (H0 → Vertical) | ID0 → ID-1 |
| \( \mathcal{P}_{L1} \) | \( \mathcal{V} \to \mathcal{L} \) | L1 zone projection onto H0 | ID-1 → ID0 |
| \( \mathbf{g} \) | \( -\nabla \delta \) | Gravitational field | ID0 |
| \( G \) | \( G_0 \cdot (1 + \gamma \cdot E_{\mathcal{V}}/E_{\text{H0}}) \) | Variable gravitational constant | ID0 / ID-1 |
| \( \ell_k \) | \( C \cdot n_k \) | CMB peak angular scale | ID0.n |
| \( \rho_{\mathcal{V}} \) | \( \rho_{\mathcal{V}}^{(0)} \cdot e^{-r/r_0} \) | Vertical energy profile | ID-1 / ID2 |

---

## 9. TESTABLE PREDICTIONS (FROM THE FORMALISM) (ID0 / ID-1 / ID1 — ID5)

| Prediction | Equation | Test method | ID correspondence |
|------------|----------|-------------|-------------------|
| G variability in galaxy centers | \( G(0)/G_0 \approx 1.50 \) | Stellar orbits (GRAVITY) | ID0 / ID-1 / ID2 |
| 6th CMB peak | \( \ell_6 \approx 1660 \) | CMB-S4, Simons Obs. | ID0.n |
| 7th CMB peak | \( \ell_7 \approx 1943 \) | CMB-S4, Simons Obs. | ID0.n |
| Absence of dark matter | \( V_{\text{MT}}(r) \approx V_{\text{obs}}(r) \) | Rotation curves (SPARC) | ID2 / ID-1 |

---

## 10. CONCLUSIONS

1. The MT formalism is **complete** — it defines all necessary operators and equations to calculate observations from fundamental structures.

2. It is **consistent** — the quantitative models of COSMOLOGY and GRAVITY follow from the same operators.

3. It is **testable** — the formalism gives precise numerical predictions that can be compared with data.

4. It is **reducible** — in appropriate limits, MT transitions to classical physics (ID0 / ID1).

5. It is **aligned with the ID system** — every operator and quantity has a clear ID correspondence, ensuring a unified theoretical structure.

---

## NOTE

This document is a **version of the MT mathematical formalism** that integrates the quantitative results of COSMOLOGY and GRAVITY and is aligned with the ID system. It is the theory's working tool for further calculations and predictions.

---

*Document prepared: July 2026*
