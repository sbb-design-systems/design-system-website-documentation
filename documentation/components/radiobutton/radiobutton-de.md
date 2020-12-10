## 1. Was macht die Komponente?
Dient zur Auswahl genau einer Option aus mehreren.

## 2. Wann soll die Komponente eingesetzt werden? 
Bei zwei und mehr Auswahlmöglichkeiten, bei der sich die Optionen gegenseitig ausschliessen.

## 3. Regeln
* Ein Radiobutton ist nur innerhalb eines Formulars erlaubt.
* Es müssen mindestens zwei Optionen zur Auswahl stehen.
* Eine Vorauswahl ist Pflicht.
* Radiobuttons können vertikal oder horizontal angeordnet werden. Die vertikale Anordnung wird bevorzugt, dadurch kann der Benutzer die Auswahlmöglichkeiten schneller erfassen.
* Bei mobilen Ansichten ist eine horizontale Anordnung nicht erlaubt.
* Der Text kann mehrzeilig sein.
* Nebst dem eigentlichen Radiobutton dient auch der gesamte Text als Click-Target.
* Oberhalb einer Radiobutton-Gruppe kann ein Titel eingesetzt werden.
* Für detaillierte Erklärungen zu einer Radiobutton-Gruppe kann neben dem Titel ein Fragezeichen im Kreis dargestellt werden. Beim Klick auf dieses Fragezeichen öffnet sich ein [Tooltip](https://digital.sbb.ch/de/websites/components/tooltip).

## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Checked
* Unchecked
* Focused checked
* Focused unchecked
* Disabled checked
* Disabled unchecked

### 4.1 Standard
![Darstellung der Komponente Radiobutton in der Ausprägung Standard](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/radiobutton/images/radiobutton_default.png 'class: image')

#### Design Spezifikation
* [Checked](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/4e5zrx#Inspector)
* [Unchecked](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/ewdAyz#Inspector)
* [Focused checked](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/GLdVrY#Inspector)
* [Focused unchecked](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/OzREq8#Inspector)
* [Disabled checked](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/mjKVyz#Inspector)
* [Disabled unchecked](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/DKwRrq#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/public/components/radio-button)

### 4.2 Vertikale Radiobutton-Gruppe
![Darstellung der Komponente Radiobutton als vertikale Gruppe](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/radiobutton/images/radiobutton_vertical.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/j9rRy0#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/public/components/radio-button)

### 4.3 Horizontale Radiobutton-Gruppe
![Darstellung der Komponente Radiobutton als horizontale Gruppe](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/radiobutton/images/radiobutton_horizontal.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/dKjaEZ#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/public/components/radio-button)