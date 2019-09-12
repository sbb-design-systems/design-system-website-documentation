## 1. Was macht das Element?
* Dient zur Eingabe eines Datums.

## 2. Wann soll das Element eingesetzt werden?
* Immer wenn vom Benutzer ein Datumswert verlangt wird.

## 3. Regeln
* Datumsangaben sind immer einzeilig.
* Die Datumswahl hat immer ein Label.
* Für detaillierte Erklärungen kann neben dem Label ein Fragezeichen im Kreis dargestellt werden. Beim Klick auf dieses Fragezeichen öffnet sich ein [Tooltip](https://digital.sbb.ch/de/webapps/components/tooltip).
* Mit Klick ins Datumsfeld kann das Datum von Hand eingetragen werden.
* Bei der manuellen Eingabe muss der Punkt immer vom Benutzer eingegeben werden. Danach übernimmt das Element die korrekte Formatierung, d.h. es müssen Eingaben wie 1.1.18 akzeptiert und ins gewünschte Format umgesetzt werden. In diesem Fall würde der 1. Januar 2018 ausgewählt.
* Bei Klick auf das Kalender-Icon öffnet sich ein Kalender-Layer zur Auswahl des Datums. Mittels Klick ausserhalb des Kalender-Layers wird dieser wieder geschlossen.
* Im Kalender-Layer können einzelne Tage oder ganze Datumsbereiche deaktiviert werden.
* Die Navigationspfeile im Kalender-Layer (Monat / Jahr) werden nur dargestellt, wenn auch ein vorangehendes/nachfolgende Datum gewählt werden kann.
* Das gewählte Datum wird im Format Wochentag, TT.MM.JJJJ dargestellt (Beispiel Fr, 04.08.2017).
* Wenn der Fokus im Kalender-Layer liegt, kann dieser wie folgt mittels Tastatur bedient  werden:
    * Pfeiltasten: Wechseln des markierten Tages.
    * Leertaste / Enter: Auswahl des markierten Tages.

## 4. Ausprägungen und Zustände 
Die Komponente hat folgende Zustände:
* Default
* Focused
* Disabled

### 4.1 Standard
![Darstellung der Datumsauswahl, Standard](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/datepicker/images/dateinput_default.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/17140415/355318424/inspect)
* [Focused](https://sbb.invisionapp.com/d/main#/console/17140415/355318425/inspect)
* [Disabled](https://sbb.invisionapp.com/d/main#/console/17140415/355318426/inspect)
* [Error](https://sbb.invisionapp.com/d/main#/console/17140415/355318427/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/business/components/datepicker)


### 4.2 Mit Blätterfunktion
![Darstellung der Datumsauswahl, mit Blätterfunktion](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/datepicker/images/dateinput_pageable.png 'class: image')
* Die Navigationspfeile werden nur dargestellt, wenn auch ein vorangehendes/nachfolgende Datum gewählt werden kann.

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/17140415/355318428/inspect)
* [Focused](https://sbb.invisionapp.com/d/main#/console/17140415/355318429/inspect)
* [Disabled](https://sbb.invisionapp.com/d/main#/console/17140415/355318430/inspect)
* [Error](https://sbb.invisionapp.com/d/main#/console/17140415/355318431/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/business/components/datepicker)

### 4.3 Datumsbereich
* Um einen Datumsbereich zu wählen, werden zwei Datepicker kombiniert.
* Wird das Von-Datum mittels Kalender-Layer gewählt und das Bis-Datum ist noch nicht definiert, öffnet sich der Kalender-Layer des Bis-Feldes. Wurde bereits ein Bis-Datum gewählt, öffnet sich der Kalender-Layer nicht.
* Wählt der Benutzer ein Von-Datum > Bis-Datum, wird das Bis-Datum gelöscht und dessen Kalender-Layer eingeblendet.
* Sind beide Daten gewählt, wird im Kalender der gewählte Bereich farblich hinterlegt.

### 4.4 Geburtsdatum
![Darstellung der Geburtsdatumsauswahl](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/datepicker/images/dateinput_birthdate.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/17140415/355318432/inspect)
* [Hinted](https://sbb.invisionapp.com/d/main#/console/17140415/355318433/inspect)
* [Focused](https://sbb.invisionapp.com/d/main#/console/17140415/355318434/inspect)
* [Disabled](https://sbb.invisionapp.com/d/main#/console/17140415/355318435/inspect)
* [Error](https://sbb.invisionapp.com/d/main#/console/17140415/355318436/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/business/components/datepicker)

### 4.5 Kalender-Layer (Datepicker)
![Darstellung der Datumsauswahl mit Kalenderdarstellung](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/datepicker/images/dateinput_picker.png 'class: image')
Die Tab-Reihenfolge innerhalb des Kalender-Layers ist wie folgt defniert:
1. Monat zurück
2. Monat vor
3. Jahr zurück
4. Jahr vor
5. Bereich der einzelnen Tage. Wenn der Fokus im Bereich der Tage liegt, kann mittels Pfeiltasten links, rechts, auf und ab innerhalb der Tage navigiert werden.

#### Design Spezifikation
* [Keine Auswahl](https://sbb.invisionapp.com/d/main#/console/17140415/355318437/inspect)
* [Datum gewählt](https://sbb.invisionapp.com/d/main#/console/17140415/355318438/inspect)
* [Datum mir Hover](https://sbb.invisionapp.com/d/main#/console/17140415/355318439/inspect)
* [Auswahleinschränkungen](https://sbb.invisionapp.com/d/main#/console/17140415/355318440/inspect)
* [Datumsbereich innerhalb eines Monats](https://sbb.invisionapp.com/d/main#/console/17140415/355318441/inspect)
* [Datumsbereich über Monatsgrenze](https://sbb.invisionapp.com/d/main#/console/17140415/355318442/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/business/components/datepicker)
