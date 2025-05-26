# Hangover-WUEedition

Interaktive Karte zur Würzburger Studierendenkultur. Dieses Projekt ist Teil eines universitären Seminars und dient der Erkundung, Dokumentation und Vermittlung lokaler Freizeitangebote für Studierende, insbesondere entlang der Straßenbahnlinien 4 und 5.

## Ziel

Das Ziel ist eine interaktive Karte, die ausgewählte Orte aus studentischer Perspektive sichtbar macht. Die Karte enthält sowohl Orte, die in eigens produzierten Videos vorgestellt werden, als auch zusätzliche Spots, die über Umfragen und Recherche zusammengetragen wurden.

## Inhalte und Funktionen

- Darstellung von Orten in Würzburg mit geografischer Verortung
- Zuordnung zu Straßenbahnlinien (Linie 4 und 5)
- Kategorisierung nach Aktivitätsform (z. B. Entspannen, Sport, Ausgehen)
- Verlinkung zu begleitenden Videos und Bildern
- Detailansicht mit Beschreibung, Tags, Öffnungszeiten, Barrierefreiheit, Preisangaben
- Such- und Filterfunktionen
- Darstellung echter Linienverläufe der Straßenbahnlinien 4 und 5 auf Basis von OpenStreetMap-Daten

## Projektstruktur

    Hangover-WUEedition/
    ├── index.html               // Hauptseite mit Leaflet-Karte (enthält aktuell JS/CSS inline)
    ├── data.geojson            // Spot-Daten inkl. Beschreibung, Medienlinks, Koordinaten
    ├── linie4.geojson          // Linienverlauf Linie 4
    ├── linie5.geojson          // Linienverlauf Linie 5
    ├── pictures/               // Bilder zu den Orten
    ├── css/                    // optionaler Ordner für eigene CSS-Dateien
    ├── js/                     // optionaler Ordner für eigene JS-Module
    └── README.md              // Projektdokumentation

## Datenquellen

- Videoaufnahmen durch das Projektteam
- Ergebnisse aus studentischen Umfragen
- OpenStreetMap (für Linienverläufe)
- Eigene Ortsrecherche


## Hinweis zu GitHub Pages

Die Karte wird über GitHub Pages zugänglich gemacht. Das Repository dient ausschließlich der Bereitstellung und Archivierung des Projekts im universitären Rahmen.

## Lizenz

Die interaktive Karte basiert auf Leaflet (BSD 2-Clause License) und verwendet Kartendaten aus OpenStreetMap (ODbL). Eine Nutzung oder Weiterverbreitung der Inhalte (einschließlich Code, Videos, Bilder, Daten) ist nur im Rahmen des Seminars und mit Zustimmung des Projektteams zulässig.
