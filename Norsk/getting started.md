---
order: 108
---

# Kom i gang

Denne guiden gjelder både Mono og Duofiller.

- Plasser en dryppbrett under boksfylleren. Bruk alltid dryppbrett for å samle opp søl under boksfylleren.
- Pass på at boksfylleren er koblet til et fat med kaldt vann, og at fattrykket er ca. 1 bar.
- Koble CO~2~ til boksfylleren og sørg for at CO~2~-trykket er under 3 psi / 0,2 bar.
- Slå på boksfylleren ved å koble strømforsyningen til stikkontakten.

Når boksfylleren starter opp første gang vil LED-en lyse grønt. Det indikerer at boksfylleren er i Timermodus. Ved førstegangs bruk vil vi ha den i Sensormodus for kalibrering og funksjonstest. Hold inne trykknappen i 2 sekunder og slipp. LED-en skal skifte til konstant blå, som indikerer at den er i Sensormodus. (Hvis LED-en i stedet begynner å blinke grønt, har du sannsynligvis holdt knappen for lenge. Hold knappen i 4–5 sekunder og slipp så bør den være tilbake i Timermodus; forsøk så å sette den i Sensormodus igjen.)

## Programmering av fyllenivå i Sensormodus
Når du er i Sensormodus, hold inne knappen i 4 sekunder og slipp. LED-en begynner å blinke blått. Det indikerer at boksfylleren er i programmeringsmodus for Sensormodus.
For å programmere fylleren starter vi en fylling og stopper den på ønsket fyllenivå. Sett et glass eller en boks under fyllehodet og start en fylling ved å trykke på trykknappen. Fyllesekvensen starter med purge og bytter deretter til selve fyllingen. Følg med på fyllenivået. Når ønsket nivå er nådd, gi knappen et kort trykk så stopper fyllingen. LED-en blir grønn, som betyr at fyllenivået er lagret. Fyllenivået lagres ikke hvis det er satt til 25 mm eller mindre. Hvis fyllenivået ikke blir lagret, blinker LED-en rødt og forblir i programmeringsmodus. Ved vellykket lagring hopper boksfylleren automatisk tilbake til Sensormodus etter at boksen er fjernet.

Start en ny fylling, og den vil stoppe på det lagrede fyllenivået.

Gå tilbake til programmeringsmodus for Sensormodus og gjenta noen ganger til du er kjent med programmeringen.

Hvis du har Duofiller, gjør det samme for det andre fyllehodet.

## Programmering av fyllenivå i Timermodus
Gå tilbake til Timermodus (hold inne knappen i 2 sekunder og slipp). Når du er i Timermodus, hold knappen inne i 4–5 sekunder og slipp for å gå til programmering av fyllenivå i Timermodus. Den grønne LED-en begynner å blinke, som indikerer at programmering av fyllenivå i Timermodus er aktiv. Bruk et glass, en boks eller en flaske til programmeringen. Programmeringen gjøres på nøyaktig samme måte som i Sensormodus. Start en fylling og stopp den ved ønsket fyllenivå. Den eneste forskjellen er at boksfylleren ved vellykket lagring ikke automatisk går tilbake til Timermodus. For å gå tilbake til Timermodus, hold inne trykknappen i 4–5 sekunder og slipp.

Start en fylling og verifiser at den stopper på det programmerte fyllenivået.

Siden Timermodus måler nøyaktig tiden som brukes til å fylle til ønsket fyllenivå, er det viktig å ha dette i bakhodet før fyllenivået programmeres. Sett fattrykket, skyll/fyll fylleslangene osv. før Timermodus-programmeringen gjøres.

## Førstegangsrens
1. Skyll gjennom boksfylleren med lunkent vann og vaskemiddel. Start en fylling i programmeringsmodus for Timermodus for å skylle — fylleventilen står da åpen til den manuelt avbrytes. Ved førstegangsrens anbefaler vi PBW eller oppvaskmiddel (i anbefalt konsentrasjon) og 10 minutters skylling.
2. Skyll gjennom med et næringsmiddelgodkjent, syrebasert desinfeksjonsmiddel for bryggeriutstyr (vi anbefaler StarSan, SureSan eller tilsvarende) i anbefalt konsentrasjon. Kontakttid 3 minutter eller mer.
3. Spray forsiktig (med en sprayflaske) eller dynk utsiden av de rustfrie fyllerørene med syrebasert desinfeksjonsmiddel. Bruk vernebriller. Kontakttid 3 minutter.

## Fylling med drikke
Etter førstegangsrens er boksfylleren klar til bruk. Koble til et fat med drikke. Gjenta kalibreringen av fyllenivået med drikken. Forvent ikke at fyllenivået programmert med vann blir likt det faktiske fyllenivået med drikken. Mange faktorer spiller inn: i Sensormodus påvirkes fyllenivået av SG, karboneringsnivå (mengden bobler) og flow. I Timermodus påvirkes fyllenivået hovedsakelig av fattrykk og drikkens viskositet. Med stabilt fattrykk vil Timermodus være den mest nøyaktige modusen. Hvis du opplever inkonsekvent fyllenivå i Timermodus, bytt til Sensormodus.

## Programmering av purgetid
Standard, anbefalt og fabrikkinnstilt purgetid er 6 sekunder. Hvis du vil endre purgetiden: pass på at du er i Sensormodus eller Timermodus. Hold inne trykknappen i mer enn 6 sekunder og slipp. LED-en slukker, som indikerer at den er i programmeringsmodus for purgetid. I denne modusen øker hvert korte trykk på knappen purgetiden med +1 sekund. For hvert steg blinker LED-en rødt. Når purgetiden er 5 sekunder blinker LED-en grønt i stedet for rødt. Når den står på 10 sekunder vil neste steg være 0 sekunder. Ved 0 sekunder blinker LED-en blått (0 sekunder = purge deaktivert). Hold inne knappen i mer enn 6 sekunder og slipp for å gå ut av programmeringsmodus for purgetid.

Hvis du har Duofiller, settes purgetiden individuelt for hvert fyllehode.

Purgetid er satt globalt for både Timermodus og Sensormodus. For Timermodus kan purge deaktiveres, men for Sensormodus anbefales minst 1 sekunds purgetid for å sikre at CO~2~-røret er fri for væske før hver fyllesekvens.

## Webgrensesnitt
Som standard starter boksfylleren ved hver oppstart et trådløst aksesspunkt (AP) med **SSID "Duofiller" og passord "duofiller"**. Bruk telefon, nettbrett eller PC og koble til dette nettverket. Når du er tilkoblet, skriv inn http://192.168.4.1 eller http://duofiller.local i nettleserens adressefelt. Du kommer da til menyen i webgrensesnittet. I webgrensesnittet kan du justere fyllenivå for Sensormodus, fylletid for Timermodus og purgetid. Det er også en fyllteller som er nyttig for enkelt å holde oversikt over hvor mange fyllinger som er gjort.

Fylletid for Timermodus kan settes i millisekunder og fyllenivå for Sensormodus i millimeter. Merk at hensikten er å finjustere et allerede satt fyllenivå. Forvent ikke å treffe nøyaktig fyllenivå i millimeter via webgrensesnittet. Men for å justere fyllenivået 1–2–5–10 mm opp eller ned fungerer det utmerket. Fyllenivå i millimeter angir målt fyllenivå over tuppen av CO~2~-røret med ikke-karbonert vann. Med karbonert drikke blir det faktiske fyllenivået litt annerledes, avhengig av karboneringsnivå og SG (egenvekt).

I oppsettsmenyen for tilkobling kan du legge inn SSID og passord for ditt eget wifi-nettverk. Etter omstart kobler boksfylleren seg til hjemmenettverket ditt, og du kan styre den fra hvilken som helst enhet på samme nettverk. Du finner menyen ved å skrive http://duofiller.local eller IP-adressen den har fått tildelt. IP-adressen finner du enten med en nettverksscanner (se etter enhet "Duofiller" eller noen ganger "espressif") eller ved å logge på ruteren og se i DHCP-listen. Sørg for at telefon, nettbrett eller PC er koblet til samme wifi som boksfylleren.

Du kan endre AP-ens SSID (og passord) for hver enkelt boksfyller for å skille mellom flere fyllere. Hostnavnet blir det samme som AP-ens SSID. Har du for eksempel flere Duofillere kan du gi dem navn som "Duofiller1", "Duofiller2" osv. Da kobler du til hver enkelt med duofiller1.local, duofiller2.local osv.

Webgrensesnittet har også en "deaktiver wifi"-funksjon. Boksfylleren fungerer helt fint uten wifi, og hvis du ikke bruker det kan du deaktivere wifi-radioen. For å aktivere wifi igjen: nullstill nettverksinnstillingene.

## Tilbakestilling til fabrikkinnstillinger

**Slå av boksfylleren, trykk inn trykknappen og slå på mens du holder knappen inne:**

Hold trykknappen inne i 5 sekunder og slipp for å nullstille nettverksinnstillingene. 5 sekunder indikeres med blå LED.

Hold trykknappen inne i 10 sekunder og slipp for å nullstille alle innstillinger til fabrikkstandard. 10 sekunder indikeres med rød LED.

For å avbryte nullstillingen, hold inne i mer enn 15 sekunder og slipp.


### Detaljer

For detaljer, se hurtigreferansen :icon-arrow-down: [!ref Hurtigreferanse](/quickreference.md)
