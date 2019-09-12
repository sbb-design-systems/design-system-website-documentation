## 1. Was macht das Element? 
* Unterstützt den Benutzer bei der Eingabe mit Vorschlägen.

## 2. Wann soll das Element eingesetzt werden? 
* Wenn ein Eingabefeld viele vordefinierte Werte aufweisen kann.
* Als Hilfe zur Vorschau bei Suchresultaten/-feldern.

## 3. Regeln
* Die Autocompletion hat immer ein Label.
* Optionale Eingaben werden mit dem Text «(optional)» hinter dem Label versehen. Bei kurzen Feldern kann der Text «(optional)» mit «(opt.)» abgekürzt werden.
* Für detaillierte Erklärungen kann neben dem Label ein Fragezeichen im Kreis dargestellt werden. Beim Klick auf dieses Fragezeichen öffnet sich ein [Tooltip](https://digital.sbb.ch/de/webapps/components/tooltip).
* Während der Eingabe werden direkt Vorschläge eingeblendet (typischerweise nach drei Zeichen, kann aber projektspezifisch angepasst werden).
* Die aufgelisteten Einträge können mittels Pfeiltasten durchlaufen und mit Enter übernommen werden.
* Es werden maximal 10 Vorschläge angezeigt.
* Bei der Auswahl eines Elementes schliesst sich die Autocompletion-Auswahl.

## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Default
* Hover

### 4.1 Standard
![Darstellung des Autocomplete, Standard](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/autocompletion/images/autocompletion_default.png 'class: image')

#### Design Spezifikation
*   [Default](https://sbb.invisionapp.com/d/#/console/17140415/383359152/inspect)
*   [Hover](https://sbb.invisionapp.com/d/#/console/17140415/383359153/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/business/components/autocomplete)

### 4.2 Mit Trefferanzeige
Optional zur Standard-Ausprägung kann diese Variante eingesetzt werden, wenn eine Autocompletion-Liste immer mehr als die maximal angezeigten 10 Treffer beinhaltet.
![Darstellung des Autocomplete, mit Trefferanzeige](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/autocompletion/images/autocompletion_overflow.png 'class: image')

#### Design Spezifikation
*   [Default](https://sbb.invisionapp.com/d/main#/console/17140415/355318376/inspect)
*   [Hover](https://sbb.invisionapp.com/d/main#/console/17140415/355318377/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/business/components/autocomplete)

### 4.3 Mit statischen Einträgen
![Darstellung des Autocomplete, mit statischen Einträgen](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/autocompletion/images/autocompletion_static.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/17140415/355318378/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/17140415/355318379/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/business/components/autocomplete)