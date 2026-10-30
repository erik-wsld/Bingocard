# Heidelberg Bingocard

Eine klassische 4×4-Bingokarte für den Heidelberg-Trip als einzelne HTML-Datei, ohne Build-Schritt.

## Funktionen

- 16 Aufgaben in fester Anordnung (zufällig verteilt, aber für alle gleich)
- Felder per Tipp oder Klick abhaken
- Bingo-Erkennung für Reihen, Spalten und Diagonalen
- Stand (Haken) bleibt im Browser gespeichert
- „Haken zurücksetzen“
- Hell- und Dunkelmodus, druckbar

## Benutzung

`index.html` im Browser öffnen. Mehr braucht es nicht.

## Aufgaben ändern

In `index.html` das Array `TASKS` im Skriptbereich bearbeiten. Es muss genau 16 Einträge enthalten, sonst passt das 4×4-Raster nicht. Die Reihenfolge im Array ist die Anordnung auf der Karte (zeilenweise von links oben nach rechts unten).

## Auf GitHub Pages veröffentlichen

1. Repository auf GitHub anlegen und die Dateien hochladen.
2. Unter *Settings → Pages* als Quelle den Branch `main` und den Ordner `/ (root)` wählen.
3. Nach kurzer Zeit ist die Karte unter `https://<benutzername>.github.io/heidelberg-bingocard/` erreichbar.
