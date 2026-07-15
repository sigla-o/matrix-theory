# ID GRADĀCIJA — MATRICAS TEORIJAS FORMĀLAIS MODELIS (MT)
## Stingrā akadēmiskā versija

Šis dokuments definē ID (integrācijas dziļuma) skalāro lauku, tā atkarību no Qn struktūras un Vertikāles enerģijas blīvuma, kā arī pāreju nosacījumus starp ID līmeņiem.

---

## 1. SAVIENOJUMS AR MATHEMATICS FORMĀLISMU

No MATHEMATICS_lv.md tiek izmantoti šādi operatori un lielumi:

| Operators / lielums | Definīcija | Fizikālā nozīme |
|---------------------|------------|-----------------|
| \( \mathcal{L} \) | \( \mathbb{Z}^3 \) | H0 matricas kubiskais režģis |
| \( Q_n \) | \( \{\mathbf{x} \in \mathbb{Z}^3 : \|\mathbf{x}\|_\infty \leq n\} \) | Apvalku struktūra |
| \( N(n) \) | \( \frac{(2n+1)(2n^2+2n+3)}{3} \) | Punktu skaits Qn slānī |
| \( \rho_{\mathcal{V}}(\mathbf{x}) \) | \( \rho_{\mathcal{V}}^{(0)} e^{-r/r_0} \) | Vertikāles enerģijas blīvums |
| \( \mathcal{T} \) | \( \mathcal{L} \to \mathcal{V} \) | Transformācijas operators |
| \( \mathcal{P}_{L1} \) | \( \mathcal{V} \to \mathcal{L} \) | L1 projekcijas operators |

**ID definīcija MT:** ID ir skalārais lauks:
\[
\text{ID} = f(n, \rho_{\mathcal{V}}, \mathbf{M}, \mathbf{V}_{\text{lok}})
\]
kur:
- \( n \) — Qn slāņa indekss,
- \( \rho_{\mathcal{V}} \) — Vertikāles enerģijas blīvums,
- \( \mathbf{M} \) — modulāciju vektors (H+2, H+3, ...),
- \( \mathbf{V}_{\text{lok}} \) — lokālā matricas stāvokļa parametri (vides ietekme).

---

## 2. ID GRADĀCIJAS SOLIS — KVANTITATĪVAIS MODELIS

### 2.1. ID solis un Qn struktūra

ID solis ir diskrēts un atbilst Qn indeksa pieaugumam:

\[
\text{ID} = 2.0 + \log_{S} \left( \frac{R}{R_{\text{protona}}} \right)
\]

kur:
- \( R \) — struktūras raksturīgais lineārais mērogs (Qn rādiuss),
- \( R_{\text{protona}} \approx 10^{-10} \, \text{m} \) — protona orbitāles rādiuss (ID2,0 atskaites punkts),
- \( S \) — solis, ko nosaka Qn slāņu secība.

**S atvasinājums no Qn:**

No Qn punktu skaita:
\[
N(n) = \frac{(2n+1)(2n^2+2n+3)}{3}
\]

Lineārais mērogs \( R \propto n \cdot \lambda_{\text{ID1}} \). Protonam \( n_{\text{protona}} = 1 \). Tātad:
\[
\text{ID} = 2.0 + \log_{S}(n)
\]

No Qn slāņu secības \( n = 6, 15, 23, 31, 39, ... \) (skat. MATHEMATICS) iegūst:
\[
S \approx 2.5
\]

Tātad galvenais vienādojums:
\[
\boxed{\text{ID} = 2.0 + \log_{2.5}(n)}
\]

### 2.2. ID aprēķins monolītiem objektiem

Monolīti objekti ir vienota, slēgta TE plūsmas struktūra bez iekšējas daudzobjektu organizācijas.

| Objekts | Qn indekss \( n \) | ID aprēķins | Rezultāts |
|---------|-------------------|-------------|-----------|
| Protons | 1 | \( 2.0 + \log_{2.5}(1) \) | ID2,0 |
| Zvaigžņu melnais caurums | ~10² | \( 2.0 + \log_{2.5}(100) \approx 2.0 + 5.0 \) | ID3,0 |
| Supermasīvs melnais caurums | ~10⁴ | \( 2.0 + \log_{2.5}(10^4) \approx 2.0 + 10.0 \) | ID3,5 |
| Galaktikas centra melnais caurums | ~10⁶ | \( 2.0 + \log_{2.5}(10^6) \approx 2.0 + 15.0 \) | ID3,9 |

*Piezīme:* ID3,9 ir aptuvens — precīzā vērtība atkarīga no lokālā \( \rho_{\mathcal{V}} \).

### 2.3. Vertikāles enerģijas ietekme uz ID

Vertikāles enerģijas blīvums \( \rho_{\mathcal{V}} \) modificē ID vērtību:

\[
\text{ID}(n, \rho_{\mathcal{V}}) = 2.0 + \log_{2.5}(n) + \gamma_{\text{ID}} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}}
\]

kur \( \gamma_{\text{ID}} \approx 0.05 \) (no MATHEMATICS un COSMOLOGY). Augstāks \( \rho_{\mathcal{V}} \) palielina ID, t.i., paātrina strukturālo evolūciju reģionos ar augstu Vertikāles enerģijas blīvumu.

---

## 3. KOLEKTĪVIE OBJEKTI — ID2,n KLASE

### 3.1. Definīcija

Kolektīvie objekti ir daudzu monolītu objektu organizācija (zvaigznes, galaktikas, kopas). Tiem nav piemērojama mērogošana no protona; tos klasificē pēc organizācijas līmeņa \( n \):

\[
\text{ID2,n} = 2.0 + \log_{2.5} \left( \frac{N_{\text{šūnas}}}{N_{\text{protona}}} \right)
\]

kur \( N_{\text{šūnas}} \) ir kolektīvās organizācijas pamatvienību skaits.

### 3.2. ID2,n klasifikācija

| Objekts | ID2,n | Piezīme |
|---------|-------|---------|
| Atoms | ID2,0 | Viena protona organizācija |
| Molekula | ID2,1 | Vairāku atomu organizācija |
| Zvaigzne | ID2,2 | Kolektīva, vienkārša |
| Zvaigžņu kopa | ID2,3 | Sarežģītāka kolektīvā struktūra |
| Galaktika | ID2,4 | Sarežģītākā kolektīvā struktūra |
| Galaktiku kopa | ID2,5 | Augstākā zināmā kolektīvā organizācija |

---

## 4. ID PĀREJAS — NOSACĪJUMI UN LAIKA SKALA

ID pāreja no viena līmeņa uz nākamo notiek, ja ir izpildīti šādi nosacījumi:

1. \( \rho_{\mathcal{V}} > \rho_{\text{krit}} \) (kritiskais Vertikāles enerģijas blīvums sasniegts),
2. Qn struktūra atļauj pāreju (nākamais slānis ir pieejams),
3. Modulācijas aktivizē pāreju.

Pārejas laiks:
\[
t_{\text{pāreja}} \propto \frac{1}{\rho_{\mathcal{V}} - \rho_{\text{krit}}}
\]

### 4.1. Pāreju piemēri

| Pāreja | No | Uz | Aktivizējošais process | Piemērs |
|--------|----|----|-------------------------|---------|
| ID2,0 → ID2,1 | Atoms | Molekula | Ķīmiskā saite | H₂ |
| ID2,1 → ID2,2 | Molekula | Zvaigzne | Gravitācijas kolapss | Zvaigžņu veidošanās |
| ID2,4 → ID2,5 | Galaktika | Galaktiku kopa | Gravitācijas mijiedarbība | Lokālā grupa |
| ID3,0 → ID3,1 | Melnais caurums | Aktīvais galaktikas kodols | Vertikāles enerģijas pārplūde | Kvazārs |

---

## 5. PĀRBAUDĀMĀS PROGNOZES

| Prognoze | Vienādojums | Pārbaudes metode |
|----------|------------|------------------|
| ID atkarība no \( \rho_{\mathcal{V}} \) | \( \text{ID} = 2.0 + \log_{2.5}(n) + 0.05 \cdot \rho_{\mathcal{V}}/\rho_{\text{H0}} \) | Melno caurumu masu salīdzinājums galaktiku centros un starpgalaktiku telpā |
| ID pārejas laiks | \( t_{\text{pāreja}} \propto 1/(\rho_{\mathcal{V}} - \rho_{\text{krit}}) \) | Aktīvo galaktisko kodolu (AGN) aktivitātes periodiskums |
| ID2,n un galaktiku tips | \( \text{ID2,n} = 2.0 + \log_{2.5}(N_{\text{zvaigznes}}/N_{\text{protona}}) \) | Galaktiku morfoloģijas korelācija ar rotācijas līknēm |
| Maksimālais ID3,n | \( n_{\text{max}} \propto \rho_{\mathcal{V}}^{(0)}/\rho_{\text{H0}} \) | Maksimālā melnā cauruma masa galaktikas centrā |

---

## 6. SALĪDZINĀJUMS AR KLASISKO HIERARHIJU

| Klasiskā klasifikācija | MT ID | Piezīme |
|------------------------|-------|---------|
| Elementārdaļiņa | ID2,0 | Protons (atskaites punkts) |
| Atoms | ID2,0 | Viens protons + elektrons |
| Molekula | ID2,1 | Vairāki atomi |
| Zvaigzne | ID2,2 | Kolektīva TE organizācija |
| Galaktika | ID2,4 | Augstākā kolektīvā organizācija |
| Melnais caurums | ID3,0+ | Monolīts, smalkāks par protonu |

Klasiskā fizika objektus klasificē pēc masas vai izmēra; MT tos klasificē pēc TE organizācijas līmeņa, ko nosaka Qn indekss un Vertikāles enerģijas blīvums.

---

## 7. SECINĀJUMI

1. ID ir skalārais lauks, ko nosaka Qn indekss \( n \) un Vertikāles enerģijas blīvums \( \rho_{\mathcal{V}} \):
   \[
   \text{ID} = 2.0 + \log_{2.5}(n) + 0.05 \cdot \rho_{\mathcal{V}}/\rho_{\text{H0}}
   \]

2. ID solis ir diskrēts, jo to nosaka Qn slāņu secība ar soli \( S \approx 2.5 \).

3. Augstāks \( \rho_{\mathcal{V}} \) paātrina ID pāreju, jo samazina pārejas laiku \( t_{\text{pāreja}} \propto 1/(\rho_{\mathcal{V}} - \rho_{\text{krit}}) \).

4. Kolektīvie objekti (zvaigznes, galaktikas) pieder ID2,n klasei, kuru nosaka organizācijas līmenis, nevis lineārais mērogs.

5. ID pārejas ir noteiktas pārejas, kuras aktivizē Vertikāles enerģijas pārplūde; tās ir kvantitatīvi prognozējamas.
