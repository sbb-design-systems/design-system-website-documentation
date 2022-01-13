## 1. Was macht die Komponente?
Dient zur Strukturierung der Anzeige von Daten und Formularen.

## 2. Wann soll die Komponente eingesetzt werden? 
* Wenn innerhalb des gleichen Kontexts zwischen verschiedenen Aspekten gewechselt werden soll.
* Wenn die Inhalte der verschiedenen Aspekte nicht gleichzeitig vom Benutzer angesehen werden.

## 3. Regeln
* Es gibt mindestens zwei Register.
* Per Default ist immer das erste Register ausgewählt.
* Die Registerbezeichungen sind immer einzeilig.
* Die Registerbezeichung sollte möglichst kurz und prägnant sein, damit die Themen schnell erfasst werden können.
* Falls die Register für den Viewport zu lang sind, sind die weiteren Register mit einer horizontalen Scrollbar (Desktop) rsp. durch Swipen (Tablet / Mobile) erreichbar.
* Ein weiteres Tab-Modul innerhalb eines Registers ist nicht erlaubt.

## 4. Ausprägungen und Zustände 
Die Komponente hat folgende Zustände:
* Active
* Inactive
* Hover
* Focused

### 4.1 Standard
![Darstellung der Komponente Tab in der Ausprägung Standard](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/tab/images/tab_default.png 'class: image')

#### Design Spezifikation
* [Active](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/bVamvo#Inspector)
* [Inactive](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/WmnWQg#Inspector)
* [Hover](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/34xdzD#Inspector)
* [Focused](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/rvrLVx#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/tabs?variant=standard)

### 4.2 Mit Mengenindikatoren 
![Darstellung der Komponente Tab mit zusätzlichen Mengenindikatoren](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/tab/images/tab_indicator.png 'class: image')
* Der Mengenindikator liefert einen Hinweis, wie viele Einträge eine Liste im Content des Registers aufweist.
* Der Mengenindikator beinhaltet nur Zahlen, maximal 3-stellig.

#### Design Spezifikation
* [Active](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/ndDYoW#Inspector)
* [Inactive](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/QJ1gQ8#Inspector)
* [Hover](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/xDQ8vA#Inspector)
* [Focused](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/EwG1pY#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/tabs?variant=standard)