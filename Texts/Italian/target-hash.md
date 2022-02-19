---
keywords: Investing,Cryptocurrency,Altcoins
title: Hash di destinazione
description: Un hash target imposta la difficoltà per il mining di criptovalute utilizzando un sistema blockchain proof-of-work (PoW).
---

# Hash di destinazione
## Che cos'è un hash target?

Nel mining di criptovalute, un hash target è un valore numerico a cui l' [intestazione di un blocco con hash](/block-header-cryptocurrency) deve essere inferiore o uguale affinché un nuovo blocco venga assegnato a un minatore. Le intestazioni dei blocchi identificano i singoli blocchi in una blockchain.

Il mining di criptovalute si riferisce al processo di raccolta della criptovaluta come ricompensa per il lavoro che completi. La natura di questo lavoro è verificare la legittimità delle transazioni di una determinata criptovaluta. In questo modo, i minatori di criptovaluta sono essenzialmente dei revisori dei conti. Quando estrai, puoi guadagnare criptovaluta senza dover spendere soldi per questo.

L'hash di destinazione viene utilizzato per determinare la difficoltà dell'input e può essere regolato per garantire che i blocchi vengano elaborati in modo efficiente. Ad esempio, gli hash target vengono utilizzati nelle criptovalute che utilizzano un sistema proof-of-work (PoW) per impostare la [difficoltà di mining corrente](/difficulty-cryptocurrencies) [y](/difficulty-cryptocurrencies) (incluso Bitcoin). Se una criptovaluta utilizza un sistema diverso per il mining, potrebbe non richiedere un hash di destinazione.

## Come funziona un hash target

[Le criptovalute](/cryptocurrency) si basano sull'uso di [blockchain](/blockchain) che contengono la cronologia di tutte le transazioni di quella criptovaluta. Queste transazioni sono codificate [tramite hash](/hash) o crittograficamente in una serie di caratteri alfanumerici. L'hashing implica il prelievo di una stringa di dati di qualsiasi lunghezza e l'esecuzione attraverso un algoritmo per produrre un output con una lunghezza fissa. L'output sarà sempre della stessa lunghezza, indipendentemente da quanto sia grande o piccolo l'input (sebbene il numero di permutazioni di un hash sia astronomicamente grande). Ogni blocco conterrà l'hash dell'intestazione del blocco precedente.

La convalida e la codifica della blockchain viene definita [mining](/bitcoin-mining). Il mining implica l'uso di computer per eseguire algoritmi di hashing per elaborare il blocco più recente; le informazioni che un utente ha bisogno di estrarre si trovano nell'intestazione del blocco. La rete di criptovaluta imposta un valore target per questo hash, chiamato hash target, e i minatori cercano di determinare quale sia questo valore testando tutti i valori possibili.

L'intestazione del blocco contiene il numero di versione del blocco, un timestamp, l'hash utilizzato nel blocco precedente, l'hash di [Merkle Roo](/merkle-root-cryptocurrency) [t](/merkle-root-cryptocurrency),. [il nonce](/nonce) e l'hash di destinazione. Il blocco viene generato prendendo l'hash del contenuto del blocco, aggiungendo una stringa casuale di numeri (il nonce) e ripetendo l'hashing del blocco.

Se l'hash soddisfa i requisiti del target, il blocco viene aggiunto alla blockchain. Il ciclo delle soluzioni per indovinare il nonce viene indicato come [Proof of Work](/proof-work) (PoW) e il minatore che è in grado di trovare il valore riceve il blocco e viene pagato in criptovaluta.

## Considerazioni speciali

### Hash target per Bitcoin

Bitcoin utilizza l'algoritmo hash SHA-256. Questo algoritmo genera numeri verificabili casuali in un modo che richiede una quantità prevedibile di potenza di elaborazione del computer.

Il mining di un blocco richiede al miner di produrre un valore (a nonce) che, dopo essere stato sottoposto a hash (codificato crittograficamente), è inferiore o uguale a quello utilizzato nel blocco più recente accettato dalla rete bitcoin. Questo numero è compreso tra 0- (l'opzione più piccola) e 256 bit (l'opzione più grande), ma è improbabile che sia mai il numero massimo.

Poiché l'hash di destinazione potrebbe essere un numero enorme, il minatore potrebbe dover testare un numero elevato di valori prima di avere successo. Un minatore senza successo deve aspettare il blocco successivo (ecco perché i minatori che trovano una soluzione hash sono paragonati ai vincitori di una corsa o della lotteria).

L'hash di destinazione viene regolato periodicamente. Le funzioni hash utilizzate per generare il nuovo target hanno proprietà specifiche progettate per rendere sicura la blockchain (e la sua criptovaluta). Questo processo è deterministico, il che significa che produrrà lo stesso risultato ogni volta che viene utilizzato lo stesso input. È abbastanza veloce da non richiedere troppo tempo per restituire un hash per l'input. Inoltre, rende molto difficile determinare l'input, specialmente per numeri grandi, e apporta piccole modifiche all'input in un output hash molto diverso.

## Mette in risalto

- Gli hash target vengono utilizzati nelle criptovalute che utilizzano un sistema di prova del lavoro (PoW) per impostare l'attuale difficoltà di mining (incluso Bitcoin); se una criptovaluta utilizza un sistema diverso per il mining, potrebbe non richiedere un hash di destinazione.

- Nel mining di criptovalute, un hash target è un valore numerico a cui un'intestazione di blocco hash (utilizzata per identificare i singoli blocchi in una blockchain) deve essere inferiore o uguale affinché un nuovo blocco venga assegnato a un minatore.

- La rete Bitcoin regola la difficoltà del mining alzando o abbassando l'hash target per preservare un intervallo medio di 10 minuti tra i nuovi blocchi.

