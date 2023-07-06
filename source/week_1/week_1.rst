#####################################
Week 1 - Basis
#####################################

Week 1 wil een *level playing field* geven voor alle studenten. Na het doornemen van week 1 weet je de grondbeginselen van information security:

* Gevoeligheid in data
* Wat is een **vulnerability**?
* Wat is een **exploit**?
* Wat is een hacker eigenlijk? En zijn er wel hackers?
* Niet benoemd in de Powerpoint-Slides, maar wel belangrijk: CIA: **Confidentiality**, **Integrity** en **Availability**

.. include:: cia.rst

#####################################
Gevoeligheden
#####################################

Een gevoeligheid in een applicatie ontstaat omdat een programmeur programmeerfouten maakt. Een programmeerfout is zo gemaakt. Interessant leesvoer in deze is het werk van Edsger Dijkstra [#]1[#]_
, een Nederlandse programmeur die grondlegger van de moderne informatica is geweest, en alles vanuit wiskunde bekeek.
De vraag blijft: kan je wiskundig bewijzen of een applicatie foutloos is? Zover ik weet is dat nog niet mogelijk.

Dus, vanuit een programmeerfout wordt een *gevoeligheid* gegenereerd.

.. [#]https://nl.wikipedia.org/wiki/Edsger_Dijkstra

#####################################
Vulnerability
#####################################

Niet elke gevoeligheid zorgt voor de mogelijkheid tot misbruik. Als dit wel ontstaat, dan heb je het over een *vulnerability*. Een vulnerability kán bestaan in software zonder dat iemand daar vanaf weet.
Zodra dit bekend wordt bij de maker van de software, kan deze gaan werken aan een *patch*. Een patch heeft als doel om de vulnerability weg te doen nemen. Veelal zal de versie van de software dan opgehoogd worden, en zullen de gebruikers dan de software moeten *patchen* of *updaten*.

Dit patchen alleen al zorgt voor risico's. Zodra er een patch uitkomt ("Installeer versie x.y.z NU"), dan wordt het voor de aanvaller een kwestie van het vinden van die vulnerability.

#####################################
Exploit
#####################################

De aanvaller kan dan gaan kijken hoe hij de vulnerability kan gaan *exploiten*, oftwel: misbruiken. Een **exploit is dus een stuk programma om misbruik te maken van een vulnerability**. De exploit heeft vaak als doel om verder toegang te krijgen tot het operating system van het systeem waar het oorspronkelijke programma op draait. De hacker krijgt dan de mogelijkheid om *lateraal te bewegen* door het netwerk, oftwel het verkrijgen van toegang op het netwerk met dezelfde rechten als degene die de software draait. Op het moment dat de hacker probeert om meer rechten te krijgen dan hebben we het over *privilege escalation*. In dit geval probeert de hacker via de gebruiker bijvoorbeeld de rol van **Administrator** of **root** te krijgen.

Bijzonder interessant leesvoer in deze is de `**Cyber Kill Chain** <https://www.lockheedmartin.com/en-us/capabilities/cyber/cyber-kill-chain.html>`_ van *Lockheed Martin*. 

.. include :: stack.rst