<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" style="height:64px;margin-right:32px"/>

# bitte stelle eine umfangreiche erklärungs für die folgenden themen für einen klassen arbeit.

so dass ich nur mit lesen diese kann alles bestehen:

Themen  Klassenarbeit 01/12/2025
IPv4: 
Aufbau, Schreibweise
Funktion Subnetzmaske ("Anding"), Standardgateway
Sonderadressen (APIPA. private IP, local Host, Netzwerk ID, Broadcast Adresse)
Subnetze (klassisch, VLSM)
IPv6:
Aufbau, Schreibweise (Kürzungsmöglichkeiten)
Adresstypen (Link-Local, Global-Unicast, Multicast)
Global-Routing-Prefix - Zusammensetzung, 3-1-4
Bildung von Hostadressen (Bsp.: EUI64...)
Stateless (SLAAC) und Stateful-Autokonfiguration
Subnetze

Jetzt habe ich genug Informationen gesammelt. Lass mich eine umfassende Lernressource für deine Klassenarbeit erstellen.

# Umfassende Erklärung: IPv4 und IPv6 für deine Klassenarbeit

Dieser Leitfaden bietet dir eine vollständige Erklärung aller relevanten Themen für deine Klassenarbeit am 01.12.2025 zu IPv4 und IPv6. Mit diesem Material solltest du optimal vorbereitet sein.

## IPv4: Grundlagen und Konzepte

### Aufbau und Schreibweise von IPv4-Adressen

Eine **IPv4-Adresse** ist das Fundament der Internet-Kommunikation und besteht aus **32 Bit**, die in vier Oktette aufgeteilt sind. Ein Oktett ist jeweils 8 Bit lang und kann daher Werte von 0 bis 255 annehmen. Die Oktette werden durch Punkte getrennt, weshalb diese Darstellung auch **Dezimalpunktschreibweise** genannt wird. Ein typisches Beispiel ist die Adresse `192.168.1.1`.[^1][^2]

Da jedes Oktett 8 Bit hat und es vier Oktette gibt, ergibt sich insgesamt 2^32 = 4.294.967.296 mögliche IPv4-Adressen. Diese Adressen sind der Grundstein für die Kommunikation im Internet. Neben der dezimalen Schreibweise können IPv4-Adressen auch in **binärer Schreibweise** dargestellt werden. Hier wird jedes Oktett als 8-stellige Binärzahl geschrieben, zum Beispiel wird 192.168.1.1 zu `11000000.10101000.00000001.00000001`. Die binäre Darstellung ist besonders wichtig für das Verständnis von Subnetzmasken.[^2][^1]

### Subnetzmaske und Anding-Funktion

Die **Subnetzmaske** ist ein entscheidender Bestandteil der IPv4-Adressierung. Sie bestimmt, welche Bits einer IP-Adresse zur **Netzidentifikation** und welche zur **Hostidentifikation** gehören. Eine Standard-Subnetzmaske sieht aus wie `255.255.255.0`, was bedeutet, dass die ersten 24 Bit das Netzwerk identifizieren und die letzten 8 Bit für Hosts reserviert sind.[^3][^1]

Die **Anding-Funktion** ist das Verfahren, mit dem Geräte bestimmen, ob eine Ziel-IP-Adresse im selben Netzwerk liegt oder nicht. Dabei wird eine **bitweise UND-Verknüpfung** zwischen der IP-Adresse und der Subnetzmaske durchgeführt. Dies funktioniert nach der logischen Regel: Nur wenn beide Bits auf 1 gesetzt sind, ist das Ergebnis 1. In binärer Form:[^3]

- 1 UND 1 = 1
- 1 UND 0 = 0
- 0 UND 0 = 0

**Praktisches Beispiel**: Angenommen, dein Computer hat die IP-Adresse `192.168.1.100` mit der Subnetzmaske `255.255.255.0`. Wenn ein Paket an `192.168.1.150` gesendet wird, führt der Computer eine UND-Verknüpfung durch:```
192.168.1.100        → 11000000.10101000.00000001.01100100
255.255.255.0        → 11111111.11111111.11111111.00000000
UND-Verknüpfung      → 11000000.10101000.00000001.00000000
Ergebnis             → 192.168.1.0 (Netzwerk-ID des Empfängers)

```

Da die Netzwerk-ID gleich ist, werden die Pakete direkt (im selben Netzwerk) zugestellt.

### Standardgateway

Das **Standardgateway** ist dein Ausgang ins Internet oder zu anderen Netzwerken. Wenn ein Gerät ein Paket an eine IP-Adresse senden möchte, die nicht im eigenen Netzwerk liegt, leitet es das Paket an das Standardgateway weiter. Das Gateway führt dann eine UND-Verknüpfung mit der Ziel-IP-Adresse durch. Stellt es fest, dass die Ziel-Adresse nicht im lokalen Netzwerk ist, leitet es das Paket weiterhin an den nächsten Router weiter, bis es sein Ziel erreicht.[^4][^5]

In einem typischen Heimnetzwerk mit Subnetz `192.168.1.0/24` ist das Standardgateway meist die Adresse `192.168.1.1` – dies ist normalerweise der Router. Jedes Gerät in diesem Netzwerk erhält diese Gateway-Adresse in seinen Netzwerk-Einstellungen.[^5][^4]

### IPv4 Sonderadressen

#### APIPA (Automatic Private IP Addressing)

**APIPA** ist ein automatisches Fallback-System, das verwendet wird, wenn ein DHCP-Server nicht erreichbar ist. Das System weist sich selbst eine IP-Adresse aus dem speziellen Bereich **169.254.0.0 bis 169.254.255.255** zu. Diese Adressen sind **nur lokal verwendbar** und nicht für das Internet geeignet.[^6][^7]

Der Prozess funktioniert so: Wenn ein Windows-Computer keinen DHCP-Server findet, wählt er eine zufällige Adresse aus dem APIPA-Bereich und überprüft mit dem **Address Resolution Protocol (ARP)**, ob diese Adresse bereits vergeben ist. Wenn nicht, wird sie dem Gerät zugewiesen. Dies ermöglicht Computern im selben lokalen Netzwerk die Kommunikation miteinander, auch ohne zentrale Verwaltung.[^7]

#### Private IP-Adressen nach RFC 1918

Die **IANA** hat drei Blöcke mit privaten IP-Adressen reserviert, die innerhalb von privaten Netzwerken verwendet werden dürfen, aber nicht über das öffentliche Internet geroutet werden:[^8][^9][^10][^11]

1. **10.0.0.0 – 10.255.255.255** (Klasse A): Für große Unternehmen mit erheblichem Adressbedarf[^10][^8]
2. **172.16.0.0 – 172.31.255.255** (Klasse B): Für mittelgroße Unternehmen[^8][^10]
3. **192.168.0.0 – 192.168.255.255** (Klasse C): Für kleinere Netzwerke[^10][^8]

Diese Adressen sind nicht eindeutig im Internet und können in verschiedenen privaten Netzwerken parallel verwendet werden.

#### Localhost und Loopback-Adresse

**Localhost** ist eine spezielle Adresse, die immer auf den eigenen Computer verweist: **127.0.0.1**. Diese Adresse wird als **Loopback-Adresse** bezeichnet. Wenn du eine Anfrage an 127.0.0.1 sendest, wird sie vom TCP/IP-Stack erkannt und nicht ins Netzwerk versendet, sondern direkt an dich selbst zurückgeführt.[^12][^13][^14]

Der gesamte Loopback-Bereich bei IPv4 umfasst **127.0.0.0 bis 127.255.255.255**. Diese Adressen werden hauptsächlich zum Testen und Debuggen von Netzwerkdiensten verwendet. Dein Webserver läuft beispielsweise auf `http://localhost:8080`, was bedeutet: Verbinde dich selbst zur IP-Adresse 127.0.0.1 auf Port 8080.[^13][^14]

#### Netzwerk-ID und Broadcast-Adresse

Die **Netzwerk-ID** (auch Netzwerkadresse) ist die erste Adresse eines Subnets, wobei alle Host-Bits auf 0 gesetzt sind. Sie wird verwendet, um das Netzwerk selbst zu identifizieren. Die **Broadcast-Adresse** ist die letzte Adresse eines Subnets, wobei alle Host-Bits auf 1 gesetzt sind. Sie wird verwendet, um ein Paket an **alle Hosts** im Netzwerk gleichzeitig zu senden.[^15][^16][^17]

**Beispiel mit Subnetz 192.168.1.0/24:**

- **Netzwerk-ID**: 192.168.1.0 (alle Host-Bits sind 0)
- **Broadcast-Adresse**: 192.168.1.255 (alle Host-Bits sind 1)
- **Nutzbare Host-Adressen**: 192.168.1.1 bis 192.168.1.254 (254 Adressen)

Die erste und letzte Adresse dürfen nicht an Hosts zugewiesen werden, daher müssen immer 2 Adressen vom Adressraum abgezogen werden.[^16][^15]

### Klassische IPv4-Subnetze (Netzklassen)

Klassische IPv4-Netzklassen waren eine frühe Strukturierung des Adressraums:[^18][^19][^20]

- **Klasse A** (0.0.0.0 bis 127.255.255.255): 1 Bit für Klasse + 7 Bits für Netz-ID + 24 Bits für Host-ID; Subnetzmaske: 255.0.0.0 (/8); für sehr große Netzwerke[^19][^20]
- **Klasse B** (128.0.0.0 bis 191.255.255.255): 2 Bits für Klasse + 14 Bits für Netz-ID + 16 Bits für Host-ID; Subnetzmaske: 255.255.0.0 (/16); für mittlere Netzwerke[^20][^19]
- **Klasse C** (192.0.0.0 bis 223.255.255.255): 3 Bits für Klasse + 21 Bits für Netz-ID + 8 Bits für Host-ID; Subnetzmaske: 255.255.255.0 (/24); für kleine Netzwerke[^19][^20]
- **Klasse D** (224.0.0.0 bis 239.255.255.255): Für Multicast[^20]
- **Klasse E** (240.0.0.0 bis 255.255.255.255): Reserviert, nicht für allgemeine Nutzung[^20]

Dieses Klassensystem ist heute überholt und wurde durch **CIDR** (Classless Inter-Domain Routing) ersetzt, da Netzklassen zu verschwenderisch waren.

### Variable Length Subnet Mask (VLSM)

**VLSM** ermöglicht es, verschiedene Subnetzmasken unterschiedlicher Länge innerhalb desselben übergeordneten Netzwerks zu verwenden. Dies bietet **maximale Flexibilität** bei der Adressvergabe und verhindert Verschwendung von Adressen.[^21]

**Beispiel**: Du hast das Netzwerk 192.168.0.0/24 mit 254 möglichen Hosts. Statt diesen großen Block an eine Abteilung zu geben, kannst du VLSM verwenden:

- Abteilung A: 192.168.0.0/26 (62 Hosts)
- Abteilung B: 192.168.0.64/26 (62 Hosts)
- Abteilung C: 192.168.0.128/26 (62 Hosts)
- Abteilung D: 192.168.0.192/26 (62 Hosts)

Jede Abteilung erhält exakt so viele Adressen, wie sie benötigt, ohne zu viel zu verschwenden.

## IPv6: Die Zukunft der Internet-Adressierung

### Aufbau und Schreibweise von IPv6-Adressen

Eine **IPv6-Adresse** besteht aus **128 Bit** (doppelt so lang wie IPv4) und wird in **8 Blöcke zu je 16 Bit** aufgeteilt. Diese Blöcke werden mit **Doppelpunkten** getrennt und in **hexadezimaler Notation** geschrieben.[^22][^23][^24][^25]

Ein Beispiel einer vollständigen IPv6-Adresse:
```

2001:0db8:85a3:0000:df19:002e:0370:7344

```

Mit 128 Bit stehen theoretisch 2^128 ≈ 3,4 × 10^38 Adressen zur Verfügung – das ist eine astronomische Zahl, die für jeden Menschen auf der Erde Milliarden Adressen bietet.

### Kürzungsregeln für IPv6-Adressen

Weil vollständige IPv6-Adressen sehr lang sind, gibt es mehrere **Kürzungsregeln**, die verbindlich sind:[^26][^27][^25]

**Regel 1 – Führende Nullen entfernen**: In jedem Block können führende Nullen weggelassen werden. Beispiel: `2001:0db8` wird zu `2001:db8`.[^27][^26]

**Regel 2 – Komplette Null-Blöcke entfernen**: Besteht ein Block ausschließlich aus Nullen, kann er ganz weggelassen werden und hinterlässt nur die begrenzenden Doppelpunkte. Beispiel: `2001:db8:0:0:0:0:0:1` wird zu `2001:db8::1`.[^26][^27]

**Regel 3 – Doppel-Doppelpunkt maximal einmal verwenden**: Die längste Sequenz von Null-Blöcken kann durch `::` ersetzt werden, aber **nur einmal pro Adresse**. Das `::` kann nicht mehrfach verwendet werden, da sonst Mehrdeutigkeit entstünde (man könnte nicht eindeutig bestimmen, wie viele Null-Blöcke es ersetzt).[^25][^27][^26]

**Beispiel der Komprimierung**:
```

Vollständige Form:    2001:0db8:85a3:0000:df19:002e:0370:7344
Regel 1 (führende 0): 2001:db8:85a3:0:df19:2e:370:7344
Regel 2 (::):         2001:db8:85a3::df19:2e:370:7344

```

In der letzten Form das `::` vertritt die vier Null-Blöcke in der Mitte.

### Adresstypen von IPv6

IPv6 definiert mehrere unterschiedliche Adresstypen für verschiedene Kommunikationsszenarien:

#### Link-Local-Adressen

**Link-Local-Adressen** beginnen mit dem Präfix **fe80::/10**. Sie werden **automatisch** von jedem IPv6-Interface generiert und dienen der lokalen Kommunikation. Diese Adressen sind **nicht im Internet routbar** – sie funktionieren nur innerhalb eines einzelnen Netzwerksegments.[^28][^29][^30]

Der große Vorteil: Ohne DHCP oder manuelle Konfiguration können sich IPv6-Geräte sofort miteinander unterhalten. Link-Local-Adressen werden für **Neighbor Discovery** und die **Ermittlung des nächsten Hops** verwendet.[^29][^30][^28]

**Beispiel**: `fe80::c001:1dff:fee0:0` ist eine typische Link-Local-Adresse.

#### Global-Unicast-Adressen

**Global-Unicast-Adressen** sind die öffentlichen Adressen von IPv6 und beginnen typischerweise mit **2000::/3**. Sie sind **weltweit eindeutig** und **über das Internet routbar**. Dies ist das Äquivalent zu öffentlichen IPv4-Adressen.[^31][^32]

Die Struktur einer Global-Unicast-Adresse ist streng definiert:
- **Erste 64 Bit**: Netzwerk-Präfix (Prefix)
- **Letzte 64 Bit**: Interface-Identifier (Host-Teil)

**Beispiel**: `2001:db8:85a3::df19:2e:370:7344` ist eine Global-Unicast-Adresse.

#### Multicast-Adressen

**Multicast-Adressen** ermöglichen es, ein Paket an **mehrere Empfänger gleichzeitig** zu senden. Sie beginnen mit dem Präfix **FF00::/8**. Das zweite Byte definiert den **Geltungsbereich** (Scope) der Multicast-Adresse, die von lokal bis global reichen kann.[^33][^34]

**Beispiele von wichtigen IPv6 Multicast-Adressen**:
- **FF02::1** (All Nodes): Alle Knoten im lokalen Link-Local-Bereich
- **FF02::2** (All Routers): Alle Router im lokalen Link-Local-Bereich

Multicast ersetzt das **Broadcast-Konzept** von IPv4. Statt Broadcasts an alle Geräte im Netzwerk, verwendest du Multicast-Gruppen für gezielte Kommunikation.[^33]

### Global-Routing-Prefix: 3-1-4-Struktur

Der Aufbau eines IPv6-Präfix folgt einer hierarchischen **3-1-4-Struktur**:[^32]

Die ersten **64 Bit** einer IPv6-Adresse (Präfix) werden wie folgt unterteilt:[^32]

- **Erste 3 Felder (48 Bit = 3 × 16 Bit)**: **Site-Präfix** – beschreibt die öffentliche Topologie eines Standorts, typischerweise von einem ISP oder einer Regional Internet Registry vergeben[^32]
- **Viertes Feld (16 Bit = 1 × 16 Bit)**: **Subnetzpräfix** – definiert die interne Topologie des Netzwerks für den Router[^32]
- **Letzte 64 Bit**: **Interface Identifier** – identifiziert einen spezifischen Host im Netzwerk[^32]

Visuell dargestellt:
```

|-------- 48 Bit --------|--16 Bit--|--------- 64 Bit ---------|
| Site Prefix (von ISP) | Subnet  | Interface Identifier     |
|---- Global Prefix ---|

```

Diese Struktur ermöglicht ISPs, Präfixe hierarchisch zu verwalten, während Unternehmen ihre Subnetze intern flexibel gestalten können.

### Hostadressen und EUI-64 Format

Der **Interface Identifier** (Hostanteil) wird bei IPv6 oft automatisch aus der **MAC-Adresse** des Netzwerkinterfaces generiert, unter Verwendung des **Modified-EUI-64-Formats**. Dies macht die Konfiguration automatischer.[^35][^36][^37][^38]

**Wie EUI-64 funktioniert**:

1. **MAC-Adresse teilen**: Die 48-Bit-MAC-Adresse wird in zwei 24-Bit-Teile geteilt. Beispiel: MAC-Adresse `00:0c:29:01:02:03`[^35]

2. **FFFE einfügen**: Zwischen den zwei Teilen werden 16 Bit `FFFE` eingefügt:[^37][^35]
```

00:0c:29 + FF:FE + 01:02:03 = 00:0c:29:ff:fe:01:02:03

```

3. **Bit invertieren**: Das 7. Bit von links wird invertiert. Dies ist das **Universal/Local Bit** (U/L-Bit), das anzeigt, ob die MAC-Adresse von IEEE vergeben wurde (0) oder lokal generiert (1).[^37][^35]

**Beispiel vollständig**:
```

MAC-Adresse: 00:0c:29:01:02:03
Nach FFFE: 00:0c:29:ff:fe:01:02:03
Binär des ersten Oktetts: 00000000 → U/L-Bit ist 0
Nach Invertierung: 00000010 → U/L-Bit ist 1
Hexadezimal: 02
Finaler Interface Identifier: 020c:29ff:fe01:0203
```Sollte deine Präfix beispielsweise `2001:db8::/64` sein, wird deine vollständige Adresse: `2001:db8::020c:29ff:fe01:0203`.

### Stateless Address Autoconfiguration (SLAAC)

**SLAAC** ist ein automatisches Konfigurationsverfahren für IPv6, das **keine zentralen Server** benötigt. So funktioniert es:[^39][^36][^40]

1. **Router Advertisement empfangen**: Der Router sendet regelmäßig **Router Advertisement (RA)-Nachrichten**, die das Präfix des Netzwerks enthalten[^40][^39]
2. **Präfix kombinieren**: Das Gerät nimmt das vom Router erhaltene Präfix und kombiniert es mit seinem **Interface Identifier** (gewöhnlich via EUI-64)[^39][^40]
3. **Eindeutigkeit überprüfen**: Das Gerät überprüft mit dem **ICMPv6-Protokoll**, ob die resultierende Adresse bereits vergeben ist[^40]
4. **Adresse verwenden**: War die Adresse frei, wird sie sofort verwendet[^40]

Der große Vorteil: Geräte können sich **vollständig selbstständig konfigurieren**, ohne einen DHCP-Server zu kontaktieren. Dies ist besonders für IoT-Geräte und mobile Endgeräte hilfreich.[^39][^40]

### Stateful Autokonfiguration und Stateless DHCP

**Stateful DHCP** (DHCPv6) ist das IPv6-Äquivalent zu DHCP bei IPv4. Der DHCP-Server **speichert**, welche Adressen an welche Geräte vergeben wurden ("stateful" = mit Zustand).[^41][^39]

**Stateless DHCP** ist ein Hybrid-Ansatz. Geräte konfigurieren ihre Adressen via SLAAC, aber erhalten zusätzliche Konfigurationsinformationen (z.B. DNS-Server) von einem DHCP-Server, ohne dass dieser ihre Adressen verwaltet. Dies ist besonders sinnvoll in großen Netzwerken.[^39]


| Methode | Adressvergabe | Zusätzliche Infos | Zentraler Server |
| :-- | :-- | :-- | :-- |
| SLAAC | Vollständig automatisch (EUI-64) | Minimal (nur Router-Prefix) | Nein |
| Stateless DHCP | SLAAC + DNS/Suffix vom DHCP | Ja, via DHCP | Ja (optional) |
| Stateful DHCPv6 | Vom DHCP-Server verwaltet | Alle vom DHCP-Server | Ja (notwendig) |

### IPv6 Subnetze

**Subnetting bei IPv6** funktioniert ähnlich wie bei IPv4, verwendet aber ausschließlich die **Präfixlänge** (z.B. /64), nicht dezimale Subnetzmasken.[^42][^43][^44][^45]

Die **Standard-LAN-Präfixlänge ist /64**, wobei:[^42]

- Erste 64 Bits: Netzwerk-Präfix (Netz-ID)
- Letzte 64 Bits: Interface Identifier (Host-ID)

Dies ergibt für jeden Host 2^64 theoretisch mögliche Adressen – mehr als ausreichend.[^42]

**Beispiel von Subnetting**:
Wenn dir der ISP das Präfix `2001:db8::/48` zuteilt, kannst du dies in 256 Subnetze mit /64-Präfixen unterteilen:

- Subnetz 1: `2001:db8:0000::/64`
- Subnetz 2: `2001:db8:0001::/64`
- Subnetz 3: `2001:db8:0002::/64`
- ...
- Subnetz 256: `2001:db8:00ff::/64`

Die Bits nach Position 48 können frei für die Subnetzstruktur verwendet werden, während die letzten 64 Bits für Hosts reserviert bleiben.[^43][^44][^45][^42]

## Zusammenfassung und Prüfungstipps

**Für IPv4 musst du verstehen:**

- Jede IPv4-Adresse hat 32 Bit in 4 Oktetten
- Die Subnetzmaske und UND-Verknüpfung bestimmen Netzwerk und Host
- Netzwerk-ID (erste Adresse) und Broadcast-Adresse (letzte) sind nicht für Hosts nutzbar
- Private Adressen (RFC 1918): 10.0.0.0/8, 172.16.0.0/12, 192.168.0.0/16
- APIPA (169.254.0.0/16) ist für automatische lokale Adressen
- Localhost (127.0.0.1) ist die Loopback-Adresse
- Klassische Netzklassen (A, B, C) sind veraltet, CIDR ist modern
- VLSM erlaubt flexible Subnetzmasken

**Für IPv6 musst du verstehen:**

- 128 Bit in 8 Blöcken mit hexadezimalen Ziffern
- Kürzungsregeln: führende Nullen und `::` für Null-Sequenzen (max. 1x pro Adresse)
- Link-Local (fe80::/10): automatisch, lokal nur
- Global-Unicast (2000::/3): öffentlich, weltweit routbar
- Multicast (FF00::/8): an mehrere Empfänger gleichzeitig
- 3-1-4-Struktur: 48 Bit Site + 16 Bit Subnet + 64 Bit Host
- EUI-64: MAC-Adresse wird zu Interface Identifier konvertiert
- SLAAC: völlig automatische Konfiguration ohne Server
- /64-Subnetze sind Standard für LANs

Mit diesem Verständnis solltest du die Klassenarbeit erfolgreich bestehen! Viel Erfolg! 🚀
<span style="display:none">[^46][^47][^48][^49][^50][^51][^52][^53][^54][^55][^56][^57]</span>

<div align="center">⁂</div>

[^1]: https://netzwerk-guides.de/ipv4-adressen/

[^2]: https://de.wikipedia.org/wiki/IPv4

[^3]: https://www.teltonika-networks.com/de/newsroom/understanding-netmask-a-comprehensive-guide-to-network-subnetting

[^4]: https://ausbildung-in-der-it.de/lexikon/standardgateway

[^5]: https://sid-500.com/2017/06/19/was-ist-ein-default-gateway/

[^6]: https://www.it-administrator.de/lexikon/automatic_private_ip_adressing.html

[^7]: https://www.computerweekly.com/de/definition/APIPA-Automatic-Private-IP-Addressing

[^8]: https://hoegerl.com/der-private-adressenbereich-bei-ipv4/

[^9]: https://docs.oracle.com/cd/E19957-01/820-2980/ewpop/index.html

[^10]: https://www.computerweekly.com/de/definition/RFC-1918

[^11]: https://www.ionos.de/hilfe/server-cloud-infrastructure/privates-netzwerk/private-ip-adressbereiche/

[^12]: https://www.seo-kueche.de/lexikon/localhost/

[^13]: https://www.hostwinds.de/blog/loopback-address

[^14]: https://www.united-domains.de/help/lexikon/localhost-127-0-0-1/

[^15]: https://www.youtube.com/watch?v=MIcvqUlni28

[^16]: https://ausbildung-in-der-it.de/lexikon/broadcast-adresse

[^17]: https://www.fachinformatiker.de/topic/156707-subnetting-broadcastadresse-berechnen/

[^18]: https://ausbildung-in-der-it.de/lexikon/netzklasse

[^19]: https://www.computerweekly.com/de/definition/IPv4-Adressklasse-IPv4-Netzklasse

[^20]: https://www.elektronik-kompendium.de/sites/net/2011221.htm

[^21]: https://interlir.com/de/2024/02/19/einfache-ipv4-subnetting-und-maskenberechnungsmethode/

[^22]: https://www.heise.de/IPv6-Adressen-3484199.html

[^23]: https://docs.tia.siemens.cloud/r/de-de/v21/scalance-x/w/m-projektieren/scalance-w-projektieren/wissenswertes/ip-adressen/ipv6-adressen/aufbau-einer-ipv6-adresse

[^24]: https://de.wikipedia.org/wiki/Wikipedia:IPv6

[^25]: https://de.wikipedia.org/wiki/IPv6

[^26]: https://www.youtube.com/watch?v=nzme14g-ZTE

[^27]: https://www.elektronik-kompendium.de/news/verbindliche-notation-fuer-ipv6-adressen/

[^28]: https://ipcisco.com/lesson/ipv6-address-types/

[^29]: https://www.cisco.com/c/de_de/support/docs/ip/ip-version-6-ipv6/113328-ipv6-lla.pdf

[^30]: https://sid-500.com/2017/01/10/cisco-ipv6-link-local-adressen-und-router-advertisements/

[^31]: https://www.uninets.com/blog/ipv6-address-types

[^32]: https://docs.hetzner.com/de/robot/dedicated-server/ip/ip-basics/

[^33]: https://de.wikipedia.org/wiki/Multicast

[^34]: https://learn.microsoft.com/de-de/windows/win32/winsock/multicast-destination-addresses-2

[^35]: https://de.wikipedia.org/wiki/EUI-64

[^36]: https://www.elektronik-kompendium.de/sites/net/1902111.htm

[^37]: https://gernardt.net/netzwerk/ipv6-internet-protocol-version-6/

[^38]: https://www.youtube.com/watch?v=DIeqFb53CyE

[^39]: https://thisbridgeistheroot.com/blog/navigating-ipv6-address-configuration-slaac-stateful-dhcpv6-and-stateless-dhcp

[^40]: https://www.networkacademy.io/ccna/ipv6/stateless-address-autoconfiguration-slaac

[^41]: https://www.reddit.com/r/ipv6/comments/1laj6h0/what_should_i_use_for_the_assigned_type_for_ipv6/

[^42]: https://www.juunit.com/blog/subnetting

[^43]: https://de.wikipedia.org/wiki/Subnetz

[^44]: https://www.windows-faq.de/2024/06/18/subnetzpraefixlaenge-aufgaben-und-funktion-bei-windows/

[^45]: https://www.ionos.de/hilfe/server-cloud-infrastructure/ip-adressen/ipv6-grundlagen/

[^46]: https://gernardt.net/netzwerk/ipv4-internet-protocol-version-4/

[^47]: https://surfshark.com/de/blog/arten-von-ip-adressen

[^48]: https://www.o2business.de/magazin/ipv4/

[^49]: https://www.youtube.com/watch?v=rE9hzNtLHUg

[^50]: https://www.youtube.com/watch?v=J5z1qlcaqdY

[^51]: https://www.ionos.de/digitalguide/server/knowhow/broadcast-adresse/

[^52]: https://www.windows-faq.de/2023/11/30/standardgateway-aufgabe-und-funktion/

[^53]: https://www.catchpoint.com/benefits-of-ipv6/ipv6-compression-rules

[^54]: https://www.iana.org/assignments/ipv6-multicast-addresses/ipv6-multicast-addresses.xhtml

[^55]: https://www.lancom-systems.de/docs/LCOS/Refmanual/DE/topics/lcos_ipv6_basics_design.html

[^56]: https://www.youtube.com/watch?v=9YysdPs3aBs

[^57]: https://www.reddit.com/r/networking/comments/1ata8d5/what_is_the_example_use_of_ff012_ipv6_multicast/

