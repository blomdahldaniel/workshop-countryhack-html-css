### Mål

Efter denna övning ska du kunna:

- Definiera "hyperlänk"
- Förstå och använda en så kallade tag `<a>`

### Exempel

Tabeller är bra för att visa en hel del data, men vad händer om användaren vill få mer information? Kunna läsa mer om varje turnering?

Då kan vi använda länkar för att leda vidare till andra hemsidor

En länk har följande format:

```html
<a href="http://www.google.com">Google</a>
```

Det ser ut så här när återges:

> <a href="http://www.google.com">Google</a>

Det så kallade `href` _-attributets_ tagg innehåller en relativ eller absolut URL. Texten mellan taggarna representerar länken titel. `href` är likt så som `src` i  `<img>`-taggen.

### Övning

1. Öppna `index.html`
1. Lägg till en kolumn i tabellen som heter **Länk** där skall det finnas en länk med texten _Läs mer_ och adressen skall peka direkt till countryhacks turneringssida för just det aktuella spelet. ([Se alla CHs turneringar här](https://countryhack.se/?page=tournament))
1. Spara och uppdatera webbläsaren för att se förändringarna.
