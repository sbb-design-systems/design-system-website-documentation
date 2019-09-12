## 1. Was macht die Komponente?
* Blättert durch eine Liste von Elementen oder Seiten.

## 2. Wann soll die Komponente eingesetzt werden? 
* Bei langen Listen von Elementen oder Seiten.

## 3. Regeln
* Anzahl Elemente pro Seite muss kontextspezifisch definiert werden.

## 4. Ausprägungen und Zustände 
### 4.1 Nummern
Die Komponente hat folgende Zustände:
* First
* Middle
* Last
* Hover

![Darstellung der Komponente zur Paginierung mittels Seitenzahlen](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/pagination/images/pagination_numbers.png 'class: image')
* Maximal 5 Seitenzahlen werden angezeigt.
* Tastaturbedienung
		* Die aktive Seite kann nicht angesprungen werden.
		* Tab-Reihenfolge: Pfeil zurück, erste anspringbare Seite, nächste anspringbare Seite usw., Pfeil vorwärts.
		* Die Kurzform «...» für versteckte Seiten kann nicht angesprungen werden.

#### Design Spezifikation
* [First](https://sbb.invisionapp.com/d/main#/console/15744722/328136679/inspect)
* [Middle](https://sbb.invisionapp.com/d/main#/console/15744722/328136680/inspect)
* [Last](https://sbb.invisionapp.com/d/main#/console/15744722/328136681/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/15744722/328136682/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/pagination)

### 4.2 Seitennamen
Diese Ausprägung hat folgende Zustände:
* Default
* Hover

![Darstellung der Komponente zur Paginierung mittels Seitennamen](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/pagination/images/pagination_pages.png 'class: image')
* Kann «vor» und «zurück» Link enthalten, oder optional nur «vor» oder «zurück» (wenn die erste oder letzte Seite aktiv ist).
* Beschriftet sind die Pagination-Links mit dem Titel der anzuspringenden Seite.
* Der Link-Text hat eine Maximalbreite entsprechend dem Layout. Längere Texte werden mittels «...» abgeschnitten.

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/328136683/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/15744722/328136684/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/pagination)