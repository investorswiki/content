---
keywords: Investing,Cryptocurrency,Altcoins
title: Målhash
description: En målhash anger svårigheten för brytning av kryptovaluta med hjälp av ett proof-of-work (PoW) blockchain-system.
---

# Målhash
## Vad är en målhash?

Vid brytning av kryptovalutor är en målhash ett numeriskt värde som en hashad [blockrubrik](/block-header-cryptocurrency) måste vara mindre än eller lika med för att ett nytt block ska kunna tilldelas en gruvarbetare. Blockrubriker identifierar enskilda block i en blockkedja.

Utvinning av kryptovaluta hänvisar till processen att samla kryptovaluta som en belöning för arbete som du utför. Arten av detta arbete är att verifiera legitimiteten för en given kryptovalutas transaktioner. På så sätt är gruvarbetare för kryptovaluta i huvudsak revisorer. När du bryter kan du tjäna kryptovaluta utan att behöva lägga ner pengar för det.

Målhashen används för att bestämma indatas svårighetsgrad och kan justeras för att säkerställa att blocken bearbetas effektivt. Till exempel används mål-hashar i kryptovalutor som använder ett proof-of-work (PoW)-system för att ställa in det aktuella [gruvproblemet](/difficulty-cryptocurrencies) [y](/difficulty-cryptocurrencies) (inklusive Bitcoin). Om en kryptovaluta använder ett annat system för gruvdrift, kanske det inte kräver en målhash.

## Hur en målhash fungerar

[Kryptovalutor](/cryptocurrency) förlitar sig på användningen av [blockkedjor](/blockchain) som innehåller historien om alla kryptovalutors transaktioner. Dessa transaktioner [hashas](/hash) eller kodas kryptografiskt till en serie alfanumeriska tecken. Hashing innebär att ta en datasträng av valfri längd och köra den genom en algoritm för att producera en utdata med en fast längd. Utdata kommer alltid att vara lika långa, oavsett hur stor eller liten ingången är (även om antalet permutationer av en hash är astronomiskt stort). Varje block kommer att innehålla hashen för föregående blockhuvud.

Validering och kodning av blockkedjan kallas [gruvdrift](/bitcoin-mining). Mining innebär användning av datorer för att köra hashalgoritmer för att bearbeta det senaste blocket; informationen som en användare behöver bryta finns i blockets header. Kryptovalutanätverket sätter ett målvärde för denna hash – kallad target-hash – och gruvarbetare försöker fastställa vad detta värde är genom att testa alla möjliga värden.

Blockhuvudet innehåller blockversionsnumret, en tidsstämpel, hashen som användes i föregående block, hashen för [Merkle Root](/merkle-root-cryptocurrency) [t](/merkle-root-cryptocurrency),. [nonce](/nonce) och målhash. Blocket genereras genom att ta hashen av blockinnehållet, lägga till en slumpmässig sträng av siffror (nonce) och hasha blocket igen.

Om hashen uppfyller kravet för målet läggs blocket till i blockkedjan. Att cykla igenom lösningar för att gissa nonce kallas [proof of work](/proof-work) (PoW), och gruvarbetaren som kan hitta värdet tilldelas blocket och betalas i kryptovaluta.

## Särskilda överväganden

### Målhash för Bitcoin

Bitcoin använder hashalgoritmen SHA-256. Denna algoritm genererar verifierbart slumpmässiga tal på ett sätt som kräver en förutsägbar mängd datorprocessorkraft.

Att bryta ett block kräver att gruvarbetaren producerar ett värde (en nonce) som efter att ha hashas (kryptografiskt kodat) är mindre än eller lika med det som användes i det senaste blocket som accepterades av bitcoinnätverket. Detta nummer är mellan 0- (det minsta alternativet) och 256-bitar (det största alternativet) men det är osannolikt att det någonsin kommer att vara det maximala antalet.

Eftersom målhashen kan vara ett stort antal, kan gruvarbetaren behöva testa ett stort antal värden innan han lyckas. En misslyckad gruvarbetare måste vänta på nästa block (vilket är anledningen till att gruvarbetare som hittar en hashlösning liknas vid vinnare av ett lopp eller lotteri).

Målhashen justeras med jämna mellanrum. Hashfunktionerna som används för att generera det nya målet har specifika egenskaper utformade för att göra blockkedjan (och dess kryptovaluta) säker. Denna process är deterministisk, vilket innebär att den kommer att ge samma resultat varje gång samma input används. Det är tillräckligt snabbt för att det inte tar för lång tid att returnera en hash för inmatningen. Det gör också att bestämma inmatningen mycket svårt, särskilt för stora antal, och gör små ändringar i inmatningen resulterar i en mycket annorlunda hash-utdata.

## Höjdpunkter

- Målhaschar används i kryptovalutor som använder ett proof-of-work (PoW)-system för att ställa in den aktuella gruvsvårigheten (inklusive Bitcoin); om en kryptovaluta använder ett annat system för gruvdrift kanske det inte kräver en målhash.

- I cryptocurrency mining är en target hash ett numeriskt värde som en hashed blockheader (som används för att identifiera enskilda block i en blockchain) måste vara mindre än eller lika med för att ett nytt block ska kunna tilldelas en gruvarbetare.

- Bitcoin-nätverket justerar svårigheten att bryta genom att höja eller sänka mål-hash för att bevara ett genomsnittligt 10-minutersintervall mellan nya block.

