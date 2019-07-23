##1. Was macht das Element?
* Kategorisiert eine grosse Anzahl an Informationen.

##2. Wann soll das Element eingesetzt werden?
* Beim Filtern von Ergebnissen mit vielen Kategorien.
* In einer Tagcloud als Linktag um Absprungspunkte auf eine neue Kategorienseite zu verwenden.

##3. Regeln
* Ein Tag hat immer einen Indikator, welcher angibt wie viele Ergebnisse dahinterstecken.
* Die Ausrichtung der Tags ist bei Content-Seiten immer links, bei Übersichtsseiten immer zentriert.
* Die Reihenfolge der Tags werden redaktionell bestimmt.
* Der Begriff im Tag ist immer einzeilig (keine Zeilenumbrüche) und das Tag selber wächst in der Breite mit dem Text mit.
* Wird ein Tag aufgrund des Textes zu lang für den Viewport, wird der Text mit «...» gekürzt.

##4. Ausprägungen und Zustände 
Das Element hat folgende Zustände:
* Active
* Inactive

###4.1 Filtertag
(srcset: tag_filtertag extension: png class: image)
* Im Filter sind die Tags im aktiven und inaktiven Zustand vorhanden.
* Mit Klick auf ein Tag toggelt der jeweilige Zustand in den anderen und beeinflusst so das Filterergebnis.
* Innerhalb des Filter wird immer zusätzlich ein Tag «Alle» eingefügt. Wird dieses Filtertag angeklickt, wechselt es in den Zustand aktiv und alle anderen Tags im Filter werden in den Zustand inaktiv gesetzt.

Beispiel:
(srcset: tag_filtertag_example extension: png class: image)

####Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327768741/inspect text: Active)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327768742/inspect text: Inactive)

####Code Spezifikation
* (link: https://sbb-angular.app.sbb.ch/develop/content/tag text: SBB Angular Component Library)

###4.2 Linktag
(srcset: tag_linktag extension: png class: image)
* Linktags sind nur im aktiven Zustand vorhanden.
* Mit einem Klick auf das Tag gelangt der Benutzer auf die entsprechende Kategorienseite.

Beispiel:
(srcset: tag_linktag_example extension: png class: image)

####Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327768743/inspect text: Active)

####Code Spezifikation
* (link: https://sbb-angular.app.sbb.ch/develop/content/tag text: SBB Angular Component Library)