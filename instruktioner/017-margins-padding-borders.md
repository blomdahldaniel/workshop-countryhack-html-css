### Mål

Efter denna övning ska du kunna:

- Förstå skillnaden mellan marginaler, padding och borders
- Förklara CSS Box Model
- förstå skillnaden mellan `<span>` och `<div>` taggar
- Använd `float` att göra elementen snäpper till sidan av skärmen

### Exempel

Denna kurs använder CSS för relativt enkla layouter. När du börjar använda mer avancerade layouttekniker, måste du förstå ** CSS Box Model **.

Lådan modell följer dessa regler:

1. `height` och` width` anges i en CSS-regel gäller själva innehållet.
2. Allt innehåll är omgiven av en kant, som kan vara osynlig.
3. ** Padding ** representerar utrymmet mellan border och innehållet.
4. ** Marginal ** representerar utrymme utanför border, som då skjuter bort andra CSS-boxar.

CSS box modell attribut är `margin`,` border`, `padding`,` height` och `width`. Och mer specifika versioner av dessa attribut finns: `margin-top`, `padding-right`, etc.

Det är vanligt att använda en `<div>`-tagg för att gruppera element tillsammans i en låda. Och du kan ändra lådan med CSS så här:

```css
div {
  bredd: 500px;
  padding: 5px;
  kant: 2px fast hotpink;
  margin: 15px;
}
```

En `<div>` är som en `<span>` som gäller för ett helt block av innehåll. Men en `<div>` hamnar automatiskt på en ny rad vilket inte en span gör.

### CSS ett utvecklande språk
CSS är ett väldigt gammalt språk som till en början inte alls var anpassat för att ha menyer, modaler och hemsidor så som våra hemsidor ser ut idag. Därför har det länge varit svårt och krångligt att få mer avancerade och dynamiska layouter att bli som man vill. Men eftersom CSS är ett utvecklande ständigt levande språk har det nu kommit uppdateringar som gör det hela lite enklare.

Om du vill lära dig mer om hur man positionerar och strukturerar responsivt innehåll kan du lära dig mer om **flexbox**.

### Övning
1. Öppna `index.html`.
- Lägg `<div>` taggar runt `<p>`-taggarna med den inledande texten.
- Ta bort `info` klassen från `p`-taggarna och sätt istället på den omringande div-taggen
2. Öppna `main.css`.
3. Lägg till en ny CSS-regel för alla `div` väljaren och följande egenskaper:
- Sätt `width` till`240px`.
- Sätt `padding` till`10px`.
- Sätt `border` till`5px solid #fab555`.
- Sätt `margin` till`10px`.
- Sätt `margin-right` till`50px` att åsidosätta högermarginalen.
- Nu blir sidan väldigt avlång, vi vill att det ska få platts innehåll bredvid får lilla info-ruta. Vi ska skapa en `div`-klassväljare som får heta `float-left`:

```css
div.float-left {
  float: left;
}
```

> Denna klassväljare gäller endast då `float-left` klassen tilldelats en `<div>`tagg.

4. Öppna `index.html`.
- Lägg till `class="float-left"` till den `<div>` som omsluter de tre info-punkterna.
