

<u>**Swot analyz**</u>:  <u>av VM mot fysisk maskin</u>

* Styrkor
  * Man kan ha flera VM på en maskin som kan arbeta individuellt.

* Svagheter
  * Det kan vara långsammare då man måste dela på den fysiska hårdvaran.
* Möjligheter 
  * de är endast begränsade med hur mycket utrymme och prestanda den fysiska maskinen har.  
* Risker
  * En VM som finns på molnet medför risken att någon annan kan komma åt den.



<u>**Azure CLI**</u> 

Först så skapade vi en resurs grupp sedan skapade vi VM:en i resurs gruppen sen fick vi öppnat port 80 och anslöt till våran VM. Installerade .NET-core , SDK och RunTime. Efter clonade vi ner Stephans Project och körde .net run.



**<u>Pulumilösning</u>** 

Vi laddade ner exempel repot  på https://github.com/pulumi/examples och installerade även pulumi. I powershell går man sedan till mappen azure-cs-webserver i den får man skriva kommandot az login och logga in med sitt Learnet-konto. När man loggat in så skriver man kommandot pulumi config set azure:location northeurope  sedan får man skapa en stack. För att deploya sin stack skriver man kommandot pulumi  up. Först får man ansluta till sin pulumi VM och sen får man öppna port 80 och installerade .NET-core , SDK och RunTime. Efter clonade vi ner Stephans Project och körde .net run.

