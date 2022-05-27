---
keywords: Economy,Economics,Behavioral Economics
title: Induzione all&#39;indietro
description: Nella teoria dei giochi, l&#39;induzione all&#39;indietro è il processo di deduzione all&#39;indietro dalla fine di un problema o di uno scenario per dedurre una sequenza di azioni ottimali.
---

# Induzione all'indietro
## Che cos'è l'induzione all'indietro?

L'induzione all'indietro nella [teoria dei giochi](/gametheory) è un processo iterativo di ragionamento indietro nel tempo, dalla fine di un problema o di una situazione, per risolvere forme estensive finite e giochi sequenziali e dedurre una sequenza di azioni ottimali.

## Spiegazione dell'induzione all'indietro

L'induzione all'indietro è stata utilizzata per risolvere i giochi da quando John von Neumann e Oskar Morgenstern hanno stabilito la teoria dei giochi come materia accademica quando hanno pubblicato il loro libro **Theory of Games and Economic Behavior** nel 1944.

In ogni fase del gioco l'induzione all'indietro determina la strategia ottimale del giocatore che fa l'ultima mossa nel gioco. Quindi, viene determinata l'azione ottimale del penultimo giocatore in movimento, prendendo come data l'azione dell'ultimo giocatore. Questo processo continua all'indietro fino a quando non è stata determinata l'azione migliore per ogni momento. In effetti, si sta determinando l' [equilibrio di Nash](/nash-equilibrium) di ogni sottogioco del gioco originale.

Tuttavia, i risultati dedotti dall'induzione all'indietro spesso non riescono a prevedere il gioco umano effettivo. Studi sperimentali hanno dimostrato che il comportamento "razionale" (come previsto dalla teoria dei giochi) si manifesta raramente nella vita reale. I giocatori irrazionali possono effettivamente finire per ottenere guadagni più alti di quanto previsto dall'induzione all'indietro, come illustrato nel [gioco del millepiedi](/centipede-game).

Nel gioco del millepiedi, due giocatori hanno alternativamente la possibilità di prendere una quota maggiore di un piatto di denaro crescente o di passare il piatto all'altro giocatore. Le vincite sono organizzate in modo tale che se il piatto viene passato al proprio avversario e l'avversario prende il piatto nel round successivo, si riceve leggermente meno che se si fosse preso il piatto in questo round. Il gioco si conclude non appena un giocatore prende la scorta, con quel giocatore che ottiene la parte più grande e l'altro giocatore che ottiene la parte più piccola.

## Esempio di induzione all'indietro

Ad esempio, supponiamo che Izaz inizi per primo e debba decidere se "prendere" o "passare" la scorta, che attualmente ammonta a $ 2. Se prendono, allora Izaz e Jian ottengono $ 1 ciascuno, ma se Izaz passa, la decisione di prendere o passare ora deve essere presa da Jian. Se Jian prende, ottengono $ 3 (cioè, la scorta precedente di $ 2 + $ 1) e Izaz ottiene $ 0. Ma se Jian passa, Izaz ora decide se prendere o passare, e così via. Se entrambi i giocatori scelgono sempre di passare, alla fine del gioco riceveranno ciascuno una vincita di $100.

Il punto del gioco è che se Izaz e Jian collaborano e continuano a passare fino alla fine del gioco, ottengono la vincita massima di $ 100 ciascuno. Ma se non si fidano dell'altro giocatore e si aspettano che lo "prendano" alla prima opportunità, l'equilibrio di Nash prevede che i giocatori prenderanno la pretesa più bassa possibile ($ 1 in questo caso).

L'equilibrio di Nash di questo gioco, in cui nessun giocatore ha un incentivo a deviare dalla strategia scelta dopo aver considerato la scelta di un avversario, suggerisce che il primo giocatore prenderebbe il piatto al primo round del gioco. Tuttavia, in realtà, relativamente pochi giocatori lo fanno. Di conseguenza, ottengono un guadagno maggiore rispetto a quello previsto dall'analisi degli equilibri.

## Risolvere giochi sequenziali utilizzando l'induzione all'indietro

Di seguito è riportato un semplice gioco sequenziale tra due giocatori. Le etichette con Player 1 e Player 2 al loro interno sono i set di informazioni rispettivamente per i giocatori uno o due. I numeri tra parentesi in fondo all'albero sono i guadagni in ogni rispettivo punto. Il gioco è anche sequenziale, quindi il Giocatore 1 prende la prima decisione (sinistra o destra) e il Giocatore 2 prende la sua decisione dopo il Giocatore 1 (su o giù).

<!--360C571136D68BDF7B1BE984014B1A1C-->

L'induzione all'indietro, come tutta la teoria dei giochi, utilizza i presupposti di razionalità e massimizzazione, il che significa che il giocatore 2 massimizzerà il proprio guadagno in una data situazione. In entrambi i set di informazioni abbiamo due scelte, quattro in tutto. Eliminando le scelte che il giocatore 2 non sceglierà, possiamo restringere il nostro albero. In questo modo, contrassegneremo le linee in blu che massimizzano il payoff del giocatore al set di informazioni fornito.

<!--E78C02A07C982A1B447ED0D16A9FCE40-->

Dopo questa riduzione, il giocatore 1 può massimizzare i suoi guadagni ora che le scelte del giocatore 2 sono rese note. Il risultato è un equilibrio trovato dall'induzione all'indietro del giocatore 1 che sceglie "giusto" e del giocatore 2 che sceglie "su". Di seguito è riportata la soluzione del gioco con il percorso dell'equilibrio in grassetto.

<!--4DEC4364358F0D1CB7D219006F74D652-->

Ad esempio, si potrebbe facilmente impostare un gioco simile a quello sopra utilizzando le aziende come giocatori. Questo gioco potrebbe includere scenari di [rilascio del prodotto .](/rollout) Se l'Azienda 1 volesse rilasciare un prodotto, cosa potrebbe fare l'Azienda 2 in risposta? Company 2 rilascerà un prodotto concorrente simile? Prevedendo le vendite di questo nuovo prodotto in diversi scenari, possiamo creare un gioco per prevedere come potrebbero svolgersi gli eventi [.](/forecasting) Di seguito è riportato un esempio di come si potrebbe modellare un gioco del genere.

<!--D102F649421403ABDBD56A5C1B29CF03-->

