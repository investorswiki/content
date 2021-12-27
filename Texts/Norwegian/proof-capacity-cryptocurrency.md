---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Kapasitetsbevis (kryptovaluta)
description: Proof of Capacity er en konsensusmekanisme som bruker en gruvenodes harddiskplass til å bestemme gruverettighetene på blokkjedenettverket.
---

# Kapasitetsbevis (kryptovaluta)
## Hva er bevis på kapasitet (PoC) for kryptovalutaer?

Proof of capacity (PoC) er en [konsensusmekanisme-](/consensus-mechanism-cryptocurrency) algoritme som brukes i blokkjeder som gjør det mulig for [gruveenheter](/bitcoin-mining) i nettverket å bruke sin tilgjengelige harddiskplass til å bestemme gruverettigheter og validere transaksjoner. Dette er i motsetning til å bruke gruveenhetens beregningskraft (som i [proof of work](/proof-work) -algoritmen) eller gruvearbeiderens eierandel i kryptovalutaene (som i [proof of stake -](/proof-stake-pos) algoritmen).

## Forstå bevis på kapasitet

Bevis på kapasitet dukket opp som en av de mange alternative løsningene på problemet med høyt energiforbruk i proof of work (PoW) systemer og kryptovaluta hamstring i proof of stake (PoS) systemer.

Bevis på kapasitet gjør at gruveenhetene, også kjent som noder, på [blokkjedenettverket](/blockchain) kan bruke tom plass på harddisken for å utvinne de tilgjengelige [kryptovalutaene](/cryptocurrency).

I stedet for gjentatte ganger å endre tallene i blokkoverskriften og gjentatt hashing for løsningsverdien som i et PoW-system, fungerer PoC ved å lagre en liste over mulige løsninger på gruveenhetens harddisk selv før gruveaktiviteten starter.

Jo større harddisken er, jo flere mulige løsningsverdier kan man lagre på harddisken, desto større sjanse har en gruvearbeider til å matche den nødvendige hashverdien fra listen sin, noe som resulterer i flere sjanser til å vinne gruvebelønningen.

For å trekke en analogi, hvis lotteribelønninger er basert på å matche flest tall på vinnerloddet, vil en spiller med en lengre liste over mulige løsninger ha bedre vinnersjanser. I tillegg har spilleren lov til å fortsette å bruke loddblokknumrene igjen og igjen gjentatte ganger.

[Burstcoin](/burstcoin) er en kryptovaluta som bruker et bevis på kapasitetssystem. Andre mynter som bruker det er Storj, Chia og SpaceMint.

## Hvordan PoC fungerer: plotting og gruvedrift

Protokollen for kapasitetsbevis innebærer en to-trinns prosess som involverer plotting og gruvedrift.

Først plottes harddisken: listen over alle mulige [ikke-](/nonce) verdier opprettes gjennom gjentatt hashing av data, inkludert en gruvearbeiders konto. Hver slik nonce inneholder 8192 hashes, som er nummerert fra 0 til 8191. Alle hashene er sammenkoblet i "scoops", som betyr at tilstøtende hashes kombineres for å danne et par av to. For eksempel utgjør hasj 0 og 1 scoop 0, hash 2 og 3 utgjør hasj 1, og så videre.

Det andre trinnet involverer selve gruveøvelsen, hvor en gruvearbeider beregner et scoopnummer. For eksempel, hvis en gruvearbeider begynner gruveaktiviteten og genererer et scoop nummer 38, vil gruvearbeideren gå til scoop nummer 38 av nonce 1 og bruke den scoopens data for å beregne en fristverdi.

Prosessen gjentas for å beregne fristen for hver nonce som holdes på gruvearbeiderens harddisk. Etter beregningen av alle fristene, velges den med minimumsfristen av gruvearbeideren.

En tidsfrist representerer varigheten av tiden i sekunder som må gå siden den siste blokken ble forfalsket før en gruvearbeider får lov til å smi en ny blokk. Hvis ingen andre har forfalsket en blokk innen denne tiden, kan gruvearbeideren forfalske en blokk og kreve blokkbelønningen.

For eksempel, hvis gruvearbeider X kommer opp med en minimumsfrist på 36 sekunder og ingen andre gruvearbeidere kan forfalske blokken innen de neste 36 sekundene, vil X sikre sjansen til å forfalske neste blokk og bli belønnet.

## Fordeler og ulemper med bevis på kapasitet

PoC har flere fordeler fremfor PoW- og PoS-systemer, samt noen viktige ulemper som inkluderer:

<h5><a href="">TTT</a></h5>

## Høydepunkter

– Hovedfordelen med et PoC-system er effektiviteten sammenlignet med proof-of-work (PoW) og proof-of-stake (PoS) systemer.

– Blokkjeder som kjører på bevis på kapasitet inkluderer Storj, Burst, Chia og SpaceMint.

- Proof of capacity (PoC) autentiseringssystemer bruker ledig plass på en enhets harddisk for å lagre løsninger på et hashingproblem med kryptovaluta.

