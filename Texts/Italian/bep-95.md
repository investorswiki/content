---
keywords: Crypto
title: BEP-95
description: BEP-95. BEP-95 è una Proposta di Binance Evolution che introduce un meccanismo di masterizzazione in tempo reale su Binance Smart Chain. Rende la tokenomica BNB più dinamica e decentralizzata.
---

# BEP-95
BEP-95 è una Proposta di Binance Evolution che introduce un meccanismo di masterizzazione in tempo reale su Binance Smart Chain. È stato introdotto per rendere la tokenomica di BNB ancora più dinamica e decentralizzare ulteriormente la rete.

Con BEP-95, la rete brucerà un rapporto fisso delle tariffe del gas di ciascun blocco che i validatori raccolgono. Il rapporto esatto sarà determinato tramite i meccanismi di governance di BSC. Le ustioni avverranno anche dopo che BSC avrà raggiunto l'obiettivo di 100 milioni di BNB. Riducendo l'offerta di BNB, viene esercitata una pressione al rialzo sul prezzo della moneta. Il BEP può anche diminuire la quantità di deleganti e validatori BNB ricevuti. Tuttavia, con la pressione al rialzo dei prezzi, anche il valore della fiat potrebbe aumentare, compensando l'eventuale riduzione delle monete.

Per implementarlo tecnicamente, la rete raccoglie le tariffe del gas di ciascun blocco e le divide tra due contratti intelligenti:

**1. Contratto System Reward.** 1/16 del canone gas entrerà a far parte del Contratto System Reward fino al raggiungimento di un massimo di 100 BNB. Queste monete saranno utilizzate come sussidi per i pacchetti a catena incrociata.

**2. Contratto ValidatorSet.** Tutte le altre tariffe gas entreranno nel Contratto ValidatorSet e saranno condivise giornalmente con deleganti e validatori tramite Binance Chain.

Per eseguire una masterizzazione, il contratto ValidatorSet dispone di una variabile burnRatio. Al termine di ogni blocco, un validatore firmerà una transazione trasferendo le sue tariffe gas agli smart contract. La funzione di deposito contiene una logica di masterizzazione che attiva la semplice formula: burnRatio * gasFee. Questa somma verrà quindi trasferita all'indirizzo di masterizzazione. Il burnRatio sarà inizialmente impostato al 10%.

I validatori BSC potranno votare tramite proposte per modificare l'importo di burnRatio. Questo meccanismo di governance avviene su Binance Chain e qualsiasi membro della community può presentare una proposta di revisione con un deposito minimo di 2.000 BNB. Tutti i BNB scommessi dietro una proposta e in un voto vengono restituiti dopo che è stata presa una decisione. Il quorum viene raggiunto al 50% e la modifica verrà implementata immediatamente tramite la comunicazione cross-chain.

