# KVANTU MEHĀNIKA — SALĪDZINĀJUMS AR MT

## 3.1 versija (2026. gada jūlijs) — precizēta pēc komutācijas relācijas atvasinājuma

Šis dokuments salīdzina klasisko kvantu mehāniku un MT pieejas, izejot cauri klasiskajai loģiskajai secībai. Tas ir savienots ar MATHEMATICS formālismu (3.0), ID sistēmu (3.0) un jauno komutācijas relācijas atvasinājumu (3.1), sniedzot kvantitatīvu skatījumu uz to, kur MT un klasiskā fizika sakrīt un kur tās atšķiras.

**Metodoloģiskais priekšnoteikums:** MT ir papildinošs ietvars, kas sniedz mehānisku izcelsmi klasiskās fizikas fenomenoloģiskajiem likumiem. Kvantu mehānika paliek spēkā savā darbības zonā (L1, ID0) kā precīzs prognozēšanas instruments. MT nenoliedz QM derīgumu — tā parāda, ka QM "varbūtiskums" un "sabrukums" ir ID-1 fona ietekmes projekcija, ko klasiskā fizika neiekļauj savā matemātiskajā aparātā.

**Galvenā atziņa (3.1):** Kanoniskā komutācijas relācija \( [\hat{x}, \hat{p}] = i\hbar \mathcal{F}(\rho_{\mathcal{V}}) \) ir stingri atvasināta no MT režģa ģeometrijas (Qn un FV). \( \mathcal{F}(\rho_{\mathcal{V}}) \) ir fokusēšanas/izkliedes funkcija no MATHEMATICS 5.2, kas ir vienāda ar 1 tikai L0 fona stāvoklī (\( \rho_{\mathcal{V}} = \rho_{\mathcal{V}}^{(0)} \)). Tādējādi QM ir **L0 robežgadījums**, nevis fundamentāla teorija.

---

## 1. SAVIENOJUMS AR MATHEMATICS FORMĀLISMU (3.1)

No MATHEMATICS_lv.md (3.0) un jaunā atvasinājuma:

| Operators / lielums | Definīcija | Kvantu mehānikas ekvivalents | ID atbilstība |
|---------------------|------------|------------------------------|---------------|
| \( \hat{x} \) | \( n \lambda_{\text{ID0}} \) (Qn slāņa rādiuss) | Pozīcijas operators | ID0.n |
| \( \hat{p} \) | \( -i \frac{\hbar}{\lambda_{\text{ID0}}} \frac{\psi(n+1)-\psi(n-1)}{2} \) | Impulsa operators (diskrētā reprezentācija) | ID0 |
| \( \mathcal{F}(\rho_{\mathcal{V}}) \) | No MATHEMATICS 5.2: \( 1 \) fokusēšanā, \( e^{-(n-n_{\text{max}})/n_{\text{izkliede}}} \) izkliedē | Kvantu režīma "ieslēgšanas" parametrs; \( \mathcal{F}=1 \) dod QM | ID0 / ID-1 |
| \( [\hat{x}, \hat{p}] \) | \( i\hbar \mathcal{F}(\rho_{\mathcal{V}}) \) | Kanoniskā komutācijas relācija | ID0 |
| \( \mathcal{P}_{L1} \) | \( \mathcal{P}_{L1}[\rho_{\mathcal{V}}] = \mathcal{F}(\rho_{\mathcal{V}}) \) un \( \delta_0(\mathbf{x}) \) | Projekcijas operators; nosaka potenciālu un fokusēšanu | ID-1 → ID0 |

**Korespondences princips:** Kad \( \rho_{\mathcal{V}} = \rho_{\mathcal{V}}^{(0)} \) (L0 fons), \( \mathcal{F} = 1 \) un MT reducējas uz QM. Kad \( \rho_{\mathcal{V}} \neq \rho_{\mathcal{V}}^{(0)} \), \( \mathcal{F} \neq 1 \) un parādās dekoherence un kvantu efektu modifikācijas.

---

## 2. VIĻŅU FUNKCIJA UN BORNA LIKUMS (3.1)

### 2.1. Viļņu funkcija

No MT:
\[
\psi(\mathbf{x}, t) = e^{i\theta(\mathbf{x}, t)} \cdot \mathcal{F}(\rho_{\mathcal{V}}(\mathbf{x}))
\]

kur:
- \( \theta(\mathbf{x}, t) \) — matricas fāze (ID0),
- \( \mathcal{F}(\rho_{\mathcal{V}}) \) — fokusēšanas/izkliedes funkcija no MATHEMATICS 5.2, kas ir \( \mathcal{P}_{L1} \) projekcijas rezultāts.

**L0 robežgadījumā** (\( \rho_{\mathcal{V}} \to \rho_{\mathcal{V}}^{(0)} \)):
\[
\mathcal{F}(\rho_{\mathcal{V}}) \to 1 \quad \Rightarrow \quad \psi(\mathbf{x}, t) \approx e^{i\theta(\mathbf{x}, t)}
\]

**Secinājums:** QM viļņu funkcija ir matricas fāzes projekcija, kas ir "ieslēgta" tikai tad, kad Vertikāle ir L0 fona stāvoklī.

### 2.2. Borna likums

No MATHEMATICS 2.2 un 5.2:
\[
|\psi(\mathbf{x}, t)|^2 = \frac{\Phi(\mathbf{x}, t)}{\phi_0} \cdot \mathcal{F}(\rho_{\mathcal{V}})
\]

kur \( \Phi \) ir TE pārneses lielums (ID0), \( \phi_0 \) — maksimālais pārneses kvants.

**L0 robežgadījumā** (\( \mathcal{F} \to 1 \)):
\[
|\psi|^2 = \frac{\Phi}{\phi_0}
\]

**Secinājums:** Borna likums nav postulāts — tas ir matricas strukturālais ierobežojums, kas izriet no diskrētās pārneses. Varbūtības blīvums ir TE pārneses blīvums L0 līmenī, mērogots ar \( \phi_0 \). \( \mathcal{F} \) modulē šo blīvumu, ja Vertikāle nav L0 stāvoklī.

---

## 3. NENOTEIKTĪBAS PRINCIPS (3.1)

### 3.1. Komutācijas relācija

No jaunā atvasinājuma (1. punkts):
\[
[\hat{x}, \hat{p}] = i\hbar \, \mathcal{F}(\rho_{\mathcal{V}})
\]

kur \( \mathcal{F} \) ir fokusēšanas/izkliedes funkcija.

**L0 robežgadījumā** (\( \mathcal{F} = 1 \)):
\[
[\hat{x}, \hat{p}] = i\hbar
\]

### 3.2. Nenoteiktības attiecība

No vispārīgās nenoteiktības attiecības:
\[
\Delta x \cdot \Delta p \geq \frac{1}{2} \left| \langle [\hat{x}, \hat{p}] \rangle \right|
= \frac{\hbar}{2} \, \mathcal{F}(\rho_{\mathcal{V}})
\]

**L0 robežgadījumā** (\( \mathcal{F} = 1 \)):
\[
\Delta x \cdot \Delta p \geq \frac{\hbar}{2}
\]

**Interpretācija:**
- Nenoteiktības princips nav fundamentāls ierobežojums — tas ir praktisks ierobežojums, ko rada nespēja izmērīt fāzi \( \theta \) kopā ar Vertikāles fonu.
- Kad \( \rho_{\mathcal{V}} \neq \rho_{\mathcal{V}}^{(0)} \), \( \mathcal{F} > 1 \) (izkliedē) vai \( \mathcal{F} < 1 \) (fokusē), nenoteiktība mainās. Augstā \( \rho_{\mathcal{V}} \) reģionos (galaktiku centros) nenoteiktība var būt lielāka.
- Precīza fāzes mērīšana (\( \Delta\theta \to 0 \)) nenozīmē \( \mathcal{F} \to 0 \) — \( \mathcal{F} \) ir neatkarīgs no \( \Delta\theta \). Tāpēc nenoteiktība neizzūd, bet to modulē Vertikāles enerģijas blīvums.

---

## 4. MĒRĪJUMA PROBLĒMA (3.1)

### 4.1. Klasiskā problēma

QM mērījums ir "sabrukums" — no vairākiem stāvokļiem tiek realizēts viens. Šis sabrukums nav izskaidrojams.

### 4.2. MT skaidrojums

Mērījums ir \( \mathcal{P}_{L1} \) projekcijas moments, kas **fiksē fāzi \( \theta \) L0 līmenī** un vienlaikus maina \( \mathcal{F} \):

1. Pirms mērījuma: \( \psi = e^{i\theta} \mathcal{F} \), kur \( \mathcal{F} \) ir noteikts.
2. Mērījuma laikā: \( \mathcal{P}_{L1} \) projicē \( \rho_{\mathcal{V}} \) uz jaunu \( \mathcal{F}' \), kas atšķiras no sākotnējā.
3. Pēc mērījuma: \( \psi' = e^{i\theta'} \mathcal{F}' \), kur \( \theta' \) ir fiksēta vērtība, un \( \mathcal{F}' \) ir jaunais fokusēšanas stāvoklis.

Tā kā \( \mathcal{P}_{L1} \) **nav unitārs** (tā ir projekcija no Vertikāles ID-1 uz H0 ID0), tas izjauc komutācijas relāciju:
\[
[\hat{x}, \hat{p}]_{\text{pēc}} = i\hbar \mathcal{F}' \neq i\hbar \mathcal{F}_{\text{pirms}}
\]

Tas ir "sabrukums" — fāze tiek fiksēta, un \( \mathcal{F} \) mainās, tādējādi mainot sistēmas turpmāko dinamiku.

**Secinājums:** Mērījuma sabrukums ir \( \mathcal{P}_{L1} \) projekcijas neunitārības sekas. Klasiskā QM neredz Vertikāli, tāpēc šķiet, ka notiek "sabrukums" no vairākiem stāvokļiem uz vienu.

---

## 5. SUPERPOZĪCIJA UN INTERFERENCE (3.1)

### 5.1. Superpozīcija

MT superpozīcija ir **L1 pārneses sadalījums pa vairākiem Qn kanāliem** uz L0 fona:
\[
\psi_{\text{tot}} = \sum_i e^{i\theta_i} \cdot \Phi_i \cdot \mathcal{F}_{n_i}(\rho_{\mathcal{V}})
\]

kur \( \Phi_i \) ir pārneses lielums pa i-to kanālu, un \( \mathcal{F}_{n_i} \) ir fokusēšanas/izkliedes funkcija, kas ir atkarīga no lokālā \( \rho_{\mathcal{V}} \).

### 5.2. Interference

Interference rodas no fāžu attiecības starp kanāliem:
\[
|\psi_{\text{tot}}|^2 = \sum_i |\psi_i|^2 + \sum_{i \neq j} 2 \Re(\psi_i \psi_j^*)
\]

kur \( \psi_i = e^{i\theta_i} \Phi_i \mathcal{F}_{n_i} \).

**Interferences izzušana** (dekoherence) notiek, kad \( \rho_{\mathcal{V}} \) lokāli pieaug, izraisot \( \mathcal{F}_{n_i} \to 0 \) un kanālu fāžu nejaušību.

---

## 6. SAPĪŠANĀS (3.1)

MT izšķir **divus sapīšanās tipus**:

### 6.1. 1. tips — caur H0 matricu (ID0)

- Savienoti caur kopīgu Qn struktūru (ID0.n).
- Izplatās ar gaismas ātrumu.
- Lineāra superpozīcija: \( \psi_{12} = \psi_1 \otimes \psi_2 \).
- \( \mathcal{F} \) ir atkarīgs no lokālā \( \rho_{\mathcal{V}} \), bet pārneses ātrums paliek \( c \).

### 6.2. 2. tips — caur TZ–Vertikāle–TZ (ID-1 / ID0)

- Savienoti caur Vertikāli (ID-1).
- Momentāni, bet **nesatur informāciju** — nav signāla pārraide.
- \( \mathcal{F} \) ir vienāds abiem objektiem, jo tie sinhronizējas ar vienu Vertikāles enerģijas notikumu.
- \( \mathcal{F} \) modulē savienojuma stiprumu: jo augstāks \( \rho_{\mathcal{V}} \), jo spēcīgāka sapīšanās 2. tips.

**Formāli:** 2. tipa sapīšanās ir \( \mathcal{F}(\Omega_1) = \mathcal{F}(\Omega_2) \) — fokusēšanas funkcija ir kopīga.

**Secinājums:** Klasiskā QM redz tikai 2. tipu un interpretē to kā "nelokālu realitāti", jo tā nezina par Vertikāli. MT redz abus tipus un saprot, ka 2. tips ir Vertikāles enerģijas kopīga sinhronizācija, nevis signāla pārraide.

---

## 7. KVANTU STATISTIKA (FERMIONI UN BOZONI) (3.1)

Kvantu statistiku MT nosaka **organizācijas struktūra**, nevis spins:

| Objekts | TZ (ID-1) | Slēgta TE pārneses cilpa (ID1) | TE bilance (ID0) | Statistika | ID atbilstība |
|---------|-----------|-------------------------------|------------------|------------|---------------|
| **Protons** | Jā | Jā | Jā | Fermions | ID1.0 / ID-1 |
| **Elektrons** | Nē | Jā | Jā | Fermions | ID1.1 / ID0 |
| **Neitrīno** | Nē | Jā (H-3 × H-4) | Jā | Fermions | ID1.1 / ID-1 |
| **Fotons** | Nē | Nē | Nav | Bozons | ID0 |

- **Fermioni** — objekti ar slēgtu TE pārneses cilpu un enerģētisko bilanci (ID1 / ID0). Tie nevar pārklāties, jo to cilpas aizņem diskrētus Qn stāvokļus.
- **Bozoni** — atvērtas, nelīdzsvarotas TE pārneses (ID0). Tās ir brīvas TE enerģijas — nav enerģētiskā bilancē, tāpēc var pārklāties bez ierobežojumiem.

**Secinājums:** Kvantu statistiku nosaka \( \mathcal{F} \) un cilpas struktūra, nevis spins. Spins ir šīs struktūras izpausme.

---

## 8. DEKOHERENCE UN KVANTU SABRUKUMS (3.1)

### 8.1. Dekoherence

Dekoherence ir \( \rho_{\mathcal{V}} \) lokālā mainība, kas izjauc fāžu sinhronizāciju:
\[
\mathcal{F}_n = e^{-(n - n_{\text{max}})/n_{\text{izkliede}}}, \quad n_{\text{izkliede}} = \frac{C}{2\pi} \cdot \frac{\rho_{\text{H0}}}{\rho_{\mathcal{V}}}
\]

Jo augstāks \( \rho_{\mathcal{V}} \), jo mazāks \( n_{\text{izkliede}} \), jo ātrāka dekoherence.

**Dekoherences laiks:**
\[
\tau_{\text{dekoherence}} = \frac{1}{\gamma} \cdot \frac{\rho_{\text{H0}}}{\rho_{\mathcal{V}}}
= \frac{1}{\gamma} \cdot \frac{1}{\mathcal{F}}
\]
kur \( \gamma = 2\pi/C \approx 0.18 \).

### 8.2. Sabrukums

Sabrukums ir \( \mathcal{P}_{L1} \) projekcija, kas fiksē fāzi, bet rada enerģijas zudumu L0 fonā. Tas maina \( \mathcal{F} \) un līdz ar to arī turpmāko dinamiku.

---

## 9. PĀRBAUDĀMĀS PROGNOZES (3.1)

| **Prognoze** | **MT vienādojums** | **Atšķirība no klasiskās QM** | **Pārbaudes metode** | **ID atbilstība** |
|--------------|-------------------|-------------------------------|----------------------|-------------------|
| Komutācijas relācija | \( [\hat{x}, \hat{p}] = i\hbar \mathcal{F} \) | \( \mathcal{F} \neq 1 \) nozīmē QM modifikāciju | Kvantu metroloģija dažādos \( \rho_{\mathcal{V}} \) reģionos | ID0 / ID-1 |
| Nenoteiktības princips | \( \Delta x \Delta p \geq \frac{\hbar}{2} \mathcal{F} \) | \( \mathcal{F} \) modulē robežu | Precīzijas mērījumi galaktiku centros | ID0 / ID-1 |
| Borna likuma korekcija | \( |\psi|^2 = \frac{\Phi}{\phi_0} \mathcal{F} \) | Varbūtības blīvums modulēts ar \( \mathcal{F} \) | Interferences eksperimenti dažādos \( \rho_{\mathcal{V}} \) reģionos | ID0 / ID-1 |
| Dekoherences laiks | \( \tau = \frac{1}{\gamma} \frac{\rho_{\text{H0}}}{\rho_{\mathcal{V}}} \) | \( \tau \) atkarīgs no \( \rho_{\mathcal{V}} \) | Kvantu metroloģija | ID0 / ID-1 |
| Sapīšanās 2. tips | \( \mathcal{F}(\Omega_1) = \mathcal{F}(\Omega_2) \) | Intensitāte atkarīga no \( \rho_{\mathcal{V}} \) | Bella testi ar laika atzīmēm | ID-1 / ID0 |

---

## 10. KOPSAVILKUMA TABULA (3.1)

| **Aspekts** | **Klasiskā QM** | **MT (3.1)** | **ID atbilstība** |
|-------------|-----------------|--------------|-------------------|
| Viļņu funkcija | Varbūtības amplitūda | \( \psi = e^{i\theta} \mathcal{F} \); \( \mathcal{F} = \mathcal{P}_{L1} \) | ID0 / ID-1 |
| Borna likums | Varbūtība | Matricas strukturāls ierobežojums; \( |\psi|^2 = \Phi/\phi_0 \cdot \mathcal{F} \) | ID0 |
| Komutācijas relācija | \( [\hat{x}, \hat{p}] = i\hbar \) | \( [\hat{x}, \hat{p}] = i\hbar \mathcal{F} \) | ID0 |
| Nenoteiktības princips | Fundamentāls | Praktisks; robeža \( \frac{\hbar}{2} \mathcal{F} \) | ID0 / ID-1 |
| Mērījuma sabrukums | Neizskaidrojams | \( \mathcal{P}_{L1} \) neunitārība; maina \( \mathcal{F} \) | ID-1 → ID0 |
| Sapīšanās | Nelokāla realitāte | Divi tipi; 2. tips atkarīgs no \( \mathcal{F} \) | ID0 / ID-1 |
| Kvantu statistika | Spins | Organizācijas struktūra (TZ, TE cilpa, bilance) | ID1 / ID0 |
| Dekoherence | Mijiedarbība ar vidi | \( \rho_{\mathcal{V}} \) lokālā mainība; \( \tau \propto 1/\rho_{\mathcal{V}} \) | ID0 / ID-1 |

---

## 11. SECINĀJUMI (3.1)

1. **Kanoniskā komutācijas relācija \( [\hat{x}, \hat{p}] = i\hbar \) ir QM robežgadījums** — tā ir spēkā tikai tad, kad Vertikāle ir L0 fona stāvoklī (\( \mathcal{F} = 1 \)). Citos gadījumos \( \mathcal{F} \neq 1 \) un QM tiek modulēta.

2. **\( \mathcal{F} = \mathcal{P}_{L1}[\rho_{\mathcal{V}}] \)** — fokusēšanas/izkliedes funkcija ir tieša Vertikāles enerģijas projekcija uz H0 matricu. Tā nosaka, cik lielā mērā diskrētais režģis atdarina nepārtraukto kvantu mehāniku.

3. **Borna likums un nenoteiktības princips nav fundamentāli** — tie ir matricas strukturālie ierobežojumi, kas izriet no diskrētās pārneses un Qn ģeometrijas. Tos modulē \( \mathcal{F} \).

4. **Mērījuma sabrukums ir \( \mathcal{P}_{L1} \) projekcijas neunitārības sekas** — projekcija maina \( \mathcal{F} \), tādējādi izjaucot komutācijas relāciju un fiksējot fāzi.

5. **Visi kvantu efekti ir atkarīgi no \( \rho_{\mathcal{V}} \)** — jo augstāks \( \rho_{\mathcal{V}} \), jo izteiktāki kvantu efekti (lielāka dekoherence, stiprāka sapīšanās 2. tips, lielāka nenoteiktība).

6. **MT nenoliedz QM derīgumu** — QM ir derīgs L1 līmeņa apraksts (ID0), taču tās "varbūtiskums" un "sabrukums" ir ID-1 fona ietekmes projekcija. MT papildina QM, nevis to aizstāj.

**Kvantitatīvais salīdzinājums ir provizorisks un paredzēts turpmākai attīstībai.** Nākamajā posmā nepieciešama sadarbība ar kvantu fiziķiem un metroloģijas speciālistiem, lai pārvērstu šos salīdzinājumus precīzās, pārbaudāmās prognozēs, īpaši ņemot vērā \( \rho_{\mathcal{V}} \) lokālās variācijas.

---

*Dokuments sagatavots: 2026. gada jūlijā*  
*Versija: 3.1 — precizēta pēc komutācijas relācijas atvasinājuma, iekļauts \( \mathcal{F} = \mathcal{P}_{L1} \), noņemts sinusa termis*
