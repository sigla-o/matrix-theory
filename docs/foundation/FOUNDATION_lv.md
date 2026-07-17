# FOUNDATION — MATRICAS TEORIJAS PAMATS

## Pārstrādātā versija (2026. gada jūlijs) — v3.0

Šis dokuments nosaka Matricas teorijas (MT) darbības robežas, pamatprincipus un Visuma evolūcijas konceptuālo ietvaru. Tas ir teorijas sākumpunkts, no kura izaug viss pārējais, un tagad tas ir savienots ar MATHEMATICS formālisma v3.0 versiju un ID sistēmu, iekļaujot **cikliskuma principu** un **lādiņa pārdefinēšanu** kā matricas enerģijas akumulācijas režīmu.

**Galvenā atziņa:** MT nav teorija par "Visuma sākumu" — tā ir teorija par **enerģijas organizācijas ciklisko pāreju** starp Horizontālēm, kas ir kvantitatīvi formulējama un pārbaudāma. MT nepretendē noteikt Visuma fizisko izmēru — tā izmanto **cikliskumu** kā strukturālo principu.

---

## 1. TEORIJAS DARBĪBAS ROBEŽAS

### 1.1. MT kā papildinošs ietvars, nevis konkurents

Matricas teorija **nekonkurē** ar vispārpieņemtajām fizikas teorijām un **nemēģina tās noliegt**.

- Klasiskās teorijas (Īpašā un Vispārīgā relativitāte, Kvantu elektrodinamika, Lambda-CDM modelis, kvantu mehānika) ir **empīriski fenomenoloģiski likumi**, kas lieliski apraksta un prognozē novērojumus savās darbības zonās (L1 un H0 līmenī).
- MT uzdevums ir sniegt **dziļāku mehānisko izcelsmi** šiem likumiem. Ja klasiskā teorija spēj aprakstīt likumsakarību, MT to neapšauba — tā parāda, kā šī likumsakarība izriet no ID0 režģa TE pārneses, Qn struktūras un Vertikāles (ID-1) mijiedarbības.

**"Kartes un teritorijas" princips:**
- Klasiskā fizika ir precīzā **karte**.
- MT apraksta **teritoriju** (diskrēto matricu un Vertikāli), uz kuras šī karte ir veidota.

Tādējādi MT reducējas uz klasiskajiem vienādojumiem atbilstošās robežās (skat. Korespondences principu MATHEMATICS 7. nodaļā), bet piedāvā jaunus skaidrojumus anomālijām (tumšā matērija/enerģija) un prognozē jaunus efektus (G mainība, augstāki CMB pīķi), kas klasiskajā kartē nav redzami.

### 1.2. Cikliskuma princips — MT nepretendē noteikt Visuma izmēru

MT nepretendē noteikt Visuma fizisko izmēru. L1 zona nav telpisks apgabals ar izmēru — tā ir **cikliskuma matemātiskā struktūra**, kas izpaužas kā harmoniku secība CMB spektrā.

- **Cikliskuma konstante \( C \)** — to nosaka novērojumi (Planck dati). Tā nav atvasināma no aksiomām, jo tā ir matricas strukturālā īpašība, kas izpaužas kā harmoniku secība.
- **Cikliskuma mērogs \( R_{L1} \)** — NAV fizisks rādiuss. Tas ir **perioda garums**, kurā L1 fokusēšana iziet pilnu ciklu.
- **Cikliskuma inversais mērogs \( \gamma \)** — tas nosaka, cik ātri harmonikas pāriet no fokusēšanas uz izkliedi.

**Secinājums:** MT darbības diapazons aptver aptuveni \(10^{-115}\) m līdz \(10^{105}\) m. Šī nav galējā robeža, bet praktiska teorijas darba zona. Teorija necenšas atbildēt uz jautājumu "kas bija pirms" — tā atbild uz jautājumu "kā enerģija organizējas".

---

## 2. SAVIENOJUMS AR MATHEMATICS FORMĀLISMU UN ID SISTĒMU

MT kvantitatīvais pamats ir definēts MATHEMATICS_lv.md v3.0. ID sistēma (ID_GRADIENT_lv.md) nodrošina organizācijas līmeņu klasifikāciju. Šeit ir apkopoti galvenie operatori, lielumi un ID līmeņi, kas tiek izmantoti visos pārējos dokumentos:

| Operators / lielums | Definīcija | Fizikālā nozīme | ID atbilstība |
|---------------------|------------|-----------------|---------------|
| \( \mathcal{L} \) | \( \mathbb{Z}^3 \) | H0 matricas režģis | ID0 |
| \( Q_n \) | \( \{\mathbf{x}: \|\mathbf{x}\|_\infty \leq n\} \) | Qn apvalku struktūra | ID0.n |
| \( N(n) \) | \( \frac{(2n+1)(2n^2+2n+3)}{3} \) | Punktu skaits Qn slānī | ID0.n |
| \( \Phi(\mathbf{x},\mathbf{y}) \) | \( \mathcal{L} \times \mathcal{L} \to \mathbb{R}^+ \) | TE pārneses lielums | ID0 (pamats) |
| \( \phi_0 \) | \( \hbar c/l_P \) | Maksimālais pārneses kvants (enerģija) | ID0 |
| \( \alpha_0 \) | \( 6\omega_0/7 \) | Matricas elastība | ID0 |
| \( G_0 \) | \( 6\omega_0\phi_0/49 \) | Gravitācijas konstante (bāze) | ID0 |
| \( G \) | \( G_0 (1 + \gamma \rho_{\mathcal{V}}/\rho_{\text{H0}}) \) | Mainīgā gravitācijas konstante | ID0 / ID-1 |
| \( \varepsilon_0 \) | \( \frac{6}{49} \cdot \frac{\hbar}{2\pi} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \) | Vakuuma caurlaidība | ID0 / ID-1 |
| \( \rho_{\mathcal{V}}(\mathbf{x}) \) | \( \rho_{\mathcal{V}}^{(0)} e^{-r/r_0} \) | Vertikāles enerģijas blīvums | ID-1 |
| \( \mathcal{T} \) | \( \mathcal{L} \to \mathcal{V} \) | Transformācijas zona (H0 → Vertikāle) | ID-1 / ID0 |
| \( \mathcal{P}_{L1} \) | \( \mathcal{V} \to \mathcal{L} \) | L1 zonas projekcijas operators | ID0 |
| \( C \) | \( \ell_k/n_k \approx 35.325 \) | Cikliskuma konstante | ID0.n |
| \( \gamma \) | \( 2\pi/C \approx 0.18 \) | Cikliskuma inversais mērogs | ID0 |

---

## 3. LĀDIŅA DABA MT — PĀRDEFINĒTA

**Vecā definīcija (v2.0):** Lādiņš ir bloķētu pārneses kanālu kopums, ko rada protona asimetriskā fāze.

**Jaunā definīcija (v3.0):**

> **Lādiņš ir matricas enerģijas akumulācijas režīms.** 
> - Tas atrodas **matricas apkārtējā struktūrā** (ne tikai protonā ID1.0) — matrica pati sevī ir akumulators.
> - Lādiņš **nebloķē** kanālus — tas **maina matricas pamatparametrus** (\( \varepsilon_0, G_0, \alpha \)), kad tā daudzums ir liels.
> - Protona (ID1.0) lādiņš ir tikai **lokāla izpausme** šim globālajam matricas stāvoklim.

**ID atbilstība:**
- Lādiņš kā **globāls matricas stāvoklis** — ID0 (matricas līmenis).
- Lādiņš kā **lokāla protona izpausme** — ID1.0 / ID-1.

**Strukturālais koeficients \( \kappa \):**
$$
\kappa = \frac{e^2}{\phi_0^2} = \frac{6}{49} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}
$$
kur \( 6/49 \) izriet no Q1 kombinatorikas, un \( \rho_{\mathcal{V}}/\rho_{\text{H0}} \) nosaka matricas akumulācijas spēju.

---

## 4. ID SISTĒMAS PAMATLĪMEŅI

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

Detalizēta ID sistēmas struktūra un piemēri ir sniegti ID_GRADIENT_lv.md.

---

## 5. PAMATDEFINĪCIJAS

### 5.1. Mūžība

Mūžība ir globāls enerģijas cikls. Tā ir augstākā zināmā organizācijas pakāpe, kuru šī teorija izmanto kā atskaites sistēmu. Mūžības pilnā struktūra teorijā netiek modelēta.

Mūžības cikls balstās uz divām savstarpēji saistītām sastāvdaļām — **Vertikāli** un **Horizontāli**.

**MT neapgalvo, ka Mūžībai ir sākums vai beigas — tā apraksta tās procesus.**

### 5.2. Vertikāle (ID-1)

Vertikāle veidojas Pamat-Horizontāles enerģiju nezūdamības, saglabāšanas un akumulācijas procesu rezultātā. Sasniedzot kritisko enerģijas akumulācijas līmeni, izveidojas jauna (smalkāka) Horizontāle. Šis cikliskais mehānisms veido Mūžības cikla pamatu un Vertikāles līmeņu hierarhiju.

**Vertikāle ir enerģijas akumulācijas sistēma.** Katrs Vertikāles līmenis atbilst noteiktam enerģijas uzkrājuma dziļumam (VEU H-3, H-4, ... H-min), kas ID sistēmā atbilst **ID-1.n**.

**Formāli:** Vertikāle ir enerģijas līmeņu kopa:
$$
\mathcal{V} = \{ E_{H-3}, E_{H-4}, \dots, E_{H-\text{min}} \}
$$
ar kopējo enerģiju \( E_{\mathcal{V}} = \sum_{k=3}^{\text{min}} E_{H-k} \).

Vertikāle nepārtraukti uztur enerģijas plūsmu uz H0 matricu caur **L1 zonu** un **TZ (Transformācijas zonu)**.

**Vertikāle nav "vieta" — tā ir enerģijas struktūra, kas nepārtraukti baro H0 matricu.**

### 5.3. Horizontāles (ID0 — ID5)

Horizontāle ir konkrētas Vertikāles stabilo enerģijas vienību matrica, kurā notiek diskrēta evolūcija pa secīgiem ID līmeņiem.

**Formāli:** Horizontāle \( H_n \) ir režģis \( \mathcal{L}_n \) ar Qn struktūru un TE pārneses lauku \( \Phi_n \).

**H0** ir viena no Horizontālēm — mūsu Visums. Tā nav Vertikāles centrs vai sākums.

**Horizontāle savā evolūcijā nevar apsteigt savu radītāju — nākamo augstāko (H+1) Horizontāli.**

### 5.4. L1 zona un cikliskums

**L1 zona** ir Vertikāles pirmais projekcijas slānis uz H0 matricu. Tā nav "vieta" — tā ir **enerģijas fokusēšanas struktūra**, kas pārveido Vertikāles plūsmu par H0 matricai saderīgām TE plūsmām. L1 darbojas divos režīmos:
- **Fokusēšana (H0 iekšpuse)** — rada diskrētos CMB pīķus (stāvviļņi, ID0.n).
- **Izkliede (protona ārpuse)** — rada nepārtraukto CMB fonu un sarkano nobīdi (ID-1).

Cikliskuma mērogs \( R_{L1} \approx 5.62 \, l_P \) nav fizisks rādiuss — tas ir **perioda garums**, kurā L1 fokusēšana iziet pilnu ciklu.

---

## 6. H0 EVOLŪCIJA — KVANTITATĪVAIS MODELS

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

### 6.1. Telpas paplašināšanās solis (kvantitatīvi)

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

## 7. MATRICA — STATISKA ARHITEKTŪRA, DINAMISKA ENERĢIJA

**Matrica (H0)** ir statiska arhitektūra — ID1 režģis, Qn struktūra un FV cikli nemainās. ID sistēmā tā atbilst **ID0** ar Qn slāņiem **ID0.n**.

Tomēr **matricas enerģētiskais saturs** nav statisks. To nosaka:
- **Vertikāles enerģētiskā piramīda** (\( \rho_{\mathcal{V}} \)).
- **H+n modulācijas** — liela mēroga pārneses struktūra.

**Fotons** ir brīvās enerģijas veidojums (VEU H-2 × H-3), kas mijiedarbojas ar matricu un tās enerģētisko saturu. Tā enerģijas zudums ceļojot caur Vertikāles lauku ir kvantitatīvi aprēķināms:
$$
\frac{dE}{dx} = -\beta \cdot E \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}
$$

---

## 8. PĀRBAUDĀMO PROGNOŽU KOPSAVILKUMS

MT kvantitatīvais formālisms un ID sistēma dod šādas pārbaudāmās prognozes:

| Prognoze | Vienādojums | Vērtība / prognoze | Pārbaudes metode | ID atbilstība |
|----------|-------------|-------------------|------------------|---------------|
| Smalkās struktūras konstante | \( \alpha = \frac{49 G_0}{24\pi \hbar c} \) | \( \alpha_{\text{MT}} \approx 0.0073 \) (< 0.4% novirze) | Precīzijas spektroskopija | ID1 |
| G mainība galaktiku centros | \( G(r) = G_0 \cdot (1 + \gamma \cdot \rho_{\mathcal{V}}(r)/\rho_{\text{H0}}) \) | \( G(0)/G_0 \approx 1.50 \) | GRAVITY interferometrs | ID2 / ID-1 |
| \( \varepsilon_0 \) atkarība no \( \rho_{\mathcal{V}} \) | \( \varepsilon_0 = \frac{6}{49} \cdot \frac{\hbar}{2\pi} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \) | — | Kvantu metroloģija | ID0 / ID-1 |
| 6. CMB pīķis | \( \ell_6 = C \cdot 47 \approx 1660 \) | \( \ell_6 \approx 1660 \) | CMB-S4, Simons Observatory | ID0.47 |
| 7. CMB pīķis | \( \ell_7 = C \cdot 55 \approx 1943 \) | \( \ell_7 \approx 1943 \) | CMB-S4, Simons Observatory | ID0.55 |
| CMB pīķu amplitūdas | \( c_n \propto n^3 \cdot \rho_{\mathcal{V}} \) | Pārbaudāms ar Planck/CBM-S4 | Augstas precizitātes CMB mērījumi | ID0.n / ID-1 |
| Neitrīno masu hierarhija | \( m_i = M_P \cdot \alpha^{n_i} \) | Normālā hierarhija, \( \sum m_i \approx 0.060 \, \text{eV} \) | DUNE, Hyper-Kamiokande, KATRIN | ID1.1 / ID-1 |
| Apziņas intensitāte anestēzijā | \( \mathcal{C} = \int \| \mathcal{P}_{L1} - \Phi \|^2 \) | \( \mathcal{C} \) palielinās anestēzijā | EEG/fMRI kvantitatīvs mērījums | ID1.4 / ID-1 / ID0 |

---

## 9. SECINĀJUMI

1. **MT ir kvantitatīvi formulēta teorija** — visi galvenie lielumi ir definēti ar operatoriem no MATHEMATICS formālisma v3.0.

2. **MT ir savienota ar ID sistēmu** — visi objekti tiek klasificēti pēc modulācijas un lieluma kategorijas, kas nodrošina vienotu organizācijas līmeņu sistēmu.

3. **MT ir pārbaudāma** — tā dod precīzas skaitliskās prognozes, ko var salīdzināt ar eksperimentiem.

4. **MT ir reducējama** — atbilstošās robežās tā pāriet klasiskajā fizikā (Ņūtona gravitācijā, Maksvela elektrodinamikā, kvantu mehānikā).

5. **MT nav nepieciešama tumšā matērija vai tumšā enerģija kā nezināmi spēki** — tos aizstāj ar Vertikāles enerģijas ietekmi uz G un fotona enerģijas zudumu.

6. **MT nav singularitāšu** — matrica pārslēdz H līmeni, neļaujot enerģijai sabrukt līdz bezgalībai.

7. **MT nepretendē noteikt Visuma izmēru** — tā izmanto cikliskumu kā strukturālo principu, un tās prognozes ir atkarīgas no cikliskuma mērogiem, nevis no absolūtajiem attālumiem.

8. **Lādiņš MT ir matricas enerģijas akumulācijas režīms** — tas maina matricas pamatparametrus, nevis bloķē kanālus.

---

## PIEZĪME

Šis dokuments ir **MT pamata kopsavilkums** ar savienojumu ar MATHEMATICS formālisma v3.0 versiju un ID sistēmu, kā arī kvantitatīvo prognožu kopsavilkumu. Tas nav pilnīgs teorijas apraksts, bet gan strukturēts izklāsts par teorijas darbības robežām, pamatprincipiem un pārbaudāmajām sekām. Detalizētāka informācija par atsevišķiem aspektiem ir pieejama citos MT dokumentos.

---

*Dokuments sagatavots: 2026. gada jūlijā*  
*Versija: 3.0 — pārrakstīta, iekļaujot cikliskuma principu, lādiņa pārdefinēšanu un atjauninātas prognozes*
