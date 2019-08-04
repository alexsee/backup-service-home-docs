# Häufig gestellte Fragen

## Wie erfahre ich, ob meine Version aktuell ist?

Sie können entweder auf der Webseite nachschauen, ob eine neue Version vorhanden ist oder Informationen zu bekannten Problemen, oder Sie nutzen die integrierte Aktualisierungsfunktion, um Backup Service Home 3 auf dem neusten Stand zu halten. Diese Funktion finden Sie im Hilfemenü (Hilfesymbol anklicken) des Konfigurationsmenüs.

## Wo erhalte ich Hilfe, wenn ich nicht weiter weiß oder Probleme auftreten?

Auf der Webseite erhalten Sie dieses Handbuch (möglicherweise in neuerer Version), welches auf häufig gestellte Fragen Antworten liefert. Ebenso ist ein Support-Forum vorhanden, wo Sie Ihre Fragen, Probleme und Kritik loswerden können.

Link zur Webseite: [http://www.alexosoft.de/](http://www.alexosoft.de/)

Link zum Forum: [http://www.alexosoft.de/forum/](http://www.alexosoft.de/forum/)

## Was ist BSHService.exe?

Die BSHService.exe ist Teil von Backup Service Home 3. Dieser Dienst wird derzeit benötigt, um Dateien zu sichern, die gerade verwendet werden. Da für diesen Vorgang Administratorenrechte erforderlich sind, läuft diese Anwendung als Systemdienst, damit Sie keine Administratorenrechte für die Verwendung von Backup Service Home 3 benötigen.

## Kann ich Backup Service Home 3 mit mehreren Benutzern auf einem PC verwenden?

Ja. Jeder Benutzer sieht nur seine Sicherungen und Einstellungen.

## Können mehrere PCs die gleiche externe Festplatte (auch via Netzwerk) nutzen?

Ja.

## Was bedeuten die Farben des Symbols rechts unten in der Taskleiste?

* Rot: Es ist ein Fehler aufgetreten, oder Backup Service Home 3 ist deaktiviert und sichert keine Dateien. Es ist möglicherweise Ihre Benutzerinteration notwendig.

* Blau: Es wird eine Datensicherung durchgeführt.

* Grün: Backup Service Home 3 sichert Ihre Dateien und es sind keine Fehler aufgetreten.

## Was bedeutet vollautomatische Sicherungen?

Im Modus „Vollautomatische Sicherungen“ wird von Ihren ausgewählten Dateien jede Stunde eine Kopie angelegt. Diese Kopien sind für 24 Stunden zur Wiederherstellung verfügbar. Danach löscht Backup Service Home 3 diese Kopien um Speicherplatz zu sparen. So sind für einen gesamten Monat tägliche Kopien Ihre Dateien verfügbar. Danach behält Backup Service Home 3 wöchentliche Kopien bereit.

## Kann ich Dateien von der Sicherung ausschließen?

Ja. Sie können sowohl gesamte Ordner inklusive deren Unterordner ausschließen, als auch bestimmte Dateitypen oder Dateien, die eine bestimmte Dateigröße überschreiten. Mit der RegEx-Maske lassen sich sogar umfangreichere Kriterien für das Ausschließen von Dateien festlegen.

## Wie kann ich nach einem System-Crash meine Dateien wiederherstellen?

Installieren Sie zunächst Backup Service Home 3 auf Ihrem PC. Doppelklicken Sie auf das Backup Service Home 3 Symbol, um den Konfigurationsassistenten aufzurufen. Klicken Sie nun auf Importieren. Wählen Sie das Sicherungsmedium aus, auf dem Sie Ihre Datensicherung zuvor durchgeführt haben. Nun können Sie den Computer und den Benutzer auswählen.

Nun müssen Sie nur noch die Verzeichnispfade korrigieren, sofern sich diese geändert hat. Zum Beispiel, wenn Ihre Musik anstatt in C:\Benutzer\Mustermann\Musik in C:\Benutzer\Max Mustermann\Musik befindet.

Weitere Informationen finden Sie im Thema [Wiederherstellung (worst case scenario)](restore.md).

## Wo erhalte ich detailliertere Informationen zu dem Sicherungsprozess?

Wenn während der Sicherung Fehler auftreten, werden diese im Ereignisprotokoll von Windows protokolliert. Dieses lässt sich über das Hilfemenü in Backup Service Home 3 oder über die Systemsteuerung aufrufen.

## Welches Verschlüsselungsverfahren wird verwendet?

Advanced Encryption Standard mit 256 Bit Schlüsselstärke.

## Ist die Sicherung im Netzwerk möglich?

Ja. Es wird empfohlen ein Netzlaufwerk zu verwenden. Die Verwendung von Netzwerkpfaden ist im Konfigurationsassistent nicht möglich. Sie können aber nach diesem Assistenten in der Konfiguration ein Netzwerkpfad angeben. Ebenso kann ein FTP-Server verwendet werden.

## Wie kann ich Dateien in ein anderes als das Originalverzeichnis wiederherstellen?

Halten Sie STRG-Taste gedrückt, wenn Sie auf die Wiederherstellen Schaltfläche klicken. Dann können Sie den Zielort auswählen.

## Gibt es einen noch schnelleren Weg zur Schnellansicht, als die Schaltfläche?

Ja. Sie können einfach die Leertaste drücken, um eine Vorschau für die markierte Datei zu erhalten. Mit der gleichen Taste lässt sich die Ansicht wieder schließen.

## Was bedeutet "Version fixieren"?

Wenn Sie eine Version fixieren, dann wird diese nicht von der automatischen Sicherungsbereinigung gelöscht (wenn Sie den Vollautomatischen Sicherungsmodus verwenden).

## Können mehrere unterschiedliche Strategien oder Backupaufgaben gleichzeitig definiert sein?

Nein, das ist nicht möglich.
