---
keywords: Crypto
title: Oanvänd transaktionsutdata (UTXO)
description: Oanvänd transaktionsutdata (UTXO). En utdata som skapas i en transaktion, som måste refereras till i en framtida transaktion för att spendera pengar.
---

# Oanvänd transaktionsutdata (UTXO)
En outnyttjad transaktionsutgång (UTXO) hänvisar till en transaktionsutgång som kan användas som indata i en ny transaktion. I huvudsak definierar UTXO var varje blockchain-transaktion börjar och slutar. UTXO-modellen är en grundläggande del av Bitcoin och många andra kryptovalutor.

Med andra ord görs kryptovalutatransaktioner av ingångar och utgångar. Varje gång en transaktion görs tar en användare en eller flera UTXO för att fungera som indata. Därefter tillhandahåller användaren sin digitala signatur för att bekräfta äganderätten till ingångarna, vilket slutligen resulterar i utdata. De UTXO som konsumeras anses nu vara "förbrukade" och kan inte längre användas. Samtidigt blir utdata från transaktionen nya UTXO - som kan spenderas i en ny transaktion senare.

Detta förklaras förmodligen bättre med ett exempel. Alice har 0,45 BTC i sin plånbok. Det här är inte en bråkdel av ett mynt som vi skulle kunna föreställa oss det. Det är snarare en samling UTXO. Specifikt två UTXO värda 0,4 BTC och 0,05 BTC - utdata från tidigare transaktioner. Låt oss nu föreställa oss att Alice behöver göra en betalning till Bob på 0,3 BTC.

Hennes enda alternativ här är att bryta upp 0,4 BTC-enheten och skicka 0,3 BTC till Bob och 0,1 BTC tillbaka till sig själv. Hon skulle normalt kräva tillbaka mindre än 0,1 BTC på grund av gruvavgifter, men låt oss förenkla och lämna gruvarbetaren utanför.

Alice skapar en transaktion som i huvudsak säger till nätverket: ta min 0,4 BTC UTXO som en ingång, bryt upp den, skicka 0,3 BTC av den till Bobs adress och returnera 0,1 BTC till min adress. 0,4 BTC är nu en förbrukad utgång och kan inte återanvändas. Under tiden har två nya UTXO skapats (0,3 BTC och 0,1 BTC).

Notera att vi bröt upp en UTXO i det här exemplet, men om Alice var tvungen att betala 0,42 BTC, kunde hon lika gärna ha kombinerat sina 0,4 BTC med ytterligare 0,05 BTC för att producera en UTXO värd 0,42 BTC, samtidigt som hon lämnade tillbaka 0,03 BTC till sig själv.

Sammanfattningsvis fungerar UTXO-modellen som protokollets mekanism för att hålla reda på var mynten finns vid varje given tidpunkt. På sätt och vis fungerar de ungefär som checkar: de är adresserade till specifika användare (eller snarare deras offentliga [adresser](/address) ). UTXO kan inte spenderas delvis – istället måste nya kontroller skapas från den gamla och skickas vidare därefter.

