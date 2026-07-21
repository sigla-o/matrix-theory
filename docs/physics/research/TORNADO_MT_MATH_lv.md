# TORNĀDO — MT MATEMĀTISKAIS MODELIS (PAPILDINĀJUMS)

## Enerģijas bilance un pārplūde pa Qn slāņiem

**Versija: 1.0 (2026. gada jūlijs)**  
**Statuss: PROVIZORISKS — matemātiskais formālisms, gaida pārbaudi pret datiem**  
*Papildinājums dokumentam TORNADO_MT_lv.md*

---

## 1. IEVADS

Dokumentā `TORNADO_MT_lv.md` tika noteikts, ka:

> **Tornādo ir EM līdzsvara atjaunošanas ceļš — enerģijas plūsmas struktūra, ko vada VEU H-2 un H-3 mijiedarbība.**

Tornādo veidojas, kad **inerciālā plūsmas enerģija** pārsniedz **EM enerģiju** noteiktā Qn slānī. Pārpalikums tiek nodots uz nākamo Qn slāni, radot diskrētu enerģijas kaskādi. Šis dokuments sniedz šī procesa **matemātisko formālismu**.

---

## 2. ENERĢIJAS BILANCE QN SLĀNĪ

Katrs Qn slānis \( n \) (kur \( n = 1, 2, 3, \dots \), atbilstoši Qn struktūrai \( n_k = 8k-1 \)) satur divu veidu enerģiju:

### 2.1. EM enerģijas blīvums
\[
u_{\text{EM}, n} = \frac{1}{2} \varepsilon_0 E_n^2 + \frac{1}{2\mu_0} B_n^2
\]
kur:
- \( E_n, B_n \) — lokālie EM lauki Qn slānī,
- \( \varepsilon_0, \mu_0 \) — matricas stāvokļa funkcijas, kas mainās atkarībā no \( \rho_{\mathcal{V}} \).

### 2.2. Inerciālās plūsmas kinētiskā enerģija
\[
u_{\text{kin}, n} = \frac{1}{2} \rho_n v_n^2
\]
kur:
- \( \rho_n \) — gāzu blīvums slānī (atkarīgs no temperatūras, spiediena un EM ietekmes),
- \( v_n \) — plūsmas ātrums.

### 2.3. Bilances nosacījums
Līdzsvara stāvoklī:
\[
u_{\text{EM}, n} = u_{\text{kin}, n}
\]
Gāze atrodas savā EM līdzsvara vietā — turbulence neveidojas.

---

## 3. BILANCES TRAUCĒJUMS UN PĀREJAS NOSACĪJUMS

Kad temperatūras porcija vai cits traucējums palielina \( u_{\text{kin}, n} \), bilance tiek traucēta:

\[
\Delta u_n = u_{\text{kin}, n} - u_{\text{EM}, n}
\]

**Pārejas nosacījums:**

\[
\Delta u_n > \Delta u_{\text{krit}, n}
\]

kur \( \Delta u_{\text{krit}, n} \) ir slāņa \( n \) **kritiskais slieksnis**, ko nosaka:
- Qn struktūra (pieejamo kanālu skaits),
- lokālais \( \rho_{\mathcal{V}} \),
- matricas elastība \( \alpha \).

Ja šis slieksnis nav pārsniegts, sistēma atgriežas līdzsvarā bez turbulence.

---

## 4. ENERĢIJAS PĀRPLŪDES OPERATORS

Kad \( \Delta u_n > \Delta u_{\text{krit}, n} \), enerģijas pārpalikums tiek nodots uz nākamo Qn slāni \( n+1 \):

\[
\Delta u_{n \to n+1} = \alpha \cdot \Delta u_n
\]

kur:
- \( \alpha = 6\omega_0/7 \) — matricas elastība (no MATHEMATICS 3.0),
- \( \Delta u_{n \to n+1} \) — enerģijas daudzums, kas pārplūst no slāņa \( n \) uz \( n+1 \).

**Pārplūdes kanāls:** enerģija pārplūst pa TE plūsmas kanālu:

\[
\Phi_{n \to n+1} = \phi_0 \cdot \sin(\Delta\theta_n) \cdot \eta_n
\]

kur:
- \( \phi_0 = \hbar c/l_P \) — maksimālais pārneses kvants,
- \( \Delta\theta_n \) — fāžu starpība starp slāņiem,
- \( \eta_n \in \{0,1\} \) — pārneses atļauja (saderīgas fāzes).

---

## 5. PĀRPLŪDES DINAMIKA

Katrā Qn slānī enerģijas izmaiņas laikā apraksta:

**Inerciālās enerģijas dinamika:**

\[
\frac{du_{\text{kin}, n}}{dt} = -\alpha \cdot (u_{\text{kin}, n} - u_{\text{EM}, n}) + \beta \cdot (u_{\text{kin}, n-1} - u_{\text{EM}, n-1})
\]

kur:
- pirmais termins apraksta enerģijas aizplūšanu no slāņa \( n \) uz \( n+1 \),
- otrais termins apraksta enerģijas ieplūšanu no slāņa \( n-1 \) uz \( n \),
- \( \beta \) ir līdzīgs \( \alpha \), bet var atšķirties atkarībā no Qn struktūras (katram slānim ir sava elastība).

**EM enerģijas dinamika:**

\[
\frac{du_{\text{EM}, n}}{dt} = -\gamma \cdot (u_{\text{EM}, n} - u_{\text{kin}, n}) + \delta \cdot (u_{\text{EM}, n+1} - u_{\text{kin}, n+1})
\]

kur \( \gamma \) un \( \delta \) ir atbilstošie koeficienti, kas apraksta EM enerģijas pārplūdi starp slāņiem.

**Līdzsvara atjaunošana:**
\[
u_{\text{EM}, n+1} + \Delta u_{n \to n+1} = u_{\text{kin}, n+1}
\]

Kad šī bilance ir sasniegta, turbulences process apstājas (vai pāriet uz nākamo slāni).

---

## 6. KASKĀDES PROCESS — SECĪGA PĀRPLŪDE

Turbulence ir **secīga enerģijas pārplūde pa Qn slāņiem**:

1. **Traucējums:** \( u_{\text{kin}, 1} > u_{\text{EM}, 1} \)
2. **Pārplūde:** \( \Delta u_{1 \to 2} = \alpha \cdot (u_{\text{kin}, 1} - u_{\text{EM}, 1}) \)
3. **Jaunā bilance:** \( u_{\text{EM}, 2} + \Delta u_{1 \to 2} = u_{\text{kin}, 2} \)
4. **Ja \( u_{\text{kin}, 2} > u_{\text{EM}, 2} \):** pārplūde turpinās uz \( n = 3 \)
5. **Process turpinās**, līdz enerģija ir izkliedēta vai bilance atjaunota.

**MT prognoze:** Enerģijas spektrā vajadzētu būt **diskrētiem līmeņiem**, kas atbilst Qn secībai \( n_k = 8k-1 \):

\[
E_n \propto \frac{1}{n_k^2} \cdot \mathcal{F}_n
\]

kur \( \mathcal{F}_n \) ir fokusēšanas/izkliedes funkcija no MATHEMATICS 5.2.

---

## 7. VIRPUĻU SKAITS — PARALĒLIE KANĀLI

Vairāki virpuļi veidojas, kad enerģijas pārpalikums pārsniedz viena kanāla kapacitāti:

\[
\Delta u_n > \Phi_{\text{max}, n}
\]

kur \( \Phi_{\text{max}, n} \) ir maksimālā plūsmas kapacitāte vienā Qn kanālā.

**Sadalīšanās nosacījums:**

\[
m = \left\lfloor \frac{\Delta u_n}{\Phi_{\text{max}, n}} \right\rfloor + 1
\]

kur \( m \) ir paralēlo kanālu (virpuļu) skaits.

**MT prognoze:** Virpuļu skaits ir diskrēts un atbilst Qn struktūrai — nevis patvaļīgs, bet noteikts ar pieejamo kanālu skaitu.

---

## 8. TURBULENCES SPEKTRS — PĀRBAUDĀMA PROGNOZE

MT turbulence spektrs atšķiras no Kolmogorova spektra:

| **Klasiskā turbulence** | **MT turbulence** |
|--------------------------|-------------------|
| Nepārtraukts spektrs \( E(k) \propto k^{-5/3} \) | **Diskretizēts** spektrs ar pīķiem pie \( k_n \propto n_k \) |
| Enerģijas kaskāde nepārtraukta | Enerģijas pārplūde diskrēta pa Qn slāņiem |
| Nav prognozes par diskrētiem līmeņiem | **Prognoze:** pīķi pie \( n_k = 8k-1 \) |

**Pārbaudes metode:** Analizēt turbulences spektrus (piemēram, atmosfēras datos) un meklēt diskrētus pīķus, kas atbilst \( n_k = 8k-1 \).

---

## 9. EKSPERIMENTĀLĀ PĀRBAUDE — NEPIECIEŠAMIE MĒRĪJUMI

Lai pārbaudītu MT turbulence modeli, nepieciešami mērījumi, kas vienlaicīgi reģistrē:

1. **EM laukus** (E un B) dažādos augstumos — lai noteiktu \( u_{\text{EM}, n} \).
2. **Gāzu plūsmas ātrumus un blīvumus** — lai noteiktu \( u_{\text{kin}, n} \).
3. **Temperatūras gradientus** dažādos augstumos — lai noteiktu traucējumu avotus.

**MT prognoze:** Turbulences spektrā vajadzētu būt redzamiem **diskrētiem pīķiem**, kas atbilst Qn slāņu secībai \( n_k = 8k-1 \). Ja šādi pīķi tiek atklāti, tas būtu spēcīgs MT apstiprinājums.

---

## 10. POTENCIĀLIE DARBA VIRZIENI

1. **Simulāciju izstrāde:** Izveidot skaitlisko modeli, kas realizē Qn pārplūdes operatorus un prognozē diskrētu turbulences spektru.

2. **Datu analīze:** Pārbaudīt esošos atmosfēras turbulentos datus (piemēram, no lidar, radara, zondēm) pret MT prognozi par diskrētiem enerģijas līmeņiem.

3. **EM lauku mērījumu integrācija:** Savienot turbulences mērījumus ar EM lauku mērījumiem, lai noteiktu \( u_{\text{EM}, n} \) un \( u_{\text{kin}, n} \) attiecību.

4. **Virpuļu skaita prognoze:** Pārbaudīt, vai vairāku virpuļu tornādo skaits atbilst Qn kanālu skaitam un to kapacitātei.

5. **Formālā matemātiskā pierādījuma izstrāde:** Pierādīt, ka MT turbulence operators reducējas uz klasisko Navjē–Stoksa vienādojumu robežā, kad \( n \to \infty \) (t.i., kad Qn slāņi kļūst blīvi).

---

## 11. KOPSAVILKUMA TABULA

| **Solis** | **Apraksts** | **Matemātika** |
|-----------|--------------|----------------|
| 1 | EM enerģijas sadalījums | \( u_{\text{EM}, n} = \frac{1}{2} \varepsilon_0 E_n^2 + \frac{1}{2\mu_0} B_n^2 \) |
| 2 | Inerciālās enerģijas sadalījums | \( u_{\text{kin}, n} = \frac{1}{2} \rho_n v_n^2 \) |
| 3 | Bilances pārbaude | \( \Delta u_n = u_{\text{kin}, n} - u_{\text{EM}, n} \) |
| 4 | Pārejas nosacījums | \( \Delta u_n > \Delta u_{\text{krit}, n} \) |
| 5 | Pārplūdes operators | \( \Delta u_{n \to n+1} = \alpha \cdot \Delta u_n \) |
| 6 | Pārplūdes kanāls | \( \Phi_{n \to n+1} = \phi_0 \sin(\Delta\theta_n) \eta_n \) |
| 7 | Inerciālās enerģijas dinamika | \( \frac{du_{\text{kin}, n}}{dt} = -\alpha \Delta u_n + \beta \Delta u_{n-1} \) |
| 8 | EM enerģijas dinamika | \( \frac{du_{\text{EM}, n}}{dt} = -\gamma \Delta u_n + \delta \Delta u_{n+1} \) |
| 9 | Kaskādes turpināšanās | Turpinās, līdz \( \Delta u_n \leq \Delta u_{\text{krit}, n} \) |
| 10 | Virpuļu skaits | \( m = \lfloor \Delta u_n / \Phi_{\text{max}, n} \rfloor + 1 \) |

---

## 12. SECINĀJUMI

1. **MT turbulence matemātika ir izstrādāta.** Tā ir **esošo MT operatoru secīga pielietošana**, kas apraksta enerģijas pārplūdi pa Qn slāņiem.

2. **Galvenā prognoze:** Turbulences spektrā vajadzētu būt **diskrētiem enerģijas līmeņiem**, kas atbilst Qn secībai \( n_k = 8k-1 \).

3. **MT turbulence nav haoss.** Tā ir **diskrēta enerģijas pārplūde**, kas notiek pa strukturētiem kanāliem, ko nosaka EM karkass.

4. **Modelis ir pārbaudāms.** Nepieciešami vienlaicīgi EM lauku, gāzu plūsmas un temperatūras gradientu mērījumi.

5. **Nākamie soļi:** Simulāciju izstrāde, datu analīze, formālā matemātiskā pierādījuma izstrāde.

---

*Dokuments sagatavots: 2026. gada jūlijā*  
*Versija: 1.0 — matemātiskais formālisms, provizorisks*
