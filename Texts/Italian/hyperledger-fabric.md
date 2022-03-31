---
keywords: Investing,Cryptocurrency,Blockchain
title: Tessuto Hyperledger
description: Hyperledger Fabric è una piattaforma per la creazione di vari prodotti, soluzioni e applicazioni basati su blockchain per uso aziendale.
---

# Tessuto Hyperledger
## Che cos'è il tessuto Hyperledger?

Hyperledger Fabric è un framework [blockchain modulare](/blockchain) che funge da base per lo sviluppo di prodotti, soluzioni e applicazioni basati su blockchain utilizzando componenti plug-and-play destinati all'uso all'interno di imprese private.

Hyperledger Fabric è stato avviato da Digital Asset e IBM ed è ora emerso come un'impresa collaborativa intersettoriale, attualmente ospitata dalla Linux Foundation. Tra i numerosi progetti Hyperledger, Fabric è stato il primo ad uscire dalla fase di “incubazione” e raggiungere la fase “attiva” a marzo 2017.

## Come funziona il tessuto Hyperledger

Le tradizionali reti blockchain non possono supportare transazioni private e contratti riservati che sono della massima importanza per le aziende. Hyperledger Fabric è stato progettato in risposta a questo come una base modulare, scalabile e sicura per offrire soluzioni blockchain industriali.

Hyperledger Fabric è il motore open source per blockchain e si occupa delle funzionalità più importanti per la valutazione e l'utilizzo della blockchain per casi d'uso aziendali.

All'interno delle reti industriali private, l'identità verificabile di un partecipante è un requisito primario. Hyperledger Fabric supporta le iscrizioni basate sull'autorizzazione; tutti i partecipanti alla rete devono avere identità note. Molti settori aziendali, come l'assistenza sanitaria e la finanza, sono vincolati da normative sulla protezione dei dati che impongono il mantenimento dei dati sui vari partecipanti e il rispettivo accesso a vari punti dati. Fabric supporta tale appartenenza basata sull'autorizzazione.

### Architettura modulare

L'architettura modulare di Hyperledger Fabric separa il flusso di lavoro di elaborazione delle transazioni in tre diverse fasi: [contratti intelligenti](/smart-contracts) chiamati chaincode che comprendono l'elaborazione logica distribuita e l'accordo del sistema, l'ordine delle transazioni e la convalida e l'impegno delle transazioni. Questa separazione offre molteplici vantaggi:

- Un numero ridotto di livelli di affidabilità e verifica che mantiene la rete e l'elaborazione libere da ingombri

- Migliorata la scalabilità della rete

- Migliori prestazioni complessive

Inoltre, il supporto di Hyperledger Fabric per il plug-and-play di vari componenti consente un facile riutilizzo delle funzionalità esistenti e l'integrazione pronta di vari moduli. Ad esempio, se esiste già una funzione che verifica l'identità del partecipante, una rete a livello aziendale deve semplicemente collegare e riutilizzare questo modulo esistente invece di creare la stessa funzione da zero.

I partecipanti alla rete hanno tre ruoli distinti:

- Sostenitore

- Commissario

- Consenso

In poche parole, la proposta di transazione viene presentata al peer girante secondo la politica di girata predefinita sul numero di giranti richiesti. Dopo aver approvato un numero sufficiente di giranti, un batch o un blocco di transazioni viene consegnato al committer. I committenti convalidano che la politica di approvazione è stata seguita e che non ci sono transazioni in conflitto. Una volta effettuati entrambi i controlli, le transazioni vengono vincolate al libro mastro.

<!--6376536357DF4ADC77E5CAB266DCF459-->

Fonte immagine: IBM

Poiché solo le istruzioni di conferma, come firme e set di lettura/scrittura, vengono inviate attraverso la rete, la scalabilità e le prestazioni della rete sono migliorate. Solo gli sponsor e i committenti hanno accesso alla transazione e la sicurezza è migliorata con un numero inferiore di partecipanti che ha accesso ai punti dati chiave.

## Esempio di tessuto Hyperledger

Supponiamo che ci sia un produttore che vuole spedire cioccolatini a uno specifico rivenditore o mercato di rivenditori (ad esempio, tutti i rivenditori statunitensi) a un prezzo specifico ma non vuole rivelare quel prezzo in altri mercati (ad esempio, rivenditori cinesi).

Poiché il movimento del prodotto può coinvolgere altre parti, come dogane, una compagnia di spedizioni e una banca finanziatrice, il prezzo privato può essere rivelato a tutte le parti coinvolte se viene utilizzata una versione base della tecnologia blockchain per supportare questa transazione.

Hyperledger Fabric risolve questo problema mantenendo private le transazioni private sulla rete; solo i partecipanti che hanno bisogno di sapere sono a conoscenza dei dettagli necessari. Il partizionamento dei dati sulla blockchain consente a punti dati specifici di essere accessibili solo alle parti che hanno bisogno di sapere.

## Critiche al tessuto Hyperledger

Il culmine del cripto-entusiasmo si è rotto nel 2018 dopo il crollo del prezzo del bitcoin (che ha toccato il picco il 17 dicembre 2017). Affermazioni eccessivamente ottimistiche sul valore della nuova tecnologia sono state sostituite con scetticismo e anche le tecnologie correlate, incluso Hyperledger, hanno sofferto di questo scetticismo.

### Concorrenti di Hyperledger Fabric

Hyperledger Fabric compete con altri progetti Hyperledger come Iroha, Indy e Sawtooth. È anche in concorrenza con Corda di R3, che è anche un DLT privato basato sui permessi.

La società di servizi blockchain Chainstack ha pubblicato un documento nel gennaio 2020 che mostra che lo sviluppo in Corda è stato storicamente superiore allo sviluppo in Fabric, sebbene lo sviluppo di Fabric abbia superato quello di Corda nel terzo trimestre del 2019 quando Fabric è passato a GitHub.

Il rapporto Chainstack mostra che mentre ci sono tre volte più sviluppatori che lavorano su Fabric, gli sviluppatori Corda hanno dato più del doppio dei contributi al codice e gli sviluppatori Fabric inviano molto meno codice per sviluppatore rispetto agli sviluppatori di Corda.

### Il tessuto Hyperledger non è blockchain e non è efficiente

Diverse critiche a Hyperledger Fabric sottolineano che una blockchain privata basata sui permessi con le funzionalità di Hyperledger Fabric non è una blockchain e le attuali tecnologie non blockchain sono molto meno costose e offrono la stessa quantità di sicurezza. Stuart Popejoy di Cointelegraph ha espresso il caso in questo modo:

>

> L'architettura di Fabric è molto più complessa di qualsiasi piattaforma blockchain e allo stesso tempo meno sicura contro manomissioni e attacchi. Penseresti che una blockchain "privata" offra almeno scalabilità e prestazioni, ma anche Fabric fallisce qui. In poche parole, i progetti pilota basati su Fabric dovranno affrontare un'implementazione complessa e insicura che non sarà in grado di adattarsi alle loro attività .

>

Hyperledger Fabric è stato anche criticato per la mancanza di resilienza. Un team di ricercatori della Sorbona di Parigi e CSIRO - Data61, l'agenzia scientifica nazionale australiana, ha scoperto che significativi ritardi di rete hanno ridotto l'affidabilità di Fabric: "[B]y ritardando la propagazione dei blocchi, abbiamo dimostrato che Hyperledger Fabric non fornisce sufficienti garanzie di coerenza da distribuire in ambienti critici. "

## Hyperledger Fabric 2.0 Rilasciato a gennaio 2020

Nel gennaio del 2020, Hyperledger Fabric 2.0 è stato rilasciato per rispondere ad alcune delle critiche esistenti. Secondo Ron Miller di Techcrunch, "Gli aggiornamenti più importanti riguardano la forzatura dell'accordo tra le parti prima che qualsiasi nuovo dato possa essere aggiunto al libro mastro, noto come governance decentralizzata degli smart contract".

Sebbene l'aggiornamento non rappresenti un cambiamento radicale nella semplicità o applicabilità di Fabric, dimostra che continuano a essere compiuti progressi nel settore delle criptovalute oltre la criptomania che si è verificata nel 2018. Nei prossimi cinque o dieci anni, è previsto che la blockchain aziendale troverà senza dubbio il suo corretto utilizzo.

## Mette in risalto

- Hyperledger è un framework di contabilità distribuito open source di livello enterprise lanciato dalla Linux Foundation a dicembre 2015.

- Poiché Hyperledger Fabric è privato e richiede l'autorizzazione per l'accesso, le aziende possono separare le informazioni (come i prezzi), inoltre le transazioni possono essere velocizzate perché il numero di nodi sulla rete è ridotto.

- Fabric 2.0 è stato rilasciato a gennaio 2020. Le caratteristiche principali di questa versione sono transazioni più veloci, tecnologia smart contract aggiornata e condivisione dei dati semplificata.

- Fabric è una piattaforma DLT (Decentralized Ledger Technology) altamente modulare progettata da IBM per l'uso da parte delle imprese industriali.

