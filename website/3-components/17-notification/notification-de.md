##1. Was macht das Modul?
* Dient zur Anzeige von Meldungen welche eine ganze Seite betreffen.

##2. Wann soll das Modul eingesetzt werden?
* Wenn ein Benutzer auf einer Seite eine Aktion ausgelöst hat und vom System ein Feedback erhalten soll.

##3. Regeln
* Notifications erscheinen immer erst nach dem Auslösen einer Aktion durch den Benutzer.
* Die Breite entspricht immer dem Content-Bereich.
* Die Höhe richtet sich nach der Textlänge der Meldung.

##4. Ausprägungen
###4.1 Bestätigung
(srcset: notification_confirmation extension: png class: image)

####Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/332849832/inspect  text: Default)

####Code Spezifikation
* (link: https://sbb-angular.app.sbb.ch/latest/content/notification text: SBB Angular Component Library)

###4.2 Hinweis
(srcset: notification_information extension: png class: image)

####Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/332849833/inspect text: Default)

####Code Spezifikation
* (link: https://sbb-angular.app.sbb.ch/latest/content/notification text: SBB Angular Component Library)

###4.3 Fehler 
(srcset: notification_error extension: png class: image)

####Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/332849834/inspect text: Default)

####Code Spezifikation
* (link: https://sbb-angular.app.sbb.ch/latest/content/notification text: SBB Angular Component Library)

###4.4 Fehler mit Sprungmarke 
(srcset: notification_link extension: png class: image)
* Die einzelnen Sprungmarken werden durch ein «/» getrennt.
* Beim Klick auf eine Sprungmarke wird direkt zum Ursprung des entsprechenden Fehlers gescrollt.
* Das Sprungmarkenziel ist immer auf derselben Seite wie die Notification (kein Absprung auf andere Seiten).

####Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/332849835/inspect text: Default)

####Code Spezifikation
* (link: https://sbb-angular.app.sbb.ch/latest/content/notification text: SBB Angular Component Library)