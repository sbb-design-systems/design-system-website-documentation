## 1. Was macht die Komponente?
* Stellt Werte und Kategorien als kompakte Elemente dar.


## 2. Wann soll die Komponente eingesetzt werden?
* Wenn es in einem Formular möglich sein soll, zu einem Attribut mehrere Werte zu setzen.
* Wenn nach Kategorien gefiltert werden soll.


## 3. Regeln
* Ein Filter-Chip hat immer einen Indikator, welcher angibt wie viele Ergebnisse dahinterstecken.
* Der Begriff im Chip ist immer einzeilig (keine Zeilenumbrüche) und der Chip selber wächst in der Breite mit dem Text mit.
* Wird ein Chip aufgrund des Textes zu lang für den Viewport, wird der Text mit «...» gekürzt.
* Die Input-Chips werden in einem [Textfield](https://digital.sbb.ch/de/webapps/components/textfield) dargestellt. Dieses kann je nach Anzahl Chips auch mehrzeilig werden.


## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Active

### 4.1 Input
Diese Ausprägung hat zusätzlich folgende Zustände:
* Disabled
* Hover
* On-Click/Dragged

![Darstellung der Komponente Chip als Eingabewert](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/chip/images/chip_input.png 'class: image')

* Je nach Anwendungsfall können die Chips über "autocomplete"-Auswahlen oder mit Freitext generiert werden.

#### Design Spezifikation
* [Active](https://sbb.invisionapp.com/d/main#/console/17140415/355318411/inspect)
* [Disabled](https://sbb.invisionapp.com/d/main#/console/17140415/355318412/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/17140415/355318413/inspect)
* [On-Click/Dragged](https://sbb.invisionapp.com/d/main#/console/17140415/355318414/inspect)

### 4.2 Filter
Diese Ausprägung hat zusätzlich folgende Zustände:
* Inactive

![Darstellung der Komponente Chip fürs Filtern](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/chip/images/chip_filter.png 'class: image')

* Mit Klick auf ein Tag toggelt der jeweilige Zustand in den anderen und beeinflusst so das Filterergebnis.

#### Design Spezifikation
* [Active](https://sbb.invisionapp.com/d/main#/console/17140415/355318415/inspect)
* [Inactive](https://sbb.invisionapp.com/d/main#/console/17140415/355318416/inspect)
