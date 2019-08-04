# Wiederherstellung (worst case scenario)

## Hinweise zur Wiederherstellung

In diesem Artikel soll Ihnen die Vorgehensweise im Falle eines kompletten Datenverlustes vorstellen. Wenn Sie lediglich einige Dateien wiederherstellen möchten, lesen Sie Wiederherstellung einer oder mehrerer Dateien.

Im Falle eines vollständigen Datenverlusts und damit auch der Funktionsfähigkeit von Backup Service Home 3 gibt es verschiedene Möglichkeiten der Wiederherstellung. In diesem Artikel soll eine empfohlene Methode dargestellt werden, wie eine Wiederherstellung reibungsfrei läuft.

## Wiederherstellung bei Neuinstallation des Betriebssystems

Im Falle einer Neuinstallation des Betriebssystems, müssen Sie zunächst Backup Service Home 3 neuinstallieren. Sie erhalten die neuste Version jeweils auf der Alexosoft Homepage. Möglicherweise müssen Sie noch weitere Software installieren, die Voraussetzung für die Installation von Backup Service Home 3 ist.

Eine Neueinrichtung wie in [Erste Einrichtung](index.md) ist nicht notwendig und überschreibt die Datenbankdatei, wodurch eine Wiederherstellung nicht mehr ohne weiteres möglich ist.

Sie können nun wie in [Wiederherstellung bei Neuinstallation](restore-2.md) vorgehen, um die Datensicherung zu importieren.

## Wiederherstellung bei Nutzung eines älteren Systemimage

Wenn Sie ein Systemimage aufspielen, auf dem Backup Service Home 3 installiert ist, ist es nach derzeitigem Stand unbedingt erforderlich, das Sicherungsmedium von dem Computer zu trennen. Dadurch, dass Backup Service Home 3 wie gehabt arbeitet und derzeit nicht überprüft, ob eine neuere Datenbank auf dem Sicherungsmedium vorhanden ist, die Datenbank überschreibt. Dadurch wird eine falsche Datenbank auf das Sicherungsmedium geschrieben und die Wiederherstellung ist nicht mehr möglich.

Im Falle dass die Datenbank bereits überschrieben wurde, ist eine Wiederherstellung entweder auf manuelle Weise möglich oder durch das Nutzen des Database Recovery Tools. Sie bekommen auf Anfrage den Downloadlink für dieses Tool. Diese Vorgehensweise ist nur für eine fehlerhafte Datenbankdatei vorgesehen.
