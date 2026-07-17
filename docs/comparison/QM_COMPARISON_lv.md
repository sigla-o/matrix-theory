# QM_COMPARISON_lv.md (v3.0)

# KVANTU MEHĀNIKA — SALĪDZINĀJUMS AR MT

## Pārstrādātā versija (2026. gada jūlijs) — v3.0

Šis dokuments salīdzina klasisko kvantu mehāniku un MT pieejas, izejot cauri klasiskajai loģiskajai secībai. Tas ir savienots ar MATHEMATICS formālisma v3.0 versiju un ID sistēmu, sniedzot kvantitatīvu skatījumu uz to, kur MT un klasiskā fizika sakrīt un kur tās atšķiras.

**Galvenā atziņa:** Klasiskā fizika darbojas tikai L1 līmenī (ID0) un nezina par L0 fonu (ID-1). MT redz abus — L0 kā fonu un L1 kā pārneses traucējumu. Tāpēc parādības, kas klasiskajā fizikā šķiet "brīnumainas" vai "fundamentāli nenoteiktas", MT ir izskaidrojamas kā matricas strukturālas īpašības (ID0 / ID-1). **MT neaizstāj kvantu mehāniku — tā sniedz mehānisko izcelsmi tās fenomenoloģiskajiem likumiem.**

---

## 1. SAVIENOJUMS AR MATHEMATICS FORMĀLISMU UN ID SISTĒMU

No MATHEMATICS_lv.md v3.0 un ID_GRADIENT_lv.md v3.0 mums ir šādi operatori, lielumi un ID līmeņi, kas ir būtiski salīdzinājumam ar kvantu mehāniku:

| Operators / lielums | Definīcija | Kvantu mehānikas ekvivalents | ID atbilstība |
|---------------------|------------|------------------------------|---------------|
| \( \theta(\mathbf{x}, t) \) | ID1 rotācijas fāze | Viļņu funkcijas fāze \( \arg(\psi) \) | ID0 |
| \( \Phi(\mathbf{x},\mathbf{y};t) \) | TE pārneses lielums starp kabatām | Varbūtības strāva \( \mathbf{j} \) (pārneses blīvums) | ID0 |
| \( \delta(n) \) | Kanālu deficīts | Potenciāla \( V(\mathbf{x}) \) | ID0.n |
| \( \rho_{\mathcal{V}}(\mathbf{x}) \) | Vertikāles enerģijas blīvums | Kvantu dekoherences avots | ID-1 |
| \( \mathcal{P}_{L1} \) | L1 zonas projekcijas operators | Mērījumu operators | ID0 / ID-1 |
| \( \phi_0 \) | \( \hbar c/l_P \) | Maksimālais pārneses kvants | ID0 |
| \( C \) | \( \ell_k/n_k \approx 35.325 \) | Cikliskuma konstante | ID0.n |
| \( \gamma \) | \( 2\pi/C \approx 0.18 \) | Cikliskuma inversais mērogs | ID0 |

**Korespondences princips:** Atbilstošās robežās MT reducējas uz kvantu mehāniku (ID0 / ID1):
$$
\psi(\mathbf{x}, t) \sim e^{i\theta(\mathbf{x}, t)}
$$
kur \( \theta \) ir kabatas rotācijas fāze (ID0).

---

## 2. VIĻŅU–DAĻIŅU DUĀLISMS (ID0 / ID1)

### Klasiskā fizika
Gaisma (un matērija) uzvedas gan kā vilnis (interference, difrakcija), gan kā daļiņa (fotoelektriskais efekts, Komptona izkliede). Šis duālisms ir fundamentāls — nav iespējams reducēt vienu uz otru.

### MT skaidrojums (ID0 / ID1)
- **Daļiņa** = slēgta TE pārneses cilpa (ID1.0 — protons, ID1.1 — elektrons).
- **Vilnis** = atvērta TE pārneses izplatīšanās (ID0).
- Elektrons un fotons ir TE pārneses slēgti objekti (ID1) — tie ir daļa no pārneses un ar to saplūst (ID0).
- **Protons** (ID1.0) ir TZ slēgtais objekts — tas atrodas uz robežas starp H0 un Vertikāli (ID0 / ID-1), un TE pārnese no tā virsmas atstarojas, radot stāvošo vilni (ID0).

**Formāli:** Viļņu–daļiņu duālisms ir fāzes \( \theta(\mathbf{x}, t) \) (ID0) un pārneses lieluma \( \Phi(\mathbf{x},\mathbf{y};t) \) (ID0) savstarpējā attiecība.

---

## 3. VIĻŅU FUNKCIJA UN BORNA LIKUMS (ID0 / ID1)

### Klasiskā fizika
Sistēmas stāvokli apraksta viļņu funkcija \( \psi(x, t) \). \( |\psi|^2 \) ir varbūtības blīvums atrast daļiņu pozīcijā \( x \) (Borna likums).

### MT skaidrojums (ID0 / ID1)
- Viļņu funkcija ir **TE pārneses sadalījuma projekcija** H0 matricā (ID0):
  $$
  \psi(\mathbf{x}, t) \sim e^{i\theta(\mathbf{x}, t)} \quad \text{(ID0)}
  $$
- \( |\psi|^2 \) nav varbūtība — tas ir **TE pārneses blīvums** (ID-1 / ID0) noteiktā Qn punktā (ID0.n):
  $$
  |\psi(\mathbf{x}, t)|^2 = \frac{\Phi(\mathbf{x}, t)}{\phi_0} \quad \text{(ID0)}
  $$
  kur \( \phi_0 \) ir maksimālais pārneses kvants.
- Borna likums ir **matricas strukturāls ierobežojums** (ID0) — TE pārnese ir diskrēta (kabatu pārnese pa soļiem), tās blīvumu var izteikt tikai kā kvadrātu (divu pus-fāžu kombinācija).

---

## 4. SUPERPOZĪCIJA UN INTERFERENCE (ID0)

### Klasiskā fizika
Sistēma var atrasties vairākos stāvokļos vienlaikus — viļņu funkciju lineārā kombinācija. Interference rodas, kad šīs viļņu funkcijas saskaitās.

### MT skaidrojums (ID0)
- Superpozīcija = **L1 pārneses sadalījums pa vairākiem Qn kanāliem** uz L0 fona (ID0 / ID-1).
- Interference = **fāžu attiecība** starp kanāliem (ID0):
  $$
  \psi_{\text{tot}} = \sum_i e^{i\theta_i} \cdot \Phi_i \quad \text{(ID0)}
  $$
  kur \( \Phi_i \) ir pārneses lielums pa i-to kanālu.
- Klasiskā fizika redz tikai L1 sadalījumu (ID0), bet neredz L0 fonu, kas to atbalsta (ID-1) — tāpēc superpozīcija tai šķiet "brīnumaina".

---

## 5. MĒRĪJUMA PROBLĒMA (ID0 / ID-1)

### Klasiskā fizika
Viļņu funkcija attīstās determinēti, bet mērījuma brīdī tā "sabrūk" — no vairākiem stāvokļiem tiek realizēts viens. Šis sabrukums nav izskaidrojams.

### MT skaidrojums (ID0 / ID-1)
- Mērījums nav "sabrukums" — tas ir **fāzes atlases moments** (ID0).
- Fāze tiek noteikta jebkuram Qn lielumam (ID0.n) kā faktam, nevis kanāla līmenī.
- To var panākt caur mērierīces sinhronizāciju ar L0 TE pārnesi (ID-1) — tā ir TE pārneses arhitektūra (ID0 / ID-1).
- Klasiskā fizika nezina par L0 (ID-1), tāpēc mērījums tai šķiet neizskaidrojams.

**Formāli:** Mērījums ir operators \( \mathcal{P}_{L1} \) (ID0), kas fiksē fāzi \( \theta \) noteiktā Qn punktā (ID0.n).

---

## 6. NENOTEIKTĪBAS PRINCIPS (ID0 / ID-1)

### Klasiskā fizika
\( \Delta x \cdot \Delta p \geq \hbar/2 \) — fundamentāls ierobežojums. Nevar vienlaicīgi precīzi zināt gan pozīciju, gan impulsu.

### MT skaidrojums (ID0 / ID-1)
- Pozīcija = **Qn** (ID0.n).
- Impulss = **FV** (ID0).
- Qn un FV ir divas savstarpēji ortogonālas matricas koordinātas (ID0):
  $$
  [\text{Qn}, \text{FV}] \neq 0 \quad \text{(ID0)}
  $$
- Zinot fāzi \( \theta \) (ID0), MT var noteikt gan pozīciju, gan impulsu vienlaicīgi — fāze ir kopējais stāvoklis, kas apvieno abas koordinātas.
- Nenoteiktība nav fundamentāla — tā ir mērījumu aparatūras nepietiekamības sekas (ID0), jo mērījums \( \mathcal{P}_{L1} \) projicē tikai vienu komponenti.

**Kvantitatīvi:** Ja \( \theta \) ir zināms ar precizitāti \( \Delta \theta \) (ID0):
$$
\Delta x \cdot \Delta p \approx \frac{\hbar}{2} \cdot \frac{1}{\sin(\Delta \theta)} \quad \text{(ID0 / ID1)}
$$
— pie \( \Delta \theta \to 0 \), nenoteiktība izzūd (ideālā fāzes mērīšanā).

---

## 7. SAPĪŠANĀS (ID0 / ID-1)

### Klasiskā fizika
Divas daļiņas var būt sapītās — to stāvokļi ir korelēti neatkarīgi no attāluma. Bella nevienādību pārkāpums pierāda, ka realitāte ir nelokāla.

### MT skaidrojums (ID0 / ID-1)
MT izšķir **divus sapīšanās tipus**:

1. **Caur matricu (H0)** (ID0) — savienoti caur kopīgu Qn struktūru (ID0.n). Izplatās ar gaismas ātrumu.
   $$
   \text{Sapīšanās 1. tips: } \Phi_1(\mathbf{x}) = \Phi_2(\mathbf{y}) \text{ caur } Q_n \quad \text{(ID0.n)}
   $$

2. **Caur TZ–Vertikāle–TZ** (ID-1 / ID0) — savienoti caur Vertikāli (ID-1). Momentāni, bet nav signāla pārraide — tas ir **impulsa pārnese** (ID-1), kur abi objekti sinhronizējas ar vienu Vertikāles enerģijas notikumu.
   $$
   \text{Sapīšanās 2. tips: } \mathcal{T}(\Omega_1) = \mathcal{T}(\Omega_2) \text{ caur } \mathcal{V} \quad \text{(ID-1 / ID0)}
   $$
   — cikliskuma mērogs \( \gamma = 2\pi/C \) nosaka šīs sinhronizācijas ātrumu.

Klasiskā fizika redz tikai 2. tipu (ID-1) un interpretē to kā "nelokālu realitāti", jo tā nezina par Vertikāli (ID-1).

---

## 8. KVANTU STATISTIKA (FERMIONI UN BOZONI) (ID1 / ID0)

### Klasiskā fizika
Fermioni — Pauli izslēgšanas princips. Bozoni — bez ierobežojumiem. Atšķirību nosaka spins.

### MT skaidrojums (ID1 / ID0)

| Objekts | TZ (ID-1) | Slēgta TE pārneses cilpa (ID1) | TE bilance (ID0) | Statistika | ID atbilstība |
|---------|-----------|-------------------------------|------------------|------------|---------------|
| **Protons** | Jā | Jā | Jā | Fermions | ID1.0 / ID-1 |
| **Elektrons** | Nē | Jā | Jā | Fermions | ID1.1 / ID0 |
| **Neitrīno** | Nē | Jā (H-3 × H-4) | Jā | Fermions | ID1.1 / ID-1 |
| **Fotons** | Nē | Nē | Nav | Bozons | ID0 |

- Protons (ID1.0) — TZ slēgtais objekts (ID-1). Pilnīgi noslēgts — nekas nevar iekļūt bez pilnīgas sinhronizācijas (ID-1 / ID0).
- Elektrons (ID1.1) — slēgts divu TE veidojums, bez TZ (ID0). Tajā var nokļūt cita enerģija, bet tikai caur pilnu sinhronizāciju (ID0).
- Fotons (ID0) — atvērtas, nelīdzsvarotas TE pārneses (ID0). Tās ir brīvas TE enerģijas — nav enerģētiskā bilancē (ID0), tāpēc var pārklāties bez ierobežojumiem.
- Neitrīno (ID1.1) — līdzīgs elektronam, bet smalkāks VEU sastāvs (ID-1 / ID1.1). Fermions.

**Secinājums:** Kvantu statistiku nosaka organizācijas struktūra (TZ piesaiste ID-1, TE pārneses cilpa ID1, bilance ID0), nevis spins.

---

## 9. PĀRBAUDĀMĀS PROGNOZES — KUR MT ATŠĶIRAS NO KLASISKĀS QM (ID0 / ID-1 / ID1)

| **Prognoze** | **MT vienādojums** | **Atšķirība no klasiskās QM** | **Pārbaudes metode** | **ID atbilstība** |
|--------------|-------------------|-------------------------------|----------------------|-------------------|
| Determinisms pie fāzes mērīšanas | \( \Delta x \cdot \Delta p = \hbar/2 \cdot 1/\sin(\Delta\theta) \) | Nenoteiktība izzūd pie \( \Delta\theta \to 0 \) | Fāzes mērīšanas eksperimenti | ID0 / ID1 |
| Sapīšanās 2. tips | \( \mathcal{T}(\Omega_1) = \mathcal{T}(\Omega_2) \) caur \( \mathcal{V} \) | Momentāna, bet bez signāla pārraides | Bella nevienādību testi ar laika atzīmēm | ID-1 / ID0 |
| Viļņu funkcija kā TE pārneses projekcija | \( \psi(\mathbf{x}, t) \sim e^{i\theta(\mathbf{x}, t)} \) | Nav varbūtības — tā ir pārneses blīvuma projekcija | Interferences eksperimenti | ID0 |
| Kvantu statistika no struktūras | Fermioni = TZ slēgti (ID-1); Bozoni = atvērti (ID0) | Spins nav fundamentāls | Daļiņu fizikas eksperimenti | ID1 / ID0 |

---

## 10. KOPSAVILKUMS — SALĪDZINĀJUMA TABULA (ID0 / ID-1 / ID1 — ID4)

| **Aspekts** | **Klasiskā fizika** | **MT** | **ID atbilstība** |
|-------------|----------------------|--------|-------------------|
| **Viļņu–daļiņu duālisms** | Fundamentāls | TE pārneses slēgta/atvērta forma | ID0 / ID1 |
| **Viļņu funkcija** | Varbūtības amplitūda | TE pārneses projekcija \( e^{i\theta} \) | ID0 |
| **Borna likums** | Varbūtība | Matricas strukturāls ierobežojums | ID0 |
| **Superpozīcija** | Stāvokļu vienlaicīga esamība | L1 pārneses sadalījums pa kanāliem | ID0 |
| **Mērījuma problēma** | Neizskaidrojams sabrukums | Fāzes atlases moments — \( \mathcal{P}_{L1} \) | ID0 / ID-1 |
| **Nenoteiktības princips** | Fundamentāls | Praktisks — atkarīgs no \( \Delta\theta \) | ID0 |
| **Sapīšanās** | Nelokāla realitāte | Divi tipi — caur matricu (ID0) un caur Vertikāli (ID-1) | ID0 / ID-1 |
| **Kvantu statistika** | Spins (fermions/bozons) | Organizācijas struktūra (TZ, TE pārneses cilpa, bilance) | ID1 / ID0 |

---

## 11. SECINĀJUMI (ID0 / ID-1)

Klasiskā fizika nezina par L0 fonu (ID-1) un TZ (ID0 / ID-1) — tā darbojas tikai L1 līmenī (ID0). Tāpēc tā saskata "kvantu brīnumus": superpozīciju, sabrukumu, nelokālu sapīšanos, fundamentālu nenoteiktību.

MT redz L0 (ID-1) un L1 (ID0) — tāpēc šīs parādības kļūst izskaidrojamas kā matricas strukturālas īpašības (ID0 / ID-1). MT nenodrošina fāzes mērīšanas instrumentu (ID0), bet tā norāda, ka fāze ir mērāma un ka tās izmērīšana atjaunotu determinismu.

**Metodoloģiskais precizējums:** MT nenoliedz kvantu mehānikas derīgumu kā prognozēšanas rīku (ID0). Tā norāda, ka QM ir derīgs L1 līmeņa apraksts, taču tās "varbūtiskums" un "sabrukums" ir ID-1 fona ietekmes projekcija, ko klasiskā fizika vienkārši neiekļauj savā matemātiskajā aparātā. QM paliek spēkā savā darbības laukā — MT to papildina, nevis aizstāj.

**Galvenā atziņa:** Kvantu mehānika nav fundamentāli varbūtiska — tā ir **L1 līmeņa statistika** (ID0), ko rada nespēja sasniegt L0 līmeni (ID-1). MT piedāvā virzienu, nevis risinājumu.

**Kvantitatīvais salīdzinājums ir provizorisks un paredzēts turpmākai attīstībai.** Nākamajā posmā nepieciešama sadarbība ar kvantu fiziķiem un metroloģijas speciālistiem, lai pārvērstu šos salīdzinājumus precīzās, pārbaudāmās prognozēs.

---

*Dokuments sagatavots: 2026. gada jūlijā*  
*Versija: 3.0 — saskaņots ar MATHEMATICS v3.0, iekļauta metodoloģiskā piezīme un cikliskuma atsauces*
