---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Sharding
description: Sharding är en databaspartitioneringsteknik som kan hjälpa blockchain-nätverk att bygga skalbarhet, minska latens och hantera mer transaktionsvolym.
---

# Sharding
## Vad är Sharding?

Sharding är en databaspartitioneringsteknik som används av [blockkedjeföretag](/blockchain) i syfte att skalbarhet, vilket gör att de kan bearbeta fler transaktioner per sekund. Sharding delar upp ett blockchain-företags hela nätverk i mindre partitioner, så kallade "shards". Varje shard består av sin egen data, vilket gör den distinkt och oberoende jämfört med andra shards.

Sharding kan hjälpa till att minska latensen eller långsamheten i ett nätverk eftersom det delar upp ett blockchain-nätverk i separata skärvor. Det finns dock vissa säkerhetsproblem kring skärvning där skärvor kan attackeras.

## Förstå Sharding

Blockchain-nätverk och deras respektive [kryptovalutor](/cryptocurrency) ökar i popularitet på grund av den utbredda tillämpningen av tekniken, som inkluderar [supply chain management](/scm) och finansiella transaktioner. I takt med att blockchains popularitet ökar, ökar också arbetsbelastningen och transaktionsvolymen som hanteras av nätverket. Om vi tänker på en blockchain som en delad databas, eftersom mer och mer data läggs till, måste nätverket hitta nya sätt för att kunna behandla all denna data effektivt och snabbt, vilket är där sharding kan hjälpa.

###Distribuerad reskontra

Den [distribuerade huvudboken](/distributed-ledgers) för blockchain-teknik gör det attraktivt eftersom det gör att transaktionerna kan delas med samförstånd över flera platser och geografi. När transaktioner registreras skickas kopior till det delade nätverket inom några sekunder och skapar offentliga "vittnen". Om en del av nätverket faller offer för bedrägeri eller en skadlig attack, kan det delade nätverkets deltagare identifiera vad som ändrades av bedragarna eftersom de alla har en kopia av redovisningens transaktioner. Som ett resultat kan blockchain-teknik och dess distribuerade reskontrasystem hjälpa till att minska bedrägerier och begränsa skadorna från [cyberattacker](/cybersecurity),. till exempel ett hack.

###Skalbarhet

En av de stora utmaningarna med blockchain-teknik är dock att när ytterligare datorer läggs till i nätverket och fler transaktioner bearbetas, kan nätverket fastna, vilket saktar ner processen – så kallad latens. Latens är ett hinder för att blockchain ska användas för utbredd användning, särskilt jämfört med de nuvarande elektroniska betalningssystemen som fungerar snabbt och effektivt. [Skalbarhet är med](/scalability) andra ord en utmaning för blockchain eftersom nätverken kanske inte kan hantera de ökade mängderna data och transaktionsflöden när fler och fler industrier tar till sig tekniken.

En av lösningarna som övervägs för att skapa latensfri skalbarhet är sönderdelningsprocessen. Sharding är designat för att sprida ut arbetsbelastningen i ett nätverk i partitioner, vilket kan bidra till att minska latensen och tillåta fler transaktioner att bearbetas av blockkedjan.

> Tre egenskaper som blockchain-nätverk försöker använda är decentralisering, skalbarhet och säkerhet.

>

## Hur skärning åstadkoms

Innan du utforskar hur sharding sker inom ett blockchain-nätverk är det viktigt att se över hur data för närvarande lagras och bearbetas.

### Blockkedjenoder

För närvarande, i blockchain, måste varje nod i ett nätverk bearbeta eller hantera alla transaktionsvolymer inom nätverket. Noder i en blockchain är oberoende och ansvarar för att underhålla och lagra all data i ett decentraliserat nätverk. Med andra ord måste varje nod lagra kritisk information, såsom kontosaldon och transaktionshistorik. Blockchain-nätverk etablerades så att varje nod måste bearbeta alla operationer, data och transaktioner på nätverket.

Även om den säkerställer en blockchains säkerhet genom att lagra varje transaktion i alla noder, saktar denna modell upp transaktionsbearbetningen avsevärt. Långsamma hastigheter för att bearbeta transaktioner bådar inte gott för en framtid där blockchain blir ansvarig för miljontals transaktioner.

Sharding kan hjälpa eftersom det partitionerar eller sprider ut transaktionsarbetsbelastningen från ett blockkedjenätverk så att varje nod inte behöver hantera eller bearbeta hela blockkedjans arbetsbelastning. På ett sätt delar skärning upp arbetsbelastningen i partitioner eller skärvor.

### Horisontell partitionering

Delning kan åstadkommas genom horisontell partitionering av databaser genom uppdelning i rader. Skärvor, som raderna kallas, konceptualiseras utifrån egenskaper. Till exempel kan en skärva vara ansvarig för att lagra status och transaktionshistorik för en specifik typ av adress. Det kan också vara möjligt att dela upp skärvor baserat på typen av digital tillgång som lagras i dem. Transaktioner som involverar den digitala tillgången kan göras möjliga genom en kombination av skärvor.

Som ett exempel, överväga en hyresfastighetstransaktion [där](/realestate) flera skärvor är inblandade. Dessa skärvor motsvarar olika enheter som är involverade i transaktionen, från kundnamn till [digitala nycklar](/private-key) konfigurerade till ett smart lås som görs tillgängligt för hyresgästen vid hyresbetalning.

### Shard Shard Shard

Varje skärva kan fortfarande delas mellan de andra skärvorna, vilket upprätthåller en nyckelaspekt av blockchain-tekniken - den decentraliserade huvudboken. Med andra ord är redovisningen fortfarande tillgänglig för alla användare, vilket gör att de kan se alla redovisningstransaktioner.

## Skärning och säkerhet

En av huvudfrågorna i praktiken som har uppstått är säkerheten. Även om varje skärva är separat och bara bearbetar sin egen data, finns det en säkerhetsoro när det gäller korruptionen av skärvorna, där en skärva tar över en annan, vilket resulterar i förlust av information eller data.

Om vi tänker på varje skärva som sitt eget blockkedjenätverk med dess autentiserade användare och data, kan en hackare eller genom en cyberattack ta över en skärva. Angriparen kan sedan introducera falska transaktioner eller ett skadligt program.

[Ethereum](/ethereum),. ett av de mest framstående blockkedjeföretagen, är i frontlinjen för att testa sharding som en möjlig lösning på latens- och skalbarhetsproblem. Ethereum planerar att rulla ut 64 nya shard-kedjor efter det som det kallar "The Merge", där Ethereum Mainnet kommer att "fusionera" med Beacon Chain proof-of-stake-systemet. Ethereum har bekämpat potentialen för en shard-attack genom att slumpmässigt tilldela noder till vissa shards och ständigt omtilldela dem med slumpmässiga intervall. Detta slumpmässiga urval skulle göra det svårt för hackare att veta när och var de ska skada en skärva.

Det är också viktigt att notera att sharding fortfarande är i den tidiga testfasen för att användas för blockchain-nätverk. Som ett resultat har alla potentiella problem och utmaningar ännu inte utarbetats.

##Höjdpunkter

- Säkerhetsproblem kring sharding inkluderar ett hack eller shard-övertagande, där en shard attackerar en annan, vilket resulterar i förlust av information.

- Sharding kan förbättra nätverkslatensen genom att dela upp ett blockchain-nätverk i separata shards - var och en med sin egen data, separat från andra shards.

- Sharding är en databaspartitioneringsteknik som övervägs av blockkedjenätverk och testas av Ethereum.

– Ju fler användare som blockchain-nätverk tar på sig, desto långsammare blir nätverket, vilket leder till betydande latens.

