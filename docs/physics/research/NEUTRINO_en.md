# NEUTRINO — MATRIX THEORY VERSION (MT)

## Revised version (July 2026) — 3.0

This document summarizes the Matrix Theory (MT) interpretation of neutrino physics — their mass, structure, anti-neutrinos, and annihilation. It is a structured theoretical description derived from MT core principles and connected to the MATHEMATICS formalism 3.0 and the ID system (3.0).

**Methodological prerequisite (3.0):** MT is a complementary framework providing a mechanical origin for the phenomenological laws of classical physics. Neutrino physics (Standard Model) remains valid in its domain; MT describes the "territory" (ID0 lattice and Vertical) on which neutrino phenomena are built. MT does not compete with neutrino physics — it complements it.

**Key insight (3.0):** The neutrino is not a "massless" particle — it is a closed TE transfer loop with weak TZ attachment, whose mass is determined by VEU H-3 energy quantization and loop geometry. All neutrino properties depend on the local Vertical energy density \( \rho_{\mathcal{V}} \), which modulates masses, oscillation frequencies, and annihilation cross-sections.

**According to MATHEMATICS 3.0:** Neutrino mass formulas use \( \alpha = 49G_0/(24\pi\hbar c) \) as a matrix structural invariant, and all mass scales depend on \( \rho_{\mathcal{V}} \) via \( \varepsilon_0, \mu_0, G \), and \( \gamma = 2\pi/C \).

---

## 1. NEUTRINO'S PLACE IN MT AND THE ID SYSTEM (3.0)

### 1.1. Definition

The neutrino (ID1.1) is:

- **A closed TE transfer loop** — like the electron, but with a different internal structure.
- **Weak TZ attachment** (ID-1) — it has a "window" to the Vertical, allowing interaction with H-3 and H-4 levels.
- **No electric charge** — phase symmetry is fully compensated (no H-3 excess load).

**According to ID_GRADIENT 3.0:** The neutrino remains ID1.1 regardless of \( \rho_{\mathcal{V}} \). The \( \rho_{\mathcal{V}} \) correction \( \gamma_{\text{ID}} \cdot \rho_{\mathcal{V}}/\rho_{\text{H0}} \) affects only the decimal part, not the fundamental ID level. However, \( \rho_{\mathcal{V}} \) affects neutrino interaction intensity via \( \varepsilon_0, \mu_0, G \), and \( \gamma \).

| Object | ID | TZ attachment | TE structure | Vertical levels | Charge |
|--------|-----|--------------|--------------|-----------------|--------|
| Electron | ID1.1 | No | Closed TE loop (H-2 × H-3) | H-3 (dominant) | -1 |
| Neutrino | ID1.1 | Yes (weak) | Closed TE loop (H-3 × H-4) | H-3 + H-4 | 0 |
| Photon | ID0 | No | Open TE transfer | None | 0 |

### 1.2. Three flavors — where do they come from? (3.0)

The three neutrino flavors (\( \nu_e, \nu_\mu, \nu_\tau \)) correspond to **three different phase combinations** in the PV cycle:

- The PV cycle has 12 channels (6 directions × 2 half-phases).
- The Vertical "window" opens only at specific phases.
- The three flavors correspond to three different phase windows:
  - \( \nu_e \): window at phase 0°–120°
  - \( \nu_\mu \): window at phase 120°–240°
  - \( \nu_\tau \): window at phase 240°–360°

**According to MATHEMATICS 3.0:** The positions and widths of the phase windows depend on local \( \rho_{\mathcal{V}} \) via \( \gamma = 2\pi/C \) and the focusing/dispersion function \( \mathcal{F}_n(\rho_{\mathcal{V}}) \). In high \( \rho_{\mathcal{V}} \) regions, phase windows can become blurred, affecting oscillation profiles.

Each window has a different number of channels, determining the H-3 energy capture capability and thus the mass.

---

## 2. NEUTRINO MASS DETERMINATION — TWO METHODS (3.0)

MT offers **two independent ways** to calculate neutrino mass. They are complementary and mutually consistent. Both depend on \( \rho_{\mathcal{V}} \) via \( \alpha \) and matrix state functions.

---

### 2.1. METHOD 1 — indirect (H-3 level quantization) (3.0)

**Assumption:** Neutrino mass is proportional to the Planck mass multiplied by a power of the fine-structure constant. This power determines what fraction of H-3 energy the neutrino can capture through its "window" to the Vertical.

**Formula (3.0):**
$$
\boxed{m_i = M_P \cdot \alpha^{n_i} \cdot \mathcal{F}(\rho_{\mathcal{V}})}
$$

where:
- \( M_P = \phi_0 / c^2 = \hbar / (c l_P) \approx 1.22 \times 10^{19} \, \text{GeV}/c^2 \)
- \( \alpha = 49G_0/(24\pi\hbar c) \approx 1/137.036 \) — from MATHEMATICS 3.0 (matrix structural invariant)
- \( n_i \) — exponent differing for the three flavors
- \( \mathcal{F}(\rho_{\mathcal{V}}) \) — focusing/dispersion function from MATHEMATICS 5.2. (3.0), modulating mass depending on local \( \rho_{\mathcal{V}} \):
  \[
  \mathcal{F}(\rho_{\mathcal{V}}) = 
  \begin{cases}
  1, & \rho_{\mathcal{V}} \ll \rho_{\text{H0}} \quad \text{(weak Vertical)} \\
  1 + \gamma \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}, & \rho_{\mathcal{V}} \approx \rho_{\text{H0}} \quad \text{(moderate Vertical)} \\
  e^{\gamma \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}}, & \rho_{\mathcal{V}} \gg \rho_{\text{H0}} \quad \text{(strong Vertical)}
  \end{cases}
  \]

**Experimentally determined values (at \( \rho_{\mathcal{V}} \approx \rho_{\text{H0}} \)):**

| Flavor | \( m_i \) (eV) | \( n_i \) |
|--------|---------------|-----------|
| \( \nu_1 \) | \( \approx 0.0015 \) | \( \approx 4.82 \) |
| \( \nu_2 \) | \( \approx 0.0087 \) | \( \approx 5.18 \) |
| \( \nu_3 \) | \( \approx 0.050 \) | \( \approx 5.54 \) |

**Exponent differences:**
$$
n_2 - n_1 \approx n_3 - n_2 \approx 0.36
$$

This means the exponents are **evenly distributed** with step \( \Delta n \approx 0.36 \).

**Mass ratios:**
$$
\frac{m_{i+1}}{m_i} = \alpha^{-\Delta n} \cdot \frac{\mathcal{F}_{i+1}(\rho_{\mathcal{V}})}{\mathcal{F}_i(\rho_{\mathcal{V}})}
\approx 137^{0.36} \cdot \frac{\mathcal{F}_{i+1}(\rho_{\mathcal{V}})}{\mathcal{F}_i(\rho_{\mathcal{V}})}
\approx 5.87 \cdot \frac{\mathcal{F}_{i+1}(\rho_{\mathcal{V}})}{\mathcal{F}_i(\rho_{\mathcal{V}})}
$$

**Mass squared difference ratio:**
$$
\frac{\Delta m_{32}^2}{\Delta m_{21}^2} \approx 34.5 \pm 2
$$

Experimental value: \( \approx 33 \). Deviation ~5%, which is acceptable and may be explained by local \( \rho_{\mathcal{V}} \) variations.

---

### 2.2. METHOD 2 — direct (loop energy) (3.0)

**Assumption:** Neutrino mass is the total energy of its closed TE transfer loop, determined by the Qn shell size and saturation level.

**Formula (3.0):**
$$
\boxed{m_\nu = \frac{\phi_0}{c^2} \cdot \frac{N_{\text{shell}}}{|Q_n|} \cdot \alpha^{n_\nu} \cdot \mathcal{F}(\rho_{\mathcal{V}})}
$$

where:
- \( N_{\text{shell}} = |Q_n| - |Q_{n-1}| \) — number of pockets in the loop shell,
- \( n_\nu \approx 14 \) — Qn index corresponding to the neutrino loop,
- \( \alpha^{n_\nu} \) — saturation level,
- \( \mathcal{F}(\rho_{\mathcal{V}}) \) — focusing/dispersion function.

**Calculation (at \( \rho_{\mathcal{V}} \approx \rho_{\text{H0}} \)):**
- \( |Q_{14}| = 4089 \), \( |Q_{13}| = 3219 \), \( N_{\text{shell}} = 870 \)
- \( \alpha^{14} \approx (1/137)^{14} \approx 4.1 \times 10^{-30} \)
- \( m_\nu = M_P \cdot \frac{870}{4089} \cdot 4.1 \times 10^{-30} \cdot \mathcal{F}(\rho_{\mathcal{V}}) \approx 1.06 \times 10^{-11} \, \text{GeV} \cdot \mathcal{F}(\rho_{\mathcal{V}}) \approx 0.0106 \, \text{eV} \cdot \mathcal{F}(\rho_{\mathcal{V}}) \)

This is close to the \( m_2 \) scale (~0.0087 eV) at \( \mathcal{F}(\rho_{\mathcal{V}}) \approx 0.82 \).

**The three flavors** arise from phase combinations that change the effective \( n \) for each flavor:
- \( \nu_1: n = 14 + \delta_1 \)
- \( \nu_2: n = 14 + \delta_2 \)
- \( \nu_3: n = 14 + \delta_3 \)

where \( \delta_i \) are small shifts from the main shell, determined by PV cycle phases and local \( \rho_{\mathcal{V}} \).

---

### 2.3. Comparison of the two methods (3.0)

| Model | Formula | Result (at \( \rho_{\mathcal{V}} \approx \rho_{\text{H0}} \)) | \( \rho_{\mathcal{V}} \) dependence |
|-------|---------|---------|--------------------------------------|
| **1. (indirect, H-3)** | \( m_\nu = M_P \cdot \alpha^{n} \cdot \mathcal{F}(\rho_{\mathcal{V}}) \), \( n \approx 4.82, 5.18, 5.54 \) | \( m_\nu \approx 0.0015 - 0.05 \, \text{eV} \) | \( \mathcal{F}(\rho_{\mathcal{V}}) \) modulates the entire scale |
| **2. (direct, loop energy)** | \( m_\nu = M_P \cdot \frac{N_{\text{shell}}}{|Q_n|} \cdot \alpha^{n} \cdot \mathcal{F}(\rho_{\mathcal{V}}) \), \( n \approx 14 \) | \( m_\nu \approx 0.01 \, \text{eV} \cdot \mathcal{F}(\rho_{\mathcal{V}}) \) (average) | \( \mathcal{F}(\rho_{\mathcal{V}}) \) modulates the average scale |

**Conclusion:** The first model gives all three flavors with different \( n \). The second model gives the overall mass scale. They are **complementary** — the first refines the differences, the second sets the baseline. \( \mathcal{F}(\rho_{\mathcal{V}}) \) modulates both, making neutrino masses dependent on local Vertical energy density.

---

## 3. ANTI-NEUTRINO IN MT (3.0)

### 3.1. Definition

The anti-neutrino (\( \bar{\nu} \)) in MT is the neutrino's **mirror configuration**:

- **Opposite phase** — neutrino phase \( \theta \) is replaced by \( \theta + \pi \).
- **Opposite spin** — circulation direction in the loop is reversed.
- **Same mass** — energy in the loop is identical, as the number of pockets and saturation level remain unchanged; \( \mathcal{F}(\rho_{\mathcal{V}}) \) is the same for both.

**ID correspondence:** The anti-neutrino retains ID1.1, but with the additional parameter \( \bar{\nu} \).

### 3.2. Mass equality (3.0)

MT predicts:
$$
m_{\bar{\nu}} = m_\nu
$$

This matches experimental limits (KATRIN: \( m_{\bar{\nu}_e} < 0.45 \, \text{eV} \)).

**Reason (3.0):** The mass formulas for both types do not depend on the phase sign — only on the energy amount in the loop and \( \mathcal{F}(\rho_{\mathcal{V}}) \), which is identical for both configurations. Local \( \rho_{\mathcal{V}} \) variations affect both equally.

---

## 4. NEUTRINO-ANTINEUTRINO ANNIHILATION IN MT (3.0)

### 4.1. Annihilation mechanism (3.0)

Neutrino-antineutrino annihilation (`ν + \bar{ν}`) in MT is the **collision and mutual cancellation** of two opposite-phase loops.

When two loops meet with opposite phases (\( \theta \) and \( \theta + \pi \)), the TE transfer channels mutually compensate, and energy is released as:

- **Photons** (low energies),
- **`Z` boson** (high energies, at \( E \sim 91 \, \text{GeV} \)),
- **Other particles** (depending on available energy).

**According to MATHEMATICS 3.0:** The annihilation cross-section depends on \( \rho_{\mathcal{V}} \) via \( \varepsilon_0, \mu_0 \), and \( \gamma \), which modulate interaction strength.

### 4.2. Energy threshold and \( \rho_{\mathcal{V}} \) influence (3.0)

The annihilation cross-section depends on energy and local \( \rho_{\mathcal{V}} \):

| Energy scale | Process | Cross-section | \( \rho_{\mathcal{V}} \) influence |
|--------------|---------|---------------|--------------------------------|
| Low (\( E \ll m_Z c^2 \)) | `ν + \bar{ν} → γ + γ` | Very small (\( \sim 10^{-60} \, \text{cm}^2 \)) | \( \sigma \propto \varepsilon_0^2 \propto \rho_{\mathcal{V}}^2 \) |
| Resonance (\( E \approx m_Z c^2 \)) | `ν + \bar{ν} → Z` | Maximum (\( \sim 10^{-38} \, \text{cm}^2 \)) | \( \sigma \propto 1/\Gamma_Z^2 \), \( \Gamma_Z \) depends on \( \rho_{\mathcal{V}} \) |
| High (\( E \gg m_Z c^2 \)) | `ν + \bar{ν} → various particles` | Decreases as \( 1/E^2 \) | \( \sigma \propto 1/\varepsilon_0^2 \propto 1/\rho_{\mathcal{V}}^2 \) |

### 4.3. MT prediction for annihilation (3.0)

MT predicts that neutrino-antineutrino annihilation is **energy-dependent** and reaches a maximum at the `Z` boson mass (~91 GeV), with its cross-section modulated by \( \rho_{\mathcal{V}} \).

**Testable prediction (3.0):** The annihilation cross-section is proportional to:
$$
\sigma_{\nu\bar{\nu}} \propto \alpha^2 \cdot \frac{E^2}{(E^2 - m_Z^2 c^4)^2 + \Gamma_Z^2 m_Z^2 c^4} \cdot \mathcal{F}(\rho_{\mathcal{V}})^2
$$
where \( \Gamma_Z \) is the `Z` boson total width, which depends on \( \rho_{\mathcal{V}} \) via \( \varepsilon_0, \mu_0 \), and \( \gamma \).

---

## 5. MAJORANA AND DIRAC — MT VIEW (3.0)

### 5.1. Majorana neutrino (3.0)

If the neutrino is a Majorana particle (i.e., \( \nu = \bar{\nu} \)), its loop has no distinction between phase \( \theta \) and \( \theta + \pi \). This means the loop is **symmetric under a \( \pi \) phase shift**.

**MT implications (3.0):** The Majorana neutrino loop has only **one phase configuration** — no distinction between particle and antiparticle. This means annihilation `ν + ν` (two Majorana neutrinos) would be possible, corresponding to the `0νββ` process. The probability of this process depends on \( \rho_{\mathcal{V}} \) via \( \mathcal{F}(\rho_{\mathcal{V}}) \).

### 5.2. Dirac neutrino (3.0)

If the neutrino is a Dirac particle (i.e., \( \nu \neq \bar{\nu} \)), the phases \( \theta \) and \( \theta + \pi \) are different configurations. Annihilation `ν + ν` is not possible.

### 5.3. MT stance (3.0)

MT **does not choose** between Majorana and Dirac — it offers **mechanisms for both**. The experimental answer (e.g., observation of `0νββ`) will determine which configuration is realized.

MT prediction (3.0): If `0νββ` is observed, it means the neutrino loop is symmetric under a \( \pi \) phase shift and is of Majorana type. The `0νββ` cross-section is proportional to \( \mathcal{F}(\rho_{\mathcal{V}})^2 \), making it dependent on local \( \rho_{\mathcal{V}} \).

---

## 6. \( \rho_{\mathcal{V}} \) INFLUENCE ON NEUTRINO PHYSICS — 3.0 SUMMARY

| Neutrino property | Dependence on \( \rho_{\mathcal{V}} \) | Mechanism |
|-------------------|-------------------------------------|-----------|
| Mass scale | \( m \propto \mathcal{F}(\rho_{\mathcal{V}}) \) | Focusing/dispersion function modulates energy quantization |
| Mass ratios | \( m_{i+1}/m_i \propto \mathcal{F}_{i+1}/\mathcal{F}_i \) | Phase windows shift with \( \rho_{\mathcal{V}} \) |
| Oscillation frequency | \( \Delta m^2 \propto \mathcal{F}(\rho_{\mathcal{V}})^2 \) | Mass squared differences modulated |
| Annihilation cross-section | \( \sigma \propto \mathcal{F}(\rho_{\mathcal{V}})^2 \) | Interaction strength changes |
| `0νββ` probability | \( \propto \mathcal{F}(\rho_{\mathcal{V}})^2 \) | Majorana loop symmetry modulated |
| Decoherence time | \( \tau_{\text{decoherence}} \propto 1/\rho_{\mathcal{V}} \) | Vertical energy density disrupts phase synchronization |

---

## 7. SUMMARY TABLE (3.0)

| Aspect | Standard Model | MT (3.0) | ID correspondence |
|--------|---------------|----------|-------------------|
| **Neutrino structure** | Point particle | Closed TE transfer loop (H-3 × H-4) | ID1.1 / ID-1 |
| **Mass origin** | Yukawa interaction (Higgs) | H-3 energy quantization + loop geometry; modulated by \( \rho_{\mathcal{V}} \) | ID0 / ID-1 |
| **Mass formula (indirect)** | Empirical | \( m_\nu = M_P \cdot \alpha^n \cdot \mathcal{F}(\rho_{\mathcal{V}}) \) | ID0 / ID1 |
| **Mass formula (direct)** | None | \( m_\nu = M_P \cdot \frac{N_{\text{shell}}}{|Q_n|} \cdot \alpha^n \cdot \mathcal{F}(\rho_{\mathcal{V}}) \) | ID0.n / ID0 |
| **Three flavors** | Free parameters | Three phase windows in PV cycle; depend on \( \rho_{\mathcal{V}} \) | ID0 |
| **Anti-neutrino mass** | Equal | Equal (mirror configuration); \( \mathcal{F}(\rho_{\mathcal{V}}) \) identical | ID1.1 |
| **Annihilation** | Weak, resonance at \( m_Z \) | Weak, resonance at \( m_Z \); \( \sigma \propto \mathcal{F}(\rho_{\mathcal{V}})^2 \) | ID0 / ID-1 |
| **Majorana/Dirac** | Unsolved | Both possible; depends on loop symmetry; modulated by \( \rho_{\mathcal{V}} \) | ID0 |
| **\( \rho_{\mathcal{V}} \) influence** | (not recognized) | All neutrino properties modulated via \( \mathcal{F}(\rho_{\mathcal{V}}) \) | ID-1 / ID0 |

---

## 8. TESTABLE PREDICTIONS (3.0)

| Prediction | Value | \( \rho_{\mathcal{V}} \) dependence | Test method | ID correspondence |
|------------|-------|-----------------------------------|-------------|-------------------|
| Normal hierarchy | \( m_1 < m_2 < m_3 \) | \( m_i \propto \mathcal{F}(\rho_{\mathcal{V}}) \) | DUNE, Hyper-Kamiokande | ID1.1 |
| Mass ratio | \( m_2/m_1 = m_3/m_2 \approx 5.87 \cdot \mathcal{F}_{i+1}/\mathcal{F}_i \) | Depends on \( \rho_{\mathcal{V}} \) profile | Precise mass measurements | ID1.1 |
| \( \Delta m_{32}^2 / \Delta m_{21}^2 \) | \( \approx 34.5 \pm 2 \cdot (\mathcal{F}_3/\mathcal{F}_1)^2 \) | Depends on \( \rho_{\mathcal{V}} \) | NOvA, T2K, JUNO | ID1.1 |
| Total mass | \( \sum m_i \approx 0.060 \cdot \mathcal{F}(\rho_{\mathcal{V}}) \, \text{eV} \) | Proportional to \( \mathcal{F}(\rho_{\mathcal{V}}) \) | KATRIN, Project 8, cosmology | ID1.1 / ID-1 |
| Annihilation resonance | At \( E \approx 91 \, \text{GeV} \); \( \sigma \propto \mathcal{F}(\rho_{\mathcal{V}})^2 \) | Cross-section varies with \( \rho_{\mathcal{V}} \) | Next-generation neutrino collisions | ID0 / ID-1 |
| Majorana/Dirac | `0νββ` observed/not observed; \( \propto \mathcal{F}(\rho_{\mathcal{V}})^2 \) | Probability depends on \( \rho_{\mathcal{V}} \) | `0νββ` experiments | ID0 |
| Decoherence time | \( \tau_{\text{decoherence}} \propto 1/\rho_{\mathcal{V}} \) | Shorter in high \( \rho_{\mathcal{V}} \) regions | Quantum metrology | ID0 / ID-1 |

---

## 9. CORRESPONDENCE WITH MATHEMATICS 3.0 AND OTHER DOCUMENTS

This document is fully aligned with:

- **MATHEMATICS 3.0** — \( \alpha = 49G_0/(24\pi\hbar c) \), \( \gamma = 2\pi/C \), \( \mathcal{F}(\rho_{\mathcal{V}}) \), \( \mathcal{P}_{L1} \).
- **ID_GRADIENT 3.0** — ID1.1 remains unchanged; \( \rho_{\mathcal{V}} \) correction only for decimal part.
- **MT_QED 3.0** — \( \varepsilon_0, \mu_0 \) as matrix state functions modulating interactions.
- **GRAVITY 3.0** — \( \gamma \) as cyclicity scale.
- **COSMOLOGY 3.0** — \( \mathcal{P}_{L1}, C, \mathcal{F}_n(\rho_{\mathcal{V}}) \).
- **QM_COMPARISON 3.0** — decoherence and \( \rho_{\mathcal{V}} \) influence on quantum effects.

**Key 3.0 changes in the NEUTRINO document:**
1. Methodological prerequisite: MT as a complementary framework for neutrino physics.
2. Mass formulas modulated by \( \mathcal{F}(\rho_{\mathcal{V}}) \) from MATHEMATICS 5.2.
3. Clear \( \rho_{\mathcal{V}} \) dependence for all neutrino properties.
4. \( \alpha \) as matrix structural invariant from MATHEMATICS 3.0.
5. Decoherence time \( \tau_{\text{decoherence}} \propto 1/\rho_{\mathcal{V}} \).
6. References to MATHEMATICS 3.0, MT_QED 3.0, GRAVITY 3.0, COSMOLOGY 3.0, QM_COMPARISON 3.0.

---

## 10. CONCLUSIONS (3.0)

1. **The neutrino in MT is a closed TE transfer loop** with weak TZ attachment, not a point particle.

2. **Neutrino mass can be calculated in two independent ways** — indirect (H-3 quantization) and direct (loop energy). Both are mutually consistent and modulated by \( \mathcal{F}(\rho_{\mathcal{V}}) \).

3. **The three flavors** arise from three different phase windows in the PV cycle, whose positions and widths depend on local \( \rho_{\mathcal{V}} \).

4. **The anti-neutrino** is a mirror configuration with equal mass; \( \mathcal{F}(\rho_{\mathcal{V}}) \) is identical for both.

5. **Annihilation** is energy-dependent with a resonance at the `Z` boson mass; the cross-section is proportional to \( \mathcal{F}(\rho_{\mathcal{V}})^2 \).

6. **The Majorana/Dirac question** in MT is open — both configurations are possible, and experiments will provide the answer. The `0νββ` probability is proportional to \( \mathcal{F}(\rho_{\mathcal{V}})^2 \).

7. **All neutrino properties depend on \( \rho_{\mathcal{V}} \)** — at higher Vertical energy density, masses, oscillation frequencies, and annihilation cross-sections change.

8. **MT predictions** are quantitative and testable with next-generation neutrino experiments (DUNE, Hyper-Kamiokande, JUNO, KATRIN, 0νββ).

---

## NOTE

This document is **version 3.0 of the MT neutrino model**, combining two independent mass calculation methods, incorporating \( \rho_{\mathcal{V}} \) dependence via \( \mathcal{F}(\rho_{\mathcal{V}}) \), and providing quantitative predictions aligned with the ID system (3.0) and MATHEMATICS formalism (3.0). Further development includes precise determination of \( \delta_i \) and \( \mathcal{F}(\rho_{\mathcal{V}}) \) from PV phases and \( \rho_{\mathcal{V}} \) profiles, as well as comparison with experimental data from different regions of the Universe.

---

*Document prepared: July 2026*  
*Version: 3.0 — ρ_V dependence, aligned with MATHEMATICS 3.0*
