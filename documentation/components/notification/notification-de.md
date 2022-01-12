## 1. Was macht die Komponente?
Dient zur Anzeige von Meldungen welche eine ganze Seite betreffen.

## 2. Wann soll die Komponente eingesetzt werden? 
Wenn ein Benutzer auf einer Seite eine Aktion ausgelöst hat und vom System ein Feedback erhalten soll.

## 3. Regeln
* Notifications erscheinen immer erst nach dem Auslösen einer Aktion durch den Benutzer.
* Die Breite entspricht immer dem Content-Bereich.
* Die Höhe richtet sich nach der Textlänge der Meldung.

## 4. Ausprägungen
### 4.1 Bestätigung
![Darstellung der Komponente Notification zur Darstellung von Bestätigungsmeldungen](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/notification/images/notification_confirmation.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/rvrL4A#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/notification?variant=standard)

### 4.2 Hinweis
![Darstellung der Komponente Notification zur Darstellung von Hinweismeldungen](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/notification/images/notification_information.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/ndDYMl#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/notification?variant=standard)

### 4.3 Fehler 
![Darstellung der Komponente Notification zur Darstellung von Fehlermeldungen](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/notification/images/notification_error.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/QJ1g7b#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/notification?variant=standard)

### 4.4 Fehler mit Sprungmarke 
![Darstellung der Komponente Notification zur Darstellung von Fehlermeldungen mit zusätzlichen Sprungmarken](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/notification/images/notification_link.png 'class: image')
* Die einzelnen Sprungmarken werden durch ein «/» getrennt.
* Beim Klick auf eine Sprungmarke wird direkt zum Ursprung des entsprechenden Fehlers gescrollt.
* Das Sprungmarkenziel ist immer auf derselben Seite wie die Notification (kein Absprung auf andere Seiten).

#### Design Spezifikation
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/xDQ8E0#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/notification?variant=standard)