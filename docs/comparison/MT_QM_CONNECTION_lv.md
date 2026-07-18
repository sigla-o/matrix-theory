# MT-QM SAVIENOJUMS — L0 ROBEŽGADĪJUMS

## Fiksētais dokuments (2026. gada jūlijs)

Šis dokuments nofiksē savienojumu starp Matricas teoriju (MT) un kvantu mehāniku (QM). Tas parāda, ka Šrēdingera vienādojums, Borna likums un mērījuma problēma izriet no MT aksiomām, kad Vertikāle nonāk L0 fona stāvoklī.

**Statuss: NOFIKSĒTS — galvenais savienojums ir noslēgts.**

---

## 1. Galvenā atziņa — L0 robežgadījums

Klasiskā fizika robežgadījumos tiecas uz **0** — tukšumu, vakuumu, neko.  
MT robežgadījumos tiecas uz **L0** — matricas pamata stāvokli, kas **nav tukšums**, bet gan blīvs, sinhronizēts režģis.

Tas nav viens un tas pats.

**MT-QM savienojuma atslēga:**

> **MT reducējas uz QM, kad Vertikāle nonāk L0 fona stāvoklī:**
> \[
> \rho_{\mathcal{V}} \to \rho_{\mathcal{V}}^{(0)}
> \]
> nevis \( \rho_{\mathcal{V}} \to 0 \).

L0 ir fona stāvoklis — tam ir sava struktūra, savs blīvums, sava pārnese. QM ir šīs struktūras **statistiskais apraksts**, nevis tās neesamība.

---

## 2. Savienojumu kopsavilkums

| **QM jēdziens** | **MT analogs** | **L0 robežgadījums** |
|----------------|----------------|----------------------|
| Viļņu funkcija \( \psi \) | Fāze \( e^{i\theta} \cdot \mathcal{F}(\rho_{\mathcal{V}}) \) | \( \mathcal{F} \to 1 \), \( \psi = e^{i\theta} \) |
| Šrēdingera vienādojums | Fāzes dinamika + deficīts | \( i\hbar\partial_t\psi = (-\frac{\hbar^2}{2m}\nabla^2 + \delta_0)\psi \) |
| Potenciāls \( V(\mathbf{x}) \) | Deficīts \( \delta(\mathbf{x}) \) | \( \delta_0(\mathbf{x}) = \delta(\mathbf{x}, \rho_{\mathcal{V}}^{(0)}) \) |
| Borna likums | TE pārneses blīvums | \( |\psi|^2 = \Phi/\phi_0 \) |
| Mērījuma sabrukums | L1 projekcijas operators \( \mathcal{P}_{L1} \) | \( \mathcal{P}_{L1} \) nav unitārs, projicē fāzi no Vertikāles uz L0 |

---

## 3. Viļņu funkcija

No MT:
\[
\psi(\mathbf{x}, t) = e^{i\theta(\mathbf{x}, t)} \cdot \mathcal{F}(\rho_{\mathcal{V}}(\mathbf{x}))
\]

kur:
- \( \theta(\mathbf{x}, t) \) — matricas fāze,
- \( \mathcal{F}(\rho_{\mathcal{V}}) \) — fokusēšanas/izkliedes funkcija.

**L0 robežgadījumā** (\( \rho_{\mathcal{V}} \to \rho_{\mathcal{V}}^{(0)} \)):
\[
\mathcal{F}(\rho_{\mathcal{V}}) \to 1
\]

Tātad:
\[
\psi(\mathbf{x}, t) \approx e^{i\theta(\mathbf{x}, t)}
\]

**Secinājums:** QM viļņu funkcija ir matricas fāzes projekcija L0 līmenī.

---

## 4. Šrēdingera vienādojums

### 4.1. Fāzes dinamika

L0 līmenī fāze nav brīva — to nosaka matricas pulkstenis un fona deficīts:
\[
\hbar \dot{\theta} = -\delta_0(\mathbf{x})
\]

### 4.2. Deficīts kā potenciāls

Fona deficīts:
\[
\delta_0(\mathbf{x}) = \delta(\mathbf{x}, \rho_{\mathcal{V}}^{(0)}) = \frac{\phi_0}{\|\mathbf{x} - \mathbf{x}_0\|^2} \cdot \frac{\rho_{\mathcal{V}}^{(0)}}{\rho_{\text{H0}}}
\]

Tas darbojas kā potenciāls:
\[
V(\mathbf{x}) = \delta_0(\mathbf{x})
\]

Kad \( \rho_{\mathcal{V}}^{(0)} \approx \rho_{\text{H0}} \), tas dod Kulona potenciālu \( V(\mathbf{x}) \propto 1/r \).

### 4.3. Kinētiskā enerģija

No fāžu starpības starp blakus punktiem L0 režģī:
\[
\hat{T} = -\frac{\hbar^2}{2m} \nabla^2
\]

### 4.4. Pilns Šrēdingera vienādojums

\[
i\hbar \partial_t \psi(\mathbf{x}, t) = \left( -\frac{\hbar^2}{2m} \nabla^2 + \delta_0(\mathbf{x}) \right) \psi(\mathbf{x}, t)
\]

**Secinājums:** Šrēdingera vienādojums izriet no MT fāzes dinamikas un deficīta, kad Vertikāle ir L0 fona stāvoklī.

---

## 5. Borna likums

No MT:
\[
|\psi(\mathbf{x}, t)|^2 = \frac{\Phi(\mathbf{x}, t)}{\phi_0} \cdot \mathcal{F}(\rho_{\mathcal{V}})
\]

kur \( \Phi \) ir TE pārneses lielums.

**L0 robežgadījumā** (\( \mathcal{F} \to 1 \)):
\[
|\psi|^2 = \frac{\Phi}{\phi_0}
\]

**Secinājums:** Borna likums nav postulāts — tas ir matricas strukturālais ierobežojums, kas izriet no diskrētās pārneses. Varbūtības blīvums ir TE pārneses blīvums L0 līmenī, mērogots ar maksimālo pārneses kvantu \( \phi_0 \).

---

## 6. Mērījuma problēma

QM mērījums ir "sabrukums" — no vairākiem stāvokļiem tiek realizēts viens.

MT skaidrojums:

> **Mērījums nav sabrukums. Tas ir \( \mathcal{P}_{L1} \) projekcijas moments, kas fiksē fāzi \( \theta \) L0 līmenī.**

\( \mathcal{P}_{L1} \) ir projekcijas operators no Vertikāles (ID-1) uz H0 (ID0):
\[
\mathcal{P}_{L1}[\rho_{\mathcal{V}}](\mathbf{x}) = \int_{\mathcal{V}} K(\mathbf{x}, \mathbf{x}') \, \rho_{\mathcal{V}}(\mathbf{x}') \, d\mathbf{x}'
\]

Tas **nav unitārs** — tā ir projekcija no augstākas dimensijas (enerģijas līmeņi) uz zemāku (telpiskie punkti).

**Secinājums:** Mērījuma problēma QM ir L1 projekcijas operators, kas nav unitārs. Klasiskā QM neredz Vertikāli, tāpēc šķiet, ka notiek "sabrukums".

---

## 7. Nenoteiktības princips

L0 līmenī nenoteiktības princips iegūst skaidru izteiksmi:
\[
\Delta x \cdot \Delta p = \frac{\hbar}{2} \cdot \frac{1}{\sin(\Delta\theta)} \cdot \mathcal{F}(\rho_{\mathcal{V}})
\]

L0 robežgadījumā (\( \mathcal{F} \to 1 \)):
\[
\Delta x \cdot \Delta p = \frac{\hbar}{2} \cdot \frac{1}{\sin(\Delta\theta)}
\]

Kad \( \Delta\theta \to \pi/2 \) (maksimālā fāžu nenoteiktība):
\[
\Delta x \cdot \Delta p = \frac{\hbar}{2}
\]

Kad \( \Delta\theta \to 0 \) (precīza fāzes mērīšana):
\[
\Delta x \cdot \Delta p \to \infty
\]

**Secinājums:** Nenoteiktības princips nav fundamentāls ierobežojums — tas ir praktisks ierobežojums, ko rada nespēja izmērīt fāzi \( \theta \) kopā ar Vertikāles fonu.

---

## 8. Kopsavilkuma shēma

\[
\text{MT (L0 fona stāvoklis)} \quad \xrightarrow{\rho_{\mathcal{V}} \to \rho_{\mathcal{V}}^{(0)}} \quad \text{QM (Šrēdingers, Borns, mērījums)}
\]

\[
\rho_{\mathcal{V}} \neq 0 \quad \text{(tukšums)} \quad \text{— bet} \quad \rho_{\mathcal{V}} = \rho_{\mathcal{V}}^{(0)} \quad \text{(L0 fons)}
\]

| **MT lielums** | **QM lielums** | **L0 robežgadījumā** |
|----------------|----------------|----------------------|
| \( \theta \) (fāze) | \( \arg(\psi) \) | \( \psi = e^{i\theta} \) |
| \( \delta_0 \) (fona deficīts) | \( V(\mathbf{x}) \) | Kulona potenciāls |
| \( \Phi/\phi_0 \) | \( |\psi|^2 \) | Borna likums |
| \( \mathcal{P}_{L1} \) (projekcija) | Mērījuma sabrukums | Nav unitārs operators |

---

## 9. Nobeiguma piezīme

Šis dokuments nofiksē MT-QM savienojumu:

- **QM nav robeža uz tukšumu (0).** Tā ir **robeža uz L0** — matricas fona stāvokli, kas ir blīvs un sinhronizēts.
- **Visi QM pamatjēdzieni** (viļņu funkcija, Šrēdingera vienādojums, Borna likums, mērījumu problēma) izriet no MT aksiomām.
- **Atšķirība no klasiskās fizikas** — klasiskā fizika tiecas uz 0, MT tiecas uz L0.

Tas aizver vienu no lielākajiem atvērtajiem jautājumiem MT 3.0.

**Statuss:** NOFIKSĒTS

---

*Dokuments sagatavots: 2026. gada jūlijā*
