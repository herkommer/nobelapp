Östra Nobelappen 2020
---------------------
Nobeldagen är torsdag 10:e december
Kodfrys fredag em den 4:e december
HyperCare måndag 7:e till torsdag 10:e

Syftet? Begränsa omfattningen, till RÄTT saker!
-Lättillgänglig för alla att kunna se nobelpriskandidater inom IT-området, läsa på om deras gärning, bilda sig en uppfattning vem som förtjänar att nomineras till ett Nobelpris, och rösta på den kandidaten.
--mobilapplikation via webben

-Presentera kandidaterna.

-Presentera röstningsstatus.(Leaderboard?)
--vill vi visa detta eller inte, funktionen behövs dock.

-Presentera vinnaren.


Funktionalitet?
-hur matar jag in information om kandidaterna?
-hur röster jag?
-vem får rösta, får man rösta flera gånger?
--alla får rösta, ja man kan rösta flera gånger om man går in i appen på nytt
-hur presentera vinnar på ett snyggt imponerande sätt?
-när avslutas röstningen? datum och klockslag? Antar: onsdag 9:e kl 1700
--visa "röstningen är avslutad", "återkom imorgon kl XX för vinnarpresentation"
-vem, eller hur kommer man åt vinnarpresentationssidan?
--kan vi ha en sida som blir aktiv ett visst klockslag? ex torsdag 10:e kl 1200

Personas?
-Elev på Östra som läser på och röstar
-Östra Nobelkommittee som presenterar vinnaren
-Redaktörer för urvalet av kandidater

UX? (mood board, wireframe)

Testfall?
Fokus för de tre Backend-teamen primärt

Teknikstack?
-datalagring. JSON, MongoDB/Atlas, SQL...
-webbserver: nodejs, expressjs, pug
-källkodshantering: git, github
-projektplanering: github project, kanban, milestones, buggar
-språk: javascript, html, css..
-driftsättning: heroku


Teamsamarbete?
1 Gustav, James, Carl		BackendWebServer, eget repo tillsammans med UX
2 Albin, Joel, Douglas 		UX
3 Mafalda, Viktor, Tobias	DataBackendAPI, eget repo i GitHub
4 Max, Oscar, Jesper		VotingBackendAPI, eget repo i GitHub

Arbetsuppgifter, uppdelning?
UX - upplevelsen, känslan, redaktörer som matar in informationen
BackendWebServer - MVC, routing, 404..
-hantera ex vad som visas vid vissa tidpunkter
-hämtar data till layoutsidorna som skickas tillbaka till GUI
DataBackendAPI - data: kandidaternas information, text, bild, listor mm
VotingBackendAPI - röstning: hantera röstning på kandidaterna

Objekthantering?
-vilka objekt har vi?
-vilken data ska hanteras?
-vilka egenskaper?


Dokumentation?
-dokumentera per team och även en gemensam övergripande sida
--github readme som start och gemensam


Start, planering, MVP, omprioritering, version 0.2, 0.3 etc..

1/sätt upp er utvecklingsmiljö
2/sätt upp den även lokalt
3/happy path - it is alive!


