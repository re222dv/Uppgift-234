# Kravspecifikation Medlemsregister
### Referenser
[Vision Medlemsregister](vision.md#vision-medlemsregister)
Här beskrivs bakgrund, användargrupper och baskrav.

## Aktörer
### Primära Aktörer
#### Medlem
Vill enkelt och smidigt kunna se möten, uppdatera sin info och boka båtplatser.

#### Styrelsemedlem
Vill kunna uppdatera klubbens kalender samt skicka ut information till klubbens medlemmar.

#### Kassör
Vill kunna se vilka medlemmar som betalat medlemsavgift och hur mycket. Vill se klubbens alla fakturor.

#### Sekreterare
Vill kunna se vilka medlemmar som har vilka båtplatser och flytta om eller ta bort dessa.

### Stödjande Aktörer
#### Nationellt båtregister
Ett externt system som behöver användas för att hämta information om medlemmarnas båtar.

#### Bankgirot
Ett externt system som behöver användas vid betalning och fakturering.

### Offstage Aktörer
#### Befintligt medlemsregister
Det befintliga medlemsregistret har flera problem. Dess brister måste tas i beaktande så att de kan undvikas i så stor grad som möjligt.

## Funktionella Krav
#### F1 Inloggning
Medlemmar måste logga in för att komma åt och ändra information.

### Användningsfall

#### Medlem
AF1.1 Kontrollera när nästa möte är

AF1.2 CRUD en båt

AF1.3 Ändra sin kontaktinfo

AF1.4 Boka en båtplats


#### Styrelsemedlem
AF2.1 CRUD ett möte

AF2.2 Skicka ut information


#### Kassör
AF3.1 Kontrollera att korrekt betalning är gjord

AF3.2 Kontrollera att faktura skickats ut till en medlem


#### Sekreterare
AF4.1 Byta plats på en medlems båt


## Ickefunktionella Krav