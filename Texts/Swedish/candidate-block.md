---
keywords: Crypto
title: Kandidatblock
description: Kandidatblock. Ett tillfälligt block skapat av en gruvnod (gruvarbetare) för att lägga till blockkedjan för att ta emot blockbelöningarna.
---

# Kandidatblock
Med några få ord är ett kandidatblock ett block som en gruvnod (gruvarbetare) försöker bryta för att ta emot blockbelöningen. Så ett kandidatblock kan beskrivas som ett temporärt block som antingen kommer att valideras eller kasseras av nätverket. Gruvarbetare tävlar med varandra för att validera nästa block och lägga till det i blockkedjan, men först måste de skapa ett kandidatblock för att delta i gruvtävlingen.

Kandidatblock skapas av gruvarbetare genom att samla in och organisera flera obekräftade transaktioner från minnespoolen. Transaktionerna hashas sedan för att bilda en [Merkle-trädstruktur](/merkle-tree),. som så småningom kommer att producera en Merkle-rot (eller root-hash). Merkle-roten är en enda hash som representerar alla tidigare hash i det trädet, och därför alla transaktioner som ingick i det specifika blocket.

Rothash - tillsammans med föregående blocks hash och ett slumptal som kallas [nonce](/nonce) - läggs sedan in i blockets rubrik. Blockhuvudet hashas sedan av gruvarbetaren och genererar en utdata baserat på dessa komponenter (root-hash, föregående blocks hash och nonce) plus några andra element. Den resulterande utgången är blockhash och kommer att fungera som en unik identifierare för det nygenererade blocket (kandidatblock).

För att anses vara giltig måste utdata (blockhash) börja med ett visst antal nollor (mindre än ett målvärde som definieras av protokollet). Detta innebär att gruvprocessen är baserad på flera försök (trial and error) eftersom gruvnoderna måste utföra en myriad av hashfunktioner med olika nonce-värden tills en giltig blockhash så småningom produceras. Blockhashen som produceras är det som bevisar att gruvarbetaren gjorde sitt arbete (därav bevis på arbete).

Efter att en gruvarbetare har hittat en giltig blockhash kommer deras kandidatblock att sändas till resten av nätverkets noder, vilket kommer att verifiera hashens äkthet. Om allt är bra kommer kandidatblocket sedan att registreras i blockkedjan. Vid denna tidpunkt uppdaterar varje validerande nod sin kopia av blockkedjedata för att återspegla det senaste minerade blocket, och gruvarbetaren kommer att få blockbelöningen.

