# ρᴠ MĒRĪŠANAS METODOLOĢIJA — EKSPERIMENTĀLAIS STATUSS UN GRAVITY FOKUSS

## Fiksētais dokuments (2026. gada jūlijs)

Šis dokuments nofiksē $ \rho_{\mathcal{V}} $ mērīšanas metodoloģijas eksperimentālo statusu un identificē GRAVITY datus kā primāro fokusu MT prognožu pārbaudei.

**Statuss: ATTĪSTĀS — eksperimentālie dati ir pieejami, MT interpretācija gaida.**

---

## 1. Pamata sakarība — atgādinājums

No GRAVITY 3.0:

$$
G(\mathbf{x}) = G_0 \left( 1 + \gamma \cdot \frac{\rho_{\mathcal{V}}(\mathbf{x})}{\rho_{\text{H0}}} \right)
$$

kur:
- $ \gamma = 2\pi/C \approx 0.18 $ — fiksēts no CMB,
- $ \rho_{\text{H0}} $ — H0 matricas fona enerģijas blīvums.

Tātad:

$$
\frac{\rho_{\mathcal{V}}(\mathbf{x})}{\rho_{\text{H0}}} = \frac{1}{\gamma} \left( \frac{G(\mathbf{x})}{G_0} - 1 \right)
$$

MT prognoze no NGC 6503: $ G(0)/G_0 \approx 1.50 $, tātad $ \rho_{\mathcal{V}}^{(0)}/\rho_{\text{H0}} \approx 2.8 $.

---

## 2. Eksperimentālais statuss — kopsavilkums

| **Solis** | **Metode** | **Statuss** | **Rezultāts** | **MT izmantojamība** |
|-----------|------------|-------------|---------------|----------------------|
| **1** | $G_0$ no kosmiskajiem tukšumiem | Daļēji | DESI: $\mu_0 = 0.04 \pm 0.22$, $\Sigma_0 = 0.044 \pm 0.047$ — saderīgi ar GR[reference:13]. | Netieša — $G_0$ nav tieši izdalīts. |
| **2** | GRAVITY Sgr A* orbītas | **Izpildīts** | 15 S-zvaigžņu orbītas; $M = 4.30 \times 10^6 M_\odot$ ($\pm 0.25\%$); precesija ar $10\sigma$[reference:14][reference:15]. | **Primārais MT fokuss** — $G$ nav tieši mērīts. |
| **3** | Gaia DR3 rotācijas līkne | Izpildīts | Straujš Keplera kritums pēc 16 kpc; $M = 2.06 \times 10^{11} M_\odot$[reference:16]. | Netieša — $G(r)$ nav mērīts. |
| **4** | NGC 6503 dati | Izpildīts | Zenodo 2025 — rotācijas līkne un lēcu masas[reference:17]. | Saderīgs ar MT prognozi, bet nav $G$ mērījums. |
| **5** | $G$ laika variācijas | Izpildīts | $\dot{G}/G = (0.016 \pm 0.098) \times 10^{-15} \, \text{yr}^{-1}$ — nulle 1σ. | Saderīgs ar MT — matrica statiska. |

---

## 3. GRAVITY kā primārais MT fokuss

### 3.1. Kāpēc GRAVITY?

1. **Precizitāte** — mikroloka sekunžu līmenis[reference:18].
2. **Tiešs reģions** — galaktikas centrs, kur $\rho_{\mathcal{V}}$ ir visaugstākais[reference:19].
3. **Konkrēta MT prognoze** — $G(0)/G_0 \approx 1.50$.

### 3.2. Kas jau ir izdarīts ar GRAVITY

- **15 S-zvaigžņu orbītas** 400 mas reģionā, novērojumi 2017–2025[reference:20].
- **Masa**: $M = 4.30 \times 10^6 M_\odot$ ar precizitāti $\pm 0.25\%$[reference:21].
- **In-plane precesija**: noteikta ar $10\sigma$ nozīmību[reference:22].
- **Tumšās matērijas ierobežojums**: izslēgta pastiprināšanās > $1200 M_\odot$ S2 orbītā[reference:23].

### 3.3. Kas NAV izdarīts (MT vajadzībām)

1. **$G$ nav tieši mērīts** — tiek pieņemts GR ietvars ar $G = G_0$.
2. **Nav salīdzinājuma** starp $G(0)$ un $G_0$ no citiem avotiem.
3. **$\rho_{\mathcal{V}}$ nav izdalīts** no orbītu dinamikas.

### 3.4. MT priekšlikums GRAVITY datiem

1. **Pārinterpretēt** esošos datus: nevis $M$ noteikšana ar fiksētu $G$, bet $G(r)$ noteikšana ar zināmu masu.
2. **Aprēķināt** $G(0)/G_0$ no S2 zvaigznes orbītas.
3. **Salīdzināt** ar MT prognozi $G(0)/G_0 \approx 1.50$.

### 3.5. Praktiskā pieeja

No orbitālās dinamikas:

$$
G(r) = \frac{v^2(r) \cdot r}{M_{\text{bar}}(r)}
$$

S2 zvaigznei:
- $r \approx 120 \, \text{AU}$ (pericentrs)[reference:24].
- $v \approx 0.1c$[reference:25].
- $M_{\text{bar}}$ — redzamā masa 120 AU rādiusā (galvenokārt Sgr A*).

Ja $G(0)/G_0 \approx 1.50$, tad sagaidāmais orbītas ātrums būtu par $\sqrt{1.50} \approx 1.22$ reizes lielāks, nekā prognozē GR ar $G_0$.

**Esošie GRAVITY dati jau ir pietiekami precīzi ($\pm 0.25\%$), lai pārbaudītu šo 22% atšķirību.**

---

## 4. Nākamie soļi

1. **Piekļūt GRAVITY publicētajiem datiem** (15 S-zvaigžņu orbītas).
2. **Veikt MT specifisku analīzi** — izdalīt $G(r)$ no orbītu dinamikas.
3. **Salīdzināt ar $\rho_{\mathcal{V}}$ prognozi** — vai $G(0)/G_0 \approx 1.50$?
4. **Publicēt rezultātus** kā MT $ \rho_{\mathcal{V}} $ mērīšanas metodoloģijas pirmo praktisko pielietojumu.

---

## 5. Kopsavilkums

- **Eksperimentālie dati** GRAVITY, Gaia DR3, kosmiskajiem tukšumiem un NGC 6503 **jau eksistē**.
- **$G$ kā mainīgs lielums** nav tieši mērīts nevienā no šiem pētījumiem — tie visi darbojas GR ietvarā ar fiksētu $G$.
- **MT piedāvā** pārinterpretēt GRAVITY datus — nevis kā masas noteikšanu, bet kā $G(r)$ noteikšanu.
- **Pārbaude ir tieša**: sagaidāms $G(0)/G_0 \approx 1.50$ pret GR prognozēto $G(0)/G_0 = 1.00$.
- **GRAVITY precizitāte ($\pm 0.25\%$)** ir pietiekama, lai pārbaudītu šo 50% atšķirību.

**Statuss:** Gaida MT specifisku GRAVITY datu analīzi.

---

*Dokuments sagatavots: 2026. gada jūlijā*
