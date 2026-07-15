# KVANTU MEHĀNIKA — SALĪDZINĀJUMS AR MT
## Stingrā akadēmiskā versija

Šis dokuments salīdzina klasiskās kvantu mehānikas un MT interpretācijas, izmantojot tikai operacionālus terminus.

---

## 1. VIĻŅU–DAĻIŅU DUĀLISMS

**Klasiskā QM**: duālisms tiek uzskatīts par fundamentālu.

**MT**: daļiņa (protons, elektrons) atbilst slēgtai TE plūsmas cilpai; vilnis atbilst atvērtai TE plūsmai. Šī atšķirība ir strukturāla, nevis ontoloģiska — to nosaka plūsmas cirkulācijas robežnosacījumi.

---

## 2. VIĻŅU FUNKCIJA UN BORNA LIKUMS

**Klasiskā QM**: \( \psi \) ir varbūtības amplitūda, \( |\psi|^2 \) — varbūtības blīvums.

**MT**: \( \psi(\mathbf{x}, t) \sim e^{i\theta(\mathbf{x}, t)} \), kur \( \theta \) ir ID1 fāze. \( |\psi|^2 \) ir TE plūsmas blīvuma projekcija:

\[
|\psi|^2 = \frac{\Phi(\mathbf{x}, t)}{\Phi_0}
\]

Borna likums izriet no matricas strukturālā ierobežojuma — plūsma ir diskrēta un tās blīvums izsakāms tikai kā kvadrātiskā forma.

---

## 3. SUPERPOZĪCIJA UN INTERFERENCE

**Klasiskā QM**: lineārā kombinācija.

**MT**: Superpozīcija atbilst TE plūsmas sadalījumam pa vairākiem Qn kanāliem. Interference rodas no fāžu starpības:

\[
\psi_{\text{tot}} = \sum_i e^{i\theta_i} \cdot \Phi_i
\]

L0 fona klātbūtne nodrošina kanālu koherenci.

---

## 4. MĒRĪJUMA PROBLĒMA

**Klasiskā QM**: viļņu funkcijas sabrukums.

**MT**: Mērījums ir fāzes atlases operators \( \mathcal{P}_{L1} \), kas fiksē \( \theta \) vērtību noteiktā Qn punktā. Sabrukuma nav — notiek projekcija uz L1 zonu.

---

## 5. NENOTEIKTĪBAS PRINCIPS

**Klasiskā QM**: \( \Delta x \cdot \Delta p \geq \hbar/2 \), fundamentāls.

**MT**: Pozīcija (Qn) un impulss (FV) ir savstarpēji ortogonālas koordinātes. Ja fāze \( \theta \) ir zināma ar precizitāti \( \Delta \theta \):

\[
\Delta x \cdot \Delta p = \frac{\hbar}{2} \cdot \frac{1}{\sin(\Delta \theta)}
\]

Pie \( \Delta \theta \to 0 \) nenoteiktība izzūd — tā ir mērierīces izšķirtspējas, nevis fundamentāla īpašība.

---

## 6. SAPĪŠANĀS

**Klasiskā QM**: nelokāla korelācija.

**MT**: divi sapīšanās tipi:
- **1. tips** — caur kopīgu Qn struktūru, izplatās ar gaismas ātrumu.
- **2. tips** — caur TZ–Vertikāle–TZ, momentāna, bet bez signāla pārraides (impulsa pārnese).

---

## 7. KVANTU STATISTIKA

| Objekts | TZ klātbūtne | Slēgta TE cilpa | Bilance | Statistika |
|---------|--------------|------------------|---------|------------|
| Protons | Jā | Jā | Jā | Fermions |
| Elektrons | Nē | Jā | Jā | Fermions |
| Neitrīno | Nē | Jā (H-3×H-4) | Jā | Fermions |
| Fotons | Nē | Nē | Nav | Bozons |

Statistiku nosaka organizācijas struktūra, nevis spins.

---

## 8. PROGNOZES

| Prognoze | MT vienādojums | Atšķirība no QM | Pārbaude |
|----------|---------------|-----------------|----------|
| Determinisms pie fāzes mērīšanas | \( \Delta x \Delta p = \hbar/2 \cdot 1/\sin(\Delta\theta) \) | Nenoteiktība izzūd | Fāzes mērīšana |
| Sapīšanās 2. tips | \( \mathcal{T}(\Omega_1) = \mathcal{T}(\Omega_2) \) | Momentāna, bez signāla | Bella testi ar laika atzīmēm |
