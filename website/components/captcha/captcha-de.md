## 1. Was macht die Komponente?
* Stellt eine Abfrage um sicherzustellen, dass eine Webseite mit einen realen Benutzer interagiert.

## 2. Wann soll die Komponente eingesetzt werden? 
* Bei Formularen welche ohne Login zugänglich sind.

## 3. Regeln
* Das Captcha steht immer am Ende eines Formulars, vor dem «Senden» Button.
* Beim Formularen, bei welchen der Benutzer eingeloggt ist, darf kein Captcha verwendet werden.

## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Checked
* Unchecked

### 4.1 Standard
![](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/captcha/images/captcha_default.png 'class: image') 

#### Design Spezifikation
*   [Checked](https://sbb.invisionapp.com/d/main#/console/15744722/327768739/inspect) 
*   [Unchecked](https://sbb.invisionapp.com/d/main#/console/15744722/327768740/inspect) 

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/captcha)