## 1. Was macht die Komponente?
Klappt einen bestehenden Text weiter auf, um noch mehr Informationen anzuzeigen.

## 2. Wann soll die Komponente eingesetzt werden? 
Bei langen Zusatzinformationen.

## 3. Regeln 
* Der Textexpand darf nur für Texte eingesetzt werden.
* Im aufgeklappten Zustand dürfen nebst dem Ausblenden keine weiteren Interaktionselemente eingesetzt werden.
* Die Trennung der Texte muss so erfolgen, dass der Kontext der gesamten Information bereits im zugeklappten Zustand klar ist.
* Darf nur bei mehrzeiligen Texten eingesetzt werden.
* Mehrfachverschachtelungen sind nicht erlaubt.
* Der Textexpand darf nicht zur Strukturierung von Elementen verwendet werden.
* Titel und andere Strukturmittel sind im ausgeblendeten Zustand nicht erlaubt.

## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Collapsed
* Expanded

### 4.1 Standard
![Darstellung der Komponente Textexpander](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/textexpand/images/textexpand_default.png 'class: image')

#### Design Spezifikation
* [Collapsed](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/ApRlk4#Inspector)
* [Expanded](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/0Z7b2y#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/textexpand?variant=standard)