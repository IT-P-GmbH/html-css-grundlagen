# 01 Starter-Template

> Dieses Kapitel ist Bestandteil des Seminars [CSS @intro](../README.md). Bitte erarbeitete dir die Kentnisse in linealer Reihenfolge.

Websites sind durch den Browser vorformatiert: weißer Hintergrund, schwarzer Text in Serifenschrift, große Überschriften und Links je nach Status in Blau und Lila. Diese Voreinstellungen variieren allerdings von Browser zu Browser. Um diese zurückzusetzen oder einen einheitlichen Startpunkt für die eigene Website zu finden, wurden sogenannte [CSS Resets](https://de.wikipedia.org/wiki/Reset-Stylesheet) geschaffen.

Oft wurden diese CSS Resets als Dependency eingebunden, die sich dann je nach Variante unterschiedlich stark auf die eigene Website ausgewirkt haben. Sehr populär war [normalize.css](https://github.com/necolas/normalize.css), später gab es auch Varianten wie [modern-normalize](https://github.com/sindresorhus/modern-normalize), die kleiner waren und nur noch moderne Browser unterstützt hatten.

Heute sollte man diese nicht mehr verwenden. Wir verfolgen daher einen [Minimal-Ansatz](https://codepen.io/macx/pen/wvXYXGv), der ohne Abhängigkeiten auskommt.

## Die Aufgabe

Mache dich mit dem neuen „Reset“ vertraut, befolge die folgenden Schritte:

1. Öffne das Verzeichnis dieses Kapitels in deiner IDE.
2. Installiere die Dependencies mit `yarn`.
3. Starte einen Entwicklungsserver mit `yarn dev`.
4. Öffne die [src/reset.scss](src/css/_reset.scss).
5. Kommentiere Zeile für Zeile aus, um die Auswirkungen zu studieren.
