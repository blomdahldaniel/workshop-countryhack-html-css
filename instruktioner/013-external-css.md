### Mål

Efter denna övning ska du kunna:

- Förklara skillnaden mellan intern CSS och extern CSS
- Utför en konvertering från intern CSS till extern CSS

### Exempel

Din CSS ingår i `index.html`-filens ` <style>`-taggar, så det gäller bara denna enda sida. (Du kan testa att trycka på länken till din **Profil-sida** och se att den inte är uppdaterad med css.) Men de flesta webbplatser återanvänder sin styling på * alla * sidor. Därför så brukar man som webbutvecklare motverka användning av `<style>` taggar och istället försöka skriva styling som går att återanvända.

Istället för intern/inline styling så rekommenderar ska/kan man istället använda separata/externa CSS-filer. Denna externa CSS-fil kan vi importera/referera genom en `<link>` HTML-tagg.

Det så kallade `<link>`-taggen definierar en relation mellan HTML-dokumentet och en annan fil. Liksom `<style>`-taggen hör den hemma inom  `<head>`-taggen i ditt HTML-dokument. Såhär kan referera till en CSS-fil:

```html
<link rel="stylesheet" type="text/css" href="filename.css">
```

- `rel` är en förkortning för * relation *. I det här fallet har vi ange en "stylesheet"-relation.
- `type` anger vilken _Internet media type_ som filen ska tolkas som. För CSS, är mediatypen: `text/css`.
- `href` tar emot länken till filen, precis som i `<img href="images/banan.png"">`.

Vi kan döpa CSS-filer hur som helst, men granska dessa [CSS namn-riktlinjer] (http://webdesign.about.com/od/css/f/blfaqcssfilenam.htm).

### Övning

I den här övningen ska du flytta den interna CSS-en till en extern fil. `index.html` ska alltså inte ha några `<style>`-taggar.

1. Skapa en fil med namnet `main.css` i en ny mapp som heter `css` som ligger i mappen `/public`
1. Kopiera allt inom `<style>`-taggarna från `index.html`.
1. Klistra in stylingen till filen `main.css`
1. Gå tillbaka till `index.html`
1. Ta bort `<style>`-taggarna (och allt däremellan) och nu ska du med hjälp av en `link`-tagg länka ihop din din HTML-fil till din CSS-fil (`href="./css/main.css"``)
1. Testa att lägga till samma `link`-tagg i din profil-sida för att se hur även den hemsidan kan påverkas av den generella styling som du skapat.
1. Spara och uppdatera webbläsaren för att se förändringarna. **Se så att allt fortfarande fungerar som det skall!**
