# ID GRADATION AND SYSTEM — MATRIX THEORY VERSION (MT)

This document combines the mathematical model of ID gradation and the practical classification of the ID system. ID is a discrete structural index determined by modulation (cyclic TE flow), size category, and additional parameters as needed.

Modulation is not an object. Modulation is a cyclic TE flow that maximally affects only those objects that are within the modulation's scale. ID indicates which modulation affects the object.

## 1. BASIC FORMAT

ID{modulation}.{size_category}/{additional_parameters_as_needed}

First digit — modulation (H+n). Required.
Second digit — size category. Required. .0 = base unit, .1, .2, ... = next sizes.
After "/" — additional parameters. Not required. Added as needed.

Parameters are not a forced order, but a necessity. The required start is modulation and size. Everything else forms during work.

**Note on ID and classical theories:**

The ID system classifies all objects — both those described by classical physics (ID1 — ID4) and MT-specific levels (ID0, ID-1). This does not mean that classical objects (e.g., a star with ID2.2) are "incorrectly" described by GR — the ID system simply indicates their place within the overall hierarchy of energy organization. Classical laws remain valid for predictions at these ID levels; MT adds the mechanical explanation for their origin.

## 2. MODULATIONS AND THEIR SCALES

ID-1 — < 10⁻³⁵ m — Vertical (energy source)
ID0 — 10⁻³⁵ m — Matrix (lattice, TE flow basis)
ID1 — 10⁻¹⁵ m — H+1 modulation
ID2 — 10⁵ – 10²⁵ m — H+2 modulation
ID3 — 10²⁵ – 10⁴⁵ m — H+3 modulation
ID4 — 10⁴⁵ – 10⁶⁵ m — H+4 modulation
ID5 — > 10⁶⁵ m — H+5 modulation (open for future)

Each next modulation is 10²⁰ times larger than the previous.

## 3. CONNECTION TO MATHEMATICS FORMALISM

From MATHEMATICS_lv.md the following operators and quantities are used:

| Operator / quantity | Definition | Physical meaning |
|---------------------|------------|------------------|
| \( \mathcal{L} \) | \( \mathbb{Z}^3 \) | H0 matrix cubic lattice |
| \( Q_n \) | \( \{\mathbf{x} \in \mathbb{Z}^3 : \|\mathbf{x}\|_\infty \leq n\} \) | Shell structure |
| \( N(n) \) | \( \frac{(2n+1)(2n^2+2n+3)}{3} \) | Point count in Qn layer |
| \( N_{\mathcal{V}}(\Omega) \) | Number of VEU units in region \( \Omega \) | Vertical energy amount |
| \( \mathcal{T} \) | \( \mathcal{L} \to \mathcal{V} \) | Transformation operator |
| \( \mathcal{P}_{L1} \) | \( \mathcal{V} \to \mathcal{L} \) | L1 projection operator |

ID is a discrete structural index determined by:
- modulation (H+n),
- Qn layer number \( n \),
- Vertical energy unit count \( N_{\mathcal{V}} \) projected onto the object's vicinity via \( \mathcal{P}_{L1} \).

## 4. ID GRADATION STEP — QUANTITATIVE MODEL

The ID step is discrete and corresponds to Qn index increase:

ID = 2.0 + log_S (R / R_proton)

where:
- R — object's Qn radius (measured in ID1 steps),
- R_proton ≈ 10⁻¹⁰ m — proton orbital radius (ID1.0 reference point),
- S — step determined by Qn layer sequence.

From Qn point count:
N(n) = (2n+1)(2n²+2n+3)/3

Linear scale R ∝ n · λ_ID1. For proton n_proton = 1. Thus:
ID = 2.0 + log_S(n)

From Qn layer sequence n = 6, 15, 23, 31, 39, ... we get:
S ≈ 2.5

Main equation:
ID = 2.0 + log_2.5(n)

Vertical energy unit count N_V modifies ID value:

ID(n, N_V) = 2.0 + log_2.5(n) + γ_ID · (N_V / N_H0)

where γ_ID ≈ 0.05 (from MATHEMATICS and COSMOLOGY). N_V/N_H0 is the ratio of Vertical and H0 energy unit counts in the object's vicinity.

Higher N_V accelerates structural evolution in regions with higher Vertical energy unit density.

## 5. ID SYSTEM STRUCTURE BY LEVELS

ID-1.0 — Vertical basis
ID-1.n — VEU levels (H-3, H-4, ... H-min)

ID0.0 — yin-yang point (phase source, rotation)
ID0.n — Qn layer (n = 1, 2, 3, ... Qmax)

ID1.0 — proton
ID1.1 — atom (element / isotope / ...)
ID1.2 — substance, crystal, liquid (type / structure / ...)
ID1.3 — molecule (type / isomer / ...)
ID1.4 — macromolecule (type / structure / ...)

Parameters:
- element — Mendeleev table number (1–118)
- isotope — mass number
- type / structure — defined as needed

ID2.size/orbit_count/atmosphere/satellite/...
Size category indicates the star's mass/size. Parameters describe planet count, atmosphere presence, satellite systems, and other system properties.

ID3.size/type/spin/magnetism/...
Size category indicates the object's mass/size. Type distinguishes white dwarf, neutron star, quark star. Spin and magnetism describe rotation and field properties.

ID4.size/mass/accretion/AGN/jets/...
Size category indicates the black hole's mass scale. Mass specifies the value in solar masses. Accretion, AGN, and jets describe environmental organization and activity.

ID5.size/...
Open — will be defined as needed.

## 6. COLLECTIVE OBJECTS — ID2,n CLASS

Collective objects are organizations of many monolithic objects (stars, galaxies, clusters). Scaling from proton does not apply; they are classified by organization level n:

ID2,n = 2.0 + log_2.5 (N_cells / N_proton)

where N_cells is the number of basic units in the collective organization.

| Object | ID2,n | Note |
|--------|-------|------|
| Atom | ID2,0 | Single proton organization |
| Molecule | ID2,1 | Multiple atom organization |
| Star | ID2,2 | Collective, simple |
| Star cluster | ID2,3 | More complex collective structure |
| Galaxy | ID2,4 | Most complex collective structure |
| Galaxy cluster | ID2,5 | Highest known collective organization |

## 7. ID TRANSITIONS — CONDITIONS AND TIME SCALE

ID transition from one level to the next occurs when the following conditions are met:

1. Vertical energy unit count N_V in the object's vicinity exceeds critical threshold N_krit:
   N_V > N_krit

2. Qn structure allows transition — next layer n+1 is available.

3. Modulations activate the transition.

Transition time:
t_transition ∝ 1 / (N_V - N_krit)

Transition examples:

| Transition | From | To | Trigger process | Example |
|------------|------|----|-----------------|---------|
| ID1.0 → ID1.1 | Proton | Atom | Electron capture | Hydrogen |
| ID1.1 → ID1.2 | Atom | Substance | Crystallization | Diamond |
| ID1.2 → ID1.3 | Substance | Molecule | Chemical bond | H₂O |
| ID1.3 → ID1.4 | Molecule | Macromolecule | Polymerization | DNA |
| ID2.0 → ID2.1 | Free planet | Planet with satellite | Satellite capture | Mars + Phobos |
| ID2.1 → ID2.2 | Planet with satellite | Planet with atmosphere | Atmosphere formation | Venus |
| ID2.2 → ID2.3 | Planet with atmosphere | Planet with atmosphere and satellites | Additional satellites | Earth + Moon |
| ID3.0 → ID3.1 | White dwarf | Neutron star | Gravitational collapse | Pulsar |
| ID4.0 → ID4.1 | Stellar black hole | Intermediate mass black hole | Accretion | — |

## 8. EXAMPLES

ID1.0 — free proton
ID1.1/1/1 — hydrogen-1
ID1.1/6/12 — carbon-12
ID1.1/92/238 — uranium-238
ID1.2/1/1 — diamond
ID1.3/1/1 — H₂O
ID1.4/1/1 — DNA
ID2.5/8/1 — Solar system (8 planets, 1 habitable)
ID2.3/4/0 — star with 4 planets, no atmosphere or satellites
ID3.1/0 — white dwarf
ID3.2/1 — pulsar
ID4.1/0 — stellar black hole without accretion
ID4.3/2 — supermassive black hole with accretion disk
ID4.3/2/1 — supermassive black hole with accretion disk and jets

## 9. TESTABLE PREDICTIONS

| Prediction | Equation | Test method |
|------------|----------|-------------|
| ID dependence on N_V | ID = 2.0 + log_2.5(n) + 0.05 · N_V/N_H0 | Black hole mass comparison |
| ID transition time | t_transition ∝ 1/(N_V - N_krit) | AGN activity periodicity |
| ID2,n and galaxy type | ID2,n = 2.0 + log_2.5(N_stars/N_proton) | Galaxy morphology |
| Maximum ID3,n | n_max ∝ N_V⁽⁰⁾/N_H0 | Maximum black hole mass |

## 10. ADDITION RULES

1. Parameters are added only as needed.
2. Number of parameters is not limited.
3. Each next .n contains the previous ones within itself.
4. The system can be supplemented and refined as the theory develops.

## 11. BASIC PRINCIPLE

1. First digit = modulation (required)
2. Second digit = size category (required)
3. Everything after "/" = as needed (not required)

The ID system is a beginning, not an end. Its refinement will happen during work.

Document prepared: July 2026
