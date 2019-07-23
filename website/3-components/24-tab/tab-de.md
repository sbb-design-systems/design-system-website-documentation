##1. Was macht das Modul?
* Dient zur Strukturierung der Anzeige von Daten und Formularen.

##2. Wann soll das Modul eingesetzt werden? 
* Wenn innerhalb des gleichen Kontexts zwischen verschiedenen Aspekten gewechselt werden soll.
* Wenn die Inhalte der verschiedenen Aspekte nicht gleichzeitig vom Benutzer angesehen werden.

##3. Regeln
* Es gibt mindestens zwei Register.
* Per Default ist immer das erste Register ausgewählt.
* Die Registerbezeichungen sind immer einzeilig.
* Die Registerbezeichung sollte möglichst kurz und prägnant sein, damit die Themen schnell erfasst werden können.
* Falls die Register für den Viewport zu lang sind, sind die weiteren Register mit einer horizontalen Scrollbar (Desktop) rsp. durch Swipen (Tablet / Mobile) erreichbar.
* Ein weiteres Tab-Modul innerhalb eines Registers ist nicht erlaubt.

##4. Ausprägungen und Zustände 
Das Modul hat folgende Zustände:
* Active
* Inactive
* Hover
* Focused

###4.1 Standard
(srcset: tab_default extension: png class: image)

####Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/332819501/inspect text: Active)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/332819502/inspect text: Inactive)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/332819503/inspect text: Hover)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/332819504/inspect text: Focused)

####Code Spezifikation
* (link: https://sbb-angular.app.sbb.ch/latest/content/tabs text: SBB Angular Component Library)

###4.2 Mit Mengenindikatoren 
(srcset: tab_indicator extension: png class: image)
* Der Mengenindikator liefert einen Hinweis, wie viele Einträge eine Liste im Content des Registers aufweist.
* Der Mengenindikator beinhaltet nur Zahlen, maximal 3-stellig.

####Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/332819505/inspect text: Active)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/332819506/inspect text: Inactive)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/332819507/inspect text: Hover)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/332819508/inspect text: Focused)

####Code Spezifikation
* (link: https://sbb-angular.app.sbb.ch/latest/content/tabs text: SBB Angular Component Library)