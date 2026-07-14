# KVANTU MEHĀNIKA — KLASISKĀS FIZIKAS UN MT SALĪDZINĀJUMS

## Kopsavilkuma dokuments

Šis dokuments salīdzina klasiskās kvantu mehānikas un Matricas teorijas (MT) pieejas, izejot cauri klasiskajai loģiskajai secībai. Tas ir patstāvīgs salīdzinājums, kas nofiksē, kur MT un klasiskā fizika sakrīt un kur tās atšķiras.

**Galvenā atziņa:** Klasiskā fizika darbojas tikai L1 līmenī un nezina par L0 fonu. MT redz abus — L0 kā fonu un L1 kā traucējumu. Tāpēc parādības, kas klasiskajā fizikā šķiet "brīnumainas" vai "fundamentāli nenoteiktas", MT ir izskaidrojamas kā matricas strukturālas īpašības.

---

## 1. solis: Viļņu–daļiņu duālisms

### Klasiskā fizika
Gaisma (un matērija) uzvedas gan kā vilnis (interference, difrakcija), gan kā daļiņa (fotoelektriskais efekts, Komptona izkliede). Šis duālisms ir fundamentāls — nav iespējams reducēt vienu uz otru.

### MT skaidrojums
- **Daļiņa** = slēgta TE plūsmas cilpa.
- **Vilnis** = atvērta TE plūsmas izplatīšanās.
- Elektrons un fotons ir TE plūsmas slēgti objekti — tie ir daļa no plūsmas un ar to saplūst.
- **Protons** ir TZ slēgtais objekts — tas atrodas uz robežas starp H0 un Vertikāli, un TE plūsma no tā virsmas atstarojas, radot stāvošo vilni.
- Klasiskā fizika redz duālismu, jo tā neredz TE plūsmas nepārtrauktību.

---

## 2. solis: Viļņu funkcija un Borna likums

### Klasiskā fizika
Sistēmas stāvokli apraksta viļņu funkcija \( \psi(x, t) \). \( |\psi|^2 \) ir varbūtības blīvums atrast daļiņu pozīcijā \( x \) (Borna likums).

### MT skaidrojums
- Viļņu funkcija ir **TE plūsmas sadalījuma projekcija** H0 matricā.
- \( |\psi|^2 \) nav varbūtība — tas ir **TE VEU H-2 × H-3 plūsmas blīvums** noteiktā Qn punktā.
- Borna likums ir **matricas strukturāls ierobežojums** — TE plūsma ir diskrēta, tās blīvumu var izteikt tikai kā kvadrātu (divu pus-fāžu kombinācija).

---

## 3. solis: Superpozīcija un interference

### Klasiskā fizika
Sistēma var atrasties vairākos stāvokļos vienlaikus — viļņu funkciju lineārā kombinācija. Interference rodas, kad šīs viļņu funkcijas saskaitās.

### MT skaidrojums
- Superpozīcija = **L1 plūsmas sadalījums pa vairākiem Qn kanāliem** uz L0 fona.
- Interference = **fāžu attiecība** starp kanāliem.
- Klasiskā fizika redz tikai L1 sadalījumu, bet neredz L0 fonu, kas to atbalsta — tāpēc superpozīcija tai šķiet "brīnumaina".

---

## 4. solis: Mērījuma problēma

### Klasiskā fizika
Viļņu funkcija attīstās determinēti, bet mērījuma brīdī tā "sabrūk" — no vairākiem stāvokļiem tiek realizēts viens. Šis sabrukums nav izskaidrojams.

### MT skaidrojums
- Mērījums nav "sabrukums" — tas ir **fāzes atlases moments**.
- Fāze tiek noteikta jebkuram Qn lielumam kā faktam, nevis kanāla līmenī.
- To var panākt caur mērierīces sinhronizāciju ar L0 TE plūsmu — tā ir TE plūsmu arhitektūra.
- Klasiskā fizika nezina par L0, tāpēc mērījums tai šķiet neizskaidrojams.

---

## 5. solis: Nenoteiktības princips

### Klasiskā fizika
\( \Delta x \cdot \Delta p \geq \hbar/2 \) — fundamentāls ierobežojums. Nevar vienlaicīgi precīzi zināt gan pozīciju, gan impulsu.

### MT skaidrojums
- Pozīcija = **Qn**.
- Impulss = **FV**.
- Qn un FV ir divas savstarpēji ortogonālas matricas koordinātas.
- Zinot fāzi (ID1 rotācijas leņķi \( \theta \)), MT var noteikt gan pozīciju, gan impulsu vienlaicīgi.
- Nenoteiktība nav fundamentāla — tā ir mērījumu aparatūras nepietiekamības sekas.

---

## 6. solis: Sapīšanās

### Klasiskā fizika
Divas daļiņas var būt sapītās — to stāvokļi ir korelēti neatkarīgi no attāluma. Bella nevienādību pārkāpums pierāda, ka realitāte ir nelokāla.

### MT skaidrojums
MT izšķir **divus sapīšanās tipus**:
1. **Caur matricu (H0)** — savienoti caur kopīgu Qn struktūru. Izplatās ar gaismas ātrumu.
2. **Caur TZ–Vertikāle–TZ** — savienoti caur Vertikāli. Momentāni, bet nav signāla pārraide — tas ir **impulsa pārnese**.
- Klasiskā fizika redz tikai 2. tipu un interpretē to kā "nelokālu realitāti", jo tā nezina par Vertikāli.

---

## 7. solis: Kvantu lauka teorija (QFT)

### Klasiskā fizika
Lauks ir fundamentāls — daļiņas ir tā ierosinājumi. Lauki tiek kvantēti. Virtuālās daļiņas un renormalizācija ir nepieciešami, lai noņemtu bezgalības.

### MT skaidrojums
- **Lauks nav kvantēts — tas ir diskrēts.** Qn režģis ir minimālais solis, tāpēc bezgalības neparādās.
- **Daļiņas nav "radītas" — tās ir L1 plūsmas pārkārtošanās.**
- **Virtuālās daļiņas** ir īslaicīgas L1 plūsmas novirzes.
- **Renormalizācija nav nepieciešama** — bezgalības rodas no nepārtraukta lauka pieņēmuma.
- Jebkurš L1 lauks atrodas L0 telpā — notikumi vienmēr ir aprēķināmi.

---

## 8. solis: Kvantu statistika (fermioni un bozoni)

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
- Elektrons — slēgts divu TE veidojums, bez TZ. Tajā var nokļūt cita enerģija, bet tikai caur pilnu sinhronizāciju. Bez sinhronizācijas enerģijas tiek atstumtas.
- Fotons — atvērtas, nelīdzsvarotas TE plūsmas. Tās ir brīvas TE enerģijas — nav enerģētiskā bilancē, tāpēc var pārklāties bez ierobežojumiem.
- Neitrīno — līdzīgs elektronam, bet smalkāks VEU sastāvs. Fermions.

**Secinājums:** Kvantu statistiku nosaka organizācijas struktūra (TZ piesaiste, TE cilpa, bilance), nevis spins.

---

## Kopsavilkums — salīdzinājuma tabula

| **Aspekts** | **Klasiskā fizika** | **MT** |
|-------------|----------------------|--------|
| **Viļņu–daļiņu duālisms** | Fundamentāls | TE plūsmas slēgta/atvērta forma |
| **Viļņu funkcija** | Varbūtības amplitūda | TE plūsmas projekcija |
| **Borna likums** | Varbūtība | Matricas strukturāls ierobežojums |
| **Superpozīcija** | Stāvokļu vienlaicīga esamība | L1 plūsmas sadalījums pa kanāliem uz L0 fona |
| **Mērījuma problēma** | Neizskaidrojams sabrukums | Fāzes atlases moments — sinhronizācija ar L0 |
| **Nenoteiktības princips** | Fundamentāls | Praktisks — atkarīgs no fāzes mērīšanas |
| **Sapīšanās** | Nelokāla realitāte | Divi tipi — caur matricu un caur Vertikāli |
| **Kvantu lauka teorija** | Kvantēts, nepārtraukts lauks | Diskrēts Qn režģis, bez bezgalībām |
| **Kvantu statistika** | Spins (fermions/bozons) | Organizācijas struktūra (TZ, TE cilpa, bilance) |

---

## Secinājums

Klasiskā fizika nezina par L0 fonu un TZ — tā darbojas tikai L1 līmenī. Tāpēc tā saskata "kvantu brīnumus": superpozīciju, sabrukumu, nelokālu sapīšanos, fundamentālu nenoteiktību.

MT redz L0 un L1 — tāpēc šīs parādības kļūst izskaidrojamas kā matricas strukturālas īpašības. MT nenodrošina fāzes mērīšanas instrumentu, bet tā norāda, ka fāze ir mērāma un ka tās izmērīšana atjaunotu determinismu.

**Galvenā atziņa:** Kvantu mehānika nav fundamentāli varbūtiska — tā ir **L1 līmeņa statistika**, ko rada nespēja sasniegt L0 līmeni. MT piedāvā virzienu, nevis risinājumu.

---

## PIEZĪME

Šis dokuments ir **salīdzinājums starp klasisko kvantu mehāniku un MT**. Tas nav QED pamats, nevis kosmoloģija, nevis tehnoloģija — tas ir patstāvīgs dokuments, kas nofiksē, kur MT un klasiskā fizika sakrīt un kur tās atšķiras.

---

*Dokuments sagatavots: 2026. gada jūlijā*
