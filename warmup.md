# PHP Mysore Uppvärming 💨🏃‍♂️🏃‍♀️
Dessa "uppvärmingsövningar" är för dig som vill träna lite mer på grunderna i PHP. När du är klar kan du börja om från 1 och se om du lärt dig något sen förra gången 🙂 

Om inget annat står så skapa en ny fil för varje uppgift, ni kan clona detta repo så har ni en egen warmup.md att utgå ifrån.

## 1 
Skriv en funktion med namnet `make_paragraph` som skriver ut en sträng som HTML-elementet \<p>.
Exempel: "hej" ska skrivas ut som "\<p>hej\</p>".
Funktionen ska ha en parameter, som är strängen som ska skrivas ut, och den ska inte returnera något. 

## 2
Funktionen `make_paragraph` är lite begränsad. Tänk om vi vill göra h1-taggar? Eller h2, h3 osv. Skriv en ny funktion med namnet `make_heading`. Funktionen behöver veta strängen som ska skrivas ut och vilken heading det ska vara. Den behöver alltså två argument.

## 1
Skriv en php sida som visar texten “Välkommen till PHP” som en h1-tagg med echo.

## 2
Skriv en php sida som visar ett slumptal mellan 1 och 100

## 3
Skriv en sida som visar det första ordet i en array som innehåller fem ord: gris, katt, häst, ko och hund.

## 4
Skriv en sida som visar ett slumpat ord från en array som innehåller sex ord: gris, katt, häst, ko, val och hund. 

## 5
Skriv en sida som visar alla värden i variabeln `$a` på var sin rad i webbläsaren. $a ska vara en array:

`$a = [1, 3, 5, 12, 34];`

Använder du inte en loop så blir blir sidan sex rader långt. Med en loop blir det istället tre rader långt.

**Extra mile:**) Skriv om sidan så att $a är en array med 100 element med slumpade heltal mellan 1 och 100.

## 6
Skriv en sida som visar upp värdet på `$x`. Använd enbart den variabeln. Utskriften ska se ut så här i webbläsaren:

```
15
16
4
2
0
100
50
48
24
````

De första två raderna i programmet ska vara:
```
$x = 15;
echo “$x<br>”;
```

## 7
Skriv en sida som visar värdet 12 ifrån följande 2D-array.

```
$a = [
		[1, 23, 11, 21],
		[5, 12, 56, 34],
		[7, 99, 27, 75]
	];
```

## 8
Titta på substr och substr_count. Skriv en sidan som visar *och förklarar* hur dessa funktioner fungerar.

## 9
Skriv en sida som visar följande i webbläsaren

```
xxxxx
xxxxx
xxxxx
```

Den första raden i din kod är

`$x = “x”;`

och vi ändrar inte på den variabeln. Vi skriver ut den upprepade gånger!

## 10
Vi ska nu bygga vidare på 9! Vi vill ha en allmän lösning vars första rader med kod är

```
$rows = 10;
$columns = 10;
$char = "x";
```

och sedan kommer din kod som använder dessa tre variabler för att skriva ut tio rader med 10 stycken `x`. Sedan ska man kunna ändra på variablerna men INTE någon övrig kod för att få en annan utskrift som matchar variablerna.

## 11
Samma övning som ovan men utskriften ska vara

```
xxxx
xxxx
oooo
oooo
```

## 12
Samma sorts övning som ovan men nu får du massa utmanande utskrifter att få till! Försök göra allmänna lösningar som fungerar för alla värden på `$rows` och `$columns`.

```
xxoo
xxoo
xxoo
xxoo
```

```
xxxo
xxxo
xxxo
oooo
```

```
xxoxx
xxoxx
xxoxx
xxoxx
```

```
xoxoxo
xoxoxo
xoxoxo
xoxoxo
```

## 13
Samma sorts övning som ovan men nu får du massa utmanande utskrifter att få till! Försök göra allmänna lösningar som fungerar för alla värden på `$rows` och `$columns`.

```
xxxxx
ooooo
xxxxx
ooooo
```

```
xxxx
xoox
xoox
xxxx
```

```
oxxx
xoxx
xxox
xxxo
```

```
oxxxxo
xoxxox
xxooxx
xxooxx
xoxxox
oxxxxo
```

```
oxxxx
ooxxx
oooxx
oooox
ooooo
```

```
xxoxx
xooox
ooooo
xooox
xxoxx
```

## 14
Skriv en sida som ger en output lik

```
5
62
89
23
74
```

Dvs din kod genererar 5 stycken slumptal mellan 1-100. Dessa slumptal lagras i en array!

Kolla in 👉 http://php.net/manual/en/function.mt-rand.php

## 15
Vi bygger vidare på förra uppgiften. Nu vill vi ha en allmän lösning där koden börjar med

`$array_length = 10;`

vilket berättar att vi ska skapa en array med tio slumptal som också visas som förut. Ändra din kod från förra uppgiften så den använder den nya variabeln!

## 16
Vi bygger vidare på förra uppgiften. Vi vill ha en utskrift som liknar

```
34, 73, 98, 15, 62
```

## 17
Vi bygger vidare på förra uppgiften. Vi inför nya värden i början av vår kod så de första fyra raderna ser ut så här:

```
$array_length = 10;
$row_length = 5;
$min_value = 1;
$max_value = 100;
```

Vi vill ha en utskrift som liknar

```
34, 73, 98, 15, 62
84, 24, 93, 14, 71
```

## 18
Vi bygger vidare på förra uppgiften. Vi vill ha samma utskrift men alla värden lika eller över `$red` ska vara röda och alla värden under ska vara gröna. Vi tillför alltså ett nytt värde:

`$red = 50;`

## 19
Vi bygger vidare på förra uppgiften. Alla siffror som börjar på 2 ska vara blåa nu. I övrigt ska programmet bete sig som i 19 ovan. Inför gärna nya variabler i början av din kod.

## 20
Vi ska nu bygga en sida som är likt de vi gjort innan. Som innan ska vi skapa en array med slumptal mellan 1 och 100. Arrayen ska vara 50 lång. Utskriften ska vara två rader som är komma-separerade precis som i övning 18-20 ovan. Varje rad har en egen textfärg. Första raden är alla tal ifrån arrayen som är under 50. Alla tal på andra raden är 50 eller större. Kom ihåg att inte ha magiska siffrori din kod! Skapa variabler i början av din kod istället.
