## 1. Was macht die Komponente?
Stellt eine Abfrage um sicherzustellen, dass eine Webseite mit einen realen Benutzer interagiert.

## 2. Wann soll die Komponente eingesetzt werden? 
Bei Formularen welche ohne Login zugänglich sind.

## 3. Regeln
* Das Captcha steht immer am Ende eines Formulars, vor dem «Senden» Button.
* Beim Formularen, bei welchen der Benutzer eingeloggt ist, darf kein Captcha verwendet werden.

## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Checked
* Unchecked

### 4.1 Standard
![Darstellung der Komponente Captcha](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/captcha/images/captcha_default.png 'class: image')

#### Design Spezifikation
* [Checked](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/vOQPW4#Inspector) 
* [Unchecked](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/4e5zAD#Inspector) 

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/public/components/captcha)