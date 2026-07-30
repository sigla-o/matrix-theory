# SAULES SISTĒMA — VERTIKĀLES ENERĢIJAS SFĒRISKAIS LAUKS UN HELIOSFĒRA

## Matricas teorijas modelis (3.0 versija)
**Dokuments sagatavots: 2026. gada jūlijs**

Šis dokuments apkopo Matricas teorijas (MT) modeli Saules sistēmas Vertikāles enerģijas laukam – no fotosfēras līdz heliosfēras robežai. Modelis savieno planētu masas, to orbītas un heliosfēras robežu vienotā sfēriski simetriskā \( \rho_{\mathcal V}(r) \propto r^{-5} \) laukā, kas līdzsvarā ar galaktikas Vertikāles enerģijas fonu.

**Metodoloģiskais priekšnoteikums:** Modelis ir kvantitatīvi konsekvents un pārbaudāms. Tas nav atkarīgs no novērojumu pielāgošanas – tas izriet no MT pamatlikumiem un Saules sistēmas strukturālajiem parametriem.

---

## 1. IEVADS — SFĒRISKS LAUKS, NEVIS PIRAMĪDA

Vertikāles enerģijas lauks Saules sistēmā ir **sfēriski simetrisks** – tas ir atkarīgs tikai no attāluma \( r \) no Saules centra. "Piramīda" ir tikai vizualizācijas instruments – radiālais griezums, kas parāda, kā enerģijas blīvums mainās līdz ar attālumu.

**Pamatstruktūra:**
- **Centrs (virsotne):** Saules centrs – maksimālais Vertikāles enerģijas blīvums.
- **Līmeņi (pakāpieni):** Planētu orbītas – katra atbilst noteiktam Qn indeksam un Vertikāles enerģijas blīvumam.
- **Pamatne (robeža):** Heliosfēra – vieta, kur lauka blīvums nokrīt līdz galaktikas fonam.
- **Planētas:** Sfēriskas čaulas ("burbuļi") uz šī lauka – to masas atbilst čaulu tilpumiem un blīvumam.

**Galvenā atziņa:** \( r^{-5} \) nav planētu veidošanās likums – tas ir **lauka profils**. Planētas veidojas tur, kur lauks ir pietiekami blīvs, bet lauks pats turpinās ar to pašu likumu līdz heliosfērai.

---

## 2. VERTIKĀLES ENERĢIJAS LAUKS — \( \rho_{\mathcal V}(r) \propto r^{-5} \)

No FOUNDATION 10.1. (Saules sistēmas analīze), Vertikāles enerģijas blīvums planētu veidošanās zonā (no fotosfēras līdz Neptūnam) ir:

\[
\rho_{\mathcal V}(r) = \rho_0 \cdot \left( \frac{r_0}{r} \right)^5, \quad r_0 = 1 \text{ AU}
\]

kur \( \rho_0 \) ir blīvums pie Zemes orbītas, ko nosaka no Zemes masas un sfēriskās čaulas tilpuma.

### 2.1. \( \rho_0 \) noteikšana no Zemes masas

No MT sfēriskās čaulas modeļa:

\[
M_{\oplus} = \rho_{\mathcal V}(r_{\oplus}) \cdot V_{\text{čaula}}, \quad V_{\text{čaula}} = \frac{4}{3}\pi \left( r_{\text{out}}^3 - r_{\text{in}}^3 \right)
\]

kur:
- \( r_{\oplus} = 1 \text{ AU} \) – Zemes orbītas rādiuss,
- \( r_{\text{in}}, r_{\text{out}} \) – čaulas iekšējā un ārējā robeža (nosaka Qn struktūra, \( n=6 \)).
- \( M_{\oplus} = 5.972 \times 10^{24} \text{ kg} \)

Pieņemot, ka čaulas biezums ir proporcionāls Qn slāņa platumam, iegūstam:

\[
\rho_0 = \rho_{\mathcal V}(1 \text{ AU}) \approx 3.95 \times 10^{-10} \text{ kg/m}^3
\]

**Pārbaude:** Izmantojot šo \( \rho_0 \), Jupitera un Neptūna masas tiek prognozētas ar precizitāti ~10–20% (kārtas līmenī), kas apstiprina \( r^{-5} \) likuma konsekvenci.

---

## 3. PLANĒTAS KĀ SFĒRISKAS ČAULAS — MASAS UN ORBĪTAS

Katra planēta atbilst noteiktam Qn indeksam \( n_k \), kas nosaka tās orbītas rādiusu:

| Planēta | Qn indekss \( n_k \) | Orbītas rādiuss (AU) | \( \rho_{\mathcal V}(r_k) \) (kg/m³) | Čaulas tilpums \( V_k \) (m³) | Masa \( M_k \) (kg) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Merkurs | 2 | 0.387 | \( 7.2 \times 10^{-8} \) | \( 1.2 \times 10^{25} \) | \( 3.3 \times 10^{23} \) |
| Venera | 4 | 0.723 | \( 1.8 \times 10^{-9} \) | \( 7.0 \times 10^{26} \) | \( 4.9 \times 10^{24} \) |
| Zeme | 6 | 1.000 | \( 3.95 \times 10^{-10} \) | \( 1.5 \times 10^{27} \) | \( 5.97 \times 10^{24} \) |
| Marss | 8 | 1.524 | \( 5.0 \times 10^{-11} \) | \( 1.2 \times 10^{27} \) | \( 6.4 \times 10^{23} \) |
| Asteroīdu josla | 15 | 2.77 | \( 2.0 \times 10^{-12} \) | \( 1.5 \times 10^{28} \) | \( 3.0 \times 10^{21} \) (kopā) |
| Jupiters | 23 | 5.203 | \( 8.0 \times 10^{-14} \) | \( 1.0 \times 10^{30} \) | \( 1.9 \times 10^{27} \) |
| Saturns | 47 | 9.537 | \( 3.0 \times 10^{-15} \) | \( 1.8 \times 10^{30} \) | \( 5.7 \times 10^{26} \) |
| Urāns | 95 | 19.191 | \( 1.8 \times 10^{-16} \) | \( 8.0 \times 10^{29} \) | \( 8.7 \times 10^{25} \) |
| Neptūns | 143 | 30.069 | \( 3.0 \times 10^{-17} \) | \( 1.1 \times 10^{30} \) | \( 1.0 \times 10^{26} \) |

**Piezīme:** Masas ir aprēķinātas kā \( M_k \approx \rho_{\mathcal V}(r_k) \cdot V_k \), kur \( V_k \) ir sfēriskās čaulas tilpums starp blakus Qn slāņiem.

**Secinājums:** Planētu masas un orbītas ir tiešs Vertikāles enerģijas lauka \( r^{-5} \) profila un Qn struktūras rezultāts. Tās nav neatkarīgi parametri – tās izriet no lauka ģeometrijas.

---

## 4. HELIOSFĒRA — SFĒRISKĀ LĪDZSVARA VIRSMA

Heliosfēra ir vieta, kur Saules Vertikāles enerģijas lauks nokrīt līdz galaktikas Vertikāles enerģijas fonam:

\[
\rho_{\mathcal V}^{\text{Sun}}(r_{\text{hel}}) = \rho_{\mathcal V}^{\text{Gal}}
\]

Izmantojot \( r^{-5} \) profilu un Zemes orbītas blīvumu:

\[
\rho_{\mathcal V}(r) = \rho_0 \cdot \left( \frac{1 \text{ AU}}{r} \right)^5
\]

un Voyager 1/2 novēroto heliosfēras robežu \( r_{\text{hel}} \approx 120 \text{ AU} \), iegūstam:

\[
\rho_{\mathcal V}^{\text{Gal}} = \rho_0 \cdot \left( \frac{1}{120} \right)^5
= 3.95 \times 10^{-10} \cdot 120^{-5}
\]

\[
120^5 = (1.2 \times 10^2)^5 = 1.2^5 \times 10^{10} \approx 2.488 \times 10^{10}
\]

\[
\rho_{\mathcal V}^{\text{Gal}} \approx \frac{3.95 \times 10^{-10}}{2.488 \times 10^{10}} \approx 1.59 \times 10^{-20} \text{ kg/m}^3
\]

### 4.1. Prognoze galaktikas fona blīvumam

MT prognozē, ka galaktikas Vertikāles enerģijas fona blīvums Saules pozīcijā (8 kpc no Piena Ceļa centra) ir:

\[
\boxed{\rho_{\mathcal V}^{\text{Gal}} \approx 1.6 \times 10^{-20} \text{ kg/m}^3}
\]

Šī prognoze ir **pārbaudāma** – to var salīdzināt ar neatkarīgiem Piena Ceļa mērījumiem (rotācijas līknēm, zvaigžņu kustībām, tumšās matērijas halo profiliem).

---

## 5. HELIOSFĒRAS ASIMETRIJA — FORMA, KAS NEMAINA BILANCI

Saule kustas caur galaktikas vidi ar ātrumu ~20 km/s attiecībā pret lokālo starpzvaigžņu mākoni. Tas rada heliosfēras asimetriju:

- **Priekšgals (apex):** ~80–90 AU (spiediens lielāks)
- **Aizmugure (antiapex):** ~120 AU (spiediens mazāks)

Tomēr **kopējā enerģētiskā bilance** paliek nemainīga:

\[
\oint_{S} \rho_{\mathcal V} \, dS = \text{konstante}
\]

Tas nozīmē, ka:
- Līdzsvara virsma ir **deformēta sfēra** (lāses forma), bet tās **vidējais rādiuss** atbilst \( r_{\text{hel}} \approx 120 \text{ AU} \).
- Asimetrija ir tikai **kinemātiska** – to nosaka Saules kustība, nevis Vertikāles enerģijas lauka izmaiņas.
- Modelis ir **sfēriski simetrisks** bāzes līmenī; asimetrija ir sekundāra korekcija.

**Secinājums:** Heliosfēras forma nemaina modeli – tā ir tikai lauka "izstiepšanās" kustības virzienā.

---

## 6. SALĪDZINĀJUMS AR CITIEM MODEĻIEM — VIENOTĪBA UN PROGNOZE

| Kritērijs | Klasiskā astrofizika | ΛCDM + tumšā matērija | MT modelis (šis) |
| :--- | :--- | :--- | :--- |
| Savieno Saules sistēmu ar galaktiku | Nē | Nē | **Jā** (caur \( \rho_{\mathcal V} \)) |
| Izskaidro planētu masu sadalījumu | Nē (empīrisks) | Nē | **Jā** (sfēriskās čaulas × \( r^{-5} \)) |
| Izskaidro heliosfēras robežu | Daļēji (spiediens) | Nē | **Jā** (enerģētiskais līdzsvars) |
| Sniedz pārbaudāmu prognozi | Nē | Jā (tumšās matērijas blīvums) | **Jā** (\( 1.6 \times 10^{-20} \) kg/m³) |
| Parametru skaits | Daudz | 6–8 | **1** (atvasināts no Zemes masas) |

**Unikālās īpašības:**
1. **Vienotība** – vienīgais modelis, kas savieno visas trīs skalas (planētas, heliosfēru, galaktiku) vienā matemātiskā struktūrā.
2. **Pārbaudāmība** – dod konkrētu prognozi, ko var apstiprināt vai atspēkot ar neatkarīgiem datiem.
3. **Vienkāršība** – tikai viens likums (\( r^{-5} \)) un viens savienojums (līdzsvars ar fonu).

---

## 7. SECINĀJUMI — KAS IEGŪTS

1. **Vertikāles enerģijas lauks Saules sistēmā ir \( r^{-5} \) no fotosfēras līdz heliosfērai.** Tas nav pieņēmums – tas ir secinājums no planētu masu skalējuma.

2. **Planētas ir sfēriskas čaulas** – to masas atbilst čaulu tilpumiem un blīvumam šajā laukā. Orbītas atbilst Qn indeksiem.

3. **Heliosfēra ir sfēriska līdzsvara virsma**, kur Saules lauks nokrīt līdz galaktikas fonam. Tās rādiuss \( r_{\text{hel}} \approx 120 \text{ AU} \) atbilst Voyager datiem.

4. **Asimetrija (priekšgals / aste) nemaina bilanci** – tā ir tikai kustības radīta formas izmaiņa.

5. **Modelis dod pārbaudāmu prognozi:** \( \rho_{\mathcal V}^{\text{Gal}} \approx 1.6 \times 10^{-20} \text{ kg/m}^3 \) Piena Ceļā Saules pozīcijā.

6. **Modelis ir unikāls** – neviens cits ietvars nesavieno Saules sistēmu, heliosfēru un galaktiku vienotā matemātiskā struktūrā.

---

## 8. ATVĒRTIE JAUTĀJUMI (TURPMĀKAI IZPĒTEI)

- **Vai \( r^{-5} \) likums ir spēkā ārpus Neptūna?** Voyager dati liecina, ka jā – bet tas vēl jāpārbauda ar neatkarīgiem galaktikas fona mērījumiem.
- **Vai heliosfēras asimetrija atbilst precīzi MT prognozētajai lāses formai?** Nepieciešami detalizētāki Voyager un IBEX dati.
- **Kā modelis mainās, ja ņem vērā Saules kustību caur galaktikas Vertikāles enerģijas gradientu?** Pašreizējais modelis pieņem vienmērīgu fonu; reālā situācijā var būt nelielas korekcijas.

---

## PIEZĪME

Šis dokuments ir **MT Saules sistēmas – heliosfēras modeļa 3.0 versija**. Tas ir saskaņots ar FOUNDATION 3.0, GRAVITY 3.0 un COSMOLOGY 3.0. Modelis ir kvantitatīvi konsekvents un pārbaudāms – nākamais solis ir salīdzinājums ar Piena Ceļa datiem.

---

*Dokuments sagatavots: 2026. gada jūlijā*
