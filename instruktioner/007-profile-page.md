### Mål

Efter denna övning ska du kunna:

- Tillämpa dina kunskaper om HTML-dokumentets grundläggande strukturer.
- Använd paragrafer `<p>`, rubriker `<h1>, <h2>...` och bilder för att bygga en grundläggande hemsida till ditt gamer-alias.

### Uppgift

Nu ska vi skapa en hemsida som presenterar dig och ditt gamer-alias om du har något. Vi ska skapa en profilsida där dina fans kan läsa mer om vem du är. Profilen ska innehålla en bild, en rubrik följt av text med grundläggande information om dig / ditt gamer-alias.

Sidan ska också ha minst en underrubrik som heter "Mina spel"
Där skall du skriva 5 spel som du tycker om att spela.

> Tips: om du vill använda egna bilder kan du spara ner dom och lägga dom inuti `public/images`

### Instruktioner

1. Skapa och öppna en fil med namnet `profile.html` i mappen `/public`
2. Tillsätt nödvändig HTML struktur: `doctype`,`html`, `head`, `meta`-med charset, body osv. osv..
3. Välj en titel för din profil, namnet på din sida.
4. Använd en kombination av bilder, rubriker och stycken för att presentera dig. Till exempel:
- Profilbild
- Rubrik (ditt nick)
- Paragraph (om dig!)
- Underrubrik (Mina spel)
- Skriv 5 spel som du tycker om att spela, varje spel ska ha sin egen `<p>`-tagg.

För att förhandsgranska ditt arbete, öppna `index.html` och lägga till denna kod längst ner i din `<body>` för att skapa en länk till din profil:

```html
<p><a href="profile.html">Till min profil</a></p>
```

> Du lär dig mer om länkar senare.
