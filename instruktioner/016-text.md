### Mål

Efter denna övning ska du kunna:
- Förklara skillnaden mellan pixlar och ems
- Använd `font` och `text` attribut för att styla texter
- Använd `text-shadow` CSS attribut för att skapa skugga

### Exempel

Du har redan sett några sätt att stil text:

- Du kan ändra `color`
- Du kan centrera den genom att ändra dess `text-align` property
- Du kan ändra `font-family`,`font-size`, `font-weight`
- Du kan ändra avståndet mellan bokstäver med `letter-spacing`

Det finns fler sätt att utformar text - alldeles för många för att inkludera i denna övning. Men här är några:

----

Vi har angett storlekar i * pixlar * (PX), som räknar antalet prickar på en datorskärm. Många designers föredrar att ange textstorlekar i * ems *:

```css
p {
  font-size: 0.75em;
}
```

Här är ett exempel:

> <p> Denna text är på väg att få `<span style="font-size: 0.75em"> mindre </span> </p>`

1 em motsvarar din del standardtextstorlek. I ovanstående exempel, framfört vi den mindre texten vid 75% av den normala storleken.

----

Radavståndet påverkar avståndet mellan linjer:

```css
p {
  line-height: 2em;
}
```

Till exempel:

> `<p style = "line-height: 2em">` Linjer kan köra långa ibland, så utrymme ut dem för att hålla läsarens ögon trötta ut `</p>`

----

Du kan lägga till skuggor till text med `text-shadow`:

```css
h1 {
  text-shadow: 3px 3px 0px rgba(0,0,0,0.3);
}
```

> `<p style = "text-shadow: 3px 3px 10px rgba(0,0,0,0.3),">` Detta är en shaaaaady text `</p>`

De första två siffrorna representerar den horisontella och vertikala storleken av skuggan. Den tredje siffran representerar oskärpa radien. Den fjärde värdet är färgen. I detta fall har vi valt en rgb*a*-färg
**rgba()** i rgba så står *a* för *alpha* och anger vilken opacity som färgen ska ha. Alltså om den ska vara genomskinlig eller inte. Värdet på _a_ kan gå från 1 till 1. alpha `0.5` är 50% transparent.

### Övning

1. Öppna `index.html`.
- Lägg till denna text i två stycken. Placera den mellan huvudet och tabellen:

> Cable Connectors Spelsällskap är en förening grundad i Vårgårda kommun 2014 av gänget bakom den lokala gaming-festivalen Countryhack. Föreningen har som huvudsakligt syfte att arrangera Countryhack två gånger om året. I dagsläget består CCSS av 334 medlemmar!

>Vår förhoppning är att kunna bidra till den lokala gaming-kulturen i och kring Vårgårda och erbjuda människor i alla åldrar, framförallt ungdomar, att träffas för att spela dator/TV-spel med och mot varandra. Vill du också bidra till den lokala gaming-kulturen? Då är det bara att bli medlem genom att trycka på knappen nedan och följa stegen som presenteras.

2. Öppna `main.css`.
3. Applicera `font-size` och`line-height` till den nya texten.
4. Lägg till en text-skugga till h1-rubriken.
