---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: Modello Box-Jenkins
description: Il modello Box-Jenkins è un modello matematico progettato per prevedere i dati da una serie temporale specificata.
---

# Modello Box-Jenkins
## Qual è il modello Box-Jenkins?

Il modello Box-Jenkins è un modello matematico progettato per prevedere intervalli di dati basati sugli input di una [serie temporale specificata](/timeseries). Il modello Box-Jenkins può analizzare diversi tipi di dati di serie temporali a fini di previsione.

La sua metodologia utilizza le differenze tra i punti dati per determinare i risultati. La metodologia consente al modello di identificare le tendenze utilizzando l'autoregressione, le medie mobili e le differenze stagionali per generare previsioni.

[modelli di media mobile integrata autoregressiva (ARIMA)](/autoregressive-integrated-moving-average-arima) sono una forma del modello Box-Jenkins. I termini ARIMA e Box-Jenkins sono talvolta usati in modo intercambiabile.

## Capire il modello Box-Jenkins

I modelli Box-Jenkins vengono utilizzati per [prevedere](/forecasting) una varietà di punti dati o intervalli di dati previsti, inclusi dati aziendali e prezzi di sicurezza futuri.

Il modello Box-Jenkins è stato creato da due matematici: George Box e Gwilym Jenkins. I due matematici hanno discusso i concetti che compongono questo modello in una pubblicazione del 1970 intitolata "Analisi delle serie temporali: previsione e controllo".

Le stime dei parametri del modello Box-Jenkins possono essere molto complicate. Pertanto, analogamente ad altri modelli di regressione di serie temporali, i risultati migliori si ottengono in genere attraverso l'uso di software programmabili. Il modello Box-Jenkins è anche generalmente più adatto per previsioni a breve termine di 18 mesi o meno.

## Metodologia Box-Jenkins

Il modello Box-Jenkins può essere uno dei numerosi modelli di analisi di serie temporali che un previsore incontrerà utilizzando un software di previsione programmata. In molti casi, il software sarà programmato per utilizzare automaticamente la metodologia di previsione più adatta in base ai dati delle [serie temporali](/timeseries) da prevedere. Si dice che Box-Jenkins sia la scelta migliore per i set di dati che sono per lo più stabili e hanno una bassa [volatilità](/volatility).

Il modello Box-Jenkins prevede i dati utilizzando tre principi: autoregressione, differenziazione e media mobile. Questi tre principi sono noti rispettivamente come p, d e q. Ciascun principio viene utilizzato nell'analisi di Box-Jenkins; insieme, sono mostrati collettivamente come ARIMA (p, d, q).

Il processo di autoregressione (p) verifica i dati per il loro livello di stazionarietà. Se i dati utilizzati sono stazionari, possono semplificare il processo di previsione. Se i dati utilizzati non sono stazionari, dovranno essere differenziati (d). I dati vengono anche testati per l'adattamento della media mobile (che viene eseguito nella parte q del processo di analisi). Nel complesso, l'analisi iniziale dei dati li prepara per la previsione determinando i parametri (p, d e q), che vengono poi applicati per sviluppare una previsione.

> Uno shock una tantum influenzerà i valori successivi di un modello Box-Jenkins all'infinito nel futuro. Pertanto, l'eredità della crisi finanziaria sopravvive nei modelli autoregressivi di oggi.

>

## Media mobile integrata autoregressiva (ARIMA)

Box-Jenkins è un tipo di modello ARIMA (Autoregressive Integrated Moving Average) che misura la forza di una variabile dipendente rispetto ad altre variabili variabili. L'obiettivo del modello è di prevedere i futuri movimenti dei titoli o dei mercati finanziari esaminando le differenze tra i valori nelle serie anziché attraverso i valori effettivi.

Un modello ARIMA può essere compreso delineando ciascuno dei suoi componenti come segue:

- [Autoregression (AR)](/autoregressive) : si riferisce a un modello che mostra una variabile variabile che regredisce sui propri valori ritardati o precedenti.

- Integrato (I): rappresenta la differenziazione delle osservazioni grezze per consentire alle serie temporali di diventare stazionarie, ovvero i valori dei dati sono sostituiti dalla differenza tra i valori dei dati ei valori precedenti.

- [Media mobile (MA)](/movingaverage) : incorpora la dipendenza tra un'osservazione e un errore residuo da un modello di media mobile applicato alle osservazioni ritardate.

## Previsione dei prezzi delle azioni

Un utilizzo dell'analisi del modello Box-Jenkins è la previsione dei prezzi delle [azioni](/stock). Questa analisi è in genere costruita e codificata tramite il software R. L'analisi si traduce in un risultato logaritmico, che può essere applicato al set di dati per generare i prezzi previsti per un determinato periodo di tempo in futuro.

I modelli ARIMA si basano sul presupposto che i valori passati abbiano un effetto residuo sui valori attuali o futuri. Ad esempio, un investitore che utilizza un modello ARIMA per prevedere i prezzi delle azioni presuppone che i nuovi acquirenti e venditori di tale azione siano influenzati dalle recenti transazioni di mercato al momento di decidere quanto offrire o accettare per il titolo.

Sebbene questa ipotesi sia valida in molte circostanze diverse, non è sempre vera. Ad esempio, negli anni precedenti la crisi finanziaria del 2008, la maggior parte degli investitori non era consapevole dei rischi posti dagli ampi portafogli di [titoli garantiti da ipoteca](/mbs) (MBS) detenuti da molte società finanziarie.

Durante quei periodi, un investitore che utilizzava un modello autoregressivo per prevedere la performance dei titoli finanziari statunitensi avrebbe avuto buone ragioni per prevedere una tendenza in corso di prezzi delle azioni stabili o in aumento in quel settore. Tuttavia, una volta che è diventato di dominio pubblico che molte istituzioni finanziarie erano a rischio di un imminente collasso, gli investitori sono improvvisamente diventati meno preoccupati per i prezzi recenti di questi titoli e molto più preoccupati per la loro esposizione al rischio sottostante.

Pertanto, il mercato ha rapidamente rivalutato i titoli finanziari a un livello molto più basso, una mossa che avrebbe completamente confuso un modello autoregressivo.

## Mette in risalto

- I modelli di media mobile integrata autoregressiva (ARIMA) sono una forma del modello Box-Jenkins.

- Il modello Box-Jenkins è più adatto per la previsione entro intervalli di tempo di 18 mesi o meno.

- La metodologia si basa sul presupposto che gli eventi passati influenzino quelli futuri.

- Il modello Box-Jenkins è una metodologia di previsione che utilizza studi di regressione su dati di serie temporali.

