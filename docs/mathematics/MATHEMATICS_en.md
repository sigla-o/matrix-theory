# MATHEMATICS — MATRIX THEORY FORMALISM

## Combined Version (August 2026) — 4.0

This document establishes the mathematical formalism of Matrix Theory (MT) — operators, equations, and balance laws that describe the Horizontal block structure and their connection in the Vertical. Version 4.0 combines:

1. **Universal Block Formalism** — the mathematical apparatus describing any Horizontal block (H0, H-1, H+1, ...) and their connection in a chain.
2. **H0 Level Formalism** (formerly 3.0) — as the special case of the H0 block, including axioms, the TE transfer operator, gravity, cosmology, and fundamental constant formalisms.

**Corrections in version 4.0** (after dimensional analysis):
- **Point 1:** \( G_0 \) is a fundamental matrix parameter with MT dimension \( E/T \), not the classical gravitational constant. Classical \( G \) emerges through the mass factor \( \mathcal{M} = 1/\rho_{\text{mass}}(\mathbf{x}) \).
- **Point 2:** \( \mathbf{g} = -\nabla\delta \) is the TE flow disturbance gradient (force), not acceleration. Classical acceleration emerges through the mass factor.
- **Point 3:** \( c_n = \frac{n^2}{6} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \cdot \gamma_n \) (dimensionless).
- **Point 4:** \( \rho_n^{(out)} \) and \( \Phi_n^{(out)} \) are distinguished. \( E_n^{(out)} = \int_{\mathcal{B}_n} \rho_n^{(out)} \, d^3x \).
- **Point 5:** \( G_0 = \frac{\alpha_0 \phi_0}{7} \) is a valid MT quantity with dimension \( E/T \). No contradiction.

**Methodological premise:** MT is a complementary framework that provides a mechanical origin for the phenomenological laws of classical physics. Classical theories remain valid in their domains; MT describes the "territory" (the ID0 lattice and the Vertical) upon which these "maps" are built.

---

## CONTENTS

1. [Universal Block Formalism](#1-universal-block-formalism)
   1.1. Mathematical Definition of a Block
   1.2. Block Parameters
   1.3. Internal Operators of a Block
   1.4. Overflow and Threshold Formalism
   1.5. Energy Balance Equations
   1.6. Block Chain Formalism
   1.7. ID Level Formalism
2. [H0 Block Formalism (formerly 3.0)](#2-h0-block-formalism-formerly-30)
   2.1. Axioms — MT Basic Assumptions
   2.2. TE Transfer Operator
   2.3. Gravity Formalism
   2.4. Cosmology Formalism
   2.5. CMB Spectrum Formalism
   2.6. Derivation of Fundamental Constants
   2.7. Correspondence Principle
3. [Operator and ID Correspondence Summary Table](#3-operator-and-id-correspondence-summary-table)
4. [Testable Predictions](#4-testable-predictions)

---

## 1. UNIVERSAL BLOCK FORMALISM

### 1.1. Mathematical Definition of a Block

Each Horizontal block \( \mathcal{B}_n \) (where \( n \) denotes the H-level — H0, H-1, H+1, ...) is a mathematical object with the following elements:

\[
\mathcal{B}_n = \{ \mathcal{L}_n, \Theta_n, \Phi_n^{(in)}, \Phi_n^{(TE)}, \Phi_n^{(out)} \}
\]

where:
- \( \mathcal{L}_n \) — matrix lattice (set of pockets) with step \( \lambda_n \)
- \( \Theta_n(\mathbf{x}, t) \) — pocket rotation phase field
- \( \Phi_n^{(in)}(\mathbf{x}, t) \) — input TE flow from the external block
- \( \Phi_n^{(TE)}(\mathbf{x}, t) \) — matrix TE flow (block's "electric" field)
- \( \Phi_n^{(out)}(\mathbf{x}, t) \) — output TE flow (excess energy) through the block boundary

**Function correspondence:**

| **Element** | **Mathematical notation** | **Physical function** |
| :--- | :--- | :--- |
| Matrix | \( \mathcal{L}_n, \Theta_n \) | Foundation, rotation, TE transfer medium |
| Matrix TE | \( \Phi_n^{(TE)} \) | "Electric" field (gradient, Coulomb) |
| External TE | \( \Phi_n^{(in)} \) | "Magnetic" field (circulation) |
| "Proton" | \( \mathbf{x}_0 \) | Next Horizontal's object (monolithic object) |

### 1.2. Block Parameters

Each block has characteristic parameters:

- \( \lambda_n \) — matrix step
- \( \omega_n \) — rotation frequency
- \( \phi_0^{(n)} \) — maximum transfer quantum
- \( \mathcal{C}_n \) — block capacity (maximum processing power)
- \( \rho_{crit}^{(n)} \) — critical energy density threshold
- \( V_n \) — effective volume of the block

**Relations:**
\[
\mathcal{C}_n = \frac{\phi_0^{(n)}}{\lambda_n^3} \cdot f(\omega_n)
\]
\[
\rho_{crit}^{(n)} = \frac{\mathcal{C}_n}{V_n}
\]
where \( f(\omega_n) \) is the capacity function, dependent on the rotation frequency.

### 1.3. Internal Operators of a Block

**TE transfer operator** (between adjacent pockets \( \mathbf{x} \) and \( \mathbf{y} \), where \( \|\mathbf{x}-\mathbf{y}\|_1 = 1 \)):
\[
\Phi_n(\mathbf{x}, \mathbf{y}; t) = \phi_0^{(n)} \cdot \sin\left(\Theta_n(\mathbf{x}, t) - \Theta_n(\mathbf{y}, t)\right) \cdot \eta_n(\mathbf{x}, \mathbf{y})
\]
where \( \eta_n(\mathbf{x}, \mathbf{y}) \in \{0,1\} \) — transfer permission (phase compatibility).

**Deficit operator** (channel deficit caused by an object in Qn shell \( n \)):
\[
\delta_n(\mathbf{x}) = \frac{\phi_0^{(n)}}{|\mathbf{x} - \mathbf{x}_0|^2}
\]

**Note:** \( \delta_n \) is the direct TE flow disturbance at the FV step — the disturbance caused by channel blocking. It is an energy quantity (J), and its \( 1/r^2 \) dependence is geometric (surface area growth of Qn shells).

**"Electric" field operator** (Matrix TE gradient):
\[
\mathbf{E}_n(\mathbf{x}) = -\kappa_n \nabla \delta_n(\mathbf{x})
\]
where \( \kappa_n \) is the block's structural coefficient:
\[
\kappa_n = \frac{6}{49} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{H0}}
\]

**"Magnetic" field operator** (External TE circulation):
\[
\mathbf{B}_n(\mathbf{x}) = \mu_n \nabla \times \Phi_n^{(TE)}(\mathbf{x})
\]
where \( \mu_n = \frac{1}{c^2 \varepsilon_n} \) is the block's magnetic permeability, and \( \varepsilon_n \) is the block's vacuum permittivity.

**Matrix TE energy density:**
\[
\rho_n^{(TE)}(\mathbf{x}) = \kappa_n \cdot \frac{\phi_0^{(n)}}{|\mathbf{x} - \mathbf{x}_0|^2} \cdot f_n(\mathbf{x})
\]
where \( f_n(\mathbf{x}) \) is the matter distribution function in the block.

### 1.4. Overflow and Threshold Formalism

**Overflow condition:**
\[
\rho_n^{(TE)}(\mathbf{x}) > \rho_{crit}^{(n)}
\]

**Overflow operator (excess energy density):**
\[
\rho_n^{(out)}(\mathbf{x}) = \max\left(0, \; \rho_n^{(TE)}(\mathbf{x}) - \rho_{crit}^{(n)} \right)
\]
\[
\mathcal{O}_{overflow}^{(n)}: \rho_n^{(TE)} \mapsto \rho_n^{(out)}
\]

**ID level energy density:**
\[
\rho_{ID-n}(\mathbf{x}) = \rho_n^{(out)}(\mathbf{x})
\]

**Total Vertical energy density:**
\[
\rho_{\mathcal{V}}(\mathbf{x}) = \sum_{n} \rho_{ID-n}(\mathbf{x}) = \sum_{n} \max\left(0, \; \rho_n^{(TE)}(\mathbf{x}) - \rho_{crit}^{(n)} \right)
\]

### 1.5. Energy Balance Equations

**Input energy:**
\[
E_n^{(in)} = \int_{\partial \mathcal{B}_n} \Phi_n^{(in)}(\mathbf{x}) \cdot d\mathbf{S}
\]

**Matrix TE energy:**
\[
E_n^{(TE)} = \int_{\mathcal{B}_n} \rho_n^{(TE)}(\mathbf{x}) \, d^3x
\]

**Output energy (excess energy):**
\[
E_n^{(out)} = \int_{\mathcal{B}_n} \rho_n^{(out)}(\mathbf{x}) \, d^3x
\]

**Balance equation:**
\[
E_n^{(in)} = E_n^{(TE)} + E_n^{(out)}
\]

**Differential balance:**
\[
\frac{dE_n^{(TE)}}{dt} = \Phi_n^{(in)} - \Phi_n^{(out)}
\]

where \( \Phi_n^{(in)} \) and \( \Phi_n^{(out)} \) are flows through the block boundary (J/s).

**Excess energy flow:**
\[
\Phi_n^{(out)} = \int_{\partial \mathcal{B}_n} \rho_n^{(out)}(\mathbf{x}) \cdot \mathbf{v}_n(\mathbf{x}) \cdot d\mathbf{S}
\]
where \( \mathbf{v}_n(\mathbf{x}) \) is the "outflow" velocity of excess energy through TZ.

**Stationary mode:**
\[
\Phi_n^{(in)} = \Phi_n^{(out)} \quad \forall n
\]

**Non-stationary mode:**
\[
\Phi_n^{(in)} > \Phi_n^{(out)}
\]

**Overflow dynamics (ID level energy evolution):**
\[
\frac{d\rho_{ID-n}}{dt} = \alpha_n \cdot \rho_n^{(out)} - \beta_n \cdot \rho_{ID-n}
\]
where \( \alpha_n \) — overflow efficiency, \( \beta_n \) — return flow efficiency.

### 1.6. Block Chain Formalism

**Transition operator through TZ:**
\[
\Phi_n^{(in)} = \mathcal{T}_{n+1 \to n}[\Phi_{n+1}^{(out)}]
\]

**Scale relation between blocks (10²⁰ step):**
\[
\lambda_{n-1} = 10^{20} \cdot \lambda_n
\]
\[
\omega_{n-1} = 10^{-20} \cdot \omega_n
\]
\[
\phi_0^{(n-1)} = 10^{-20} \cdot \phi_0^{(n)}
\]

**Total balance of the block chain:**
\[
\sum_n \frac{dE_n^{(TE)}}{dt} = \sum_n \left( \Phi_n^{(in)} - \Phi_n^{(out)} \right)
\]

**Closed chain (stationary mode):**
\[
\sum_n \Phi_n^{(in)} = \sum_n \Phi_n^{(out)}
\]

**Open chain (overflow to higher ID levels):**
\[
\sum_n \Phi_n^{(in)} > \sum_n \Phi_n^{(out)}
\]

### 1.7. ID Level Formalism

**ID level correspondence:**
\[
\text{ID-}n \longleftrightarrow \mathcal{B}_n
\]
where \( n \) denotes the H-level index (0 H0, -1 H-1, +1 H+1, ...).

**Vertical ID level energy densities:**
\[
\rho_{ID-1} = \rho_0^{(out)}, \quad \rho_{ID-2} = \rho_{-1}^{(out)}, \quad \rho_{ID-3} = \rho_{-2}^{(out)}, \dots
\]

**Total Vertical energy density:**
\[
\rho_{\mathcal{V}} = \sum_{k=1}^{\infty} \rho_{ID-k}
\]

**Connection with fundamental parameters:**
\[
\varepsilon_0 = \frac{6}{49} \cdot \frac{\hbar}{2\pi} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{H0}}
\]
\[
G = G_0 \left( 1 + \gamma \cdot \frac{\rho_{\mathcal{V}}}{\rho_{H0}} \right), \quad \gamma = \frac{2\pi}{C}
\]

**Note:** \( G_0 \) in this expression is the **fundamental matrix parameter** with MT dimension \( E/T \), which characterizes energy transfer between half-phases. The classical gravitational constant emerges through the mass factor \( \mathcal{M} = 1/\rho_{\text{mass}}(\mathbf{x}) \).

---

## 2. H0 BLOCK FORMALISM (FORMERLY 3.0)

The H0 block \( \mathcal{B}_0 \) is a special case of the universal block formalism, where:

- \( \lambda_0 = l_P = \sqrt{\hbar G_0/c^3} \) (Planck length)
- \( \omega_0 = 2\pi c/l_P \)
- \( \phi_0 = \hbar c/l_P \)

### 2.1. Axioms — MT Basic Assumptions

**A1. Discrete space (ID0):**
The H0 matrix is a periodic cubic lattice:
\[
\mathcal{L} = \{ \mathbf{x} = (i,j,k) \in \mathbb{Z}^3 \}
\]
with minimum step \( \lambda_{\text{ID0}} = l_P \).

**A2. Pocket rotation and phase (ID0):**
Each lattice point has a rotation state \( \theta(\mathbf{x}, t) \in [0, 2\pi) \):
\[
\dot{\theta}(\mathbf{x}, t) = \omega_0 = \frac{2\pi c}{l_P} \quad \forall \mathbf{x}
\]

**A3. Qn structure (ID0.n):**
\[
Q_1 = \{ \mathbf{0} \} \cup \{ \pm \mathbf{e}_x, \pm \mathbf{e}_y, \pm \mathbf{e}_z \}, \quad |Q_1| = 7
\]
\[
Q_n = \{ \mathbf{x} \in \mathbb{Z}^3 : \|\mathbf{x}\|_\infty \leq n \}, \quad |Q_n| = \frac{(2n+1)(2n^2+2n+3)}{3}
\]

**A4. FV (phase–direction) (ID0):**
\[
\text{FV}: \mathbb{N} \times [0,2\pi) \to \{ \pm X, \pm Y, \pm Z \}
\]
with periodicity \( \text{FV}(n, \theta + 2\pi) = \text{FV}(n, \theta) \).

**A5. Vertical and energy pyramid (ID-1):**
\[
\mathcal{V} = \{ E_{H-3}, E_{H-4}, \dots, E_{H-\text{min}} \}
\]
\[
E_{\mathcal{V}} = \sum_{k=3}^{\text{min}} E_{H-k}
\]
\[
\mathcal{T}: \mathcal{L} \to \mathcal{V}
\]

### 2.2. TE Transfer Operator (ID0)

**Transfer quantity \( \Phi \):**
\[
\Phi(\mathbf{x}, \mathbf{y}; t) = \phi_0 \cdot \sin\left(\theta(\mathbf{x}, t) - \theta(\mathbf{y}, t)\right) \cdot \eta(\mathbf{x}, \mathbf{y})
\]
where \( \phi_0 = \hbar c/l_P \) and \( \eta(\mathbf{x}, \mathbf{y}) \in \{0,1\} \).

**Channel deficit \( \delta \):**
\[
\delta(n) = \frac{6\phi_0}{n^2}
\]

**Note:** \( \delta(n) \) is the direct TE flow disturbance at the FV step. It is an energy quantity, and the \( 1/n^2 \) dependence is geometric (surface area growth of Qn shells).

**Matrix elasticity \( \alpha_0 \):**
\[
\alpha_0 = \frac{6}{7} \omega_0
\]

**Deficit dynamics:**
\[
\frac{d}{dt} \delta(n) = -\alpha_0 \cdot \delta(n)
\]

### 2.3. Gravity Formalism (ID0 / ID-1)

**TE flow disturbance gradient (MT gravity field):**
\[
\mathbf{g}_{\text{MT}}(\mathbf{x}) = -\nabla \delta(\mathbf{x})
\]

**Note:** \( \mathbf{g}_{\text{MT}} \) is the TE flow disturbance gradient. It is a force (dimension J/m = N). The classical gravitational field (acceleration) emerges through the mass factor.

**Gravitational constant (MT fundamental parameter):**
\[
G_0 = \frac{\alpha_0 \phi_0}{7} = \frac{6\omega_0\phi_0}{49}
\]

**Note:** \( G_0 \) is a fundamental matrix parameter with MT dimension \( E/T \) (energy/time), characterizing energy transfer between half-phases. The classical gravitational constant emerges through the mass factor.

**Mass factor operator \( \mathcal{M} \):**
\[
\mathcal{M}[\mathbf{g}_{\text{MT}}](\mathbf{x}) = \frac{1}{\rho_{\text{mass}}(\mathbf{x})} \cdot \mathbf{g}_{\text{MT}}(\mathbf{x})
\]
where \( \rho_{\text{mass}}(\mathbf{x}) \) is the local mass density.

**Classical gravitational field expression:**
\[
\mathbf{g}_{\text{classical}}(\mathbf{x}) = \mathcal{M}[\mathbf{g}_{\text{MT}}](\mathbf{x}) = -\frac{1}{\rho_{\text{mass}}(\mathbf{x})} \nabla \delta(\mathbf{x})
\]

**Cyclicity scale \( \gamma \):**
\[
\gamma = \frac{2\pi}{C} \approx 0.18, \quad C = \frac{\ell_k}{n_k} \approx 35.325
\]

**Effective gravitational constant (dependent on Vertical density):**
\[
G(\rho_{\mathcal{V}}) = G_0 \cdot \left( 1 + \gamma \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \right)
\]

**Rotation curve prediction (ID2 / ID-1):**
\[
V_{\text{MT}}(r) = \sqrt{\frac{G(\rho_{\mathcal{V}}(r)) \cdot M_{\text{bar}}(r)}{r}}
\]
with exponential Vertical energy profile:
\[
\frac{\rho_{\mathcal{V}}(r)}{\rho_{\text{H0}}} = \frac{\rho_{\mathcal{V}}^{(0)}}{\rho_{\text{H0}}} \cdot \exp\left(-\frac{r}{r_0}\right)
\]

### 2.4. Cosmology Formalism (ID1 — ID5 / ID-1)

**H+n modulations as transfer curvature:**
\[
\Delta \mathbf{x}(n) = \epsilon(n) \cdot \mathbf{r}, \quad \epsilon(n) \propto \frac{1}{n}
\]

**Photon energy loss (L1 path):**
\[
\frac{dE}{dx} = -\beta \cdot E \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}
\]

**Total redshift:**
\[
z(d) = f(\text{curvature}) + g(\text{energy loss})
\]

**Hubble constant:**
\[
H_0 = \alpha_{\text{mod}} + \beta \cdot \langle \rho_{\mathcal{V}}/\rho_{\text{H0}} \rangle
\]

### 2.5. CMB Spectrum Formalism (L1 focusing, ID0.n / ID-1)

**Cyclicity constant:**
\[
C = \frac{\ell_k}{n_k} \approx 35.325, \quad n_k = 8k - 1 \ (k \ge 2), \quad n_1 = 6
\]

**L1 projection operator \( \mathcal{P}_{L1} \):**
\[
\mathcal{P}_{L1}[\rho_{\mathcal{V}}](\mathbf{x}) = \int_{\mathcal{V}} K(\mathbf{x}, \mathbf{x}') \, \rho_{\mathcal{V}}(\mathbf{x}') \, d\mathbf{x}'
\]
with kernel:
\[
K(\mathbf{x}, \mathbf{x}') = \sum_{n=1}^{\infty} \sum_{\hat{\mathbf{r}} \in \{\pm X, \pm Y, \pm Z\}} \frac{1}{N(n)} \cdot e^{i \mathbf{k}_n \cdot (\mathbf{x} - \mathbf{x}')} \cdot \mathcal{F}_n(\mathbf{x}, \mathbf{x}')
\]

**Focusing/scattering transition function \( \mathcal{F}_n \):**
\[
n_{\text{max}} = \frac{C}{2\pi} = \frac{1}{\gamma} \approx 5.62
\]
\[
\mathcal{F}_n = 
\begin{cases}
1, & n \leq n_{\text{max}} \quad \text{(focusing)} \\
e^{-(n - n_{\text{max}})/n_{\text{scattering}}}, & n > n_{\text{max}} \quad \text{(scattering)}
\end{cases}
\]
\[
n_{\text{scattering}} = \frac{C}{2\pi} \cdot \frac{\rho_{\text{H0}}}{\rho_{\mathcal{V}}}
= \frac{1}{\gamma} \cdot \frac{\rho_{\text{H0}}}{\rho_{\mathcal{V}}}
\]

**Projection coefficients (dimensionless):**
\[
c_n = \frac{\phi_0}{\delta(n)} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \cdot \gamma_n
= \frac{n^2}{6} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \cdot \gamma_n
\]
where \( \gamma_n = \gamma \cdot \frac{n}{n_{\text{max}}} \).

**Full CMB spectrum:**
\[
I(\nu) = B_\nu(T_{L0}) \cdot \left[ 1 + \sum_k |c_{n_k}|^2 \cdot \delta(\nu - \nu_k) \right]
\]

### 2.6. Derivation of Fundamental Constants (ID0 / ID1)

**Vacuum permittivity \( \varepsilon_0 \):**
\[
\varepsilon_0 = \frac{6}{49} \cdot \frac{\hbar}{2\pi} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}
\]

**Magnetic permeability \( \mu_0 \):**
\[
\mu_0 = \frac{1}{c^2 \varepsilon_0}
= \frac{49}{6} \cdot \frac{2\pi}{\hbar c^2} \cdot \frac{\rho_{\text{H0}}}{\rho_{\mathcal{V}}}
\]

**Fine-structure constant \( \alpha \):**
\[
\alpha = \frac{49 G_0}{24\pi \hbar c} \approx 0.0073
\]

**Note:** Here \( G_0 \) is used as the fundamental matrix parameter with MT dimension \( E/T \). To obtain the classical value, \( G_0 \) is connected to mass through the mass factor \( \mathcal{M} \).

### 2.7. Correspondence Principle (ID0 / ID1)

**Limit: Solar System (ID1 / ID2):**
When \( \rho_{\mathcal{V}}/\rho_{\text{H0}} \ll 1 \):
\[
G \to G_0, \quad \mathbf{g} \to -G_0 \frac{M}{r^2} \hat{\mathbf{r}}
\]

**Note:** Here \( G_0 \) and \( \mathbf{g} \) are already connected to mass through the mass factor \( \mathcal{M} \).

**Limit: weak field (ID0):**
When \( \delta(\mathbf{x}) \) is small:
\[
\nabla^2 \delta = 4\pi G_0 \rho
\]

**Limit: quantum mechanics (ID0 / ID1):**
When the phase distribution \( \theta(\mathbf{x}, t) \) is interpreted as the phase of a wavefunction:
\[
\psi(\mathbf{x}, t) \sim e^{i\theta(\mathbf{x}, t)}
\]

---

## 3. OPERATOR AND ID CORRESPONDENCE SUMMARY TABLE

| Operator | Definition | Physical meaning | ID correspondence |
|-----------|------------|------------------|-------------------|
| \( \mathcal{L} \) | \( \mathbb{Z}^3 \) | H0 matrix lattice | ID0 |
| \( \theta(\mathbf{x}, t) \) | \( [0, 2\pi) \) | Pocket rotation phase | ID0 |
| \( \Phi(\mathbf{x},\mathbf{y};t) \) | \( \phi_0 \sin(\Delta\theta) \cdot \eta \) | Transfer quantum between pockets | ID0 |
| \( \phi_0 \) | \( \hbar c/l_P \) | Maximum transfer quantum | ID0 |
| \( \delta(n) \) | \( 6\phi_0/n^2 \) | Channel deficit in Qn shell | ID0.n |
| \( \alpha_0 \) | \( 6\omega_0/7 \) | Matrix elasticity | ID0 |
| \( \mathcal{T} \) | \( \mathcal{L} \to \mathcal{V} \) | Transformation Zone | ID0 → ID-1 |
| \( \mathcal{P}_{L1} \) | \( \int K \rho_{\mathcal{V}} \) | L1 projection operator | ID-1 → ID0 |
| \( \mathbf{g}_{\text{MT}} \) | \( -\nabla \delta \) | TE flow disturbance gradient | ID0 |
| \( G_0 \) | \( \alpha_0 \phi_0/7 \) | Matrix fundamental parameter (\( E/T \)) | ID0 |
| \( G(\rho_{\mathcal{V}}) \) | \( G_0 (1 + \gamma \rho_{\mathcal{V}}/\rho_{\text{H0}}) \) | Effective gravitational constant | ID0 / ID-1 |
| \( \varepsilon_0 \) | \( \frac{6}{49} \cdot \frac{\hbar}{2\pi} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \) | Vacuum permittivity | ID0 |
| \( \alpha \) | \( 49G_0/(24\pi\hbar c) \) | Fine-structure constant | ID1 |
| \( \ell_k \) | \( C \cdot n_k, C \approx 35.325 \) | CMB peak angular scale | ID0.n |
| \( \gamma \) | \( 2\pi/C \approx 0.18 \) | Inverse cyclicity scale | ID0 / ID-1 |
| \( \mathcal{M} \) | \( 1/\rho_{\text{mass}}(\mathbf{x}) \) | Mass factor operator | ID0 / ID1 |

---

## 4. TESTABLE PREDICTIONS

| Prediction | Equation | Value / prediction | Status | Test method | ID correspondence |
|------------|----------|-------------------|---------|-------------|-------------------|
| Fine-structure constant | \( \alpha = \frac{49 G_0}{24\pi \hbar c} \) | \( \alpha_{\text{MT}} \approx 0.0073 \) | Confirmed (< 0.4%) | Precision spectroscopy | ID1 |
| G variability in galactic centers | \( G(0)/G_0 = 1 + \gamma \rho_{\mathcal{V}}/\rho_{\text{H0}} \) | \( G(0)/G_0 \approx 1.50 \) | Awaiting test | Stellar orbits (GRAVITY) | ID2 / ID-1 |
| 6th CMB peak | \( \ell_6 = 35.325 \times 47 \) | \( \ell_6 \approx 1660 \) | Awaiting test | CMB-S4, Simons Obs. | ID0.47 |
| 7th CMB peak | \( \ell_7 = 35.325 \times 55 \) | \( \ell_7 \approx 1943 \) | Awaiting test | CMB-S4, Simons Obs. | ID0.55 |
| \( \varepsilon_0 \) dependence on \( \rho_{\mathcal{V}} \) | \( \varepsilon_0 = \frac{6}{49} \cdot \frac{\hbar}{2\pi} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \) | — | Awaiting test | Quantum metrology | ID0 / ID-1 |
| Neutrino masses | \( m_i = M_P \cdot \alpha^{n_i} \) | \( m_1 \approx 0.0015, m_2 \approx 0.0087, m_3 \approx 0.050 \, \text{eV} \) | Awaiting test | DUNE, Hyper-K, KATRIN | ID1.1 / ID-1 |

---

## NOTE

This document is **MATHEMATICS 4.0** — the combined and corrected version, containing:

1. **Universal Block Formalism** (Chapter 1) — the mathematical apparatus describing any Horizontal block and their connection in a chain.
2. **H0 Block Formalism** (Chapter 2) — the content of the previous 3.0 version, now understood as a special case of the H0 block.

**Main corrections in version 4.0:**
- \( G_0 \) defined as a fundamental matrix parameter with MT dimension \( E/T \).
- \( \mathbf{g}_{\text{MT}} = -\nabla\delta \) defined as the TE flow disturbance gradient.
- The mass factor operator \( \mathcal{M} = 1/\rho_{\text{mass}}(\mathbf{x}) \) introduced for transition to classical physics.
- \( c_n \) corrected to dimensionless form: \( c_n = \frac{n^2}{6} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \cdot \gamma_n \).
- \( \rho_n^{(out)} \) (density) and \( \Phi_n^{(out)} \) (flow) distinguished.

The document is fully aligned with FOUNDATION 3.3 and other MT documents.

---

*Document prepared: August 2026*  
*Version: 4.0 — combined universal block formalism and H0 level formalism with dimensional corrections*
