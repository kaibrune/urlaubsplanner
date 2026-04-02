# Urlaubsplaner

Ein statisches Browser-Tool für die Urlaubsplanung in Deutschland.  
Du wählst Bundesland, Jahr und verfügbare Urlaubstage, setzt Zeiträume direkt im Kalender und siehst sofort, wie viele Urlaubstage du wirklich brauchst.

## Was das Tool macht

- zeigt ein komplettes Kalenderjahr
- markiert Feiertage, Brückentage und Schulferien
- berechnet gesetzte Urlaubstage nur auf Werktagen
- zeigt Resturlaub und freie Gesamttage
- schlägt gute Zeiträume mit wenig eingesetzten Urlaubstagen vor
- speichert die aktuelle Planung direkt im Browser
- erzeugt einen teilbaren Link zur aktuellen Ansicht

## So benutzt du das Tool

1. Bundesland wählen
2. Jahr wählen
3. Verfügbare Urlaubstage eintragen
4. Im Kalender einmal auf den Starttag und einmal auf den Endtag klicken
5. Den gesetzten Zeitraum in der Liste prüfen

Ein weiterer Klick auf einen Vorschlag übernimmt den Zeitraum direkt.

## Kalenderlogik

- Feiertage werden automatisch für das jeweilige Jahr berechnet
- Brückentage werden aus den Feiertagen abgeleitet
- Schulferien kommen aus den hinterlegten Datensätzen je Bundesland
- Jahre ohne Schulferien-Daten sind in der Jahresauswahl nicht verfügbar

## Farben im Kalender

- Wochenende
- Feiertag
- Brückentag
- Urlaub
- Vorschau
- Schulferien

Die Legende oberhalb des Kalenders zeigt die aktuelle Zuordnung.

## Zeiträume setzen und ändern

- 1. Klick setzt den Start
- 2. Klick setzt das Ende
- `ESC` bricht eine laufende Auswahl ab
- einzelne Zeiträume lassen sich in der Tabelle löschen
- oben rechts stehen `Undo`, `Redo`, `Alles löschen` und `Link kopieren`

## Vorschläge

Die Vorschläge basieren auf Feiertagen und Brückentagen.  
Bereits vollständig übernommene Vorschläge verschwinden automatisch aus der Liste.

## Speicherung

Die Planung wird lokal im Browser gespeichert.  
Wenn du dieselbe Browser-Umgebung erneut öffnest, bleibt dein Stand erhalten.

## Teilen

Über das Share-Icon oben rechts wird ein Link mit der aktuellen Planung erzeugt und in die Zwischenablage kopiert.

## Hinweise

- Das Tool läuft direkt im Browser
- es ist keine Anmeldung nötig
- die Daten gelten für Deutschland und deutsche Bundesländer
