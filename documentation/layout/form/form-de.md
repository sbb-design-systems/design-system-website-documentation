## 1. Was macht das Modul?
Eingaben des Benutzers sammeln, validieren und absenden.

## 2. Wann soll das Modul eingesetzt werden?
Wenn man Daten des Benutzers braucht, dann ist es ein Formular.

## 3. Regeln 
* Formularlayout
    * Hat das Formular eine eigene Seite hat es immer einen Titel und optional einen [Leadtext](https://digital.sbb.ch/de/basics/typography).
    * Einzelne Formularelemente können zu Abschnitten zusammengefügt werden. Diese Abschnitte sind mit einer horizontalen Linie voneinander getrennt.
    * Ein Abschnitt hat immer einen Titel.
* Absenden des Formulars
    * Nach dem Versand erscheint eine Bestätigung der Übermittlung.
* Feldvalidierung
    * Die Feldvalidierung passiert beim Verlassen eines einzelnen Feldes.
    * Fehlerhafte Felder werden direkt rot markiert (roter Rahmen und Fehlerhinweis).
* Formvalidierung
    * Wird durchgeführt, wenn das Formular über den «Submit» Button versendet wird.
    * Fehler in der Formvalidierung werden mit einer [Notification](https://digital.sbb.ch/de/components/notification) angezeigt (bei Fehlern aus der Feldvalidierung wird die [Notification mit Sprungmarke](https://digital.sbb.ch/de/components/notification) eingesetzt).
* Inaktive Felder
    * Formularfelder sind als disabled darzustellen, wenn sie noch abhängig von einer anderen Auswahl sind. Können Felder nie enabled werden (z.B. aufgrund der Berechtigung eines Benutzers), so soll das Feld als Label angezeigt werden.
    * Der «Submit» Button ist immer aktiv.
* Optionale Eingaben im Formular werden bei der Feldbezeichnung mit «(optional)» ergänzt.

## 4. Ausprägungen und Zustände
Das Modul hat folgende Zustände:
* Valid
* Invalid

### 4.1 Floating Layout (ein Feld nach dem anderen mit Umbruch)
* Die Formularfelder werden aneinander gereiht, mit allfälligem Zeilenumbruch.

### 4.2 Zweispaltiges Layout