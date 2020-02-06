## 1. Was macht die Komponente?
Dient zur Eingabe von Texten und Zahlen.

## 2. Wann soll die Komponente eingesetzt werden? 
Wenn vom Benutzer eine Eingabe benötigt. wird.

## 3. Regeln 
* Ein Eingabefeld hat immer ein Label.
* Optionale Eingaben werden mit dem Text «(optional)» hinter dem Label-Text versehen. Bei kurzen Feldern darf der Text «(optional)» mit «(opt.)» abgekürzt werden.
* Für detaillierte Erklärungen kann neben dem Label ein Fragezeichen im Kreis dargestellt werden. Beim Klick auf dieses Fragezeichen öffnet sich ein [Tooltip](https://digital.sbb.ch/de/websites/components/tooltip).
* Der Eingabetext ist immer einzeilig.
* Wird der Text während der Eingabe länger als die Breite des Eingabefeldes wird der geschriebene Text nach links verdrängt, damit das aktuell Geschriebene immer gesehen wird.
* Nach dem Verlassen des Eingabefeldes mit einem langen Text wird dieser am Ende abgeschnitten und mit «\...» gekennzeichnet.
* Ein Eingabefeld kann einen Hinweistext (Placeholder) enthalten, welcher direkt im Eingabefeld angezeigt wird, solange vom Benutzer kein Wert eingetragen wurde.
* Ein Eingabefeld kann drei unterschiedliche Breiten haben:
    * Kurz → 1/6 der verfügbaren Breite des Containers/Parent-Elements (1/4 bei Tablet Portrait, 1/3 bei Mobile Portrait).
    * Mittel → 1/2 der verfügbaren Breite des Containers/Parent-Elements (ganze Breite bei Mobile Portrait).
    * Lang → ganze verfügbare Breite des Containers/Parent-Elements.
* Kann der Benutzer ein Formularfeld nie bearbeiten, so darf kein Eingabefeld verwendet werden (Darstellung als Text).

## 4. Ausprägungen und Zustände 
Die Komponente hat folgende Zustände:
* Default
* Hinted
* Focused
* Disabled
* Error

### 4.1 Standard
![Darstellung der Komponente Eingabefeld Standard](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/textfield/images/textfield_default.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/327021294/inspect)
* [Hinted](https://sbb.invisionapp.com/d/main#/console/15744722/327021295/inspect)
* [Focused](https://sbb.invisionapp.com/d/main#/console/15744722/327021296/inspect)
* [Disabled](https://sbb.invisionapp.com/d/main#/console/15744722/327021297/inspect)
* [Error](https://sbb.invisionapp.com/d/main#/console/15744722/327021298/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/public/components/field)

### 4.2 Passworteingabe
![Darstellung der Komponente Eingabefeld für Passwort](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/textfield/images/textfield_password.png 'class: image')
* Das Eingabefeld in der Ausprägung "Passwort" stellt keinen Zustand "Hinted" zur Verfügung.

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/327021299/inspect)
* [Focused](https://sbb.invisionapp.com/d/main#/console/15744722/327021300/inspect)
* [Disabled](https://sbb.invisionapp.com/d/main#/console/15744722/327021301/inspect)
* [Error](https://sbb.invisionapp.com/d/main#/console/15744722/327021302/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/public/components/field)