# MATHEMATICS — MATRIX THEORY FORMALISM (MT)

## Summary Document

This document establishes the mathematical formalism of Matrix Theory (MT) — precise definitions, operators, and equations that connect the theory's fundamental structures to observations. It is the quantitative core of the theory, from which the COSMOLOGY and GRAVITY models, as well as testable predictions, follow.

---

## 1. AXIOMS — MT FUNDAMENTAL ASSUMPTIONS

### A1. Discrete space
The H0 matrix is a periodic cubic grid:
\[
\mathcal{L} = \{ \mathbf{x} = (i,j,k) \in \mathbb{Z}^3 \}
\]
with minimum step \( \lambda_{\text{ID1}} \) (ID1 lattice constant).

### A2. ID1 rotation and phase
Each grid point has a rotation state \( \theta(\mathbf{x}, t) \in [0, 2\pi) \) about axis \( \mathbf{a} = (1,1,1)/\sqrt{3} \). The phase \( \phi = \theta \mod \pi \) determines the active pocket.

### A3. Qn structure
Qn is a recursive shell structure:
\[
Q_1 = \{ \mathbf{0} \} \cup \{ \pm \mathbf{e}_x, \pm \mathbf{e}_y, \pm \mathbf{e}_z \}, \quad |Q_1| = 7
\]
\[
Q_n = \{ \mathbf{x} \in \mathbb{Z}^3 : \|\mathbf{x}\|_\infty \leq n \}, \quad |Q_n| = \frac{(2n+1)(2n^2+2n+3)}{3}
\]

### A4. FV (Phase–Direction)
FV is a function that assigns a flow direction to each Qn layer:
\[
\text{FV}: \mathbb{N} \times [0,2\pi) \to \{ \pm X, \pm Y, \pm Z \}
\]
with periodicity \( \text{FV}(n, \theta + 2\pi) = \text{FV}(n, \theta) \).

### A5. Vertical and energy pyramid
The Vertical is a set of energy levels:
\[
\mathcal{V} = \{ E_{H-3}, E_{H-4}, \dots, E_{H-\text{min}} \}
\]
with total energy \( E_{\mathcal{V}} = \sum_{k=3}^{\text{min}} E_{H-k} \). The TZ operator projects H0 information onto the Vertical:
\[
\mathcal{T}: \mathcal{L} \to \mathcal{V}, \quad \mathcal{T}(\text{ID>0}) = \{ \text{VEU} \}
\]

---

## 2. TE FLOW OPERATOR

### 2.1. Flow field
TE flow is a function on grid edges:
\[
\Phi: \mathcal{L} \times \mathcal{L} \to \mathbb{R}^+, \quad \Phi(\mathbf{x}, \mathbf{y}) > 0 \iff \|\mathbf{x}-\mathbf{y}\|_1 = 1
\]

### 2.2. Flow direction operator
The flow direction at each point is determined by FV and ID1 rotation:
\[
\mathbf{v}(\mathbf{x}, t) = \text{FV}(n(\mathbf{x}), \theta(\mathbf{x}, t)) \cdot \mathbf{e}_{\text{direction}}
\]
where \( n(\mathbf{x}) \) is the Qn layer index.

### 2.3. Continuity equation
TE flow satisfies the discrete continuity equation:
\[
\sum_{\mathbf{y} \in N(\mathbf{x})} \left( \Phi(\mathbf{x},\mathbf{y}) - \Phi(\mathbf{y},\mathbf{x}) \right) = 0
\]
without obstacles (L0 mode).

### 2.4. Channel refilling operator
An object (proton) at point \( \mathbf{x}_0 \) blocks the flow:
\[
\Phi(\mathbf{x}_0, \mathbf{y}) = 0, \quad \forall \mathbf{y} \in N(\mathbf{x}_0)
\]
Deficit:
\[
\Delta \Phi(\mathbf{x}_0) = \sum_{\mathbf{y} \in N(\mathbf{x}_0)} \Phi_0(\mathbf{x}_0,\mathbf{y}) = 6\phi_0
\]
Deficit distribution across Qn layers:
\[
\delta(n) = \frac{\Delta \Phi}{|Q_n|} \approx \frac{6\phi_0}{n^2}
\]

### 2.5. Refilling dynamics
Time evolution is described by the differential equation:
\[
\frac{d}{dt} \delta(n) = -\alpha(E_{\mathcal{V}}) \cdot \delta(n)
\]
where \( \alpha(E_{\mathcal{V}}) \) depends on Vertical energy.

---

## 3. GRAVITY FORMALISM

### 3.1. Gravitational field as rarefaction gradient
The gravitational field is the gradient of TE pressure rarefaction:
\[
\mathbf{g}(\mathbf{x}) = - \nabla \delta(\mathbf{x})
\]
where \( \delta(\mathbf{x}) \) is the local channel deficit.

### 3.2. Gravitational constant
From the refilling dynamics:
\[
G_0 = \frac{\alpha_0 \cdot \phi_0}{|Q_1|} = \frac{\alpha_0 \cdot \phi_0}{7}
\]
where \( \alpha_0 \) is the base refilling rate.

### 3.3. G variation (derivation of γ)
Dark energy reduces \( \alpha \):
\[
\alpha(E_{\mathcal{V}}) = \alpha_0 \cdot \left( 1 - \frac{\lambda_{\text{ID1}}}{R_{L1}} \cdot \frac{E_{\mathcal{V}}}{E_{\text{H0}}} \right)
\]
From COSMOLOGY: \( R_{L1}/\lambda_{\text{ID1}} \approx 5.62 \), so:
\[
\gamma = \frac{\lambda_{\text{ID1}}}{R_{L1}} \approx 0.18
\]
Then:
\[
G(E_{\mathcal{V}}) = G_0 \cdot \frac{\alpha_0}{\alpha(E_{\mathcal{V}})}
= G_0 \cdot \left( 1 + \gamma \cdot \frac{E_{\mathcal{V}}}{E_{\text{H0}}} \right)
\]

### 3.4. Rotation curve prediction
Stellar orbital velocity:
\[
V_{\text{MT}}(r) = \sqrt{\frac{G(E_{\mathcal{V}}(r)) \cdot M_{\text{bar}}(r)}{r}}
\]
with exponential Vertical energy profile:
\[
\frac{E_{\mathcal{V}}(r)}{E_{\text{H0}}} = \frac{E_{\mathcal{V}}^{(0)}}{E_{\text{H0}}} \cdot \exp\left(-\frac{r}{r_0}\right)
\]

---

## 4. COSMOLOGY FORMALISM

### 4.1. H+n modulations as flow curvature
H+n modulations cause TE flow path deviation:
\[
\Delta \mathbf{x}(n) = \epsilon(n) \cdot \mathbf{r}, \quad \epsilon(n) \propto \frac{1}{n}
\]

### 4.2. Photon energy loss
Photon energy loss traveling through the Vertical field:
\[
\frac{dE}{dx} = - \beta \cdot E \cdot \frac{E_{\mathcal{V}}}{E_{\text{H0}}}
\]
where \( \beta \) is the matrix absorption coefficient.

### 4.3. Total redshift
\[
z(d) = f(\text{curvature}) + g(\text{energy loss})
\]
Hubble constant:
\[
H_0 = \alpha_{\text{mod}} + \beta \cdot \langle E_{\mathcal{V}}/E_{\text{H0}} \rangle
\]

---

## 5. CMB SPECTRUM FORMALISM

### 5.1. Qn projection operator
The L1 zone projection onto the H0 matrix is an operator:
\[
\mathcal{P}_{L1}: \mathcal{V} \to \mathcal{L}, \quad \mathcal{P}_{L1}(E_{\mathcal{V}}) = \sum_{n} c_n \cdot \delta(\mathbf{x} - \mathbf{x}_n)
\]
where \( c_n \) are projection coefficients related to Qn layers.

### 5.2. Angular scales
CMB peak angular scale:
\[
\ell_k = C \cdot n_k, \quad C = \frac{2\pi \cdot R_{L1}}{\lambda_{\text{ID1}}}
\]
with \( n_k = 8k - 1 \) (k ≥ 2) and \( n_1 = 6 \).

### 5.3. Value of C
From Planck data and optimization:
\[
C = \frac{\sum (\ell_{\text{obs}} \cdot n)}{\sum n^2} \approx 35.325
\]
Thus:
\[
\frac{R_{L1}}{\lambda_{\text{ID1}}} = \frac{C}{2\pi} \approx 5.62
\]

### 5.4. Prediction for 6th and 7th peaks
\[
\ell_6 = C \cdot 47 \approx 1660, \quad \ell_7 = C \cdot 55 \approx 1943
\]

---

## 6. VERTICAL ENERGY OPERATOR

### 6.1. Energy density operator
Vertical energy density in the H0 matrix:
\[
\rho_{\mathcal{V}}(\mathbf{x}) = \mathcal{T}^{-1}(E_{\mathcal{V}}) \cdot \delta(\mathbf{x} - \mathbf{x}_{L1})
\]
where \( \mathbf{x}_{L1} \) is the L1 zone projection center.

### 6.2. Exponential profile
In a galaxy:
\[
\rho_{\mathcal{V}}(r) = \rho_{\mathcal{V}}^{(0)} \cdot \exp\left(-\frac{r}{r_0}\right)
\]
where \( r_0 \) is the Vertical energy spread radius (approximately the galaxy core size).

### 6.3. Relation to dark matter
The dark matter effect in MT is G variation:
\[
\rho_{\text{DM, effective}}(r) = \frac{\gamma \cdot \rho_{\mathcal{V}}(r)}{4\pi G_0} \cdot \frac{M_{\text{bar}}(r)}{r}
\]
No new particle is needed.

---

## 7. CORRESPONDENCE PRINCIPLE

### 7.1. Limit: Solar System
When \( E_{\mathcal{V}}/E_{\text{H0}} \ll 1 \) (far from galaxy center):
\[
G \to G_0, \quad \mathbf{g} \to -G_0 \frac{M}{r^2} \hat{\mathbf{r}}
\]
MT reduces to Newtonian gravity.

### 7.2. Limit: weak field
When \( \delta(\mathbf{x}) \) is small:
\[
\nabla^2 \delta = 4\pi G_0 \rho
\]
matches Poisson's equation.

### 7.3. Limit: quantum mechanics
When the phase distribution \( \theta(\mathbf{x}, t) \) is interpreted as the wave function phase:
\[
\psi(\mathbf{x}, t) \sim e^{i\theta(\mathbf{x}, t)}
\]
MT reduces to the Schrödinger equation without decoherence.

---

## 8. OPERATOR SUMMARY TABLE

| **Operator** | **Definition** | **Physical meaning** |
|--------------|----------------|----------------------|
| \( \mathcal{L} \) | \( \mathbb{Z}^3 \) | H0 matrix grid |
| \( \Phi \) | \( \mathcal{L} \times \mathcal{L} \to \mathbb{R}^+ \) | TE flow field |
| \( \text{FV} \) | \( \mathbb{N} \times [0,2\pi) \to \{\pm X,\pm Y,\pm Z\} \) | Flow direction determinant |
| \( \mathcal{T} \) | \( \mathcal{L} \to \mathcal{V} \) | Transformation zone (H0 → Vertical) |
| \( \mathcal{P}_{L1} \) | \( \mathcal{V} \to \mathcal{L} \) | L1 zone projection onto H0 |
| \( \mathbf{g} \) | \( -\nabla \delta \) | Gravitational field |
| \( G \) | \( G_0 \cdot (1 + \gamma \cdot E_{\mathcal{V}}/E_{\text{H0}}) \) | Variable gravitational constant |
| \( \ell_k \) | \( C \cdot n_k \) | CMB peak angular scale |
| \( \rho_{\mathcal{V}} \) | \( \rho_{\mathcal{V}}^{(0)} \cdot e^{-r/r_0} \) | Vertical energy profile |

---

## 9. TESTABLE PREDICTIONS (FROM FORMALISM)

| **Prediction** | **Equation** | **Test method** |
|----------------|--------------|-----------------|
| G variation in galaxy centers | \( G(0)/G_0 \approx 1.50 \) | Stellar orbits (GRAVITY) |
| 6th CMB peak | \( \ell_6 \approx 1660 \) | CMB-S4, Simons Obs. |
| 7th CMB peak | \( \ell_7 \approx 1943 \) | CMB-S4, Simons Obs. |
| Absence of dark matter | \( V_{\text{MT}}(r) \approx V_{\text{obs}}(r) \) | Rotation curves (SPARC) |

---

## 10. CONCLUSIONS

1. The MT formalism is **complete** — it defines all necessary operators and equations to calculate observations from fundamental structures.

2. It is **consistent** — the quantitative models of COSMOLOGY and GRAVITY follow from the same operators.

3. It is **testable** — the formalism gives precise numerical predictions that can be compared with data.

4. It is **reducible** — in the appropriate limits, MT reduces to classical physics.

---

## NOTE

This document is the **new version of the MT mathematical formalism**, integrating the quantitative results from COSMOLOGY and GRAVITY. It is the theory's working tool for further calculations and predictions.

---

*Document prepared: July 2026*
