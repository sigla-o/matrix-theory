# ID GRADĀCIJA UN SISTĒMA — MATRICAS TEORIJAS VERSIJA (MT)

Šis dokuments apvieno ID gradācijas matemātisko modeli un ID sistēmas praktisko klasifikāciju. ID ir diskrēts strukturāls indekss, ko nosaka modulācija (cikliskā TE plūsma), lieluma kategorija un papildus parametri pēc nepieciešamības.

Modulācija nav objekts. Modulācija ir cikliska TE plūsma, kura maksimāli ietekmē tikai tos objektus, kuri ir modulācijas lielumā. ID norāda, kura modulācija ietekmē objektu.

## 1. PAMATFORMĀTS

ID{modulācija}.{lieluma_kategorija}/{parametri_pēc_vajadzības}

Pirmais cipars — modulācija (H+n). Obligāts.
Otrais cipars — lieluma kategorija. Obligāts. .0 = pamatvienība, .1, .2, ... = nākamie lielumi.
Aiz "/" — papildus parametri. Nav obligāti. Pievieno pēc nepieciešamības.

Parametri nav piespiedu kārta, bet nepieciešamība. Obligāts sākums ir modulācija un lielums. Pārējais veidojas darba gaitā.

**Piezīme par ID un klasiskajām teorijām:**

ID sistēma klasificē visus objektus — gan tos, kurus apraksta klasiskā fizika (ID1 — ID4), gan MT specifiskos līmeņus (ID0, ID-1). Tas nenozīmē, ka klasiskie objekti (piemēram, zvaigzne ar ID2.2) būtu "nepareizi" aprakstīti ar GR — ID sistēma vienkārši norāda to vietu kopējā enerģijas organizācijas hierarhijā. Klasiskie likumi ir derīgi prognozēm šajos ID līmeņos; MT pievieno mehānisko skaidrojumu to izcelsmei.

## 2. MODULĀCIJAS UN TO SKALAS

ID-1 — < 10⁻³⁵ m — Vertikāle (enerģijas avots)
ID0 — 10⁻³⁵ m — Matrica (režģis, TE plūsmas pamats)
ID1 — 10⁻¹⁵ m — H+1 modulācija
ID2 — 10⁵ – 10²⁵ m — H+2 modulācija
ID3 — 10²⁵ – 10⁴⁵ m — H+3 modulācija
ID4 — 10⁴⁵ – 10⁶⁵ m — H+4 modulācija
ID5 — > 10⁶⁵ m — H+5 modulācija (atvērts nākotnei)

Katra nākamā modulācija ir 10²⁰ reizes lielāka par iepriekšējo.

## 3. SAVIENOJUMS AR MATHEMATICS FORMĀLISMU

No MATHEMATICS_lv.md tiek izmantoti šādi operatori un lielumi:

| Operators / lielums | Definīcija | Fizikālā nozīme |
|---------------------|------------|-----------------|
| \( \mathcal{L} \) | \( \mathbb{Z}^3 \) | H0 matricas kubiskais režģis |
| \( Q_n \) | \( \{\mathbf{x} \in \mathbb{Z}^3 : \|\mathbf{x}\|_\infty \leq n\} \) | Apvalku struktūra |
| \( N(n) \) | \( \frac{(2n+1)(2n^2+2n+3)}{3} \) | Punktu skaits Qn slānī |
| \( N_{\mathcal{V}}(\Omega) \) | VEU vienību skaits reģionā \( \Omega \) | Vertikāles enerģijas daudzums |
| \( \mathcal{T} \) | \( \mathcal{L} \to \mathcal{V} \) | Transformācijas operators |
| \( \mathcal{P}_{L1} \) | \( \mathcal{V} \to \mathcal{L} \) | L1 projekcijas operators |

ID ir diskrēts strukturāls indekss, ko nosaka:
- modulācija (H+n),
- Qn slāņa numurs \( n \),
- Vertikāles enerģijas vienību skaits \( N_{\mathcal{V}} \), kas projicējas uz objekta apkārtni caur \( \mathcal{P}_{L1} \).

## 4. ID GRADĀCIJAS SOLIS — KVANTITATĪVAIS MODELIS

ID solis ir diskrēts un atbilst Qn indeksa pieaugumam:

ID = 2.0 + log_S (R / R_protona)

kur:
- R — objekta Qn rādiuss (mērāms ID1 soļos),
- R_protona ≈ 10⁻¹⁰ m — protona orbitāles rādiuss (ID1.0 atskaites punkts),
- S — solis, ko nosaka Qn slāņu secība.

No Qn punktu skaita:
N(n) = (2n+1)(2n²+2n+3)/3

Lineārais mērogs R ∝ n · λ_ID1. Protonam n_protona = 1. Tātad:
ID = 2.0 + log_S(n)

No Qn slāņu secības n = 6, 15, 23, 31, 39, ... iegūst:
S ≈ 2.5

Galvenais vienādojums:
ID = 2.0 + log_2.5(n)

Vertikāles enerģijas vienību skaits N_V modificē ID vērtību:

ID(n, N_V) = 2.0 + log_2.5(n) + γ_ID · (N_V / N_H0)

kur γ_ID ≈ 0.05 (no MATHEMATICS un COSMOLOGY). N_V/N_H0 ir Vertikāles un H0 enerģijas vienību skaita attiecība objekta apkārtnē.

Augstāks N_V paātrina strukturālo evolūciju reģionos ar augstu Vertikāles enerģijas vienību blīvumu.

## 5. ID SISTĒMAS STRUKTŪRA PA LĪMEŅIEM

ID-1.0 — Vertikāles pamats
ID-1.n — VEU līmeņi (H-3, H-4, ... H-min)

ID0.0 — iņ–jaņ punkts (fāzes avots, rotācija)
ID0.n — Qn slānis (n = 1, 2, 3, ... Qmax)

ID1.0 — protons
ID1.1 — atoms (elements / izotops / ...)
ID1.2 — viela, kristāls, šķidrums (tips / struktūra / ...)
ID1.3 — molekula (tips / izomērs / ...)
ID1.4 — makromolekula (tips / struktūra / ...)

Parametri:
- elements — Mendeļejeva tabulas numurs (1–118)
- izotops — masas skaitlis
- tips / struktūra — tiek definēts pēc nepieciešamības

ID2.lielums/orbītu_sk/atmosfēra/pavadonis/...
Lieluma kategorija norāda zvaigznes masu/izmēru. Parametri apraksta planētu skaitu, atmosfēras klātbūtni, pavadoņu sistēmas un citas sistēmas īpašības.

ID3.lielums/tips/spins/magnētisms/...
Lieluma kategorija norāda objekta masu/izmēru. Tips atšķir balto punduri, neitronu zvaigzni, kvarku zvaigzni. Spins un magnētisms apraksta rotācijas un lauka īpašības.

ID4.lielums/masa/akrēcija/AGN/strūklas/...
Lieluma kategorija norāda melnā cauruma masas skalu. Masa precizē vērtību Saules masās. Akrēcija, AGN un strūklas apraksta vides organizāciju un aktivitāti.

ID5.lielums/...
Atvērts — tiks definēts pēc nepieciešamības.

## 6. KOLEKTĪVIE OBJEKTI — ID2,n KLASE

Kolektīvie objekti ir daudzu monolītu objektu organizācija (zvaigznes, galaktikas, kopas). Tiem nav piemērojama mērogošana no protona; tos klasificē pēc organizācijas līmeņa n:

ID2,n = 2.0 + log_2.5 (N_šūnas / N_protona)

kur N_šūnas ir kolektīvās organizācijas pamatvienību skaits.

| Objekts | ID2,n | Piezīme |
|---------|-------|---------|
| Atoms | ID2,0 | Viena protona organizācija |
| Molekula | ID2,1 | Vairāku atomu organizācija |
| Zvaigzne | ID2,2 | Kolektīva, vienkārša |
| Zvaigžņu kopa | ID2,3 | Sarežģītāka kolektīvā struktūra |
| Galaktika | ID2,4 | Sarežģītākā kolektīvā struktūra |
| Galaktiku kopa | ID2,5 | Augstākā zināmā kolektīvā organizācija |

## 7. ID PĀREJAS — NOSACĪJUMI UN LAIKA SKALA

ID pāreja no viena līmeņa uz nākamo notiek, ja ir izpildīti šādi nosacījumi:

1. Vertikāles enerģijas vienību skaits N_V objekta apkārtnē pārsniedz kritisko slieksni N_krit:
   N_V > N_krit

2. Qn struktūra atļauj pāreju — nākamais slānis n+1 ir pieejams.

3. Modulācijas aktivizē pāreju.

Pārejas laiks:
t_pāreja ∝ 1 / (N_V - N_krit)

Pāreju piemēri:

| Pāreja | No | Uz | Aktivizējošais process | Piemērs |
|--------|----|----|-------------------------|---------|
| ID1.0 → ID1.1 | Protons | Atoms | Elektrona pievienošanās | Ūdeņradis |
| ID1.1 → ID1.2 | Atoms | Viela | Kristalizācija | Dimants |
| ID1.2 → ID1.3 | Viela | Molekula | Ķīmiskā saite | H₂O |
| ID1.3 → ID1.4 | Molekula | Makromolekula | Polimerizācija | DNS |
| ID2.0 → ID2.1 | Brīva planēta | Planēta ar pavadoni | Pavadoņa notveršana | Marss + Foboss |
| ID2.1 → ID2.2 | Planēta ar pavadoni | Planēta ar atmosfēru | Atmosfēras veidošanās | Venera |
| ID2.2 → ID2.3 | Planēta ar atmosfēru | Planēta ar atmosfēru un pavadoņiem | Papildu pavadoņi | Zeme + Mēness |
| ID3.0 → ID3.1 | Baltais punduris | Neitronu zvaigzne | Gravitācijas kolapss | Pulsārs |
| ID4.0 → ID4.1 | Zvaigžņu melnais caurums | Vidējas masas melnais caurums | Akrēcija | — |

## 8. PIEMĒRI

ID1.0 — brīvs protons
ID1.1/1/1 — ūdeņradis-1
ID1.1/6/12 — ogleklis-12
ID1.1/92/238 — urāns-238
ID1.2/1/1 — dimants
ID1.3/1/1 — H₂O
ID1.4/1/1 — DNS
ID2.5/8/1 — Saules sistēma (8 planētas, 1 apdzīvojama)
ID2.3/4/0 — zvaigzne ar 4 planētām, bez atmosfēras un pavadoņiem
ID3.1/0 — baltais punduris
ID3.2/1 — pulsārs
ID4.1/0 — zvaigžņu melnais caurums bez akrēcijas
ID4.3/2 — supermasīvs melnais caurums ar akrēcijas disku
ID4.3/2/1 — supermasīvs melnais caurums ar akrēcijas disku un strūklām

## 9. PĀRBAUDĀMĀS PROGNOZES

| Prognoze | Vienādojums | Pārbaudes metode |
|----------|------------|------------------|
| ID atkarība no N_V | ID = 2.0 + log_2.5(n) + 0.05 · N_V/N_H0 | Melno caurumu masu salīdzinājums |
| ID pārejas laiks | t_pāreja ∝ 1/(N_V - N_krit) | AGN aktivitātes periodiskums |
| ID2,n un galaktiku tips | ID2,n = 2.0 + log_2.5(N_zvaigznes/N_protona) | Galaktiku morfoloģija |
| Maksimālais ID3,n | n_max ∝ N_V⁽⁰⁾/N_H0 | Maksimālā melnā cauruma masa |

## 10. PAPILDINĀŠANAS NOTEIKUMI

1. Parametrus pievieno tikai pēc vajadzības.
2. Parametru skaits nav ierobežots.
3. Katrs nākamais .n satur iepriekšējos sevī.
4. Sistēmu var papildināt un precizēt, teorijai attīstoties.

## 11. PAMATPRINCIPS

1. Pirmais cipars = modulācija (obligāts)
2. Otrais cipars = lieluma kategorija (obligāts)
3. Viss pārējais aiz "/" = pēc vajadzības (nav obligāts)

ID sistēma ir sākums, nevis beigas. Tās pilnveide notiks darba gaitā.

Dokuments sagatavots: 2026. gada jūlijā
