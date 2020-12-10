## 1. Was macht die Komponente?
Dient zur Darstellung von Detailinformationen einer Content-Seite.

## 2. Wann soll die Komponente eingesetzt werden? 
* Wenn zu einem Teil einer Seite on-demand detailliertere oder zusätzliche Informationen angezeigt werden soll (beispielsweise erweiterte Hilfestellungen, bei denen der [Tooltip](https://digital.sbb.ch/de/websites/components/tooltip) nicht ausreicht).
* Zur Darstellung des Editiermodus bei Formularen.
* Zur vergrösserten Ansicht von Bildern.

## 3. Regeln
* Die referenzierte Seite wird nicht verlassen.
* Die Lightbox öffnet sich immer Browserfenster-füllend.
* Die Lightbox hat einen eigenen Header, welcher immer sticky ist.
* Im Header dürfen kontextbeschreibende Informationen stehen (beispielsweise die Zug-Nummer).
* Der Inhalt der Lightbox kann im Rahmen des Grunddesigns gestaltet werden.

## 4. Ausprägungen und Zustände
### 4.1 Standard
![Darstellung der Komponente Lightbox in der Ausprägung Standard](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/lightbox/images/lightbox_default.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/QJ1g5b#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/public/components/lightbox)

### 4.2 Mit Formularkomponenten
![Darstellung der Komponente Lightbox mit Formular als Inhalt](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/lightbox/images/lightbox_form.png 'class: image')
* Eine Lightbox mit Formularelementen erhält mindestens einen «Abbrechen» und einen «Übernehmen» Button.
* Der «Abbrechen» Button schliesst die Lightbox wieder.
* Wird die Lightbox geschlossen («Abbrechen» oder X-Button) während bereits Eingaben im Formular geändert wurden, erscheint ein Warnhinweis das ungesicherte Daten im Formular sind.
* Die Buttons eines Formulars («Abbrechen», «Übernehmen», andere Funktionen) dürfen im Footer eingesetzt werden.
* Der Footer ist immer sticky und wird über die ganze Breite der Lightbox dargestellt (gleich wie Header).

#### Design Spezifikation
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/xDQ8a0#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/public/components/lightbox)