### Mål

Efter denna övning ska du kunna:

- definiera skillnaden mellan ordnade och oordnade listor
- Kunna förstå och använda taggarna `<ol>`, `<ul>`, `<li>`

### Exempel

På vår startsida i `index.html` så har vi just nu lite kort information om CH. Men nu vill vi lägga till en lista med några av de turneringar som vi anordnar.

HTML stödjer två typer av listor: ordnade listor ( `<ol>`) och oordnade listor (`<ul>`). Varje listobjekt definieras av en `<li>`tag.

----

Här är en ordnad lista:

```html
<h3>Vinnare på Curve Feever</h3>
<ol>
  <li>Krubb</li>
  <li>Y-front</li>
  <li>Blodluvan</li>
</ol>
```

Dessa medför en räknande rangordning

<ol>
  <li>Krubb</li>
  <li>Y-front</li>
  <li>Blodluvan</li>
</ol>

----

Här är en oordnad lista:

```html
<h3>Våra turneringar</h3>
<ul>
  <li>CS</li>
  <li>LoL</li>
  <li>Soldat</li>
  <li>Curve fever</li>
  <li>Rocket league</li>
  <li>Overwatch</li>
  <li>Hearthstone</li>
  <li>Smash</li>
  <li>Fifa</li>
  <li>Mario kart</li>
  <li>Duckhunt</li>
  <li>Ice climber</li>
  <li>BIT Frenzy - Femkamp i retrospel</li>
  <li>bomberman</li>
  <li>Mario football</li>
  <li>Sten, sax, påse</li>
</ul>
```

Dessa är oftast återges med punkter, så här:

<ul>
  <li>CS</li>
  <li>LoL</li>
  <li>Soldat</li>
  <li>Curve fever</li>
  <li>Rocket league</li>
  <li>Overwatch</li>
  <li>Hearthstone</li>
  <li>Smash</li>
  <li>Fifa</li>
  <li>Mario kart</li>
  <li>Duckhunt</li>
  <li>Ice climber</li>
  <li>BIT Frenzy - Femkamp i retrospel</li>
  <li>bomberman</li>
  <li>Mario football</li>
  <li>Sten, sax, påse</li>
</ul>

### Övning

1. Öppna `index.html`
2. Lägg till en underrubrik **Turneringar** och lägg till minst 5 av våra turneringar, varje spel ska vara inuti var sin `<li>`-tagg i en osorterad lista.
3. Spara och uppdatera webbläsaren för att se förändringarna.
