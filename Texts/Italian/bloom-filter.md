---
keywords: Crypto
title: Filtro di fioritura
description: Filtro di fioritura. Una struttura di dati che può essere utilizzata per informare l&#39;utente se un particolare elemento fa parte di un insieme di elementi
---

# Filtro di fioritura
Un filtro Bloom è una struttura di dati che può essere utilizzata per informare l'utente se un particolare elemento fa parte di un set. Sebbene non possa dire con certezza se un elemento è nell'insieme, può dire con certezza se l'elemento non lo è.

Creati da Burton Howard Bloom nel 1970, i filtri Bloom sono un'offerta interessante per una vasta gamma di applicazioni grazie alla loro efficienza nell'utilizzo dello spazio. In alcune criptovalute (in particolare Bitcoin), svolgono un ruolo fondamentale nella verifica dei pagamenti semplificata o SPV.

Utilizzando un client SPV, gli utenti possono interagire con la rete Bitcoin senza eseguire un nodo completo. I nodi completi sono dotati di determinati requisiti di archiviazione e di calcolo che li rendono poco maneggevoli da eseguire su dispositivi a bassa potenza come gli smartphone. I client SPV, d'altra parte, interrogano semplicemente i full node per informazioni rilevanti per i portafogli dell'utente.

La soluzione più semplice per trasmettere questi dati all'utente sarebbe rendere i nodi completi consapevoli delle chiavi del client, in modo che vengano inviate loro solo le transazioni pertinenti. Evidentemente, questa è una soluzione scadente in quanto la privacy del cliente verrebbe sacrificata. D'altra parte, scaricare tutte le transazioni solo per scartarne la maggior parte sarebbe uno spreco di larghezza di banda. Inserisci i filtri Bloom.

Illustriamo. Supponiamo che un cliente, Alice, abbia una transazione di alto valore di cui non vuole che Bob, che gestisce un nodo completo, sia a conoscenza. Costruisce un filtro Bloom, che illustreremo come una griglia 10x1:

Passa i dati della transazione che le interessano attraverso due diverse funzioni hash, che emettono due numeri compresi tra 0 e 9. Chiamiamoli 4 e 7. Invia il filtro a Bob.

Guardando questa griglia, non hai idea di quali dati Alice abbia passato al filtro. Se avessi un set in cui erano contenuti i dati, saresti in grado di eseguirne l'hashing e confrontarlo con il filtro: se c'è una corrispondenza, c'è la possibilità che fosse l'informazione richiesta da Alice.

Allo stesso tempo, è probabile che ci siano molti input che verranno mappati su 4 e 7, quindi Bob non può determinare quale parte dei dati è interessata ad Alice. Restituisce semplicemente tutte le corrispondenze e Alice le filtra dalla sua parte.

Questa è, ovviamente, una semplificazione eccessiva, ma dimostra il concetto: i filtri Bloom offuscano i veri interessi del cliente. Non è un metodo perfetto (ci sono ancora preoccupazioni sulla sua privacy), ma è un miglioramento rispetto a una richiesta non schermata a un nodo.

