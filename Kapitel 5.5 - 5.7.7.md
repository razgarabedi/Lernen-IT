# Kapitel 5.5 - 5.7.7: Klassenarbeit Vorbereitung

## 5.5: Den Prozess der Anforderungsspezifikation und der Softwareplanung beschreiben

**Kurz-Definition:**
Der Prozess der Anforderungsspezifikation und Softwareplanung umfasst die systematische Erfassung, Dokumentation und Strukturierung von Anforderungen an eine Software sowie die Planung ihrer Entwicklung von der Idee bis zur fertigen Lösung.

**Tabellarische Übersicht:**

| Phase | Beschreibung | Ergebnis | Beteiligte |
|-------|--------------|----------|------------|
| **Anforderungserhebung** | Gespräche, Interviews, Beobachtungen | Informelle Anforderungen | Auftraggeber, Nutzer |
| **Anforderungsspezifikation** | Strukturierte Dokumentation | Lastenheft/Pflichtenheft | Analysten, Entwickler |
| **Entwurf** | Architektur und Struktur planen | Design-Dokumente, Modelle | Architekten, Entwickler |
| **Implementierung** | Code schreiben | Funktionsfähige Software | Entwickler |
| **Test** | Software prüfen | Getestete Software | Tester, Entwickler |

**Visuelle Darstellung:**
```
[Anforderungserhebung] → [Anforderungsspezifikation] → [Entwurf] → [Implementierung] → [Test]
         ↓                        ↓                      ↓              ↓                ↓
    [Lastenheft]            [Pflichtenheft]        [UML-Diagramme]  [Code]        [Testberichte]
```

**Praxis-Beispiel:**
Ein Unternehmen benötigt eine neue Buchhaltungssoftware. Zuerst werden die Anforderungen durch Interviews mit Buchhaltern erhoben (Lastenheft). Dann spezifiziert das Entwicklungsteam die technischen Details (Pflichtenheft). Anschließend wird die Software-Architektur mit UML modelliert, bevor die Programmierung beginnt.

**Prüfungscheck:**
**Frage:** Nennen Sie die fünf Hauptphasen des Prozesses der Anforderungsspezifikation und Softwareplanung.

**Antwort:**
1. **Anforderungserhebung:** Gespräche, Interviews zur Ermittlung der Bedürfnisse
2. **Anforderungsspezifikation:** Strukturierte Dokumentation in Lasten- und Pflichtenheft
3. **Entwurf:** Planung der Software-Architektur und Struktur
4. **Implementierung:** Programmierung der Software
5. **Test:** Prüfung der Funktionalität und Qualität

**Merksatz:**
"Erheben → Spezifizieren → Entwerfen → Implementieren → Testen = Der Weg zur fertigen Software!"

---

### 5.5.1: Anforderungen an eine Software spezifizieren

**Kurz-Definition:**
Die Spezifikation von Anforderungen bedeutet die strukturierte, vollständige und präzise Dokumentation aller funktionalen und nicht-funktionalen Anforderungen an eine Software in einem nachvollziehbaren Format.

**Tabellarische Übersicht:**

| Anforderungstyp | Beschreibung | Beispiele | Wichtig für |
|-----------------|--------------|-----------|-------------|
| **Funktionale Anforderungen** | Was soll die Software tun? | "System soll Benutzer anmelden", "Daten exportieren" | Funktionalität |
| **Nicht-funktionale Anforderungen** | Wie soll die Software sein? | Performance, Sicherheit, Benutzerfreundlichkeit | Qualität |
| **FURPS+** | Functionality, Usability, Reliability, Performance, Supportability | Umfassendes Modell | Vollständigkeit |
| **SMART-Kriterien** | Specific, Measurable, Achievable, Relevant, Time-bound | Qualitätskriterien | Formulierung |

**Visuelle Darstellung:**
```
Anforderungen
    ├── Funktionale Anforderungen
    │   ├── Was soll die Software tun?
    │   └── Funktionen, Features
    │
    └── Nicht-funktionale Anforderungen
        ├── Performance (Geschwindigkeit)
        ├── Sicherheit
        ├── Benutzerfreundlichkeit
        ├── Zuverlässigkeit
        └── Wartbarkeit
```

**Praxis-Beispiel:**
Für eine Online-Shop-Software werden Anforderungen spezifiziert:
- **Funktional:** "Kunden können Produkte in den Warenkorb legen und bestellen"
- **Nicht-funktional:** "Seitenaufbau in unter 2 Sekunden", "SSL-Verschlüsselung für Zahlungen", "Mobile-optimiert"

**Prüfungscheck:**
**Frage:** Was ist der Unterschied zwischen funktionalen und nicht-funktionalen Anforderungen? Nennen Sie je ein Beispiel.

**Antwort:**
- **Funktionale Anforderungen:** Beschreiben WAS die Software tun soll (z.B. "System soll Benutzerdaten speichern")
- **Nicht-funktionale Anforderungen:** Beschreiben WIE die Software sein soll (z.B. "System soll 1000 Anfragen pro Sekunde verarbeiten können")

**Merksatz:**
"Funktional = WAS, Nicht-funktional = WIE - beide sind wichtig für die Spezifikation!"

---

### 5.5.2: Lasten- und Pflichtenheft unterscheiden

**Kurz-Definition:**
Das Lastenheft beschreibt die Anforderungen aus Sicht des Auftraggebers (WAS gewünscht wird), während das Pflichtenheft die technische Umsetzung aus Sicht des Auftragnehmers beschreibt (WIE es umgesetzt wird).

**Tabellarische Übersicht:**

| Aspekt | Lastenheft | Pflichtenheft |
|--------|------------|---------------|
| **Ersteller** | Auftraggeber (Kunde) | Auftragnehmer (Entwickler) |
| **Perspektive** | Fachlich, aus Anwendersicht | Technisch, aus Entwicklersicht |
| **Inhalt** | Was soll erreicht werden? | Wie wird es umgesetzt? |
| **Sprache** | Fachsprache, verständlich für Laien | Technische Fachsprache |
| **Detaillierungsgrad** | Grob, Ziele und Wünsche | Detailliert, konkrete Lösungen |
| **Zweck** | Anforderungen definieren | Umsetzung planen |
| **Rechtliche Bedeutung** | Grundlage für Vertrag | Verbindliche Umsetzungsvorgabe |

**Visuelle Darstellung:**
```
[Auftraggeber]                    [Auftragnehmer]
      │                                │
      │  "Ich brauche..."              │  "Ich setze um mit..."
      │                                │
      ↓                                ↓
[Lastenheft]                    [Pflichtenheft]
  - WAS?                          - WIE?
  - Ziele                         - Technologie
  - Wünsche                       - Architektur
  - Anforderungen                 - Implementierung
```

**Praxis-Beispiel:**
**Lastenheft (Auftraggeber):** "Wir benötigen ein System zur Verwaltung unserer Kundenkontakte. Es soll einfach zu bedienen sein und auf allen Geräten funktionieren."

**Pflichtenheft (Auftragnehmer):** "Wir entwickeln eine Web-Anwendung mit React (Frontend), Node.js (Backend) und MySQL (Datenbank). Responsive Design für mobile Geräte. REST-API für Datenzugriff."

**Prüfungscheck:**
**Frage:** Erklären Sie den Unterschied zwischen Lasten- und Pflichtenheft. Wer erstellt welches?

**Antwort:**
- **Lastenheft:** Wird vom Auftraggeber erstellt, beschreibt fachliche Anforderungen und Ziele aus Anwendersicht (WAS)
- **Pflichtenheft:** Wird vom Auftragnehmer erstellt, beschreibt technische Umsetzung und Lösungsweg (WIE)

**Merksatz:**
"Lastenheft = Kunde sagt WAS, Pflichtenheft = Entwickler sagt WIE!"

---

### 5.5.3: Den Entwurfsprozess beschreiben

**Kurz-Definition:**
Der Entwurfsprozess umfasst die systematische Planung der Software-Architektur, Struktur und Komponenten, bevor die Implementierung beginnt. Er transformiert Anforderungen in ein umsetzbares Design.

**Tabellarische Übersicht:**

| Entwurfsphase | Beschreibung | Ergebnis | Methoden |
|---------------|--------------|----------|----------|
| **Systementwurf** | Grobe Architektur, Systemgrenzen | Systemarchitektur | Top-Down |
| **Komponentenentwurf** | Detaillierung einzelner Module | Komponentendiagramme | Modularisierung |
| **Datenmodellierung** | Datenstrukturen und Beziehungen | ER-Diagramme, Datenbankschema | Datenbankdesign |
| **Schnittstellendesign** | APIs, Kommunikation zwischen Komponenten | Interface-Spezifikationen | API-Design |
| **Benutzeroberfläche** | UI/UX-Design | Mockups, Wireframes | UI-Design |

**Visuelle Darstellung:**
```
Entwurfsprozess
    │
    ├── [Systementwurf]
    │   └── Grobe Architektur
    │
    ├── [Komponentenentwurf]
    │   └── Module und Klassen
    │
    ├── [Datenmodellierung]
    │   └── ER-Diagramm
    │
    ├── [Schnittstellendesign]
    │   └── API-Spezifikation
    │
    └── [UI-Design]
        └── Mockups
```

**Praxis-Beispiel:**
Für eine E-Commerce-Plattform:
1. **Systementwurf:** 3-Tier-Architektur (Frontend, Backend, Datenbank)
2. **Komponentenentwurf:** Module für Warenkorb, Zahlung, Kundenverwaltung
3. **Datenmodellierung:** ER-Diagramm mit Entitäten: Kunde, Produkt, Bestellung
4. **Schnittstellendesign:** REST-API für Frontend-Backend-Kommunikation
5. **UI-Design:** Wireframes für Produktseite, Warenkorb, Checkout

**Prüfungscheck:**
**Frage:** Nennen Sie die fünf Hauptphasen des Entwurfsprozesses und beschreiben Sie kurz, was in jeder Phase passiert.

**Antwort:**
1. **Systementwurf:** Grobe Architektur und Systemgrenzen definieren
2. **Komponentenentwurf:** Detaillierung einzelner Module und Komponenten
3. **Datenmodellierung:** Datenstrukturen und Beziehungen planen (ER-Diagramme)
4. **Schnittstellendesign:** APIs und Kommunikation zwischen Komponenten definieren
5. **UI-Design:** Benutzeroberfläche und Benutzerführung planen (Mockups)

**Merksatz:**
"Entwerfen = System → Komponenten → Daten → Schnittstellen → UI planen!"

---

### 5.5.4: Modellierungssprachen unterscheiden

**Kurz-Definition:**
Modellierungssprachen sind formale Sprachen zur visuellen Darstellung von Software-Systemen, Prozessen und Strukturen. Die wichtigste ist UML (Unified Modeling Language) mit verschiedenen Diagrammtypen für unterschiedliche Aspekte.

**Tabellarische Übersicht:**

| Modellierungssprache | Zweck | Diagrammtypen | Verwendung |
|---------------------|-------|---------------|------------|
| **UML** | Objektorientierte Modellierung | Use Case, Klassen-, Sequenz-, Aktivitätsdiagramme | Standard für Software-Entwurf |
| **ER-Modell** | Datenmodellierung | Entity-Relationship-Diagramme | Datenbankdesign |
| **BPMN** | Geschäftsprozesse | Business Process Model and Notation | Prozessmodellierung |
| **Flowchart** | Ablaufdarstellung | Flussdiagramme | Algorithmen, Prozesse |
| **Pseudocode** | Algorithmusbeschreibung | Textbasierte Beschreibung | Algorithmenentwurf |

**Visuelle Darstellung:**
```
Modellierungssprachen
    ├── UML (Unified Modeling Language)
    │   ├── Use Case Diagramm (Anwendungsfälle)
    │   ├── Klassendiagramm (Struktur)
    │   ├── Sequenzdiagramm (Ablauf)
    │   └── Aktivitätsdiagramm (Prozesse)
    │
    ├── ER-Modell (Entity-Relationship)
    │   └── Datenbankstruktur
    │
    ├── BPMN
    │   └── Geschäftsprozesse
    │
    └── Flowchart
        └── Algorithmen
```

**Praxis-Beispiel:**
Für ein Online-Banking-System:
- **UML Use Case:** "Geld überweisen", "Kontostand abfragen" als Anwendungsfälle
- **UML Klassendiagramm:** Klassen: Kunde, Konto, Transaktion mit Attributen und Methoden
- **UML Sequenzdiagramm:** Ablauf: Kunde → Login → Überweisung → Bestätigung
- **ER-Diagramm:** Entitäten: Kunde, Konto, Transaktion mit Beziehungen

**Prüfungscheck:**
**Frage:** Welche vier wichtigsten UML-Diagrammtypen kennen Sie? Beschreiben Sie kurz den Zweck jedes Typs.

**Antwort:**
1. **Use Case Diagramm:** Zeigt Anwendungsfälle und Akteure (WAS macht das System?)
2. **Klassendiagramm:** Zeigt Klassen, Attribute, Methoden und Beziehungen (Struktur)
3. **Sequenzdiagramm:** Zeigt zeitlichen Ablauf von Nachrichten zwischen Objekten (WIE läuft es ab?)
4. **Aktivitätsdiagramm:** Zeigt Abläufe und Entscheidungen (Prozessfluss)

**Merksatz:**
"UML = Use Case (WAS), Klasse (Struktur), Sequenz (Ablauf), Aktivität (Prozess)!"

---

## 5.6: Programmiersprachen und -werkzeuge unterscheiden und auswählen

**Kurz-Definition:**
Programmiersprachen sind formale Sprachen zur Kommunikation mit Computern, die unterschiedliche Paradigmen, Syntax und Einsatzgebiete haben. Die Auswahl hängt von Projektanforderungen, Team-Expertise und technischen Gegebenheiten ab.

**Tabellarische Übersicht:**

| Aspekt | Beschreibung | Relevanz |
|--------|--------------|----------|
| **Paradigmen** | Objektorientiert, prozedural, funktional | Programmierstil |
| **Syntax** | Regeln für Code-Schreibung | Lesbarkeit, Erlernbarkeit |
| **Typisierung** | Statisch vs. dynamisch | Fehlererkennung |
| **Ausführungsart** | Kompiliert vs. interpretiert | Performance |
| **Einsatzgebiete** | Web, Desktop, Mobile, Embedded | Projektauswahl |

**Visuelle Darstellung:**
```
Programmiersprachen-Auswahl
    │
    ├── Paradigmen
    │   ├── Objektorientiert (Java, C++)
    │   ├── Prozedural (C)
    │   └── Funktional (Haskell)
    │
    ├── Typisierung
    │   ├── Statisch (Java, C#)
    │   └── Dynamisch (Python, JavaScript)
    │
    └── Ausführung
        ├── Kompiliert (C, C++)
        └── Interpretiert (Python, JavaScript)
```

**Praxis-Beispiel:**
Ein Startup entwickelt eine Web-Anwendung:
- **Frontend:** JavaScript (React) - dynamisch, interpretiert, für Browser
- **Backend:** Python (Django) - dynamisch, interpretiert, schnell entwickelbar
- **Mobile App:** Java/Kotlin (Android) - objektorientiert, kompiliert, plattformspezifisch

**Prüfungscheck:**
**Frage:** Welche Faktoren sollten bei der Auswahl einer Programmiersprache berücksichtigt werden?

**Antwort:**
1. **Projektanforderungen:** Web, Desktop, Mobile, Embedded?
2. **Team-Expertise:** Welche Sprachen kennt das Team?
3. **Performance:** Benötigt hohe Geschwindigkeit (kompiliert) oder schnelle Entwicklung (interpretiert)?
4. **Ökosystem:** Verfügbarkeit von Bibliotheken und Frameworks
5. **Wartbarkeit:** Syntax, Lesbarkeit, Community-Support

**Merksatz:**
"Sprache wählen = Projekt + Team + Performance + Ökosystem berücksichtigen!"

---

### 5.6.1: Den Aufbau von Programmiersprachen beschreiben

**Kurz-Definition:**
Programmiersprachen bestehen aus Syntax (Regeln für Code-Schreibung), Semantik (Bedeutung), Datentypen, Operatoren, Kontrollstrukturen und Funktionen/Prozeduren, die zusammen die Struktur und Funktionsweise definieren.

**Tabellarische Übersicht:**

| Komponente | Beschreibung | Beispiele |
|------------|--------------|-----------|
| **Syntax** | Regeln für korrekte Code-Schreibung | Klammern, Semikolons, Einrückung |
| **Semantik** | Bedeutung von Code-Konstrukten | Was macht der Code? |
| **Datentypen** | Arten von Daten | int, string, boolean, float |
| **Variablen** | Speicherplätze für Werte | x = 5, name = "Max" |
| **Operatoren** | Rechen- und Vergleichszeichen | +, -, *, ==, <, > |
| **Kontrollstrukturen** | Steuerung des Programmablaufs | if, while, for |
| **Funktionen/Prozeduren** | Wiederverwendbare Code-Blöcke | def, function, method |

**Visuelle Darstellung:**
```
Programmiersprache
    │
    ├── Syntax (Regeln)
    │   └── Wie schreibe ich Code?
    │
    ├── Semantik (Bedeutung)
    │   └── Was bedeutet der Code?
    │
    ├── Datentypen
    │   ├── Primitive (int, string, boolean)
    │   └── Komplexe (Array, Objekt)
    │
    ├── Operatoren
    │   ├── Arithmetisch (+, -, *)
    │   ├── Vergleich (==, <, >)
    │   └── Logisch (&&, ||, !)
    │
    └── Kontrollstrukturen
        ├── Verzweigungen (if, switch)
        └── Schleifen (for, while)
```

**Praxis-Beispiel:**
Python-Code zeigt verschiedene Komponenten:
```python
# Syntax: Einrückung, Doppelpunkt
# Datentypen: int, string
# Variablen: alter, name
alter = 25
name = "Max"

# Operatoren: +, ==
# Kontrollstruktur: if
if alter >= 18:
    # Funktion: print()
    print(name + " ist volljährig")
```

**Prüfungscheck:**
**Frage:** Erklären Sie den Unterschied zwischen Syntax und Semantik in Programmiersprachen.

**Antwort:**
- **Syntax:** Die Regeln für die korrekte Schreibung von Code (z.B. Klammern, Semikolons, Einrückung). Syntax-Fehler führen zu Kompilier-/Parse-Fehlern.
- **Semantik:** Die Bedeutung und Funktionsweise des Codes. Semantische Fehler führen zu falschen Ergebnissen, obwohl der Code syntaktisch korrekt ist.

**Merksatz:**
"Syntax = WIE schreibe ich es? Semantik = WAS bedeutet es?"

---

### 5.6.2: Programmiersprachen unterscheiden

**Kurz-Definition:**
Programmiersprachen unterscheiden sich durch Paradigmen (objektorientiert, prozedural, funktional), Typisierung (statisch/dynamisch), Ausführungsart (kompiliert/interpretiert) und Einsatzgebiete (Web, Desktop, Mobile).

**Tabellarische Übersicht:**

| Sprache | Paradigma | Typisierung | Ausführung | Haupt-Einsatzgebiet |
|---------|-----------|-------------|------------|---------------------|
| **Python** | Multi-Paradigma (OO, prozedural, funktional) | Dynamisch | Interpretiert | Web, Data Science, Scripting |
| **Java** | Objektorientiert | Statisch | Kompiliert (Bytecode) | Enterprise, Android, Web |
| **JavaScript** | Multi-Paradigma | Dynamisch | Interpretiert | Web (Frontend/Backend) |
| **C/C++** | Prozedural/Objektorientiert | Statisch | Kompiliert | Systemprogrammierung, Embedded |
| **C#** | Objektorientiert | Statisch | Kompiliert (Bytecode) | Windows, Web (.NET) |
| **PHP** | Prozedural/Objektorientiert | Dynamisch | Interpretiert | Web (Backend) |

**Visuelle Darstellung:**
```
Programmiersprachen
    │
    ├── Nach Paradigma
    │   ├── Objektorientiert: Java, C++, C#, Python
    │   ├── Prozedural: C, Pascal
    │   └── Funktional: Haskell, Lisp
    │
    ├── Nach Typisierung
    │   ├── Statisch: Java, C, C#
    │   └── Dynamisch: Python, JavaScript, PHP
    │
    └── Nach Ausführung
        ├── Kompiliert: C, C++, Java (Bytecode)
        └── Interpretiert: Python, JavaScript, PHP
```

**Praxis-Beispiel:**
- **Python:** Dynamisch typisiert, interpretiert, vielseitig → Ideal für schnelle Entwicklung, Data Science
- **Java:** Statisch typisiert, kompiliert zu Bytecode, plattformunabhängig → Ideal für große Enterprise-Anwendungen
- **JavaScript:** Dynamisch typisiert, interpretiert im Browser → Standard für Web-Frontend
- **C++:** Statisch typisiert, kompiliert, sehr schnell → Ideal für Systemprogrammierung, Spiele

**Prüfungscheck:**
**Frage:** Nennen Sie drei Unterschiede zwischen Python und Java.

**Antwort:**
1. **Typisierung:** Python ist dynamisch typisiert (Typ wird zur Laufzeit bestimmt), Java ist statisch typisiert (Typ muss deklariert werden)
2. **Ausführung:** Python wird interpretiert, Java wird zu Bytecode kompiliert und dann von JVM interpretiert
3. **Syntax:** Python verwendet Einrückung für Blöcke, Java verwendet geschweifte Klammern
4. **Performance:** Java ist typischerweise schneller durch Kompilierung, Python ist flexibler für schnelle Entwicklung

**Merksatz:**
"Python = dynamisch + interpretiert + flexibel, Java = statisch + kompiliert + robust!"

---

### 5.6.3: Programmiersprachen für ein Projekt auswählen

**Kurz-Definition:**
Die Auswahl einer Programmiersprache erfolgt basierend auf Projektanforderungen (Plattform, Performance, Skalierbarkeit), Team-Expertise, verfügbaren Bibliotheken/Frameworks, Wartbarkeit und langfristigen Aspekten.

**Tabellarische Übersicht:**

| Kriterium | Beschreibung | Beispiele |
|-----------|--------------|-----------|
| **Projekttyp** | Web, Desktop, Mobile, Embedded | Web → JavaScript/Python, Mobile → Java/Kotlin/Swift |
| **Performance** | Geschwindigkeitsanforderungen | Hoch → C/C++, Mittel → Java, Niedrig → Python |
| **Team-Expertise** | Kenntnisse des Entwicklungsteams | Bekannte Sprache = schneller Start |
| **Ökosystem** | Verfügbare Bibliotheken/Frameworks | Python → Data Science, JavaScript → Web-Frameworks |
| **Wartbarkeit** | Langfristige Pflege | Statische Typisierung, gute Dokumentation |
| **Community** | Support und Ressourcen | Große Community = mehr Hilfe |
| **Kosten** | Lizenzen, Tools | Open Source vs. kommerziell |

**Visuelle Darstellung:**
```
Sprachauswahl-Entscheidung
    │
    ├── Projektanforderungen
    │   ├── Plattform? (Web/Desktop/Mobile)
    │   ├── Performance? (Hoch/Mittel/Niedrig)
    │   └── Skalierbarkeit?
    │
    ├── Team-Faktoren
    │   ├── Expertise vorhanden?
    │   └── Lernkurve akzeptabel?
    │
    ├── Technische Faktoren
    │   ├── Bibliotheken verfügbar?
    │   ├── Frameworks passend?
    │   └── Tooling vorhanden?
    │
    └── Langfristigkeit
        ├── Wartbarkeit
        ├── Community-Support
        └── Zukunftssicherheit
```

**Praxis-Beispiel:**
**Projekt:** E-Commerce-Webshop
- **Anforderung:** Web, skalierbar, schnell entwickelbar
- **Entscheidung:** 
  - Frontend: JavaScript (React) - Standard für Web, große Community
  - Backend: Python (Django) - Schnelle Entwicklung, viele Bibliotheken, Team kennt Python
  - Datenbank: PostgreSQL - Skalierbar, Open Source

**Prüfungscheck:**
**Frage:** Welche fünf Kriterien sollten bei der Auswahl einer Programmiersprache für ein Projekt berücksichtigt werden?

**Antwort:**
1. **Projekttyp und Plattform:** Web, Desktop, Mobile oder Embedded?
2. **Performance-Anforderungen:** Benötigt hohe Geschwindigkeit?
3. **Team-Expertise:** Welche Sprachen kennt das Entwicklungsteam?
4. **Ökosystem:** Sind passende Bibliotheken und Frameworks verfügbar?
5. **Wartbarkeit und Langfristigkeit:** Ist die Sprache zukunftssicher, gibt es Community-Support?

**Merksatz:**
"Sprache wählen = Projekt + Team + Ökosystem + Performance + Zukunft prüfen!"

---

### 5.6.4: Programmierwerkzeuge und Frameworks unterscheiden

**Kurz-Definition:**
Programmierwerkzeuge unterstützen den Entwicklungsprozess (IDEs, Debugger, Versionskontrolle), während Frameworks vorgefertigte Strukturen und Bibliotheken für spezifische Anwendungsbereiche bereitstellen.

**Tabellarische Übersicht:**

| Kategorie | Beschreibung | Beispiele | Zweck |
|-----------|--------------|-----------|-------|
| **IDE** | Integrierte Entwicklungsumgebung | Visual Studio, IntelliJ, PyCharm | Code schreiben, debuggen, testen |
| **Editor** | Texteditor mit Features | VS Code, Sublime, Atom | Code schreiben |
| **Debugger** | Fehlersuche im Code | GDB, Browser DevTools | Programmfehler finden |
| **Versionskontrolle** | Code-Verwaltung | Git, SVN | Änderungen verwalten |
| **Build-Tools** | Kompilierung, Packaging | Maven, Gradle, npm | Software bauen |
| **Frameworks** | Vorgefertigte Strukturen | Django, React, Spring | Schnelle Entwicklung |
| **Bibliotheken** | Wiederverwendbare Funktionen | NumPy, jQuery | Funktionalität nutzen |

**Visuelle Darstellung:**
```
Entwicklungsumgebung
    │
    ├── Werkzeuge (Tools)
    │   ├── IDE (Entwicklung)
    │   ├── Debugger (Fehlersuche)
    │   ├── Versionskontrolle (Git)
    │   └── Build-Tools (Kompilierung)
    │
    └── Code-Basis
        ├── Frameworks (Struktur)
        │   └── Django, React, Spring
        │
        └── Bibliotheken (Funktionen)
            └── NumPy, jQuery, pandas
```

**Praxis-Beispiel:**
Ein Python-Entwickler nutzt:
- **IDE:** PyCharm - Code schreiben, Debugging, Testing
- **Versionskontrolle:** Git - Code-Versionen verwalten
- **Framework:** Django - Web-Anwendung schnell entwickeln
- **Bibliothek:** NumPy - Mathematische Operationen für Data Science

**Prüfungscheck:**
**Frage:** Erklären Sie den Unterschied zwischen einem Framework und einer Bibliothek.

**Antwort:**
- **Framework:** Bietet eine vorgefertigte Struktur und Architektur für Anwendungen. Der Entwickler füllt die Struktur mit Code (Inversion of Control). Beispiel: Django, React
- **Bibliothek:** Bietet wiederverwendbare Funktionen, die der Entwickler nach Bedarf aufruft. Der Entwickler kontrolliert den Ablauf. Beispiel: NumPy, jQuery

**Merksatz:**
"Framework = Struktur vorgegeben, Bibliothek = Funktionen nutzen!"

---

## 5.7: Einfache Anwendungen in Python implementieren

**Kurz-Definition:**
Python ist eine vielseitige, interpretierte Programmiersprache mit klarer Syntax, die sich ideal für Einsteiger eignet. Einfache Anwendungen umfassen Programme mit Variablen, Kontrollstrukturen, Funktionen und Dateioperationen.

**Tabellarische Übersicht:**

| Aspekt | Beschreibung | Python-Besonderheit |
|--------|--------------|---------------------|
| **Syntax** | Einrückung statt Klammern | Lesbarer, sauberer Code |
| **Typisierung** | Dynamisch | Keine Typdeklaration nötig |
| **Ausführung** | Interpretiert | Direkt ausführbar, keine Kompilierung |
| **Einfachheit** | Klare, verständliche Syntax | Ideal für Einsteiger |
| **Vielseitigkeit** | Web, Data Science, Scripting | Breites Einsatzgebiet |

**Visuelle Darstellung:**
```
Python-Programm
    │
    ├── Variablen und Datentypen
    │   ├── int, float, string, boolean
    │   └── Listen, Dictionaries
    │
    ├── Kontrollstrukturen
    │   ├── if/elif/else
    │   └── for/while
    │
    ├── Funktionen
    │   └── def funktion():
    │
    └── Dateioperationen
        ├── Lesen (open, read)
        └── Schreiben (write)
```

**Praxis-Beispiel:**
Ein einfaches Python-Programm zur Temperaturumrechnung:
```python
def celsius_zu_fahrenheit(celsius):
    return celsius * 9/5 + 32

temp_c = 25
temp_f = celsius_zu_fahrenheit(temp_c)
print(f"{temp_c}°C = {temp_f}°F")
```

**Prüfungscheck:**
**Frage:** Nennen Sie drei Vorteile von Python als Programmiersprache.

**Antwort:**
1. **Einfache Syntax:** Klare, lesbare Syntax mit Einrückung statt Klammern
2. **Dynamische Typisierung:** Keine Typdeklaration nötig, flexibel
3. **Vielseitigkeit:** Einsatz in Web, Data Science, Scripting, Automatisierung
4. **Große Community:** Viele Bibliotheken, Frameworks und Support verfügbar

**Merksatz:**
"Python = einfach + flexibel + vielseitig = ideal für Einsteiger!"

---

### 5.7.1: Python beschreiben und eine Entwicklungsumgebung auswählen

**Kurz-Definition:**
Python ist eine interpretierte, dynamisch typisierte Programmiersprache mit klarer Syntax. Eine Entwicklungsumgebung (IDE oder Editor) unterstützt beim Schreiben, Testen und Debuggen von Python-Code.

**Tabellarische Übersicht:**

| Entwicklungsumgebung | Typ | Vorteile | Nachteile | Für wen? |
|----------------------|-----|----------|-----------|----------|
| **PyCharm** | IDE | Vollständig, Debugger, Testing | Ressourcenintensiv | Professionelle Entwicklung |
| **Visual Studio Code** | Editor | Leicht, Erweiterbar, Kostenlos | Weniger Features als IDE | Vielseitig, beliebt |
| **IDLE** | Einfache IDE | Mit Python installiert | Sehr einfach, wenig Features | Einsteiger |
| **Jupyter Notebook** | Web-basiert | Interaktiv, Visualisierung | Nicht für große Projekte | Data Science |
| **Sublime Text** | Editor | Schnell, leicht | Kostenpflichtig | Erfahrene Entwickler |

**Visuelle Darstellung:**
```
Python-Entwicklungsumgebung
    │
    ├── IDE (Integriert)
    │   ├── PyCharm (Professionell)
    │   └── IDLE (Einfach)
    │
    ├── Editor + Plugins
    │   ├── VS Code (Beliebt)
    │   └── Sublime Text (Schnell)
    │
    └── Spezialisiert
        └── Jupyter Notebook (Data Science)
```

**Praxis-Beispiel:**
**Einsteiger:** Beginnt mit IDLE (bereits installiert) oder VS Code (kostenlos, viele Tutorials)
**Professioneller Entwickler:** Nutzt PyCharm (vollständige IDE mit Debugger, Testing, Refactoring)
**Data Scientist:** Nutzt Jupyter Notebook (interaktive Datenanalyse und Visualisierung)

**Prüfungscheck:**
**Frage:** Welche Entwicklungsumgebung würden Sie einem Python-Einsteiger empfehlen und warum?

**Antwort:**
**VS Code (Visual Studio Code)** oder **IDLE**:
- **VS Code:** Kostenlos, leichtgewichtig, viele Python-Erweiterungen, große Community, gut für den Einstieg und späteres Wachstum
- **IDLE:** Bereits mit Python installiert, sehr einfach, keine zusätzliche Installation nötig, ideal für erste Schritte

**Merksatz:**
"Einsteiger → VS Code oder IDLE, Profis → PyCharm, Data Science → Jupyter!"

---

### 5.7.2: Ein erstes Programm implementieren und ausführen

**Kurz-Definition:**
Ein erstes Python-Programm besteht aus einfachen Anweisungen wie Ausgaben (print), Variablenzuweisungen und grundlegenden Operationen. Die Ausführung erfolgt durch den Python-Interpreter.

**Tabellarische Übersicht:**

| Schritt | Beschreibung | Beispiel |
|---------|--------------|----------|
| **Programm schreiben** | Code in Datei speichern | `programm.py` |
| **Ausführen** | Python-Interpreter starten | `python programm.py` |
| **Ausgabe** | Ergebnis im Terminal | Text, Zahlen, Fehler |
| **Syntax-Fehler** | Falsche Schreibweise | Fehlermeldung vom Interpreter |
| **Logik-Fehler** | Falsche Logik | Programm läuft, aber falsches Ergebnis |

**Visuelle Darstellung:**
```
[Code schreiben] → [Als .py speichern] → [Python ausführen] → [Ergebnis/Fehler]
     programm.py          programm.py      python programm.py      Ausgabe
```

**Praxis-Beispiel:**
**Programm:** `hallo.py`
```python
# Mein erstes Python-Programm
name = "Max"
alter = 20

print("Hallo, ich bin", name)
print("Ich bin", alter, "Jahre alt")
print("In 5 Jahren bin ich", alter + 5)
```

**Ausführung:**
```bash
python hallo.py
```

**Ausgabe:**
```
Hallo, ich bin Max
Ich bin 20 Jahre alt
In 5 Jahren bin ich 25
```

**Prüfungscheck:**
**Frage:** Schreiben Sie ein Python-Programm, das zwei Zahlen einliest, sie addiert und das Ergebnis ausgibt.

**Antwort:**
```python
# Zahlen einlesen
zahl1 = int(input("Erste Zahl: "))
zahl2 = int(input("Zweite Zahl: "))

# Addieren
summe = zahl1 + zahl2

# Ergebnis ausgeben
print("Die Summe ist:", summe)
```

**Merksatz:**
"Programm schreiben → Speichern → Python ausführen → Ergebnis prüfen!"

---

### 5.7.3: Syntaktische Grundlagen beschreiben

**Kurz-Definition:**
Die syntaktischen Grundlagen von Python umfassen Einrückung für Blöcke, Variablendeklaration ohne Typ, Kommentare, Operatoren und grundlegende Datentypen. Python verwendet Einrückung statt geschweifter Klammern.

**Tabellarische Übersicht:**

| Syntax-Element | Beschreibung | Beispiel |
|----------------|--------------|----------|
| **Einrückung** | Definiert Code-Blöcke (4 Leerzeichen oder Tab) | `if x > 0:`<br>`    print("positiv")` |
| **Variablen** | Keine Typdeklaration nötig | `name = "Max"`<br>`alter = 25` |
| **Kommentare** | `#` für einzeilige Kommentare | `# Dies ist ein Kommentar` |
| **Strings** | Einfache oder doppelte Anführungszeichen | `"Hallo"` oder `'Hallo'` |
| **Operatoren** | Arithmetisch: `+`, `-`, `*`, `/` | `5 + 3`, `10 / 2` |
| **Vergleich** | `==`, `!=`, `<`, `>`, `<=`, `>=` | `x == 5`, `y > 10` |
| **Zuweisung** | `=` für Zuweisung | `x = 10` |

**Visuelle Darstellung:**
```
Python-Syntax
    │
    ├── Einrückung (statt Klammern)
    │   if x > 0:
    │       print("positiv")  ← 4 Leerzeichen
    │
    ├── Variablen (dynamisch)
    │   name = "Max"  ← Kein Typ nötig
    │
    ├── Kommentare
    │   # Einzeiliger Kommentar
    │
    └── Operatoren
        +, -, *, /, ==, !=, <, >
```

**Praxis-Beispiel:**
```python
# Variablen deklarieren
name = "Anna"           # String
alter = 23              # Integer
gehalt = 3500.50        # Float
ist_aktiv = True        # Boolean

# Arithmetische Operationen
summe = alter + 5
produkt = alter * 2

# Vergleich
if alter >= 18:
    print(name, "ist volljährig")
else:
    print(name, "ist minderjährig")
```

**Prüfungscheck:**
**Frage:** Welche Besonderheit hat Python bei der Definition von Code-Blöcken im Vergleich zu Sprachen wie Java oder C++?

**Antwort:**
Python verwendet **Einrückung (Indentation)** statt geschweifter Klammern `{}` oder Schlüsselwörter wie `begin/end` zur Definition von Code-Blöcken. Die Einrückung (typischerweise 4 Leerzeichen) zeigt an, welche Zeilen zu einem Block gehören. Dies macht den Code lesbarer, aber erfordert konsequente Einrückung.

**Merksatz:**
"Python-Syntax = Einrückung statt Klammern, dynamische Typen, klare Struktur!"

---

### 5.7.4: Anweisungsfolgen programmieren und Exceptions abfangen

**Kurz-Definition:**
Anweisungsfolgen sind sequenzielle Code-Ausführungen von oben nach unten. Exceptions (Ausnahmen) sind Fehler, die zur Laufzeit auftreten und mit try-except-Blöcken abgefangen werden können, um das Programm nicht abstürzen zu lassen.

**Tabellarische Übersicht:**

| Konzept | Beschreibung | Syntax | Zweck |
|---------|--------------|--------|-------|
| **Anweisungsfolge** | Code wird sequenziell ausgeführt | Zeile für Zeile | Normale Ausführung |
| **Exception** | Laufzeitfehler | Automatisch bei Fehler | Fehlerbehandlung |
| **try-except** | Fehler abfangen | `try:` ... `except:` | Programm stabil halten |
| **finally** | Immer ausführen | `finally:` | Aufräumen (z.B. Datei schließen) |
| **Häufige Exceptions** | ValueError, TypeError, FileNotFoundError | Verschiedene Typen | Spezifische Fehler |

**Visuelle Darstellung:**
```
Anweisungsfolge:
    Zeile 1 → Zeile 2 → Zeile 3 → ...

Exception-Behandlung:
    try:
        Code (kann Fehler werfen)
    except Fehlertyp:
        Fehlerbehandlung
    finally:
        Immer ausführen
```

**Praxis-Beispiel:**
```python
# Anweisungsfolge
print("Programm startet")
zahl1 = 10
zahl2 = 2

# Exception-Behandlung
try:
    ergebnis = zahl1 / zahl2
    print("Ergebnis:", ergebnis)
    
    # Datei öffnen
    datei = open("daten.txt", "r")
    inhalt = datei.read()
    print(inhalt)
    datei.close()
    
except ZeroDivisionError:
    print("Fehler: Division durch Null!")
except FileNotFoundError:
    print("Fehler: Datei nicht gefunden!")
except Exception as e:
    print("Allgemeiner Fehler:", e)
finally:
    print("Programm beendet")
```

**Prüfungscheck:**
**Frage:** Schreiben Sie ein Python-Programm, das eine Zahl vom Benutzer einliest, durch 2 teilt und das Ergebnis ausgibt. Fangen Sie mögliche Exceptions ab.

**Antwort:**
```python
try:
    zahl = int(input("Geben Sie eine Zahl ein: "))
    ergebnis = zahl / 2
    print("Die Hälfte ist:", ergebnis)
except ValueError:
    print("Fehler: Bitte geben Sie eine gültige Zahl ein!")
except ZeroDivisionError:
    print("Fehler: Division durch Null!")
except Exception as e:
    print("Ein Fehler ist aufgetreten:", e)
```

**Merksatz:**
"try-except = Fehler abfangen, Programm stabil halten, finally = immer aufräumen!"

---

### 5.7.5: Verzweigungen und Funktionen implementieren

**Kurz-Definition:**
Verzweigungen (if/elif/else) ermöglichen bedingte Ausführung von Code. Funktionen sind wiederverwendbare Code-Blöcke, die mit `def` definiert werden und Parameter sowie Rückgabewerte haben können.

**Tabellarische Übersicht:**

| Konzept | Beschreibung | Syntax | Beispiel |
|---------|--------------|--------|----------|
| **if** | Einfache Bedingung | `if bedingung:` | `if alter >= 18:` |
| **elif** | Weitere Bedingung | `elif bedingung:` | `elif alter >= 65:` |
| **else** | Sonst-Fall | `else:` | `else:` |
| **Funktion** | Wiederverwendbarer Block | `def name():` | `def berechne_summe():` |
| **Parameter** | Eingabewerte | `def name(para):` | `def addiere(a, b):` |
| **Rückgabewert** | Ergebnis zurückgeben | `return wert` | `return summe` |

**Visuelle Darstellung:**
```
Verzweigung:
    if Bedingung1:
        Code 1
    elif Bedingung2:
        Code 2
    else:
        Code 3

Funktion:
    def funktionsname(parameter):
        Code
        return wert
```

**Praxis-Beispiel:**
```python
# Verzweigung
def bewertung(punkte):
    if punkte >= 90:
        return "Sehr gut"
    elif punkte >= 80:
        return "Gut"
    elif punkte >= 70:
        return "Befriedigend"
    else:
        return "Nicht bestanden"

# Funktion mit Parametern und Rückgabewert
def berechne_durchschnitt(zahlen):
    if len(zahlen) == 0:
        return 0
    summe = 0
    for zahl in zahlen:
        summe += zahl
    return summe / len(zahlen)

# Funktion aufrufen
noten = [85, 90, 78, 92]
durchschnitt = berechne_durchschnitt(noten)
print("Durchschnitt:", durchschnitt)
print("Bewertung:", bewertung(durchschnitt))
```

**Prüfungscheck:**
**Frage:** Schreiben Sie eine Python-Funktion `ist_gerade(zahl)`, die prüft, ob eine Zahl gerade ist, und True/False zurückgibt. Verwenden Sie eine Verzweigung.

**Antwort:**
```python
def ist_gerade(zahl):
    if zahl % 2 == 0:
        return True
    else:
        return False

# Oder kürzer:
def ist_gerade(zahl):
    return zahl % 2 == 0

# Verwendung
print(ist_gerade(4))   # True
print(ist_gerade(5))   # False
```

**Merksatz:**
"if/elif/else = Verzweigung, def = Funktion, return = Ergebnis zurückgeben!"

---

### 5.7.6: Schleifen und Listen implementieren

**Kurz-Definition:**
Schleifen (for, while) ermöglichen wiederholte Ausführung von Code. Listen sind geordnete Sammlungen von Elementen, die mit eckigen Klammern `[]` erstellt werden und über Indizes zugänglich sind.

**Tabellarische Übersicht:**

| Konzept | Beschreibung | Syntax | Verwendung |
|---------|--------------|--------|------------|
| **for-Schleife** | Über Sequenz iterieren | `for element in sequenz:` | Listen durchlaufen |
| **while-Schleife** | Solange Bedingung wahr | `while bedingung:` | Wiederholung bis Bedingung |
| **range()** | Zahlenfolge erzeugen | `range(start, stop, step)` | Zahlen generieren |
| **Liste** | Geordnete Sammlung | `[element1, element2]` | Daten speichern |
| **Index** | Position in Liste | `liste[0]` (erstes Element) | Elemente zugreifen |
| **Listen-Methoden** | append(), remove(), len() | `liste.append(wert)` | Liste manipulieren |

**Visuelle Darstellung:**
```
for-Schleife:
    for element in liste:
        Code für jedes Element

while-Schleife:
    while bedingung:
        Code (wiederholt)

Liste:
    [Element1, Element2, Element3]
      Index 0   Index 1   Index 2
```

**Praxis-Beispiel:**
```python
# Liste erstellen
noten = [85, 90, 78, 92, 88]

# for-Schleife über Liste
print("Alle Noten:")
for note in noten:
    print(note)

# for-Schleife mit Index
print("\nNoten mit Index:")
for i in range(len(noten)):
    print(f"Index {i}: {noten[i]}")

# while-Schleife
zaehler = 0
while zaehler < 5:
    print(f"Zähler: {zaehler}")
    zaehler += 1

# Liste manipulieren
noten.append(95)        # Element hinzufügen
noten.remove(78)        # Element entfernen
durchschnitt = sum(noten) / len(noten)  # Durchschnitt berechnen

print(f"\nDurchschnitt: {durchschnitt}")
```

**Prüfungscheck:**
**Frage:** Schreiben Sie ein Python-Programm, das eine Liste von Zahlen erstellt, alle Zahlen größer als 10 findet und in einer neuen Liste speichert. Verwenden Sie eine for-Schleife.

**Antwort:**
```python
# Liste erstellen
zahlen = [5, 15, 8, 20, 3, 12, 7]

# Neue Liste für Zahlen > 10
groessere_zahlen = []

# Schleife über alle Zahlen
for zahl in zahlen:
    if zahl > 10:
        groessere_zahlen.append(zahl)

# Ergebnis ausgeben
print("Ursprüngliche Liste:", zahlen)
print("Zahlen größer als 10:", groessere_zahlen)
```

**Merksatz:**
"for = über Liste iterieren, while = wiederholen bis Bedingung, Liste = geordnete Sammlung!"

---

### 5.7.7: Daten in Dateien verwalten

**Kurz-Definition:**
Daten können in Dateien gespeichert und gelesen werden. Python bietet Funktionen zum Öffnen, Lesen, Schreiben und Schließen von Dateien. Wichtig ist die Exception-Behandlung und das ordnungsgemäße Schließen von Dateien.

**Tabellarische Übersicht:**

| Operation | Beschreibung | Methode | Beispiel |
|-----------|--------------|---------|----------|
| **Datei öffnen** | Datei zum Lesen/Schreiben öffnen | `open(dateiname, modus)` | `open("daten.txt", "r")` |
| **Lesen** | Inhalt aus Datei lesen | `read()`, `readline()`, `readlines()` | `inhalt = datei.read()` |
| **Schreiben** | Inhalt in Datei schreiben | `write()`, `writelines()` | `datei.write("Text")` |
| **Schließen** | Datei schließen | `close()` | `datei.close()` |
| **with-Statement** | Automatisches Schließen | `with open(...) as datei:` | Sicherer Umgang |
| **Modi** | r (read), w (write), a (append) | `"r"`, `"w"`, `"a"` | Zugriffsart |

**Visuelle Darstellung:**
```
Dateioperationen:
    Öffnen → Lesen/Schreiben → Schließen
    
    with open("datei.txt", "r") as datei:
        inhalt = datei.read()
    # Datei wird automatisch geschlossen
```

**Praxis-Beispiel:**
```python
# Daten in Datei schreiben
with open("noten.txt", "w") as datei:
    noten = [85, 90, 78, 92, 88]
    for note in noten:
        datei.write(f"{note}\n")

# Daten aus Datei lesen
try:
    with open("noten.txt", "r") as datei:
        zeilen = datei.readlines()
        noten_gelesen = []
        for zeile in zeilen:
            # Zeilenumbruch entfernen und zu Zahl konvertieren
            noten_gelesen.append(int(zeile.strip()))
    
    print("Gelesene Noten:", noten_gelesen)
    print("Durchschnitt:", sum(noten_gelesen) / len(noten_gelesen))
    
except FileNotFoundError:
    print("Fehler: Datei nicht gefunden!")
except ValueError:
    print("Fehler: Ungültige Daten in Datei!")

# Daten an Datei anhängen
with open("noten.txt", "a") as datei:
    datei.write("95\n")
```

**Prüfungscheck:**
**Frage:** Schreiben Sie ein Python-Programm, das eine Liste von Namen in eine Datei "namen.txt" schreibt und anschließend wieder einliest.

**Antwort:**
```python
# Namen in Datei schreiben
namen = ["Anna", "Max", "Lisa", "Tom"]

with open("namen.txt", "w") as datei:
    for name in namen:
        datei.write(f"{name}\n")

# Namen aus Datei lesen
try:
    with open("namen.txt", "r") as datei:
        gelesene_namen = []
        for zeile in datei:
            gelesene_namen.append(zeile.strip())
    
    print("Gelesene Namen:", gelesene_namen)
    
except FileNotFoundError:
    print("Fehler: Datei nicht gefunden!")
```

**Merksatz:**
"with open() = sicher öffnen/schließen, r/w/a = lesen/schreiben/anhängen, Exception = Fehler abfangen!"

---

## Zusammenfassung: Wichtige Prüfungsfragen

### Kapitel 5.5: Anforderungsspezifikation und Softwareplanung
1. **Was ist der Unterschied zwischen Lasten- und Pflichtenheft?**
   - Lastenheft: Auftraggeber, WAS gewünscht wird
   - Pflichtenheft: Auftragnehmer, WIE umgesetzt wird

2. **Nennen Sie die Phasen des Entwurfsprozesses.**
   - Systementwurf → Komponentenentwurf → Datenmodellierung → Schnittstellendesign → UI-Design

3. **Welche UML-Diagrammtypen kennen Sie?**
   - Use Case, Klassendiagramm, Sequenzdiagramm, Aktivitätsdiagramm

### Kapitel 5.6: Programmiersprachen und -werkzeuge
1. **Unterscheiden Sie statische und dynamische Typisierung.**
   - Statisch: Typ muss deklariert werden (Java, C)
   - Dynamisch: Typ wird zur Laufzeit bestimmt (Python, JavaScript)

2. **Was ist der Unterschied zwischen Framework und Bibliothek?**
   - Framework: Struktur vorgegeben (Inversion of Control)
   - Bibliothek: Funktionen nutzen, Entwickler kontrolliert Ablauf

### Kapitel 5.7: Python-Implementierung
1. **Wie werden Code-Blöcke in Python definiert?**
   - Durch Einrückung (4 Leerzeichen), nicht durch Klammern

2. **Wie fängt man Exceptions in Python ab?**
   - Mit try-except-Blöcken, optional finally

3. **Wie iteriert man über eine Liste in Python?**
   - `for element in liste:` oder `for i in range(len(liste)):`

4. **Wie öffnet man eine Datei sicher in Python?**
   - Mit `with open(dateiname, modus) as datei:` - schließt automatisch

---

**Viel Erfolg bei der Klassenarbeit! 🎓**

