## 1. Was macht die Komponente?
Dient zur Eingabe einer Uhrzeit.

## 2. Wann soll die Komponente eingesetzt werden? 
Immer wenn vom Benutzer eine Uhrzeit verlangt wird.

## 3. Regeln 
* Standardmässig ist die aktuelle Uhrzeit vorausgefüllt, ausser es macht im Kontext des Einsatzes keinen Sinn.
* Die Zeiteingabe kann ohne Eingabe des Doppelpunktes geschehen. Eingaben wie 130, 1.30 oder 1,30 werden nach verlassen des Feldes korrekt in 01:30 umformatiert.
* Bei Touch-Geräten erscheint die Zahlen-Eingabetastatur des entsprechenden Systems.

## 4. Ausprägungen und Zustände 
Die Komponente hat folgende Zustände:
* Default
* Hinted
* Focused
* Disabled
* Error

### 4.1 Standard
![Darstellung der Komponente Eingabefeld für Uhrzeiten](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/timefield/images/timefield_default.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/wmQgJV#Inspector)
* [Hinted](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/qJVqpd#Inspector)
* [Focused](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/LgnLQ5#Inspector)
* [Disabled](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/7mav4w#Inspector)
* [Error](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/yaQ2p8#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/time-input?variant=standard)