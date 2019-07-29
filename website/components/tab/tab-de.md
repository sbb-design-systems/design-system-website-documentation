## 1. Was macht die Komponente?
* Dient zur Strukturierung der Anzeige von Daten und Formularen.

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
![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/tab/images/tab_default.png 'class: image') 

#### Design Spezifikation
* [Active](https://sbb.invisionapp.com/d/main#/console/15744722/332819501/inspect)
* [Inactive](https://sbb.invisionapp.com/d/main#/console/15744722/332819502/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/15744722/332819503/inspect)
* [Focused](https://sbb.invisionapp.com/d/main#/console/15744722/332819504/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/tabs)

### 4.2 Mit Mengenindikatoren 
![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/tab/images/tab_indicator.png 'class: image') 
* Der Mengenindikator liefert einen Hinweis, wie viele Einträge eine Liste im Content des Registers aufweist.
* Der Mengenindikator beinhaltet nur Zahlen, maximal 3-stellig.

#### Design Spezifikation
* [Active](https://sbb.invisionapp.com/d/main#/console/15744722/332819505/inspect)
* [Inactive](https://sbb.invisionapp.com/d/main#/console/15744722/332819506/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/15744722/332819507/inspect)
* [Focused](https://sbb.invisionapp.com/d/main#/console/15744722/332819508/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/tabs)