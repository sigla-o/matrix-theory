# KOSMOLOĢIJA — MT FORMĀLAIS MODELIS
## Stingrā akadēmiskā versija

Kosmoloģiskā sarkanā nobīde MT tiek interpretēta kā divu neatkarīgu efektu superpozīcija, nevis telpas metrikas izplešanās.

---

## 1. H+n MODULĀCIJAS — FOTONA TRAJEKTORIJAS IZLIEKUMS

H+n modulācijas (10²⁵, 10⁴⁵, 10⁶⁵, 10⁸⁵ m) ir matricas strukturālas īpašības, kas rada liela mēroga TE plūsmas izliekumu. Fotons pārvietojas pa šo izliekto ģeodēzisko līniju. Izliekuma lielums pieaug lineāri ar attālumu, radot šķietamu "attālināšanās" efektu, ko klasiskā fizika interpretē kā telpas izplešanos.

---

## 2. VERTIKĀLES ENERĢIJAS B LĪVUMS — FOTONA ENERĢIJAS ZUDUMS

Vertikāles enerģijas blīvums \( \rho_{\mathcal{V}} \) darbojas kā matricas enerģētiskais fons. Fotons, ceļojot pa H0, mijiedarbojas ar šo fonu, zaudējot enerģiju:

\[
\frac{dE}{dx} = -\beta \cdot E \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}
\]

Šis zudums ir proporcionāls ceļa garumam un \( \rho_{\mathcal{V}} \) lokālajai vērtībai.

---

## 3. HABLA LIKUMS KĀ KOMBINĒTS PARAMETRS

Novērojamā Habla konstante:
\[
H_0 = \alpha_{\text{mod}} + \beta \cdot \left\langle \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \right\rangle
\]
- \( \alpha_{\text{mod}} \) — H+n modulāciju izliekuma koeficients.
- \( \beta \cdot \langle \rho_{\mathcal{V}}/\rho_{\text{H0}} \rangle \) — vidējais enerģijas zuduma devums.

\( H_0 \) nav universāla konstante; tā ir atkarīga no lokālā \( \rho_{\mathcal{V}} \) sadalījuma.

---

## 4. CMB — L1 ZONAS PROJEKCIJA

CMB nav Lielā sprādziena relikts. Tā ir L1 zonas stāvviļņu projekcija uz H0 matricu, ko nepārtraukti baro \( \rho_{\mathcal{V}} \).

**Projekcijas operators:**
\[
\mathcal{P}_{L1}: \mathcal{V} \to \mathcal{L}, \quad \mathcal{P}_{L1}(\rho_{\mathcal{V}}) = \sum_n c_n \delta(\mathbf{x} - \mathbf{x}_n)
\]

**Leņķiskās skalas:**
\[
\ell_k = C \cdot n_k, \quad C = \frac{2\pi R_{L1}}{\lambda_{\text{ID1}}} \approx 35.325, \quad n_k = 8k - 1 \ (k \ge 2), \ n_1 = 6
\]

**Prognozes 6. un 7. pīķim:**
\[
\ell_6 \approx 1660, \quad \ell_7 \approx 1943
\]
7. pīķa novirze no Planck datiem (+6.8%) tiek attiecināta uz Silka slāpēšanu un projekcijas fāžu nobīdi augstos \( \ell \); precīza pārbaude gaidāma ar CMB-S4 un Simons Observatory.

---

## 5. ENERĢIJAS AVOTS

CMB enerģija nav "iesaldēta" — tā ir nepārtraukta Vertikāles plūsma caur \( \mathcal{P}_{L1} \). Tādējādi CMB ir **stacionāra** matricas īpašība, nevis laikā mainīgs signāls.

---

## 6. PROGNOŽU TABULA

| Prognoze | Vienādojums | Pārbaude |
|----------|------------|----------|
| 6. CMB pīķis | \( \ell_6 = 1660 \) | CMB-S4 |
| 7. CMB pīķis | \( \ell_7 = 1943 \) | Simons Observatory |
| Habla konstantes atkarība | \( H_0 = \alpha_{\text{mod}} + \beta \langle \rho_{\mathcal{V}}/\rho_{\text{H0}} \rangle \) | Lokāli H₀ mērījumi |
| Fotona enerģijas zudums | \( dE/dx = -\beta E \rho_{\mathcal{V}}/\rho_{\text{H0}} \) | Tolmana tests |
