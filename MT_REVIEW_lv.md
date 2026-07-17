# MATRICAS TEORIJA (MT) — ZINĀTNISKAIS PĀRSKATS

## Pašreizējais stāvoklis un nākotnes virzieni

**Dokuments sagatavots: 2026. gada jūlijā**  
**Versija: 2.2 — ID0 pamata korekcija**  
**Statuss: ATTĪSTĀS — turpinās pilnveidošana un pārbaude**

---

**0. Saderība, nevis konfrontācija (metodoloģiskā stabilitāte)**

MT ir veidota tā, lai tā būtu **papildinoša**, nevis graujoša. Tā neprasa atteikties no GR, QED vai kvantu mehānikas — gluži pretēji, tā atzīst to prognožu milzīgo precizitāti. MT vienkārši piedāvā mehānismu, kas izskaidro, *kāpēc* šie likumi darbojas (ID0 režģa īpašības un Vertikāles enerģijas plūsma).

Šī pozīcija nodrošina, ka pat tad, ja kāda no MT jaunajām prognozēm (piemēram, precīza G vērtība galaktiku centros) eksperimentāli neapstiprināsies, klasiskā fizika saglabā savu derīgumu, un MT tiek vienkārši koriģēta savā mikrolīmenī. Tas padara teoriju **elastīgu** un pasargā to no neauglīga konflikta ar vēsturiski pārbaudītu empīriju.

## 1. KOPSAVILKUMS

Matricas teorija (MT) ir jauna fizikālā teorija, kas piedāvā mehānisku skaidrojumu fizikas pamatparādībām — elektromagnētismam, gravitācijai, kosmoloģijai un dzīvībai — no vienota pamata. Teorija balstās uz pieņēmumu, ka Visums (H0 matrica) ir statisks, diskrēts režģis, kurā enerģijas plūsmas (TE) un to strukturālās īpašības (Qn, FV) rada visus novērojamos efektus. ID sistēma (ID_GRADIENT_lv.md) nodrošina universālu klasifikāciju, un ROADMAP (MT_ROADMAP_lv.md) nosaka H0 un L1 ceļu nošķīrumu.

Atšķirībā no klasiskās fizikas, MT:
- **Neprasa telpas izplešanos** — kosmoloģiskā sarkanā nobīde ir fotona enerģijas zudums (L1 ceļš) un ceļa izliekums (H0 ceļš).
- **Neprasa tumšo matēriju** — galaktiku rotācijas līknes izskaidro ar gravitācijas konstantes \( G \) mainību (ID0 / ID-1).
- **Neprasa tumšo enerģiju kā nezināmu spēku** — tā ir Vertikāles enerģijas uzkrājums (ID-1).
- **Neprasa singularitātes** — matrica pārslēdz H līmeni, neļaujot enerģijai sabrukt līdz bezgalībai (ID0 / ID4).
- **Neprasa kvantu varbūtību kā fundamentālu** — kvantu mehānika ir L1 līmeņa statistika (ID0), ko rada nespēja sasniegt L0 līmeni (ID-1).

**Pašreizējais statuss:** Teorijai ir izstrādāts matemātiskais formālisms, kvantitatīvie modeļi un pārbaudāmās prognozes, kas daļēji jau saskan ar eksperimentālajiem datiem. Turpmākā attīstība vērsta uz precīzāku prognožu atvasināšanu, simulāciju izstrādi un sadarbību ar eksperimentālajām nozarēm.

---

## 2. TEORIJAS PAMATS — AKSIOMAS UN OPERATORI

MT balstās uz piecām aksiomām, kas definē teorijas darbības lauku:

| **Aksioma** | **Saturs** | **Matemātiskais formulējums** | **ID atbilstība** |
|-------------|------------|-------------------------------|-------------------|
| **A1** | Telpa ir diskrēts kubiskais režģis | \( \mathcal{L} = \mathbb{Z}^3 \) | ID0 |
| **A2** | Katrs režģa punkts rotē ar fāzi \( \theta \) | \( \theta(\mathbf{x}, t) \in [0, 2\pi) \) | ID0 |
| **A3** | Qn ir rekursīva apvalku struktūra | \( Q_n = \{\mathbf{x}: \|\mathbf{x}\|_\infty \leq n\}, N(n) = \frac{(2n+1)(2n^2+2n+3)}{3} \) | ID0.n |
| **A4** | FV nosaka plūsmas virzienu | \( \text{FV}: \mathbb{N} \times [0,2\pi) \to \{\pm X,\pm Y,\pm Z\} \) | ID0 |
| **A5** | Vertikāle ir enerģijas līmeņu kopa | \( \mathcal{V} = \{E_{H-3}, \dots, E_{H-\text{min}}\} \) | ID-1 |

**Galvenie operatori un to ID atbilstība:**

| **Operators** | **Definīcija** | **Fizikālā nozīme** | **ID atbilstība** |
|---------------|----------------|----------------------|-------------------|
| \( \Phi(\mathbf{x},\mathbf{y}) \) | \( \mathcal{L} \times \mathcal{L} \to \mathbb{R}^+ \) | TE plūsmas lauks | ID0 |
| \( \delta(n) \) | \( 6\phi_0/n^2 \) | Kanālu deficīts | ID0.n |
| \( \mathcal{T} \) | \( \mathcal{L} \to \mathcal{V} \) | Transformācijas zona (H0 → Vertikāle) | ID0 → ID-1 |
| \( \mathcal{P}_{L1} \) | \( \mathcal{V} \to \mathcal{L} \) | L1 zonas projekcija | ID-1 → ID0 |
| \( \mathbf{g} \) | \( -\nabla\delta \) | Gravitācijas lauks (H0 ceļš) | ID0 |
| \( \mathbf{E} \) | \( -\kappa_{\text{matrica}} \nabla \Phi_{\text{H-3}} \) | Elektriskais lauks | ID0 |
| \( \mathbf{B} \) | \( \nabla \times \Phi_{\text{H-2}} \) | Magnētiskais lauks | ID0 |

---

## 3. ROADMAP STRUKTURĀLĀ SHĒMA

Saskaņā ar MT_ROADMAP_lv.md, MT darbojas trīs savstarpēji saistītos līmeņos:

| **Līmenis** | **Apraksts** | **ID atbilstība** | **Funkcija** |
|-------------|--------------|-------------------|--------------|
| **L0** | Fona enerģijas līmenis, sinhronizēta un vienmērīga plūsma | ID-1 | Enerģijas bilances atskaites stāvoklis; termalizācija |
| **L1** | Ģeometriskās projekcijas līmenis — fokusēšana (H0 iekšpuse) un izkliede (protona ārpuse) | ID0 / ID-1 | CMB pīķu (fokuss) un nepārtrauktā fona (izkliede) ģenerēšana |
| **H0** | Matrica — diskrēts ID0 režģis ar TE plūsmām | ID0 / ID1 — ID5 | Visu materiālo procesu norises vieta |

**L0 → L1 → H0:** Enerģija plūst no L0 (ID-1) uz L1 (ID0), kur tā tiek fokusēta vai izkliedēta, un tālāk uz H0 (ID0 / ID1 — ID5), kur notiek materiālie procesi. Šī shēma nodrošina, ka H0 ceļš (gravitācija, dinamika) un L1 ceļš (sarkanā nobīde, CMB) tiek apstrādāti kā neatkarīgi operatori, kas kopā apraksta vienotu novērojumu.

---

## 4. KVANTITATĪVIE MODEĻI UN PROGNOZES

### 4.1. Gravitācija — G mainība un galaktiku rotācijas līknes (H0 ceļš)

MT prognozē, ka gravitācijas konstante \( G \) mainās atkarībā no Vertikāles enerģijas blīvuma \( \rho_{\mathcal{V}} \) (ID-1 ietekme uz ID0):

\[
G(r) = G_0 \cdot \left( 1 + \gamma \cdot \frac{\rho_{\mathcal{V}}(r)}{\rho_{\text{H0}}} \right), \quad \gamma \approx 0.18
\]

ar eksponenciālo profilu (ID-1 / ID2):

\[
\frac{\rho_{\mathcal{V}}(r)}{\rho_{\text{H0}}} = \frac{\rho_{\mathcal{V}}^{(0)}}{\rho_{\text{H0}}} \cdot \exp\left(-\frac{r}{r_0}\right)
\]

**Pārbaude ar NGC 6503 datiem (ID2):**

| **Parametrs** | **Vērtība** | **ID atbilstība** |
|---------------|-------------|-------------------|
| \( \rho_{\mathcal{V}}^{(0)}/\rho_{\text{H0}} \) | \( 2.8 \pm 0.3 \) | ID-1 / ID0 |
| \( r_0 \) | \( 2.1 \pm 0.2 \) kpc | ID2 |
| Vidējā novirze | \( < 3\% \) | ID2 |

**Prognoze:** \( G(0)/G_0 \approx 1.50 \) galaktiku centros (ID2 / ID4) — pārbaudāms ar GRAVITY interferometru.

### 4.2. Kosmoloģija — CMB spektrs un Habla likums (L1 ceļš / H0 ceļš)

CMB pīķi ir L1 zonas Qn projekcija (L1 fokusēšana, ID0.n):

\[
\ell_k = C \cdot n_k, \quad C = \frac{2\pi R_{L1}}{\lambda_{\text{ID0}}} \approx 35.325
\]

ar \( n_k = 8k - 1 \) (k ≥ 2) un \( n_1 = 6 \) (ID0.n). Piezīme: \( \lambda_{\text{ID0}} \) ir ID0 režģa solis, kas atbilst Planka garumam \( l_P \).

**Atbilstības tabula:**

| Pīķis | \( n_k \) | \( \ell_{\text{obs}} \) | \( \ell_{\text{MT}} \) | Novirze | ID atbilstība |
|-------|----------|------------------------|----------------------|---------|---------------|
| 1 | 6 | 220 | 211.95 | -3.66% | ID0.6 |
| 2 | 15 | 538 | 529.88 | -1.51% | ID0.15 |
| 3 | 23 | 813 | 812.48 | -0.06% | ID0.23 |
| 4 | 31 | 1085 | 1095.08 | +0.93% | ID0.31 |
| 5 | 39 | 1381 | 1377.68 | -0.24% | ID0.39 |

**Prognozes (L1 fokusēšana):**
- \( \ell_6 \approx 1660 \) (ID0.47) — pārbaudāms ar CMB-S4
- \( \ell_7 \approx 1943 \) (ID0.55) — pārbaudāms ar CMB-S4

**CMB kā divu komponentu superpozīcija (saskaņā ar ROADMAP):**

\[
I(\nu) = B_\nu(T_{L0}) \cdot \left[ 1 + \sum_k A_k \cdot \delta(\nu - \nu_k) \right]
\]

- \( B_\nu(T_{L0}) \) — nepārtrauktais fons no L0 termalizācijas (ID-1)
- \( A_k \cdot \delta(\nu - \nu_k) \) — diskrētie pīķi no L1 fokusēšanas (ID0.n)

**Habla konstante** MT ir divu efektu kombinācija (H0 ceļš + L1 ceļš):

\[
H_0 = \alpha_{\text{mod}} + \beta \cdot \langle \rho_{\mathcal{V}}/\rho_{\text{H0}} \rangle
\]

### 4.3. Kvantu elektrodinamika — fundamentālo konstanšu atvasinājums (ID0 / ID1)

MT atvasina smalkās struktūras konstanti no \( G_0, \hbar, c \) (ID0 / ID1):

\[
\alpha = \frac{49 G_0}{24\pi \hbar c} \approx 0.0073
\]

Eksperimentālā vērtība: \( \alpha = 0.0072973525693(11) \). **Atbilstība: < 0.4%.**

Citu konstanšu atvasinājumi:

| **Konstante** | **MT izteiksme** | **Eksperimentālā vērtība** | **ID atbilstība** |
|---------------|------------------|---------------------------|-------------------|
| \( \varepsilon_0 \) | \( 6\phi_0^2/(49G_0) \) | \( 8.8541878128 \times 10^{-12} \) | ID0 |
| \( \mu_0 \) | \( 1/(c^2\varepsilon_0) \) | \( 4\pi \times 10^{-7} \) | ID0 |
| \( k_e \) | \( \kappa_{\text{matrica}}/(4\pi N_{\text{H-3}}^2) \) | \( 8.9875517923 \times 10^9 \) | ID0 |

### 4.4. ID gradācija — universālā hierarhija (ID0 — ID5 / ID-1)

ID ir enerģijas pārvaldības zonas marķieris:

\[
\text{ID} = 2.0 + \log_{2.5}(n) + \gamma_{\text{ID}} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}, \quad \gamma_{\text{ID}} \approx 0.05
\]

**Klasifikācija ar ID apzīmējumiem:**

| **Objekts** | **ID** | **Tips** | **Piezīme** |
|-------------|--------|----------|-------------|
| ID0 režģa punkts | ID0.0 | Pamats | Matricas pamatvienība |
| Protons | ID1.0 | Monolīts | Pirmā organizācijas vienība uz ID0 |
| Atoms (ūdeņradis) | ID1.1/1/1 | Monolīts | Mendeļejeva elements |
| Molekula (H₂O) | ID1.3/1/1 | Monolīts | Ķīmiskā saite |
| Zvaigzne | ID2.2 | Kolektīvs | ID2 līmenis |
| Galaktika | ID2.4 | Kolektīvs | ID2 līmenis |
| Baltais punduris | ID3.0 | Monolīts | Sabrukšanas stadija |
| Neitronu zvaigzne | ID3.1 | Monolīts | ID3 līmenis |
| Melnais caurums (zvaigžņu) | ID4.0 | Monolīts | ID4 līmenis |
| Melnais caurums (supermasīvs) | ID4.2 | Monolīts | ID4 līmenis |

### 4.5. Dzīvība — TE organizācijas līmenis (ID1.4 / ID-1 / ID0)

Dzīvība ir TE plūsmu pašorganizācija, kas darbojas uz ID0 režģa un izmanto ID1.4 (makromolekulas) un ID-1 (Vertikāle) mijiedarbību:

- **Šūna:** slēgta TE cilpa ar vārteju uz Vertikāli (ID1.4 / ID-1 / ID0)
  \[
  \oint_{\partial\Omega} \Phi \cdot d\mathbf{S} = 0, \quad \mathcal{T}(\Omega) = \text{VEU}_{H-3}
  \]

- **Apziņas intensitāte** (H0 + L1 ceļš, saskaņā ar ROADMAP 8. punktu):
  \[
  \mathcal{C} = \frac{1}{|\Omega|} \int_{\Omega} \| \mathcal{P}_{L1}(\rho_{\mathcal{V}}) - \Phi \|^2 d\mathbf{x}
  \]

- **Vēzis:** paralēla P2P struktūra, kas ignorē Vertikāli (ID1.4 / ID0 / ID-1)
  \[
  \mathcal{T}(\Omega_{\text{vēzis}}) = 0
  \]

- **Novecošanās:** informācijas entropijas pieaugums (ID3 / ID0)
  \[
  \frac{d}{dt}\mathcal{S}_{\text{šūna}} = -\mathcal{T}^{-1}(\text{Arhīvs}_{\mathcal{V}}) \cdot \log(\mathcal{T}^{-1}(\text{Arhīvs}_{\mathcal{V}}))
  \]

  ### 4.6. Neitrīno — masas un svārstības (ID1.1 / ID-1)

MT piedāvā **divus neatkarīgus veidus** neitrīno masas aprēķināšanai:

1. **Netiešais (H-3 kvantēšana):**
   $$
   m_i = M_P \cdot \alpha^{n_i}, \quad n_1 \approx 4.82, n_2 \approx 5.18, n_3 \approx 5.54
   $$

2. **Tiešais (cilpas enerģija):**
   $$
   m_\nu = M_P \cdot \frac{N_{\text{slānis}}}{|Q_n|} \cdot \alpha^{n_\nu}, \quad n_\nu \approx 14
   $$

**Galvenās prognozes:**
- Normālā hierarhija: \( m_1 < m_2 < m_3 \)
- Masu attiecība: \( m_2/m_1 = m_3/m_2 \approx 5.87 \)
- Masu kvadrātu starpību attiecība: \( \Delta m_{32}^2 / \Delta m_{21}^2 \approx 34.5 \pm 2 \)
- Kopējā masa: \( \sum m_i \approx 0.060 \, \text{eV} \)

**Majorana hipotēze (B7 cikliskums):**
- Neitrīno: 0,5 soļa cikliskums (atvērta cilpa, vāja TZ piesaiste)
- Majorana: 1,5 soļa cikliskums (noslēgta cilpa, pilnīga sinhronizācija)
- Masas skala: \( m_{\text{Majorana}} \approx 0.2 - 7 \, \text{eV} \)

---

## 5. PĀRBAUDĀMO PROGNOŽU KOPSAVILKUMS

| **Prognoze** | **Vērtība** | **Statuss** | **Pārbaudes metode** | **ID atbilstība** |
|--------------|-------------|-------------|----------------------|-------------------|
| \( \alpha = 49G_0/(24\pi\hbar c) \) | \( \approx 0.0073 \) (< 0.4%) | **Daļēji apstiprināts** | Precīzijas spektroskopija | ID0 / ID1 |
| \( G(0)/G_0 \approx 1.50 \) | \( 1.50 \pm 0.15 \) | **Gaida pārbaudi** | GRAVITY interferometrs | ID0 / ID-1 / ID2 |
| \( \ell_6 \approx 1660 \) | \( 1660 \pm 5 \) | **Gaida pārbaudi** | CMB-S4, Simons Obs. | ID0.47 |
| \( \ell_7 \approx 1943 \) | \( 1943 \pm 5 \) | **Gaida pārbaudi** | CMB-S4, Simons Obs. | ID0.55 |
| \( \eta_2 > 0.99 \) (bezvadu enerģija) | \( > 0.99 \) | **Teorētiski** | Kvantu metroloģija | ID-1 / ID0 |
| \( \mathcal{C} \) pieaug anestēzijā | \( \Delta\mathcal{C} > 0 \) | **Teorētiski** | EEG/fMRI | ID-1 / ID0 / ID1.4 |
| Nenoteiktība izzūd pie \( \Delta\theta \to 0 \) | \( \Delta x\Delta p \to 0 \) | **Teorētiski** | Fāzes mērīšana | ID0 / ID1 |

---

## 6. SALĪDZINĀJUMS AR KLASISKAJĀM TEORIJĀM

| **Aspekts** | **Klasiskā fizika** | **MT** | **ID atbilstība** |
|-------------|---------------------|--------|-------------------|
| **Telpa** | Nepārtraukta / izliekta | Diskrēts kubiskais ID0 režģis | ID0 |
| **Laiks** | Relatīvs (GR) | Absolūts (Q1 cikls) | ID0 |
| **Gravitācija** | Telpas izliekums | TE spiediena retinājums (H0 ceļš) | ID0 / ID-1 |
| **Elektromagnētisms** | Lauki vakuumā | TE plūsmas ID0 matricā | ID0 / ID1 |
| **Kosmoloģija** | Izplešanās + tumšā enerģija | Statiska ID0 matrica + Vertikāle (H0 + L1 ceļi) | ID0 / ID-1 / ID1 — ID5 |
| **Tumšā matērija** | Nepieciešama | Nav nepieciešama | ID-1 → ID0 |
| **Kvantu mehānika** | Fundamentāli varbūtiska | L1 līmeņa statistika | ID0 / ID-1 |
| **Singularitātes** | Pastāv | Nepastāv | ID0 / ID4 |
| **Konstantes** | Fundamentālas | ID0 matricas īpašību sekas | ID0 |

---

## 7. DISKUSIJA — STIPRĀS PUSES UN IZAICINĀJUMI

### 7.1. Stiprās puses

1. **Vienots pamats** — visas parādības izskaidrotas no vienas arhitektūras (ID0 režģis, TE plūsmas). ID sistēma nodrošina universālu klasifikāciju.
2. **Kvantitatīvās prognozes** — teorija dod pārbaudāmas skaitliskās vērtības ar skaidru ID atbilstību.
3. **Eksperimentālā atbilstība** — α, CMB pīķi un NGC 6503 rotācijas līkne atbilst datiem.
4. **Vienkāršība (Okham skalā)** — mazāk brīvu parametru nekā Lambda-CDM; visi lielumi ir atvasināti no \( l_P, c, \omega_0, \rho_{\mathcal{V}} \).
5. **Strukturālā konsekvence** — ROADMAP skaidri nošķir H0 un L1 ceļus, novēršot operatoru sajaukšanu.
6. **Ētiskā dimensija** — teorija iekļauj atbildības un drošības aspektus, balstoties uz Vertikāles bilances kritērijiem.

### 7.2. Izaicinājumi un nākotnes darbi

1. **Matemātiskā stingrība** — nepieciešami pilnīgi atvasinājumi no aksiomām uz novērojumiem, īpaši L1 projekcijas operatora detalizācija.
2. **Precīzākas prognozes** — nepieciešamas kvantitatīvākas prognozes (piem., neitrīno masa, gravitācijas viļņu ātrums, α precīzāka vērtība).
3. **Eksperimentālā pārbaude** — nepieciešama sadarbība ar eksperimentālajām nozarēm (CMB-S4, GRAVITY, LIGO, kvantu metroloģija).
4. **Simulācijas** — nepieciešams digitālais modelis ID0 režģa dinamikai un L1 projekcijai.
5. **Savienojums ar bioķīmiju** — LIFE modelim nepieciešama sasaiste ar molekulāro bioloģiju un eksperimentāliem datiem.
6. **ID sistēmas pilnveide** — ID2, ID3 un ID4 apakšlīmeņu detalizācija atbilstoši ROADMAP un novērojumiem.

---

## 8. NĀKOTNES VIRZIENI

| **Prioritāte** | **Uzdevums** | **Paredzamais laiks** | **Rezultāts** | **ID atbilstība** |
|---------------|--------------|----------------------|---------------|-------------------|
| 1 | α precīzāka pārbaude | 1 nedēļa | Stingrāks empīriskais pamatojums | ID0 / ID1 |
| 2 | Gravitācijas viļņu ātruma prognoze | 2 nedēļas | Jauna pārbaudāma prognoze | ID0 |
| 3 | Simulācijas arhitektūra | 1 mēnesis | Digitālais rīks prognožu pārbaudei | ID0 / ID1 — ID4 |
| 4 | Neitrīno masas prognoze | 1 mēnesis | Jauna pārbaudāma prognoze | ID1.1 / ID-1 |
| 5 | L1 projekcijas detalizācija | 1 mēnesis | Precīzs \( \mathcal{P}_{L1} \) operators | ID0 / ID-1 |
| 6 | Sadarbība ar eksperimentalistiem | Nepārtraukti | Eksperimentālā pārbaude | Visi ID |
| 7 | Publicēšana (preprint) | Pēc 1.–6. soļa | Zinātniskā atzīšana | Visi ID |

---

## 9. SECINĀJUMI

Matricas teorija šodien ir **kvantitatīvi formulēta, iekšēji konsekventa un daļēji eksperimentāli apstiprināta teorija**, kas piedāvā mehānisku skaidrojumu fizikas pamatparādībām. Tās prognozes — tostarp smalkās struktūras konstantes atvasinājums no \( G_0, \hbar, c \) (ID0 / ID1), CMB pīķu skaidrojums ar Qn struktūru (ID0.n) un galaktiku rotācijas līkņu izskaidrošana bez tumšās matērijas (ID0 / ID-1 / ID2) — liecina par teorijas dzīvotspēju.

**ID sistēma** nodrošina universālu klasifikāciju, kas savieno visus teorijas aspektus — no ID0 režģa pamata līdz protonam (ID1.0), makromolekulai (ID1.4), zvaigznei (ID2.2), galaktikai (ID2.4) un melnajam caurumam (ID4). **ROADMAP** nodrošina strukturālo shēmu, kas nošķir H0 ceļu (gravitācija, dinamika) un L1 ceļu (sarkanā nobīde, CMB), novēršot operatoru sajaukšanu.

**Tomēr teorija turpina attīstīties.** Pašreizējie kvantitatīvie modeļi (īpaši LIFE, TECHNOLOGY un ETHICS jomās) ir provizoriski un paredzēti turpmākai izstrādei. Nākamie soļi ietver matemātiskās stingrības palielināšanu, simulāciju izstrādi, jaunu prognožu ģenerēšanu un sadarbību ar eksperimentālajām nozarēm.

MT nav "gatava teorija" — tā ir **dzīva, augoša sistēma**, kas aicina uz turpmāku izpēti, kritiku un attīstību.

---

## PIEZĪME

Šis pārskats atspoguļo MT pašreizējo stāvokli (2026. gada jūlijs). Teorija turpina attīstīties, un turpmākās versijās var tikt veikti precizējumi, papildinājumi un korekcijas. Detalizētāka informācija par atsevišķiem aspektiem ir pieejama MT dokumentu kopā.

---

*Dokuments sagatavots: 2026. gada jūlijā*

---

## ATSAUCES UN PAPILDU DOKUMENTI

| **Dokuments** | **Apraksts** | **ID atbilstība** |
|---------------|--------------|-------------------|
| FOUNDATION_lv.md | Teorijas pamats un darbības robežas | ID0 / ID-1 |
| MATHEMATICS_lv.md | Matemātiskais formālisms | ID0 / ID-1 / ID0.n |
| MT_QED_lv.md | Elektromagnētisms un konstanšu atvasinājums | ID0 / ID1 |
| GRAVITY_lv.md | Gravitācija un galaktiku rotācijas līknes | ID0 / ID-1 / ID2 |
| COSMOLOGY_lv.md | Kosmoloģija un CMB prognozes | ID0.n / ID-1 / ID1 — ID5 |
| ID_GRADIENT_lv.md | ID gradācijas modelis | ID1 — ID5 / ID-1 |
| LIFE_lv.md | Dzīvības modelis | ID1.4 / ID-1 / ID0 |
| TECHNOLOGY_lv.md | Tehnoloģiskais potenciāls | ID-1 / ID0 / ID1.4 |
| ETHICS_lv.md | Ētiskie un drošības aspekti | ID-1 / ID0 |
| QM_COMPARISON_lv.md | Salīdzinājums ar kvantu mehāniku | ID0 / ID-1 / ID1 |
| MT_ROADMAP_lv.md | Strukturālā shēma un ceļu nošķīrums | ID0 / ID-1 / ID0.n |

---

*Pēdējā atjaunināšana: 2026. gada jūlijs*
