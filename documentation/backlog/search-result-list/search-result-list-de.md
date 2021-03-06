## 1. Was macht das Modul?
Dient zu Darstellung von Suchresultaten.

## 2. Wann soll das Modul eingesetzt werden? 
Als Anzeige von Resultaten von Suchabfragen.

## 3. Regeln 
* Die Anzahl Suchergebnisse wird zu Beginn der Liste angezeigt.
* Wenn keine Suchergebnisse verfügbar sind, wird mit einer [Notification](https://digital.sbb.ch/de/components/notification) der Text «Keine Ergebnisse zum Suchbegriff «Chuchichästli»» angezeigt.
* Empfehlung: Nach 10 Ergebnissen eine [Pagination](https://digital.sbb.ch/de/components/pagination) einsetzen.

## 4. Ausprägungen
### 4.1 Standard
* Ergebnis besteht mindestens aus einer Headerzeile, welche klickbar ist und zur entsprechenden Seite führt.
* Bei Bedarf kann ein zusätzlicher Informationstext hinzugefügt werden. Dieser ist ebenfalls Teil des Links der Headerzeile.
* Der Informationstext kann mehrzeilig sein.
* Als letzte Zeile steht immer der Breadcrumb Pfad.
* Die einzelnen Begriffe des Pfades werden mit «/» getrennt.

### 4.2 Als Bilder
* Die [Bilder](https://digital.sbb.ch/de/basics/images) sind verlinkt und führen zur entsprechenden Seite.

### 4.3 Tabellarisch
* Die Liste hat immer genau 2 Spalten.
* Die Suchresultate sind zeilenweise (ganze Zeile) als [Links](https://digital.sbb.ch/de/components/link) ausgeprägt.