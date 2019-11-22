## 1. Was macht die Komponente?
* Bietet kontextspezifische Aktionen an, entweder dynamisch per Maus-Rechtsklick auf ein Element oder statisch über ein Icon.


## 2. Wann soll die Komponente eingesetzt werden?
* Wenn auf einem Objekt je nach Zustand oder Rolle des Benutzers Aktionen zur effizienten Ausführung angeboten werden sollen.


## 3. Regeln
* Ein Contextmenu kann über die rechte Maustaste oder ein Icon angeboten werden.
* Das Contextmenu kann Icons enthalten, muss aber nicht.
* Auf einer Ebene des Contextmenu gibt es entweder bei allen Menuitems ein Icon oder bei keinem. 
* Menuitems können gruppiert werden. Gruppen werden durch einen Strich getrennt.
* Ein Contextmenu kann zur Sortierung von Elementen genutzt werden. In diesem Fall wird mittels Pfeil gezeigt, nach welchem Attribut in welche Richtung sortiert ist.
* Es ist erlaubt, auch tiefere Ebenenstrukturen anzubieten. Es sollte aber darauf geachtet werden, dass je mehr Verschachtelung, desto ineffizienter die Bedienung.


## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Default
* Hover

### 4.1 Standard
Diese Ausprägung hat zusätzlich folgende Zustände:
* Expanded (optional)

![Darstellung der Komponente Kontextmenü zum Öffnen mittels rechter Maustaste](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/contextmenu/images/contextmenu_default.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/17140415/355318417/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/17140415/355318418/inspect)
* [Expanded](https://sbb.invisionapp.com/d/main#/console/17140415/355318419/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/business/components/contextmenu)

### 4.2 Icon
Diese Ausprägung hat zusätzlich folgende Zustände:
* Default
* Hover
* Expanded Hover
* Expanded Active

![Darstellung der Komponente Kontextmenü zum Öffnen mittels Icon](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/contextmenu/images/contextmenu_icon.png 'class: image')

* Als Icon werden standardmässig die drei Punkte verwendet. 

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/17140415/355318420/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/17140415/355318421/inspect)
* [Expanded Hover](https://sbb.invisionapp.com/d/main#/console/17140415/355318422/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/business/components/contextmenu)

### 4.3 Sorting
Diese Ausprägung hat zusätzlich folgende Zustände:
* Expanded Hover
* Expanded Active

![Darstellung der Komponente Kontextmenü zur Sortierung von Inhalten](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/contextmenu/images/contextmenu_sorting.png 'class: image')
* Zur Anzeige der Sortierung wird das Pfeil-Icon verwendet.
* Per Default wird absteigend (ascending) sortiert.
* Beim Hover auf aktiv sortiertes Attribut wird das Pfeil-Icon gedreht.
* Der ganze Menueintrag (Name und Icon) ist klickbar.

#### Design Spezifikation
* [Hover](https://sbb.invisionapp.com/d/main#/console/17140415/369105601/inspect)
* [Active](https://sbb.invisionapp.com/d/main#/console/17140415/355318423/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/business/components/contextmenu)
