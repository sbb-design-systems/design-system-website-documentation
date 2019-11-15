## 1. Was macht die Komponente?
* Dient zur Auswahl einer oder mehrerer Optionen aus einer vorgegebenen Liste.


## 2. Wann soll die Komponente eingesetzt werden?
* Bei einer Auswahl aus mehreren Optionen (Einfach- oder Mehrfachauswahl) einer Liste.
* Wenn eine Auswahl getroffen werden muss, bei der sich die Einträge gegenseitig ausschliessen und kein Defaultwert gesetzt werden soll (anders als beim Element [Radiobutton](https://digital.sbb.ch/de/webapps/components/radiobutton).
* Wenn Auswahloptionen gruppiert werden sollen.


## 3. Regeln
* Es müssen mindestens zwei Optionen zur Auswahl stehen.
* Das Element hat immer ein Label.
* Für detaillierte Erklärungen kann neben dem Label ein Fragezeichen im Kreis dargestellt werden. Beim Klick auf dieses Fragezeichen öffnet sich ein [Tooltip](https://digital.sbb.ch/de/webapps/components/tooltip).
* Der Text im Select-Element ist immer einzeilig.
* Ist ein Eintrag länger als die verfügbare Breite des Elements, wird der Text des Eintrages mit «...» abgekürzt.
* Bei einem Pflichtfeld ist eine Vorauswahl nicht erlaubt.
* Wenn noch keine Auswahl getroffen wurde, lautet der Element-Text «Bitte wählen...».


## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
- Default
- Focused
- Disabled
- Error
- Expanded

### 4.1 Standard
![Darstellung der Komponente Select in der Standard Ausprägung](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/select/images/select_default.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/17140415/355347615/inspect)
* [Focused](https://sbb.invisionapp.com/d/main#/console/17140415/355347616/inspect)
* [Disabled](https://sbb.invisionapp.com/d/main#/console/17140415/355347617/inspect)
* [Error](https://sbb.invisionapp.com/d/main#/console/17140415/355347618/inspect)
* [Expanded](https://sbb.invisionapp.com/d/main#/console/17140415/355347619/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/17140415/355347620/inspect)
* [Active](https://sbb.invisionapp.com/d/main#/console/17140415/355347621/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/business/components/select)

### 4.2 Mehrfachauswahl 
![Darstellung de rKomponente Select mit Mehrfachauswahl](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/select/images/select_multi.png 'class: image')

#### Design Spezifikation
* [Collapsed](https://sbb.invisionapp.com/d/main#/console/17140415/355347622/inspect)
* [Expanded](https://sbb.invisionapp.com/d/main#/console/17140415/355347623/inspect)
* [Expanded Autocomplete](https://sbb.invisionapp.com/d/main#/console/17140415/371074705/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/business/components/select)

### 4.3 Gruppierte Einfachauswahl
![Darstellung der Komponente Select mit gruppierten Einträgen](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/select/images/select_grouped_single.png 'class: image')

#### Design Spezifikation
* [Expanded](https://sbb.invisionapp.com/d/main#/console/17140415/355347624/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/business/components/select)

### 4.4 Gruppierte Mehrfachauswahl
![Darstellung der Komponente Select mit gruppierten Einträgen und Mehrfachauswahl](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/select/images/select_grouped_multi.png 'class: image')

#### Design Spezifikation
* [Expanded](https://sbb.invisionapp.com/d/main#/console/17140415/355347625/inspect)
* [Expanded Tree Checkbox](https://sbb.invisionapp.com/d/main#/console/17140415/371074670/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/business/components/select)
