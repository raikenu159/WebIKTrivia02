# Kwik Kwiz
### Projectleden 
* Daan van Baarsen, 
* Una Garcia, 
* Sem Kjaer, 
* Soufiane Zouli

## Samenvatting
Op onze webapplicatie is het mogelijk zijn om  multiple choice trivia quizzes af te nemen onder een tijdslimiet. De quizzes worden individueel afgenomen, dus er is geen directe multiplayer. Wel is er een leaderboards-pagina , waar de tien hoogste scores getoond worden. Zo is er toch nog een vorm van concurrentie tussen verschillende spelers. Na een quiz afgenomen te hebben kan de gebruiker grafieken zien die de behaalde score per onderdeel en soort vraag tonen. Ook kan de gebruiker een tabel zien met daarin alle beantwoorde vragen met het gegeven antwoord en het correcte antwoord.

## Afbeeldingen
**Homepagina met uitleg quiz**
![Homepagina](https://i.imgur.com/I1EepTC.png)
**Quizvraag pagina type 1 meerkeuze**
![Quizvraag pagina meerkeuze](https://i.imgur.com/gobQsLO.png)
**Quizvraag pagina type 2 boolean**
![Quizvraag pagina boolean](https://i.imgur.com/ATSs2sh.png)
**Quizvraag pagina tijd verlopen zonder top 10 score behaald te hebben**
![Quizvraag pagina tijd verlopen zonder top 10 score behaald te hebben](https://i.imgur.com/2KWoOco.png)
**Quizvraag pagina tijd verlopen top 10 score behaald**
![Quizvraag pagina tijd verlopen top 10 score behaald](https://i.imgur.com/oSkyIT5.png)
**Leaderboards pagina**
![Leaderboards pagina](https://i.imgur.com/cyqAbDQ.png)
**Barcharts pagina**
![Barcharts pagina](https://i.imgur.com/IIAyq8s.png)![Barcharts pagina](https://i.imgur.com/5zJP0vX.png)
**Question results pagina**
![Question results pagina](https://i.imgur.com/H643Jcm.png)
## Features
1. De vragen in de quizzes komen uit Online Trivia Database (https://opentdb.com)
2. Alle gebruikers nemen een quiz af die vragen bevat uit een aantal verschillende categorieën die 45 of meer vragen bevatten in Open Trivia Database.
3. De quizzes zijn multiple choice.
4. Gebruikers kunnen ervoor kiezen om een vraag over te slaan zonder tijd te verliezen.
5. Elke quiz begint met een tijdslimiet van een minuut.
6. Gebruikers verdienen extra tijd met elke goed beantwoorde vraag.
7. Gebruikers behalen punten met elke goed beantwoorde vraag.
8. Gebruikers behalen meer punten bij het goed beantwoorden van moeilijkere vragen.
9. Er is een leaderboards-pagina met daarin de 10 gebruikers met de hoogste scores, hun scores en de datum waarop de score is behaald.
11. Alleen als een gebruiker een score heeft behaald die in de top 10 zit, wordt er om een username gevraagd.
12. Wanneer een gebruiker vanuit de quiz naar de leaderboards-pagina gaat, kan de net behaalde score verwijderd worden. 
13. In de chart-page kan de gebruiker zien hoeveel punten die behaalde per categorie.
14. In de question_result-page kan de gebruiker alle vragen zien die die heeft beantwoord, met het gegeven antwoord en het correcte antwoord.

## Repository gids

Onze repository heeft de naam 'WebIKTrivia02'. Bij het bezoeken van de repository staan er 6 items in de lijst. Drie van deze items zijn mappen, waar we zo op in gaan, de andere drie items zijn bestanden:

 - application.py
 - README.md
 - trivia.db
 
 **Het eerste** bestand 'Application.py' bevat de volledige backend code in python. Voor alle functies  die gebruikt zijn in application.py inclusief de bijbehorende uitleg volg je het pad WebIKTrivia02/doc/Textfiles/Functies.md.
 
**Het tweede** bestand 'README.md' is het huidige bestand.

**Het derde** en laatste bestand 'trivia.db' is de database waarop ons project werkt. Hierin wordt de user id (en hiermee de session id) de username (mocht speler in de top 10 zitten) en natuurlijk de behaalde score, inclusief datum waarop, bijgehouden.

Vervolgens de **3 mappen** in de repository:

 - doc
 - static
 - templates

In de **doc-map** vind je twee mappen:

/afbeeldingen: hierin staan alle afbeeldingen die gebruikt worden in de README file.

/Textfiles: hierin staan de markdown-bestanden waarin je de gebruikte frameworks kunt vinden inclusief een description (Frameworks&Plugins.md), alle gebruikte functies in application.py inclusief uitleg (Functies.md) en de teamcharter (teamcharter(up-to-date).md) 

Ook het losse bestand DESIGN.md staat in de '/doc' waarin een design in de vroege fase van het project staat.


In de **static-map** vind je:

-/js: Hierin staan alle gebruikte javascript files opgeslagen.

-styles.css: het bestand voor de styling van de webpagina's.

-Verder staan hier alle afbeeldingen die gebruikt worden op de webpagina's.

In de **templates-map** vind je:

Alle HTML-files waaruit de trivia web-applicatie bestaat.

## Werkverdeling

Over het algemeen is het werk vrij goed verdeeld over de groepsleden. Iedereen heeft aan elk onderdeel van het project een bijdrage geleverd. Toch was er tussen de groepsleden enige vorm van specialisatie. 
 
**Daan van Baarsen**
 - Leaderboard
 - Database
 - Backend

**Sem Kjaer**
- Backend
- javascript (frontend)
- database

**Una Garcia**
- layout
- HTML & CSS
- textfiles (README)

* Quizpagina passend maken op verschillende apparaten
* 


**Soufiane Zouli**
- javascript (frontend)
- HTML & CSS
- textfiles (README)



<!--stackedit_data:
eyJoaXN0b3J5IjpbMTc4OTI0NjgzNiwtMTM1Njk4OTM0NCwtNz
cwMzk2ODg3LC0xMzIwMjAwOCwtMTQ5MzIxMDY2Nl19
-->