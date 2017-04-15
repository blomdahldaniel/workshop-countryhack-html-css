### Mål

Efter denna övning ska du kunna:

- Uppmärksamma en väljare/selector
- Förklara vad en väljare/selector är
- Förklara skillnaden mellan "id" och "klass" selectors
- Använd selectors för att styla för alla delar av en enda typ
- Använd selectors för att styla för alla element med en viss klass
- Använd selectors för att styla på ett specifikt element
- Använd `<span>` för att styla ett element inuti ett annat

### Exempel

Vi har använt några ** väljare/selectors ** i vår CSS-fil:

- `body`
- `a`
- `img`
- `h1`
- `th`
- `table, td`

Väljare tillämpar regler för ett eller flera element. Det finns många typer av väljare ([här är en lista] (http://www.w3schools.com/cssref/css_selectors.asp)), men det finns tre huvudtyper väljar: element, klass och id.

** Element Väljare ** är de du redan har använt. De väljer alla HTML-element av en viss typ, som `p` eller `img`.

** Klass Väljare ** föregås av en punkt (`.`) definierar styling som du kan tillämpa på alla element, oavsett typ. Till exempel, om du gör en tidning eller blogg-hemsida, skulle du använda en klass-väljare för bildtexter som går under en bild. Du kan skapa CSS så här:

```css
.captionText {
    font-size: 11px;
    line-height: 14px;
    font-style: normal;
    font-family: Georgia, "Times New Roman", Serif;
}
```


Och då kan du tillämpa denna klass stil med hjälp av HTML `class` attribut, så här:

```html
<img src="images/ch-band.png" alt="CH-Band är ett av norra europas fläkigaste band.">
<p class="captionText">CH-Band är ett av norra europas fläkigaste band. Dom missar aldrig en chans att få äta ba... </p>
```

Du kan obegränsat antal klasser till ett element. Om du använder flera klasser så skiljs dom åt med ett mellanslag inom attributet `class`s value:  t.ex. `class="captionText orangeText underlinedText"`.

** ID Väljare **, som föregås av en hash (`#`) väljer ett specifikt element på sidan. Till exempel, om en sida har ett alert-stycke med viktig information, kan du definiera din styling såhär:

```css
#alert {
  color snow;
  background: salmon;
  border: 2px solid dimgray;
  font-weight: bold;
}
```

För att använda en ID-styling anger du det genom attributet `id`:

```html
<p id="alert"> Varning: Det finns risk för 100% awesomeness idag!</p>
```

`id` attribut är unika på varje sida. Till exempel, kan dokumentet ovan inte innehålla ett andra element med `alert` som dess` id`.

Om du vill styla delar av ett element så kan man använda sig av taggen `<span>` för att fästa attribut. Till exempel kanske du i din *alert* vill att procentvärdet skall stå med lite större text:

```css
# alert-percentage {
  font-size: 20px;
  font-weight: bold;
}
```

```html
<p id="alert"> Varning: Det finns risk för <span id="alert-percentage">100%</ span> awesomeness idag!</p>
```

Om du vill läsa mer kan du lära dig mer kan du experimentera här: [CSS Selector] (http://www.w3schools.com/cssref/trysel.asp)

### Övning

1. Öppna `main.css`.
1. Lägg till en `info` klassväljare (en klassväljare börjar med en punkt: `.`).
- Sätt dess `background` till `gray`.
- Sätt dess `font-weight` till`bold`.
- Sätt dess `padding` till`10px`.
1. Lägg till en `vga` ID väljare (en ID-väljare börjar med en hashtag  `#`).
- Sätt dess `letter-spacing` till`8px`.
- Sätt dess `padding` till`10px`.
- Sätt dess `text-transform` till `uppercase`.
- Sätt dess `background` till `blue`.
- Sätt dess `color` till `white`.
1. Öppna `index.html`.
- Lägg till info-klassen på de första info paragraferna.
- Lägg till `vga` som `id` attribut till en `span`-tagg som omger texten vga i rubriken.

