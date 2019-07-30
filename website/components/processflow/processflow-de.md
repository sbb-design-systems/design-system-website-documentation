## 1. Was macht die Komponente?
* Dient zur Anzeige in welchem Schritt eines Prozesses sich ein Benutzer befindet.

## 2. Wann soll die Komponente eingesetzt werden? 
* Bei sämtlichen Prozessen bei denen ein Benutzer mehrere Schritte/Seiten durchläuft um diesen abschliessen zu können.

## 3. Regeln
* Der Processflow ist immer zuoberst, direkt nach dem [Breadcrumb](https://digital.sbb.ch/de/components/breadcrumb) positioniert.
* Der Benutzer kann im Processflow auf einen bereits durchlaufenen Prozesschritt zurücknavigieren.
* Vorwärtsnavigation im Prozess ist nur durch den Call-to-Action der entsprechenden Seite erlaubt. Ein Überspringen (vorwärts) von Schritten ist nicht erlaubt.

## 4. Ausprägungen
### 4.1 Standard
![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/processflow/images/processflow_default.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/328136685/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/processflow)