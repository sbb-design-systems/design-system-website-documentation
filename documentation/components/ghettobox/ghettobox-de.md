## 1. Was macht die Komponente?
Dient zur Anzeige von seitenübergreifenden Meldungen.

## 2. Wann soll die Komponente eingesetzt werden? 
Bei Hinweisen und Störungen welche eine ganze Applikation betreffen.

## 3. Regeln
* Die Ghettobox kann mit dem X-Icon bis zum nächsten Seiten-Reload ausgeblendet werden.
* Die Ghettobox steht immer direkt unterhalb des [Header](https://digital.sbb.ch/de/websites/modules/header).
* Die Ghettobox ist nicht sticky sondern scrollt mit dem Inhalt weg.
* Der Text kann mehrzeilig sein.
* Vor dem Text steht immer ein [Icon](https://digital.sbb.ch/de/brand_elemente/icons) in roter Fläche (HIM/CUS-Icons).
* Wenn mehrere Ghettoboxen gleichzeitig verwendet werden, sind diese untereinander anzuordnen.

## 4. Ausprägungen und Zustände
### 4.1 Standard
![Darstellung der Komponente Ghettobox in der Ausprägung Standard](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/ghettobox/images/ghettobox_default.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/34xd8m#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/alert?variant=standard)

### 4.2 Link
Diese Ausprägung hat folgende Zustände:
* Default
* Hover

![Darstellung der Komponente Ghettobox mit Link](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/ghettobox/images/ghettobox_link.png 'class: image')
* Sofern der Text einen weiterführenden [Link](https://digital.sbb.ch/de/components/link) beinhaltet, unterscheidet die Ghettobox die Zustände Normal und Hover.
* Am Ende des Textes folgt immer ein Pfeil-Icon.
* Die ganze Fläche der Ghettobox ist klickbar und öffnet den hinterlegten Link (ausser über dem X-Icon).

#### Design Spezifikation
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/rvrLaA#Inspector)
* [Hover](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/ndDYzl#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/alert?variant=standard)