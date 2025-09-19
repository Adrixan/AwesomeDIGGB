# Alles im Blick: Den Projektstatus verfolgen

## Warum: Wir lernen eine Tabelle so zu formatieren, dass sie sich automatisch färbt um auf einen Blick zu sehen, welche Aufgaben erledigt sind.

## Aufgabe: Fügt eurem Projektplan eine Status-Spalte mit einem Dropdown-Menü hinzu und sorgt dafür, dass erledigte Aufgaben automatisch grün markiert werden.

Schritt-für-Schritt Anleitung:
1. Öffnet euren Projektplan.
2. Fügt die Status-Spalte hinzu: Erstellt eine neue Spalte mit der Überschrift "Status".
3. Erstellt die Dropdown-Liste:
* Markiert alle Zellen in der neuen Spalte.
* Geht im Menü auf "Daten" -> "Datenüberprüfung".
* Wählt bei "Zulassen" die Option "Liste".
* Gebt bei "Quelle" ein: Offen;In Arbeit;Erledigt
4. Richtet die bedingte Formatierung ein:
* Markiert eure gesamte Tabelle (alle Zeilen und Spalten mit Inhalt).
* Geht im Menü auf "Start" -> "Bedingte Formatierung" -> "Neue Regel...".
* Wählt "Formel zur Ermittlung der zu formatierenden Zellen verwenden".
* Gebt die Formel ein: =$H2="Erledigt" (wenn H die Status-Spalte ist).
* Klickt auf "Formatieren...", wählt eine grüne Füllfarbe und bestätigt alles.

