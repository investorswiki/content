---
keywords: Investing,Cryptocurrency,Blockchain
title: Hashgraph konsensus
description: Hashgraph-konsensus fungerer anderledes end mere velkendte blockchain-konsensusmekanismer. Lær mere om det, og hvordan det virker.
---

# Hashgraph konsensus
## Hvad er Hashgraph-konsensus?

Hashgraph-konsensus er et alternativ til – eller den næste generation af – teknologien bag blockchain-konsensusmekanismer. I stedet for at bruge store netværks regnekraft til at verificere transaktioner, registreres og bekræftes transaktioner via en protokol, der bruger nodekommunikation.

En hashgraf er en decentraliseret hovedbog på samme måde som en blockchain er. Den gemmer information, sikrer den med kryptografi, begrænser adgangen og bruger de lagrede data som verifikation. Et hashgraph-netværk når dog konsensus på en meget anden måde end en blockchain gør.

Hashgraph-konsensus opnås ved hjælp af begreber kaldet "sladder", "sladder om sladder" og virtuel afstemning. Designere af systemet rapporterer, at det løser de problemer, der er forbundet med konsensusskabende [algoritmer](/algorithm),. såsom [proof of work](/proof-work) (PoW), i form af bedre hastighed og højere effektivitet.

> Hashgraph-konsensus – sladder, sladder om sladder og virtuel afstemning – er den mekanisme, som Hedera distribuerede hovedbog bruger til at validere og bekræfte transaktioner.

>

## Forståelse af Hashgraph-konsensus

Hashgraph er et alternativ til blockchain. I lighed med en blockchain gemmer den data og krypterer dem. Der genereres en hash til transaktionsinformation, og nye transaktioner eller data tilføjes og bygges videre på. En blockchain er dog en hovedbog, der består af datablokke. Hver blok er knyttet til den forrige blok ved hjælp af dens data, verificeret af et netværk af validatorer for at oprette den næste blok. Denne proces skaber én kæde. En hashgraf er ikke én kæde – al information opbevares i en krypteret hovedbog, og hver bruger deltager i valideringsprocessen, ikke kun validatorerne.

For eksempel opretter Alice en transaktion med Bob, og alle de oplysninger, hun kender, bliver givet til ham. Bob laver derefter en transaktion med Kris. Al information Bob er blevet kommunikeret til Kris. Kris handler med Eli, og alt hvad hun ved bliver overført. Dette fortsætter i hele netværket, hvor kæden i det væsentlige sladrer om de begivenheder, der finder sted. Hver node ved, hvad alle andre noder ved, så der er ikke behov for beregningsvalidering.

Efterhånden som sladderen spredes fra bruger til bruger, bruger netværket algoritmer og automatisering til at sikre, at status for hashgraph-hovedbogen er opdateret og den samme.

###Sladre

Oplysninger om data kaldes "sladder". Datastrukturen indeholdt i en transaktion er:

- Et tidsstempel

- Flere transaktioner eller nuller

- To hash fra forældrebeholderne

- En krypteret signatur.

De to hashes er de sidste hændelser fra to synkroniseringsknuder, der sammenligner deres information. Noder opretter løbende begivenheder og synkroniserer.

> Hashgraph – hovedbogen – er mere effektiv end blockchain, fordi der ikke spildes energi på blokke, der ikke accepteres. Alle oplysninger gemmes i en hashgraf.

>

### Sladder om sladder

Oplysninger om transaktionsdata kaldes "sladder om sladder." Information synkroniseres i hashgraph-netværket ved hjælp af en hændelse kaldet en "sladdersynkronisering". En sladdersynkronisering er en samarbejdshistorie af "sladderbegivenheder" gennem hele hashgrafen. På denne måde kan data ikke ændres eller manipuleres, og der er konsensus.

###Virtuel afstemning

Virtuel afstemning opstår, når noderne sammenligner begivenheder og når en konsensus via en afstemningsalgoritme. Sådan fungerer det – en transaktion tildeles et tidsstempel, efterhånden som en node modtager den. Når den passerer til de andre knudepunkter i netværket, tildeles den et tidsstempel, der er en median af alle tidsstempler for den transaktion, der modtages af knudepunkterne i netværket. Medianen fungerer som resultatet af afstemningen. Dette skaber et mere retfærdigt transaktionssystem end en blockchain, fordi netværket bestemmer, ikke én node.

### Fejltolerance

Som med de fleste distribuerede hovedbøger og blockchain, er der altid en chance for, at en deltager i netværket ikke er ærlig. Der kan være forsinkelser i kommunikation eller netværksforsinkelse, der gør, at noder ikke kommunikerer korrekt.

Konsensusmekanismer er designet til at håndtere disse fejl ved at opstille fejltolerancekriterier. Udviklere skal overveje og tage højde for dårlige skuespillere, dårlige forbindelser, netværksforsinkelse og andre netværksproblemer. Hashgraph-konsensus kan tolerere, at en tredjedel af netværket handler ondsindet. Det er angiveligt asynkron byzantinsk fejltolerant - det højeste sikkerhedsniveau - hvilket betyder, at ærlige noder på et netværk fortsætter med at fungere, selvom der er dårlige skuespillere.

## Hvordan er Hashgraph anderledes end Blockchain?

Hashgraph er en datastruktur, der vedligeholder registreringerne af, hvem der fortalte hvem hvad og i hvilken rækkefølge de gjorde det. Det er en kollaborativ historie om sladderbegivenheder, da deltagere tilføjer og deler information, som validerer transaktioner meget hurtigere end en blockchain.

Blockchain tilføjer tidligere transaktionsoplysninger til nye transaktionsoplysninger og krypterer dem. En tredjepart er nødvendig for at validere transaktionerne mellem parterne. Hashgraph har ikke brug for denne langsomme proces på grund af sladderprotokollen.

> Hashgraph-konsensus er meget hurtigere end blockchain-konsensusmekanismer, med gennemsnitlige transaktionsbekræftelsestider i sekunder i stedet for minutter.

>

Bitcoin og mange andre kryptovalutaer har problemer med timing af beskeder. Imidlertid overvinder hashgraphs asynkrone byzantinske fejltolerance problemet med beskedtiming ved at antage, at mistede eller forsinkede beskeder i sidste ende når frem til deres destinationer.

For eksempel, hvis to transaktioner finder sted samtidigt, vælger et blockchain-netværk, hvilken rækkefølge transaktionerne fandt sted. I nogle blockchains prioriterer transaktionsgebyrer bekræftelse. Andre netværk kan beslutte, hvilken transaktion der bekræftes baseret på, hvor mange tokens en validator har satset. I disse blockchains påvirker én node resultatet.

Hashgraph-konsensus eliminerer indflydelsen fra én node eller en gruppe af noder kan have på transaktioner. Fordi der er et tidsstempel på hver transaktion, og hver transaktion kommunikeres til hele netværket, er transaktionstidsproblemer løst.

##Højdepunkter

- Det distribuerede hashgraph-ledger-system har ikke modtaget bred adoption af kryptosamfundet.

- Hashgraph-konsensus bruger information om information frem for selve indholdet til at skabe konsensus.

- Primær information i hashgrafen kaldes "sladder", og sekundær information kaldes "sladder om sladder."

##Ofte stillede spørgsmål

### Hvordan virker Hashgraph Consensus?

Hashgraph-konsensus fungerer ved hjælp af konsensustidsstempler og "sladder", hvor hver node kommunikerer alt, hvad den ved, til tilfældige noder i "sladderbegivenheder".

### Hvad er Hashgraph-konsensus?

Hashgraph-konsensus er en mekanisme, der bruges i en hashgraph-distribueret hovedbog til at validere transaktioner.

### Vil Hashgraph erstatte Blockchain?

Hashgraph er designet til at være - og markedsføres som - en forbedring af blockchain-teknologien, men om den vil erstatte den, er stadig uvist. Det har endnu ikke så meget udviklerinteresse og adoption som blockchain-teknologi.

