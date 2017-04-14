### Mål

Efter denna övning ska du kunna:

- Identifiera `<head>` och `<title>` taggar
- Beskriv ordningen av dessa taggar
- Beskriv varför dessa taggar är viktiga
- Förklara var texten i `<title>`-taggen används
- Identifiera `DOCTYPE` instruktion
- Förklara varför det så kallade `DOCTYPE` instruktionen används
- Veta om hur man kan anpassa ett HTML-dokument att förstå och kunna visa svenska tecken (åäö)

### Exempel

HTML-dokument måste innehålla en kropp, *body*, och ett **huvud**-avsnitt. Huvudet innehåller icke-synliga element som webbläsaren eller sökrobotar kan behöva.

Åtminstone måste du inkludera deN så kallade `<title>`-taggen som definierar titeln på HTML-dokument. Titeln används på några platser:
- I webbläsarens namnlist och bokmärkesmenyn
- Resultat på sökmotorer

Här är en titt på ett simpelt HTML-dokument med ett _huvud_ och en _titel_:

```html
<html>
  <head>
    <title> en iögonfallande Titel </title>
  </head>
  <body>
    Mer HTML går här.
  </body>
</html>
```

Vi måste ha dessa element på plats för att följa HTML5 standarder. Och för att deklarera vår sida som ett HTML5-dokument, vi sätter ytterligare en tagg: `DOCTYPE` i toppen, så här:

```html
<! DOCTYPE html>
<html>
  <head>
   
   ....
```

Till skillnad från andra taggar vi har arbetat med så är `DOCTYPE` inte en HTML-tagg. Det är en speciell webbläsare instruktion som visar vilken typ av dokument det är. Detta hjälper webbläsare gör dina sidor snabbare eftersom de hoppa över den process som bestämmer vilken version av HTML dokumentet kräver (i detta fall, vi vet att det är 5).

#### Meta-taggar
För att webbläsaren ska kunna förstå och tolka svenska tecken måste vi tala om det för den. Det gör vi genom att lägga till en så kallad **meta**-tagg `<meta>`. Meta-taggar tillhandahåller information om hemsidan till webbläsaren och sökmotorer. För att webbläsaren ska förstå svenska måste vi lägga till en meta-tagg med attributet `charset` med värdet `utf-8` som är ett charset, en bas med de bokstäver som skall användas.

``` 
<meta charset="utf-8">
```


### Övning
1. Öppna `index.html`
2. Lägg `<head>` taggar till dokumentet.
3. Lägg till en titel för dokumentet.
4. Lägg till `DOCTYPE` instruktion.
5. Lägg till meta-taggen som kan förstå svenska tecken.
5. Spara och uppdatera webbläsaren för att se förändringarna. **Titta särskilt noga efter flikens namn.**
