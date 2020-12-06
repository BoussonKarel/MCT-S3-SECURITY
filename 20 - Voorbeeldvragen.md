# Voorbeeldvragen
**Formule van Risico**  
![](https://i.imgur.com/WFO1L5R.png)

Comment

**encryptie berekenen**  
Er worden twee priemgetallen gekozen voor deze exchange, zorg ervoor dat Prime > Generator.  
bijvoorbeeld  
G = 3  
P = 17

Bob en Alice kiezen elk een willekeurig getal

Alice kiest 15.  
Bob kiest 13.

Alice berekent dat 3 tot de macht 15 modulo 17 gelijk is aan 6.  
Bob berekent dat 3 tot de macht 13 modulo 17 gelijk is aan 12.

Nu worden die uitkomsten “getoond” aan elkaar.  
Alice ziet de 12.  
Bob ziet de 6.

Alice berekent dat 12 tot de macht 15 modulo 17 gelijk is aan 10.  
Bob berekent dat 6 tot de macht 13 modulo 17 gelijk is aan 10.

Diffie-Hellman key exchange compleet. De secret key is 10.

**CIA model**

-   Confidentiality --> Vertrouwelijkheid
-   Integrity --> Integriteit
-   Availability --> Beschikbaarheid

**Wat is een bedreiging**

-   Een bedreiging is een gevaarlijke gebeurtenis die wellicht ooit voorkomt

**Wat kenmerkt een goed wachtwoord?**  
Kies het beste antwoord:

-   Dat het absoluut geen delen van bestaande begrippen bevat
-   Een goed wachtwoord moet zeer moeilijk leesbaar zijn
-   Dat het voldoende verschillende soorten tekens bevat, minstens cijfers, kleine- en hoofdletters, en een of meerdere speciale tekens
-   De totale entropie van het wachtwoord, voornamelijk bepaald door de lengte

**Wpa Enterprise is technisch veiliger dan WPA Personal**

-   Waar
-   Niet waar

**Wat is privilege escalation**

Privilege-escalatie is het misbruiken van een bug, ontwerpfout of configuratietoezicht in een besturingssysteem of softwaretoepassing om verhoogde toegang te krijgen tot bronnen die normaal worden beschermd tegen een toepassing of gebruiker.

**Horizontale escalation:** Session Hijacking van een andere gebruiker met dezelfde rechten als jou.

**Verticale escalation:** Meer machtigingen verwerven.

**Backup Media’s:**

-   Tape
-   Harddisk
-   USB-stick
-   Cloud-backup

RAID is geen backup!

**Kies een passend algoritme in de juiste categorie**

Symmetrische encryptie: Tripple DES, AES/Rijndael, IDEA, CAST-128 en Blowfish  
Assymetrische encryptie: RSA, ECC  
Hashing functie: MD5, SHA2

**Wat is defence in depth ?**

-   je zorgt voor zoveel mogelijke lagen van protection
-   Je hebt een strategie bij een incident
-   Plannen en documenteren

**Alle beveiligingssystemen baseren zich op deze basisregels**

-   Weten (something you know)
-   Hebben (something you have)
-   Zijn (something you are)

**Je bent bedrijfsleider, wat zou je doen om de kwetsbaarheid van je bedrijf te verminderen?**

-   Corporate policy - Training - Awareness
-   Coding practices
-   Testing (Pentest)
-   Vulnerability management
-   Regelmatig backups nemen (grandfather father son)
-   Disaster recovery plan
-   Physical Security
-   Firewall opzetten

**Welke factoren dragen bij aan een risico?**

-   Bedreiging
-   Kwetsbaarheid
-   Asset

**Wat is een pentest?**

Een penetratietest of pentest is een toets van een of meer computersystemen op kwetsbaarheden, waarbij deze kwetsbaarheden ook werkelijk gebruikt worden om in deze systemen in te breken.

Fase’s:

-   Information gathering
-   Network scanning
-   Vulnerability assessment
-   Exploit, Access, Penetration
-   Maintaining access

**Wat is de ISM band?**

De industriële, wetenschappelijke en medische (ISM) radiobanden zijn radiobanden (delen van het radiospectrum) die internationaal zijn gereserveerd voor het gebruik van radiofrequentie (RF) energie voor industriële, wetenschappelijke en andere medische doeleinden dan telecommunicatie.

**Wat is Proprietary encryption?**

Proprietary encryption (bedrijfseigen cryptografie) is een term die wordt gebruikt om aangepaste coderingstechnieken te beschrijven die door de ontwerpers geheim worden gehouden om extra beveiliging toe te voegen.

**Wat is BOYD?**

BYOD (of kortweg BYO) is een bedrijfsconcept waarbij personeel apparatuur naar werk meebrengt die niet wordt uitgeleverd door de werkgever. Vaak wordt bij deze trend gerefereerd naar het meebrengen van mobiele apparatuur, zoals laptops, tablets en smartphones.

**Wat is een redundant server?**

Redundant servers --> Upon detecting a server as being down, a redundant server is used to replace the down server

**Wat is social engeneering?**

Social engineering of social hacking, is een techniek waarbij een computerkraker een aanval op computersystemen tracht te ondernemen door de zwakste schakel in de computerbeveiliging, namelijk de mens, te kraken.

**Wat is een man in the middle?**

Man in the middle is een persoon die data probeerd op te halen van gebruikers die surfen op niet encrypted site aan de hand van een netwerk sniffer bijvoorbeeld.

**Wat is een man in the middle aanval?**

Een man-in-the-middle-aanval (MITM-aanval) is een aanval waarbij informatie tussen twee communicerende partijen onderschept wordt zonder dat beide partijen daar weet van hebben.

**Wat is spoofing?**

Spoofing = Spoofing is het vervalsen van kenmerken met als doel om tijdelijk een valse identiteit aan te nemen. Dit kan bijvoorbeeld gaan om e-mail, website, IP-adres, telefoonnummer en biometrische kenmerken.

**Wat is OWASP?**

Het Open Web Application Security Project is een open source-project rond computerbeveiliging. Individuen, scholen en bedrijven delen via dit platform informatie en technieken.

**Wat is GDPR**

General Data Protection Regulation (Algemene verordening gegevensbescherming) = een Europese verordening die de regels voor de verwerking van persoonsgegevens door particuliere bedrijven en overheidsinstanties in de hele Europese Unie standaardiseert.

**3 belangrijke punten bij protection van personal data**

-   Gegevens **beschikbaar** houden, beschermen tegen verlies
-   Gegevens **confidentieel** houden, beschermen tegen derden
-   waken over de **integriteit** van de gegevens, beschermen tegen ongeoorloofde aanpassingen.

**Wat is een DPO?**

Data Protection Officer = verantwoordelijk voor persoonlijke data binnen een bedrijf. Elk bedrijf moet een DPO hebben.

DPO != system administrator

**Wat is AUP?**

Acceptable Use Policy, je moet deze policy accepteren om op het netwerk te mogen.

**Wat is BIA?**

Business impact analysis (BIA) is een systematisch proces om de potentiële effecten van een onderbreking van kritieke bedrijfsactiviteiten als gevolg van een ramp, ongeval of noodsituatie te bepalen en te evalueren.

**RPO**

-   Recovery point objective
-   How often do we take back-ups?
-   How far back can we go?
-   What’s lost

**RTO**

-   Recovery Time Objective
-   When back online
-   How do we take back-ups?

**Wat is Stuxnet?**

Stuxnet is een schadelijk computerprogramma die zich focuste op Nucleaire systemen.

**Wat is SCADA?**

SCADA afkorting van Supervisory Control And Data Acquisition, is het verzamelen, doorsturen, verwerken en visualiseren van meet- en regelsignalen van verschillende machines in grote industriële systemen.

**Wat is encryption?**

het coderen (versleutelen) van gegevens op basis van een bepaald algoritme.

**Wat is Hashing?**

Hashing is de transformatie van een string van karkters in een value of key die korter is en de originele string representeerd

**Wat betekent SSL?**

SSL betekent dat het niet kan worden afgeluisterd, dit betekent niet dat de site daarom veilig is.

**Wat is een exploit?**

Exploiting = making use of (a situation) in a way considered unfair.

**Wat is reverse engeneering?**

Reverse engineering is het onderzoeken van een product om daaruit af te leiden wat de eisen zijn waaraan het product probeert te voldoen, of om de precieze interne werking ervan te achterhalen.

**Wat is een Static analysys of statische analyse?**

Static analysis, also called static code analysis, is a method of computer program debugging that is done by examining the code without executing the program.

**En Dynamic analysys?**

Live code gaan testen in de debugger.

**Wat is Shadow-IT en hoe kunnen we het tegengaan?**

Shadow IT is een fenomeen waar werknemers hun eigen **niet toegelaten toestellen** meenemen naar hun werk.  
Bijvoorbeeld de GDPR en de AUP zegt dat er een beveiliging moet zitten achter de printer. Zodat er geen sensitieve data rondslingert. Maar sommige werknemers hebben geen zin om bij de printer te wachten dus ze brengen hun eigen printer mee.

Je kan het tegen gaan door **awareness** te geven aan de werknemers, **uitleggen waarom** deze regels nodig zijn.

**Wat is het Grandfather-father-son systeem?**  
Het pricipe van 3 vershillende backup cycles die apart van elkaar lopen

**Son:** elke dag  
**Father:** elke week  
**Grandfather:** elke maand

**Wat is DNSSEC**  
DNSSEC zijn DNS security extensions die ervoor zorgen dat DNS beveiligd is tegen allerlei attacks bij voorbeeld de Kaminsky attack [https://www.youtube.com/watch?v=JIG0giryqqY](https://www.youtube.com/watch?v=JIG0giryqqY).  
Je hebt NSEC en NSEC3.  
Deze twee werken allebei rond het principe dat ze een chain of trust maken. Zo kan een hacker niet voordoen als .BE DNS server. De parent zal altijd de trusted public key, die de parent ook gesigned heeft, geven van zijn children.  
Bv ik zoek voor [howest.be](http://howest.be/).

1.  Ik vraag aan .BE waar is [Howest.be](http://howest.be/)
2.  Hij antwoord a.b.c.d samen met de, door de .BE gesigned, public key van [Howest.be](http://howest.be/)
3.  .BE maakt een chain of trust door de public key van [Howest.be](http://howest.be/) te vertrouwen.
4.  Eenmaal de client dus een request stuurt naar a.b.c.d versleuteld met die public key kan slechts de enige echte server met de private key die decrypten en het echte antwoord sturen die dan weer versleuteld is.

Het is dus wel de bedoeling dat je de ROOT vertrouwt want de chain of trust moet volledig zijn. de root moet de TLD (bv .BE) vertrouwen maar ook .BE moet [howest.be](http://howest.be/) vertrouwen.

NSEC3 is nu de verbeterde versie van NSEC die ervoor zorgt dat de dns records hashed zijn zodat je geen zone walking kan doen.

![](https://i.imgur.com/8NOkVRw.png)  
![](https://i.imgur.com/e8k5Uy9.png)

**Lijst met afkortingen**

-   CIA => Confidentiality Integrity Availability
-   ISM => Industrial Scientific Medical band
-   SaaS => Software as a Service
-   BYOD => Bring Your Own Device
-   MDM => Mobile Device Management
-   Dos => Denial Of Service
-   DDos => Distributed Denial Of Service
-   OWASP => the Open Web Application Security Project
-   GDPR => General Data Protection Regulation
-   AVG => Algemene Verordening Gegevensbescherming
-   DPO => Data Protection Officer
-   AUP => Acceptable Use Policy
-   BIA => Business Impact Analysis
-   RPO => Recovery Point Objective
-   RTO => Recovery Time Objective
-   ICS => Industrial Control System
-   SCADA => Supervisory Control And Data Acquisition
<!--stackedit_data:
eyJoaXN0b3J5IjpbNDc2NDg5MjU3LC0xOTY4OTU0ODM5XX0=
-->