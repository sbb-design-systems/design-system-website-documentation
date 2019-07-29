## 1. Was macht die Komponente?
* Stellt unterschiedliche Informationen und Funktionen zur Verfügung.

## 2. Wann soll die Komponente eingesetzt werden? 
* Zur Ergänzung von Inhaltsseiten.

## 3. Regeln
* Das Modul wird immer in der Marginalspalte (rechts) eingesetzt.
* Es können mehrere Module in der Marginalspalte untereinander platziert werden.
* Beim Scrollen werden alle Boxen in der Marginalspalte sticky. Die einzelnen Boxen werden sukzessive minimiert, sobald sie am oberen Rand des Viewports angelangt sind.
* Einzelne Boxen im gescrollten Zustand können vom Benutzer aufgeklappt werden.
* Es darf im gescrollten Zustand immer nur eine Box aufgeklappt sein.

## 4. Ausprägungen und Zustände 
Der Next Best Click Container hat keine Viewport übergreifenden Zustände, da sie sich unterschiedlich verhalten. Des Weiteren haben die einzelnen Ausprägungen zusätzlich unterschiedliche Varianten.

### 4.1 Aktion
![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/nbc/images/nbc_action.png 'class: image') 

####Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/345616913/inspect)
* [Double](https://sbb.invisionapp.com/d/main#/console/15744722/345616914/inspect)
* [Collapsed](https://sbb.invisionapp.com/d/main#/console/15744722/345616915/inspect)

#### Code Spezifikation
In Bearbeitung.

### 4.2 Kontakt
![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/nbc/images/nbc_contact.png 'class: image') 

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/345616916/inspect)
* [Collapsed](https://sbb.invisionapp.com/d/main#/console/15744722/345616917/inspect)

#### Code Spezifikation
In Bearbeitung.

### 4.3 Link
![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/nbc/images/nbc_link.png 'class: image') 

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/345616918/inspect)
* [Collapsed](https://sbb.invisionapp.com/d/main#/console/15744722/345616919/inspect)

#### Code Spezifikation
In Bearbeitung.

### 4.4 Download
![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/nbc/images/nbc_download.png 'class: image') 

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/345616920/inspect)
* [App](https://sbb.invisionapp.com/d/main#/console/15744722/345616921/inspect)
* [Collapsed](https://sbb.invisionapp.com/d/main#/console/15744722/345616922/inspect)

#### Code Spezifikation
In Bearbeitung.

### 4.5 Chat
![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/nbc/images/nbc_chat.png 'class: image') 

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/345616923/inspect)
* [Collapsed](https://sbb.invisionapp.com/d/main#/console/15744722/345616924/inspect)

#### Code Spezifikation
In Bearbeitung.

## 5. Verhalten
### 5.1 Desktop (und grössere Auflösungen)
* Alle Next-Best-Click Optionen sind auf Inhalts-Seiten in der Margin-Spalte (rechten Spalte) angeordnet.
* Beim Scrollen werden alle Boxen in der rechten Spalte sticky. Die einzelnen Boxen werden sukzessive minimiert, sobald sie an den oberen Rand des Viewports (unterhalb des Sticky Headers) angelangt sind (respektive bei schon minimierten Boxen jeweils darunter).
* Im minimierten Zustand bleiben alle Boxen jederzeit für den User zugängig/erreichbar.
* Der User kann dann jeweils eine Box öffnen (und auch wieder schliessen).
* Im gescrollten Zustand kann jeweils nur eine Box zugleich geöffnet sein.
* Die NBC-Box bleibt solange sticky, bis der User am Ende der Content-Area angelangt ist. Scrollt der User weiter nach unten werden die Boxen mit dem Content nach oben weggescrolled.
* Scrollt der User danach wieder nach oben, erscheint auch die NBC-Box wieder und bleibt wieder sticky.

![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/nbc/images/nbc_behaviour_desktop_default.png 'class: image') 

#### Sonderfall NBC-Box innerhalb eines Accordion
* Bei der Anwendung einer NBC-Box innerhalb eines [Accordion](https://digital.sbb.ch/de/components/accordion) wird diese nie minimiert.
* Es darf nur eine NBC-Box in einem Accordion eingesetzt werden.
* Beim Scrollen bleibt die NBC-Box sticky am oberen Rand bis zum Ende der Content-Area des Accordions, dannach wird die Box mit dem Content weitergescrollt.

![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/nbc/images/nbc_behaviour_desktop_accordion.png 'class: image') 

### 5.2 Tablet
* Alle Next-Best-Click Optionen sind jederzeit über das sticky Element rechts unten verfügbar.
* Auf Klick öffnet sich ein Layer mit allen NBC-Modulen im offenen Zustand nebeneinander (zweispaltige Darstellung)
* Das Icon im Sticky-Element wechselt dann zum Schliessen-Button (Toggle-Button).
* In der Tablet-Variante werden die NBC-Boxen am Ende der Content-Area redundant (offen) dargestellt.
* Scrollt der User in den entsprechenden Bereich (und darüberhinaus) wird das Element zum Öffnen des NBC-Layers ausgeblendet.
* Scrollt der User wieder nach oben erscheint auch das Sticky-Element wieder.

![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/nbc/images/nbc_behaviour_tablet.png 'class: image') 

### 5.3 Mobile
* Alle Next-Best-Click Optionen sind jederzeit über das Sticky-Element rechts unten aufrufbar.
* Auf Klick öffnet sich ein Layer mit allen NBC-Modulen im geschlossenen Zustand. 
* Es kann jeweils nur ein Modul einzeln geöffnet werden.
* Das Icon in dem Sticky Element wechselt zum Schliessen-Icon (Toggle-Button).
* In der mobilen Variante werden die NBC-Boxen am Ende der Content-Area redundant (offen) dargestellt.
* Scrollt der User in den entsprechenden Bereich (und darüberhinaus) wird das Element zum Öffnen des NBC-Layers ausgeblendet.
* Scrollt der User wieder nach oben erscheint auch das Sticky-Element wieder

![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/nbc/images/nbc_behaviour_mobile.png 'class: image') 