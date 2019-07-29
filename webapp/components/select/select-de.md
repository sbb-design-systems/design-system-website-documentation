## 1. Was macht das Element? 
* Dient zur Auswahl einer oder mehrerer Optionen aus einer vorgegebenen Liste.

## 2. Wann wird das Element eingesetzt?
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

## 4.  Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
- Default
- Focused
- Disabled
- Error
- Expanded

### 4.1 Standard
![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/select/images/select_default.png 'class: image')


#### 4.1.1 Vermassung
* [Default](https://sbb.invisionapp.com/d/main#/console/17140415/355347615/inspect)
* [Focused](https://sbb.invisionapp.com/d/main#/console/17140415/355347616/inspect)
* [Disabled](https://sbb.invisionapp.com/d/main#/console/17140415/355347617/inspect)
* [Error](https://sbb.invisionapp.com/d/main#/console/17140415/355347618/inspect)
* [Expanded](https://sbb.invisionapp.com/d/main#/console/17140415/355347619/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/17140415/355347620/inspect)
* [Active](https://sbb.invisionapp.com/d/main#/console/17140415/355347621/inspect)

### 4.2 Mehrfachauswahl 
![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/select/images/select_multi.png 'class: image')


#### 4.2.1 Vermassung
* [Collapsed](https://sbb.invisionapp.com/d/main#/console/17140415/355347622/inspect)
* [Expanded](https://sbb.invisionapp.com/d/main#/console/17140415/355347623/inspect)
* [Expanded Autocomplete](https://sbb.invisionapp.com/d/main#/console/17140415/371074705/inspect)

### 4.3 Gruppierte Einfachauswahl
![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/select/images/select_grouped_single.png 'class: image')


#### 4.3.1 Vermassung
* [Expanded](https://sbb.invisionapp.com/d/main#/console/17140415/355347624/inspect)


### 4.4 Gruppierte Mehrfachauswahl
![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/select/images/select_grouped_multi.png 'class: image')


#### 4.4.1 Vermassung
* [Expanded](https://sbb.invisionapp.com/d/main#/console/17140415/355347625/inspect)
* [Expanded Tree Checkbox](https://sbb.invisionapp.com/d/main#/console/17140415/371074670/inspect)