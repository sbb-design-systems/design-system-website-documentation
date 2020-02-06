## 1. Was macht die Komponente?
Dient zur Auswahl einer oder mehrerer Optionen aus einer vorgegebenen Liste.

## 2. Wann soll die Komponente eingesetzt werden? 
* Bei einer Auswahl aus mehreren Optionen (Einfach- oder Mehrfachauswahl) einer Liste.
* Wenn eine Auswahl getroffen werden muss, bei der sich die Einträge gegenseitig ausschliessen und kein Defaultwert gesetzt werden soll (anders als beim Element [Radiobutton](https://digital.sbb.ch/de/websites/components/radiobutton)).
* Wenn Auswahloptionen gruppiert werden sollen.

## 3. Regeln
* Es müssen mindestens zwei Optionen zur Auswahl stehen.
* Das Element hat immer ein Label.
* Optionale Auswahlen werden mit dem Text «(optional)» hinter dem Label versehen. Bei kurzen Feldern kann der Text «(optional)» mit «(opt.)» abgekürzt werden.
* Für detaillierte Erklärungen kann neben dem Label ein Fragezeichen im Kreis dargestellt werden. Beim Klick auf dieses Fragezeichen öffnet sich ein [Tooltip](https://digital.sbb.ch/de/websites/components/tooltip).
* Der Text im Select-Element ist immer einzeilig.
* Ist ein Eintrag länger als die verfügbare Breite des Elements, wird der Text des Eintrages mit «...» abgekürzt.
* Bei einem Pflichtfeld ist eine Vorauswahl nicht erlaubt.
* Wenn noch keine Auswahl getroffen wurde, lautet der Element-Text «Bitte wählen...».

## 4.  Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Default
* Focused
* Disabled
* Error
* Expanded

### 4.1 Standard
![Darstellung der Komponente Select in der Ausprägung Standard](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/select/images/select_default.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/327200956/inspect)
* [Focused](https://sbb.invisionapp.com/d/main#/console/15744722/327200957/inspect)
* [Disabled](https://sbb.invisionapp.com/d/main#/console/15744722/327200958/inspect)
* [Error](https://sbb.invisionapp.com/d/main#/console/15744722/327200959/inspect)
* [Expanded](https://sbb.invisionapp.com/d/main#/console/15744722/327200960/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/public/components/select)

### 4.2 Mehrfachauswahl 
![Darstellung der Komponente Select mit Mehrfachauswahl](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/select/images/select_multi.png 'class: image')

#### Design Spezifikation
* [Collapsed](https://sbb.invisionapp.com/d/main#/console/15744722/327200961/inspect)
* [Expanded](https://sbb.invisionapp.com/d/main#/console/15744722/327200962/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/public/components/select)

### 4.3 Gruppierte Einfachauswahl
![Darstellung der Komponente Select mit gruppierten Einträgen](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/select/images/select_grouped_single.png 'class: image')

#### Design Spezifikation
* [Collapsed](https://sbb.invisionapp.com/d/main#/console/15744722/327200963/inspect)
* [Expanded](https://sbb.invisionapp.com/d/main#/console/15744722/327200964/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/public/components/select)

### 4.4 Gruppierte Mehrfachauswahl
![Darstellung der Komponente Select mit gruppierten Einträgen und Mehrfachauswahl](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/select/images/select_grouped_multi.png 'class: image')

#### Design Spezifikation
* [Collapsed](https://sbb.invisionapp.com/d/main#/console/15744722/327200965/inspect)
* [Expanded](https://sbb.invisionapp.com/d/main#/console/15744722/327200966/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/public/components/select)