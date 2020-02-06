## 1. Was macht die Komponente?
Dient zum Hochladen von Dateien.

## 2. Wann soll die Komponente eingesetzt werden? 
Wenn eine Anwendung eine oder mehrere Dateien eines Benutzers verlangt.

## 3. Regeln 
* Mit Klick auf den [Button](https://digital.sbb.ch/de/websites/components/button) «Datei hochladen» öffnet sich der Datei-Browser des Systems.
* Die hochgeladenen Dateien werden in einer Liste angezeigt.
* Die Liste ist sortiert nach der chronologischen Reihenfolge des Hochladens.
* Mittels «Löschen» Button (Papierkorb) kann eine einzelne Datei wieder aus der Liste entfernt werden.
* Der Listeneintrag beinhaltet das Icon des Dateityps, den Dateinamen sowie in Klammern den Dateityp und die Dateigrösse.
* Der Datei-Upload hat über dem [Button](https://digital.sbb.ch/de/websites/components/button) immer einen Hinweis, welche Dateitypen und -grössen hochgeladen werden können.

## 4. Ausprägungen und Zustände 
Die Komponente hat folgende Zustände:
* Default
* Uploaded
* Disabled

### 4.1 Standard
![Darstellung der Komponente zur Hochladen von Dateien](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/fileselector/images/fileselector_default.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/378105832/inspect)
* [Uploaded](https://sbb.invisionapp.com/d/main#/console/15744722/378105833/inspect)
* [Disabled](https://sbb.invisionapp.com/d/main#/console/15744722/378105834/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/public/components/file-selector)