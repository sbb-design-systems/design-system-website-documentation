## 1. Was macht die Komponente?
* Dient zur Anzeige der Navigationshierarchie der aktuellen Seite.

## 2. Wann soll die Komponente eingesetzt werden? 
* Auf jeder Seite, bei denen der Benutzer schnell auf eine Schwester-oder Eltern-Seite navigieren können soll.

## 3. Regeln
* Der Breadcrumb ist immer direkt unter dem [Header](https://digital.sbb.ch/de/modules/header) zu positionieren. Ausnahme wenn eine [Ghettobox](https://digital.sbb.ch/de/components/ghettobox) angezeigt wird, dann folgt der Breadcrumb unmittelbar nach der letzten Ghettobox.
* Der Breadcrumb kann bei langen Einträgen mehrzeilig werden.
* Bei Desktop und Tablet werden immer alle Ebenen angezeigt.
* Auf Mobile wird lediglich die letzte Ebenen ausgeschrieben. Vorangehende Ebenen werden durch eine einzige mit «...» dargestellt. Bei Klick auf «...» werden alle Zwischenebenen eingeblendet.
* Falls die horizontale Breite des Viewports auf Mobile nicht ausreicht um alle Ebenen anzuzeigen, wird der Breadcrumb-Content scollbar.

## 4. Ausprägungen und Zustände 
Die Komponente hat folgende Zustände:
* Default
* Hover

Beim Viewport «Mobile» gibt es folgende Zustände:
* Full
* Overflow

### 4.1 Standard
![Darstellung der Komponente Breadcrumb in der Ausprägung Standard](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/breadcrumb/images/breadcrumb_default.png 'class: image')

#### Design Spezifikation
* [Default / Full](https://sbb.invisionapp.com/d/main#/console/15744722/328136674/inspect)
* [Hover / Overflow](https://sbb.invisionapp.com/d/main#/console/15744722/328136675/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/breadcrumb)

### 4.2 Mit Schwesterseiten
Diese Ausprägung hat zusätzlich folgende Zustände:
* Expanded

![Darstellung der Komponente Breadcrumb mit der Angabe der Schwesterseiten](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/breadcrumb/images/breadcrumb_sibling.png 'class: image')
* Klick auf Bezeichner oder Pfeil öffnet das Dropdown.
* Im Dropdown sind alle Schwesterseiten aufgelistet.
* Ein Klick ausserhalb des Dropdowns schliesst dieses wieder.
* Die aktive Seite wird im Dropdown hervorgehoben.

#### Design Spezifikation
* [Default / Full](https://sbb.invisionapp.com/d/main#/console/15744722/328136676/inspect)
* [Hover / Overflow](https://sbb.invisionapp.com/d/main#/console/15744722/328136677/inspect)
* [Expanded](https://sbb.invisionapp.com/d/main#/console/15744722/328136678/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/breadcrumb)