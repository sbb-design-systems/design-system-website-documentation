## 1. Was macht die Komponente?
* Erlaubt dem Benutzer bei Bedarf Erklärungen einzublenden.

## 2. Wann soll das Modul eingesetzt werden?
* Bei kontextspezifischen Erklärungen zu Interaktionselementen oder Text.

## 3. Regeln
* Der Tooltip besteht aus einem Icon und dem Overlay. Das Info-Icon ist Standard und kann bei Bedarf durch ein anderes Icon ersetzt werden.
* Das Overlay öffnet sich bei Klick auf das Icon.
* Im Overlay dürfen nur Freitext und [Links](https://digital.sbb.ch/de/webapps/components/link) eingesetzt werden. Der Text darf auch als Liste dargestellt werden.
* Der Tooltip-Text darf maximal 300 Zeichen umfassen.
* Das Overlay enthält ein 'X'-Icon zum schliessen des Overlays.
* Das Overlay kann auch wieder ausgeblendet werden, indem irgendwo neben das Overlay geklickt wird.
* Der Spickel des Overlays, der zum Icon zeigt, kann horizontal irgendwo platziert werden (kommt auf die Position des Tooltips auf der Seite an).
* Der Tooltip darf auch auf Texten oder Bildern platziert / zugänglich gemacht werden.

## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Hidden
* Hover
* Visible

### 4.1 Overlay oberhalb des Icons
![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/tooltip/images/tooltip_above.png 'class: image')

#### 4.1.1 Vermassung
* [Hidden](https://sbb.invisionapp.com/d/main#/console/17140415/355318612/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/17140415/355318613/inspect)
* [Visible](https://sbb.invisionapp.com/d/main#/console/17140415/355318614/inspect)


### 4.2 Overlay unterhalb des Icons
![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/tooltip/images/tooltip_underneath.png 'class: image')

#### 4.2.1 Vermassung
* [Hidden](https://sbb.invisionapp.com/d/main#/console/17140415/355318612/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/17140415/355318613/inspect)
* [Visible](https://sbb.invisionapp.com/d/main#/console/17140415/355318615/inspect)


