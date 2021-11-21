---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: Media mobile integrata autoregressiva (ARIMA)
description: Una media mobile integrata autoregressiva (ARIMA) è un modello di analisi statistica che sfrutta i dati delle serie temporali per prevedere le tendenze future.
---

# Media mobile integrata autoregressiva (ARIMA)
## Che cos'è una media mobile integrata autoregressiva (ARIMA)?

Una media mobile integrata autoregressiva, o ARIMA, è un modello di analisi statistica che utilizza i dati delle [serie temporali](/timeseries) per comprendere meglio il set di dati o per prevedere le tendenze future.

Un modello statistico è autoregressivo se prevede valori futuri basati su valori passati. Ad esempio, un modello ARIMA potrebbe cercare di prevedere i prezzi futuri di un'azione in base alla sua performance passata o prevedere gli utili di una società in base a periodi passati.

## Comprendere la media mobile integrata autoregressiva (ARIMA)

Un modello di media mobile integrato autoregressivo è una forma di [analisi di regressione](/regression) che misura la forza di una variabile dipendente rispetto ad altre variabili variabili. L'obiettivo del modello è di prevedere i futuri movimenti dei titoli o dei mercati finanziari esaminando le differenze tra i valori nelle serie anziché attraverso i valori effettivi.

Un modello ARIMA può essere compreso delineando ciascuno dei suoi componenti come segue:

- [Autoregression (AR)](/autoregressive) : si riferisce a un modello che mostra una variabile variabile che regredisce sui propri valori ritardati o precedenti.

- **Integrato (I):** rappresenta la differenziazione delle osservazioni grezze per consentire alle serie temporali di diventare stazionarie (ovvero, i valori dei dati sono sostituiti dalla differenza tra i valori dei dati e i valori precedenti).

- [Media mobile (MA)](/movingaverage) : incorpora la dipendenza tra un'osservazione e un errore residuo da un modello di media mobile applicato alle osservazioni ritardate.

## Parametri ARIMA

Ciascun componente in ARIMA funziona come un parametro con una notazione standard. Per i modelli ARIMA, una notazione standard sarebbe ARIMA con p, d e q, dove i valori interi sostituiscono i parametri per indicare il tipo di modello ARIMA utilizzato. I parametri possono essere definiti come:

- **p**: il numero di osservazioni di ritardo nel modello; noto anche come ordine di ritardo.

- **d**: il numero di volte in cui le osservazioni grezze vengono differenziate; noto anche come grado di differenziazione.

- q: la dimensione della finestra della media mobile; noto anche come ordine della media mobile.

In un modello di [regressione lineare](/nonlinear-regression),. ad esempio, sono inclusi il numero e il tipo di termini. Un valore 0, che può essere utilizzato come parametro, significherebbe che un particolare componente non deve essere utilizzato nel modello. In questo modo, il modello ARIMA può essere costruito per svolgere la funzione di un modello ARMA, o anche semplici modelli AR, I o MA.

> Poiché i modelli ARIMA sono complicati e funzionano meglio su insiemi di dati molto grandi, per calcolarli vengono utilizzati algoritmi informatici e tecniche di apprendimento automatico.

>

## Media mobile integrata autoregressiva (ARIMA) e stazionarietà

In un modello di media mobile integrato autoregressivo, i dati vengono differenziati per renderli stazionari. Un modello che mostra la stazionarietà è quello che mostra la costanza dei dati nel tempo. La maggior parte dei dati economici e di mercato mostra le tendenze, quindi lo scopo della differenziazione è rimuovere eventuali tendenze o strutture stagionali.

[La stagionalità](/seasonality),. o quando i dati mostrano schemi regolari e prevedibili che si ripetono nell'arco di un anno solare, potrebbero influire negativamente sul modello di regressione. Se compare una tendenza e la stazionarietà non è evidente, molti dei calcoli durante il processo non possono essere eseguiti con grande efficacia.

> Uno shock una tantum influenzerà i valori successivi di un modello ARIMA all'infinito nel futuro. Pertanto, l'eredità della crisi finanziaria sopravvive nei modelli autoregressivi di oggi.

>

## Considerazioni speciali

I modelli ARIMA si basano sul presupposto che i valori passati abbiano un effetto residuo sui valori attuali o futuri. Ad esempio, un investitore che utilizza un modello ARIMA per prevedere i prezzi delle azioni presuppone che i nuovi acquirenti e venditori di tale azione siano influenzati dalle recenti transazioni di mercato al momento di decidere quanto offrire o accettare per il titolo.

Sebbene questa ipotesi sia valida in molte circostanze, non è sempre così. Ad esempio, negli anni precedenti la crisi finanziaria del 2008, la maggior parte degli investitori non era consapevole dei rischi posti dagli ampi portafogli di [titoli garantiti da ipoteca](/mbs) (MBS) detenuti da molte società finanziarie.

Durante quei periodi, un investitore che utilizzava un modello autoregressivo per prevedere la performance dei titoli finanziari statunitensi avrebbe avuto buone ragioni per prevedere una tendenza in corso di prezzi delle azioni stabili o in aumento in quel settore. Tuttavia, una volta che è diventato di dominio pubblico che molte istituzioni finanziarie erano a rischio di un imminente collasso, gli investitori sono improvvisamente diventati meno preoccupati per i prezzi recenti di questi titoli e molto più preoccupati per la loro esposizione al rischio sottostante. Pertanto, il mercato ha rapidamente rivalutato i titoli finanziari a un livello molto più basso, una mossa che avrebbe completamente confuso un modello autoregressivo.

## Domande frequenti

### A cosa serve ARIMA?

ARIMA è un metodo per prevedere o prevedere i risultati futuri sulla base di una serie storica. Si basa sul concetto statistico di correlazione seriale, in cui i punti dati passati influenzano i punti dati futuri.

### Quali sono le differenze tra i modelli autoregressivi e a media mobile?

ARIMA combina le caratteristiche autoregressive con quelle delle medie mobili. Un processo autoregressivo AR(1), ad esempio, è quello in cui il valore corrente è basato sul valore immediatamente precedente, mentre un processo AR(2) è quello in cui il valore corrente è basato sui due valori precedenti. Una media mobile è un calcolo utilizzato per analizzare i punti dati creando una serie di medie di diversi sottoinsiemi dell'intero set di dati al fine di attenuare l'influenza dei valori anomali. Come risultato di questa combinazione di tecniche, i modelli ARIMA possono tenere conto di tendenze, cicli, stagionalità e altri tipi di dati non statici quando si effettuano previsioni.

### Come funziona la previsione ARIMA?

La previsione ARIMA si ottiene inserendo i dati delle serie temporali per la variabile di interesse. Il software statistico identificherà il numero appropriato di ritardi o la quantità di differenze da applicare ai dati e ne verificherà la stazionarietà. Quindi produrrà i risultati, che sono spesso interpretati in modo simile a quello di un modello di regressione lineare multipla.

## Mette in risalto

- I modelli di media mobile integrata autoregressiva (ARIMA) predicono i valori futuri in base ai valori passati.

- ARIMA utilizza le medie mobili ritardate per uniformare i dati delle serie temporali.

- Sono ampiamente utilizzati nell'analisi tecnica per prevedere i prezzi futuri dei titoli.

- I modelli autoregressivi presuppongono implicitamente che il futuro assomiglierà al passato.

- Pertanto, possono rivelarsi imprecisi in determinate condizioni di mercato, come crisi finanziarie o periodi di rapidi cambiamenti tecnologici.

