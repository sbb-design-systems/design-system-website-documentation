## 1. Was macht das Element?
* Dient zur Eingabe eines Datums.

## 2. Wann soll das Element eingesetzt werden?
* Immer wenn vom Benutzer ein Datumswert verlangt wird.

## 3. Regeln
* Datumsangaben sind immer einzeilig.
* Die Datumswahl hat immer ein Label.
* Optionale Datumseingaben werden mit dem Text «(optional)» hinter dem Label versehen. Bei kurzen Feldern kann der Text «(optional)» mit «(opt.)» abgekürzt werden.
* Für detaillierte Erklärungen kann neben dem Label ein Fragezeichen im Kreis dargestellt werden. Beim Klick auf dieses Fragezeichen öffnet sich ein (link: websites/components/tooltip text: Tooltip).
* Mit Klick ins Datumsfeld kann das Datum von Hand eingetragen werden. Bei Touch-Geräten erscheint die Zahlen-Eingabetastatur des entsprechenden Systems.
* Bei der manuellen Eingabe muss der Punkt immer vom Benutzer eingegeben werden. Danach übernimmt das Element die korrekte Formatierung, d.h. es müssen Eingaben wie 1.1.18 akzeptiert und ins gewünschte Format umgesetzt werden.
* Bei Klick auf das Kalender-Icon öffnet sich ein Kalender-Layer zur Auswahl des Datums. Mittels Klick ausserhalb des Kalender-Layers wird dieser wieder geschlossen.
* Auf Touch-Geräten wird nie der System-Datepicker verwendet.
* Im Kalender-Layer können einzelne Tage oder ganze Datumsbereiche deaktiviert werden.
* Die Navigationspfeile im Kalender-Layer (Monat / Jahr) werden nur dargestellt, wenn auch ein vorangehendes/nachfolgende Datum gewählt werden kann.

## 4. Ausprägungen und Zustände 
Das Element hat folgende Zustände:
* Default
* Focused
* Disabled

### 4.1 Standard
(srcset: datepicker_default extension: png class: image)
* Das gewählte Datum wird im Format Wochentag, TT.MM.JJJJ dargestellt (Beispiel Fr, 04.08.2017).
* Ein Klick auf das Kalender-Icon öffnet den Kalender-Layer.
* Wenn der Fokus im Kalender-Layer liegt, kann dieser wie folgt mittels Tastatur bedient  werden:
        * Pfeiltasten: Wechseln des markierten Tages.
        * Leertaste / Enter: Auswahl des markierten Tages.

#### Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327605628/inspect text: Default)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327605629/inspect text: Focused)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327605630/inspect text: Disabled)

#### Code Spezifikation
* (link: https://sbb-angular.app.sbb.ch/latest/content/datepicker text: SBB Angular Components Library)

### 4.2 Mit Blätterfunktion
(srcset: datepicker_pageable extension: png class: image)
* Das gewählte Datum wird im Format Wochentag, TT.MM.JJJJ dargestellt (Beispiel Fr, 04.08.2017).
* Die Navigationspfeile werden nur dargestellt, wenn auch ein vorangehendes/nachfolgende Datum gewählt werden kann.
* Ein Klick auf das Kalender-Icon öffnet den Kalender-Layer.
* Wenn der Fokus im Kalender-Layer liegt, kann dieser wie folgt mittels Tastatur bedient  werden:
        * Pfeiltasten: Wechseln des markierten Tages.
        * Leertaste / Enter: Auswahl des markierten Tages.

#### Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327605631/inspect text: Default)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327605632/inspect text: Focused)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327605633/inspect text: Disabled)

#### Code Spezifikation
* (link: https://sbb-angular.app.sbb.ch/latest/content/datepicker text: SBB Angular Components Library)

### 4.3 Datumsbereich
* Um einen Datumsbereich zu wählen, werden zwei Datepicker kombiniert.
* Wird das Von-Datum mittels Kalender-Layer gewählt und das Bis-Datum ist noch nicht definiert, öffnet sich der Kalender-Layer des Bis-Feldes. Wurde bereits ein Bis-Datum gewählt, öffnet sich der Kalender-Layer nicht.
* Wählt der Benutzer ein Von-Datum > Bis-Datum, wird das Bis-Datum gelöscht und dessen Kalender-Layer eingeblendet.
* Sind beide Daten gewählt, wird im Kalender der gewählte Bereich farblich hinterlegt.
* Die gewählten Daten wird im Format Wochentag, TT.MM.JJJJ dargestellt (Beispiel Fr, 04.08.2017).

### 4.4 Geburtsdatum
(srcset: datepicker_birthdate extension: png class: image)
* Das Geburtsdatum wird im Format TT.MM.JJJJ dargestellt (Beispiel 02.09.1986).

#### Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327605634/inspect text: Default)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327605635/inspect text: Focused)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327605636/inspect text: Disabled)

#### Code Spezifikation
* (link: https://sbb-angular.app.sbb.ch/latest/content/datepicker text: SBB Angular Components Library)

### 4.5 Kalender-Layer
(srcset: datepicker_picker extension: png class: image)
Die Tab-Reihenfolge innerhalb des Kalender-Layers ist wie folgt
defniert:
1.  Monat zurück
2.  Monat vor
3.  Jahr zurück
4.  Jahr vor
5.  Bereich der einzelnen Tage. Wenn der Fokus im Bereich der Tageliegt, kann mittels Pfeiltasten links, rechts, auf und ab innerhalb der Tage navigiert werden.

#### Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327605637/inspect text: Keine Auswahl)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327605638/inspect text: Datum gewählt)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327605639/inspect text: Datum mir Hover)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327605640/inspect text: Auswahleinschränkungen)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327605641/inspect text: Datumsbereich innerhalb eines Monats)
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/327605642/inspect text: Datumsbereich über Monatsgrenze)

#### Code Spezifikation
* (link: https://sbb-angular.app.sbb.ch/latest/content/datepicker text: SBB Angular Components Library)