# Kommandozeilenparameter

> [!NOTE]
> Die Verwendung der Kommandozeilenparameter ist für den normalen Einsatz von Backup Service Home 3 nicht notwendig.

> [!NOTE]
> Es kann jeweils nur eine Instanz pro Benutzer gestartet werden.

## /autodeletion

Führt vor einer mit dem Kommandozeilenparameter /startbackup initiierten Sicherung eine Löschung der Sicherungen wie beim automatischen Datensicherungsmodus durch.

## /browser

Zeigt den Backupbrowser an.

## /config

Zeigt das Konfigurationsfenster an.

## /createprotokoll

Erzeugt das Backup Service Home 3 Ereignisprotokoll in der Ereignisanzeige von Windows. Dies wird automatisch bei der Installation der Software ausgeführt. Es ist nicht notwendig diesen Schritt manuell durchzuführen. Backup Service Home 3 wird danach beendet.

## /databasefile

Legt die Datenbankdatei fest, die für die gestartete Instanz von Backup Service Home 3 verwendet werden soll. Standardmäßig wird die Datenbank des aktuell angemeldeten Benutzers bzw. des Benutzers, der die Instanz startet geladen.

## /delayedstart

Startet Backup Service Home 3 verzögert.

## /deleteprotokoll

Löscht das Backup Service Home 3 Ereignisprotokoll in der Ereignisanzeige von Windows. Dies wird automatisch bei der Deinstallation der Software ausgeführt. Es ist nicht notwendig diesen Schritt manuell durchzuführen. Backup Service Home 3 wird danach beendet.

## /ftplogging

Startet Backup Service Home 3 im Debugmodus. Im Debugmodus können Probleme mit dem FTP Upload / Download analysiert werden. Eine entsprechende Protokolldatei befindet sich im C:\Benutzer\\AppData\Roaming\Alexosoft\Backup Service Home 3 Verzeichnis. Die Datei heißt FTP.log.

## /resumeonerror

Ignoriert Fehler bei einer mit dem Kommandozeilenparameter /startbackup initiierten Sicherung.

## /shutdownapp

Beendet Backup Service Home 3 nach einer mit dem Kommandozeilenparameter /startbackup initiierten Sicherung.

## /shutdownpc

Fährt den Computer nach einer mit dem Kommandozeilenparameter /startbackup initiierten Sicherung herunter.

## /startbackup

Startet eine manuelle Datensicherung für den aktuell angemeldeten Benutzer.
