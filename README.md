# Geburtstagsliste für EFG Niedernberg

## Beschreibung

Dieses kleine Webprojekt zeigt alle Geburtstage der aktuellen Woche an, also von letztem Montag bis diesem Sonntag. 

- Die Geburtstage werden aus einer externen `data.json` Datei geladen.
- Es werden nur die Geburtstage angezeigt, die in diesem Zeitraum liegen.
- Die Namen werden genau in der Reihenfolge angezeigt, wie sie in der JSON-Datei stehen.
- Unter der Liste werden das heutige Datum, der letzte Montag und der kommende Sonntag angezeigt.
- Über einen Button können die angezeigten Namen in die Zwischenablage kopiert werden.
- Die Benutzeroberfläche ist einfach und übersichtlich gestaltet.

## Nutzung

Das Projekt eignet sich ideal für den Einsatz in der Gemeinde der **EFG Niedernberg**, um Geburtstage der Gemeindemitglieder übersichtlich darzustellen und schnell kopieren zu können.

## Voraussetzungen

- Die Datei `data.json` muss die Geburtstage im Format 
  ```json




  [
    { "name": "Max Maximilian", "birthday": "01.01" },
    { "name": "Sam Samman", "birthday": "15.07" }
  ]
