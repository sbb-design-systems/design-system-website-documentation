## 1. Was macht die Komponente?
* Erlaubt dem Benutzer bei Bedarf Erklärungen einzublenden.


## 2. Wann soll die Komponente eingesetzt werden?
* Bei kontextspezifischen Erklärungen zu Interaktionselementen oder Text.


## 3. Regeln
* Der Tooltip besteht aus einem Icon und dem Overlay. Das Info-Icon ist Standard und kann bei Bedarf durch ein anderes Icon ersetzt werden.
* Das Overlay öffnet sich bei Klick auf das Icon.
* Alternativ kann der Tooltip auch mittels Hover angezeigt werden.
* Der Tooltip darf auch auf Texten oder Bildern platziert / zugänglich gemacht werden.
* Im Overlay dürfen nur Freitext und [Links](https://digital.sbb.ch/de/webapps/components/link) eingesetzt werden. Der Text darf auch als Liste dargestellt werden.
* Der Tooltip-Text darf maximal 300 Zeichen umfassen.
* Das Overlay enthält ein 'X'-Icon zum schliessen des Overlays.
* Das Overlay kann auch wieder ausgeblendet werden, indem irgendwo neben das Overlay geklickt wird.
* Der Spickel des Overlays, der zum Icon zeigt, kann horizontal irgendwo platziert werden (kommt auf die Position des Tooltips auf der Seite an).


## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Hidden
* Hover
* Visible

### 4.1 Overlay oberhalb des Icons
![Darstellung der Komponente Tooltip mit obenliegender Textbox](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/tooltip/images/tooltip_above.png 'class: image')

#### Design Spezifikation
* [Hidden](https://sbb.invisionapp.com/d/main#/console/17140415/355318612/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/17140415/355318613/inspect)
* [Visible](https://sbb.invisionapp.com/d/main#/console/17140415/355318614/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/business/components/tooltip)

### 4.2 Overlay unterhalb des Icons
![Darstellung der Komponente Tooltip mit untenliegender Textbox](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/tooltip/images/tooltip_underneath.png 'class: image')

#### Design Spezifikation
* [Hidden](https://sbb.invisionapp.com/d/main#/console/17140415/355318612/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/17140415/355318613/inspect)
* [Visible](https://sbb.invisionapp.com/d/main#/console/17140415/355318615/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/business/components/tooltip)
