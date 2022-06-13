---
keywords: Investing,Cryptocurrency,Blockchain
title: Hashgraph-konsensus
description: Hashgraph-konsensus fungerer annerledes enn mer kjente blockchain-konsensusmekanismer. Lær mer om det og hvordan det fungerer.
---

# Hashgraph-konsensus
## Hva er Hashgraph-konsensus?

Hashgraph-konsensus er et alternativ til – eller neste generasjon av – teknologien bak blockchain-konsensusmekanismer. I stedet for å bruke beregningskraften til store nettverk for å verifisere transaksjoner, blir transaksjoner registrert og bekreftet via en protokoll som bruker nodekommunikasjon.

En hashgraf er en desentralisert hovedbok omtrent på samme måte som en blokkjede er. Den lagrer informasjon, sikrer den med kryptografi, begrenser tilgangen og bruker de lagrede dataene som verifisering. Imidlertid når et hashgraph-nettverk konsensus på en mye annen måte enn en blokkjede gjør.

Hashgraph-konsensus oppnås ved å bruke konsepter kalt "sladder", "sladder om sladder" og virtuell stemmegivning. Designere av systemet rapporterer at det løser problemene som er iboende til konsensusbyggende [algoritmer](/algorithm),. for eksempel [proof of work](/proof-work) (PoW), i form av bedre hastighet og høyere effektivitet.

> Hashgraph-konsensus – sladder, sladder om sladder og virtuell stemmegivning – er mekanismen Hedera distribuerte hovedbok bruker for å validere og bekrefte transaksjoner.

>

## Forstå Hashgraph-konsensus

Hashgraph er et alternativ til blockchain. I likhet med en blokkjede lagrer den data og krypterer dem. En hash genereres for transaksjonsinformasjon, og nye transaksjoner eller data legges til og bygges på. En blokkjede er imidlertid en hovedbok som består av blokker med data. Hver blokk er koblet til den forrige blokken ved å bruke dataene, verifisert av et nettverk av validatorer for å lage neste blokk. Denne prosessen skaper én kjede. En hashgraf er ikke én kjede – all informasjon lagres i en kryptert hovedbok, og hver bruker deltar i valideringsprosessen, ikke bare validatorene.

For eksempel oppretter Alice en transaksjon med Bob, og all informasjonen hun vet blir gitt til ham. Bob gjør deretter en transaksjon med Kris. All informasjon Bob har er formidlet til Kris. Kris handler med Eli, og alt hun vet blir overført. Dette fortsetter i hele nettverket, med kjeden som i hovedsak sladrer om hendelsene som finner sted. Hver node vet hva alle andre noder vet, så det er ikke behov for beregningsmessig validering.

Ettersom sladderen sprer seg fra bruker til bruker, bruker nettverket algoritmer og automatisering for å sikre at statusen til hashgraph-reskontroen er oppdatert og den samme.

### Sladder

Informasjon om data kalles «sladder». Datastrukturen i en transaksjon er:

- Et tidsstempel

- Flere transaksjoner eller nuller

- To hashes fra foreldrebeholderne

- En kryptert signatur.

De to hashene er de siste hendelsene fra to synkroniseringsnoder som sammenligner informasjonen deres. Noder oppretter kontinuerlig hendelser og synkroniserer.

> Hashgraph – hovedboken – er mer effektiv enn blokkjede fordi ingen energi kastes bort på blokker som ikke er akseptert. All informasjon lagres i en hashgraf.

>

### Sladder om sladder

Informasjon om transaksjonsdata kalles «sladder om sladder». Informasjon synkroniseres i hashgraph-nettverket ved hjelp av en hendelse kalt "sladdersynkronisering". En sladdersynkronisering er en samarbeidshistorie med "sladderhendelser" gjennom hashgrafen. På denne måten kan ikke data endres eller tukles med, og det er konsensus.

### Virtuell stemmegivning

Virtuell stemmegivning skjer når nodene sammenligner hendelser og når en konsensus via en stemmealgoritme. Slik fungerer det – en transaksjon blir tildelt et tidsstempel etter hvert som en node mottar det. Når den overføres til de andre nodene i nettverket, tildeles den et tidsstempel som er en median av alle tidsstemplene for den transaksjonen mottatt av nodene i nettverket. Medianen fungerer som resultatet av avstemningen. Dette skaper et mer rettferdig transaksjonssystem enn en blokkjede fordi nettverket bestemmer, ikke én node.

### Feiltoleranse

Som med de fleste distribuerte hovedbøker og blokkjeder, er det alltid en sjanse for at en deltaker i nettverket ikke er ærlig. Det kan være forsinkelser i kommunikasjon eller nettverksforsinkelse som gjør at noder ikke kommuniserer riktig.

Konsensusmekanismer er utviklet for å håndtere disse feilene ved å sette feiltoleransekriterier. Utviklere må vurdere og gjøre rede for dårlige skuespillere, dårlige tilkoblinger, nettverksforsinkelse og andre nettverksproblemer. Hashgraph-konsensus kan tolerere at en tredjedel av nettverket opptrer ondsinnet. Det er angivelig asynkron bysantinsk feiltolerant – det høyeste sikkerhetsnivået – noe som betyr at ærlige noder på et nettverk fortsetter å fungere selv om det er dårlige skuespillere.

## Hvordan er Hashgraph forskjellig fra Blockchain?

Hashgraph er en datastruktur som opprettholder registrene over hvem som fortalte hvem hva og i hvilken rekkefølge de gjorde det. Det er en samarbeidshistorie med sladderbegivenheter ettersom deltakerne legger til og deler informasjon, som validerer transaksjoner mye raskere enn en blokkjede.

Blockchain legger tidligere transaksjonsinformasjon til ny transaksjonsinformasjon og krypterer den. En tredjepart er nødvendig for å validere transaksjonene mellom partene. Hashgraph trenger ikke denne langsomme prosessen på grunn av sladderprotokollen.

> Hashgraph-konsensus er mye raskere enn blockchain-konsensusmekanismer, med gjennomsnittlige transaksjonsbekreftelsestider i sekunder i stedet for minutter.

>

Bitcoin og mange andre kryptovalutaer har problemer med timing av meldinger. Imidlertid overvinner hashgraphs asynkrone bysantinske feiltoleranse problemet med meldingstiming ved å anta at tapte eller forsinkede meldinger til slutt vil komme frem til deres destinasjoner.

For eksempel, hvis to transaksjoner skjer samtidig, velger et blokkjedenettverk hvilken rekkefølge transaksjonene skjedde. I noen blokkjeder prioriterer transaksjonsgebyrer bekreftelse. Andre nettverk kan bestemme hvilken transaksjon som bekreftes basert på hvor mange tokens en validator har satset. I disse blokkjedene påvirker en node resultatet.

Hashgraph-konsensus eliminerer innflytelsen en node eller en gruppe noder kan ha på transaksjoner. Fordi det er et tidsstempel på hver transaksjon, og hver transaksjon kommuniseres til hele nettverket, er transaksjonstidsproblemer løst.

## Høydepunkter

- Det distribuerte hovedboksystemet for hashgraph har ikke fått bred adopsjon av kryptosamfunnet.

– Hashgraph-konsensus bruker informasjon om informasjon i stedet for selve innholdet for å skape konsensus.

– Primærinformasjon i hashgrafen kalles «sladder», og sekundærinformasjon kalles «sladder om sladder».

## FAQ

### Hvordan fungerer Hashgraph Consensus?

Hashgraph-konsensus fungerer ved å bruke konsensustidsstempler og «sladder», der hver node kommuniserer alt den vet til tilfeldige noder i «sladderhendelser».

### Hva er Hashgraph-konsensus?

Hashgraph-konsensus er en mekanisme som brukes i en hashgraf-distribuert hovedbok for å validere transaksjoner.

### Vil Hashgraph erstatte Blockchain?

Hashgraph er designet for å være – og markedsføres som – en forbedring av blockchain-teknologi, men om den vil erstatte den gjenstår å se. Den har ennå ikke så mye utviklerinteresse og adopsjon som blokkjedeteknologi.

