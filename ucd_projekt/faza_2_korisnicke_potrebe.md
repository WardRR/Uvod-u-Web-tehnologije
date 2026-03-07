# FAZA 2 - Korisničke potrebe

## Analiza korisničkih potreba

> Metodologija: **IZJAVA → PROBLEM → POTREBA → FUNKCIONALNOST**

### 1.

| | |
|---|---|
| **Izjava** | "Sve je u jednoj velikoj tablici, puno stupaca, puno podataka odjednom. Trebam malo vremena da se snađem." |
| **Problem** | Sučelje je pretrpano i nepregledano — previše informacija prikazano odjednom. |
| **Potreba** | Student treba čisto i pregledno sučelje s jasnom vizualnom hijerarhijom. |
| **Funkcionalnost** | Redizajn prikaza predmeta s karticama/grupiranjem umjesto guste tablice. |

### 2.

| | |
|---|---|
| **Izjava** | "Na Studomatu nema opisa predmeta, moram ići na web stranicu fakulteta ili pitati kolege." |
| **Problem** | Nedostaju ključne informacije o predmetima (opis, sadržaj, način ocjenjivanja). |
| **Potreba** | Student treba pristup detaljnim informacijama o predmetu na jednom mjestu. |
| **Funkcionalnost** | Detaljan prikaz predmeta (silabus, ishodi učenja, način ocjenjivanja) na klik. |

### 3.

| | |
|---|---|
| **Izjava** | "Nema nikakvog filtera pa moram sam skrolati i tražiti." |
| **Problem** | Ne postoji mogućnost filtriranja ili pretraživanja predmeta. |
| **Potreba** | Student treba brzo suziti popis predmeta prema svojim kriterijima. |
| **Funkcionalnost** | Filtriranje po ECTS bodovima, semestru, kategoriji i pretraživanje po ključnim riječima. |

### 4.

| | |
|---|---|
| **Izjava** | "Htio sam usporediti dva predmeta i morao sam otvarati svaki posebno, zapisivati na papir." |
| **Problem** | Ne postoji mogućnost usporedbe predmeta unutar sustava. |
| **Potreba** | Student treba mogućnost izravne usporedbe predmeta. |
| **Funkcionalnost** | Usporedba 2-3 predmeta usporedno prema odabranim kriterijima. |

### 5.

| | |
|---|---|
| **Izjava** | "Tablica prikazuje sve predmete zajedno — i obvezne i izborne — pa je teško razlikovati koje mogu birati." |
| **Problem** | Nema jasnog vizualnog razlikovanja obveznih i izbornih predmeta. |
| **Potreba** | Student treba jasno vidjeti koji su predmeti izborni, a koji obvezni. |
| **Funkcionalnost** | Vizualno razdvajanje obveznih i izbornih predmeta (boje, oznake, kategorije). |

### 6.

| | |
|---|---|
| **Izjava** | "Najviše me zanima što ću zapravo učiti — sadržaj predmeta. I kakva su iskustva drugih studenata." |
| **Problem** | Ne postoji način da student unaprijed sazna sadržaj predmeta niti iskustva drugih studenata. |
| **Potreba** | Student treba uvid u stvarni sadržaj predmeta i povratne informacije od kolega. |
| **Funkcionalnost** | Prikaz silabusa i sustav ocjena/recenzija predmeta od studenata prethodnih generacija. |

### 7.

| | |
|---|---|
| **Izjava** | "Nejasne informacije o težini predmeta, nemamo neke recenzije o predmetu." |
| **Problem** | Nepostojana informacija prolaznosti predmeta / težini u neovisnosti ECTS brojeva. |
| **Potreba** | Student treba biti informiran o prolaznosti predmeta. |
| **Funkcionalnost** | Sučelje koje govori o prolaznosti predmeta. |
---

### 8.

| | |
|---|---|
| **Izjava** | "Propustio sam rok za upis jer nisam znao do kad traje upisni period. Nema nikakvog upozorenja osim da pratim obavijesti na web stranici fakulteta." |
| **Problem** | Sustav ne obavještava studente o važnim rokovima i datumima. |
| **Potreba** | Student treba pravovremene obavijesti o rokovima vezanim uz upis predmeta. |
| **Funkcionalnost** | Sustav obavijesti (push/email) s podsjetnicima o upisnim rokovima i važnim datumima. |

### 9.

| | |
|---|---|
| **Izjava** | "Da mogu vidjeti koje su predmete upisali moji kolege ili da vidim popularnost predmeta." |
| **Problem** | Student nema uvid u to koliko je predmet popularan ili što biraju drugi studenti. |
| **Potreba** | Student treba socijalni kontekst koji mu pomaže u donošenju odluke. |
| **Funkcionalnost** | Prikaz statistike upisa (broj upisanih studenata, popularnost). |

### 10.

| | |
|---|---|
| **Izjava** | "Htio sam promijeniti izborni predmet ali to nemogu bez da kontaktiram studentsku službu (tajništvo)." |
| **Problem** | Nemogućnost promjene odabranih predmeta unutar sustava od strane studenta do nekog određenog perioda. |
| **Potreba** | Student treba mogućnost jednostavne izmjene odabira predmeta ali do nekog određenog roka. |
| **Funkcionalnost** | Opcija zamjene/uklanjanja predmeta direktno u sustavu tijekom nekog određenog perioda. |

## Zahtjevi korisnika (User Requirements)

| # | Zahtjev | Izvor (potreba) |
|---|---|---|
| UR1 | Sustav mora prikazivati predmete na pregledan način s jasnom vizualnom hijerarhijom (kartice ili grupirani prikaz umjesto guste tablice). | Potreba 1 |
| UR2 | Sustav mora omogućiti pristup detaljnim informacijama o svakom predmetu (opis, silabus, ishodi učenja, način ocjenjivanja) unutar jednog klika. | Potreba 2 |
| UR3 | Sustav mora omogućiti filtriranje predmeta po ECTS bodovima, semestru i kategoriji te pretraživanje po ključnim riječima. | Potreba 3 |
| UR4 | Sustav mora omogućiti usporedbu najmanje 2 predmeta usporedno prema odabranim kriterijima. | Potreba 4 |
| UR5 | Sustav mora jasno vizualno razlikovati obvezne od izbornih predmeta (bojama, oznakama ili kategorijama). | Potreba 5 |
| UR6 | Sustav mora prikazivati sadržaj predmeta (silabus) i omogućiti uvid u ocjene/recenzije studenata prethodnih generacija. | Potreba 6 |
| UR7 | Sustav mora biti u potpunosti funkcionalan i optimiziran za mobilne uređaje (mobile-first pristup). | Potreba 7 |
| UR8 | Sustav mora slati obavijesti i podsjetnike o upisnim rokovima putem e-maila ili push notifikacija. | Potreba 8 |
| UR9 | Sustav mora prikazivati statistike upisa (broj upisanih studenata, popularnost predmeta) kao pomoć pri odlučivanju. | Potreba 9 |
| UR10 | Sustav mora omogućiti studentu zamjenu ili uklanjanje odabranih predmeta direktno u sustavu tijekom određenog perioda. | Potreba 10 |

