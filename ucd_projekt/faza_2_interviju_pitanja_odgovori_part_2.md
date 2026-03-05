# Faza 2: Intervju - Pitanja i odgovori (Part 2)

## Podaci o intervjuu

| Podatak | Vrijednost |
|---|---|
| **Datum** | |
| **Moderator** | |
| **Ispitanik** | |
| **Bilješke vodi** | |

---

## Pitanja moderatora i odgovori ispitanika

### Pitanje 1: Možeš li mi reći nešto o sebi — što studiraš, koja si godina i kako općenito doživljavaš digitalne sustave na fakultetu?

**Odgovor ispitanika:**
Studiram prvu godinu Informacijske tehnologije na UNIZD-u. Generalno sam naviknut na moderne aplikacije pa mi fakultetski sustavi djeluju dosta staromodno. Studomat koristim tek od ove godine i još se snalazim.

---

### Pitanje 2: Kada si zadnji put koristio/la Studomat za upis predmeta, možeš li mi opisati kako je to izgledalo korak po korak?

**Odgovor ispitanika:**
Otvorio sam stranicu, ulogirao se, kliknuo na "Aktivni predmeti" i onda sam dobio jednu veliku tablicu. Nisam bio siguran što trebam napraviti — kliknuo sam na "Detalji" kod jednog predmeta ali to me odvelo na neku drugu stranicu s malo informacija. Na kraju sam samo označio predmete koje su mi kolege preporučili i potvrdio.

---

### Pitanje 3: Koliko ti je bilo jasno koji su predmeti obvezni, a koji izborni kada si prvi put vidio/la tu stranicu?

**Odgovor ispitanika:**
Uopće mi nije bilo jasno. Svi predmeti su u istoj tablici, istom formatu. Morao sam pitati kolegu da mi objasni koji su izborni. Mislim da postoji stupac "Izborna grupa" ali vrijednosti u njemu mi ništa ne govore — piše nešto poput "predmet se ne nalazi u grupi izbornih predmeta" što je zbunjujuće.

---

### Pitanje 4: Što ti je najvažnije znati o nekom predmetu prije nego što ga odlučiš upisati?

**Odgovor ispitanika:**
Najviše me zanima što ću zapravo učiti — sadržaj predmeta. Onda koliko je zahtjevan, koliko ima ispita i kolokvija, i kakva su iskustva drugih studenata. ECTS bodovi su mi bitni jer moram skupiti dovoljno. Također me zanima tko predaje jer to utječe na kvalitetu nastave.

---

### Pitanje 5: Jesi li ikada upisao/la predmet pa se nakon toga razočarao/la jer nije bio onakav kakav si očekivao/la?

**Odgovor ispitanika:**
Da, upisao sam jedan izborni predmet jer mi se naziv činio zanimljiv, ali kad je počela nastava shvatio sam da sadržaj nema veze s onim što sam očekivao. Da sam negdje mogao pročitati silabus ili ishode učenja prije upisa, vjerojatno bih odabrao nešto drugo.

---

### Pitanje 6: Kako se snalaziš s navigacijom na Studomatu — koliko ti je lako pronaći ono što tražiš?

**Odgovor ispitanika:**
Navigacija je dosta konfuzna. Na lijevoj strani ima puno opcija i ne znam uvijek koja vodi kamo. "Podaci o studiranju" ima podizbornik s puno stavki — "Aktivni predmeti", "Upisane godine i završeni", "Dosadašnji ECTS bodovi"... Ponekad kliknem krivu stvar i moram se vraćati. Nema nekakve tražilice ili brze navigacije.

---

### Pitanje 7: Da imaš čarobni štapić i možeš potpuno promijeniti kako Studomat izgleda i radi — što bi napravio/la?

**Odgovor ispitanika:**
Napravio bih da je sve na jednoj stranici — da vidim predmete s kratkim opisom, da mogu kliknuti za više detalja, i da imam nekakav košaricu poput web shopa gdje dodajem predmete. I obavezno bih dodao ocjene ili recenzije od studenata koji su već prošli taj predmet. I da radi dobro na mobitelu jer često gledam s telefona.

---

## Analiza korisničkih potreba

> Metodologija: **IZJAVA → PROBLEM → POTREBA → FUNKCIONALNOST**

### 1.

| | |
|---|---|
| **Izjava** | "Nisam bio siguran što trebam napraviti — kliknuo sam na Detalji ali to me odvelo na neku drugu stranicu s malo informacija." |
| **Problem** | Proces upisa predmeta nije intuitivan, a stranica s detaljima ne pruža korisne informacije. |
| **Potreba** | Student treba jasan i vođen proces upisa s korisnim informacijama na svakom koraku. |
| **Funkcionalnost** | Vodič kroz proces upisa (wizard/stepper) s jasnim koracima i informativnim detaljima predmeta. |

### 2.

| | |
|---|---|
| **Izjava** | "Svi predmeti su u istoj tablici, istom formatu. Morao sam pitati kolegu da mi objasni koji su izborni." |
| **Problem** | Brucoši ne mogu razlikovati obvezne od izbornih predmeta bez pomoći drugih. |
| **Potreba** | Sustav mora biti razumljiv i novim korisnicima bez prethodnog iskustva. |
| **Funkcionalnost** | Jasne oznake i tooltipovi koji objašnjavaju kategorije predmeta i pojmove. |

### 3.

| | |
|---|---|
| **Izjava** | "Najviše me zanima što ću zapravo učiti — sadržaj predmeta. I kakva su iskustva drugih studenata." |
| **Problem** | Ne postoji način da student unaprijed sazna sadržaj predmeta niti iskustva drugih studenata. |
| **Potreba** | Student treba uvid u stvarni sadržaj predmeta i povratne informacije od kolega. |
| **Funkcionalnost** | Prikaz silabusa i sustav ocjena/recenzija predmeta od studenata prethodnih generacija. |

### 4.

| | |
|---|---|
| **Izjava** | "Upisao sam predmet jer mi se naziv činio zanimljiv, ali sadržaj nema veze s onim što sam očekivao." |
| **Problem** | Nedostatak informacija dovodi do pogrešnih odluka pri upisu. |
| **Potreba** | Student treba dovoljno informacija da donese informiranu odluku prije upisa. |
| **Funkcionalnost** | Obavezan prikaz ishoda učenja, sadržaja i načina ocjenjivanja prije potvrde odabira. |

### 5.

| | |
|---|---|
| **Izjava** | "Navigacija je dosta konfuzna. Puno opcija, ne znam koja vodi kamo. Nema tražilice." |
| **Problem** | Navigacijska struktura je složena i neintuitivna, bez mogućnosti brzog pristupa. |
| **Potreba** | Student treba jednostavnu navigaciju s brzim pristupom ključnim funkcijama. |
| **Funkcionalnost** | Pojednostavljena navigacija s tražilicom i prečacima do najčešćih akcija. |

### 6.

| | |
|---|---|
| **Izjava** | "Da imam košaricu poput web shopa gdje dodajem predmete." |
| **Problem** | Trenutni sustav nema intuitivan mehanizam za skupljanje i pregled odabranih predmeta. |
| **Potreba** | Student treba poznat i intuitivan obrazac za odabir i pregled predmeta. |
| **Funkcionalnost** | Sustav košarice za predmete s pregledom odabranih, ukupnim ECTS-om i mogućnošću uklanjanja. |

### 7.

| | |
|---|---|
| **Izjava** | "Često gledam s telefona." / "Da radi dobro na mobitelu." |
| **Problem** | Studomat nije optimiziran za mobilne uređaje. |
| **Potreba** | Student treba pristupiti sustavu s bilo kojeg uređaja. |
| **Funkcionalnost** | Mobile-first responzivan dizajn s prilagođenim prikazom za manje ekrane. |

---

## Zahtjevi korisnika (User Requirements)

| # | Zahtjev | Izvor (potreba) |
|---|---|---|
| UR1 | Sustav mora voditi studenta kroz proces upisa jasnim koracima s informativnim povratnim informacijama. | Potreba 1 |
| UR2 | Sustav mora biti razumljiv novim korisnicima bez prethodnog iskustva — s jasnim oznakama, tooltipovima i pojašnjenjima pojmova. | Potreba 2 |
| UR3 | Sustav mora prikazivati sadržaj predmeta (silabus) i omogućiti uvid u ocjene/recenzije studenata prethodnih generacija. | Potreba 3 |
| UR4 | Sustav mora prikazati ishode učenja, sadržaj i način ocjenjivanja predmeta prije nego student potvrdi odabir. | Potreba 4 |
| UR5 | Sustav mora imati jednostavnu navigaciju s tražilicom i brzim pristupom najčešćim akcijama. | Potreba 5 |
| UR6 | Sustav mora omogućiti dodavanje predmeta u osobnu košaricu s pregledom ukupnih ECTS bodova i mogućnošću uklanjanja. | Potreba 6 |
| UR7 | Sustav mora biti u potpunosti funkcionalan i optimiziran za mobilne uređaje (mobile-first pristup). | Potreba 7 |
