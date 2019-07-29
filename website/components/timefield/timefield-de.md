## 1. Was macht die Komponente?
* Dient zur Eingabe einer Uhrzeit.

## 2. Wann soll die Komponente eingesetzt werden? 
* Immer wenn vom Benutzer eine Uhrzeit verlangt wird.

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

### 4.1 Standard
![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/timefield/images/timefield_default.png 'class: image') 

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/327611017/inspect)
* [Hinted](https://sbb.invisionapp.com/d/main#/console/15744722/335006454/inspect)
* [Focused](https://sbb.invisionapp.com/d/main#/console/15744722/327611018/inspect)
* [Disabled](https://sbb.invisionapp.com/d/main#/console/15744722/327611019/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/time-input)