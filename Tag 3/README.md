# Tag 3
## 26.05.2025

Heute haben wir gemeinsam mit Herr Kellenburger kurz besprochen, was wir in den letzten zwei Tagen bereits erledigt und dokumentiert haben. Dabei wurde deutlich, dass unsere bisherigen Einträge zwar vollständig, aber noch zu knapp und technisch formuliert waren. 
Herr Kellenburger hat uns deshalb darauf hingewiesen, dass wir ausführlicher dokumentieren sollten, insbesondere unsere persönliche Sichtweise, unser Vorgehen und auch unsere Gedanken dabei.

Das haben wir dann gemacht, da wir gemerkt haben, dass es tatsächlich hilfreich ist, wenn man nicht nur festhält, was man getan hat, sondern auch wie und warum. 
Das macht die Dokumentation später verständlicher, auch für uns selbst, wenn wir etwas nachschlagen oder reflektieren wollen.

Im Verlauf des Tages haben wir sämtliche Aufträge zu den Bash-Grundlagen bearbeitet. 
Dabei haben wir zum Beispiel mit Befehlen wie chmod, chown, useradd oder grep gearbeitet und ein besseres Verständnis für den Umgang mit Benutzerrechten und Kommandozeilentools gewonnen.

Einige Aufgaben waren zunächst etwas knifflig, vor allem wenn die Syntax nicht auf Anhieb stimmte. Trotzdem fanden wir es spannend, wie viel man in der Shell automatisieren und kontrollieren kann. 
Besonders motivierend war das Gefühl, mit jedem Befehl ein Stück mehr Kontrolle über das System zu bekommen. 
Auch wenn es zwischendurch mal frustrierend war, hat uns das Lösen der Aufgaben zufrieden gemacht und unser Selbstvertrauen im Umgang mit Linux gestärkt.

Wir nehmen aus dem heutigen Tag mit, dass eine gute Dokumentation nicht nur für die Bewertung wichtig ist, sondern uns auch hilft, unser Lernen bewusster zu gestalten. 
In den nächsten Einträgen werden wir deshalb gezielt unsere Denkweise und Lernprozesse festhalten.



---

# Teil 3: Rechte und Benutzerverwaltung

## Zugriffsrechte in Linux

In Linux gibt es drei Benutzerkreise für jede Datei und jedes Verzeichnis:
- **Eigentümer (Owner)**
- **Gruppe (Group)**
- **Andere (Others)**

Die Zugriffsrechte werden durch folgende Zeichen dargestellt:
- `r`: Lesen (Read)
- `w`: Schreiben (Write)
- `x`: Ausführen (Execute)

Die Darstellung erfolgt in drei Gruppen zu je drei Zeichen, z. B. `-rwxr-xr--`. Jede Gruppe steht für eine Benutzerart.

Der erste Buchstabe einer Dateiliste zeigt den Typ an:
- `-` = Datei
- `d` = Verzeichnis
- `b`, `c` = Geräte-Dateien (Device files)

### `ls -al`: Bedeutung der Spalten
1. Zugriffsrechte
2. Anzahl Referenzen
3. Eigentümer (Benutzer)
4. Gruppe
5. Dateigrösse (Bytes)
6. Letzte Änderung
7. Name der Datei/des Verzeichnisses

## Wichtige Befehle zur Rechteverwaltung
- `chmod`: Rechte ändern (Change Mode)
- `chown`: Eigentümer oder Gruppe ändern (Change Owner)

## Benutzer- und Gruppenverwaltung

### Abfragen von Benutzerinformationen:
- `whoami`: zeigt den aktuellen Benutzernamen
- `who`: zeigt alle angemeldeten Benutzer
- `groups`: zeigt Gruppen des aktuellen Benutzers
- `id`: zeigt UID und Gruppen des aktuellen Benutzers

### Benutzer wechseln:
- `su - <User>`: wechselt Benutzer inkl. Login-Skripte und Heimverzeichnis
- `su <User>`: wechselt nur die Benutzer-ID

## Benutzerbezogene Befehle
- `useradd <User>`: neuen Benutzer hinzufügen
- `userdel <User>`: Benutzer löschen
- `passwd <User>`: Passwort setzen oder ändern
- `logout` / `exit`: Benutzer abmelden

## Nützliche Kommandozeilen-Tools

Diese Tools arbeiten zeilenorientiert:

- `grep`: Suche mit regulären Ausdrücken (REGEX)
- `cut`: Text oder Spalten ausschneiden
- `paste`: Gegenstück zu `cut`
- `sed`: Zeichen in Zeilen löschen oder ersetzen
- `tr`: Zeichen ersetzen
- `awk`: Textbearbeitung und einfache Programmierung
- `curl`: Daten aus dem Internet laden
- `xargs`: Listenverarbeitung

---

**Hinweis:** Für eine vollständige Übersicht über alle BASH-Befehle und Tools siehe Projektarbeit oder Systemreferenz.
