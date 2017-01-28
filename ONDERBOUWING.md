# Onderbouwing
Dit is de onderbouwing voor de keuzes in [het project](README.md).

## Waarom een Node.Js app met EJS en SASS?
### Node.Js
Ik zal niet een complete uitleg geven over de voordelen van Node.Js, hierna te noemen Node. Hierover zijn eindeloze artikelen te vinden (ook onder het kopje links). Het is niet voor niets de keuze vanuit de opleiding bij bijvoorbeeld het vak Server Side Scripting.

Dit is echter exact de reden, naast de voordelen van Node, dat Niels de Bruin en ik hebben gekozen voor Node. De opdrachtgever, het AMC, gaf aan niet steeds een half prototype te willen ontvangen, maar een goed werkende app. Om hiervoor de basis te leggen hebben we gekozen voor Node.

Het is belangrijk dat er verder gebouwd kan worden aan deze app door medestudenten. Aangezien Node wordt aangeleerd binnen onze opleiding was dit de perfecte keuze.

### EJS
We hebben gekozen voor de view engine EJS. Ook EJS wordt aangeleerd bij het vak Server Side Scripting. Naast dit voordeel is er ook nog een ander voordeel. Het is feitelijk Javascript en HTML. Hierdoor kunnen medestudenten die niet Server Side Scripting hebben gevolgd toch mee programmeren.

### SASS
We hebben gekozen om SASS te gebruiken voor styling. Dit staat in licht contrast met de bovengenoemde redenatie. SASS wordt niet bij Server Side Scripting aangeleerd. Toch hebben we ervoor gekozen om dit te gebruiken. Een van de voordelen is bijvoorbeeld al het gebruik van variabelen. De leercurve van SASS voor iemand die CSS kan schrijven is niet heel groot. Ook kan iemand in het slechtste geval CSS in SASS schrijven en er gaat niks stuk.

## Waarom Bootstrap?
Terechte vraag. Bootstrap is niet perfect, maar wel uitstekend in één iets. Snel een front-end opzetten. We hebben alle tijd moeten steken het werkend krijgen van alles binnen de app. Hierdoor was er geen tijd om een uitgebreid front-end op te zetten. Bootstrap was de oplossing.

## Waarom de Node modules?
### Async
Bij het ophalen uit de database, het manipuleren en het versturen van de data ging het soms mis. De data was nog niet gemanipuleerd en het werd al naar de front-end gestuurd. Om dit tegen te gaan heb ik Async gebruikt. Hierdoor kon ik zorgen dat de data pas naar het front-end ging wanneer ik klaar was met het manipuleren. Meer informatie over asynchroniteit in Node is te vinden bij de links.

### Multer
In de applicatie is er de mogelijkheid om afbeeldingen te uploaden. Om dit af te handelen slaan we de afbeeldingen op op de server. Vervolgens slaan we de bestandsnaam op in de database. Dit houdt de database een stuk kleiner. We hebben voor Multer gekozen, omdat dit een simpele manier is van het opslaan van bestanden op een server.

### Moment.Js
Voor het afhandelen van alles gerelateerd aan datums en tijden heb ik gekozen voor Moment.Js, hierna te noemen Moment. Moment is een goed gedocumenteerde library die alles kan afhandelen van het opzoeken, maken, manipuleren en formatteren van een datum of tijdstip. Uiteraard kan je zelf functies schrijven in Javascript, maar dit is simpelweg gemakkelijker en de code is korter en dus leesbaarder. Meer voordelen zijn te vinden in het artikel over Moment in de links

## Links
### Node.Js
https://www.toptal.com/nodejs/why-the-hell-would-i-use-node-js

### EJS
https://scotch.io/tutorials/use-ejs-to-template-your-node-application

### SASS
http://alistapart.com/article/why-sass

### Async
https://www.codementor.io/codeforgeek/manage-async-nodejs-callback-example-code-du107q1pn

### Multer
https://github.com/expressjs/multer

### Moment.Js
https://neoteric.eu/why-should-you-use-moment-js-and-how-to-do-it-effectively
