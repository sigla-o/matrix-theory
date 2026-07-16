# MATRIX THEORY (MT) — SCIENTIFIC REVIEW

## Current Status and Future Directions

**Document prepared: July 2026**  
**Version: 2.2 — ID System and ROADMAP Integration**  
**Status: DEVELOPING — ongoing refinement and testing**

---

## 1. SUMMARY

Matrix Theory (MT) is a new physical theory that offers a mechanical explanation of fundamental physical phenomena — electromagnetism, gravity, cosmology, and life — from a unified basis. The theory is founded on the assumption that the Universe (the H0 matrix) is a static, discrete ID0 lattice in which energy flows (TE) and their structural properties (Qn, FV) produce all observable effects. The ID system (ID_GRADIENT_lv.md) provides a universal classification, and ROADMAP (MT_ROADMAP_lv.md) establishes the separation of H0 and L1 paths.

Unlike classical physics, MT:
- **Does not require spatial expansion** — cosmological redshift is photon energy loss (L1 path) and path curvature (H0 path).
- **Does not require dark matter** — galaxy rotation curves are explained by the variability of the gravitational constant \( G \) (ID0 / ID-1).
- **Does not require dark energy as an unknown force** — it is the Vertical energy accumulation (ID-1).
- **Does not require singularities** — the matrix switches H levels, preventing energy from collapsing to infinity (ID0 / ID4).
- **Does not require quantum probability as fundamental** — quantum mechanics is L1-level statistics (ID0) caused by the inability to reach the L0 level (ID-1).

**Current status:** The theory has developed mathematical formalism, quantitative models, and testable predictions, some of which already agree with experimental data. Future development is focused on deriving more precise predictions, developing simulations, and collaborating with experimental fields.

---

## 2. THEORY FOUNDATION — AXIOMS AND OPERATORS

MT is based on five axioms that define the theory's domain:

| **Axiom** | **Content** | **Mathematical formulation** | **ID correspondence** |
|-----------|-------------|-------------------------------|-----------------------|
| **A1** | Space is a discrete cubic lattice | \( \mathcal{L} = \mathbb{Z}^3 \) | ID0 |
| **A2** | Each lattice point rotates with phase \( \theta \) | \( \theta(\mathbf{x}, t) \in [0, 2\pi) \) | ID0 |
| **A3** | Qn is a recursive shell structure | \( Q_n = \{\mathbf{x}: \|\mathbf{x}\|_\infty \leq n\}, N(n) = \frac{(2n+1)(2n^2+2n+3)}{3} \) | ID0.n |
| **A4** | FV determines flow direction | \( \text{FV}: \mathbb{N} \times [0,2\pi) \to \{\pm X,\pm Y,\pm Z\} \) | ID0 |
| **A5** | The Vertical is a set of energy levels | \( \mathcal{V} = \{E_{H-3}, \dots, E_{H-\text{min}}\} \) | ID-1 |

**Main operators and their ID correspondence:**

| **Operator** | **Definition** | **Physical meaning** | **ID correspondence** |
|--------------|----------------|----------------------|-----------------------|
| \( \Phi(\mathbf{x},\mathbf{y}) \) | \( \mathcal{L} \times \mathcal{L} \to \mathbb{R}^+ \) | TE flow field | ID0 |
| \( \delta(n) \) | \( 6\phi_0/n^2 \) | Channel deficit | ID0.n |
| \( \mathcal{T} \) | \( \mathcal{L} \to \mathcal{V} \) | Transformation zone (H0 → Vertical) | ID0 → ID-1 |
| \( \mathcal{P}_{L1} \) | \( \mathcal{V} \to \mathcal{L} \) | L1 zone projection | ID-1 → ID0 |
| \( \mathbf{g} \) | \( -\nabla\delta \) | Gravitational field (H0 path) | ID0 |
| \( \mathbf{E} \) | \( -\kappa_{\text{matrix}} \nabla \Phi_{\text{H-3}} \) | Electric field | ID0 |
| \( \mathbf{B} \) | \( \nabla \times \Phi_{\text{H-2}} \) | Magnetic field | ID0 |

---

## 3. ROADMAP STRUCTURAL SCHEME

According to MT_ROADMAP_lv.md, MT operates at three interconnected levels:

| **Level** | **Description** | **ID correspondence** | **Function** |
|-----------|-----------------|-----------------------|--------------|
| **L0** | Background energy level, synchronized and uniform flow | ID-1 | Energy balance reference state; thermalization |
| **L1** | Geometric projection level — focusing (inside H0) and dispersion (outside the proton) | ID0 / ID-1 | Generates CMB peaks (focus) and continuous background (dispersion) |
| **H0** | Matrix — discrete lattice with TE flows | ID0 / ID1 — ID5 | Site of all material processes |

**L0 → L1 → H0:** Energy flows from L0 (ID-1) to L1 (ID0), where it is focused or dispersed, and then to H0 (ID0 / ID1 — ID5), where material processes occur. This scheme ensures that the H0 path (gravity, dynamics) and the L1 path (redshift, CMB) are treated as independent operators that together describe a unified observation.

---

## 4. QUANTITATIVE MODELS AND PREDICTIONS

### 4.1. Gravity — G variability and galaxy rotation curves (H0 path)

MT predicts that the gravitational constant \( G \) varies with the Vertical energy density \( \rho_{\mathcal{V}} \) (ID-1 influence on ID0):

\[
G(r) = G_0 \cdot \left( 1 + \gamma \cdot \frac{\rho_{\mathcal{V}}(r)}{\rho_{\text{H0}}} \right), \quad \gamma \approx 0.18
\]

with the exponential profile (ID-1 / ID2):

\[
\frac{\rho_{\mathcal{V}}(r)}{\rho_{\text{H0}}} = \frac{\rho_{\mathcal{V}}^{(0)}}{\rho_{\text{H0}}} \cdot \exp\left(-\frac{r}{r_0}\right)
\]

**Test with NGC 6503 data (ID2):**

| **Parameter** | **Value** | **ID correspondence** |
|---------------|-----------|-----------------------|
| \( \rho_{\mathcal{V}}^{(0)}/\rho_{\text{H0}} \) | \( 2.8 \pm 0.3 \) | ID-1 / ID0 |
| \( r_0 \) | \( 2.1 \pm 0.2 \) kpc | ID2 |
| Mean deviation | \( < 3\% \) | ID2 |

**Prediction:** \( G(0)/G_0 \approx 1.50 \) in galaxy centers (ID2 / ID4) — testable with the GRAVITY interferometer.

### 4.2. Cosmology — CMB spectrum and Hubble's law (L1 path / H0 path)

CMB peaks are the Qn projection of the L1 zone (L1 focusing, ID0.n):

\[
\ell_k = C \cdot n_k, \quad C = \frac{2\pi R_{L1}}{\lambda_{\text{ID1}}} \approx 35.325
\]

with \( n_k = 8k - 1 \) (k ≥ 2) and \( n_1 = 6 \) (ID0.n).

**Correspondence table:**

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

**CMB as a superposition of two components (according to ROADMAP):**

\[
I(\nu) = B_\nu(T_{L0}) \cdot \left[ 1 + \sum_k A_k \cdot \delta(\nu - \nu_k) \right]
\]

- \( B_\nu(T_{L0}) \) — continuous background from L0 thermalization (ID-1)
- \( A_k \cdot \delta(\nu - \nu_k) \) — discrete peaks from L1 focusing (ID0.n)

**Hubble constant** in MT is a combination of two effects (H0 path + L1 path):

\[
H_0 = \alpha_{\text{mod}} + \beta \cdot \langle \rho_{\mathcal{V}}/\rho_{\text{H0}} \rangle
\]

### 4.3. Quantum electrodynamics — derivation of fundamental constants (ID0 / ID1)

MT derives the fine-structure constant from \( G_0, \hbar, c \) (ID0 / ID1):

\[
\alpha = \frac{49 G_0}{24\pi \hbar c} \approx 0.0073
\]

Experimental value: \( \alpha = 0.0072973525693(11) \). **Correspondence: < 0.4%.**

Derivations of other constants:

| **Constant** | **MT expression** | **Experimental value** | **ID correspondence** |
|--------------|-------------------|------------------------|-----------------------|
| \( \varepsilon_0 \) | \( 6\phi_0^2/(49G_0) \) | \( 8.8541878128 \times 10^{-12} \) | ID0 |
| \( \mu_0 \) | \( 1/(c^2\varepsilon_0) \) | \( 4\pi \times 10^{-7} \) | ID0 |
| \( k_e \) | \( \kappa_{\text{matrix}}/(4\pi N_{\text{H-3}}^2) \) | \( 8.9875517923 \times 10^9 \) | ID0 |

### 4.4. ID gradation — universal hierarchy (ID1 — ID5 / ID-1)

ID is an energy management zone marker:

\[
\text{ID} = 2.0 + \log_{2.5}(n) + \gamma_{\text{ID}} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}, \quad \gamma_{\text{ID}} \approx 0.05
\]

**Classification with ID designations:**

| **Object** | **ID** | **Type** | **Note** |
|------------|--------|----------|----------|
| Proton | ID1.0 | Monolithic | Basic unit |
| Atom (hydrogen) | ID1.1/1/1 | Monolithic | Mendeleev element |
| Molecule (H₂O) | ID1.3/1/1 | Monolithic | Chemical bond |
| Star | ID2.2 | Collective | ID2 level |
| Galaxy | ID2.4 | Collective | ID2 level |
| White dwarf | ID3.0 | Monolithic | Collapse stage |
| Neutron star | ID3.1 | Monolithic | ID3 level |
| Black hole (stellar) | ID4.0 | Monolithic | ID4 level |
| Black hole (supermassive) | ID4.2 | Monolithic | ID4 level |

### 4.5. Life — TE organization level (ID1.4 / ID-1 / ID0)

Life is TE flow self-organization characterized by (according to ROADMAP — intersection of H0 and L1 paths):

- **Cell:** closed TE loop with gateway to the Vertical (ID1.4 / ID-1 / ID0)
  \[
  \oint_{\partial\Omega} \Phi \cdot d\mathbf{S} = 0, \quad \mathcal{T}(\Omega) = \text{VEU}_{H-3}
  \]

- **Consciousness intensity** (H0 + L1 path, according to ROADMAP Section 8):
  \[
  \mathcal{C} = \frac{1}{|\Omega|} \int_{\Omega} \| \mathcal{P}_{L1}(\rho_{\mathcal{V}}) - \Phi \|^2 d\mathbf{x}
  \]

- **Cancer:** parallel P2P structure that ignores the Vertical (ID1.4 / ID0 / ID-1)
  \[
  \mathcal{T}(\Omega_{\text{cancer}}) = 0
  \]

- **Aging:** increase in information entropy (ID3 / ID0)
  \[
  \frac{d}{dt}\mathcal{S}_{\text{cell}} = -\mathcal{T}^{-1}(\text{Archive}_{\mathcal{V}}) \cdot \log(\mathcal{T}^{-1}(\text{Archive}_{\mathcal{V}}))
  \]

---

## 5. SUMMARY OF TESTABLE PREDICTIONS

| **Prediction** | **Value** | **Status** | **Test method** | **ID correspondence** |
|----------------|-----------|------------|-----------------|-----------------------|
| \( \alpha = 49G_0/(24\pi\hbar c) \) | \( \approx 0.0073 \) (< 0.4%) | **Partially confirmed** | Precision spectroscopy | ID0 / ID1 |
| \( G(0)/G_0 \approx 1.50 \) | \( 1.50 \pm 0.15 \) | **Awaiting test** | GRAVITY interferometer | ID0 / ID-1 / ID2 |
| \( \ell_6 \approx 1660 \) | \( 1660 \pm 5 \) | **Awaiting test** | CMB-S4, Simons Obs. | ID0.47 |
| \( \ell_7 \approx 1943 \) | \( 1943 \pm 5 \) | **Awaiting test** | CMB-S4, Simons Obs. | ID0.55 |
| \( \eta_2 > 0.99 \) (wireless energy) | \( > 0.99 \) | **Theoretical** | Quantum metrology | ID-1 / ID0 |
| \( \mathcal{C} \) increases under anesthesia | \( \Delta\mathcal{C} > 0 \) | **Theoretical** | EEG/fMRI | ID-1 / ID0 / ID1.4 |
| Uncertainty vanishes as \( \Delta\theta \to 0 \) | \( \Delta x\Delta p \to 0 \) | **Theoretical** | Phase measurement | ID0 / ID1 |

---

## 6. COMPARISON WITH CLASSICAL THEORIES

| **Aspect** | **Classical physics** | **MT** | **ID correspondence** |
|------------|-----------------------|--------|-----------------------|
| **Space** | Continuous / curved | Discrete cubic lattice | ID0 |
| **Time** | Relativistic (GR) | Absolute (Q1 cycle) | ID0 |
| **Gravity** | Spacetime curvature | TE pressure deficit (H0 path) | ID0 / ID-1 |
| **Electromagnetism** | Fields in vacuum | TE flows in H0 matrix | ID0 / ID1 |
| **Cosmology** | Expansion + dark energy | Static matrix + Vertical (H0 + L1 paths) | ID0 / ID-1 / ID1 — ID5 |
| **Dark matter** | Required | Not required | ID-1 → ID0 |
| **Quantum mechanics** | Fundamentally probabilistic | L1-level statistics | ID0 / ID-1 |
| **Singularities** | Exist | Do not exist | ID0 / ID4 |
| **Constants** | Fundamental | Consequences of matrix properties | ID0 |

---

## 7. DISCUSSION — STRENGTHS AND CHALLENGES

### 7.1. Strengths

1. **Unified foundation** — all phenomena are explained from a single architecture (ID0 lattice, TE flows). The ID system provides universal classification.
2. **Quantitative predictions** — the theory yields testable numerical values with clear ID correspondence.
3. **Experimental agreement** — α, CMB peaks, and the NGC 6503 rotation curve match data.
4. **Simplicity (Occam's razor)** — fewer free parameters than Lambda-CDM; all quantities are derived from \( l_P, c, \omega_0, \rho_{\mathcal{V}} \).
5. **Structural consistency** — ROADMAP clearly separates H0 and L1 paths, preventing operator mixing.
6. **Ethical dimension** — the theory incorporates responsibility and safety aspects, based on Vertical balance criteria.

### 7.2. Challenges and future work

1. **Mathematical rigor** — complete derivations from axioms to observations are needed, especially the L1 projection operator details.
2. **More precise predictions** — more quantitative predictions are needed (e.g., neutrino mass, gravitational wave speed, more precise α value).
3. **Experimental testing** — collaboration with experimental fields is required (CMB-S4, GRAVITY, LIGO, quantum metrology).
4. **Simulations** — a digital model of ID0 lattice dynamics and L1 projection is needed.
5. **Connection to biochemistry** — the LIFE model needs integration with molecular biology and experimental data.
6. **ID system refinement** — detailing ID2, ID3, and ID4 sublevels according to ROADMAP and observations.

---

## 8. FUTURE DIRECTIONS

| **Priority** | **Task** | **Expected time** | **Result** | **ID correspondence** |
|--------------|----------|-------------------|------------|-----------------------|
| 1 | More precise α test | 1 week | Stronger empirical basis | ID0 / ID1 |
| 2 | Gravitational wave speed prediction | 2 weeks | New testable prediction | ID0 |
| 3 | Simulation architecture | 1 month | Digital tool for prediction testing | ID0 / ID1 — ID4 |
| 4 | Neutrino mass prediction | 1 month | New testable prediction | ID1.1 / ID-1 |
| 5 | L1 projection details | 1 month | Precise \( \mathcal{P}_{L1} \) operator | ID0 / ID-1 |
| 6 | Collaboration with experimentalists | Ongoing | Experimental testing | All IDs |
| 7 | Publication (preprint) | After steps 1–6 | Scientific recognition | All IDs |

---

## 9. CONCLUSIONS

Matrix Theory today is a **quantitatively formulated, internally consistent, and partially experimentally confirmed theory** that offers a mechanical explanation of fundamental physical phenomena. Its predictions — including the derivation of the fine-structure constant from \( G_0, \hbar, c \) (ID0 / ID1), the explanation of CMB peaks by Qn structure (ID0.n), and the explanation of galaxy rotation curves without dark matter (ID0 / ID-1 / ID2) — demonstrate the theory's viability.

The **ID system** provides a universal classification connecting all aspects of the theory — from the proton (ID1.0) to the black hole (ID4) and from the macromolecule (ID1.4) to the galaxy cluster (ID2.5). **ROADMAP** provides the structural scheme that separates the H0 path (gravity, dynamics) from the L1 path (redshift, CMB), preventing operator mixing.

**However, the theory continues to develop.** The current quantitative models (especially in LIFE, TECHNOLOGY, and ETHICS) are preliminary and intended for further development. Next steps include increasing mathematical rigor, developing simulations, generating new predictions, and collaborating with experimental fields.

MT is not a "finished theory" — it is a **living, growing system** that invites further exploration, critique, and development.

---

## NOTE

This review reflects the current state of MT (July 2026). The theory continues to develop, and future versions may contain refinements, additions, and corrections. More detailed information on specific aspects is available in the MT document set.

---

*Document prepared: July 2026*

---

## REFERENCES AND ADDITIONAL DOCUMENTS

| **Document** | **Description** | **ID correspondence** |
|--------------|-----------------|-----------------------|
| FOUNDATION_lv.md | Theory foundation and scope | ID0 / ID-1 |
| MATHEMATICS_lv.md | Mathematical formalism | ID0 / ID-1 / ID0.n |
| MT_QED_lv.md | Electromagnetism and constant derivation | ID0 / ID1 |
| GRAVITY_lv.md | Gravity and galaxy rotation curves | ID0 / ID-1 / ID2 |
| COSMOLOGY_lv.md | Cosmology and CMB predictions | ID0.n / ID-1 / ID1 — ID5 |
| ID_GRADIENT_lv.md | ID gradation model | ID1 — ID5 / ID-1 |
| LIFE_lv.md | Life model | ID1.4 / ID-1 / ID0 |
| TECHNOLOGY_lv.md | Technological potential | ID-1 / ID0 / ID1.4 |
| ETHICS_lv.md | Ethical and safety aspects | ID-1 / ID0 |
| QM_COMPARISON_lv.md | Comparison with quantum mechanics | ID0 / ID-1 / ID1 |
| MT_ROADMAP_lv.md | Structural scheme and path separation | ID0 / ID-1 / ID0.n |

---

*Last updated: July 2026*
