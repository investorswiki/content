---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Bevis for kapacitet (kryptovaluta)
description: Proof of Capacity er en konsensusmekanisme, der bruger en mineknudes harddiskplads til at bestemme netværket for minerettigheder på blockchain.
---

# Bevis for kapacitet (kryptovaluta)
## Hvad er bevis for kapacitet (PoC) for kryptovalutaer?

Proof of capacity (PoC) er en [konsensusmekanisme -](/consensus-mechanism-cryptocurrency) algoritme, der bruges i blockchains, der gør det muligt for [mineenheder](/bitcoin-mining) i netværket at bruge deres ledige harddiskplads til at bestemme minerettigheder og validere transaktioner. Dette er i modsætning til at bruge mineenhedens beregningskraft (som i [proof of work](/proof-work) -algoritmen) eller minearbejderens andel i kryptovalutaerne (som i [proof of stake -](/proof-stake-pos) algoritmen).

## Forståelse af bevis for kapacitet

Bevis for kapacitet er dukket op som en af de mange alternative løsninger på problemet med højt energiforbrug i proof of work (PoW) systemer og cryptocurrency hamstring i proof of stake (PoS) systemer.

Bevis for kapacitet gør det muligt for mineenhederne, også kendt som noder, på [blockchain](/blockchain) -netværket at bruge tom plads på deres harddisk til at mine de tilgængelige [kryptovalutaer](/cryptocurrency).

I stedet for gentagne gange at ændre tallene i blokoverskriften og gentagne hashing for løsningsværdien som i et PoW-system, fungerer PoC ved at gemme en liste over mulige løsninger på mineenhedens harddisk, selv før mineaktiviteterne starter.

Jo større harddisk, jo flere mulige løsningsværdier kan man gemme på harddisken, jo flere chancer har en minearbejder for at matche den påkrævede hashværdi fra sin liste, hvilket resulterer i flere chancer for at vinde minedriftsbelønningen.

For at tegne en analogi, hvis lotteribelønninger er baseret på at matche de fleste numre på den vindende kupon, så vil en spiller med en længere liste over mulige løsninger have bedre chancer for at vinde. Derudover har spilleren lov til at fortsætte med at bruge lotterisedlens bloknumre igen og igen gentagne gange.

[Burstcoin](/burstcoin) er en kryptovaluta, der bruger et kapacitetsbevissystem. Andre mønter, der bruger det, er Storj, Chia og SpaceMint.

## Sådan fungerer PoC: Plotte og minedrift

Protokollen for kapacitetsbevis involverer en to-trins proces, der involverer plotning og minedrift.

Først plottes harddisken: listen over alle mulige [nonce](/nonce) -værdier oprettes gennem gentagen hash af data, inklusive en minearbejders konto. Hver sådan nonce indeholder 8192 hashes, som er nummereret fra 0 til 8191. Alle hashes er parret i "scoops", hvilket betyder, at tilstødende hashes kombineres for at danne et par af to. For eksempel udgør hash 0 og 1 scoop 0, hash 2 og 3 udgør hash 1, og så videre.

Det andet trin involverer selve mineøvelsen, hvor en minearbejder beregner et scoop-tal. For eksempel, hvis en minearbejder påbegynder mineaktiviteten og genererer et scoop nummer 38, vil minearbejderen derefter gå til scoop nummer 38 af nonce 1 og bruge det scoops data til at beregne en deadlineværdi.

Processen gentages for at beregne deadline for hver nonce, der holdes på minearbejderens harddisk. Efter beregningen af alle fristerne vælges den med minimumsfristen af minearbejderen.

En deadline repræsenterer varigheden af tid i sekunder, der skal gå siden den sidste blok blev smedet, før en minearbejder får lov til at smede en ny blok. Hvis ingen andre har smedet en blok inden for denne tid, kan minearbejderen smede en blok og gøre krav på blokbelønningen.

For eksempel, hvis miner X kommer med en minimumsfrist på 36 sekunder, og ingen andre minearbejdere kan forfalske blokken inden for de næste 36 sekunder, vil X sikre sig chancen for at smede den næste blok og blive belønnet.

## Fordele og ulemper ved bevis for kapacitet

PoC har flere fordele i forhold til PoW- og PoS-systemer, samt nogle vigtige ulemper, der inkluderer:

<h5><a href="">TTT</a></h5>

##Højdepunkter

- Den største fordel ved et PoC-system er dets effektivitet sammenlignet med proof-of-work (PoW) og proof-of-stake (PoS) systemer.

- Blockchains, der kører på bevis for kapacitet, omfatter Storj, Burst, Chia og SpaceMint.

- Proof of Capacitet (PoC) godkendelsessystemer anvender ledig plads på en enheds harddisk til at gemme løsninger på et hashingproblem med kryptovaluta.

