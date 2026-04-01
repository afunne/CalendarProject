# ProjectLibre veebileht

## Eesmärk

Veebileht selgitab, kuidas kasutada ProjectLibre programmi projekti ajakava haldamiseks. Leht on loodud õppematerjalina, et aidata kasutajatel mõista kalendri, tööaja ja diagrammide seadistamist ning visualiseerimist ProjectLibre keskkonnas. Kõik lehed on omavahel seotud ja võimaldavad kiiret navigeerimist.

---

## Lehtede kirjeldus

### index.html – Kalender

<img width="1440" height="703" alt="{7F190A31-B5CA-4DAB-BC65-FFB8C678F8DC}" src="https://github.com/user-attachments/assets/63b2723a-4ae1-4b5e-bb4f-0b92b19acaa2" />

See leht keskendub ProjectLibre kalendri seadistamisele ja muutmisele. Kasutaja saab samm-sammult juhiseid, kuidas avada kalendrit, muuta tööaega, määrata mitte-tööpäevi ning lisada eripäevi. Iga samm on selgitatud loetavalt ja praktiliste näidetega.

> [!TIP] Näpunäide
> Kui muudate tööaega, kontrollige kindlasti, et kõik projektis olevad ülesanded kasutaksid õiget kalendrit!

> [!NOTE]
> Useful information that users should know, even when skimming content.

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

> [!IMPORTANT] Oluline
> Kui lisate eripäevi, veenduge, et need ei kattuks juba määratud pühadega – see võib põhjustada ajakavas vigu!

---

### diagramm.html – Diagrammid

<img width="1440" height="707" alt="{3298F44F-18C1-4C48-A1C7-0A4256E47404}" src="https://github.com/user-attachments/assets/9ab104cc-3d73-430a-a927-34c8e2bea962" />

Diagrammide leht tutvustab, kuidas ProjectLibre abil visualiseerida projekti ajakava ja ülesannete kestusi. Lehel on juhised Gantt diagrammi kasutamiseks, ülesannete ajakava kuvamiseks ning ressursside vaate kasutamiseks. Lisaks on toodud näiteid, kuidas diagrammid aitavad projekti paremini planeerida ja jälgida.

> [!NOTE] Märkus
> Gantt diagramm annab kiire ülevaate kogu projekti ajakavast ja aitab tuvastada võimalikke kattuvusi või viivitusi.

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

> [!WARNING] Hoiatus
> Kui ülesandeid ei ole õigesti ajastatud, võib diagramm olla eksitav – kontrollige alati, et kõik kuupäevad oleksid õiged!

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

> [!TIP] Näpunäide
> Kasutage navigeerimismenüüd, et kiiresti liikuda erinevate funktsioonide ja lehtede vahel.

---

## Kokkuvõte

Veebileht aitab kasutajal mõista ProjectLibre programmi põhifunktsioone ja ajakava visualiseerimist. Struktureeritud juhendid, näited ja tabelid muudavad õppimise lihtsamaks ning toetavad praktilist kasutamist.
