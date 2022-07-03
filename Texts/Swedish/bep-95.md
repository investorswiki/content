---
keywords: Crypto
title: BEP-95
description: BEP-95. BEP-95 är ett Binance Evolution Proposal som introducerar en realtidsförbränningsmekanism till Binance Smart Chain. Det gör BNB tokenomics mer dynamisk och decentraliserad.
---

# BEP-95
BEP-95 är ett Binance Evolution Proposal som introducerar en realtidsförbränningsmekanism till Binance Smart Chain. Det har introducerats för att göra BNB:s tokenomics ännu mer dynamisk och ytterligare decentralisera nätverket.

Med BEP-95 kommer nätverket att bränna ett fast förhållande av varje blocks gasavgifter som validerare samlar in. Det exakta förhållandet kommer att bestämmas via BSC:s styrningsmekanismer. Bränningarna kommer att ske även efter att BSC har nått sitt mål på 100 miljoner BNB. Genom att minska utbudet av BNB sätts ett tryck uppåt på myntets pris. BEP kan också minska antalet BNB-delegatorer och validerare som tas emot. Men med uppåtgående prispress kan fiat-värdet också öka, vilket kompenserar för eventuell minskning av mynt.

För att tekniskt implementera detta samlar nätverket in varje blocks gasavgifter och delar upp mellan två smarta kontrakt:

**ett. System Reward Contract.** 1/16 av gasavgifterna kommer in i System Reward Contract tills det når maximalt 100 BNB. Dessa mynt kommer att användas som subventioner för paketöverskridande paket.

**2. ValidatorSet-kontrakt.** Alla andra gasavgifter kommer in i ValidatorSet-kontraktet och delas dagligen med delegatorer och validerare via Binance Chain.

För att utföra en bränning har ValidatorSet-kontraktet en burnRatio-variabel. När varje block har slutförts kommer en validator att underteckna en transaktion som överför sina gasavgifter till de smarta kontrakten. Deponeringsfunktionen innehåller brinnande logik som utlöser den enkla formeln: burnRatio * gasFee. Denna summa kommer sedan att överföras till brännadressen. Brännförhållandet kommer initialt att ställas in på 10 %.

BSC Validators kommer att kunna rösta via förslag om att ändra burnRatio-beloppet. Denna förvaltningsmekanism förekommer på Binance Chain, och alla medlemmar i communityn kan skicka in ett förslag för granskning med en minsta insättning på 2 000 BNB. Alla BNB satsade bakom ett förslag och i en omröstning returneras efter att beslut har fattats. Quorum nås till 50 %, och förändringen kommer att implementeras via kommunikation över kedjan omedelbart.

