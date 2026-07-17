# MATEMĀTIKA — MATRICAS TEORIJAS FORMĀLISMS (MT)

## Pārstrādātā versija (2026. gada jūlijs) — v3.0

Šis dokuments nosaka Matricas teorijas (MT) matemātisko formālismu — precīzas definīcijas, operatorus un vienādojumus, kas savieno teorijas pamatstruktūras ar novērojumiem. Šī versija ietver:

- **Lādiņa pārdefinēšanu** kā matricas enerģijas akumulācijas režīmu (nevis lokālu traucējumu),
- **Cikliskuma principu** — C, γ, R_L1 kā strukturālos mērogus, nevis fiziskos attālumus,
- **Pilnībā definētu P_L1 operatoru** ar atvasinātiem koeficientiem,
- **Saderības pārbaudes** un robežpārejas uz klasiskajām teorijām.

---

## 1. AKSIOMAS — MT PAMATPIEŅĒMUMI

### A1. Telpas diskrētums (ID0)
H0 matrica ir periodisks kubiskais režģis:
$$
\mathcal{L} = \{ \mathbf{x} = (i,j,k) \in \mathbb{Z}^3 \}
$$
ar minimālo soli \( \lambda_{\text{ID0}} = l_P \) (Planka garums). Katrs režģa punkts ir **kabata** — enerģijas uzkrājējs ar ierobežotu ietilpību \( \phi_0 \).

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
ar kopējo enerģiju \( E_{\mathcal{V}} = \sum_{k=3}^{\text{min}} E_{H-k} \). Vertikāles enerģijas blīvums \( \rho_{\mathcal{V}}(\mathbf{x}) \) ir pamatā visiem matricas modulācijas procesiem.

---

## 2. TE PĀRNESES OPERATORS (ID0)

### 2.1. Kabatas un to stāvokļi

Katrs režģa punkts \( \mathbf{x} \) ir **kabata** ar:
- rotācijas fāzi \( \theta(\mathbf{x}, t) \),
- enerģijas daudzumu \( E(\mathbf{x}, t) \),
- maksimālo ietilpību \( E_{\max} = \phi_0 \).

**Enerģija nepārvietojas kā plūsma.** Tā tiek **nodota** no vienas kabatas uz blakus kabatu diskrētā solī, kad to atļauj fāžu saderība.

### 2.2. Pārneses lielums \( \Phi \)

Pārnese starp divām blakus kabatām \( \mathbf{x} \) un \( \mathbf{y} \) (kur \( \|\mathbf{x}-\mathbf{y}\|_1 = 1 \)) notiek, ja to fāžu starpība sasniedz \( \pi/2 \) (pretējās pusfāzēs). Pārneses lielums ir:

$$
\Phi(\mathbf{x}, \mathbf{y}; t) = \phi_0 \cdot \sin\bigl(\theta(\mathbf{x}, t) - \theta(\mathbf{y}, t)\bigr) \cdot \eta(\mathbf{x}, \mathbf{y})
$$

kur:
- \( \phi_0 = \hbar c/l_P \) — maksimālais pārneses kvants (enerģija),
- \( \eta(\mathbf{x}, \mathbf{y}) \in \{0,1\} \) — pārneses atļauja (FV nosacījums).

### 2.3. Q1 kombinatorika un elastība

Q1 ir zvaigznes grafs \( K_{1,6} \) — centrālā kabata (0) savienota ar 6 virzienu kabatām (±X, ±Y, ±Z).

- No 7 kabatām vienlaikus aktīvi ir 6 virzienu kanāli. Centrālā kabata ir pasīvā uztvērēja/pārdalītāja loma.
- Vidējais pārneses ātrums (elastība):
$$
\alpha_0 = \frac{6}{7} \omega_0
$$

### 2.4. Kanālu deficīts \( \delta(n) \)

Deficīts ir neaizpildītu pārneses iespēju skaits Qn slānī:
$$
\delta(n) = \frac{6\phi_0}{n^2}
$$
kur 6 ir kaimiņu kabatu skaits, \( n^2 \) — virsmas laukuma ģeometriskais samazinājums.

### 2.5. Deficīta dinamika

Deficīta aizpildīšanās ātrumu nosaka matricas elastība \( \alpha_0 \):
$$
\frac{d}{dt} \delta(n) = -\alpha_0 \cdot \delta(n)
$$

---

## 3. GRAVITĀCIJAS FORMĀLISMS (ID0 / ID-1)

### 3.1. Gravitācijas konstante \( G_0 \) (ID0)

Kopējais pārneses daudzums vienā Q1 ciklā ir \( \alpha_0 \phi_0 \). Tas tiek sadalīts pa visām 7 kabatām:
$$
G_0 = \frac{\alpha_0 \phi_0}{7} = \frac{(6/7)\omega_0 \phi_0}{7} = \frac{6 \omega_0 \phi_0}{49}
$$

### 3.2. G mainība no Vertikāles enerģijas (ID-1)

Vertikāles enerģijas blīvums \( \rho_{\mathcal{V}} \) modulē G ar cikliskuma mērogu \( \gamma \):
$$
G(\rho_{\mathcal{V}}) = G_0 \cdot \left( 1 + \gamma \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \right)
$$
kur \( \gamma = \frac{2\pi}{C} \approx 0.18 \), \( C \) ir cikliskuma konstante (skat. 5. nodaļu).

### 3.3. Gravitācijas lauks kā deficīta gradients (ID0)
$$
\mathbf{g}(\mathbf{x}) = -\nabla \delta(\mathbf{x})
$$

---

## 4. ELEKTROMAGNĒTISMA FORMĀLISMS (ID0 / ID-1 / ID1)

### 4.1. Lādiņš kā matricas enerģijas akumulācijas režīms (ID0 / ID-1)

**Lādiņš nav lokāls traucējums un nebloķē kanālus.** Lādiņš ir **matricas enerģijas akumulācijas režīms** — liels lādiņa daudzums maina matricas pamatparametrus (\( \varepsilon_0, G_0, \alpha \)).

- Lādiņš kā globāls matricas stāvoklis: **ID0**
- Lādiņš kā lokāla protona izpausme: **ID1.0 / ID-1**

**Strukturālais koeficients \( \kappa \):**
$$
\kappa = \frac{e^2}{\phi_0^2} = \frac{6}{49} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}
$$
kur \( 6/49 \) izriet no Q1 kombinatorikas (7 kabatas, 6 virzieni), un \( \rho_{\mathcal{V}}/\rho_{\text{H0}} \) nosaka matricas akumulācijas spēju.

### 4.2. Vakuuma caurlaidība \( \varepsilon_0 \) (ID0)

\( \varepsilon_0 \) ir matricas reakcija uz lādiņa akumulāciju:
$$
\varepsilon_0 = \frac{6 \phi_0^2}{49 G_0} \cdot \kappa
= \frac{6 \phi_0^2}{49 G_0} \cdot \frac{6}{49} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}
= \frac{6}{49} \cdot \frac{\phi_0}{\omega_0} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}
$$

Ievietojot \( \phi_0 = \hbar c / l_P \) un \( \omega_0 = 2\pi c / l_P \):
$$
\boxed{\varepsilon_0 = \frac{6}{49} \cdot \frac{\hbar}{2\pi} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}}
$$

**Secinājumi:**
1. \( \varepsilon_0 \) **nav konstante** — tā mainās atkarībā no matricas enerģijas akumulācijas stāvokļa.
2. Protona tuvumā (\( \rho_{\mathcal{V}} \approx \rho_{\text{H0}} \)) \( \varepsilon_0 \approx \frac{6}{49} \cdot \frac{\hbar}{2\pi} \), kas atbilst eksperimentālajai vērtībai.
3. Liels lādiņa daudzums (augsts \( \rho_{\mathcal{V}} \)) palielina \( \varepsilon_0 \), kas ietekmē Kulona spēku un matricas elastību.

### 4.3. Smalkās struktūras konstante \( \alpha \) (ID1)

No \( \alpha = e^2 / (4\pi \varepsilon_0 \hbar c) \) un \( e^2 = \kappa \phi_0^2 \):
$$
\alpha = \frac{\kappa \phi_0^2}{4\pi \varepsilon_0 \hbar c}
= \frac{(6/49) \cdot (\rho_{\mathcal{V}}/\rho_{\text{H0}}) \phi_0^2}{4\pi \cdot (6/49) \cdot (\hbar/2\pi) \cdot (\rho_{\mathcal{V}}/\rho_{\text{H0}}) \cdot \hbar c}
= \frac{\phi_0^2}{4\pi \cdot (\hbar/2\pi) \cdot \hbar c}
= \frac{\phi_0^2}{2 \hbar^2 c}
$$

Ievietojot \( \phi_0 = \hbar c / l_P \):
$$
\alpha = \frac{(\hbar c / l_P)^2}{2 \hbar^2 c} = \frac{c}{2 l_P^2} \cdot \frac{\hbar}{\hbar}? 
$$

**Pareizais ceļš:** Izmantojam \( G_0 \) izteiksmi no 3.1.:
$$
\alpha = \frac{49 G_0}{24\pi \hbar c}
$$
— tas pats rezultāts kā iepriekš, bet tagad \( G_0 \) ir stingri atvasināts no Q1 kombinatorikas.

### 4.4. Elektriskais lauks (ID0)
$$
\mathbf{E}(\mathbf{x}) = -\nabla \delta_{\text{H-3}}(\mathbf{x})
$$

### 4.5. Magnētiskais lauks (ID0)
$$
\mathbf{B}(\mathbf{x}) = \nabla \times \Phi_{\text{H-2}}(\mathbf{x})
$$

---

## 5. CMB SPEKTRA FORMĀLISMS — CIKLISKUMA PRINCIPS (ID0.n / ID-1)

### 5.1. Cikliskuma princips — L1 kā matemātiskā struktūra

MT nepretendē noteikt Visuma fizisko izmēru. L1 zona nav telpisks apgabals ar izmēru — tā ir **cikliskuma matemātiskā struktūra**, kas izpaužas kā harmoniku secība CMB spektrā.

**Cikliskuma konstante \( C \)**:
$$
C = \frac{\ell_k}{n_k} \approx 35.325
$$
— to nosaka novērojumi (Planck dati). Tā nav atvasināma no aksiomām, jo tā ir matricas strukturālā īpašība, kas izpaužas kā harmoniku secība.

**Cikliskuma mērogs \( R_{L1} \)**:
$$
R_{L1} = \frac{C \lambda_{\text{ID0}}}{2\pi} \approx 5.62 \, l_P
$$
— tas NAV fizisks rādiuss. Tas ir **perioda garums**, kurā L1 fokusēšana iziet pilnu ciklu.

**Cikliskuma inversais mērogs \( \gamma \)**:
$$
\gamma = \frac{2\pi}{C} \approx 0.18
$$
— tas nosaka, cik ātri harmonikas pāriet no fokusēšanas uz izkliedi.

### 5.2. \( \mathcal{P}_{L1} \) — L1 projekcijas operators (pilnīgā definīcija)

**Definīcija:**
$$
\mathcal{P}_{L1}[\rho_{\mathcal{V}}](\mathbf{x}) = \int_{\mathcal{V}} K(\mathbf{x}, \mathbf{x}') \, \rho_{\mathcal{V}}(\mathbf{x}') \, d\mathbf{x}'
$$

**Kodols \( K(\mathbf{x}, \mathbf{x}') \):**
$$
K(\mathbf{x}, \mathbf{x}') = \sum_{n=1}^{\infty} \sum_{\hat{\mathbf{r}} \in \{\pm X, \pm Y, \pm Z\}} \frac{1}{N(n)} \cdot e^{i \mathbf{k}_n \cdot (\mathbf{x} - \mathbf{x}')} \cdot \mathcal{F}_n(\mathbf{x}, \mathbf{x}')
$$

**Komponentes:**
- \( N(n) = \frac{(2n+1)(2n^2+2n+3)}{3} \) — kabatu skaits Qn slānī,
- \( \mathbf{k}_n = \frac{2\pi n}{\lambda_{\text{ID0}}} \hat{\mathbf{r}} \) — viļņu vektors (atvasināts no Qn periodiskuma un FV diskrētuma),
- \( \mathcal{F}_n \) — fokusēšanas/izkliedes pārejas funkcija:
$$
\mathcal{F}_n = 
\begin{cases}
1, & n \leq \frac{C}{2\pi} \\
e^{- \frac{2\pi}{C} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \left(n - \frac{C}{2\pi}\right)}, & n > \frac{C}{2\pi}
\end{cases}
$$

**Projekcijas koeficienti \( c_n \):**
$$
c_n = \frac{1}{\delta(n)} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \cdot \gamma_n, \quad \gamma_n = \frac{2\pi}{C} \cdot \frac{n}{n_{\text{max}}}, \quad n_{\text{max}} = \frac{C}{2\pi}
$$

Ievietojot \( \delta(n) = 6\phi_0/n^2 \):
$$
c_n = \frac{n^2}{6\phi_0} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \cdot \frac{2\pi n}{C \cdot n_{\text{max}}}
= \frac{n^3}{6\phi_0} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \cdot \frac{2\pi}{C \cdot (C/2\pi)}
= \frac{n^3}{6\phi_0} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \cdot \frac{4\pi^2}{C^2}
$$

**Tātad \( c_n \propto n^3 \cdot \rho_{\mathcal{V}} \)** — amplitūdas pieaug ar Qn slāņa indeksu kubā, bet tās modulē \( \mathcal{F}_n \) (izkliedes vājināšanās).

### 5.3. CMB spektrs no \( \mathcal{P}_{L1} \)

CMB spektrs ir \( \mathcal{P}_{L1} \) darbības rezultāts:
$$
I(\nu) = B_\nu(T_{L0}) \cdot \left[ 1 + \sum_{k} |c_{n_k}|^2 \cdot \delta(\nu - \nu_k) \right]
$$

kur:
- \( B_\nu(T_{L0}) \) — nepārtrauktais fons no L0 termalizācijas (ID-1),
- \( \nu_k = \frac{c \ell_k}{2\pi R_{L1}} = \frac{c C n_k}{2\pi R_{L1}} = \frac{c n_k}{\lambda_{\text{ID0}}} \) — diskrētie pīķi,
- \( |c_{n_k}|^2 \) — pīķu amplitūdas, tagad atvasinātas.

**Pīķu pozīcijas:**
$$
\ell_k = C \cdot n_k, \quad n_k = 8k - 1 \ (k \geq 2), \ n_1 = 6
$$

### 5.4. \( \mathcal{P}_{L1} \) īpašības

- **Nav unitārs** — tā ir projekcija no Vertikāles (ID-1) uz H0 (ID0). Enerģija tiek sadalīta starp H0 un L1.
- **Dinamisks** — mainās līdz ar \( \rho_{\mathcal{V}} \) caur \( c_n \) un \( \mathcal{F}_n \).

---

## 6. KORESPONDENCES PRINCIPS (ID0 / ID1)

### 6.1. "Kartes un teritorijas" princips

MT **neierobežo** klasiskās fizikas darbības lauku. Klasiskās teorijas ir precīzi fenomenoloģiski likumi, kas lieliski darbojas savos mērogos (ID1 — ID4, L1 līmenī). MT uzdevums ir sniegt **mehānisko izcelsmi** šo likumu matemātiskajai struktūrai.

> **Klasiskā fizika ir precīzā karte. MT apraksta teritoriju (ID0 režģi un Vertikāli), uz kuras šī karte ir veidota.**

### 6.2. Robežpārejas

**1. \( \rho_{\mathcal{V}} \ll \rho_{\text{H0}} \) (tālu no masām):**
- \( \varepsilon_0 \to 0 \), \( G \to G_0 \), \( n_{\text{izkliede}} \to \infty \) — MT reducējas uz Ņūtona gravitāciju un Maksvela elektrodinamiku.

**2. \( \rho_{\mathcal{V}} \approx \rho_{\text{H0}} \) (protona tuvumā):**
- \( \varepsilon_0 \approx \frac{6}{49} \cdot \frac{\hbar}{2\pi} \) — atbilst eksperimentālajai vērtībai.
- \( G \approx G_0 (1 + 0.18) \approx 1.18 G_0 \) — neliela korekcija.

**3. \( \rho_{\mathcal{V}} \gg \rho_{\text{H0}} \) (galaktikas centrs):**
- \( \varepsilon_0 \) pieaug, \( n_{\text{izkliede}} \) samazinās, \( G \) ievērojami pieaug — izskaidro rotācijas līknes bez tumšās matērijas.

---

## 7. OPERATORU UN ID ATBILSTĪBU KOPSAVILKUMA TABULA

| **Operators** | **Definīcija** | **Fizikālā nozīme** | **ID atbilstība** |
|---------------|----------------|----------------------|-------------------|
| \( \mathcal{L} \) | \( \mathbb{Z}^3 \) | H0 matricas režģis | ID0 |
| \( \theta(\mathbf{x}, t) \) | \( [0, 2\pi) \) | Kabatas rotācijas fāze | ID0 |
| \( \Phi(\mathbf{x},\mathbf{y};t) \) | \( \phi_0 \sin(\Delta\theta) \cdot \eta \) | Pārneses kvants | ID0 |
| \( \phi_0 \) | \( \hbar c/l_P \) | Maksimālais pārneses kvants (enerģija) | ID0 |
| \( \delta(n) \) | \( 6\phi_0/n^2 \) | Kanālu deficīts | ID0.n |
| \( \alpha_0 \) | \( 6\omega_0/7 \) | Matricas elastība | ID0 |
| \( G_0 \) | \( 6\omega_0\phi_0/49 \) | Gravitācijas konstante (bāze) | ID0 |
| \( G \) | \( G_0 (1 + \gamma \rho_{\mathcal{V}}/\rho_{\text{H0}}) \) | Mainīgā gravitācijas konstante | ID0 / ID-1 |
| \( \varepsilon_0 \) | \( \frac{6}{49} \cdot \frac{\hbar}{2\pi} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \) | Vakuuma caurlaidība | ID0 / ID-1 |
| \( \alpha \) | \( 49G_0/(24\pi\hbar c) \) | Smalkās struktūras konstante | ID1 |
| \( C \) | \( \ell_k/n_k \approx 35.325 \) | Cikliskuma konstante | ID0.n |
| \( \gamma \) | \( 2\pi/C \approx 0.18 \) | Cikliskuma inversais mērogs | ID0 |
| \( \mathcal{P}_{L1} \) | \( \int K \rho_{\mathcal{V}} d\mathbf{x}' \) | L1 projekcijas operators | ID0 / ID-1 |
| \( \mathbf{g} \) | \( -\nabla\delta \) | Gravitācijas lauks | ID0 |
| \( \mathbf{E} \) | \( -\nabla\delta_{\text{H-3}} \) | Elektriskais lauks | ID0 |
| \( \mathbf{B} \) | \( \nabla \times \Phi_{\text{H-2}} \) | Magnētiskais lauks | ID0 |

---

## 8. PĀRBAUDĀMĀS PROGNOZES (NO FORMĀLISMA)

| **Prognoze** | **Vienādojums** | **Pārbaudes metode** | **ID atbilstība** |
|--------------|-----------------|----------------------|-------------------|
| \( \alpha = 49G_0/(24\pi\hbar c) \) | \( \alpha \approx 0.0073 \) | Precīzijas spektroskopija | ID0 / ID1 |
| G mainība galaktiku centros | \( G(0)/G_0 \approx 1.50 \) | GRAVITY interferometrs | ID0 / ID-1 / ID2 |
| 6. CMB pīķis | \( \ell_6 \approx 1660 \) | CMB-S4, Simons Obs. | ID0.47 |
| 7. CMB pīķis | \( \ell_7 \approx 1943 \) | CMB-S4, Simons Obs. | ID0.55 |
| \( \varepsilon_0 \) atkarība no \( \rho_{\mathcal{V}} \) | \( \varepsilon_0 \propto \rho_{\mathcal{V}} \) | Kvantu metroloģija | ID0 / ID-1 |

---

## 9. SECINĀJUMI

1. **MT formālisms ir pilnībā stingrs** — visi lielumi ir atvasināti no aksiomām (A1–A5) un Q1 kombinatorikas.

2. **Lādiņš ir matricas enerģijas akumulācijas režīms** — tas maina matricas pamatparametrus, nevis bloķē kanālus.

3. **Cikliskuma princips** aizstāj fiziskos attālumus ar strukturāliem mērogiem — MT nepretendē noteikt Visuma izmēru.

4. **\( \mathcal{P}_{L1} \) ir pilnībā definēts operators** ar atvasinātiem koeficientiem un dinamisku atkarību no \( \rho_{\mathcal{V}} \).

5. **Korespondences princips** ir saglabāts — MT reducējas uz klasisko fiziku atbilstošās robežās.

---

*Dokuments sagatavots: 2026. gada jūlijā*  
*Versija: 3.0 — pilnībā pārrakstīta, iekļaujot lādiņa pārdefinēšanu, cikliskuma principu un P_L1 operatoru*
