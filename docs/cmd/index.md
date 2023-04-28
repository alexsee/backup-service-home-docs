# Kommandozeilenparameter

!!! note

    Die Verwendung der Kommandozeilenparameter ist für den normalen Einsatz von Backup Service Home 3 nicht notwendig.

!!! note

    Es kann jeweils nur eine Instanz pro Benutzer gestartet werden.

!!! warning

    In Version 3.8.3 gab es eine Neustrukturierung der Kommandozeilenparameter. Die vorher verwendeten Kommandos sind nicht mehr verfügbar.


## Generelle Optionen

### `--delayedstart`

Startet Backup Service Home 3 mit 10s Verzögerung. Alle Aufgaben und weitere Aktivitäten stehen erst nach der Verzögerungszeit zur Verfügung.

### `--databasefile`

Legt die Datenbankdatei fest, die für die gestartete Instanz von Backup Service Home 3 verwendet werden soll. Standardmäßig wird die Datenbank des aktuell angemeldeten Benutzers bzw. des Benutzers, der die Instanz startet geladen.

### `--deleteprotocol`

(Veraltet) Löscht das Backup Service Home Protokoll aus der Windows Ereignisanzeige.


## Backupbrowser anzeigen

### `browser`

Startet nach dem Start von Backup Service Home direkt den Backupbrowser.


## Konfiguration anzeigen

### `config`

Zeigt nach dem Start von Backup Service Home direkt das Konfigurationsfenster an.


## Sicherung starten

Mit dem Kommando `startbackup` lässt sich eine Sicherung starten.

### `--title`

Legt den Titel der anzulegenden Sicherung fest.

### `--description`

Legt die Beschreibung der anzulegenden Sicherung fest.

## `--shutdownapp`

Beendet Backup Service Home 3 nach einer mit dem Kommandozeilenparameter `startbackup` initiierten Sicherung.

## `--shutdownpc`

Fährt den Computer nach einer mit dem Kommandozeilenparameter `startbackup` initiierten Sicherung herunter.

## `--autodelete`

Führt vor einer mit dem Kommandozeilenparameter `startbackup` initiierten Sicherung eine Löschung der Sicherungen wie beim automatischen Datensicherungsmodus durch.

## Beispiel

```
BSH.Main.exe startbackup --title "Manuelle Sicherung" --shutdownapp
```
