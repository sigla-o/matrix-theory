# KVANTU MEHĀNIKA — KLASISKĀS FIZIKAS UN MT SALĪDZINĀJUMS

## Kopsavilkuma dokuments

Šis dokuments salīdzina klasiskās kvantu mehānikas un Matricas teorijas (MT) pieejas, izejot cauri klasiskajai loģiskajai secībai. Tas ir savienots ar MATHEMATICS formālismu un sniedz kvantitatīvu skatījumu uz to, kur MT un klasiskā fizika sakrīt un kur tās atšķiras.

**Galvenā atziņa:** Klasiskā fizika darbojas tikai L1 līmenī un nezina par L0 fonu. MT redz abus — L0 kā fonu un L1 kā traucējumu. Tāpēc parādības, kas klasiskajā fizikā šķiet "brīnumainas" vai "fundamentāli nenoteiktas", MT ir izskaidrojamas kā matricas strukturālas īpašības.

**Būtisks precizējums:** Kvantitatīvais salīdzinājums (9. nodaļa) ir provizorisks un paredzēts turpmākai attīstībai. Tas iezīmē virzienu, kādā MT varētu sniegt precīzākas prognozes par kvantu parādībām, taču prasa turpmāku izstrādi un eksperimentālu pārbaudi.

---

## 1. SAVIENOJUMS AR MATHEMATICS FORMĀLISMU

No MATHEMATICS_lv.md mums ir šādi operatori un lielumi, kas ir būtiski salīdzinājumam ar kvantu mehāniku:

| **Operators / lielums** | **Definīcija** | **Kvantu mehānikas ekvivalents** |
|--------------------------|----------------|----------------------------------|
| \( \theta(\mathbf{x}, t) \) | ID1 rotācijas fāze | Viļņu funkcijas fāze \( \arg(\psi) \) |
| \( \Phi(\mathbf{x},\mathbf{y}) \) | TE plūsmas lauks | Varbūtības strāva \( \mathbf{j} \) |
| \( \delta(n) \) | Kanālu deficīts | Potenciāla \( V(\mathbf{x}) \) |
| \( \rho_{\mathcal{V}}(\mathbf{x}) \) | Vertikāles enerģijas blīvums | Kvantu dekoherences avots |
| \( \mathcal{P}_{L1} \) | L1 zonas projekcijas operators | Mērījumu operators |

**Korespondences princips:** Atbilstošās robežās MT reducējas uz kvantu mehāniku:
\[
\psi(\mathbf{x}, t) \sim e^{i\theta(\mathbf{x}, t)}
\]

---

## 2. VIĻŅU–DAĻIŅU DUĀLISMS

### Klasiskā fizika
Gaisma (un matērija) uzvedas gan kā vilnis (interference, difrakcija), gan kā daļiņa (fotoelektriskais efekts, Komptona izkliede). Šis duālisms ir fundamentāls — nav iespējams reducēt vienu uz otru.

### MT skaidrojums
- **Daļiņa** = slēgta TE plūsmas cilpa.
- **Vilnis** = atvērta TE plūsmas izplatīšanās.
- Elektrons un fotons ir TE plūsmas slēgti objekti — tie ir daļa no plūsmas un ar to saplūst.
- **Protons** ir TZ slēgtais objekts — tas atrodas uz robežas starp H0 un Vertikāli, un TE plūsma no tā virsmas atstarojas, radot stāvošo vilni.

**Formāli:** Viļņu–daļiņu duālisms ir fāzes \( \theta(\mathbf{x}, t) \) un plūsmas \( \Phi(\mathbf{x},\mathbf{y}) \) savstarpējā attiecība.

---

## 3. VIĻŅU FUNKCIJA UN BORNA LIKUMS

### Klasiskā fizika
Sistēmas stāvokli apraksta viļņu funkcija \( \psi(x, t) \). \( |\psi|^2 \) ir varbūtības blīvums atrast daļiņu pozīcijā \( x \) (Borna likums).

### MT skaidrojums
- Viļņu funkcija ir **TE plūsmas sadalījuma projekcija** H0 matricā:
  \[
  \psi(\mathbf{x}, t) \sim e^{i\theta(\mathbf{x}, t)}
  \]
- \( |\psi|^2 \) nav varbūtība — tas ir **TE VEU H-2 × H-3 plūsmas blīvums** noteiktā Qn punktā:
  \[
  |\psi(\mathbf{x}, t)|^2 = \frac{\Phi(\mathbf{x}, t)}{\Phi_0}
  \]
- Borna likums ir **matricas strukturāls ierobežojums** — TE plūsma ir diskrēta, tās blīvumu var izteikt tikai kā kvadrātu (divu pus-fāžu kombinācija).

---

## 4. SUPERPOZĪCIJA UN INTERFERENCE

### Klasiskā fizika
Sistēma var atrasties vairākos stāvokļos vienlaikus — viļņu funkciju lineārā kombinācija. Interference rodas, kad šīs viļņu funkcijas saskaitās.

### MT skaidrojums
- Superpozīcija = **L1 plūsmas sadalījums pa vairākiem Qn kanāliem** uz L0 fona.
- Interference = **fāžu attiecība** starp kanāliem:
  \[
  \psi_{\text{tot}} = \sum_i e^{i\theta_i} \cdot \Phi_i
  \]
- Klasiskā fizika redz tikai L1 sadalījumu, bet neredz L0 fonu, kas to atbalsta — tāpēc superpozīcija tai šķiet "brīnumaina".

---

## 5. MĒRĪJUMA PROBLĒMA

### Klasiskā fizika
Viļņu funkcija attīstās determinēti, bet mērījuma brīdī tā "sabrūk" — no vairākiem stāvokļiem tiek realizēts viens. Šis sabrukums nav izskaidrojams.

### MT skaidrojums
- Mērījums nav "sabrukums" — tas ir **fāzes atlases moments**.
- Fāze tiek noteikta jebkuram Qn lielumam kā faktam, nevis kanāla līmenī.
- To var panākt caur mērierīces sinhronizāciju ar L0 TE plūsmu — tā ir TE plūsmu arhitektūra.
- Klasiskā fizika nezina par L0, tāpēc mērījums tai šķiet neizskaidrojams.

**Formāli:** Mērījums ir operators \( \mathcal{P}_{L1} \), kas fiksē fāzi \( \theta \) noteiktā Qn punktā.

---

## 6. NENOTEIKTĪBAS PRINCIPS

### Klasiskā fizika
\( \Delta x \cdot \Delta p \geq \hbar/2 \) — fundamentāls ierobežojums. Nevar vienlaicīgi precīzi zināt gan pozīciju, gan impulsu.

### MT skaidrojums
- Pozīcija = **Qn**.
- Impulss = **FV**.
- Qn un FV ir divas savstarpēji ortogonālas matricas koordinātas:
  \[
  [\text{Qn}, \text{FV}] \neq 0
  \]
- Zinot fāzi \( \theta \), MT var noteikt gan pozīciju, gan impulsu vienlaicīgi.
- Nenoteiktība nav fundamentāla — tā ir mērījumu aparatūras nepietiekamības sekas.

**Kvantitatīvi:** Ja \( \theta \) ir zināms ar precizitāti \( \Delta \theta \), tad:
\[
\Delta x \cdot \Delta p \approx \frac{\hbar}{2} \cdot \frac{1}{\sin(\Delta \theta)}
\]
— pie \( \Delta \theta \to 0 \), nenoteiktība izzūd.

---

## 7. SAPĪŠANĀS

### Klasiskā fizika
Divas daļiņas var būt sapītās — to stāvokļi ir korelēti neatkarīgi no attāluma. Bella nevienādību pārkāpums pierāda, ka realitāte ir nelokāla.

### MT skaidrojums
MT izšķir **divus sapīšanās tipus**:

1. **Caur matricu (H0)** — savienoti caur kopīgu Qn struktūru. Izplatās ar gaismas ātrumu.
   \[
   \text{Sapīšanās 1. tips: } \Phi_1(\mathbf{x}) = \Phi_2(\mathbf{y}) \text{ caur } Q_n
   \]

2. **Caur TZ–Vertikāle–TZ** — savienoti caur Vertikāli. Momentāni, bet nav signāla pārraide — tas ir **impulsa pārnese**.
   \[
   \text{Sapīšanās 2. tips: } \mathcal{T}(\Omega_1) = \mathcal{T}(\Omega_2) \text{ caur } \mathcal{V}
   \]

Klasiskā fizika redz tikai 2. tipu un interpretē to kā "nelokālu realitāti", jo tā nezina par Vertikāli.

---

## 8. KVANTU STATISTIKA (FERMIONI UN BOZONI)

### Klasiskā fizika
Fermioni — Pauli izslēgšanas princips. Bozoni — bez ierobežojumiem. Atšķirību nosaka spins.

### MT skaidrojums

| **Objekts** | **TZ** | **Slēgta TE cilpa** | **TE bilance** | **Statistika** |
|-------------|--------|----------------------|----------------|----------------|
| **Protons** | Jā | Jā | Jā | Fermions |
| **Elektrons** | Nē | Jā | Jā | Fermions |
| **Neitrīno** | Nē | Jā (H-3 × H-4) | Jā | Fermions |
| **Fotons** | Nē | Nē | Nav | Bozons |

- Protons — TZ slēgtais objekts. Pilnīgi noslēgts — nekas nevar iekļūt bez pilnīgas sinhronizācijas.
- Elektrons — slēgts divu TE veidojums, bez TZ. Tajā var nokļūt cita enerģija, bet tikai caur pilnu sinhronizāciju.
- Fotons — atvērtas, nelīdzsvarotas TE plūsmas. Tās ir brīvas TE enerģijas — nav enerģētiskā bilancē, tāpēc var pārklāties bez ierobežojumiem.
- Neitrīno — līdzīgs elektronam, bet smalkāks VEU sastāvs. Fermions.

**Secinājums:** Kvantu statistiku nosaka organizācijas struktūra (TZ piesaiste, TE cilpa, bilance), nevis spins.

---

## 9. PĀRBAUDĀMĀS PROGNOZES — KUR MT ATŠĶIRAS NO KLASISKĀS QM

| **Prognoze** | **MT vienādojums** | **Atšķirība no klasiskās QM** | **Pārbaudes metode** |
|--------------|-------------------|-------------------------------|----------------------|
| Determinisms pie fāzes mērīšanas | \( \Delta x \cdot \Delta p = \hbar/2 \cdot 1/\sin(\Delta\theta) \) | Nenoteiktība izzūd pie \( \Delta\theta \to 0 \) | Fāzes mērīšanas eksperimenti |
| Sapīšanās 2. tips | \( \mathcal{T}(\Omega_1) = \mathcal{T}(\Omega_2) \) | Momentāna, bet bez signāla pārraides | Bella nevienādību testi ar laika atzīmēm |
| Viļņu funkcija kā TE plūsma | \( \psi(\mathbf{x}, t) \sim e^{i\theta(\mathbf{x}, t)} \) | Nav varbūtības — tā ir plūsma | Interferences eksperimenti |
| Kvantu statistika no struktūras | Fermioni = TZ slēgti; Bozoni = atvērti | Spins nav fundamentāls | Daļiņu fizikas eksperimenti |

---

## 10. KOPSAVILKUMS — SALĪDZINĀJUMA TABULA

| **Aspekts** | **Klasiskā fizika** | **MT** |
|-------------|----------------------|--------|
| **Viļņu–daļiņu duālisms** | Fundamentāls | TE plūsmas slēgta/atvērta forma |
| **Viļņu funkcija** | Varbūtības amplitūda | TE plūsmas projekcija \( e^{i\theta} \) |
| **Borna likums** | Varbūtība | Matricas strukturāls ierobežojums |
| **Superpozīcija** | Stāvokļu vienlaicīga esamība | L1 plūsmas sadalījums pa kanāliem |
| **Mērījuma problēma** | Neizskaidrojams sabrukums | Fāzes atlases moments — \( \mathcal{P}_{L1} \) |
| **Nenoteiktības princips** | Fundamentāls | Praktisks — atkarīgs no \( \Delta\theta \) |
| **Sapīšanās** | Nelokāla realitāte | Divi tipi — caur matricu un caur Vertikāli |
| **Kvantu statistika** | Spins (fermions/bozons) | Organizācijas struktūra (TZ, TE cilpa, bilance) |

---

## 11. SECINĀJUMI

Klasiskā fizika nezina par L0 fonu un TZ — tā darbojas tikai L1 līmenī. Tāpēc tā saskata "kvantu brīnumus": superpozīciju, sabrukumu, nelokālu sapīšanos, fundamentālu nenoteiktību.

MT redz L0 un L1 — tāpēc šīs parādības kļūst izskaidrojamas kā matricas strukturālas īpašības. MT nenodrošina fāzes mērīšanas instrumentu, bet tā norāda, ka fāze ir mērāma un ka tās izmērīšana atjaunotu determinismu.

**Galvenā atziņa:** Kvantu mehānika nav fundamentāli varbūtiska — tā ir **L1 līmeņa statistika**, ko rada nespēja sasniegt L0 līmeni. MT piedāvā virzienu, nevis risinājumu.

**Kvantitatīvais salīdzinājums ir provizorisks un paredzēts turpmākai attīstībai.** Nākamajā posmā nepieciešama sadarbība ar kvantu fiziķiem un metroloģijas speciālistiem, lai pārvērstu šos salīdzinājumus precīzās, pārbaudāmās prognozēs.

---

## PIEZĪME

Šis dokuments ir **salīdzinājums starp klasisko kvantu mehāniku un MT** ar provizoriskiem kvantitatīviem aspektiem. Tas nav QED pamats, nevis kosmoloģija, nevis tehnoloģija — tas ir patstāvīgs dokuments, kas nofiksē, kur MT un klasiskā fizika sakrīt un kur tās atšķiras.

---

*Dokuments sagatavots: 2026. gada jūlijā*
