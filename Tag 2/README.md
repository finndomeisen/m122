# Tag 2

## 19.05.2025

Heute habe ich mich rund um Bash Commands beschäftigt.
Ich habe viele verschiedene Commands ausprobiert und gelernt, was diese machen.

Ein paar wichtige kannte ich schon vom ZLI oder von ÜKs.

Wir haben noch ein Cheatsheet erstellt:

# Linux Bash Cheat Sheet

## Dateisystem-Navigation
| Befehl                        | Beschreibung                              |
|------------------------------|-------------------------------------------|
| `pwd`                        | Zeigt den aktuellen Pfad                  |
| `ls`                         | Listet Dateien und Ordner auf             |
| `ls -l`                      | Detaillierte Liste                        |
| `cd [Pfad]`                  | Wechselt Verzeichnis                      |
| `cd ..`                      | Geht ein Verzeichnis nach oben            |
| `cd ~`                       | Wechselt ins Home-Verzeichnis             |
| `mkdir [Ordnername]`         | Erstellt einen neuen Ordner               |
| `rmdir [Ordnername]`         | Löscht einen leeren Ordner                |

## Dateien verwalten
| Befehl                          | Beschreibung                                |
|--------------------------------|---------------------------------------------|
| `touch [Dateiname]`            | Erstellt eine neue Datei                    |
| `cp [Quelle] [Ziel]`           | Kopiert Datei oder Ordner                   |
| `mv [Quelle] [Ziel]`           | Verschiebt oder benennt Datei/Ordner um     |
| `rm [Dateiname]`               | Löscht eine Datei                           |
| `rm -r [Ordnername]`           | Löscht Ordner inkl. Inhalt                  |
| `cat [Datei]`                  | Zeigt Dateiinhalt an                        |
| `less [Datei]`                 | Zeigt Datei seitenweise an                  |
| `head -n 10 [Datei]`           | Zeigt die ersten 10 Zeilen                  |
| `tail -n 10 [Datei]`           | Zeigt die letzten 10 Zeilen                 |

## Suchen und Filtern
| Befehl                                   | Beschreibung                             |
|-----------------------------------------|------------------------------------------|
| `find [Pfad] -name "[Name]"`            | Sucht Datei/Ordner im Pfad               |
| `grep "[Text]" [Datei]`                 | Sucht Text in Datei                      |
| `grep -r "[Text]" [Pfad]`               | Rekursive Suche                          |

## Rechte und Eigentümer
| Befehl                              | Beschreibung                              |
|------------------------------------|-------------------------------------------|
| `chmod [Modus] [Datei]`            | Ändert Datei-Rechte                       |
| `chown [Benutzer] [Datei]`         | Ändert Eigentümer                         |
| `ls -l`                            | Zeigt Rechte, Eigentümer usw.             |

## Nützliche Tools
| Befehl                     | Beschreibung                                |
|---------------------------|---------------------------------------------|
| `man [Befehl]`            | Zeigt Hilfeseite zu Befehl                  |
| `history`                 | Zeigt Befehlsverlauf                        |
| `clear`                   | Räumt das Terminal auf                      |
| `echo [Text]`             | Gibt Text aus                               |
| `date`                    | Zeigt aktuelles Datum & Uhrzeit             |
| `whoami`                  | Zeigt aktuellen Benutzer                    |

## Prozesse und System
| Befehl                | Beschreibung                             |
|----------------------|------------------------------------------|
| `top`                | Zeigt laufende Prozesse                  |
| `ps aux`             | Zeigt Prozesse ausführlich               |
| `kill [PID]`         | Beendet Prozess mit Prozess-ID           |
| `df -h`              | Zeigt Speicherplatz auf Festplatten      |
| `du -sh [Pfad]`      | Zeigt Ordnergröße                        |
| `uptime`             | Zeigt Systemlaufzeit                     |

## Netzwerk
| Befehl                    | Beschreibung                           |
|--------------------------|------------------------------------------|
| `ping [Adresse]`         | Prüft Verbindung zu Host                |
| `curl [URL]`             | Holt Daten von URL                      |
| `wget [URL]`             | Lädt Datei herunter                     |
| `ip a`                   | Zeigt IP-Adressen                       |

## Paketverwaltung (Ubuntu/Debian)
| Befehl                             | Beschreibung                           |
|-----------------------------------|----------------------------------------|
| `sudo apt update`                 | Paketliste aktualisieren               |
| `sudo apt upgrade`                | Alle Pakete aktualisieren              |
| `sudo apt install [paket]`        | Installiert ein Paket                  |
| `sudo apt remove [paket]`         | Entfernt ein Paket                     |

