---
keywords: Crypto
title: Output delle transazioni non spese (UTXO)
description: Output di transazione non speso (UTXO). Un output creato in una transazione, a cui fare riferimento in una transazione futura per spendere fondi.
---

# Output delle transazioni non spese (UTXO)
Un output di transazione non speso (UTXO) si riferisce a un output di transazione che può essere utilizzato come input in una nuova transazione. In sostanza, gli UTXO definiscono dove inizia e finisce ogni transazione blockchain. Il modello UTXO è un elemento fondamentale di Bitcoin e di molte altre criptovalute.

In altre parole, le transazioni in criptovaluta sono costituite da input e output. Ogni volta che viene effettuata una transazione, un utente prende uno o più UTXO come input. Successivamente, l'utente fornisce la propria firma digitale per confermare la proprietà degli input, che alla fine si traducono in output. Gli UTXO consumati sono ora considerati "spesi" e non possono più essere utilizzati. Nel frattempo, gli output della transazione diventano nuovi UTXO, che possono essere spesi in una nuova transazione in un secondo momento.

Questo è probabilmente spiegato meglio con un esempio. Alice ha 0,45 BTC nel suo portafoglio. Questa non è una frazione di una moneta come potremmo concettualizzare. È piuttosto una raccolta di UTXO. In particolare, due UTXO del valore di 0,4 BTC e 0,05 BTC – output di transazioni passate. Ora immaginiamo che Alice debba effettuare un pagamento a Bob di 0,3 BTC.

La sua unica opzione qui è rompere l'unità da 0,4 BTC e inviare 0,3 BTC a Bob e 0,1 BTC a se stessa. Normalmente rivendicherebbe meno di 0,1 BTC a causa delle commissioni di mining, ma semplifichiamo e lasciamo fuori il minatore.

Alice crea una transazione che essenzialmente dice alla rete: prendi il mio UTXO da 0,4 BTC come input, spezzettalo, invia 0,3 BTC all'indirizzo di Bob e restituisci lo 0,1 BTC al mio indirizzo. Lo 0,4 BTC è ora un output speso e non può essere riutilizzato. Nel frattempo sono stati creati due nuovi UTXO (0,3 BTC e 0,1 BTC).

Nota che in questo esempio abbiamo rotto un UTXO, ma se Alice avesse dovuto pagare 0,42 BTC, avrebbe potuto facilmente combinare i suoi 0,4 BTC con altri 0,05 BTC per produrre un UTXO del valore di 0,42 BTC, restituendo al contempo 0,03 BTC a se stessa.

Riassumendo, il modello UTXO funge da meccanismo del protocollo per tenere traccia di dove si trovano le monete in un dato momento. In un certo senso, funzionano in modo molto simile agli assegni: sono indirizzati a utenti specifici (o meglio, ai loro [indirizzi pubblici](/address) ). Gli UTXO non possono essere spesi in parte, invece, nuovi assegni devono essere creati da quello vecchio e trasferiti di conseguenza.

