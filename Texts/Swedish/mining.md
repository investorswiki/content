---
keywords: Crypto
title: Brytning
description: Brytning. Verifiering av transaktioner på ett blockchain-nätverk, där transaktioner läggs till som poster i blockchain-reskontran.
---

# Brytning
Gruvdrift är den process genom vilken [kryptovalutatransaktioner](/cryptocurrency) samlas in, verifieras och registreras i en digital reskontra känd som [blockchain](/blockchain). Det arbete som utförs av gruvarbetare är avgörande för att upprätthålla nätverkets integritet och är också ansvarigt för att introducera nya mynt i systemet.

Inom det traditionella banksystemet skrivs fiat-valuta ut och distribueras av finansinstitutioner och statliga myndigheter – men för de flesta kryptovalutor är utgivningen av nya mynt inte i händerna på centraliserade enheter. Istället genereras nya kryptovalutaenheter genom gruvprocessen, som följer en fördefinierad uppsättning regler som fastställts av det underliggande protokollet. Medan protokollet definierar vad de primära reglerna är, skisserar de så kallade konsensusalgoritmerna hur dessa regler kommer att följas (till exempel under valideringen av transaktioner).

Om man tar Bitcoin som ett exempel, de deltagare som är involverade i gruvprocessen kallas gruvnoder (eller bara gruvarbetare), och de spelar en nyckelroll i säkerheten för blockchain-nätverket. En gruvarbetares jobb är att samla obekräftade transaktioner från minnespoolen och organisera dem i ett [kandidatblock](/candidate-block) som de kommer att försöka validera.

När man skapar ett kandidatblock inkluderar en gruvarbetare en transaktion där de skickar [blockbelöningen](/block-reward) till sig själva. Denna transaktion är känd som en myntbastransaktion och är ofta den första som registreras i ett block.

Efter att listan över obekräftade transaktioner har skapats hashas varje transaktion och deras utdata organiseras i par. Dessa par hashas sedan, vilket ger nya utdata som också organiseras i par och hashas igen. Processen upprepas tills en enda hash produceras, vilket kallas rothash eller [Merkle tree](/merkle-tree) root.

Rothashen kombineras sedan med hashen för det tidigare bekräftade blocket, tillsammans med ett pseudoslumptal som kallas [nonce](/nonce) (plus några andra parametrar). Dessa element hashas sedan och producerar blockhash för det kandidatblocket.

Mineraren kommer dock bara att lyckas om den resulterande utdata (blockhash) för deras kandidatblock ligger under ett förutbestämt värde (mål). Följaktligen är processen baserad på trial and error och de behöver utföra många hashfunktioner med olika nonces för att hitta ett giltigt resultat. Den första gruvarbetaren att hitta en giltig hash validerar sitt kandidatblock och får blockbelöningen. Hela processen tar i genomsnitt tio minuter.

När ett block väl har validerats läggs det till i blockkedjan och gruvarbetare börjar arbeta med nästa block. Den giltiga hashen som produceras av gruvarbetare fungerar som beviset för deras arbete och det är därför Bitcoin konsensusalgoritmen kallas Proof of Work. Varje bekräftat block har en unik blockhash som fungerar som en identifierare.

Blockbelöningen definieras av Bitcoin-protokollet och minskar vart 210 000:e block (cirka fyra år) [.](/block-reward) Ursprungligen var blockbelöningen 50 BTC och är nu 12,5 BTC.

