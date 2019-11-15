## 1. Was macht die Komponente?
* Dient zur Anzeige von Meldungen, welche eine ganze Seite oder ein Modul einer Anwendung betreffen.


## 2. Wann soll die Komponente eingesetzt werden?
* Wenn ein Benutzer auf einer Seite eine Aktion ausgelöst hat und vom System ein Feedback erhalten soll.
* Oder wenn ein technisches Problem besteht, das den Benutzer am Arbeiten hindert.


## 3. Regeln
* Notifications erscheinen immer erst nach dem Auslösen einer Aktion durch den Benutzer.
* Die Breite kann sich nach der Breite eines Formulars, dem ganzen Content-Bereich oder einer Standardbreite beim Ensatz als Toast richten.
* Die Höhe richtet sich nach der Textlänge der Meldung.
* Wird der Benutzer am Weiterarbeiten gehindert (durch einen Fehler), so wird die Applikation mittels Milchglas gesperrt. In diesem Fall kann auch die Notification nicht weggeklickt werden (das 'X' wird dann nicht angezeigt).


## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Default

### 4.1 Bestätigung
![Darstellung der Komponente Benachrichtigung in der Ausprägung Bestätigung](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/notification/images/notification_confirmation.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/17140415/355318543/inspect)

### 4.2 Hinweis
![Darstellung der Komponente Benachrichtigung in der Ausprägung Hinweis](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/notification/images/notification_information.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/17140415/355318544/inspect)

### 4.3 Warnung 
![Darstellung der Komponente Benachrichtigung in der Ausprägung Warnung](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/notification/images/notification_warning.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/17140415/355318545/inspect)

### 4.4 Fehler 
![Darstellung der Komponente Benachrichtigung in der Ausprägung Fehler](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/notification/images/notification_error.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/17140415/355318546/inspect)

### 4.5 Fehler mit Sprungmarke 
![Darstellung der Komponente Benachrichtigung in der Ausprägung Fehler mit Sprungmarke](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/notification/images/notification_link.png 'class: image')

* Kann ein Fehler nicht einem einzelnen Element zugewiesen werden, dann wird die Fehlermeldung mit Sprungmarken eingesetzt.
* Die einzelnen Sprungmarken werden durch ein «/» getrennt.
* Beim Klick auf eine Sprungmarke wird direkt zum Ursprung des entsprechenden Fehlers gescrollt.
* Das Sprungmarkenziel ist immer auf derselben Seite wie die Notification (kein Absprung auf andere Seiten).

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/17140415/355318547/inspect)
