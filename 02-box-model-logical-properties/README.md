# 02 Box model und Logical Properties

> Dieses Kapitel ist Bestandteil des Seminars [CSS @intro](../README.md). Bitte erarbeitete dir die Kentnisse in linealer Reihenfolge.

## Box model

Das [CSS box model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model) beschreibt, wie die Browser HTML-ELemente rendern. Die Breite und Höhe dieser Elemente ergibt sich aus der Summe von `width`, `padding`, `border` und `margin`. Das solltest du beherrschen, um zu verstehen, was welche CSS-Attribute du setzen kannst, um die gewünschte Änderung vornehmen zu können.

## Logical Properties

Physikalische Größenangaben wie `width`, `height`, sowie Werte wie `top`, `right`, `bottom` und 'left' werden dann zum Problem, wenn sich beispielsweise der Flow oder die Schreibrichtung der Website ändert.

Chinesisch, Japanisch, Koreanisch und Mongolisch können nämlich entweder horizontal von links nach rechts oder vertikal von oben nach unten geschrieben werden. Auch wenn in diesen Sprachen die Schreibrichtung meist horizontal gesetzt wird, überwiegt im Japanischen die vertikale Schreibrichtung. Manche Websites verwenden einen Mix. Während vertikal geschriebene Sprachen wie Chinesich, Japanisch und Koreanisch oben rechts anfangen, wird im mongolischen von links nach rechts gelesen.

Und so können Abstände plötzlich an der falsche Stelle stehen oder Größenangaben in der Axe getauscht sind. Um diesen Problem mit einem einheitlichen CSS entgegenzutreten, wurden die [Logitcal Properties](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Logical_Properties?retiredLocale=de) eingeführt, also den logischen Eigenschaften und Werten. Statt `top` und `bottom` verwendet man so beispielsweise nun `start` und `end`.

Auch wenn andere Sprachen nicht Verwendung finden, solltest du dir angewöhnen, Logical Properties zu verwenden.

## Die Aufgabe

Starte das Projekt und schaue dir zunächst das Schaubild des Box model an. Verändere die Werte, um zu verstehen, wie sich die Größenangaben ändern. Dann schalte zusätzlich auch noch die Logical Properties ein, um zu sehen, wie die Eigenschaften sich ändern.
