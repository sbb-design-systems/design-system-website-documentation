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
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/5GoZ0w#Inspector) 
* [Hover](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/bVamYJ#Inspector) 
* [On-Click](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/WmnWay#Inspector) 
* [Disabled](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/34xdar#Inspector) 

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/public/components/button)

### 4.2 Secondary Button
![Darstellung der Komponente Secondary Button](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/button/images/button_secondary.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/rvrLW7#Inspector) 
* [Hover](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/ndDY9d#Inspector) 
* [On-Click](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/QJ1g4L#Inspector) 
* [Disabled](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/xDQ8xJ#Inspector) 

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/public/components/button)

### 4.3 Ghost Button
![Darstellung der Komponente Ghost Button](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/button/images/button_ghost.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/EwG1ad#Inspector) 
* [Hover](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/j9rRYm#Inspector) 
* [On-Click](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/dKja5L#Inspector) 

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/public/components/button)

### 4.4 Frameless Button
![Darstellung der Komponente Frameless Button](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/button/images/button_frameless.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/zAKMWM#Inspector) 
* [Hover](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/ZAnzl3#Inspector) 
* [On-Click](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/J9Jwok#Inspector) 

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/public/components/button)