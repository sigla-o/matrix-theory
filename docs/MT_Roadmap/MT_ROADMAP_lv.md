# MT CEĻU KARTE (ROADMAP) — v1.1
## Strukturālā atgriezeniskā saite

> *“Teorija nāk no novērojumiem, nevis otrādi. MT balstās uz Planka garumu kā ilgdzīvotāju.”*

---

## 1. AKSIOMĀTISKIE PAMATI (NAV BRĪVI)

| Lielums | Vērtība / Operators | Izcelsme | Statuss |
|---------|----------------------|----------|---------|
| **Režģa solis** | \( \lambda_{\text{ID1}} = l_P = \sqrt{\hbar G_0/c^3} \) | Fiksēts no novērojumiem (Planka garums) | Pamats |
| **Matricas pulkstenis** | \( \omega_0 = \dfrac{2\pi c}{l_P} \) | Atvasināts no \( c \) un \( l_P \) | Pamats |
| **Sinhronā rotācija** | \( \dot{\theta}(\mathbf{x},t) = \omega_0, \forall \mathbf{x} \) | Visi ID1 punkti rotē vienādi | Aksioma |
| **Fāze** | \( \psi(\mathbf{x},t) \sim e^{i\theta(\mathbf{x},t)} \) | Viļņu funkcijas pamats | Operators |
| **Qn apvalki** | \( Q_n = \{\|\mathbf{x}\|_\infty \leq n\}, \ | Q_n| = \frac{(2n+1)(2n^2+2n+3)}{3} \) | Ģeometrija no \( \mathbb{Z}^3 \) | Strukturāls |
| **ID solis** | \( \text{ID} = 2.0 + \log_{2.5}(n) \) | No Qn slāņu secības | Strukturāls |

---

## 2. H0 CEĻŠ — GRAVITĀCIJA UN DINAMIKA (horizontālais)

**Operators:**
\[
\mathbf{g}(\mathbf{x}) = -\nabla \delta(\mathbf{x}), \quad \delta(\mathbf{x}) = \frac{\Phi_0}{\|\mathbf{x} - \mathbf{x}_0\|^2}
\]

**Ko dara:** Apraksta materiālo objektu kustību pa H0 režģi.

**Kur ved:**
- Keplera likumi, orbītas,
- Galaktiku rotācijas līknes (ar \( G(\rho_{\mathcal{V}}) \)),
- Gravitācijas viļņi kā spiediena viļņi,
- Masas sadalījums no \( \nabla^2\delta = 4\pi G_0\rho \).

**Lieto, ja:** novērojums ir dinamisks (ātrumi, pozīcijas, paātrinājumi).

**Nesaisti ar:** \( \rho_{\mathcal{V}} \) absolūto vērtību — tikai ar tās gradientu.

---

## 3. L1 ĢEOMETRISKĀ SHĒMA (vertikālais)

L1 ir **ģeometriskās projekcijas līmenis**, nevis enerģijas līmenis. Tam ir divi darbības režīmi atkarībā no atrašanās vietas attiecībā pret protonu (H0 iekšpuse / ārpuse).

### 3.1. L1 — FOKUSĒŠANA (H0 IEKŠPUSE)

**Darbība:** Fokusē enerģiju un modulācijas, radot **stāvviļņus**.

**Rezultāts:** Diskrētie CMB pīķi (\( \ell_k \)).

**Ģeometriskais pamats:**
\[
\ell_k = C \cdot n_k, \quad C = \frac{2\pi R_{L1}}{\lambda_{\text{ID1}}}, \quad n_k = 8k-1 \ (k \ge 2), \ n_1 = 6
\]

Harmonikas atbilst Qn slāņiem, kur režģa simetrija rada rezonansi.

---

### 3.2. L1 — IZKIEDE (PROTONA ĀRPUSE)

**Darbība:** Izplata enerģiju no fokusēšanas zonas ārpusē.

**Rezultāts:** Nepārtrauktais CMB fons un sarkanā nobīde.

**Mehānisms:** Izkliedētā enerģija nonāk L0 līmenī, kur tā termalizējas.

---

### 3.3. L0 — ENERĢIJAS BALANSS

L0 ir **fona līmenis**, kurā plūsma ir sinhronizēta un vienmērīga. Tā nav tukšums, bet gan atskaites stāvoklis.

- **L0 → L1:** fokusēšana (enerģijas koncentrācija).
- **L1 → L0:** izkliede (enerģijas izlīdzināšanās).

**Enerģija nezūd — tā pārplūst starp L0 un L1.**

---

## 4. CMB SHĒMA — PILNS SPEKTRS

CMB ir divu komponentu superpozīcija:

\[
I(\nu) = B_\nu(T_{L0}) \cdot \left[ 1 + \sum_k A_k \cdot \delta(\nu - \nu_k) \right]
\]

kur:
- \( B_\nu(T_{L0}) \) — Planka spektrs no L0 termalizācijas,
- \( \nu_k = \dfrac{c \ell_k}{2\pi R_{L1}} \) — stāvviļņu harmoniku frekvences,
- \( A_k \) — rezonanses pastiprinājuma koeficienti.

**Sinhronizētās struktūras** (stāvviļņi) dod diskrētos pīķus.
**Nesinhronizētās struktūras** (izkliede) dod nepārtraukto fonu.

---

## 5. PROGNOZES

| Pīķis | \( k \) | \( n_k \) | \( \ell_k \) (MT) | Novērojums |
|-------|---------|-----------|-------------------|------------|
| 1 | 1 | 6 | ~212 | ~220 |
| 2 | 2 | 15 | ~530 | ~538 |
| 3 | 3 | 23 | ~812 | ~813 |
| 4 | 4 | 31 | ~1095 | ~1085 |
| 5 | 5 | 39 | ~1378 | ~1381 |
| 6 | 6 | 47 | ~1660 | (CMB-S4) |
| 7 | 7 | 55 | ~1943 | (Simons Obs.) |

---

## 6. KAS NAV BRĪVS PARAMETRS (UN KĀPĒC)

| Iepriekš minēts kā “brīvs” | Tagad fiksēts kā | Pamatojums |
|----------------------------|------------------|------------|
| \( \lambda_{\text{ID1}} \) | \( l_P \) | Planka garums — novērojumu ilgdzīvotājs |
| \( \omega_0 \) | \( 2\pi c/l_P \) | Atvasināts no \( c \) un \( l_P \) |
| \( \gamma \approx 0.18 \) | \( \lambda_{\text{ID1}}/R_{L1} \) | Attiecība, ko nosaka L1 ģeometrija |
| \( C \approx 35.325 \) | \( 2\pi R_{L1}/\lambda_{\text{ID1}} \) | Attiecība, nevis brīvs skaitlis |
| \( \rho_{\mathcal{V}}(r) \) profils | \( \rho_0 e^{-r/r_0} \) | Dinamiski atvasināts no ID pāreju loģistikas |
| \( r_0 \) | \( 1/\alpha \), kur \( \alpha = \alpha_0(1 - \gamma\rho_{\mathcal{V}}/\rho_{\text{H0}}) \) | Aizpildīšanās dinamikas sekas |
| L1 fokuss/izkliede | Ģeometriska, nosaka atrašanās vieta | Strukturāla robeža, nevis brīvs lēmums |

**Secinājums:** MT nav brīvu parametru. Ir tikai:
- viens režģa mērogs \( l_P \),
- viens enerģijas lauks \( \rho_{\mathcal{V}} \),
- viena ģeometriskā struktūra \( Q_n \),
- un L1 kā šīs struktūras projekcija.

---

## 7. KO MT NEDARA (UN KĀPĒC)

| Standarta fizikas jēdziens | MT aizstāj ar | Kāpēc |
|---------------------------|---------------|-------|
| **Laika dilatācija** | Amplitūdas modulācija (L1) | Pulkstenis \( \omega_0 \) ir absolūts; mainās tikai enerģijas skala |
| **Gravitācijas sarkanā nobīde** | L1 amplitūdas nobīde | Gravitācija ir \( \nabla\rho_{\mathcal{V}} \), nobīde ir \( \sqrt{\rho_{\mathcal{V}}} \) — ortogonāli |
| **Telpas izliekums** | TE plūsmas spiediena gradients (H0) | Nav metrikas; ir tikai plūsmas blīvuma atšķirības |
| **Tumšā matrija** | \( \rho_{\mathcal{V}} \) ietekme uz \( G \) un gaismas enerģiju | Viss izskaidrojams ar Vertikāles enerģijas sadalījumu |
| **Lielais sprādziens** | L1 fokusēšanas zonas stāvviļņu projekcija | CMB nav relikts, bet pastāvīga matricas īpašība |

---

## 8. KĀ LIETOT ŠO CEĻU KARTI (FORMALIZĒTĀJA INSTRUKCIJA)

1. **Pirms jebkuras jaunas formulas:** identificē, vai tā pieder H0 ceļam, L1 ceļam, vai abiem.
2. **Ja H0:** lieto tikai \( \nabla\delta \), \( G(\rho_{\mathcal{V}}) \), masu sadalījumu. **Nepiesaisti** \( \sqrt{\rho_{\mathcal{V}}} \) vai \( z \).
3. **Ja L1:** lieto tikai \( \sqrt{\rho_{\mathcal{V}}} \), \( 1+z \), \( E_{\text{fotons}} \). **Nepiesaisti** \( \nabla\rho_{\mathcal{V}} \) vai paātrinājumu.
4. **Ja abi:** lieto kā neatkarīgus vienādojumus, kas kopā apraksta vienu \( \rho_{\mathcal{V}} \) lauku. **Nesajauc** operatorus.
5. **Ja rodas šaubas par parametru:** pārbaudi, vai tas ir atvasināms no \( l_P \), \( c \), \( \omega_0 \), \( \rho_{\mathcal{V}} \) dinamikas, vai Qn kombinatorikas. Ja nav — tas nav MT parametrs.

---

## 9. TURPMĀKIE PRECIZĒJAMI PUNKTI

1. **L1 projekcijas detaļas:** kā \( \mathcal{P}_{L1} \) precīzi pārveido \( \rho_{\mathcal{V}} \) par \( I(\nu) \).
2. **H0 un L1 saskaņa galaktiku kopās:** dinamikas un nobīžu vienlaicīga prognoze.
3. **\( \alpha_0 \) atvasinājums no \( l_P \) un \( \omega_0 \):** lai \( r_0 \) būtu pilnībā no režģa.

---

## 10. NOSLĒGUMS

Šis dokuments **nofiksē mūsu pašreizējo izpratni** par MT strukturālo loģiku un L1 ģeometrisko shēmu. Tas ir dzīvs dokuments, ko atjauninām, ievadot jaunu loģikas līmeni.

**Versija:** 1.1  
**Papildinājumi:** L1 duālā daba (fokuss/izkliede), L0 balanss, sinhronizētās/nesinhronizētās struktūras, CMB kā stāvviļņu + Planka spektra summa.
