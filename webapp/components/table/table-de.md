## 1. Was macht das Element?
* Strukturierte Darstellung von Daten innerhalb einer Tabelle.

## 2. Wann soll das Element eingesetzt werden? 
* Einsatz bei der Darstellung von Daten, nicht zur Strukturierung von Content.
* Tabellen sollen so aufgebaut werden, dass diese beim Hinzufügen von Datensätzen in der Vertikalen (Zeilen) wächst.

## 3. Regeln
* Tabellenzellen können entweder nur Information (z.B. Text, Person, Statusanzeige, Icon, ...) oder Interaktionselemente (z.B. Textfeld, Select, Button, ...) enthalten.
* Pro Zeile können verschiedene Aktionen platziert werden (z.B. Buttons, Icon-Buttons, Links).
* Jede Spalte hat zwingend einen Header (Text oder Icon).
* Header können ein- oder mehrzeilig sein.
* Header- und Zeileninhalte können innerhalb der Tabellenzelle links-, rechtsbündig oder zentriert sein: Text linksbündig, Icons zentriert, Zahlen rechtsbündig
* Masseinheiten von Inhalten werden optimalerweise auf der zweiten Zeile des Spaltenheaders eingefügt. Alternativ können sie direkt neben der Spaltenheader-Bezeichnung in runden Klammern angezeigt.
* Horizontales Scrolling sollte wo möglich vermieden werden.
* Beim Hover über Zeilen können Aktionen auf den Elementen mittels Icons angeboten werden.
* Spalten können zu logischen Gruppen zusammengefasst werden. Zwischen gruppierten Spalten gibt es keine Trennlinie.

## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Default
* Hover

### 4.1 Standard
![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/table/images/table_default.png 'class: image')


#### 4.1.1 Vermassung
* (link: https://sbb.invisionapp.com/d/main#/console/17140415/355362889/inspect text: Default / Hover)

### 4.2 Gruppiert
![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/table/images/table_grouped.png 'class: image')


#### 4.2.1 Vermassung
* (link: https://sbb.invisionapp.com/d/main#/console/17140415/355362890/inspect text: Default / Hover)

### 4.3 Sortierbar
Diese Ausprägung hat folgende Zustände:
* Sorted
* Unsorted

![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/table/images/table_sortable.png 'class: image')


#### 4.3.1 Vermassung
* (link: https://sbb.invisionapp.com/d/main#/console/17140415/355362891/inspect text: Default / Hover)