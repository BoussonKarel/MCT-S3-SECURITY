# Intro
**Wat is het CIA model**
|  |  |
|--|--|
| **Confidentiality** | Vertrouwelijkheid |
| **Integrity** | Integriteit |
| **Availability** | Beschikbaarheid |

**Wat is de formule van risico?**
![](https://i.imgur.com/WFO1L5R.png)

**Welke factoren dragen bij aan een risico?**
-   Threat (bedreiging)
-   Asset
-   Vulnerability (kwetsbaarheid)

**Wat veroorzaakt een bepaald risico?**
**Hoe ga je daarmee om?**

# Threats
**Wat zijn bedreigingen?**
Gevaarlijke gebeurtenisen die wellicht ooit voorkomen.

**Wat is phishing?**
Oplichting over e-mail, vaak met een onwaarschijnlijk verhaal. Vaak herkenbaar aan de malafide links, maar soms moeilijk herkenbaar.

Gericht op grote groepen mensen.

**Wat is spear phishing?**
Doelgerichte phishing, dieper uitgewerkt.
Bevat vaak persoonlijke info of bedrijfsinfo die klopt.

**Wat is double barrel?**
Twee phishing mails:
- Eerste is duidelijk een scam
- Tweede is geloofwaardig en vermeldt de eerste mail.

**Wat is smishing?**
Phishing via sms of WhatsApp.

**Wat is vishing?**
Phishing met stem ("voice"), vaak overtuigender want er is meer contact.

**Wat zijn money mules?**
Beschikbaar stellen van je rekening, bankkaart en pincode voor criminele activiteiten.

Criminelen storten geld, sluizen het door of nemen het cash op. Zo verbergen ze geld voor de overheden.

**Wat is ransomware?**
Ransomware maakt de data op je PC onbruikbaar: bestanden openen niet langer en ze vragen vaak losgeld.

**Wat is een rubber ducky?**
Een rubber ducky is een vorm van hardware die toetsaanslagen uitvoert alsof het een toetsenbord is, zonder dat de gebruiker het door heeft.

*Zo kan het RATs installeren op je pc door een binair bestand te maken en deze te compileren, in te stellen als service...*

**Wat is een white hat / black hat / gray hat hacker?**
- Black hat
*Hacking activiteit voor persoonlijk gewin (ingehuurd)*

+ White hat
*Nobele mensen die hacking skills gebruiken “for the greater good”, om beter te doen*

- Gray hat
*White hat die niet helemaal proper komt, Black hat die wat afdwaalt. Iemand die met de juiste doelen soms over de lijn gaat, soms illegale dingen doet om nobele dingen te doen.*

**Wat is een Security by Obscurity?**
Het beveiligen van het systeem op basis van "Je weet niet hoe het beveiligd is, dus je kan het niet kraken."

Dit is al vele malen slecht gebleken.

**Wat is een Man In The Middle?**
Een MITM is een persoon die data probeert op te halen van gebruikers die surfen op niet encrypted site (aan de hand van bijvoorbeeld een netwerk sniffer).

**Wat is een Man In The Middle aanval?**
Een MITM-aanval is een aanval waarbij informatie tussen twee communicerende partijen onderschept wordt zonder dat beide partijen daar weet van hebben.

**Wat is het verschil tussen limited, full en responsible disclosure?**
- Limited disclosure
*Aan niemand zeggen, fabrikant zal de moeite niet willen doen.*
+ Full disclosure
*Zomaar online gooien naar iedereen*
- Responsible  disclosure
*Zeggen aan de fabrikant, vragen hoeveel tijd ze nodig hebben. Zeggen dat je het publiceert x weken na hun oplossing.*

**Wat is threat intelligence en hoe is het belangrijk?**
"Know your enemy"

Noodzakelijk om risico in te schatten en om te beslissen over de opportuniteit van de implementatie van *tegenmaatregelen*.

# Beveiligingen

**Kwetsbaarheden**
- Software vulnerabilities
  - Geen updates
  - Foutief patch management
- Interne toegang
  - Misbruik machtigingen
  - Wraak (na ontslag)
- Extern bereikbare diensten
- Phishing / Spear phishing
  - The human factor

**Usability en Security, hoe goed komen die overeen?**
Totale / optimale security is enkel mogelijk bij onbestaande usability en omgekeerd.

**Wat is defense in depth?**
Je zorgt voor zoveel mogelijk lagen van beveiligen en vertrouwt nooit op 1 enkele maatregel, je hebt een strategie bij een incident en je plant en documenteert.

**Wat is Maltego?**
Software gebruikt voor open-source intelligence in fase 1: information gathering.

**Lees de ICC Belgian Cyber Security Guide!**
(vragen rechtstreeks hieruit)

# Access
**Wat zijn de drie beveiligingsbasissen?**
WETEN - HEBBEN - ZIJN

**De sterkte van een wachtwoord uitgedrukt in ...**
Entropie

Dictionary attack

Algemene tips

**Wat kenmerkt een goed wachtwoord?**
**Waarmee opletten bij een wachtwoord?**
- Woordenlijsten
- Vaak gebruikte wachtwoorden
- Hergebruik
- Logische patronen
- Uitlenen
- Noteren (waar derden ze kunnen achterhalen)

**Belangrijke kenmerken / tips bij een wachtwoord?**
- Voldoende "sterk"
  - Hoofdletters
  - Lang (12 tekens)
  - Verschillende soorten tekens
  - Geen bestaande woorden, logische sequenties
- Beperkte geldigheidsduur (regelmatig wijzigen)
- Gebruik 2fa voor authenticatie.
- Gebruik eventueel een wachtwoordkluis (door organisatie goedgekeurd).

**Waarom zijn wachtwoorden nutteloos?**
De manier van aanvallen verschuift. Ze gaan er niet meer vanuit dat het kraakbaar is en doen vaak aan bv. spear phishing: fake login, keylogger...

**Wat is beveiliging op hebben-basis?**
Smartcards, dongles, transponders, digipass, Google Authenticator...

Op basis van tijd, datum en een gedeeld geheim tussen server en authenticator wordt telkens een nieuw wachtwoord gegenereerd.

**Wat is beveiliging op zijn-basis?**
Iris scanners, vingerafdrukken, stemherkenning...

**Wat is Privilege escalation?**
Het misbruiken van een bug, ontwerpfout... in een besturingssysteem of softwaretoepassing om toegang te krijgen tot bronnen die normaal worden beschermd tegen een toepassing of gebruiker.

**Wat is horizontal en wat is vertical escalaton?**
- **Horizontal:** Session Hijacking van een andere gebruiker met dezelfde rechten als jou
- **Vertical:** Meer machtigingen verwerven

# Back-ups
**Back-up media's**
- Tape
- Harddisk
- USB-stick
- Cloud back-up

**Wat zijn de eigenschappen van een correcte back-up?**
Ze zijn bij voorkeur offline.
Ze voldoen aan het CIA model.

- 3 copies (*origineel +2*)
- on 2 formats (*harddrive + cloud*)
- with 1 offsite (*op locatie + cloud*)

**RAID is GEEN back-up**

**Wat zijn de onderdelen van een back-up policy?**
-   Frequentie
-   Strategie
-   Type
-   Opslag (dichtbij of andere locatie)
-   Controle van integriteit
+   Testen van disaster recovery plan.

**Wat is het grandfather-father-son systeem?**
Een back-up rotatiesysteem waarbij er drie of meer cycli zijn, zoals dagelijks, wekelijks en maandelijks.
![enter image description here](https://i.imgur.com/F18PkwQ.png)

# Pentesting
**Wat is een pentest?**
Een penetratietest is een toets van één of meerdere computersystemen op kwetsbaarheden, waarbij deze ook werkelijk gebruikt worden om in deze systemen in te breken.

**Wat is Black-box / White-box / Crystal box testing?**
- Black-box testing
*Je weet niets over de infrastructuur van het bedrijf etc...*

- White-box testing
*Je krijgt uitleg, eventueel een admin account. Je kan zien welke software en infrastructuur ze gebruiken.*

- Crystal box testing
*Korte black-box gevolgd zonder al teveel resources, daarna wat verder testen: wat kan een user, admin tools gebruiken... Heeft voordelen van zowel white als black-box testing.*

**Wat zijn de verschillende (Reconaisance) fases?**
1. Information gathering
*Algemene info, bedrijfsinfo verzamelen zoals organogram, e-mails, leveranciers...*

2. Network scanning
*Information harvesting: Sniffing, port scanning, DNS zone data... a.d.h.v. tools zoals nmap...*

3. Vulnerability assessment
*Scanners identificatie uit CVE Database, Nexpose, Retina/Iris*
4. Exploit, Access, Penetration

5. Maintaining access
*A.d.h.v. een RAT (Remote Access Tool), backdoors...*

**Wat is Enumeration?**
Het 'opsommen' van kwetsbaarheden door nmap, vulnerability scanner...

Gebruik v tools
vulnerabilities

# Sociale media
**Wat is Metadata?**
Extra data die informatie geeft over andere data.
*Bij een smartphone foto is dat bijvoorbeeld de locatie, exacte datum/tijd, camera...*

**Wat is Oversharing?**
Wanneer je alles op sociale media plaatst, vertel je eigenlijk alles aan wildvreemden.

**Wat is social engineering?**
Een techniek waarbij een computerkraker een aanval op computersystemen tracht te ondernemen door de zwakste schakel in de computerbeveiliging, nl. de mens, te kraken.

# Social Engineering
**Wat is pretexting?**
Een vorm van so

Weinig "echte" vragen over theoretische kennis.

Meer denkkader: rekening houden ermee bij beantwoording van ALLE vragen.

Verder niet zo belangrijk

# Wireless
**Wat is de ISM band?**
De industriële, wetenschappelijke en medische (ISM) radiobanden zijn radiobanden (delen van het radiospectrum) die internationaal zijn gereserveerd voor het gebruik van radiofrequentie (RF) energie voor industriële, wetenschappelijke en andere medische doeleinden dan telecommunicatie.

**Wat is Proprietary encryption?**
Proprietary encryption (bedrijfseigen cryptografie) is een term die wordt gebruikt om aangepaste coderingstechnieken te beschrijven die door de ontwerpers geheim worden gehouden om extra beveiliging toe te voegen.

---
Technologie kennen, weten wat er allemaal bestaat.

Tonen dat je nadenkt bij implementatie draadloze technologie (zoals draadloze muis)

# Virussen en malware



Wat is RAT?
Wat is scareware, homoglyphen...

# Cloud
Vrij algemeen.

Kunnen aantonen dat je in staat bent na te denken over concepten: voordelen, nadelen...

"Casusvragen"

Firma overweegt over te stappen: wat kan je hem zeggen over dit aspect?

# BYOD
**Wat is BOYD?**
BYOD (of kortweg BYO) is een bedrijfsconcept waarbij personeel apparatuur naar werk meebrengt die niet wordt uitgeleverd door de werkgever. Vaak wordt bij deze trend gerefereerd naar het meebrengen van mobiele apparatuur, zoals laptops, tablets en smartphones.

Eigenschappen.

Geen cijfers, weten dat "mobile malware" bestaat.

# Availibility
**Wat is een redundant server?**
Wanneer een server down is, wordt een redundante server gebruikt om de server die down is te vervangen.

Wat is DoS? DDoS?

**Wat is spoofing?**
Spoofing is het vervalsen van kenmerken met als doel om tijdelijk een valse identiteit aan te nemen. Dit kan bijvoorbeeld gaan om e-mail, website, IP-adres, telefoonnummer en biometrische kenmerken.

Inschattingen & berekeningen uptime & availibility

Waarden van de nines ongeveer kennen
- 3 nines = 99,9 = dikke 8 uur
- 5 nines = 99,999 = paar minuten op een jaar

# Web Sec
**Wat is OWASP?**
Het Open Web Application Security Project is een open source-project rond computerbeveiliging. Individuen, scholen en bedrijven delen via dit platform informatie en technieken.

Lees OWASP document!
Alle nodige informatie voor Web Security (naast domme problemen).

Injection, authenticatiefouten, cross site scripting...

# GDPR & Privacy
**Wat is GDPR**
De GDPR of General Data Protection Regulation (Algemene Verordening Gegevensbescherming) is een Europese verordening die de regels voor de verwerking van persoonsgegevens door particuliere bedrijven en overheidsinstanties in de hele Europese Unie standaardiseert.

**3 belangrijke punten bij protection van personal data**
-   Gegevens **beschikbaar** houden, beschermen tegen verlies
-   Gegevens **confidentieel** houden, beschermen tegen derden
-   waken over de **integriteit** van de gegevens, beschermen tegen ongeoorloofde aanpassingen.

**Wat is een DPO?**
De Data Protection Officer is verantwoordelijk voor persoonlijke data binnen een bedrijf. Elk bedrijf moet een DPO hebben.

DPO != system administrator

**Wat is AUP?**
Acceptable Use Policy, je moet deze policy accepteren om op het netwerk te mogen.

Paar vragen.

Kennen, weten wat de GDPR gaat zeggen.

"GDPR stelt dat je je werkplek steeds proper moet opruimen. Waar of niet waar?"
- Waar
*Hoewel het niet letterlijk in de wet staat moet je een "clean desk policy" hebben, anders kan je andere zaken in de wet niet gaan afdwingen.*
- ~~Niet waar~~

# Risk - pentest
**Wat is BIA?**
Systematisch proces om potentiële effecten van een onderbreking van kritieke bedrijfsactiviteiten als gevolg van een ramp, ongeval of noodsituatie te bepalen en te evalueren.

**RPO (Recovery Point Objective)**
Punt naarwaar je teruggaat (bv. elke zaterdag), de frequentie waaraan je back-ups neemt...

**RTO (Recovery Time Objective)**
Tijd nodig om terug te zetten, terug operationeel te zijn, hoe je back-ups neemt...


# IOT en ICS
**Wat is Stuxnet?**
Een schadelijk computerprogramma die zich focuste op Nucleaire systemen.

# Encryptie
**Wat is encryptie?**
Het coderen (versleutelen) van gegevens op basis van een bepaald algoritme.

**Wat is hashing?**
De transformatie van een string in een bepaald format die de originele string representeert.

**Wat betekent SSL?**
SSL betekent dat het niet kan worden afgeluisterd, dit betekent niet dat de site daarom veilig is.

**Hoe werkt Diffie-Hellman key exchange?**
![Diffie-Hellman key exchange explained](https://i.imgur.com/b8Y6JVp.png)

**Wat is PKI?**
Public Key Infrastructure
![enter image description here](https://i.imgur.com/A5r9ZG8.png)
+
![enter image description here](https://i.imgur.com/9AOiOy1.png)


**Cryptografie**
Het Diffie-Hellman protocol wordt gebruikt om:
- ~~verbindingen te versleutelen~~
- een shared secret uit te wisselen
- ~~authenticatie uit te voeren~~
- ~~de afzender te verifiëren~~

# DNS

# Exploits
**Wat is een exploit?**
Making use of (a situation) in a way considered unfair.

**Wat is reverse engeneering?**
Het onderzoeken van een product om daaruit af te leiden wat de eisen zijn waaraan het product probeert te voldoen, of om de precieze interne werking ervan te achterhalen.

**Shellcode**: Stuk uitvoerbare code voorgesteld door een sequentie hexadecimaal geëncodeerde karakters met als bedoeling die code ergens gaan te injecteren in een invulveld gevoelig voor buffer overflow.

**Enumeration**: enumereren van kwetsbaarheden door nmap, vulnerability scanner...

# Algemeen
Antwoorden op complexe vragen soms heel evident
- Gebruik standaardoplossing, houd je er niet mee bezig

**Je bent bedrijfsleider, wat zou je doen om de kwetsbaarheid van je bedrijf te verminderen?**
-   Corporate policy - Training - Awareness
-   Coding practices
-   Testing (Pentest)
-   Vulnerability management
-   Regelmatig back-ups (grandfather-father-son)
-   Disaster recovery plan
-   Physical Security
-   Firewall opzetten

| Afkorting | Betekenis |
|--|--|
|CIA|Confidentiality Integrity Availability|
| ISM | Industrial Scientific Medical band | 
| SaaS | Software as a Service | 
| BYOD | Bring Your Own Device |
| MDM | Mobile Device Management |
| Dos | Denial Of Service |
| DDos | Distributed Denial Of Service |
| OWASP | Open Web Application Security Project |
| GDPR | General Data Protection Regulation |
| AVG | Algemene Verordening Gegevensbescherming |
| DPO | Data Protection Officer |
| AUP | Acceptable Use Policy |
| BIA | Business Impact Analysis |
| RPO | Recovery Point Objective |
| RTO | Recovery Time Objective |
| ICS | Industrial Control System |
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEzMzU3OTAyNzMsNzA1NTkyNjQwXX0=
-->