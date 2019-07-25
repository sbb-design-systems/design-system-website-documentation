## 1. Was macht das Element? 
* Dient zur Auswahl einer oder mehrerer Optionen aus einer vorgegebenen Liste.

## 2. Wann wird das Element eingesetzt?
* Bei einer Auswahl aus mehreren Optionen (Einfach- oder Mehrfachauswahl) einer Liste.
* Wenn eine Auswahl getroffen werden muss, bei der sich die Einträge gegenseitig ausschliessen und kein Defaultwert gesetzt werden soll (anders als beim Element (link: webapps/components/radiobutton text: Radiobutton).
* Wenn Auswahloptionen gruppiert werden sollen.

## 3. Regeln
* Es müssen mindestens zwei Optionen zur Auswahl stehen.
* Das Element hat immer ein Label.
* Für detaillierte Erklärungen kann neben dem Label ein Fragezeichen im Kreis dargestellt werden. Beim Klick auf dieses Fragezeichen öffnet sich ein (link: webapps/components/tooltip text: Tooltip).
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
(srcset: select_default extension: png class: image)

#### 4.1.1 Vermassung
* (link: https://sbb.invisionapp.com/d/main#/console/17140415/355347615/inspect text: Default)
* (link: https://sbb.invisionapp.com/d/main#/console/17140415/355347616/inspect text: Focused)
* (link: https://sbb.invisionapp.com/d/main#/console/17140415/355347617/inspect text: Disabled)
* (link: https://sbb.invisionapp.com/d/main#/console/17140415/355347618/inspect text: Error)
* (link: https://sbb.invisionapp.com/d/main#/console/17140415/355347619/inspect text: Expanded)
* (link: https://sbb.invisionapp.com/d/main#/console/17140415/355347620/inspect text: Hover)
* (link: https://sbb.invisionapp.com/d/main#/console/17140415/355347621/inspect text: Active)

### 4.2 Mehrfachauswahl 
(srcset: select_multi extension: png class: image)

#### 4.2.1 Vermassung
* (link: https://sbb.invisionapp.com/d/main#/console/17140415/355347622/inspect text: Collapsed)
* (link: https://sbb.invisionapp.com/d/main#/console/17140415/355347623/inspect text: Expanded)
* (link: https://sbb.invisionapp.com/d/main#/console/17140415/371074705/inspect text: Expanded Autocomplete)

### 4.3 Gruppierte Einfachauswahl
(srcset: select_grouped_single extension: png class: image)

#### 4.3.1 Vermassung
* (link: https://sbb.invisionapp.com/d/main#/console/17140415/355347624/inspect text: Expanded)

### 4.4 Gruppierte Mehrfachauswahl
(srcset: select_grouped_multi extension: png class: image)

#### 4.4.1 Vermassung
* (link: https://sbb.invisionapp.com/d/main#/console/17140415/355347625/inspect text: Expanded)
*  (link: https://sbb.invisionapp.com/d/main#/console/17140415/371074670/inspect text: Expanded Tree Checkbox)