## 1. Was macht die Komponente?
* Dient zur Eingabe von Texten und Zahlen.

## 2. Wann soll das Element eingesetzt werden?
* Wenn vom Benutzer eine Eingabe benötigt. wird.

## 3. Regeln 
* Ein Eingabefeld hat immer ein Label.
* Für detaillierte Erklärungen kann neben dem Label ein Fragezeichen im Kreis dargestellt werden. Beim Klick auf dieses Fragezeichen öffnet sich ein (link: webapps/components/tooltip text: Tooltip).
* Der Eingabetext ist immer einzeilig.
* Wird der Text während der Eingabe länger als die Breite des Eingabefeldes wird der geschriebene Text nach links verdrängt, damit das aktuell Geschriebene immer gesehen wird.
* Nach dem Verlassen des Eingabefeldes mit einem langen Text wird dieser am Ende abgeschnitten und mit «...» gekennzeichnet.
* Ein Eingabefeld kann einen Hinweistext (Placeholder) enthalten, welcher direkt im Eingabefeld angezeigt wird, solange vom Benutzer kein Wert eingetragen wurde.
* Kann der Benutzer ein Formularfeld nie bearbeiten, so darf kein Eingabefeld verwendet werden (Darstellung als Text).

## 4. Ausprägungen und Zustände 
Das Element hat folgende Zustände:
* Default
* Hinted
* Focused
* Disabled
* Error

### 4.1 Standard
(srcset: textfield_default extension: png class: image)

#### 4.1.1 Vermassung
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318592/inspect text: Default)
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318593/inspect text: Hinted)
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318594/inspect text: Focused)
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318595/inspect text: Disabled)
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318596/inspect text: Error)

### 4.2 Passworteingabe
(srcset: textfield_password extension: png class: image)
* Das Eingabefeld in der Ausprägung «Passwort» stellt keinen Zustand «Hinted» zur Verfügung.

#### 4.2.1 Vermassung
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318596/inspect text: Default)
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318597/inspect text: Focused)
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318598/inspect text: Disabled)
*   (link: https://sbb.invisionapp.com/d/main#/console/17140415/355318600/inspect text: Error)