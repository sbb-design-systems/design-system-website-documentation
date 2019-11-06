## 1. Was macht die Komponente?
* Dient zur Anzeige von Meldungen welche eine ganze Seite betreffen.

## 2. Wann soll die Komponente eingesetzt werden? 
* Wenn ein Benutzer auf einer Seite eine Aktion ausgelöst hat und vom System ein Feedback erhalten soll.

## 3. Regeln
* Notifications erscheinen immer erst nach dem Auslösen einer Aktion durch den Benutzer.
* Die Breite entspricht immer dem Content-Bereich.
* Die Höhe richtet sich nach der Textlänge der Meldung.

## 4. Ausprägungen
### 4.1 Bestätigung
![Darstellung der Komponente Notification zur Darstellung von Bestätigungsmeldungen](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/notification/images/notification_confirmation.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/332849832/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/notification)

### 4.2 Hinweis
![Darstellung der Komponente Notification zur Darstellung von Hinweismeldungen](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/notification/images/notification_information.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/332849833/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/notification)

### 4.3 Fehler 
![Darstellung der Komponente Notification zur Darstellung von Fehlermeldungen](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/notification/images/notification_error.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/332849834/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/notification)

### 4.4 Fehler mit Sprungmarke 
![Darstellung der Komponente Notification zur Darstellung von Fehlermeldungen mit zusätzlichen Sprungmarken](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/notification/images/notification_link.png 'class: image')
* Die einzelnen Sprungmarken werden durch ein «/» getrennt.
* Beim Klick auf eine Sprungmarke wird direkt zum Ursprung des entsprechenden Fehlers gescrollt.
* Das Sprungmarkenziel ist immer auf derselben Seite wie die Notification (kein Absprung auf andere Seiten).

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/332849835/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/notification)