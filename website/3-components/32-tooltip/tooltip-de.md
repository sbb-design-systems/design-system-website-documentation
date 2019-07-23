##1. Was macht das Modul?
* Erlaubt dem Benutzer bei Bedarf Erklärungen einzublenden.

##2. Wann soll das Modul eingesetzt werden?
* Bei kontextspezifischen Erklärungen zu Interaktionselementen oder Text.

##3. Regeln
* Der Tooltip besteht aus dem Icon und dem Overlay. → In Ausnahmefällen darf auch ein anderes Icon für den Tooltip verwendet werden (z.B. ein Info-Icon).
* Das Overlay öffnet sich bei Klick auf das ???
* Im Overlay dürfen nur Freitext und (link: websites/components/link text: Links) eingesetzt werden. Der Text darf auch als Liste dargestellt werden.
* Der Tooltip-Text darf maximal 300 Zeichen umfassen.
* Ein Link darf Inhalt in einer (link: websites/components/lightbox text: Lightbox) oder auf einer neuen Seite (neuer Tab) öffnen; es darf nicht im aktuellen Browserfenster geladen werden.
* Das Overlay enthält ein ??? zum schliessen des Overlays.
* Das Overlay kann auch wieder ausgeblendet werden, indem irgendwo neben das Overlay geklickt wird.
* Der Spickel des Overlays, der zum Icon zeigt, kann horizontal irgendwo platziert werden (kommt auf die Position des Tooltips auf der Seite an).

##4. Ausprägungen und Zustände
Das Modul hat folgende Zustände:
* Hidden
* Visible

###4.1 Overlay oberhalb des Icons
(srcset: tooltip_above extension: png class: image)

####Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/328424439/inspect text: Hidden)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/328424440/inspect text: Visible)

####Code Spezifikation
* (link: https://sbb-angular.app.sbb.ch/latest/content/tooltip text: SBB Angular Component Library)

###4.2 Overlay unterhalb des Icons
(srcset: tooltip_underneath extension: png class: image)

####Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/328424441/inspect text: Hidden)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/328424442/inspect text: Visible)

####Code Spezifikation
* (link: https://sbb-angular.app.sbb.ch/latest/content/tooltip text: SBB Angular Component Library)