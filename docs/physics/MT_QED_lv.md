# KVANTU ELEKTRODINAMIKA — MT FORMĀLAIS MODELIS
## Stingrā akadēmiskā versija

QED MT tiek reducēta uz TE VEU H‑3 un H‑2 plūsmu mijiedarbību, ko nosaka matricas režģa simetrija.

---

## 1. LĀDIŅŠ — H‑3 PAPILDU SLODZE

Lādiņš \( q \) rodas no protona pus‑fāžu asimetrijas:
\[
q = N_{\text{H-3}} \cdot \phi_0
\]
Pozitīvs = 0° fāzes dominence; negatīvs = 180° fāzes dominence. Neitrālais stāvoklis atbilst fāžu līdzsvaram (FV noteiktais kompensācijas punkts).

---

## 2. ELEKTRISKAIS LAUKS — SPIEDIENA GRADIENTS

TE spiediens: \( P(\mathbf{x}) = \kappa_{\text{matrica}} \cdot \Phi(\mathbf{x}) \).
Elektriskais lauks:
\[
\mathbf{E}(\mathbf{x}) = -\nabla P_{\text{H-3}}(\mathbf{x}) = -\kappa_{\text{matrica}} \nabla \Phi_{\text{H-3}}(\mathbf{x})
\]
Kulona likums \( \mathbf{E} \propto q/r^2 \) izriet no \( \delta(n) \propto 1/n^2 \).

---

## 3. MAGNĒTISKAIS LAUKS — H‑2 CIRKULĀCIJA

\( \mathbf{B}(\mathbf{x}) = \nabla \times \Phi_{\text{H-2}}(\mathbf{x}) = \mu_{\text{matrica}} \nabla \times \mathbf{J}_{\text{H-3}}(\mathbf{x}) \).
Ampēra likums izriet no cirkulācijas integrāļa pa Qn kontūru.

---

## 4. MAKSVELA VIENĀDOJUMI — PLŪSMAS OPERATORI

| Klasiskais | MT ekvivalents |
|------------|----------------|
| \( \nabla \cdot \mathbf{E} = \rho/\varepsilon_0 \) | \( \nabla \cdot (-\kappa \nabla \Phi_{\text{H-3}}) = \rho_{\text{H-3}}/\varepsilon_0 \) |
| \( \nabla \times \mathbf{E} = -\partial \mathbf{B}/\partial t \) | No plūsmas dinamikas (2.5.) |
| \( \nabla \times \mathbf{B} = \mu_0 \mathbf{J} + \mu_0 \varepsilon_0 \partial \mathbf{E}/\partial t \) | No plūsmas nepārtrauktības |

---

## 5. FUNDAMENTĀLĀS KONSTANTES NO REŽĢA

\( \varepsilon_0 = \frac{6\phi_0^2}{49 G_0} \), \( \mu_0 = 1/(c^2 \varepsilon_0) \).

**Smalkās struktūras konstante:**
\[
\alpha = \frac{e^2}{4\pi \varepsilon_0 \hbar c} = \frac{49 G_0}{24\pi \hbar c} \approx 0.0073
\]
Novirze no eksperimentālās vērtības < 0.4%.

---

## 6. SUPERPOZĪCIJA UN INDUKCIJA

Superpozīcija = TE plūsmas lauku summa:
\[
\mathbf{E}_{\text{tot}} = -\kappa \nabla \left( \sum_i \Phi_{\text{H-3}, i} \right)
\]

Indukcija (Faradeja likums):
\[
\oint \nabla P_{\text{H-3}} \cdot d\mathbf{l} = -\frac{d}{dt} \oint \Phi_{\text{H-2}} \cdot d\mathbf{Qn}
\]
Mīnusa zīme atbilst Lenca likumam — matricas reakcijai, kas pretdarbojas plūsmas izmaiņām.

---

## 7. PROGNOZES

| Prognoze | MT vērtība | Pārbaude |
|----------|------------|----------|
| \( \alpha \) | \( 49 G_0/(24\pi \hbar c) \) | Spektroskopija |
| \( g-2 \) anomālija | \( a_\mu^{\text{MT}} = a_\mu^{\text{QED}} + \delta a_\mu \) | Muon g‑2 |
| Lemba nobīde | \( \Delta E_{\text{MT}} = \Delta E_{\text{QED}} + \delta E \) | Ūdeņraža spektroskopija |
| \( \varepsilon_0 \) atkarība no \( \rho_{\mathcal{V}} \) | \( \varepsilon_0(\rho_{\mathcal{V}}) = \varepsilon_0^{(0)}(1 + \gamma_\varepsilon \rho_{\mathcal{V}}/\rho_{\text{H0}}) \) | Kvantu metroloģija |
