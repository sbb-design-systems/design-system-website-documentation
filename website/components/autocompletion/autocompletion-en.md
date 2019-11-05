## 1. Was macht die Komponente?
* Unterstützt den Benutzer bei der Eingabe mit Vorschlägen.

## 2. Wann soll die Komponente eingesetzt werden? 
* Wenn ein Eingabefeld viele vordefinierte Werte aufweisen kann.
* Als Hilfe zur Vorschau bei Suchresultaten/-feldern.

## 3. Regeln
* Die Autocompletion hat immer ein Label.
* Optionale Eingaben werden mit dem Text «(optional)» hinter dem Label versehen. Bei kurzen Feldern kann der Text «(optional)» mit «(opt.)» abgekürzt werden.
* Für detaillierte Erklärungen kann neben dem Label ein Fragezeichen im Kreis dargestellt werden. Beim Klick auf dieses Fragezeichen öffnet sich ein [Tooltip](https://digital.sbb.ch/de/components/tooltip).
* Während der Eingabe werden direkt Vorschläge eingeblendet (typischerweise nach drei Zeichen, kann aber projektspezifisch angepasst werden).
* Die aufgelisteten Einträge können mittels Pfeiltasten durchlaufen und mit Enter übernommen werden.
* Es werden maximal 10 Vorschläge angezeigt.
* Bei der Auswahl eines Elementes schliesst sich die Autocompletion-Auswahl.

## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Default
* Hover

### 4.1 Standard
![Darstellung der Komponente Autocompletion in der Ausprägung Standard](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/autocompletion/images/autocompletion_default.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/327147336/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/15744722/327147337/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/autocomplete)

### 4.2 Mit Trefferanzeige
Optional zur Standard-Ausprägung kann diese Variante eingesetzt werden, wenn eine Autocompletion-Liste immer mehr als die maximal angezeigten 10 Treffer beinhaltet.
![Darstellung der Komponente Autocompletion mit der Anzeige von weiteren Treffern](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/autocompletion/images/autocompletion_overflow.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/383235117/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/15744722/383235118/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/autocomplete)

### 4.3 Mit statischen Einträgen
![Darstellung der Komponente Autocompletion mit statischen Einträgen](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/autocompletion/images/autocompletion_static.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/327147338/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/15744722/327147339/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/autocomplete)