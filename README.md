# Vernieuwde POC
Dit is mijn vernieuwde POC. Mijn oude POC, verloren gegaan in het organiseren van mijn repo's, was nog gericht op het idee dat we verder gingen met de PHP app genaamd "NO2OCD".

## Oude POC
In het kort, ik wilde leren werken met PHP aangezien ik daar nog nauwelijks mee hebt gewerkt. Ik wilde onder andere data visualiseren. Ik heb in het blok voor dit project veel kennis opgedaan over datavisualisatie en de technieken om dit te verwezenlijken. Ik wilde deze vaardigheden inzetten om de app te verbeteren.

Dit was van waarde voor de oude app, maar niet voor mij. Aangezien ik het kunstje van datavisualisatie nu zou vertonen in deze app zou ik mezelf niet naar een hoger niveau tillen.

Niels de Bruin, de andere developer met wie ik zou gaan werken, en ik besloten de app volledig opnieuw de bouwen. Redenering en onderbouwing is te vinden in [de onderbouwing](ONDERBOUWING.md)

## Nieuwe POC
### Wat is de uitdaging?
Door het volgen van het vak Server Side Scripting en mijn werk als front-end Developer bij ben ik bekend met Node.Js en front-end frameworks. Het stukje waar ik echter vaak veel moeite mee heb is het ophalen, updaten en deleten van data op een goede manier. Ik heb basis kennis van MySQL en phpMyAdmin, maar ik wil leren hoe ik door middel van MongoDB en Mongoose de afhandeling van data kan verwezenlijken.

Een tweede uitdaging was het uit handen geven van taken aan teamgenoten. Ik heb hierover eerder gesproken met mijn SLC’er Albert de Klein. Al vroeg kwam de vraag vanuit mijn team hoe zij nou mee moesten programmeren terwijl Niels en ik de app bouwen. het antwoord: Git(Hub). Ik merkte al snel dat medestudenten hier wel is iets gedownload hadden, maar nog niet in een project hadden meegedraaid die hiervan gebruik maakte. Ik wilde zorgen dat mijn medestudenten een basiskennis over Git(Hub) kregen en hierdoor ook in het project mee konden werken aan de app.

### Hoe heb ik het aangepakt
Voor MongoDb en mongoose was de aanpak als verwacht. Zoeken, zoeken en zoeken. Uiteraard staat veel informatie gedocumenteerd in de API van Mongoose, maar dit blijft altijd een uitdaging. Voor basisinformatie, over bijvoorbeeld schema’s, kon ik hier alles vinden.

Voor, mij als beginner met mongoose, moeilijkere dingen heb ik veelvuldig op StackOverflow informatie gevonden. TIjdens het bouwen wilde ik de functie toevoegen van het updaten van data in de database. Uiteraard is deze informatie te vinden in de documentatie, maar door snel een voorbeeld te bekijken op StackOverflow leerde ik mezelf dit aan.

Voor het uitleggen van Git(Hub) heb ik veel geput uit eigen kennis. Ik besloot op een vrijdag, vlak voor het beginnen met programmeren aan de app voor veel klasgenoten, een presentatie te geven over Git(Hub). De presentatie, genaamd “Hoe kan je als niet Developer toch mee programmeren aan projecten?“, is te vinden bij de links.

Alhoewel het een zeer lastig iets is om uit te leggen bleef de hoofdgedachte hangen bij de meeste medestudenten. Ik leerde echter ook veel nieuws uit deze presentatie geven. Hoe leg ik iets technisch zo duidelijk en vatbaar mogelijk uit? Deze uitdaging bleef me, de laatste weken van het project, bij. Het was dan ook een zeer welkom compliment toen ik van een van mijn medestudenten hoorde: “Zoals jij het uitlegt begrijp ik het wel”.

### Wat zijn de resultaten?
Een app. En snelle, duidelijke, fijn werkende app. De oude app was niet het sterkst qua functionaliteit, vormgeving en interactie. Hier is een grote verbeterslag in gemaakt. De app heeft vrijwel dezelfde functionaliteiten, maar nu beter uitgewerkt. Ook zijn er veel toevoegingen gedaan. Hierbij valt te denken aan de pagina’s van het dashboard, witboek, g-schema. Ook is de app nu responsive.

Waar ik zeer tevreden over ben is de afhandeling van het ontbreken van data. De app laat door het front-end heen op basis van de aanwezigheid of het ontbreken van data verschillende informatie zien.

Daarnaast ben ik zeer tevreden over de “kleine” dingetjes. Op de dashboard pagina staat de zin “De exposure opdrachten gaan oke/goed/uitstekend!”. Om die informatie te geven moest er op een slimme manier naar de data gekeken worden. Ik heb dit gedaan door uit te rekenen op hoeveel procent de gebruiker deze week moet zijn met zijn/haar opdrachten en hoever hij/zij daadwerkelijk is. Ik geef marges op waarop het systeem vervolgens kijkt welk bericht het moet tonen. Dit kleine stukje feedback voor de feedback heeft nog verrassend veel voeten in de aarde.

Tenslotte ben ik ook tevreden over het multi-step formulier met de progress bar. Door aan elke stap de class “formStep” mee te geven en de id “formStep-1” bijvoorbeeld werkt alles. Hij berekent hier de procenten en verbergt/toont de stappen zonder dat het uitmaakt of je drie of tien stappen hebt.

### Conclusie
Dit was op technisch vlak een zeer druk project. Een volledige app opzetten met een nieuwe datastructuur, nieuwe interactie en nieuwe vormgeving was zeer uitdagend. Desalniettemin ben ik van mening dat wat wij hebben gebouwd de ideale basis legt voor verder werken aan de app in de toekomst. De app is solide en klaar voor uitbreiding. Ik ben zeer benieuwd wat andere met deze app gaan doen.

## Wat moet er nu nog gebeuren aan de app?
Goede vraag! Een hoop moet er nog gebeuren. De app is uiteraard niet volledig af in zo’n ontzettend korte tijdspanne. In de repository is alles te vinden onder issues. De issues zijn gecategoriseerd op verschillende punten. De informatie hierover is te vinden in de readMe van de repository.

## Screenshots
### Dashboard
![alt tag](https://raw.githubusercontent.com/DaveBitter/ehealth-maken/master/screenshots/1.jpg)
![alt tag](https://raw.githubusercontent.com/DaveBitter/ehealth-maken/master/screenshots/2.jpg)
### Multi-step form
![alt tag](https://raw.githubusercontent.com/DaveBitter/ehealth-maken/master/screenshots/3.jpg)
![alt tag](https://raw.githubusercontent.com/DaveBitter/ehealth-maken/master/screenshots/4.jpg)
![alt tag](https://raw.githubusercontent.com/DaveBitter/ehealth-maken/master/screenshots/5.jpg)
![alt tag](https://raw.githubusercontent.com/DaveBitter/ehealth-maken/master/screenshots/6.jpg)
### Oefeningen
![alt tag](https://raw.githubusercontent.com/DaveBitter/ehealth-maken/master/screenshots/7.jpg)
![alt tag](https://raw.githubusercontent.com/DaveBitter/ehealth-maken/master/screenshots/8.jpg)
### Afhandeling ontbreken van data
![alt tag](https://raw.githubusercontent.com/DaveBitter/ehealth-maken/master/screenshots/9.jpg)
![alt tag](https://raw.githubusercontent.com/DaveBitter/ehealth-maken/master/screenshots/10.jpg)

## Links
### Presentatie over Git(Hub)
https://docs.google.com/presentation/d/1pJWxzwLzpLQ0MrMe1QQ8_b5o-y25UuZwowNRrPYArpo/edit?usp=sharing

### App/Prototype
Vraag om inloggegevens.
https://ocd.cmdhealth.nl/

### App/Prototype repository
https://github.com/nielsdB97/CMD-OCD

