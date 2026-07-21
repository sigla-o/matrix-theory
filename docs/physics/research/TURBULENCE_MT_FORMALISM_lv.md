# TURBULENCE — MT FORMĀLAIS MODELIS

## Diskrētā enerģijas pārplūde pa Qn slāņiem

**Versija: 1.0 (2026. gada jūlijs)**  
**Statuss: NOFIKSĒTS — formālais modelis**

---

## 1. IEVADS

Klasiskā turbulence ir neatrisināta, jo tā balstās uz nepareizu pieņēmumu — ka gāzu/šķidrumu plūsma ir primāra. MT turbulence ir **enerģijas pārplūde starp EM karkasu (VEU H-2/H-3) un inerciālo plūsmu**, kas notiek pa diskrētiem Qn slāņiem.

Šis dokuments sniedz **formālo MT turbulence modeli** — operatoru secību, kas apraksta enerģijas pārplūdi, spektru un pārejas nosacījumus.

---

## 2. PAMATDEFINĪCIJAS

### 2.1. Qn struktūra

Qn ir diskrētu enerģijas līmeņu secība:

\[
n_k = 8k - 1, \quad k = 1, 2, 3, \dots
\]

Katrs Qn slānis \( n \) satur noteiktu enerģijas daudzumu un kanālu skaitu:

\[
N(n) = \frac{(2n+1)(2n^2+2n+3)}{3}
\]

### 2.2. EM enerģijas blīvums

EM enerģijas blīvums Qn slānī \( n \):

\[
u_{\text{EM}, n} = \mathcal{P}_{L1}[\rho_{\mathcal{V}}] \cdot \frac{\Phi_n}{\phi_0} \cdot \frac{1}{N(n)}
\]

kur:
- \( \mathcal{P}_{L1}[\rho_{\mathcal{V}}] \) — L1 projekcijas operators,
- \( \Phi_n \) — TE plūsmas blīvums slānī \( n \),
- \( \phi_0 = \hbar c/l_P \) — maksimālais pārneses kvants.

### 2.3. Inerciālās enerģijas blīvums

Inerciālās plūsmas kinētiskā enerģija Qn slānī \( n \):

\[
u_{\text{kin}, n} = \frac{1}{2} \rho_n v_n^2
\]

kur:
- \( \rho_n \) — blīvums slānī \( n \),
- \( v_n \) — plūsmas ātrums.

---

## 3. BILANCE UN TRAUCĒJUMS

### 3.1. Līdzsvara nosacījums

Līdzsvara stāvoklī:

\[
u_{\text{EM}, n} = u_{\text{kin}, n}
\]

### 3.2. Bilances traucējums

Traucējums rodas, kad \( u_{\text{kin}, n} \) palielinās:

\[
\Delta u_n = u_{\text{kin}, n} - u_{\text{EM}, n}
\]

### 3.3. Kritiskais slieksnis

Pārejas nosacījums:

\[
\Delta u_n > \Delta u_{\text{krit}, n}
\]

kur:

\[
\Delta u_{\text{krit}, n} = \frac{\phi_0}{N(n)} \cdot \frac{\rho_{\mathcal{V}}}{\rho_{\text{H0}}} \cdot \alpha
\]

un \( \alpha = 6\omega_0/7 \) — matricas elastība.

---

## 4. PĀRPLŪDES OPERATORS

Kad \( \Delta u_n > \Delta u_{\text{krit}, n} \), enerģijas pārpalikums tiek nodots uz nākamo slāni:

\[
\Delta u_{n \to n+1} = \alpha \cdot \Delta u_n \cdot \mathcal{F}_n
\]

kur:
- \( \mathcal{F}_n \) — fokusēšanas/izkliedes funkcija:

\[
\mathcal{F}_n = 
\begin{cases}
1, & n \leq n_{\text{max}} \\
e^{-(n - n_{\text{max}})/n_{\text{izkliede}}}, & n > n_{\text{max}}
\end{cases}
\]

- \( n_{\text{max}} = C/(2\pi) \), \( n_{\text{izkliede}} = \frac{C}{2\pi} \cdot \frac{\rho_{\text{H0}}}{\rho_{\mathcal{V}}} \).

**Pārplūdes kanāls:**

\[
\Phi_{n \to n+1} = \phi_0 \cdot \sin(\Delta\theta_n) \cdot \eta_n
\]

kur:
- \( \Delta\theta_n \) — fāžu starpība starp slāņiem,
- \( \eta_n \in \{0,1\} \) — pārneses atļauja.

---

## 5. KASKĀDES DINAMIKA

### 5.1. Inerciālās enerģijas dinamika

\[
\frac{du_{\text{kin}, n}}{dt} = -\alpha \Delta u_n + \beta \Delta u_{n-1}
\]

kur:
- pirmais termins — aizplūšana no slāņa \( n \) uz \( n+1 \),
- otrais termins — ieplūšana no slāņa \( n-1 \) uz \( n \),
- \( \beta \) — līdzīgs \( \alpha \), bet atkarīgs no Qn struktūras.

### 5.2. EM enerģijas dinamika

\[
\frac{du_{\text{EM}, n}}{dt} = -\gamma \Delta u_n + \delta \Delta u_{n+1}
\]

kur \( \gamma \) un \( \delta \) ir atbilstošie koeficienti.

---

## 6. KASKĀDES PROCESS

Turbulence ir secīga pārplūde pa Qn slāņiem:

1. **Traucējums:** \( \Delta u_1 > \Delta u_{\text{krit}, 1} \)
2. **Pārplūde:** \( \Delta u_{1 \to 2} = \alpha \cdot \Delta u_1 \cdot \mathcal{F}_1 \)
3. **Jaunā bilance:** \( u_{\text{EM}, 2} + \Delta u_{1 \to 2} = u_{\text{kin}, 2} \)
4. **Turpināšanās:** Ja \( \Delta u_2 > \Delta u_{\text{krit}, 2} \), pārplūde turpinās uz \( n = 3 \)
5. **Beigas:** Kad \( \Delta u_n \leq \Delta u_{\text{krit}, n} \), process apstājas.

---

## 7. TURBULENCES SPEKTRS

MT turbulence spektrs ir **diskretizēts**:

\[
E(k) = \sum_{k=1}^{\infty} A_k \cdot \delta\left(k - \frac{2\pi}{\lambda_0 \cdot n_k}\right) + \text{fona spektrs}
\]

kur:
- \( n_k = 8k - 1 \),
- \( \lambda_0 \) — sistēmas raksturīgais garums,
- \( A_k \) — amplitūdas koeficienti.

**MT prognoze:** Spektrā ir redzami diskrēti pīķi pie \( k \propto n_k \).

---

## 8. PĀREJA NO LAMINĀRAS UZ TURBULENTU PLŪSMU

### 8.1. MT Reinoldsa skaitlis

\[
Re_{\text{MT}, n} = \frac{u_{\text{kin}, n}}{u_{\text{EM}, n}}
\]

### 8.2. Pārejas nosacījums

\[
Re_{\text{MT}, n} > Re_{\text{krit}, n}
\]

kur:

\[
Re_{\text{krit}, n} = 1 + \frac{\Delta u_{\text{krit}, n}}{u_{\text{EM}, n}}
\]

---

## 9. VIRPUĻU IZMĒRI

Katram Qn slānim atbilst noteikts virpuļu izmēru diapazons:

\[
L_n = \frac{L_0}{n_k}
\]

kur \( L_0 \) — lielākais virpulis (sistēmas izmērs), \( n_k = 8k - 1 \).

**MT prognoze:** Virpuļu izmēri nav nepārtraukti — tie ir diskretizēti.

---

## 10. ROBEŽPĀREJA UZ KLASISKO TURBULENCI

Kad \( n \to \infty \):

- Qn slāņi kļūst blīvi,
- \( \Delta n \to 0 \),
- \( \Delta u_{n \to n+1} \to \frac{du}{dn} \).

**Robežpāreja:**

\[
\lim_{n \to \infty} \Delta u_{n \to n+1} = \alpha \cdot \frac{du}{dn}
\]

Rezultāts — klasiskais Navjē–Stoksa vienādojums, kur nelineārais konvekcijas termins ir šīs pārplūdes nepārtrauktā robeža.

---

## 11. PĀRBAUDĀMĀS PROGNOZES

1. **Diskretizēts spektrs:** Turbulences spektrā ir pīķi pie \( k \propto n_k = 8k-1 \).
2. **Virpuļu izmēri:** Virpuļi veidojas diskrētos izmēros \( L_n = L_0/n_k \).
3. **Pārejas punkti:** Pāreja no lamināras uz turbulentu plūsmu notiek pie diskretizētiem kritiskajiem punktiem, nevis nepārtraukti.
4. **EM loma:** Turbulence ir atkarīga no EM enerģijas sadalījuma \( u_{\text{EM}, n} \).

---

## 12. KOPSAVILKUMA TABULA

| **Solis** | **Vienādojums** | **Apraksts** |
|-----------|-----------------|--------------|
| 1 | \( u_{\text{EM}, n} = \mathcal{P}_{L1} \cdot \Phi_n/\phi_0 \cdot 1/N(n) \) | EM enerģijas blīvums |
| 2 | \( u_{\text{kin}, n} = \frac{1}{2} \rho_n v_n^2 \) | Inerciālās enerģijas blīvums |
| 3 | \( \Delta u_n = u_{\text{kin}, n} - u_{\text{EM}, n} \) | Bilances traucējums |
| 4 | \( \Delta u_{\text{krit}, n} = \phi_0/N(n) \cdot \rho_{\mathcal{V}}/\rho_{\text{H0}} \cdot \alpha \) | Kritiskais slieksnis |
| 5 | \( \Delta u_{n \to n+1} = \alpha \cdot \Delta u_n \cdot \mathcal{F}_n \) | Pārplūdes operators |
| 6 | \( du_{\text{kin}, n}/dt = -\alpha \Delta u_n + \beta \Delta u_{n-1} \) | Inerciālās enerģijas dinamika |
| 7 | \( E(k) = \sum A_k \delta(k - 2\pi/(\lambda_0 n_k)) \) | Turbulences spektrs |
| 8 | \( Re_{\text{MT}, n} = u_{\text{kin}, n}/u_{\text{EM}, n} \) | MT Reinoldsa skaitlis |
| 9 | \( L_n = L_0/n_k \) | Virpuļu izmēri |
| 10 | \( \lim_{n \to \infty} \Delta u_{n \to n+1} = \alpha \cdot du/dn \) | Robežpāreja uz Navjē–Stoksu |

---

## 13. SECINĀJUMI

1. **MT turbulence ir formāli definēta.** Tā ir enerģijas pārplūde pa diskrētiem Qn slāņiem, ko vada EM karkass.

2. **Turbulence nav haoss.** Tā ir diskretizēta enerģijas pārnese, kas notiek pa strukturētiem kanāliem.

3. **Modelis ir pārbaudāms.** Prognozes par diskretizētu spektru, virpuļu izmēriem un pārejas punktiem ir salīdzināmas ar eksperimentiem.

4. **Robežpāreja uz klasisko turbulenci** ir definēta — MT operators reducējas uz Navjē–Stoksa vienādojumu, kad Qn slāņi kļūst blīvi.

---

*Dokuments sagatavots: 2026. gada jūlijā*  
*Versija: 1.0 — formālais modelis*
