## 1. Was macht die Komponente?
Dient zur Anzeige in welchem Schritt eines Prozesses sich ein Benutzer befindet.

## 2. Wann soll die Komponente eingesetzt werden? 
Bei sämtlichen Prozessen bei denen ein Benutzer mehrere Schritte/Seiten durchläuft um diesen abschliessen zu können.

## 3. Regeln
* Der Processflow ist immer zuoberst, direkt nach dem [Breadcrumb](https://digital.sbb.ch/de/websites/components/breadcrumb) positioniert.
* Der Benutzer kann im Processflow auf einen bereits durchlaufenen Prozesschritt zurücknavigieren.
* Vorwärtsnavigation im Prozess ist nur durch den Call-to-Action der entsprechenden Seite erlaubt. Ein Überspringen (vorwärts) von Schritten ist nicht erlaubt.

## 4. Ausprägungen
### 4.1 Standard
![Darstellung der Komponente für Prozessschritte](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/processflow/images/processflow_default.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/vOQPb1#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/processflow?variant=standard)