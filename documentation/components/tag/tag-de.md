## 1. Was macht die Komponente?
Kategorisiert eine grosse Anzahl an Informationen.

## 2. Wann soll die Komponente eingesetzt werden? 
* Beim Filtern von Ergebnissen mit vielen Kategorien.
* In einer Tagcloud als Linktag um Absprungspunkte auf eine neue Kategorienseite zu verwenden.

## 3. Regeln
* Ein Tag hat immer einen Indikator, welcher angibt wie viele Ergebnisse dahinterstecken.
* Die Ausrichtung der Tags ist bei Content-Seiten immer links, bei Übersichtsseiten immer zentriert.
* Die Reihenfolge der Tags werden redaktionell bestimmt.
* Der Begriff im Tag ist immer einzeilig (keine Zeilenumbrüche) und das Tag selber wächst in der Breite mit dem Text mit.
* Wird ein Tag aufgrund des Textes zu lang für den Viewport, wird der Text mit «...» gekürzt.

## 4. Ausprägungen und Zustände 
Die Komponente hat folgende Zustände:
* Active (Default)
* Inactive
* Hover active
* Hover inactive

### 4.1 Filtertag
![Darstellung der Komponente Tag zur Verwendung als Filter](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/tag/images/tag_filtertag.png 'class: image')
* Im Filter sind die Tags im aktiven und inaktiven Zustand vorhanden.
* Mit Klick auf ein Tag toggelt der jeweilige Zustand in den anderen und beeinflusst so das Filterergebnis.
* Innerhalb des Filter wird immer zusätzlich ein Tag «Alle» eingefügt. Wird dieses Filtertag angeklickt, wechselt es in den Zustand aktiv und alle anderen Tags im Filter werden in den Zustand inaktiv gesetzt.

Beispiel:
![](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/tag/images/tag_filtertag_example.png 'class: image')

#### Design Spezifikation
* [Active](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/ZAnzQ7#Inspector)
* [Inactive](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/J9JwQ5#Inspector)
* [Hover active](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/vOQPZb#Inspector)
* [Hover inactive](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/4e5zZZ#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/tag?variant=standard)

### 4.2 Linktag
![Darstellung der Komponente Tag zur Verwendung als Link](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/tag/images/tag_linktag.png 'class: image')
* Linktags sind nur im aktiven Zustand vorhanden.
* Mit einem Klick auf das Tag gelangt der Benutzer auf die entsprechende Kategorienseite.

Beispiel:
![](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/tag/images/tag_linktag_example.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/ewdAGj#Inspector)
* [Hover](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/GLdVQ7#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/tag?variant=standard)