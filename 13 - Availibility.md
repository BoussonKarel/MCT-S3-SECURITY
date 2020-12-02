# Availibility
## High availibility
- High availibility op netwerkniveau
- High availibility op systemen
- Clusters
  - 5 servers waarvan er 3 workload kunnen behandelen
- Redundante servers
  - Server down? Redundant server vervangt.
- Redundante server ruimte (disaster center)
- Virtualisatie

## Externe netwerk bedreigingen
- DoS
  - Server overspoelen met TCP en UDP packets
- DDoS
- Portscanning
- Sniffers
- Man in the middle
- Spoofing
- ...

### Denial of Service (DoS)
- E-mail bommen
  - Emails with "+++ath0" would disconnect modems.
- Repetitive login
  - Lockout instellen. 3 pogingen = lockout.
- SYN-Flood
  - Weinig moeite: 1 pakketje = veel moeite
- UDP-Flooding
  - *Gigabit aan UDP traffic sturen, dan gaat de server het lastig hebben.*
- Ping of death
  - Maximale grootte van een ICMP Echo Request pakket was x bytes
  - Groter pakket > Blue Screen of Death
  - Sturen is gemakkelijk: kan via ingebouwde "ping" commando.

#### SYN-Flood
**A --> SYN --> B**
*A stuurt 1 pakketje*

**B <-- SYNACK <-- A**
*B ontvangt het pakketje en zet er één van zijn 20 workers op. Die is verantwoordelijk voor de afhandeling. Worker bestaat uit Process, Memory...*

*Ondertussen stuurt hij een SYNACK.*

*Wanneer de workers op zijn doet hij aan Forking: meer workers aanmaken. Dit vergt veel CPU en memory*

**A --> ACK --> B**
*A negeert de SYNACK*

*De worker zal wachten en blijven pakketjes sturen*

*De worker zal wenen tot zijn wachttijd expired.*

*Client blijft op deze manier SYN pakketjes sturen.*

### Distributed DoS (DDoS)
- DoS simultaan vanuit verschillende locaties
- Zeer moeilijk tegen te houden
- Meestal zijn de "drones" geïnfecteerde thuis-PC's

### Spoofing
Vervalsen van informatie in de header
- IP Spoofing
- MAC Spoofing
- E-mail spoofing

## "Cloudflare"
Attacks gebeuren zodanig veel dat het "regelmaat" is.
Ze zijn erop voorzien en hebben de brandbreedte ervoor.

Confidentiality? Cloudflare kan ALLES lezen!


## Availibility
**Update <> Availibility**
99,9% = 3 nines = 8,76u/jaar
99,999% = 5 nines = 5,26m/jaar
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjEzODg5NzYxOCwxNjgzNzc5ODUyXX0=
-->