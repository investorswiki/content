---
keywords: Crypto
title: Mempool
description: Mempool. Il meccanismo di un nodo per tenere traccia delle transazioni non confermate che il nodo ha visto (ma non sono state ancora aggiunte a un blocco).
---

# Mempool
Un mempool (una contrazione di memoria e pool) è un meccanismo di un nodo di criptovaluta per archiviare informazioni su transazioni non confermate. Funziona come una sorta di sala d'attesa per le transazioni che non sono state ancora incluse in un [blocco](/block).

Quando una transazione viene trasmessa, viene inviata da un nodo ai suoi peer, che poi la passeranno ai loro peer. Ciò continua fino a quando la transazione non è stata ampiamente propagata, pronta per i minatori di aggiungerla a un blocco. È fondamentale che questa zona cuscinetto esista, poiché le transazioni non vengono aggiunte immediatamente alla blockchain.

I nodi eseguiranno una serie di controlli per garantire che la transazione sia valida, vale a dire, verificando che le firme siano corrette, che gli output non superino gli input e che i fondi non siano già stati spesi. Se non soddisfa queste condizioni, viene rifiutato.

Si parla spesso di mempool, ma va notato che non esiste un pool universale condiviso da tutti i nodi. Ognuno è configurato in modo diverso e riceve transazioni in momenti diversi. I dispositivi di fascia bassa con risorse limitate possono dedicare solo piccole quantità di memoria alla registrazione delle transazioni, mentre quelli di fascia alta potrebbero dedicare molto di più.

Poiché i minatori sono motivati principalmente dai profitti, le transazioni con commissioni più elevate sono quelle che più probabilmente verranno scartate dal mempool per prime quando vengono confermate. Una stima precisa delle commissioni è difficile, in particolare quando lo spazio dei blocchi è limitato e la domanda è elevata, ma il mempool fornisce un punto di partenza.

Per stimare le commissioni, si può guardare alle transazioni correnti non confermate. È logico che gli utenti non dovrebbero pagare più del dovuto in tempi di bassa velocità effettiva. Né dovrebbero sottopagare le transazioni sensibili al fattore tempo nelle ore di punta, poiché potrebbe volerci un po' prima che venga confermato. Tenendo conto della diffusione delle commissioni in un dato momento, possono fare un'ipotesi plausibile su quanto velocemente verrà inclusa la loro transazione.

