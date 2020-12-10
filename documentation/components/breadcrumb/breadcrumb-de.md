## 1. Was macht die Komponente?
Dient zur Anzeige der Navigationshierarchie der aktuellen Seite.

## 2. Wann soll die Komponente eingesetzt werden? 
Auf jeder Seite, bei denen der Benutzer schnell auf eine Schwester-oder Eltern-Seite navigieren können soll.

## 3. Regeln
* Der Breadcrumb ist immer direkt unter dem [Header](https://digital.sbb.ch/de/websites/modules/header) zu positionieren. Ausnahme wenn eine [Ghettobox](https://digital.sbb.ch/de/websites/components/ghettobox) angezeigt wird, dann folgt der Breadcrumb unmittelbar nach der letzten Ghettobox.
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
![Darstellung der Komponente Breadcrumb in der Ausprägung Standard](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/breadcrumb/images/breadcrumb_default.png 'class: image')

#### Design Spezifikation
* [Default/Full](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/PZoPvQ#Inspector)
* [Hover/Overflow](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/gLZlYz#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/public/components/breadcrumb)

### 4.2 Mit Schwesterseiten
Diese Ausprägung hat zusätzlich folgende Zustände:
* Expanded

![Darstellung der Komponente Breadcrumb mit der Angabe der Schwesterseiten](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/breadcrumb/images/breadcrumb_sibling.png 'class: image')
* Klick auf Bezeichner oder Pfeil öffnet das Dropdown.
* Im Dropdown sind alle Schwesterseiten aufgelistet.
* Ein Klick ausserhalb des Dropdowns schliesst dieses wieder.
* Die aktive Seite wird im Dropdown hervorgehoben.

#### Design Spezifikation
* [Default / Full](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/8Dp4o7#Inspector)
* [Hover / Overflow](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/2vejDM#Inspector)
* [Expanded](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/MjM7zw#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/public/components/breadcrumb)