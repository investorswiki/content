---
keywords: Investing,Cryptocurrency,Bitcoin
title: Prova di lavoro (PoW)
description: La prova del lavoro descrive il processo che consente alla rete bitcoin di rimanere solida rendendo difficile il processo di mining o registrazione delle transazioni.
---

# Prova di lavoro (PoW)
## Che cos'è la prova di lavoro (PoW)?

Proof of work (PoW) descrive un sistema che richiede uno sforzo non insignificante ma fattibile per scoraggiare usi frivoli o dannosi della potenza di calcolo, come l'invio di e-mail di spam o il lancio di attacchi denial of service. Il concetto è stato successivamente adattato per proteggere il denaro digitale da Hal Finney nel 2004 attraverso l'idea di una "prova di lavoro riutilizzabile" utilizzando l'algoritmo di hashing SHA-256.

Dopo la sua introduzione nel 2009, Bitcoin è diventata la prima applicazione ampiamente adottata dell'idea PoW di Finney (Finney è stato anche il destinatario della prima transazione bitcoin). La prova del lavoro costituisce anche la base di molte altre [criptovalute ,](/cryptocurrency) [consentendo](/cryptocurrency) un consenso sicuro e decentralizzato.

## Capire la prova del lavoro

Questa spiegazione si concentrerà sulla prova del lavoro in quanto funziona nella rete [bitcoin](/bitcoin). Bitcoin è una valuta digitale supportata da una sorta di [registro distribuito](/distributed-ledger-technology-dlt) noto come " [blockchain](/blockchain) ". Questo registro contiene un record di tutte le transazioni bitcoin, disposte in "blocchi" sequenziali, in modo che nessun utente possa spendere due volte le proprie partecipazioni. Al fine di prevenire manomissioni, il libro mastro è pubblico, o "distribuito"; una versione modificata verrebbe rapidamente rifiutata da altri utenti.

Il modo in cui gli utenti rilevano la manomissione in pratica è tramite [hash](/hash),. lunghe stringhe di numeri che fungono da prova del lavoro. Inserisci un determinato set di dati attraverso una funzione hash (bitcoin utilizza SHA-256) e genererà sempre un solo hash. A causa dell '"effetto valanga", tuttavia, anche una piccola modifica a qualsiasi parte dei dati originali risulterà in un hash totalmente irriconoscibile. Qualunque sia la dimensione del set di dati originale, l'hash generato da una determinata funzione avrà la stessa lunghezza. L'hash è una funzione unidirezionale: non può essere utilizzato per ottenere i dati originali, solo per verificare che i dati che hanno generato l'hash corrispondano ai dati originali.

Generare un qualsiasi hash per un insieme di transazioni bitcoin sarebbe banale per un computer moderno, quindi per trasformare il processo in "lavoro", la rete bitcoin imposta un certo livello di "difficoltà". Questa impostazione viene regolata in modo che un nuovo blocco venga " [minato](/bitcoin-mining) ", aggiunto alla blockchain generando un hash valido, circa ogni 10 minuti. L'impostazione della difficoltà si ottiene stabilendo un ["target" per l'hash](/target-hash) : più basso è il target, minore è l'insieme di hash validi e più difficile è generarne uno. In pratica, questo significa un hash che inizia con una stringa di zeri molto lunga.

> La prova di lavoro è stata inizialmente creata come soluzione proposta al crescente problema delle e-mail di spam.

>

## Considerazioni speciali

Poiché un determinato set di dati può generare un solo hash, in che modo i minatori si assicurano di generare un hash al di sotto del target? Modificano l'input aggiungendo un numero intero, chiamato [nonce](/nonce) ("numero usato una volta"). Una volta trovato un hash valido, viene trasmesso alla rete e il blocco viene aggiunto alla blockchain.

L'estrazione mineraria è un processo competitivo, ma è più una lotteria che una gara. In media, qualcuno genererà una prova accettabile del lavoro ogni dieci minuti, ma chiunque sarà è indovinato. I minatori si uniscono per aumentare le loro possibilità di minare blocchi, che genera commissioni di transazione e, per un periodo di tempo limitato, una ricompensa di bitcoin appena creati.

La prova del lavoro rende estremamente difficile alterare qualsiasi aspetto della blockchain, poiché tale alterazione richiederebbe il re-mining di tutti i blocchi successivi. Inoltre, rende difficile per un utente o un pool di utenti monopolizzare la potenza di calcolo della rete, poiché i macchinari e la potenza necessari per completare le funzioni hash sono costosi.

> Se parte di una rete mineraria inizia ad accettare una prova di lavoro alternativa, si parla di [hard fork](/hard-fork).

>

## Esempio di prova di lavoro

La prova del lavoro richiede che un computer si impegni in modo casuale in funzioni di hashing fino a quando non arriva a un output con la quantità minima corretta di zeri iniziali. Ad esempio, l'hash per il blocco #660000, estratto il 4 dicembre 2020, è 00000000000000000008eddcaf078f12c69a439dde30dbb5aac3d9d94e9c18f6. La ricompensa del blocco per quell'hash riuscito è stata di 6,25 BTC.

Quel blocco conterrà sempre 745 transazioni che coinvolgono poco più di 1.666 bitcoin, così come l'intestazione del blocco precedente. Se qualcuno tentasse di modificare l'importo di una transazione anche di 0,000001 bitcoin, l'hash risultante sarebbe irriconoscibile e la rete rifiuterebbe il tentativo di frode.

## Domande frequenti sulla prova di lavoro

### Cosa significa prova di lavoro?

PoW richiede che i nodi su una rete forniscano la prova che hanno speso potenza di calcolo (cioè lavoro) per ottenere il consenso in modo decentralizzato e per impedire ai malintenzionati di sorpassare la rete.

### In che modo la prova di lavoro convalida una transazione crittografica?

Il lavoro stesso è arbitrario. Per Bitcoin, implica iterazioni di algoritmi di hash SHA-256. Il "vincitore" di un round di hashing, tuttavia, aggrega e registra le transazioni dal mempool nel blocco successivo. Poiché il "vincitore" è scelto casualmente in proporzione al lavoro svolto, incentiva tutti sulla rete ad agire onestamente e registrare solo transazioni vere.

### Perché le criptovalute hanno bisogno di una prova di lavoro?

Poiché sono decentralizzate e peer-to-peer in base alla progettazione, blockchain come le reti di criptovaluta richiedono un modo per raggiungere sia il consenso che la sicurezza. La prova di lavoro è uno di questi metodi che rende troppo dispendioso in termini di risorse cercare di superare la rete. Esistono anche altri meccanismi di prova che richiedono meno risorse, ma che presentano altri inconvenienti o difetti, come il [proof](/proof-stake-pos) [of stake (PoS)](/proof-stake-pos) e [il proof of burn](/proof-burn-cryptocurrency). Senza un meccanismo di prova, la rete e i dati archiviati al suo interno sarebbero vulnerabili ad attacchi o furti.

### Bitcoin utilizza la prova del lavoro?

Sì. Utilizza un algoritmo PoW basato sulla funzione di hashing SHA-256 per convalidare e confermare le transazioni nonché per emettere nuovi bitcoin in circolazione.

### Qual è la differenza tra Proof of Stake (PoS) e PoW?

PoS è un meccanismo di consenso che assegna casualmente il nodo che estrarrà o convaliderà le transazioni di blocco in base a quante monete detiene quel nodo. Più token sono detenuti in un portafoglio, maggiore è il potere di mining che gli viene effettivamente concesso. Sebbene PoS richieda molte meno risorse, ha molti altri difetti tra cui una maggiore possibilità di un [attacco del 51%](/51-attack) in altcoin più piccoli e incentivi per accumulare token e non usarli.

## Mette in risalto

- Proof of Stake (POS) è stato uno dei numerosi nuovi meccanismi di consenso creati come alternativa al proof of work.

- La prova del lavoro (PoW) è un meccanismo di consenso decentralizzato che richiede ai membri di una rete di dedicare sforzi alla risoluzione di un arbitrario puzzle matematico per impedire a chiunque di giocare con il sistema.

- La prova del lavoro su larga scala richiede enormi quantità di energia, che aumentano solo man mano che più minatori si uniscono alla rete.

- A causa della prova del lavoro, le transazioni di Bitcoin e altre criptovalute possono essere elaborate peer-to-peer in modo sicuro senza la necessità di una terza parte fidata.

- La prova del lavoro è ampiamente utilizzata nel mining di criptovalute, per la convalida delle transazioni e l'estrazione di nuovi token.

