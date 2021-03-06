# 17 - Encryptie
Helpt niet echt met **beschikbaarheid**
Alles versleuteld = minder beschikbaar

## Encryptie
- Geheimhouding
- Authenticatie
- Integriteit

+ Nonrepudabiliteit (onweerlegbaarheid-
  + *Hoe kan je bewijzen dat een bepaalde domeinnaam NIET van jou is*


### Traditionele cryptografie
- Substitutie
  - *Karakters veranderen door andere*
- Transpositie
  - *x plaatsen opschuiven in het alfabet*
- One-time pad

## Symmetrische Encryptie
**Sleutel + algoritme**
Plain text <-> code (met zelfde kennis kan je beide)

- Geheimhouding
 - GEEN authenticatie
 - Snel en eenvoudig
 
+ **DES**
  + *Block-cipher van 64 bit*
  + *16 encryptiecycli met telkens andere subkey*
  + *Bitlengte van de sleutel is bepalend, 56 bit is tegenwoordig te laag*
[Toffe cartoon](http://www.moserware.com/2009/09/stick-figure-guide-to-advanced.html)

- **Tripple DES, 2 of 3 sleutels**
Factor 3 moeilijker (na 1 kraken, nog 1 kraken, nog 1...)
  - Verhoogde veiligheid
  - Kan in hardware

+ **AES** / Rijndael
*IDEA
CAST-128
Blowfish (variabele sleutellengte)*

## Asymmetrische Encryptie
**Public key encryptie**
- Geheimhouding
- Authenticatie
- Werkt met sleutelPAREN
  - Private sleutel
    - NOOIT lekken aan NIEMAND.
  - Publieke sleutel
    - IEDEREEN mag die kennen.
- Niet mogelijk de ene in de andere om te zetten

Alles dat je versleutelt met de ene sleutel, kan je enkel ontsleutelen met de andere sleutel.
Zeer berekeningsintensief

|Server|Client|
|--|--|
|Kan clientberichten decoderen met private sleutel.|Kan serverberichten controleren met publieke sleutel.|
||Extra controle: De afzender is "legit", want de sleutel klopt.|

*Voorbeeld: RSA, ECC*
**Examen:**
Wat is AES? Symmetrische...
Wat is RSA? Assymetrische, Intensief...

## Hashing
Bepaalde string omzetten in iets van een bepaald format.
- Message Digest
- Variabele input
- Vaste output
- Kleine inputvariatie > Grote outputvariatie
- Niet reversibel

 *Voorbeeld: MD5, SHA2...*

## Diffie-Hellman exchange
![Diffie-Hellman key exchange explained](https://i.imgur.com/b8Y6JVp.png)

## Schneier's Law
*“Anyone, from the most clueless amateur to the best cryptographer, can create an algorithm that he himself can't break. It's not even hard. What is hard is creating an algorithm that no one else can break, even after years of analysis. And the only way to prove that is to subject the algorithm to years of analysis by the best cryptographers around.”*

**Laat het ontwerpen van crypto over aan professionals**
*Een programmeur is geen wiskundige expert.*
*Een wiskundige is geen programmeur.*

## Veilige websites
|  |  |
|--|--|
| HTTP**S**:// | "Veilige" verbindingen (SSL) |
| HTTP:// | "Onveilige" verbindingen

 + Kwaadwillige sites kunnen "HTTPS" gebruiken!
 + SSL betekent enkel dat gegevens niet kunnen worden afgeluisterd!

## Praktisch gebruik
SSL Certificaten
- Websites
- E-mail versleutelen
- E-mail afzender identificatie
- Websites
- API's
- ...

## Tips
- Gebruik steeds een correct algoritme voor de toepassing (symmetrisch, asymmetrisch, hashing).
- Checksum (transmissiefouten) <> Hashing
  - Checksum: tegen transmissiefouten
    - CRC ok voor foutcontrole, niet authenticatie
  - Hashing: tegen moedwillige aanpassing
    - MD5 is dood
- *Voorbeeld: check op rekeningnummers / creditkaarten*
  - *Beveiligd tegen het verkeerd INGEVEN, cijfertje verkeerd intikken.*

## PKI
![enter image description here](https://i.imgur.com/A5r9ZG8.png)

---
![enter image description here](https://i.imgur.com/nsilNeY.png)

---
![enter image description here](https://i.imgur.com/Zs35uLE.png)

---
### Public Key Infrastructure
![enter image description here](https://i.imgur.com/9AOiOy1.png)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE4NjY2NDg5MDEsMTc1NzI3NjAyMiwtMz
E0NzI5OTQyLDc4NzQzNTYxOSwtNDA5MzQ5NTY1LDUzNzQ5MjQ1
NV19
-->