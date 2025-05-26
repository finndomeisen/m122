# Modul 122

## Modulübersicht

**Modulcode:** M122  
**Titel:** Abläufe mit einer Scriptsprache automatisieren  
**Ziel:** Automatisierung von Systemabläufen mittels einer Scriptsprache wie Bash

---

## Einführung
In diesem Modul lernen die Lernenden, wie man mit Hilfe von Skriptsprachen systembezogene Abläufe automatisiert. Solche Skripte werden von einem Interpreter (auch "Scripting-Host" genannt) Zeile für Zeile ausgeführt. Sie dienen der Automatisierung alltäglicher Aufgaben in Betriebssystemen, Applikationen, Web-Clients oder Web-Servern.

### Anwendungsbereiche & Beispiele
| Bereich          | Skriptsprachen (Interpreter)                     | Zweck der Automation                               |
|------------------|--------------------------------------------------|----------------------------------------------------|
| Betriebssystem   | Bash, Batch, PowerShell, AppleScript, Python     | Login, Installation, Konfiguration etc.            |
| Applikation      | VBA, LUA, AppleScript, UnityScript               | Automatisierung innerhalb von Applikationen        |
| Web-Client       | JavaScript, TypeScript, Dart                     | Dynamische Webseiten                              |
| Web-Server       | PHP, NodeJS, Python, Perl                        | Abarbeiten von Anfragen auf dem Webserver          |

### Wissenswert
- Interpreter führen Skripte zeilenweise aus.
- Fehlerhafte Zeilen stoppen die Ausführung.
- Interpreter-Skripte sind eher langsam, daher für einfache, gezielte Aufgaben geeignet.
- Shellskripte (bash, csh, etc.) oder Batch-Dateien (cmd.exe, PowerShell) sind typische Formate.

---

## Lernziele
- Verstehen und Schreiben von Bash-Skripten
- Automatisieren von Systemaufgaben
- Einsatz von Konfigurationsdateien
- Fehlertoleranz und robuste Datenverarbeitung

---

## Lektionenplan (Beispiel)

| Tag | Thema                      | Inhalt / Auftrag |
|-----|----------------------------|------------------|
| 1   | Linux Einführung           | Virtualisierung, erste Bash-Kommandos |
| 2-3 | Bash Grundlagen            | Übungen, Checkpoints mit Lösungen |
| 4   | Bash Aufgaben              | Aufgaben 1 & 2 |
| 5   | Vorbereitung LB1           | Lösungen, Repetition |
| 6   | Projektstart (LB2)         | Antrag & Design |
| 7   | Projektarbeit (Code)       | Meilenstein B |
| 8-9 | Projektarbeit              | Codierung, Reserve |
| 10  | Projektabschluss           | Demo, Abgabe Code & Doku |

---

## Projektrahmenbedingungen
- Umsetzung vorzugsweise mit **Bash**, Alternativen z. B. PowerShell, Python
- Automatisierte Aufgaben: z. B. Benutzerverwaltung, Netzwerk, Datenverarbeitung
- Script startet automatisch (CronJob)
- Konfiguration via Datei, keine GUI
- Robuster Datenimport/-export mit Fehlerbehandlung

---

## Einsatz von KI als Tutor
### Haltung:
KI kann Lernende begleiten, aber nicht ersetzen. Ziel: "**Ich will es selber wissen und können!**"

### Tutor-Prompt für Start:
```text
Sei mein persönlicher Tutor für das Thema "Abläufe mit der Scriptsprache BASH (Linux) automatisieren" auf dem Niveau der Schweizer Berufsschule für Informatik. 
Deine Aufgabe ist es, mir beim Verständnis der Grundlagen und Konzepte zu helfen, ohne direkt Lösungen für meine Aufgaben zu liefern. 
Führe mich stattdessen durch den Lernprozess, indem du mir zeigst, wie ich Probleme selbstständig angehen kann. 

Halte dich dabei an den Selbstlernzyklus, der in der folgenden Website erklärt wird: <https://gitlab.com/ch-tbz-it/Stud/m319/-/tree/main/N0-Portfolio>

Strukturiere deine Antworten immer in die folgenden vier Kategorien:
1) Grundlagen
2) Konzeptverständnis
3) Nächster Schritt
4) Nutzung Lernportfolio

Benutze ausschliesslich Inhalte aus: <https://gitlab.com/ch-tbz-it/Stud/m122/-/tree/main>
```

### Empfehlungen:
- Übungen selbst tippen und verstehen
- KI-Ausgaben reflektieren, prüfen und kommentieren
- Immer Quelle und Prompt dokumentieren

---

**Letzte Aktualisierung:** Mai 2025
