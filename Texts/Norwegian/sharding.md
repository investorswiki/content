---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Sharding
description: Sharding er en databasepartisjoneringsteknikk som kan hjelpe blokkjedenettverk med å bygge skalerbarhet, redusere ventetiden og håndtere mer transaksjonsvolum.
---

# Sharding
## Hva er Sharding?

Sharding er en databasepartisjoneringsteknikk som brukes av [blokkjedeselskaper](/blockchain) med det formål å skalerbarhet, slik at de kan behandle flere transaksjoner per sekund. Sharding deler opp hele nettverket til et blokkjedeselskap i mindre partisjoner, kjent som «shards». Hvert shard består av sine egne data, noe som gjør det særegent og uavhengig sammenlignet med andre shards.

Deling kan bidra til å redusere ventetiden eller tregheten til et nettverk siden det deler et blokkjedenettverk i separate shards. Imidlertid er det noen sikkerhetsproblemer rundt sharding der shards kan angripes.

## Forstå Sharing

Blockchain-nettverk og deres respektive [kryptovalutaer](/cryptocurrency) øker i popularitet på grunn av den utbredte anvendelsen av teknologien, som inkluderer [forsyningskjedestyring](/scm) og finansielle transaksjoner. Ettersom populariteten til blockchain vokser, øker også arbeidsmengden og transaksjonsvolumet som håndteres av nettverket. Hvis vi tenker på en blokkjede som en delt database, ettersom mer og mer data legges til, må nettverket finne nye måter å kunne behandle alle disse dataene effektivt og raskt, og det er der sharding kan hjelpe.

### Distribuert hovedbok

Den [distribuerte hovedboken](/distributed-ledgers) for blokkjedeteknologi gjør det attraktivt siden det lar transaksjonene deles konsensuelt på tvers av flere nettsteder og geografier. Etter hvert som transaksjoner registreres, sendes kopier til det delte nettverket i løpet av sekunder og skaper offentlige "vitner". Hvis en del av nettverket blir offer for svindel eller et ondsinnet angrep, kan deltakerne i det delte nettverket identifisere hva som ble endret av svindlerne siden de alle opprettholder en kopi av hovedbokens transaksjoner. Som et resultat kan blokkjedeteknologi og dets distribuerte hovedboksystem bidra til å redusere svindel og begrense skaden fra [nettangrep](/cybersecurity),. for eksempel et hack.

### Skalerbarhet

En av de største utfordringene med blokkjedeteknologi er imidlertid at etter hvert som flere datamaskiner legges til nettverket og flere transaksjoner behandles, kan nettverket sette seg fast, noe som bremser prosessen – kalt latens. Latency er en hindring for at blokkjede blir tatt i bruk for utbredt bruk, spesielt sammenlignet med dagens elektroniske betalingssystemer som fungerer raskt og effektivt. [Skalerbarhet er med](/scalability) andre ord en utfordring for blockchain siden nettverkene kanskje ikke er i stand til å håndtere de økte datamengdene og transaksjonsflyten ettersom flere og flere bransjer tar i bruk teknologien.

En av løsningene som vurderes for å skape latency-fri skalerbarhet er prosessen med sharding. Sharding er designet for å spre arbeidsmengden til et nettverk i partisjoner, noe som kan bidra til å redusere ventetiden og tillate flere transaksjoner å bli behandlet av blokkjeden.

> Tre trekk som blokkjedenettverk søker å bruke er desentralisering, skalerbarhet og sikkerhet.

>

## Hvordan shading oppnås

Før du utforsker hvordan sharding oppnås i et blokkjedenettverk, er det viktig å gå gjennom hvordan data lagres og behandles.

### Blockchain Noder

For øyeblikket, i blockchain, må hver node i et nettverk behandle eller håndtere alle transaksjonsvolumene i nettverket. Noder i en blokkjede er uavhengige og er ansvarlige for å vedlikeholde og lagre all data i et desentralisert nettverk. Med andre ord må hver node lagre kritisk informasjon, som kontosaldo og transaksjonshistorikk. Blockchain-nettverk ble etablert slik at hver node må behandle alle operasjoner, data og transaksjoner på nettverket.

Selv om den sikrer en blokkjedes sikkerhet ved å lagre hver transaksjon i alle nodene, bremser denne modellen transaksjonsbehandlingen betraktelig. Lave hastigheter for behandling av transaksjoner lover ikke godt for en fremtid der blockchain blir ansvarlig for millioner av transaksjoner.

Sharding kan hjelpe siden den deler opp eller sprer transaksjonsarbeidsbelastningen fra et blokkjedenettverk slik at hver node ikke trenger å håndtere eller behandle hele blokkjedens arbeidsmengde. På en måte deler oppdeling arbeidsmengden inn i partisjoner eller skår.

### Horisontal partisjonering

Deling kan oppnås gjennom horisontal partisjonering av databaser gjennom inndeling i rader. Shards, som radene kalles, konseptualiseres basert på egenskaper. For eksempel kan ett shard være ansvarlig for å lagre tilstanden og transaksjonshistorikken for en bestemt type adresse. Det kan også være mulig å dele opp shards basert på typen digital eiendel som er lagret i dem. Transaksjoner som involverer den digitale ressursen kan gjøres mulig gjennom en kombinasjon av shards.

Som et eksempel kan du vurdere en [eiendomstransaksjon med utleie](/realestate) der flere skjær er involvert. Disse skårene tilsvarer ulike enheter involvert i transaksjonen, fra kundenavn til [digitale nøkler](/private-key) konfigurert til en smart lås som gjøres tilgjengelig for leietaker ved leiebetaling.

### Shard-deling

Hvert shard kan fortsatt deles mellom de andre shards, noe som opprettholder et nøkkelaspekt av blockchain-teknologi - den desentraliserte hovedboken. Med andre ord er hovedboken fortsatt tilgjengelig for alle brukere, slik at de kan se alle hovedboktransaksjonene.

## Deling og sikkerhet

En av hovedproblemstillingene i praksisen som har oppstått er sikkerhet. Selv om hvert shard er separat og kun behandler sine egne data, er det en sikkerhetsbekymring angående korrupsjon av shards, der ett shard overtar et annet shard, noe som resulterer i tap av informasjon eller data.

Hvis vi tenker på hvert shard som sitt eget blokkjedenettverk med sine autentiserte brukere og data, kan en hacker eller gjennom et cyberangrep ta over et shard. Angriperen kan deretter introdusere falske transaksjoner eller et ondsinnet program.

[Ethereum](/ethereum),. et av de mest fremtredende blokkjedeselskapene, er i frontlinjen for å teste sharding som en mulig løsning på problemer med ventetid og skalerbarhet. Ethereum planlegger å rulle ut 64 nye shard-kjeder etter at det den kaller «The Merge» finner sted, hvor Ethereum Mainnet vil «fusjonere» med Beacon Chain proof-of-stake-systemet. Ethereum har bekjempet potensialet til et shard-angrep ved å tilfeldig tilordne noder til visse shards og hele tiden tilordne dem på nytt med tilfeldige intervaller. Denne tilfeldige prøvetakingen vil gjøre det vanskelig for hackere å vite når og hvor de skal ødelegge et skår.

Det er også viktig å merke seg at sharding fortsatt er i den tidlige testfasen for å bli brukt for blockchain-nettverk. Som et resultat er alle potensielle problemer og utfordringer ennå ikke løst.

## Høydepunkter

- Sikkerhetsproblemer rundt sharding inkluderer et hack eller shard-overtakelse, der ett shard angriper et annet, noe som resulterer i tap av informasjon.

– Deling kan forbedre nettverksforsinkelsen ved å dele et blokkjedenettverk i separate shards – hver med sine egne data, atskilt fra andre shards.

- Sharding er en databasepartisjoneringsteknikk som vurderes av blokkjedenettverk og testes av Ethereum.

– Jo flere brukere som blokkjedenettverk tar på, jo tregere blir nettverket, noe som fører til betydelig latens.

