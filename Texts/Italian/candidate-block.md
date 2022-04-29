---
keywords: Crypto
title: Blocco Candidato
description: Blocco Candidato. Un blocco temporaneo creato da un nodo di mining (miner) da aggiungere alla blockchain per ricevere i premi del blocco.
---

# Blocco Candidato
In poche parole, un blocco candidato è un blocco che un nodo di mining (miner) sta cercando di estrarre per ricevere la ricompensa del blocco. Quindi un blocco candidato può essere descritto come un blocco temporaneo che verrà convalidato o scartato dalla rete. I miner competono tra loro per convalidare il blocco successivo e aggiungerlo alla blockchain, ma prima devono creare un blocco candidato per partecipare alla competizione mineraria.

I blocchi candidati vengono creati dai miner raccogliendo e organizzando più transazioni non confermate dal pool di memoria. Le transazioni vengono quindi sottoposte a hash per formare una struttura [ad albero Merkle](/merkle-tree),. che alla fine produrrà una radice Merkle (o hash radice). La radice di Merkle è un singolo hash che rappresenta tutti gli hash precedenti di quell'albero e, quindi, tutte le transazioni incluse in quel particolare blocco.

L'hash della radice, insieme all'hash del blocco precedente e un numero casuale chiamato [nonce](/nonce),. viene quindi inserito nell'intestazione del blocco. L'intestazione del blocco viene quindi sottoposta a hash dal minatore, generando un output basato su tali componenti (hash radice, hash del blocco precedente e nonce) più alcuni altri elementi. L'output risultante è l'hash del blocco e fungerà da identificatore univoco del blocco appena generato (blocco candidato).

Per essere considerato valido, l'output (block hash) deve iniziare con un certo numero di zeri (inferiore a un valore target definito dal protocollo). Ciò significa che il processo di mining si basa su più tentativi (prova ed errore) poiché i nodi di mining devono eseguire una miriade di funzioni di hashing con valori nonce diversi fino a quando non viene prodotto un hash di blocco valido. Il block hash prodotto è ciò che prova che il minatore ha svolto il suo lavoro (da qui Proof of Work).

Dopo che un miner ha trovato un hash di blocco valido, il suo blocco candidato verrà trasmesso al resto dei nodi della rete, che verificheranno l'autenticità dell'hash. Se tutto è a posto, il blocco candidato verrà quindi registrato nella blockchain. A questo punto, ogni nodo di convalida aggiorna la propria copia dei dati blockchain per riflettere il blocco estratto di recente e il minatore riceverà la ricompensa del blocco.

