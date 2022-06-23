---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Merkle Root (Criptovaluta)
description: Una radice Merkle contiene informazioni su ogni singolo hash di transazione che sia mai stato su un particolare blocco in una blockchain.
---

# Merkle Root (Criptovaluta)
## Che cos'è una radice Merkle?

Una radice Merkle è l' [hash](/hash) di tutti gli hash di tutte le transazioni che fanno parte di un blocco in una rete [blockchain](/blockchain).

## Capire una radice Merkle

Una blockchain è composta da vari blocchi collegati tra loro (da cui il nome blockchain). Un hash tree, o [Merkle tree](/merkle-tree),. codifica i dati blockchain in modo efficiente e sicuro. Consente la rapida verifica dei dati blockchain, nonché il rapido spostamento di grandi quantità di dati da un nodo di computer all'altro sulla rete blockchain peer-to-peer.

Ogni transazione che si verifica sulla rete blockchain ha un hash ad essa associato. Tuttavia, questi hash non sono archiviati in un ordine sequenziale sul blocco, piuttosto sotto forma di una struttura ad albero tale che ogni hash è collegato al suo genitore seguendo una relazione ad albero genitore-figlio.

Poiché ci sono numerose transazioni memorizzate su un particolare blocco, anche tutti gli hash delle transazioni nel blocco vengono sottoposti a hash, il che si traduce in una radice Merkle.

Ad esempio, considera un blocco di sette transazioni. Al livello più basso (chiamato livello foglia), ci saranno quattro hash di transazione. Al livello uno sopra il livello foglia, ci saranno due hash di transazione, ognuno dei quali si collegherà a due hash che si trovano al di sotto di essi al livello foglia. In alto (livello due), ci sarà l'ultimo hash di transazione chiamato root e si collegherà ai due hash sottostanti (al livello uno).

In effetti, ottieni un albero binario capovolto, con ogni nodo dell'albero che si connette solo a due nodi sotto di esso (da cui il nome "albero binario"). Ha un hash radice in alto, che si collega a due hash al livello uno, ognuno dei quali si collega nuovamente ai due hash al livello tre (livello foglia) e la struttura continua a seconda del numero di hash di transazione.

<!--AAFEB15A7406E8DD3ABDD652D7C85823-->

L'hashing inizia dai nodi di livello più basso (a livello di foglia) e tutti e quattro gli hash sono inclusi nell'hash dei nodi che sono collegati ad esso al livello uno. Allo stesso modo, l'hashing continua al livello uno, il che porta a hash di hash che raggiungono livelli più alti, fino a raggiungere l'hash di radice singola superiore.

Questo hash di root è chiamato radice di Merkle e, a causa del collegamento ad albero degli hash, contiene tutte le informazioni su ogni singolo hash di transazione esistente sul blocco. Offre un valore hash a punto singolo che consente di convalidare tutto ciò che è presente su quel blocco.

Ad esempio, se uno deve verificare una transazione che afferma di provenire dal blocco n. 137, deve solo controllare l'albero Merkle del blocco, senza preoccuparsi di verificare nulla su qualsiasi altro blocco sulla blockchain, come il blocco n. 136 o il blocco n. 138.

<!--4861E8697637B7236BF11AA57D958059-->

Inserisci la radice Merkle, che velocizza ulteriormente la verifica. Poiché contiene tutte le informazioni sull'intero albero, è sufficiente verificare l'hash della transazione, il suo nodo di pari livello (se esiste), e quindi procedere verso l'alto fino a raggiungere la cima.

In sostanza, l'albero di Merkle e il meccanismo di radice di Merkle riducono significativamente i livelli di hashing da eseguire, consentendo verifiche e transazioni più rapide.

## Mette in risalto

- Le radici Merkle sono fondamentali per il calcolo richiesto per mantenere criptovalute come bitcoin ed ether.

- Le radici Merkle vengono utilizzate nella criptovaluta per assicurarsi che i blocchi di dati passati tra peer su una rete peer-to-peer siano interi, integri e inalterati.

- Una radice Merkle è un modo matematico semplice per verificare i dati su un albero Merkle.

