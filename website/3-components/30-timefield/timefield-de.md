##1. Was macht das Element?
* Dient zur Eingabe einer Uhrzeit.

##2. Wann soll das Element eingesetzt werden?
* Immer wenn vom Benutzer eine Uhrzeit verlangt wird.

##3. Regeln 
* Standardmässig ist die aktuelle Uhrzeit vorausgefüllt, ausser es macht im Kontext des Einsatzes keinen Sinn.
* Die Zeiteingabe kann ohne Eingabe des Doppelpunktes geschehen. Eingaben wie 130, 1.30 oder 1,30 werden nach verlassen des Feldes korrekt in 01:30 umformatiert.
* Bei Touch-Geräten erscheint die Zahlen-Eingabetastatur des entsprechenden Systems.

##4. Ausprägungen und Zustände 
Das Element hat folgende Zustände:
* Default
* Hinted
* Focused
* Disabled

###4.1 Standard
(srcset: timefield_default extension: png class: image)

####Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327611017/inspect text: Default)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/335006454/inspect text: Hinted)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327611018/inspect text: Focused)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327611019/inspect text: Disabled)

####Code Spezifikation
* (link: https://sbb-angular.app.sbb.ch/develop/content/time-input text: SBB Angular Component Library)