## 1. Was macht das Modul?
* Sammeln der Kontaktinformationen eines Benutzers.

## 2. Wann soll das Modul eingesetzt werden?
* Registrierung
* Kauf
* Sonstige Kontaktaufnahme seitens Benutzer
* Ist der Benutzer bereits eingeloggt, so sollten diese Informationen aus dem Account gezogen werden.

## 3. Regeln 
* Für Kontakt-/Adressangaben steht ein standardisierter Block zur Verfügung. Dieser enthält folgende Felder:

    1.  Anrede ([Radio-Button](WE21---Radiobutton_30824096.html) Herr/Frau)
    2.  Vorname ([Eingabefeld](WE15---Eingabefeld_30823990.html))
    3.  Nachname ([Eingabefeld](WE15---Eingabefeld_30823990.html))
    4.  Firma ([Eingabefeld](WE15---Eingabefeld_30823990.html), optional)
    5.  Strasse ([Eingabefeld](WE15---Eingabefeld_30823990.html))
    6.  Nr. ([Eingabefeld](WE15---Eingabefeld_30823990.html), kurz)
    7.  Adresszusatz ([Eingabefeld](WE15---Eingabefeld_30823990.html), optional)
    8.  PLZ ([Eingabefeld](WE15---Eingabefeld_30823990.html), kurz, nur Zahlen erlaubt, max. Länge 5)
    9.  Ort ([Eingabefeld](WE15---Eingabefeld_30823990.html))
    10. Land ([Select](WE18---Select_30824011.html), Schweiz vorausgewählt, danach Deutschland, Frankreich, Italien, Österreich, danach alle Länder alphabetisch)
    11. E-Mail ([Eingabefeld](WE15---Eingabefeld_30823990.html), E-Mail-Validierung)
    12. Telefon ([Eingabefeld](WE15---Eingabefeld_30823990.html), Tel-Nr.-Validierung)

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
* [Radio-Buttons](WE21---Radiobutton_30824096.html) mit Auswahl identischer Lieferadresse
### 4.8 Rechnungs- und Lieferadresse abweichend 
* [Radio-Buttons](WE21---Radiobutton_30824096.html) mit Auswahl abweichender Lieferadresse