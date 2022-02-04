---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Crypto,Strategy and Education
title: Contratto di blocco temporale con hash (HTLC)
description: Contratto TimeLock con hash (HTLC). Si riferisce a una funzione speciale utilizzata per creare contratti intelligenti in grado di modificare i canali di pagamento.
---

# Contratto di blocco temporale con hash (HTLC)
Il termine Hashed TimeLock Contract (HTLC) si riferisce a una funzione speciale utilizzata per creare [contratti intelligenti](/smart-contract) in grado di modificare i canali di pagamento. Tecnicamente, la funzione HTLC consente l'implementazione di transazioni a tempo determinato tra due utenti. In pratica, il destinatario di una transazione HTLC deve riconoscere il pagamento presentando una prova crittografica entro un determinato lasso di tempo (numero di blocchi). Se il destinatario rinuncia o non reclama il pagamento, i fondi verranno restituiti al mittente originale.

La funzionalità HTLC viene applicata sia nei canali di pagamento bidirezionali che instradati per consentire trasferimenti sicuri di fondi su vari canali, senza richiedere fiducia a nessuno degli intermediari.

Ci sono due elementi chiave che distinguono HTLC dalle transazioni standard in criptovaluta, che sono:

- Hashlock: una funzione che limita la spesa di fondi fino a quando un determinato dato non viene divulgato pubblicamente (come prova crittografica). Tale prova può anche essere definita pre-immagine dell'hashlock. La pre-immagine è semplicemente l'informazione che viene utilizzata per generare l'hashlock e successivamente per sbloccarne i fondi.

- Timelock: è una funzione che limita la spesa di fondi fino a un momento specifico (o altezza del blocco) nel futuro. Può essere ottenuto in Bitcoin, ad esempio, utilizzando funzioni come CheckLockTimeVerify o CheckSequenceVerify.

Il Bitcoin Lightning Network è tra i casi d'uso più popolari dei contratti Hashed Timelocked. Implementando l'HTLC nei canali di pagamento, i fondi possono essere trasferiti da un utente all'altro attraverso canali di pagamento interconnessi, senza richiedere alcun livello di fiducia. Questo processo è noto come routing di rete. Consente ad Alice di scambiare fondi con Carol anche se non sono direttamente collegati tramite un canale di pagamento. Gli HTLC consentono ad Alice di inviare i suoi fondi a Carol tramite altri partecipanti alla rete (ad es. Bob) e le funzionalità di hashlock e timelock assicurano che Bob non possa intercettare i fondi.

Oltre ad essere utilizzati sulla rete Lightning, gli HTLC possono essere utili anche in altri contesti, come scambi [atomici cross-chain](/atomic-swaps),. contratti intelligenti finanziari e escrow e molto altro.

## Mette in risalto

- I pagamenti tramite HTLC sono condizionali e quindi hanno vantaggi in termini di efficienza per le transazioni blockchain. Questa proprietà rende gli HTLC uno strumento fondamentale utilizzato dalla rete di fulmini.

- Questo tipo di contratto intelligente richiede che il destinatario di un pagamento lo riconosca entro un certo periodo di tempo o lo rinunci.

- Un contratto di blocco temporale con hash (HTLC) riduce il rischio di controparte nei contratti intelligenti decentralizzati creando efficacemente un deposito a garanzia basato sul tempo che utilizza una passphrase crittografica.

## FAQ

### Quanto costa uno Smart Contract?

Sulla blockchain di Ethereum, un'implementazione di smart contract richiede gas, che costa Gwei (una denominazione inferiore di etere). A seconda della complessità del contratto, l'implementazione di uno smart contract può costare miliardi di Gwei. Contratti meno complessi come un semplice scambio sono molto più economici.

### Che cos'è un contratto intelligente?

Uno smart contract è un programma memorizzato su una blockchain che viene eseguito quando vengono soddisfatte condizioni specifiche.

### Che cos'è un contratto Timelock?

Un contratto timelock è uno smart contract incorporato in una blockchain che esegue una transazione in un momento specifico. Sono utilizzati nei contratti di blocco temporale con hash e nei canali di pagamento in cui sono necessari tempi di pagamento specifici.

### Bitcoin ha contratti intelligenti?

Inizialmente, la blockchain di Bitcoin non era in grado di eseguire contratti intelligenti. Tuttavia, l'aggiornamento di Taproot nel 2021 ha consentito alla blockchain di utilizzare contratti intelligenti nelle transazioni.

