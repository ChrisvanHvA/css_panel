# CSS To The Rescue

## Documentatie - Chris Gabriel III
### CMD J3 500849088

![banner](https://user-images.githubusercontent.com/90341211/224004124-4047435b-5de7-48c8-8293-0ce572bd1557.png)



# Debriefing 

Voor dit vak hadden we de opdracht gekregen om een interactieve animatie in CSS te bouwen, zonder gebruik te maken van JS.
het project moet interessant, semantisch en leerzaam zijn, want het doel is dat je aan het einde van de opdracht iets geleerd
hebt wat je eerst nog niet kon in CSS. 

Zelf heb ik niet super veel ervaring met coderen, alhoewel ik de basics begrijp heb ik me nog niet eerder verdiept in iets
specifieks.

### Om deze reden zijn er wel een aantal dingen waar ik graag wil oefenen:
-CSS has selectors
-Keyframe animaties
-3D transforms



# Week 1 - CSS Filters - Kennismakingsoefening

In de eerste week kregen we een kleine groepsopdracht om onze klasgenoten iets te leren (kennen) en werden we in groepjes
ingedeelt, mijn taak was om te laten zien wat het effect was van verschillende blend modes en filters.

### mijn uitwerking is [hier te zien!](https://chrisvanhva.github.io/MinorwebCSS/)

Ik heb deze week veel kunnen leren over niet alleen het toepassen van blend modes, maar ook om snel en efficient een project 
te maken die ik meteen kan presenteren, het liet ook aan mij zien hoe belangrijk het is om modulair aan het werk te gaan.



# Week 2 concepting and building - Eindopdracht

Deze week kregen we de briefing over de eindopdrachten.
De leerdoelen waren dat je ging experimenteren met nieuwe CSS-technieken, het inzien dat CSS niet alleen voor stylen is,
Dat je een gebruikersvriendelijke UX maakt en dat je designt met progressive enhancement in gedachte.

## Uitgangspunten

Om de studenten comfortabeler te maken met CSS selectors mochten we geen ID's en Classes toevoegen aan ons project, 
ookal zijn deze wel nuttig is het ook van belang dat we selectors leren te gebruiken.
Daarnaast mochten we niet aan Javascript zitten, met uitzondering van een slider code.
Het doel is om je meer onderzoek te laten doen naar de mogelijkheden van CSS, ipv. te doen waar je comfortabel mee bent.

## Gekozen opdracht - Modulair bedieningspaneel
Alhoewel ik in het begin wel interesse had in het maken van een rubiks cube, wist ik dat dit boven mijn niveau zou liggen.
ik kreeg vervolgens al meteen een goed idee waarin ik de bedieningspaneel kon toepassen.

### Mijn plan was om de cockpit van een ruimteschip te bouwen, met meerdere buttons en sliders om te drukken.
wat van belang was:
-Affordance (gebruikers kunnen zien hoe iets te bedienen is)
-Feedback aan de gebruiker
-Duidelijke status van alle bedieningselementen

Mijn schetsen voor het project:
![sketch for css](https://github.com/ChrisvanHvA/css_panel/blob/main/images/css%20drawings.jpg?raw=true)
Op mijn schetsen kreeg ik al snel te horen van de docenten dat ik het te ingewikkeld aan het schetsen was, ik moet eerst
beginnen met kernfuncties toe te voegen en daarna pas meer knoppen toevoegen waar tijd voor is.

Ook kreeg ik van mijn klasgenoten te horen dat veel ronde vormen moeilijker zijn om te maken in css dan rechte vormen, dus
ben ik gegaan voor een hoekigere design.

### eerste uitwerking

![version 1 css](https://user-images.githubusercontent.com/90341211/224000853-8869f27d-3f49-4b7b-b0e3-f15d8680b0a7.png)

in de eerste versie had ik een cockpit gemaakt sterren die via een animatie scalen, en daardoor de illusie geven dat ze 
dichterbij komen, ook had ik een knop gemaakt om de speed te increasen door een has: selector te gebruiken.

Omdat dit mijn eerste poging was tot een cockpit was het resultaat nog niet wat ik precies wou, ook vooral wanneer ik
de pagina scalede zag ik hoe triest mijn werk was, ik kan de volgende keer beter wat meer onderzoek doen voordat ik
willekeurig iets ga proberen.


# Week 3 Itereren en updaten.

### Tweede uitwerking

![version 2 css](https://github.com/ChrisvanHvA/css_panel/blob/main/images/css_v2.png?raw=true)

In de tweede week had ik al vrij veel feedback gekregen, ik had ook een laser toegevoegd die kan schieten op basis
van een input, ik kreeg wel als feedback dat ik deze wat mooier kon maken en dat de terugslag een beetje onrealistisch
is, tot slot heb ik een gradient background aan space toegevoegd om het interessanter te maken om naar te kijken.

### Derde uitwerking

![version 3 css](https://user-images.githubusercontent.com/90341211/224001133-cd00356f-9901-41f5-8191-57adcbb16e89.png)


ik had gehoord dat je wel gebruik van 1 slider met JS mocht gebruiken, alleen had ik dit verkeerd begrepen dus had ik 
eerst mijn eigen js slider geprogrameerd voordat ik hem vervangde met de JS slider die voorgeleverd was.
De slider zorgt ervoor dat je de snelheid kan increasen relatief van waar de slider staat.
Ook had ik de cockpit geupdate zodat hij er mooier er uit zag en betere scaling had, ik had ook geoefend met het toevoegen
van een explosion bij het einde van de laser maar ik kreeg dit niet mooi genoeg om het er in te laten, tot slot had ik
nog een planeet toegevoegd.

Deze week begon mijn project meer te lijken op wat ik wou hebben, ook merkte ik dat het toevoegen van technieken die ik
nog niet eerder heb gebruikt mooie resultaten konden leveren, ook was het een belangrijk leermoment dat niet alles 
precies zal werken zoals je zou willen, en dat je soms ideeen toch moet gaan scrappen ipv. er teveel tijd aan te 
besteden.

# Week 4 Afronding en beoordelignsgesprek


### Laatste iteratie

![version 4 css](https://user-images.githubusercontent.com/90341211/224001215-eae552f4-2737-4f88-a14e-015559fa29ab.png)


De laatste versie had een gestylede control panel met knopjes die feedback geven wanneer ze gedrukt zijn, ook ben ik de
slider gaan stylen, momenteel zijn er wel alleen maar 2 browsers die dit supporten (Chrome en Firefox), hiernaast heb ik
een functie toegevoegd om het voertuig te landen en ook weer op te stijgen uit de dampkring.

Ik heb deze week ook erg gewerkt aan het verschonen van mijn code en het verwijderen van classes die ik er nog van het
begin in had zitten.


Deze laatste week heeft me nog de tijd gegeven om mijn project toch af te krijgen op de manier dat ik had gewilt had
en om nog een interessante feature te kunnen toe te voegen waardoor het hele project een stuk completer aanvoelt.
# Reflectie

Ik heb het gevoel dat ik tijdens dit project een stuk sneller ben geworden met het maken van CSS, het maken van animaties
kan ik bijvoorbeeld uit mijn hoofd en hoef ik niks voor op te zoeken, ook snap ik hoe ik box shadows en filters kan toevoegen
en kan aanpassen, ik snap hoe ik de Has: selector kan gebruiken en waar dit me tijd kan schelen door geen JS te gebruiken.

Als ik meer tijd had zou ik graag nog meer willen werken met 3D transforms en het maken van vormen in css.

-Chris Gabriel III 09.03.2023
