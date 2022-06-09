---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Prova di capacità (criptovaluta)
description: La prova di capacità è un meccanismo di consenso che utilizza lo spazio su disco rigido di un nodo di mining per decidere i diritti di mining sulla rete blockchain.
---

# Prova di capacità (criptovaluta)
## Che cos'è la prova di capacità (PoC) per le criptovalute?

La prova della capacità (PoC) è un algoritmo del [meccanismo di consenso](/consensus-mechanism-cryptocurrency) utilizzato nelle blockchain che consente ai dispositivi di [mining](/bitcoin-mining) nella rete di utilizzare lo spazio disponibile sul disco rigido per decidere i diritti di mining e convalidare le transazioni. Ciò è in contrasto con l'utilizzo della potenza di calcolo del dispositivo di mining (come nell'algoritmo [proof of work](/proof-work) ) o della partecipazione del minatore nelle criptovalute (come nell'algoritmo [proof of stake](/proof-stake-pos) ).

## Comprensione della prova di capacità

La prova di capacità è emersa come una delle tante soluzioni alternative al problema dell'elevato consumo di energia nei sistemi Proof of Work (PoW) e dell'accaparramento di criptovalute nei sistemi Proof of Stake (PoS).

La prova di capacità consente ai dispositivi di mining, noti anche come nodi, sulla rete [blockchain](/blockchain) di utilizzare lo spazio vuoto sul proprio disco rigido per estrarre le [criptovalute disponibili](/cryptocurrency).

Invece di alterare ripetutamente i numeri nell'intestazione del blocco e ripetere l'hashing per il valore della soluzione come in un sistema PoW, il PoC funziona archiviando un elenco di possibili soluzioni sul disco rigido del dispositivo di mining anche prima dell'inizio dell'attività di mining.

Più grande è il disco rigido, maggiori sono i valori di soluzione possibili che si possono memorizzare sul disco rigido, maggiori sono le possibilità che un minatore corrisponda al valore hash richiesto dalla sua lista, con conseguente maggiore possibilità di vincere il premio di mining.

Per fare un'analogia, se i premi della lotteria si basano sull'abbinamento del maggior numero di numeri sul biglietto vincente, un giocatore con un elenco più lungo di possibili soluzioni avrà maggiori possibilità di vincere. Inoltre, il giocatore può continuare a utilizzare i numeri di blocco dei biglietti della lotteria ancora e ancora ripetutamente.

[Burstcoin](/burstcoin) è una criptovaluta che utilizza un sistema di prova di capacità. Altre monete che lo utilizzano sono Storj, Chia e SpaceMint.

## Come funziona PoC: plotting e mining

Il protocollo proof-of-capacità prevede un processo in due fasi che prevede il tracciamento e l'estrazione mineraria.

Per prima cosa, viene tracciato il disco rigido: l'elenco di tutti i possibili valori [nonce](/nonce) viene creato attraverso l'hashing ripetuto dei dati, incluso l'account di un minatore. Ciascuno di questi nonce contiene 8192 hash, numerati da 0 a 8191. Tutti gli hash sono accoppiati in "scoop", il che significa che gli hash adiacenti vengono combinati per formare una coppia di due. Ad esempio, hash 0 e 1 costituiscono scoop 0, hash 2 e 3 costituiscono hash 1 e così via.

Il secondo passaggio prevede l'esercizio di mining vero e proprio, durante il quale un minatore calcola un numero di scoop. Ad esempio, se un minatore inizia l'attività di mining e genera uno scoop numero 38, il minatore andrà allo scoop numero 38 di nonce 1 e utilizzerà i dati di quello scoop per calcolare un valore di scadenza.

Il processo viene ripetuto per calcolare la scadenza per ogni nonce trattenuto sul disco rigido del minatore. Dopo il calcolo di tutte le scadenze, viene scelta dal minatore quella con la scadenza minima.

Una scadenza rappresenta la durata in secondi che deve trascorrere da quando l'ultimo blocco è stato falsificato prima che un minatore possa creare un nuovo blocco. Se nessun altro ha falsificato un blocco entro questo tempo, il minatore può creare un blocco e richiedere la ricompensa del blocco.

Ad esempio, se il minatore X arriva con una scadenza minima di 36 secondi e nessun altro minatore può falsificare il blocco entro i prossimi 36 secondi, X si assicurerà la possibilità di creare il blocco successivo e ottenere una ricompensa.

## Pro e contro della prova di capacità

PoC presenta diversi vantaggi rispetto ai sistemi PoW e PoS, oltre ad alcuni importanti svantaggi che includono:

<h5><a href="">TTT</a></h5>

## Mette in risalto

- Il principale vantaggio di un sistema PoC è la sua efficienza rispetto ai sistemi proof-of-work (PoW) e proof-of-stake (PoS).

- Le blockchain che funzionano a prova di capacità includono Storj, Burst, Chia e SpaceMint.

- I sistemi di autenticazione Proof of Capacity (PoC) utilizzano lo spazio libero sul disco rigido di un dispositivo per archiviare le soluzioni a un problema di hashing di criptovaluta.

