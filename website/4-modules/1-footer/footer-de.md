## 1. Was macht die Komponente?
-   Bietet dem Benutzer allgemeine Informationen zur Webseite / Anwendung.e

## 2. Wann soll die Komponente eingesetzt werden?
-   Ein Footer ist bei jeder Webseite / jeder Anwendung einzufügen.

## 3. Regeln
-   Der 4-spaltige Rich Footer hat folgende Bereiche:
    -   Kontakt
    -   Bahnverkehrsinformationen (auf (link: http://sbb.ch text: sbb.ch) oder Microsite-/Anwendungs-spezifische Informationen
    -   Newsletter & Social Media
    -   Über die SBB
-   Weitere Elemente im Footer sind:
    -   Uhr-Modul
    -   Sprachwahl
    -   Links zu Impressum, Rechtliche Hinweise, Datenschutz
-   Mittels Klick auf die Uhr wird sie ganzflächig in einer (link: websites/components/lightbox text: Lightbox) angezeigt.

## 4. Ausprägungen und Zustände
### 4.1 Standard
(srcset: footer_default extension: png class: image)
-   Der Bereich Kontakt enthält ein Dropdown mit div. Kontaktoptionen. Gibt es nur eine Kontaktinformation (keine Auswahl), so wird diese direkt gezeigt.
-   Je nach Länge des Kontaktinhalts verändert sich die Höhe des Footers.
-   Die zweite Spalte enthält die Bahnverkehrsinformationen.
-   In der dritten Spalte stehen Informationen zu Newsletter & Social Media:
    -   Informationstext zum Newsletter mit (link: websites/components/link text: Link) zur Anmeldung
    -   Externe Social Media Plattformen (Links zu den SBB-Auftritten auf div. Social Media Plattformen)
    -   Optional interne Social Media Plattformen (z.B. Links zum SBB Blog (Bezeichnung «SBB Stories»)  und der SBB Community).
-   Die letzte Spalte beinhaltet Links zu ausgewählten SBB-Inhalten. Diese sind je nach Kontext zu definieren.

#### Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/326985471/inspect text: Default)

### 4.2 Microsite mit einem Kontakt
(srcset: footer_microsite_single_contact extension: png class: image)
-   Der Bereich Kontakt hat genau eine Kontaktinformation.
-   Die zweite Spalte enthält Microsite-spezifische Informationen.

#### Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/326985472/inspect text: Default)

### 4.3 Microsite mit mehreren Kontakten
(srcset: footer_microsite_multi_contact extension: png class: image)
-   Die zweite Spalte enthält Microsite-spezifische Informationen.

#### Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/326985473/inspect text: Default)

### 4.4 Microsite mit eigenem Logo
(srcset: footer_microsite_logo extension: png class: image)
-   Darf nur eingesetzt werden, wenn gleichzeitig auf der Seite der «Header mit eigenem Logo» eingesetzt wird.
-   Der Bereich Kontakt hat genau eine Kontaktadresse.
-   Die zweite Spalte enthält Microsite-spezifische Informationen.
-   Das SBB-Logo ist mit (link: http://sbb.ch text: sbb.ch) verlinkt.

#### Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/326985474/inspect text: Default)