## 1. Was macht die Komponente?
* Dient zur Eingabe von Ja/Nein-Werten.

## 2. Wann soll die Komponente eingesetzt werden? 
* Beim Auswählen einer Option.
* Beim Auswählen mehrerer zueinander unabhängigen Optionen.

## 3. Regeln 
* Eine Checkbox ist nur innerhalb von Formularen erlaubt.
* Eine Vorauswahl ist Pflicht (aktiv oder inaktiv, kein Tristate).
* Mehrere Checkboxen können vertikal oder horizontal angeordnet werden. Die vertikal Anordnung wird bevorzugt, dadurch kann der Benutzer die Auswahlmöglichkeiten schneller erfassen.
* Horizontal Anordnung nur bei zwei bis drei Auswahlmöglichkeiten und kurzen Bezeichnungen.
* Bei mobilen Ansichten ist eine horizontale Anordnung nicht erlaubt.
* Der Text kann mehrzeilig sein.
* Nebst der eigentlich Checkbox dient auch der gesamte Text als Click-Target.
* Oberhalb einer Checkbox-Gruppe kann ein Titel eingesetzt werden.
* Für detaillierte Erklärungen zu einer Checkbox-Gruppe kann neben dem Titel ein Fragezeichen im Kreis dargestellt werden. Beim Klick auf dieses Fragezeichen öffnet sich ein [Tooltip](https://digital.sbb.ch/de/components/tooltip).

## 4. Ausprägungen und Zustände 
Die Komponente hat folgende Zustände:
* Checked
* Unchecked
* Focused checked
* Focused unchecked
* Disabled checked
* Disabled unchecked

### 4.1 Standard
![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/checkbox/images/checkbox_default.png 'class: image')

#### Design Spezifikation
* [Checked](https://sbb.invisionapp.com/d/main#/console/15744722/327724165/inspect)
* [Unchecked](https://sbb.invisionapp.com/d/main#/console/15744722/327724166/inspect)
* [Focused checked](https://sbb.invisionapp.com/d/main#/console/15744722/327724167/inspect)
* [Focused unchecked](https://sbb.invisionapp.com/d/main#/console/15744722/327724168/inspect)
* [Disabled checked](https://sbb.invisionapp.com/d/main#/console/15744722/327724169/inspect)
* [Disabled unchecked](https://sbb.invisionapp.com/d/main#/console/15744722/327724170/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/checkbox)

### 4.2 Vertikale Checkbox-Gruppe 
![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/checkbox/images/checkbox_vertical.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/327724171/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/checkbox)

### 4.3 Horizontale Checkbox-Gruppe
![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/checkbox/images/checkbox_horizontal.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/327724172/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/checkbox)