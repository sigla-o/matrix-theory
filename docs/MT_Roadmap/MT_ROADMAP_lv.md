# MT CEĻU KARTE (ROADMAP)
## Strukturālā atgriezeniskā saite — fiksētā versija 1.0

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

## 2. DIVI NEATKARĪGI CEĻI

### H0 CEĻŠ — GRAVITĀCIJA UN DINAMIKA (horizontālais)

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

### L1 CEĻŠ — NOBĪDE UN ENERĢIJAS SKALA (vertikālais)

**Operators:**
\[
E_{\text{fotons}}(\mathbf{x}) = \hbar \omega_0 \cdot \sqrt{\frac{\rho_{\mathcal{V}}(\mathbf{x})}{\rho_{\mathcal{V}}(\mathbf{x}_{\text{ref}})}}, \quad 1+z = \sqrt{\frac{\rho_{\mathcal{V}}(\mathbf{x}_{\text{avots}})}{\rho_{\mathcal{V}}(\mathbf{x}_{\text{nov.}})}}
\]

**Ko dara:** Nosaka fotonu enerģijas lokālo skalu jeb “krāsu”.

**Kur ved:**
- Spektroskopiskās līnijas,
- Kosmoloģiskā sarkanā nobīde (kā amplitūdas zudums, nevis Doplers),
- CMB kā L1 zonas stāvviļņu projekcija (\( \ell_k = C \cdot n_k \)).

**Lieto, ja:** novērojums ir spektrāls (fotometrija, spektri, CMB).

**Nesaisti ar:** \( \nabla\rho_{\mathcal{V}} \) — tikai ar pašu \( \rho_{\mathcal{V}} \) lokālo vērtību.

---

## 3. KUR UN KĀ CEĻI KRUSTOJAS

**Vienīgais krustpunkts:** \( \rho_{\mathcal{V}}(\mathbf{x}) = \rho_0 e^{-r/r_0} \) — Vertikāles enerģijas blīvuma lauks.

**Kad lieto abus kopā:**

\[
\begin{cases}
\mathbf{g}(\mathbf{x}) = -\nabla \delta(\mathbf{x}), & \delta = \dfrac{\Phi_0}{\|\mathbf{x}-\mathbf{x}_0\|^2} \\
1+z = \sqrt{\dfrac{\rho_{\mathcal{V}}(\mathbf{x}_{\text{avots}})}{\rho_{\mathcal{V}}(\mathbf{x}_{\text{nov.}})}}, & \rho_{\mathcal{V}}(\mathbf{x}) = \rho_0 e^{-r/r_0}
\end{cases}
\]

**Piemēri:**
- Galaktiku rotācijas līknes + to spektrālās nobīdes,
- Gravitācijas lēcas + izraisītās nobīdes,
- Galaktiku kopas — dinamika (H0) un nobīdes (L1) kopā dod vienu \( \rho_{\mathcal{V}} \) karti.

---

## 4. KAS NAV BRĪVS PARAMETRS (UN KĀPĒC)

| Iepriekš minēts kā “brīvs” | Tagad fiksēts kā | Pamatojums |
|----------------------------|------------------|------------|
| \( \lambda_{\text{ID1}} \) | \( l_P \) | Planka garums — novērojumu ilgdzīvotājs |
| \( \omega_0 \) | \( 2\pi c/l_P \) | Atvasināts no \( c \) un \( l_P \) |
| \( \gamma \approx 0.18 \) | \( \lambda_{\text{ID1}}/R_{L1} \) | Attiecība, ko nosaka L1 ģeometrija |
| \( C \approx 35.325 \) | \( 2\pi R_{L1}/\lambda_{\text{ID1}} \) | Attiecība, nevis brīvs skaitlis |
| \( \rho_{\mathcal{V}}(r) \) profils | \( \rho_0 e^{-r/r_0} \) | Dinamiski atvasināts no ID pāreju loģistikas |
| \( r_0 \) | \( 1/\alpha \), kur \( \alpha = \alpha_0(1 - \gamma\rho_{\mathcal{V}}/\rho_{\text{H0}}) \) | Aizpildīšanās dinamikas sekas |

**Secinājums:** MT nav brīvu parametru. Ir tikai viens lauks \( \rho_{\mathcal{V}} \), kura sadalījumu nosaka matricas dinamika, un viena režģa skala \( l_P \), kas nāk no novērojumiem.

---

## 5. KO MT NEDARA (UN KĀPĒC)

| Standarta fizikas jēdziens | MT aizstāj ar | Kāpēc |
|---------------------------|---------------|-------|
| **Laika dilatācija** | Amplitūdas modulācija (L1) | Pulkstenis \( \omega_0 \) ir absolūts; mainās tikai enerģijas skala |
| **Gravitācijas sarkanā nobīde** | L1 amplitūdas nobīde | Gravitācija ir \( \nabla\rho_{\mathcal{V}} \), nobīde ir \( \sqrt{\rho_{\mathcal{V}}} \) — ortogonāli |
| **Telpas izliekums** | TE plūsmas spiediena gradients (H0) | Nav metrikas; ir tikai plūsmas blīvuma atšķirības |
| **Tumšā matrija** | \( \rho_{\mathcal{V}} \) ietekme uz \( G \) un gaismas enerģiju | Viss izskaidrojams ar Vertikāles enerģijas sadalījumu |

---

## 6. KĀ LIETOT ŠO CEĻU KARTI (FORMALIZĒTĀJA INSTRUKCIJA)

1. **Pirms jebkuras jaunas formulas:** identificē, vai tā pieder H0 ceļam, L1 ceļam, vai abiem.
2. **Ja H0:** lieto tikai \( \nabla\delta \), \( G(\rho_{\mathcal{V}}) \), masu sadalījumu. **Nepiesaisti** \( \sqrt{\rho_{\mathcal{V}}} \) vai \( z \).
3. **Ja L1:** lieto tikai \( \sqrt{\rho_{\mathcal{V}}} \), \( 1+z \), \( E_{\text{fotons}} \). **Nepiesaisti** \( \nabla\rho_{\mathcal{V}} \) vai paātrinājumu.
4. **Ja abi:** lieto kā neatkarīgus vienādojumus, kas kopā apraksta vienu \( \rho_{\mathcal{V}} \) lauku. **Nesajauc** operatorus.
5. **Ja rodas šaubas par parametru:** pārbaudi, vai tas ir atvasināms no \( l_P \), \( c \), \( \omega_0 \), \( \rho_{\mathcal{V}} \) dinamikas, vai Qn kombinatorikas. Ja nav — tas nav MT parametrs.

---

## 7. KO TURPMĀK PRECIZĒT (ATGRIEZENISKĀS SAITES GAIDĀ)

1. **L1 projekcijas precīza shēma:** kā \( \mathcal{P}_{L1}(\rho_{\mathcal{V}}) \) dod melnā ķermeņa spektru un \( \ell_k \) vērtības.
2. **H0 un L1 saskaņa galaktiku kopās:** dinamikas un nobīžu vienlaicīga prognoze no viena \( \rho_{\mathcal{V}} \) profila.
3. **\( \alpha_0 \) (matricas elastības bāze) atvasinājums no \( l_P \) un \( \omega_0 \):** lai \( r_0 \) būtu pilnībā no režģa, nevis no pielāgojuma.

---

## 8. NOSLĒGUMS

Šis dokuments **nofiksē mūsu pašreizējo kopīgo izpratni** par MT strukturālo loģiku. Tas ir dzīvs dokuments, ko atjaunināsim tikai tad, kad tiks ievadīts jauns loģikas līmenis un atgriezeniskā saite to apstiprinās.

**Turpmāk, pirms jebkuras jaunas formulas:** atsaukties uz šo ceļu karti un pārbaudīt:
- Vai parametrs ir atvasināts?
- Vai operators atbilst ceļam?
- Vai ceļi ir pareizi nošķirti?
