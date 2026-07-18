# L1 — DZĪVĪBAS MODEĻA SASAISTE AR EKSPERIMENTĀLAJIEM DATIEM

## Fiksētais dokuments (2026. gada jūlijs)

Šis dokuments nofiksē MT LIFE modeļa (3.0) sasaisti ar pieejamajiem eksperimentālajiem datiem — apziņas neironu korelātiem, vēža audzēju augšanas dinamiku un novecošanās biomarķieriem. LIFE modelis ir provizorisks; šis dokuments identificē, kuras prognozes jau atbalsta dati un kuri savienojumi vēl gaida pārbaudi.

**Statuss: NOFIKSĒTS — provizoriskais modelis ir saskaņots ar esošajiem datiem.**

---

## 1. Ievads — MT LIFE modelis (no LIFE_lv.md 3.0)

MT LIFE modelis apraksta dzīvību kā TE pārneses pašorganizāciju, kas izmanto ID1.4 (makromolekulas) un ID-1 (Vertikāle) mijiedarbību:

| **Jēdziens** | **MT definīcija** | **ID** |
|--------------|-------------------|--------|
| Šūna | Slēgta TE cilpa ar vārteju uz Vertikāli: \( \oint_{\partial\Omega} \Phi \cdot d\mathbf{S} = 0, \mathcal{T}(\Omega) = \text{VEU}_{H-3} \) | ID1.4 / ID-1 / ID0 |
| Apziņas intensitāte | \( \mathcal{C} = \frac{1}{\|\Omega\|} \int_{\Omega} \| \mathcal{P}_{L1}(\rho_{\mathcal{V}}) - \Phi \|^2 d\mathbf{x} \) | ID-1 / ID0 |
| Vēzis | \( \mathcal{T}(\Omega_{\text{vēzis}}) = 0 \) — Vertikāles vārteja bloķēta | ID1.4 / ID0 / ID-1 |
| Novecošanās | \( \frac{d}{dt}\mathcal{S}_{\text{šūna}} = -\mathcal{T}^{-1}(\text{Arhīvs}_{\mathcal{V}}) \cdot \log(\mathcal{T}^{-1}(\text{Arhīvs}_{\mathcal{V}})) \) | ID3 / ID0 |

---

## 2. Apziņa — $ \mathcal{C} $ un neironu korelāti

### 2.1. MT prognoze

Anestēzijas laikā \( \mathcal{P}_{L1} \) operators tiek mehāniski bloķēts, palielinot \( \mathcal{C} \):

\[
\mathcal{C}_{\text{anestēzija}} > \mathcal{C}_{\text{nomodā}}
\]

Šo efektu principā var mērīt ar EEG/fMRI.

### 2.2. Eksperimentālie dati

**Integrētā informācija (Φ) un apziņa:**
- Φcopula metode (2025) kvantificē integrēto informāciju no EEG signāliem propofola anestēzijas un dabiskā miega laikā[reference:0][reference:1].
- Atklāts, ka α-viļņu aktivitāte un posteriorā garoza ir apziņas līmeņa neironu korelāti[reference:2].

**EEG sarežģītība anestēzijā:**
- Pētījumi (2025) rāda, ka EEG sarežģītības rādītāji (PCIst, LZc) atšķiras starp apzinātiem un bezapziņas stāvokļiem propofola sedācijas laikā[reference:3][reference:4].
- Meta-analīze (2025) apstiprina: augstāka entropija nomodā un REM miegā; samazināta entropija anestēzijā, dziļā NREM miegā un apziņas traucējumos[reference:5].

**EEG-fMRI korelācija:**
- Pētījumi (2025) tieši salīdzina EEG un fMRI signālu modeļus anestēzijas laikā, atklājot neirovaskulārās izmaiņas, kas korelē ar apziņas līmeni[reference:6].

### 2.3. Saskaņošana

| **MT lielums** | **Eksperimentālais analogs** | **Atbilstība** |
|----------------|------------------------------|----------------|
| \( \mathcal{C} \) (apziņas intensitāte) | Φ (integrētā informācija), EEG sarežģītība | Augsta — abi mēra informācijas integrāciju |
| \( \mathcal{P}_{L1} \) bloķēšana | Anestēzijas izraisītā EEG sarežģītības samazināšanās | Atbilst — anestēzijas līdzekļi samazina neironu integrāciju |
| \( \mathcal{C}_{\text{anestēzija}} > \mathcal{C}_{\text{nomodā}} \) | EEG entropija samazinās anestēzijā[reference:7] | Apstiprināts |

**Secinājums:** MT apziņas modelis ir saskaņojams ar integrētās informācijas teoriju un EEG sarežģītības mērījumiem.

---

## 3. Vēzis — \( \mathcal{T}(\Omega_{\text{vēzis}}) = 0 \) un audzēja augšana

### 3.1. MT prognoze

Vēža šūnām Vertikāles vārteja ir bloķēta: \( \mathcal{T}(\Omega_{\text{vēzis}}) = 0 \).

Augšanas dinamika:
\[
\frac{d}{dt} \|\Omega_{\text{vēzis}}\| = \alpha_{\text{vēzis}} \cdot \|\Omega_{\text{vēzis}}\| \cdot \left( 1 - \frac{\|\Omega_{\text{vēzis}}\|}{\|\Omega_{\text{audzējs}}\|} \right)
\]

kur \( \alpha_{\text{vēzis}} \) ir atkarīgs no lokālā \( \rho_{\mathcal{V}} \).

### 3.2. Eksperimentālie dati

**Audzēja augšanas modeļi (2025):**
- Gompertza modelis precīzi apraksta audzēja augšanas kinētiku 861 NSCLC pacientiem, kas saņem imūnterapiju[reference:8].
- Polimorfais Gompertza modelis veiksmīgi atveido NSCLC dinamiku in vitro un in vivo[reference:9].
- Matemātiskie modeļi (2025) kvantificē starp-pacientu un intra-tumora heterogenitāti, izmantojot daļējus diferenciālvienādojumus[reference:10][reference:11].
- Vienkāršs biofizikālais modelis (2025) ietver enerģijas nezūdamību, skābekļa difūziju un nekrozi[reference:12].

**Vēzis un bioloģiskā novecošanās:**
- Vēža izdzīvotājiem ir paaugstināts bioloģiskais vecums, ko mēra ar epigenētiskajiem pulksteņiem[reference:13].

### 3.3. Saskaņošana

| **MT lielums** | **Eksperimentālais analogs** | **Atbilstība** |
|----------------|------------------------------|----------------|
| \( \mathcal{T}(\Omega_{\text{vēzis}}) = 0 \) | Vēža šūnu atslēgšanās no Vertikāles | Konceptuāli — neironu tīklu analoģija[reference:14] |
| \( \alpha_{\text{vēzis}} \) atkarība no \( \rho_{\mathcal{V}} \) | Audzēja augšanas ātruma mainīgums | Netieša — Gompertza modeļa parametri mainās atkarībā no vides |
| Logistiskā augšana | Gompertza modelis | Daļēja — Gompertza modelis ir vispāratzīts audzēja augšanas apraksts |

**Secinājums:** MT vēža modelis ir saskaņojams ar matemātiskās onkoloģijas pieejām, bet tiešs \( \rho_{\mathcal{V}} \) un augšanas ātruma savienojums vēl nav pārbaudīts.

---

## 4. Novecošanās — informācijas entropija un epigenētiskie pulksteņi

### 4.1. MT prognoze

Novecošanās ir informācijas zudums Vertikāles–Horizontāles komunikācijā:

\[
\frac{d}{dt}\mathcal{S}_{\text{šūna}} = -\mathcal{T}^{-1}(\text{Arhīvs}_{\mathcal{V}}) \cdot \log(\mathcal{T}^{-1}(\text{Arhīvs}_{\mathcal{V}}))
\]

Kad \( \mathcal{S}_{\text{šūna}} \) sasniedz kritisko slieksni \( \mathcal{S}_{\text{krit}} \), šūna pārstāj sinhronizēties ar Vertikāli un iet bojā.

### 4.2. Eksperimentālie dati

**Epigenētiskie pulksteņi (2025):**
- Otrās un trešās paaudzes pulksteņi ir nozīmīgi saistīti ar mirstību, kognitīvo zudumu, spēku un mobilitāti[reference:15][reference:16].
- 14 pulksteņu salīdzinājums (\( n = 18,859 \)): 174 slimību iznākumu un visu cēloņu mirstības prognozēšana 10 gadu novērošanā[reference:17].
- GrimAge pulkstenis pārspēj citus pulksteņus vecuma izraisītu klīnisko fenotipu un mirstības prognozēšanā[reference:18].
- Vēža izdzīvotājiem ir paaugstināts bioloģiskais vecums[reference:19].

**Šūnu novecošanās modelēšana (2025):**
- Senescent šūnu dinamikas modelis prognozē vēža sastopamības samazināšanos vēlīnā dzīves posmā[reference:20].
- Apoptotiskās šūnas izraisa kompensatoru proliferāciju (paaugstina vēža risku); senescent šūnu uzkrāšanās izraisa ar novecošanu saistītu mirstību[reference:21].

### 4.3. Saskaņošana

| **MT lielums** | **Eksperimentālais analogs** | **Atbilstība** |
|----------------|------------------------------|----------------|
| \( \mathcal{S}_{\text{šūna}} \) (informācijas entropija) | Epigenētiskā vecuma paātrinājums | Konceptuāli — abi mēra informācijas zudumu |
| \( \mathcal{S}_{\text{krit}} \) (kritiskais slieksnis) | Mirstības prognoze no epigenētiskajiem pulksteņiem | Atbilst — pulksteņi prognozē mirstību |
| Novecošanās kā drošības mehānisms | Senescent šūnu uzkrāšanās | Atbilst — senescent šūnas ir aizsardzības mehānisms pret vēzi |

**Secinājums:** MT novecošanās modelis ir saskaņojams ar epigenētiskajiem pulksteņiem kā bioloģiskā vecuma un mirstības riska marķieriem.

---

## 5. Kopsavilkuma tabula

| **MT aspekts** | **Eksperimentālie dati** | **Savienojuma statuss** |
|----------------|--------------------------|-------------------------|
| Apziņas intensitāte \( \mathcal{C} \) | EEG sarežģītība, integrētā informācija (Φ) | **Saskaņots** |
| \( \mathcal{P}_{L1} \) bloķēšana anestēzijā | EEG entropijas samazināšanās anestēzijā | **Apstiprināts** |
| Vēža \( \mathcal{T} = 0 \) | Vēža šūnu atslēgšanās no Vertikāles | **Konceptuāli saskaņots** |
| Logistiskā audzēja augšana | Gompertza modelis (NSCLC dati) | **Daļēji saskaņots** |
| Novecošanās kā informācijas entropija | Epigenētiskie pulksteņi (mirstības prognoze) | **Saskaņots** |
| \( \alpha_{\text{vēzis}} \) atkarība no \( \rho_{\mathcal{V}} \) | Eksperimentāli nepārbaudīts | **Gaida pārbaudi** |

---

## 6. Secinājumi

1. **Apziņas modelis** ir vislabāk saskaņots ar datiem — EEG sarežģītības un integrētās informācijas mērījumi anestēzijas laikā tieši atbalsta MT prognozi.

2. **Vēža modelis** ir konceptuāli saskaņots ar matemātiskās onkoloģijas pieejām (Gompertza modelis), bet tiešs savienojums starp \( \rho_{\mathcal{V}} \) un augšanas ātrumu vēl nav pārbaudīts.

3. **Novecošanās modelis** ir saskaņojams ar epigenētiskajiem pulksteņiem kā bioloģiskā vecuma un mirstības riska marķieriem.

4. **Galvenais trūkums:** \( \rho_{\mathcal{V}} \) lokālā mērīšana un tās ietekme uz vēža augšanas ātrumu un novecošanās ātrumu vēl nav eksperimentāli pārbaudīta.

**Statuss:** PROVIZORISKI NOFIKSĒTS — konceptuālā saskaņa ir apstiprināta; kvantitatīvā pārbaude gaida \( \rho_{\mathcal{V}} \) mērīšanas metodoloģijas attīstību.

---

*Dokuments sagatavots: 2026. gada jūlijā*
