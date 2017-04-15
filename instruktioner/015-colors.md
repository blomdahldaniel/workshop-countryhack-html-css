### Mål

Efter denna övning ska du kunna:
- Känna igen en RGB-färg
- Känna igen en hex-färg
- Förklara skillnaden mellan hex- och RGB- färger
- Tilldela färger till olika element

### Exempel
Vi har hittills använt färger som `black` och`blue`. Men det finns miljontals färger som inte har ett namn.

På datorer så skapas färger genom att blanda rött, grönt och blått. Det finns två sätt att definiera dessa färger. Den första är en ** röd / grön / blå (RGB) Triplet Color **. Med den här syntaxen kan mäta mängden av varje färg på en skala från 0 till 255. Till exempel:

Här är _ren_ röd: bakgrund: `rgb(255,0,0)

Här är _ren_ grön: bakgrund: `rgb(0,255,0)

Här är magenta: bakgrund: `rgb(255.0.255)

Här är en djupblå: bakgrund: `rgb(34,55,90)

Och en ljusrosa: bakgrund: `rgb(250.202.222)


Man kan alltså koppla ihop och skapa många olika färger. Det finns många hemsidor som har färgpaletter [color-hex] (http://www.color-hex.com/color-palettes/).

En del grafiska formgivare tycker att RGB-färger är lättare att läsa, medan vissa föredrar hex färger. En ** hex-färg ** uttrycker exakt samma information men på ett annat sätt. Det är en _sex-teckenkod_ efter en `#`.

Här är _ren_ röd färg i hex: `#ff0000`

De två första tecknen representerar röd, nästa två gröna och de två sista blå. Om du vill kan du [Läs mer om hexadecimal numrering] (http://www.mathsisfun.com/hexadecimals.html), men det viktigaste att komma ihåg är att de är som vanliga siffror, men A-F representerar 10-15 (F är den högsta hexadecimala siffran).

> Lägg märke till att ff` direkt motsvarar `255`. Det beror på att `f` (15) i den vänstra platsen multipliceras med basen, 16, och 'f` på rätt ställe multipliceras med 1. Tillsammans blir det: 15 x 16 + 15 x 1 = 255.

### Övning

Nu ska vi färga om sidan lite...

1. Öppna `main.css`.
2. Ställ in `body` `background` `#f5f5f5`, body-textfärgen och tablerubrikens border till `#424242` Sätt också `body` `font-size` till `18px` och `font-weight` till `lighter`.
4. Ställ in länkens färg till `#2991c7`.
5. Ställ in `h1` färg till` #fab555`.
6. Ställ in `.info` bakgrundsfärg och tabellens kantfärg till `#ffffff`.
6. Ställ in `#vga` bakgrundsfärg till `#2991c7`.
