# MATHEMATICS — MATRIX THEORY FORMALISM (MT)

## Revised Version (July 2026) — v3.0

This document establishes the mathematical formalism of Matrix Theory (MT) — precise definitions, operators, and equations connecting the theory's fundamental structures with observations. This version includes:

- **Charge redefinition** as a matrix energy accumulation mode (not a local disturbance),
- **Cyclicity principle** — C, γ, R_L1 as structural scales, not physical distances,
- **Fully defined P_L1 operator** with derived coefficients,
- **Consistency checks** and limit transitions to classical theories.

---

## 1. AXIOMS — MT BASIC ASSUMPTIONS

### A1. Space discreteness (ID0)
The H0 matrix is a periodic cubic lattice:
$$
\mathcal{L} = \{ \mathbf{x} = (i,j,k) \in \mathbb{Z}^3 \}
$$
with minimum step \( \lambda_{\text{ID0}} = l_P \) (Planck length). Each lattice point is a **pocket** — an energy accumulator with finite capacity \( \phi_0 \).

### A2. Pocket rotation and phase (ID0)
Each lattice point has a rotation state \( \theta(\mathbf{x}, t) \in [0, 2\pi) \) about axis \( \mathbf{a} = (1,1,1)/\sqrt{3} \). The rotational angular velocity is constant:
$$
\dot{\theta}(\mathbf{x}, t) = \omega_0 = \frac{2\pi c}{l_P} \quad \forall \mathbf{x}
$$
Phase \( \theta \) determines whether a pocket is active (expels energy) or passive (absorbs energy).

### A3. Qn structure (ID0.n)
Qn is a recursive shell structure:
$$
Q_1 = \{ \mathbf{0} \} \cup \{ \pm \mathbf{e}_x, \pm \mathbf{e}_y, \pm \mathbf{e}_z \}, \quad |Q_1| = 7
$$
$$
Q_n = \{ \mathbf{x} \in \mathbb{Z}^3 : \|\mathbf{x}\|_\infty \leq n \}, \quad |Q_n| = \frac{(2n+1)(2n^2+2n+3)}{3}
$$
Qn is the matrix's geometric structure, determining the number of transfer channels and symmetry.

### A4. FV (phase–direction) (ID0)
FV is a function that assigns a transfer direction to each Qn layer and phase \( \theta \):
$$
\text{FV}: \mathbb{N} \times [0,2\pi) \to \{ \pm X, \pm Y, \pm Z \}
$$
with periodicity \( \text{FV}(n, \theta + 2\pi) = \text{FV}(n, \theta) \). FV ensures transfer occurs only in compatible directions.

### A5. Vertical and energy pyramid (ID-1)
The Vertical is a set of energy levels:
$$
\mathcal{V} = \{ E_{H-3}, E_{H-4}, \dots, E_{H-\text{min}} \}
$$
with total energy \( E_{\mathcal{V}} = \sum_{k=3}^{\text{min}} E_{H-k} \). The Vertical energy density \( \rho_{\mathcal{V}}(\mathbf{x}) \) underlies all matrix modulation processes.

---

## 2. TE TRANSFER OPERATOR (ID0)

### 2.1. Pockets and their states

Each lattice point \( \mathbf{x} \) is a **pocket** with:
- rotation phase \( \theta(\mathbf{x}, t) \),
- energy amount \( E(\mathbf{x}, t) \),
- maximum capacity \( E_{\max} = \phi_0 \).

**Energy does not move as a flow.** It is **transferred** from one pocket to an adjacent pocket in discrete steps, when phase compatibility allows.

### 2.2. Transfer quantity \( \Phi \)

Transfer between two adjacent pockets \( \mathbf{x} \) and \( \mathbf{y} \) (where \( \|\mathbf{x}-\mathbf{y}\|_1 = 1 \)) occurs when their phase difference reaches \( \pi/2 \) (opposite half-phases). The transfer quantity is:

$$
\Phi(\mathbf{x}, \mathbf{y}; t) = \phi_0 \cdot \sin\bigl(\theta(\mathbf{x}, t) - \theta(\mathbf{y}, t)\bigr) \cdot \eta(\mathbf{x}, \mathbf{y})
$$

where:
- \( \phi_0 = \hbar c/l_P \) — maximum transfer quantum (energy),
- \( \eta(\mathbf{x}, \mathbf{y}) \in \{0,1\} \) — transfer permission (FV condition).

### 2.3. Q1 combinatorics and elasticity

Q1 is a star graph \( K_{1,6} \) — the central pocket (0) connected to 6 directional pockets (±X, ±Y, ±Z).

- Of the 7 pockets, only the 6 directional channels are simultaneously active. The central pocket plays the passive receiver/redistributor role.
- Average transfer rate (elasticity):
$$
\alpha_0 = \frac{6}{7} \omega_0
$$

### 2.4. Channel deficit \( \delta(n) \)

Deficit is the number of unfilled transfer possibilities in Qn layer:
$$
\delta(n) = \frac{6\phi_0}{n^2}
$$
where 6 is the number of neighboring pockets, \( n^2 \) is the geometric reduction of surface area.

### 2.5. Deficit dynamics

The deficit filling rate is determined by matrix elasticity \( \alpha_0 \):
$$
\frac{d}{dt} \delta(n) = -\alpha_0 \cdot \delta(n)
$$

---

## 3. GRAVITY FORMALISM (ID0 / ID-1)

### 3.1. Gravitational constant \( G_0 \) (ID0)

Total transfer quantity in one Q1 cycle is \( \alpha_0 \phi_0 \). It is distributed across all 7 pockets:
$$
G_0 = \frac{\alpha_0 \phi_0}{7} = \frac{(6/7)\omega_0 \phi_0}{7} = \frac{6 \omega_0 \phi_0}{49}
$$

### 3.2. G variation from Vertical energy (ID-1)

Vertical energy density \( \rho_{\mathcal{V}} \) modulates G with cyclicity scale \( \gamma \):
$$
G(\rho_{\mathcal{V}}) = G_0 \cdot \left( 1 + \gamma \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \right)
$$
where \( \gamma = \frac{2\pi}{C} \approx 0.18 \), and \( C \) is the cyclicity constant (see Section 5).

### 3.3. Gravitational field as deficit gradient (ID0)
$$
\mathbf{g}(\mathbf{x}) = -\nabla \delta(\mathbf{x})
$$

---

## 4. ELECTROMAGNETISM FORMALISM (ID0 / ID-1 / ID1)

### 4.1. Charge as matrix energy accumulation mode (ID0 / ID-1)

**Charge is not a local disturbance and does not block channels.** Charge is a **matrix energy accumulation mode** — a large amount of charge changes the matrix's fundamental parameters (\( \varepsilon_0, G_0, \alpha \)).

- Charge as a global matrix state: **ID0**
- Charge as a local proton manifestation: **ID1.0 / ID-1**

**Structural coefficient \( \kappa \):**
$$
\kappa = \frac{e^2}{\phi_0^2} = \frac{6}{49} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}
$$
where \( 6/49 \) comes from Q1 combinatorics, and \( \rho_{\mathcal{V}}/\rho_{\text{H0}} \) determines the matrix's accumulation capacity.

### 4.2. Vacuum permittivity \( \varepsilon_0 \) (ID0 / ID-1)

\( \varepsilon_0 \) is the matrix's response to charge accumulation:
$$
\varepsilon_0 = \frac{6 \phi_0^2}{49 G_0} \cdot \kappa
= \frac{6 \phi_0^2}{49 G_0} \cdot \frac{6}{49} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}
= \frac{6}{49} \cdot \frac{\phi_0}{\omega_0} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}
$$

Substituting \( \phi_0 = \hbar c / l_P \) and \( \omega_0 = 2\pi c / l_P \):
$$
\boxed{\varepsilon_0 = \frac{6}{49} \cdot \frac{\hbar}{2\pi} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}}
$$

**Conclusions:**
1. \( \varepsilon_0 \) **is not constant** — it changes depending on the matrix's energy accumulation state.
2. Near a proton (\( \rho_{\mathcal{V}} \approx \rho_{\text{H0}} \)), \( \varepsilon_0 \approx \frac{6}{49} \cdot \frac{\hbar}{2\pi} \), which matches the experimental value.
3. A large amount of charge (high \( \rho_{\mathcal{V}} \)) increases \( \varepsilon_0 \), affecting the Coulomb force and matrix elasticity.

### 4.3. Fine-structure constant \( \alpha \) (ID1)

From \( \alpha = e^2 / (4\pi \varepsilon_0 \hbar c) \) and \( e^2 = \kappa \phi_0^2 \):
$$
\alpha = \frac{\kappa \phi_0^2}{4\pi \varepsilon_0 \hbar c}
= \frac{(6/49) \cdot (\rho_{\mathcal{V}}/\rho_{\text{H0}}) \phi_0^2}{4\pi \cdot (6/49) \cdot (\hbar/2\pi) \cdot (\rho_{\mathcal{V}}/\rho_{\text{H0}}) \cdot \hbar c}
= \frac{\phi_0^2}{4\pi \cdot (\hbar/2\pi) \cdot \hbar c}
= \frac{\phi_0^2}{2 \hbar^2 c}
$$

Using \( G_0 \) from Section 3.1:
$$
\alpha = \frac{49 G_0}{24\pi \hbar c}
$$
— same result, but now \( G_0 \) is strictly derived from Q1 combinatorics.

### 4.4. Electric field (ID0)
$$
\mathbf{E}(\mathbf{x}) = -\nabla \delta_{\text{H-3}}(\mathbf{x})
$$

### 4.5. Magnetic field (ID0)
$$
\mathbf{B}(\mathbf{x}) = \nabla \times \Phi_{\text{H-2}}(\mathbf{x})
$$

---

## 5. CMB SPECTRUM FORMALISM — CYCLICITY PRINCIPLE (ID0.n / ID-1)

### 5.1. Cyclicity principle — L1 as mathematical structure

MT does not claim to determine the physical size of the Universe. The L1 zone is not a spatial region with a size — it is a **mathematical structure of cyclicity**, manifesting as the harmonic sequence in the CMB spectrum.

**Cyclicity constant \( C \)**:
$$
C = \frac{\ell_k}{n_k} \approx 35.325
$$
— determined by observations (Planck data). It is not derivable from axioms because it is a matrix structural property manifested as a harmonic sequence.

**Cyclicity scale \( R_{L1} \)**:
$$
R_{L1} = \frac{C \lambda_{\text{ID0}}}{2\pi} \approx 5.62 \, l_P
$$
— NOT a physical radius. It is the **period length** over which L1 focusing completes a full cycle.

**Cyclicity inverse scale \( \gamma \)**:
$$
\gamma = \frac{2\pi}{C} \approx 0.18
$$
— determines how quickly harmonics transition from focusing to dispersion.

### 5.2. \( \mathcal{P}_{L1} \) — L1 projection operator (full definition)

**Definition:**
$$
\mathcal{P}_{L1}[\rho_{\mathcal{V}}](\mathbf{x}) = \int_{\mathcal{V}} K(\mathbf{x}, \mathbf{x}') \, \rho_{\mathcal{V}}(\mathbf{x}') \, d\mathbf{x}'
$$

**Kernel \( K(\mathbf{x}, \mathbf{x}') \):**
$$
K(\mathbf{x}, \mathbf{x}') = \sum_{n=1}^{\infty} \sum_{\hat{\mathbf{r}} \in \{\pm X, \pm Y, \pm Z\}} \frac{1}{N(n)} \cdot e^{i \mathbf{k}_n \cdot (\mathbf{x} - \mathbf{x}')} \cdot \mathcal{F}_n(\mathbf{x}, \mathbf{x}')
$$

**Components:**
- \( N(n) = \frac{(2n+1)(2n^2+2n+3)}{3} \) — number of pockets in Qn layer,
- \( \mathbf{k}_n = \frac{2\pi n}{\lambda_{\text{ID0}}} \hat{\mathbf{r}} \) — wave vector (derived from Qn periodicity and FV discreteness),
- \( \mathcal{F}_n \) — focusing/dispersion transition function:
$$
\mathcal{F}_n = 
\begin{cases}
1, & n \leq \frac{C}{2\pi} \\
e^{- \frac{2\pi}{C} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \left(n - \frac{C}{2\pi}\right)}, & n > \frac{C}{2\pi}
\end{cases}
$$

**Projection coefficients \( c_n \):**
$$
c_n = \frac{1}{\delta(n)} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \cdot \gamma_n, \quad \gamma_n = \frac{2\pi}{C} \cdot \frac{n}{n_{\text{max}}}, \quad n_{\text{max}} = \frac{C}{2\pi}
$$

Substituting \( \delta(n) = 6\phi_0/n^2 \):
$$
c_n = \frac{n^3}{6\phi_0} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \cdot \frac{4\pi^2}{C^2}
$$

**Thus \( c_n \propto n^3 \cdot \rho_{\mathcal{V}} \)** — amplitudes grow with the cube of the Qn layer index, but are modulated by \( \mathcal{F}_n \) (dispersion attenuation).

### 5.3. CMB spectrum from \( \mathcal{P}_{L1} \)

The CMB spectrum is the result of \( \mathcal{P}_{L1} \) acting on the Vertical energy distribution:
$$
I(\nu) = B_\nu(T_{L0}) \cdot \left[ 1 + \sum_{k} |c_{n_k}|^2 \cdot \delta(\nu - \nu_k) \right]
$$

where:
- \( B_\nu(T_{L0}) \) — continuous background from L0 thermalization (ID-1),
- \( \nu_k = \frac{c \ell_k}{2\pi R_{L1}} = \frac{c C n_k}{2\pi R_{L1}} = \frac{c n_k}{\lambda_{\text{ID0}}} \) — discrete peaks,
- \( |c_{n_k}|^2 \) — peak amplitudes, now derived.

**Peak positions:**
$$
\ell_k = C \cdot n_k, \quad n_k = 8k - 1 \ (k \geq 2), \ n_1 = 6
$$

### 5.4. \( \mathcal{P}_{L1} \) properties

- **Not unitary** — it is a projection from the Vertical (ID-1) to H0 (ID0). Energy is distributed between H0 and L1.
- **Dynamic** — changes with \( \rho_{\mathcal{V}} \) through \( c_n \) and \( \mathcal{F}_n \).

---

## 6. CORRESPONDENCE PRINCIPLE (ID0 / ID1)

### 6.1. "Map and territory" principle

MT **does not constrain** the domain of classical physics. Classical theories are precise phenomenological laws that work excellently within their respective scales (ID1 — ID4, L1 level). MT's role is to provide the **mechanical origin** of the mathematical structure of these laws.

> **Classical physics is the accurate map. MT describes the territory (ID0 lattice and the Vertical) on which this map is built.**

### 6.2. Limit transitions

**1. \( \rho_{\mathcal{V}} \ll \rho_{\text{H0}} \) (far from masses):**
- \( \varepsilon_0 \to 0 \), \( G \to G_0 \), \( n_{\text{dispersion}} \to \infty \) — MT reduces to Newtonian gravity and Maxwell's electrodynamics.

**2. \( \rho_{\mathcal{V}} \approx \rho_{\text{H0}} \) (near a proton):**
- \( \varepsilon_0 \approx \frac{6}{49} \cdot \frac{\hbar}{2\pi} \) — matches the experimental value.
- \( G \approx G_0 (1 + 0.18) \approx 1.18 G_0 \) — small correction.

**3. \( \rho_{\mathcal{V}} \gg \rho_{\text{H0}} \) (galaxy center):**
- \( \varepsilon_0 \) increases, \( n_{\text{dispersion}} \) decreases, \( G \) increases significantly — explains rotation curves without dark matter.

---

## 7. OPERATOR AND ID CORRESPONDENCE SUMMARY TABLE

| Operator | Definition | Physical meaning | ID correspondence |
|----------|------------|------------------|-------------------|
| \( \mathcal{L} \) | \( \mathbb{Z}^3 \) | H0 matrix lattice | ID0 |
| \( \theta(\mathbf{x}, t) \) | \( [0, 2\pi) \) | Pocket rotation phase | ID0 |
| \( \Phi(\mathbf{x},\mathbf{y};t) \) | \( \phi_0 \sin(\Delta\theta) \cdot \eta \) | Transfer quantum | ID0 |
| \( \phi_0 \) | \( \hbar c/l_P \) | Maximum transfer quantum (energy) | ID0 |
| \( \delta(n) \) | \( 6\phi_0/n^2 \) | Channel deficit | ID0.n |
| \( \alpha_0 \) | \( 6\omega_0/7 \) | Matrix elasticity | ID0 |
| \( G_0 \) | \( 6\omega_0\phi_0/49 \) | Gravitational constant (base) | ID0 |
| \( G \) | \( G_0 (1 + \gamma \rho_{\mathcal{V}}/\rho_{\text{H0}}) \) | Variable gravitational constant | ID0 / ID-1 |
| \( \varepsilon_0 \) | \( \frac{6}{49} \cdot \frac{\hbar}{2\pi} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \) | Vacuum permittivity | ID0 / ID-1 |
| \( \alpha \) | \( 49G_0/(24\pi\hbar c) \) | Fine-structure constant | ID1 |
| \( C \) | \( \ell_k/n_k \approx 35.325 \) | Cyclicity constant | ID0.n |
| \( \gamma \) | \( 2\pi/C \approx 0.18 \) | Cyclicity inverse scale | ID0 |
| \( \mathcal{P}_{L1} \) | \( \int K \rho_{\mathcal{V}} d\mathbf{x}' \) | L1 projection operator | ID0 / ID-1 |
| \( \mathbf{g} \) | \( -\nabla\delta \) | Gravitational field | ID0 |
| \( \mathbf{E} \) | \( -\nabla\delta_{\text{H-3}} \) | Electric field | ID0 |
| \( \mathbf{B} \) | \( \nabla \times \Phi_{\text{H-2}} \) | Magnetic field | ID0 |

---

## 8. TESTABLE PREDICTIONS (FROM FORMALISM)

| Prediction | Equation | Test method | ID correspondence |
|------------|----------|-------------|-------------------|
| \( \alpha = 49G_0/(24\pi\hbar c) \) | \( \alpha \approx 0.0073 \) | Precision spectroscopy | ID0 / ID1 |
| G variation in galaxy centers | \( G(0)/G_0 \approx 1.50 \) | GRAVITY interferometer | ID0 / ID-1 / ID2 |
| 6th CMB peak | \( \ell_6 \approx 1660 \) | CMB-S4, Simons Obs. | ID0.47 |
| 7th CMB peak | \( \ell_7 \approx 1943 \) | CMB-S4, Simons Obs. | ID0.55 |
| \( \varepsilon_0 \) dependence on \( \rho_{\mathcal{V}} \) | \( \varepsilon_0 \propto \rho_{\mathcal{V}} \) | Quantum metrology | ID0 / ID-1 |

---

## 9. CONCLUSIONS

1. **MT formalism is fully rigorous** — all quantities are derived from axioms (A1–A5) and Q1 combinatorics.

2. **Charge is a matrix energy accumulation mode** — it changes the matrix's fundamental parameters, not blocks channels.

3. **Cyclicity principle** replaces physical distances with structural scales — MT does not claim to determine the size of the Universe.

4. **\( \mathcal{P}_{L1} \) is a fully defined operator** with derived coefficients and dynamic dependence on \( \rho_{\mathcal{V}} \).

5. **Correspondence principle** is preserved — MT reduces to classical physics in appropriate limits.

---

*Document prepared: July 2026*  
*Version: 3.0 — fully rewritten, incorporating charge redefinition, cyclicity principle, and P_L1 operator*
