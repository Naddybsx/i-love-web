## Week 1
## 03-02-2025
- Sprint planning
- [Wiki documentatie: Client/server, basis principes data, fetch API... (bronnen leertaak)](https://github.com/Naddybsx/connect-your-tribe-profile-card/issues/2#issue-2828657976)
- [De server code analyseren: Begrip & toepassing, dmv comments server uitleggen](https://github.com/Naddybsx/connect-your-tribe-profile-card/issues/3#issue-2828720775)
## 04-02-2025
- [Liquid documentatie](https://github.com/Naddybsx/connect-your-tribe-profile-card/issues/4#issue-2829972999)
## 05- & 06-02-2025
[Profielkaart bouwen](https://github.com/Naddybsx/connect-your-tribe-profile-card/commit/07e7982e36ca02800cd37fa15a502493864a7728)
## 07-02-2025
- Expo profiel kaart
- [reflecteren op de week ](https://github.com/Naddybsx/connect-your-tribe-profile-card/issues/7#issue-2843305713)

## Week 2
## 10-02-2025
[Teamcanvas, ideeen bedenken met groepje, filteren en sorteren documentatie](https://github.com/Naddybsx/connect-your-tribe-squad-page/issues/1#issuecomment-2649506987)
## 11-02-2025
- [High res schets + breakdown data](https://github.com/Naddybsx/connect-your-tribe-squad-page/issues/5#issue-2846526112)
## 12- 13-02-2025
[Squadpage v1 bouwen + commits](https://github.com/users/Naddybsx/projects/2/views/1?pane=issue&itemId=100201092&issue=Naddybsx%7Cconnect-your-tribe-profile-card%7C9)


## Week 3
## 24-02-2025
## 25-02-2025
## 26-02-2025
## 27-02-2025

## 28-02-2025
### Vragenlijst reflectie op nieuwe technieken
1.Ik kan uitleggen wat NodeJS is en waarvoorhet gebruikt wordt (2)
  - NodeJS is een runtime omgeving waarmee je JavaScript buiten de brower kan draaien. Dit is handig om servers te maken. [Server opzet analyse](https://github.com/Naddybsx/connect-your-tribe-profile-card/commit/bcfc2c1dd178d8037aaac3f5f085cad5ba7e553f)
2.Ik weet wat het doelvan package.json is en heb hier aanpassingen in gemaakt (0)
  - Package.json is een bestand waarin alle informatie over een Node project staat. Ik heb hier nog geen aanpassingen in gemaakt.
3.Ik heb met npm packages geïnstalleerd en gebruikt in het bestand server.js (2)
  - Met npm install heb ik paketten zoals express geinstalleerd. In de server.js importeer je deze en gebruik je om een server op te zetten.
4.Ik kan met commando’s in de terminal een NodeJSproject stoppen en starten (2)
5.Ik weet waarom ik mijn NodeJSproject regelmatig moet herstarten en kan dit uitleggen (3)
  - Node past veranderingen in bestanden niet automatisch toe. Daarom moet de server opnieuw gestart worden bij updates.
6.Ik heb een strategie voor debuggen in NodeJS (2)
  - Ik gebruik [console.log()](https://github.com/Naddybsx/connect-your-tribe-team-squad-page/commit/0102e10a6471d78118698cb0c879c6d8e667bbc9#diff-a4c65ede64197e1a112899a68bf994485b889c4b143198bac4af53425b38406fR237) om variabelen en fouten te controleren.
7.Ik kan uitleggen wat Express.js doet en waarom het nodig is om met NodeJS een website te bouwen (2)
  - Express.js is een framework dat het makkelijker maakt om een server te bouwen met Node.js. Hiermee kan je routes en API's aanmaken.
8.Ik weet wat routes zijn en kan zelf een nieuwe route aanmaken (2)
  - Routes bepalen hoe een server reageert op een verzoek.[Route](https://github.com/Naddybsx/connect-your-tribe-squad-page/blob/52f5208a3cf33ca707aa241ea95bde0484f4b4b4/server.js#L47-L60)
9.Ik weet wat request en response argumenten zijn in een functie voor het laden van data (2)
  - Req bevat informatie over het verzoek, res stuurt een antwoord terug naar de gebruiker.
10.Ik heb gebruik gemaakt van een request parameter om specifieke data te laden (0)
11.Ik kan uitleggen wat Liquid doet en waarom het nodig is om met Express.js een website te maken (2)
  - Liquid is een template engine waarmee je dynamische HTML kunt genereren. [Ik heb liquid gebruikt om data uit mijn server in de frontend te tonen](https://github.com/Naddybsx/connect-your-tribe-profile-card/commit/07e7982e36ca02800cd37fa15a502493864a7728#diff-0657cad62d7f42d5fbc201fa032838a7ff2595c6978593498404c76eb027ab59R3-R9)
12.Ik weet hoe ik data naar Liquid verstuur om dit te gebruiken bij het renderen van een pagina (2)
  - met [res.render('index.liquid', {..}](https://github.com/Naddybsx/connect-your-tribe-team-squad-page/commit/a35414fbe450b91854b7275a0139db5bfbe32c7c#diff-a4c65ede64197e1a112899a68bf994485b889c4b143198bac4af53425b38406fR93-R100) heb ik variabelen naar een liquid template gestuurd.
13.Ik weet hoe ik Liquid filters toe kan passen en waar ik kan vinden hoe die werken (2)
  - Liquid filters worden gebruikt om data te bewerken voordat deze op de pagina wordt weergegeven. Ik heb [slice en upcase](https://github.com/Naddybsx/connect-your-tribe-squad-page/commit/f01081a2b35f636747e582f26c4f30f8b5d13bab#diff-0657cad62d7f42d5fbc201fa032838a7ff2595c6978593498404c76eb027ab59R6) gebruikt om de eerste letter van een naam te krijgen en in hoofdletters te zetten.
14.Ik heb een nieuwe route gemaakt en nieuwe data meegegeven aan een Liquid view (2)
  - Ik heb een nieuwe route /like gemaakt en likes data doorgegeven aan de liquid template.
15.Ik weet waar een foreach loop voor gebruikt wordt en pas het toe in een Liquid view om HTML te renderen (3)
  - Een for loop in liquid herhaalt data. Dit [loopt](https://github.com/Naddybsx/connect-your-tribe-squad-page/blob/52f5208a3cf33ca707aa241ea95bde0484f4b4b4/views/index.liquid#L5-L25) door alle personen in persos geen en genereet voor elk persoon een list item met hun naam en link.
16.Ik kan in Liquid een controle maken waarmee de avatar niet getoond wordt als deze niet in whois.fdnd.nl is ingevuld (0)
17.Ik heb een strategie voor debuggen in Liquid (0)
18.Ik kan data fetchen uit een REST API (2)
  - Met fetch('APIURL') kan je data ophalen uit een API.
19.Ik snap het verschil tussen HTTP requests van de methodes GET en POST (3)
  - GET haalt data op, POST stuurt nieuwe data naar een server. Ik heb beide methodes gebruikt.
20.Ik kan data uit een REST API filteren of sorteren (0)
21.Ik snap wat het async keyword doet in JavaScript code (2)
  - Async maakt een funtie asynchroon, zodat je await kan gebruiken om een actie te laten wachten op een resultaat.
22.Ik weet wat het doel is van eentry/catch block en kan het gebruiken bij het parsenvan JSON (1)
23.Ik begrijp het verschil tussen client-side JavaScript en server-side JavaScript en wanneer ik welke het handigst in kan zetten (2)
  - client side js draait in de browser (voor UI), server side js draait op een server (voor data opslag en verwerking)
24.Ik kan formulierdata die is ge-POST opslaan in een variabele op de server en gebruiken bij het renderen van een pagina(1)
[req.body](https://github.com/Naddybsx/connect-your-tribe-team-squad-page/commit/0102e10a6471d78118698cb0c879c6d8e667bbc9#diff-a4c65ede64197e1a112899a68bf994485b889c4b143198bac4af53425b38406fR232)
25.Ik kan formulierdata die is ge-POST door middel van een POST of PATCH HTTP request opslaan in de REST API (0)
