---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Sharding
description: Sharding er en databasepartitioneringsteknik, der kan hjælpe blockchain-netværk med at opbygge skalerbarhed, reducere latens og håndtere mere transaktionsvolumen.
---

# Sharding
## Hvad er Sharding?

Sharding er en databaseopdelingsteknik, der bruges af [blockchain-](/blockchain) virksomheder med det formål at skalerbarhed, hvilket gør dem i stand til at behandle flere transaktioner i sekundet. Sharding opdeler en blockchain-virksomheds hele netværk i mindre partitioner, kendt som "shards". Hvert shard består af sine egne data, hvilket gør det karakteristisk og uafhængigt sammenlignet med andre shards.

Sharding kan hjælpe med at reducere et netværks latens eller langsommelighed, da det opdeler et blockchain-netværk i separate shards. Der er dog nogle sikkerhedsproblemer omkring sharding, hvor shards kan angribes.

## Forstå Sharding

Blockchain-netværk og deres respektive [kryptovalutaer](/cryptocurrency) vinder i popularitet på grund af den udbredte anvendelse af teknologien, som omfatter [supply chain management](/scm) og finansielle transaktioner. Efterhånden som blockchains popularitet vokser, vokser arbejdsbyrden og transaktionsvolumen, der håndteres af netværket, også. Hvis vi tænker på en blockchain som en delt database, efterhånden som flere og flere data tilføjes, skal netværket finde nye måder at kunne behandle alle disse data effektivt og hurtigt, og det er her sharding kan hjælpe.

###Distribueret hovedbog

Den [distribuerede hovedbog](/distributed-ledgers) af blockchain-teknologi gør det attraktivt, da det giver mulighed for, at transaktionerne deles konsensuelt på tværs af flere websteder og geografi. Efterhånden som transaktioner registreres, sendes kopier til det delte netværk inden for få sekunder, hvilket skaber offentlige "vidner". Hvis en del af netværket bliver offer for svig eller et ondsindet angreb, kan det delte netværks deltagere identificere, hvad der blev ændret af svindlerne, da de alle opbevarer en kopi af hovedbogens transaktioner. Som et resultat kan blockchain-teknologi og dets distribuerede hovedbogssystem hjælpe med at reducere svindel og begrænse skaden fra [cyberangreb](/cybersecurity),. såsom et hack.

###Skalerbarhed

En af de store udfordringer med blockchain-teknologi er dog, at efterhånden som yderligere computere føjes til netværket, og flere transaktioner behandles, kan netværket hænge fast, hvilket bremser processen - kaldet latency. Latency er en hindring for, at blockchain bliver vedtaget til udbredt brug, især sammenlignet med de nuværende elektroniske betalingssystemer, der fungerer hurtigt og effektivt. [Skalerbarhed er](/scalability) med andre ord en udfordring for blockchain, da netværkene måske ikke er i stand til at håndtere de øgede mængder af data og transaktionsflow, efterhånden som flere og flere industrier tager teknologien i brug.

En af de løsninger, der overvejes til at skabe latency-fri skalerbarhed, er processen med sharding. Sharding er designet til at sprede arbejdsbyrden på et netværk i partitioner, hvilket kan hjælpe med at reducere latens og tillade flere transaktioner at blive behandlet af blockchain.

> Tre træk, som blockchain-netværk søger at anvende, er decentralisering, skalerbarhed og sikkerhed.

>

## Hvordan Sharding opnås

Før du udforsker, hvordan sharding udføres inden for et blockchain-netværk, er det vigtigt at gennemgå, hvordan data i øjeblikket lagres og behandles.

### Blockchain noder

I øjeblikket, i blockchain, skal hver node i et netværk behandle eller håndtere alle transaktionsvolumener i netværket. Noder i en blockchain er uafhængige og er ansvarlige for at vedligeholde og opbevare alle data i et decentraliseret netværk. Med andre ord skal hver node gemme kritisk information, såsom kontosaldi og transaktionshistorik. Blockchain-netværk blev etableret, så hver node skal behandle alle operationer, data og transaktioner på netværket.

Selvom den sikrer en blockchains sikkerhed ved at gemme hver transaktion i alle noderne, bremser denne model transaktionsbehandlingen betydeligt. Langsomme hastigheder til behandling af transaktioner lover ikke godt for en fremtid, hvor blockchain bliver ansvarlig for millioner af transaktioner.

Sharding kan hjælpe, da det opdeler eller spreder den transaktionelle arbejdsbyrde fra et blockchain-netværk, så hver node ikke behøver at håndtere eller behandle hele blockchainens arbejdsbyrde. På en måde opdeler sønderdeling arbejdsbyrden i skillevægge eller skår.

### Vandret partitionering

Sharding kan opnås gennem horisontal opdeling af databaser gennem opdeling i rækker. Shards, som rækkerne kaldes, konceptualiseres ud fra karakteristika. For eksempel kan et shard være ansvarlig for at gemme tilstanden og transaktionshistorikken for en bestemt type adresse. Det kan også være muligt at opdele shards baseret på typen af digitalt aktiv, der er gemt i dem. Transaktioner, der involverer det digitale aktiv, kan blive muliggjort gennem en kombination af shards.

Som et eksempel kan du overveje en udlejnings [-ejendomstransaktion](/realestate),. hvor flere skår er involveret. Disse shards svarer til forskellige enheder, der er involveret i transaktionen, fra kundenavne til [digitale nøgler](/private-key) konfigureret til en smart lås, der stilles til rådighed for lejeren ved lejebetaling.

### Shard Deling

Hvert shard kan stadig deles mellem de andre shards, hvilket opretholder et nøgleaspekt af blockchain-teknologi - den decentraliserede hovedbog. Med andre ord er hovedbogen stadig tilgængelig for alle brugere, hvilket giver dem mulighed for at se alle finanstransaktioner.

## Sharding og sikkerhed

Et af hovedspørgsmålene i praksis, der er opstået, er sikkerhed. Selvom hvert shard er separat og kun behandler sine egne data, er der en sikkerhedsmæssig bekymring vedrørende korruption af shards, hvor et shard overtager et andet shard, hvilket resulterer i tab af information eller data.

Hvis vi tænker på hvert shard som sit eget blockchain-netværk med dets autentificerede brugere og data, kan en hacker eller gennem et cyberangreb overtage et shard. Angriberen kan derefter indføre falske transaktioner eller et ondsindet program.

[Ethereum](/ethereum),. en af de mest fremtrædende blockchain-virksomheder, er på frontlinjen med at teste sharding som en mulig løsning på problemer med latency og skalerbarhed. Ethereum planlægger at udrulle 64 nye shard-kæder, efter det, det kalder "The Merge", finder sted, hvor Ethereum Mainnet vil "fusionere" med Beacon Chain proof-of-stake-systemet. Ethereum har bekæmpet potentialet for et shard-angreb ved tilfældigt at tildele noder til visse shards og konstant omtildele dem med tilfældige intervaller. Denne tilfældige prøveudtagning ville gøre det svært for hackere at vide, hvornår og hvor de skal ødelægge et skår.

Det er også vigtigt at bemærke, at sharding stadig er i den tidlige testfase for at blive brugt til blockchain-netværk. Som et resultat er alle de potentielle problemer og udfordringer endnu ikke bearbejdet.

##Højdepunkter

- Sikkerhedsproblemer omkring sharding omfatter et hack eller shard-overtagelse, hvor et shard angriber et andet, hvilket resulterer i tab af information.

- Sharding kan forbedre netværkets latenstid ved at opdele et blockchain-netværk i separate shards – hver med sine egne data, adskilt fra andre shards.

- Sharding er en databasepartitioneringsteknik, der overvejes af blockchain-netværk og testes af Ethereum.

- Jo flere brugere, som blockchain-netværk tager på, jo langsommere bliver netværket, hvilket fører til betydelig latens.

