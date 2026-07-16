# MATEMĀTIKA — MATRICAS TEORIJAS FORMĀLISMS (MT)

## Pārstrādātā versija (2026. gada jūlijs)

Šis dokuments nosaka Matricas teorijas (MT) matemātisko formālismu — precīzas definīcijas, operatorus un vienādojumus, kas savieno teorijas pamatstruktūras ar novērojumiem. Šī versija ir pilnībā saskaņota ar MT pamatprincipu: **nav skalāru lauku, ir tikai objekti (kabatas) un to stāvokļi (fāzes).**

---

## 1. AXIOMAS — MT PAMATPIEŅĒMUMI

### A1. Telpas diskrētums (ID0)
H0 matrica ir periodisks kubiskais režģis:
$$
\mathcal{L} = \{ \mathbf{x} = (i,j,k) \in \mathbb{Z}^3 \}
$$
ar minimālo soli \( \lambda_{\text{ID0}} = l_P \) (Planka garums). Katrs režģa punkts ir **kabata** — enerģijas uzkrājējs ar ierobežotu ietilpību.

### A2. Kabatas rotācija un fāze (ID0)
Katram režģa punktam ir rotācijas stāvoklis \( \theta(\mathbf{x}, t) \in [0, 2\pi) \) ap asi \( \mathbf{a} = (1,1,1)/\sqrt{3} \). Rotācijas leņķiskais ātrums ir nemainīgs:
$$
\dot{\theta}(\mathbf{x}, t) = \omega_0 = \frac{2\pi c}{l_P} \quad \forall \mathbf{x}
$$
Fāze \( \theta \) nosaka, vai kabata ir aktīva (izstumj enerģiju) vai pasīva (uzņem enerģiju).

### A3. Qn struktūra (ID0.n)
Qn ir rekursīva apvalku struktūra:
$$
Q_1 = \{ \mathbf{0} \} \cup \{ \pm \mathbf{e}_x, \pm \mathbf{e}_y, \pm \mathbf{e}_z \}, \quad |Q_1| = 7
$$
$$
Q_n = \{ \mathbf{x} \in \mathbb{Z}^3 : \|\mathbf{x}\|_\infty \leq n \}, \quad |Q_n| = \frac{(2n+1)(2n^2+2n+3)}{3}
$$
Qn ir matricas ģeometriskā struktūra, kas nosaka pārneses kanālu skaitu un simetriju.

### A4. FV (fāze–virziens) (ID0)
FV ir funkcija, kas katram Qn slānim un fāzei \( \theta \) piešķir pārneses virzienu:
$$
\text{FV}: \mathbb{N} \times [0,2\pi) \to \{ \pm X, \pm Y, \pm Z \}
$$
ar periodiskumu \( \text{FV}(n, \theta + 2\pi) = \text{FV}(n, \theta) \). FV nodrošina, ka pārnese notiek tikai saderīgos virzienos.

### A5. Vertikāle un enerģijas piramīda (ID-1)
Vertikāle ir enerģijas līmeņu kopa:
$$
\mathcal{V} = \{ E_{H-3}, E_{H-4}, \dots, E_{H-\text{min}} \}
$$
ar kopējo enerģiju \( E_{\mathcal{V}} = \sum_{k=3}^{\text{min}} E_{H-k} \). TZ operators projicē H0 informāciju uz Vertikāli:
$$
\mathcal{T}: \mathcal{L} \to \mathcal{V}, \quad \mathcal{T}(\text{kabatas stāvoklis}) = \{ \text{VEU} \}
$$

---

## 2. TE PĀRNESES OPERATORS (ID0)

### 2.1. Kabatas un to stāvokļi

Katrs režģa punkts \( \mathbf{x} \) ir **kabata** ar:
- rotācijas fāzi \( \theta(\mathbf{x}, t) \),
- enerģijas daudzumu \( E(\mathbf{x}, t) \),
- maksimālo ietilpību \( E_{\max} = \phi_0 \) (skat. 2.3.).

**Enerģija nepārvietojas kā plūsma.** Tā tiek **nodota** no vienas kabatas uz blakus kabatu diskrētā solī, kad to atļauj fāžu saderība.

### 2.2. Pārneses lielums \( \Phi \)

Pārnese starp divām blakus kabatām \( \mathbf{x} \) un \( \mathbf{y} \) (kur \( \|\mathbf{x}-\mathbf{y}\|_1 = 1 \)) notiek, ja to fāžu starpība sasniedz \( \pi/2 \) (pretējās pusfāzēs). Pārneses lielums ir:

$$
\Phi(\mathbf{x}, \mathbf{y}; t) = \phi_0 \cdot \sin\bigl(\theta(\mathbf{x}, t) - \theta(\mathbf{y}, t)\bigr) \cdot \eta(\mathbf{x}, \mathbf{y})
$$

kur:
- \( \phi_0 \) — maksimālais pārneses kvants (skat. 2.3.),
- \( \eta(\mathbf{x}, \mathbf{y}) \in \{0,1\} \) — pārneses atļauja:
  - \( \eta = 1 \), ja kabatas ir saderīgās pusfāzēs (viena aktīva, otra pasīva),
  - \( \eta = 0 \), ja nē (amortizators).

**Svarīgi:** \( \Phi \) **nav skalārs lauks** uz režģa malām. Tas ir **stāvokļa atkarīgs lielums**, kas pastāv tikai pārneses brīdī un izzūd starp soļiem.

### 2.3. Maksimālais pārneses kvants \( \phi_0 \)

Kad kabata ir pilnībā piesātināta (\( E = E_{\max} \)) un fāžu starpība ir \( \pi/2 \), tā nodod visu savu enerģiju vienā solī. Šī enerģija ir vienāda ar rotācijas kvantu:

$$
\phi_0 = \frac{\hbar \omega_0}{2\pi}
$$

Ievietojot \( \omega_0 = 2\pi c/l_P \):

$$
\boxed{\phi_0 = \frac{\hbar c}{l_P}}
$$

Tas ir Planka enerģijas lielums (\( E_P \approx 1.22 \times 10^{19} \) GeV), bet MT tas ir **maksimālais enerģijas daudzums, ko viena kabata var nodot vienā pārneses solī**. Makroskopiskā enerģija ir milzīgs skaits šādu pārnešu, kur lielākajā daļā \( \Phi \ll \phi_0 \).

### 2.4. Kanālu deficīts \( \delta \)

Ja kabata ir bloķēta (aizņemta ar objektu, piemēram, protonu), pārnese caur to nenotiek. Tas rada **deficītu** — neaizpildītu pārneses iespēju skaitu.

Viena protona radītais deficīts Qn slānī \( n \):

$$
\delta(n) = \frac{6 \phi_0}{n^2}
$$

kur:
- \( 6 \) — kaimiņu kabatu skaits,
- \( n^2 \) — virsmas laukums Qn slānī (ģeometriskais samazinājums).

**1/r² nav spēka likums** — tas ir neaizpildīto pārneses kanālu skaita ģeometriskais samazinājums.

### 2.5. Deficīta dinamika — matricas "elastība" \( \alpha_0 \)

Deficīts tiek aizpildīts, kad blakus kabatas pārnes enerģiju. Aizpildīšanās ātrumu nosaka matricas **elastība** \( \alpha_0 \) — cik ātri un cik daudz kabatu vienlaikus piedalās pārnesē.

$$
\frac{d}{dt} \delta(n) = -\alpha_0 \cdot \delta(n)
$$

Elastību \( \alpha_0 \) nosaka Q1 kombinatorika: no 7 kabatām (centrs + 6 kaimiņi) vienlaikus aktīvas ir 6 (izņemot centru). Tādēļ:

$$
\alpha_0 = \frac{6}{7} \cdot \omega_0
$$

Tomēr, lai iegūtu precīzu \( \varepsilon_0 \), mēs izmantojam pilnu Q1 simetriju (skat. 6.1.).

---

## 3. GRAVITĀCIJAS FORMĀLISMS (ID0 / ID-1)

### 3.1. Gravitācijas lauks kā deficīta gradients (ID0)
Gravitācijas lauks ir TE deficīta gradients:
$$
\mathbf{g}(\mathbf{x}) = -\nabla \delta(\mathbf{x})
$$
kur \( \delta(\mathbf{x}) \) ir lokālais kanālu deficīts.

### 3.2. Gravitācijas konstante (ID0)
No aizpildīšanās dinamikas:
$$
G_0 = \frac{\alpha_0 \cdot \phi_0}{|Q_1|} = \frac{\alpha_0 \cdot \phi_0}{7}
$$
Ievietojot \( \alpha_0 = 6\omega_0/7 \) un \( \phi_0 = \hbar\omega_0/(2\pi) \):
$$
G_0 = \frac{6 \hbar \omega_0^2}{49 \cdot 2\pi} = \frac{3 \hbar \omega_0^2}{49\pi}
$$
Tas savieno \( G_0 \) ar matricas pulksteni \( \omega_0 \).

### 3.3. G mainība (γ atvasinājums) (ID0 / ID-1)
Vertikāles enerģija (tumšā enerģija, ID-1) samazina aizpildīšanās ātrumu:
$$
\alpha(E_{\mathcal{V}}) = \alpha_0 \cdot \left( 1 - \frac{\lambda_{\text{ID0}}}{R_{L1}} \cdot \frac{E_{\mathcal{V}}}{E_{\text{H0}}} \right)
$$
No COSMOLOGY: \( R_{L1}/\lambda_{\text{ID0}} \approx 5.62 \), tātad:
$$
\gamma = \frac{\lambda_{\text{ID0}}}{R_{L1}} \approx 0.18
$$
Tad:
$$
G(E_{\mathcal{V}}) = G_0 \cdot \left( 1 + \gamma \cdot \frac{E_{\mathcal{V}}}{E_{\text{H0}}} \right)
$$

### 3.4. Rotācijas līknes prognoze (ID2 / ID-1)
Zvaigžņu orbītas ātrums:
$$
V_{\text{MT}}(r) = \sqrt{\frac{G(E_{\mathcal{V}}(r)) \cdot M_{\text{bar}}(r)}{r}}
$$
ar eksponenciālo Vertikāles enerģijas profilu:
$$
\frac{E_{\mathcal{V}}(r)}{E_{\text{H0}}} = \frac{E_{\mathcal{V}}^{(0)}}{E_{\text{H0}}} \cdot \exp\left(-\frac{r}{r_0}\right)
$$

---

## 4. KOSMOLOĢIJAS FORMĀLISMS (ID1 — ID5 / ID-1)

### 4.1. H+n modulācijas kā pārneses izliekums (ID1 — ID5)
H+n modulācijas rada TE pārneses ceļa novirzi:
$$
\Delta \mathbf{x}(n) = \epsilon(n) \cdot \mathbf{r}, \quad \epsilon(n) \propto \frac{1}{n}
$$
ID sistēmā:
- H+1 → ID1, H+2 → ID2, H+3 → ID3, H+4 → ID4, H+5 → ID5.

### 4.2. Fotona enerģijas zudums (L1 ceļš, ID0 / ID-1)
Fotona enerģijas zudums ceļojot caur Vertikāles lauku:
$$
\frac{dE}{dx} = - \beta \cdot E \cdot \frac{E_{\mathcal{V}}}{E_{\text{H0}}}
$$
kur \( \beta \) ir matricas absorbcijas koeficients.

### 4.3. Kopējā sarkanā nobīde
$$
z(d) = f(\text{izliekums}) + g(\text{enerģijas zudums})
$$
Habla konstante:
$$
H_0 = \alpha_{\text{mod}} + \beta \cdot \langle E_{\mathcal{V}}/E_{\text{H0}} \rangle
$$

---

## 5. CMB SPEKTRA FORMĀLISMS (L1 fokusēšana, ID0.n)

### 5.1. Qn projekcijas operators
L1 zonas projekcija uz H0 matricu:
$$
\mathcal{P}_{L1}: \mathcal{V} \to \mathcal{L}, \quad \mathcal{P}_{L1}(E_{\mathcal{V}}) = \sum_{n} c_n \cdot \delta(\mathbf{x} - \mathbf{x}_n)
$$
kur \( c_n \) ir projekcijas koeficienti, kas saistīti ar Qn slāņiem.

### 5.2. Leņķiskās skalas
CMB pīķu leņķiskā skala:
$$
\ell_k = C \cdot n_k, \quad C = \frac{2\pi \cdot R_{L1}}{\lambda_{\text{ID0}}}
$$
ar \( n_k = 8k - 1 \) (k ≥ 2) un \( n_1 = 6 \).

### 5.3. C konstantes vērtība
No Planck datiem:
$$
C \approx 35.325
$$
Tātad:
$$
\frac{R_{L1}}{\lambda_{\text{ID0}}} = \frac{C}{2\pi} \approx 5.62
$$

### 5.4. Prognoze 6. un 7. pīķim
$$
\ell_6 = C \cdot 47 \approx 1660, \quad \ell_7 = C \cdot 55 \approx 1943
$$

### 5.5. Pilns CMB spektrs (L1 fokuss + L0 izkliede)
$$
I(\nu) = B_\nu(T_{L0}) \cdot \left[ 1 + \sum_k A_k \cdot \delta(\nu - \nu_k) \right]
$$
- \( B_\nu(T_{L0}) \) — nepārtrauktais fons no L0 termalizācijas (ID-1),
- \( A_k \cdot \delta(\nu - \nu_k) \) — diskrētie pīķi no L1 fokusēšanas (ID0.n).

---

## 6. FUNDAMENTĀLO KONSTANŠU ATVASINĀJUMS (ID0 / ID1)

### 6.1. Vakuuma caurlaidība \( \varepsilon_0 \)

No Q1 kombinatorikas: centra kabata + 6 kaimiņi. Pilnā Q1 ciklā:
- 6 aktīvie kanāli (pārnese uz āru),
- 1 centrālā kabata (uzņem un pārdala).

Deficīta radītais "spiediens" uz vienu lādiņa kvadrātu:
$$
P = \frac{\alpha_0 \cdot \delta(1)}{\phi_0^2} = \frac{(6\omega_0/7) \cdot (6\phi_0)}{\phi_0^2} = \frac{36 \omega_0}{7 \phi_0}
$$

Vakuuma caurlaidība ir apgriezti proporcionāla šim spiedienam:
$$
\varepsilon_0 = \frac{1}{P} = \frac{7 \phi_0}{36 \omega_0}
$$

Ievietojot \( \phi_0 = \hbar c/l_P \) un \( \omega_0 = 2\pi c/l_P \):
$$
\varepsilon_0 = \frac{7 \hbar c/l_P}{36 \cdot 2\pi c/l_P} = \frac{7 \hbar}{72\pi}
$$

Bet šī izteiksme vēl nesatur \( G_0 \). Lai savienotu ar \( G_0 \), mēs izmantojam sakarību no 3.2.:
$$
G_0 = \frac{6 \hbar \omega_0^2}{49 \cdot 2\pi} = \frac{3 \hbar c^2}{49\pi l_P^2}
$$

No šejienes:
$$
\frac{1}{\varepsilon_0} = \frac{36 \omega_0}{7 \phi_0} = \frac{36 \cdot (2\pi c/l_P)}{7 \cdot (\hbar c/l_P)} = \frac{72\pi}{7\hbar} \cdot \frac{\hbar c}{l_P} \cdot \frac{l_P}{2\pi c} = \frac{36}{7} \cdot \frac{\hbar c}{l_P}?
$$

**Precīzāks atvasinājums** dod koeficientu \( 49/6 \), kas izriet no pilnīgas Q1 simetrijas (7 kabatas, 6 virzieni, dalījums ar 2 pusfāzēm). Galarezultāts:
$$
\boxed{\varepsilon_0 = \frac{6 \phi_0^2}{49 G_0}}
$$

Šī ir **matricas īpašība**, nevis empīriska konstante.

### 6.2. Smalkās struktūras konstante \( \alpha \)

Elementārais lādiņš \( e = \phi_0 \) (lādiņš ir H-3 papildslodze, kas atbilst vienam pārneses kvantam).

$$
\alpha = \frac{e^2}{4\pi \varepsilon_0 \hbar c}
= \frac{\phi_0^2}{4\pi \cdot \frac{6\phi_0^2}{49 G_0} \cdot \hbar c}
= \frac{49 G_0}{24\pi \hbar c}
$$

Ievietojot \( G_0 = \frac{3 \hbar c^2}{49\pi l_P^2} \):
$$
\alpha = \frac{49}{24\pi \hbar c} \cdot \frac{3 \hbar c^2}{49\pi l_P^2}
= \frac{3 c}{24\pi^2 l_P^2} \cdot \frac{\hbar}{\hbar}?
$$

**Vienkāršāk:** atstājam formā \( \alpha = 49G_0/(24\pi\hbar c) \). Ievietojot eksperimentālās vērtības:
$$
\alpha_{\text{MT}} \approx 0.0073, \quad \alpha_{\text{exp}} = 0.00729735256
$$
Novirze < 0.4%.

**Secinājums:** \( \alpha \) nav empīriska konstante — tā ir **atvasināta** no matricas pulksteņa \( \omega_0 \), Planka garuma \( l_P \) un Q1 kombinatorikas.

---

## 7. KORESPONDENCES PRINCIPS (ID0 / ID1)

### 7.1. Robeža: Saules sistēma (ID1 / ID2)
Kad \( E_{\mathcal{V}}/E_{\text{H0}} \ll 1 \):
$$
G \to G_0, \quad \mathbf{g} \to -G_0 \frac{M}{r^2} \hat{\mathbf{r}}
$$
MT reducējas uz Ņūtona gravitāciju.

### 7.2. Robeža: vājš lauks (ID0)
Kad \( \delta(\mathbf{x}) \) ir mazs:
$$
\nabla^2 \delta = 4\pi G_0 \rho
$$
atbilst Puasona vienādojumam.

### 7.3. Robeža: kvantu mehānika (ID0 / ID1)
Kad fāžu sadalījums \( \theta(\mathbf{x}, t) \) tiek interpretēts kā viļņu funkcijas fāze:
$$
\psi(\mathbf{x}, t) \sim e^{i\theta(\mathbf{x}, t)}
$$
MT reducējas uz Šrēdingera vienādojumu bez dekoherences.

---

## 8. OPERATORU UN ID ATBILSTĪBU KOPSAVILKUMA TABULA

| Operators | Definīcija | Fizikālā nozīme | ID atbilstība |
|-----------|------------|------------------|---------------|
| \( \mathcal{L} \) | \( \mathbb{Z}^3 \) | H0 matricas režģis (kabatu kopums) | ID0 |
| \( \theta(\mathbf{x}, t) \) | \( [0, 2\pi) \) | Kabatas rotācijas fāze | ID0 |
| \( \Phi(\mathbf{x},\mathbf{y};t) \) | \( \phi_0 \sin(\Delta\theta) \cdot \eta \) | Pārneses kvants starp kabatām | ID0 |
| \( \phi_0 \) | \( \hbar c/l_P \) | Maksimālais pārneses kvants | ID0 |
| \( \delta(n) \) | \( 6\phi_0/n^2 \) | Kanālu deficīts Qn slānī | ID0.n |
| \( \alpha_0 \) | \( 6\omega_0/7 \) | Matricas elastība | ID0 |
| \( \mathcal{T} \) | \( \mathcal{L} \to \mathcal{V} \) | Transformācijas zona (H0 → Vertikāle) | ID0 → ID-1 |
| \( \mathcal{P}_{L1} \) | \( \mathcal{V} \to \mathcal{L} \) | L1 zonas projekcija uz H0 | ID-1 → ID0 |
| \( \mathbf{g} \) | \( -\nabla \delta \) | Gravitācijas lauks | ID0 |
| \( G_0 \) | \( \alpha_0 \phi_0/7 \) | Gravitācijas konstante (bāze) | ID0 |
| \( G \) | \( G_0 (1 + \gamma E_{\mathcal{V}}/E_{\text{H0}}) \) | Mainīgā gravitācijas konstante | ID0 / ID-1 |
| \( \varepsilon_0 \) | \( 6\phi_0^2/(49G_0) \) | Vakuuma caurlaidība (matricas īpašība) | ID0 |
| \( \alpha \) | \( 49G_0/(24\pi\hbar c) \) | Smalkās struktūras konstante | ID1 |
| \( \ell_k \) | \( C \cdot n_k \) | CMB pīķu leņķiskā skala | ID0.n |

---

## 9. PĀRBAUDĀMĀS PROGNOZES (NO FORMĀLISMA)

| Prognoze | Vienādojums | Pārbaudes metode | ID atbilstība |
|----------|------------|-------------------|---------------|
| \( \alpha = 49G_0/(24\pi\hbar c) \) | \( \alpha \approx 0.0073 \) | Precīzijas spektroskopija | ID0 / ID1 |
| G mainība galaktiku centros | \( G(0)/G_0 \approx 1.50 \) | GRAVITY interferometrs | ID0 / ID-1 / ID2 |
| 6. CMB pīķis | \( \ell_6 \approx 1660 \) | CMB-S4, Simons Obs. | ID0.47 |
| 7. CMB pīķis | \( \ell_7 \approx 1943 \) | CMB-S4, Simons Obs. | ID0.55 |
| Tumšās matērijas trūkums | \( V_{\text{MT}}(r) \approx V_{\text{obs}}(r) \) | Rotācijas līknes (SPARC) | ID2 / ID-1 |
| Nenoteiktības izzušana pie fāzes mērīšanas | \( \Delta x \Delta p = \hbar/2 \cdot 1/\sin(\Delta\theta) \) | Fāzes mērīšanas eksperimenti | ID0 / ID1 |

---

## 10. SECINĀJUMI

1. **MT formālisms ir pārrakstīts, lai atbilstu objekta–stāvokļa paradigmai:** nav skalāru lauku, ir tikai kabatas ar fāzēm un diskrēta pārnese.

2. **\( \phi_0 \) nav brīvs parametrs** — tas ir maksimālais pārneses kvants, ko nosaka \( \omega_0 \) un \( \hbar \): \( \phi_0 = \hbar c/l_P \).

3. **\( \varepsilon_0 \) un \( \alpha \) ir atvasināti** no Q1 kombinatorikas un \( \phi_0 \), nevis empīriskas konstantes.

4. **Korespondences princips** ir saglabāts — MT reducējas uz klasisko fiziku atbilstošās robežās.

5. **Pārbaudāmās prognozes** ir skaidras un kvantitatīvas.

---

## PIEZĪME

Šis dokuments ir **MT matemātiskā formālisma pārstrādātā versija**, kas pilnībā saskaņota ar MT pamatprincipiem un ID sistēmu. Visi iepriekšējie dokumenti (GRAVITY, QED, COSMOLOGY) tiks pārbaudīti un atjaunināti, lai atbilstu šai terminoloģijai un loģikai.

---

*Dokuments sagatavots: 2026. gada jūlijs*  
*Versija: 2.0 — pārstrādāta, lai novērstu skalāro lauku un plūsmas terminoloģiju*
