# Automatisering av bygg och release

## Del 1 CI pipeline i Azure DevOps

De första vi behöver göra är att skapa ett projekt i Visualstudio(eller så kan du klona ner https://github.com/skjohansen/SimpleWebHalloWorld.git). Skapa sen ett enhets test projekt i samma map som dit vanliga projekt. Nästa steg är att skapa ett eller flera enhets tester. Efter vi gjort färdigt dessa steg kan vi skapa ett Azure DevOps konto om man inte redan har det. När du har kommit in på DevOps så får vi skapa en organisation.  Nu så ska vi skapa en Pipline detta gör du genom att klicka först på pipelines till vänster sida av hemsidan sedan klickar du på Create pipline. Du kommer nu få frågan vart någonstans din kod ligger välj då antingen Azure repos eller Github. Nu får du välja ditt repository som du ska skapa en pipeline med. När du kommer till konfiguration delen så ska du välja  starter pipeline och klicka sedan på show assistant, i assistant sök och lägg till visual studio test. där det står test files kan du behöva skriva in din sökväg till test.csproj beroende på hur ditt projekt är uppbyggt. nu ska din pipeline fungera att bygga så nu kan du trycka på save and run. Den ska även bygga din pipeline varje gång du pushar något till master. 

 

