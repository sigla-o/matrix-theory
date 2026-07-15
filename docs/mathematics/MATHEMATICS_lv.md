# MATEMĀTIKA — MT FORMĀLISMS
## Stingrā akadēmiskā versija

Šis dokuments sniedz precīzu MT operatoru, aksiomu un vienādojumu kopumu, no kuriem izriet kosmoloģiskie un gravitācijas modeļi.

---

## 1. AKSIOMAS

**A1. Telpas diskrētums:** H0 = periodisks kubiskais režģis \( \mathcal{L} = \mathbb{Z}^3 \) ar soli \( \lambda_{\text{ID1}} \).

**A2. ID1 rotācija:** Katram punktam \( \theta(\mathbf{x}, t) \in [0, 2\pi) \) ap asi \( (1,1,1)/\sqrt{3} \). Fāze \( \phi = \theta \mod \pi \) nosaka aktīvo kanālu.

**A3. Qn struktūra:** \( Q_n = \{\mathbf{x}: \|\mathbf{x}\|_\infty \leq n\} \), \( |Q_n| = \frac{(2n+1)(2n^2+2n+3)}{3} \).

**A4. FV operators:** \( \text{FV}: \mathbb{N} \times [0,2\pi) \to \{\pm X,\pm Y,\pm Z\} \), periodisks \( 2\pi \).

**A5. Vertikāle:** \( \mathcal{V} = \{E_{H-3}, ..., E_{H-\text{min}}\} \). \( \mathcal{T}: \mathcal{L} \to \mathcal{V} \) projicē ID>0 uz VEU.

---

## 2. TE PLŪSMAS OPERATORS

\( \Phi: \mathcal{L} \times \mathcal{L} \to \mathbb{R}^+ \), definēts tikai blakus punktiem (\( \|\mathbf{x}-\mathbf{y}\|_1 = 1 \)).

Plūsmas virziens:
\[
\mathbf{v}(\mathbf{x}, t) = \text{FV}(n(\mathbf{x}), \theta(\mathbf{x}, t)) \cdot \mathbf{e}_{\text{virziens}}
\]

Nepārtrauktības vienādojums bez šķēršļiem:
\[
\sum_{\mathbf{y} \in N(\mathbf{x})} (\Phi(\mathbf{x},\mathbf{y}) - \Phi(\mathbf{y},\mathbf{x})) = 0
\]

Objekts (protons) punktā \( \mathbf{x}_0 \) bloķē plūsmu:
\[
\Phi(\mathbf{x}_0, \mathbf{y}) = 0, \quad \Delta \Phi(\mathbf{x}_0) = 6\phi_0
\]
Deficīts:
\[
\delta(n) = \frac{6\phi_0}{n^2}
\]

Aizpildīšanās dinamika:
\[
\frac{d}{dt} \delta(n) = -\alpha(E_{\mathcal{V}}) \cdot \delta(n), \quad \alpha(E_{\mathcal{V}}) = \alpha_0 \left(1 - \gamma \frac{E_{\mathcal{V}}}{E_{\text{H0}}}\right)
\]

---

## 3. GRAVITĀCIJAS FORMĀLISMS

Gravitācijas lauks = retinājuma gradients:
\[
\mathbf{g}(\mathbf{x}) = -\nabla \delta(\mathbf{x})
\]

Gravitācijas konstante:
\[
G_0 = \frac{\alpha_0 \phi_0}{7}
\]

G mainība:
\[
G(E_{\mathcal{V}}) = G_0 \left(1 + \gamma \frac{E_{\mathcal{V}}}{E_{\text{H0}}}\right), \quad \gamma \approx 0.18
\]

Rotācijas ātrums:
\[
V_{\text{MT}}(r) = \sqrt{\frac{G(E_{\mathcal{V}}(r)) M_{\text{bar}}(r)}{r}}, \quad \frac{E_{\mathcal{V}}(r)}{E_{\text{H0}}} = \frac{E_{\mathcal{V}}^{(0)}}{E_{\text{H0}}} e^{-r/r_0}
\]

---

## 4. KOSMOLOĢIJAS FORMĀLISMS

H+n modulāciju izliekums:
\[
\Delta \mathbf{x}(n) = \epsilon(n) \mathbf{r}, \quad \epsilon(n) \propto 1/n
\]

Fotona enerģijas zudums:
\[
\frac{dE}{dx} = -\beta E \frac{E_{\mathcal{V}}}{E_{\text{H0}}}
\]

Habla konstante:
\[
H_0 = \alpha_{\text{mod}} + \beta \left\langle \frac{E_{\mathcal{V}}}{E_{\text{H0}}} \right\rangle
\]

---

## 5. CMB PROJEKCIJA

\( \mathcal{P}_{L1}: \mathcal{V} \to \mathcal{L} \), \( \mathcal{P}_{L1}(E_{\mathcal{V}}) = \sum_n c_n \delta(\mathbf{x} - \mathbf{x}_n) \).

Leņķiskās skalas:
\[
\ell_k = C \cdot n_k, \quad C = \frac{2\pi R_{L1}}{\lambda_{\text{ID1}}} \approx 35.325, \quad n_k = 8k - 1 \ (k \ge 2), \ n_1 = 6
\]

Prognoze: \( \ell_6 \approx 1660, \ \ell_7 \approx 1943 \).

---

## 6. KORESPONDENCES PRINCIPS

- Ja \( E_{\mathcal{V}}/E_{\text{H0}} \ll 1 \): \( G \to G_0 \), \( \mathbf{g} \to -G_0 M/r^2 \hat{\mathbf{r}} \) (Ņūtons).
- Ja \( \delta \) mazs: \( \nabla^2 \delta = 4\pi G_0 \rho \) (Puasons).
- Ja fāžu sadalījums interpretējams kā viļņu funkcija: \( \psi \sim e^{i\theta} \) (Šrēdingers).
