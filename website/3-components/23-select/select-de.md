##1. Was macht das Element? 
* Dient zur Auswahl einer oder mehrerer Optionen aus einer vorgegebenen Liste.

##2. Wann wird das Element eingesetzt?
* Bei einer Auswahl aus mehreren Optionen (Einfach- oder Mehrfachauswahl) einer Liste.
* Wenn eine Auswahl getroffen werden muss, bei der sich die Einträge gegenseitig ausschliessen und kein Defaultwert gesetzt werden soll (anders als beim Element (link: websites/components/radiobutton text: Radiobutton)).
* Wenn Auswahloptionen gruppiert werden sollen.

##3. Regeln
* Es müssen mindestens zwei Optionen zur Auswahl stehen.
* Das Element hat immer ein Label.
* Optionale Auswahlen werden mit dem Text «(optional)» hinter dem Label versehen. Bei kurzen Feldern kann der Text «(optional)» mit «(opt.)» abgekürzt werden.
* Für detaillierte Erklärungen kann neben dem Label ein Fragezeichen im Kreis dargestellt werden. Beim Klick auf dieses Fragezeichen öffnet sich ein (link: websites/components/tooltip text: Tooltip).
* Der Text im Select-Element ist immer einzeilig.
* Ist ein Eintrag länger als die verfügbare Breite des Elements, wird der Text des Eintrages mit «...» abgekürzt.
* Bei einem Pflichtfeld ist eine Vorauswahl nicht erlaubt.
* Wenn noch keine Auswahl getroffen wurde, lautet der Element-Text «Bitte wählen...».

##4.  Ausprägungen und Zustände
Das Element hat folgende Zustände:
- Default
- Focused
- Disabled
- Error
- Expanded

###4.1 Standard
(srcset: select_default extension: png class: image)

####Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327200956/inspect text: Default)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327200957/inspect text: Focused)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327200958/inspect text: Disabled)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327200959/inspect text: Error)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327200960/inspect text: Expanded)

####Code Spezifikation
* (link: https://sbb-angular.app.sbb.ch/latest/content/select text: SBB Angular Component Library )

###4.2 Mehrfachauswahl 
(srcset: select_multi extension: png class: image)

####Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327200961/inspect text: Collapsed)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327200962/inspect text: Expanded)

####Code Spezifikation
* (link: https://sbb-angular.app.sbb.ch/latest/content/select text: SBB Angular Component Library )

###4.3 Gruppierte Einfachauswahl
(srcset: select_grouped_single extension: png class: image)

####Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327200963/inspect text: Collapsed)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327200964/inspect text: Expanded)

####Code Spezifikation
* (link: https://sbb-angular.app.sbb.ch/latest/content/select text: SBB Angular Component Library )

###4.4 Gruppierte Mehrfachauswahl
(srcset: select_grouped_multi extension: png class: image)

####Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327200965/inspect text: Collapsed)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327200966/inspect text: Expanded)

####Code Spezifikation
* (link: https://sbb-angular.app.sbb.ch/latest/content/select text: SBB Angular Component Library )