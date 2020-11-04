## 1. Was macht die Komponente?
Dient zur Eingabe von Ja/Nein-Werten.

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
* Für detaillierte Erklärungen zu einer Checkbox-Gruppe kann neben dem Titel ein Fragezeichen im Kreis dargestellt werden. Beim Klick auf dieses Fragezeichen öffnet sich ein [Tooltip](https://digital.sbb.ch/de/websites/components/tooltip).

## 4. Ausprägungen und Zustände 
Die Komponente hat folgende Zustände:
* Checked
* Unchecked
* Focused checked
* Focused unchecked
* Disabled checked
* Disabled unchecked

### 4.1 Standard
![Darstellung der Komponente Checkbox in der Ausprägung Standard](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/checkbox/images/checkbox_default.png 'class: image')

#### Design Spezifikation
* [Checked](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/ewdALP#Inspector)
* [Unchecked](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/GLdVeO#Inspector)
* [Focused checked](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/OzRElm#Inspector)
* [Focused unchecked](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/mjKVeP#Inspector)
* [Disabled checked](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/DKwRJ4#Inspector)
* [Disabled unchecked](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/j9rRJb#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/public/components/checkbox)

### 4.2 Vertikale Checkbox-Gruppe 
![Darstellung der Komponente Checkbox als vertikale Gruppe](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/checkbox/images/checkbox_vertical.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/dKja7j#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/public/components/checkbox)

### 4.3 Horizontale Checkbox-Gruppe
![Darstellung der Komponente Checkbox als horizontale Gruppe](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/checkbox/images/checkbox_horizontal.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/zAKM2l#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/public/components/checkbox)