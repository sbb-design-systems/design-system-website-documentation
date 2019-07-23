##1. Was macht das Element?
* Dient zur Eingabe von Texten und Zahlen.

##2. Wann soll das Element eingesetzt werden?
* Wenn vom Benutzer eine Eingabe benötigt. wird.

##3. Regeln 
* Ein Eingabefeld hat immer ein Label.
* Optionale Eingaben werden mit dem Text «(optional)» hinter dem Label-Text versehen. Bei kurzen Feldern darf der Text «(optional)» mit «(opt.)» abgekürzt werden.
* Für detaillierte Erklärungen kann neben dem Label ein Fragezeichen im Kreis dargestellt werden. Beim Klick auf dieses Fragezeichen öffnet sich ein (link: websites/components/tooltip text: Tooltip).
* Der Eingabetext ist immer einzeilig.
* Wird der Text während der Eingabe länger als die Breite des Eingabefeldes wird der geschriebene Text nach links verdrängt, damit das aktuell Geschriebene immer gesehen wird.
* Nach dem Verlassen des Eingabefeldes mit einem langen Text wird dieser am Ende abgeschnitten und mit «\...» gekennzeichnet.
* Ein Eingabefeld kann einen Hinweistext (Placeholder) enthalten, welcher direkt im Eingabefeld angezeigt wird, solange vom Benutzer kein Wert eingetragen wurde.
* Ein Eingabefeld kann drei unterschiedliche Breiten haben:
    * Kurz → 1/6 der verfügbaren Breite des Containers/Parent-Elements (1/4 bei Tablet Portrait, 1/3 bei Mobile Portrait).
    * Mittel → 1/2 der verfügbaren Breite des Containers/Parent-Elements (ganze Breite bei Mobile Portrait).
    * Lang → ganze verfügbare Breite des Containers/Parent-Elements.
* Kann der Benutzer ein Formularfeld nie bearbeiten, so darf kein Eingabefeld verwendet werden (Darstellung als Text).

##4. Ausprägungen und Zustände 
Das Element hat folgende Zustände:
* Default
* Hinted
* Focused
* Disabled
* Error

###4.1 Standard
(srcset: textfield_default extension: png class: image)

####Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327021294/inspect text: Default)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327021295/inspect text: Hinted)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327021296/inspect text: Focused)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327021297/inspect text: Disabled)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327021298/inspect text: Error)

####Code Spezifikation
* (link: https://sbb-angular.app.sbb.ch/develop/content/field text: SBB Angular Component Library)

###4.2 Passworteingabe
(srcset: textfield_password extension: png class: image)
* Das Eingabefeld in der Ausprägung "Passwort" stellt keinen Zustand "Hinted" zur Verfügung.

####Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327021299/inspect text: Default)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327021300/inspect text: Focused)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327021301/inspect text: Disabled)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327021302/inspect text: Error)

####Code Spezifikation
* (link: https://sbb-angular.app.sbb.ch/develop/content/field text: SBB Angular Component Library)