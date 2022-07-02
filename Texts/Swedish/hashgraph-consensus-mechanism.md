---
keywords: Investing,Cryptocurrency,Blockchain
title: Hashgraph Consensus
description: Hashgraph-konsensus fungerar annorlunda än mer välkända blockchain-konsensusmekanismer. Lär dig mer om det och hur det fungerar.
---

# Hashgraph Consensus
## Vad är Hashgraph Consensus?

Hashgraph-konsensus är ett alternativ till – eller nästa generation av – tekniken bakom blockchain-konsensusmekanismer. Istället för att använda beräkningskraften hos stora nätverk för att verifiera transaktioner, registreras och bekräftas transaktioner via ett protokoll som använder nodkommunikation.

En hashgraf är en decentraliserad reskontra på ungefär samma sätt som en blockchain. Den lagrar information, säkrar den med kryptografi, begränsar åtkomsten och använder lagrad data som verifiering. Ett hashgraph-nätverk når dock konsensus på ett mycket annat sätt än en blockchain.

Hashgraph-konsensus uppnås med begrepp som kallas "skvaller", "skvaller om skvaller" och virtuell röstning. Designers av systemet rapporterar att det löser problemen med konsensusbyggande [algoritmer](/algorithm),. såsom [proof of work](/proof-work) (PoW), i form av bättre hastighet och högre effektivitet.

> Hashgraph-konsensus – skvaller, skvaller om skvaller och virtuell omröstning – är den mekanism som Hedera distribuerade huvudbok använder för att validera och bekräfta transaktioner.

>

## Förstå Hashgraph Consensus

Hashgraph är ett alternativ till blockchain. I likhet med en blockchain lagrar den data och krypterar den. En hash genereras för transaktionsinformation och nya transaktioner eller data läggs till och bygger på. En blockkedja är dock en reskontra som består av datablock. Varje block är länkat till föregående block med hjälp av dess data, verifierat av ett nätverk av validatorer för att skapa nästa block. Denna process skapar en kedja. En hashgraf är inte en kedja – all information förvaras i en krypterad reskontra, och varje användare deltar i valideringsprocessen, inte bara validerarna.

Till exempel skapar Alice en transaktion med Bob, och all information hon känner till ges till honom. Bob gör sedan en transaktion med Kris. All information Bob har förmedlas till Kris. Kris gör transaktioner med Eli, och allt hon vet överförs. Detta fortsätter i hela nätverket, med kedjan som i huvudsak skvallrar om händelserna som äger rum. Varje nod vet vad alla andra noder vet, så det finns inget behov av beräkningsvalidering.

När skvallret sprids från användare till användare använder nätverket algoritmer och automatisering för att säkerställa att tillståndet för hashgraph-reskontran är uppdaterat och detsamma.

### Skvaller

Information om data kallas "skvaller". Datastrukturen som ingår i en transaktion är:

- En tidsstämpel

- Fler transaktioner eller nollor

- Två hash från föräldracontainrarna

- En krypterad signatur.

De två hasharna är de sista händelserna från två synkroniseringsnoder som jämför deras information. Noder skapar kontinuerligt händelser och synkroniserar.

> Hashgraph – huvudboken – är effektivare än blockchain eftersom ingen energi slösas bort på block som inte accepteras. All information sparas i en hashgraf.

>

### Skvaller om skvaller

Information om transaktionsdata kallas "skvaller om skvaller". Information synkroniseras i hashgraph-nätverket med hjälp av en händelse som kallas "skvallersynkronisering". En skvallersynkronisering är en gemensam historia av "skvallhändelser" genom hela hashgrafen. På detta sätt kan data inte ändras eller manipuleras, och det råder konsensus.

### Virtuell röstning

Virtuell röstning sker när noderna jämför händelser och når en konsensus via en röstningsalgoritm. Så här fungerar det – en transaktion tilldelas en tidsstämpel när en nod tar emot den. När den passerar till de andra noderna i nätverket tilldelas den en tidsstämpel som är en median av alla tidsstämplar för den transaktionen som tas emot av noderna i nätverket. Medianen fungerar som resultatet av omröstningen. Detta skapar ett mer rättvist transaktionssystem än en blockchain eftersom nätverket bestämmer, inte en nod.

### Feltolerans

Som med de flesta distribuerade reskontra och blockchain finns det alltid en chans att en deltagare i nätverket inte är ärlig. Det kan finnas förseningar i kommunikationen eller nätverkslatens som gör att noder inte kommunicerar korrekt.

Konsensusmekanismer är utformade för att hantera dessa fel genom att sätta feltoleranskriterier. Utvecklare måste överväga och ta hänsyn till dåliga aktörer, dåliga anslutningar, nätverkslatens och andra nätverksproblem. Hashgraph-konsensus kan tolerera att en tredjedel av nätverket agerar illvilligt. Den är enligt uppgift asynkron bysantinsk feltolerant – den högsta säkerhetsnivån – vilket innebär att ärliga noder på ett nätverk fortsätter att fungera även om det finns dåliga aktörer.

## Hur skiljer sig Hashgraph från Blockchain?

Hashgraph är en datastruktur som upprätthåller register över vem som berättade vem vad och i vilken ordning de gjorde det. Det är en kollaborativ historia av skvallerhändelser när deltagare lägger till och delar information, vilket validerar transaktioner mycket snabbare än en blockchain.

Blockchain lägger till tidigare transaktionsinformation till ny transaktionsinformation och krypterar den. En tredje part behövs för att validera transaktionerna mellan parterna. Hashgraph behöver inte denna långsamma process på grund av skvallerprotokollet.

> Hashgraph-konsensus är mycket snabbare än blockchain-konsensusmekanismer, med genomsnittliga transaktionsbekräftelsetider i sekunder snarare än minuter.

>

Bitcoin och många andra kryptovalutor har problem med timing av meddelanden. Men hashgraphs asynkrona bysantinska feltolerans övervinner problemet med meddelandetiming genom att anta att förlorade eller försenade meddelanden så småningom kommer att nå sina destinationer.

Till exempel, om två transaktioner sker samtidigt, väljer ett blockchain-nätverk vilken ordning transaktionerna inträffade. I vissa blockkedjor prioriterar transaktionsavgifter bekräftelse. Andra nätverk kan bestämma vilken transaktion som bekräftas baserat på hur många tokens en validerare har satsat. I dessa blockkedjor påverkar en nod resultatet.

Hashgraph-konsensus eliminerar inflytandet som en nod eller en grupp av noder kan ha på transaktioner. Eftersom det finns en tidsstämpel på varje transaktion, och varje transaktion kommuniceras till hela nätverket, är transaktionstidsproblem lösta.

## Höjdpunkter

- Det distribuerade hashgraph-systemet har inte fått bred användning av kryptogemenskapen.

- Hashgraph consensus använder information om information snarare än själva innehållet för att skapa konsensus.

- Primär information i hashgrafen kallas "skvaller", och sekundär information kallas "skvaller om skvaller."

## Vanliga frågor

### Hur fungerar Hashgraph Consensus?

Hashgraph-konsensus fungerar med konsensustidsstämplar och "skvaller", där varje nod kommunicerar allt den vet till slumpmässiga noder i "skvallerhändelser".

### Vad är Hashgraph Consensus?

Hashgraph-konsensus är en mekanism som används i en hashgraf-distribuerad reskontra för att validera transaktioner.

### Kommer Hashgraph att ersätta Blockchain?

Hashgraph är designad för att vara – och marknadsföras som – en förbättring av blockchain-teknologin, men om den kommer att ersätta den återstår att se. Det har ännu inte så mycket utvecklarintresse och adoption som blockchain-teknik.

