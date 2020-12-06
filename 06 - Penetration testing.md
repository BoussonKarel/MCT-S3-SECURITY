# 6 - Penetration testing
- **Bewustwording van security**
- **Testen van security**
+ **Wat gebeurt er écht?**
+ **Wat (kan) de hacker doen?**

**Black-box testing**
Je weet niets over de infrastructuur van het bedrijf etc...

**White-box testing**
Je krijgt uitleg, eventueel een admin account. Je kan zien welke software en infrastructuur ze gebruiken.

**Crystal box testing**
*Eerst kort een black box test (maximum tijd die je eraan besteedt) zonder al te veel resources erin te steken of gigantisch je best te doen.*

*Afhankelijk van de resultaten verder testen:*
- *Wat kan een gewone user account (privilege* escalation)
- *Met admin account wat tools testen*

*Heeft ook de voordelen van white box: je vindt zaken die je niet vond met black box.*

- **Wettelijke beperkingen!!**
- **Wat met aansprakelijkheid?**

## Reconaisance Fases
### Fase 1 / Information gathering
Algemene info, bedrijfsinfo:
- E-mailadressen
- Organogram
- Leveranciers (*toetsenborden met keyloggers*)

+ **Inzetbaar voor social engineering**
+ **Spear-phishing**

- **Tools & attack surfaces**
  - Google
  - DNS
  - Sociale netwerken
  - Website
  - ...

### Fase 2 / Netwerk scanning
*Nmap, WireShark...*

**Network reconnaissance**
- Sniffing
- Port scanning
  - OS fingerprinting
  - Detectie van gebruikte software
- DNS zone data
- Information harvesting

### Fase 3 / Vulnerability assessment
Scanners
Identificatie uit CVE Database
Nexpose
Retina/Iris

### Fase 4
**Exploit, Access, Penetratie...**
- Availibility !
- Condifentiality !
- Legaliteit !

### Fase 5
**Maintaining access.**
A.d.h.v. RAT (Remote Access Tool), backdoors...

*Hoewel een echte aanvaller dit zou doen, hier zéér voorzichtig mee omgaan.*
*Niets van backdoors voorzien die minstens niet veiliger is dan de huidige standaarden.*

*Een echte aanvaller zal ook zijn logs verwijderen etc... Maar... hier is geen meerwaarde om ze te wissen.*

- Availibility !
- Condifentiality !
- Legaliteit !
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwODI2MjEwMDJdfQ==
-->