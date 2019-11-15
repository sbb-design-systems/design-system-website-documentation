## 1. Was macht die Komponente?
* Dient zur Eingabe von Texten und Zahlen.


## 2. Wann soll die Komponente eingesetzt werden?
* Wenn vom Benutzer eine Eingabe benötigt wird.


## 3. Regeln 
* Ein Eingabefeld hat immer ein Label.
* Für detaillierte Erklärungen kann neben dem Label ein Fragezeichen im Kreis dargestellt werden. Beim Klick auf dieses Fragezeichen öffnet sich ein [Tooltip](https://digital.sbb.ch/de/webapps/components/tooltip).
* Der Eingabetext ist immer einzeilig.
* Wird der Text während der Eingabe länger als die Breite des Eingabefeldes wird der geschriebene Text nach links verdrängt, damit das aktuell Geschriebene immer gesehen wird.
* Nach dem Verlassen des Eingabefeldes mit einem langen Text wird dieser am Ende abgeschnitten und mit «...» gekennzeichnet.
* Ein Eingabefeld kann einen Hinweistext (Placeholder) enthalten, welcher direkt im Eingabefeld angezeigt wird, solange vom Benutzer kein Wert eingetragen wurde.
* Kann der Benutzer ein Formularfeld nie bearbeiten, so darf kein Eingabefeld verwendet werden (Darstellung als Text).


## 4. Ausprägungen und Zustände 
Das Element hat folgende Zustände:
* Default
* Hinted
* Focused
* Disabled
* Error

### 4.1 Standard
![Darstellung der Komponente Textfeld in der Standard Ausprägung](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/textfield/images/textfield_default.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/17140415/355318592/inspect)
* [Hinted](https://sbb.invisionapp.com/d/main#/console/17140415/355318593/inspect)
* [Focused](https://sbb.invisionapp.com/d/main#/console/17140415/355318594/inspect)
* [Disabled](https://sbb.invisionapp.com/d/main#/console/17140415/355318595/inspect)
* [Error](https://sbb.invisionapp.com/d/main#/console/17140415/355318596/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/business/components/field)

### 4.2 Passworteingabe
![Darstellung der Komponente Textfeld zur Passworteingabe](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/textfield/images/textfield_password.png 'class: image')
* Das Eingabefeld in der Ausprägung «Passwort» stellt keinen Zustand «Hinted» zur Verfügung.

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/17140415/355318596/inspect)
* [Focused](https://sbb.invisionapp.com/d/main#/console/17140415/355318597/inspect)
* [Disabled](https://sbb.invisionapp.com/d/main#/console/17140415/355318598/inspect)
* [Error](https://sbb.invisionapp.com/d/main#/console/17140415/355318600/inspect)
