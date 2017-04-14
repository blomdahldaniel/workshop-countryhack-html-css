### Mål

Efter denna övning ska du kunna:

- Definiera en HTML-tabell
- Förstå och använda det så kallade `<table>`,`<th>`,`<tr> `och`<td>`taggar
- Konvertera listor till tabeller

### Exempel

Listor är bra för att visa en serie artiklar i en enda kolumn. Men viss information är bättre representerade på ett rutnät.

Till exempel är det svårt att uttrycka denna information i en enkel lista:

| Datum             | Spel              | Prispott  | Vinnare       |
| ----------------- |------------------ | --------- | ------------- |
| 13 April kl 18:00 | Counter-Strike    | 10.000 kr | Krubbs pojkar |
| 14 April kl 13:37 | Curve Feever      | Y-fronts gamla kalsonger | Blodluvan |
| 15 April kl 16:00 | Mario Football    | Äran      | Los Gurk0s |

`<table>`fungerar på samma sätt som` <ol>`och '<ul>', men med lite mer hierarki. Här är taggarna du normalt hittar på insidan:

- '<tr>`( "tabellrad") omger varje rad
- '<th>`( "table header") omger varje rubrikcell
- '<td>`( "tabelldata") omger varje vanlig cell

Här är HTML som producerar ovanstående exempel. Lägg märke till hur rubrikcellerna är utformade med mer betoning än datacellerna.

```html
<table>
  <tr>
    <th>Datum</th>
    <th>Spel</th>
    <th>Pris</th>
    <th>Vinnare</th>
  </tr>
  <tr>
    <td>13 April kl 18:00</td>
    <td>Counter-Strike</td>
    <td>10.000 kr</td>
    <td>Krubbs pojkar</td>
  </tr>
  <tr>
    <td>14 April kl 13:37</td>
    <td>Curve Feever</td>
    <td>Y-fronts gamla kalsonger</td>
    <td>Blodluvan</td>
  </tr>
  <tr>
    <td>15 April kl 16:00</td>
    <td>Mario Football</td>
    <td>Äran</td>
    <td>Los Gurk0s</td>
  </tr>
</table>
```

### Övning

1. Öppna `index.html`
2. Gör ett schema över lördag dags aktiviteter för CS, LoL och FIFA. Hämta informationen från [Countryhacks kalender](https://countryhack.se/calendar/index.php)

Tabellen ska ha följande kolumner:
- Datum (Ex. "15 april")
- Tid Start (Ex. "10:00")
- Tid Slut (Ex. "11:00")
- Turnering (Ex. "Slutspel - FIFA")


3. Spara och uppdatera webbläsaren för att se förändringarna.
