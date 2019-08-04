# Sicherungsoptionen

Im Reiter **Sicherungsoptionen** können Sie festlegen, ob die Datensicherung komprimiert **oder** verschlüsselt werden soll. Derzeit existiert keine Möglichkeit, beide Optionen gleichzeitig auszuwählen.

## Datensicherung komprimieren

Wenn Sie sich entscheiden die Datensicherung zu komprimieren, dann wird jede einzelne Datei in ein eigenes Archiv gepackt. Das hat den Vorteil, dass wenn ein Archiv beschädigt ist, dass auch nur diese eine Datei nicht wiederhergestellt werden kann. Würde Backup Service Home 3 alle Dateien in ein Archiv verpacken, wäre keine Wiederherstellung der gesamten Datensicherung möglich.

Bei der Komprimierung können Sie entscheiden, wie stark Backup Service Home 3 die Datensicherung komprimieren möchten. Es stehen 9 Stufen zur Verfügung (1 - niedrige Kompression, 9 - hohe Kompression).

> [!WARNING]
> Das Komprimieren erfordert mehr Rechenleistung und führt dazu, dass eine Datensicherung länger dauert.

## Datensicherung verschlüsseln

Wenn Sie sich entscheiden die Datensicherung zu verschlüsseln, dann wird jede einzelne Datei einzeln verschlüsselt. Als Verschlüsselungsverfahren setzt Backup Service Home 3 auf den aktuellen Verschlüsselungsstandard Advanced Encryption Standard mit Schlüsselstärke von 256 Bit.

Sollten Sie bereits Datensicherungen durchgeführt haben und nun die Verschlüsselung aktivieren, dann werden die bereits vorhandenen Sicherungen nicht verschlüsselt. Die Verschlüsselung gilt erst ab der nächsten Datensicherung. Beachten Sie hier, dass Backup Service Home 3 jeweils nur neue oder veränderte Dateien sichert und somit nicht alle Dateien verschlüsselt sind. In diesem Fall wird empfohlen die Datensicherungen zu löschen und danach die Verschlüsselung zu aktivieren, um in jedem Fall zu garantieren, dass alle Dateien verschlüsselt sind.

Wenn Sie sich entscheiden die Verschlüsselung wieder zu deaktivieren, dann entschlüsselt Backup Service Home 3 alle Ihre Datensicherungen. Dieser Vorgang kann u.U. einige Minuten bis Stunden dauern (je nach Größe Ihrer Datensicherung).

Damit Sie nicht ständig Ihr Kennwort eingeben müssen, speichert Backup Service Home 3 das Kennwort für die aktuelle Sitzung. Alternativ können Sie das Kennwort speichern lassen. Dieses wird nicht auf dem Sicherungsmedium, sondern in Ihrem Benutzerprofil auf Ihrem Computer abgelegt.

> [!IMPORTANT]
> Sollten Sie Ihr Kennwort vergessen haben, ist eine Wiederherstellung der Daten nicht mehr möglich.
