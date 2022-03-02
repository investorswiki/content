---
keywords: Trading,Options and Derivatives Trading,Options and Derivatives
title: Modello di prezzo dell&#39;opzione binomiale
description: Un modello binomiale di determinazione del prezzo delle opzioni è un metodo di valutazione delle opzioni che utilizza una procedura iterativa e consente la specifica del nodo in un determinato periodo.
---

# Modello di prezzo dell'opzione binomiale
## Qual è il modello di prezzo dell'opzione binomiale?

[valutazione](/valuation) delle opzioni sviluppato nel 1979. Il modello di determinazione del prezzo dell'opzione binomiale utilizza una procedura iterativa, che consente di specificare i nodi, o punti temporali, durante l'intervallo di tempo tra la data di valutazione e la data di [scadenza](/expiration-date) [dell'opzione](/expiration-date).

Il modello riduce le possibilità di variazione dei prezzi ed elimina la possibilità di [arbitraggio](/arbitrage). Un esempio semplificato di [albero binomiale](/binomial_tree) potrebbe assomigliare a questo:

<!--87C9D3D79FF63D08201E6E848035602D-->

## Nozioni di base sul modello di prezzo dell'opzione binomiale

Con i modelli binomiali del prezzo delle opzioni, le ipotesi sono che ci sono due possibili risultati: quindi, la parte binomiale del modello. Con un modello di prezzo, i due risultati sono un aumento o un movimento verso il basso. Il principale vantaggio di un modello di prezzo delle opzioni binomiale è che sono matematicamente semplici. Eppure questi modelli possono diventare complessi in un modello multiperiodale.

A differenza del [modello Black-Scholes](/blackscholes),. che fornisce un risultato numerico basato sugli input, il modello binomiale consente il calcolo dell'attività e l'opzione per più periodi insieme alla gamma di risultati possibili per ciascun periodo (vedi sotto).

Il vantaggio di questa visualizzazione multiperiodale è che l'utente può visualizzare la variazione del prezzo dell'attività da un periodo all'altro e valutare l'opzione in base a decisioni prese in momenti diversi. Per [un'opzione con sede negli Stati Uniti](/americanoption),. che può essere esercitata in qualsiasi momento prima della data di [scadenza](/expirationdate),. il modello binomiale può fornire informazioni su quando può essere consigliabile esercitare l'opzione e quando dovrebbe essere detenuta per periodi più lunghi.

Osservando l' [albero binomiale](/binomial_tree) dei valori, un trader può determinare in anticipo quando può verificarsi una decisione su un [esercizio](/exercise). Se l'opzione ha un valore positivo vi è la possibilità di esercizio mentre, se l'opzione ha un valore inferiore a zero, dovrebbe essere detenuta per periodi più lunghi.

## Calcolo del prezzo con il modello binomiale

Il metodo di base per calcolare il modello di opzione binomiale consiste nell'utilizzare la stessa probabilità in ogni periodo di successo e fallimento fino alla scadenza dell'opzione. Tuttavia, un trader può incorporare probabilità diverse per ogni periodo in base alle nuove informazioni ottenute con il passare del tempo.

Un albero binomiale è uno strumento utile quando si valutano [le opzioni americane](/americanoption) e le opzioni [incorporate](/embeddedoption). La sua semplicità è il suo vantaggio e svantaggio allo stesso tempo. L'albero è facile da modellare meccanicamente, ma il problema risiede nei possibili valori che l'attività sottostante può assumere in un determinato periodo di tempo. In un modello ad albero binomiale, l'attività sottostante può valere esattamente solo uno dei due valori possibili, il che non è realistico, poiché le attività possono valere un numero qualsiasi di valori all'interno di un determinato intervallo.

Ad esempio, potrebbe esserci una probabilità del 50/50 che il prezzo dell'attività sottostante possa aumentare o diminuire del 30 percento in un periodo. Per il secondo periodo, tuttavia, la probabilità che il prezzo dell'attività sottostante aumenti fino a 70/30.

Ad esempio, se un investitore sta valutando un [pozzo petrolifero](/exploratory-well),. quell'investitore non è sicuro di quale sia il valore di quel pozzo petrolifero, ma c'è una probabilità del 50/50 che il prezzo salga. Se i prezzi del petrolio salgono nel periodo 1, rendendo il pozzo più prezioso e i [fondamentali del mercato](/fundamentals) ora indicano un aumento continuo dei prezzi del petrolio, la probabilità di un ulteriore apprezzamento del prezzo potrebbe ora essere del 70%. Il modello binomiale consente questa flessibilità; il modello Black-Scholes no.

<!--94DBA31F9D3220C6052579D485B8A416-->

## Esempio reale di modello di prezzo delle opzioni binomiali

Un esempio semplificato di [albero binomiale](/binomial_tree) ha solo un passaggio. Supponiamo che ci sia un'azione il cui prezzo è di $ 100 per azione. In un mese, il prezzo di questo titolo aumenterà di $ 10 o scenderà di $ 10, creando questa situazione:

- **Prezzo delle azioni** = $ 100

- **Prezzo delle azioni in un mese (stato superiore)** = $ 110

- **Prezzo delle azioni in un mese (stato down)** = $ 90

Quindi, supponiamo che sia disponibile un'opzione call su questo titolo che scade tra un mese e ha un prezzo di esercizio di $ 100. Nello stato in alto, questa opzione call vale $ 10 e nello stato in basso vale $ 0. Il modello binomiale può calcolare quale dovrebbe essere il prezzo dell'opzione call oggi.

A fini di semplificazione, si supponga che un investitore acquisti la metà delle azioni e scriva o venda un'opzione call. L'investimento totale di oggi è il prezzo di mezza azione meno il prezzo dell'opzione, e i possibili guadagni a fine mese sono:

- **Costo oggi** = $ 50 - prezzo dell'opzione

- **Valore del portafoglio** (stato attivo) = $ 55 - massimo ($ 110 - $ 100, 0) = $ 45

- **Valore del portafoglio** (stato inattivo) = $ 45 - max($ 90 - $ 100, 0) = $ 45

Il guadagno del portafoglio è uguale indipendentemente da come si muove il prezzo delle azioni. Dato questo risultato, supponendo che non ci siano opportunità di arbitraggio, un investitore dovrebbe guadagnare il tasso privo di rischio nel corso del mese. Il costo di oggi deve essere pari al payoff scontato al tasso privo di rischio per un mese. L'equazione da risolvere è quindi:

- **Prezzo dell'opzione** = $50 - $45 xe ^ (-tasso privo di rischio x T), dove e è la costante matematica 2,7183.

Supponendo che il tasso privo di rischio sia del 3% all'anno e che T sia pari a 0,0833 (uno diviso per 12), il prezzo dell'opzione call oggi è di $ 5,11.

Il modello binomiale dei prezzi delle opzioni presenta due vantaggi per i venditori di opzioni rispetto al modello Black-Scholes. Il primo è la sua semplicità, che consente meno errori nell'applicazione commerciale. Il secondo è la sua operazione iterativa, che adegua i prezzi in modo tempestivo in modo da ridurre l'opportunità per gli acquirenti di eseguire strategie di arbitraggio.

Ad esempio, poiché fornisce un flusso di valutazioni per un [derivato](/derivative) per ciascun nodo in un arco di tempo, è utile per valutare derivati come le opzioni americane, che possono essere eseguite in qualsiasi momento tra la data di acquisto e la data di scadenza. È anche molto più semplice di altri modelli di prezzo come il modello Black-Scholes.

## Mette in risalto

- Il modello è intuitivo e viene utilizzato più frequentemente nella pratica rispetto al noto modello Black-Scholes.

- Con il modello, ci sono due possibili risultati con ogni iterazione: uno spostamento in alto o uno in basso che segue un albero binomiale.

- Il modello binomiale di determinazione del prezzo delle opzioni valuta le opzioni utilizzando un approccio iterativo che utilizza più periodi per valutare le opzioni americane.

