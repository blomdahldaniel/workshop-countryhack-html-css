### Mål

Efter denna övning ska du kunna:

- Definiera HTML
- Förstå en HTML-tagg
- Identifiera en HTML paragraf-tagg

### Exempel

HTML eller *Hypertext Markup Language*, beskriver en hierarki av visuella element som en webbläsare kan visa.

HTML ser oftast ut som _någorlunda_ läsbar text som men som omges av _taggar_. Man skapar taggar med hjälp av _krokodilmunnar_ `< >`, så här:

```Html
<exempeltagg>
    Att ha lanmössa bör man, annars dör man!
</exempeltagg>
```

De flesta taggar kräver både en **öppnings-** `<exempeltagg>` och en **stängnings**-tagg `</exempeltagg>`. En framåt snedstreck `/` markerar att taggen är en stängningstagg.

### Taggar
En tagg kan heta vad som helst och man kan döpa dom till vad som helst.
Men det finns några förbestämda taggar som webbläsaren vet hur den ska tolka och visa.
Det finns till exempel taggar för rubriker, paragrafer, bilder, inputs (formulär där man skriver in text osv.)

Man kan skapa sina egna taggar men det bästa är att först välja och använda de taggar som finns förutbestämda. 

En av de vanligaste taggarna är `<p>`, kort för engelskans *Paragraph*.

### Övning

1. Skapa en ny fil och döp den till `index.html`
1. Skriv `Hello World`.
1. Omringa `Hello World`-texten med öppnings- och stängnings-taggen för en `paragraph`.
1. Spara ändringarna.
1. Dubbelklicka på filen för att öppna den i webbläsaren.
