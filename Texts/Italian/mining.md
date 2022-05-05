---
keywords: Crypto
title: Estrazione
description: Estrazione. La verifica delle transazioni su una rete blockchain, in cui le transazioni vengono aggiunte come voci nel registro blockchain.
---

# Estrazione
Il mining è il processo attraverso il quale le transazioni [di criptovaluta](/cryptocurrency) vengono raccolte, verificate e registrate in un registro digitale noto come [blockchain](/blockchain). Il lavoro svolto dai miner è essenziale per mantenere l'integrità della rete ed è anche responsabile dell'introduzione di nuove monete nel sistema.

All'interno del sistema bancario tradizionale, la valuta fiat viene stampata e distribuita da istituzioni finanziarie e autorità governative, ma per la maggior parte delle criptovalute, l'emissione di nuove monete non è nelle mani di entità centralizzate. Invece, nuove unità di criptovaluta vengono generate attraverso il processo di mining, che segue un insieme predefinito di regole stabilite dal protocollo sottostante. Mentre il protocollo definisce quali sono le regole primarie, i cosiddetti algoritmi di consenso delineano come queste regole verranno seguite (ad esempio, durante la convalida delle transazioni).

Prendendo ad esempio Bitcoin, i partecipanti coinvolti nel processo di mining sono chiamati nodi di mining (o semplicemente minatori), e svolgono un ruolo chiave nella sicurezza della rete blockchain. Il compito di un miner è raccogliere le transazioni non confermate dal pool di memoria e organizzarle in un [blocco candidato](/candidate-block) che cercherà di convalidare.

Quando crea un blocco candidato, un miner include una transazione in cui invia a se stesso il [premio del blocco](/block-reward). Questa transazione è nota come transazione coinbase ed è spesso la prima ad essere registrata in un blocco.

Dopo aver formato l'elenco delle transazioni non confermate, ogni transazione viene sottoposta a hash e i relativi output sono organizzati in coppie. Queste coppie vengono quindi sottoposte a hash, producendo nuovi output che sono anche organizzati in coppie e nuovamente sottoposti a hash. Il processo viene ripetuto fino a quando non viene prodotto un singolo hash, che viene indicato come root hash o radice [dell'albero di Merkle](/merkle-tree).

L'hash della radice viene quindi combinato con l'hash del blocco precedentemente confermato, insieme a un numero pseudo-casuale chiamato [nonce](/nonce) (più alcuni altri parametri). Questi elementi vengono quindi sottoposti a hash, producendo l'hash del blocco per quel blocco candidato.

Tuttavia, il miner avrà successo solo se l'output risultante (hash del blocco) per il blocco candidato è inferiore a un valore predeterminato (target). Di conseguenza, il processo si basa su tentativi ed errori e devono eseguire numerose funzioni di hashing con nonce differenti per trovare un risultato valido. Il primo miner che trova un hash valido convalida il blocco candidato e ottiene il premio del blocco. L'intero processo richiede in media dieci minuti.

Una volta che un blocco viene convalidato, viene aggiunto alla blockchain e i minatori iniziano a lavorare sul blocco successivo. L'hash valido prodotto dai miner funge da prova del loro lavoro ed è per questo che l'algoritmo di consenso Bitcoin è chiamato Proof of Work. Ogni blocco confermato ha un hash di blocco univoco che funge da identificatore.

La [ricompensa del blocco](/block-reward) è definita dal protocollo Bitcoin e diminuisce ogni 210.000 blocchi (circa quattro anni). Inizialmente, la ricompensa del blocco era di 50 BTC e ora è di 12,5 BTC.

