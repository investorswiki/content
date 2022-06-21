---
keywords: Crypto
title: Dimezzamento
description: Dimezzamento. Quando la ricompensa in blocco di un asset crittografico, scende alla metà di quella che era prima; questo viene utilizzato per creare un tasso di emissione decrescente.
---

# Dimezzamento
Nello spazio delle criptovalute, il termine dimezzamento si riferisce a un processo che riduce il tasso di emissione di nuove monete. Più precisamente, dimezzamento è la riduzione periodica del sussidio di blocco erogato ai minatori. Il dimezzamento garantisce che un asset crittografico seguirà un tasso di emissione costante fino al raggiungimento della sua [offerta massima](/maximum-supply).

Quando si tratta di Bitcoin, le monete di notizie vengono generate continuamente come parte del [premio di blocco](/block-reward) (che è costituito dal sussidio di blocco più le commissioni di transazione). Quindi ogni volta che un miner "scopre" e convalida con successo un nuovo [blocco](/block),. guadagna monete appena create come compenso per il proprio lavoro.

Quindi il processo di [mining](/mining) è ciò che introduce nuovi [Bitcoin](/bitcoin) nel sistema, e questo avviene a un ritmo prevedibile e controllato. Nuovi blocchi Bitcoin vengono estratti, in media, ogni 10 minuti e il sussidio per blocchi segue un tasso di decadimento controllato. Di conseguenza, il dimezzamento è ciò che garantisce che il sussidio di blocco diminuirà del 50% ogni 210.000 blocchi (all'incirca ogni quattro anni).

A partire dal blocco di [genesi](/genesis-block),. il sussidio di blocco di Bitcoin è stato inizialmente fissato a 50 BTC. Quindi, è stato ridotto a 25 BTC nel 2012 ea 12,5 BTC nel 2016. Il successivo dimezzamento dovrebbe avvenire intorno a maggio 2020, riducendo il sussidio di blocco a 6,25 BTC. Una volta che si sono verificati 32 dimezzamenti, il processo si interrompe e non verranno più creati Bitcoin. A questo punto si raggiungerà la fornitura massima di 21 milioni di BTC.

[Segui l'halving di Bitcoin](/halving)

L'halving è una parte importante del protocollo Bitcoin e, poiché il codice è open-source, chiunque può vederlo. Ad esempio, l'implementazione di Bitcoin Core è disponibile su [GitHub](/github) e una delle sezioni di codice che definisce il sussidio di blocco è simile a questa:

CAmount GetBlockSubsidy(int nHeight, const Consensus::Params& consensusParams)

{

int halvings = nHeight/consensusParams.nSubsidyHalvingInterval;

// Forza la ricompensa del blocco a zero quando lo spostamento a destra non è definito.

se (dimezzamenti >= 64)

restituire 0;

Importo CA nSussidiazione = 50 * MONETA;

// Il sussidio viene dimezzato ogni 210.000 blocchi, il che avverrà all'incirca ogni 4 anni.

nSussidio >>= dimezzamento;

restituire nSussidio;

}

