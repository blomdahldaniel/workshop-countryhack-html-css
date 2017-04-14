### Mål

Efter denna övning ska du kunna:

- Identifiera `<html>` och `<body>` taggar
- Förklara följden av dessa taggar
- Förklara funktionen av varje tagg

### Exempel

Texten som vi skrivit hittills tillhör det visuella innehållet i HTML-dokument. Detta kallas dokumentets **kropp**, `body` och är då också omgivet med `<body>` taggar.

Sektionen **body** är en del av ett HTML-dokument. Och ett HTML-dokument måste i sin tur omges av `<html>`-taggar, såhär:

```html
<html>
  <body>
    <h1>Rubrik för sidan!</h1>
    <p>Lite text till sidan, bla bla bla...</p>
  </body>
</html>
```

`<html>` indikerar början och `</html>` indikerar slutet av ett HTML-dokument.

Det kan tyckas konstigt och kanske omständligt, men dessa formateringsregler hjälper webbläsaren att visa dokumenten på rätt sätt. Utan dem kan webbläsare visa ditt innehåll felaktigt, kan ta längre tid att visa den, eller kanske inte visas alls.

#### Webbläsarens förståelse:
1. "Aha, detta är ett html-dokument"
2. "Och här är innehållet *bodyn* som ska visas upp"

### Övning
1. Öppna `index.html`
2. Placera `<html> 'och' <body>` taggar runt ditt innehåll.
3. Spara och uppdatera webbläsaren för att se förändringarna.
