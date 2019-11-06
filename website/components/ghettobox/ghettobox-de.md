## 1. Was macht die Komponente?
Dient zur Anzeige von seitenübergreifenden Meldungen.

## 2. Wann soll die Komponente eingesetzt werden? 
Bei Hinweisen und Störungen welche eine ganze Applikation betreffen.

## 3. Regeln
* Die Ghettobox kann mit dem X-Icon bis zum nächsten Seiten-Reload ausgeblendet werden.
* Die Ghettobox steht immer direkt unterhalb des [Header](https://digital.sbb.ch/de/modules/header).
* Die Ghettobox ist nicht sticky sondern scrollt mit dem Inhalt weg.
* Der Text kann mehrzeilig sein.
* Vor dem Text steht immer ein [Icon](https://digital.sbb.ch/de/icons-und-piktogramme/sbb-icons) in roter Fläche (HIM/CUS-Icons).
* Wenn mehrere Ghettoboxen gleichzeitig verwendet werden, sind diese untereinander anzuordnen.

## 4. Ausprägungen und Zustände
### 4.1 Standard
![Darstellung der Komponente Ghettobox in der Ausprägung Standard](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/ghettobox/images/ghettobox_default.png 'class: image')

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/328136671/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/public/components/ghettobox)

### 4.2 Link
Diese Ausprägung hat folgende Zustände:
* Default
* Hover

![Darstellung der Komponente Ghettobox mit Link](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/ghettobox/images/ghettobox_link.png 'class: image')
* Sofern der Text einen weiterführenden [Link](https://digital.sbb.ch/de/components/link) beinhaltet, unterscheidet die Ghettobox die Zustände Normal und Hover.
* Am Ende des Textes folgt immer ein Pfeil-Icon.
* Die ganze Fläche der Ghettobox ist klickbar und öffnet den hinterlegten Link (ausser über dem X-Icon).

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/328136672/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/15744722/328136673/inspect)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/public/components/ghettobox)