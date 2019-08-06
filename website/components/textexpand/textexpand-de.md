## 1. Was macht die Komponente?
* Klappt einen bestehenden Text weiter auf, um noch mehr Informationen anzuzeigen.

## 2. Wann soll die Komponente eingesetzt werden? 
* Bei langen Zusatzinformationen.

## 3. Regeln 
* Der Textexpand darf nur für Texte eingesetzt werden.
* Im aufgeklappten Zustand dürfen nebst dem Ausblenden keine weiteren Interaktionselemente eingesetzt werden.
* Die Trennung der Texte muss so erfolgen, dass der Kontext der gesamten Information bereits im zugeklappten Zustand klar ist.
* Darf nur bei mehrzeiligen Texten eingesetzt werden.
* Mehrfachverschachtelungen sind nicht erlaubt.
* Der Textexpand darf nicht zur Strukturierung von Elementen verwendet werden.
* Titel und andere Strukturmittel sind im ausgeblendeten Zustand nicht erlaubt.

## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Collapsed
* Expanded

### 4.1 Standard
![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/textexpand/images/textexpand_default.png 'class: image')

#### Design Spezifikation
* [Collapsed](https://sbb.invisionapp.com/d/main#/console/15744722/327015708/inspect)
* [Expanded](https://sbb.invisionapp.com/d/main#/console/15744722/327015709/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/textexpand)