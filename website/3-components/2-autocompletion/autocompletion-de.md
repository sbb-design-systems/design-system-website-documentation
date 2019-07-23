##1. Was macht das Element? 
* Unterstützt den Benutzer bei der Eingabe mit Vorschlägen.

##2. Wann soll das Element eingesetzt werden? 
* Wenn ein Eingabefeld viele vordefinierte Werte aufweisen kann.
* Als Hilfe zur Vorschau bei Suchresultaten/-feldern.

##3. Regeln
* Die Autocompletion hat immer ein Label.
* Optionale Eingaben werden mit dem Text «(optional)» hinter dem Label versehen. Bei kurzen Feldern kann der Text «(optional)» mit «(opt.)» abgekürzt werden.
* Für detaillierte Erklärungen kann neben dem Label ein Fragezeichen im Kreis dargestellt werden. Beim Klick auf dieses Fragezeichen öffnet sich ein (link: websites/components/tooltip text: Tooltip).
* Während der Eingabe werden direkt Vorschläge eingeblendet (typischerweise nach drei Zeichen, kann aber projektspezifisch angepasst werden).
* Die aufgelisteten Einträge können mittels Pfeiltasten durchlaufen und mit Enter übernommen werden.
* Es werden maximal 10 Vorschläge angezeigt.
* Bei der Auswahl eines Elementes schliesst sich die Autocompletion-Auswahl.

##4. Ausprägungen und Zustände
Das Element hat folgende Zustände:
* Default
* Hover

###4.1 Standard
(srcset: autocompletion_default extension: png class: image)

####Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327147336/inspect text: Default)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327147337/inspect text: Hover)

####Code Spezifikation
*   (link: https://sbb-angular.app.sbb.ch/develop/content/autocomplete text: SBB Angular Component Library)

###4.2 Mit statischen Einträgen
(srcset: autocompletion_static extension: png class: image)

####Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327147338/inspect text: Default)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327147339/inspect text: Hover)

####Code Spezifikation
*   (link: https://sbb-angular.app.sbb.ch/latest/content/autocomplete text: SBB Angular Component Library)