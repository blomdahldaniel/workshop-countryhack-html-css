### Mål

Efter denna övning ska du kunna:

- Identifiera attribut för taggar
- Identifiera taggar som inte skall stängas
- Förklara skillnaden mellan absoluta och relativa URL: er
- Beskriv taggen `<img>`
- Förklara attributen `alt` och `src`
- Förklara varför det så kallade `alt` attributet är viktigt

### Exempel

Låt oss piffa upp saker lite genom att lägga till en bild. Vi lägger till bilder med hjälp av `<img>`-taggen. Den skiljer sig från andra taggar vi har använt på två sätt:

1. Det kräver **attribut**
2. Vi behöver inte stänga den (ingen `</img>` i slutet)

En bildtagg kan se ut så här:

```html
<img src="./images/countryhack-vga-logga.png" alt="Countryhack är en fläskig datorspelsfestival!">
```

`src` = _source_ anger webbadressen till den bild som ska visas. Exemplet ovan är en _relativ_ URL, men du kan använda absoluta URL: er som, `http://example.com/images/flower.png`.

> Du kan [läsa mer om relativa vs. absoluta webbadresser på webreference] (http://www.webreference.com/html/tutorial2/3.html).

`alt`=_alternate_ (alternativ) ger en kort beskrivning av bilden. Om bilden inte kan visas så kommer webbläsaren istället visa texten som skrivs i `alt`-attributet. Alt-taggen kan används vid olika tillfällen, t.ex:

- Användaren har en dålig anslutning
- Användaren är synskadad och använder sig av röststyrning för att navigera sig runt på hemsidan
- Användaren har en gammal webbläsare som inte stöder bilder
- Bilden kan inte hittas (bruten länk)

### Övning

1. Öppna `index.html`
2. Lägg till en bild ovanför rubriken inom den så kallade `<body>`-taggen.
- Du kan ta en valfri bild från internet eller välja countryhack-loggan som finns under `public/images`. Den bilden får då en relativ adress: `./images/countryhack-vga-logga.png`.
- Se till att ge en `alt` attribut med din bild.
3. Spara och uppdatera webbläsaren för att se förändringarna.
