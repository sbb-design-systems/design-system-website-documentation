## 1. Was macht die Komponente?
Löst eine Aktion auf einer Seite aus.

## 2. Wann soll die Komponente eingesetzt werden? 
* Beim Starten oder Beenden eines Prozesses.
* Beim Absenden eines Formulars.
* Beim Aufrufen einer Funktion auf einer Seite.

## 3. Regeln
* Darf nicht innerhalb von Fliesstext eingesetzt werden.
* Darf nicht im [Header](https://digital.sbb.ch/de/websites/modules/header) als Navigation oder Funktion eingesetzt werden.
* Die Mindestbreite beträgt 60px, die Maximalbreite 400px.
* Die Breite wächst mit der Textlänge. Beim Einsatz im [Next Best Click (NBC)](https://digital.sbb.ch/de/websites/components/nbc) oder in mobilen Ansichten ist die Breite 100%.
* Ist der Text beim Erreichen der Maximallänge immer noch zu lang, wird dieser mit «\...» abgekürzt.
* Der Text ist immer einzeilig.
* In Ausnahmefällen darf das Pfeil-Icon durch ein anderes, passendes Icon ersetzt werden.
* Pro Seite darf nur ein Primary Button eingesetzt werden.
* Secondary, Ghost und Frameless Buttons dürfen nur eingesetzt werden, wenn bereits ein Primary Button vorhanden ist.

## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Default
* Hover
* On-click
* Disabled

### 4.1 Primary Button
![Darstellung der Komponente Primary Button](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/button/images/button_primary.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/326883321/inspect) 
* [Hover](https://sbb.invisionapp.com/d/main#/console/15744722/326883322/inspect) 
* [On-Click](https://sbb.invisionapp.com/d/main#/console/15744722/326883323/inspect) 
* [Disabled](https://sbb.invisionapp.com/d/main#/console/15744722/326883324/inspect) 

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/public/components/button)

### 4.2 Secondary Button
![Darstellung der Komponente Secondary Button](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/button/images/button_secondary.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/326896021/inspect) 
* [Hover](https://sbb.invisionapp.com/d/main#/console/15744722/326896022/inspect) 
* [On-Click](https://sbb.invisionapp.com/d/main#/console/15744722/326896023/inspect) 
* [Disabled](https://sbb.invisionapp.com/d/main#/console/15744722/326896024/inspect) 

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/public/components/button)

### 4.3 Ghost Button
![Darstellung der Komponente Ghost Button](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/button/images/button_ghost.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/326896025/inspect) 
* [Hover](https://sbb.invisionapp.com/d/main#/console/15744722/326896026/inspect) 
* [On-Click](https://sbb.invisionapp.com/d/main#/console/15744722/326896027/inspect) 

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/public/components/button)

### 4.4 Frameless Button
![Darstellung der Komponente Frameless Button](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/button/images/button_frameless.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/326896028/inspect) 
* [Hover](https://sbb.invisionapp.com/d/main#/console/15744722/326896029/inspect) 
* [On-Click](https://sbb.invisionapp.com/d/main#/console/15744722/326896030/inspect) 

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/public/components/button)