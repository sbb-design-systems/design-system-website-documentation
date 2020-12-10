## 1. Was macht die Komponente?
Dient zur Eingabe von einfachen Suchabfragen.

## 2. Wann soll die Komponente eingesetzt werden? 
Wenn dem Benutzer die Eingabe einer Suchabfrage mittels einem oder mehreren (Teil-)Wörtern zur Verfügung gestellt werden soll.

## 3. Regeln
* Das Suchfeld hat immer einen Platzhaltertext, mit einem Hinweis, welche Suchbegriffe akzeptiert werden.
* Sobald der Fokus im Suchfeld ist, können bei Bedarf dem Benutzer bis zu 9 häufigste Stichworte «Oft gesucht» angezeigt werden.
* Nachdem der zweite Buchstaben eingetippt wurde, erscheinen vier mögliche Ergebnisse (Auto-Suggest-Mechanismus).
* Die Übereinstimmung der eingegebenen Buchstaben werden in der Treffer-Liste fett ausgezeichnet.
* Falls es keine Treffer gibt, bleiben die häufigsten Stichworte alleine stehen. Sind keine häufigsten Stichworte definiert und es gibt keine Treffer, ist die Auto-Suggest-Box ausgeblendet.
* Zu lange Auto-Suggest-Begriffe werden abgeschnitten und mit «...» gekennzeichnet.
* Werden als Eingabe Webcodes zugelassen, ist der Auto-Suggest-Mechanismus deaktiviert.
* Durch Klick auf den «Suchen» Button (Lupe) oder durch die Enter-Taste wird die Suche ausgelöst.
* Wird der Text während der Eingabe länger als die Breite des Suchfeldes wird der geschriebene Text nach links verdrängt, damit das aktuell Geschriebene immer gesehen wird.
* Nach dem Verlassen des Suchfeldes mit einem langen Text wird dieser am Ende abgeschnitten und mit «\...» gekennzeichnet.
* Wird ein Auto-Suggest Begriff aus der Liste angeklickt, wird direkt zu dieser Seite navigiert.

## 4. Ausprägungen und Zustände 
Die Komponente hat folgende Zustände:
* Default
* No Result
* Suggested
 
### 4.1 Standard
![Darstellung der Komponente Suchfeld in der Ausprägung Standard](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/searchfield/images/searchfield_default.png 'class: image')
* Die Anzahl der angezeigten Auto-Suggest Begriffe ist für jeden Anwendungsfall zu definieren.
* Empfehlung maximal 10 Einträge.

#### Design Spezifikation
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/ozDKx3#Inspector)
* [No Result](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/Rvo8qj#Inspector)
* [Suggested](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/1JPWRk#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/public/components/search)

### 4.2 Im Header
Diese Ausprägung hat folgende Zustände:
* Default
* Hover
* Focused
* No Result
* Suggested

![Darstellung der Komponente Suchfeld integriert im Header](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/searchfield/images/searchfield_header.png 'class: image')
* Durch Klick auf «Suchen» öffnet sich die Eingabemaske.
* Nach dem Auslösen der Suche, wird die Eingabemaske wieder ausgeblendet und nur der Link «Suchen» angezeigt.
* Dieses Modul darf nur im [Header](https://digital.sbb.ch/de/websites/modules/header) eingesetzt werden.
* Beim Auslösen der Suche werden die Resultate auf einer eigenen Seite dargestellt.
* Während des Tippens werden maximal 4 Auto-Suggest Vorschläge angezeigt.

#### Design Spezifikation
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/pZKwyk#Inspector)
* [Hover](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/VOobqa#Inspector)
* [Focused](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/Ya5dqd#Inspector)
* [No Result](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/KPRq8K#Inspector)
* [Suggested](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/wmQgYV#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/public/components/search)