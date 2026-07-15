# ID GRADIENT — MATRIX THEORY FORMAL MODEL (MT)
## Strict Academic Version

This document defines the discrete structural ID (integration depth) index, its dependence on Qn structure and Vertical energy unit count, and the transition conditions between ID levels.

---

## 1. CONNECTION TO MATHEMATICS FORMALISM

From MATHEMATICS:

| Operator / quantity | Definition | Physical meaning |
|---------------------|------------|------------------|
| \( \mathcal{L} \) | \( \mathbb{Z}^3 \) | H0 cubic lattice |
| \( Q_n \) | \( \{\mathbf{x}: \|\mathbf{x}\|_\infty \leq n\} \) | Shell structure |
| \( N(n) \) | \( \frac{(2n+1)(2n^2+2n+3)}{3} \) | Point count in Qn layer |
| \( N_{\mathcal{V}}(\Omega) \) | Number of VEU units in region \( \Omega \) | Vertical energy amount |
| \( \mathcal{T} \) | \( \mathcal{L} \to \mathcal{V} \) | Transformation operator |
| \( \mathcal{P}_{L1} \) | \( \mathcal{V} \to \mathcal{L} \) | L1 projection operator |

**ID definition:** ID is a discrete structural index determined by:
- Qn layer number \( n \),
- Vertical energy unit count \( N_{\mathcal{V}} \) projected onto the object's vicinity via \( \mathcal{P}_{L1} \),
- presence of modulations (H+2, H+3, ...).

ID is not a continuous field; it is an organizational level marker corresponding to discrete Qn layer sequence.

---

## 2. ID STEP — QUANTITATIVE MODEL

### 2.1. ID step and Qn structure

\[
\text{ID} = 2.0 + \log_{S} \left( \frac{R}{R_{\text{proton}}} \right)
\]

where \( R \) is Qn radius, \( R_{\text{proton}} \approx 10^{-10} \) m, \( S \approx 2.5 \) from Qn sequence.

Main equation:
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

### 2.3. Effect of Vertical energy unit count

\[
\text{ID}(n, N_{\mathcal{V}}) = 2.0 + \log_{2.5}(n) + 0.05 \cdot \frac{N_{\mathcal{V}}}{N_{\text{H0}}}
\]

---

## 3. COLLECTIVE OBJECTS — ID2,n CLASS

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

## 4. ID TRANSITIONS

Transition occurs when:
1. \( N_{\mathcal{V}} > N_{\text{krit}} \)
2. Next Qn layer available
3. Modulations activate

Transition time:
\[
t_{\text{transition}} \propto \frac{1}{N_{\mathcal{V}} - N_{\text{krit}}}
\]

---

## 5. TESTABLE PREDICTIONS

| Prediction | Equation | Test method |
|------------|----------|-------------|
| ID vs \( N_{\mathcal{V}} \) | \( \text{ID} = 2.0 + \log_{2.5}(n) + 0.05 \cdot N_{\mathcal{V}}/N_{\text{H0}} \) | BH mass comparison |
| Transition time | \( t_{\text{transition}} \propto 1/(N_{\mathcal{V}} - N_{\text{krit}}) \) | AGN periodicity |
| ID2,n vs galaxy type | \( \text{ID2,n} = 2.0 + \log_{2.5}(N_{\text{stars}}/N_{\text{proton}}) \) | Galaxy morphology |
| Max ID3,n | \( n_{\text{max}} \propto N_{\mathcal{V}}^{(0)}/N_{\text{H0}} \) | Max BH mass |

---

## 6. CONCLUSIONS

1. ID is a discrete structural index:  
   \[
   \text{ID} = 2.0 + \log_{2.5}(n) + 0.05 \cdot N_{\mathcal{V}}/N_{\text{H0}}
   \]
2. ID steps are discrete with \( S \approx 2.5 \).
3. Higher \( N_{\mathcal{V}} \) accelerates ID transitions.
4. Collective objects belong to ID2,n class.
5. ID transitions are quantifiable and testable.
