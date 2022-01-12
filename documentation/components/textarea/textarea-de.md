## 1. Was macht die Komponente?
Dient zur Eingabe von grösseren Textmengen in Formularen.

## 2. Wann soll die Komponente eingesetzt werden? 
Wenn vom Benutzer längere Texteingaben verlangt werden.

## 3. Regeln 
* Die Textarea hat immer ein Label.
* Optionale Eingaben werden mit dem Text «(optional)» hinter dem Label versehen. Bei kurzen Feldern kann der Text «(optional)» mit «(opt.)» abgekürzt werden.
* Für detaillierte Erklärungen kann neben dem Label ein Fragezeichen im Kreis dargestellt werden. Beim Klick auf dieses Fragezeichen öffnet sich ein [Tooltip](https://digital.sbb.ch/de/websites/components/tooltip).
* Unten rechts wird die noch verfügbare Anzahl Zeichen angezeigt (ausser die Textarea ist disabled).
* Die Breite der Textarea entspricht immer der ganzen Formularbreite.
* Die Basishöhe kann beim Gestalten des Formulars gesetzt werden.
* Wird der Text länger als die Basishöhe der Textarea, wächst das Element in der Höhe mit dem Inhalt mit.

## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Default
* Focused
* Disabled
* Error

### 4.1 Standard
![Darstellung der Komponente Textarea in der Ausprägung Standard](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/textarea/images/textarea_default.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/OzREQ4#Inspector)
* [Focused](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/mjKVkJ#Inspector)
* [Disabled](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/DKwR1W#Inspector)
* [Error](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/apaOJZ#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/textarea?variant=standard)