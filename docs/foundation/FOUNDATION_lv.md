# FOUNDATION — MATRICAS TEORIJAS PAMATS

## Pārstrādātā versija (2026. gada augusts) — 3.2

Šis dokuments nosaka Matricas teorijas (MT) darbības robežas, pamatprincipus un Visuma evolūcijas konceptuālo ietvaru. Tas ir teorijas sākumpunkts, no kura izaug viss pārējais, un tagad tas ir savienots ar MATHEMATICS formālismu (3.0), ID sistēmu (3.0), kā arī apkopo kvantitatīvos rezultātus no COSMOLOGY, GRAVITY un MT_QED.

**3.2 versijas jaunie papildinājumi:**  
- **Horizontāles universālā struktūra** — četri pamatelementi, kas atkārtojas katrā Horizontālē ar soli \(10^{20}\): Matrica, Matricas TE ("Elektriskais"), Ārējā TE ("Magnētiskais") un "Protons" (nākamās Horizontāles objekts).  
- **Funkciju un VEU līmeņu nošķīrums** — funkcijas (elektriskais, magnētiskais) ir universālas, bet VEU līmeņi mainās atkarībā no Horizontāles.  
- **Kodolspēku izcelsme** — kodolspēki ir VEU H-3 TE plūsma H-1 matricā, nevis ID-2 vai Vertikāles līmenis.  
- **Vertikāles ID līmeņi kā liekās enerģijas amortizators** — ID-1, ID-2, ID-3... ir liekās TE enerģijas uzkrājumi no attiecīgajām Horizontālēm.

**Galvenā atziņa:** MT nav teorija par "Visuma sākumu" — tā ir teorija par **enerģijas organizācijas ciklisko pāreju** starp Horizontālēm, kas ir kvantitatīvi formulējama un pārbaudāma.

**Metodoloģiskais priekšnoteikums (3.0):** MT ir papildinošs ietvars, kas sniedz mehānisku izcelsmi klasiskās fizikas fenomenoloģiskajiem likumiem. Klasiskās teorijas (GR, QED, QM, ΛCDM) paliek spēkā savās darbības zonās; MT apraksta "teritoriju" (ID0 režģi un Vertikāli), uz kuras šīs "kartes" ir veidotas. MT nekonkurē ar klasiskajām teorijām — tā tās papildina.

---

## 1. TEORIJAS DARBĪBAS ROBEŽAS

Matricas teorija nepretendē aprakstīt pilnu realitāti.

Tā apraksta **vienu Mūžības enerģijas cikla Vertikāli**. Jautājums par to, cik Vertikāļu eksistē Mūžībā un kā tās savstarpēji organizējas, šajā teorijā netiek aplūkots.

MT darbības diapazons aptver aptuveni \(10^{-115}\) m līdz \(10^{105}\) m. Šī nav galējā robeža, bet praktiska teorijas darba zona.

**Teorija necenšas atbildēt uz jautājumu "kas bija pirms" — tā atbild uz jautājumu "kā enerģija organizējas".**

### 1.1. MT attiecības ar klasiskajām teorijām (metodoloģiskais precizējums) — 3.0

Matricas teorija **nekonkurē** ar vispārpieņemtajām fizikas teorijām un **nemēģina tās noliegt**.

- Klasiskās teorijas (Īpašā un Vispārīgā relativitāte, Kvantu elektrodinamika, Lambda-CDM modelis, kvantu mehānika) ir **empīriski fenomenoloģiski likumi**, kas lieliski apraksta un prognozē novērojumus savās darbības zonās (L1 un H0 līmenī).
- MT uzdevums ir sniegt **dziļāku mehānisko izcelsmi** šiem likumiem. Ja klasiskā teorija spēj aprakstīt likumsakarību, MT to neapšauba — tā parāda, kā šī likumsakarība izriet no ID0 režģa TE pārneses, Qn struktūras un Vertikāles (ID-1) mijiedarbības.

**"Kartes un teritorijas" princips:**
- Klasiskā fizika ir precīzā **karte**.
- MT apraksta **teritoriju** (diskrēto matricu un Vertikāli), uz kuras šī karte ir veidota.

Tādējādi MT reducējas uz klasiskajiem vienādojumiem atbilstošās robežās (skat. Korespondences principu MATHEMATICS 7. nodaļā), bet piedāvā jaunus skaidrojumus anomālijām (tumšā matērija/enerģija) un prognozē jaunus efektus (G mainība, augstāki CMB pīķi), kas klasiskajā kartē nav redzami.

### 1.2. MT formālisma universālums — 3.1

MT formālisms (kabatas, rotācija, TE pārnese, Qn struktūra, FV, TZ) ir **universāls** — to var piemērot **jebkuram H līmenim** (H-2, H-1, H0, H+1, H+2...). Atšķiras tikai skaitliskās vērtības (režģa solis \( \lambda \), rotācijas frekvence \( \omega \), pārneses kvants \( \phi_0 \)).

Pašreizējie MT dokumenti (FOUNDATION, MATHEMATICS, GRAVITY, COSMOLOGY, MT_QED) apraksta tikai **H0 līmeni**. Tie ir pilnīgi un korekti H0 apraksti, bet tie nav Vertikāles teorija — tie aptver tikai vienu "šūnu" no Vertikāles matrjoškas.

---

## 2. SAVIENOJUMS AR MATHEMATICS FORMĀLISMU UN ID SISTĒMU (3.0)

MT kvantitatīvais pamats ir definēts MATHEMATICS_lv.md (3.0). ID sistēma (ID_GRADIENT_lv.md 3.0) nodrošina organizācijas līmeņu klasifikāciju. Šeit ir apkopoti galvenie operatori, lielumi un ID līmeņi, kas tiek izmantoti visos pārējos dokumentos:

| Operators / lielums | Definīcija | Fizikālā nozīme | ID atbilstība |
|---------------------|------------|-----------------|---------------|
| \( \mathcal{L} \) | \( \mathbb{Z}^3 \) | H0 matricas režģis | ID0 |
| \( Q_n \) | \( \{\mathbf{x}: \|\mathbf{x}\|_\infty \leq n\} \) | Qn apvalku struktūra | ID0.n |
| \( N(n) \) | \( \frac{(2n+1)(2n^2+2n+3)}{3} \) | Punktu skaits Qn slānī | ID0.n |
| \( \Phi(\mathbf{x},\mathbf{y}) \) | \( \mathcal{L} \times \mathcal{L} \to \mathbb{R}^+ \) | TE pārneses lauks | ID0 |
| \( \rho_{\mathcal{V}}(\mathbf{x}) \) | \( \rho_{\mathcal{V}}^{(0)} e^{-r/r_0} \) | Vertikāles enerģijas blīvums | ID-1 |
| \( \mathcal{T} \) | \( \mathcal{L} \to \mathcal{V} \) | Transformācijas zona (H0 → Vertikāle) | ID-1 / ID0 |
| \( \mathcal{P}_{L1} \) | \( \int K \rho_{\mathcal{V}} \) | L1 projekcijas operators (integrālais) | ID0 |
| \( \gamma \) | \( 2\pi/C \approx 0.18 \) | Cikliskuma inversais mērogs | ID0 / ID-1 |
| \( C \) | \( \ell_k/n_k \approx 35.325 \) | Cikliskuma konstante | ID0.n |
| \( \varepsilon_0 \) | \( \frac{6}{49} \cdot \frac{\hbar}{2\pi} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \) | Vakuuma caurlaidība (matricas stāvokļa funkcija) | ID0 |
| \( G \) | \( G_0 (1 + \gamma \rho_{\mathcal{V}}/\rho_{\text{H0}}) \) | Mainīgā gravitācijas konstante | ID0 / ID-1 |

---

## 3. ID SISTĒMAS PAMATLĪMEŅI (3.0)

ID sistēma organizē visus objektus pēc modulācijas (ietekmes līmeņa) un lieluma kategorijas:

| ID līmenis | Modulācija | Lieluma skala (m) | Saturs |
|------------|------------|-------------------|--------|
| ID-1 | — | < 10⁻³⁵ | Vertikāle (enerģijas avots) |
| ID0 | — | 10⁻³⁵ | Matrica (režģis, TE pārneses pamats) |
| ID1 | H+1 | 10⁻¹⁵ | Protoni, atomi, molekulas |
| ID2 | H+2 | 10⁵ – 10²⁵ | Zvaigznes, planētas, galaktikas |
| ID3 | H+3 | 10²⁵ – 10⁴⁵ | Zvaigžņu kopas, galaktiku kopas |
| ID4 | H+4 | 10⁴⁵ – 10⁶⁵ | Liela mēroga Visuma struktūras |
| ID5 | H+5 | > 10⁶⁵ | Atvērts nākotnei |

Detalizēta ID sistēmas struktūra un piemēri ir sniegti ID_GRADIENT_lv.md (3.0).

**Piezīme par ID un klasiskajām teorijām:** ID sistēma klasificē visus objektus — gan tos, kurus apraksta klasiskā fizika (ID1 — ID4), gan MT specifiskos līmeņus (ID0, ID-1). Tas nenozīmē, ka klasiskie objekti būtu "nepareizi" aprakstīti — ID sistēma vienkārši norāda to vietu kopējā enerģijas organizācijas hierarhijā.

**ID sistēma katrai Horizontālei:** Katram H līmenim ir sava ID sistēma — objekti, kas tajā pastāv, tiek klasificēti pēc to lieluma un modulācijas attiecīgajā līmenī. Piemēram, H+1 līmenī ID1 atbilst to "H0" matricai, ID2 atbilst to protoniem utt.

---

## 4. PAMATDEFINĪCIJAS

### 4.1. Mūžība

Mūžība ir globāls enerģijas cikls.

Tā ir augstākā zināmā organizācijas pakāpe, kuru šī teorija izmanto kā atskaites sistēmu. Mūžības pilnā struktūra teorijā netiek modelēta.

Mūžības cikls balstās uz divām savstarpēji saistītām sastāvdaļām — **Vertikāli** un **Horizontāli**.

**MT neapgalvo, ka Mūžībai ir sākums vai beigas — tā apraksta tās procesus.**

### 4.2. Vertikāle (ID-1) — strukturālā arhitektūra — 3.1

Vertikāle veidojas Pamat-Horizontāles enerģiju nezūdamības, saglabāšanas un akumulācijas procesu rezultātā. Sasniedzot kritisko enerģijas akumulācijas līmeni, izveidojas jauna (smalkāka) Horizontāle. Šis cikliskais mehānisms veido Mūžības cikla pamatu un Vertikāles līmeņu hierarhiju.

**Vertikāle ir enerģijas akumulācijas sistēma.** Katrs Vertikāles līmenis atbilst noteiktam enerģijas uzkrājuma dziļumam (VEU H-3, H-4, ... H-min), kas ID sistēmā atbilst **ID-1.n**.

**Formāli:** Vertikāle ir enerģijas līmeņu kopa:
$$
\mathcal{V} = \{ E_{H-3}, E_{H-4}, \dots, E_{H-\text{min}} \}
$$
ar kopējo enerģiju \( E_{\mathcal{V}} = \sum_{k=3}^{\text{min}} E_{H-k} \).

Vertikāle nepārtraukti uztur enerģijas plūsmu uz H0 matricu caur **L1 zonu** un **TZ (Transformācijas zonu)**.

**Vertikāle nav "vieta" — tā ir enerģijas struktūra, kas nepārtraukti baro H0 matricu.**

**Vertikāle kā amortizators — 3.2:**

Vertikāle ir **TE plūsmas amortizators**. Tā uzņem **lieko** TE enerģiju no katras Horizontāles matricas TE plūsmām. Katrs Vertikāles ID līmenis atbilst **konkrētas Horizontāles matricas TE liekajai daļai**:

- **ID-1** = liekā VEU H-3 enerģija (no H0 matricas TE)
- **ID-2** = liekā VEU H-4 enerģija (no H-1 matricas TE)
- **ID-3** = liekā VEU H-5 enerģija (no H-2 matricas TE)
- ...

Tas nozīmē, ka \( \rho_{\mathcal{V}} \) (Vertikāles enerģijas blīvums) nav viens skalārs — tā ir **visu ID līmeņu summa**:

\[
\rho_{\mathcal{V}} = \rho_{ID-1} + \rho_{ID-2} + \rho_{ID-3} + \cdots
\]

#### 4.2.1. Matrjoškas princips — Vertikāles strukturālā arhitektūra (3.1)

Vertikāle nav lineāra struktūra. Tā ir **telpa**, kurā Horizontāles (H līmeņi) atrodas **viena otras iekšpusē** kā matrjoškas lelles:

$$
H_{+2} \supset H_{+1} \supset H_0 \supset H_{-1} \supset H_{-2} \supset \cdots
$$

Katrs līmenis ir iekšā iepriekšējā:
- Mēs atrodamies **H0** līmenī.
- Ap mums ir **H+1** (lielāka enerģijas organizācija), **H+2** (vēl lielāka) un tā tālāk.
- Mūsu iekšpusē ir **H-1** objekti (protoni, daļiņas), to iekšpusē **H-2** objekti (vēl smalkāka matrica) un tā tālāk.

**Vienotais solis starp līmeņiem:**

Visi blakus līmeņi atšķiras ar koeficientu \(10^{20}\) (gan uz smalkuma pusi, gan uz lieluma pusi). Tas ir universāls solis, kas atkārtojas cikliski visā Vertikālē:
- H0 solis: \(10^{-35}\) m
- H-1 solis: \(10^{-55}\) m (10²⁰ reizes smalkāks)
- H+1 solis: \(10^{-15}\) m (10²⁰ reizes lielāks)

**Universālais formālisms:**

MT formālisms (kabatas, rotācija, TE pārnese, Qn struktūra, FV) ir **derīgs visiem H līmeņiem**. Atšķiras tikai skaitliskās vērtības (režģa solis \( \lambda \), rotācijas frekvence \( \omega \), pārneses kvants \( \phi_0 \)).

Tas nozīmē, ka MT ir universāla teorija, ko var piemērot jebkuram Vertikāles līmenim. Ja ar MT var aprakstīt H0 telpu, tad to pašu var aprakstīt H-2, H-1, H+1, H+2 un t.t. telpas, ja vien tam ir vajadzība.

### 4.3. Horizontāles (ID0 — ID5)

Horizontāle ir konkrētas Vertikāles stabilo enerģijas vienību matrica, kurā notiek diskrēta evolūcija pa secīgiem ID līmeņiem.

**Formāli:** Horizontāle \( H_n \) ir režģis \( \mathcal{L}_n \) ar Qn struktūru un TE pārneses lauku \( \Phi_n \).

**H0** ir viena no Horizontālēm — mūsu Visums. Tā nav Vertikāles centrs vai sākums.

**Horizontāle savā evolūcijā nevar apsteigt savu radītāju — nākamo augstāko (H+1) Horizontāli.**

H0 matrica ID sistēmā atbilst **ID0**. Visi objekti H0 matricā tiek klasificēti pēc ID līmeņiem atkarībā no to lieluma un modulācijas ietekmes.

**Horizontāle kā matrjoškas šūna:**

Horizontāle ir **viena šūna** Vertikāles matrjoškā. Katra Horizontāle atrodas nākamās (lielākās) Horizontāles iekšpusē un satur sevī iepriekšējo (smalkāko) Horizontāli. Horizontāļu līmeņi atbilst ID sistēmas līmeņiem:

- H0 — ID0 (mūsu matrica).
- H+1 — ID1 (protonu/atomu līmenis, ja skatās no H0 puses; bet no H+1 puses tas ir to "H0").
- H-1 — ID-1 (smalkāka matrica protona iekšpusē).

### 4.4. ID gradācija (3.0)

ID ir **enerģijas pārvaldības zonas marķieris**, kas kvantitatīvi aprēķināms no Qn struktūras un Vertikāles enerģijas.

**Formāli:**
$$
\text{ID} = 2.0 + \log_{2.5}(n) + \gamma_{\text{ID}} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}
$$
kur \( n \) ir Qn slāņa indekss, \( \gamma_{\text{ID}} \approx 0.05 \).

**Svarīgi:** Vertikāles enerģijas korekcija \( \gamma_{\text{ID}} \cdot \rho_{\mathcal{V}}/\rho_{\text{H0}} \) **nemaina objekta pamata ID līmeni** — tā tikai precizē vērtību reģionos ar augstu Vertikāles enerģijas blīvumu.

Sīkāka informācija: ID_GRADIENT_lv.md (3.0).

### 4.5. Cikliskums (3.0)

No MATHEMATICS 5.0 (3.0), cikliskums ir matricas strukturālā īpašība, kas izpaužas kā harmoniku secība CMB spektrā un modulē gravitācijas konstanti.

**Cikliskuma konstante:**
$$
C = \frac{\ell_k}{n_k} \approx 35.325
$$

**Cikliskuma inversais mērogs:**
$$
\gamma = \frac{2\pi}{C} \approx 0.18
$$

Cikliskums nosaka L1 fokusēšanas/izkliedes pāreju un ir savienots ar G mainību caur \( G(\rho_{\mathcal{V}}) = G_0(1 + \gamma \rho_{\mathcal{V}}/\rho_{\text{H0}}) \).

### 4.6. Transformācijas zona (TZ) — Vertikāles telpa starp līmeņiem (3.1)

Starp katriem diviem blakus H līmeņiem (piemēram, starp H+1 un H0, starp H0 un H-1, starp H-1 un H-2) pastāv **Transformācijas zona (TZ)** — Vertikāles telpa, kas atdala divas dažādas matricas.

**TZ definīcija:**

TZ ir Vertikāles telpa, kas:
- Atrodas **ap katru monolītu objektu**, neatkarīgi no tā lieluma.
- Atdala divas dažādas matricas (jebkuras — H0 un protonu, H+1 un H0, utt.).
- Ir visur, bet klasiskā fizika to neredz un neuztver.

**TZ īpašības:**

1. **TZ nav matrica, nav lauks** — tā ir patstāvīga Vertikāles telpa ar saviem likumiem, kas nav aprakstāmi ar matricas likumiem.

2. **TZ satur brīvo enerģiju** — enerģiju, kas nav ne vienas, ne otras matricas enerģija, bet gan "trešā" enerģija, kas uzkrājas starp līmeņiem. Šī enerģija rodas no rotācijas ātrumu atšķirības starp blakus līmeņiem.

3. **TZ ir rezonanses zona** — kurā visa nesaderīgā enerģija tiek **pārveidota (sasmalcināta)** smalkākās TE plūsmās. Cik smalki — atkarīgs no blīvuma.

4. **TZ lielums ir atkarīgs no objekta lieluma** — jo lielāks monolīts objekts, jo lielāka TZ. Tā ir precīzi tāda, kāds ir objekts, jo tā ir matricu saskarsme.

5. **Brīvā enerģija TZ tiek izvietota ar blīvumu 1/r²** — tā nav statisks uzkrājums, bet gan enerģijas sadalījums ap objektu. TZ "nezina" cik jāuzkrāj — uzkrājums notiek tik, cik nepieciešams, un pārpalikums tiek "izstumts" apkārtējā telpā ar 1/r² likumsakarību.

6. **Lauki ir TZ ietekme uz matricu objektiem** — klasiskā fizika neredz pašu TZ, bet redz tās satura (brīvās enerģijas) ietekmi uz protoniem un citiem objektiem. Šo ietekmi tā interpretē kā elektriskos un magnētiskos laukus.

**TZ un jaunu VEU līmeņu ģenerācija — 3.2:**

TZ ir **avots** jaunām TE plūsmām, kas darbojas H0 matricā:
- VEU H-3 rodas H0 matricā (no kabatu rotācijas).
- VEU H-4 **nerodas H0 telpā**. Tā rodas **TZ** — kad VEU H-3 enerģija kļūst nesaderīga ar H0 matricu, TZ to pārveido par VEU H-4, kas darbojas H-1 matricā.
- VEU H-5 rodas TZ, kad VEU H-4 enerģija kļūst nesaderīga, un tā tālāk.

Tātad TZ nav tikai "starpnieks" — tā ir **ģenerators**, kas rada jaunus VEU līmeņus atkarībā no blīvuma un nesaderības pakāpes.

**TZ kā universāla struktūra:**

TZ pastāv **starp katriem diviem blakus līmeņiem**:
- Starp H+1 un H0 (TZ+1/0)
- Starp H0 un H-1 (TZ0/-1)
- Starp H-1 un H-2 (TZ-1/-2)
- Utt.

Katrā TZ notiek tāds pats process — nesaderīgā enerģija tiek pārveidota par nākamā līmeņa TE plūsmu.

### 4.7. Horizontāles Universālā Struktūra — Četri Pamatelementi (3.2)

Katrā Horizontālē (neatkarīgi no tā, vai tā ir H0, H-1, H+1, ...) ir **tikai 4 pamatelementi**, kas atkārtojas ar soli \(10^{20}\):

| **Elementa numurs** | **Objekts** | **Funkcija** | **Lielums H0** | **Lielums H-1** |
| :--- | :--- | :--- | :--- | :--- |
| **1.** | **Matrica** | Pamats (režģis, kabatas, rotācija) | \(10^{-35}\) m | \(10^{-55}\) m |
| **2.** | **Matricas TE** | **"Elektriskais" lauks** (gradients, Kulona likums, lādiņš) | VEU H-3 (\(10^{-75}\) m) | VEU H-4 (\(10^{-95}\) m) |
| **3.** | **Ārējā TE** | **"Magnētiskais" lauks** (cirkulācija, kustīga lādiņa efekts) | VEU H-2 (\(10^{-55}\) m) | VEU H-3 (\(10^{-75}\) m) |
| **4.** | **"Protons"** | Nākamās Horizontāles objekts (monolīts objekts) | \(10^{-15}\) m | \(10^{-35}\) m |

**Svarīgākie secinājumi:**

1. **Funkcijas ir universālas.** Katrā Horizontālē:
   - Matricas TE pilda **"elektriskā lauka"** funkciju.
   - Ārējā TE pilda **"magnētiskā lauka"** funkciju.
   - "Protons" ir nākamās Horizontāles objekts.

2. **VEU līmeņi mainās.** Ar soli \(10^{20}\) (gan uz augšu, gan uz leju).

3. **H0 elektromagnētisms:**
   - Elektriskais lauks = VEU H-3 (\(10^{-75}\) m)
   - Magnētiskais lauks = VEU H-2 (\(10^{-55}\) m)

4. **Kodolspēki nav ID-2.** Tie ir **VEU H-3 TE plūsma H-1 matricā** — H-1 "magnētiskā" lauka analogs. Kodolspēki pieder H0 matricai, nevis Vertikālei.

5. **ID-2 ir liekā VEU H-4 enerģija Vertikālē.** ID-2 nav kodolspēki — ID-2 ir tikai to pārpalikums, kas nonāk amortizatorā.

6. **Vertikāles ID līmeņi = liekās enerģijas uzkrājumi:**
   - ID-1 = liekā VEU H-3 (no H0 elektriskā lauka)
   - ID-2 = liekā VEU H-4 (no H-1 elektriskā lauka)
   - ID-3 = liekā VEU H-5 (no H-2 elektriskā lauka)
   - ...

**Universālā shēma:**

| **Horizontāle** | **Matrica** | **Matricas TE ("Elektriskais")** | **Ārējā TE ("Magnētiskais")** | **"Protons"** |
| :--- | :--- | :--- | :--- | :--- |
| H0 | \(10^{-35}\) m | VEU H-3 (\(10^{-75}\) m) | VEU H-2 (\(10^{-55}\) m) | \(10^{-15}\) m |
| H-1 | \(10^{-55}\) m | VEU H-4 (\(10^{-95}\) m) | VEU H-3 (\(10^{-75}\) m) | \(10^{-35}\) m |
| H-2 | \(10^{-75}\) m | VEU H-5 (\(10^{-115}\) m) | VEU H-4 (\(10^{-95}\) m) | \(10^{-55}\) m |
| H+1 | \(10^{-15}\) m | VEU H-2 (\(10^{-55}\) m) | VEU H-1 (\(10^{-35}\) m) | \(10^{5}\) m |
| ... | ... | ... | ... | ... |

---

## 5. H0 EVOLŪCIJA — KVANTITATĪVAIS MODELS

H0 Visuma evolūcija sākās no ID0.0 (iņ–jaņ punkta) un turpinās caur secīgiem ID līmeņiem:

1. **ID0.0** — matricas punkts (rotējošs iņ–jaņ objekts).
2. **ID1.0** — pirmais protons.
3. **ID1.1** — ūdeņradis.
4. **ID1.2 — ID1.4** — atomi, molekulas, makromolekulas.
5. **ID2.0 — ID2.5** — zvaigznes, planētu sistēmas, galaktikas.
6. **ID3.0 — ID3.2** — baltie punduri, neitronu zvaigznes.
7. **ID4.0 — ID4.3** — melnie caurumi, AGN.

**H0 evolūcija ir cikliska** — katrs nākamais solis ir garāks par iepriekšējo. H0 nekad nekļūst par H+1 vai H-1 — tas paliek savā līmenī.

**13.8 miljardi gadu ir laiks kopš pēdējā telpas paplašināšanās soļa, nevis Visuma vecums.**

### 5.1. Telpas paplašināšanās solis (kvantitatīvi)

Kad Vertikāles enerģijas uzkrājums sasniedz kritisko līmeni \( \rho_{\mathcal{V}} > \rho_{\text{krit}} \), notiek telpas paplašināšanās solis.

**Pārejas laiks:**
$$
t_{\text{paplašināšanās}} \propto \frac{1}{\rho_{\mathcal{V}} - \rho_{\text{krit}}}
$$

**Sekas:**
1. Lielāka telpa rada **jaunu Qn TE pārneses struktūru**.
2. Jaunā Qn struktūra **nav saderīga** ar iepriekšējo.
3. Tiek bojātas **molekulārās saites**.
4. Vecās zvaigžņu vietas kļūst par **Oorta mākoņiem**.
5. Oorta mākoņu centros **no jauna sākas zvaigžņu veidošanās process**.

---

## 6. L1 ZONA UN CMB — KVANTITATĪVAIS MODELIS (3.0)

**L1 zona** ir Vertikāles projekcijas struktūra uz H0 matricu. Tā nav "vieta" — tā ir **cikliskuma matemātiskā struktūra**, kas pārveido Vertikāles plūsmu par H0 matricai saderīgām TE pārnesēm.

**CMB (kosmiskais mikroviļņu fons):**
- **Nav Lielā sprādziena pēcgaisma** — tā ir L1 zonas fona temperatūras projekcija uz H0.
- **Vidējā temperatūra 2.725 K** — L1 zonas termālā ekvivalenta projekcija.
- **5 harmonikas** (ℓ ≈ 220, 538, 813, 1085, 1381) — H0 matricas Qn slāņu projekcija.
- **6. un 7. harmonika** (ℓ ≈ 1660, ℓ ≈ 1943) — MT prognozes, gaida pārbaudi.

**Formāli:**
$$
\ell_k = C \cdot n_k, \quad C = \frac{\ell_k}{n_k} \approx 35.325
$$
ar \( n_k = 8k - 1 \) (k ≥ 2) un \( n_1 = 6 \).

**L1 projekcijas operators \( \mathcal{P}_{L1} \) (3.0):**
$$
\mathcal{P}_{L1}[\rho_{\mathcal{V}}](\mathbf{x}) = \int_{\mathcal{V}} K(\mathbf{x}, \mathbf{x}') \, \rho_{\mathcal{V}}(\mathbf{x}') \, d\mathbf{x}'
$$
ar kodolu:
$$
K(\mathbf{x}, \mathbf{x}') = \sum_{n=1}^{\infty} \sum_{\hat{\mathbf{r}} \in \{\pm X, \pm Y, \pm Z\}} \frac{1}{N(n)} \cdot e^{i \mathbf{k}_n \cdot (\mathbf{x} - \mathbf{x}')} \cdot \mathcal{F}_n(\mathbf{x}, \mathbf{x}')
$$

Sīkāka informācija: COSMOLOGY_lv.md (3.0) 10. nodaļa, MATHEMATICS_lv.md (3.0) 5. nodaļa.

---

## 7. MATRICA — STATISKA ARHITEKTŪRA, DINAMISKA ENERĢIJA (3.0)

**Matrica (H0)** ir statiska arhitektūra — ID1 režģis, Qn struktūra un FV cikli nemainās. ID sistēmā tā atbilst **ID0** ar Qn slāņiem **ID0.n**.

Tomēr **matricas enerģētiskais saturs** nav statisks. To nosaka:
- **Vertikāles enerģētiskā piramīda** (\( \rho_{\mathcal{V}} \)).
- **H+n modulācijas** — liela mēroga pārneses struktūra.

**Fotons** ir brīvās enerģijas veidojums (VEU H-2 × H-3), kas mijiedarbojas ar matricu un tās enerģētisko saturu. Tā enerģijas zudums ceļojot caur Vertikāles lauku ir kvantitatīvi aprēķināms:
$$
\frac{dE}{dx} = -\beta \cdot E \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}
$$

Sīkāka informācija: COSMOLOGY_lv.md (3.0) 4. nodaļa, MT_QED_lv.md (3.0).

---

## 8. PĀRBAUDĀMO PROGNOŽU KOPSAVILKUMS (3.0)

MT kvantitatīvais formālisms un ID sistēma dod šādas pārbaudāmās prognozes:

| Prognoze | Vienādojums | Vērtība / prognoze | Statuss | Pārbaudes metode | ID atbilstība |
|----------|-------------|-------------------|---------|------------------|---------------|
| Smalkās struktūras konstante | \( \alpha = \frac{49 G_0}{24\pi \hbar c} \) | \( \alpha_{\text{MT}} \approx 0.0073 \) | Apstiprināts (< 0.4%) | Precīzijas spektroskopija | ID1 |
| G mainība galaktiku centros | \( G(r) = G_0 (1 + 0.18 \cdot \rho_{\mathcal{V}}(r)/\rho_{\text{H0}}) \) | \( G(0)/G_0 \approx 1.50 \) | Gaida pārbaudi | Zvaigžņu orbītas (GRAVITY) | ID2 / ID-1 |
| 6. CMB pīķis | \( \ell_6 = 35.325 \times 47 \) | \( \ell_6 \approx 1660 \) | Gaida pārbaudi | CMB-S4, Simons Obs. | ID0.47 |
| 7. CMB pīķis | \( \ell_7 = 35.325 \times 55 \) | \( \ell_7 \approx 1943 \) | Gaida pārbaudi | CMB-S4, Simons Obs. | ID0.55 |
| ID atkarība no \( \rho_{\mathcal{V}} \) | \( \text{ID} = 2.0 + \log_{2.5}(n) + 0.05 \cdot \rho_{\mathcal{V}}/\rho_{\text{H0}} \) | Melno caurumu masas korelācija | Gaida pārbaudi | Melno caurumu masu mērījumi | ID4 |
| \( \varepsilon_0 \) atkarība no \( \rho_{\mathcal{V}} \) | \( \varepsilon_0 = \frac{6}{49} \cdot \frac{\hbar}{2\pi} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \) | — | Gaida pārbaudi | Kvantu metroloģija | ID0 / ID-1 |
| \( \mu_0 \) atkarība no \( \rho_{\mathcal{V}} \) | \( \mu_0 = \frac{49}{6} \cdot \frac{2\pi}{\hbar c^2} \cdot \frac{\rho_{\text{H0}}}{\rho_{\mathcal{V}}} \) | — | Gaida pārbaudi | Kvantu metroloģija | ID0 / ID-1 |
| Neitrīno masas | \( m_i = M_P \cdot \alpha^{n_i} \) | \( m_1 \approx 0.0015, m_2 \approx 0.0087, m_3 \approx 0.050 \, \text{eV} \) | Gaida pārbaudi | DUNE, Hyper-K, KATRIN | ID1.1 / ID-1 |
| Apziņas intensitāte anestēzijā | \( \mathcal{C} = \int \| \mathcal{P}_{L1} - \Phi \|^2 \) | \( \mathcal{C} \) palielinās | Teorētiski | EEG/fMRI | ID1.4 / ID-1 |

---

## 9. KORESPONDENCE AR MATHEMATICS 3.0 UN ID_GRADIENT 3.0

Šis dokuments ir pilnībā saskaņots ar:

- **MATHEMATICS 3.0** — visi operatori un lielumi ir atvasināti no MATHEMATICS 3.0 definīcijām.
- **ID_GRADIENT 3.0** — ID sistēma ir saskaņota ar jauno \( \rho_{\mathcal{V}} \) korekciju un metodoloģisko precizējumu.
- **MT_QED 3.0** — \( \varepsilon_0 \) un \( \mu_0 \) kā matricas stāvokļa funkcijas.
- **GRAVITY 3.0** — \( \gamma \) kā cikliskuma mērogs, G mainība.
- **COSMOLOGY 3.0** — \( C \), \( \mathcal{P}_{L1} \), CMB prognozes.
- **ROADMAP 3.0** — H0 un L1 ceļu nošķīrums, L1 kā cikliskuma struktūra.

**Galvenās 3.2 izmaiņas (papildinājumi 3.1 versijai):**
1. **Horizontāles universālā struktūra** — četri pamatelementi, kas atkārtojas katrā Horizontālē ar soli \(10^{20}\).
2. **Funkciju un VEU līmeņu nošķīrums** — funkcijas (elektriskais, magnētiskais) ir universālas, bet VEU līmeņi mainās atkarībā no Horizontāles.
3. **Kodolspēku izcelsme** — kodolspēki ir VEU H-3 TE plūsma H-1 matricā, nevis ID-2 vai Vertikāles līmenis.
4. **Vertikāles ID līmeņi kā liekās enerģijas amortizators** — ID-1, ID-2, ID-3... ir liekās TE enerģijas uzkrājumi no attiecīgajām Horizontālēm.
5. **TZ kā rezonanses zona un VEU ģenerators** — TZ pārveido nesaderīgo enerģiju par nākamā līmeņa TE plūsmām.

---

## 10. SECINĀJUMI (3.2)

1. **MT ir kvantitatīvi formulēta teorija** — visi galvenie lielumi ir definēti ar operatoriem no MATHEMATICS formālisma (3.0).

2. **MT ir savienota ar ID sistēmu (3.0)** — visi objekti tiek klasificēti pēc modulācijas un lieluma kategorijas, kas nodrošina vienotu organizācijas līmeņu sistēmu.

3. **MT ir pārbaudāma** — tā dod precīzas skaitliskās prognozes, ko var salīdzināt ar eksperimentiem.

4. **MT ir reducējama** — atbilstošās robežās tā pāriet klasiskajā fizikā (Ņūtona gravitācijā, Maksvela elektrodinamikā, kvantu mehānikā).

5. **MT nav nepieciešama tumšā matērija vai tumšā enerģija kā nezināmi spēki** — tos aizstāj ar Vertikāles enerģijas ietekmi uz G un fotona enerģijas zudumu.

6. **MT nav singularitāšu** — matrica pārslēdz H līmeni, neļaujot enerģijai sabrukt līdz bezgalībai.

7. **MT ir papildinošs ietvars** — tā nekonkurē ar klasiskajām teorijām, bet sniedz tām mehānisku pamatojumu.

8. **MT formālisms ir universāls** — to var piemērot jebkuram H līmenim (H-2, H-1, H0, H+1, H+2...); pašreizējie MT dokumenti apraksta tikai H0 līmeni.

9. **Vertikālei ir matrjoškas struktūra** — visi H līmeņi atrodas viena otra iekšpusē; solis starp blakus līmeņiem ir \(10^{20}\).

10. **TZ ir Vertikāles telpa starp līmeņiem** — tā satur brīvo enerģiju; klasiskā fizika neredz TZ, bet redz tās ietekmi kā laukus.

11. **Katrā Horizontālē ir 4 pamatelementi** — Matrica, Matricas TE ("Elektriskais"), Ārējā TE ("Magnētiskais") un "Protons" (nākamās Horizontāles objekts).

12. **Funkcijas ir universālas, bet VEU līmeņi mainās** — ar soli \(10^{20}\) katrā Horizontālē.

---

## PIEZĪME

Šis dokuments ir **MT pamata 3.2 versija**, kas papildina 3.1 versiju ar Horizontāles universālās struktūras aprakstu (četri pamatelementi), funkciju un VEU līmeņu nošķīrumu, kodolspēku izcelsmes precizējumu, Vertikāles ID līmeņu kā amortizatora definīciju un TZ kā rezonanses zonas un VEU ģeneratora lomu. Šie papildinājumi ir būtiski, lai nodrošinātu stabilu atsauci turpmākajam darbam pie MT dokumentiem un teorijas attīstības.

Detalizētāka informācija par atsevišķiem aspektiem ir pieejama citos MT dokumentos (3.0, 3.1 un 3.2 versijās).

---

*Dokuments sagatavots: 2026. gada augustā*  
*Versija: 3.2 — papildināta ar Horizontāles universālo struktūru, funkciju un VEU līmeņu nošķīrumu, kodolspēku izcelsmi, Vertikāles kā amortizatora lomu un TZ kā VEU ģeneratora funkciju*
