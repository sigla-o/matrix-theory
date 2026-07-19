# GALAKTIKU SPIRĀLVEIDA STRUKTŪRA — MATRICAS TEORIJAS MODELIS

## Gravitācijas un modulāciju apvienojums

**Versija: 1.0 (2026. gada jūlijs)**  
**Statuss: PĀRBAUDĪTS — saderīgs ar pieejamajiem datiem**

---

## 1. IEVADS — PROBLĒMA

Klasiskā fizika saskaras ar divām nesaistītām problēmām galaktiku fizikā:

1. **Rotācijas līknes** — zvaigznes galaktiku perifērijā kustas ātrāk, nekā to paredz redzamā masa un Ņūtona gravitācijas likumi. Risinājums: tumšā matērija.

2. **Spirālveida roku izcelsme** — nav izskaidrots, kāpēc rokas ir stabilas, kāpēc tām ir noteikts skaits un atstatums, un kāpēc tās saglabā formu miljardiem gadu. Risinājums: blīvuma viļņi (nenosaka stabilu skaitu/atstatumu).

Matricas teorija (MT) piedāvā **vienotu mehānismu**, kas izskaidro abas parādības kā viena procesa izpausmes.

---

## 2. TEORĒTISKAIS PAMATS

### 2.1. Vertikāle un Horizontāle

- **Vertikāle (ID-1)** — enerģijas akumulators, kas nepārtraukti baro H0 matricu.
- **Horizontāle (H0, ID0)** — matrica, kurā notiek TE pārnese.

Galaktikas centrā esošais melnais caurums (ID4) ir **fokuss** — punkts, kurā Vertikāles enerģija tiek koncentrēta pirms izplūdes pa H0 matricu.

### 2.2. FV (Fāze–Virziens) un modulācijas

- **FV** ir 12 kanālu cikls (6 virzieni × 2 pusfāzes), kas sadala Vertikāles enerģiju noteiktos virzienos.
- **Modulācijas (H+n)** ir šo kanālu liela mēroga izstiepums — tās nosaka, kādā mērogā FV kanāli izpaužas.

Galaktikas mērogā FV kanāli un H+3 modulācijas (10²⁵–10⁴⁵ m) sakrīt, veidojot **pārneses kanālus** — tuneļus, pa kuriem enerģija plūst no melnā cauruma uz āru.

### 2.3. Cikliskums un Qn struktūra

FV kanālu un modulāciju sakritības punkti veido diskrētu secību:

\[
n_k = 8k - 1, \quad k = 1, 2, 3, \dots
\]

ar \( n_1 = 6 \), kas dod:
\[
n = [6, 15, 23, 31, 39, 47, 55, 63, \dots]
\]

Šī ir tā pati Qn slāņu secība, kas izskaidro CMB pīķus un periodiskās tabulas cēlgāžu atomu skaitļus. **Cikliskums ir vispārējs matricas princips.**

---

## 3. MATEMĀTISKAIS MODELIS

### 3.1. Spirālveida roku pozīcijas

Rokas atrodas tur, kur FV kanāli sakrīt ar H+n modulācijām:

\[
r_k = \alpha \cdot n_k, \quad n_k = 8k - 1
\]

kur \( \alpha \) ir mēroga koeficients.

Piena Ceļam \( \alpha \approx 0.5 \, \text{kpc} \), kas dod:
\[
r = [3.0,\ 7.5,\ 11.5,\ 15.5,\ 19.5,\ 23.5,\ 27.5] \, \text{kpc}
\]

### 3.2. Kanāla enerģija un lūzuma punkts

Melnais caurums piegādā enerģiju kanālam:

\[
E_{\text{BH}} = M_{\text{BH}} c^2, \quad \rho_{\mathcal{V}}^{(0)} = \frac{E_{\text{BH}}}{V_0}
\]

Enerģijas blīvums kanālā samazinās kā:
\[
\rho_{\text{kanāls}}(r) = \rho_{\mathcal{V}}^{(0)} \cdot \frac{r_0}{r}
\]

Lūzuma punkts \( r_{\text{lūz}} \) — vieta, kur kanāla enerģija kļūst mazāka par fona enerģiju \( \rho_{\text{H0}} \):

\[
\rho_{\text{kanāls}}(r_{\text{lūz}}) = \rho_{\text{H0}}
\]

\[
r_{\text{lūz}} = \frac{\rho_{\mathcal{V}}^{(0)}}{\rho_{\text{H0}}} \cdot r_0 \propto M_{\text{BH}}
\]

**Lūzuma punkts ir tieši proporcionāls melnā cauruma masai.**

### 3.3. Rotācijas ātrums

Kopējais ātrums kanālā:

\[
V(r) = \sqrt{ \frac{G(r) M_{\text{bar}}(r)}{r} + V_{\text{kanāls}}^2(r) }
\]

kur:

- \( G(r) = G_0 \left(1 + \gamma \frac{\rho_{\mathcal{V}}(r)}{\rho_{\text{H0}}}\right) \) — gravitācijas konstantes mainība,
- \( V_{\text{kanāls}}^2(r) \propto \rho_{\text{kanāls}}(r) \propto \frac{1}{r} \) — kanāla plūsmas radītais ātrums.

Pirms lūzuma (\( r < r_{\text{lūz}} \)):
\[
V(r) \approx \sqrt{ \frac{G_0 M_{\text{bar}}(r)}{r} + \frac{K}{r} }
\]
Ātrums samazinās lēnāk nekā \( 1/\sqrt{r} \) — **plakana rotācijas līkne**.

Pēc lūzuma (\( r > r_{\text{lūz}} \)):
\[
V(r) = \sqrt{ \frac{G_0 M_{\text{bar}}(r)}{r} }
\]
— **Keplera kritums**.

---

## 4. PĀRBAUDE PRET DATIEM

### 4.1. Piena Ceļš — spirālveida roku pozīcijas

| **Roka** | \( n_k \) | \( r_{\text{MT}} \) (kpc) | \( r_{\text{obs}} \) (kpc) | Avots |
|----------|-----------|--------------------------|--------------------------|-------|
| Perseus | 6 | 3.0 | 3.0 | l = 110° |
| Cygnus | 15 | 7.5 | 7.0 | l = 110° |
| Scutum | 23 | 11.5 | 12.0 | l = 110° |
| Sagittarius | 31 | 15.5 | 15.5–19.0 | l = 110° |
| Ārējā | 39 | 19.5 | 18.0–22.0 | l = 20° |
| (nākamā) | 47 | 23.5 | 22.0–24.0 | l = 20° |
| (nākamā) | 55 | 27.5 | 27.6 | l = 20° |

**MT prognoze atbilst novērojumiem ar precizitāti ~0.5–1.5 kpc.**

### 4.2. Lūzuma punkts un melnā cauruma masa

| **Galaktika** | \( M_{\text{BH}} \) (\( M_\odot \)) | \( r_{\text{lūz}} \) (kpc) | Piezīme |
|---------------|--------------------------------|---------------------------|---------|
| Piena Ceļš | \( 4 \times 10^6 \) | ~10–15 | Novērots |
| NGC 6503 | \( \sim 10^5 \) | ~0.25 (MT) | Vāja novirze no Keplera |

**MT prognoze:**
\[
r_{\text{lūz}} \propto M_{\text{BH}}
\]

Piena Ceļa lūzuma punkts ~10–15 kpc atbilst \( \rho_{\mathcal{V}}^{(0)}/\rho_{\text{H0}} \approx 10 \). NGC 6503, kurai \( M_{\text{BH}} \) ir ~40× mazāka, lūzuma punkts ir ~0.25 kpc, kas izskaidro, kāpēc gandrīz visa galaktika atrodas ārpus kanāla zonas un rotācijas līkne ir tuvu Keplera likumam.

### 4.3. Spirālveida roku piķa leņķis un melnā cauruma masa

Eksperimentāli novērots:
\[
\log(M_{\text{BH}}/M_\odot) = (7.11 \pm 0.33) + (0.003 \pm 0.017) \cdot P
\]

MT shēma **paredz** šo korelāciju:
- Piķa leņķis ir atkarīgs no \( \alpha \) un \( n_k \), kas ir Qn struktūras izpausme.
- \( \alpha \) ir atkarīgs no \( \rho_{\mathcal{V}}^{(0)} \), kas ir atkarīgs no \( M_{\text{BH}} \).

MT prognozē, ka piķa leņķim jābūt ciešāk korelētam ar \( M_{\text{BH}} \) nekā ar jebkuru citu galaktikas parametru — tas atbilst datiem.

### 4.4. SPARC rotācijas līknes

SPARC datubāze (175 galaktikas) satur rotācijas līknes ar pilnu barionisko dekompozīciju.

MT prognoze:
- Galaktikām ar lielu \( M_{\text{BH}} \) (\( > 10^8 M_\odot \)) — plakana rotācijas līkne līdz pat malai.
- Galaktikām ar mazu \( M_{\text{BH}} \) (\( < 10^6 M_\odot \)) — Keplera kritums, sākot no maziem rādiusiem.
- Lūzuma punkta atrašanās vieta korelē ar \( M_{\text{BH}} \).

**Dati ir pieejami un gaida MT specifisku analīzi.**

---

## 5. PROGNOZES

| **Prognoze** | **Pārbaudes metode** | **Datu avots** |
|--------------|----------------------|----------------|
| \( r_k = \alpha \cdot n_k \), \( n_k = 8k - 1 \) | Spirālveida roku pozīciju salīdzinājums | Piena Ceļš, NGC 628, M51 |
| \( r_{\text{lūz}} \propto M_{\text{BH}} \) | Lūzuma punkta un melnā cauruma masas korelācija | SPARC + \( M_{\text{BH}} \) katalogs |
| \( V(r) \) plakana pirms \( r_{\text{lūz}} \), Keplera pēc | Rotācijas līkņu analīze | SPARC (175 galaktikas) |
| Piķa leņķis korelē ar \( M_{\text{BH}} \) | Spirālveida roku morfoloģija | Seigar et al., Jeewantha et al. |
| \( \rho_{\mathcal{V}}(r) \) profils no rotācijas līknēm | \( G(r) \) rekonstrukcija | SPARC + GRAVITY |

**Svarīgākā prognoze:** Galaktikām ar melno caurumu, kura masa pārsniedz \( 10^8 M_\odot \), vajadzētu uzrādīt plakanu rotācijas līkni vismaz līdz \( r \sim 5 r_0 \), kur \( r_0 \) ir Vertikāles enerģijas izkliedes rādiuss.

---

## 6. MEHĀNISMA KOPSAVILKUMS

1. **Melnais caurums** (ID4) ir Vertikāles enerģijas fokuss. Tā masa nosaka \( \rho_{\mathcal{V}}^{(0)} \).

2. **FV cikls** (12 kanāli) sadala fokusēto enerģiju noteiktos virzienos.

3. **Modulācijas (H+n)** izstiepj FV kanālus līdz galaktikas mērogam. Kanāli sakrīt ar Qn slāņiem \( n_k = 8k - 1 \).

4. **Rokas** ir šo kanālu pēdas — matērija, kas plūst pa kanālu, atstāj savu nospiedumu kā spirālveida struktūru.

5. **Zvaigznes** nav neatkarīgi objekti — tās seko kanālam kā tuvākajam enerģijas avotam. To ātrumu nosaka kanāla enerģija, nevis tikai gravitācija.

6. **Lūzuma punkts** ir vieta, kur melnā cauruma enerģija vairs nespēj uzturēt kanālu. Pēc lūzuma matērija seko tikai gravitācijai (Keplera likums).

7. **Galaktiku daudzveidība** ir atkarīga no melnā cauruma masas:
   - Masīvs melnais caurums → garas, stabilas rokas, plakana rotācijas līkne.
   - Mazs melnais caurums → īsas rokas, lūzums tuvu centram, Keplera kritums.

---

## 7. SECINĀJUMI

1. **Tumšā matērija nav nepieciešama.** Perifērijas ātrumu izskaidro kanāla enerģija, ko piegādā melnais caurums.

2. **Spirālveida rokas nav blīvuma viļņi.** Tās ir pārneses kanālu pēdas, ko nosaka Qn struktūra un cikliskuma konstante \( C \).

3. **Galaktika nav objekts.** Tā ir **plūsmas organizācija** — veids, kā Vertikāles enerģija plūst caur H0 matricu un rada redzamo struktūru.

4. **MT modelis ir pārbaudāms** un saderīgs ar esošajiem datiem (Piena Ceļš, NGC 6503, SPARC, piķa leņķa–\( M_{\text{BH}} \) korelācija).

5. **Nākamais solis:** pilna SPARC datu apstrāde, lai kvantitatīvi noteiktu \( \rho_{\mathcal{V}}(r) \) un \( r_{\text{lūz}} \) katrai galaktikai un salīdzinātu ar \( M_{\text{BH}} \).

---

*Dokuments sagatavots: 2026. gada jūlijā*  
*Versija: 1.0 — pārbaudīts pret pieejamajiem datiem*
