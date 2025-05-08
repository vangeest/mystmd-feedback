# Codespaces voor docenten

Pagina met hulp voor docenten die met de online ontwikkelomgeving Codespaces aan de slag willen in hun klassen.

Codespaces is een online codeeromgeving binnen GitHub. In Codespaces run je programma's in een container in de cloud. Codespaces maakt gebruik van de webversie van de editor Visual Studio Code, daarmee maak je wijzigingen in je Codespace. Wijzigingen sla je op (push) in GitHub. 

## 1. Quickstart: Codespaces gebruiken in je klas

1. Maak organisaties in GitHub (eenmalig)
    1. Maak github account
    2. Maak twee organisaties, één voor docenten (vanaf nu: schooldocent) en één voor leerlingen (vanaf nu: schoolleerling)
    3. Nodig collega informaticadocenten van je school uit als owner van beide organisaties
    4. Optioneel: vraag de gratis educatiestatus aan voor je github account en zet daarmee je abonnement voor je organisaties om van free naar team
2. Maak startcode voor opdrachten (eenmalig)
    1. Kopieer wat voorbeelden van anderen: maak een fork van een repository van iemand anders en zet die in je schooldocent organisatie
    2. optioneel: startcode aanpassen
    3. optioneel: aanpassen devcontainer configuratie
    4. optioneel: aanpassen vscode configuratie
3. Maak klassen in GitHub Classroom (jaarlijks)
    1. Maak een class voor elke lesgroep en elk jaar. Tip: Gebruik een systematische naamgeving, bijvoorbeeld 2425-4Hin1 volgens schema jaar-klas.
    2. Voeg leerlingen toe aan elke klas. Tip: Gebruik voornaam zonder speciale tekens en als nodig een letter van de achternaam.
    3. optioneel: nodig collega's uit als TA's in je klassen
4. Maak een opdracht aan (per opdracht)
    1. Kies de repository met startcode, deze wordt gekopieerd naar de school-leerling organisatie voor elke leerling of elk groepje. <br>
    Tip: Gebruik een systematische naamgeving voor de opdrachten, bijvoorbeeld 2425-4Hin1-website volgens schema jaar-klas-opdracht. <br>
    Gebruik dit systeem ook voor de voorvoegsels van de namen van de repositories en als je in groepjes werkt tevens voor de voorvoegsels van de namen van de teams.
    2. Deel de inschrijflink met je leerlingen.
5. Begeleid leerlingen (per opdracht)
    1. Gebruik [Leerlinghandleiding Codespaces](/help/codespaces/)
6. Ga nakijken (per opdracht)
    1. Bekijk het werk p github in de organisatie school-leerling.<br>
    Tip: je kunt alle bestanden downloaden onder de groene knop "Code" (dit kan per repository, niet voor alle repositories tegelijk) of het werk openen in een Codespace<br>
    Tip: onder "commits" kun je zien wanneer de laatste wijziging is gemaakt, je kunt een oude versie kiezen als er na de afgesproken inleverdatum nog gewijzigd is.<br>
    Tip: per bestand kun je onder "blame" zien welke regels op welk moment door wie zijn toegevoegd of gewijzigd<br>

## 2. GitHub

GitHub is een online omgeving waar programmeurs code opslaan en delen. GitHub is gebaseerd op Git. 

Het kost tijd om Git te leren begrijpen, maar een team dat Git begrijpt kan veel efficienter werken. Leeringen die beginnen met programmeren werken veelal samen tegelijk achter 1 computer of typen tegelijk online in hetzelfde document. Het typen en runnen van code moet dan synchroon gebeuren. Professionele teams van programmeurs verdelen werk, maken en testen dat in hun eigen kopie van de omgeving en voegen stukjes code die werken toe aan het gezamenlijke product. Zo is er altijd een werkende versie van het product en kan iedereen zijn eigen versie op elk moment runnen.

### 2.1 GitHub: Functionaliteit

Functionaliteit van GitHub:
- Online opslaan van code
- Versiebeheer
- Met meerdere mensen werken aan dezelfde code
- Hosting van static websites
- Toegankelijk via website
- API beschikbaar
- ...

### 2.2 GitHub: Gratis aanbod

Git is open-source.

GitHub is eigendom van Microsoft. Met een gratis account kun je bijna alle functionaliteit gebruiken. De betaalde functies zijn gericht op software-bedrijven, in het onderwijs heb je die niet nodig.

### 2.3 GitHub: Aan de slag

Tips voor gebruik:
- Maak een gratis GitHub account aan en start met het maken van repositories.
- Maak een organisatie aan in GitHub. Nodig de informaticadocenten op je school uit als (mede)owner van de organisatie. Je kunt dan gemakkelijker met collega informatica-docenten op je school samenwerken en je kunt je schoolwerk gescheiden houden van andere dingen die je op je GitHub account doet. Het is handig om een tweede organisatie te maken waarin je werk van leerlingen bewaart (zie ook onder Classroom).
- Wijzigen van code gaat in de volgende stappen: 
    - change (maak wijzigingen in de code met een editor)
    - stage changes (kies de wijzigingen waarmee je verder wilt, meestal allemaal)
    - commit (maak een foto van je wijzigingen)
    - pull (haal de laatste wijzigingen van anderen op uit GitHub)
    - los eventuele merge-conflicten op (als jij en anderen in dezelfde regels code aanpassingen hebben gedaan, dan moet je handmatig aangeven welke aanpassingen voorrang krijgen) 
    - push (upload jouw wijzigingen inclusief opgeloste merge-conflicten naar GitHub)
- Er zijn instellingen in Git die het gemakkelijker maken voor beginners om ermee te werken, bijvoorbeeld dat alle changes automatisch gestaged worden, dat bij commit automatisch geprobeerd wordt te pullen en pushen, een merge-editor aanzetten die helpt met het oplossen van merge-conflicten etc. In de template-repositories van Emmauscollege vind je de instellingen die wij handig vinden.
- Voor grotere projecten kun je gebruik maken van branches. Een branch bevat een nieuwe functies die meerdere commits bevat. Als de feature klaar is, dan merge je de branch in de main branche. Je kunt incidenten aanmaken om bij te houden welke bugs er zijn of welke uitbreidingen nog gedaan moeten worden. De indicenten kun je koppelen aan wijzigingen in de code. Dit kan handig zijn voor grotere projecten, bijvoorbeeld in 6-vwo. 

### 2.4 GitHub: Alternatieven

GitHub wordt heel veel gebruikt, als je specifieke wensen hebt dan zijn er alternatieven voor GitHub.
- Git lokaal op je PC installeren en via de commandline je code opslaan op een andere git-server dan GitHub.
- Gitlab, eveneens gebaseerd op Git, zowel te gebruiken in een cloud omgeving als op eigen servers.

## 3. Codespaces

Codespaces is een online ontwikkelomgeving voor alle programmeertalen.

### 3.1 Codespaces: Functionaliteit

Functionaliteit van Codespaces:
- Virtual machine in de cloud waarop je een Docker image kunt draaien. Het Docker image kun je zelf volledig configureren. 
- Online toegang via webbrowser, inclusief mogelijkheden om bestanden te wijzigen, terminal commando's te geven en server-applicaties te draaien (zoals webserver, database, vnc-server).
- Visual Studio Code editor ingebouwd.
- Met enkel kliks in GitHub kun je een Codespace maken vanuit een GitHub repository. Wijzigingen in je Codespace bewaar je in GitHub.
- ...

Wat kan niet:
- Een Codespace dag en nacht laten draaien kan niet, want als je de browser afsluit dan stopt de Codespace na enige tijd (half uur). Als een Codespace stopt dan blijven de bestanden in de Codespace bewaard, dus je kunt de Codespace later weer opnieuw starten. Als een Codespace langere tijd (30 dagen) niet gebruikt is, dan wordt hij gewist. De bestanden uit de Codespace verdwijnen dan, wat je vanuit de CodeSpace in GitHub hebt gezet blijft uiteraard wel bestaan.

### 3.2 Codespaces: Gratis aanbod

Codespaces maakt onderdeel uit van GitHub. CodeSpaces is geïntegreerd in GitHub. Je GitHub account gebruik je voor CodeSpaces. 

Met een gratis GitHub account kun je per maand 60 uur gebruik maken van Codespaces en gemiddeld 15 GB opslag gebruiken. Je kunt je gebruik inzien, bij overschrijding van de limit wordt Codespaces (niet GitHub) geblokkeerd totdat de maand voorbij is. 

Eén codespace vraagt ongeveer 1 GB data, tegen de opslag limiet loop je normaliter niet aan. 

De 60 uur is voldoende voor bijna alle leerlingen. Een enkele leerling die door de limiet gaat kan een 2e GitHub account aanmaken op een ander email adres, zichzelf als collaborator toevoegen aan de repositories waarin die werkt en dan weer 60 uur vooruit.

Een docent die door de limieten heen gaat kan creditcardgegevens en een bestedingslimiet toevoegen aan zijn account. Dat is normaal gesproken niet nodig. Een tweede account aanmaken kan ook.

### 3.3 Codespaces: Aan de slag

Login op GitHub, ga naar een repository, klik op de groene code knop en maak een Codespace. Er wordt een standaard image van een linux server gestart en je bestanden uit de repository worden gekopieerd naar de server. Je kunt de Codespace configureren door een devcontainer.json bestand in de .devcontainer map te plaatsen. Open het Source-Control tab links in het scherm om wijzigingen te bewaren in GitHub. 

### 3.4 Codespaces: Alternatieven

Alle onderstaande alternatieven kunnen samenwerken met GitHub, maar zijn ook zonder GitHub te gebruiken.
- https://gitpod.io/, zelfde look and feel en nagenoeg dezelfde mogelijkheden als Codespaces, inclusief editor VS Code.
- https://replit.com/, in 2017-2020 begonnen als online multi-language platform voor kleine stukjes code, inmiddels fors gegroeid kwa mogelijkheden en aantal gebruikers.

Wij hebben enkele jaren Gitpod (vwo) en replit (havo) gebruikt. In 2023 hebben we een geslaagde pilot in 5-vwo gedraaid met Codespaces, ondermeer vanwege de naadloze integratie met GitHub. De firewall van de nieuwe internetaanbieder van de school blokkeerde gebruik op schoolcomputers. In schooljaar 24/25 willen we Gitpod gebruiken, zowel voor de havo als voor het vwo.

## 4 GitHub Classroom

Met GitHub Classroom kun je opdrachten klaarzetten voor (grote aantallen) leerlingen.

### 4.1 Classroom: Functionaliteit

Wat wel kan:
- Opdrachten aanmaken en uitnodigingen versturen per email naar leerlingen.
- Leerlingen schrijven zichzelf in.
- Leerlingen kunnen zelf groepjes maken, als je groepjes maken aanzet voor die opdracht.
- Bij het inschrijven krijgen leerlingen een kopie van een template-repository uit GitHub die de docent bij de opdracht meegeeft.

Wat niet kan:
- Template-repository aanpassen nadat opdracht is uitgezet. Sinds januari 2024 is er beta functionaliteit beschikbaar waarmee dit wel kan. Zie https://github.blog/changelog/2024-01-22-migrating-github-classroom-assignment-repository-creation-from-create-from-template-to-forks-public-beta/
- Groepjes aanpassen nadat opdracht is uitgezet. Je kunt dit wel handmatig in GitHub doen door de teams die Classroom aanmaakt in GitHub aan te passen.

### 4.2 Classroom: Gratis aanbod

Je gebruikt je GitHub account voor classroom. Classroom is geheel gratis, zonder beperkingen. Je kunt de educatie-status aanvragen voor je GitHub account, maar dat is niet nodig. 

### 4.3 Classroom: Aan de slag

Tips voor gebruik:
- Maak een organisatie in GitHub waarin je alle leerlingwerkstukken neerzet. Gebruik een andere organisatie voor je eigen voorbeelden en templates. Op die manier hou je werk van leerlingen en van docenten gemakkelijk uit elkaar.
- Bij elke opdracht die je aanmaakt kunt je aangeven waarmee de naam van de repository die Classroom voor leerlingen in GitHub aanmaakt moet beginnen. Gebruik een systematische naam, dat maakt het vinden van klassen en leerlingen veel gemakkelijker. Bijvoorbeeld :2324-5hin1-website (jaar-klas-opdracht).
- Geef herkenbare identifiers voor leerlingen op in Classroom. Voornamen werkt handiger dan leerlingnummers. Leerlingen koppelen bij inschrijven hun GitHub account aan de identifier. Deze identifiers worden door Classroom toegevoegd aan de namen van de repositories voor leerlingen.
- Leerlingen kiezen hun eigen GitHub accountnaam en hun eigen teamnaam, deze zie je terug in de teams die Classroom in GitHub aanmaakt. Hou in de gaten dat de namen die leerlingen kiezen okee zijn.

### 4.4 Classroom: Alternatieven

Alternatieven voor Classroom:
- Laat leerlingen zelf hun repositories aanmaken, eventueel op basis van een template-repository die de docent online zet. Voor een eerste keer en tot enkele tientallen leerlingen is dit een prima oplossing.
- De docent maakt de repositories met de hand aan. In een situatie met enkele tientallen leerlingen is dit prima te doen.
- Gebruik eigen scripts om repo's aan te maken. Dit hebben wij enkele jaren gedaan, omdat Classroom toen nog niet betrouwbaar werkte.

## 5. Veelgestelde vragen

Heb je een voorbeeld-repository om mee aan de slag te gaan?
- Mail ons even voor de laatste versie, of ga zelf op zoek tussen onze template-repositories op
  [https://github.com/orgs/emmauscollege/repositories?q=template](https://github.com/orgs/emmauscollege/repositories?q=template)

Ik zie geen open poorten Codespaces, hoe kan dat?
- Sommige scholen blokkeren verkeer naar https://euw.rel.tunnels.api.visualstudio.com in hun firewall. Een work around is om de link naar de juiste poort op de server zelf te typen. Als je een webserver draait op poort 8080, dan doe je dat als volgt:
    - Knip de link van je Codespace boven in je browser naar een nieuw tabblad (de link lijkt op https://xxxxxx-xxxxxx-xxxxxx.github.dev)
    - Verander de link in https://xxxxxx-xxxxxx-xxxxxx-8080.app.github.dev (dus voeg -8080.app toe)
    - Je ziet nu de webpagina die je in je codespace gemaakt hebt.

De merge-conflicten zijn lastig op te lossen, is er een simpelere manier van werken?
- Gebruik de plugin live-share, waardoor leerlingen tegelijk kunnen typen in dezelfde codespace. De ene leerling nodigt de andere uit.
  
## 6. Documentatie
- GitHub<br>
To be added, er is heeeel veel te vinden. 
    - The EXTREMELY helpful guide to merge conflicts [YouTube](https://youtu.be/HosPml1qkrg?si=r02MvcxlS9AbuPky)
- Codespaces, officiele documentatie<br>
[https://docs.github.com/en/codespaces](https://docs.github.com/en/codespaces)
- GitHub Classroom, officiele documentatie<br>
[https://docs.github.com/en/education/manage-coursework-with-github-classroom](https://docs.github.com/en/education/manage-coursework-with-github-classroom)

