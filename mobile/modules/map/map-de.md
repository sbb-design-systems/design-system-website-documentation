## 1. Was macht das Modul?
*   Zeigt Kartenmaterial an.

## 2. Wann soll das Modul eingesetzt werden?
*   Geografische Darstellung irgendwelcher Objekte (z.B. Shops, Züge, Haltestellen, POIs, ...).

## 3. Regeln
*   Wenn der Benutzer die App dazu berechtigt hat, den aktuellen Standort zu verwenden, wird dieser in der Karte angezeigt.
*   Die Karte soll je nach Element bzw. nach Einsatzkontext defaultmässig immer einen sinnvollen Ausschnitt darstellen; in den meisten Fällen ist der aktuelle Standort auf der Karte initial zu fokussieren.
*   Mittels einem Suchfeld kann nach einem Ort oder einer Adresse gesucht werden.
*   Ein Klick auf die Karte im Small Zustand (innerhalb eines Moduls) öffnet die Karte im Fullscreen.
    *   Im Fullscreen können Interaktionen über die Karte ermöglicht werden.
    *   Die Karten bieten die Möglichkeit zum Verkleinern und Vergrössern des Kartenausschnittes (Zoom).

## 4. Ausprägungen und Zustände
Das Modul hat folgende Ausprägungen:
*   Inline
*   Fullscreen

### 4.1 Standard
![Darstellung von Karten, Inline und Fullscreen](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/mobile/modules/map/images/MM13_Karte.png 'class: image')

#### Design Spezifikation
*   [Inline](https://sbb.invisionapp.com/d/main#/console/14051805/322943572/inspect)
*   [Fullscreen](https://sbb.invisionapp.com/d/main#/console/14051805/322943573/inspect)