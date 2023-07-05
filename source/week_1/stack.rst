~~~~~~~~~~~~~~~~~~~
The Stack
~~~~~~~~~~~~~~~~~~~

We zullen veel van de gevoeligheden bekijken aan iets wat ik een *stack* ben gaan noemen. In deze is de stack een verzameling objecten wat allemaal kapot kan.

.. image :: images/stack.png

# Netwerk

Elke computer is tegenwoordig verbonden met elkaar. Een applicatie heeft een *socket* nodig op het operating system om te communiceren tussen applicaties en applicaties die geïnstalleerd zijn op een andere computer.
Als die socket niet goed geprogrammeerd is, dan is daar een aanvalsvector beschikbaar.

# Hardware

Hardware zorgt voor het aan kunnen sluiten van een computer aan het netwerk, het invoeren en het uitvoeren van data. Alleen: ook hardware is niet onfeilbaar. Het gaat íets ver om op in te gaan, maar neem in ieder geval mee:

1) Als je bij de data kan die op hardware staat, dan ben je de eigenaar van die data. Als ik bijvoorbeeld in een ziekenhuis een laptop mee zou nemen, dan zou ik bij die data kunnen door bijvoorbeeld de harde schijf uit te bouwen. Een oplossing hier is *encryptie*. Hier gaan we later naar kijken.
2) Mocht je dit vak écht leuk vinden, dan kan je eens zoeken naar de begrippen *side-channel analyse*. Ook **Meltdown** en **Spectre** is leuk (maar pittig!) leesvoer.

.. image :: images/spectre.svg.png
    :width: 400
    :alt: Alternative text
    

----------------
Operating system
----------------
Je operating system verbind je netwerk, hardware, software in de vorm van applicaties en data aan de gebruiker. Hier komt eigenlijk alles samen. 

Je hebt bij programming essentials, en bij Operating Systems uitgebreid geleerd over hoe een Operating System gebruikers scheidt, en hoe het OS er voor zorgt dat de applicaties de resources krijgen zoals systeembeheer ze voor ogen had.
Je kan je dan ook voorstellen wat de mogelijke schade kan zijn als er een fout ontstaat in een OS! Op het moment dat een OS een zwakheid heeft, dan is het mogelijk dat de hacker van de ene applicatie overspringt naar de andere applicatie. Hij kan er voor zorgen dat hij *persistent* blijft op het operating system. Persistence is dat de hacker toegang blijft houden zolang de PC aan staat.
Je ziet met de stack ook dat hij opeens de mogelijkheid krijgt om andere PC's en servers in het netwerk aan te vallen. 

----------------
Applicaties
----------------
Een applicatie die gehackt is zorgt voor een springplank. Er vanuit gaande dat de hacker nog niet in staat is gebleken om *privilege escalation* toe te passen, kan hij wél bij de data van de gebruiker. Ook kan hij mogelijk bij de servers met de zelfde rechten als dat de gebruiker heeft.

----------------
Data
----------------
Data is in deze redelijk statisch. Tenzij ik mijn applicatie slecht schrijf, en vía de data extra rechten verkrijg.

----------------
Gebruiker
----------------
De gebruiker is altijd de zwakste schakel. Het probleem is: we kunnen tamelijk niet zonder ze :)


