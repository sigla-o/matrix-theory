# ID GRADATION AND SYSTEM — MATRIX THEORY VERSION (MT)

## Revised version (July 2026) — 3.0

This document combines the mathematical model of ID gradation and the practical classification of the ID system. ID is a discrete structural index determined by modulation (cyclic TE transfer), size category, and additional parameters as needed.

Modulation is not an object. Modulation is a cyclic TE transfer that maximally affects only those objects that are of the modulation's size. ID indicates which modulation affects the object.

**Methodological prerequisite:** The ID system classifies all objects — both those described by classical physics (ID1 — ID4) and MT-specific levels (ID0, ID-1). This does not mean that classical objects (e.g., a star with ID2.2) are "incorrectly" described by GR — the ID system simply indicates their place within the overall hierarchy of energy organization. Classical laws remain valid for predictions at these ID levels; MT adds the mechanical explanation for their origin.

**According to MATHEMATICS 3.0:** The ID system is independent of the local variation of \( \varepsilon_0 \), \( \mu_0 \), and \( G \) — these are matrix state functions that vary with \( \rho_{\mathcal{V}} \), but ID is a structural index primarily determined by the Qn shell number \( n \) and modulation level. The Vertical energy density \( \rho_{\mathcal{V}} \) causes only a small correction (via \( \gamma_{\text{ID}} \)), but does not change the object's fundamental ID level.

---

## 1. BASIC FORMAT

ID{modulation}.{size_category}/{parameters_as_needed}

First digit — modulation (H+n). Mandatory.
Second digit — size category. Mandatory. .0 = base unit, .1, .2, ... = subsequent sizes.
After "/" — additional parameters. Not mandatory. Added as needed.

Parameters are not forced order, but necessity. Mandatory start is modulation and size. The rest is developed during work.

---

## 2. MODULATIONS AND THEIR SCALES

ID-1 — < 10⁻³⁵ m — Vertical (energy source)
ID0 — 10⁻³⁵ m — Matrix (lattice, TE transfer foundation)
ID1 — 10⁻¹⁵ m — H+1 modulation
ID2 — 10⁵ – 10²⁵ m — H+2 modulation
ID3 — 10²⁵ – 10⁴⁵ m — H+3 modulation
ID4 — 10⁴⁵ – 10⁶⁵ m — H+4 modulation
ID5 — > 10⁶⁵ m — H+5 modulation (open for the future)

Each subsequent modulation is 10²⁰ times larger than the previous.

---

## 3. CONNECTION TO MATHEMATICS FORMALISM (3.0)

From MATHEMATICS_lv.md (3.0), the following operators and quantities are used:

| Operator / quantity | Definition | Physical meaning | ID correspondence |
|---------------------|------------|-----------------|-------------------|
| \( \mathcal{L} \) | \( \mathbb{Z}^3 \) | H0 matrix cubic lattice | ID0 |
| \( Q_n \) | \( \{\mathbf{x} \in \mathbb{Z}^3 : \|\mathbf{x}\|_\infty \leq n\} \) | Shell structure | ID0.n |
| \( N(n) \) | \( \frac{(2n+1)(2n^2+2n+3)}{3} \) | Number of points in Qn shell | ID0.n |
| \( \rho_{\mathcal{V}}(\Omega) \) | Vertical energy density | VEU unit density in region \( \Omega \) | ID-1 |
| \( \mathcal{T} \) | \( \mathcal{L} \to \mathcal{V} \) | Transformation operator | ID0 → ID-1 |
| \( \mathcal{P}_{L1} \) | \( \int K \rho_{\mathcal{V}} \) | L1 projection operator (integral) | ID-1 → ID0 |
| \( C \) | \( \ell_k/n_k \approx 35.325 \) | Cyclicity constant | ID0.n |
| \( \gamma \) | \( 2\pi/C \approx 0.18 \) | Cyclicity inverse scale | ID0 / ID-1 |
| \( \varepsilon_0 \) | \( \frac{6}{49} \cdot \frac{\hbar}{2\pi} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \) | Vacuum permittivity (matrix state function) | ID0 |

ID is a discrete structural index determined by:
- modulation (H+n),
- Qn shell number \( n \),
- number of Vertical energy units \( N_{\mathcal{V}} \) projected onto the object's vicinity via \( \mathcal{P}_{L1} \).

---

## 4. ID GRADATION STEP — QUANTITATIVE MODEL (3.0)

The ID step is discrete and corresponds to an increase in the Qn index:

ID = 2.0 + log_S (R / R_proton)

where:
- R — object's Qn radius (measured in ID1 steps),
- R_proton ≈ 10⁻¹⁰ m — proton orbital radius (ID1.0 reference point),
- S — step determined by Qn shell sequence.

From Qn point count:
N(n) = (2n+1)(2n²+2n+3)/3

Linear scale R ∝ n · λ_ID1. For a proton, n_proton = 1. Thus:
ID = 2.0 + log_S(n)

From the Qn shell sequence n = 6, 15, 23, 31, 39, ... we obtain:
S ≈ 2.5

**Main equation:**
ID = 2.0 + log_2.5(n)

**Vertical energy correction (3.0):**

The number of Vertical energy units \( \rho_{\mathcal{V}} \) modifies the ID value, but only as a small correction:

ID(n, ρ_V) = 2.0 + log_2.5(n) + γ_ID · (ρ_V / ρ_H0)

where γ_ID ≈ 0.05 (from MATHEMATICS and COSMOLOGY 3.0). ρ_V/ρ_H0 is the ratio of Vertical and H0 energy density in the object's vicinity.

**Important:** This correction **does not change the object's fundamental ID level** — it only refines the value in regions with high Vertical energy density. For example, an object with ID2.2 remains ID2.2 regardless of ρ_V; the correction affects only the decimal part, not the modulation level.

Higher ρ_V accelerates structural evolution in regions with high Vertical energy density (according to MATHEMATICS 3.3. and GRAVITY 11.1.).

---

## 5. ID SYSTEM STRUCTURE BY LEVELS

ID-1.0 — Vertical foundation
ID-1.n — VEU levels (H-3, H-4, ... H-min)

ID0.0 — yin–yang point (phase source, rotation)
ID0.n — Qn shell (n = 1, 2, 3, ... Qmax)

ID1.0 — proton
ID1.1 — atom (element / isotope / ...)
ID1.2 — substance, crystal, liquid (type / structure / ...)
ID1.3 — molecule (type / isomer / ...)
ID1.4 — macromolecule (type / structure / ...)

Parameters:
- element — Mendeleev table number (1–118)
- isotope — mass number
- type / structure — defined as needed

ID2.size/orbits/atmosphere/moon/...
Size category indicates star mass/size. Parameters describe planet count, atmosphere presence, moon systems, and other system properties.

ID3.size/type/spin/magnetism/...
Size category indicates object mass/size. Type distinguishes white dwarf, neutron star, quark star. Spin and magnetism describe rotation and field properties.

ID4.size/mass/accretion/AGN/jets/...
Size category indicates black hole mass scale. Mass specifies value in solar masses. Accretion, AGN, and jets describe environmental organization and activity.

ID5.size/...
Open — to be defined as needed.

---

## 6. COLLECTIVE OBJECTS — ID2,n CLASS

Collective objects are organizations of many monolithic objects (stars, galaxies, clusters). Scaling from the proton is not applicable to them; they are classified by organization level n:

ID2,n = 2.0 + log_2.5 (N_cells / N_proton)

where N_cells is the number of fundamental units in the collective organization.

| Object | ID2,n | Note |
|--------|-------|------|
| Atom | ID2,0 | Single proton organization |
| Molecule | ID2,1 | Multiple atom organization |
| Star | ID2,2 | Collective, simple |
| Star cluster | ID2,3 | More complex collective structure |
| Galaxy | ID2,4 | Most complex collective structure |
| Galaxy cluster | ID2,5 | Highest known collective organization |

---

## 7. ID TRANSITIONS — CONDITIONS AND TIME SCALE

An ID transition from one level to the next occurs when the following conditions are met:

1. The Vertical energy density ρ_V in the object's vicinity exceeds the critical threshold ρ_krit:
   ρ_V > ρ_krit

2. The Qn structure allows the transition — the next shell n+1 is available.

3. Modulations activate the transition.

Transition time:
t_transition ∝ 1 / (ρ_V - ρ_krit)

**According to MATHEMATICS 3.0:** ρ_V also affects G (via γ = 2π/C) and ε₀ (via ε₀ ∝ ρ_V), meaning that in high ρ_V regions, ID transitions occur faster because the matrix's fundamental parameters are altered.

Transition examples:

| Transition | From | To | Activating process | Example |
|------------|------|----|--------------------|---------|
| ID1.0 → ID1.1 | Proton | Atom | Electron addition | Hydrogen |
| ID1.1 → ID1.2 | Atom | Substance | Crystallization | Diamond |
| ID1.2 → ID1.3 | Substance | Molecule | Chemical bond | H₂O |
| ID1.3 → ID1.4 | Molecule | Macromolecule | Polymerization | DNA |
| ID2.0 → ID2.1 | Free planet | Planet with moon | Moon capture | Mars + Phobos |
| ID2.1 → ID2.2 | Planet with moon | Planet with atmosphere | Atmosphere formation | Venus |
| ID2.2 → ID2.3 | Planet with atmosphere | Planet with atmosphere and moons | Additional moons | Earth + Moon |
| ID3.0 → ID3.1 | White dwarf | Neutron star | Gravitational collapse | Pulsar |
| ID4.0 → ID4.1 | Stellar black hole | Intermediate-mass black hole | Accretion | — |

---

## 8. EXAMPLES

ID1.0 — free proton
ID1.1/1/1 — hydrogen-1
ID1.1/6/12 — carbon-12
ID1.1/92/238 — uranium-238
ID1.2/1/1 — diamond
ID1.3/1/1 — H₂O
ID1.4/1/1 — DNA
ID2.5/8/1 — Solar System (8 planets, 1 habitable)
ID2.3/4/0 — star with 4 planets, no atmosphere or moons
ID3.1/0 — white dwarf
ID3.2/1 — pulsar
ID4.1/0 — stellar black hole without accretion
ID4.3/2 — supermassive black hole with accretion disk
ID4.3/2/1 — supermassive black hole with accretion disk and jets

---

## 9. TESTABLE PREDICTIONS (3.0)

| Prediction | Equation | Test method | ID correspondence |
|------------|----------|-------------|-------------------|
| ID dependence on ρ_V | ID = 2.0 + log_2.5(n) + 0.05 · ρ_V/ρ_H0 | Black hole mass comparison | ID4 |
| ID transition time | t_transition ∝ 1/(ρ_V - ρ_krit) | AGN activity periodicity | ID2 / ID-1 |
| ID2,n and galaxy type | ID2,n = 2.0 + log_2.5(N_stars/N_proton) | Galaxy morphology | ID2 |
| Maximum ID3,n | n_max ∝ ρ_V⁽⁰⁾/ρ_H0 | Maximum black hole mass | ID3 / ID-1 |
| ID correlation with ε₀ variation | ID unchanged, ε₀ varies with ρ_V | Quantum metrology in high-energy regions | ID0 / ID-1 |

---

## 10. ADDITION RULES

1. Parameters are added only as needed.
2. The number of parameters is not limited.
3. Each subsequent .n contains the previous ones.
4. The system can be supplemented and refined as the theory develops.

---

## 11. CORE PRINCIPLE

1. First digit = modulation (mandatory)
2. Second digit = size category (mandatory)
3. Everything after "/" = as needed (not mandatory)

The ID system is a beginning, not an end. Its refinement will occur during work.

---

## 12. CORRESPONDENCE WITH MATHEMATICS 3.0

This document is fully aligned with MATHEMATICS 3.0:

- ID base value \( 2.0 + \log_{2.5}(n) \) — from Qn structure (MATHEMATICS 1.0).
- Vertical correction \( \gamma_{\text{ID}} \cdot \rho_{\mathcal{V}}/\rho_{\text{H0}} \) — from MATHEMATICS 3.3. and COSMOLOGY 3.0.
- \( \rho_{\mathcal{V}} \) dynamics — from MATHEMATICS 2.5. and GRAVITY 11.1.
- Cyclicity constant \( C \) and \( \gamma \) — from MATHEMATICS 5.0.

The ID system is **independent** of \( \varepsilon_0 \) and \( \mu_0 \) variation — these are matrix state functions, but ID is a structural index primarily determined by the Qn shell number and modulation level.

---

*Document prepared: July 2026*
