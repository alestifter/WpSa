# WpSa

Ein Projekt zum Vergleich und Testen von zwei SIEM-Systemen (**Splunk** und **Wazuh**) anhand definierter Testfälle, um herauszufinden, welches Tool für spezifische Anforderungen besser geeignet ist.

---

## 🚀 **Projektübersicht**

In diesem Projekt testen wir die Funktionen, Effizienz und Benutzerfreundlichkeit von Splunk und Wazuh. Unsere Analyse erfolgt anhand von Testfällen, die typische Sicherheitsvorfälle simulieren und bewerten, wie die beiden SIEMs darauf reagieren.

---

## 🔧 **Features**
- **Vergleich von SIEM-Systemen**: Leistungsanalyse und Vergleich von Splunk und Wazuh.
- **Testumgebung**: Nutzung von Virtuellen Maschinen, Kali Linux und verschiedenen Tools wie Nmap und OWASP ZAP zur Simulation von Angriffen.
- **Projektmanagement**: Verwendung von Jira zur Organisation und Nachverfolgung der Testfälle.
- **Testfälle**:
  - Log-Sammlung und -Analyse
  - Echtzeit-Benachrichtigungen
  - Erkennung von Schwachstellen und Angriffen
  - Integration und Benutzerfreundlichkeit
- **Virtuelle Maschinen (VMs)**: Einsatz von VMs zur Bereitstellung der SIEM-Umgebungen.

---

## 🛠️ **Projektumgebung**

### Tools & Technologien
- **SIEM-Systeme**: Splunk, Wazuh
- **Testumgebung**: Kali Linux
- **Virtuelle Maschinen (VMs)**: Für die Bereitstellung von Splunk und Wazuh.
- **Angriffssimulation**:
  - **Nmap**: Netzwerkscans und Erkennung offener Ports.
  - **OWASP ZAP**: Web-Schwachstellenscans.
  - **Hydra**: Bruteforce-Angriffe auf SSH.
  - **LOIC**: DDOS-Angriffe.
  - **Metasploit**: Privilege Escalation und andere Exploits.
  - **Ettercap**: Mac-Flooding.
- **Projektmanagement**: Jira

---

## 🔍 **Testfälle**

### Übersicht der Testfälle
1. **Log-Sammlung und -Analyse**:
   - Logs aus verschiedenen Quellen (z. B. Firewalls, Server) sammeln und analysieren.
   - Bewertung der Genauigkeit und Geschwindigkeit.
2. **Echtzeit-Benachrichtigungen**:
   - Test der Alert-Funktionalität bei spezifischen Angriffen.
3. **Schwachstellen-Erkennung**:
   - Simulation von Angriffen mit Tools wie Nmap und OWASP ZAP.
   - Bewertung der Erkennungsrate.
4. **Benutzerfreundlichkeit und Integration**:
   - Bewertung der Oberfläche und Konfigurationsmöglichkeiten.


## **Team**
- **Mitglieder**:
  - Clemens Burger (Projektleiter)
  - Paul Gradischnig (Projektleiter Stv., Controller)
  - Phillip Leimer (Riskmanager, Dokumentationsbeautragter)
  - Alessandro Stifter

## **Rollen**:

- **Projektleiter (Clemens Burger)**:
  - Gesamtverantwortung für das Projekt
  - Koordination und Steuerung der Projektaktivitäten
  - Kommunikation mit Stakeholdern
  - Nutzung von Jira für das Projektmanagement

- **Projektleiter Stv., Controller (Paul Gradischnig)**:
  - Unterstützung des Projektleiters bei der Planung und Durchführung des Projekts
  - Überwachung der zeitlichen und aufwandsbezogenen Aspekte des Projekts
  - Nutzung von Jira für die Aufgabenverteilung und Planung

- **Riskmanager, Dokumentationsbeauftragter (Phillip Leimer)**:
  - Identifikation und Management von Risiken im Projekt
  - Erstellung und Pflege der Projektdokumentation
  - Vergleich der Testergebnisse und Erstellung von Berichten

---

