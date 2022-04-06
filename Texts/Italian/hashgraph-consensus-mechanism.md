---
keywords: Investing,Cryptocurrency,Blockchain
title: Consenso hashgraph
description: Il consenso hashgraph funziona in modo diverso dai più noti meccanismi di consenso blockchain. Scopri di più su di esso e su come funziona.
---

# Consenso hashgraph
## Che cos'è il consenso hashgraph?

Il consenso Hashgraph è un'alternativa alla tecnologia alla base dei meccanismi di consenso blockchain. Invece di utilizzare la potenza di calcolo delle grandi reti per verificare le transazioni, le transazioni vengono registrate e confermate tramite un protocollo che utilizza la comunicazione del nodo.

Un hashgraph è un registro decentralizzato più o meno allo stesso modo di una blockchain. Memorizza le informazioni, le protegge con la crittografia, limita l'accesso e utilizza i dati archiviati come verifica. Tuttavia, una rete hashgraph raggiunge il consenso in un modo molto diverso rispetto a una blockchain.

Il consenso dell'hashgraph viene raggiunto utilizzando concetti chiamati "gossip", "gossip sul gossip" e voto virtuale. I progettisti del sistema riferiscono che risolve i problemi inerenti agli [algoritmi di costruzione del consenso](/algorithm),. come il [proof of work](/proof-work) (PoW), in termini di migliore velocità e maggiore efficienza.

> Il consenso hashgraph (pettegolezzi, pettegolezzi e votazioni virtuali) è il meccanismo utilizzato dal registro distribuito di Hedera per convalidare e confermare le transazioni.

>

## Capire il consenso dell'hashgraph

Hashgraph è un'alternativa alla blockchain. Simile a una blockchain, memorizza i dati e li crittografa. Viene generato un hash per le informazioni sulle transazioni e nuove transazioni o dati vengono aggiunti e basati su. Tuttavia, una blockchain è un libro mastro costituito da blocchi di dati. Ogni blocco è collegato al blocco precedente utilizzando i suoi dati, verificati da una rete di validatori per creare il blocco successivo. Questo processo crea una catena. Un hashgraph non è una catena: tutte le informazioni sono conservate in un registro crittografato e ogni utente partecipa al processo di convalida, non solo i validatori.

Ad esempio, Alice crea una transazione con Bob e tutte le informazioni che conosce vengono fornite a lui. Bob quindi effettua una transazione con Kris. Tutte le informazioni che Bob ha vengono comunicate a Kris. Kris negozia con Eli e tutto ciò che sa viene trasferito. Ciò continua in tutta la rete, con la catena che essenzialmente spettegola sugli eventi in corso. Ogni nodo sa cosa sanno tutti gli altri nodi, quindi non è necessaria la convalida computazionale.

Man mano che i pettegolezzi si diffondono da utente a utente, la rete utilizza algoritmi e automazione per garantire che lo stato del registro hashgraph sia aggiornato e lo stesso.

### Gossip

Le informazioni sui dati sono chiamate "pettegolezzi". Le strutture dati contenute in una transazione sono:

- Un timestamp

- Più transazioni o zeri

- Due hash dai contenitori principali

- Una firma crittografata.

I due hash sono gli ultimi eventi di due nodi di sincronizzazione che confrontano le loro informazioni. I nodi creano continuamente eventi e si sincronizzano.

> Hashgraph, il libro mastro, è più efficiente della blockchain perché nessuna energia viene sprecata per blocchi che non vengono accettati. Tutte le informazioni vengono conservate in un hashgraph.

>

### Gossip sul gossip

Le informazioni sui dati delle transazioni sono chiamate "pettegolezzi sui pettegolezzi". Le informazioni vengono sincronizzate nella rete hashgraph utilizzando un evento chiamato "sincronizzazione gossip". Una sincronizzazione di gossip è una cronologia collaborativa di "eventi di gossip" in tutto l'hashgraph. In questo modo i dati non possono essere alterati o manomessi, e c'è consenso.

### Voto virtuale

Il voto virtuale si verifica quando i nodi confrontano gli eventi e raggiungono un consenso tramite un algoritmo di voto. Ecco come funziona: a una transazione viene assegnato un timestamp quando un nodo la riceve. Quando passa agli altri nodi della rete, gli viene assegnato un timestamp che è una mediana di tutti i timestamp per quella transazione ricevuta dai nodi nella rete. La mediana agisce come risultato del voto. Questo crea un sistema di transazione più equo rispetto a una blockchain perché la rete decide, non un nodo.

### Tolleranza ai guasti

Come con la maggior parte dei libri mastri distribuiti e blockchain, c'è sempre la possibilità che un partecipante alla rete non sia onesto. Potrebbero esserci ritardi nella comunicazione o nella latenza della rete che impediscono ai nodi di comunicare correttamente.

I meccanismi di consenso sono progettati per affrontare questi errori impostando criteri di tolleranza agli errori. Gli sviluppatori devono considerare e rendere conto di attori dannosi, connessioni difettose, latenza di rete e altri problemi di rete. Il consenso di Hashgraph può tollerare che un terzo della rete agisca in modo dannoso. Secondo quanto riferito, è tollerante ai guasti bizantino asincrono, il livello di sicurezza più alto, il che significa che i nodi onesti su una rete continuano a funzionare anche se ci sono attori dannosi.

## In che modo l'hashgraph è diverso dalla blockchain?

Hashgraph è una struttura di dati che mantiene i record di chi ha detto chi cosa e in quale ordine lo ha fatto. È una storia collaborativa di eventi di gossip quando i partecipanti aggiungono e condividono informazioni, che convalida le transazioni molto più velocemente di una blockchain.

Blockchain aggiunge le informazioni sulle transazioni precedenti alle nuove informazioni sulle transazioni e le crittografa. È necessaria una terza parte per convalidare le transazioni tra le parti. Hashgraph non ha bisogno di questo processo lento a causa del protocollo gossip.

> Il consenso hashgraph è molto più veloce dei meccanismi di consenso blockchain, con tempi medi di conferma delle transazioni in secondi anziché in minuti.

>

Bitcoin e molte altre criptovalute hanno problemi con la tempistica dei messaggi. Tuttavia, la tolleranza agli errori bizantina asincrona di hashgraph supera il problema della tempistica dei messaggi presumendo che i messaggi persi o ritardati alla fine arriveranno alle loro destinazioni.

Ad esempio, se si verificano due transazioni contemporaneamente, una rete blockchain sceglie in quale ordine si sono verificate le transazioni. In alcune blockchain, le commissioni di transazione danno la priorità alla conferma. Altre reti potrebbero decidere quale transazione è confermata in base a quanti token ha puntato un validatore. In queste blockchain, un nodo influenza il risultato.

Il consenso hashgraph elimina l'influenza che un nodo o un gruppo di nodi può avere sulle transazioni. Poiché è presente un timestamp su ogni transazione e ogni transazione viene comunicata all'intera rete, i problemi di tempistica delle transazioni vengono risolti.

## Mette in risalto

- Il sistema di contabilità distribuita hashgraph non ha ricevuto ampia adozione dalla comunità crittografica.

- Il consenso Hashgraph utilizza le informazioni sulle informazioni piuttosto che il contenuto stesso per creare consenso.

- Le informazioni primarie nell'hashgraph sono chiamate "pettegolezzi" e le informazioni secondarie sono chiamate "pettegolezzi sul gossip".

## FAQ

### Come funziona il consenso Hashgraph?

Il consenso dell'hashgraph funziona utilizzando timestamp di consenso e "gossip", in cui ogni nodo comunica tutto ciò che sa a nodi casuali in "eventi di gossip".

### Che cos'è il consenso hashgraph?

Il consenso hashgraph è un meccanismo utilizzato in un libro mastro distribuito hashgraph per convalidare le transazioni.

### Hashgraph sostituirà Blockchain?

Hashgraph è progettato per essere, e commercializzato come, un miglioramento della tecnologia blockchain, ma resta da vedere se lo sostituirà. Non ha ancora tanto interesse e adozione da parte degli sviluppatori quanto la tecnologia blockchain.

