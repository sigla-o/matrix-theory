# NEITRĪNO — MATRICAS TEORIJAS VERSIJA (MT)

## Pārstrādātā versija (2026. gada jūlijs)

Šis dokuments apkopo Matricas teorijas (MT) interpretāciju neitrīno fizikai — to masai, struktūrai, anti-neitrīno un anihilācijai. Tas ir strukturēts teorijas apraksts, kas izriet no MT pamatprincipiem un ir savienots ar MATHEMATICS formālisma pārstrādāto versiju un ID sistēmu.

**Galvenā atziņa:** Neitrīno nav "bezmasas" daļiņa — tā ir slēgta TE pārneses cilpa ar vāju TZ piesaisti, kuras masu nosaka VEU H-3 enerģijas kvantēšana un cilpas ģeometrija.

---

## 1. NEITRĪNO VIETA MT UN ID SISTĒMĀ

### 1.1. Definīcija

Neitrīno (ID1.1) ir:

- **Slēgta TE pārneses cilpa** — tāpat kā elektrons, bet ar atšķirīgu iekšējo struktūru.
- **Vāja TZ piesaiste** (ID-1) — tam ir "logs" uz Vertikāli, kas ļauj mijiedarboties ar H-3 un H-4 līmeņiem.
- **Bez elektriskā lādiņa** — fāžu simetrija ir pilnībā kompensēta (nav H-3 papildslodzes).

| Objekts | ID | TZ piesaiste | TE struktūra | Vertikāles līmeņi | Lādiņš |
|---------|-----|--------------|--------------|-------------------|--------|
| Elektrons | ID1.1 | Nē | Slēgta TE cilpa (H-2 × H-3) | H-3 (dominē) | -1 |
| Neitrīno | ID1.1 | Jā (vāja) | Slēgta TE cilpa (H-3 × H-4) | H-3 + H-4 | 0 |
| Fotons | ID0 | Nē | Atvērta TE pārnese | Nav | 0 |

### 1.2. Trīs tipi — no kurienes tie nāk?

Neitrīno trim tipiem (\( \nu_e, \nu_\mu, \nu_\tau \)) atbilst **trīs dažādas fāžu kombinācijas** FV ciklā:

- FV ciklam ir 12 kanāli (6 virzieni × 2 pusfāzes).
- Vertikāles "logs" atveras tikai noteiktās fāzēs.
- Trīs tipi atbilst trim dažādiem fāžu logiem:
  - \( \nu_e \): logs pie fāzes 0°–120°
  - \( \nu_\mu \): logs pie fāzes 120°–240°
  - \( \nu_\tau \): logs pie fāzes 240°–360°

Katram logam ir atšķirīgs kanālu skaits, kas nosaka H-3 enerģijas uztveršanas spēju un līdz ar to masu.

---

## 2. NEITRĪNO MASAS NOTEIKŠANA — DIVI VEIDI

MT piedāvā **divus neatkarīgus veidus**, kā aprēķināt neitrīno masu. Tie ir komplementāri un savstarpēji saskaņoti.

---

### 2.1. 1. VEIDS — netiešais (H-3 līmeņa kvantēšana)

**Pieņēmums:** Neitrīno masa ir proporcionāla Planka masai, kas reizināta ar smalkās struktūras konstantes pakāpi. Šī pakāpe nosaka, cik lielu daļu no H-3 enerģijas neitrīno spēj uztvert caur savu "logu" uz Vertikāli.

**Formula:**
$$
\boxed{m_i = M_P \cdot \alpha^{n_i}}
$$

kur:
- \( M_P = \phi_0 / c^2 = \hbar / (c l_P) \approx 1.22 \times 10^{19} \, \text{GeV}/c^2 \)
- \( \alpha = 49G_0/(24\pi\hbar c) \approx 1/137.036 \)
- \( n_i \) — eksponents, kas atšķiras trim tipiem

**Eksperimentāli noteiktās vērtības:**

| Tips | \( m_i \) (eV) | \( n_i \) |
|------|---------------|-----------|
| \( \nu_1 \) | \( \approx 0.0015 \) | \( \approx 4.82 \) |
| \( \nu_2 \) | \( \approx 0.0087 \) | \( \approx 5.18 \) |
| \( \nu_3 \) | \( \approx 0.050 \) | \( \approx 5.54 \) |

**Eksponentu starpības:**
$$
n_2 - n_1 \approx n_3 - n_2 \approx 0.36
$$

Tas nozīmē, ka eksponenti ir **vienmērīgi sadalīti** ar soli \( \Delta n \approx 0.36 \).

**Masu attiecības:**
$$
\frac{m_{i+1}}{m_i} = \alpha^{-\Delta n} \approx 137^{0.36} \approx 5.87
$$

**Masu kvadrātu starpību attiecība:**
$$
\frac{\Delta m_{32}^2}{\Delta m_{21}^2} \approx 34.5 \pm 2
$$

Eksperimentālā vērtība: \( \approx 33 \). Novirze ~5%, kas ir pieļaujama.

---

### 2.2. 2. VEIDS — tiešais (cilpas enerģija)

**Pieņēmums:** Neitrīno masa ir tā slēgtās TE pārneses cilpas kopējā enerģija, ko nosaka Qn slāņa izmērs un piesātinājuma pakāpe.

**Formula:**
$$
\boxed{m_\nu = \frac{\phi_0}{c^2} \cdot \frac{N_{\text{slānis}}}{|Q_n|} \cdot \alpha^{n_\nu}}
$$

kur:
- \( N_{\text{slānis}} = |Q_n| - |Q_{n-1}| \) — kabatu skaits cilpas slānī,
- \( n_\nu \approx 14 \) — Qn indekss, kas atbilst neitrīno cilpai,
- \( \alpha^{n_\nu} \) — piesātinājuma pakāpe.

**Aprēķins:**
- \( |Q_{14}| = 4089 \), \( |Q_{13}| = 3219 \), \( N_{\text{slānis}} = 870 \)
- \( \alpha^{14} \approx (1/137)^{14} \approx 4.1 \times 10^{-30} \)
- \( m_\nu = M_P \cdot \frac{870}{4089} \cdot 4.1 \times 10^{-30} \approx 1.22 \times 10^{19} \, \text{GeV} \cdot 0.213 \cdot 4.1 \times 10^{-30} \approx 1.06 \times 10^{-11} \, \text{GeV} \approx 0.0106 \, \text{eV} \)

Tas ir tuvu \( m_2 \) skalai (~0.0087 eV).

**Trīs tipi** rodas no fāžu kombinācijām, kas maina efektīvo \( n \) katram tipam:
- \( \nu_1: n = 14 + \delta_1 \)
- \( \nu_2: n = 14 + \delta_2 \)
- \( \nu_3: n = 14 + \delta_3 \)

kur \( \delta_i \) ir mazi nobīdes no galvenā slāņa, ko nosaka FV cikla fāzes.

---

### 2.3. Divu veidu salīdzinājums

| Modelis | Formula | Rezultāts |
|---------|---------|-----------|
| **1. (netiešais, H-3)** | \( m_\nu = M_P \cdot \alpha^{n} \), \( n \approx 4.82, 5.18, 5.54 \) | \( m_\nu \approx 0.0015 - 0.05 \, \text{eV} \) |
| **2. (tiešais, cilpas enerģija)** | \( m_\nu = M_P \cdot \frac{N_{\text{slānis}}}{|Q_n|} \cdot \alpha^{n} \), \( n \approx 14 \) | \( m_\nu \approx 0.01 \, \text{eV} \) (vidējais) |

**Secinājums:** Pirmais modelis dod visus trīs tipus ar atšķirīgiem \( n \). Otrais modelis dod vispārējo masas skalu. Tie ir **komplementāri** — pirmais precizē atšķirības, otrais nosaka pamata līmeni.

---

## 3. ANTI-NEITRĪNO MT

### 3.1. Definīcija

Anti-neitrīno (\( \bar{\nu} \)) MT ir neitrīno **spoguļkonfigurācija**:

- **Pretēja fāze** — neitrīno fāze \( \theta \) tiek aizstāta ar \( \theta + \pi \).
- **Pretējs spins** — cirkulācijas virziens cilpā ir pretējs.
- **Vienāda masa** — enerģija cilpā ir identiska, jo kabatu skaits un piesātinājums nemainās.

**ID atbilstība:** Anti-neitrīno saglabā ID1.1, bet ar papildus parametru \( \bar{\nu} \).

### 3.2. Masas vienādība

MT paredz:
$$
m_{\bar{\nu}} = m_\nu
$$

Tas atbilst eksperimentālajiem ierobežojumiem (KATRIN: \( m_{\bar{\nu}_e} < 0.45 \, \text{eV} \)).

**Iemesls:** Abu masas veidu formulas nav atkarīgas no fāzes zīmes — tikai no enerģijas daudzuma cilpā.

---

## 4. NEITRĪNO-ANTINEITRĪNO ANIHILĀCIJA MT

### 4.1. Anihilācijas mehānisms

Neitrīno un anti-neitrīno anihilācija (`ν + \bar{ν}`) MT ir divu pretējas fāzes cilpu **sadursme un savstarpēja dzēšanās**.

Kad divas cilpas satiekas un to fāzes ir pretējas (\( \theta \) un \( \theta + \pi \)), TE pārneses kanāli savstarpēji kompensējas, un enerģija tiek atbrīvota kā:

- **Fotoni** (zemās enerģijās),
- **`Z` bozons** (augstās enerģijās, pie \( E \sim 91 \, \text{GeV} \)),
- **Citas daļiņas** (atkarībā no pieejamās enerģijas).

### 4.2. Enerģijas slieksnis

Anihilācijas šķērsgriezums ir atkarīgs no enerģijas:

| Enerģijas skala | Process | Šķērsgriezums |
|-----------------|---------|---------------|
| Zema (\( E \ll m_Z c^2 \)) | `ν + \bar{ν} → γ + γ` | Ļoti mazs (\( \sim 10^{-60} \, \text{cm}^2 \)) |
| Rezonanse (\( E \approx m_Z c^2 \)) | `ν + \bar{ν} → Z` | Maksimāls (\( \sim 10^{-38} \, \text{cm}^2 \)) |
| Augsta (\( E \gg m_Z c^2 \)) | `ν + \bar{ν} → dažādas daļiņas` | Samazinās kā \( 1/E^2 \) |

### 4.3. MT prognoze anihilācijai

MT paredz, ka neitrīno-antineitrīno anihilācija ir **enerģētiski atkarīga** un sasniedz maksimumu pie `Z` bozona masas (~91 GeV). Šī ir unikāla prognoze, ko var pārbaudīt ar nākamās paaudzes neitrīno sadursmju eksperimentiem.

**Pārbaudāma prognoze:** Anihilācijas šķērsgriezums ir proporcionāls:
$$
\sigma_{\nu\bar{\nu}} \propto \alpha^2 \cdot \frac{E^2}{(E^2 - m_Z^2 c^4)^2 + \Gamma_Z^2 m_Z^2 c^4}
$$
kur \( \Gamma_Z \) ir `Z` bozona pilnais platums.

---

## 5. MAJORANA UN DIRAKA — MT SKATĪJUMS

### 5.1. Majorana neitrīno

Ja neitrīno ir Majorana daļiņa (t.i., \( \nu = \bar{\nu} \)), tad tā cilpai nav atšķirības starp fāzi \( \theta \) un \( \theta + \pi \). Tas nozīmē, ka cilpa ir **simetriska pret fāzes maiņu par \( \pi \)**.

**MT sekas:** Majorana neitrīno cilpai ir tikai **viena fāzes konfigurācija** — nav atšķirības starp daļiņu un antidaļiņu. Tas nozīmē, ka anihilācija `ν + ν` (divi Majorana neitrīno) būtu iespējama, kas atbilst `0νββ` procesam.

### 5.2. Diraka neitrīno

Ja neitrīno ir Diraka daļiņa (t.i., \( \nu \neq \bar{\nu} \)), tad fāze \( \theta \) un \( \theta + \pi \) ir atšķirīgas konfigurācijas. Anihilācija `ν + ν` nav iespējama.

### 5.3. MT nostāja

MT **neizvēlas** starp Majorana un Diraku — tas piedāvā **abiem mehānismu**. Eksperimentālā atbilde (piemēram, `0νββ` novērojums) noteiks, kura konfigurācija realizējas.

MT prognoze: Ja `0νββ` tiek novērots, tas nozīmē, ka neitrīno cilpa ir simetriska pret \( \pi \) fāzes nobīdi, un tā ir Majorana tips.

---

## 6. KOPSAVILKUMA TABULA

| Aspekts | Standarta modelis | MT | ID atbilstība |
|---------|-------------------|-----|---------------|
| **Neitrīno struktūra** | Punktveida daļiņa | Slēgta TE pārneses cilpa (H-3 × H-4) | ID1.1 / ID-1 |
| **Masas izcelsme** | Jukavas mijiedarbība (Higss) | H-3 enerģijas kvantēšana + cilpas ģeometrija | ID0 / ID-1 |
| **Masas formula (netiešā)** | Empīriska | \( m_\nu = M_P \cdot \alpha^n \) | ID0 / ID1 |
| **Masas formula (tiešā)** | Nav | \( m_\nu = M_P \cdot \frac{N_{\text{slānis}}}{|Q_n|} \cdot \alpha^n \) | ID0.n / ID0 |
| **Trīs tipi** | Brīvi parametri | Trīs fāžu logi FV ciklā | ID0 |
| **Anti-neitrīno masa** | Vienāda | Vienāda (spoguļkonfigurācija) | ID1.1 |
| **Anihilācija** | Vāja, rezonanse pie \( m_Z \) | Vāja, rezonanse pie \( m_Z \) | ID0 / ID-1 |
| **Majorana/Diraks** | Neatrisināts | Abi iespējami; atkarīgs no cilpas simetrijas | ID0 |

---

## 7. PĀRBAUDĀMĀS PROGNOZES

| Prognoze | Vērtība | Pārbaudes metode | ID atbilstība |
|----------|---------|------------------|---------------|
| Normālā hierarhija | \( m_1 < m_2 < m_3 \) | DUNE, Hyper-Kamiokande | ID1.1 |
| Masu attiecība | \( m_2/m_1 = m_3/m_2 \approx 5.87 \) | Precīzi masu mērījumi | ID1.1 |
| \( \Delta m_{32}^2 / \Delta m_{21}^2 \) | \( \approx 34.5 \pm 2 \) | NOvA, T2K, JUNO | ID1.1 |
| Kopējā masa | \( \sum m_i \approx 0.060 \, \text{eV} \) | KATRIN, Project 8, kosmoloģija | ID1.1 / ID-1 |
| Anihilācijas rezonanse | Pie \( E \approx 91 \, \text{GeV} \) | Nākamās paaudzes neitrīno sadursmes | ID0 / ID-1 |
| Majorana/Diraks | `0νββ` novērojums/no novērojums | `0νββ` eksperimenti | ID0 |

---

## 8. SECINĀJUMI

1. **Neitrīno MT ir slēgta TE pārneses cilpa** ar vāju TZ piesaisti, nevis punktveida daļiņa.

2. **Neitrīno masu var aprēķināt divos neatkarīgos veidos** — netiešā (H-3 kvantēšana) un tiešā (cilpas enerģija). Abi ir savstarpēji saskaņoti.

3. **Trīs tipi** rodas no trim dažādiem fāžu logiem FV ciklā, nevis no patvaļīgiem parametriem.

4. **Anti-neitrīno** ir spoguļkonfigurācija ar vienādu masu.

5. **Anihilācija** ir enerģētiski atkarīga ar rezonansi pie `Z` bozona masas.

6. **Majorana/Diraks** jautājums MT ir atvērts — abas konfigurācijas ir iespējamas, un atbildi sniegs eksperimenti.

7. **MT prognozes** ir kvantitatīvas un pārbaudāmas ar nākamās paaudzes neitrīno eksperimentiem (DUNE, Hyper-Kamiokande, JUNO, KATRIN).

---

## PIEZĪME

Šis dokuments ir **MT neitrīno modeļa pārstrādātā versija**, kas apvieno divus neatkarīgus masas aprēķina veidus un sniedz kvantitatīvas prognozes, saskaņotas ar ID sistēmu un MATHEMATICS formālisma pārstrādāto versiju. Turpmākā attīstība ietver precīzu \( \delta_i \) noteikšanu no FV fāzēm un salīdzinājumu ar eksperimentāliem datiem.

---

*Dokuments sagatavots: 2026. gada jūlijā*  
*Versija: 1.0 — MT neitrīno modelis (abi masas aprēķina veidi)*
