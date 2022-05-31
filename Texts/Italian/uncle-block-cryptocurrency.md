---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Blocco Ommer
description: I blocchi Ommer sono blocchi non selezionati dalla rete Ethereum da aggiungere alla blockchain. Scopri di più su di loro e su cosa fanno per la rete.
---

# Blocco Ommer
## Che cos'è un blocco Ommer?

È possibile che due blocchi vengano creati contemporaneamente da una rete. Quando ciò accade, un blocco verrà tralasciato. Questo blocco rimanente è chiamato blocco ommer. In passato venivano chiamati blocchi dello zio, riferendosi alle relazioni familiari usate per descrivere le posizioni dei blocchi all'interno di una blockchain.

## Capire i blocchi di Ommer

In una blockchain pubblica come Ethereum e Bitcoin, è essenziale utilizzare un metodo che assicuri che i dati all'interno della blockchain siano verificati e aggiunti per consenso. È altrettanto importante evitare che i dati vengano modificati. Molte blockchain utilizzano una struttura di dati chiamata Merkle tree per raggiungere questo obiettivo.

Un albero Merkle stabilisce relazioni ancestrali per i blocchi di dati. Le informazioni dei blocchi precedenti sono incluse nei nuovi blocchi, in modo simile al DNA trasmesso tra le generazioni. Questo crea il concetto di blocco genitore, fratello del genitore, figlio e fratello simile a una rappresentazione grafica di un albero genealogico.

Ecco come funziona: il primo blocco in un albero potrebbe essere chiamato blocco A. Il blocco successivo creato dal blocco A sarebbe considerato figlio del blocco A e includerebbe le informazioni di A più le proprie.

> Ethereum sta passando dal consenso proof-of-work al consenso proof-of-stake. Con il meccanismo del consenso proof-of-stake, i blocchi ommer possono ancora essere prodotti e le commissioni di transazione vengono premiate.

>

Questo blocco potrebbe essere chiamato blocco B ma potrebbe essere rappresentato come B~a~. B è il nome del nuovo blocco e "a" si riferisce ai dati del blocco padre. Questa relazione genitore/figlio continua man mano che vengono aggiunti più blocchi con le informazioni di ogni blocco precedente. Questo crea un albero genealogico e blockchain.

Ora considera se due blocchi sono stati convalidati e creati contemporaneamente da B~a. Sono blocchi~ C~ab~ e C~ab2,~ blocchi fratelli dello stesso blocco padre. Solo uno può essere aggiunto alla blockchain, quindi la rete sceglie C~ab~. C~ab2~ è un fork della blockchain originale ma non viene aggiunto o convalidato. Infine, un altro blocco viene estratto sulla blockchain che teneva C~ab.~ Questo è il blocco D~cab.~ C~ab2 è il fratello del ~genitore di~ D~cab~, quindi~ C~ab2~ è un ommer bloccare.

## Considerazioni speciali

Questi blocchi orfani erano, in sostanza, bug nel codice, sottoprodotti non intenzionali e accidentali del processo di mining. Tuttavia, Ethereum ha incentivato i minatori di blocchi ommer per diversi motivi:

- Per consentire la creazione di più blocchi ommer come sottoprodotto di tempi di blocco più brevi e accelerare la rete.

- Diminuire la centralizzazione degli incentivi per i grandi pool minerari. Questi pool impiegano grandi mining farm e rivendicano la maggior parte dei premi in criptovaluta, lasciando poco per i singoli minatori.

- Aumentare la sicurezza della rete integrando il lavoro sulla blockchain principale consentendo di includere il lavoro svolto sui blocchi ommer.

I blocchi Ommer sono incorporati di proposito nella blockchain di Ethereum utilizzando il protocollo di convalida del suo meccanismo di consenso, Casper the Friendly GHOST (Greedy Heaviest Object Sub Tree). Quando si verifica un fork della blockchain da blocchi creati contemporaneamente, una regola di consenso dei due terzi dei validatori di rete seleziona quale blocco viene utilizzato.

<!--7D655E4B296C31937FEB1522C669FA07-->

## Mette in risalto

- I blocchi Ommer sono simili agli orfani di Bitcoin ma hanno un uso integrato, a differenza delle loro controparti Bitcoin.

- I blocchi Ommer vengono creati nella blockchain di Ethereum quando due blocchi vengono creati e inviati al libro mastro più o meno contemporaneamente. Solo uno può entrare nel registro.

- I minatori o validatori di Ethereum vengono ricompensati per la creazione di blocchi ommer nel sistema Ethereum tramite commissioni di transazione per pagare il loro lavoro.

## FAQ

### Cos'è un blocco Ommer (zio)?

Uncle block è il vecchio nome di un ommer block. Gli sviluppatori e la comunità di Ethereum hanno deciso che non c'era motivo di avere nomi specifici per genere, quindi hanno deciso di ommer come nuovo nome.

### Qual è la tariffa Ommer (zio) di Ethereum?

La tariffa ommer (in precedenza la tariffa zio) è la velocità con cui la rete produce blocchi ommer. La tariffa cambia giornalmente e dipende dal numero di transazioni che si verificano.

### Qual è la ricompensa Ommer (zio) di Ethereum?

Secondo il meccanismo del consenso proof-of-work, i premi per i blocchi ommer erano una piccola percentuale del premio del blocco, più le commissioni di transazione. Quando Ethereum passa al proof-of-stake, i blocchi ommer riceveranno commissioni di transazione.

