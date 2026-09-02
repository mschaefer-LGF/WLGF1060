# Fernerkundung in der Forstwirtschaft

Aktives Quarto-Book für das freie Wahlmodul an der Fakultät
Landschaftsarchitektur, Gartenbau und Forst der FH Erfurt.

## Eckdaten

- 5 ECTS, 150 Stunden Workload
- 4 SWS, 60 Stunden Präsenz und 90 Stunden Selbststudium
- empfohlen für das 5. Fachsemester
- Prüfungsleistung: mündliche Prüfung mit Präsentation
- Fallstudie: Waldbrand 2025 bei Gösselsdorf auf der Saalfelder Höhe
- Arbeitsumgebung: QGIS mit Semi-Automatic Classification Plugin

## Arbeitsprinzip

Die `.qmd`-Dateien sind die bearbeitbaren Kapitel. Der Ordner `_book` ist nur
die erzeugte Vorschau und wird nicht manuell verändert.

## Vorschau

Voraussetzung ist eine lokale Installation der Quarto CLI.

```powershell
quarto preview --profile dev
```

## Rendern

```powershell
quarto render --profile dev
```

Die fertige Website liegt danach in `_book/index.html`.
