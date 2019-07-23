##1. Was macht das Modul?
* Dient zur Darstellung von Detailinformationen einer Content-Seite.

##2. Wann soll das Modul eingesetzt werden?
* Wenn zu einem Teil einer Seite on-demand detailliertere oder zusätzliche Informationen angezeigt werden soll (beispielsweise erweiterte Hilfestellungen, bei denen der Tooltip nicht ausreicht).
* Zur Darstellung des Editiermodus bei Formularen.
* Zur vergrösserten Ansicht von Bildern.

##3. Regeln
* Die referenzierte Seite wird nicht verlassen.
* Die Lightbox öffnet sich immer Browserfenster-füllend.
* Die Lightbox hat einen eigenen Header, welcher immer sticky ist.
* Im Header dürfen kontextbeschreibende Informationen stehen (beispielsweise die Zug-Nummer).
* Der Inhalt der Lightbox kann im Rahmen des Grunddesigns gestaltet werden.

##4. Ausprägungen und Zustände
###4.1 Standard
(srcset: lightbox_default extension: png class: image)

####Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/344969031/inspect text: Default)

####Code Spezifikation
* (link: https://sbb-angular.app.sbb.ch/latest/content/lightbox text: SBB Angular Component Library)

###4.2 Mit Formularkomponenten
(srcset: lightbox_form extension: png class: image)
* Eine Lightbox mit Formularelementen erhält mindestens einen «Abbrechen» und einen «Übernehmen» Button.
* Der «Abbrechen» Button schliesst die Lightbox wieder.
* Wird die Lightbox geschlossen («Abbrechen» oder X-Button) während bereits Eingaben im Formular geändert wurden, erscheint ein Warnhinweis das ungesicherte Daten im Formular sind.
* Die Buttons eines Formulars («Abbrechen», «Übernehmen», andere Funktionen) dürfen im Footer eingesetzt werden.
* Der Footer ist immer sticky und wird über die ganze Breite der Lightbox dargestellt (gleich wie Header).

####Design Spezifikation
*   (link: https://sbb.invisionapp.com/d/main#/console/15744722/344969032/inspect text: Default)

####Code Spezifikation
* (link: https://sbb-angular.app.sbb.ch/latest/content/lightbox text: SBB Angular Component Library)