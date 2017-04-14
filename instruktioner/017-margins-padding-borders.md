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
- Lägg `<div>` taggar runt det så kallade <p> `taggar med den inledande texten.
2. Öppna `main.css`.
3. Lägg till en ny CSS-regel in med det så kallade div` väljaren och följande egenskaper:
- Sätt `width` till`240px`.
- Sätt `padding` till`10px`.
- Sätt `border` till`5px solid white`.
- Sätt `margin` till`10px`.
- Sätt `margin-right` till`60px` att åsidosätta högermarginalen.
- Lägg märke till att den nya styling skjuter tabellen långt ner. För att lösa detta, lägg till en `div`-klassväljare som kallas `float-left`:

```css
div.float-vänster {
  float: vänster;
}
```

> Denna klassväljare gäller endast då `float-left` klassen tilldelats en `<div>`tagg.

4. Öppna `index.html`.
- Lägg `class = "float-vänster"` till `<div>`.
