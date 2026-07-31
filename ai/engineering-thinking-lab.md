# Engineering Thinking Lab
## Közös mentális modellek építése az AI-korszak szoftverfejlesztéséhez

> **Központi kérdés**
>
> Hogyan lehet közös mentális modellt kialakítani olyan emberek között, akik ugyanazokat a szavakat használják, de teljesen eltérő tapasztalattal, felelősségi körrel és nézőponttal rendelkeznek?

---

# A probléma

Az AI megjelenésével nem csupán új eszközök jelentek meg.

Megváltozott a szoftverfejlesztés sebessége, a szervezeti kommunikáció, a döntéshozatal és a tudás terjedése is.

A legtöbb szervezet jelenleg:

- AI-eszközökről beszél,
- guardrail-eket készít,
- promptokat gyűjt,
- Copilot demókat tart.

Miközben sokkal kevesebb szó esik arról, hogy

- hogyan változik a mérnöki munka,
- hogyan változik a kommunikáció,
- hogyan kezeljük a komplexitást,
- hogyan biztosítjuk a valódi üzleti értéket.

---

# Amit keresek: egy közös fogalomrendszer.

Először meg kellene érteni:
- Ki kicsoda?
- Milyen problémákkal dolgozik?
- Mit jelent nála a "jó megoldás"?
- Milyen döntéseket hozhat meg?
- Milyen döntéseket nem?

```text
                 CTO

                  │

          Principal Engineer

                  │

           Staff Engineer

                  │

        Senior Software Engineer

                  │

   ┌──────────────┼──────────────┐
   │              │              │
Data Eng.      DBA          DevOps
   │              │              │
Junior       Junior DBA     Junior DevOps
```

---

# A kommunikáció valódi problémája

## A kompetenciák relatívak

Ugyanaz a pozíció teljesen mást jelent különböző szervezetekben.

| Cím | KKV | OTP-szerű nagyvállalat | FAANG-szerű cég |
|------|-----|-------------------------|-----------------|
| Junior Data Engineer | ETL-eket ír | Bronze–Silver pipeline | Elosztott rendszereket fejleszt |
| Senior Data Engineer | "Mindenes" | Platform komponensek | Technikai irányt ad |
| Staff Engineer | Gyakran nincs | Ritka | Szervezeti technológiai döntéseket hoz |

A címek tehát nem abszolútak.

Hanem szervezetfüggők.

---

## A szerepkör és a kompetencia nem ugyanaz

Valaki lehet

**Senior Data Engineer**

miközben valójában

- Oracle DBA
- SQL Server DBA
- Hadoop admin
- Azure specialista

és nagyon kevés szoftvermérnöki tapasztalata van.

Papíron ugyanaz.

A kompetenciamátrix teljesen más.

---

## Emiatt mindenki más nyelvet beszél

Például:

**Data Quality**

DBA számára:

- constraint
- consistency
- index

Data Engineer számára:

- schema evolution
- lineage
- pipeline

Product Owner számára:

- rossz riport

Manager számára:

- SLA
- KPI

Mindenki ugyanazt a szót használja.

Mégsem ugyanarról beszélnek.

---

# A kommunikáció három dimenziója

## 1. Vertikális

Ki milyen felelősségi szinten gondolkodik?

```text
Junior

↓

Medior

↓

Senior

↓

Staff

↓

Principal

↓

CTO
```

---

## 2. Horizontális

Melyik szakmai területet képviseli?

```text
Backend

Data

ML

DevOps

DBA

Security

Architecture

Product
```

---

## 3. Mélységi (absztrakció)

Milyen szinten gondolkodik?

```text
Kód

↓

Komponens

↓

Rendszer

↓

Platform

↓

Üzleti folyamat

↓

Üzleti érték
```

---

# Miért fulladnak kudarcba a beszélgetések?

Mert ugyanazokat a szavakat használjuk.

De más absztrakciós szinteken.

Például ugyanarra a kérdésre:

> Hogyan használjuk az AI-t?

más választ vár

### Junior

"Hogyan írjak jobb promptot?"

---

### Senior

"Hogyan validáljam a generált kódot?"

---

### Staff

"Hogyan változtatja meg az AI az architektúrát?"

---

### Principal

"Hogyan változtatja meg az AI a szervezetet?"

---

### CTO

"Hogyan változik a cég versenyképessége?"

Valójában öt különböző beszélgetés zajlik egyszerre.

---

# A hiányzó réteg

A legtöbb szervezetben hiányzik egy

> **Engineering Translation Layer**

Ez fordítja le

- a stratégiai döntéseket operatív döntésekké,
- és az operatív tapasztalatokat stratégiai tanulságokká.

Példa:

A chapter kimondja:

> "Használjunk AI-t."

Ez még nem használható.

A fordító réteg ebből csinálja:

- Bronze pipeline-ban generálhatunk unit teszteket.
- Silver pipeline-ban SQL csak review mellett generálható.
- Gold rétegben két reviewer kötelező.

Na ez már mérnöki iránymutatás.

---

# A cél nem AI Community

Hanem

# Engineering Thinking Lab

vagy

# Engineering Atlas

---

Nem technológiát tanítani.

Hanem

**közös mentális modelleket építeni.**

---

# Az origó

Minden beszélgetés ugyanabból indul.

Nem a titulusból.

Hanem ebből:

> **Milyen problémát próbálsz megoldani?**

Ez minden szerepkörre igaz.

---

# A közös térkép

```text
                    Miért?
             (üzleti érték)

                    ▲
                    │
                    │
      Kinek?        │        Hogyan?
 (stakeholderek)    │     (technológia)
                    │
                    │
                    ▼
                Mit?
            (artefaktum)
```

Minden téma elhelyezhető ezen.

---

# A tudástérkép

```text
AI

↓

Kód

↓

Artefaktum

↓

Rendszer

↓

Platform

↓

Üzleti folyamat

↓

Emberi érték
```

Minden szinten léteznek

- dilemmák
- minták
- anti-patternök
- esettanulmányok
- nyitott kérdések

---

# Nem dokumentáció

Hanem kérdésgyűjtemény

Például.

## Artefaktum

- Mitől jó egy artefaktum?
- Mikor túl nagy?
- Mikor kell törölni?
- Mikor válik technikai adóssággá?
- Milyen metrikákat mérjünk?

---

## Platform

- Ki a platform ügyfele?
- Mitől lesz platform?
- Mikor túl általános?
- Mitől lesz framework?

---

## AI

- Mit gyorsít?
- Mit lassít?
- Mit változtat meg?
- Hol növeli a komplexitást?
- Hol csökkenti?

---

A válaszok változnak.

A jó kérdések sokkal tovább élnek.

---

# Minden beszélgetés koordinátát kap

Például.

## Prompt Engineering

```text
Szerepkör:
Junior–Senior

Terület:
Mindenki

Absztrakció:
Kód
```

---

## Data Contract

```text
Szerepkör:
Senior

Terület:
Data

Absztrakció:
Rendszer
```

---

## ROI

```text
Szerepkör:
Manager

Terület:
Product

Absztrakció:
Üzlet
```

Így mindenki tudja

- nekem szól?
- csak értenem kell?
- én vagyok a célközönség?

---

# A beszélgetések formátuma

Nem előadások.

Hanem közös gondolkodás.

```text
30 perc

↓

1 dilemma

↓

15 perc vita

↓

15 perc összegzés

↓

Nyitott kérdések
```

Nem PowerPoint.

Nem Copilot demó.

Nem "best practice".

---

# A kurátor szerepe

A legfontosabb ember nem az előadó.

Hanem a kurátor.

Ő nem válaszokat ad.

Hanem kapcsolatokat épít.

Például.

Valaki felveti:

> AI Code Review

Kapcsolódó témák:

- Ownership
- Conway's Law
- Architecture
- Technical Debt
- ROI
- Team Topologies

Így idővel kialakul egy

**Engineering Knowledge Graph**.

---

# Alacsony karbantartási igény

Minden téma maximum egy oldal.

```text
Mi ez?

↓

Miért fontos?

↓

Milyen dilemmák vannak?

↓

Kapcsolódó témák

↓

Nyitott kérdések
```

Nincs százoldalas dokumentáció.

Nincs kötelező guideline.

Csak egy élő tudástérkép.

---

# A végső cél

Nem az, hogy mindenki ugyanúgy gondolkodjon.

Hanem hogy mindenki megtalálja

- hol van a térképen,
- mit lát,
- mit nem lát,
- kitől tud tanulni,
- és hogyan kapcsolódik a munkája a teljes rendszerhez.

---

# Alapelv

> **Ne tudást gyűjtsünk, hanem közös mentális modelleket építsünk.**

A technológiák, AI-eszközök és keretrendszerek folyamatosan változnak.

A közös gondolkodási modellek sokkal lassabban.

Ezért nem egy újabb AI workshopra van szükség.

Hanem egy olyan mérnöki műhelyre, amely segít közös nyelvet kialakítani különböző szerepkörök, szakterületek és absztrakciós szintek között.

Ha ez sikerül, akkor nemcsak az AI-eszközök használata lesz jobb.

Hanem maga a mérnöki döntéshozatal, a kommunikáció és végső soron az üzleti értékteremtés is.
