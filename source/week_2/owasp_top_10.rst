OWASP Top 10
******************************

Het lijkt mij niet handig om alles wat op internet staat hier te repliceren. Ga dus vooral kijken op <"https://owasp.org/Top10/">
Ik heb vanuit de Top10 zaken die ik veel fout zie gaan op de werkplaats opgenomen.

A01:2021 - Broken Access Control (<https://owasp.org/Top10/A01_2021-Broken_Access_Control/>_)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
* Geen scheiding van rechten
* ACL's voorbij komen door het aanpassen van de URL
* Toegang verkrijgen tot de API door het missen van ACL's op GET, POST, PUT en DELETE
* Elevation of privilege. Je kunnen gedragen als een gebruiker zonder ingelogged te zijn. Of taken als admin kunnen doen terwijl je een reguliere gebruiker bent.

A02:2021 - Cryptographic Failures (<https://owasp.org/Top10/A02_2021-Cryptographic_Failures/>_)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Je wil alle data (at rest en in transit) zoveel mogelijk versleutelen. Op te letten op:

* Wordt er data uberhaupt plaintext verstuurd?
* Heb je je crypto-engines up-to-date? Maak je gebruik van oude cyphers?
* Heb je default keys in gebruik (vaste sleutels die overal hergebruikt worden)
* Gebruik je oude hashingmethoden?

Op te lossen:

* Zorg er voor dat je weet waar je data hebt. Check dit met DFD en STRIDE-analyse. 
* Móet je data opslaan?
* Versleutel data als het gevoelige data is
* Gebruik geen plain-text protocollen als FTP en SMTP


A01:2021 – Broken Access Control
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~



A01:2021 – Broken Access Control
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~



A01:2021 – Broken Access Control
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~



A01:2021 – Broken Access Control
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~



A01:2021 – Broken Access Control
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~



A01:2021 – Broken Access Control
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~