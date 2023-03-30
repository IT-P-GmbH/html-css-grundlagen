# 01 Starter-Template

> Dieses Kapitel ist Bestandteil des Seminars [HTML- und CSS-Grundlagen](../README.md). Bitte erarbeitete dir die Kentnisse in linealer Reihenfolge.

Websites sind durch den Browser vorformatiert: weißer Hintergrund, schwarzer Text in Serifenschrift, große Überschriften und Links je nach Status in Blau und Lila. Diese Voreinstellungen variieren allerdings von Browser zu Browser. Um diese zurückzusetzen oder einen einheitlichen Startpunkt für die eigene Website zu finden, wurden sogenannte [Reset-Stylesheets](https://de.wikipedia.org/wiki/Reset-Stylesheet) geschrieben.

Oft wurden diese CSS Resets als Dependency eingebunden, die sich dann je nach Variante unterschiedlich stark auf die eigene Website ausgewirkt haben. Sehr populär war [normalize.css](https://github.com/necolas/normalize.css), später gab es auch Varianten wie [modern-normalize](https://github.com/sindresorhus/modern-normalize), die kleiner waren und nur noch moderne Browser unterstützt hatten.

Aus heutiger Sicht, mutet das an wie Heute sollte man diese nicht mehr verwenden, denn aaus nicht mehr verwenden. Wir verfolgen daher einen [Minimal-Ansatz](https://codepen.io/macx/pen/wvXYXGv), der ohne Abhängigkeiten auskommt.

## Die Aufgabe

Mache dich mit dem neuen „Reset“ vertraut, befolge die folgenden Schritte:

1. Öffne das Verzeichnis dieses Kapitels in deiner IDE und installiere die Dependencies mit `yarn`.
2. Starte das Projekt mit `yarn dev`.
3. Öffne die [src/reset.scss](src/css/_reset.scss).
4. Kommentiere Zeile für Zeile aus, um die Auswirkungen auf das Layout zu studieren.
