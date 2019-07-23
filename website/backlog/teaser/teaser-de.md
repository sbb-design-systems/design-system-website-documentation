## 1. Was macht das Modul?
* Es werden Themen und Inhalte beworben.

## 2. Wann soll das Modul eingesetzt werden? 
* Zur Navigation von einer Themen Übersichtsseite zu den Detailseiten.

## 3. Regeln 
* Teaser bestehen immer aus einem [Bild](WE10---Bild_30823793.html) (keine Videos), einer Headline, allenfalls einer Copy und einem [Link](WE11---Link_30823966.html).
* Teaser können interne oder externe Seiten verlinken.
* Bei Hover vergrössert sich das Bild auf 110% (maskiert) und der Link wechselt auf die Hover-Version.

## 4. Ausprägungen und Zustände
Das Modul hat folgende Zustände:
* Normal
* Hover

### 4.1 Kacheln
* Alle Kacheln haben zusammen eine Überschrift.
* Der Linktext heisst immer «Mehr Info» (in der deutschen Sprachvariante).
* Die Headline ist maximal 2-zeilig.
* Der Abstand Headline / Copy ist fix.
* Der Hintergrund orientiert sich an der Höhe des längsten Teasers (innerhalb der Gruppe).
* Die Position des «Mehr Info» Links ist fix definiert vom unteren Rand der Hintergrundfläche. Der Abstand zwischen der Copy und dem Link ist damit flexibel.
* Die Copy ist maximal 4-zeilig.
* Im Mobile-Layout wird die Copy ausgeblendet.
* Sollte der Text der Copy zu lang sein, so wird der Satz mit «...» beendet. Wörter werden nicht abgeschnitten.
* Die komplette Fläche (Bild und Text-Fläche) ist klickbar.
* Es können 3 bis 6 Teaser platziert werden. Bei einer ungeraden Anzahl von Teasern (3 und 5) wird die Breite der Teaser angepasst.
* Der 5. und der 6. Teaser werden auf einer zweiten Zeile zentriert dargestellt.
* Tastaturbedienung
    * Die einzelnen Teaser können mittels Tab angesprungen werden.

### 4.2 Contentwide Teaser
Diese Ausprägung hat zusätzlich folgende Zustände:
* Automode active
* Automode inactive

* Es dürfen 1-3 Bilder im Teaser eingesetzt werden.
* Die Bilder werden defaultmässig automatisch gewechselt (alle 5 Sekunden).
* Die automatische Animation verschiebt die Bilder von rechts nach links. Dies auch beim Wechsel vom letzten auf das erste Bild. Bei manuellem Wechsel auf ein vorheriges Bild wird dann von links nach rechts verschoben.
* Der Teaser enthält das rote SBB Panel (mit Titel und einem Link, z.B. ???)
    * Optional dürfen auch Icons im Panel angezeigt werden. In der mobilen Ansicht, werden diese nicht gezeigt.
    * Optional darf zum Panel noch ein Aktionselement eingesetzt werden. Dies darf nur Text enthalten.
* Der Teaser nutzt die ganze Breite des Inhaltsbereichs.
*  Es gibt nur einen contentweiten Teaser pro Seite.
* Typischerweise wird dieser Teaser am Anfang der Seite eingesetzt.
* Bei Hover wird die automatische Animation wird unterbrochen.
* Auf mobilen Geräten kann mittels Swipe-Interaktion zwischen den Bildern gewechselt werden.
* Wird manuell auf ein anderes Bild gewechselt, so wird die automatische Animation unterbrochen.
* Tastaturbedienung
    * Die einzelnen Elemente der Navigationsleiste unterhalb der Bilder (Play- / Pause-Knopf, Bullets für die einzelnen Bilder) können mittels Tab angesprungen werden.
    * Die Elemente können mittels Leertaste oder Enter angewählt werden.
    * Nach dem letzten Bullet wird mittels Tab das Bild im Karrussel angesprungen. Auf den Inhalt dieses Teasers kann dann mittels Enter gesprungen werden.

#### 4.2.1 Homepage 
* Bilder sind oben und unten schräg abgeschnitten (Trapezform).
* Titel maximal 3-zeilig.

#### 4.2.2 Detailpage
* Bilder sind rechteckig dargestellt.
* Titel ist maximal 2-zeilig.