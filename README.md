# Hangover-WUEedition

Interaktive Karte zur Würzburger Studierendenkultur. Dieses Projekt ist Teil eines universitären Seminars und dient der Erkundung, Dokumentation und Vermittlung lokaler Freizeitangebote für Studierende.

## Ziel

Das Ziel ist eine interaktive Karte, die ausgewählte Orte aus studentischer Perspektive sichtbar macht. Die Karte enthält sowohl Orte, die in eigens produzierten Videos vorgestellt werden, als auch zusätzliche Spots, die über Umfragen und Recherche zusammengetragen wurden.

## Inhalte und Funktionen

- Darstellung von Orten in Würzburg mit geografischer Verortung
- Kategorisierung nach Aktivitätsform (z. B. Entspannen, Sport, Ausgehen)
- Verlinkung zu begleitenden Videos und Bildern
- Detailansicht mit Beschreibung, Tags, Öffnungszeiten, Barrierefreiheit, Preisangaben
- Such- und Filterfunktionen

## Technische Grundlagen

Dieses Projekt verwendet [Leaflet](https://leafletjs.com/) zur Darstellung der interaktiven Karte.

Weitere Informationen:

- Leaflet Dokumentation: https://leafletjs.com/reference.html
- Einführung: https://leafletjs.com/examples/quick-start/
- GeoJSON-Handling: https://leafletjs.com/examples/geojson/

## Projektstruktur

    Hangover-WUEedition/
    ├── index.html               // Hauptseite mit Leaflet-Karte (enthält aktuell JS/CSS inline)
    ├── data.geojson            // Spot-Daten inkl. Beschreibung, Medienlinks, Koordinaten
    ├── pictures/               // Bilder zu den Orten
    ├── css/                    // optionaler Ordner für eigene CSS-Dateien
    ├── js/                     // optionaler Ordner für eigene JS-Module
    ├── ANLEITUNG.md            // Anleitung zur Mitarbeit
    └── README.md              // Projektdokumentation

## Datenquellen

- Videoaufnahmen durch das Projektteam
- Ergebnisse aus studentischen Umfragen
- OpenStreetMap
- Eigene Ortsrecherche
  
## Beteiligung am Projekt

Eine Anleitung zur Mitarbeit findet sich in der Datei `ANLEITUNG.md`.

## Hinweis zu GitHub Pages

Die Karte wird über GitHub Pages zugänglich gemacht. Das Repository dient ausschließlich der Bereitstellung und Archivierung des Projekts im universitären Rahmen.

Die Karte kann hier aufgerufen werden:

https://moritz380.github.io/Hangover-WUEedition/

## Lizenz

Die interaktive Karte basiert auf Leaflet (BSD 2-Clause License) und verwendet Kartendaten aus OpenStreetMap (ODbL). Eine Nutzung oder Weiterverbreitung der Inhalte (einschließlich Code, Videos, Bilder, Daten) ist nur im Rahmen des Seminars und mit Zustimmung des Projektteams zulässig.
