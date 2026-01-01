## 3: Clients in Rechnernetzwerke einbinden

**Kurz-Definition:**
Die Einbindung von Clients in Rechnernetzwerke umfasst die Planung, Installation, Konfiguration und Wartung von Endgeräten, damit diese sicher und zuverlässig auf Netzwerkressourcen zugreifen können.

**Tabellarische Übersicht:**

| Aspekt | Beschreibung | Bedeutung |
|--------|--------------|-----------|
| **Planung** | Anforderungen analysieren, Netzwerkstruktur verstehen | Erfolgreiche Integration |
| **Installation** | Hardware einrichten, Software konfigurieren | Funktionale Einbindung |
| **Konfiguration** | Netzwerkeinstellungen, Authentifizierung | Sicherer Zugriff |
| **Prüfung** | Verbindungstests, Namensauflösung | Funktionsfähigkeit sicherstellen |
| **Wartung** | Updates, Monitoring, Fehlerbehebung | Langzeitbetrieb |

**Visuelle Darstellung:**
```
Client-Einbindung Prozess:
    Planung
         ↓
    Installation (Hardware + Software)
         ↓
    Konfiguration (Netzwerk + Authentifizierung)
         ↓
    Prüfung (Verbindungstest + Namensauflösung)
         ↓
    Wartung (Updates + Monitoring + Fehlerbehebung)
         ↓
    Betrieb

Komponenten:
    Client → Switch → Router → Internet
         ↓
    Server (Dateien, Druck, E-Mail)
```

**Praxis-Beispiel:**
Ein neuer Mitarbeiter bekommt einen Laptop:
1. **Planung:** Anforderungen prüfen (Windows 11, Office, Zugriff auf Dateiserver)
2. **Installation:** Laptop einrichten, Windows installieren, Netzwerkkarte prüfen
3. **Konfiguration:** IP-Adresse per DHCP erhalten, Domain-Anmeldung einrichten, Drucker hinzufügen
4. **Prüfung:** ping Gateway, ping Dateiserver, Zugriff auf Netzwerkressourcen testen
5. **Wartung:** Regelmäßige Windows-Updates, Antivirus-Scans, Monitoring der Verbindung

**Prüfungscheck:**
**Frage:** Welche Hauptschritte umfasst die Einbindung von Clients in ein Netzwerk?

**Antwort:**
1. **Anforderungen analysieren:** Client-Anforderungen und Netzwerkanforderungen ermitteln
2. **Planung:** Netzwerkstruktur verstehen, Komponenten auswählen
3. **Installation:** Hardware installieren, Software konfigurieren
4. **Konfiguration:** Netzwerkeinstellungen vornehmen, Authentifizierung einrichten
5. **Prüfung:** Verbindungstests durchführen, Namensauflösung prüfen
6. **Wartung:** Regelmäßige Updates, Monitoring, Fehlerbehebung

**Merksatz:**
"Client-Einbindung = Planen → Installieren → Konfigurieren → Prüfen → Warten - systematisch vorgehen!"

---

## 3.1: Eine Einführung in das Netzwerk des Ausbildungsbetriebs geben

**Kurz-Definition:**
Die Einführung in das Netzwerk des Ausbildungsbetriebs vermittelt einen Überblick über die vorhandene Netzwerkinfrastruktur, deren Komponenten, Struktur und Funktionsweise.

**Tabellarische Übersicht:**

| Netzwerkkomponente | Funktion | Beispiel im Betrieb |
|-------------------|----------|---------------------|
| **Clients** | Endgeräte der Benutzer | PCs, Laptops, Tablets |
| **Server** | Zentrale Dienste bereitstellen | Dateiserver, Druckserver, E-Mail-Server |
| **Switch** | Verbindung von Geräten im LAN | Netzwerkverteiler |
| **Router** | Verbindung verschiedener Netzwerke | Internet-Zugang, VLAN-Routing |
| **Firewall** | Sicherheit, Zugriffskontrolle | Schutz vor externen Angriffen |
| **Access Points** | WLAN-Zugang | Drahtlose Verbindungen |
| **Strukturierte Verkabelung** | Physische Verbindungen | Patchfelder, Kabel |

**Visuelle Darstellung:**
```
Unternehmensnetzwerk-Struktur:
    Internet
         ↓
    Firewall
         ↓
    Router
         ↓
    Switch (Zentral)
         ├── Server (Datei, Druck, E-Mail)
         ├── Access Point (WLAN)
         └── Switch (Etage)
              ├── Client 1
              ├── Client 2
              └── Client 3

Komponenten:
    Clients ←→ Switch ←→ Router ←→ Firewall ←→ Internet
         ↓
    Server (zentrale Dienste)
```

**Praxis-Beispiel:**
Ein mittelständisches Unternehmen mit 50 Mitarbeitern:
- **Clients:** 50 PCs/Laptops in verschiedenen Abteilungen
- **Server:** Dateiserver (Windows Server), Druckserver, E-Mail-Server (Exchange)
- **Netzwerk:** Zentraler 48-Port-Switch, mehrere 24-Port-Switches pro Etage
- **Router:** Business-Router für Internet-Zugang (100 Mbit/s)
- **Firewall:** Hardware-Firewall zum Schutz vor Angriffen
- **WLAN:** 3 Access Points für mobile Geräte
- **Verkabelung:** Strukturierte Verkabelung mit Cat 6 Kabeln, Patchfelder im Serverraum

**Prüfungscheck:**
**Frage:** Welche Hauptkomponenten sind typischerweise in einem Unternehmensnetzwerk vorhanden?

**Antwort:**
1. **Clients:** Endgeräte (PCs, Laptops)
2. **Server:** Zentrale Dienste (Dateien, Druck, E-Mail)
3. **Switch:** Verbindung von Geräten im lokalen Netzwerk
4. **Router:** Verbindung verschiedener Netzwerke, Internet-Zugang
5. **Firewall:** Sicherheit und Zugriffskontrolle
6. **Access Points:** WLAN-Zugang
7. **Verkabelung:** Strukturierte Verkabelung (Patchfelder, Kabel)

**Merksatz:**
"Netzwerk = Clients + Server + Switch + Router + Firewall + Verkabelung - alle zusammen ergeben das Netz!"

---

## 3.2: Hauptbestandteile von Computernetzen unterscheiden

### 3.2.1: Computernetzwerke und deren Hauptbestandteile im Überblick unterscheiden

**Kurz-Definition:**
Computernetzwerke verbinden mehrere Computer und Geräte zur gemeinsamen Nutzung von Ressourcen. Hauptbestandteile sind Clients, Server, Netzwerkkomponenten (Switch, Router) und Übertragungsmedien.

**Tabellarische Übersicht:**

| Bestandteil | Funktion | Beispiele |
|-------------|----------|-----------|
| **Clients** | Endgeräte, die Dienste nutzen | PC, Laptop, Smartphone |
| **Server** | Dienste bereitstellen | Dateiserver, Webserver, Druckserver |
| **Netzwerkkomponenten** | Verbindung und Datenverkehr steuern | Switch, Router, Hub, Bridge |
| **Übertragungsmedien** | Physische Verbindung | Kabel (Twisted Pair, Glasfaser), Funk (WLAN) |
| **Protokolle** | Regeln für Kommunikation | TCP/IP, Ethernet, HTTP |
| **Netzwerkbetriebssysteme** | Verwaltung des Netzwerks | Windows Server, Linux |

**Visuelle Darstellung:**
```
Computernetzwerk-Komponenten:
    Clients (PC, Laptop, Smartphone)
         ↓
    Übertragungsmedien (Kabel, Funk)
         ↓
    Netzwerkkomponenten (Switch, Router)
         ↓
    Server (Datei, Web, Mail)
         ↓
    Protokolle (TCP/IP, Ethernet, HTTP)
         ↓
    Netzwerkbetriebssystem (Windows Server, Linux)

Datenfluss:
    Client → Protokoll → Medium → Komponente → Server
```

**Praxis-Beispiel:**
Ein Büro mit 10 Arbeitsplätzen:
- **Clients:** 10 Desktop-PCs mit Windows 11
- **Server:** Ein Server mit Windows Server 2022 (Dateiserver, Druckserver)
- **Netzwerkkomponenten:** Ein 24-Port-Switch (Gigabit), Router für Internet
- **Übertragungsmedien:** Cat 6 Twisted Pair Kabel, WLAN für Laptops
- **Protokolle:** TCP/IP für Kommunikation, HTTP für Intranet, SMB für Dateifreigabe
- **Betriebssystem:** Windows Server verwaltet Benutzer, Freigaben, Drucker

**Prüfungscheck:**
**Frage:** Nennen Sie die fünf Hauptbestandteile eines Computernetzwerks.

**Antwort:**
1. **Clients:** Endgeräte, die Dienste nutzen
2. **Server:** Stellen Dienste bereit
3. **Netzwerkkomponenten:** Verbinden Geräte (Switch, Router)
4. **Übertragungsmedien:** Physische Verbindung (Kabel, Funk)
5. **Protokolle:** Regeln für Kommunikation (TCP/IP, Ethernet)

**Merksatz:**
"Netzwerk = Clients + Server + Komponenten + Medien + Protokolle - alle zusammen ermöglichen Kommunikation!"

---

### 3.2.2: Netzbereiche im Überblick unterscheiden

**Kurz-Definition:**
Netzbereiche sind logische oder physische Abgrenzungen von Netzwerken. Wichtige Bereiche sind LAN (lokal), WAN (weiträumig), MAN (städtisch), PAN (persönlich) und VLAN (virtuell).

**Tabellarische Übersicht:**

| Netzbereich | Abkürzung | Beschreibung | Reichweite | Beispiel |
|-------------|-----------|--------------|------------|----------|
| **PAN** | Personal Area Network | Persönliches Netzwerk | < 10 m | Bluetooth, USB |
| **LAN** | Local Area Network | Lokales Netzwerk | Gebäude, Campus | Firmennetzwerk |
| **MAN** | Metropolitan Area Network | Städtisches Netzwerk | Stadt | Stadtweites Netz |
| **WAN** | Wide Area Network | Weiträumiges Netzwerk | Länder, Kontinente | Internet |
| **VLAN** | Virtual LAN | Virtuelles LAN | Logische Trennung | Abteilungsnetze |
| **WLAN** | Wireless LAN | Drahtloses LAN | Wie LAN, aber Funk | WiFi-Netzwerk |

**Visuelle Darstellung:**
```
Netzbereiche nach Reichweite:
    PAN (< 10 m)
         ↓
    LAN (Gebäude/Campus)
         ↓
    MAN (Stadt)
         ↓
    WAN (Länder/Kontinente)

Beispiel-Struktur:
    PAN: Smartphone ↔ Bluetooth-Kopfhörer
    LAN: Firmennetzwerk (Gebäude)
    MAN: Stadtweites Netz (mehrere Standorte)
    WAN: Internet (weltweit)

VLAN: Logische Trennung auf physischem LAN
    Physisches LAN
         ├── VLAN 10 (Abteilung A)
         ├── VLAN 20 (Abteilung B)
         └── VLAN 30 (Gäste)
```

**Praxis-Beispiel:**
Ein Unternehmen mit mehreren Standorten:
- **PAN:** Mitarbeiter nutzt Bluetooth-Maus und -Tastatur am Laptop
- **LAN:** Hauptstandort hat lokales Netzwerk (192.168.1.0/24) mit 100 Geräten
- **VLAN:** Netzwerk ist in VLANs getrennt: VLAN 10 (Verwaltung), VLAN 20 (Produktion), VLAN 30 (Gäste-WLAN)
- **WAN:** Hauptstandort ist über VPN mit Filialen verbunden (weiträumiges Netzwerk)
- **Internet:** Alle Standorte haben Internet-Zugang über verschiedene Provider

**Prüfungscheck:**
**Frage:** Was ist der Unterschied zwischen LAN, WAN und VLAN?

**Antwort:**
- **LAN (Local Area Network):** Lokales Netzwerk in einem Gebäude oder Campus, physisch begrenzt
- **WAN (Wide Area Network):** Weiträumiges Netzwerk über große Entfernungen (Länder, Kontinente), oft über Internet
- **VLAN (Virtual LAN):** Virtuelles LAN - logische Trennung von Netzwerkbereichen auf einem physischen Netzwerk, ermöglicht Segmentierung ohne separate Hardware

**Merksatz:**
"LAN = lokal, WAN = weit, VLAN = virtuell - Reichweite und Art bestimmen den Netzbereich!"

---

### 3.2.3: Clients im Überblick unterscheiden

**Kurz-Definition:**
Clients sind Endgeräte, die auf Netzwerkressourcen zugreifen. Unterschieden werden Fat Clients (volle Funktionalität), Thin Clients (server-basiert) und Zero Clients (minimal).

**Tabellarische Übersicht:**

| Client-Typ | Beschreibung | Rechenleistung | Speicher | Einsatz | Beispiel |
|------------|--------------|----------------|----------|---------|----------|
| **Fat Client** | Vollständiger PC mit lokalem OS | Hoch | Groß | Individuelle Arbeitsplätze | Desktop-PC, Laptop |
| **Thin Client** | Schlanker Client, Server-basiert | Minimal | Sehr gering | Viele identische Arbeitsplätze | Terminal, VDI-Client |
| **Zero Client** | Noch schlanker, keine lokale Konfiguration | Sehr minimal | Minimal | Spezialisierte Umgebungen | PXE-Boot, Cloud-Client |
| **Mobile Client** | Smartphone, Tablet | Mobil optimiert | Variabel | Mobile Nutzung | Smartphone, Tablet |

**Visuelle Darstellung:**
```
Client-Typen nach Funktionalität:
    Fat Client
    ├── Lokales OS (Windows, Linux)
    ├── Lokale Anwendungen
    ├── Lokale Daten
    └── Hohe Rechenleistung

    Thin Client
    ├── Minimales OS
    ├── Server-basierte Anwendungen
    ├── Daten auf Server
    └── Geringe Rechenleistung

    Zero Client
    ├── Sehr minimales OS
    ├── PXE-Boot oder Cloud
    ├── Keine lokale Konfiguration
    └── Sehr geringe Rechenleistung

Einsatz:
    Fat Client → Individuelle Arbeitsplätze
    Thin Client → Call-Center, VDI
    Zero Client → Spezialisierte Umgebungen
```

**Praxis-Beispiel:**
Verschiedene Client-Typen im Einsatz:
- **Fat Client:** Entwickler-PC mit Windows 11, lokal installierte Entwicklungsumgebung (Visual Studio), lokale Datenbank, 16 GB RAM, starke CPU
- **Thin Client:** Call-Center mit 50 Terminals, die auf Remote Desktop Server zugreifen, alle Anwendungen laufen auf Server, Terminals haben nur 2 GB RAM
- **Zero Client:** Kiosk-System im Foyer, bootet über PXE, zeigt nur Webseite an, keine lokale Konfiguration nötig
- **Mobile Client:** Vertriebsmitarbeiter nutzt Tablet mit WLAN, greift auf Cloud-basierte CRM-Software zu

**Prüfungscheck:**
**Frage:** Wann ist ein Thin Client statt eines Fat Clients sinnvoll?

**Antwort:**
Ein Thin Client ist sinnvoll bei:
1. **Vielen identischen Arbeitsplätzen:** Call-Center, Verwaltung
2. **Zentraler Verwaltung:** Einheitliche Umgebung, einfache Updates
3. **Sicherheitsanforderungen:** Daten bleiben auf Server
4. **Kosteneinsparung:** Geringere Hardware-Kosten pro Arbeitsplatz
5. **VDI/RDS-Umgebung:** Virtual Desktop Infrastructure oder Remote Desktop Services

**Merksatz:**
"Fat Client = vollständig lokal, Thin Client = server-basiert, Zero Client = minimal - Einsatz bestimmt die Wahl!"

---

### 3.2.4: Servertypen und deren Dienste beschreiben

**Kurz-Definition:**
Server sind Computer, die Dienste für Clients bereitstellen. Unterschieden werden Server nach Funktion (Dateiserver, Webserver, etc.) und nach Architektur (physisch, virtuell, Cloud).

**Tabellarische Übersicht:**

| Servertyp | Funktion | Dienste | Beispiel |
|-----------|----------|---------|----------|
| **Dateiserver** | Dateien speichern und bereitstellen | File Sharing, NAS | Windows File Server, NAS-Gerät |
| **Druckserver** | Druckaufträge verwalten | Druckerfreigabe, Warteschlangen | Print Server |
| **Webserver** | Webseiten bereitstellen | HTTP, HTTPS | Apache, IIS, Nginx |
| **E-Mail-Server** | E-Mails senden/empfangen | SMTP, POP3, IMAP | Exchange, Postfix |
| **DNS-Server** | Namen in IP-Adressen auflösen | DNS-Auflösung | BIND, Windows DNS |
| **DHCP-Server** | IP-Adressen automatisch vergeben | IP-Konfiguration | Windows DHCP, ISC DHCP |
| **Domain Controller** | Authentifizierung, Verwaltung | Active Directory, LDAP | Windows Domain Controller |
| **Datenbankserver** | Datenbanken bereitstellen | SQL, Datenbankzugriff | MySQL, PostgreSQL, SQL Server |
| **Anwendungsserver** | Anwendungen bereitstellen | App-Services | Application Server |

**Visuelle Darstellung:**
```
Server-Client-Architektur:
    Clients (PC, Laptop)
         ↓
    Netzwerk
         ↓
    Server
         ├── Dateiserver (SMB, NFS)
         ├── Druckserver (Print Spooler)
         ├── Webserver (HTTP, HTTPS)
         ├── E-Mail-Server (SMTP, POP3, IMAP)
         ├── DNS-Server (Namensauflösung)
         ├── DHCP-Server (IP-Vergabe)
         ├── Domain Controller (AD, LDAP)
         ├── Datenbankserver (SQL)
         └── Anwendungsserver (Apps)

Dienste-Flow:
    Client-Anfrage → Server-Dienst → Antwort → Client
```

**Praxis-Beispiel:**
Ein Unternehmen nutzt verschiedene Server:
- **Dateiserver:** Windows File Server, Clients greifen über SMB auf Freigaben zu (\\server\abteilung)
- **Druckserver:** Print Server verwaltet 5 Drucker, Clients senden Druckaufträge an Server
- **Webserver:** Apache-Server hostet Intranet-Website, Clients greifen über Browser zu
- **E-Mail-Server:** Exchange Server, Clients nutzen Outlook (SMTP/POP3)
- **DNS-Server:** Windows DNS löst interne Namen (server.firma.local → 192.168.1.10)
- **DHCP-Server:** Vergibt automatisch IP-Adressen an Clients (192.168.1.100-200)
- **Domain Controller:** Active Directory verwaltet Benutzer, Gruppen, Richtlinien
- **Datenbankserver:** SQL Server für ERP-System, Anwendungen greifen über SQL zu

**Prüfungscheck:**
**Frage:** Welche Dienste stellt ein DHCP-Server bereit und warum ist er wichtig?

**Antwort:**
Ein DHCP-Server (Dynamic Host Configuration Protocol) stellt folgende Dienste bereit:
1. **Automatische IP-Adressvergabe:** Weist Clients automatisch IP-Adressen zu
2. **Subnetzmaske:** Informiert über Netzwerkstruktur
3. **Standard-Gateway:** Gibt Router-Adresse bekannt
4. **DNS-Server:** Informiert über DNS-Server-Adressen

**Wichtig:** Ohne DHCP müsste jeder Client manuell konfiguriert werden - sehr aufwendig und fehleranfällig.

**Merksatz:**
"Server = Dienst für Clients - Datei, Druck, Web, Mail, DNS, DHCP - jeder Server hat seine Aufgabe!"

---

### 3.2.5: Rechenzentren unterscheiden

**Kurz-Definition:**
Rechenzentren sind spezielle Räume oder Gebäude zur Unterbringung von IT-Infrastruktur. Unterschieden werden nach Größe (klein, mittel, groß), Standort (on-premise, Cloud, Colocation) und Verfügbarkeit (Tier-Level).

**Tabellarische Übersicht:**

| Kriterium | Typ | Beschreibung | Beispiel |
|-----------|-----|--------------|----------|
| **Größe** | Kleines RZ | Wenige Racks, lokales Unternehmen | Serverraum im Unternehmen |
| | Mittleres RZ | Mehrere Racks, mittlere Unternehmen | Regionales Rechenzentrum |
| | Großes RZ | Viele Racks, Cloud-Provider | Hyperscale-Datacenter |
| **Standort** | On-Premise | Im eigenen Gebäude | Firmenrechenzentrum |
| | Cloud | Extern, bei Provider | AWS, Azure, Google Cloud |
| | Colocation | Externe Räume, eigene Hardware | Shared Datacenter |
| **Tier-Level** | Tier I | Basis-Ausstattung, 99,67% Verfügbarkeit | Einfache Kühlung, keine Redundanz |
| | Tier II | Redundante Komponenten, 99,75% | Redundante Kühlung |
| | Tier III | N+1 Redundanz, 99,98% | Wartung ohne Ausfall möglich |
| | Tier IV | Vollständige Redundanz, 99,995% | Fehlertolerant, höchste Verfügbarkeit |

**Prüfungscheck:**
**Frage:** Was bedeutet Tier-Level in Rechenzentren und welche Unterschiede gibt es?

**Antwort:**
Tier-Level klassifizieren Rechenzentren nach Verfügbarkeit und Redundanz:
- **Tier I:** Basis-Ausstattung, 99,67% Verfügbarkeit, keine Redundanz
- **Tier II:** Redundante Komponenten, 99,75% Verfügbarkeit
- **Tier III:** N+1 Redundanz, 99,98% Verfügbarkeit, Wartung ohne Ausfall möglich
- **Tier IV:** Vollständige Redundanz, 99,995% Verfügbarkeit, fehlertolerant

**Höheres Tier = höhere Verfügbarkeit und mehr Redundanz = höhere Kosten**

**Merksatz:**
"Rechenzentrum = Server + Kühlung + Strom + Sicherheit - Tier-Level bestimmt Verfügbarkeit!"

---

## 3.3: Grundlagen der Datenübertragung in Netzwerken

### 3.3.1: Funktionsweise von Rechnernetzen verstehen

**Kurz-Definition:**
Rechnernetze funktionieren durch die Übertragung von Datenpaketen zwischen Geräten über gemeinsame Übertragungsmedien. Protokolle regeln die Kommunikation, Adressierung ermöglicht die richtige Zustellung.

**Tabellarische Übersicht:**

| Aspekt | Beschreibung | Beispiel |
|--------|--------------|----------|
| **Datenpakete** | Daten werden in Pakete aufgeteilt | IP-Paket mit Header und Daten |
| **Adressierung** | Jedes Gerät hat eine eindeutige Adresse | IP-Adresse (192.168.1.1), MAC-Adresse |
| **Routing** | Pakete werden zum Ziel geleitet | Router entscheidet über Weg |
| **Protokolle** | Regeln für Kommunikation | TCP/IP, Ethernet |
| **Schichtenmodell** | Verschiedene Ebenen der Kommunikation | OSI-Modell (7 Schichten) |
| **Fehlererkennung** | Prüfung auf Übertragungsfehler | Checksummen, CRC |

**Visuelle Darstellung:**
```
Datenübertragung im Netzwerk:
    Sender
         ↓
    Daten → Pakete aufteilen
         ↓
    Adressierung (IP, MAC)
         ↓
    Übertragung über Medium
         ↓
    Routing (Router/Switch)
         ↓
    Empfänger
         ↓
    Pakete → Daten zusammenfügen
         ↓
    Fehlerprüfung (Checksumme)

Paket-Struktur:
    [Header] [Daten] [Checksumme]
    Header: Quell-IP, Ziel-IP, Protokoll
    Daten: Nutzdaten
    Checksumme: Fehlererkennung
```

**Praxis-Beispiel:**
Ein Client sendet eine E-Mail:
1. **Datenaufbereitung:** E-Mail wird in Pakete aufgeteilt (z.B. 1500 Bytes pro Paket)
2. **Adressierung:** Jedes Paket erhält Header mit Quell-IP (192.168.1.100), Ziel-IP (Mail-Server), MAC-Adressen
3. **Verschicken:** Pakete werden über Ethernet-Kabel gesendet
4. **Routing:** Switch leitet Pakete basierend auf MAC-Adresse weiter, Router leitet basierend auf IP-Adresse zum Mail-Server
5. **Zustellung:** Mail-Server empfängt Pakete
6. **Zusammenfügen:** Pakete werden wieder zur E-Mail zusammengesetzt
7. **Fehlerprüfung:** Checksummen werden geprüft, bei Fehlern wird erneut gesendet

**Prüfungscheck:**
**Frage:** Wie funktioniert die Datenübertragung in einem Netzwerk grundlegend?

**Antwort:**
1. **Datenaufbereitung:** Daten werden in Pakete aufgeteilt
2. **Adressierung:** Jedes Paket erhält Quell- und Zieladresse (IP, MAC)
3. **Verschicken:** Paket wird über Übertragungsmedium gesendet
4. **Routing:** Router/Switch leiten Paket zum Ziel
5. **Zustellung:** Paket erreicht Zielgerät
6. **Zusammenfügen:** Pakete werden wieder zu Daten zusammengesetzt
7. **Fehlerprüfung:** Checksummen prüfen auf Fehler

**Merksatz:**
"Netzwerk = Pakete + Adressen + Routing + Protokolle - Daten werden in Paketen adressiert übertragen!"

---

### 3.3.2: Den Zugriff auf die Netzwerkmedien verstehen

**Kurz-Definition:**
Der Zugriff auf Netzwerkmedien regelt, wie mehrere Geräte auf ein gemeinsames Übertragungsmedium zugreifen. Wichtige Methoden sind CSMA/CD (Ethernet), CSMA/CA (WLAN) und Token-Passing.

**Tabellarische Übersicht:**

| Zugriffsmethode | Beschreibung | Vorteil | Nachteil | Einsatz |
|-----------------|--------------|---------|----------|---------|
| **CSMA/CD** | Carrier Sense Multiple Access / Collision Detection | Einfach, kostengünstig | Kollisionen möglich | Ethernet (Kabel) |
| **CSMA/CA** | Carrier Sense Multiple Access / Collision Avoidance | Kollisionen vermeiden | Overhead, langsamer | WLAN (Funk) |
| **Token-Passing** | Token wird weitergegeben, nur Token-Inhaber sendet | Keine Kollisionen | Komplex, langsamer | Token Ring (veraltet) |
| **Polling** | Master fragt Slaves ab | Kontrolliert | Master-Abhängigkeit | Spezialnetze |
| **Switching** | Switch leitet direkt weiter | Keine Kollisionen, schnell | Hardware-Kosten | Moderne LANs |

**Visuelle Darstellung:**
```
Zugriffsmethoden auf Netzwerkmedien:

CSMA/CD (Ethernet - Kabel):
    Gerät 1: Hört → Medium frei? → Sendet
    Gerät 2: Hört → Medium frei? → Sendet
    → Kollision erkannt → Beide warten → Erneut senden

CSMA/CA (WLAN - Funk):
    Gerät 1: Hört → RTS (Request to Send)
    Access Point: → CTS (Clear to Send)
    Gerät 1: → Sendet
    → Kollision vermieden

Switching (Moderne LANs):
    Switch hat MAC-Tabelle
    Gerät 1 → Switch → Gerät 2 (direkt)
    → Keine Kollisionen, Vollduplex möglich
```

**Praxis-Beispiel:**
Verschiedene Zugriffsmethoden im Einsatz:
- **CSMA/CD (veraltet):** Altes Ethernet-Netzwerk mit Hub, mehrere Geräte senden gleichzeitig, Kollisionen treten auf, Geräte erkennen Kollision und senden erneut
- **CSMA/CA (WLAN):** Laptop verbindet sich mit WLAN, sendet RTS, Access Point antwortet mit CTS, dann wird gesendet - Kollisionen werden vermieden
- **Switching (heute Standard):** Moderne Netzwerke mit Switch, Switch kennt MAC-Adressen aller Geräte, leitet Pakete direkt zum Zielport weiter, keine Kollisionen, Vollduplex-Kommunikation möglich

**Prüfungscheck:**
**Frage:** Was ist der Unterschied zwischen CSMA/CD und CSMA/CA?

**Antwort:**
- **CSMA/CD (Carrier Sense Multiple Access / Collision Detection):**
  - Wird bei kabelgebundenen Netzwerken (Ethernet) verwendet
  - Gerät hört zuerst, ob Medium frei ist (Carrier Sense)
  - Wenn frei, sendet es
  - Bei Kollision wird erkannt (Collision Detection) und erneut gesendet
  - Funktioniert gut bei Kabeln, da Kollisionen schnell erkannt werden

- **CSMA/CA (Carrier Sense Multiple Access / Collision Avoidance):**
  - Wird bei drahtlosen Netzwerken (WLAN) verwendet
  - Gerät hört zuerst, ob Medium frei ist
  - Sendet dann eine "Request to Send" (RTS) Nachricht
  - Empfänger bestätigt mit "Clear to Send" (CTS)
  - Vermeidet Kollisionen, da bei Funk Kollisionen nicht zuverlässig erkannt werden können

**Merksatz:**
"CSMA/CD = Kollision erkennen (Kabel), CSMA/CA = Kollision vermeiden (Funk) - Medium bestimmt Methode!"

---

### 3.3.3: Ethernet als Netzwerkstandard verwenden

**Kurz-Definition:**
Ethernet ist der dominierende Standard für lokale Netzwerke (LAN). Es definiert Übertragungsgeschwindigkeiten, Kabeltypen, Topologien und Zugriffsverfahren (CSMA/CD).

**Tabellarische Übersicht:**

| Ethernet-Standard | Geschwindigkeit | Kabeltyp | Maximale Länge | Jahr |
|-------------------|-----------------|----------|---------------|------|
| **10BASE-T** | 10 Mbps | Twisted Pair (Cat 3) | 100 m | 1990 |
| **100BASE-TX** | 100 Mbps (Fast Ethernet) | Twisted Pair (Cat 5) | 100 m | 1995 |
| **1000BASE-T** | 1 Gbps (Gigabit Ethernet) | Twisted Pair (Cat 5e/6) | 100 m | 1999 |
| **10GBASE-T** | 10 Gbps | Twisted Pair (Cat 6a/7) | 100 m | 2006 |
| **1000BASE-SX** | 1 Gbps | Multimode Glasfaser | 550 m | 1998 |
| **10GBASE-SR** | 10 Gbps | Multimode Glasfaser | 300 m | 2002 |

**Visuelle Darstellung:**
```
Ethernet-Evolution:
    10BASE-T (10 Mbps, 1990) → Veraltet
         ↓
    100BASE-TX (100 Mbps, 1995) → Fast Ethernet
         ↓
    1000BASE-T (1 Gbps, 1999) → Gigabit Ethernet (Standard heute)
         ↓
    10GBASE-T (10 Gbps, 2006) → 10 Gigabit (Server/Backbone)

Kabeltypen:
    Twisted Pair: Cat 5e/6 → Standard LAN (bis 100 m)
    Glasfaser: Multimode/Singlemode → Lange Distanzen (bis km)

Ethernet-Frame:
    [Preamble] [Ziel-MAC] [Quell-MAC] [Typ] [Daten] [CRC]
```

**Praxis-Beispiel:**
Ethernet-Standards im Unternehmen:
- **100BASE-TX:** Alte PCs mit Fast Ethernet (100 Mbps), Cat 5 Kabel, noch in Verwendung
- **1000BASE-T:** Neue PCs und Server mit Gigabit Ethernet (1 Gbps), Cat 6 Kabel, Standard heute
- **10GBASE-T:** Server-Backbone mit 10 Gigabit (10 Gbps), Cat 6a Kabel, für Server-zu-Server-Verbindungen
- **1000BASE-SX:** Glasfaser-Verbindung zwischen Gebäuden (1 Gbps), 500 m Distanz, störungsresistent

**Prüfungscheck:**
**Frage:** Welche Ethernet-Standards gibt es und welche Geschwindigkeiten erreichen sie?

**Antwort:**
Wichtige Ethernet-Standards:
1. **10BASE-T:** 10 Mbps, Twisted Pair (Cat 3), veraltet
2. **100BASE-TX (Fast Ethernet):** 100 Mbps, Twisted Pair (Cat 5), noch verbreitet
3. **1000BASE-T (Gigabit Ethernet):** 1 Gbps, Twisted Pair (Cat 5e/6), Standard heute
4. **10GBASE-T:** 10 Gbps, Twisted Pair (Cat 6a/7), für Server/Backbone
5. **Glasfaser-Varianten:** 1000BASE-SX (1 Gbps), 10GBASE-SR (10 Gbps) für längere Distanzen

**Merksatz:**
"Ethernet = Standard für LAN - 10/100/1000/10000 Mbps - Twisted Pair oder Glasfaser!"

---

### 3.3.4: TCP/IP als Netzwerkstandard verwenden

**Kurz-Definition:**
TCP/IP (Transmission Control Protocol / Internet Protocol) ist das Standard-Protokoll für Netzwerke und das Internet. Es besteht aus mehreren Schichten und ermöglicht die Kommunikation zwischen verschiedenen Systemen.

**Tabellarische Übersicht:**

| TCP/IP-Schicht | Funktion | Protokolle | Beispiel |
|----------------|----------|------------|----------|
| **Anwendungsschicht** | Anwendungsdienste | HTTP, HTTPS, FTP, SMTP, DNS, DHCP | Webbrowser, E-Mail |
| **Transportschicht** | Ende-zu-Ende-Kommunikation | TCP, UDP | TCP (zuverlässig), UDP (schnell) |
| **Internetschicht** | Routing, Adressierung | IP, ICMP, ARP | IP-Adressen, Routing |
| **Netzzugangsschicht** | Physische Übertragung | Ethernet, WLAN | Kabel, Funk |

| Protokoll | Beschreibung | Einsatz |
|-----------|--------------|---------|
| **TCP** | Zuverlässige, verbindungsorientierte Übertragung | Web, E-Mail, Dateitransfer |
| **UDP** | Schnelle, verbindungslose Übertragung | Video-Streaming, DNS, VoIP |
| **IP** | Adressierung und Routing | Basis für alle Netzwerkkommunikation |
| **HTTP/HTTPS** | Web-Kommunikation | Webbrowser |
| **FTP** | Dateitransfer | Dateiübertragung |
| **SMTP** | E-Mail-Versand | E-Mail-Server |
| **DNS** | Namensauflösung | Domain-Namen → IP-Adressen |
| **DHCP** | Automatische IP-Konfiguration | IP-Adressvergabe |

**Visuelle Darstellung:**
```
TCP/IP-Schichtenmodell:
    Anwendungsschicht
    ├── HTTP, HTTPS (Web)
    ├── FTP (Dateitransfer)
    ├── SMTP (E-Mail)
    ├── DNS (Namensauflösung)
    └── DHCP (IP-Konfiguration)
         ↓
    Transportschicht
    ├── TCP (zuverlässig, verbindungsorientiert)
    └── UDP (schnell, verbindungslos)
         ↓
    Internetschicht
    ├── IP (Adressierung, Routing)
    ├── ICMP (Fehlermeldungen)
    └── ARP (MAC-Auflösung)
         ↓
    Netzzugangsschicht
    ├── Ethernet (Kabel)
    └── WLAN (Funk)

Datenfluss:
    Anwendung → TCP/UDP → IP → Ethernet → Medium
```

**Praxis-Beispiel:**
TCP/IP-Kommunikation beim Web-Browsing:
- **Anwendungsschicht:** Browser sendet HTTP-Anfrage (GET /index.html)
- **Transportschicht:** TCP baut Verbindung auf, garantiert Zustellung
- **Internetschicht:** IP adressiert Paket (Quell: 192.168.1.100, Ziel: Webserver-IP)
- **Netzzugangsschicht:** Ethernet verpackt in Frame mit MAC-Adressen
- **Übertragung:** Paket wird über Kabel gesendet
- **Empfänger:** Webserver empfängt, verarbeitet Anfrage, sendet Antwort zurück
- **Zustellung:** Browser empfängt HTML-Seite, stellt sie dar

**Prüfungscheck:**
**Frage:** Was ist der Unterschied zwischen TCP und UDP?

**Antwort:**
- **TCP (Transmission Control Protocol):**
  - Verbindungsorientiert: Verbindung wird aufgebaut
  - Zuverlässig: Garantiert Zustellung, Fehlerkorrektur
  - Reihenfolge: Pakete kommen in richtiger Reihenfolge an
  - Langsamer: Overhead durch Kontrollmechanismen
  - Einsatz: Web (HTTP), E-Mail (SMTP), Dateitransfer (FTP)

- **UDP (User Datagram Protocol):**
  - Verbindungslos: Keine Verbindung nötig
  - Schnell: Wenig Overhead
  - Unzuverlässig: Keine Garantie auf Zustellung
  - Keine Reihenfolge: Pakete können durcheinander ankommen
  - Einsatz: Video-Streaming, DNS, VoIP, Gaming

**Merksatz:**
"TCP = zuverlässig aber langsam, UDP = schnell aber unzuverlässig - Anwendung bestimmt Protokoll!"

---

## 3.4: Netzwerkstrukturen, -komponenten, -standards und -modelle unterscheiden

### 3.4.1: Netzwerktopologien unterscheiden

**Kurz-Definition:**
Netzwerktopologien beschreiben die physische oder logische Anordnung von Geräten in einem Netzwerk. Wichtige Topologien sind Bus, Stern, Ring, Mesh und Baum.

**Tabellarische Übersicht:**

| Topologie | Beschreibung | Vorteile | Nachteile | Einsatz |
|-----------|--------------|----------|-----------|---------|
| **Bus** | Alle Geräte an einem Kabel | Einfach, günstig | Ausfall des Kabels = Ausfall aller | Veraltet |
| **Stern** | Alle Geräte an zentralem Switch | Ausfall eines Geräts betrifft nur dieses | Switch-Ausfall = Ausfall aller | Standard heute |
| **Ring** | Geräte in Ring verbunden | Gleichmäßige Last | Ausfall eines Geräts = Ausfall aller | Token Ring (veraltet) |
| **Mesh** | Jedes Gerät mit jedem verbunden | Sehr ausfallsicher | Sehr teuer, komplex | Kritische Systeme |
| **Baum** | Hierarchische Struktur | Skalierbar, strukturiert | Abhängigkeit von Wurzel | Große Netzwerke |
| **Hybrid** | Kombination mehrerer Topologien | Flexibel | Komplex | Reale Netzwerke |

**Visuelle Darstellung:**
```
Netzwerktopologien:

Bus-Topologie (veraltet):
    [Client1]---[Client2]---[Client3]---[Client4]
    Alle an einem Kabel

Stern-Topologie (Standard):
           [Switch]
         /    |    \
    [Client1][Client2][Client3]
    Alle an zentralem Switch

Ring-Topologie (veraltet):
    [Client1]→[Client2]→[Client3]→[Client4]→[Client1]
    Ringförmige Verbindung

Mesh-Topologie:
    [Client1]↔[Client2]↔[Client3]
         ↕         ↕
    [Client4]↔[Client5]
    Jedes mit jedem verbunden

Baum-Topologie:
         [Root-Switch]
        /            \
    [Switch1]      [Switch2]
    /      \        /      \
[Client1][Client2][Client3][Client4]
Hierarchische Struktur
```

**Praxis-Beispiel:**
Verschiedene Topologien im Einsatz:
- **Stern (Standard):** Bürogebäude mit zentralem Switch, alle PCs verbunden über Cat 6 Kabel, Ausfall eines PCs betrifft nur diesen
- **Baum:** Großes Unternehmen mit Hauptstandort (Root), Filialen (Switches), Arbeitsplätze (Clients), hierarchische Struktur
- **Hybrid:** Kombination aus Stern (lokal) und Baum (zwischen Standorten), reales Netzwerk mit verschiedenen Bereichen
- **Mesh (teilweise):** Kritische Server mit redundanten Verbindungen, mehrere Wege für Ausfallsicherheit

**Prüfungscheck:**
**Frage:** Welche Topologie ist heute Standard und warum?

**Antwort:**
Die **Sterntopologie** ist heute Standard, weil:
1. **Ausfallsicherheit:** Ausfall eines Geräts betrifft nur dieses Gerät
2. **Einfache Verwaltung:** Zentrale Verwaltung über Switch
3. **Skalierbarkeit:** Einfach erweiterbar durch zusätzliche Ports
4. **Kosteneffizient:** Switch-Kosten sind akzeptabel
5. **Performance:** Vollduplex-Kommunikation möglich, keine Kollisionen

**Nachteil:** Ausfall des zentralen Switches führt zum Ausfall des gesamten Netzwerks (kann durch Redundanz gelöst werden).

**Merksatz:**
"Stern = Standard heute - alle an Switch, ausfallsicher und skalierbar!"

---

### 3.4.2: Strukturierte Verkabelung herstellen

**Kurz-Definition:**
Strukturierte Verkabelung ist eine standardisierte, hierarchische Verkabelungsstruktur für Netzwerke. Sie besteht aus Primärbereich (Gebäude), Sekundärbereich (Etage) und Tertiärbereich (Arbeitsplatz).

**Tabellarische Übersicht:**

| Verkabelungsbereich | Beschreibung | Komponenten | Standard |
|---------------------|--------------|-------------|----------|
| **Primärbereich** | Verbindung zwischen Gebäuden | Glasfaser, größere Distanzen | EN 50173 |
| **Sekundärbereich** | Verbindung zwischen Etagen | Twisted Pair, Glasfaser | EN 50173 |
| **Tertiärbereich** | Verbindung zum Arbeitsplatz | Twisted Pair (Cat 5e/6) | EN 50173 |
| **Patchfeld** | Zentrale Verbindungsstelle | Patchpanel, Switches | Strukturierte Verkabelung |
| **Dose** | Anschluss am Arbeitsplatz | Netzwerkdose (RJ45) | Arbeitsplatz-Anschluss |

| Kabelkategorie | Geschwindigkeit | Frequenz | Einsatz |
|----------------|-----------------|----------|---------|
| **Cat 5** | 100 Mbps | 100 MHz | Veraltet |
| **Cat 5e** | 1 Gbps | 100 MHz | Noch verbreitet |
| **Cat 6** | 1 Gbps (10 Gbps bis 55 m) | 250 MHz | Standard heute |
| **Cat 6a** | 10 Gbps | 500 MHz | Zukunftssicher |
| **Cat 7** | 10 Gbps | 600 MHz | Spezialanwendungen |

**Visuelle Darstellung:**
```
Strukturierte Verkabelung - Hierarchie:

Primärbereich (Campus):
    Gebäude A ←→ [Glasfaser] ←→ Gebäude B
    Verbindung zwischen Gebäuden

Sekundärbereich (Gebäude):
    Etage 1
         ↓
    [Switch] ←→ [Glasfaser/Twisted Pair] ←→ [Switch]
         ↓                                    ↓
    Etage 2                              Etage 3
    Verbindung zwischen Etagen

Tertiärbereich (Etage):
    [Patchfeld] → [Kabel] → [Dose] → [Client]
    Verbindung zum Arbeitsplatz

Verkabelungsstruktur:
    Primär (Gebäude) → Sekundär (Etage) → Tertiär (Arbeitsplatz)
```

**Praxis-Beispiel:**
Strukturierte Verkabelung in einem 3-stöckigen Bürogebäude:
- **Primärbereich:** Glasfaser-Verbindung zwischen Hauptgebäude und Nebengebäude (500 m Distanz)
- **Sekundärbereich:** Cat 6 Kabel zwischen Etagen, zentraler Switch pro Etage im Technikraum
- **Tertiärbereich:** Cat 6 Kabel von Patchfeld zu jedem Arbeitsplatz, Netzwerkdose (RJ45) an der Wand
- **Patchfeld:** Zentrale Patchpanels im Technikraum, einfache Verwaltung durch Patchkabel
- **Vorteil:** Standardisiert, wartbar, erweiterbar - neue Arbeitsplätze einfach hinzufügbar

**Prüfungscheck:**
**Frage:** Was bedeutet strukturierte Verkabelung und welche Bereiche gibt es?

**Antwort:**
Strukturierte Verkabelung ist eine standardisierte, hierarchische Verkabelungsstruktur:

1. **Primärbereich (Campus):** Verbindung zwischen Gebäuden, meist Glasfaser
2. **Sekundärbereich (Gebäude):** Verbindung zwischen Etagen, Twisted Pair oder Glasfaser
3. **Tertiärbereich (Etage):** Verbindung zum Arbeitsplatz, Twisted Pair (Cat 5e/6)

**Vorteile:**
- Standardisiert, wartbar, erweiterbar
- Unabhängig von Anwendungen
- Zentrale Verwaltung über Patchfelder

**Merksatz:**
"Strukturierte Verkabelung = Primär (Gebäude) + Sekundär (Etage) + Tertiär (Arbeitsplatz) - hierarchisch und standardisiert!"

---

### 3.4.3: Netzwerkmedien unterscheiden und spezifizieren

**Kurz-Definition:**
Netzwerkmedien sind die physischen Übertragungsmedien für Daten. Unterschieden werden kabelgebundene Medien (Twisted Pair, Glasfaser, Koaxial) und drahtlose Medien (Funk).

**Tabellarische Übersicht:**

| Medium | Beschreibung | Geschwindigkeit | Distanz | Vorteile | Nachteile |
|--------|--------------|-----------------|---------|----------|-----------|
| **Twisted Pair** | Verdrillte Kupferkabel | 10 Mbps - 10 Gbps | 100 m | Günstig, einfach | Störanfällig, begrenzte Distanz |
| **Glasfaser** | Lichtwellenleiter | 1 Gbps - 100 Gbps+ | km | Sehr schnell, störungsresistent | Teuer, aufwendig |
| **Koaxialkabel** | Koaxialkabel | 10 Mbps - 1 Gbps | 500 m | Robust | Veraltet, schwer |
| **WLAN** | Drahtlos (Funk) | 11 Mbps - 9,6 Gbps | 50-100 m | Flexibel, mobil | Störanfällig, Sicherheit |
| **Powerline** | Über Stromleitung | 200 Mbps - 2 Gbps | Haus | Nutzt vorhandene Leitungen | Störanfällig |

| Twisted Pair Typ | Geschwindigkeit | Einsatz |
|------------------|-----------------|---------|
| **Cat 5e** | 1 Gbps | Standard LAN |
| **Cat 6** | 1 Gbps (10 Gbps bis 55 m) | Standard heute |
| **Cat 6a** | 10 Gbps | Zukunftssicher |
| **Cat 7** | 10 Gbps | Spezialanwendungen |

| Glasfasertyp | Beschreibung | Distanz |
|--------------|--------------|---------|
| **Multimode** | Mehrere Lichtmoden | Bis 550 m |
| **Singlemode** | Ein Lichtmodus | Bis 40 km+ |

**Visuelle Darstellung:**
```
Netzwerkmedien-Vergleich:

Twisted Pair (Kupfer):
    [Client] ←→ [Cat 6 Kabel] ←→ [Switch]
    Bis 100 m, 1-10 Gbps, günstig

Glasfaser:
    [Server] ←→ [Lichtwellenleiter] ←→ [Switch]
    Bis km, 1-100+ Gbps, teuer, störungsresistent

WLAN (Funk):
    [Laptop] ←→ [Funk] ←→ [Access Point]
    Bis 100 m, 11 Mbps - 9,6 Gbps, flexibel

Medien-Auswahl:
    Kurze Distanz (< 100 m) → Twisted Pair
    Lange Distanz (> 100 m) → Glasfaser
    Mobil → WLAN
```

**Praxis-Beispiel:**
Verschiedene Medien im Einsatz:
- **Twisted Pair (Cat 6):** Standard-Verbindung von PCs zu Switch im Büro (max. 100 m), 1 Gbps, kostengünstig
- **Glasfaser (Multimode):** Verbindung zwischen Server-Racks im Rechenzentrum (200 m), 10 Gbps, störungsresistent
- **Glasfaser (Singlemode):** Verbindung zwischen zwei Gebäuden (2 km), 10 Gbps, sehr lange Distanz möglich
- **WLAN (802.11ac):** Mobile Geräte im Büro, flexibler Zugang, 1,3 Gbps, Reichweite ca. 50 m
- **Powerline:** Alternative in Altbau ohne Netzwerkverkabelung, nutzt Stromleitung, 200-500 Mbps

**Prüfungscheck:**
**Frage:** Wann sollte Glasfaser statt Twisted Pair verwendet werden?

**Antwort:**
Glasfaser sollte verwendet werden bei:
1. **Langen Distanzen:** Über 100 m (Twisted Pair Limit)
2. **Hohen Geschwindigkeiten:** 10 Gbps und mehr
3. **Störungen:** Elektromagnetische Störungen (EMV)
4. **Sicherheit:** Keine Abhörung möglich (keine elektromagnetische Abstrahlung)
5. **Backbone:** Verbindung zwischen Gebäuden, Etagen
6. **Zukunftssicherheit:** Höhere Bandbreiten möglich

**Nachteile:** Teurer, aufwendigere Installation, spezielle Geräte nötig

**Merksatz:**
"Twisted Pair = Standard LAN, Glasfaser = lang und schnell, WLAN = mobil - Medium nach Anforderung wählen!"

---

### 3.4.4: Schichtenmodelle der Kommunikation unterscheiden

**Kurz-Definition:**
Schichtenmodelle strukturieren die Netzwerkkommunikation in Ebenen. Wichtig sind das OSI-Modell (7 Schichten) und das TCP/IP-Modell (4 Schichten). Jede Schicht hat spezifische Aufgaben.

**Tabellarische Übersicht:**

| OSI-Schicht | Name | Aufgabe | Beispiel |
|-------------|------|---------|-----------|
| **7. Anwendung** | Application | Anwendungsdienste | HTTP, FTP, SMTP |
| **6. Darstellung** | Presentation | Datenformatierung | Verschlüsselung, Kompression |
| **5. Sitzung** | Session | Sitzungsverwaltung | Login, Logout |
| **4. Transport** | Transport | Ende-zu-Ende-Kommunikation | TCP, UDP |
| **3. Vermittlung** | Network | Routing, Adressierung | IP, Router |
| **2. Sicherung** | Data Link | Fehlererkennung, MAC | Ethernet, Switch |
| **1. Bitübertragung** | Physical | Physische Übertragung | Kabel, Funk |

| TCP/IP-Schicht | Entspricht OSI | Protokolle |
|----------------|----------------|------------|
| **Anwendung** | Schicht 5-7 | HTTP, FTP, SMTP, DNS |
| **Transport** | Schicht 4 | TCP, UDP |
| **Internet** | Schicht 3 | IP, ICMP |
| **Netzzugang** | Schicht 1-2 | Ethernet, WLAN |

**Visuelle Darstellung:**
```
OSI-Modell (7 Schichten):
    7. Anwendung      → HTTP, FTP, SMTP
    6. Darstellung    → Verschlüsselung, Kompression
    5. Sitzung        → Login, Logout
    4. Transport      → TCP, UDP
    3. Vermittlung    → IP, Routing
    2. Sicherung      → Ethernet, MAC
    1. Bitübertragung → Kabel, Funk

TCP/IP-Modell (4 Schichten):
    Anwendung    → HTTP, FTP, SMTP, DNS (OSI 5-7)
    Transport    → TCP, UDP (OSI 4)
    Internet     → IP, ICMP (OSI 3)
    Netzzugang   → Ethernet, WLAN (OSI 1-2)

Datenfluss:
    Anwendung → Transport → Internet → Netzzugang → Medium
```

**Praxis-Beispiel:**
Schichtenmodell beim Web-Browsing:
- **Schicht 7 (Anwendung):** Browser sendet HTTP-Anfrage "GET /index.html"
- **Schicht 6 (Darstellung):** Daten werden komprimiert (gzip), verschlüsselt (HTTPS)
- **Schicht 5 (Sitzung):** Session wird verwaltet, Login-Status
- **Schicht 4 (Transport):** TCP baut Verbindung auf, garantiert Zustellung
- **Schicht 3 (Vermittlung):** IP adressiert Paket (Quell: 192.168.1.100, Ziel: Webserver)
- **Schicht 2 (Sicherung):** Ethernet verpackt in Frame mit MAC-Adressen
- **Schicht 1 (Bitübertragung):** Elektrische Signale über Kabel übertragen

**Prüfungscheck:**
**Frage:** Nennen Sie die 7 Schichten des OSI-Modells in der richtigen Reihenfolge.

**Antwort:**
1. **Bitübertragungsschicht (Physical):** Physische Übertragung (Kabel, Funk)
2. **Sicherungsschicht (Data Link):** Fehlererkennung, MAC-Adressierung (Ethernet, Switch)
3. **Vermittlungsschicht (Network):** Routing, IP-Adressierung (IP, Router)
4. **Transportschicht (Transport):** Ende-zu-Ende-Kommunikation (TCP, UDP)
5. **Sitzungsschicht (Session):** Sitzungsverwaltung (Login, Logout)
6. **Darstellungsschicht (Presentation):** Datenformatierung (Verschlüsselung)
7. **Anwendungsschicht (Application):** Anwendungsdienste (HTTP, FTP, SMTP)

**Merksatz:** "OSI = 7 Schichten, TCP/IP = 4 Schichten - Schichten strukturieren Kommunikation!"

---

### 3.4.5: Adressen im Netzwerk unterscheiden

**Kurz-Definition:**
Im Netzwerk werden verschiedene Adresstypen verwendet: MAC-Adressen (physisch, Schicht 2), IP-Adressen (logisch, Schicht 3) und Portnummern (Anwendungen, Schicht 4).

**Tabellarische Übersicht:**

| Adresstyp | Schicht | Format | Beispiel | Zweck |
|-----------|---------|--------|----------|-------|
| **MAC-Adresse** | 2 (Data Link) | 6 Bytes (hex) | 00:1A:2B:3C:4D:5E | Physische Geräte-Identifikation |
| **IP-Adresse (IPv4)** | 3 (Network) | 4 Bytes (dezimal) | 192.168.1.1 | Logische Netzwerk-Adressierung |
| **IP-Adresse (IPv6)** | 3 (Network) | 16 Bytes (hex) | 2001:0db8::1 | Erweiterte Adressierung |
| **Portnummer** | 4 (Transport) | 16 Bit (0-65535) | 80 (HTTP), 443 (HTTPS) | Anwendungs-Identifikation |
| **Subnetzmaske** | 3 (Network) | 4 Bytes | 255.255.255.0 | Netzwerk-Bereich |

| IP-Adresstyp | Bereich | Beschreibung |
|--------------|---------|--------------|
| **Privat (IPv4)** | 10.0.0.0/8, 172.16.0.0/12, 192.168.0.0/16 | Lokale Netzwerke |
| **Öffentlich (IPv4)** | Rest | Internet |
| **Link-Local** | 169.254.0.0/16 | Automatische Konfiguration |
| **Loopback** | 127.0.0.0/8 | Lokaler Rechner |

| Portnummern | Protokoll | Beschreibung |
|-------------|-----------|--------------|
| **20, 21** | FTP | Dateitransfer |
| **22** | SSH | Sichere Shell |
| **23** | Telnet | Terminal-Zugriff |
| **25** | SMTP | E-Mail-Versand |
| **53** | DNS | Namensauflösung |
| **80** | HTTP | Web |
| **443** | HTTPS | Web (verschlüsselt) |
| **3389** | RDP | Remote Desktop |

**Visuelle Darstellung:**
```
Adressen im Netzwerk:

MAC-Adresse (Schicht 2):
    Format: 00:1A:2B:3C:4D:5E
    Physisch, fest im Gerät
    Lokal im Netzwerk
    Wird von Switches verwendet

IP-Adresse (Schicht 3):
    IPv4: 192.168.1.100
    IPv6: 2001:0db8::1
    Logisch, konfigurierbar
    Routingfähig
    Wird von Routern verwendet

Portnummer (Schicht 4):
    80 (HTTP), 443 (HTTPS), 25 (SMTP)
    Identifiziert Anwendung
    Kombination: IP:Port (192.168.1.100:80)

Zusammenarbeit:
    MAC (lokal) + IP (routing) + Port (Anwendung) = vollständige Adressierung
```

**Praxis-Beispiel:**
Adressierung beim Web-Zugriff:
- **MAC-Adresse:** Netzwerkkarte hat feste MAC 00:1A:2B:3C:4D:5E, Switch verwendet diese für lokale Weiterleitung
- **IP-Adresse:** Client hat IP 192.168.1.100 (lokal), Webserver hat IP 203.0.113.10 (öffentlich), Router verwendet IP für Routing
- **Portnummer:** Browser nutzt Port 80 (HTTP) oder 443 (HTTPS), identifiziert Web-Anwendung
- **Vollständige Adresse:** 192.168.1.100:443 → Client mit IP 192.168.1.100, Port 443 (HTTPS)
- **ARP:** Client fragt "Wer hat IP 192.168.1.1?" → Antwort: "MAC 00:1B:2C:3D:4E:5F"

**Prüfungscheck:**
**Frage:** Was ist der Unterschied zwischen MAC-Adresse und IP-Adresse?

**Antwort:**
- **MAC-Adresse (Media Access Control):**
  - Physische Adresse, fest im Gerät eingebaut
  - 48 Bit (6 Bytes), Format: 00:1A:2B:3C:4D:5E
  - Eindeutig weltweit (theoretisch)
  - Schicht 2 (Data Link), lokal im Netzwerk
  - Wird von Switches verwendet

- **IP-Adresse (Internet Protocol):**
  - Logische Adresse, konfigurierbar
  - IPv4: 32 Bit (4 Bytes), Format: 192.168.1.1
  - IPv6: 128 Bit (16 Bytes)
  - Schicht 3 (Network), routingfähig
  - Wird von Routern verwendet
  - Kann sich ändern (DHCP)

**Zusammenarbeit:** MAC für lokale Kommunikation, IP für Routing über Netzwerke hinweg.

**Merksatz:**
"MAC = physisch lokal, IP = logisch routingfähig - beide zusammen ermöglichen Kommunikation!"

---

### 3.4.6: Netzwerkkomponenten unterscheiden

**Kurz-Definition:**
Netzwerkkomponenten verbinden und steuern den Datenverkehr. Unterschieden werden Hub (veraltet), Switch (Standard), Router (Routing), Bridge (Segmentierung) und Gateway (Protokollumsetzung).

**Tabellarische Übersicht:**

| Komponente | Schicht | Funktion | Einsatz |
|------------|---------|----------|---------|
| **Hub** | 1 (Physical) | Verstärkt Signal, Broadcast | Veraltet, nicht mehr verwendet |
| **Switch** | 2 (Data Link) | Verbindet Geräte, MAC-basiert | Standard LAN-Komponente |
| **Router** | 3 (Network) | Verbindet Netzwerke, IP-basiert | Internet-Zugang, VLAN-Routing |
| **Bridge** | 2 (Data Link) | Verbindet Netzwerksegmente | Segmentierung, veraltet |
| **Gateway** | 3-7 | Protokollumsetzung | Verbindung verschiedener Protokolle |
| **Access Point** | 1-2 | WLAN-Zugang | Drahtlose Verbindungen |
| **Modem** | 1 (Physical) | Signalumsetzung | Internet-Zugang (DSL, Kabel) |

| Komponente | Entscheidung | Vorteil | Nachteil |
|------------|--------------|---------|----------|
| **Hub** | Keine, Broadcast | Günstig | Kollisionen, langsam, veraltet |
| **Switch** | MAC-Adresse | Keine Kollisionen, schnell | Teurer als Hub |
| **Router** | IP-Adresse | Routing, Firewall | Komplexer, teurer |
| **Access Point** | WLAN-Protokoll | Drahtlos, flexibel | Störanfällig, Sicherheit |

**Visuelle Darstellung:**
```
Netzwerkkomponenten nach Schicht:

Schicht 1 (Physical):
    Hub: Broadcast an alle Ports (veraltet)
    Modem: Signalumsetzung

Schicht 2 (Data Link):
    Switch: MAC-basiert, lokale Verbindung
    Bridge: Segmentierung (veraltet)
    Access Point: WLAN-Zugang

Schicht 3 (Network):
    Router: IP-basiert, verbindet Netzwerke
    Gateway: Protokollumsetzung

Funktionsweise:
    Hub: [Client1] → [Hub] → [Alle Clients] (Broadcast)
    Switch: [Client1] → [Switch] → [Client2] (gezielt, MAC-Tabelle)
    Router: [Netzwerk1] → [Router] → [Netzwerk2] (Routing-Tabelle)
```

**Praxis-Beispiel:**
Verschiedene Komponenten im Netzwerk:
- **Switch (Layer 2):** 24-Port-Switch verbindet PCs im Büro, kennt MAC-Adressen, leitet Pakete gezielt weiter, keine Kollisionen
- **Router (Layer 3):** Router verbindet lokales Netzwerk (192.168.1.0/24) mit Internet, verwendet IP-Adressen für Routing, NAT für Internet-Zugang
- **Access Point (Layer 1-2):** WLAN-Access Point ermöglicht drahtlose Verbindung, konvertiert zwischen WLAN und Ethernet
- **Gateway:** Verbindet verschiedene Protokolle, z.B. IPv4 zu IPv6 oder Ethernet zu DSL

**Prüfungscheck:**
**Frage:** Was ist der Unterschied zwischen Switch und Router?

**Antwort:**
- **Switch (Schicht 2 - Data Link):**
  - Verbindet Geräte im gleichen Netzwerk (LAN)
  - Entscheidet basierend auf MAC-Adressen
  - Erstellt MAC-Adresstabelle (welches Gerät an welchem Port)
  - Broadcast-Domäne bleibt erhalten
  - Einsatz: Lokale Netzwerke, Verbindung von Geräten

- **Router (Schicht 3 - Network):**
  - Verbindet verschiedene Netzwerke
  - Entscheidet basierend auf IP-Adressen
  - Erstellt Routing-Tabelle (welches Netzwerk über welchen Weg)
  - Trennt Broadcast-Domänen
  - Einsatz: Internet-Zugang, Verbindung verschiedener Netzwerke, VLAN-Routing

**Zusammenarbeit:** Switch verbindet Geräte lokal, Router verbindet Netzwerke.

**Merksatz:**
"Switch = lokal (MAC), Router = zwischen Netzwerken (IP) - Schicht bestimmt Funktion!"

---

### 3.4.7: Netzwerkstandards unterscheiden

**Kurz-Definition:**
Netzwerkstandards definieren Regeln und Spezifikationen für die Kommunikation. Wichtige Standards sind IEEE 802 (Ethernet, WLAN), TCP/IP, und verschiedene Kabelstandards (TIA/EIA).

**Tabellarische Übersicht:**

| Standard | Beschreibung | Bereich | Beispiel |
|----------|--------------|---------|----------|
| **IEEE 802.3** | Ethernet (kabelgebunden) | LAN | 10BASE-T, 100BASE-TX, 1000BASE-T |
| **IEEE 802.11** | WLAN (drahtlos) | Wireless | 802.11n, 802.11ac, 802.11ax (WiFi 6) |
| **IEEE 802.1Q** | VLAN-Tagging | Virtualisierung | VLAN-Erkennung |
| **TCP/IP** | Internet-Protokoll | Internet | IPv4, IPv6 |
| **TIA/EIA-568** | Strukturierte Verkabelung | Verkabelung | Cat 5e, Cat 6, Cat 6a |
| **ISO/IEC 11801** | Internationale Verkabelung | Verkabelung | Internationaler Standard |

| WLAN-Standard | Frequenz | Geschwindigkeit | Jahr |
|---------------|----------|-----------------|------|
| **802.11a** | 5 GHz | 54 Mbps | 1999 |
| **802.11b** | 2,4 GHz | 11 Mbps | 1999 |
| **802.11g** | 2,4 GHz | 54 Mbps | 2003 |
| **802.11n** | 2,4/5 GHz | 600 Mbps | 2009 |
| **802.11ac** | 5 GHz | 6,9 Gbps | 2013 |
| **802.11ax (WiFi 6)** | 2,4/5/6 GHz | 9,6 Gbps | 2019 |

**Visuelle Darstellung:**
```
Netzwerkstandards:

IEEE 802.3 (Ethernet):
    10BASE-T → 100BASE-TX → 1000BASE-T → 10GBASE-T
    10 Mbps → 100 Mbps → 1 Gbps → 10 Gbps

IEEE 802.11 (WLAN):
    802.11b → 802.11g → 802.11n → 802.11ac → 802.11ax
    11 Mbps → 54 Mbps → 600 Mbps → 6,9 Gbps → 9,6 Gbps

Standards-Hierarchie:
    IEEE 802.3 (Ethernet) → Kabelgebundenes LAN
    IEEE 802.11 (WLAN) → Drahtloses LAN
    TCP/IP → Internet-Protokoll
    TIA/EIA-568 → Verkabelungsstandard
```

**Praxis-Beispiel:**
Standards im Unternehmen:
- **IEEE 802.3 (Ethernet):** Alle Netzwerkkarten unterstützen 1000BASE-T (Gigabit Ethernet), Cat 6 Kabel, Standard für kabelgebundene Verbindungen
- **IEEE 802.11ac (WLAN):** Access Points nutzen 802.11ac Standard, 5 GHz Frequenz, bis zu 1,3 Gbps, für mobile Geräte
- **IEEE 802.1Q (VLAN):** Switch unterstützt VLAN-Tagging, ermöglicht logische Netzwerksegmentierung
- **TIA/EIA-568:** Verkabelung nach Standard, Cat 6 Kabel, strukturierte Verkabelung, zertifiziert

**Prüfungscheck:**
**Frage:** Welche IEEE-Standards sind wichtig für Netzwerke?

**Antwort:**
Wichtige IEEE-Standards:
1. **IEEE 802.3:** Ethernet (kabelgebunden) - 10BASE-T, 100BASE-TX, 1000BASE-T
2. **IEEE 802.11:** WLAN (drahtlos) - 802.11n, 802.11ac, 802.11ax (WiFi 6)
3. **IEEE 802.1Q:** VLAN-Tagging - Erkennung von VLANs
4. **IEEE 802.1X:** Authentifizierung - Port-basierte Zugriffskontrolle
5. **IEEE 802.3af/at:** Power over Ethernet (PoE) - Stromversorgung über Netzwerkkabel

**Merksatz:**
"IEEE 802.3 = Ethernet, IEEE 802.11 = WLAN - Standards ermöglichen Kompatibilität!"

---

## 3.5: Selbstständig die Integration von Clients in ein Netzwerk planen und durchführen

### 3.5.1: Anforderungen der Clients und des Netzwerkes untersuchen

**Kurz-Definition:**
Vor der Integration müssen Anforderungen von Clients (Hardware, Software, Funktionen) und Netzwerk (Bandbreite, Sicherheit, Protokolle) analysiert werden, um eine passende Lösung zu finden.

**Tabellarische Übersicht:**

| Anforderungsbereich | Client-Anforderungen | Netzwerkanforderungen |
|---------------------|---------------------|----------------------|
| **Hardware** | CPU, RAM, Speicher, Netzwerkkarte | Switch-Ports, Bandbreite |
| **Software** | Betriebssystem, Anwendungen | Protokolle, Kompatibilität |
| **Funktionalität** | Benötigte Dienste (Druck, Dateien) | Server-Verfügbarkeit, Dienste |
| **Sicherheit** | Authentifizierung, Verschlüsselung | Firewall, Zugriffskontrollen |
| **Performance** | Geschwindigkeit, Latenz | Bandbreite, QoS |
| **Verfügbarkeit** | Ausfallzeiten, Redundanz | Netzwerk-Redundanz |

**Visuelle Darstellung:**
```
Anforderungsanalyse-Prozess:

Client-Anforderungen:
    Hardware (CPU, RAM, Speicher, NIC)
         ↓
    Software (OS, Anwendungen, Treiber)
         ↓
    Funktionalität (Dienste, Zugriff)
         ↓
    Sicherheit (Authentifizierung, Verschlüsselung)

Netzwerkanforderungen:
    Hardware (Switch-Ports, Kabel, Bandbreite)
         ↓
    Software (Protokolle, Dienste, Kompatibilität)
         ↓
    Performance (Geschwindigkeit, Latenz)
         ↓
    Verfügbarkeit (Redundanz, Ausfallzeiten)

Abgleich:
    Client-Anforderungen ↔ Netzwerkanforderungen
    → Passende Lösung finden
```

**Praxis-Beispiel:**
Anforderungsanalyse für neuen Arbeitsplatz:
- **Client-Hardware:** PC mit Windows 11, 16 GB RAM, Gigabit-Netzwerkkarte, benötigt für CAD-Software
- **Client-Software:** Windows 11, CAD-Programm, Office, benötigt Zugriff auf Dateiserver
- **Netzwerk-Hardware:** Verfügbarer Switch-Port, Cat 6 Kabel vorhanden, 1 Gbps Bandbreite
- **Netzwerk-Software:** TCP/IP, DHCP, DNS verfügbar, kompatibel
- **Funktionale Anforderungen:** Zugriff auf Dateiserver, Drucker, Internet, CAD-Lizenzserver
- **Sicherheit:** Domain-Anmeldung, verschlüsselte Verbindung, Firewall-Regeln
- **Ergebnis:** PC kann integriert werden, alle Anforderungen erfüllt

**Prüfungscheck:**
**Frage:** Welche Anforderungen müssen vor der Client-Integration untersucht werden?

**Antwort:**
1. **Client-Hardware:** CPU, RAM, Speicher, Netzwerkkarte (Gigabit?), Schnittstellen
2. **Client-Software:** Betriebssystem, benötigte Anwendungen, Treiber
3. **Netzwerk-Hardware:** Verfügbare Switch-Ports, Kabel, Bandbreite
4. **Netzwerk-Software:** Protokolle (TCP/IP), Dienste (DHCP, DNS), Kompatibilität
5. **Funktionale Anforderungen:** Benötigte Dienste (Drucker, Dateiserver, Internet)
6. **Sicherheitsanforderungen:** Authentifizierung, Verschlüsselung, Firewall-Regeln
7. **Performance-Anforderungen:** Geschwindigkeit, Latenz, Bandbreite

**Merksatz:**
"Anforderungen = Hardware + Software + Funktion + Sicherheit + Performance - alles prüfen vor Integration!"

---

### 3.5.2: Cloud-Dienste nutzen

**Kurz-Definition:**
Cloud-Dienste sind IT-Dienste, die über das Internet bereitgestellt werden. Unterschieden werden SaaS (Software), PaaS (Plattform) und IaaS (Infrastruktur). Clients können auf Cloud-Dienste zugreifen.

**Tabellarische Übersicht:**

| Cloud-Modell | Beschreibung | Beispiel | Client-Zugriff |
|--------------|--------------|----------|----------------|
| **SaaS** | Software as a Service | Office 365, Google Workspace | Browser, App |
| **PaaS** | Platform as a Service | Azure, AWS | Entwickler-Plattform |
| **IaaS** | Infrastructure as a Service | Virtual Server, Storage | Verwaltung über API |
| **DaaS** | Desktop as a Service | Virtual Desktop | Thin Client, Browser |

| Cloud-Typ | Beschreibung | Vorteile | Nachteile |
|-----------|--------------|----------|-----------|
| **Public Cloud** | Öffentliche Cloud (Provider) | Skalierbar, günstig | Abhängigkeit, Datenschutz |
| **Private Cloud** | Eigene Cloud | Kontrolle, Sicherheit | Teuer, Wartung |
| **Hybrid Cloud** | Kombination | Flexibel | Komplex |
| **Multi-Cloud** | Mehrere Provider | Ausfallsicherheit | Komplex |

**Visuelle Darstellung:**
```
Cloud-Modelle:

SaaS (Software as a Service):
    Client → Browser/App → Cloud-Anwendung
    Beispiel: Office 365, Google Workspace

PaaS (Platform as a Service):
    Entwickler → Cloud-Plattform → Anwendung
    Beispiel: Azure, AWS Elastic Beanstalk

IaaS (Infrastructure as a Service):
    Client → Verwaltung → Cloud-Infrastruktur
    Beispiel: Virtual Server, Storage

Cloud-Typen:
    Public Cloud → Provider (AWS, Azure)
    Private Cloud → Eigene Cloud
    Hybrid Cloud → Kombination
    Multi-Cloud → Mehrere Provider
```

**Praxis-Beispiel:**
Cloud-Dienste im Unternehmen:
- **SaaS:** Office 365 für E-Mail und Office-Anwendungen, Mitarbeiter nutzen über Browser, keine lokale Installation
- **PaaS:** Entwickler nutzen Azure für App-Entwicklung, Plattform stellt Datenbank, Web-Server bereit
- **IaaS:** Virtual Server auf AWS für Testumgebung, IT verwaltet Server selbst, flexibel skalierbar
- **Hybrid Cloud:** Wichtige Daten lokal (Private Cloud), weniger kritische Anwendungen in Public Cloud
- **Multi-Cloud:** Ausfallsicherheit durch Nutzung mehrerer Provider (AWS + Azure)

**Prüfungscheck:**
**Frage:** Was sind die drei Hauptmodelle von Cloud-Diensten?

**Antwort:**
1. **SaaS (Software as a Service):**
   - Komplette Anwendung aus der Cloud
   - Beispiel: Office 365, Google Workspace, Salesforce
   - Client: Nutzt über Browser oder App

2. **PaaS (Platform as a Service):**
   - Entwicklungsplattform aus der Cloud
   - Beispiel: Microsoft Azure, AWS Elastic Beanstalk
   - Client: Entwickler nutzen Plattform

3. **IaaS (Infrastructure as a Service):**
   - IT-Infrastruktur aus der Cloud
   - Beispiel: Virtual Server, Storage, Netzwerk
   - Client: Verwaltet Infrastruktur selbst

**Merksatz:**
"SaaS = Software, PaaS = Plattform, IaaS = Infrastruktur - Cloud-Modell bestimmt Kontrolle!"

---

### 3.5.3: Benutzer anmelden

**Kurz-Definition:**
Die Benutzeranmeldung (Login) authentifiziert Benutzer im Netzwerk. Unterschieden werden lokale Anmeldung (lokal auf Client) und Netzwerkanmeldung (Domain, Active Directory).

**Tabellarische Übersicht:**

| Anmeldetyp | Beschreibung | Authentifizierung | Einsatz |
|------------|--------------|-------------------|---------|
| **Lokal** | Anmeldung am Client | Lokale Benutzerdatenbank | Einzelplatz |
| **Domain** | Anmeldung im Netzwerk | Active Directory, LDAP | Unternehmen |
| **Cloud** | Anmeldung über Cloud | Azure AD, Google Workspace | Cloud-Umgebung |
| **SSO** | Single Sign-On | Einmal anmelden, Zugriff auf alles | Moderne Umgebungen |

| Authentifizierungsmethode | Beschreibung | Sicherheit |
|---------------------------|--------------|------------|
| **Passwort** | Klassisches Passwort | Niedrig-Mittel |
| **2FA/MFA** | Zwei-/Multi-Faktor-Authentifizierung | Hoch |
| **Biometrie** | Fingerabdruck, Gesichtserkennung | Hoch |
| **Zertifikat** | Digitale Zertifikate | Sehr hoch |
| **Token** | Hardware/Software-Token | Hoch |

**Visuelle Darstellung:**
```
Anmeldungsarten:

Lokale Anmeldung:
    Client → Lokale Benutzerdatenbank → Zugriff
    Jeder Client hat eigene Datenbank

Domain-Anmeldung:
    Client → Domain Controller (AD) → Zugriff
    Zentrale Benutzerdatenbank

Cloud-Anmeldung:
    Client → Cloud (Azure AD) → Zugriff
    Cloud-basierte Authentifizierung

SSO (Single Sign-On):
    Einmal anmelden → Zugriff auf alle Dienste
    Beispiel: Office 365, Google Workspace

Authentifizierungsmethoden:
    Passwort → 2FA/MFA → Biometrie → Zertifikat
    (steigende Sicherheit)
```

**Praxis-Beispiel:**
Verschiedene Anmeldungsarten:
- **Lokale Anmeldung:** Einzelplatz-PC zu Hause, Benutzer "Max" lokal auf PC, keine Netzwerkverbindung nötig
- **Domain-Anmeldung:** Büro-PC im Unternehmen, Benutzer meldet sich an Domain "FIRMA.local" an, zentrale Verwaltung durch IT, Zugriff auf alle Ressourcen
- **Cloud-Anmeldung:** Laptop nutzt Azure AD, Anmeldung über Microsoft-Konto, Zugriff auf Office 365, von überall möglich
- **SSO:** Mitarbeiter meldet sich einmal an, hat automatisch Zugriff auf E-Mail, Dateien, Anwendungen, ohne erneute Anmeldung

**Prüfungscheck:**
**Frage:** Was ist der Unterschied zwischen lokaler Anmeldung und Domain-Anmeldung?

**Antwort:**
- **Lokale Anmeldung:**
  - Benutzerdaten werden lokal auf dem Client gespeichert
  - Jeder Client hat eigene Benutzerdatenbank
  - Keine zentrale Verwaltung
  - Einsatz: Einzelplatz-PCs, kleine Umgebungen

- **Domain-Anmeldung (Active Directory):**
  - Benutzerdaten werden zentral auf Domain Controller gespeichert
  - Einmalige Anmeldung für Zugriff auf alle Ressourcen
  - Zentrale Verwaltung, Richtlinien
  - Einsatz: Unternehmen, Netzwerke

**Vorteile Domain:** Zentrale Verwaltung, einheitliche Richtlinien, Single Sign-On

**Merksatz:**
"Lokal = einzeln, Domain = zentral - Anmeldung bestimmt Verwaltung!"

---

## 3.6: Die Netzwerkfunktion der Clients prüfen und warten

### 3.6.1: Verbindungstest durchführen

**Kurz-Definition:**
Verbindungstests prüfen, ob Clients erfolgreich mit dem Netzwerk verbunden sind. Wichtige Tools sind ping, tracert/traceroute, ipconfig/ifconfig und netstat.

**Tabellarische Übersicht:**

| Tool | Befehl | Funktion | Beispiel |
|------|--------|----------|----------|
| **ping** | `ping <IP/Name>` | Prüft Erreichbarkeit | `ping 192.168.1.1` |
| **tracert** | `tracert <IP/Name>` | Zeigt Route zum Ziel | `tracert google.com` |
| **ipconfig** | `ipconfig /all` | Zeigt IP-Konfiguration | Windows |
| **ifconfig** | `ifconfig` | Zeigt IP-Konfiguration | Linux/Mac |
| **netstat** | `netstat -an` | Zeigt Verbindungen | Aktive Verbindungen |
| **arp** | `arp -a` | Zeigt ARP-Tabelle | MAC-Adressen |

| Test | Zweck | Erwartetes Ergebnis |
|------|-------|---------------------|
| **ping localhost** | Lokaler Stack funktioniert | Antwort von 127.0.0.1 |
| **ping Gateway** | Gateway erreichbar | Antwort von Router |
| **ping DNS** | DNS-Server erreichbar | Antwort von DNS-Server |
| **ping Internet** | Internet-Verbindung | Antwort von externer IP |
| **tracert** | Route prüfen | Liste der Hops |

**Visuelle Darstellung:**
```
Systematischer Verbindungstest (von innen nach außen):

1. ping localhost (127.0.0.1)
   → TCP/IP-Stack funktioniert?

2. ping eigene IP (192.168.1.100)
   → Netzwerkkarte funktioniert?

3. ping Gateway (192.168.1.1)
   → Router erreichbar?

4. ping DNS-Server (8.8.8.8)
   → DNS erreichbar?

5. ping Internet (8.8.8.8 oder google.com)
   → Internet-Verbindung?

6. tracert google.com
   → Route anzeigen, Hops identifizieren

7. ipconfig /all
   → IP-Konfiguration prüfen
```

**Praxis-Beispiel:**
Verbindungstest bei Netzwerkproblem:
1. **ping localhost:** Antwort erhalten → TCP/IP-Stack funktioniert ✓
2. **ping eigene IP:** Antwort erhalten → Netzwerkkarte funktioniert ✓
3. **ping Gateway (192.168.1.1):** Keine Antwort → Problem: Router nicht erreichbar ✗
4. **ipconfig /all:** IP-Adresse vorhanden, aber Gateway falsch konfiguriert
5. **Lösung:** Gateway korrigieren, erneut testen → Verbindung funktioniert ✓
6. **tracert google.com:** Zeigt Route: Client → Router → ISP → Internet

**Prüfungscheck:**
**Frage:** Wie führt man einen systematischen Verbindungstest durch?

**Antwort:**
Systematischer Verbindungstest (von lokal zu entfernt):
1. **ping localhost (127.0.0.1):** Prüft, ob TCP/IP-Stack funktioniert
2. **ping eigene IP:** Prüft, ob Netzwerkkarte funktioniert
3. **ping Gateway:** Prüft, ob Router erreichbar ist
4. **ping DNS-Server:** Prüft, ob DNS erreichbar ist
5. **ping Internet (z.B. 8.8.8.8):** Prüft Internet-Verbindung
6. **tracert <Ziel>:** Zeigt Route und mögliche Probleme
7. **ipconfig /all:** Prüft IP-Konfiguration (IP, Subnetz, Gateway, DNS)

**Merksatz:**
"Verbindungstest = ping lokal → Gateway → DNS → Internet - systematisch von innen nach außen!"

---

### 3.6.2: Namensauflösung prüfen und einen Schnelltest durchführen

**Kurz-Definition:**
Namensauflösung wandelt Domain-Namen (z.B. www.example.com) in IP-Adressen um. DNS (Domain Name System) ist der Standard. Prüfung erfolgt mit nslookup, dig oder ping.

**Tabellarische Übersicht:**

| Tool | Befehl | Funktion | Beispiel |
|------|--------|----------|----------|
| **nslookup** | `nslookup <Name>` | DNS-Abfrage | `nslookup google.com` |
| **dig** | `dig <Name>` | DNS-Abfrage (Linux) | `dig example.com` |
| **ping** | `ping <Name>` | Prüft DNS + Verbindung | `ping www.example.com` |
| **ipconfig /flushdns** | DNS-Cache leeren | Windows | Cache zurücksetzen |
| **ipconfig /displaydns** | DNS-Cache anzeigen | Windows | Cache-Inhalt |

| DNS-Komponente | Funktion | Beispiel |
|----------------|----------|----------|
| **Resolver** | Client-seitige DNS-Abfrage | Windows DNS-Client |
| **DNS-Server** | Beantwortet DNS-Anfragen | 8.8.8.8 (Google), 1.1.1.1 (Cloudflare) |
| **DNS-Cache** | Speichert vorherige Anfragen | Lokaler Cache |
| **Root-Server** | Top-Level der DNS-Hierarchie | .com, .de, .org |

**Visuelle Darstellung:**
```
Namensauflösung (DNS):

Client → DNS-Server → Root-Server → TLD-Server → Authoritative Server
    ↓
IP-Adresse erhalten

DNS-Hierarchie:
    . (Root)
     ├── .com
     │    └── example.com → 192.0.2.1
     ├── .de
     │    └── beispiel.de → 203.0.113.1
     └── .org

DNS-Abfrage-Prozess:
    1. Client fragt: "Was ist IP von google.com?"
    2. DNS-Server fragt Root-Server
    3. Root-Server verweist auf .com-Server
    4. .com-Server verweist auf google.com-Server
    5. google.com-Server gibt IP zurück
    6. Client erhält IP-Adresse
```

**Praxis-Beispiel:**
Namensauflösung beim Web-Zugriff:
- **Client möchte:** www.example.com aufrufen
- **DNS-Abfrage:** Client fragt DNS-Server (8.8.8.8): "Was ist IP von www.example.com?"
- **DNS-Auflösung:** DNS-Server fragt hierarchisch: Root → .com → example.com → Antwort: 93.184.216.34
- **Cache:** IP wird im DNS-Cache gespeichert, nächste Anfrage schneller
- **Prüfung:** `nslookup www.example.com` zeigt IP-Adresse und verwendeten DNS-Server
- **Problem:** Wenn DNS-Server nicht erreichbar → `ping www.example.com` schlägt fehl, aber `ping 93.184.216.34` funktioniert

**Prüfungscheck:**
**Frage:** Wie prüft man die Namensauflösung?

**Antwort:**
Namensauflösung prüfen:
1. **ping <Domain-Name>:** Prüft, ob Name aufgelöst wird und erreichbar ist
   - Beispiel: `ping google.com`
   - Erfolg: Name wird zu IP aufgelöst, Antwort erhalten

2. **nslookup <Domain-Name>:** Direkte DNS-Abfrage
   - Beispiel: `nslookup google.com`
   - Zeigt IP-Adresse und DNS-Server

3. **ipconfig /displaydns:** Zeigt DNS-Cache (Windows)
   - Prüft, ob Einträge im Cache sind

4. **ipconfig /flushdns:** Leert DNS-Cache (Windows)
   - Bei Problemen: Cache leeren und erneut testen

**Häufige Probleme:**
- DNS-Server nicht erreichbar → Gateway prüfen
- Falsche DNS-Server konfiguriert → ipconfig /all prüfen
- DNS-Cache veraltet → Cache leeren

**Merksatz:**
"Namensauflösung = DNS wandelt Name in IP - ping, nslookup, Cache prüfen!"

---

### 3.6.3: Management und vorbeugende Wartung

**Kurz-Definition:**
Management und vorbeugende Wartung umfassen regelmäßige Maßnahmen zur Aufrechterhaltung der Netzwerkfunktionalität: Updates, Monitoring, Backups, Dokumentation und präventive Maßnahmen.

**Tabellarische Übersicht:**

| Wartungsmaßnahme | Beschreibung | Häufigkeit | Zweck |
|------------------|--------------|------------|-------|
| **Updates** | Betriebssystem, Treiber, Software | Regelmäßig | Sicherheit, Stabilität |
| **Monitoring** | Überwachung von Performance, Fehlern | Kontinuierlich | Früherkennung |
| **Backups** | Sicherung von Konfiguration, Daten | Täglich/Wöchentlich | Wiederherstellung |
| **Dokumentation** | Netzwerkstruktur, Konfiguration | Bei Änderungen | Nachvollziehbarkeit |
| **Präventive Prüfung** | Hardware, Kabel, Verbindungen | Monatlich | Ausfälle vermeiden |
| **Log-Analyse** | Auswertung von Log-Dateien | Regelmäßig | Probleme identifizieren |

| Monitoring-Bereich | Was wird überwacht? | Tool |
|-------------------|---------------------|------|
| **Performance** | CPU, RAM, Bandbreite | Task Manager, Performance Monitor |
| **Verbindungen** | Aktive Verbindungen, Ports | netstat, Resource Monitor |
| **Fehler** | Fehlerprotokolle, Events | Event Viewer, Logs |
| **Sicherheit** | Firewall, Angriffe | Firewall-Logs, IDS |

**Visuelle Darstellung:**
```
Vorbeugende Wartung - Zyklus:

Regelmäßige Updates
    ↓
Monitoring (Performance, Fehler)
    ↓
Backups (Konfiguration, Daten)
    ↓
Dokumentation (Änderungen)
    ↓
Präventive Prüfung (Hardware, Kabel)
    ↓
Log-Analyse (Probleme identifizieren)
    ↓
(Wiederholen)

Monitoring-Bereiche:
    Performance → CPU, RAM, Bandbreite
    Verbindungen → Aktive Sessions, Ports
    Fehler → Event Logs, Fehlerprotokolle
    Sicherheit → Firewall, Angriffe
```

**Praxis-Beispiel:**
Vorbeugende Wartung im Unternehmen:
- **Updates:** Windows-Updates automatisch jeden Dienstag, Antivirus-Updates täglich, Treiber-Updates monatlich
- **Monitoring:** Performance Monitor überwacht CPU, RAM, Netzwerk, Alerts bei >80% Auslastung
- **Backups:** Tägliche Backups von wichtigen Daten, wöchentliche Backups von Konfigurationen, monatliche Archivierung
- **Dokumentation:** Netzwerkdiagramm aktualisiert, IP-Adressen dokumentiert, Passwörter in Passwort-Manager
- **Präventive Prüfung:** Monatliche Prüfung von Kabeln, Verbindungen, Hardware, Reinigung von Geräten
- **Log-Analyse:** Wöchentliche Auswertung von Event Viewer, Firewall-Logs, Fehlerprotokolle

**Prüfungscheck:**
**Frage:** Welche vorbeugenden Wartungsmaßnahmen sind wichtig für Clients im Netzwerk?

**Antwort:**
Wichtige vorbeugende Wartungsmaßnahmen:
1. **Regelmäßige Updates:** Betriebssystem, Treiber, Software (Sicherheit, Stabilität)
2. **Monitoring:** Performance, Verbindungen, Fehler überwachen
3. **Backups:** Konfiguration, wichtige Daten sichern
4. **Dokumentation:** Netzwerkstruktur, IP-Adressen, Passwörter dokumentieren
5. **Präventive Prüfung:** Hardware, Kabel, Verbindungen regelmäßig prüfen
6. **Log-Analyse:** Event Viewer, Log-Dateien auswerten
7. **Antivirus/Antimalware:** Regelmäßige Scans, Updates
8. **Zugriffskontrollen:** Benutzerrechte prüfen, unnötige Rechte entfernen

**Merksatz:**
"Vorbeugende Wartung = Updates + Monitoring + Backups + Dokumentation - regelmäßig durchführen!"

---

## 3.7: Netzwerkkomponenten auswählen und konfigurieren

### 3.7.1: Netzwerkkarte auswählen

**Kurz-Definition:**
Netzwerkkarten (NIC - Network Interface Card) verbinden Clients mit dem Netzwerk. Auswahlkriterien sind Geschwindigkeit (10/100/1000 Mbps), Schnittstelle (PCIe, USB, integriert) und Features (PoE, WLAN).

**Tabellarische Übersicht:**

| Kriterium | Optionen | Empfehlung |
|-----------|----------|------------|
| **Geschwindigkeit** | 10/100 Mbps, 1 Gbps, 10 Gbps | Mindestens 1 Gbps (Gigabit) |
| **Schnittstelle** | PCIe, USB, integriert (Onboard) | PCIe für Desktop, USB für Laptop |
| **Typ** | Kabelgebunden, WLAN, Kombination | Nach Bedarf |
| **Features** | PoE, Wake-on-LAN, Teaming | Nach Anforderung |

| Geschwindigkeit | Standard | Einsatz | Kabel |
|-----------------|---------|----------|-------|
| **100 Mbps** | Fast Ethernet | Veraltet | Cat 5 |
| **1 Gbps** | Gigabit Ethernet | Standard heute | Cat 5e/6 |
| **10 Gbps** | 10 Gigabit | Server, Backbone | Cat 6a/7, Glasfaser |

| Schnittstelle | Beschreibung | Einsatz |
|---------------|--------------|---------|
| **Onboard** | Integriert im Mainboard | Standard bei modernen PCs |
| **PCIe** | Steckkarte für Desktop | Erweiterung, höhere Performance |
| **USB** | Externe Netzwerkkarte | Laptop, Erweiterung |

**Visuelle Darstellung:**
```
Netzwerkkarten-Auswahl:

Geschwindigkeit:
    100 Mbps (Fast Ethernet) → Veraltet
    1 Gbps (Gigabit) → Standard heute
    10 Gbps → Server, Backbone

Schnittstelle:
    Onboard → Integriert (Standard)
    PCIe → Desktop-Erweiterung
    USB → Laptop, extern

Typ:
    Kabelgebunden → Standard
    WLAN → Mobil
    Kombination → Beides

Auswahlkriterien:
    Geschwindigkeit → Schnittstelle → Typ → Features → Kompatibilität
```

**Praxis-Beispiel:**
Netzwerkkarten-Auswahl für verschiedene Szenarien:
- **Desktop-PC:** Onboard-Gigabit-NIC vorhanden, ausreichend für Standard-Nutzung, keine zusätzliche Karte nötig
- **Server:** PCIe 10-Gigabit-NIC für Server-zu-Server-Verbindungen, hohe Performance, Cat 6a Kabel
- **Laptop ohne Ethernet:** USB-Gigabit-Adapter, kompakt, Plug-and-Play, für Präsentationen mit kabelgebundener Verbindung
- **Gaming-PC:** PCIe-Gigabit-NIC mit Gaming-Features, niedrige Latenz, Priorisierung

**Prüfungscheck:**
**Frage:** Welche Kriterien sind bei der Auswahl einer Netzwerkkarte wichtig?

**Antwort:**
Wichtige Auswahlkriterien:
1. **Geschwindigkeit:** Mindestens 1 Gbps (Gigabit Ethernet) - Standard heute
2. **Schnittstelle:** PCIe (Desktop), USB (Laptop), Onboard (wenn vorhanden)
3. **Typ:** Kabelgebunden (Standard) oder WLAN (mobil)
4. **Kompatibilität:** Betriebssystem-Treiber verfügbar
5. **Features:** Wake-on-LAN (Fernstart), PoE (Power over Ethernet), Teaming (mehrere Karten)
6. **Hersteller:** Zuverlässige Marken (Intel, Realtek, Broadcom)
7. **Kosten:** Preis-Leistungs-Verhältnis

**Merksatz:**
"Netzwerkkarte = mindestens 1 Gbps, PCIe/USB/Onboard - Geschwindigkeit und Schnittstelle entscheiden!"

---

### 3.7.2: Switch auswählen

**Kurz-Definition:**
Switches verbinden Geräte im lokalen Netzwerk. Auswahlkriterien sind Port-Anzahl, Geschwindigkeit (10/100/1000 Mbps), Features (VLAN, PoE, Management) und Typ (Managed/Unmanaged).

**Tabellarische Übersicht:**

| Kriterium | Optionen | Empfehlung |
|-----------|----------|------------|
| **Port-Anzahl** | 4, 8, 16, 24, 48 Ports | Nach Bedarf + Reserve |
| **Geschwindigkeit** | 10/100 Mbps, 1 Gbps, 10 Gbps | Mindestens 1 Gbps |
| **Typ** | Unmanaged, Managed | Managed für Unternehmen |
| **Features** | VLAN, PoE, Link Aggregation | Nach Anforderung |
| **PoE** | Power over Ethernet | Für WLAN-APs, IP-Telefone |

| Switch-Typ | Beschreibung | Einsatz | Kosten |
|------------|--------------|---------|--------|
| **Unmanaged** | Plug & Play, keine Konfiguration | Kleine Netzwerke, Heim | Günstig |
| **Managed** | Konfigurierbar, VLAN, Monitoring | Unternehmen | Teurer |
| **Layer 2** | MAC-basiert, Standard | Standard LAN | Standard |
| **Layer 3** | IP-basiert, Routing | Erweiterte Funktionen | Teurer |

**Visuelle Darstellung:**
```
Switch-Auswahl:

Unmanaged Switch:
    Plug & Play
    Keine Konfiguration
    Günstig
    → Kleine Netzwerke

Managed Switch:
    Konfigurierbar
    VLAN, Monitoring, QoS
    Teurer
    → Unternehmen

Layer 2 vs. Layer 3:
    Layer 2: MAC-basiert (Standard)
    Layer 3: IP-basiert (Routing)

Features:
    VLAN → Netzwerksegmentierung
    PoE → Stromversorgung über Kabel
    Link Aggregation → Höhere Bandbreite
    Monitoring → Traffic-Überwachung
```

**Praxis-Beispiel:**
Switch-Auswahl für verschiedene Umgebungen:
- **Kleines Büro (5 PCs):** Unmanaged 8-Port-Switch, Plug & Play, günstig, ausreichend
- **Mittelständisches Unternehmen (50 PCs):** Managed 48-Port-Switch, VLANs für Abteilungen, Monitoring, QoS für VoIP
- **Großes Unternehmen:** Layer-3-Switch mit Routing, mehrere VLANs, Link Aggregation, erweiterte Sicherheit
- **WLAN-Umgebung:** PoE-Switch für Access Points, versorgt APs über Netzwerkkabel mit Strom

**Prüfungscheck:**
**Frage:** Wann sollte ein Managed Switch statt eines Unmanaged Switches verwendet werden?

**Antwort:**
Ein Managed Switch ist sinnvoll bei:
1. **VLANs:** Netzwerksegmentierung (Abteilungen, Sicherheit)
2. **Monitoring:** Überwachung von Traffic, Fehlern
3. **QoS (Quality of Service):** Priorisierung von Traffic
4. **Link Aggregation:** Bündelung mehrerer Ports für höhere Bandbreite
5. **Sicherheit:** Port-basierte Zugriffskontrollen, 802.1X
6. **Skalierbarkeit:** Erweiterte Funktionen für Wachstum
7. **Troubleshooting:** Detaillierte Logs, Diagnose-Tools

**Unmanaged Switch:** Ausreichend für kleine Netzwerke ohne spezielle Anforderungen.

**Merksatz:**
"Unmanaged = einfach, Managed = konfigurierbar - Anforderungen bestimmen Typ!"

---

### 3.7.3: Router auswählen

**Kurz-Definition:**
Router verbinden verschiedene Netzwerke und leiten Datenpakete weiter. Auswahlkriterien sind Routing-Performance, WAN-Ports, Features (Firewall, VPN, QoS) und Typ (Consumer, Business, Enterprise).

**Tabellarische Übersicht:**

| Kriterium | Optionen | Empfehlung |
|-----------|----------|------------|
| **Routing-Performance** | Pakete pro Sekunde | Nach Netzwerk-Größe |
| **WAN-Ports** | Anzahl, Geschwindigkeit | Nach Internet-Anschluss |
| **LAN-Ports** | Anzahl, Geschwindigkeit | Nach lokalen Geräten |
| **Features** | Firewall, VPN, QoS, WLAN | Nach Anforderungen |
| **Typ** | Consumer, Business, Enterprise | Nach Einsatz |

| Router-Typ | Beschreibung | Einsatz | Features |
|------------|--------------|---------|----------|
| **Consumer** | Heim-Router | Privat, kleine Büros | WLAN, einfache Firewall |
| **Business** | Geschäfts-Router | Unternehmen | VPN, erweiterte Firewall |
| **Enterprise** | Unternehmens-Router | Große Netzwerke | Hochleistung, erweiterte Features |

| Feature | Beschreibung | Wichtig für |
|---------|--------------|------------|
| **Firewall** | Schutz vor Angriffen | Sicherheit |
| **VPN** | Verschlüsselte Verbindungen | Remote-Zugriff |
| **QoS** | Traffic-Priorisierung | Performance |
| **VLAN** | Virtuelle Netzwerke | Segmentierung |
| **WLAN** | Drahtloser Zugang | Mobilität |

**Visuelle Darstellung:**
```
Router-Features:

Firewall:
    Paketfilterung
    Schutz vor Angriffen
    → Sicherheit

VPN:
    Verschlüsselte Verbindungen
    Remote-Zugriff
    → Flexibilität

QoS:
    Traffic-Priorisierung
    VoIP vorrangig
    → Performance

VLAN:
    Virtuelle Netzwerke
    Segmentierung
    → Organisation

Router-Typen:
    Consumer → Heim, kleine Büros
    Business → Unternehmen
    Enterprise → Große Netzwerke
```

**Praxis-Beispiel:**
Router-Auswahl für verschiedene Anforderungen:
- **Heim-Router:** Consumer-Router mit WLAN, einfache Firewall, günstig, für Privatnutzer
- **Kleines Unternehmen:** Business-Router mit VPN (für Home-Office), erweiterte Firewall, QoS für VoIP-Telefonie
- **Großes Unternehmen:** Enterprise-Router mit hoher Performance, mehrere WAN-Ports für Redundanz, erweiterte Features
- **Spezialanforderungen:** Router mit Dual-WAN für Ausfallsicherheit, VLAN-Unterstützung für Segmentierung

**Prüfungscheck:**
**Frage:** Welche Features sind bei der Router-Auswahl wichtig?

**Antwort:**
Wichtige Router-Features:
1. **Firewall:** Schutz vor externen Angriffen, Paketfilterung
2. **VPN:** Verschlüsselte Verbindungen für Remote-Zugriff (IPsec, SSL-VPN)
3. **QoS (Quality of Service):** Priorisierung von Traffic (z.B. VoIP vorrangig)
4. **VLAN-Unterstützung:** Virtuelle Netzwerke für Segmentierung
5. **WLAN:** Integrierter Access Point (optional)
6. **Dual-WAN:** Mehrere Internet-Anschlüsse für Redundanz
7. **Monitoring/Logging:** Überwachung und Protokollierung
8. **Port-Weiterleitung:** Für Server-Zugriff von außen

**Merksatz:**
"Router = Firewall + VPN + QoS + VLAN - Features bestimmen Einsatz!"

---

### 3.7.4: Netzwerkgeräte konfigurieren

**Kurz-Definition:**
Die Konfiguration von Netzwerkgeräten umfasst die Einrichtung von IP-Adressen, Subnetzmasken, Gateways, DNS-Servern, VLANs, Firewall-Regeln und weiteren Einstellungen je nach Gerät.

**Tabellarische Übersicht:**

| Gerät | Wichtige Konfigurationen | Beispiel |
|-------|-------------------------|----------|
| **Client** | IP, Subnetz, Gateway, DNS | DHCP oder statisch |
| **Switch** | VLANs, Port-Konfiguration, Management-IP | VLAN 10, 20, 30 |
| **Router** | Routing, Firewall, NAT, DHCP | Internet-Routing, Firewall-Regeln |
| **Access Point** | SSID, Verschlüsselung, Kanal | WLAN-Name, WPA2, Kanal 6 |
| **Firewall** | Regeln, Ports, Protokolle | Port 80/443 erlauben |

| Konfigurationsmethode | Beschreibung | Einsatz |
|----------------------|--------------|---------|
| **Web-Interface** | Browser-basierte Konfiguration | Standard, benutzerfreundlich |
| **CLI** | Kommandozeile | Erweiterte Konfiguration |
| **SNMP** | Netzwerk-Management-Protokoll | Monitoring, zentrale Verwaltung |
| **Konfigurationsdatei** | Textdatei mit Einstellungen | Backup, Wiederherstellung |

**Visuelle Darstellung:**
```
Client-Konfiguration:

IP-Konfiguration:
    IP-Adresse: 192.168.1.100 (statisch oder DHCP)
    Subnetzmaske: 255.255.255.0
    Gateway: 192.168.1.1
    DNS: 8.8.8.8, 1.1.1.1

Netzwerk-Einstellungen:
    Computername: PC-ABED-01
    Arbeitsgruppe/Domain: FIRMA.local
    Netzwerkprofil: Privat/Domäne/Öffentlich

Sicherheit:
    Firewall: Aktiviert
    Updates: Automatisch

Konfigurationsmethoden:
    Web-Interface → Browser (Router, Switch)
    CLI → Kommandozeile (erweitert)
    GUI → Windows-Einstellungen (Client)
```

**Praxis-Beispiel:**
Client-Konfiguration im Unternehmen:
- **IP-Konfiguration:** DHCP aktiviert, Client erhält automatisch IP 192.168.1.100, Subnetz 255.255.255.0, Gateway 192.168.1.1, DNS 192.168.1.10
- **Computername:** PC-VERTRIEB-05 (eindeutig im Netzwerk)
- **Domain:** Client ist Mitglied der Domain "FIRMA.local", zentrale Verwaltung
- **Firewall:** Windows-Firewall aktiviert, erlaubt Domain-Traffic, blockiert unbekannte Verbindungen
- **Netzwerkprofil:** "Domäne" - optimiert für Unternehmensnetzwerk

**Prüfungscheck:**
**Frage:** Welche grundlegenden Konfigurationen sind für einen Client im Netzwerk nötig?

**Antwort:**
Grundlegende Client-Konfiguration:
1. **IP-Adresse:** Statisch oder per DHCP
2. **Subnetzmaske:** Netzwerk-Bereich (z.B. 255.255.255.0)
3. **Standard-Gateway:** Router-Adresse (z.B. 192.168.1.1)
4. **DNS-Server:** DNS-Server-Adressen (z.B. 8.8.8.8, 1.1.1.1)
5. **Computername:** Eindeutiger Name im Netzwerk
6. **Arbeitsgruppe/Domain:** Lokale Gruppe oder Domain-Anmeldung
7. **Firewall:** Windows-Firewall konfigurieren
8. **Netzwerkprofil:** Privat, Öffentlich, Domäne

**DHCP vereinfacht:** Automatische Konfiguration von IP, Subnetz, Gateway, DNS

**Merksatz:**
"Client-Konfiguration = IP + Subnetz + Gateway + DNS - DHCP macht's automatisch!"

---

## 3.8: Grundlagen der Daten- und Netzwerksicherheit beschreiben

### 3.8.1: RAID-Systeme unterscheiden

**Kurz-Definition:**
RAID (Redundant Array of Independent Disks) kombiniert mehrere Festplatten zu einem logischen Laufwerk für Performance, Redundanz oder beides. Unterschieden werden verschiedene RAID-Level (0, 1, 5, 6, 10).

**Tabellarische Übersicht:**

| RAID-Level | Beschreibung | Mindest-Festplatten | Redundanz | Performance | Einsatz |
|------------|--------------|---------------------|-----------|------------|---------|
| **RAID 0** | Striping (keine Redundanz) | 2 | Keine | Sehr hoch | Performance, nicht kritisch |
| **RAID 1** | Mirroring (Spiegelung) | 2 | 1 Platte | Mittel | Wichtige Daten |
| **RAID 5** | Striping + Parity | 3 | 1 Platte | Hoch | Standard Server |
| **RAID 6** | Striping + doppelte Parity | 4 | 2 Platten | Hoch | Kritische Daten |
| **RAID 10** | RAID 1 + RAID 0 | 4 | 1 Platte pro Mirror | Sehr hoch | Performance + Redundanz |

| RAID-Typ | Vorteile | Nachteile |
|----------|----------|-----------|
| **RAID 0** | Sehr schnell, günstig | Keine Redundanz, Ausfall = Datenverlust |
| **RAID 1** | Einfach, gute Redundanz | 50% Speicherverlust, teuer |
| **RAID 5** | Gute Balance, effizient | Langsam bei Rebuild, 1 Platte Redundanz |
| **RAID 6** | 2 Platten Redundanz | Langsamer, mehr Platten nötig |
| **RAID 10** | Sehr schnell, gute Redundanz | Teuer, 50% Speicherverlust |

**Visuelle Darstellung:**
```
RAID-Level:

RAID 0 (Striping):
    [Daten1][Daten2][Daten3][Daten4]
    → Sehr schnell, keine Redundanz

RAID 1 (Mirroring):
    [Daten] → [Daten] (Spiegelung)
    → Redundanz, 50% Verlust

RAID 5 (Striping + Parity):
    [D1][D2][P] [D3][D4][P] [D5][D6][P]
    → Balance, 1 Platte Redundanz

RAID 10 (RAID 1+0):
    [Daten]→[Daten] [Daten]→[Daten]
    → Sehr schnell + Redundanz
```

**Praxis-Beispiel:**
RAID-Auswahl für verschiedene Server:
- **RAID 0:** Gaming-PC mit 2 SSDs, sehr schnell, keine wichtigen Daten, Performance wichtiger als Sicherheit
- **RAID 1:** Kleiner Server mit 2 Festplatten, einfache Lösung, 1 Platte kann ausfallen, 50% Speicherverlust
- **RAID 5:** Standard-Server mit 4 Festplatten, gute Balance, 1 Platte Redundanz, effizienter Speicher
- **RAID 6:** Kritischer Server mit 6 Festplatten, 2 Platten können ausfallen, höchste Sicherheit
- **RAID 10:** Datenbankserver mit 8 Festplatten, sehr schnell, gute Redundanz, für Performance-kritische Anwendungen

**Prüfungscheck:**
**Frage:** Welches RAID-Level sollte für einen Server mit wichtigen Daten verwendet werden?

**Antwort:**
Für Server mit wichtigen Daten empfohlen:
1. **RAID 5:** Gute Balance aus Performance und Redundanz, Standard für Server
   - Mindestens 3 Festplatten
   - 1 Platte kann ausfallen
   - Gute Performance

2. **RAID 6:** Höhere Redundanz für kritische Daten
   - Mindestens 4 Festplatten
   - 2 Platten können ausfallen
   - Etwas langsamer als RAID 5

3. **RAID 10:** Für hohe Performance und Redundanz
   - Mindestens 4 Festplatten
   - Sehr schnell, gute Redundanz
   - Teurer, 50% Speicherverlust

**RAID 0:** Nicht für wichtige Daten (keine Redundanz)!
**RAID 1:** Für kleine Server, einfache Lösung

**Merksatz:**
"RAID 0 = schnell aber gefährlich, RAID 1 = sicher aber teuer, RAID 5 = Standard, RAID 10 = Beste!"

---

### 3.8.2: Backupstrategien unterscheiden

**Kurz-Definition:**
Backupstrategien sichern Daten regelmäßig, um bei Verlust wiederherstellen zu können. Unterschieden werden Vollbackup, Inkrementelles Backup, Differenzielles Backup und verschiedene Speicherorte.

**Tabellarische Übersicht:**

| Backup-Typ | Beschreibung | Vorteile | Nachteile | Einsatz |
|------------|--------------|----------|-----------|---------|
| **Vollbackup** | Alle Daten sichern | Einfach, schnell wiederherstellbar | Langsam, viel Speicher | Wöchentlich |
| **Inkrementell** | Nur geänderte Daten seit letztem Backup | Schnell, wenig Speicher | Langsam wiederherstellen | Täglich |
| **Differenziell** | Alle Änderungen seit letztem Vollbackup | Schneller wiederherstellen | Mehr Speicher als inkrementell | Täglich |
| **Snapshot** | Momentaufnahme | Sehr schnell | Kurzfristig | Kontinuierlich |

| Speicherort | Beschreibung | Vorteile | Nachteile |
|-------------|--------------|----------|-----------|
| **Lokal** | Externe Festplatte, NAS | Schnell, einfach | Kein Schutz vor Diebstahl/Brand |
| **Cloud** | Online-Speicher | Automatisch, ortsunabhängig | Abhängigkeit, Kosten |
| **Offsite** | Externer Standort | Schutz vor lokalen Katastrophen | Aufwendig |
| **Band** | Magnetband | Günstig, langfristig | Langsam, veraltet |

| Backup-Strategie | Beispiel | Beschreibung |
|------------------|----------|--------------|
| **3-2-1-Regel** | 3 Kopien, 2 Medien, 1 offsite | Best Practice |
| **Grandfather-Father-Son** | Täglich, wöchentlich, monatlich | Langfristige Archivierung |

**Visuelle Darstellung:**
```
Backup-Strategien:

Vollbackup:
    [Alle Daten] → Backup-Medium
    → Einfach, schnell wiederherstellbar

Inkrementell:
    Mo: [Vollbackup]
    Di: [Änderungen seit Mo]
    Mi: [Änderungen seit Di]
    Do: [Änderungen seit Mi]
    → Wiederherstellung: Mo + Di + Mi + Do

Differenziell:
    Mo: [Vollbackup]
    Di: [Alle Änderungen seit Mo]
    Mi: [Alle Änderungen seit Mo]
    Do: [Alle Änderungen seit Mo]
    → Wiederherstellung: Mo + Do

3-2-1-Regel:
    3 Kopien (Original + 2 Backups)
    2 Medien (z.B. Festplatte + Cloud)
    1 Offsite (externe Sicherung)
```

**Praxis-Beispiel:**
Backup-Strategie im Unternehmen:
- **Vollbackup:** Wöchentlich am Sonntag, alle Daten, 500 GB, 2 Stunden, einfach wiederherstellbar
- **Inkrementell:** Täglich Montag-Freitag, nur geänderte Dateien, 10-50 GB, 15 Minuten, Speicherplatz sparen
- **Differenziell:** Alternative täglich, alle Änderungen seit letztem Vollbackup, 50-200 GB, 30 Minuten, schneller wiederherstellbar
- **3-2-1-Regel:** Original auf Server, Backup 1 auf NAS (lokal), Backup 2 in Cloud (offsite), Schutz vor lokalen Katastrophen

**Prüfungscheck:**
**Frage:** Was ist der Unterschied zwischen inkrementellem und differenziellem Backup?

**Antwort:**
- **Inkrementelles Backup:**
  - Sichert nur Daten, die seit dem letzten Backup (egal welcher Typ) geändert wurden
  - Schnell, wenig Speicher
  - Wiederherstellung: Vollbackup + alle Inkremente seitdem (langsam)
  - Beispiel: Mo Voll, Di Inkr, Mi Inkr, Do Inkr → Wiederherstellung: Mo + Di + Mi + Do

- **Differenzielles Backup:**
  - Sichert alle Daten, die seit dem letzten Vollbackup geändert wurden
  - Etwas mehr Speicher als inkrementell
  - Wiederherstellung: Vollbackup + letztes Differenziell (schneller)
  - Beispiel: Mo Voll, Di Diff, Mi Diff, Do Diff → Wiederherstellung: Mo + Do

**Merksatz:**
"Inkrementell = seit letztem Backup, differenziell = seit letztem Vollbackup - Typ bestimmt Wiederherstellung!"

---

### 3.8.3: Netzwerksicherheit herstellen

**Kurz-Definition:**
Netzwerksicherheit umfasst alle Maßnahmen zum Schutz des Netzwerks vor Bedrohungen: Firewall, Verschlüsselung, Authentifizierung, Zugriffskontrollen, Monitoring und Updates.

**Tabellarische Übersicht:**

| Sicherheitsmaßnahme | Beschreibung | Einsatz |
|---------------------|--------------|---------|
| **Firewall** | Paketfilterung, Zugriffskontrolle | Router, Server, Client |
| **Verschlüsselung** | Daten verschlüsseln | WPA2/WPA3 (WLAN), VPN, HTTPS |
| **Authentifizierung** | Benutzer identifizieren | Passwort, 2FA, Zertifikate |
| **Zugriffskontrollen** | Wer darf auf was zugreifen | ACLs, Benutzerrechte |
| **IDS/IPS** | Intrusion Detection/Prevention | Angriffserkennung |
| **Updates** | Sicherheitsupdates installieren | Betriebssystem, Software |
| **Monitoring** | Überwachung von Traffic, Logs | Früherkennung von Angriffen |

| Bedrohung | Schutzmaßnahme |
|-----------|----------------|
| **Viren/Malware** | Antivirus, Firewall, Updates |
| **Hacking** | Firewall, IDS/IPS, starke Passwörter |
| **Man-in-the-Middle** | Verschlüsselung (HTTPS, VPN) |
| **DDoS** | Firewall, Traffic-Filterung |
| **Phishing** | Schulungen, Awareness |
| **Unbefugter Zugriff** | Authentifizierung, Zugriffskontrollen |

| Verschlüsselungsstandard | Einsatz | Sicherheit |
|--------------------------|---------|------------|
| **WPA2** | WLAN | Gut (Standard) |
| **WPA3** | WLAN | Sehr gut (neu) |
| **AES** | Datenverschlüsselung | Sehr gut |
| **TLS/SSL** | HTTPS, VPN | Sehr gut |

**Visuelle Darstellung:**
```
Netzwerksicherheit - Mehrschichtiger Schutz:

Schicht 1: Firewall
    → Paketfilterung, Zugriffskontrolle

Schicht 2: Verschlüsselung
    → WPA2/WPA3 (WLAN), VPN, HTTPS

Schicht 3: Authentifizierung
    → Passwort, 2FA, Zertifikate

Schicht 4: Zugriffskontrollen
    → ACLs, Benutzerrechte

Schicht 5: Monitoring
    → IDS/IPS, Log-Analyse

Schicht 6: Updates
    → Sicherheitspatches

Bedrohungen → Schutzmaßnahmen:
    Viren/Malware → Antivirus, Firewall
    Hacking → Firewall, IDS/IPS
    Man-in-the-Middle → Verschlüsselung
    DDoS → Firewall, Filterung
```

**Praxis-Beispiel:**
Mehrschichtige Sicherheit im Unternehmen:
- **Firewall:** Router-Firewall blockiert unerwünschten Traffic, erlaubt nur Port 80/443 (HTTP/HTTPS)
- **Verschlüsselung:** WLAN mit WPA3, VPN für Remote-Zugriff, HTTPS für Web-Zugriff
- **Authentifizierung:** Domain-Anmeldung, 2FA für wichtige Systeme, Zertifikate für Server
- **Zugriffskontrollen:** Benutzerrechte, ACLs auf Dateiserver, Least Privilege
- **Monitoring:** IDS überwacht Netzwerk, Alerts bei verdächtigem Traffic, Log-Analyse
- **Updates:** Automatische Windows-Updates, monatliche Sicherheitspatches, regelmäßige Software-Updates

**Prüfungscheck:**
**Frage:** Welche Maßnahmen sind wichtig für die Netzwerksicherheit?

**Antwort:**
Wichtige Sicherheitsmaßnahmen:
1. **Firewall:** Paketfilterung, Zugriffskontrollen (Router, Server, Client)
2. **Verschlüsselung:** WPA2/WPA3 (WLAN), VPN, HTTPS
3. **Starke Authentifizierung:** Komplexe Passwörter, 2FA/MFA
4. **Zugriffskontrollen:** ACLs, Benutzerrechte, Least Privilege
5. **Updates:** Regelmäßige Sicherheitsupdates (Betriebssystem, Software)
6. **Antivirus/Antimalware:** Schutz vor Schadsoftware
7. **Monitoring/Logging:** Überwachung von Traffic, Logs auswerten
8. **IDS/IPS:** Intrusion Detection/Prevention Systeme
9. **Schulungen:** Awareness für Benutzer (Phishing, Social Engineering)
10. **Backups:** Regelmäßige Backups für Wiederherstellung

**Merksatz:**
"Sicherheit = Firewall + Verschlüsselung + Authentifizierung + Updates + Monitoring - mehrschichtig schützen!"

---

### 3.8.4: Verfügbarkeit und Ausfallzeiten von IT-Systemen berechnen

**Kurz-Definition:**
Verfügbarkeit ist der Prozentsatz der Zeit, in der ein System funktionsfähig ist. Ausfallzeiten sind die Zeiten, in denen das System nicht verfügbar ist. Berechnet wird dies basierend auf Betriebszeit und Gesamtzeit.

**Tabellarische Übersicht:**

| Begriff | Formel | Beispiel |
|---------|--------|----------|
| **Verfügbarkeit** | (Betriebszeit ÷ Gesamtzeit) × 100% | (365 Tage - 1 Tag) ÷ 365 × 100% = 99,73% |
| **Ausfallzeit** | Gesamtzeit - Betriebszeit | 365 Tage - 364 Tage = 1 Tag |
| **MTBF** | Mean Time Between Failures | Durchschnittliche Zeit zwischen Ausfällen |
| **MTTR** | Mean Time To Repair | Durchschnittliche Reparaturzeit |

| Verfügbarkeit | Ausfallzeit/Jahr | Beschreibung |
|---------------|------------------|--------------|
| **99%** | 3,65 Tage | Einfach |
| **99,9%** | 8,76 Stunden | Gut |
| **99,99%** | 52,56 Minuten | Sehr gut |
| **99,999%** | 5,26 Minuten | Hochverfügbar |
| **99,9999%** | 31,5 Sekunden | Kritische Systeme |

| Verfügbarkeitsfaktor | Maßnahme | Verbesserung |
|---------------------|----------|--------------|
| **Redundanz** | Doppelte Komponenten | Höhere Verfügbarkeit |
| **Backups** | Regelmäßige Sicherungen | Schnellere Wiederherstellung |
| **Monitoring** | Früherkennung | Weniger Ausfälle |
| **Wartung** | Präventive Maßnahmen | Weniger Ausfälle |

**Visuelle Darstellung:**
```
Verfügbarkeitsberechnung:

Formel:
    Verfügbarkeit = (Betriebszeit ÷ Gesamtzeit) × 100%

Beispiel:
    Gesamtzeit: 365 Tage × 24 h = 8.760 Stunden
    Ausfallzeit: 4 Stunden
    Betriebszeit: 8.760 - 4 = 8.756 Stunden
    Verfügbarkeit: (8.756 ÷ 8.760) × 100% = 99,954%

Verfügbarkeitsstufen:
    99% → 3,65 Tage Ausfall/Jahr
    99,9% → 8,76 Stunden Ausfall/Jahr
    99,99% → 52,56 Minuten Ausfall/Jahr
    99,999% → 5,26 Minuten Ausfall/Jahr

Verbesserung:
    Redundanz → Höhere Verfügbarkeit
    Backups → Schnellere Wiederherstellung
    Monitoring → Früherkennung
```

**Praxis-Beispiel:**
Verfügbarkeitsberechnung und -verbesserung:
- **Server 2023:** 4 Stunden Ausfallzeit → Verfügbarkeit: 99,954% (sehr gut)
- **Ziel:** 99,9% Verfügbarkeit → Maximal 8,76 Stunden Ausfall/Jahr erlaubt
- **Verbesserung:** Redundante Server (Failover), USV für Stromausfälle, Monitoring für Früherkennung
- **Ergebnis:** Nach Verbesserungen nur noch 2 Stunden Ausfallzeit → 99,977% Verfügbarkeit
- **Vergleich:** Tier III Rechenzentrum hat 99,98% Verfügbarkeit (N+1 Redundanz)

**Prüfungscheck:**
**Frage:** Ein Server hat im Jahr 2023 insgesamt 4 Stunden Ausfallzeit. Wie hoch ist die Verfügbarkeit?

**Antwort:**
Berechnung:
- **Gesamtzeit:** 365 Tage × 24 Stunden = 8.760 Stunden
- **Ausfallzeit:** 4 Stunden
- **Betriebszeit:** 8.760 Stunden - 4 Stunden = 8.756 Stunden
- **Verfügbarkeit:** (8.756 ÷ 8.760) × 100% = **99,954%**

**Ausfallzeit in verschiedenen Einheiten:**
- 4 Stunden = 240 Minuten = 14.400 Sekunden

**Merksatz:**
"Verfügbarkeit = (Betriebszeit ÷ Gesamtzeit) × 100% - höher ist besser, 99,9% = gut!"

---

## 3.9: Geräte mit Strom versorgen

### 3.9.1: Stromversorgung allgemein

**Kurz-Definition:**
Die Stromversorgung von Netzwerkgeräten umfasst die Bereitstellung von elektrischer Energie. Wichtige Aspekte sind Spannung, Leistung, Redundanz (USV), Effizienz und Sicherheit.

**Tabellarische Übersicht:**

| Aspekt | Beschreibung | Wichtig für |
|---------|--------------|-------------|
| **Spannung** | 230V (Europa), 110V (USA) | Kompatibilität |
| **Leistung** | Watt (W), Verbrauch | Dimensionierung |
| **Stromstärke** | Ampere (A) | Kabeldimensionierung |
| **USV** | Unterbrechungsfreie Stromversorgung | Ausfallschutz |
| **Redundanz** | Doppelte Stromversorgung | Hochverfügbarkeit |
| **Effizienz** | Wirkungsgrad (80 Plus) | Energiekosten |

| Gerät | Typischer Verbrauch | Anmerkung |
|-------|---------------------|-----------|
| **Client (PC)** | 50-200 W | Je nach Ausstattung |
| **Laptop** | 20-100 W | Mit Akku |
| **Switch** | 10-50 W | Je nach Port-Anzahl |
| **Router** | 5-30 W | Je nach Typ |
| **Server** | 100-500 W+ | Je nach Ausstattung |

| USV-Typ | Beschreibung | Einsatz |
|---------|--------------|---------|
| **Offline/Standby** | Schaltet bei Ausfall ein | Einfache Anwendungen |
| **Line-Interactive** | Spannungsregelung | Standard |
| **Online/Double-Conversion** | Kontinuierliche Umwandlung | Kritische Systeme |

| 80 Plus Zertifizierung | Wirkungsgrad bei 50% Last | Energieeffizienz |
|------------------------|---------------------------|------------------|
| **80 Plus** | 80% | Basis |
| **80 Plus Bronze** | 82% | Gut |
| **80 Plus Gold** | 87% | Sehr gut |
| **80 Plus Platinum** | 90% | Hervorragend |
| **80 Plus Titanium** | 92% | Beste |

**Visuelle Darstellung:**
```
Stromversorgung für Netzwerkgeräte:

Netzstrom (230V)
         ↓
    USV (Unterbrechungsfreie Stromversorgung)
         ↓
    Geräte (Server, Switch, Router)

USV-Typen:
    Offline → Schaltet bei Ausfall ein
    Line-Interactive → Spannungsregelung
    Online → Kontinuierliche Umwandlung

Stromverbrauch:
    Client (PC): 50-200 W
    Laptop: 20-100 W
    Switch: 10-50 W
    Router: 5-30 W
    Server: 100-500 W+

Effizienz (80 Plus):
    80 Plus → 80% Wirkungsgrad
    80 Plus Gold → 87% Wirkungsgrad
    80 Plus Titanium → 92% Wirkungsgrad
```

**Praxis-Beispiel:**
Stromversorgung im Serverraum:
- **USV (Online):** 3000 VA USV für Server-Rack, kontinuierliche Umwandlung, beste Qualität, 30 Minuten Laufzeit bei Ausfall
- **Verbrauch:** Server (300 W), Switch (30 W), Router (20 W) = 350 W Gesamt
- **USV-Kapazität:** 3000 VA = ca. 2400 W, ausreichend für mehrere Geräte
- **Effizienz:** 80 Plus Gold Netzteile (87% Wirkungsgrad), spart Energiekosten
- **Redundanz:** Doppelte USV für kritische Server, Ausfallsicherheit

**Prüfungscheck:**
**Frage:** Warum ist eine USV (Unterbrechungsfreie Stromversorgung) wichtig für Netzwerkgeräte?

**Antwort:**
USV ist wichtig, weil:
1. **Ausfallschutz:** Verhindert Datenverlust bei Stromausfall
2. **Geordnetes Herunterfahren:** Zeit für sauberes Shutdown von Servern
3. **Spannungsschwankungen:** Schützt vor Überspannung, Unterspannung
4. **Kontinuierlicher Betrieb:** Kritische Systeme bleiben online
5. **Datenintegrität:** Verhindert Korruption durch abruptes Abschalten

**USV-Typen:**
- **Offline:** Schaltet bei Ausfall ein (günstig, kurze Umschaltzeit)
- **Line-Interactive:** Spannungsregelung, bessere Qualität
- **Online:** Kontinuierliche Umwandlung, beste Qualität (teuer)

**Merksatz:**
"USV = Ausfallschutz + geordnetes Shut