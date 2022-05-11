---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Bevis på kapacitet (kryptovaluta)
description: Proof of Capacity är en konsensusmekanism som använder en gruvnods hårddiskutrymme för att bestämma nätverket om gruvrättigheterna på blockkedjan.
---

# Bevis på kapacitet (kryptovaluta)
## Vad är kapacitetsbevis (PoC) för kryptovalutor?

Bevis på kapacitet (PoC) är en [konsensusmekanismalgoritm som](/consensus-mechanism-cryptocurrency) används i blockkedjor som gör det möjligt för [gruvenheter](/bitcoin-mining) i nätverket att använda sitt tillgängliga hårddiskutrymme för att bestämma gruvrättigheter och validera transaktioner. Detta i motsats till att använda gruvenhetens beräkningskraft (som i algoritmen för [bevis på arbete](/proof-work) ) eller gruvarbetarens andel i kryptovalutorna (som i algoritmen för [bevis på insats](/proof-stake-pos) ).

## Förstå bevis på kapacitet

Bevis på kapacitet har dykt upp som en av de många alternativa lösningarna på problemet med hög energiförbrukning i proof of work (PoW) system och kryptovaluta hamstring i proof of stake (PoS) system.

Bevis på kapacitet gör att gruvenheterna, även kända som noder, på [blockchain](/blockchain) -nätverket kan använda tomt utrymme på sin hårddisk för att bryta de tillgängliga [kryptovalutorna](/cryptocurrency).

Istället för att upprepade gånger ändra siffrorna i blockhuvudet och upprepade hashningar för lösningsvärdet som i ett PoW-system, fungerar PoC genom att lagra en lista med möjliga lösningar på gruvenhetens hårddisk redan innan gruvaktiviteten börjar.

Ju större hårddisk, desto fler möjliga lösningsvärden kan man lagra på hårddisken, desto större chans har en gruvarbetare att matcha det nödvändiga hashvärdet från sin lista, vilket resulterar i fler chanser att vinna gruvbelöningen.

För att dra en analogi, om lotteribelöningar baseras på att matcha flest siffror på den vinnande lotten, kommer en spelare med en längre lista med möjliga lösningar att ha bättre chanser att vinna. Dessutom tillåts spelaren fortsätta använda lottoblocksnumren om och om igen upprepade gånger.

[Burstcoin](/burstcoin) är en kryptovaluta som använder ett kapacitetssystem. Andra mynt som använder det är Storj, Chia och SpaceMint.

## Hur PoC fungerar: plottning och gruvdrift

Protokollet för kapacitetsbevis involverar en tvåstegsprocess som involverar plottning och gruvdrift.

Först plottas hårddisken: listan över alla möjliga [icke-](/nonce) värden skapas genom upprepad hash av data, inklusive en gruvarbetares konto. Varje sådan nonce innehåller 8192 hashar, som är numrerade från 0 till 8191. Alla hash är parade till "scoops", vilket innebär att intilliggande hashar kombineras för att bilda ett par av två. Till exempel utgör hash 0 och 1 scoop 0, hash 2 och 3 utgör hash 1, och så vidare.

Det andra steget involverar själva gruvövningen, under vilken en gruvarbetare beräknar ett scoopnummer. Till exempel, om en gruvarbetare börjar gruvaktiviteten och genererar ett scoop nummer 38, skulle gruvarbetaren sedan gå till scoop nummer 38 av nonce 1 och använda det scoopets data för att beräkna ett deadlinevärde.

Processen upprepas för att beräkna deadline för varje nonce som hålls på gruvarbetarens hårddisk. Efter beräkningen av alla deadlines väljs den med minsta deadline av gruvarbetaren.

En deadline representerar hur lång tid i sekunder som måste förflyta sedan det sista blocket smiddes innan en gruvarbetare tillåts smida ett nytt block. Om ingen annan har förfalskat ett block inom denna tid, kan gruvarbetaren förfalska ett block och göra anspråk på blockbelöningen.

Till exempel, om gruvarbetare X kommer med en minsta deadline på 36 sekunder och inga andra gruvarbetare kan förfalska blocket inom de närmaste 36 sekunderna, kommer X att säkra chansen att smida nästa block och bli belönad.

## För- och nackdelar med bevis på kapacitet

PoC har flera fördelar jämfört med PoW- och PoS-system, samt några viktiga nackdelar som inkluderar:

<h5><a href="">TTT</a></h5>

##Höjdpunkter

- Den största fördelen med ett PoC-system är dess effektivitet jämfört med proof-of-work (PoW) och proof-of-stake (PoS) system.

- Blockkedjor som körs på bevis på kapacitet inkluderar Storj, Burst, Chia och SpaceMint.

- Bevis på kapacitet (PoC) autentiseringssystem använder ledigt utrymme på en enhets hårddisk för att lagra lösningar på ett hashproblem med kryptovaluta.

