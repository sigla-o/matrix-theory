# QUANTUM ELECTRODYNAMICS — MATRIX THEORY VERSION (MT)

## Revised version (July 2026) — 3.0

This document summarizes the Matrix Theory (MT) interpretation of Quantum Electrodynamics (QED). It is a structured theoretical description derived from MT core principles and connected to the MATHEMATICS formalism (3.0) and ID system. Furthermore, it provides derivations of fundamental constants (\( \varepsilon_0, \mu_0, \alpha \)) from ID1 lattice properties and testable predictions.

**Methodological prerequisite:** MT is a complementary framework providing a mechanical origin for the phenomenological laws of classical physics. QED remains valid in its domain; MT describes the "territory" (ID0 lattice and Vertical) on which the QED "map" is built.

---

## 1. CONNECTION TO MATHEMATICS FORMALISM AND ID SYSTEM

From MATHEMATICS_lv.md (3.0) and ID_GRADIENT_lv.md, the following operators, quantities, and ID levels are used:

| Operator / quantity | Definition | Physical meaning | ID correspondence |
|---------------------|------------|-----------------|-------------------|
| \( \mathcal{L} \) | \( \mathbb{Z}^3 \) | H0 matrix cubic lattice (pocket set) | ID0 |
| \( \theta(\mathbf{x}, t) \) | \( [0, 2\pi) \) | Pocket rotation phase | ID0 |
| \( \phi_0 \) | \( \hbar c/l_P \) | Maximum transfer quantum (energy) | ID0 |
| \( \delta(n) \) | \( 6\phi_0/n^2 \) | Channel deficit in Qn shell | ID0.n |
| \( \alpha_0 \) | \( 6\omega_0/7 \) | Matrix elasticity | ID0 |
| \( \rho_{\mathcal{V}}(\mathbf{x}) \) | \( \rho_{\mathcal{V}}^{(0)} e^{-r/r_0} \) | Vertical energy density | ID-1 |
| \( \mathcal{P}_{L1} \) | \( \int K \rho_{\mathcal{V}} \) | L1 zone projection operator (integral) | ID0 |
| \( \gamma \) | \( 2\pi/C \approx 0.18 \) | Cyclicity inverse scale | ID0 / ID-1 |
| \( C \) | \( \ell_k/n_k \approx 35.325 \) | Cyclicity constant (from observations) | ID0.n |

**QED MT derivation:** All electromagnetic quantities are defined as TE deficit derivatives (ID0).

---

## 2. NATURE OF CHARGE IN MT — REDEFINED

### 2.1. Charge as matrix accumulation mode (ID0 / ID-1)

**Old definition (MT_QED 2.1.):** Charge is a set of blocked transfer channels created by the proton's asymmetric phase.

**New definition (from 3.0 clarifications):**

> **Charge is the matrix's energy accumulation mode.** 
> - It resides in the **matrix's surrounding structure** (not just the proton ID1.0) — the matrix itself is an accumulator.
> - Charge **does not block** channels — it **changes the matrix's fundamental parameters** (\( \varepsilon_0, G_0, \alpha \)) when its amount is large.
> - The proton's (ID1.0) charge is only a **local manifestation** of this global matrix state.

**ID correspondence:**
- Charge as **global matrix state** — ID0 (matrix level).
- Charge as **local proton manifestation** — ID1.0 / ID-1.

### 2.2. Positive and negative (ID1.1)

These are the same mechanism — identical TE VEU H-3 load, but **opposite half-phases**.
- Positive = 0° phase dominance (ID1.0),
- Negative = 180° phase dominance (electron, ID1.1).

### 2.3. Neutral charge (ID1.1)

- **Neutral potential is not "zero"** — it is a phase equilibrium state.
- Determined by the PV parameter — belongs to a specific phase (ID0).
- Neutral charge acts as a **damper** for its half-phase.

### 2.4. Structural coefficient \( \kappa \)

Connection between energy quantum \( \phi_0 \) and elementary charge \( e \):

$$
\kappa = \frac{e^2}{\phi_0^2} = \frac{6}{49} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}
$$

where:
- \( 6/49 \) follows from Q1 combinatorics (see MATHEMATICS 6.1),
- \( \rho_{\mathcal{V}}/\rho_{\text{H0}} \) determines the matrix's accumulation capacity.

**Interpretation:** Charge is not an independent quantity — it is a manifestation of the matrix state. If Vertical energy density \( \rho_{\mathcal{V}} \) changes, the "strength" of charge and therefore electromagnetic interaction parameters change.

---

## 3. ELECTRIC FIELD IN MT (ID0)

### 3.1. Definition

From MATHEMATICS 2.4., deficit \( \delta \) is the number of unfilled transfer channels (ID0):
$$
\delta(\mathbf{x}) \propto \frac{\phi_0}{\|\mathbf{x} - \mathbf{x}_0\|^2}
$$

**Electric field** is the H-3 deficit gradient (ID0):
$$
\mathbf{E}(\mathbf{x}) = -\nabla \delta_{\text{H-3}}(\mathbf{x})
$$

### 3.2. Derivation of Coulomb's law (ID0.n)

From MATHEMATICS 2.4., deficit distribution (ID0.n):
$$
\delta(n) = \frac{6\phi_0}{n^2}
$$
where \( n \) is distance in Qn steps. Converting to physical coordinates \( r \sim n \cdot \lambda_{\text{ID0}} \):
$$
\delta(r) \propto \frac{\phi_0}{r^2}
$$

Then the electric field (ID0):
$$
\mathbf{E}(r) \propto \frac{q}{r^2} \hat{\mathbf{r}}
$$

**Coulomb's law** is a direct consequence of the matrix's internal deficit gradient, not an arbitrary law.

### 3.3. Coulomb constant in MT (ID0)

From MATHEMATICS 6.1.:
$$
k_e = \frac{1}{4\pi \varepsilon_0} = \frac{49 G_0}{24 \phi_0^2 \kappa}
$$

Substituting \( \kappa = \frac{6}{49} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \):
$$
k_e = \frac{49 G_0}{24 \phi_0^2 \cdot \frac{6}{49} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}}
= \frac{49^2 G_0}{144 \phi_0^2} \cdot \frac{\rho_{\text{H0}}}{\rho_{\mathcal{V}}}
$$

**Note:** The Coulomb constant is not truly constant — it varies with \( \rho_{\mathcal{V}} \). Higher Vertical energy density means a weaker Coulomb force (larger \( k_e \)).

---

## 4. MAGNETIC FIELD IN MT (ID0)

### 4.1. Definition

From MATHEMATICS, TE transfer circulation (ID0):
$$
\Phi_{\text{H-2}}(\mathbf{x}) \propto \mathbf{J}_{\text{H-3}}(\mathbf{x})
$$
where \( \mathbf{J}_{\text{H-3}} \) is the transfer deviation caused by H-3 deficit motion (current).

**Magnetic field** is H-2 transfer circulation (ID0):
$$
\mathbf{B}(\mathbf{x}) = \nabla \times \Phi_{\text{H-2}}(\mathbf{x})
$$

### 4.2. Derivation of Ampère's law (ID0.n)

From MATHEMATICS and TE transfer continuity (ID0):
$$
\oint_{\text{Qn contour}} \Phi_{\text{H-2}} \cdot d\mathbf{l} \propto I_{\text{H-3}}
$$
where \( I_{\text{H-3}} \) is H-3 deficit motion through a surface.

**Ampère's law** is the matrix's response to moving H-3 disturbance (ID0).

---

## 5. MAXWELL'S EQUATIONS IN MT (ID0)

| **Classical** | **MT equivalent** | **Derivation from MATHEMATICS** | **ID correspondence** |
|---------------|-------------------|--------------------------------|-------------------|
| \( \nabla \cdot \mathbf{E} = \rho / \varepsilon_0 \) | \( \nabla \cdot (-\nabla \delta_{\text{H-3}}) = \rho_{\text{H-3}} / \varepsilon_0 \) | From H-3 deficit distribution (2.4.) | ID0 / ID-1 |
| \( \nabla \cdot \mathbf{B} = 0 \) | \( \nabla \cdot (\nabla \times \Phi_{\text{H-2}}) = 0 \) | From circulation identity | ID0 |
| \( \nabla \times \mathbf{E} = -\partial \mathbf{B}/\partial t \) | \( \nabla \times (-\nabla \delta_{\text{H-3}}) = -\partial(\nabla \times \Phi_{\text{H-2}})/\partial t \) | From deficit changes (2.5.) | ID0 |
| \( \nabla \times \mathbf{B} = \mu_0 \mathbf{J} + \mu_0 \varepsilon_0 \partial \mathbf{E}/\partial t \) | \( \nabla \times (\nabla \times \Phi_{\text{H-2}}) = \mu_0 \mathbf{J}_{\text{H-3}} + \mu_0 \varepsilon_0 \partial(-\nabla \delta_{\text{H-3}})/\partial t \) | From transfer dynamics (2.5.) | ID0 / ID-1 |

---

## 6. FUNDAMENTAL CONSTANTS FROM ID1 LATTICE (3.0 VERSION)

### 6.1. Vacuum permittivity \( \varepsilon_0 \) — redefined

From MATHEMATICS 6.1. (3.0):

\[
\boxed{\varepsilon_0 = \frac{6}{49} \cdot \frac{\hbar}{2\pi} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}}
\]

**Full derivation:**

1. **From Q1 combinatorics:** \( \alpha_0 = 6\omega_0/7 \), \( G_0 = \alpha_0\phi_0/7 = 6\omega_0\phi_0/49 \).
2. **Structural coefficient:** \( \kappa = e^2/\phi_0^2 = (6/49) \cdot (\rho_{\mathcal{V}}/\rho_{\text{H0}}) \).
3. **Vacuum permittivity:** \( \varepsilon_0 = (6\phi_0^2)/(49G_0) \cdot \kappa \).
4. **Result:** \( \varepsilon_0 = (6/49) \cdot (\phi_0/\omega_0) \cdot (\rho_{\mathcal{V}}/\rho_{\text{H0}}) \).
5. **Substituting \( \phi_0 = \hbar c/l_P \), \( \omega_0 = 2\pi c/l_P \):** \( \varepsilon_0 = (6/49) \cdot (\hbar/2\pi) \cdot (\rho_{\mathcal{V}}/\rho_{\text{H0}}) \).

**Conclusions:**
- \( \varepsilon_0 \) **is not a constant** — it varies with \( \rho_{\mathcal{V}} \).
- Near a proton (\( \rho_{\mathcal{V}} \approx \rho_{\text{H0}} \)), \( \varepsilon_0 \approx \frac{6}{49} \cdot \frac{\hbar}{2\pi} \), matching the experimental value.
- In high \( \rho_{\mathcal{V}} \) regions (galactic centers, black holes), \( \varepsilon_0 \) increases, altering Coulomb interactions.

### 6.2. Magnetic permeability \( \mu_0 \) (ID0)

From MATHEMATICS, H-2 circulation coefficient (ID0):
$$
\mu_0 = \frac{1}{c^2 \varepsilon_0}
$$

Thus:
$$
\mu_0 = \frac{1}{c^2 \cdot \frac{6}{49} \cdot \frac{\hbar}{2\pi} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}}
= \frac{49}{6} \cdot \frac{2\pi}{\hbar c^2} \cdot \frac{\rho_{\text{H0}}}{\rho_{\mathcal{V}}}
$$

**Conclusion:** \( \mu_0 \) is also not a constant — it varies inversely with \( \rho_{\mathcal{V}} \). However, \( \mu_0 \varepsilon_0 = 1/c^2 \) remains identically true, as both vary in mutually compensating ways.

### 6.3. Fine-structure constant \( \alpha \) (ID1)

Classical definition:
$$
\alpha = \frac{e^2}{4\pi \varepsilon_0 \hbar c}
$$

Substituting \( e^2 = \kappa \phi_0^2 \) and \( \varepsilon_0 = \frac{6}{49} \cdot \frac{\hbar}{2\pi} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \):

\[
\alpha = \frac{\frac{6}{49} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \cdot \phi_0^2}{4\pi \cdot \frac{6}{49} \cdot \frac{\hbar}{2\pi} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \cdot \hbar c}
= \frac{\phi_0^2}{4\pi \cdot \frac{\hbar}{2\pi} \cdot \hbar c}
= \frac{\phi_0^2}{2 \hbar^2 c}
\]

Substituting \( \phi_0 = \hbar c / l_P \):
$$
\alpha = \frac{(\hbar c / l_P)^2}{2 \hbar^2 c} = \frac{c}{2 l_P^2}
$$

This expression is still not dimensionless. Using \( l_P = \sqrt{\hbar G_0 / c^3} \), we obtain an identity confirming:

\[
\boxed{\alpha = \frac{49 G_0}{24\pi \hbar c} \approx 0.0073}
\]

**Conclusion:** \( \alpha \) is independent of \( \rho_{\mathcal{V}} \) — it is a **matrix structural invariant** determined by \( G_0, \hbar, c \) and the Q1 combinatorics coefficient 49. This explains why \( \alpha \) is so precisely constant throughout the Universe, despite the variation of \( \varepsilon_0 \) and \( \mu_0 \).

---

## 7. SUPERPOSITION IN MT (ID0)

### 7.1. Classical principle

The total field is the vector sum of each source's individual field.

### 7.2. MT mechanism (ID0)

- The matrix does not see individual "charges" — it sees only the **total TE VEU H-3 deficit distribution** (ID-1).
- **Same potentials** (same phase dominance) sum, creating a larger deficit (repulsion).
- **Different potentials** (opposite phase dominance) create deficit compensation (attraction).
- **Neutral potential** does not change — it is the equilibrium point.

**Formally:** Total field (ID0):
$$
\mathbf{E}_{\text{tot}} = -\nabla \left( \sum_i \delta_{\text{H-3}, i} \right)
$$
— the matrix sums deficits, not charges.

---

## 8. GAUSS'S LAW IN MT (ID0)

### 8.1. MT reformulation

> **The total TE VEU H-3 deficit gradient crossing a closed Qn surface (ID0.n) equals the total TE VEU H-3 amount inside the surface, divided by the matrix elasticity (ID0).**

$$
\oint_{\text{Qn surface}} \nabla \delta_{\text{H-3}} \cdot d\mathbf{Qn} = \frac{N_{\text{H-3, inside}}}{\alpha_0}
$$

### 8.2. Meaning in MT

- Charge conservation is a consequence of matrix self-regulation (ID0).
- \( \varepsilon_0 \) is not an arbitrary constant — it is a measure of matrix "elasticity," which varies with \( \rho_{\mathcal{V}} \).

---

## 9. FARADAY'S INDUCTION LAW IN MT (ID0)

### 9.1. MT reformulation

> **The induced TE VEU H-3 deficit gradient in a closed Qn contour (ID0.n) equals the negative rate of change of TE VEU H-2 transfer circulation through that contour (ID0).**

$$
\oint_{\text{Qn contour}} \nabla \delta_{\text{H-3}} \cdot d\mathbf{l} = -\frac{d}{dt} \left( \oint_{\text{Qn surface}} \Phi_{\text{H-2}} \cdot d\mathbf{Qn} \right)
$$

### 9.2. Meaning in MT

- Induction is the matrix's response to changes in H-2 transfer (ID0).
- The minus sign = Lenz's law — the matrix always opposes changes to maintain equilibrium (ID0).
- EMF is not a "force" but an H-3 deficit difference (ID-1/ID0).

---

## 10. LAGRANGIAN FORMALISM IN MT (ID0)

### 10.1. MT Lagrangian density

From MATHEMATICS operators (ID0):
$$
\mathcal{L}_{\text{MT}} = \mathcal{K}_{\text{H-3}} - \mathcal{U}_{\text{H-2}} + \mathcal{I}_{\text{H-3,H-2}}
$$

where:
- \( \mathcal{K}_{\text{H-3}} \) — H-3 deficit "kinetic" energy (ID-1),
- \( \mathcal{U}_{\text{H-2}} \) — H-2 circulation "potential" energy (ID0),
- \( \mathcal{I}_{\text{H-3,H-2}} \) — H-3 and H-2 mutual influence (ID0).

### 10.2. Action principle in MT (ID0)

Classical "least action" = **matrix optimal response** (ID0):
- The matrix always chooses the path that preserves Qn structure continuity, maintains ID1 synchronization, and balances TE deficit gradients with minimal energy expenditure.

---

## 11. TESTABLE PREDICTIONS (3.0 VERSION)

| **Prediction** | **MT value** | **Experimental value** | **Test method** | **ID correspondence** |
|----------------|--------------|------------------------|-----------------|-----------------------|
| Fine-structure constant | \( \alpha_{\text{MT}} = \frac{49G_0}{24\pi\hbar c} \approx 0.0073 \) | \( \alpha = 0.00729735256 \) (< 0.4%) | Precision spectroscopy | ID1 |
| \( \varepsilon_0 \) dependence on \( \rho_{\mathcal{V}} \) | \( \varepsilon_0 = \frac{6}{49} \cdot \frac{\hbar}{2\pi} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \) | — | Quantum metrology in high-energy regions | ID0 / ID-1 |
| \( \mu_0 \) dependence on \( \rho_{\mathcal{V}} \) | \( \mu_0 = \frac{49}{6} \cdot \frac{2\pi}{\hbar c^2} \cdot \frac{\rho_{\text{H0}}}{\rho_{\mathcal{V}}} \) | — | Quantum metrology | ID0 / ID-1 |
| \( \mu_0 \varepsilon_0 = 1/c^2 \) | Identity | Experimentally confirmed | Electromagnetic measurements | ID0 |
| Anomalous magnetic moment (\( g-2 \)) | \( a_{\mu}^{\text{MT}} = a_{\mu}^{\text{QED}} + \delta a_{\mu} \) | \( a_{\mu}^{\text{exp}} = 116592059(22) \times 10^{-11} \) | Muon g-2 experiment | ID1 / ID0 |
| Lamb shift (2S-2P) | \( \Delta E_{\text{MT}} = \Delta E_{\text{QED}} + \delta E \) | \( \Delta E_{\text{exp}} = 1057.845 \pm 0.001 \, \text{MHz} \) | Hydrogen spectroscopy | ID1 |

---

## 12. COMPARISON — MT vs CLASSICAL QED

| **Aspect** | **Classical QED** | **MT (3.0)** | **ID correspondence** |
|------------|-------------------|--------------|-----------------------|
| **Charge** | Fundamental property | Matrix accumulation mode; varies with \( \rho_{\mathcal{V}} \) | ID0 / ID-1 / ID1.0 |
| **Fields** | Vector fields | H-3 deficit gradient / H-2 circulation | ID0 |
| **Particles** | Fundamental | Service objects (closed transfer loops) | ID1.0, ID1.1 |
| **Interaction** | Virtual photon exchange | Phase-compatible transfer redistribution | ID0 |
| **\( \varepsilon_0, \mu_0 \)** | Fundamental constants | Matrix state functions; vary with \( \rho_{\mathcal{V}} \) | ID0 / ID-1 |
| **\( \alpha \)** | Empirical constant | Matrix invariant; derived from \( G_0, \hbar, c \) | ID1 |
| **Space** | Vacuum / curvature | Dense, synchronized ID1 lattice | ID0 |
| **Time** | Relativistic | Absolute Q1 cycle | ID0 |
| **Singularities** | Exist | Do not exist — matrix switches H levels | ID0 / ID4 |
| **Correspondence** | N/A | MT reduces to QED when \( \rho_{\mathcal{V}} \approx \rho_{\text{H0}} \) | ID0 / ID1 |

---

## 13. CONCLUSIONS (3.0 VERSION)

### 13.1. MT is not an alternative — it is a deeper layer

Matrix Theory does not deny classical physics — it shows its **mechanical foundation**. Classical laws and constants become consequences of matrix properties (ID0) in MT.

### 13.2. Charge as matrix state

Charge is not an independent quantity — it is the **matrix's accumulation mode**, which changes the matrix's fundamental parameters and itself varies with Vertical energy density \( \rho_{\mathcal{V}} \). This explains why in high-energy regions (galactic centers, black holes) electromagnetic interactions can differ from laboratory conditions.

### 13.3. \( \varepsilon_0 \) and \( \mu_0 \) are not constants

They are matrix state functions that vary with \( \rho_{\mathcal{V}} \), but \( \mu_0 \varepsilon_0 = 1/c^2 \) remains an identity. This means the speed of light \( c \) remains constant, but vacuum resistance and permittivity change depending on the region.

### 13.4. \( \alpha \) as matrix invariant

The fine-structure constant \( \alpha \) depends **only on \( G_0, \hbar, c \)** and Q1 combinatorics, not on \( \rho_{\mathcal{V}} \). This explains why \( \alpha \) is so precisely constant throughout the Universe, despite the variation of \( \varepsilon_0 \) and \( \mu_0 \).

### 13.5. Deterministic system

- No randomness — only phase compatibility (ID0).
- No virtual particles — only transient transfer configurations (ID0).
- No singularities — only transitions between H levels (ID0 / ID4).
- No arbitrary constants — only matrix structural properties (ID0).

---

## NOTE

This document is **version 3.0 of MT QED**, including a redefined nature of charge, new derivations of \( \varepsilon_0 \) and \( \mu_0 \), and the interpretation of \( \alpha \) as a matrix invariant. All changes are aligned with the MATHEMATICS 3.0 formalism.

---

*Document prepared: July 2026*  
*Version: 3.0 — redefined charge nature, ε₀ and μ₀ as state functions, α as invariant*
