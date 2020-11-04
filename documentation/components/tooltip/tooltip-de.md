## 1. Was macht die Komponente?
Erlaubt dem Benutzer bei Bedarf Erklärungen einzublenden.

## 2. Wann soll die Komponente eingesetzt werden? 
Bei kontextspezifischen Erklärungen zu Interaktionselementen oder Text.

## 3. Regeln
* Der Tooltip besteht aus dem Icon und dem Overlay. → In Ausnahmefällen darf auch ein anderes Icon für den Tooltip verwendet werden (z.B. ein Info-Icon).
* Das Overlay öffnet sich bei Klick auf das ???
* Im Overlay dürfen nur Freitext und [Links](https://digital.sbb.ch/de/websites/components/link) eingesetzt werden. Der Text darf auch als Liste dargestellt werden.
* Der Tooltip-Text darf maximal 300 Zeichen umfassen.
* Ein Link darf Inhalt in einer [Lightbox](https://digital.sbb.ch/de/websites/components/lightbox) oder auf einer neuen Seite (neuer Tab) öffnen; es darf nicht im aktuellen Browserfenster geladen werden.
* Das Overlay enthält ein ??? zum schliessen des Overlays.
* Das Overlay kann auch wieder ausgeblendet werden, indem irgendwo neben das Overlay geklickt wird.
* Der Spickel des Overlays, der zum Icon zeigt, kann horizontal irgendwo platziert werden (kommt auf die Position des Tooltips auf der Seite an).

## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Hidden
* Visible

### 4.1 Overlay oberhalb des Icons
![Darstellung der Komponente Tooltip mit obenliegender Textbox](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/tooltip/images/tooltip_above.png 'class: image')

#### Design Spezifikation
* [Hidden](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/WmnWOg#Inspector)
* [Visible](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/34xdgD#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/public/components/tooltip)

### 4.2 Overlay unterhalb des Icons
![Darstellung der Komponente Tooltip mit untenliegender Textbox](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/tooltip/images/tooltip_underneath.png 'class: image')

#### Design Spezifikation
* [Hidden](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/rvrLEx#Inspector)
* [Visible](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/ndDYOW#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/public/components/tooltip)