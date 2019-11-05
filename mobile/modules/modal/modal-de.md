## 1. Was macht das Modul?
*   Dunkelt den aktuellen View ab und legt einen modalen Dialog darüber.

## 2. Wann soll das Modul eingesetzt werden?
*   Wenn die Aufmerksamkeit des Benutzer benötigt wird.
*   Wenn vom Benutzer eine Information/Input verlangt wird.
*   Wenn verwandter Inhalt dargestellt werden soll.
*   Wenn zusätzlicher Inhalt dargestellt werden soll.
*   Das Modul ist nicht geeignet für Fehlermeldung, Warnungen oder Ähnliches.

## 3. Regeln
*   Der Benutzer muss immer die Möglichkeit haben den modalen Dialog zu schliessen.
*   Jeder modale Dialog besteht aus einem Header (Schliessen-Icon und Titel) und Inhalt.
*   Der Inhalt muss mindestens ein Interaktionselement enthalten (z.B. «Speichern» oder «OK»).
*   Der modale Dialog darf nicht für Fehlermeldungen verwendet werden.
*   Die Breite und Höhe des Dialogs wird durch die Grösse des Inhalts bestimmt.
*   Ein Mindestabstand zum Bildschirmrand ist zu gewährleisten.
*   Bei Klick auf den abgedunkelten Bereich wird der modale Dialog geschlossen.
*   Ist der Inhalt zu gross, kann ein vollflächiger modaler Dialog gewählt werden: siehe Seitentypen.

## 4. Ausprägungen
### 4.1 Standard
![Darstellung eines modalen Dialogs](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/mobile/modules/modal/images/MM03.png 'class: image')

#### 4.1.1 Vermassung
*   [Standard](https://sbb.invisionapp.com/d/main#/console/14051805/322943545/inspect)

## 5. Barrierefreiheit
*   Inhalte ausserhalb des geöffneten Dialogs sollen per Screen Reader nicht mehr erreichbar sein.