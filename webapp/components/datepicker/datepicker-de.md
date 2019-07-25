## 1. Was macht das Element?
* Dient zur Eingabe eines Datums.

## 2. Wann soll das Element eingesetzt werden?
* Immer wenn vom Benutzer ein Datumswert verlangt wird.

## 3. Regeln
* Datumsangaben sind immer einzeilig.
* Die Datumswahl hat immer ein Label.
* Für detaillierte Erklärungen kann neben dem Label ein Fragezeichen im Kreis dargestellt werden. Beim Klick auf dieses Fragezeichen öffnet sich ein (link: webapps/components/tooltip text: Tooltip).
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
(srcset: dateinput_default extension: png class: image)

#### 4.1.1 Vermassung
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318424/inspect text: Default)
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318425/inspect text: Focused)
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318426/inspect text: Disabled)
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318427/inspect text: Error)

### 4.2 Mit Blätterfunktion
(srcset: dateinput_pageable extension: png class: image)
* Die Navigationspfeile werden nur dargestellt, wenn auch ein vorangehendes/nachfolgende Datum gewählt werden kann.

#### 4.2.1 Vermassung
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318428/inspect text: Default)
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318429/inspect text: Focused)
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318430/inspect text: Disabled)
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318431/inspect text: Error)

### 4.3 Datumsbereich
* Um einen Datumsbereich zu wählen, werden zwei Datepicker kombiniert.
* Wird das Von-Datum mittels Kalender-Layer gewählt und das Bis-Datum ist noch nicht definiert, öffnet sich der Kalender-Layer des Bis-Feldes. Wurde bereits ein Bis-Datum gewählt, öffnet sich der Kalender-Layer nicht.
* Wählt der Benutzer ein Von-Datum > Bis-Datum, wird das Bis-Datum gelöscht und dessen Kalender-Layer eingeblendet.
* Sind beide Daten gewählt, wird im Kalender der gewählte Bereich farblich hinterlegt.

### 4.4 Geburtsdatum
(srcset: dateinput_birthdate extension: png class: image)

#### 4.4.1 Vermassung
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318432/inspect text: Default)
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318433/inspect text: Hinted)
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318434/inspect text: Focused)
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318435/inspect text: Disabled)
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318436/inspect text: Error)

### 4.5 Kalender-Layer (Datepicker)
(srcset: dateinput_picker extension: png class: image)
Die Tab-Reihenfolge innerhalb des Kalender-Layers ist wie folgt defniert:
1. Monat zurück
2. Monat vor
3. Jahr zurück
4. Jahr vor
5. Bereich der einzelnen Tage. Wenn der Fokus im Bereich der Tage liegt, kann mittels Pfeiltasten links, rechts, auf und ab innerhalb der Tage navigiert werden.

#### 4.5.1 Vermassung
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318437/inspect text: Keine Auswahl)
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318438/inspect text: Datum gewählt)
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318439/inspect text: Datum mir Hover)
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318440/inspect text: Auswahleinschränkungen)
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318441/inspect text: Datumsbereich innerhalb eines Monats)
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318442/inspect text: Datumsbereich über Monatsgrenze)