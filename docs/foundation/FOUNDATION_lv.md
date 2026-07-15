# PAMATS — MATRICAS TEORIJAS FORMĀLAIS IETVARS (MT)
## Stingrā akadēmiskā versija

Šis dokuments nosaka MT darbības robežas, pamatoperatorus un Visuma evolūcijas deterministiskos principus.

---

## 1. DARBĪBAS ROBEŽAS

MT apraksta vienas Vertikāles enerģijas cikla pārejas starp Horizontālēm. Darbības diapazons aptver skalas no \(10^{-115}\) m līdz \(10^{105}\) m — praktisks teorijas pielietojuma intervāls, ko nosaka Qn struktūras izšķirtspējas un H+n modulāciju periodu attiecība.

Jautājums par Vertikāļu skaitu Mūžībā un to savstarpējo organizāciju nav MT priekšmets.

---

## 2. PAMATOPERATORI UN LIELUMI

| Operators / lielums | Definīcija | Fizikālā nozīme |
|---------------------|------------|-----------------|
| \( \mathcal{L} \) | \( \mathbb{Z}^3 \) | H0 matricas kubiskais režģis |
| \( Q_n \) | \( \{\mathbf{x}: \|\mathbf{x}\|_\infty \leq n\} \) | Apvalku struktūra ar \( |Q_n| = \frac{(2n+1)(2n^2+2n+3)}{3} \) |
| \( \Phi(\mathbf{x},\mathbf{y}) \) | \( \mathcal{L} \times \mathcal{L} \to \mathbb{R}^+ \) | TE plūsmas lauks, definēts uz režģa malām |
| \( \rho_{\mathcal{V}}(\mathbf{x}) \) | \( \rho_{\mathcal{V}}^{(0)} e^{-r/r_0} \) | Vertikāles enerģijas blīvuma profils |
| \( \mathcal{T} \) | \( \mathcal{L} \to \mathcal{V} \) | Transformācijas operators (H0 → Vertikāle) |
| \( \mathcal{P}_{L1} \) | \( \mathcal{V} \to \mathcal{L} \) | L1 zonas projekcijas operators |
| \( \gamma \) | \( \lambda_{\text{ID1}}/R_{L1} \approx 0.18 \) | G mainības konstante (no režģa ģeometrijas) |
| \( C \) | \( 2\pi R_{L1}/\lambda_{\text{ID1}} \approx 35.325 \) | CMB projekcijas konstante |

---

## 3. VERTIKĀLE UN HORIZONTĀLES — STRUKTURĀLĀS ATTIECĪBAS

**Vertikāle** \( \mathcal{V} \) ir enerģijas līmeņu kopa:
\[
\mathcal{V} = \{ E_{H-3}, E_{H-4}, \dots, E_{H-\text{min}} \}, \quad E_{\mathcal{V}} = \sum_{k=3}^{\text{min}} E_{H-k}
\]
Tā uztur nepārtrauktu enerģijas plūsmu uz H0 matricu caur \( \mathcal{P}_{L1} \).

**Horizontāle** \( H_n \) ir stabilo enerģijas vienību matrica, kurā notiek diskrēta evolūcija pa ID līmeņiem. H0 ir viena no Horizontālēm.

**Mūžības ciklu** raksturo periodisks enerģijas pārneses operators starp Vertikāli un Horizontālēm; šī cikla sākums vai beigas netiek definēti.

---

## 4. H0 EVOLŪCIJA — KVANTITATĪVAIS MODELIS

H0 evolūcija ir secīgu telpas paplašināšanās soļu virkne, ko aktivizē Vertikāles enerģijas blīvuma kritiskā vērtība:

1. ID1 — rotējošs režģa punkts (fāzes avots).
2. ID2,0 — pirmā protona struktūra.
3. ID2,n — atomi, molekulas, zvaigznes.
4. ID3,0 — pirmais melnais caurums (no supernovas kolapsa).
5. ID3,n — melno caurumu evolūcija un sekojoši telpas izplešanās notikumi.

**Telpas paplašināšanās solis** notiek, kad \( \rho_{\mathcal{V}} > \rho_{\text{krit}} \). Pārejas laiks:
\[
t_{\text{paplašināšanās}} \propto \frac{1}{\rho_{\mathcal{V}} - \rho_{\text{krit}}}
\]

Sekas:
- Izveidojas jauna Qn TE plūsmas struktūra, kas nav saderīga ar iepriekšējo.
- Tiek pārrautas iepriekšējās molekulārās saites.
- Zvaigžņu paliekas kļūst par Oorta mākoņiem, kuru centros atsākas zvaigžņu veidošanās.

---

## 5. L1 ZONA UN CMB — OPERACIONĀLĀ INTERPRETĀCIJA

**L1 zona** ir operators \( \mathcal{P}_{L1} \), kas pārveido Vertikāles enerģijas blīvumu \( \rho_{\mathcal{V}} \) par H0 matricai saderīgām TE plūsmām.

**CMB** ir L1 zonas stāvviļņu projekcija uz H0:
- Vidējā temperatūra 2.725 K — L1 zonas termālā ekvivalenta projekcija.
- 5 harmonikas (\( \ell \approx 220, 538, 813, 1085, 1381 \)) atbilst Qn slāņu indeksiem \( n_k = 8k - 1 \) (k ≥ 2), \( n_1 = 6 \).
- Enerģijas avots ir nepārtraukta \( \rho_{\mathcal{V}} \) plūsma, nevis "iesaldēta" enerģija.

---

## 6. MATRICES ARHITEKTŪRA — STATISKĀ, ENERĢĒTISKI DINAMISKĀ

Matricas (H0) ģeometrija (ID1 režģis, Qn, FV cikli) ir statiska. Tās enerģētiskais saturs nosaka:
- Vertikāles piramīda \( \rho_{\mathcal{V}} \),
- H+n modulācijas (liela mēroga plūsmas struktūra).

Fotons ir brīvās TE plūsmas veidojums (VEU H-2 × H-3), kura enerģijas zudumu ceļojumā caur Vertikāles lauku apraksta:
\[
\frac{dE}{dx} = -\beta \cdot E \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}
\]

---

## 7. PROGNOŽU KOPSAVILKUMS

| Prognoze | Vienādojums | Pārbaude |
|----------|------------|----------|
| Smalkās struktūras konstante | \( \alpha = \frac{49 G_0}{24\pi \hbar c} \) | Spektroskopija |
| G mainība galaktiku centros | \( G(r) = G_0(1 + 0.18 \rho_{\mathcal{V}}/\rho_{\text{H0}}) \) | Zvaigžņu orbītas (GRAVITY) |
| 6. CMB pīķis | \( \ell_6 = 35.325 \times 47 \approx 1660 \) | CMB-S4 |
| 7. CMB pīķis | \( \ell_7 = 35.325 \times 55 \approx 1943 \) | CMB-S4 |
