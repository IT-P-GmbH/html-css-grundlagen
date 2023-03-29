# HTML- und CSS- Grundlagenseminar

Du lernst die Grundlagen von HTML und CSS/Sass unter Berücksichtigung neuer Spezifikationen und Browser-Implementation. Die erlernten Kenntnisse helfen dir auch, Fehler bei der Nutzung von Frameworks zu vermeiden oder einer spezifischen Anpassung an die Kundenwünsche gerecht zu werden.

## Nutzung

Dieses Seminar wird im [CoE Web durchgeführt](https://doku.it-p.de/display/KB/HTML-+und+CSS-+Grundlagenseminar+%7C+CoE+Web) und dort auch aufgezeichnet. Schaue dir diese dort an, um in Folge dessen ein Teilnahmezertifikat, sowie die Skill-Punkte zu erhalten.

Jedes Kapitel verfügt über ein eigenes Verzeichnis und einer README.md, die dir als Dokumentation und Aufgabenstellung dient. Lies dir zunächst aber bitte den Abschnitt [Installation](#Installation) durch, um zu erfahren, wie du mit den Kapiteln und den jeweiligen Code-Demos arbeiten kannst.

## Kapitel

1. [Starter-Template](01-startertemplate/README.md)\
   _Starterkit, Template und Normalize_
2. [Box model und Logical Properties](02-box-model-logical-properties/README.md)\
   _Collapsing Margins, Block- und Inline-Attribute_
3. [CSS Units, Spezifität und Vererbung](03-css-units-specifity/README.md)\
   _dvh, rem, lh und die Vermeidung von !important_
4. [Selektoren, Pseudo-Klassen und -Elemente](04-selectors-pseudo/README.md)\
   _:not, :has, :is und ::after_
5. [Layout-Konzepte](05-layouts/README.md)\
   _Flexbox, Grid, Position und Float_
6. [Media- und Container Queries](06-media-container-queries/README.md)\
   _Breakpoints, Viewports und Devices_
7. [Transitions und Animationen](07-transitions-animations/README.md)\
   _Übergänge und Effekte_
8. [Prä- und Post-Prozessoren](08-pre-post-processors/README.md)\
   _Einführung in Sass und Post-CSS_
9. [Skalierbare Projektstruktur](09-skalable-projects/README.md)\
   _Dateiorganisation und Best practise_

## Installation

Wir empfehlen die Verwendung der IDE [Visual Studio Code](https://code.visualstudio.com/). Klone dir zunächst das Repository dieses Seminars:

```shell
$ git clone http://gitlab.it-p.de/coe-web/html-css-grundlagen.git
$ cd html-css-grundlagen
```

Öffne es in der IDE diese `README.md` und schalte die Markdown-Vorschau ein (<kbd>Ctrl/Command</kbd>+<kbd>Shift</kbd>+<kbd>V</kbd>). Nutze diese zur Navigation zu den Kapieln oder alternativ die Github-Oberfläche.

### Voraussetzungen

Wir verwenden in den Demos Node.js, [yarn](https://yarnpkg.com/) als Package Manager und die vorkonfigurierten Entwicklungsumgebungen [Vite](https://vitejs.dev/) und [Parcel](https://parceljs.org/).

1. Lade dir den [Node.js-Installer](https://nodejs.org/en/download/) für dein System runter und führe die Installation durch.\
   _Windows-User sollten die Option „Automatically install necessary tools“ unter „Tools for native modules“ aktivieren._
2. Öffne das Terminal (Mac) bzw. die PowerShell (Windows).
3. Installiere yarn und kontrolliere die erfolgreiche Installation durch folgende Befehle (Eingabe bitte ohne `$`):

```shell
$ sudo npm install -g yarn
$ npm -v && yarn -v
```

> Unter Windows musst du die Ausführungsrichtlinien ändern, damit Skripte wie yarn ausgeführt werden dürfen. Gehe dazu in die Einstellungen unter **Datenschutz und Sicherheit → Entwickler → PowerShell** und bestätige dies mit einem Klick auf den Button **Anwenden**.

### Arbeiten mit den Kapieln

Öffne das Verzeichnis des zur bearbeitenden Kapitels in einem seperaten IDE-Fenster/Projekt und installiere die Dependencies. Zum Beispiel:

```shell
$ cd 01-startertemplate
$ code .
$ yarn
```

Neben der `README.md` als Arbeitssgrundlage stehen dir meistens folgende Befehle zur Verfügung:

<!-- prettier-ignore -->
| Befehl | Verwendung |
| ---- | --- |
| `yarn dev` | Start einer lokalen Entwicklungsumgebung. Alle Dateiänderungen werden durch hotloading nachgeladen und im Browser angezeigt. |
| `yarn build` | Zum Kompilieren einer minified version im `dist` Verezichis. |
| `yarn preview` | Vorschau der kompilierten Variante im Browser. | 
