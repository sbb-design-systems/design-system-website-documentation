## 1. Was macht das Modul?
* Dient zur Eingabe von einfachen Suchabfragen.

## 2. Wann soll das Modul eingesetzt werden?
* Wenn dem Benutzer die Eingabe einer Suchabfrage mittels einem oder mehreren (Teil-)Wörtern zur Verfügung gestellt werden soll.

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
Das Modul hat folgende Zustände:
* Initial
* Suggested
* NoResult

### 4.1 Standard
* Die Anzahl der angezeigten Auto-Suggest Begriffe ist für jeden Anwendungsfall zu definieren.
* Empfehlung maximal 10 Einträge.

### 4.2 Im Header
Diese Ausprägung hat zusätzlich folgende Zustände:
* Hover
* Focused

* Durch Klick auf «Suchen» öffnet sich die Eingabemaske.
* Nach dem Auslösen der Suche, wird die Eingabemaske wieder ausgeblendet und nur der Link «Suchen» angezeigt.
* Dieses Modul darf nur im [Header](WK01---Header_30824686.html) eingesetzt werden.
* Beim Auslösen der Suche werden die Resultate auf einer eigenen Seite dargestellt.
* Während des Tippens werden maximal 4 Auto-Suggest Vorschläge angezeigt.