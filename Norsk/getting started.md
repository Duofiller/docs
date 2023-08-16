---
order: 108
---

# Kom i gang 

Dette er en guide for både Mono og Duofiller. 

- Plasser en dryppskål under fylleren. Bruk alltid dryppskål for å samle opp søl under fylleren. 
- Pass på at fylleren er koblet til fatet med kaldt vann og at trykket I fatet er cirka 1 bar.  
- Fest CO2 til fylleren og pass på at CO2-presset er under 3psi/0,2bar. 
- Skru på fylleren ved å plugge strømforsyningen i stikkontakten. 

Første gang fylleren starter opp vil LED-lyset lyse grønt. Dette indikerer at fylleren er I Timer Mode. Første gang den brukes vil vi ha den i sensor mode for å kalibrere og en funksjonstest. Hold trykk-knappen i to sekunder og slipp. LED-lyset vil gå over til blått, som indikerer at den er i sensormodus. (Hvis lyset begynner å blinke grønt har du holdt knappen for lenge. Hold knappen i 4-5 sekunder for å få den tilbake i timermodus; prøv å sett den i sensormodus igjen).

## Sensor programmeringsmodus
Når du er i sensormodus holder du knappen i 4 sekunder og slipper. LED-lyset skal da blinke blått. Dette indikerer at fylleren er i sensor programmeringsmodus. 
For å programmere fylleren vil vi starte en fylling og stoppe denne på ønsket nivå. Sett et glass eller boks under fylleren og start en fylling ved å trykke på knappen. Fyllesekvensen begynner først med en purge, og bytter deretter over til fylling. Følg med på fyllingsnivået. Når ønskelig nivå er nådd trykker du på knappen og fyllingen stopper. LED-lyset bytter til grønt, som betyr at fyllenivået er lagret. Fyllenivået vil ikke bli lagret hvis fyllenivået er under 25mm. Hvis fyllenivået ikke blir lagret, vil lyset blinke rødt og den blir værende i programmeringsmodus. Når fyllenivået lagres vil den automatisk hoppe tilbake til sensormodus etter at boksen er fjernet.

Start en ny fylling, og den vil stoppe på det lagrede nivået.  

Gå tilbake til sensor programmeringsmodus og gjenta dette flere ganger til du er kjent med programmeringen.  

Hvis du har Duofilter gjør du det same for det andre hodet. 

## Timer programmeringsmodus
Gå tilbake til timermodus (hold knappen I 2 sekunder og slipp). Lampen skal lyse grønt. Når du er i timermodus holder du knappen i 4-5 sekunder og slipper for å komme til programmering av timermodus. Lyset skal da begynne å blinke grønt, som indikerer at den er i timer programmeringsmodus. Bruk glass, boks, eller flaske for å fullføre prorammeringen. Programmering blir gjort på akkurat same måte som i sensormodus.  

Start en fylling og verifiser at den stopper på det programmerte nivået. 

Siden timermodus måler tid brukt for å fylle opp til riktig nivå er det viktig å tenke over dette før fyllingnivå er programmert. Sett fatet under trykk, flush ut luft osv, før du programmerer den i timer mode. 

## Førstegangsrens
1. Skyll gjennom fylleren med lunkent vann, med vaskemiddel. Start en fylling i timer programmeringsmodus for å gjøre dette. Ventilen vil da bli stående åpen til dette manuelt blir endret. For førstegangsrensing anbefaler vi PBW eller oppvaskmiddel, og skyll i 10 minutter.
2. Skyll gjennom med næringsmiddelgodkjent, syrebasert rensemiddel for tappeutstyr (vi anbefaler StarSan, SureSan eller lignende). Kontakttiden skal være på 3 minutter eller mer.
3. Spray forsiktig med en sprayflaske eller dynk utsiden av det rustfrie stålrøret med syrebasert rensemiddel. Bruk briller. Kontakttiden er på 3 minutter. 

## Væskefylling
Etter at det er rengjort for først gang er fylleren klar til å brukes. Koble den til et fat med drikkevare. Gjenta fyllingsnivå programmering. Forvent ikke at det programmerte nivået med vann blir likt som en annen drikkevare. Mange faktorer spiller inn; i sensormodus blir resultatet påvirket av SG, kullsyre, mengde bobler, og flow. I timermodus blir fyllenivået for det meste påvirket av trykk i fatet. Hvis du har stabilt trykk i fatet vil timermodus være den mest presise fyllemodusen. Hvis du opplever variasjon i fyllenivået i timermodus kan du bytte til sensormodus.

## Rensetidprogrammering
Default, anbefalt og fabrikkinnstilt purgetid er 6 sekunder. Hvis du ønsker å endre purgetiden må du være i enten sensor- eller timermodus. Hold inne knappen i mer enn 6 sekunder og slipp. LED-lyset vil slukke, som indikerer at den er i purgetid-programmeringsmodus. Når du er i purgetid-programmering vil et kort trykk på knappen øke purgetiden med 1 sekund. For hvert steg vil lyse blinke rødt. Når purgetiden er 5 sekunder vil lyset blinke grønt istedenfor rødt. Når den er på 10 sekunder vil neste steg være 0 sekunder. Når du er på 0 sekunder vil lyset blinke blått. (0 sekunder = purge deaktivert) hold knappen mer enn 6 sekunder og slipp for å gå ut av purgetid-programmeringmodus.

Hvis du har Duofilleren vil purgetid bli programmert individuelt for hvert fyllehode. 

Purgetiden er satt globalt for både timermodus og sensormodus. For timermodus kan purge kan bli skrudd av, men for sensormodus er det anbefalt å bruke minst 1 sekund for å forsikre om at CO2 røret er tomt for væske etter hver fyllesekvens. 

## Web interface
Default, for hver oppstart vil fylleren starte et trådløst nettverk (AP) med **SSID “Duofiller” og passord “duofiller”**. Bruk en telefon, nettbrett eller pc, og koble til nettverket "Duofiller". Når du er tilkoblet oppkobling skal du skrive inn http://192.168.4.1 eller http://duofiller.local i nettleserens adressefelt. Du vil da bli tatt til webinterfacen. Her kan du endre fyllenivået for sensormodus, fylletid for timermodus og purgetid. Det er også mulig å se hvor mange fyllinger som er gjort totalt.  

Fyllingstimer for timermodus kan bli satt til millisekunder og fyllenivået for sensormodus kan bli satt til millimeter. Merk at dette er ment for å finjustere allerede eksisterende innstillinger, som er programmert med knappene. Vil du endre fyllenivået med f.eks 1-2-5-10mm opp eller ned gjøres det enklest med webinterfacet i stedet for å gjøre en ny programmering.

I tilkoblingsmenyen kan du skrive inn ditt hjemmenettverk (wifi) SSID og password. Etter omstart vil fylleren koble seg til ditt nettverk og du kan kontrollere den med en pc eller telefon som er tilkoblet hjemmenettverket. Du kan finne webinterfacet ved å skrive adressen: http://duofiller.local eller IP adressen den har fått tildelt av routeren din. En kan finne IP-adressen enten ved å bruke en nettverkscanner (se etter enhet “Duofiller” eller noen ganger «espressif» eller logg inn på ruteren og finner fylleren i "DHCP lease" listen. 

Du kan endre hver enkelt fyller sin SSID og passord. For f.eks å skille mellom flere fyllere gi de forksjellige SSIDer. Hostnavnet vil også være det samme som SSID. For eksempel kan du, hvis du har flere Duofillere, endre SSID til «Duofiller1», «Duofiller2» osv. Koble til de forskjellige ved å koble til Duofiller1.local, Duofiller2.local osv. 

Webinterfacen har også en “skru av wifi” mulighet. Fylleren fungerer godt uten wifi, så hvis du ikke benytter deg av wifi kan du enkelt skru av dette valget. For å skru den på igjen kan du resette nettverkinnstillingene. 


## Tilbakestilling til fabrikkinnstillinger

**Ta strømmen til av fylleren, hold inne knappen og skru på mens du holder knappen nede:**

Mens den starter opp, fortsett å holde inne knappen. Hold knappen nede i 5 sekunder og slipp for å resette nettverkinnstillinger. 5 sekunder indikeres med blått lys. 

Hold knappen i 10 sekunder og slipp for å resette alle innstillinger til fabrikkinnstillinger. 10 sekunder indikeres med et rødt lys.  



### Detaljer

For detaljer kan du se vår quick reference :icon-arrow-down: [!ref Quick Reference](/quickreference.md)
