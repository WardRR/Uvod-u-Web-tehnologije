# FAZA 1 - Definicija projekta

## 1. Svrha sustava

Sustav služi kao **web sučelje za odabir izbornih predmeta** na UNIZD-u. Njegova svrha je omogućiti studentima da:

- pregledaju cjelokupnu ponudu izbornih predmeta na strukturiran i pregledan način
- donesu **informiranu odluku** o tome koje izborne predmete žele upisati (uspoređujući ECTS bodove, opis predmeta, nositelje, raspored i sl.)
- odaberu željene predmete i dodaju ih na svoj popis
- pregledaju svoj konačni odabir prije potvrde upisa

**Problem sadašnjeg sustava**: sučelje je tabelarno, pretrpano, bez mogućnosti filtriranja/usporedbe, bez opisa predmeta, i ne razlikuje jasno obvezne od izbornih predmeta. Student nema dovoljno informacija za kvalitetnu odluku.


## 2. Identifikacija korisnika

| Korisnik | Opis | Ciljevi |
|---|---|---|
| **Student (primarni)** | Redovni ili izvanredni student koji upisuje izborne predmete | Brzo pronaći relevantne izborne predmete, usporediti ih i odabrati |
| **Brucoš** | Novoupisani student bez prethodnog iskustva sa sustavom | Treba intuitivno sučelje, pojašnjenja i vođenje kroz proces |
| **Student viših godina** | Ima iskustva s upisom, zna što traži | Brz pristup, filtriranje po kriterijima, usporedba s prethodnim godinama |

> Sekundarni korisnici mogli bi biti **nastavnici** (pregled koliko studenata je odabralo njihov predmet) i **studentska služba** (administracija), ali fokus prototipa je na **studentu**.


## 3. Ključne funkcionalnosti i zadaci korisnika

### Funkcionalnosti

1. **Pregled ponude izbornih predmeta** - prikaz svih dostupnih izbornih predmeta s osnovnim informacijama (naziv, ECTS, nositelj, semestar, opis)
2. **Filtriranje i pretraživanje** - mogućnost filtriranja po ECTS bodovima, semestru, kategoriji, ključnim riječima
3. **Detaljan prikaz predmeta** - klik na predmet otvara detalje (silabus, ishodi učenja, način ocjenjivanja)
4. **Usporedba predmeta** - mogućnost usporedbe 2-3 predmeta usporedno prema odabranim kriterijima
5. **Odabir predmeta u popis** - dodavanje predmeta na osobni popis odabranih izbornih predmeta
6. **Pregled odabranih predmeta** - pregled popisa s ukupnim ECTS bodovima i mogućnošću uklanjanja predmeta
7. **Potvrda odabira** - završni korak s pregledom i potvrdom konačnog odabira

### Zadaci korisnika (user tasks)

| # | Zadatak | Opis |
|---|---|---|
| T1 | Pregledati ponudu | Student otvara popis izbornih predmeta i pregledava što je dostupno |
| T2 | Pretražiti/filtrirati | Student koristi filtre da suzi izbor prema svojim kriterijima |
| T3 | Pogledati detalje predmeta | Student klikne na predmet da vidi potpune informacije |
| T4 | Usporediti predmete | Student uspoređuje dva ili više predmeta |
| T5 | Dodati predmet na popis | Student odabire predmet i dodaje ga na svoj popis |
| T6 | Ukloniti predmet s popisa | Student se predomisli i miče predmet s popisa |
| T7 | Pregledati odabrane | Student pregledava konačni popis odabranih predmeta |
| T8 | Potvrditi odabir | Student potvrđuje svoj konačni izbor izbornih predmeta |

## Kritika trenutnog sučelja (Studomat)

Trenutni Studomat prikazuje predmete u gustoj tablici bez:

- opisa predmeta ili dodatnih informacija
- mogućnosti filtriranja ili pretraživanja
- vizualnog razlikovanja obveznih i izbornih predmeta
- mogućnosti usporedbe
- jasnog prikaza ukupnih ECTS bodova za odabrane predmete
- responzivnog dizajna za mobilne uređaje
