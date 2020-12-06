# 1 - Security - Intro
## Doel
 - Security awareness  (bewustwording)
 - Correcte nomenclatuur (communicatie)
 - Advies over verantwoordelijkheden
 - Inzien v/d consequenties v/h falen van security
 - Situeren en herkennen van problemen
 - Oplossingen correct implementeren
 - Correcte methodieken toepassen

> Alles suckt en zal blijven sucken

## Risico
```
risico = ((bedreiging * kwetsbaarheid) / tegenmaatregelen) * impact
```
![Threat, Asset, Vulnerability, Risk](https://i.imgur.com/mPykVqv.png)
![Threat, Asset, Vulnerability, Risk](https://i.imgur.com/TUuapNJ.png)

### Tegenmaatregelen
Er is geen magische oplossing.

**Tegenmaatregelen** reduceren de kwetsbaarheid, maar zijn(slechts nuttig indien effectief gebruikt.

Bedreigingen kunnen niet door 1 partij worden tegengehouden.

**Internet:** zeer veel mensen, zeer snel, met weinig inspanning te bereiken.

## Theoretisch model
### CIA-Model
| | |
| -- | -- |
| **Confidentiality** | Vertrouwelijkheid |
| **Integrity** | Integriteit |
| **Availability** | Beschikbaarheid |

## Bedreiging / kwetsbaarheid
**Threat** (bedreiging)
**Vulnerability** (kwetsbaarheid)

## Bedreigde doelen
- Infrastructuur
- Gegevens
- Operationaliteit
## Impact
- Bedrijfsimpact bepaalt opportuniteit van beveiligingsinvestering.
> *Pas vervangen als de kost van de incidenten groter is dan de kost van de investering*
- Financiële impact =bedrijfsspecifiek
## Voorbeelden
**Confidentiality**
*Punten van een ander kunnen raadplegen door te hacken.*
**Integrity**
*Punten kunnen aanpassen door te hacken.*
**Availability**
*IBAMAFLEX kunnen plat leggen.*

> **Backup maken:** Availibility+
> *Backup wordt gestolen: Confidentiality-*
> 
> **Backup encrypteren:** Confidentiality+
> *Encryptiesleutel kwijt: Availibility-*
> 
> **Encryptiesleutel op server zetten:** Availibility+
> *Server brandt af, backups onbruikbaar: Availibility-*



<!--stackedit_data:
eyJoaXN0b3J5IjpbNzcyNjI5OTBdfQ==
-->