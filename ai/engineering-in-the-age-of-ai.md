# A szoftverfejlesztés fókusza eltolódott

Régen a szűk keresztmetszet ez volt:

> Ki tud egyáltalán működő szoftvert írni?

Ma egyre inkább ez:

> Ki tud jó problémát választani?

és

> Ki tudja fenntarthatóan fejleszteni?

Ez óriási különbség.

AI előtt a programozás volt drága.

AI után a döntések lettek drágák.

---

# Az AI nem a kódot gyorsította fel

Hanem a **változtatás sebességét**.

Ez szerintem egy teljesen más gondolkodásmódot igényel.

Ha tízszer gyorsabban lehet változtatni, akkor tízszer gyorsabban lehet:

- rossz architektúrát építeni,
- rossz feature-t fejleszteni,
- rossz dokumentációt generálni,
- rossz API-t publikálni.

A sebesség önmagában nem érték.

---

# A valódi szűk keresztmetszet

Ha mérnöki szemmel nézzük, a pipeline ma inkább így néz ki:

```text
Üzleti probléma
        │
        ▼
    Megértés
        │
        ▼
   Priorizálás
        │
        ▼
  Architektúra
        │
        ▼
   Fejlesztés
        │
        ▼
      Teszt
        │
        ▼
  Üzemeltetés
        │
        ▼
 Üzleti eredmény
```

Az AI gyakorlatilag csak ezt gyorsította fel:

```text
Architektúra?
      │
      ▼
 Fejlesztés
      │
      ▼
    Teszt
```

Viszont a többi lépés ugyanannyira emberi maradt.

---

# Ezért beszél mindenki a Copilotról

Mert azt könnyű demonstrálni.

> "Nézd, 20 másodperc alatt írt egy függvényt."

Ez látványos.

De senki nem tud bemutatni egy videót arról, hogy:

> "Így döntöttük el, hogy ezt a feature-t inkább meg sem építjük."

Pedig lehet, hogy az utóbbi spórolt meg három hónapot.

---

# Amit hiányolsz, annak már neve is van

Valójában több tudományterület metszetéről beszélsz:

- Systems Thinking
- Lean Product Development
- Value Stream Management
- Engineering Management
- Software Economics
- Socio-technical Systems
- Architecture Governance

Az AI csak egy új szereplő ezekben.

---

# Szerintem a beszélgetés fókusza nem az AI kellene legyen

Hanem például:

> **Mit tekintünk értéknek az AI-korszakban?**

vagy

> **Mit optimalizálunk?**

Mert ha a KPI:

- PR-ek száma,

akkor AI-val rengeteg PR lesz.

Ha a KPI:

- üzleti eredmény,

akkor lehet, hogy feleannyi fejlesztés készül.

---

# Egy érdekes modell

Én valahogy így bontanám fel:

```text
AI
 │
 ▼
Artefaktum
 │
 ▼
Rendszer
 │
 ▼
Üzleti folyamat
 │
 ▼
Emberi eredmény
```

Minden szinten más mérőszám kell.

| Szint | Lehetséges mérőszámok |
|--------|------------------------|
| AI | Tokenek, válaszidő (latency) |
| Artefaktum | Kódsorok (LOC), tesztlefedettség |
| Rendszer | Karbantarthatóság, regressziók, komplexitás |
| Üzlet | ROI, költség, lead time |
| Ember | Ügyfél-elégedettség, hibaszám, stressz |

Ma szerintem sok szervezet az első két szintet méri.

A probléma viszont az utolsó kettőn jelentkezik.

---

# Mit tudna adni egy beszélgetéssorozat?

Nem oktatás lenne.

Hanem **közös gondolkodás**.

Lehetséges témák:

1. Mi számít valódi értéknek?
2. Mit nem kellene lefejlesztenünk?
3. Hogyan mérjük egy feature sikerét?
4. Hogyan ismerjük fel a technikai adósságot még azelőtt, hogy létrejön?
5. Mennyi dokumentáció elég?
6. Mikor kell újratervezni, nem tovább javítani?
7. Hogyan használjuk az AI-t úgy, hogy ne csak több kódunk legyen?
8. Mikor mondjunk nemet egy fejlesztésre?

Ez már nem "AI workshop", hanem inkább **Engineering Governance** vagy **Software Strategy**.

---

# Mérnökinformatikusként milyen megoldások vannak?

Azt gondolom, három különböző időtávon lehet gondolkodni.

## 1. Operatív szint

Olyan gyakorlatok, amelyek csökkentik a kód- és dokumentációs túlburjánzást.

Például:

- kisebb változtatások,
- rövidebb életű feature branchek,
- kötelező törlési (deletion) szemlélet,
- egyszerűbb architektúrák,
- rendszeres refaktorálási kapacitás.

---

## 2. Taktikai szint

A siker mérésének átalakítása.

Nem azt kérdezni, hogy:

> "Mennyi kód készült?"

Hanem:

- Milyen üzleti hipotézist igazoltunk vagy cáfoltunk?
- Mennyivel csökkent egy folyamat ideje?
- Mennyivel nőtt az ügyfél-elégedettség?

---

## 3. Stratégiai szint

A fejlesztés fókuszát áthelyezni az eszközökről a döntésekre.

A legértékesebb mérnök nem feltétlenül az lesz, aki a leggyorsabban generál kódot.

Hanem az, aki felismeri:

- mit **nem** érdemes megépíteni,
- vagy hogyan lehet ugyanazt az üzleti célt egyszerűbben elérni.

---

# A központi felismerés

> **Az AI korában a szűk keresztmetszet már nem a kód előállítása, hanem a jó mérnöki döntések meghozatala.**

Ha ez igaz, akkor a következő években a legnagyobb versenyelőnyt nem azok a szervezetek szerzik meg, amelyek a legjobb AI-eszközöket használják.

Hanem azok,

- amelyek képesek a gyorsabb fejlesztést valódi értékteremtéssé alakítani,
- amelyek a technológia mellett termékgondolkodásra is fókuszálnak,
- amelyek mérik az üzleti eredményeket,
- és amelyek tudatosan kezelik a komplexitást.

Az AI csak felgyorsította a fejlesztést.

A valódi versenyelőnyt továbbra is az fogja meghatározni, hogy **milyen döntéseket hozunk, milyen problémákat választunk ki megoldásra, és milyen értéket teremtünk velük.**
