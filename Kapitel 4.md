# 4: Schutzbedarfsanalyse im eigenen Arbeitsbereich durchführen

**Kurz-Definition:**
Die Schutzbedarfsanalyse ist ein systematischer Prozess zur Ermittlung des erforderlichen Schutzniveaus für Informationen und IT-Systeme im Arbeitsbereich. Sie bildet die Grundlage für die Auswahl und Umsetzung angemessener Sicherheitsmaßnahmen.

**Tabellarische Übersicht:**

| Aspekt | Beschreibung | Bedeutung |
|--------|--------------|-----------|
| **Ziel** | Schutzbedarf für Informationen und Systeme ermitteln | Angemessene Sicherheitsmaßnahmen wählen |
| **Vorgehen** | Systematische Analyse nach BSI-Grundschutz | Strukturierte Herangehensweise |
| **Ergebnis** | Schutzbedarfsfeststellung mit Klassifizierung | Basis für Sicherheitskonzept |
| **Anwendung** | Arbeitsplatzsoftware, Clients, Datenträger | Praktische Umsetzung im Arbeitsbereich |

**Visuelle Darstellung:**
```
Schutzbedarfsanalyse-Prozess:
┌─────────────────┐
│  Informations-  │
│   sammlung      │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│  Gefährdungs-   │
│   analyse       │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│  Schadens-      │
│   bewertung     │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│  Schutzbedarfs- │
│   feststellung  │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│  Maßnahmen-     │
│   auswahl       │
└─────────────────┘
```

**Praxis-Beispiel:**
Ein Unternehmen analysiert den Schutzbedarf für die Personalabteilung: Die dort verarbeiteten personenbezogenen Daten (Gehaltsabrechnungen, Bewerbungen) haben einen hohen Schutzbedarf hinsichtlich Vertraulichkeit. Bei Verlust oder unbefugtem Zugriff drohen rechtliche Konsequenzen (DSGVO) und Reputationsschäden. Daher werden verschlüsselte Speicherung, Zugriffskontrollen und regelmäßige Backups als Maßnahmen festgelegt.

**Prüfungscheck:**
**Frage:** Was ist das Hauptziel einer Schutzbedarfsanalyse im Arbeitsbereich?

**Antwort:** Das Hauptziel ist die systematische Ermittlung des erforderlichen Schutzniveaus für Informationen und IT-Systeme, um darauf aufbauend angemessene und wirtschaftlich vertretbare Sicherheitsmaßnahmen auswählen und umsetzen zu können.

**Merksatz:**
"Schutzbedarfsanalyse = Gefährdungen erkennen → Schäden bewerten → Schutzbedarf feststellen → Maßnahmen wählen!"

---

## 4.1: Grundlagen zur Informationssicherheit erarbeiten

**Kurz-Definition:**
Informationssicherheit umfasst alle Maßnahmen zum Schutz von Informationen vor Gefährdungen. Sie gewährleistet die drei Schutzziele Vertraulichkeit, Integrität und Verfügbarkeit von Informationen und IT-Systemen.

**Tabellarische Übersicht:**

| Aspekt | Beschreibung | Bedeutung |
|--------|--------------|-----------|
| **Schutzziele** | Vertraulichkeit, Integrität, Verfügbarkeit | Grundpfeiler der IT-Sicherheit |
| **Verantwortung** | Management, IT-Sicherheitsbeauftragter, Mitarbeiter | Klare Zuständigkeiten erforderlich |
| **Standards** | ISO 27001, BSI-Grundschutz, IT-Grundschutz-Kompendium | Bewährte Vorgehensweisen |
| **Bedrohungen** | Cyberangriffe, Social Engineering, Malware | Aktuelle Gefahrenlage |

**Prüfungscheck:**
**Frage:** Nennen Sie die drei grundlegenden Schutzziele der Informationssicherheit.

**Antwort:**
1. **Vertraulichkeit:** Informationen sind nur für berechtigte Personen zugänglich
2. **Integrität:** Informationen sind unverändert und vollständig
3. **Verfügbarkeit:** Informationen und Systeme sind bei Bedarf nutzbar

**Merksatz:**
"Informationssicherheit = Vertraulichkeit + Integrität + Verfügbarkeit - die drei Säulen des Schutzes!"

---

### 4.1.1: Einführung, Verantwortung, Zuständigkeiten und Sicherheitsbereiche beschreiben

**Kurz-Definition:**
Informationssicherheit erfordert klare Verantwortlichkeiten und Zuständigkeiten auf allen Ebenen einer Organisation. Sicherheitsbereiche strukturieren die Organisation und helfen bei der systematischen Umsetzung von Sicherheitsmaßnahmen.

**Tabellarische Übersicht:**

| Ebene | Verantwortung | Aufgaben |
|-------|---------------|----------|
| **Geschäftsführung** | Gesamtverantwortung | Sicherheitsleitlinie, Ressourcen bereitstellen |
| **IT-Sicherheitsbeauftragter** | Operative Umsetzung | Sicherheitskonzept, Maßnahmen koordinieren |
| **Abteilungsleiter** | Bereichsverantwortung | Umsetzung in ihrem Bereich, Mitarbeiterschulung |
| **Mitarbeiter** | Einhaltung von Regeln | Sicherheitsrichtlinien befolgen, Vorfälle melden |
| **IT-Abteilung** | Technische Umsetzung | Systeme absichern, Monitoring, Incident Response |

**Sicherheitsbereiche (BSI-Grundschutz):**

| Bereich | Beispiele | Schutzbedarf |
|---------|-----------|--------------|
| **Organisation** | Sicherheitsleitlinie, Notfallmanagement | Grundlegend |
| **Personal** | Einstellung, Schulung, Kündigung | Hoch |
| **IT-Systeme** | Server, Clients, Netzwerk | Hoch |
| **Kommunikation** | E-Mail, Internet, VPN | Hoch |
| **Infrastruktur** | Gebäude, Stromversorgung | Mittel |

**Visuelle Darstellung:**
```
Verantwortungshierarchie:
┌─────────────────────────────┐
│   Geschäftsführung          │
│   (Gesamtverantwortung)     │
└──────────────┬──────────────┘
               │
       ┌───────┴───────┐
       │               │
┌──────▼──────┐  ┌─────▼──────┐
│ IT-Sicher-  │  │ Abteilungs- │
│ heits-      │  │ leiter      │
│ beauftragter│  └─────┬───────┘
└──────┬──────┘        │
       │               │
┌──────▼──────┐  ┌─────▼──────┐
│ IT-Abteilung│  │ Mitarbeiter │
└─────────────┘  └─────────────┘
```

**Praxis-Beispiel:**
In einem mittelständischen Unternehmen ist der Geschäftsführer für die Informationssicherheit verantwortlich. Er ernennt einen IT-Sicherheitsbeauftragten, der das Sicherheitskonzept erstellt. Die Abteilungsleiter sorgen für die Umsetzung in ihren Bereichen und schulen ihre Mitarbeiter. Die IT-Abteilung setzt technische Maßnahmen um (Firewall, Virenschutz, Backups). Alle Mitarbeiter müssen Sicherheitsrichtlinien befolgen und Vorfälle melden.

**Prüfungscheck:**
**Frage:** Welche Verantwortlichkeiten hat die Geschäftsführung im Bereich der Informationssicherheit?

**Antwort:** Die Geschäftsführung trägt die Gesamtverantwortung für die Informationssicherheit. Sie muss die Sicherheitsleitlinie erlassen, ausreichende Ressourcen bereitstellen, den IT-Sicherheitsbeauftragten ernennen und regelmäßig über den Sicherheitsstatus informiert werden.

**Merksatz:**
"Verantwortung = Geschäftsführung (Gesamt) → IT-Sicherheitsbeauftragter (Operativ) → Abteilungen (Umsetzung) → Mitarbeiter (Einhaltung)!"

---

### 4.1.2: Gesetze und Standards zur Informationssicherheit unterscheiden

**Kurz-Definition:**
Gesetze sind rechtlich bindende Vorschriften, die Unternehmen einhalten müssen. Standards sind bewährte Vorgehensweisen und Best Practices, die freiwillig angewendet werden können, aber oft als Maßstab dienen.

**Tabellarische Übersicht:**

| Kategorie | Name | Art | Geltungsbereich | Hauptinhalt |
|-----------|------|-----|-----------------|-------------|
| **Gesetz** | DSGVO | EU-Verordnung | EU-weit | Datenschutz, personenbezogene Daten |
| **Gesetz** | BDSG | Bundesgesetz | Deutschland | Ergänzung zur DSGVO |
| **Gesetz** | IT-Sicherheitsgesetz | Bundesgesetz | Kritische Infrastrukturen | IT-Sicherheitsanforderungen |
| **Standard** | ISO/IEC 27001 | International | Weltweit | ISMS (Information Security Management System) |
| **Standard** | BSI-Grundschutz | National | Deutschland | IT-Grundschutz-Kompendium, Bausteine |
| **Standard** | ITIL | International | Weltweit | IT-Service-Management |
| **Standard** | COBIT | International | Weltweit | IT-Governance und -Management |

**Unterschiede:**

| Aspekt | Gesetze | Standards |
|--------|---------|-----------|
| **Bindung** | Rechtlich verpflichtend | Freiwillig, aber empfohlen |
| **Konsequenzen** | Bußgelder, Strafen | Keine rechtlichen Konsequenzen |
| **Zertifizierung** | Nicht möglich | Zertifizierung möglich (z.B. ISO 27001) |
| **Flexibilität** | Vorgegeben | Anpassbar an Organisation |
| **Zweck** | Rechtssicherheit, Schutz | Best Practices, Qualität |

**Visuelle Darstellung:**
```
Gesetze vs. Standards:
┌─────────────────────────────────┐
│         Gesetze                 │
│  (Rechtlich bindend)            │
├─────────────────────────────────┤
│ • DSGVO                         │
│ • BDSG                          │
│ • IT-Sicherheitsgesetz          │
│                                 │
│  ⚠️ Bei Nichteinhaltung:        │
│  Bußgelder, Strafen             │
└─────────────────────────────────┘

┌─────────────────────────────────┐
│         Standards               │
│  (Freiwillig, Best Practices)   │
├─────────────────────────────────┤
│ • ISO 27001                     │
│ • BSI-Grundschutz               │
│ • ITIL, COBIT                   │
│                                 │
│  ✓ Zertifizierung möglich       │
│  ✓ Anpassbar an Organisation    │
└─────────────────────────────────┘
```

**Praxis-Beispiel:**
Ein Unternehmen muss die DSGVO einhalten (Gesetz), da es personenbezogene Daten verarbeitet. Bei Verstößen drohen Bußgelder bis zu 4% des Jahresumsatzes. Zusätzlich entscheidet sich das Unternehmen, nach ISO 27001 zertifizieren zu lassen (Standard), um Kunden zu zeigen, dass es hohe Sicherheitsstandards einhält. Die Zertifizierung ist freiwillig, aber ein Wettbewerbsvorteil.

**Prüfungscheck:**
**Frage:** Was ist der Hauptunterschied zwischen Gesetzen und Standards im Bereich der Informationssicherheit?

**Antwort:** Gesetze sind rechtlich bindend und müssen eingehalten werden - bei Verstößen drohen Bußgelder oder Strafen. Standards sind freiwillige Best Practices, die angewendet werden können, um Sicherheit und Qualität zu verbessern. Standards können zertifiziert werden, bieten aber keine rechtliche Absicherung.

**Merksatz:**
"Gesetze = Muss (rechtlich bindend) | Standards = Soll (Best Practices) - beide wichtig für Sicherheit!"

---

### 4.1.3: IT-Grundschutz, Schutzziele, Gefährdungen, Schadensszenarien unterscheiden

**Kurz-Definition:**
IT-Grundschutz ist eine Methodik des BSI zur systematischen Absicherung von IT-Systemen. Schutzziele definieren, was geschützt werden soll. Gefährdungen sind potenzielle Bedrohungen, Schadensszenarien beschreiben konkrete Schadensfälle.

**Tabellarische Übersicht:**

**Schutzziele (CIA-Triade):**

| Schutzziel | Definition | Beispiel |
|------------|------------|----------|
| **Vertraulichkeit (Confidentiality)** | Informationen sind nur für Berechtigte zugänglich | Verschlüsselung, Zugriffskontrollen |
| **Integrität (Integrity)** | Informationen sind unverändert und vollständig | Digitale Signaturen, Checksummen |
| **Verfügbarkeit (Availability)** | Informationen und Systeme sind bei Bedarf nutzbar | Redundanz, Backups, Notfallplanung |

**Gefährdungen (Beispiele):**

| Kategorie | Gefährdung | Betroffenes Schutzziel |
|-----------|------------|------------------------|
| **Technisch** | Malware, Hackerangriffe | Vertraulichkeit, Integrität |
| **Organisatorisch** | Fehlende Richtlinien, ungeschulte Mitarbeiter | Alle Schutzziele |
| **Personell** | Innentäter, Social Engineering | Vertraulichkeit, Integrität |
| **Physisch** | Feuer, Wasser, Diebstahl | Verfügbarkeit, Vertraulichkeit |
| **Extern** | Naturkatastrophen, Stromausfall | Verfügbarkeit |

**Schadensszenarien:**

| Szenario | Auswirkung | Schutzziele betroffen |
|----------|------------|----------------------|
| **Datenleck** | Unbefugter Zugriff auf Kundendaten | Vertraulichkeit |
| **Ransomware** | Systeme verschlüsselt, Erpressung | Verfügbarkeit, Integrität |
| **Datenmanipulation** | Gehaltsabrechnungen verändert | Integrität |
| **DDoS-Angriff** | Server nicht erreichbar | Verfügbarkeit |
| **Phishing** | Zugangsdaten gestohlen | Vertraulichkeit |

**IT-Grundschutz-Methodik:**

| Phase | Beschreibung |
|-------|--------------|
| **Strukturanalyse** | IT-Landschaft analysieren, Bausteine zuordnen |
| **Schutzbedarfsfeststellung** | Schutzbedarf für Informationen ermitteln |
| **Modellierung** | IT-Grundschutz-Bausteine auswählen |
| **Umsetzung** | Maßnahmen umsetzen |
| **Wartung** | Regelmäßige Überprüfung und Anpassung |

**Visuelle Darstellung:**
```
Schutzziele (CIA-Triade):
        ┌──────────────┐
        │ Vertraulich- │
        │    keit     │
        └──────┬───────┘
               │
    ┌──────────┴──────────┐
    │                     │
┌───▼────┐          ┌─────▼───┐
│Integri-│          │Verfüg-  │
│  tät   │          │barkeit   │
└────────┘          └──────────┘

IT-Grundschutz-Prozess:
Strukturanalyse → Schutzbedarfsfeststellung 
→ Modellierung → Umsetzung → Wartung
```

**Praxis-Beispiel:**
Ein Unternehmen nutzt IT-Grundschutz zur Absicherung: In der Strukturanalyse werden alle IT-Systeme erfasst (Server, Clients, Netzwerk). Bei der Schutzbedarfsfeststellung wird ermittelt, dass Kundendaten einen hohen Schutzbedarf hinsichtlich Vertraulichkeit haben. Als Gefährdung wird "unbefugter Zugriff" identifiziert. Das Schadensszenario wäre: Ein Hacker stiehlt Kundendaten → DSGVO-Verstoß → Bußgeld und Reputationsschaden. Als Maßnahme werden Verschlüsselung und Zugriffskontrollen umgesetzt.

**Prüfungscheck:**
**Frage:** Erklären Sie die drei Schutzziele der Informationssicherheit und nennen Sie jeweils eine Maßnahme.

**Antwort:**
1. **Vertraulichkeit:** Informationen sind nur für Berechtigte zugänglich. Maßnahme: Verschlüsselung von Daten.
2. **Integrität:** Informationen sind unverändert und vollständig. Maßnahme: Digitale Signaturen oder Checksummen.
3. **Verfügbarkeit:** Informationen und Systeme sind bei Bedarf nutzbar. Maßnahme: Redundante Systeme oder regelmäßige Backups.

**Merksatz:**
"CIA = Confidentiality (Vertraulichkeit) + Integrity (Integrität) + Availability (Verfügbarkeit) - die drei Schutzziele!"

---

### 4.1.4: Aktuelle Bedrohungen zur IT-Sicherheit von Unternehmen präsentieren

**Kurz-Definition:**
Aktuelle Bedrohungen zur IT-Sicherheit umfassen vielfältige Angriffsformen wie Ransomware, Phishing, DDoS-Angriffe und Advanced Persistent Threats (APT). Die Bedrohungslage entwickelt sich ständig weiter und erfordert aktive Abwehrmaßnahmen.

**Tabellarische Übersicht:**

| Bedrohung | Beschreibung | Häufigkeit | Schadenspotenzial | Betroffene Schutzziele |
|-----------|--------------|------------|-------------------|------------------------|
| **Ransomware** | Verschlüsselung von Daten, Erpressung | Sehr hoch | Sehr hoch | Verfügbarkeit, Integrität |
| **Phishing** | Betrügerische E-Mails zur Datenerlangung | Sehr hoch | Hoch | Vertraulichkeit |
| **DDoS-Angriffe** | Überlastung von Servern durch viele Anfragen | Hoch | Mittel-Hoch | Verfügbarkeit |
| **Malware** | Schadsoftware (Viren, Trojaner, Spyware) | Sehr hoch | Hoch | Alle Schutzziele |
| **Social Engineering** | Manipulation von Personen | Hoch | Hoch | Vertraulichkeit |
| **APT (Advanced Persistent Threats)** | Langfristige, gezielte Angriffe | Mittel | Sehr hoch | Alle Schutzziele |
| **Insider Threats** | Bedrohungen von innen | Mittel | Hoch | Alle Schutzziele |
| **Supply Chain Attacks** | Angriffe über Lieferanten/Partner | Steigend | Hoch | Alle Schutzziele |
| **Zero-Day-Exploits** | Ausnutzung unbekannter Schwachstellen | Mittel | Sehr hoch | Alle Schutzziele |
| **Cloud-Sicherheit** | Fehlkonfigurationen, Datenlecks | Hoch | Hoch | Vertraulichkeit |

**Trends 2024/2025:**

| Trend | Beschreibung |
|-------|--------------|
| **KI-gestützte Angriffe** | Künstliche Intelligenz für effektivere Angriffe |
| **Ransomware-as-a-Service** | Ransomware wird als Dienstleistung angeboten |
| **IoT-Angriffe** | Angriffe auf vernetzte Geräte |
| **Mobile Bedrohungen** | Zunehmende Angriffe auf mobile Geräte |
| **Deepfakes** | Gefälschte Audio/Video-Inhalte für Social Engineering |

**Visuelle Darstellung:**
```
Bedrohungslandschaft:
┌─────────────────────────────────────┐
│     Externe Bedrohungen             │
│  ┌──────────┐  ┌──────────┐        │
│  │Ransomware│  │ Phishing  │        │
│  └──────────┘  └──────────┘        │
│  ┌──────────┐  ┌──────────┐        │
│  │   DDoS   │  │ Malware  │        │
│  └──────────┘  └──────────┘        │
└─────────────────────────────────────┘
              │
              ▼
┌─────────────────────────────────────┐
│         Unternehmen                 │
│  ┌──────────────────────────────┐   │
│  │  Schutzmaßnahmen:            │   │
│  │  • Firewall                  │   │
│  │  • Virenschutz               │   │
│  │  • Schulungen                │   │
│  │  • Backups                   │   │
│  └──────────────────────────────┘   │
└─────────────────────────────────────┘
              │
              ▼
┌─────────────────────────────────────┐
│     Interne Bedrohungen             │
│  • Insider Threats                  │
│  • Fehlkonfigurationen              │
│  • Unachtsamkeit                    │
└─────────────────────────────────────┘
```

**Praxis-Beispiel:**
Ein mittelständisches Unternehmen wird Opfer einer Ransomware-Attacke: Ein Mitarbeiter öffnet einen Phishing-Anhang, wodurch Ransomware auf das System gelangt. Alle Server und Clients werden verschlüsselt. Die Angreifer fordern 50.000 € Bitcoin. Das Unternehmen hat Backups, aber die Wiederherstellung dauert 3 Tage. In dieser Zeit ist der Geschäftsbetrieb stark eingeschränkt. Kosten: Lösegeld (nicht gezahlt) + Ausfallzeit + Reputationsschaden + Wiederherstellungskosten.

**Prüfungscheck:**
**Frage:** Nennen Sie drei aktuelle Bedrohungen zur IT-Sicherheit und beschreiben Sie jeweils kurz, wie sie funktionieren.

**Antwort:**
1. **Ransomware:** Schadsoftware verschlüsselt Daten auf dem System. Angreifer fordern Lösegeld für die Entschlüsselung. Verbreitung oft über Phishing-E-Mails.
2. **Phishing:** Betrügerische E-Mails, die vorgeben, von vertrauenswürdigen Absendern zu stammen. Ziel: Zugangsdaten oder persönliche Informationen stehlen.
3. **DDoS-Angriffe:** Distributed Denial of Service - viele infizierte Computer senden gleichzeitig Anfragen an einen Server, um ihn zu überlasten und unerreichbar zu machen.

**Merksatz:**
"Bedrohungen = Ransomware (Verschlüsselung) + Phishing (Betrug) + DDoS (Überlastung) - ständig wachsam bleiben!"

---

### 4.1.5: Identitätsdiebstahl und Social Engineering begegnen

**Kurz-Definition:**
Identitätsdiebstahl ist die unbefugte Nutzung persönlicher Daten einer anderen Person. Social Engineering nutzt menschliche Schwächen (Vertrauen, Neugier, Angst) statt technischer Schwachstellen, um an Informationen zu gelangen.

**Tabellarische Übersicht:**

**Identitätsdiebstahl:**

| Methode | Beschreibung | Beispiel |
|---------|--------------|----------|
| **Phishing** | Gefälschte E-Mails/Websites | E-Mail von "Bank" zur Passwortänderung |
| **Pharming** | Umleitung auf gefälschte Websites | DNS-Manipulation |
| **Skimming** | Auslesen von Karten-Daten | Manipulierte Geldautomaten |
| **Datenlecks** | Nutzung gestohlener Daten | Nutzung von Daten aus Hacks |
| **Shoulder Surfing** | Ablesen von Eingaben | Passwort beim Tippen beobachten |

**Social Engineering - Angriffsmethoden:**

| Methode | Beschreibung | Beispiel |
|---------|--------------|----------|
| **Pretexting** | Erfinden einer falschen Identität | Anruf als "IT-Support" |
| **Baiting** | Köder mit verlockendem Angebot | USB-Stick mit "Gehaltsliste" |
| **Quid Pro Quo** | Gegenleistung versprechen | "Gratis-Software" gegen Daten |
| **Tailgating** | Unbefugtes Mitgehen | Hinter Mitarbeiter durch Tür |
| **Phishing** | Betrügerische Kommunikation | E-Mail mit dringender Aufforderung |
| **Spear Phishing** | Gezieltes Phishing auf Person/Gruppe | Personalisierte E-Mail an CFO |
| **Whaling** | Angriff auf Führungskräfte | CEO-Fraud, gefälschte Anweisungen |

**Abwehrmaßnahmen:**

| Maßnahme | Beschreibung | Wirksamkeit |
|----------|--------------|-------------|
| **Schulungen** | Sensibilisierung der Mitarbeiter | Sehr hoch |
| **Zwei-Faktor-Authentifizierung** | Zusätzliche Sicherheitsebene | Sehr hoch |
| **Richtlinien** | Klare Regeln für Datenweitergabe | Hoch |
| **Vier-Augen-Prinzip** | Bestätigung bei kritischen Aktionen | Hoch |
| **Vorsicht bei Anhängen** | Keine unbekannten Dateien öffnen | Hoch |
| **Quellenprüfung** | Identität von Anrufern prüfen | Mittel-Hoch |
| **Phishing-Filter** | Technische Erkennung | Mittel |

**Visuelle Darstellung:**
```
Social Engineering Angriff:
Angreifer → Kontaktaufnahme (E-Mail/Anruf)
    ↓
Vertrauen aufbauen (falsche Identität)
    ↓
Informationen anfordern (dringend/wichtig)
    ↓
Opfer gibt Informationen preis
    ↓
Angreifer nutzt Informationen
    ↓
Schaden (Zugriff, Datenklau, etc.)

Abwehr:
Schulung → Vorsicht → Prüfung → Verweigerung
```

**Praxis-Beispiel:**
Ein Mitarbeiter erhält eine E-Mail, die scheinbar vom Geschäftsführer stammt (gefälschte Absenderadresse). Die E-Mail ist dringend formuliert und fordert die sofortige Überweisung von 10.000 € auf ein Konto wegen einer "wichtigen Geschäftstransaktion". Der Mitarbeiter ist unsicher, ruft aber den Geschäftsführer an und stellt fest, dass dieser die E-Mail nicht geschickt hat. Durch die Rückfrage wurde der Angriff abgewehrt. Hätte der Mitarbeiter nicht nachgefragt, wäre das Geld verloren gewesen.

**Prüfungscheck:**
**Frage:** Was ist Social Engineering und welche drei Abwehrmaßnahmen können dagegen ergriffen werden?

**Antwort:**
Social Engineering ist die Manipulation von Personen, um an vertrauliche Informationen zu gelangen, statt technische Schwachstellen auszunutzen. Drei Abwehrmaßnahmen:
1. **Schulungen:** Mitarbeiter für Social Engineering sensibilisieren und typische Angriffsmuster erklären
2. **Zwei-Faktor-Authentifizierung:** Auch wenn Zugangsdaten gestohlen werden, ist zusätzliche Bestätigung nötig
3. **Quellenprüfung:** Bei ungewöhnlichen Anfragen (z.B. Überweisungen) immer die Identität des Absenders prüfen (Rückfrage per Telefon)

**Merksatz:**
"Social Engineering = Angriff auf den Menschen, nicht die Technik - Vorsicht, Prüfung und Schulung schützen!"

---

## 4.2: Technisch-organisatorische Maßnahmen und Beiträge zum Sicherheitskonzept erstellen

**Kurz-Definition:**
Technisch-organisatorische Maßnahmen (TOM) kombinieren technische Sicherheitsmaßnahmen (z.B. Verschlüsselung, Firewall) mit organisatorischen Maßnahmen (z.B. Richtlinien, Schulungen). Ein Sicherheitskonzept dokumentiert alle Maßnahmen systematisch.

**Tabellarische Übersicht:**

**Technische Maßnahmen:**

| Maßnahme | Beschreibung | Beispiel |
|----------|--------------|----------|
| **Verschlüsselung** | Daten unlesbar machen | TLS für E-Mail, BitLocker für Festplatten |
| **Firewall** | Netzwerkzugriff kontrollieren | Paketfilter, Application Firewall |
| **Virenschutz** | Malware erkennen und blockieren | Antivirus-Software, EDR-Systeme |
| **Zugriffskontrollen** | Berechtigungen verwalten | Benutzerkonten, Rollen, ACLs |
| **Backups** | Daten sichern | Regelmäßige Backups, Offsite-Speicherung |
| **Monitoring** | Systeme überwachen | Logging, SIEM-Systeme |
| **Patch-Management** | Sicherheitsupdates einspielen | Regelmäßige Updates, Testumgebung |

**Organisatorische Maßnahmen:**

| Maßnahme | Beschreibung | Beispiel |
|----------|--------------|----------|
| **Richtlinien** | Schriftliche Regeln | Passwortrichtlinie, Nutzungsordnung |
| **Schulungen** | Mitarbeiter sensibilisieren | Sicherheitsschulungen, Awareness-Training |
| **Notfallplanung** | Vorgehen bei Vorfällen | Incident Response Plan, BCM |
| **Zugriffsverwaltung** | Prozesse für Berechtigungen | Onboarding, Offboarding, Vier-Augen-Prinzip |
| **Dokumentation** | Maßnahmen dokumentieren | Sicherheitskonzept, Verfahrensdokumentation |
| **Audits** | Regelmäßige Überprüfung | Interne Audits, Penetrationstests |

**Sicherheitskonzept - Struktur:**

| Abschnitt | Inhalt |
|-----------|--------|
| **Sicherheitsleitlinie** | Grundsätze und Ziele der Informationssicherheit |
| **Risikoanalyse** | Identifizierte Risiken und Bewertung |
| **Schutzbedarfsfeststellung** | Klassifizierung von Informationen |
| **Maßnahmenkatalog** | Technische und organisatorische Maßnahmen |
| **Verantwortlichkeiten** | Zuständigkeiten und Rollen |
| **Notfallplanung** | Vorgehen bei Sicherheitsvorfällen |
| **Wartung und Review** | Regelmäßige Überprüfung und Anpassung |

**Visuelle Darstellung:**
```
Sicherheitskonzept:
┌─────────────────────────────────────┐
│     Sicherheitsleitlinie             │
│     (Grundsätze, Ziele)              │
└──────────────┬──────────────────────┘
               │
       ┌───────┴───────┐
       │               │
┌──────▼──────┐  ┌─────▼──────┐
│ Risiko-     │  │ Schutz-    │
│ analyse     │  │ bedarfs-   │
│             │  │ feststellung│
└──────┬──────┘  └─────┬───────┘
       │               │
       └───────┬───────┘
               │
       ┌───────▼───────┐
       │ Maßnahmen-    │
       │ katalog       │
       ├───────────────┤
       │ Technisch     │
       │ Organisatorisch│
       └───────────────┘
```

**Praxis-Beispiel:**
Ein Unternehmen erstellt ein Sicherheitskonzept: Die Sicherheitsleitlinie definiert, dass alle personenbezogenen Daten besonders geschützt werden müssen. In der Risikoanalyse wird identifiziert, dass unverschlüsselte E-Mails ein Risiko darstellen. Als technische Maßnahme wird TLS-Verschlüsselung für E-Mails eingeführt. Als organisatorische Maßnahme wird eine Richtlinie erstellt, die regelt, dass vertrauliche Daten nur verschlüsselt versendet werden dürfen. Mitarbeiter werden geschult, wie sie E-Mails verschlüsseln. Das alles wird im Sicherheitskonzept dokumentiert.

**Prüfungscheck:**
**Frage:** Was sind technisch-organisatorische Maßnahmen und warum sind beide wichtig?

**Antwort:**
Technisch-organisatorische Maßnahmen kombinieren technische Sicherheitslösungen (z.B. Verschlüsselung, Firewall) mit organisatorischen Regelungen (z.B. Richtlinien, Schulungen). Beide sind wichtig, weil:
- **Technische Maßnahmen** allein nutzlos sind, wenn Mitarbeiter sie umgehen oder falsch nutzen
- **Organisatorische Maßnahmen** allein nicht ausreichen, wenn technische Schwachstellen bestehen
- Nur die Kombination beider schafft umfassenden Schutz (Defense in Depth)

**Merksatz:**
"TOM = Technisch + Organisatorisch - beide zusammen schaffen umfassenden Schutz!"

---

## 4.3: Schutzbedarfsfeststellungen anhand eines Beispielunternehmens des BSI vorbereiten

**Kurz-Definition:**
Die Schutzbedarfsfeststellung ermittelt den erforderlichen Schutz für Informationen und IT-Systeme. Anhand von Beispielunternehmen des BSI kann der Prozess strukturiert erlernt und angewendet werden.

**Tabellarische Übersicht:**

| Aspekt | Beschreibung | Bedeutung |
|--------|--------------|-----------|
| **Ziel** | Schutzbedarf für Informationen klassifizieren | Angemessene Maßnahmen wählen |
| **Klassifizierung** | Normal, Hoch, Sehr Hoch | Abstufung des Schutzniveaus |
| **Kriterien** | Vertraulichkeit, Integrität, Verfügbarkeit | Bewertungsgrundlage |
| **Beispielunternehmen** | BSI-Vorlagen (z.B. Handelsunternehmen) | Praktische Anwendung |

**Schutzbedarfsklassen:**

| Klasse | Beschreibung | Beispiel |
|--------|--------------|----------|
| **Normal** | Keine besonderen Anforderungen | Öffentliche Informationen |
| **Hoch** | Erhebliche Schäden bei Verlust | Geschäftsdaten, Kundenstamm |
| **Sehr Hoch** | Existenzbedrohende Schäden | Geheimhaltungspflichtige Daten, kritische Systeme |

**Prüfungscheck:**
**Frage:** Was ist das Ziel einer Schutzbedarfsfeststellung?

**Antwort:** Das Ziel ist die systematische Ermittlung und Klassifizierung des erforderlichen Schutzniveaus für Informationen und IT-Systeme, um darauf aufbauend angemessene und wirtschaftlich vertretbare Sicherheitsmaßnahmen auswählen zu können.

**Merksatz:**
"Schutzbedarfsfeststellung = Informationen klassifizieren (Normal/Hoch/Sehr Hoch) → Maßnahmen ableiten!"

---

### 4.3.1: Phasen des Sicherheitsprozesses nach dem BSI-Grundschutz beschreiben

**Kurz-Definition:**
Der BSI-Grundschutz definiert einen strukturierten Sicherheitsprozess in mehreren Phasen, von der Strukturanalyse bis zur kontinuierlichen Verbesserung. Dieser Prozess gewährleistet eine systematische Absicherung von IT-Systemen.

**Tabellarische Übersicht:**

| Phase | Beschreibung | Aktivitäten | Ergebnis |
|-------|--------------|-------------|----------|
| **1. Strukturanalyse** | IT-Landschaft analysieren | Systeme erfassen, Bausteine zuordnen | Strukturübersicht |
| **2. Schutzbedarfsfeststellung** | Schutzbedarf ermitteln | Informationen klassifizieren | Schutzbedarfsmatrix |
| **3. Modellierung** | Bausteine auswählen | IT-Grundschutz-Bausteine zuordnen | Maßnahmenkatalog |
| **4. Basis-Sicherheitscheck** | Lücken identifizieren | Soll-Ist-Vergleich | Maßnahmenplan |
| **5. Umsetzung** | Maßnahmen realisieren | Technische und organisatorische Maßnahmen | Umsetzungsnachweis |
| **6. Wartung** | Kontinuierliche Verbesserung | Regelmäßige Überprüfung, Anpassung | Aktualisiertes Konzept |

**Detaillierte Phasen:**

**Phase 1: Strukturanalyse**
- Alle IT-Systeme erfassen
- Netzwerkstruktur dokumentieren
- Anwendungen und Datenflüsse analysieren
- IT-Grundschutz-Bausteine zuordnen

**Phase 2: Schutzbedarfsfeststellung**
- Informationen identifizieren
- Schutzbedarf für Vertraulichkeit, Integrität, Verfügbarkeit bewerten
- Klassifizierung: Normal, Hoch, Sehr Hoch
- Schutzbedarfsmatrix erstellen

**Phase 3: Modellierung**
- Passende IT-Grundschutz-Bausteine auswählen
- Bausteine an Organisation anpassen
- Maßnahmen aus Bausteinen ableiten
- Maßnahmenkatalog erstellen

**Phase 4: Basis-Sicherheitscheck**
- Aktuelle Sicherheitsmaßnahmen erfassen
- Soll-Ist-Vergleich durchführen
- Lücken identifizieren
- Prioritäten setzen

**Phase 5: Umsetzung**
- Maßnahmen planen
- Technische Maßnahmen umsetzen
- Organisatorische Maßnahmen einführen
- Umsetzung dokumentieren

**Phase 6: Wartung**
- Regelmäßige Überprüfung (mindestens jährlich)
- Änderungen in IT-Landschaft berücksichtigen
- Neue Bedrohungen einbeziehen
- Sicherheitskonzept aktualisieren

**Visuelle Darstellung:**
```
BSI-Grundschutz-Prozess (Zyklus):
         ┌──────────────┐
         │  1. Struktur-│
         │   analyse    │
         └──────┬───────┘
                │
         ┌──────▼───────┐
         │  2. Schutz-  │
         │  bedarfs-    │
         │  feststellung│
         └──────┬───────┘
                │
         ┌──────▼───────┐
         │  3. Modellie-│
         │   rung       │
         └──────┬───────┘
                │
         ┌──────▼───────┐
         │  4. Basis-   │
         │  Sicherheits-│
         │  check       │
         └──────┬───────┘
                │
         ┌──────▼───────┐
         │  5. Umsetzung│
         └──────┬───────┘
                │
         ┌──────▼───────┐
         │  6. Wartung  │
         └──────┬───────┘
                │
                └──────────┐
                           │
         (Kontinuierlicher Prozess)
```

**Praxis-Beispiel:**
Ein Handelsunternehmen führt BSI-Grundschutz ein:
1. **Strukturanalyse:** Erfassung aller Systeme (Server, Clients, Netzwerk, Anwendungen)
2. **Schutzbedarfsfeststellung:** Kundendaten = Hoch (Vertraulichkeit), Lagerverwaltung = Hoch (Verfügbarkeit)
3. **Modellierung:** Bausteine "Client unter Windows", "Server", "LAN" auswählen
4. **Basis-Sicherheitscheck:** Fehlende Firewall, keine Verschlüsselung identifiziert
5. **Umsetzung:** Firewall installiert, Verschlüsselung eingeführt, Richtlinien erstellt
6. **Wartung:** Jährliche Überprüfung, neue Server werden in den Prozess integriert

**Prüfungscheck:**
**Frage:** Nennen Sie die sechs Phasen des BSI-Grundschutz-Prozesses in der richtigen Reihenfolge.

**Antwort:**
1. **Strukturanalyse:** IT-Landschaft analysieren und Bausteine zuordnen
2. **Schutzbedarfsfeststellung:** Schutzbedarf für Informationen ermitteln und klassifizieren
3. **Modellierung:** IT-Grundschutz-Bausteine auswählen und Maßnahmen ableiten
4. **Basis-Sicherheitscheck:** Aktuelle Maßnahmen prüfen und Lücken identifizieren
5. **Umsetzung:** Maßnahmen planen und realisieren
6. **Wartung:** Regelmäßige Überprüfung und kontinuierliche Verbesserung

**Merksatz:**
"BSI-Grundschutz = Struktur → Schutzbedarf → Modellierung → Check → Umsetzung → Wartung - der Sicherheitszyklus!"

---

### 4.3.2: Den Prozess von der Sicherheitsleitlinie zur Schutzbedarfsfeststellung beschreiben

**Kurz-Definition:**
Die Sicherheitsleitlinie ist das strategische Dokument, das Grundsätze und Ziele der Informationssicherheit festlegt. Aus ihr leiten sich alle weiteren Schritte ab, bis hin zur konkreten Schutzbedarfsfeststellung für einzelne Informationen.

**Tabellarische Übersicht:**

| Stufe | Dokument/Prozess | Inhalt | Zweck |
|-------|------------------|--------|-------|
| **1. Sicherheitsleitlinie** | Strategisches Dokument | Grundsätze, Ziele, Verantwortlichkeiten | Rahmen setzen |
| **2. Sicherheitskonzept** | Taktisches Dokument | Risikoanalyse, Maßnahmenkatalog | Umsetzung planen |
| **3. Verfahrensanweisungen** | Operative Dokumente | Konkrete Abläufe, Richtlinien | Praktische Umsetzung |
| **4. Schutzbedarfsfeststellung** | Klassifizierung | Schutzbedarf für Informationen | Maßnahmen ableiten |

**Prozessschritte:**

| Schritt | Aktivität | Ergebnis |
|---------|-----------|----------|
| **1. Sicherheitsleitlinie erstellen** | Management definiert Grundsätze | Schriftliches Dokument |
| **2. Verantwortlichkeiten festlegen** | Rollen und Zuständigkeiten | Organigramm, Jobbeschreibungen |
| **3. Informationen identifizieren** | Alle Informationen erfassen | Informationsinventar |
| **4. Informationen kategorisieren** | Nach Bereichen gruppieren | Kategorien (z.B. Personal, Finanzen) |
| **5. Schutzbedarf bewerten** | Für jede Information: V, I, A | Bewertungsmatrix |
| **6. Schutzbedarf klassifizieren** | Normal, Hoch, Sehr Hoch | Schutzbedarfsmatrix |
| **7. Maßnahmen ableiten** | Aus Schutzbedarf Maßnahmen | Maßnahmenplan |

**Sicherheitsleitlinie - Inhalte:**

| Abschnitt | Inhalt |
|-----------|--------|
| **Zweck und Geltungsbereich** | Warum und für wen gilt die Leitlinie |
| **Grundsätze** | Allgemeine Sicherheitsprinzipien |
| **Schutzziele** | Vertraulichkeit, Integrität, Verfügbarkeit |
| **Verantwortlichkeiten** | Wer ist verantwortlich |
| **Risikomanagement** | Wie werden Risiken behandelt |
| **Compliance** | Welche Gesetze/Standards gelten |

**Visuelle Darstellung:**
```
Prozess von Leitlinie zur Schutzbedarfsfeststellung:
┌─────────────────────────────┐
│  Sicherheitsleitlinie       │
│  (Strategie, Grundsätze)    │
└──────────────┬──────────────┘
               │
               ▼
┌─────────────────────────────┐
│  Sicherheitskonzept          │
│  (Risikoanalyse, Maßnahmen)  │
└──────────────┬──────────────┘
               │
               ▼
┌─────────────────────────────┐
│  Verfahrensanweisungen       │
│  (Konkrete Abläufe)          │
└──────────────┬──────────────┘
               │
               ▼
┌─────────────────────────────┐
│  Schutzbedarfsfeststellung   │
│  (Klassifizierung)           │
└─────────────────────────────┘
```

**Praxis-Beispiel:**
Ein Unternehmen erstellt zuerst eine Sicherheitsleitlinie: "Die Informationssicherheit hat höchste Priorität. Alle personenbezogenen Daten müssen besonders geschützt werden." Aus dieser Leitlinie wird ein Sicherheitskonzept erstellt, das Risiken analysiert. Dann werden Verfahrensanweisungen erstellt, z.B. "Wie werden E-Mails verschlüsselt?". Schließlich wird für jede Information eine Schutzbedarfsfeststellung durchgeführt: Kundendaten haben einen hohen Schutzbedarf hinsichtlich Vertraulichkeit, daher werden Verschlüsselung und Zugriffskontrollen als Maßnahmen festgelegt.

**Prüfungscheck:**
**Frage:** Beschreiben Sie den Prozess von der Sicherheitsleitlinie zur Schutzbedarfsfeststellung.

**Antwort:**
1. **Sicherheitsleitlinie:** Management definiert strategische Grundsätze und Ziele der Informationssicherheit
2. **Sicherheitskonzept:** Auf Basis der Leitlinie werden Risiken analysiert und Maßnahmen geplant
3. **Verfahrensanweisungen:** Konkrete Abläufe und Richtlinien werden dokumentiert
4. **Schutzbedarfsfeststellung:** Für jede Information wird der Schutzbedarf (Vertraulichkeit, Integrität, Verfügbarkeit) bewertet und klassifiziert (Normal/Hoch/Sehr Hoch), um daraus konkrete Maßnahmen abzuleiten

**Merksatz:**
"Leitlinie (Strategie) → Konzept (Planung) → Verfahren (Abläufe) → Schutzbedarf (Klassifizierung) - von oben nach unten!"

---

### 4.3.3: Elemente der Schutzbedarfsfeststellungen im Beispielunternehmen präsentieren

**Kurz-Definition:**
Die Schutzbedarfsfeststellung im Beispielunternehmen umfasst die systematische Erfassung und Bewertung aller Informationen nach ihren Schutzanforderungen. Elemente sind Informationsinventar, Bewertungsmatrix und Klassifizierung.

**Tabellarische Übersicht:**

**Elemente der Schutzbedarfsfeststellung:**

| Element | Beschreibung | Inhalt |
|---------|--------------|--------|
| **Informationsinventar** | Liste aller Informationen | Welche Informationen gibt es? |
| **Informationskategorien** | Gruppierung nach Bereichen | Personal, Finanzen, Kunden, etc. |
| **Bewertungsmatrix** | Schutzbedarf für V, I, A | Vertraulichkeit, Integrität, Verfügbarkeit |
| **Schutzbedarfsmatrix** | Klassifizierung | Normal, Hoch, Sehr Hoch |
| **Schadensbewertung** | Auswirkungen bei Verlust | Finanziell, rechtlich, Reputation |
| **Maßnahmenzuordnung** | Ableitung von Maßnahmen | Welche Maßnahmen sind nötig? |

**Beispiel: Handelsunternehmen**

| Information | Kategorie | Vertraulichkeit | Integrität | Verfügbarkeit | Gesamt |
|-------------|-----------|-----------------|------------|---------------|--------|
| **Kundendaten** | Kunden | Hoch | Hoch | Normal | Hoch |
| **Gehaltsabrechnungen** | Personal | Sehr Hoch | Hoch | Normal | Sehr Hoch |
| **Lagerbestand** | Betrieb | Normal | Hoch | Hoch | Hoch |
| **Öffentliche Website** | Marketing | Normal | Normal | Hoch | Normal |
| **Geschäftsgeheimnisse** | Strategie | Sehr Hoch | Sehr Hoch | Normal | Sehr Hoch |

**Bewertungskriterien:**

| Schutzbedarf | Vertraulichkeit | Integrität | Verfügbarkeit |
|--------------|-----------------|------------|---------------|
| **Normal** | Öffentlich zugänglich | Geringe Auswirkungen | Kurze Ausfälle tolerierbar |
| **Hoch** | Vertraulich, interne Nutzung | Erhebliche Schäden | Ausfälle beeinträchtigen Geschäft |
| **Sehr Hoch** | Streng vertraulich, gesetzlich geschützt | Existenzbedrohend | Ausfälle kritisch für Geschäft |

**Visuelle Darstellung:**
```
Schutzbedarfsfeststellung - Elemente:
┌─────────────────────────────────────┐
│  1. Informationsinventar            │
│  • Alle Informationen erfassen       │
│  • Kategorien bilden                │
└──────────────┬──────────────────────┘
               │
               ▼
┌─────────────────────────────────────┐
│  2. Bewertungsmatrix                │
│  • Vertraulichkeit bewerten         │
│  • Integrität bewerten              │
│  • Verfügbarkeit bewerten           │
└──────────────┬──────────────────────┘
               │
               ▼
┌─────────────────────────────────────┐
│  3. Schutzbedarfsmatrix             │
│  • Klassifizierung (N/H/SH)         │
│  • Gesamtschutzbedarf ermitteln     │
└──────────────┬──────────────────────┘
               │
               ▼
┌─────────────────────────────────────┐
│  4. Maßnahmenzuordnung              │
│  • Maßnahmen aus Schutzbedarf       │
│    ableiten                         │
└─────────────────────────────────────┘
```

**Praxis-Beispiel:**
In einem Handelsunternehmen wird eine Schutzbedarfsfeststellung durchgeführt:
- **Informationsinventar:** Kundendaten, Gehaltsabrechnungen, Lagerbestand, Rechnungen, Geschäftsgeheimnisse
- **Bewertung:** Kundendaten haben hohen Schutzbedarf (DSGVO), Gehaltsabrechnungen sehr hoch (personenbezogen, gesetzlich geschützt)
- **Klassifizierung:** Kundendaten = Hoch, Gehaltsabrechnungen = Sehr Hoch
- **Maßnahmen:** Für Sehr Hoch: Verschlüsselung, strenge Zugriffskontrollen, Audit-Logging. Für Hoch: Verschlüsselung, Zugriffskontrollen.

**Prüfungscheck:**
**Frage:** Welche Elemente umfasst eine Schutzbedarfsfeststellung im Beispielunternehmen?

**Antwort:**
Eine Schutzbedarfsfeststellung umfasst:
1. **Informationsinventar:** Systematische Erfassung aller Informationen
2. **Bewertungsmatrix:** Bewertung des Schutzbedarfs für Vertraulichkeit, Integrität und Verfügbarkeit
3. **Schutzbedarfsmatrix:** Klassifizierung in Normal, Hoch oder Sehr Hoch
4. **Schadensbewertung:** Analyse der Auswirkungen bei Verlust oder Kompromittierung
5. **Maßnahmenzuordnung:** Ableitung konkreter Sicherheitsmaßnahmen aus dem Schutzbedarf

**Merksatz:**
"Schutzbedarfsfeststellung = Inventar → Bewertung (V/I/A) → Klassifizierung (N/H/SH) → Maßnahmen!"

---

## 4.4: Schutzbedarfsfeststellung in Arbeitsbereichen von JIKU IT-Solutions durchführen

**Kurz-Definition:**
Die Schutzbedarfsfeststellung in konkreten Arbeitsbereichen von JIKU IT-Solutions beinhaltet die praktische Anwendung der Methodik auf spezifische IT-Komponenten wie Arbeitsplatzsoftware, Clients und mobile Datenträger.

**Tabellarische Übersicht:**

| Arbeitsbereich | Komponente | Schutzbedarf | Maßnahmen |
|----------------|------------|--------------|-----------|
| **Arbeitsplatzsoftware** | Office, Browser, E-Mail-Client | Abhängig von Daten | Updates, Virenschutz |
| **Clients** | PC, Laptop, Arbeitsplatzrechner | Hoch (Zugriff auf Daten) | Verschlüsselung, Zugriffskontrolle |
| **Mobile Datenträger** | USB-Stick, externe Festplatte | Hoch (Datenverlustrisiko) | Verschlüsselung, Richtlinien |

**Prüfungscheck:**
**Frage:** Warum ist eine Schutzbedarfsfeststellung für Arbeitsbereiche wichtig?

**Antwort:**
Eine Schutzbedarfsfeststellung für Arbeitsbereiche ist wichtig, weil sie den konkreten Schutzbedarf für einzelne IT-Komponenten ermittelt. Dadurch können angemessene und wirtschaftlich vertretbare Sicherheitsmaßnahmen gezielt ausgewählt und umgesetzt werden, anstatt alle Komponenten gleich zu behandeln.

**Merksatz:**
"Arbeitsbereich-Schutzbedarf = Komponenten analysieren → Schutzbedarf ermitteln → Maßnahmen umsetzen!"

---

### 4.4.1: Den Schutzbedarf bezüglich der Arbeitsplatzsoftware feststellen

**Kurz-Definition:**
Die Schutzbedarfsfeststellung für Arbeitsplatzsoftware ermittelt den erforderlichen Schutz für auf Clients installierte Anwendungen (Office, Browser, E-Mail-Client, etc.) in Abhängigkeit von den verarbeiteten Daten und den Funktionen der Software.

**Tabellarische Übersicht:**

**Arbeitsplatzsoftware - Kategorien:**

| Kategorie | Beispiele | Typischer Schutzbedarf | Begründung |
|-----------|----------|------------------------|------------|
| **Office-Suite** | Word, Excel, PowerPoint | Hoch | Verarbeitet geschäftskritische Daten |
| **E-Mail-Client** | Outlook, Thunderbird | Hoch | Überträgt vertrauliche Informationen |
| **Webbrowser** | Chrome, Firefox, Edge | Mittel-Hoch | Zugriff auf interne Systeme, Phishing-Risiko |
| **PDF-Viewer** | Adobe Reader | Mittel | Kann vertrauliche Dokumente anzeigen |
| **Messenger** | Teams, Slack | Hoch | Kommunikation, möglicherweise vertraulich |
| **Virenschutz** | Antivirus-Software | Hoch | Schutz vor Malware |
| **Verschlüsselung** | BitLocker, VeraCrypt | Sehr Hoch | Schutz der Datenintegrität |

**Schutzbedarfsbewertung - Kriterien:**

| Kriterium | Normal | Hoch | Sehr Hoch |
|-----------|--------|------|-----------|
| **Verarbeitete Daten** | Öffentlich | Vertraulich | Streng vertraulich |
| **Zugriff auf Systeme** | Kein Zugriff | Zugriff auf interne Systeme | Zugriff auf kritische Systeme |
| **Schadenspotenzial** | Gering | Erheblich | Existenzbedrohend |
| **Gesetzliche Anforderungen** | Keine | DSGVO, etc. | Geheimhaltungspflicht |

**Maßnahmen für Arbeitsplatzsoftware:**

| Maßnahme | Beschreibung | Schutzbedarf |
|----------|--------------|--------------|
| **Regelmäßige Updates** | Sicherheitsupdates einspielen | Alle |
| **Virenschutz** | Aktuelle Antivirus-Software | Alle |
| **Zugriffskontrolle** | Nur autorisierte Software installieren | Hoch, Sehr Hoch |
| **Verschlüsselung** | Daten verschlüsselt speichern | Hoch, Sehr Hoch |
| **Sandboxing** | Software isoliert ausführen | Hoch |
| **Whitelisting** | Nur erlaubte Software zulassen | Sehr Hoch |
| **Monitoring** | Software-Nutzung überwachen | Hoch, Sehr Hoch |

**Visuelle Darstellung:**
```
Schutzbedarfsfeststellung Arbeitsplatzsoftware:
┌─────────────────────────────────────┐
│  Software identifizieren             │
│  • Office-Suite                      │
│  • E-Mail-Client                     │
│  • Webbrowser                        │
└──────────────┬──────────────────────┘
               │
               ▼
┌─────────────────────────────────────┐
│  Verarbeitete Daten analysieren      │
│  • Welche Daten werden verarbeitet?  │
│  • Wie vertraulich sind die Daten?   │
└──────────────┬──────────────────────┘
               │
               ▼
┌─────────────────────────────────────┐
│  Schutzbedarf bewerten               │
│  • Vertraulichkeit                  │
│  • Integrität                       │
│  • Verfügbarkeit                    │
└──────────────┬──────────────────────┘
               │
               ▼
┌─────────────────────────────────────┐
│  Maßnahmen ableiten                  │
│  • Updates                           │
│  • Virenschutz                       │
│  • Zugriffskontrolle                 │
└─────────────────────────────────────┘
```

**Praxis-Beispiel:**
Bei JIKU IT-Solutions wird der Schutzbedarf für Arbeitsplatzsoftware festgestellt:
- **Microsoft Office:** Verarbeitet Kundendaten, Angebote, Verträge → Schutzbedarf: Hoch (Vertraulichkeit, Integrität)
- **Outlook (E-Mail):** Überträgt vertrauliche E-Mails mit Anhängen → Schutzbedarf: Hoch (Vertraulichkeit)
- **Chrome (Browser):** Zugriff auf interne Systeme, Cloud-Dienste → Schutzbedarf: Hoch (Zugriffskontrolle)
- **Maßnahmen:** Regelmäßige Updates, Virenschutz, Verschlüsselung von Office-Dateien, Zugriffskontrolle für Software-Installation

**Prüfungscheck:**
**Frage:** Wie wird der Schutzbedarf für Arbeitsplatzsoftware festgestellt?

**Antwort:**
Der Schutzbedarf für Arbeitsplatzsoftware wird festgestellt durch:
1. **Identifikation:** Welche Software ist installiert und wird genutzt?
2. **Datenanalyse:** Welche Daten werden von der Software verarbeitet? Wie vertraulich sind diese?
3. **Funktionsanalyse:** Welche Funktionen hat die Software? Zugriff auf welche Systeme?
4. **Bewertung:** Schutzbedarf für Vertraulichkeit, Integrität und Verfügbarkeit bewerten
5. **Klassifizierung:** Normal, Hoch oder Sehr Hoch zuordnen
6. **Maßnahmen:** Aus dem Schutzbedarf konkrete Maßnahmen ableiten (Updates, Virenschutz, Verschlüsselung, etc.)

**Merksatz:**
"Arbeitsplatzsoftware-Schutzbedarf = Software + Daten + Funktionen analysieren → Schutzbedarf feststellen → Maßnahmen umsetzen!"

---

### 4.4.2: Den Schutzbedarf bezüglich der Clients eines Arbeitsplatzes feststellen

**Kurz-Definition:**
Die Schutzbedarfsfeststellung für Clients ermittelt den erforderlichen Schutz für Arbeitsplatzrechner (PCs, Laptops) in Abhängigkeit von den gespeicherten Daten, dem Zugriff auf Systeme und der Nutzungsumgebung.

**Tabellarische Übersicht:**

**Client-Typen und Schutzbedarf:**

| Client-Typ | Umgebung | Typischer Schutzbedarf | Begründung |
|------------|----------|------------------------|------------|
| **Desktop-PC** | Büro, internes Netzwerk | Hoch | Zugriff auf Unternehmensdaten |
| **Laptop** | Mobil, verschiedene Standorte | Sehr Hoch | Höheres Diebstahlrisiko, mobile Nutzung |
| **Thin Client** | Server-basiert | Mittel | Weniger lokale Daten |
| **Tablet/Smartphone** | Mobil, BYOD möglich | Hoch-Sehr Hoch | Mobile Nutzung, möglicherweise privat |

**Schutzbedarfsbewertung - Faktoren:**

| Faktor | Normal | Hoch | Sehr Hoch |
|--------|--------|------|-----------|
| **Gespeicherte Daten** | Keine kritischen Daten | Vertrauliche Daten lokal | Sehr vertrauliche Daten lokal |
| **Zugriff auf Systeme** | Kein Zugriff | Zugriff auf interne Systeme | Zugriff auf kritische Systeme |
| **Nutzungsumgebung** | Geschütztes Büro | Verschiedene Standorte | Öffentliche Bereiche |
| **Diebstahlrisiko** | Niedrig | Mittel | Hoch |
| **Mobilität** | Stationär | Gelegentlich mobil | Häufig mobil |

**Maßnahmen für Clients:**

| Maßnahme | Beschreibung | Schutzbedarf |
|----------|--------------|--------------|
| **Festplattenverschlüsselung** | BitLocker, FileVault | Hoch, Sehr Hoch |
| **Zugriffskontrolle** | Benutzerkonten, Passwörter, 2FA | Alle |
| **Virenschutz** | Aktuelle Antivirus-Software | Alle |
| **Firewall** | Lokale Firewall aktivieren | Hoch, Sehr Hoch |
| **Automatische Updates** | Betriebssystem und Software | Alle |
| **Remote-Wipe** | Gerät aus der Ferne löschen | Sehr Hoch (mobile Geräte) |
| **Device Control** | USB/Externe Geräte kontrollieren | Hoch, Sehr Hoch |
| **Monitoring** | Überwachung von Aktivitäten | Hoch, Sehr Hoch |
| **Backup** | Regelmäßige Datensicherung | Alle |
| **Physischer Schutz** | Kabel, Alarmsysteme | Hoch, Sehr Hoch |

**Visuelle Darstellung:**
```
Schutzbedarfsfeststellung Clients:
┌─────────────────────────────────────┐
│  Client-Typ identifizieren           │
│  • Desktop, Laptop, Tablet           │
└──────────────┬──────────────────────┘
               │
               ▼
┌─────────────────────────────────────┐
│  Nutzungsumgebung analysieren        │
│  • Stationär oder mobil?             │
│  • Geschützt oder öffentlich?        │
└──────────────┬──────────────────────┘
               │
               ▼
┌─────────────────────────────────────┐
│  Daten und Zugriffe bewerten         │
│  • Welche Daten sind gespeichert?    │
│  • Zugriff auf welche Systeme?       │
└──────────────┬──────────────────────┘
               │
               ▼
┌─────────────────────────────────────┐
│  Schutzbedarf feststellen            │
│  • Normal / Hoch / Sehr Hoch         │
└──────────────┬──────────────────────┘
               │
               ▼
┌─────────────────────────────────────┐
│  Maßnahmen ableiten                  │
│  • Verschlüsselung                   │
│  • Zugriffskontrolle                 │
│  • Virenschutz                       │
└─────────────────────────────────────┘
```

**Praxis-Beispiel:**
Bei JIKU IT-Solutions wird der Schutzbedarf für Clients festgestellt:
- **Desktop-PC im Büro:** Zugriff auf Kundendaten, interne Systeme → Schutzbedarf: Hoch
  - Maßnahmen: Verschlüsselung, Zugriffskontrolle, Virenschutz, Updates
- **Laptop für Außendienst:** Mobile Nutzung, Zugriff auf vertrauliche Daten → Schutzbedarf: Sehr Hoch
  - Maßnahmen: Festplattenverschlüsselung (BitLocker), 2FA, Remote-Wipe, Device Control, physischer Schutz
- **Thin Client:** Nur Terminal-Zugriff, keine lokalen Daten → Schutzbedarf: Mittel
  - Maßnahmen: Zugriffskontrolle, Updates

**Prüfungscheck:**
**Frage:** Welche Faktoren beeinflussen den Schutzbedarf eines Clients und welche Maßnahmen sind typischerweise erforderlich?

**Antwort:**
Faktoren für den Schutzbedarf:
- **Gespeicherte Daten:** Je vertraulicher die lokal gespeicherten Daten, desto höher der Schutzbedarf
- **Nutzungsumgebung:** Mobile Geräte haben höheren Schutzbedarf als stationäre
- **Zugriff auf Systeme:** Zugriff auf kritische Systeme erhöht den Schutzbedarf
- **Diebstahlrisiko:** Höheres Risiko erfordert höheren Schutz

Typische Maßnahmen:
- **Verschlüsselung:** Festplattenverschlüsselung (BitLocker) für Hoch/Sehr Hoch
- **Zugriffskontrolle:** Starke Passwörter, 2FA
- **Virenschutz:** Aktuelle Antivirus-Software
- **Updates:** Regelmäßige Sicherheitsupdates
- **Remote-Wipe:** Für mobile Geräte mit Sehr Hoch
- **Device Control:** Kontrolle von USB/Externen Geräten

**Merksatz:**
"Client-Schutzbedarf = Typ + Umgebung + Daten analysieren → Verschlüsselung + Zugriffskontrolle + Updates!"

---

### 4.4.3: Den Schutzbedarf bezüglich des Austausches von Daten mithilfe von mobilen Datenträgern feststellen

**Kurz-Definition:**
Die Schutzbedarfsfeststellung für mobile Datenträger ermittelt den erforderlichen Schutz für USB-Sticks, externe Festplatten und andere portable Speichermedien, die zum Datenaustausch genutzt werden. Diese stellen ein hohes Risiko für Datenverlust und Malware-Verbreitung dar.

**Tabellarische Übersicht:**

**Mobile Datenträger - Typen:**

| Typ | Beschreibung | Typischer Schutzbedarf | Risiken |
|-----|--------------|------------------------|---------|
| **USB-Stick** | Kleine portable Speicher | Hoch-Sehr Hoch | Verlust, Diebstahl, Malware |
| **Externe Festplatte** | Portable HDD/SSD | Hoch-Sehr Hoch | Verlust, Diebstahl, physischer Schaden |
| **SD-Karte** | Speicherkarte | Hoch | Verlust, Kompatibilität |
| **CD/DVD** | Optische Medien | Mittel-Hoch | Physischer Schaden, begrenzte Kapazität |
| **Smartphone/Tablet** | Mobile Geräte als Datenträger | Sehr Hoch | Verlust, Diebstahl, unkontrollierte Nutzung |

**Schutzbedarfsbewertung - Kriterien:**

| Kriterium | Normal | Hoch | Sehr Hoch |
|-----------|--------|------|-----------|
| **Übertragene Daten** | Öffentlich | Vertraulich | Streng vertraulich |
| **Datenmenge** | Klein | Mittel | Groß |
| **Häufigkeit der Nutzung** | Selten | Regelmäßig | Häufig |
| **Verlustrisiko** | Niedrig | Mittel | Hoch |
| **Gesetzliche Anforderungen** | Keine | DSGVO | Geheimhaltungspflicht |

**Gefährdungen durch mobile Datenträger:**

| Gefährdung | Beschreibung | Auswirkung |
|------------|--------------|------------|
| **Verlust/Diebstahl** | Datenträger geht verloren oder wird gestohlen | Unbefugter Zugriff auf Daten |
| **Malware-Verbreitung** | Infizierter Datenträger infiziert Systeme | Systemkompromittierung |
| **Unbefugte Nutzung** | Privater Datenträger wird genutzt | Datenlecks, Compliance-Verstöße |
| **Fehlkonfiguration** | Falsche Berechtigungen | Unbefugter Zugriff |
| **Physischer Schaden** | Datenträger wird beschädigt | Datenverlust |

**Maßnahmen für mobile Datenträger:**

| Maßnahme | Beschreibung | Schutzbedarf |
|----------|--------------|--------------|
| **Verschlüsselung** | Vollständige Verschlüsselung des Datenträgers | Hoch, Sehr Hoch |
| **Zugriffskontrolle** | Authentifizierung vor Zugriff | Hoch, Sehr Hoch |
| **Device Control** | Kontrolle, welche Geräte genutzt werden dürfen | Hoch, Sehr Hoch |
| **Whitelisting** | Nur autorisierte Datenträger zulassen | Sehr Hoch |
| **Virenscan** | Automatischer Scan beim Anschluss | Alle |
| **Richtlinien** | Regeln für Nutzung und Datenaustausch | Alle |
| **Schulungen** | Sensibilisierung der Mitarbeiter | Alle |
| **Zentraler Datenaustausch** | Alternative zu mobilen Datenträgern | Alle |
| **Audit-Logging** | Protokollierung der Nutzung | Hoch, Sehr Hoch |
| **Remote-Löschung** | Möglichkeit, Daten aus der Ferne zu löschen | Sehr Hoch |

**Visuelle Darstellung:**
```
Schutzbedarfsfeststellung mobile Datenträger:
┌─────────────────────────────────────┐
│  Datenträger-Typ identifizieren     │
│  • USB-Stick, externe Festplatte    │
└──────────────┬──────────────────────┘
               │
               ▼
┌─────────────────────────────────────┐
│  Übertragene Daten analysieren       │
│  • Welche Daten werden übertragen?  │
│  • Wie vertraulich sind die Daten?  │
└──────────────┬──────────────────────┘
               │
               ▼
┌─────────────────────────────────────┐
│  Risiken bewerten                    │
│  • Verlustrisiko                     │
│  • Diebstahlrisiko                   │
│  • Malware-Risiko                    │
└──────────────┬──────────────────────┘
               │
               ▼
┌─────────────────────────────────────┐
│  Schutzbedarf feststellen            │
│  • Normal / Hoch / Sehr Hoch         │
└──────────────┬──────────────────────┘
               │
               ▼
┌─────────────────────────────────────┐
│  Maßnahmen ableiten                  │
│  • Verschlüsselung                   │
│  • Device Control                    │
│  • Virenscan                         │
│  • Richtlinien                       │
└─────────────────────────────────────┘
```

**Praxis-Beispiel:**
Bei JIKU IT-Solutions wird der Schutzbedarf für mobile Datenträger festgestellt:
- **Szenario:** Mitarbeiter nutzen USB-Sticks, um Kundendaten zwischen Standorten zu transportieren
- **Bewertung:** Kundendaten sind vertraulich (DSGVO), USB-Sticks gehen häufig verloren → Schutzbedarf: Sehr Hoch
- **Gefährdungen:** Verlust/Diebstahl, Malware-Verbreitung, unbefugte Nutzung
- **Maßnahmen:**
  - Verschlüsselung aller mobilen Datenträger (BitLocker To Go)
  - Device Control: Nur autorisierte, verschlüsselte USB-Sticks zulassen
  - Automatischer Virenscan beim Anschluss
  - Richtlinie: Nur verschlüsselte Datenträger nutzen, Alternative: Cloud-basierter Datenaustausch
  - Schulung der Mitarbeiter
  - Audit-Logging der Nutzung

**Prüfungscheck:**
**Frage:** Welche Gefährdungen bestehen bei der Nutzung mobiler Datenträger und welche Maßnahmen können dagegen ergriffen werden?

**Antwort:**
Gefährdungen:
1. **Verlust/Diebstahl:** Datenträger geht verloren oder wird gestohlen → Unbefugter Zugriff auf Daten
2. **Malware-Verbreitung:** Infizierter Datenträger infiziert Systeme beim Anschluss
3. **Unbefugte Nutzung:** Private Datenträger werden genutzt → Datenlecks, Compliance-Verstöße

Maßnahmen:
1. **Verschlüsselung:** Vollständige Verschlüsselung des Datenträgers (z.B. BitLocker To Go)
2. **Device Control:** Nur autorisierte, verschlüsselte Datenträger zulassen, private Geräte blockieren
3. **Virenscan:** Automatischer Scan beim Anschluss
4. **Richtlinien:** Klare Regeln für Nutzung, Alternative: Cloud-basierter Datenaustausch
5. **Schulungen:** Mitarbeiter sensibilisieren
6. **Audit-Logging:** Nutzung protokollieren

**Merksatz:**
"Mobile Datenträger = Hohes Risiko (Verlust, Malware) → Verschlüsselung + Device Control + Virenscan + Richtlinien!"

---

## Zusammenfassung

**Kernaussagen:**
- Schutzbedarfsanalyse ist systematischer Prozess zur Ermittlung des Schutzniveaus
- Informationssicherheit basiert auf drei Schutzzielen: Vertraulichkeit, Integrität, Verfügbarkeit
- BSI-Grundschutz bietet strukturierten Prozess in 6 Phasen
- Technisch-organisatorische Maßnahmen müssen kombiniert werden
- Schutzbedarfsfeststellung muss für konkrete Arbeitsbereiche durchgeführt werden

**Prüfungsrelevante Stichworte:**
- CIA-Triade (Vertraulichkeit, Integrität, Verfügbarkeit)
- BSI-Grundschutz-Prozess (6 Phasen)
- Schutzbedarfsklassen (Normal, Hoch, Sehr Hoch)
- Technische vs. organisatorische Maßnahmen
- Social Engineering, Ransomware, Phishing
- DSGVO, ISO 27001, IT-Grundschutz
- Verschlüsselung, Zugriffskontrolle, Device Control

