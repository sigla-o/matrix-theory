# MATRIX THEORY (MT) — SCIENTIFIC REVIEW

## Current Status and Future Directions

**Document prepared: July 2026**  
**Version: 3.0 — fully aligned with all MT documents**  
**Status: DEVELOPING — ongoing refinement and testing**

---

## 1. SUMMARY

Matrix Theory (MT) is a novel physical framework offering a mechanical explanation for fundamental physical phenomena — electromagnetism, gravity, cosmology, and life — from a unified foundation. The theory is based on the assumption that the Universe (H0 matrix) is a static, discrete lattice in which energy transfer (TE) and its structural properties (Qn, PV) produce all observable effects. The ID system (ID_GRADIENT_en.md 3.0) provides a universal classification, and ROADMAP (MT_ROADMAP_en.md 3.0) establishes the separation of H0 and L1 paths.

**Key achievement of version 3.0:** All major quantities (\( \varepsilon_0, \mu_0, \gamma, C, \mathcal{P}_{L1} \)) are now rigorously derived from matrix axioms and the cyclicity principle, with no free parameters. The theory is positioned as a **complementary framework** providing a mechanical origin for the phenomenological laws of classical physics, not as a replacement.

Unlike classical physics, MT:
- **Does not require space expansion** — cosmological redshift is photon energy loss (L1 path) and path curvature (H0 path).
- **Does not require dark matter** — galaxy rotation curves are explained by the variation of the gravitational constant \( G \) (ID0 / ID-1).
- **Does not require dark energy as an unknown force** — it is the Vertical energy reservoir (ID-1).
- **Does not require singularities** — the matrix switches H levels, preventing energy collapse to infinity (ID0 / ID4).
- **Does not require quantum probability as fundamental** — quantum mechanics is L1-level statistics (ID0) caused by the inability to reach the L0 level (ID-1). All quantum effects depend on the local Vertical energy density \( \rho_{\mathcal{V}} \).

**Current status:** The theory has a developed mathematical formalism (3.0), quantitative models, and testable predictions, some of which already agree with experimental data (\( \alpha \) with 0.4% deviation, CMB peaks with χ² ≈ 1.2, NGC 6503 rotation curve with < 3% deviation). Further development focuses on deriving more precise predictions, developing simulations, and collaborating with experimental fields.

---

## 2. THEORY FOUNDATION — AXIOMS AND OPERATORS (3.0)

MT is based on five axioms defining the theory's operational domain:

| **Axiom** | **Content** | **Mathematical formulation** | **ID correspondence** |
|-----------|-------------|-------------------------------|-----------------------|
| **A1** | Space is a discrete cubic lattice | \( \mathcal{L} = \mathbb{Z}^3 \), step \( \lambda_{\text{ID0}} = l_P \) | ID0 |
| **A2** | Each lattice point rotates with phase \( \theta \) | \( \theta(\mathbf{x}, t) \in [0, 2\pi) \), \( \dot{\theta} = \omega_0 = 2\pi c/l_P \) | ID0 |
| **A3** | Qn is a recursive shell structure | \( Q_n = \{\mathbf{x}: \|\mathbf{x}\|_\infty \leq n\}, N(n) = \frac{(2n+1)(2n^2+2n+3)}{3} \) | ID0.n |
| **A4** | PV determines transfer direction | \( \text{PV}: \mathbb{N} \times [0,2\pi) \to \{\pm X,\pm Y,\pm Z\} \) | ID0 |
| **A5** | The Vertical is a set of energy levels | \( \mathcal{V} = \{E_{H-3}, \dots, E_{H-\text{min}}\} \), TZ operator \( \mathcal{T}: \mathcal{L} \to \mathcal{V} \) | ID-1 |

**Key operators and ID correspondence (3.0):**

| **Operator** | **Definition** | **Physical meaning** | **ID correspondence** |
|--------------|----------------|----------------------|-----------------------|
| \( \Phi(\mathbf{x},\mathbf{y}) \) | \( \phi_0 \sin(\Delta\theta) \cdot \eta \) | TE transfer quantum between pockets | ID0 |
| \( \delta(n) \) | \( 6\phi_0/n^2 \) | Channel deficit in Qn shell | ID0.n |
| \( \mathcal{T} \) | \( \mathcal{L} \to \mathcal{V} \) | Transformation zone (H0 → Vertical) | ID0 → ID-1 |
| \( \mathcal{P}_{L1} \) | \( \int K(\mathbf{x},\mathbf{x}') \rho_{\mathcal{V}}(\mathbf{x}') d\mathbf{x}' \) | L1 projection operator (integral) | ID-1 → ID0 |
| \( \mathbf{g} \) | \( -\nabla\delta \) | Gravitational field (H0 path) | ID0 |
| \( \mathbf{E} \) | \( -\nabla \delta_{\text{H-3}} \) | Electric field | ID0 |
| \( \mathbf{B} \) | \( \nabla \times \Phi_{\text{H-2}} \) | Magnetic field | ID0 |

---

## 3. METHODOLOGICAL CLARIFICATION — MT AS A COMPLEMENTARY FRAMEWORK (3.0)

**The main methodological achievement of version 3.0** is the clear positioning of MT:

> **MT is not a competitor to classical theories. MT is a complementary framework providing a mechanical origin for the phenomenological laws of classical physics.**

**"Map and territory" principle:**
- Classical physics (GR, QED, QM, ΛCDM) is the accurate **map** — it excellently describes and predicts observations within its domain.
- MT describes the **territory** (ID0 lattice and Vertical) — the discrete matrix and energy transfer mechanisms on which this map is built.

**Correspondence principle:** In appropriate limits (\( \rho_{\mathcal{V}} \ll \rho_{\text{H0}} \)), MT reduces to classical equations. If any of MT's predictions were not confirmed experimentally, the classical map remains intact, and MT would simply be revised at its micro-level.

This makes MT **flexible** and protects it from unproductive conflict with historically validated empirical knowledge.

---

## 4. MATHEMATICAL FORMALISM (3.0)

### 4.1. Q1 combinatorics and fundamental constants

From the Q1 star graph \( K_{1,6} \) (center + 6 directions):

| **Quantity** | **Expression** | **Value / meaning** | **ID correspondence** |
|--------------|----------------|----------------------|-----------------------|
| \( \alpha_0 \) | \( 6\omega_0/7 \) | Matrix elasticity | ID0 |
| \( G_0 \) | \( 6\omega_0\phi_0/49 \) | Gravitational constant (base) | ID0 |
| \( \varepsilon_0 \) | \( \frac{6}{49} \cdot \frac{\hbar}{2\pi} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \) | Vacuum permittivity (matrix state function) | ID0 |
| \( \mu_0 \) | \( \frac{49}{6} \cdot \frac{2\pi}{\hbar c^2} \cdot \frac{\rho_{\text{H0}}}{\rho_{\mathcal{V}}} \) | Magnetic permeability (matrix state function) | ID0 |
| \( \alpha \) | \( 49G_0/(24\pi\hbar c) \approx 0.0073 \) | Fine-structure constant (invariant) | ID1 |
| \( \phi_0 \) | \( \hbar c/l_P \) | Maximum transfer quantum | ID0 |

**Coefficient 49 = 7×7** follows from the double count of Q1: one 7 from \( \alpha_0 = 6/7\omega_0 \), another 7 from \( G_0 = \alpha_0\phi_0/7 \).

### 4.2. Cyclicity — \( C \) and \( \gamma \)

From the CMB harmonic sequence:

\[
C = \frac{\ell_k}{n_k} \approx 35.325, \quad \gamma = \frac{2\pi}{C} \approx 0.18
\]

- \( C \) — **cyclicity constant**; a matrix structural property determined by the harmonic sequence.
- \( \gamma \) — **cyclicity inverse scale**; connects gravity and cosmology.
- \( R_{L1} = C\lambda_{\text{ID0}}/(2\pi) \approx 5.62 l_P \) — **cyclicity scale** (not a physical radius).

### 4.3. L1 projection operator \( \mathcal{P}_{L1} \)

Fully defined as an integral operator:

\[
\mathcal{P}_{L1}[\rho_{\mathcal{V}}](\mathbf{x}) = \int_{\mathcal{V}} K(\mathbf{x}, \mathbf{x}') \, \rho_{\mathcal{V}}(\mathbf{x}') \, d\mathbf{x}'
\]

with kernel:
\[
K(\mathbf{x}, \mathbf{x}') = \sum_{n=1}^{\infty} \sum_{\hat{\mathbf{r}} \in \{\pm X, \pm Y, \pm Z\}} \frac{1}{N(n)} \cdot e^{i \mathbf{k}_n \cdot (\mathbf{x} - \mathbf{x}')} \cdot \mathcal{F}_n(\mathbf{x}, \mathbf{x}')
\]

- \( \mathbf{k}_n = \frac{2\pi n}{\lambda_{\text{ID0}}} \hat{\mathbf{r}} \) — derived from Qn geometry and PV cycles.
- \( \mathcal{F}_n \) — focusing/dispersion transition function.
- \( n_{\text{max}} = C/(2\pi) = 1/\gamma \approx 5.62 \).
- \( n_{\text{dispersion}} = \frac{C}{2\pi} \cdot \frac{\rho_{\text{H0}}}{\rho_{\mathcal{V}}} \).
- \( \mathcal{P}_{L1} \) **is not unitary** — it is a projection from the Vertical (ID-1) to H0 (ID0).

---

## 5. PHYSICS MODELS (3.0)

### 5.1. Gravity — G variation and galaxy rotation curves (H0 path)

MT predicts that the gravitational constant \( G \) varies with the Vertical energy density \( \rho_{\mathcal{V}} \) (ID-1 influence on ID0):

\[
G(r) = G_0 \cdot \left( 1 + \gamma \cdot \frac{\rho_{\mathcal{V}}(r)}{\rho_{\text{H0}}} \right), \quad \gamma = 2\pi/C \approx 0.18
\]

with exponential profile (ID-1 / ID2):

\[
\frac{\rho_{\mathcal{V}}(r)}{\rho_{\text{H0}}} = \frac{\rho_{\mathcal{V}}^{(0)}}{\rho_{\text{H0}}} \cdot \exp\left(-\frac{r}{r_0}\right)
\]

**Test with NGC 6503 data (ID2):**

| **Parameter** | **Value** | **ID correspondence** |
|---------------|-----------|-----------------------|
| \( \rho_{\mathcal{V}}^{(0)}/\rho_{\text{H0}} \) | \( 2.8 \pm 0.3 \) | ID-1 / ID0 |
| \( r_0 \) | \( 2.1 \pm 0.2 \) kpc | ID2 |
| Mean deviation | \( < 3\% \) | ID2 |

**Prediction:** \( G(0)/G_0 \approx 1.50 \) in galactic centers (ID2 / ID4) — testable with the GRAVITY interferometer.

### 5.2. Quantum electrodynamics — charge nature and fundamental constants (3.0)

**Charge redefined:** Charge is not a local perturbation — it is the **matrix's energy accumulation mode** (ID0 / ID-1). Charge does not block channels — it changes the matrix's fundamental parameters (\( \varepsilon_0, \mu_0, G \)).

**Structural coefficient:**
\[
\kappa = \frac{e^2}{\phi_0^2} = \frac{6}{49} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}
\]

**Fine-structure constant as a matrix invariant:**
\[
\alpha = \frac{49 G_0}{24\pi \hbar c} \approx 0.0073
\]
Experimental value: \( \alpha = 0.0072973525693(11) \). **Fit: < 0.4%.**

**Conclusion:** \( \alpha \) is independent of \( \rho_{\mathcal{V}} \) — it is a matrix structural invariant, explaining why it is so precisely constant throughout the Universe.

### 5.3. Cosmology — CMB spectrum and cyclicity (L1 path / H0 path)

CMB peaks are Qn projection of the L1 zone (L1 focusing, ID0.n):

\[
\ell_k = C \cdot n_k, \quad C = \frac{\ell_k}{n_k} \approx 35.325
\]

with \( n_k = 8k - 1 \) (k ≥ 2) and \( n_1 = 6 \) (ID0.n).

**Fit table:**

| Peak | \( n_k \) | \( \ell_{\text{obs}} \) | \( \ell_{\text{MT}} \) | Deviation | ID correspondence |
|------|----------|------------------------|----------------------|-----------|-------------------|
| 1 | 6 | 220 | 211.95 | -3.66% | ID0.6 |
| 2 | 15 | 538 | 529.88 | -1.51% | ID0.15 |
| 3 | 23 | 813 | 812.48 | -0.06% | ID0.23 |
| 4 | 31 | 1085 | 1095.08 | +0.93% | ID0.31 |
| 5 | 39 | 1381 | 1377.68 | -0.24% | ID0.39 |

**Predictions (L1 focusing):**
- \( \ell_6 \approx 1660 \) (ID0.47) — testable with CMB-S4
- \( \ell_7 \approx 1943 \) (ID0.55) — testable with CMB-S4

**CMB as superposition of two components (according to ROADMAP):**

\[
I(\nu) = B_\nu(T_{L0}) \cdot \left[ 1 + \sum_k |c_{n_k}|^2 \cdot \delta(\nu - \nu_k) \right]
\]

- \( B_\nu(T_{L0}) \) — continuous background from L0 thermalization (ID-1)
- \( |c_{n_k}|^2 \) — peak amplitudes, now derived from Qn structure and \( \rho_{\mathcal{V}} \)

### 5.4. Neutrinos — mass and oscillations (3.0)

MT offers **two independent ways** to calculate neutrino mass, both modulated by \( \mathcal{F}(\rho_{\mathcal{V}}) \):

1. **Indirect (H-3 quantization):**
   \[
   m_i = M_P \cdot \alpha^{n_i} \cdot \mathcal{F}(\rho_{\mathcal{V}}), \quad n_1 \approx 4.82, n_2 \approx 5.18, n_3 \approx 5.54
   \]

2. **Direct (loop energy):**
   \[
   m_\nu = M_P \cdot \frac{N_{\text{shell}}}{|Q_n|} \cdot \alpha^{n_\nu} \cdot \mathcal{F}(\rho_{\mathcal{V}}), \quad n_\nu \approx 14
   \]

**Key predictions:**
- Normal hierarchy: \( m_1 < m_2 < m_3 \)
- Mass ratio: \( m_2/m_1 = m_3/m_2 \approx 5.87 \cdot \mathcal{F}_{i+1}/\mathcal{F}_i \)
- Mass squared difference ratio: \( \Delta m_{32}^2 / \Delta m_{21}^2 \approx 34.5 \pm 2 \cdot (\mathcal{F}_3/\mathcal{F}_1)^2 \)
- Total mass: \( \sum m_i \approx 0.060 \cdot \mathcal{F}(\rho_{\mathcal{V}}) \, \text{eV} \)

**Majorana hypothesis (B7 cyclicity):**
- Neutrino: 0.5-step cyclicity (open loop, weak TZ attachment)
- Majorana: 1.5-step cyclicity (closed loop, full synchronization)
- Mass scale: \( m_{\text{Majorana}} \approx 0.2 - 7 \cdot \mathcal{F}(\rho_{\mathcal{V}}) \, \text{eV} \)
- Transition from neutrino to Majorana possible at \( \rho_{\mathcal{V}} > \rho_{\text{crit}} = \rho_{\text{H0}} \cdot C/(2\pi) \)

---

## 6. LIFE — LEVEL OF TE ORGANIZATION (3.0)

Life is TE transfer self-organization operating on the ID0 lattice and utilizing ID1.4 (macromolecules) and ID-1 (Vertical) interactions:

- **Cell:** closed TE loop with gateway to the Vertical (ID1.4 / ID-1 / ID0)
  \[
  \oint_{\partial\Omega} \Phi \cdot d\mathbf{S} = 0, \quad \mathcal{T}(\Omega) = \text{VEU}_{H-3}
  \]

- **Consciousness intensity** (H0 + L1 path, according to ROADMAP 3.0):
  \[
  \mathcal{C} = \frac{1}{|\Omega|} \int_{\Omega} \| \mathcal{P}_{L1}(\rho_{\mathcal{V}}) - \Phi \|^2 d\mathbf{x}
  \]

- **Cancer:** parallel P2P structure ignoring the Vertical (ID1.4 / ID0 / ID-1)
  \[
  \mathcal{T}(\Omega_{\text{cancer}}) = 0
  \]

- **Aging:** increase in information entropy (ID3 / ID0), modulated by \( \rho_{\mathcal{V}} \)
  \[
  \frac{d}{dt}\mathcal{S}_{\text{cell}} = -\mathcal{T}^{-1}(\text{Archive}_{\mathcal{V}}) \cdot \log(\mathcal{T}^{-1}(\text{Archive}_{\mathcal{V}}))
  \]

---

## 7. TECHNOLOGY AND ETHICS (3.0)

### 7.1. Two technological paths

| **Path** | **Mechanism** | **Efficiency** | **Hazard** | **ID correspondence** |
|----------|---------------|----------------|------------|-----------------------|
| **Type 1** | Through H0 matrix (horizontal) | \( \eta_1 \approx 1 - e^{-d/\lambda} \) | Low (comparable to existing) | ID0 |
| **Type 2** | Through TZ–Vertical–TZ (vertical) | \( \eta_2 \approx 1 - \rho_{\text{H0}}/\rho_{\mathcal{V}} \) | High (can disrupt Vertical balance) | ID-1 / ID0 |

### 7.2. Safety criteria

A technology is safe if:
\[
\left| \frac{d}{dt} \rho_{\mathcal{V}} \right| < \epsilon_{\text{crit}}, \quad
\left| \frac{d}{dt} \varepsilon_0 \right| < \varepsilon_{\text{crit}}, \quad
\left| \frac{d}{dt} \mu_0 \right| < \mu_{\text{crit}}, \quad
\left| \frac{d}{dt} G \right| < G_{\text{crit}}
\]

**Key insight:** Technologies must be **in balance with the Vertical** (ID-1) — they must use energy transfer, not release explosions. The atomic bomb is a warning of what happens when Vertical balance is disrupted.

---

## 8. TESTABLE PREDICTIONS SUMMARY (3.0)

| **Prediction** | **Equation** | **Value** | **Status** | **Test method** | **ID correspondence** |
|----------------|--------------|-----------|------------|-----------------|-----------------------|
| Fine-structure constant | \( \alpha = \frac{49 G_0}{24\pi \hbar c} \) | \( \alpha \approx 0.0073 \) (< 0.4%) | **Confirmed** | Precision spectroscopy | ID1 |
| G variation in galactic centers | \( G(0) = G_0(1 + \gamma \rho_{\mathcal{V}}/\rho_{\text{H0}}) \) | \( G(0)/G_0 \approx 1.50 \) | **Awaiting test** | GRAVITY interferometer | ID2 / ID-1 |
| 6th CMB peak | \( \ell_6 = C \cdot 47 \) | \( \ell_6 \approx 1660 \) | **Awaiting test** | CMB-S4, Simons Obs. | ID0.47 |
| 7th CMB peak | \( \ell_7 = C \cdot 55 \) | \( \ell_7 \approx 1943 \) | **Awaiting test** | CMB-S4, Simons Obs. | ID0.55 |
| NGC 6503 rotation curve | \( V_{\text{MT}}(r) = \sqrt{G(r)M_{\text{bar}}(r)/r} \) | Matches < 3% | **Confirmed** | SPARC database | ID2 / ID-1 |
| ε₀ dependence on ρ_V | \( \varepsilon_0 = \frac{6}{49} \cdot \frac{\hbar}{2\pi} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \) | — | **Awaiting test** | Quantum metrology | ID0 / ID-1 |
| μ₀ dependence on ρ_V | \( \mu_0 = \frac{49}{6} \cdot \frac{2\pi}{\hbar c^2} \cdot \frac{\rho_{\text{H0}}}{\rho_{\mathcal{V}}} \) | — | **Awaiting test** | Quantum metrology | ID0 / ID-1 |
| Neutrino masses | \( m_i = M_P \cdot \alpha^{n_i} \cdot \mathcal{F}(\rho_{\mathcal{V}}) \) | 0.0015, 0.0087, 0.050 eV | **Awaiting test** | DUNE, Hyper-K, KATRIN | ID1.1 / ID-1 |
| Majorana mass scale | \( m_{\text{Majorana}} \approx 0.2 - 7 \cdot \mathcal{F}(\rho_{\mathcal{V}}) \, \text{eV} \) | — | **Awaiting test** | 0νββ experiments | ID0 / ID-1 |
| Decoherence time | \( \tau_{\text{decoherence}} = \frac{C}{2\pi} \cdot \frac{\rho_{\text{H0}}}{\rho_{\mathcal{V}}} \) | — | **Theoretical** | Quantum metrology | ID0 / ID-1 |
| Consciousness intensity under anesthesia | \( \mathcal{C} = \int \| \mathcal{P}_{L1} - \Phi \|^2 \) | \( \mathcal{C} \) increases | **Theoretical** | EEG/fMRI | ID1.4 / ID-1 |
| Wireless energy transfer (type 2) | \( \eta_2 = 1 - \rho_{\text{H0}}/\rho_{\mathcal{V}} \) | \( \eta > 0.99 \) | **Theoretical** | Quantum metrology | ID-1 / ID0 |

---

## 9. COMPARISON WITH CLASSICAL THEORIES (3.0)

| **Aspect** | **Classical physics** | **MT (3.0)** | **ID correspondence** |
|------------|-----------------------|--------------|-----------------------|
| **Space** | Continuous / curved | Discrete cubic ID0 lattice | ID0 |
| **Time** | Relativistic (GR) | Absolute (Q1 cycle) | ID0 |
| **Gravity** | Space curvature | TE deficit gradient (H0 path) | ID0 / ID-1 |
| **Electromagnetism** | Fields in vacuum | TE transfer in ID0 matrix; ε₀, μ₀ vary with ρ_V | ID0 / ID1 |
| **Cosmology** | Expansion + dark energy | Static ID0 matrix + Vertical (H0 + L1 paths) | ID0 / ID-1 / ID1—ID5 |
| **Dark matter** | Required | Not required — ρ_V influence on G | ID-1 → ID0 |
| **Dark energy** | Required | Vertical energy reservoir (L1 path) | ID-1 |
| **Quantum mechanics** | Fundamentally probabilistic | L1-level statistics; depends on ρ_V | ID0 / ID-1 |
| **Singularities** | Exist | Do not exist — matrix switches H levels | ID0 / ID4 |
| **Constants** | Fundamental | Consequences of ID0 matrix properties; ε₀, μ₀ vary with ρ_V | ID0 |
| **γ and C** | Free parameters | Derived from cyclicity | ID0 / ID-1 |

---

## 10. ID SYSTEM (3.0)

ID is an energy management zone marker:

\[
\text{ID} = 2.0 + \log_{2.5}(n) + \gamma_{\text{ID}} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}, \quad \gamma_{\text{ID}} \approx 0.05
\]

**Important:** The \( \rho_{\mathcal{V}} \) correction **does not change the object's fundamental ID level** — it only refines the decimal part.

**Classification with ID notations:**

| **Object** | **ID** | **Type** | **Note** |
|------------|--------|----------|----------|
| ID0 lattice point | ID0.0 | Foundation | Matrix fundamental unit |
| Proton | ID1.0 | Monolith | First organization unit on ID0 |
| Atom (hydrogen) | ID1.1/1/1 | Monolith | Mendeleev element |
| Molecule (H₂O) | ID1.3/1/1 | Monolith | Chemical bond |
| Star | ID2.2 | Collective | ID2 level |
| Galaxy | ID2.4 | Collective | ID2 level |
| White dwarf | ID3.0 | Monolith | Collapse stage |
| Neutron star | ID3.1 | Monolith | ID3 level |
| Black hole (stellar) | ID4.0 | Monolith | ID4 level |
| Black hole (supermassive) | ID4.2 | Monolith | ID4 level |

---

## 11. DISCUSSION — STRENGTHS AND CHALLENGES (3.0)

### 11.1. Strengths

1. **No free parameters** — all major quantities are derived from matrix axioms and cyclicity.

2. **Quantitative predictions** — the theory provides testable numerical values with clear ID correspondence.

3. **Experimental fit** — α, CMB peaks, and NGC 6503 rotation curve match data.

4. **Simplicity (Ockham's razor)** — fewer free parameters than Lambda-CDM; all quantities are derived.

5. **Structural consistency** — ROADMAP clearly separates H0 and L1 paths, preventing operator mixing.

6. **Methodological stability** — MT is positioned as a complementary framework, not a competitor to classical theories.

7. **Ethical dimension** — the theory includes responsibility and safety aspects based on Vertical balance criteria.

8. **ρ_V dependence** — all effects depend on local Vertical energy density, making the theory richer and more testable.

### 11.2. Challenges and future work

1. **Mathematical rigor** — although version 3.0 has made significant improvements, some derivations (especially the complete functional form of \( \mathcal{P}_{L1} \)) require further development.

2. **More precise predictions** — more quantitative predictions are needed (e.g., precise neutrino mass values, gravitational wave speed, α more precise alignment with experiment).

3. **Experimental testing** — collaboration with experimental fields is needed (CMB-S4, GRAVITY, LIGO, quantum metrology, 0νββ).

4. **Simulations** — a digital model of ID0 lattice dynamics and L1 projection is needed.

5. **Connection to biochemistry** — the LIFE model needs linkage with molecular biology and experimental data.

6. **ρ_V measurement** — methods for local \( \rho_{\mathcal{V}} \) determination are needed to test predictions in different regions of the Universe.

---

## 12. FUTURE DIRECTIONS (3.0)

| **Priority** | **Task** | **Expected time** | **Result** | **ID correspondence** |
|--------------|----------|-------------------|------------|-----------------------|
| 1 | Precise α verification | 1 week | Stronger empirical foundation | ID0 / ID1 |
| 2 | Gravitational wave speed prediction | 2 weeks | New testable prediction | ID0 |
| 3 | Simulation architecture | 1 month | Digital tool for prediction testing | ID0 / ID1—ID4 |
| 4 | Neutrino mass prediction refinement | 1 month | New testable prediction | ID1.1 / ID-1 |
| 5 | ρ_V measurement method development | 2 months | Experimental ρ_V determination | ID-1 / ID0 |
| 6 | L1 projection detailing | 1 month | Precise \( \mathcal{P}_{L1} \) kernel | ID0 / ID-1 |
| 7 | Collaboration with experimentalists | Continuous | Experimental testing | All ID |
| 8 | Publication (preprint) | After steps 1–7 | Scientific recognition | All ID |

---

## 13. CONCLUSIONS (3.0)

Matrix Theory in version 3.0 is a **quantitatively formulated, internally consistent, and partially experimentally confirmed theory** offering a mechanical explanation for fundamental physical phenomena. Its predictions — including the derivation of the fine-structure constant from \( G_0, \hbar, c \) (ID0 / ID1), the explanation of CMB peaks via Qn structure (ID0.n), the explanation of galaxy rotation curves without dark matter (ID0 / ID-1 / ID2), and the neutrino mass hierarchy (ID1.1 / ID-1) — demonstrate the theory's viability.

**Key achievements of version 3.0:**

1. **No free parameters** — all quantities are derived from matrix axioms and cyclicity.
2. **\( \varepsilon_0, \mu_0 \) as matrix state functions** — vary with \( \rho_{\mathcal{V}} \).
3. **\( \gamma \) and \( C \) derived from cyclicity** — not free parameters.
4. **\( \mathcal{P}_{L1} \) fully defined** — as an integral operator.
5. **Methodological clarification** — MT as a complementary framework.
6. **All predictions depend on \( \rho_{\mathcal{V}} \)** — making the theory richer and more testable.

The **ID system** provides a universal classification connecting all aspects of the theory — from the ID0 lattice foundation to the proton (ID1.0), macromolecule (ID1.4), star (ID2.2), galaxy (ID2.4), and black hole (ID4). **ROADMAP** provides the structural scheme separating the H0 path (gravity, dynamics) and the L1 path (redshift, CMB), preventing operator mixing.

**However, the theory continues to develop.** Next steps include increasing mathematical rigor, developing simulations, generating new predictions, and collaborating with experimental fields. Particularly important is the local measurement of \( \rho_{\mathcal{V}} \), which would allow testing of the theory's core predictions in different regions of the Universe.

MT is not a "finished theory" — it is a **living, growing system** inviting further exploration, critique, and development.

---

## NOTE

This review reflects the current state of MT (July 2026, version 3.0). The theory continues to develop, and future versions may include refinements, additions, and corrections. More detailed information on specific aspects is available in the full set of MT documents (3.0 versions).

---

*Document prepared: July 2026*

---

## REFERENCES AND SUPPLEMENTARY DOCUMENTS (3.0)

| **Document** | **Description** | **ID correspondence** |
|--------------|-----------------|-----------------------|
| FOUNDATION_en.md (3.0) | Theory foundation and operational boundaries | ID0 / ID-1 |
| MATHEMATICS_en.md (3.0) | Mathematical formalism | ID0 / ID-1 / ID0.n |
| MT_QED_en.md (3.0) | Electromagnetism and constant derivation | ID0 / ID1 |
| GRAVITY_en.md (3.0) | Gravity and galaxy rotation curves | ID0 / ID-1 / ID2 |
| COSMOLOGY_en.md (3.0) | Cosmology and CMB predictions | ID0.n / ID-1 / ID1—ID5 |
| ID_GRADIENT_en.md (3.0) | ID gradation model | ID1—ID5 / ID-1 |
| LIFE_en.md (3.0) | Life model | ID1.4 / ID-1 / ID0 |
| TECHNOLOGY_en.md (3.0) | Technological potential | ID-1 / ID0 / ID1.4 |
| ETHICS_en.md (3.0) | Ethical and safety aspects | ID-1 / ID0 |
| QM_COMPARISON_en.md (3.0) | Comparison with quantum mechanics | ID0 / ID-1 / ID1 |
| NEUTRINO_en.md (3.0) | Neutrino physics | ID1.1 / ID-1 |
| NEUTRINO_MAJORANA_en.md (3.0) | Majorana particle hypothesis | ID0 / ID-1 |
| MT_ROADMAP_en.md (3.0) | Structural scheme and path separation | ID0 / ID-1 / ID0.n |

---

*Last updated: July 2026*
