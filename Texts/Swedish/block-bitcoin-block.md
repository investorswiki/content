---
keywords: Investing,Cryptocurrency,Blockchain
title: Block (Bitcoin Block)
description: Block är datastrukturer inom en databas där transaktionsdata för kryptovaluta registreras permanent; när den väl har skrivits kan den inte ändras eller tas bort.
---

# Block (Bitcoin Block)
## Vad är ett block (Blockchain Block)?

Block är datastrukturer inom blockkedjedatabasen, där transaktionsdata i en kryptovaluta blockkedja registreras permanent. Ett block registrerar några eller alla av de senaste transaktionerna som ännu inte har validerats av nätverket. När data väl har validerats stängs blocket. Sedan skapas ett nytt block för att nya transaktioner ska ingås och valideras.

Ett block är alltså ett permanent lager av poster som, när de väl skrivits, inte kan ändras eller tas bort.

## Hur ett block (Blockchain Block) fungerar

Ett [blockchain](/blockchain) -nätverk upplever en hel del transaktionsaktivitet. När det används i kryptovaluta, hjälper ett register över dessa transaktioner systemet att spåra hur mycket som användes eller inte användes och vilka parter som var inblandade. Transaktionerna som görs under en given period registreras i en fil som kallas ett block, vilket är grunden för blockchain-nätverket.

Ett block lagrar information. Det finns många delar av information som ingår i ett block, men det tar inte upp en stor mängd lagringsutrymme. Block innehåller vanligtvis dessa element, men det kan variera mellan olika typer:

- **Magiskt nummer**: Ett nummer som innehåller specifika värden som identifierar det blocket som en del av en viss kryptovalutas nätverk.

- **Blockstorlek**: Ställer in storleksgränsen på blocket så att endast en specifik mängd information kan skrivas i det.

- **Blockhuvud**: Innehåller information om blocket.

- **Transaktionsräknare**: Ett tal som representerar hur många transaktioner som är lagrade i blocket.

- **Transaktioner**: En lista över alla transaktioner inom ett block.

Transaktionselementet är störst eftersom det innehåller mest information. Den följs i lagringsstorlek av blockhuvudet, som inkluderar dessa underelement:

- **Version**: Den kryptovalutaversion som används.

- **Föregående blockhash**: Innehåller en hash (krypterat nummer) av föregående blocks rubrik.

- **Hash Merkle root**: Hash av transaktioner i [Merkle-trädet](/merkle-tree) i det aktuella blocket.

- **Tid**: En tidsstämpel för att placera blocket i blockkedjan.

- **Bits**: Svårighetsgraden för målhashen, vilket anger svårigheten att lösa nonce.

- **Nonce**: Det krypterade numret som en gruvarbetare måste lösa för att verifiera blocket och stänga det.

Ett 32-bitars nummer i rubriken kallas nonce – gruvprogrammet använder slumptal för att "gissa" nonce i [hashen](/hash). När en nonce verifieras, löses hashen när nonce, eller ett antal mindre än det, gissas. Sedan stänger nätverket det blocket, genererar ett nytt med en rubrik och processen upprepas.

olika mekanismer används för att nå konsensus; den mest populära för kryptovaluta är [proof-of-work](/proof-work) (PoW), där proof-of-stake (PoS) blir mer så på grund av den minskade energiförbrukningen jämfört med PoW.

## Gruvdriftens förhållande till block

Mining är termen som används för att lösa talet som är nonce, det enda numret som kan ändras i en blockrubrik. Det är också den process som kryptovalutans nätverk använder om proof-of-work används i protokollet.

Utvinning av kryptovalutor anses allmänt vara ett komplext matematiskt problem; det är faktiskt ett slumptal som genereras genom hash. Hashing är processen att kryptera information med den krypteringsmetod som en kryptovaluta använder. Till exempel använder Bitcoin SHA256 för sin krypteringsalgoritm. För att en gruvarbetare ska generera det "vinnande" numret måste gruvprogrammet använda SHA 256 för att hasha slumpmässiga nummer och placera dem i nonce för att se om det är en matchning.

> Att lösa hash för slumptal under protokollet om arbetsbevis är det som tar så mycket energi och beräkningskraft. Ett omfattande nätverk av gruvarbetare och tillräckligt med energi för att driva ett litet land krävs för att hålla det igång.

>

Svårigheten ligger i att alla tidigare blockrubriker krypteras slumpmässigt. Följaktligen är det aktuella blockhuvudet ett slumpmässigt genererat krypterat nummer baserat på de slumpmässigt genererade krypterade numren av tidigare block och information från det aktuella blocket.

## Andra block- och blockkedjeanvändningar

Eftersom de flesta blockkedjedefinitioner refererar till Bitcoin eftersom det var den första kryptovalutan som använde en, associerar många människor block och blockkedjor med Bitcoin. Men även andra kryptovalutor använder block och blockkedjor. Det är viktigt att notera att Ethereums nätverk har en kryptovaluta som kallas eter som också använder block och blockchain.

Ethereum och dess blockchain designades dock för flera användningsområden som sträcker sig till mycket mer än kryptovaluta. Till exempel har icke-fungibla tokens, smarta kontrakt, decentraliserade finansapplikationer och mer utvecklats med Ethereum.

##Höjdpunkter

– Block och blockkedjor används inte enbart av kryptovalutor. De har också många andra användningsområden.

- Block identifieras med långa siffror som inkluderar krypterad transaktionsinformation från tidigare block och ny transaktionsinformation.

– Block och informationen i dem måste verifieras av ett nätverk innan nya block kan skapas.

– Ett block är en plats i en blockkedja där information lagras och krypteras.

##FAQ

### Vad är Blockchain i enkla ord?

En blockchain är en databas som lagrar och krypterar information på ett länkat sätt, så att tidigare information inte kan ändras, och en grupp verifierar eventuella poster innan de slutförs genom en konsensus – en överenskommelse om att data är korrekta.

### Vad används blockkedjor till?

Blockkedjor används i kryptovaluta, decentraliserade finansapplikationer, icke-fungibla tokens, med fler användningsområden ständigt under utveckling.

### Hur skapas ett blockkedjeblock?

Block skapas när gruvarbetare eller blockvaliderare framgångsrikt validerar den krypterade informationen i blockheadern, vilket uppmanar till skapandet av ett nytt block.

