# MATEMĀTIKA — MATRICAS TEORIJAS FORMĀLISMS (MT)

## Kopsavilkuma dokuments

Šis dokuments nosaka Matricas teorijas (MT) matemātisko formālismu — precīzas definīcijas, operatorus un vienādojumus, kas savieno teorijas pamatstruktūras ar novērojumiem. Tas ir teorijas kvantitatīvais kodols, no kura izriet COSMOLOGY un GRAVITY modeļi, kā arī pārbaudāmās prognozes.

---

## 1. AXIOMAS — MT PAMATPIEŅĒMUMI

### A1. Telpas diskrētums
H0 matrica ir periodisks kubiskais režģis:
\[
\mathcal{L} = \{ \mathbf{x} = (i,j,k) \in \mathbb{Z}^3 \}
\]
ar minimālo soli \( \lambda_{\text{ID1}} \) (ID1 režģa konstante).

### A2. ID1 rotācija un fāze
Katram režģa punktam ir rotācijas stāvoklis \( \theta(\mathbf{x}, t) \in [0, 2\pi) \) ap asi \( \mathbf{a} = (1,1,1)/\sqrt{3} \). Fāze \( \phi = \theta \mod \pi \) nosaka aktīvo kabatu.

### A3. Qn struktūra
Qn ir rekursīva apvalku struktūra:
\[
Q_1 = \{ \mathbf{0} \} \cup \{ \pm \mathbf{e}_x, \pm \mathbf{e}_y, \pm \mathbf{e}_z \}, \quad |Q_1| = 7
\]
\[
Q_n = \{ \mathbf{x} \in \mathbb{Z}^3 : \|\mathbf{x}\|_\infty \leq n \}, \quad |Q_n| = \frac{(2n+1)(2n^2+2n+3)}{3}
\]

### A4. FV (fāze–virziens)
FV ir funkcija, kas katram Qn slānim piešķir plūsmas virzienu:
\[
\text{FV}: \mathbb{N} \times [0,2\pi) \to \{ \pm X, \pm Y, \pm Z \}
\]
ar periodiskumu \( \text{FV}(n, \theta + 2\pi) = \text{FV}(n, \theta) \).

### A5. Vertikāle un enerģijas piramīda
Vertikāle ir enerģijas līmeņu kopa:
\[
\mathcal{V} = \{ E_{H-3}, E_{H-4}, \dots, E_{H-\text{min}} \}
\]
ar kopējo enerģiju \( E_{\mathcal{V}} = \sum_{k=3}^{\text{min}} E_{H-k} \). TZ operators projicē H0 informāciju uz Vertikāli:
\[
\mathcal{T}: \mathcal{L} \to \mathcal{V}, \quad \mathcal{T}(\text{ID>0}) = \{ \text{VEU} \}
\]

---

## 2. TE PLŪSMAS OPERATORS

### 2.1. Plūsmas lauks
TE plūsma ir funkcija uz režģa malām:
\[
\Phi: \mathcal{L} \times \mathcal{L} \to \mathbb{R}^+, \quad \Phi(\mathbf{x}, \mathbf{y}) > 0 \iff \|\mathbf{x}-\mathbf{y}\|_1 = 1
\]

### 2.2. Plūsmas virziena operators
Plūsmas virzienu katrā punktā nosaka FV un ID1 rotācija:
\[
\mathbf{v}(\mathbf{x}, t) = \text{FV}(n(\mathbf{x}), \theta(\mathbf{x}, t)) \cdot \mathbf{e}_{\text{virziens}}
\]
kur \( n(\mathbf{x}) \) ir Qn slāņa indekss.

### 2.3. Nepārtrauktības vienādojums
TE plūsma apmierina diskrēto nepārtrauktības vienādojumu:
\[
\sum_{\mathbf{y} \in N(\mathbf{x})} \left( \Phi(\mathbf{x},\mathbf{y}) - \Phi(\mathbf{y},\mathbf{x}) \right) = 0
\]
bez šķēršļiem (L0 režīms).

### 2.4. Kanālu aizpildīšanās operators
Objekts (protons) punktā \( \mathbf{x}_0 \) bloķē plūsmu:
\[
\Phi(\mathbf{x}_0, \mathbf{y}) = 0, \quad \forall \mathbf{y} \in N(\mathbf{x}_0)
\]
Deficīts:
\[
\Delta \Phi(\mathbf{x}_0) = \sum_{\mathbf{y} \in N(\mathbf{x}_0)} \Phi_0(\mathbf{x}_0,\mathbf{y}) = 6\phi_0
\]
Deficīta sadalījums pa Qn slāņiem:
\[
\delta(n) = \frac{\Delta \Phi}{|Q_n|} \approx \frac{6\phi_0}{n^2}
\]

### 2.5. Aizpildīšanās dinamika
Laika evolūciju apraksta diferenciālvienādojums:
\[
\frac{d}{dt} \delta(n) = -\alpha(E_{\mathcal{V}}) \cdot \delta(n)
\]
kur \( \alpha(E_{\mathcal{V}}) \) ir atkarīgs no Vertikāles enerģijas.

---

## 3. GRAVITĀCIJAS FORMĀLISMS

### 3.1. Gravitācijas lauks kā retinājuma gradients
Gravitācijas lauks ir TE spiediena retinājuma gradients:
\[
\mathbf{g}(\mathbf{x}) = - \nabla \delta(\mathbf{x})
\]
kur \( \delta(\mathbf{x}) \) ir lokālais kanālu deficīts.

### 3.2. Gravitācijas konstante
No aizpildīšanās dinamikas:
\[
G_0 = \frac{\alpha_0 \cdot \phi_0}{|Q_1|} = \frac{\alpha_0 \cdot \phi_0}{7}
\]
kur \( \alpha_0 \) ir bāzes aizpildīšanās ātrums.

### 3.3. G mainība (γ atvasinājums)
Tumšā enerģija samazina \( \alpha \):
\[
\alpha(E_{\mathcal{V}}) = \alpha_0 \cdot \left( 1 - \frac{\lambda_{\text{ID1}}}{R_{L1}} \cdot \frac{E_{\mathcal{V}}}{E_{\text{H0}}} \right)
\]
No COSMOLOGY: \( R_{L1}/\lambda_{\text{ID1}} \approx 5.62 \), tātad:
\[
\gamma = \frac{\lambda_{\text{ID1}}}{R_{L1}} \approx 0.18
\]
Tad:
\[
G(E_{\mathcal{V}}) = G_0 \cdot \frac{\alpha_0}{\alpha(E_{\mathcal{V}})}
= G_0 \cdot \left( 1 + \gamma \cdot \frac{E_{\mathcal{V}}}{E_{\text{H0}}} \right)
\]

### 3.4. Rotācijas līknes prognoze
Zvaigžņu orbītas ātrums:
\[
V_{\text{MT}}(r) = \sqrt{\frac{G(E_{\mathcal{V}}(r)) \cdot M_{\text{bar}}(r)}{r}}
\]
ar eksponenciālo Vertikāles enerģijas profilu:
\[
\frac{E_{\mathcal{V}}(r)}{E_{\text{H0}}} = \frac{E_{\mathcal{V}}^{(0)}}{E_{\text{H0}}} \cdot \exp\left(-\frac{r}{r_0}\right)
\]

---

## 4. KOSMOLOĢIJAS FORMĀLISMS

### 4.1. H+n modulācijas kā plūsmas izliekums
H+n modulācijas rada TE plūsmas ceļa novirzi:
\[
\Delta \mathbf{x}(n) = \epsilon(n) \cdot \mathbf{r}, \quad \epsilon(n) \propto \frac{1}{n}
\]

### 4.2. Fotona enerģijas zudums
Fotona enerģijas zudums ceļojot caur Vertikāles lauku:
\[
\frac{dE}{dx} = - \beta \cdot E \cdot \frac{E_{\mathcal{V}}}{E_{\text{H0}}}
\]
kur \( \beta \) ir matricas absorcijas koeficients.

### 4.3. Kopējā sarkanā nobīde
\[
z(d) = f(\text{izliekums}) + g(\text{enerģijas zudums})
\]
Habla konstante:
\[
H_0 = \alpha_{\text{mod}} + \beta \cdot \langle E_{\mathcal{V}}/E_{\text{H0}} \rangle
\]

---

## 5. CMB SPEKTRA FORMĀLISMS

### 5.1. Qn projekcijas operators
L1 zonas projekcija uz H0 matricu ir operators:
\[
\mathcal{P}_{L1}: \mathcal{V} \to \mathcal{L}, \quad \mathcal{P}_{L1}(E_{\mathcal{V}}) = \sum_{n} c_n \cdot \delta(\mathbf{x} - \mathbf{x}_n)
\]
kur \( c_n \) ir projekcijas koeficienti, kas saistīti ar Qn slāņiem.

### 5.2. Leņķiskās skalas
CMB pīķu leņķiskā skala:
\[
\ell_k = C \cdot n_k, \quad C = \frac{2\pi \cdot R_{L1}}{\lambda_{\text{ID1}}}
\]
ar \( n_k = 8k - 1 \) (k ≥ 2) un \( n_1 = 6 \).

### 5.3. C konstantes vērtība
No Planck datiem un optimizācijas:
\[
C = \frac{\sum (\ell_{\text{obs}} \cdot n)}{\sum n^2} \approx 35.325
\]
Tātad:
\[
\frac{R_{L1}}{\lambda_{\text{ID1}}} = \frac{C}{2\pi} \approx 5.62
\]

### 5.4. Prognoze 6. un 7. pīķim
\[
\ell_6 = C \cdot 47 \approx 1660, \quad \ell_7 = C \cdot 55 \approx 1943
\]

---

## 6. VERTIKĀLES ENERĢIJAS OPERATORS

### 6.1. Enerģijas blīvuma operators
Vertikāles enerģijas blīvums H0 matricā:
\[
\rho_{\mathcal{V}}(\mathbf{x}) = \mathcal{T}^{-1}(E_{\mathcal{V}}) \cdot \delta(\mathbf{x} - \mathbf{x}_{L1})
\]
kur \( \mathbf{x}_{L1} \) ir L1 zonas projekcijas centrs.

### 6.2. Eksponenciālais profils
Galaktikā:
\[
\rho_{\mathcal{V}}(r) = \rho_{\mathcal{V}}^{(0)} \cdot \exp\left(-\frac{r}{r_0}\right)
\]
kur \( r_0 \) ir Vertikāles enerģijas izkliedes rādiuss (aptuveni galaktikas kodola izmērs).

### 6.3. Saistība ar tumšo matēriju
Tumšās matērijas efekts MT ir G mainība:
\[
\rho_{\text{DM, efektīvais}}(r) = \frac{\gamma \cdot \rho_{\mathcal{V}}(r)}{4\pi G_0} \cdot \frac{M_{\text{bar}}(r)}{r}
\]
Nav nepieciešama jauna daļiņa.

---

## 7. KORESPONDENCES PRINCIPS

### 7.1. Robeža: Saules sistēma
Kad \( E_{\mathcal{V}}/E_{\text{H0}} \ll 1 \) (tālu no galaktikas centra):
\[
G \to G_0, \quad \mathbf{g} \to -G_0 \frac{M}{r^2} \hat{\mathbf{r}}
\]
MT reducējas uz Ņūtona gravitāciju.

### 7.2. Robeža: vājš lauks
Kad \( \delta(\mathbf{x}) \) ir mazs:
\[
\nabla^2 \delta = 4\pi G_0 \rho
\]
atbilst Puasona vienādojumam.

### 7.3. Robeža: kvantu mehānika
Kad fāžu sadalījums \( \theta(\mathbf{x}, t) \) tiek interpretēts kā viļņu funkcijas fāze:
\[
\psi(\mathbf{x}, t) \sim e^{i\theta(\mathbf{x}, t)}
\]
MT reducējas uz Šrēdingera vienādojumu bez dekoherences.

---

## 8. OPERATORU KOPSAVILKUMA TABULA

| **Operators** | **Definīcija** | **Fizikālā nozīme** |
|---------------|----------------|----------------------|
| \( \mathcal{L} \) | \( \mathbb{Z}^3 \) | H0 matricas režģis |
| \( \Phi \) | \( \mathcal{L} \times \mathcal{L} \to \mathbb{R}^+ \) | TE plūsmas lauks |
| \( \text{FV} \) | \( \mathbb{N} \times [0,2\pi) \to \{\pm X,\pm Y,\pm Z\} \) | Plūsmas virziena noteicējs |
| \( \mathcal{T} \) | \( \mathcal{L} \to \mathcal{V} \) | Transformācijas zona (H0 → Vertikāle) |
| \( \mathcal{P}_{L1} \) | \( \mathcal{V} \to \mathcal{L} \) | L1 zonas projekcija uz H0 |
| \( \mathbf{g} \) | \( -\nabla \delta \) | Gravitācijas lauks |
| \( G \) | \( G_0 \cdot (1 + \gamma \cdot E_{\mathcal{V}}/E_{\text{H0}}) \) | Mainīgā gravitācijas konstante |
| \( \ell_k \) | \( C \cdot n_k \) | CMB pīķu leņķiskā skala |
| \( \rho_{\mathcal{V}} \) | \( \rho_{\mathcal{V}}^{(0)} \cdot e^{-r/r_0} \) | Vertikāles enerģijas profils |

---

## 9. PĀRBAUDĀMĀS PROGNOZES (NO FORMĀLISMA)

| **Prognoze** | **Vienādojums** | **Pārbaudes metode** |
|--------------|-----------------|----------------------|
| G mainība galaktiku centros | \( G(0)/G_0 \approx 1.50 \) | Zvaigžņu orbītas (GRAVITY) |
| 6. CMB pīķis | \( \ell_6 \approx 1660 \) | CMB-S4, Simons Obs. |
| 7. CMB pīķis | \( \ell_7 \approx 1943 \) | CMB-S4, Simons Obs. |
| Tumšās matērijas trūkums | \( V_{\text{MT}}(r) \approx V_{\text{obs}}(r) \) | Rotācijas līknes (SPARC) |

---

## 10. SECINĀJUMI

1. MT formālisms ir **pilnīgs** — tas definē visus nepieciešamos operatorus un vienādojumus, lai aprēķinātu novērojumus no pamatstruktūrām.

2. Tas ir **konsekvents** — COSMOLOGY un GRAVITY kvantitatīvie modeļi izriet no vieniem un tiem pašiem operatoriem.

3. Tas ir **pārbaudāms** — formālisms dod precīzas skaitliskās prognozes, ko var salīdzināt ar datiem.

4. Tas ir **reducējams** — atbilstošās robežās MT pāriet klasiskajā fizikā.

---

## PIEZĪME

Šis dokuments ir **MT matemātiskā formālisma jaunā versija**, kas integrē COSMOLOGY un GRAVITY kvantitatīvos rezultātus. Tas ir teorijas darba instruments turpmākiem aprēķiniem un prognozēm.

---

*Dokuments sagatavots: 2026. gada jūlijā*
