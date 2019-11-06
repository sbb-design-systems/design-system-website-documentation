## 1. Was macht das Modul?
Sammeln der Kontaktinformationen eines Benutzers.

## 2. Wann soll das Modul eingesetzt werden?
* Registrierung.
* Kauf.
* Sonstige Kontaktaufnahme seitens Benutzer.
* Ist der Benutzer bereits eingeloggt, so sollten diese Informationen aus dem Account gezogen werden.

## 3. Regeln 
Für Kontakt-/Adressangaben steht ein standardisierter Block zur Verfügung. Dieser enthält folgende Felder:
1.  Anrede ([Radiobutton](https://digital.sbb.ch/de/components/radiobutton) Herr/Frau)
2.  Vorname ([Eingabefeld](https://digital.sbb.ch/de/components/textfield))
3.  Nachname ([Eingabefeld](https://digital.sbb.ch/de/components/textfield))
4.  Firma ([Eingabefeld](https://digital.sbb.ch/de/components/textfield), optional)
5.  Strasse ([Eingabefeld](https://digital.sbb.ch/de/components/textfield))
6.  Nr. ([Eingabefeld](https://digital.sbb.ch/de/components/textfield), kurz)
7.  Adresszusatz ([Eingabefeld](https://digital.sbb.ch/de/components/textfield), optional)
8.  PLZ ([Eingabefeld](https://digital.sbb.ch/de/components/textfield), kurz, nur Zahlen erlaubt, max. Länge 5)
9.  Ort ([Eingabefeld](Whttps://digital.sbb.ch/de/components/textfield))
10. Land ([Select](https://digital.sbb.ch/de/components/select), Schweiz vorausgewählt, danach Deutschland, Frankreich, Italien, Österreich, danach alle Länder alphabetisch)
11. E-Mail ([Eingabefeld](https://digital.sbb.ch/de/components/textfield), E-Mail-Validierung)
12. Telefon ([Eingabefeld](https://digital.sbb.ch/de/components/textfield), Tel-Nr.-Validierung)

## 4. Ausprägungen und Zustände
Das Modul hat folgende Zustände:
* Valid
* Invalid

### 4.1 Kontakt 
### 4.2 Kontakt und Firma
### 4.3 Kontakt, Firma und Adresse 
### 4.4 Kontakt, Firma, Adresse und E-Mail 
### 4.5 Kontakt, Firma, Adresse und Telefon
### 4.6 Kontakt, Firma, Adresse, E-Mail und Telefon 
### 4.7 Rechnungs- und Lieferadresse identisch
* [Radiobuttons](https://digital.sbb.ch/de/components/radiobutton) mit Auswahl identischer Lieferadresse

### 4.8 Rechnungs- und Lieferadresse abweichend 
* [Radiobuttons](https://digital.sbb.ch/de/components/radiobutton) mit Auswahl abweichender Lieferadresse