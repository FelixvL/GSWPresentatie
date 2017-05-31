De Presentatie over Spring, Maven, REST en HTML als moderne Java Stack door Felix.
 
In 9 stappen klaar!

Met dit stappenplan maak je een maven java BackEnd project dat via rest met een front-end HTML site communiceert.
Een standaard met een losse frontend server en een losse backend server is nu gebruikelijk in de markt.
Het geeft zicht op een volledige stack die veel in het hedendaagse development gebruikt wordt.
 
Spring: Het Java-Framework waarbij middels een werkstandaard, distributie van functionaliteit mogelijk is.
Maven: Een buildtool (Gradle is een concurrent)

-1- Ga naar start.spring.io voor een pom.xml, je klikt de features die je nodig hebt bij elkaar.  
 
-2- Importeer het geheel als project in bv Eclipse
Het systeem begint te importeren.
Vaak kopieer ik componenten(dependencies) die ik moet gebruiken vanuit een andere xml
 
-3- Daarna pas je de application.properties aan, aan jouw omgeving.
denk om de database naam, maak deze aan in SQL database
denk om credits
De Database MOET al bestaan voordat je je applicatie nu voor het eerst probeert te starten.
 
-4- Je kunt de applicatie nu starten. LET OP de poort.
 
-5- Maak nu een @EntityKlasse aan (een bv een package domain), let op de ID en de bijbehorende annotaties.
Als je de applicatie nu start zie je dat de velden worden aangemaakt in je database.
 
-6- Nu gaan we de Reposistory wat een extend is van de CRUDRepository maken
En we maken tegelijk een Service aan, hierbij even twee methoden, save en getAll
Hiermee haal je data op, of sla je data op in de database. De CRUD interface regelt een hele hoop functionaliteit voor je zonder dat je goed kunt nagaan HOE dat het gebeurd.

-7- We gaan een ENDpoint maken, standaard als eerste de algemene acceptatievoorwaarden voor http-requests. 
Dit zijn de JerseyConfig en een CORSFilter als bestanden.
Daarna maken we een specifiek endpoint aan. 
In het JerseyConfig registreren we het gemaakte endpoint. We maken een GET-methode en een POST-methode.
 
-8- We starten de applicatie.
We starten het programma POSTMAN en testen of onze software werkt.
 
De backend is af.
 
Nu de frontend:

-9- open een bestand index.html en hier kunnen we met de javascriptfuncties doen wat we willen mbv tekstvensters en knoppen.
Dit index.html heb ik in de STATIC map gezet. ECHTER deze index.html kan vanuit anywhere in het netwerk worden gebruikt.
Deze index.html heb ik in static gezet zodat het in deze repository past.

Veel succes en veel plezier met de gerealiseerde stack van DB -> Spring -> Endpoints -> REST -> HTML.

Met vriendelijke groet,

Felix
 
 
 
 
 
 
