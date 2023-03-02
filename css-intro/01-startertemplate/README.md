# 01 Starterertemplate

> Dieses Kapitel ist Bestandteil des Seminars [CSS @intro](../README.md). Bitte erarbeitete dir die Kentnisse in linealer Reihenfolge.

Die Browser formatieren HTML-Elemente out of the box mit Farben, Größen und Abständen. Diese Basisangaben variieren allerdings von Browser zu Browser. Um diese zurückzusetzen oder einen einheitlichen Startpunkt für die eigene Website zu finden, wurden sogenannte [CSS Resets](https://de.wikipedia.org/wiki/Reset-Stylesheet) ins Leben gerufen.

Oft wurden diese CSS Resets als Dependency eingebunden, die sich dann je nach Variante unterschiedlich stark auf die eigene Website ausgewirkt haben. Sehr populär war [normalize.css](https://github.com/necolas/normalize.css), später gab es auch Varianten wie [modern-normalize](https://github.com/sindresorhus/modern-normalize), die kleiner waren und nur noch moderne Browser unterstützt hatten.

## Die Aufgabe

Wir verwenden heute einen [Minimalansatz](https://codepen.io/macx/pen/wvXYXGv), der ohne Dependency auskommt. Um zu verstehen, was dieser an der Website ändert, befolge diese Schritte:

1. Starte das Projekt.
2. Öffne die [reset.scss](src/css/_reset.scss).
3. Kommentiere Zeile für Zeile aus, um die Auswirkungen zu studieren.
