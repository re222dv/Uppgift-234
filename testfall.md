# Testfall Medlemsregister
## TF [AF2.1 Huvudscenario - Skapa ett möte](AF2.1 CRUD ett möte.md#af21-crud-ett-möte)
I detta testfall är målet att undersöka så att [Styrelsemedlem](kravspecifikation.md#styrelsemedlem) enkelt kan skapa ett möte.

### Förkrav
Initiera testmiljöns databas. Gå till test.dgp.se och logga in med Användarnamn: Styrelsen Lösenord: password

### Efterkrav
Kontrollera att ett nytt möte mellan 17:00 och 18:30 den 2014-7-21 är skapat i databasen. Kontrollera att mötet syns i alla medlemmars kalendrar.

### Scenario
1. Välj "Kalender":"Skapa ett möte"
2. Mata in Mötesnamn "Testmöte" och mötesbeskrivning "Ett möte för att testa att möten kan skapas"
3. Tre förslag på mötestider visas 2014-7-14, 2014-7-21 och 2014-7-28 alla mellan 17:00 och 18:30
4. Välj det föreslagna datumet 2014-7-21, ändra inte den föreslagna tiden för mötet
5. Mötestyper presenteras "Styrelsemöte" och "Medlemsmöte"
6. Välj "Medlemsmöte" och klicka på "Skapa möte"
7. Kalendern visas, kontrollera att mötet är skapad på rätt dag med rätt tid och med rätt namn samt beskrivning

## TF [AF2.1 4a - Visa ett möte som Styrelsemedlem](AF2.1 CRUD ett möte.md#4a-styrelsemedlemmen-väljer-att-visa-ett-möte)
I detta testfall är målet att undersöka så att [Styrelsemedlem](kravspecifikation.md#styrelsemedlem) kan visa alla möten.

### Förkrav
Initiera testmiljöns databas. Gå till test.dgp.se och logga in med Användarnamn: Styrelsen Lösenord: password

### Scenario
1. Välj "Kalender"
2. Kontrollera att två möten syns

## TF [AF2.1 4a - Visa ett möte som Medlem](AF2.1 CRUD ett möte.md#4a-styrelsemedlemmen-väljer-att-visa-ett-möte)
I detta testfall är målet att undersöka så att [Medlem](kravspecifikation.md#medlem) bara kan visa medlemsmöten.

### Förkrav
Initiera testmiljöns databas. Gå till test.dgp.se och logga in med Användarnamn: Medlem Lösenord: password

### Scenario
1. Välj "Kalender"
2. Kontrollera att ett möte syns

## TF [AF2.1 4b - Uppdatera ett möte](AF2.1 CRUD ett möte.md#4b-styrelsemedlemmen-väljer-att-uppdatera-ett-möte)
I detta testfall är målet att undersöka så att [Styrelsemedlem](kravspecifikation.md#styrelsemedlem) enkelt kan uppdatera ett möte.

### Förkrav
Initiera testmiljöns databas. Gå till test.dgp.se och logga in med Användarnamn: Styrelsen Lösenord: password

### Efterkrav
Kontrollera att ett möte är uppdaterat från den 2014-6-16 till den 2014-6-23 i databasen. Kontrollera att mötet syns med korrekt info i alla medlemmars kalendrar.

### Scenario
1. Välj "Kalender"
2. Öppna möte "Styrelsemöte" den 2014-6-16
4. Ändra datumet för mötet till den 2014-6-23 och klicka på "Uppdatera möte"
7. Kalendern visas, kontrollera att mötet nu visas korrekt på det nya datumet

## TF [AF2.1 4c - Radera ett möte](AF2.1 CRUD ett möte.md#4c-styrelsemedlemmen-väljer-att-radera-ett-möte)
I detta testfall är målet att undersöka så att [Styrelsemedlem](kravspecifikation.md#styrelsemedlem) enkelt kan radera ett möte.

### Förkrav
Initiera testmiljöns databas. Gå till test.dgp.se och logga in med Användarnamn: Styrelsen Lösenord: password

### Efterkrav
Kontrollera att ett mötet från den 2014-5-12 inte längre finns i databasen eller i medlemmarnas kalendrar.

### Scenario
1. Välj "Kalender"
2. Öppna möte "Medlemsmöte" den 2014-5-12 och klicka på "Radera möte"
7. Kalendern visas, kontrollera att mötet inte längre visas
