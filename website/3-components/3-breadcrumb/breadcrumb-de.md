##1. Was macht das Modul?
* Dient zur Anzeige der Navigationshierarchie der aktuellen Seite.

##2. Wann soll das Modul eingesetzt werden? 
* Auf jeder Seite, bei denen der Benutzer schnell auf eine Schwester-oder Eltern-Seite navigieren können soll.

##3. Regeln
* Der Breadcrumb ist immer direkt unter dem (link: websites/modules/header text: Header) zu positionieren. Ausnahme wenn eine (link: websites/components/ghettobox text: Ghettobox) angezeigt wird, dann folgt der Breadcrumb unmittelbar nach der letzten Ghettobox.
* Der Breadcrumb kann bei langen Einträgen mehrzeilig werden.
* Bei Desktop und Tablet werden immer alle Ebenen angezeigt.
* Auf Mobile wird lediglich die letzte Ebenen ausgeschrieben. Vorangehende Ebenen werden durch eine einzige mit «...» dargestellt. Bei Klick auf «...» werden alle Zwischenebenen eingeblendet.
* Falls die horizontale Breite des Viewports auf Mobile nicht ausreicht um alle Ebenen anzuzeigen, wird der Breadcrumb-Content scollbar.

##4. Ausprägungen und Zustände 
Dieses Modul hat folgende Zustände:
* Default
* Hover

Beim Viewport ‹Mobile› gibt es folgende Zustände:
* Full
* Overflow

###4.1 Standard
(srcset: breadcrumb_default extension: png class: image)

####Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/328136674/inspect text: Default / Full)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/328136675/inspect text: Hover / Overflow)

####Code Spezifikation
In Bearbeitung.

###4.2 Mit Schwesterseiten
Diese Ausprägung hat zusätzlich folgende Zustände:
* Expanded

(srcset: breadcrumb_sibling extension: png class: image)
* Klick auf Bezeichner oder Pfeil öffnet das Dropdown.
* Im Dropdown sind alle Schwesterseiten aufgelistet.
* Ein Klick ausserhalb des Dropdowns schliesst dieses wieder.
* Die aktive Seite wird im Dropdown hervorgehoben.

####Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/328136676/inspect text: Default / Full)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/328136677/inspect text: Hover / Overflow)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/328136678/inspect text: Expanded)

####Code Spezifikation
In Bearbeitung.