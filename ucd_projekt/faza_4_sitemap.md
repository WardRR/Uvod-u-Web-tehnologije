[← Natrag na README](../README.md)

# Faza 4: Sitemap

> **Projekt:** Web sučelje za odabir izbornih predmeta (UNIZD)
> **Metodologija:** Struktura stranica definirana na temelju korisničkih zahtjeva (UR1–UR10), JTBD izjava i funkcionalnosti iz prethodnih faza.

Miro link: [Sitemap na Miro ploči](https://miro.com/app/board/uXjVGszo5Ow=/?share_link_id=652923526895)
---

## Sitemap — strukturni prikaz

```
[0] Početna stranica (Landing Page)
│
├── [1] Prijava / Autentifikacija
│   ├── [1.1] Prijava (AAI@EduHr)
│   └── [1.2] Oporavak lozinke
│
├── [2] Nadzorna ploča (Dashboard)
│   ├── [2.1] Pregled statusa upisa
│   ├── [2.2] Obavijesti i rokovi (UR8)
│   └── [2.3] Brzi pristup — odabrani predmeti
│
├── [3] Katalog predmeta
│   ├── [3.1] Popis svih predmeta — kartični prikaz (UR1, UR5)
│   │   ├── Vizualno razlikovanje obveznih / izbornih (UR5)
│   │   └── Prikaz osnovnih info (naziv, ECTS, nositelj, semestar)
│   ├── [3.2] Filtriranje i pretraživanje (UR3)
│   │   ├── Filter po ECTS bodovima
│   │   ├── Filter po semestru
│   │   ├── Filter po kategoriji
│   │   └── Pretraživanje po ključnim riječima
│   ├── [3.3] Detalji predmeta (UR2, UR6, UR7)
│   │   ├── Opis i silabus
│   │   ├── Ishodi učenja
│   │   ├── Način ocjenjivanja
│   │   ├── Prolaznost i zahtjevnost (UR7)
│   │   ├── Recenzije studenata (UR6)
│   │   └── Statistika upisa — popularnost (UR9)
│   └── [3.4] Usporedba predmeta (UR4)
│       └── Usporedba 2–3 predmeta usporedno
│
├── [4] Moj odabir
│   ├── [4.1] Popis odabranih predmeta (UR1)
│   │   ├── Ukupni ECTS bodovi
│   │   ├── Uklanjanje predmeta s popisa
│   │   └── Zamjena predmeta (UR10)
│   └── [4.2] Potvrda odabira
│       ├── Pregled konačnog odabira
│       └── Potvrda upisa
│
├── [5] Obavijesti (UR8)
│   ├── [5.1] Popis obavijesti
│   ├── [5.2] Postavke obavijesti (email / push)
│   └── [5.3] Kalendar rokova
│
└── [6] Profil studenta
    ├── [6.1] Osobni podaci
    ├── [6.2] Povijest upisa predmeta
    └── [6.3] Postavke (notifikacije, jezik)
```

---

## Mapiranje stranica → Korisnički zahtjevi

| Stranica | Korisnički zahtjevi | JTBD |
|---|---|---|
| [3.1] Popis predmeta — kartični prikaz | UR1, UR5 | JTBD 1, JTBD 5 |
| [3.2] Filtriranje i pretraživanje | UR3 | JTBD 3 |
| [3.3] Detalji predmeta | UR2, UR6, UR7 | JTBD 2, JTBD 6, JTBD 7 |
| [3.3] Statistika upisa | UR9 | JTBD 9 |
| [3.4] Usporedba predmeta | UR4 | JTBD 4 |
| [4.1] Popis odabranih + zamjena | UR10 | JTBD 10 |
| [4.2] Potvrda odabira | — | Job Map: faza 5 |
| [5] Obavijesti | UR8 | JTBD 8 |

---

## Napomene

- **Navigacija** — globalna navigacija uvijek vidljiva s pristupom: Katalog, Moj odabir, Obavijesti, Profil.
- **Pristupačnost** — sustav koristi jasne oznake, kontrastne boje i semantički HTML.
