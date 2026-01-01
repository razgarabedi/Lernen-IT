# Kapitel 5: Software zur Verwaltung von Daten anpassen

## 5: Software zur Verwaltung von Daten anpassen

**Kurz-Definition:**
Die Anpassung von Software zur Datenverwaltung umfasst die Modifikation, Erweiterung oder Neuentwicklung von Anwendungen, um spezifische Anforderungen an die Datenspeicherung, -verarbeitung und -verwaltung zu erfüllen.

**Tabellarische Übersicht:**

| Aspekt | Beschreibung | Bedeutung |
|--------|--------------|-----------|
| **Anpassung bestehender Software** | Konfiguration, Parametrisierung, Customizing | Schnelle Lösung, geringere Kosten |
| **Erweiterung** | Plugins, Module, Add-ons hinzufügen | Funktionalität erweitern |
| **Neuentwicklung** | Individuelle Software erstellen | Maximale Flexibilität |
| **Datenverwaltung** | Speicherung, Abfrage, Aktualisierung, Löschung | Kernfunktionalität |
| **Integration** | Verbindung mit anderen Systemen | Datenfluss sicherstellen |

**Visuelle Darstellung:**
```
[Bestandssoftware] → [Anpassung] → [Angepasste Software]
         ↓                ↓                ↓
    [Standard]    [Konfiguration]    [Individuell]
    [Plugins]     [Customizing]      [Neu entwickelt]
```

**Praxis-Beispiel:**
Ein Unternehmen nutzt eine Standard-CRM-Software, benötigt aber eine spezielle Funktion zur automatischen Erstellung von Angeboten basierend auf Kundendaten. Die Software wird durch ein individuelles Modul erweitert, das die vorhandenen Kundendaten nutzt und neue Funktionen hinzufügt.

**Prüfungscheck:**
**Frage:** Welche drei Hauptmöglichkeiten gibt es, Software zur Datenverwaltung anzupassen?

**Antwort:**
1. **Konfiguration/Parametrisierung:** Einstellungen in der Software ändern, ohne Code zu modifizieren
2. **Erweiterung:** Plugins, Module oder Add-ons hinzufügen, um Funktionalität zu erweitern
3. **Neuentwicklung:** Individuelle Software von Grund auf erstellen, wenn Standardlösungen nicht ausreichen

**Merksatz:**
"Software anpassen = Konfigurieren, Erweitern oder Neuentwickeln - je nach Anforderung!"

---

## 5.1: Das Umfeld der Softwareentwicklung analysieren

**Kurz-Definition:**
Die Analyse des Umfelds der Softwareentwicklung umfasst das Verstehen der verschiedenen Softwaretypen, Anpassungsmöglichkeiten sowie der Rollen und Kompetenzen von Softwareentwicklern im Entwicklungsprozess.

**Tabellarische Übersicht:**

| Aspekt | Beschreibung | Relevanz |
|--------|--------------|----------|
| **Softwaretypen** | System-, Anwendungs-, Standard-, Individualsoftware | Grundverständnis |
| **Anpassungsmöglichkeiten** | Konfiguration, Customizing, Programmierung | Flexibilität |
| **Entwicklerrollen** | Frontend, Backend, Full-Stack, DevOps | Teamstruktur |
| **Kompetenzen** | Programmierung, Datenbanken, Testing, Dokumentation | Qualifikation |

**Visuelle Darstellung:**
```
Softwareentwicklungsumfeld
    ├── Softwaretypen
    │   ├── Systemsoftware
    │   ├── Anwendungssoftware
    │   └── Standard vs. Individual
    ├── Anpassungsmöglichkeiten
    │   ├── Konfiguration
    │   ├── Customizing
    │   └── Programmierung
    └── Entwickler
        ├── Rollen
        └── Kompetenzen
```

**Praxis-Beispiel:**
Ein mittelständisches Unternehmen analysiert sein Softwareumfeld: Es nutzt Standard-Buchhaltungssoftware (konfiguriert), eine individuelle Lagerverwaltung (neu entwickelt) und erweitert die CRM-Software durch Customizing. Das Entwicklungsteam besteht aus Frontend-Entwicklern (UI), Backend-Entwicklern (Datenbank) und einem Full-Stack-Entwickler für Integrationen.

**Prüfungscheck:**
**Frage:** Was umfasst die Analyse des Umfelds der Softwareentwicklung?

**Antwort:**
Die Analyse umfasst:
1. **Softwaretypen verstehen:** Systemsoftware, Anwendungssoftware, Standard- vs. Individualsoftware
2. **Anpassungsmöglichkeiten kennen:** Konfiguration, Customizing, Programmierung
3. **Entwicklerrollen definieren:** Frontend, Backend, Full-Stack, DevOps
4. **Kompetenzen ermitteln:** Programmiersprachen, Datenbanken, Testing, Dokumentation

**Merksatz:**
"Umfeld analysieren = Softwaretypen + Anpassungen + Rollen + Kompetenzen verstehen!"

---

### 5.1.1: Software und Möglichkeiten der Anpassung unterscheiden

**Kurz-Definition:**
Software kann nach verschiedenen Kriterien klassifiziert werden (System- vs. Anwendungssoftware, Standard- vs. Individualsoftware), und es gibt unterschiedliche Anpassungsmöglichkeiten von einfacher Konfiguration bis hin zur vollständigen Neuentwicklung.

**Tabellarische Übersicht:**

| Softwaretyp | Beschreibung | Beispiele | Anpassungsgrad |
|-------------|--------------|-----------|----------------|
| **Systemsoftware** | Verwaltet Hardware und Basis-Funktionen | Betriebssystem, Treiber | Sehr gering |
| **Anwendungssoftware** | Erfüllt spezifische Aufgaben | Office, CRM, ERP | Mittel bis hoch |
| **Standardsoftware** | Vorgefertigte Lösung für viele Nutzer | Microsoft Office, SAP | Konfiguration, Customizing |
| **Individualsoftware** | Speziell für einen Kunden entwickelt | Eigene Web-App, spezifische Tools | Vollständig anpassbar |

| Anpassungsmethode | Beschreibung | Aufwand | Flexibilität |
|-------------------|--------------|---------|--------------|
| **Konfiguration** | Einstellungen ändern (Menüs, Parameter) | Niedrig | Gering |
| **Parametrisierung** | Vordefinierte Optionen nutzen | Niedrig | Gering |
| **Customizing** | Anpassung durch Konfiguration + kleine Änderungen | Mittel | Mittel |
| **Erweiterung** | Plugins, Module, Add-ons hinzufügen | Mittel | Mittel-Hoch |
| **Programmierung** | Code schreiben, Funktionen entwickeln | Hoch | Sehr hoch |
| **Neuentwicklung** | Komplette Software neu erstellen | Sehr hoch | Maximal |

**Visuelle Darstellung:**
```
Software-Klassifikation
    ├── Nach Funktion
    │   ├── Systemsoftware (OS, Treiber)
    │   └── Anwendungssoftware (Office, CRM)
    │
    └── Nach Individualität
        ├── Standardsoftware (vorgefertigt)
        └── Individualsoftware (maßgeschneidert)

Anpassungsmöglichkeiten (steigender Aufwand)
    Konfiguration → Parametrisierung → Customizing → Erweiterung → Programmierung → Neuentwicklung
    (niedrig)      (niedrig)          (mittel)      (mittel)      (hoch)          (sehr hoch)
```

**Praxis-Beispiel:**
Ein Unternehmen nutzt:
- **Standardsoftware (konfiguriert):** Microsoft Excel mit angepassten Vorlagen und Makros
- **Standardsoftware (customized):** SAP ERP mit individuellen Workflows und Reports
- **Individualsoftware:** Eigene Web-Anwendung zur Verwaltung von Projektdaten, vollständig programmiert

**Prüfungscheck:**
**Frage:** Nennen Sie drei Anpassungsmethoden für Software und ordnen Sie sie nach steigendem Aufwand.

**Antwort:**
1. **Konfiguration/Parametrisierung:** Niedrigster Aufwand, nur Einstellungen ändern
2. **Customizing/Erweiterung:** Mittlerer Aufwand, Plugins oder Module hinzufügen
3. **Programmierung/Neuentwicklung:** Höchster Aufwand, Code schreiben oder komplett neu entwickeln

**Merksatz:**
"Software anpassen: Konfiguration < Customizing < Programmierung - Aufwand steigt mit Flexibilität!"

---

### 5.1.2: Aufgaben und Kompetenzen von Softwareentwicklern beschreiben

**Kurz-Definition:**
Softwareentwickler übernehmen verschiedene Rollen im Entwicklungsprozess und benötigen spezifische Kompetenzen in Programmierung, Datenbanken, Testing und Projektmanagement, um qualitativ hochwertige Software zu erstellen.

**Tabellarische Übersicht:**

| Entwicklerrolle | Hauptaufgaben | Technologien | Verantwortung |
|-----------------|--------------|--------------|---------------|
| **Frontend-Entwickler** | Benutzeroberfläche, UI/UX | HTML, CSS, JavaScript, React, Vue | Darstellung, Interaktion |
| **Backend-Entwickler** | Server, Datenbank, API | Java, Python, PHP, SQL, Node.js | Logik, Datenverarbeitung |
| **Full-Stack-Entwickler** | Frontend + Backend | Kombination beider Bereiche | Komplette Anwendung |
| **DevOps-Engineer** | Deployment, Infrastruktur | Docker, Kubernetes, CI/CD | Betrieb, Automatisierung |
| **Datenbankentwickler** | Datenbankdesign, Optimierung | SQL, NoSQL, Datenmodellierung | Datenstrukturen |
| **Test-Engineer** | Qualitätssicherung, Testing | Test-Frameworks, Automatisierung | Fehlerfindung |

| Kompetenzbereich | Beschreibung | Beispiele |
|------------------|--------------|-----------|
| **Programmierung** | Code schreiben, Algorithmen | Sprachen: Java, Python, C#, JavaScript |
| **Datenbanken** | Datenmodellierung, SQL, NoSQL | MySQL, PostgreSQL, MongoDB |
| **Software-Architektur** | Systemdesign, Patterns | MVC, Microservices, REST |
| **Testing** | Unit-Tests, Integrationstests | JUnit, Selenium, Test-Driven Development |
| **Versionskontrolle** | Code-Verwaltung, Zusammenarbeit | Git, SVN, Branching-Strategien |
| **Dokumentation** | Code, APIs, Handbücher | Javadoc, API-Docs, README |
| **Projektmanagement** | Agile, Scrum, Kanban | Sprint-Planning, Retrospektiven |
| **Problemlösung** | Debugging, Analyse | Logging, Profiling, Fehleranalyse |

**Visuelle Darstellung:**
```
Softwareentwickler-Team
    ├── Frontend-Entwickler
    │   └── UI/UX, Client-seitige Logik
    ├── Backend-Entwickler
    │   └── Server, Datenbank, API
    ├── Full-Stack-Entwickler
    │   └── Frontend + Backend
    ├── DevOps-Engineer
    │   └── Deployment, Infrastruktur
    ├── Datenbankentwickler
    │   └── Datenmodellierung, Optimierung
    └── Test-Engineer
        └── Qualitätssicherung

Kompetenzen
    ├── Technisch: Programmierung, Datenbanken, Architektur
    ├── Methodisch: Testing, Versionskontrolle, Dokumentation
    └── Sozial: Teamarbeit, Kommunikation, Problemlösung
```

**Praxis-Beispiel:**
Ein Entwicklungsteam arbeitet an einer E-Commerce-Plattform:
- **Frontend-Entwickler:** Erstellt die Benutzeroberfläche mit React, sorgt für responsive Design
- **Backend-Entwickler:** Entwickelt REST-APIs mit Java Spring, verwaltet Bestellungen
- **Datenbankentwickler:** Entwirft das Datenmodell für Produkte, Kunden, Bestellungen
- **Test-Engineer:** Schreibt automatisierte Tests, führt Integrationstests durch
- **DevOps-Engineer:** Konfiguriert CI/CD-Pipeline, verwaltet Server-Infrastruktur

**Prüfungscheck:**
**Frage:** Welche Hauptaufgaben hat ein Backend-Entwickler und welche Kompetenzen benötigt er?

**Antwort:**
**Hauptaufgaben:**
- Entwicklung von Server-seitiger Logik
- Datenbankanbindung und -abfragen
- Erstellung von APIs (REST, GraphQL)
- Sicherheit und Authentifizierung
- Performance-Optimierung

**Benötigte Kompetenzen:**
- Programmiersprachen (Java, Python, PHP, Node.js)
- Datenbanken (SQL, NoSQL)
- API-Design
- Server-Architektur
- Sicherheitskonzepte

**Merksatz:**
"Entwickler = Rolle + Kompetenzen - Frontend (UI), Backend (Logik), Full-Stack (beides)!"

---

## 5.2: Grundlagen zur Verwaltung von Daten in IT-Systemen erläutern

**Kurz-Definition:**
Die Verwaltung von Daten in IT-Systemen umfasst das Verstehen von Datenstrukturen, deren Digitalisierung, Speicherung, Verarbeitung und Sicherheit, um Informationen effizient und sicher zu handhaben.

**Tabellarische Übersicht:**

| Aspekt | Beschreibung | Bedeutung |
|--------|--------------|-----------|
| **Daten vs. Informationen** | Rohdaten vs. interpretierte Daten | Grundverständnis |
| **Datenarten** | Strukturiert, unstrukturiert, halbstrukturiert | Klassifikation |
| **Digitalisierung** | Umwandlung in binäre Form | Zahlensysteme |
| **Speicherung** | Dateiformate, Datenbanken | Persistenz |
| **Sicherheit** | Vertraulichkeit, Integrität, Verfügbarkeit | Schutz |

**Visuelle Darstellung:**
```
Datenverwaltung in IT-Systemen
    ├── Datenverständnis
    │   ├── Daten vs. Informationen
    │   └── Datenarten
    ├── Digitalisierung
    │   ├── Zahlensysteme (Binär, Hexadezimal)
    │   └── Codierung
    ├── Speicherung
    │   ├── Dateiformate
    │   └── Datenbanken
    └── Sicherheit
        ├── Vertraulichkeit
        ├── Integrität
        └── Verfügbarkeit
```

**Praxis-Beispiel:**
Ein Unternehmen verwaltet Kundendaten: Die Rohdaten (Name, Adresse, Telefonnummer) werden in strukturierter Form in einer Datenbank gespeichert, digitalisiert (ASCII/UTF-8), in verschiedenen Formaten exportiert (CSV, JSON) und durch Verschlüsselung und Backups gesichert.

**Prüfungscheck:**
**Frage:** Welche Hauptaspekte umfasst die Verwaltung von Daten in IT-Systemen?

**Antwort:**
1. **Datenverständnis:** Unterschied zwischen Daten und Informationen, Klassifikation von Datenarten
2. **Digitalisierung:** Umwandlung in binäre Form, Zahlensysteme, Codierung
3. **Speicherung:** Dateiformate, Datenbankstrukturen, Persistenz
4. **Sicherheit:** Vertraulichkeit (Verschlüsselung), Integrität (Prüfsummen), Verfügbarkeit (Backups)

**Merksatz:**
"Datenverwaltung = Verstehen + Digitalisieren + Speichern + Sichern!"

---

### 5.2.1: Informationen und Daten unterscheiden

**Kurz-Definition:**
Daten sind rohe, unverarbeitete Fakten und Zeichen ohne Kontext, während Informationen interpretierte, strukturierte und in einen Kontext gesetzte Daten sind, die für den Empfänger bedeutsam und nutzbar sind.

**Tabellarische Übersicht:**

| Aspekt | Daten | Informationen |
|--------|-------|---------------|
| **Definition** | Rohdaten, Zeichen, Symbole | Interpretierte, kontextbezogene Daten |
| **Struktur** | Unstrukturiert, roh | Strukturiert, organisiert |
| **Bedeutung** | Keine eigene Bedeutung | Hat Bedeutung im Kontext |
| **Verarbeitung** | Noch nicht verarbeitet | Verarbeitet und aufbereitet |
| **Nutzen** | Allein nicht nutzbar | Direkt nutzbar für Entscheidungen |
| **Beispiel** | "25", "Berlin", "2024" | "25 Jahre alt, wohnhaft in Berlin, Stand 2024" |

| Merkmal | Daten | Informationen |
|---------|-------|---------------|
| **Kontext** | Fehlt | Vorhanden |
| **Interpretation** | Nicht interpretiert | Interpretiert |
| **Wert** | Niedrig (roh) | Hoch (verarbeitet) |
| **Abhängigkeit** | Unabhängig | Abhängig von Daten |
| **Verwendung** | Input für Verarbeitung | Output, nutzbar |

**Visuelle Darstellung:**
```
Daten → Verarbeitung → Informationen
  ↓           ↓              ↓
Rohdaten   Kontext      Bedeutsam
Zeichen    Struktur     Nutzbar
Symbole    Interpretation Entscheidungsgrundlage

Beispiel:
Daten: "25", "Berlin", "2024"
    ↓ (Verarbeitung + Kontext)
Information: "Person ist 25 Jahre alt, wohnhaft in Berlin, Stand 2024"
```

**Praxis-Beispiel:**
- **Daten:** Eine Tabelle mit Zahlen: 25, 30, 28, 32, 27
- **Information:** "Das Durchschnittsalter der Mitarbeiter beträgt 28,4 Jahre. Die Altersspanne liegt zwischen 25 und 32 Jahren."

Die Daten (Zahlen) werden durch Berechnung und Interpretation zu einer nutzbaren Information.

**Prüfungscheck:**
**Frage:** Erklären Sie den Unterschied zwischen Daten und Informationen anhand eines Beispiels.

**Antwort:**
**Daten** sind rohe, unverarbeitete Fakten ohne Kontext (z.B. "25", "Berlin", "2024").

**Informationen** sind interpretierte, strukturierte Daten mit Kontext und Bedeutung (z.B. "Person ist 25 Jahre alt, wohnhaft in Berlin, Stand 2024").

**Unterschied:** Daten haben keine eigene Bedeutung und sind erst nach Verarbeitung und Kontextualisierung nutzbar. Informationen sind bereits verarbeitet, haben Bedeutung und können direkt für Entscheidungen genutzt werden.

**Merksatz:**
"Daten = Rohmaterial, Information = verarbeitet + kontextbezogen = nutzbar!"

---

### 5.2.2: Daten hinsichtlich ihrer Art und ihrer Herkunft vergleichen

**Kurz-Definition:**
Daten können nach ihrer Struktur (strukturiert, unstrukturiert, halbstrukturiert) und ihrer Herkunft (primär, sekundär, intern, extern) klassifiziert werden, was ihre Verarbeitung und Nutzung beeinflusst.

**Tabellarische Übersicht:**

| Datenart | Beschreibung | Struktur | Beispiele | Verarbeitung |
|----------|--------------|----------|-----------|--------------|
| **Strukturiert** | Klar definierte Struktur, Schema | Tabellarisch, relational | Datenbanken, CSV, Excel | Einfach, standardisiert |
| **Unstrukturiert** | Keine feste Struktur | Frei, variabel | Texte, Bilder, Videos, Audio | Komplex, spezielle Tools |
| **Halbstrukturiert** | Teilweise strukturiert | Flexibel, Tags/Markup | JSON, XML, HTML, E-Mails | Mittel, Parser nötig |

| Herkunft | Beschreibung | Beispiele | Qualität | Verfügbarkeit |
|----------|--------------|-----------|----------|---------------|
| **Primär** | Direkt erhoben, original | Umfragen, Messungen, Beobachtungen | Hoch, kontrollierbar | Abhängig von Erhebung |
| **Sekundär** | Bereits vorhanden, weiterverwendet | Statistiken, Berichte, Studien | Variabel, prüfen nötig | Oft verfügbar |
| **Intern** | Aus eigenem Unternehmen | Kunden-DB, Vertriebsdaten, HR | Bekannt, vertrauenswürdig | Direkt verfügbar |
| **Extern** | Von außerhalb | Marktforschung, APIs, öffentliche Daten | Prüfung nötig | Abhängig von Quelle |

| Vergleichskriterium | Strukturiert | Unstrukturiert | Halbstrukturiert |
|---------------------|--------------|----------------|------------------|
| **Speicherung** | Datenbanken, Tabellen | Dateien, Objektspeicher | Dateien, NoSQL |
| **Abfrage** | SQL, einfach | Komplex, Volltextsuche | Parser, XPath, JSON-Query |
| **Analyse** | Standard-Tools | KI, NLP, Bilderkennung | Spezialisierte Tools |
| **Volumen** | Meist klein-mittel | Sehr groß | Mittel-groß |

**Visuelle Darstellung:**
```
Datenklassifikation
    ├── Nach Struktur
    │   ├── Strukturiert (Tabellen, DB)
    │   ├── Unstrukturiert (Texte, Bilder)
    │   └── Halbstrukturiert (JSON, XML)
    │
    └── Nach Herkunft
        ├── Primär (direkt erhoben)
        ├── Sekundär (weiterverwendet)
        ├── Intern (eigenes Unternehmen)
        └── Extern (von außen)

Beispiel-Matrix:
                Strukturiert    Unstrukturiert    Halbstrukturiert
Primär/Intern   Kundendaten     E-Mails          JSON-Logs
Primär/Extern   Umfragen        Social Media     API-Responses
Sekundär/Intern Reports         Dokumente        XML-Exports
Sekundär/Extern Statistiken     Web-Inhalte      RSS-Feeds
```

**Praxis-Beispiel:**
Ein E-Commerce-Unternehmen nutzt:
- **Strukturiert, primär, intern:** Kundendatenbank mit Namen, Adressen, Bestellungen (SQL-Datenbank)
- **Unstrukturiert, primär, intern:** Kundenbewertungen als Freitext, Produktbilder
- **Halbstrukturiert, primär, extern:** JSON-Daten von Lieferanten-APIs
- **Strukturiert, sekundär, extern:** Marktstatistiken von Branchenverbänden

**Prüfungscheck:**
**Frage:** Vergleichen Sie strukturierte und unstrukturierte Daten hinsichtlich Struktur, Speicherung und Verarbeitung.

**Antwort:**
**Strukturierte Daten:**
- **Struktur:** Klar definiert, tabellarisch, Schema vorhanden
- **Speicherung:** Relationale Datenbanken, CSV, Excel
- **Verarbeitung:** Einfach, SQL-Abfragen, Standard-Tools

**Unstrukturierte Daten:**
- **Struktur:** Keine feste Struktur, frei, variabel
- **Speicherung:** Dateisystem, Objektspeicher, NoSQL
- **Verarbeitung:** Komplex, benötigt spezielle Tools (NLP, Bilderkennung, KI)

**Merksatz:**
"Datenarten: Strukturiert (Tabellen) < Halbstrukturiert (JSON/XML) < Unstrukturiert (Texte/Bilder) - Komplexität steigt!"

---

### 5.2.3: Zahlensysteme für die Digitalisierung von Daten beschreiben und umrechnen

**Kurz-Definition:**
Zahlensysteme (Dezimal, Binär, Hexadezimal) dienen der Darstellung von Zahlen in verschiedenen Basen. Die Digitalisierung von Daten erfolgt durch Umwandlung in das Binärsystem (0 und 1), das Grundlage aller digitalen Systeme ist.

**Tabellarische Übersicht:**

| Zahlensystem | Basis | Ziffern | Verwendung | Beispiel |
|--------------|-------|---------|------------|----------|
| **Dezimal** | 10 | 0-9 | Menschen, Alltag | 255 |
| **Binär** | 2 | 0, 1 | Computer, Digitalisierung | 11111111 |
| **Hexadezimal** | 16 | 0-9, A-F | Programmierung, kompakte Darstellung | FF |
| **Oktal** | 8 | 0-7 | Selten, historisch | 377 |

| Umrechnung | Methode | Beispiel |
|------------|---------|----------|
| **Dezimal → Binär** | Division durch 2, Reste von unten nach oben | 10 → 1010 |
| **Binär → Dezimal** | Potenzen von 2 addieren | 1010 → 10 |
| **Dezimal → Hexadezimal** | Division durch 16, Reste (0-9, A-F) | 255 → FF |
| **Hexadezimal → Dezimal** | Potenzen von 16 addieren | FF → 255 |
| **Binär → Hexadezimal** | Gruppen zu 4 Bits, jede Gruppe = 1 Hex-Ziffer | 11111111 → FF |
| **Hexadezimal → Binär** | Jede Hex-Ziffer = 4 Bits | FF → 11111111 |

| Bit-Gruppen | Dezimal | Hexadezimal | Bedeutung |
|-------------|---------|-------------|-----------|
| **4 Bits (Nibble)** | 0-15 | 0-F | Halbes Byte |
| **8 Bits (Byte)** | 0-255 | 00-FF | Ein Zeichen (ASCII) |
| **16 Bits (Word)** | 0-65535 | 0000-FFFF | Zwei Bytes |
| **32 Bits (DWord)** | 0-4294967295 | 00000000-FFFFFFFF | Vier Bytes |

**Visuelle Darstellung:**
```
Zahlensysteme-Hierarchie
    Dezimal (Basis 10) ← Menschen
         ↕ Umrechnung
    Hexadezimal (Basis 16) ← Kompakte Darstellung
         ↕ Umrechnung
    Binär (Basis 2) ← Computer (Hardware)

Umrechnung Dezimal → Binär (Beispiel: 10)
    10 : 2 = 5 Rest 0  ← LSB (Least Significant Bit)
     5 : 2 = 2 Rest 1
     2 : 2 = 1 Rest 0
     1 : 2 = 0 Rest 1  ← MSB (Most Significant Bit)
    Ergebnis: 1010

Umrechnung Binär → Dezimal (Beispiel: 1010)
    1×2³ + 0×2² + 1×2¹ + 0×2⁰
    = 8 + 0 + 2 + 0
    = 10

Hexadezimal ↔ Binär (Beispiel: FF)
    F = 1111, F = 1111
    FF = 11111111 = 255
```

**Praxis-Beispiel:**
Ein Textzeichen "A" wird digitalisiert:
1. **ASCII-Code:** "A" = 65 (dezimal)
2. **Binär:** 65 = 01000001 (8 Bits = 1 Byte)
3. **Hexadezimal:** 65 = 41 (kompakte Darstellung)
4. Im Computer wird "A" als 01000001 gespeichert

**Prüfungscheck:**
**Frage:** Rechnen Sie die Dezimalzahl 42 in Binär und Hexadezimal um.

**Antwort:**
**Dezimal → Binär (42):**
```
42 : 2 = 21 Rest 0
21 : 2 = 10 Rest 1
10 : 2 =  5 Rest 0
 5 : 2 =  2 Rest 1
 2 : 2 =  1 Rest 0
 1 : 2 =  0 Rest 1
```
Ergebnis: **101010** (von unten nach oben gelesen)

**Dezimal → Hexadezimal (42):**
```
42 : 16 = 2 Rest 10 (A)
 2 : 16 = 0 Rest 2
```
Ergebnis: **2A**

**Kontrolle:** 101010 (binär) = 32 + 8 + 2 = 42 ✓

**Merksatz:**
"Digitalisierung = Alles wird zu 0 und 1! Dezimal (10) → Binär (2) → Hexadezimal (16) für kompakte Darstellung!"

---

### 5.2.4: Darstellungsformen von Daten in IT-Systemen beschreiben

**Kurz-Definition:**
Daten werden in IT-Systemen in verschiedenen Darstellungsformen gespeichert und verarbeitet: als Zeichen (Text), Zahlen, Bilder, Audio, Video, wobei jede Form spezifische Codierungen und Formate verwendet.

**Tabellarische Übersicht:**

| Darstellungsform | Beschreibung | Codierung | Beispiele | Speicherung |
|------------------|--------------|-----------|-----------|-------------|
| **Text** | Zeichen, Buchstaben, Symbole | ASCII, UTF-8, Unicode | Dokumente, E-Mails | 1 Byte pro Zeichen (ASCII) |
| **Zahlen** | Numerische Werte | Binär, BCD, IEEE 754 | Ganzzahlen, Fließkomma | 1-8 Bytes je nach Typ |
| **Bilder** | Pixel, Rastergrafiken | RGB, CMYK, Kompression | JPEG, PNG, GIF | Abhängig von Auflösung |
| **Audio** | Schallwellen, digitalisiert | PCM, MP3, AAC | Musik, Sprache | Abhängig von Qualität |
| **Video** | Bewegtbild, Frames | H.264, MPEG, AVI | Filme, Aufnahmen | Sehr groß |
| **Strukturierte Daten** | Tabellen, Hierarchien | JSON, XML, CSV | Datenbanken, APIs | Variabel |

| Datentyp (Zahlen) | Größe | Wertebereich | Verwendung |
|-------------------|-------|--------------|------------|
| **Integer (int)** | 4 Bytes (32 Bit) | -2.147.483.648 bis 2.147.483.647 | Ganzzahlen |
| **Long** | 8 Bytes (64 Bit) | Sehr groß | Große Ganzzahlen |
| **Float** | 4 Bytes | ±3,4×10³⁸ | Fließkommazahlen |
| **Double** | 8 Bytes | ±1,7×10³⁰⁸ | Präzise Fließkommazahlen |
| **Boolean** | 1 Bit | true/false | Wahrheitswerte |
| **Char** | 1-4 Bytes | Zeichen | Einzelne Zeichen |

| Bildformate | Kompression | Qualität | Verwendung |
|-------------|------------|----------|------------|
| **JPEG** | Verlustbehaftet | Gut | Fotos |
| **PNG** | Verlustfrei | Sehr gut | Grafiken, Screenshots |
| **GIF** | Verlustfrei | Gut | Animationen, einfache Grafiken |
| **BMP** | Unkomprimiert | Sehr gut | Rohdaten, große Dateien |

**Visuelle Darstellung:**
```
Darstellungsformen in IT-Systemen
    ├── Text
    │   ├── ASCII (7 Bit, 128 Zeichen)
    │   ├── UTF-8 (1-4 Bytes, Unicode)
    │   └── Beispiel: "A" = 01000001
    │
    ├── Zahlen
    │   ├── Integer (Ganzzahlen)
    │   ├── Float (Fließkomma)
    │   └── Beispiel: 42 = 00101010
    │
    ├── Bilder
    │   ├── Pixel (RGB: Rot, Grün, Blau)
    │   ├── Auflösung (Breite × Höhe)
    │   └── Beispiel: 1920×1080 = 2.073.600 Pixel
    │
    ├── Audio
    │   ├── Abtastrate (Hz)
    │   ├── Bittiefe (Bits)
    │   └── Beispiel: 44.100 Hz, 16 Bit
    │
    └── Video
        ├── Frames (Bilder pro Sekunde)
        ├── Codec (Kompression)
        └── Beispiel: 30 fps, H.264

Codierungshierarchie:
    Daten → Codierung → Binär → Speicherung
    (Text/Zahl/Bild)  (ASCII/UTF-8)  (0/1)  (Datei/DB)
```

**Praxis-Beispiel:**
Ein Foto wird in einem IT-System gespeichert:
- **Darstellungsform:** Bild (Rastergrafik)
- **Auflösung:** 1920 × 1080 Pixel = 2.073.600 Pixel
- **Farbtiefe:** 24 Bit (RGB, je 8 Bit) = 16,7 Millionen Farben
- **Rohdaten:** 2.073.600 × 3 Bytes = 6.220.800 Bytes ≈ 6 MB
- **Kompression:** JPEG reduziert auf ca. 500 KB (ca. 92% Kompression)
- **Format:** JPEG-Datei (.jpg)

**Prüfungscheck:**
**Frage:** Erklären Sie die Darstellungsform "Text" in IT-Systemen und nennen Sie zwei wichtige Codierungen.

**Antwort:**
**Text-Darstellung:**
Text wird als Folge von Zeichen gespeichert, wobei jedes Zeichen durch einen numerischen Code repräsentiert wird.

**Wichtige Codierungen:**
1. **ASCII (American Standard Code for Information Interchange):**
   - 7 Bit, 128 Zeichen (0-127)
   - 1 Byte pro Zeichen
   - Beispiel: "A" = 65 = 01000001

2. **UTF-8 (Unicode Transformation Format 8-bit):**
   - Variable Länge (1-4 Bytes)
   - Unterstützt alle Unicode-Zeichen (über 1 Million)
   - Rückwärtskompatibel zu ASCII
   - Beispiel: "A" = 1 Byte, "€" = 3 Bytes

**Merksatz:**
"Datenformen: Text (ASCII/UTF-8), Zahlen (Integer/Float), Bilder (Pixel), Audio (Abtastung), Video (Frames)!"

---

### 5.2.5: Datenmengen bestimmen

**Kurz-Definition:**
Die Bestimmung von Datenmengen umfasst die Berechnung des Speicherbedarfs für verschiedene Datentypen, Dateien und Datenstrukturen unter Berücksichtigung von Einheiten (Bit, Byte, KB, MB, GB, TB) und Formeln.

**Tabellarische Übersicht:**

| Einheit | Abkürzung | Größe | Umrechnung | Beispiel |
|---------|-----------|-------|------------|----------|
| **Bit** | b | Kleinste Einheit | 1 Bit = 0 oder 1 | Ein Schalter |
| **Byte** | B | 8 Bits | 1 Byte = 8 Bits | Ein Zeichen (ASCII) |
| **Kilobyte** | KB | 1.024 Bytes | 1 KB = 2¹⁰ Bytes | Kleine Textdatei |
| **Megabyte** | MB | 1.024 KB | 1 MB = 2²⁰ Bytes | Foto, Lied |
| **Gigabyte** | GB | 1.024 MB | 1 GB = 2³⁰ Bytes | Film, viele Fotos |
| **Terabyte** | TB | 1.024 GB | 1 TB = 2⁴⁰ Bytes | Große Datenbanken |
| **Petabyte** | PB | 1.024 TB | 1 PB = 2⁵⁰ Bytes | Big Data |

| Datentyp | Größe | Berechnung | Beispiel |
|----------|-------|------------|----------|
| **Text (ASCII)** | 1 Byte pro Zeichen | Anzahl Zeichen × 1 Byte | "Hallo" = 5 Bytes |
| **Text (UTF-8)** | 1-4 Bytes pro Zeichen | Variabel | "Hallo" = 5 Bytes, "€" = 3 Bytes |
| **Integer (32 Bit)** | 4 Bytes | Immer 4 Bytes | Eine Zahl = 4 Bytes |
| **Float (32 Bit)** | 4 Bytes | Immer 4 Bytes | Eine Zahl = 4 Bytes |
| **Bild (unkomprimiert)** | Breite × Höhe × Farbtiefe | Pixel × Bytes pro Pixel | 1920×1080×3 = 6.220.800 Bytes |
| **Audio (unkomprimiert)** | Abtastrate × Bittiefe × Zeit × Kanäle | Hz × Bits × Sekunden × Kanäle | 44100×16×60×2 = 10.584.000 Bytes |

| Berechnungsformeln | Beschreibung |
|---------------------|--------------|
| **Text:** | Anzahl Zeichen × Bytes pro Zeichen |
| **Bild (unkomprimiert):** | Breite × Höhe × (Farbtiefe / 8) Bytes |
| **Audio (unkomprimiert):** | Abtastrate × (Bittiefe / 8) × Zeit × Kanäle |
| **Video (unkomprimiert):** | Breite × Höhe × (Farbtiefe / 8) × fps × Zeit |
| **Datenbank:** | Anzahl Datensätze × Größe pro Datensatz + Overhead |

**Visuelle Darstellung:**
```
Datenmengen-Hierarchie
    Bit (b) → Byte (B) → KB → MB → GB → TB → PB
    1        8 Bits    1024  1024  1024  1024  1024
                      Bytes  KB    MB    GB    TB

Berechnungsbeispiele:
    Text: "Hello World" = 11 Zeichen × 1 Byte = 11 Bytes
    
    Bild: 1920×1080, 24 Bit Farbtiefe
    = 1920 × 1080 × (24/8) Bytes
    = 2.073.600 × 3 Bytes
    = 6.220.800 Bytes
    = 6.220.800 / 1.024 / 1.024 ≈ 5,93 MB
    
    Audio: 44.100 Hz, 16 Bit, 3 Minuten, Stereo
    = 44.100 × (16/8) × 180 × 2 Bytes
    = 44.100 × 2 × 180 × 2 Bytes
    = 31.752.000 Bytes
    ≈ 30,3 MB
```

**Praxis-Beispiel:**
Berechnung der Datenmenge für eine Kundendatenbank:
- **Datensatz-Struktur:**
  - Name (Vorname + Nachname): 50 Zeichen = 50 Bytes
  - E-Mail: 50 Zeichen = 50 Bytes
  - Telefon: 20 Zeichen = 20 Bytes
  - Geburtsdatum: 10 Zeichen = 10 Bytes
  - Kunden-ID (Integer): 4 Bytes
  - **Gesamt pro Datensatz:** 134 Bytes

- **Bei 10.000 Kunden:**
  - 10.000 × 134 Bytes = 1.340.000 Bytes
  - = 1.340.000 / 1.024 ≈ 1.308 KB
  - = 1.308 / 1.024 ≈ 1,28 MB

**Prüfungscheck:**
**Frage:** Berechnen Sie die Datenmenge für ein unkomprimiertes Bild mit 800×600 Pixel und 24 Bit Farbtiefe.

**Antwort:**
**Berechnung:**
- Anzahl Pixel: 800 × 600 = 480.000 Pixel
- Farbtiefe: 24 Bit = 3 Bytes pro Pixel (RGB: je 8 Bit)
- Datenmenge: 480.000 Pixel × 3 Bytes = 1.440.000 Bytes
- Umrechnung: 1.440.000 Bytes / 1.024 = 1.406,25 KB
- 1.406,25 KB / 1.024 ≈ 1,37 MB

**Ergebnis:** Das unkomprimierte Bild benötigt ca. **1,37 MB** Speicherplatz.

**Merksatz:**
"Datenmengen: Bit < Byte < KB < MB < GB < TB - immer ×1024! Berechnung = Anzahl × Größe pro Einheit!"

---

### 5.2.6: Daten speichern und Dateiformate unterscheiden

**Kurz-Definition:**
Die Speicherung von Daten erfolgt in verschiedenen Dateiformaten, die sich durch ihre Struktur, Codierung, Kompression und Verwendungszweck unterscheiden. Die Wahl des richtigen Formats ist entscheidend für Kompatibilität, Effizienz und Funktionalität.

**Tabellarische Übersicht:**

| Dateiformat-Kategorie | Formate | Beschreibung | Verwendung |
|----------------------|---------|--------------|------------|
| **Textformate** | .txt, .csv, .json, .xml, .html | Reine Textdaten, strukturiert | Dokumente, Daten, Web |
| **Dokumente** | .docx, .pdf, .odt, .rtf | Formatierte Dokumente | Office, Präsentationen |
| **Bilder** | .jpg, .png, .gif, .bmp, .svg | Raster- oder Vektorgrafiken | Fotos, Grafiken |
| **Audio** | .mp3, .wav, .aac, .ogg | Komprimierte/unkomprimierte Audiodaten | Musik, Sprache |
| **Video** | .mp4, .avi, .mkv, .mov | Bewegtbild mit/ohne Kompression | Filme, Aufnahmen |
| **Datenbanken** | .db, .sqlite, .mdb | Strukturierte Daten | Datenbanken |
| **Archive** | .zip, .rar, .7z | Komprimierte Dateien | Backup, Übertragung |
| **Programmcode** | .java, .py, .js, .cpp | Quellcode | Softwareentwicklung |

| Speicherungsart | Beschreibung | Vorteile | Nachteile |
|-----------------|--------------|----------|-----------|
| **Dateisystem** | Einzelne Dateien auf Festplatte | Einfach, universell | Keine Struktur, langsam bei vielen Dateien |
| **Datenbank** | Strukturierte Speicherung | Schnelle Abfragen, Integrität | Komplexer, Overhead |
| **Cloud-Speicher** | Online, verteilt | Zugriff von überall, Backup | Abhängigkeit, Kosten |
| **Objektspeicher** | Für große, unstrukturierte Daten | Skalierbar, kostengünstig | Weniger Features |

| Formatvergleich (Bilder) | Kompression | Qualität | Transparenz | Animation |
|--------------------------|-------------|----------|-------------|-----------|
| **JPEG** | Verlustbehaftet | Gut | Nein | Nein |
| **PNG** | Verlustfrei | Sehr gut | Ja | Nein |
| **GIF** | Verlustfrei | Gut | Ja (1 Bit) | Ja |
| **BMP** | Unkomprimiert | Sehr gut | Nein | Nein |
| **SVG** | Vektorgrafik | Skalierbar | Ja | Ja (via CSS/JS) |

| Formatvergleich (Daten) | Struktur | Lesbarkeit | Größe | Verwendung |
|-------------------------|----------|------------|-------|------------|
| **CSV** | Tabellarisch, einfach | Menschlich lesbar | Klein | Import/Export |
| **JSON** | Objektstruktur, verschachtelt | Menschlich lesbar | Mittel | APIs, Konfiguration |
| **XML** | Hierarchisch, Tags | Menschlich lesbar | Groß | Dokumente, Konfiguration |
| **Binary** | Binär, komprimiert | Nicht lesbar | Sehr klein | Effiziente Speicherung |

**Visuelle Darstellung:**
```
Daten-Speicherung
    ├── Dateisystem
    │   ├── Einzelne Dateien
    │   └── Ordnerstruktur
    │
    ├── Datenbank
    │   ├── Relational (SQL)
    │   └── NoSQL (Dokument, Key-Value)
    │
    └── Cloud/Objekt-Speicher
        └── Skalierbar, verteilt

Dateiformat-Auswahl
    Text → .txt, .csv, .json, .xml
    Dokument → .docx, .pdf
    Bild → .jpg (Fotos), .png (Grafiken), .svg (Vektoren)
    Audio → .mp3 (komprimiert), .wav (unkomprimiert)
    Video → .mp4 (komprimiert), .avi (unkomprimiert)
    Daten → .db, .sqlite (strukturiert)
```

**Praxis-Beispiel:**
Ein Unternehmen speichert verschiedene Datentypen:
- **Kundendaten:** CSV-Datei (.csv) für Import/Export, SQL-Datenbank (.db) für Abfragen
- **Produktbilder:** JPEG (.jpg) für Fotos (kleine Dateigröße), PNG (.png) für Logos (Transparenz)
- **Dokumente:** PDF (.pdf) für finale Dokumente, DOCX (.docx) für Bearbeitung
- **API-Daten:** JSON (.json) für Datenaustausch zwischen Systemen
- **Backups:** ZIP (.zip) für komprimierte Archive

**Prüfungscheck:**
**Frage:** Vergleichen Sie die Dateiformate CSV, JSON und XML hinsichtlich Struktur, Lesbarkeit und Verwendung.

**Antwort:**
**CSV (Comma-Separated Values):**
- **Struktur:** Tabellarisch, einfach, Zeilen und Spalten
- **Lesbarkeit:** Sehr gut, direkt lesbar
- **Verwendung:** Import/Export, Tabellenkalkulation, einfache Daten

**JSON (JavaScript Object Notation):**
- **Struktur:** Objektstruktur, verschachtelt, Key-Value-Paare
- **Lesbarkeit:** Gut, strukturiert lesbar
- **Verwendung:** APIs, Konfigurationsdateien, Web-Anwendungen

**XML (eXtensible Markup Language):**
- **Struktur:** Hierarchisch, Tags, selbstbeschreibend
- **Lesbarkeit:** Gut, aber verbos (große Dateien)
- **Verwendung:** Dokumente, Konfiguration, Datenübertragung

**Merksatz:**
"Dateiformate wählen nach Zweck: CSV (Tabellen), JSON (APIs), XML (Dokumente), JPEG (Fotos), PNG (Grafiken)!"

---

### 5.2.7: Aspekte der Informationssicherheit präsentieren

**Kurz-Definition:**
Informationssicherheit umfasst Maßnahmen zum Schutz von Daten und IT-Systemen vor Bedrohungen, um Vertraulichkeit (Confidentiality), Integrität (Integrity) und Verfügbarkeit (Availability) zu gewährleisten - das sogenannte CIA-Triple.

**Tabellarische Übersicht:**

| Sicherheitsaspekt (CIA) | Beschreibung | Bedrohung | Schutzmaßnahme |
|--------------------------|--------------|-----------|----------------|
| **Vertraulichkeit (Confidentiality)** | Daten nur für Berechtigte zugänglich | Unbefugter Zugriff, Abhören | Verschlüsselung, Zugriffskontrolle |
| **Integrität (Integrity)** | Daten unverändert, korrekt | Manipulation, Fälschung | Digitale Signaturen, Prüfsummen |
| **Verfügbarkeit (Availability)** | Systeme und Daten erreichbar | Ausfälle, DDoS-Angriffe | Backups, Redundanz, Monitoring |

| Bedrohung | Beschreibung | Auswirkung | Schutz |
|-----------|--------------|------------|--------|
| **Malware** | Viren, Trojaner, Ransomware | Datenverlust, Systemausfall | Antivirus, Firewall |
| **Phishing** | Betrügerische E-Mails/Websites | Datenklau, Identitätsdiebstahl | Aufklärung, Filter |
| **Hacking** | Unbefugter Zugriff | Datenklau, Manipulation | Firewall, Zugriffskontrolle |
| **DDoS** | Überlastung von Servern | Systemausfall | DDoS-Schutz, Redundanz |
| **Datenverlust** | Hardwarefehler, Löschung | Daten weg | Backups, Redundanz |
| **Social Engineering** | Manipulation von Personen | Zugriff auf Systeme | Schulungen, Richtlinien |

| Schutzmaßnahme | Beschreibung | Schutz vor | Implementierung |
|----------------|--------------|------------|-----------------|
| **Verschlüsselung** | Daten unlesbar machen | Unbefugtem Zugriff | AES, RSA, TLS/SSL |
| **Authentifizierung** | Identität prüfen | Unbefugtem Zugriff | Passwörter, 2FA, Biometrie |
| **Autorisierung** | Berechtigungen prüfen | Unbefugten Aktionen | Rollen, Rechte |
| **Firewall** | Netzwerkverkehr filtern | Angriffen von außen | Hardware/Software-Firewall |
| **Backups** | Kopien erstellen | Datenverlust | Regelmäßig, automatisch |
| **Updates** | Sicherheitspatches | Bekannten Schwachstellen | Regelmäßig installieren |
| **Monitoring** | Systeme überwachen | Anomalien erkennen | Logs, Alerts |

| Verschlüsselungsarten | Beschreibung | Verwendung |
|----------------------|--------------|------------|
| **Symmetrisch** | Gleicher Schlüssel für Ver- und Entschlüsselung | AES, schnell, große Datenmengen |
| **Asymmetrisch** | Öffentlicher + privater Schlüssel | RSA, Schlüsselaustausch, Signaturen |
| **Hash-Funktionen** | Einweg-Verschlüsselung, Prüfsummen | SHA-256, Passwort-Hashing, Integrität |

**Visuelle Darstellung:**
```
Informationssicherheit (CIA-Triple)
    ├── Vertraulichkeit (Confidentiality)
    │   └── Verschlüsselung, Zugriffskontrolle
    ├── Integrität (Integrity)
    │   └── Signaturen, Prüfsummen
    └── Verfügbarkeit (Availability)
        └── Backups, Redundanz

Bedrohungen → Schutzmaßnahmen
    Malware → Antivirus, Firewall
    Phishing → Aufklärung, Filter
    Hacking → Firewall, Zugriffskontrolle
    DDoS → DDoS-Schutz, Redundanz
    Datenverlust → Backups, Redundanz
    Social Engineering → Schulungen

Verschlüsselung
    Symmetrisch (AES): [Daten] → [Schlüssel] → [Verschlüsselt]
    Asymmetrisch (RSA): [Daten] → [Öffentlicher Schlüssel] → [Verschlüsselt] → [Privater Schlüssel] → [Entschlüsselt]
```

**Praxis-Beispiel:**
Ein Unternehmen sichert seine Kundendatenbank:
- **Vertraulichkeit:** Datenbank-Verschlüsselung (AES-256), Zugriff nur für autorisierte Mitarbeiter mit 2FA
- **Integrität:** Digitale Signaturen für Backups, Prüfsummen (SHA-256) für Dateien
- **Verfügbarkeit:** Tägliche automatische Backups auf separaten Servern, Redundanz durch Replikation
- **Zusätzlich:** Firewall gegen externe Angriffe, regelmäßige Sicherheitsupdates, Monitoring-System für Anomalien

**Prüfungscheck:**
**Frage:** Erklären Sie das CIA-Triple der Informationssicherheit und nennen Sie für jeden Aspekt eine konkrete Schutzmaßnahme.

**Antwort:**
**CIA-Triple:**

1. **Vertraulichkeit (Confidentiality):**
   - Daten nur für Berechtigte zugänglich
   - **Schutzmaßnahme:** Verschlüsselung (z.B. AES-256), Zugriffskontrolle mit Authentifizierung

2. **Integrität (Integrity):**
   - Daten unverändert und korrekt
   - **Schutzmaßnahme:** Digitale Signaturen, Prüfsummen (z.B. SHA-256) zur Erkennung von Manipulationen

3. **Verfügbarkeit (Availability):**
   - Systeme und Daten stets erreichbar
   - **Schutzmaßnahme:** Regelmäßige Backups, Redundanz durch mehrere Server, DDoS-Schutz

**Merksatz:**
"CIA-Triple: Vertraulichkeit (Verschlüsselung), Integrität (Signaturen), Verfügbarkeit (Backups) - alle drei sind wichtig!"

---

## 5.3: Software im Rahmen von Projekten entwickeln

**Kurz-Definition:**
Die Softwareentwicklung erfolgt in strukturierten Projekten mit definierten Phasen, Rollen und Methoden des Projektmanagements, um komplexe Softwarelösungen planbar, kontrollierbar und erfolgreich umzusetzen.

**Tabellarische Übersicht:**

| Aspekt | Beschreibung | Bedeutung |
|--------|--------------|-----------|
| **Projektdefinition** | Einmalig, zeitlich begrenzt, spezifisches Ziel | Abgrenzung zu Routineaufgaben |
| **Projektphasen** | Initiierung, Planung, Durchführung, Abschluss | Strukturierter Ablauf |
| **Projektorganisation** | Rollen, Verantwortlichkeiten, Strukturen | Klare Zuständigkeiten |
| **Projektmanagement** | Planung, Steuerung, Kontrolle | Erfolgreiche Umsetzung |

**Visuelle Darstellung:**
```
Softwareentwicklung als Projekt
    ├── Projektdefinition
    │   ├── Einmalig
    │   ├── Zeitlich begrenzt
    │   └── Spezifisches Ziel
    │
    ├── Projektphasen
    │   ├── Initiierung
    │   ├── Planung
    │   ├── Durchführung
    │   └── Abschluss
    │
    ├── Projektorganisation
    │   ├── Rollen
    │   └── Strukturen
    │
    └── Projektmanagement
        ├── Planung
        ├── Steuerung
        └── Kontrolle
```

**Praxis-Beispiel:**
Ein Unternehmen entwickelt eine neue Kundenverwaltungssoftware:
- **Projekt:** Einmalig, 6 Monate Laufzeit, Ziel: Neue Software einführen
- **Phasen:** Initiierung (Anforderungen), Planung (Ressourcen), Durchführung (Entwicklung), Abschluss (Einführung)
- **Organisation:** Projektleiter, Entwicklerteam, Tester, Stakeholder
- **Management:** Meilensteine, Budget, Risikomanagement

**Prüfungscheck:**
**Frage:** Was kennzeichnet ein Softwareentwicklungsprojekt?

**Antwort:**
Ein Softwareentwicklungsprojekt ist gekennzeichnet durch:
1. **Einmaligkeit:** Nicht routinemäßig, spezifische Lösung
2. **Zeitliche Begrenzung:** Start- und Endtermin definiert
3. **Spezifisches Ziel:** Klare Anforderungen und Erfolgskriterien
4. **Begrenzte Ressourcen:** Budget, Personal, Zeit
5. **Projektorganisation:** Rollen, Verantwortlichkeiten, Strukturen
6. **Projektmanagement:** Planung, Steuerung, Kontrolle

**Merksatz:**
"Softwareentwicklung = Projekt (einmalig, zeitlich begrenzt, spezifisches Ziel) mit Phasen, Organisation und Management!"

---

### 5.3.1: Das Wesen von Projekten erläutern und Projektphasen differenzieren

**Kurz-Definition:**
Ein Projekt ist eine einmalige, zeitlich begrenzte Aufgabe mit spezifischem Ziel, die sich von Routineaufgaben unterscheidet. Projekte durchlaufen typische Phasen von der Initiierung bis zum Abschluss.

**Tabellarische Übersicht:**

| Projektmerkmal | Beschreibung | Abgrenzung zu Routine |
|----------------|--------------|----------------------|
| **Einmaligkeit** | Nicht routinemäßig, neuartig | Routine = wiederkehrend |
| **Zeitliche Begrenzung** | Start- und Endtermin | Routine = kontinuierlich |
| **Spezifisches Ziel** | Klare, messbare Ziele | Routine = Standardprozess |
| **Begrenzte Ressourcen** | Budget, Personal, Zeit | Routine = feste Ressourcen |
| **Komplexität** | Verschiedene Aufgaben, Abhängigkeiten | Routine = standardisiert |
| **Risiko** | Unsicherheit, Veränderungen | Routine = vorhersehbar |

| Projektphase | Beschreibung | Hauptaufgaben | Ergebnis |
|--------------|--------------|---------------|----------|
| **1. Initiierung** | Projekt starten, legitimieren | Anforderungen sammeln, Machbarkeit prüfen, Projektauftrag | Projektauftrag, Zieldefinition |
| **2. Planung** | Detaillierte Planung | Aufgaben, Ressourcen, Zeitplan, Budget, Risiken | Projektplan, Meilensteine |
| **3. Durchführung** | Projekt umsetzen | Arbeiten ausführen, koordinieren, kommunizieren | Teilprodukte, Fortschritt |
| **4. Überwachung/Steuerung** | Kontrolle und Anpassung | Fortschritt messen, Abweichungen erkennen, korrigieren | Statusberichte, Anpassungen |
| **5. Abschluss** | Projekt beenden | Abnahme, Dokumentation, Lessons Learned | Abnahme, Dokumentation |

| Phase im Detail | Aktivitäten | Beteiligte | Dokumente |
|-----------------|------------|------------|-----------|
| **Initiierung** | Bedarfsanalyse, Stakeholder identifizieren, Ziele definieren | Auftraggeber, Projektleiter | Projektauftrag, Lastenheft |
| **Planung** | Aufgaben strukturieren (WBS), Zeitplan (Gantt), Ressourcen planen, Budget erstellen | Projektleiter, Team | Projektplan, Meilensteinplan |
| **Durchführung** | Entwickeln, testen, dokumentieren, kommunizieren | Entwicklerteam, Tester | Code, Tests, Dokumentation |
| **Überwachung** | Status prüfen, Risiken überwachen, Änderungen managen | Projektleiter, Team | Statusberichte, Risikoliste |
| **Abschluss** | Abnahme durchführen, Wissen dokumentieren, Team auflösen | Alle Beteiligten | Abnahmeprotokoll, Lessons Learned |

**Visuelle Darstellung:**
```
Projektlebenszyklus
    Initiierung → Planung → Durchführung → Überwachung → Abschluss
         ↓           ↓            ↓             ↓            ↓
    Projektauftrag  Projektplan  Umsetzung    Kontrolle   Abnahme

Projekt vs. Routine
    Projekt:              Routine:
    ├── Einmalig         ├── Wiederkehrend
    ├── Zeitlich begrenzt ├── Kontinuierlich
    ├── Spezifisches Ziel ├── Standardprozess
    └── Komplex          └── Standardisiert

Projektphasen-Details
    Initiierung: Anforderungen → Machbarkeit → Projektauftrag
    Planung: Aufgaben → Zeitplan → Ressourcen → Budget
    Durchführung: Entwickeln → Testen → Dokumentieren
    Überwachung: Fortschritt → Abweichungen → Korrekturen
    Abschluss: Abnahme → Dokumentation → Lessons Learned
```

**Praxis-Beispiel:**
Entwicklung einer neuen E-Commerce-Plattform:
- **Initiierung:** Kunde benötigt neue Plattform, Anforderungen werden gesammelt, Machbarkeitsstudie, Projektauftrag erteilt
- **Planung:** Aufgabenliste (Frontend, Backend, Datenbank), Zeitplan (6 Monate), Team (5 Entwickler), Budget (200.000€), Risiken identifiziert
- **Durchführung:** Code wird geschrieben, Features implementiert, Tests durchgeführt, regelmäßige Team-Meetings
- **Überwachung:** Wöchentliche Statusberichte, Abweichungen vom Zeitplan erkannt, Anpassungen vorgenommen
- **Abschluss:** Kunde testet und nimmt ab, Dokumentation übergeben, Lessons Learned dokumentiert (z.B. bessere Kommunikation nötig)

**Prüfungscheck:**
**Frage:** Nennen Sie die fünf Hauptphasen eines Projekts und beschreiben Sie kurz die Hauptaufgabe jeder Phase.

**Antwort:**
1. **Initiierung:** Projekt starten, Anforderungen sammeln, Machbarkeit prüfen, Projektauftrag erstellen
2. **Planung:** Detaillierte Planung von Aufgaben, Zeitplan, Ressourcen, Budget und Risiken
3. **Durchführung:** Projekt umsetzen, Arbeiten ausführen, koordinieren, kommunizieren
4. **Überwachung/Steuerung:** Fortschritt messen, Abweichungen erkennen und korrigieren
5. **Abschluss:** Projekt beenden, Abnahme durchführen, Dokumentation erstellen, Lessons Learned sammeln

**Merksatz:**
"Projektphasen: Initiieren → Planen → Durchführen → Überwachen → Abschließen - systematisch zum Ziel!"

---

### 5.3.2: Projektorganisation und Projektmanagement beschreiben

**Kurz-Definition:**
Projektorganisation definiert die Struktur, Rollen und Verantwortlichkeiten im Projekt, während Projektmanagement die Methoden, Techniken und Prozesse zur Planung, Steuerung und Kontrolle von Projekten umfasst.

**Tabellarische Übersicht:**

| Organisationsform | Beschreibung | Vorteile | Nachteile | Verwendung |
|-------------------|--------------|----------|-----------|------------|
| **Linienorganisation** | Projekt in bestehende Hierarchie integriert | Einfach, klare Struktur | Konflikte mit Linie, langsam | Kleine Projekte |
| **Matrixorganisation** | Projektteam aus verschiedenen Abteilungen | Ressourcen optimal nutzen | Doppelte Weisungsbefugnis | Mittelgroße Projekte |
| **Reine Projektorganisation** | Eigenständiges Projektteam | Schnell, fokussiert | Hohe Kosten, Isolation | Große, wichtige Projekte |
| **Stab-Linien-Organisation** | Projektleiter als Stab, Team in Linie | Unterstützung durch Stab | Komplexe Struktur | Unterstützungsprojekte |

| Projektrolle | Beschreibung | Verantwortlichkeiten | Kompetenzen |
|--------------|--------------|----------------------|-------------|
| **Projektleiter** | Verantwortlich für Projekterfolg | Planung, Steuerung, Kommunikation, Risikomanagement | Führung, Organisation, Kommunikation |
| **Projektteam** | Führt Projektaufgaben aus | Entwicklung, Tests, Dokumentation | Fachkompetenz, Teamarbeit |
| **Auftraggeber** | Erteilt Projektauftrag | Ziele definieren, Budget freigeben, Abnahme | Entscheidungsbefugnis |
| **Projektsponsor** | Unterstützt Projekt | Ressourcen bereitstellen, Hindernisse beseitigen | Einfluss, Budget |
| **Stakeholder** | Interessierte Parteien | Anforderungen, Feedback | Fachwissen, Interesse |
| **Projektbüro (PMO)** | Unterstützt Projekte | Standards, Methoden, Beratung | Projektmanagement-Expertise |

| Projektmanagement-Bereich | Beschreibung | Werkzeuge/Methoden |
|---------------------------|--------------|-------------------|
| **Zeitmanagement** | Termine planen und überwachen | Gantt-Diagramm, Meilensteinplan, Critical Path Method |
| **Kostenmanagement** | Budget planen und kontrollieren | Kostenschätzung, Budgetplan, Earned Value |
| **Qualitätsmanagement** | Qualität sicherstellen | Qualitätsplan, Reviews, Tests, Standards |
| **Risikomanagement** | Risiken identifizieren und managen | Risikoliste, Risikobewertung, Maßnahmenplan |
| **Kommunikationsmanagement** | Information und Kommunikation | Kommunikationsplan, Meetings, Berichte |
| **Ressourcenmanagement** | Personal und Material planen | Ressourcenplan, Kapazitätsplanung |
| **Änderungsmanagement** | Änderungen steuern | Änderungsantrag, Impact-Analyse, Freigabe |

| Projektmanagement-Methoden | Beschreibung | Vorteile | Nachteile |
|----------------------------|--------------|----------|-----------|
| **Wasserfallmodell** | Sequenziell, Phasen nacheinander | Übersichtlich, planbar | Unflexibel, späte Änderungen schwierig |
| **Agil (Scrum, Kanban)** | Iterativ, inkrementell, flexibel | Flexibel, schnelles Feedback | Weniger vorhersagbar, mehr Kommunikation nötig |
| **V-Modell** | Phasen mit Tests verknüpft | Qualitätssicherung integriert | Weniger flexibel |
| **Hybrid** | Kombination verschiedener Methoden | Flexibel, angepasst | Komplexer |

**Visuelle Darstellung:**
```
Projektorganisation
    ├── Linienorganisation
    │   └── Projekt in bestehender Hierarchie
    ├── Matrixorganisation
    │   └── Team aus verschiedenen Abteilungen
    ├── Reine Projektorganisation
    │   └── Eigenständiges Team
    └── Stab-Linien-Organisation
        └── Projektleiter als Stab

Projektrollen
    Auftraggeber
        ↓
    Projektleiter
        ↓
    Projektteam (Entwickler, Tester, etc.)
        ↓
    Stakeholder (interessierte Parteien)

Projektmanagement-Bereiche
    Zeit → Kosten → Qualität → Risiko → Kommunikation → Ressourcen → Änderungen
    (alle parallel und miteinander verknüpft)
```

**Praxis-Beispiel:**
Ein Softwareentwicklungsprojekt wird organisiert:
- **Organisationsform:** Matrixorganisation - Entwickler aus verschiedenen Abteilungen (Frontend, Backend, QA)
- **Rollen:**
  - Projektleiter: Verantwortlich für Planung, Steuerung, Kommunikation
  - Entwicklerteam: 3 Frontend-, 2 Backend-Entwickler, 1 Tester
  - Auftraggeber: Geschäftsführung, definiert Ziele
  - Stakeholder: Kunden, Marketing, Support
- **Projektmanagement:**
  - Zeitmanagement: Gantt-Diagramm, 6 Monate, wöchentliche Meilensteine
  - Kostenmanagement: Budget 200.000€, monatliche Kostenkontrolle
  - Qualitätsmanagement: Code-Reviews, automatisierte Tests, Definition of Done
  - Risikomanagement: Risikoliste, wöchentliche Risikobewertung
  - Kommunikation: Tägliches Stand-up, wöchentliche Statusberichte

**Prüfungscheck:**
**Frage:** Erklären Sie die Matrixorganisation und nennen Sie Vor- und Nachteile.

**Antwort:**
**Matrixorganisation:**
Das Projektteam setzt sich aus Mitarbeitern verschiedener Abteilungen zusammen, die sowohl ihrer Linienabteilung als auch dem Projekt zugeordnet sind.

**Vorteile:**
- Optimale Nutzung von Ressourcen (Experten aus verschiedenen Bereichen)
- Fachkompetenz wird eingebracht
- Flexibilität bei Ressourcenzuteilung
- Wissenstransfer zwischen Abteilungen

**Nachteile:**
- Doppelte Weisungsbefugnis (Linienvorgesetzter + Projektleiter) kann zu Konflikten führen
- Komplexere Kommunikation und Koordination nötig
- Mögliche Prioritätskonflikte zwischen Linienaufgaben und Projektaufgaben

**Merksatz:**
"Projektorganisation = Struktur + Rollen, Projektmanagement = Planen + Steuern + Kontrollieren - beide sind wichtig!"

---

## 5.4: Den Prozess der Softwareentwicklung analysieren

**Kurz-Definition:**
Der Prozess der Softwareentwicklung umfasst strukturierte Phasen von der Anforderungsanalyse bis zur Wartung sowie verschiedene Vorgehensmodelle (Wasserfall, agil, V-Modell), die den Entwicklungsablauf organisieren.

**Tabellarische Übersicht:**

| Aspekt | Beschreibung | Bedeutung |
|--------|--------------|-----------|
| **Prozessphasen** | Strukturierte Schritte von Analyse bis Wartung | Systematischer Ablauf |
| **Vorgehensmodelle** | Methoden zur Organisation des Prozesses | Planung und Steuerung |
| **Iteration** | Wiederholte Durchläufe | Verbesserung, Anpassung |
| **Dokumentation** | Dokumentation in jeder Phase | Nachvollziehbarkeit, Wartung |

**Visuelle Darstellung:**
```
Softwareentwicklungsprozess
    ├── Prozessphasen
    │   ├── Analyse
    │   ├── Design
    │   ├── Implementierung
    │   ├── Test
    │   └── Wartung
    │
    └── Vorgehensmodelle
        ├── Wasserfall
        ├── V-Modell
        ├── Agil (Scrum)
        └── Iterativ
```

**Praxis-Beispiel:**
Ein Unternehmen entwickelt eine neue Software:
- **Prozess:** Durchläuft Phasen von Anforderungsanalyse über Design, Implementierung, Tests bis zur Wartung
- **Vorgehensmodell:** Agiles Scrum mit 2-wöchigen Sprints
- **Iteration:** Jeder Sprint liefert ein funktionsfähiges Inkrement
- **Dokumentation:** User Stories, Code-Kommentare, API-Dokumentation

**Prüfungscheck:**
**Frage:** Was umfasst der Prozess der Softwareentwicklung?

**Antwort:**
Der Prozess der Softwareentwicklung umfasst:
1. **Prozessphasen:** Strukturierte Schritte von der Anforderungsanalyse über Design, Implementierung, Tests bis zur Wartung
2. **Vorgehensmodelle:** Methoden zur Organisation des Entwicklungsprozesses (Wasserfall, agil, V-Modell)
3. **Iteration:** Wiederholte Durchläufe zur Verbesserung und Anpassung
4. **Dokumentation:** Dokumentation in jeder Phase für Nachvollziehbarkeit und Wartung

**Merksatz:**
"Softwareentwicklungsprozess = Phasen (Analyse → Design → Implementierung → Test → Wartung) + Vorgehensmodell!"

---

### 5.4.1: Die Prozessphasen beschreiben

**Kurz-Definition:**
Der Softwareentwicklungsprozess durchläuft typische Phasen: Anforderungsanalyse, Systemdesign, Implementierung, Test, Integration, Einführung und Wartung, wobei jede Phase spezifische Aufgaben und Ergebnisse hat.

**Tabellarische Übersicht:**

| Prozessphase | Beschreibung | Hauptaufgaben | Ergebnis/Dokumente | Beteiligte |
|--------------|--------------|--------------|-------------------|------------|
| **1. Anforderungsanalyse** | Anforderungen ermitteln und spezifizieren | Interviews, Workshops, Use Cases, Anforderungen dokumentieren | Lastenheft, Anforderungsspezifikation, Use Cases | Analysten, Stakeholder |
| **2. Systemdesign** | Architektur und Struktur planen | Architektur entwerfen, Datenmodell, Schnittstellen definieren | Systemarchitektur, Datenmodell, Schnittstellenspezifikation | Architekten, Designer |
| **3. Implementierung** | Code schreiben | Programmieren, Code-Reviews, Standards einhalten | Quellcode, Code-Dokumentation | Entwickler |
| **4. Test** | Software testen | Unit-Tests, Integrationstests, Systemtests, Abnahmetests | Testfälle, Testprotokolle, Fehlerberichte | Tester, QA |
| **5. Integration** | Komponenten zusammenführen | Integrationstests, Schnittstellen prüfen | Integrierte Software | Entwickler, Tester |
| **6. Einführung** | Software in Betrieb nehmen | Installation, Schulung, Migration, Go-Live | Betriebsfähige Software | IT, Anwender |
| **7. Wartung** | Software pflegen und weiterentwickeln | Fehler beheben, Anpassungen, Updates | Aktualisierte Software | Entwickler, Support |

| Phase im Detail | Aktivitäten | Methoden/Werkzeuge |
|-----------------|------------|-------------------|
| **Anforderungsanalyse** | Stakeholder-Interviews, Workshops, Dokumentenanalyse, Prototyping | Interviews, Workshops, Use Cases, User Stories, Prototypen |
| **Systemdesign** | Architektur-Design, Datenmodellierung, Schnittstellen-Design, UI-Design | UML, ER-Diagramme, Mockups, Architektur-Patterns |
| **Implementierung** | Programmieren, Code-Reviews, Versionskontrolle, Dokumentation | IDE, Programmiersprachen, Git, Code-Standards |
| **Test** | Testplanung, Testdurchführung, Fehlerverfolgung, Testautomatisierung | Test-Frameworks, Bug-Tracker, Test-Tools |
| **Integration** | Komponenten-Integration, Schnittstellen-Tests, System-Integration | Integration-Tools, API-Tests |
| **Einführung** | Deployment-Planung, Installation, Schulung, Rollback-Plan | Deployment-Tools, Schulungsmaterial |
| **Wartung** | Fehleranalyse, Anpassungen, Performance-Optimierung, Updates | Monitoring-Tools, Log-Analyse |

| Phasen-Charakteristika | Sequenziell | Iterativ | Agil |
|------------------------|-------------|----------|------|
| **Anforderungsanalyse** | Einmalig am Anfang | In jedem Zyklus | Kontinuierlich, User Stories |
| **Design** | Detailliert vor Implementierung | Pro Iteration | Minimal, just-in-time |
| **Implementierung** | Nach Design abgeschlossen | Pro Iteration | In Sprints |
| **Test** | Nach Implementierung | Parallel/Pro Iteration | Kontinuierlich, TDD |
| **Wartung** | Nach Einführung | Kontinuierlich | Teil des Prozesses |

**Visuelle Darstellung:**
```
Softwareentwicklungsprozess-Phasen
    Anforderungsanalyse
         ↓
    Systemdesign
         ↓
    Implementierung
         ↓
    Test
         ↓
    Integration
         ↓
    Einführung
         ↓
    Wartung (kontinuierlich)

Detaillierte Phasen:
    1. Anforderungsanalyse
        → Lastenheft, Use Cases, Anforderungen
    2. Systemdesign
        → Architektur, Datenmodell, Schnittstellen
    3. Implementierung
        → Quellcode, Dokumentation
    4. Test
        → Testfälle, Testprotokolle
    5. Integration
        → Integrierte Software
    6. Einführung
        → Betriebsfähige Software
    7. Wartung
        → Aktualisierte Software
```

**Praxis-Beispiel:**
Entwicklung einer Kundenverwaltungssoftware:
- **Anforderungsanalyse:** Interviews mit Vertrieb, Workshops, Use Cases (Kunde anlegen, bearbeiten, suchen), Lastenheft erstellt
- **Systemdesign:** 3-Schichten-Architektur (Präsentation, Logik, Daten), Datenmodell (Kunden, Kontakte, Bestellungen), REST-API definiert
- **Implementierung:** Frontend (React), Backend (Java Spring), Datenbank (PostgreSQL), Code-Reviews durchgeführt
- **Test:** Unit-Tests für alle Module, Integrationstests für API, Systemtests mit Testdaten, Abnahmetests durch Kunde
- **Integration:** Frontend und Backend integriert, Datenbank migriert, End-to-End-Tests
- **Einführung:** Installation auf Produktionsserver, Schulung der Mitarbeiter, Datenmigration, Go-Live
- **Wartung:** Fehlerbehebung (z.B. Performance-Problem), neue Features (Export-Funktion), Updates

**Prüfungscheck:**
**Frage:** Nennen Sie die sieben Hauptphasen des Softwareentwicklungsprozesses und beschreiben Sie kurz die Hauptaufgabe jeder Phase.

**Antwort:**
1. **Anforderungsanalyse:** Anforderungen von Stakeholdern ermitteln, dokumentieren und spezifizieren (Lastenheft, Use Cases)
2. **Systemdesign:** Architektur, Datenmodell und Schnittstellen planen und entwerfen
3. **Implementierung:** Code schreiben, programmieren, Code-Reviews durchführen
4. **Test:** Software testen (Unit, Integration, System, Abnahme), Fehler finden und beheben
5. **Integration:** Komponenten zusammenführen, Integrationstests durchführen
6. **Einführung:** Software in Betrieb nehmen, Installation, Schulung, Migration, Go-Live
7. **Wartung:** Software pflegen, Fehler beheben, Anpassungen vornehmen, Updates einspielen

**Merksatz:**
"Prozessphasen: Analysieren → Designen → Implementieren → Testen → Integrieren → Einführen → Warten - systematisch vorgehen!"

---

### 5.4.2: Vorgehensmodelle unterscheiden

**Kurz-Definition:**
Vorgehensmodelle strukturieren den Softwareentwicklungsprozess durch definierte Phasen, Aktivitäten und Regeln. Wichtige Modelle sind Wasserfall, V-Modell, Iterativ-Inkrementell und Agil (Scrum, Kanban), die sich in Flexibilität, Planbarkeit und Anwendungsbereich unterscheiden.

**Tabellarische Übersicht:**

| Vorgehensmodell | Beschreibung | Phasen | Flexibilität | Planbarkeit | Anwendung |
|-----------------|--------------|--------|--------------|-------------|-----------|
| **Wasserfallmodell** | Sequenziell, Phasen nacheinander | Linear, keine Rückkehr | Sehr niedrig | Sehr hoch | Klare Anforderungen, kleine Projekte |
| **V-Modell** | Wasserfall + Tests verknüpft | Linear mit Testphasen | Niedrig | Hoch | Qualitätskritisch, reguliert |
| **Iterativ-Inkrementell** | Wiederholte Zyklen, schrittweise | Iterative Zyklen | Mittel | Mittel | Unklare Anforderungen, mittlere Projekte |
| **Agil (Scrum)** | Iterativ, inkrementell, flexibel | Sprints (2-4 Wochen) | Sehr hoch | Niedrig-Mittel | Schnelle Änderungen, komplexe Projekte |
| **Kanban** | Kontinuierlicher Fluss, Pull-Prinzip | Kontinuierlich | Sehr hoch | Niedrig | Wartung, kontinuierliche Entwicklung |
| **Spiralmodell** | Risikofokussiert, iterative Zyklen | Spiral-Zyklen | Mittel-Hoch | Mittel | Risikoreiche Projekte |

| Vergleich: Wasserfall vs. Agil | Wasserfallmodell | Agiles Modell (Scrum) |
|--------------------------------|------------------|----------------------|
| **Phasen** | Sequenziell, linear | Iterativ, Sprints |
| **Änderungen** | Schwer, spät teuer | Einfach, früh integriert |
| **Planung** | Detailliert am Anfang | Kurzfristig, adaptiv |
| **Dokumentation** | Umfangreich, formal | Minimal, just-in-time |
| **Feedback** | Spät (am Ende) | Früh, kontinuierlich |
| **Team** | Groß, spezialisiert | Klein, selbstorganisiert |
| **Anforderungen** | Fest, am Anfang definiert | Flexibel, entwickeln sich |
| **Qualität** | Am Ende getestet | Kontinuierlich getestet |

| V-Modell Phasen | Entwicklungsphase | Testphase |
|-----------------|-------------------|-----------|
| **Anforderungsanalyse** | ↔ | **Abnahmetest** |
| **Systemdesign** | ↔ | **Systemtest** |
| **Architekturdesign** | ↔ | **Integrationstest** |
| **Komponentendesign** | ↔ | **Komponententest** |
| **Implementierung** | (Mitte) | |

| Agiles Scrum | Beschreibung | Dauer | Ergebnis |
|--------------|--------------|-------|----------|
| **Sprint Planning** | Aufgaben für Sprint planen | 2-4h | Sprint Backlog |
| **Daily Scrum** | Tägliches Stand-up | 15 Min | Synchronisation |
| **Sprint** | Entwicklungszyklus | 2-4 Wochen | Funktionsfähiges Inkrement |
| **Sprint Review** | Demo, Feedback | 2-4h | Feedback, Anpassungen |
| **Sprint Retrospective** | Prozess verbessern | 1-2h | Verbesserungen |

| Vorgehensmodell-Auswahl | Kriterium | Empfohlenes Modell |
|-------------------------|-----------|-------------------|
| **Klare, stabile Anforderungen** | Anforderungen bekannt, ändern sich nicht | Wasserfall, V-Modell |
| **Unklare, sich ändernde Anforderungen** | Anforderungen entwickeln sich | Agil, Iterativ |
| **Qualitätskritisch** | Hohe Qualitätsanforderungen | V-Modell |
| **Schnelle Markteinführung** | Zeitdruck, schnelle Lieferung | Agil |
| **Kleine Projekte** | Überschaubar, einfach | Wasserfall |
| **Große, komplexe Projekte** | Viele Komponenten, komplex | Agil, Iterativ |
| **Risikoreich** | Viele Unsicherheiten | Spiralmodell, Agil |

**Visuelle Darstellung:**
```
Wasserfallmodell
    Analyse → Design → Implementierung → Test → Einführung → Wartung
    (linear, keine Rückkehr)

V-Modell
    Analyse ──────────────── Abnahmetest
        ↓                       ↑
    Systemdesign ───────── Systemtest
        ↓                       ↑
    Architekturdesign ─── Integrationstest
        ↓                       ↑
    Komponentendesign ─── Komponententest
        ↓                       ↑
    Implementierung (Mitte)

Iterativ-Inkrementell
    [Analyse → Design → Implementierung → Test] → [Analyse → Design → ...]
    Zyklus 1 (Inkrement 1)    Zyklus 2 (Inkrement 2)    ...

Agiles Scrum
    Sprint Planning → Sprint (2-4 Wochen) → Sprint Review → Retrospective
         ↑                                                           ↓
         └─────────────────── (wiederholen) ────────────────────────┘
    Daily Scrum (täglich während Sprint)
```

**Praxis-Beispiel:**
Verschiedene Projekte mit unterschiedlichen Vorgehensmodellen:

- **Wasserfallmodell:** Einfache Website mit klaren Anforderungen
  - Phase 1: Anforderungen klar definiert
  - Phase 2: Design komplett geplant
  - Phase 3: Implementierung
  - Phase 4: Tests
  - Phase 5: Go-Live
  - Keine Änderungen während Entwicklung

- **V-Modell:** Medizinische Software (qualitätskritisch)
  - Jede Entwicklungsphase hat entsprechende Testphase
  - Systematische Qualitätssicherung
  - Regulatorische Anforderungen erfüllt

- **Agiles Scrum:** Mobile App (sich ändernde Anforderungen)
  - Sprint 1 (2 Wochen): Login, Registrierung
  - Sprint 2: Profil, Einstellungen
  - Sprint 3: Hauptfunktionen
  - Jeder Sprint liefert funktionsfähiges Inkrement
  - Anforderungen können sich pro Sprint ändern
  - Daily Stand-ups, Sprint Reviews, Retrospektiven

*