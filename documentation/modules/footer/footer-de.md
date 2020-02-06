## 1. Was macht das Modul?
Bietet dem Benutzer allgemeine Informationen zur Webseite / Anwendung.

## 2. Wann soll das Modul eingesetzt werden?
Ein Footer ist bei jeder Webseite / jeder Anwendung einzufügen.

## 3. Regeln
* Der 4-spaltige Rich Footer hat folgende Bereiche:
    * Kontakt.
    * Bahnverkehrsinformationen (auf [sbb.ch](https://sbb.ch) oder Microsite-/Anwendungs-spezifische Informationen.
    * Newsletter & Social Media.
    * Über die SBB.
* Weitere Elemente im Footer sind:
    * Uhr-Modul.
    * Sprachwahl.
    * Links zu Impressum, Rechtliche Hinweise, Datenschutz.
* Mittels Klick auf die Uhr wird sie ganzflächig in einer [Lightbox](https://digital.sbb.ch/de/websites/components/lightbox) angezeigt.

## 4. Ausprägungen und Zustände
### 4.1 Standard
![Darstellung des Moduls Footer in der Ausprägung Standard](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/modules/footer/images/footer_default.png 'class: image')
* Der Bereich Kontakt enthält ein Dropdown mit div. Kontaktoptionen. Gibt es nur eine Kontaktinformation (keine Auswahl), so wird diese direkt gezeigt.
* Je nach Länge des Kontaktinhalts verändert sich die Höhe des Footers.
* Die zweite Spalte enthält die Bahnverkehrsinformationen.
* In der dritten Spalte stehen Informationen zu Newsletter & Social Media:
    * Informationstext zum Newsletter mit [Link](https://digital.sbb.ch/de/websites/components/link) zur Anmeldung.
    * Externe Social Media Plattformen (Links zu den SBB-Auftritten auf div. Social Media Plattformen)
    * Optional interne Social Media Plattformen (z.B. Links zum SBB Blog (Bezeichnung «SBB Stories»)  und der SBB Community).
* Die letzte Spalte beinhaltet Links zu ausgewählten SBB-Inhalten. Diese sind je nach Kontext zu definieren.

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/326985471/inspect)

### 4.2 Microsite mit einem Kontakt
![Darstellung des Moduls Footer für Microsites mit einem Kontakt](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/modules/footer/images/footer_microsite_single_contact.png 'class: image')
* Der Bereich Kontakt hat genau eine Kontaktinformation.
* Die zweite Spalte enthält Microsite-spezifische Informationen.

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/326985472/inspect)

### 4.3 Microsite mit mehreren Kontakten
![Darstellung des Moduls Footer für Microsites mit mehreren Kontakten](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/modules/footer/images/footer_microsite_multi_contact.png 'class: image')
* Die zweite Spalte enthält Microsite-spezifische Informationen.

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/326985473/inspect)

### 4.4 Microsite mit eigenem Logo
![Darstellung des Moduls Footer für Microsites mit eigenem Logo](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/modules/footer/images/footer_microsite_logo.png 'class: image')
* Darf nur eingesetzt werden, wenn gleichzeitig auf der Seite der «Header mit eigenem Logo» eingesetzt wird.
* Der Bereich Kontakt hat genau eine Kontaktadresse.
* Die zweite Spalte enthält Microsite-spezifische Informationen.
* Das SBB-Logo ist mit [sbb.ch](https://sbb.ch) verlinkt.

#### Design Spezifikation
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/326985474/inspect)