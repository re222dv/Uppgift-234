# AF2.1 CRUD ett möte
En styrelsemedlem vill CRUD ett möte och väljer att öppna klubbkalendern. Systemet presenterar kalendern samt val för att CRUD ett möte. En medlem vill kunna visa års och medlemsmöten.

## Primära Aktörer
[Styrelsemedlem](kravspecifikation.md#styrelsemedlem), 
[Medlem](kravspecifikation.md#medlem)

## Förkrav
Inloggad (F1) som Styrelsemedlem eller medlem.

## Efterkrav
Medlemmarnas kalendrar uppdateras för att matcha de nya ändringarna.

## Huvudscenario
1. Startar när Styrelsemedlem vill CRUD ett möte
2. Styrelsemedlemmen väljer att visa klubbkalendern
3. Systemet presenterar klubbkalendern och ber om önskad åtgärd
4. Styrelsemedlemmen väljer att skapa ett möte
5. Systemet presenterar lediga tider och ett formulär
6. Styrelsemedlemmen fyller i mötesbeskrivning, väljer tid och vilka som ska kallas till mötet
7. Systemet skapar mötet och bekräftar

## Alternativa Scenarion
###2a. Medlem väljer att visa klubbkalendern
1. Systemet presenterar klubbkalendern med styrelsemöten filtrerade.

*Scenariot avslutas*

###4a. Styrelsemedlemmen väljer att visa ett möte
1. Systemet presenterar detaljerad information om mötet

*Scenariot avslutas*

###4b. Styrelsemedlemmen väljer att uppdatera ett möte
1. Systemet presenterar detaljerad information om mötet
2. Styrelsemedlemmen ändrar informationen
3. Systemet sparar ändringarna och bekräftar

*Scenariot avslutas*

###4c. Styrelsemedlemmen väljer att radera ett möte
1. Systemet tar bort mötet och bekräftar

*scenariot avslutas*
