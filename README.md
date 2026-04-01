# ProjectLibre veebileht

## Eesmärk

Veebileht selgitab, kuidas kasutada ProjectLibre programmi projekti ajakava haldamiseks. Leht on loodud õppematerjalina, et aidata kasutajatel mõista kalendri, tööaja ja diagrammide seadistamist ning visualiseerimist ProjectLibre keskkonnas. Kõik lehed on omavahel seotud ja võimaldavad kiiret navigeerimist.

---

## Lehtede kirjeldus

### index.html – Kalender

See leht keskendub ProjectLibre kalendri seadistamisele ja muutmisele. Kasutaja saab samm-sammult juhiseid, kuidas avada kalendrit, muuta tööaega, määrata mitte-tööpäevi ning lisada eripäevi. Iga samm on selgitatud loetavalt ja praktiliste näidetega.

**Põhifunktsioonid:**
- Kalendri avamine ja valimine
- Tööaja muutmine (nt tööpäevade ja -tundide seadistamine)
- Mitte-tööpäevade ja pühade lisamine
- Eripäevade haldamine
- Kalendri rakendamine projektile

**Näide navigeerimismenüüst (index.html):**
```html
<nav>
  <a href="index.html">Kalender</a>
  <a href="diagramm.html">Diagrammid</a>
</nav>
```

**Näide sammude kirjeldusest markdowni loeteluna:**
- Ava ProjectLibre ja vali projekt
- Mine menüüsse **Project** > **Calendar**
- Muuda tööaega ja määra eripäevad
- Salvesta muudatused

---

### diagramm.html – Diagrammid

Diagrammide leht tutvustab, kuidas ProjectLibre abil visualiseerida projekti ajakava ja ülesannete kestusi. Lehel on juhised Gantt diagrammi kasutamiseks, ülesannete ajakava kuvamiseks ning ressursside vaate kasutamiseks. Lisaks on toodud näiteid, kuidas diagrammid aitavad projekti paremini planeerida ja jälgida.

**Põhifunktsioonid:**
- Gantt diagrammi loomine ja kohandamine
- Ülesannete ajakava visuaalne esitamine
- Ressursside vaate kasutamine
- Diagrammide eksportimine või jagamine

**Näide diagrammi sektsioonist (diagramm.html):**
```html
<section>
  <h2>Gantt diagramm</h2>
  <img width="720" height="471" src="images/gantt_example.png" alt="Gantt diagrammi näide">
  <p>Gantt diagramm võimaldab ülesannete ajakava visuaalselt jälgida.</p>
</section>
```

**Näide markdowni tabelist, kuidas ülesandeid planeerida:**

| Ülesanne         | Alguskuupäev | Lõppkuupäev | Vastutaja |
|------------------|--------------|-------------|-----------|
| Planeerimine     | 01.04.2026   | 03.04.2026  | Mari      |
| Teostus          | 04.04.2026   | 10.04.2026  | Jüri      |
| Testimine        | 11.04.2026   | 13.04.2026  | Kati      |

---

## Navigeerimine

Veebilehel on menüü, mis võimaldab liikuda erinevate lehtede vahel. Menüüd kasutatakse igal lehel, et tagada mugav ja kiire liikumine.

**Näide menüüst:**
```html
<nav>
  <a href="index.html">Kalender</a>
  <a href="diagramm.html">Diagrammid</a>
</nav>
```

---

## Kokkuvõte

Veebileht aitab kasutajal mõista ProjectLibre programmi põhifunktsioone ja ajakava visualiseerimist. Struktureeritud juhendid, näited ja tabelid muudavad õppimise lihtsamaks ning toetavad praktilist kasutamist.
