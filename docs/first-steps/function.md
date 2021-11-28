# Funktionsweise

## Funktionsweise der Sicherung

Backup Service Home 3 ist eine sogenannte Versionssicherung. Darunter versteht man eine Software, die mehrere Abbilder einer Datei anfertigt, sodass man zu nahezu jeder Dateiänderung zurückgehen kann. So können Sie sich zum Beispiel anzeigen lassen, wie Ihr PC vor einer Woche oder einem Monat aussah. Ein weiterer Vorteil besteht in der Geschwindigkeit. Im Gegensatz zu anderen Methoden muss bei der Versionssicherung nur der Teil der Daten gesichert werden, der sich geändert hat.

Aber keine Angst, denn Backup Service Home 3 kümmert sich ohne Ihr Zutun um die Organisation Ihrer Datensicherungen, sodass Sie sich auf das Wesentliche konzentrieren können.

Damit Backup Service Home 3 den Überblick behält, erzeugt es eine Datenbank, die alle Informationen enthält, die notwendig sind, um Ihre Datensicherung wiederherzustellen. Die Datenbank wird bei jeder Sicherung automatisch auf dem Sicherungsmedium gesichert. Sie nennt sich Backup.bshdb und liegt in der Regel im Verzeichnis Backups\Computername\Benutzername.

Ihre Dateien können auch ohne die Software wiederhergestellt werden (allerdings mit mehr Aufwand). Alle Dateien werden (außer bei der Verschlüsselung) in einem für Sie lesbarem Format gespeichert. Sie benötigen keinerlei weitere Software, um auf Ihre Sicherung zuzugreifen. Die Schwierigkeit besteht darin, dass in jedem Sicherungsordner nur jeweils die Dateien enthalten sind, die geändert oder erstellt worden sind. Sie müssten also im Extremfall alle Sicherungen durchsuchen, um zu finden, was Sie suchen. Es empfiehlt sich daher die Wiederherstellung unbedingt mit der Software zu erledigen.

!!! note

    Wenn Sie Datensicherungen aus Backup Service Home 3 entfernen, bewirkt das nicht automatisch, dass der entsprechende Ordner auf dem Sicherungsmedium ebenfalls gelöscht wird. Das hat den Hintergrund, dass Backup Service Home 3 Verweise aus dieser Datensicherung behält, sodass andere Datensicherungen wiederhergestellt werden können. Durch Löschen dieser Ordner zerstören Sie u.U. Ihre gesamte Datensicherung. Daher Löschen Sie Sicherungen nur aus Backup Service Home 3 heraus.

## Vollautomatische Datensicherungen

Wenn Sie den vollautomatischen Datensicherungsmodus verwenden (wird automatisch als Standard eingestellt, wenn Sie wie in Erste Einrichtung vorgegangen sind), dann sichert Backup Service Home 3 Ihre Dateien und Ordner in einen festen Intervall. Ebenso kümmert es sich um alte Datensicherungen und dünnt diese im Zeitverlauf aus.

Im vollautomatischen Sicherungsmodus erstellt Backup Service Home 3 jede Stunde eine Sicherung. Diese stündlichen Sicherungen werden für 24 Stunden aufbewahrt. Danach werden diese Sicherungen zusammengefasst, sodass Sie je Tag eine Sicherung (nämlich den Zustand der letzten Sicherung an diesem Tag) besitzen. Diese täglichen Sicherungen bewahrt Backup Service Home 3 einen gesamten Monat auf, um diese danach zu wöchentlichen Sicherungen zusammenzufassen.

Durch diesen automatischen Modus haben Sie eine optimale Ausnutzung Ihres Sicherungsmediums und gleichzeitig haben Sie kleine Intervalle zwischen den Sicherungen, zu denen Sie zurückkehren können.

## Zeitplanbasierte Datensicherungen

Wenn Sie Ihren Sicherungszeitplan selbst zusammenstellen möchten, dann verwenden Sie die **zeitplanbasierten Sicherungen**, um volle Flexibilität zu erhalten. Sie können bestimmen, wann Backup Service Home 3 Datensicherungen durchführen soll, und welche Datensicherungen es vorhalten soll. Ebenso ist es möglich verpasste Sicherungszeitpunkte nachzuholen, falls Ihr Computer an diesem Zeitpunkt nicht verfügbar ist.

## Manuelle Datensicherungen

Wenn Sie Datensicherungen lieber von Hand durchführen möchten, können Sie den **manuellen Sicherungsmodus** verwenden. Alle automatischen Sicherungen sind dadurch deaktiviert und Sie können mittels zwei Mausklicks eine Datensicherung anstoßen.
