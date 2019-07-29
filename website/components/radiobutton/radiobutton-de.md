## 1. Was macht die Komponente?
* Dient zur Auswahl genau einer Option aus mehreren.

## 2. Wann soll die Komponente eingesetzt werden? 
* Bei zwei und mehr Auswahlmöglichkeiten, bei der sich die Optionen gegenseitig ausschliessen.

## 3. Regeln
* Ein Radiobutton ist nur innerhalb eines Formulars erlaubt.
* Es müssen mindestens zwei Optionen zur Auswahl stehen.
* Eine Vorauswahl ist Pflicht.
* Radiobuttons können vertikal oder horizontal angeordnet werden. Die vertikale Anordnung wird bevorzugt, dadurch kann der Benutzer die Auswahlmöglichkeiten schneller erfassen.
* Bei mobilen Ansichten ist eine horizontale Anordnung nicht erlaubt.
* Der Text kann mehrzeilig sein.
* Nebst dem eigentlichen Radiobutton dient auch der gesamte Text als Click-Target.
* Oberhalb einer Radiobutton-Gruppe kann ein Titel eingesetzt werden.
* Für detaillierte Erklärungen zu einer Radiobutton-Gruppe kann neben dem Titel ein Fragezeichen im Kreis dargestellt werden. Beim Klick auf dieses Fragezeichen öffnet sich ein [Tooltip](https://digital.sbb.ch/de/components/tooltip).

## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Checked
* Unchecked
* Focused checked
* Focused unchecked
* Disabled checked
* Disabled unchecked

### 4.1 Standard
![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/radiobutton/images/radiobutton_default.png 'class: image') 

#### Design Spezifikation
* [Checked](https://sbb.invisionapp.com/d/main#/console/15744722/327724157/inspect)
* [Unchecked](https://sbb.invisionapp.com/d/main#/console/15744722/327724158/inspect)
* [Focused checked](https://sbb.invisionapp.com/d/main#/console/15744722/327724159/inspect)
* [Focused unchecked](https://sbb.invisionapp.com/d/main#/console/15744722/327724160/inspect)
* [Disabled checked](https://sbb.invisionapp.com/d/main#/console/15744722/327724161/inspect)
* [Disabled unchecked](https://sbb.invisionapp.com/d/main#/console/15744722/327724162/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/radio-button)

### 4.2 Vertikale Radiobutton-Gruppe
![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/radiobutton/images/radiobutton_vertical.png 'class: image') 

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/327724163/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/radio-button)

### 4.3 Horizontale Radiobutton-Gruppe
![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/radiobutton/images/radiobutton_horizontal.png 'class: image') 

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/327724164/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/radio-button)