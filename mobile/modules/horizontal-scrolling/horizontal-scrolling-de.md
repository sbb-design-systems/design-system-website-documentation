##1. Was macht das Modul?
*   Erlaubt das Scrollen durch eine horizontal angeordnete Liste von Elementen.

##2. Wann soll das Modul eingesetzt werden?
*   Wenn in einer horizontalen Liste mehrere Elemente darstellbar sind.
*   Wenn der Benutzer schnell durch eine Liste scrollen soll.
*   Zur Anordnung voneinander unabhängiger Elemente.

##3. Regeln
*   Das vorangehende und nächste Element der Liste ausserhalb des sichtbaren Bereichs muss angeschnitten dargestellt werden.
*   Das Scrollen funktioniert nicht Pixel für Pixel, sondern es gibt «Fangpunkte», sodass rechts und links jeweils (wenn vorhanden) die nächste Kachel angedeutet wird.

##4. Ausprägungen und Zustände
Das Modul hat folgende Zustände:
*   First
*   Middle
*   Last

### 4.1 Standard
![Darstellung von horizontalem Scrollen](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/mobile/modules/horizontal-scrolling/images/MM08.png 'class: image')

####4.1.1 Vermassung
[Standard](https://sbb.invisionapp.com/d/main#/console/14051805/322943557/inspect)

## 5. Barrierefreiheit
* Horizontales Scrollen muss auch per Screen Reader und Schaltersteuerung möglich sein.