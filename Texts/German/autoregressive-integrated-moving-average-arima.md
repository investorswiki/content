---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: Autoregressiver integrierter gleitender Durchschnitt (ARIMA)
description: Ein autoregressiver integrierter gleitender Durchschnitt (ARIMA) ist ein statistisches Analysemodell, das Zeitreihendaten nutzt, um zukünftige Trends vorherzusagen.
---

# Autoregressiver integrierter gleitender Durchschnitt (ARIMA)
## Was ist ein autoregressiver integrierter gleitender Durchschnitt (ARIMA)?

Ein autoregressiver integrierter gleitender Durchschnitt oder ARIMA ist ein statistisches Analysemodell, das [Zeitreihendaten verwendet](/timeseries),. um entweder den Datensatz besser zu verstehen oder zukünftige Trends vorherzusagen.

Ein statistisches Modell ist autoregressiv, wenn es zukünftige Werte basierend auf vergangenen Werten vorhersagt. Beispielsweise könnte ein ARIMA-Modell versuchen, die zukünftigen Kurse einer Aktie auf der Grundlage ihrer vergangenen Performance vorherzusagen oder die Gewinne eines Unternehmens auf der Grundlage vergangener Perioden vorherzusagen.

## Autoregressive Integrated Moving Average (ARIMA) verstehen

Ein autoregressives integriertes gleitendes Durchschnittsmodell ist eine Form der [Regressionsanalyse](/regression),. die die Stärke einer abhängigen Variablen im Verhältnis zu anderen sich ändernden Variablen misst. Ziel des Modells ist es, zukünftige Wertpapier- oder Finanzmarktbewegungen vorherzusagen, indem die Unterschiede zwischen Werten in der Reihe untersucht werden, anstatt durch tatsächliche Werte.

Ein ARIMA-Modell kann verstanden werden, indem jede seiner Komponenten wie folgt beschrieben wird:

- [Autoregression (AR)](/autoregressive) : bezieht sich auf ein Modell, das eine sich ändernde Variable zeigt, die auf ihre eigenen verzögerten oder früheren Werte zurückgeht.

- **Integriert (I):** stellt die Differenzierung von Rohbeobachtungen dar, um zu ermöglichen, dass die Zeitreihen stationär werden (dh Datenwerte werden durch die Differenz zwischen den Datenwerten und den vorherigen Werten ersetzt).

- [Gleitender Durchschnitt (MA)](/movingaverage) : beinhaltet die Abhängigkeit zwischen einer Beobachtung und einem Restfehler aus einem gleitenden Durchschnittsmodell, das auf verzögerte Beobachtungen angewendet wird.

## ARIMA-Parameter

Jede Komponente in ARIMA fungiert als Parameter mit einer Standardnotation. Für ARIMA-Modelle wäre eine Standardnotation ARIMA mit p, d und q, wobei ganzzahlige Werte die Parameter ersetzen, um den Typ des verwendeten ARIMA-Modells anzugeben. Die Parameter können wie folgt definiert werden:

- **p**: die Anzahl der Verzögerungsbeobachtungen im Modell; auch bekannt als Lag-Order.

- **d**: die Häufigkeit, mit der die Rohbeobachtungen differenziert werden; auch Differenzierungsgrad genannt.

- q: die Größe des gleitenden Durchschnittsfensters; auch als Ordnung des gleitenden Durchschnitts bekannt.

In ein [lineares Regressionsmodell](/nonlinear-regression) gehen beispielsweise Anzahl und Art der Terme ein. Ein 0-Wert, der als Parameter verwendet werden kann, würde bedeuten, dass eine bestimmte Komponente nicht im Modell verwendet werden sollte. Auf diese Weise kann das ARIMA-Modell konstruiert werden, um die Funktion eines ARMA-Modells oder sogar einfacher AR-, I- oder MA-Modelle auszuführen.

> Da ARIMA-Modelle kompliziert sind und am besten mit sehr großen Datensätzen funktionieren, werden Computeralgorithmen und maschinelle Lerntechniken verwendet, um sie zu berechnen.

>

## Autoregressiver integrierter gleitender Durchschnitt (ARIMA) und Stationarität

In einem autoregressiven integrierten gleitenden Durchschnittsmodell werden die Daten differenziert, um sie stationär zu machen. Ein Modell, das Stationarität zeigt, ist eines, das zeigt, dass die Daten über die Zeit konstant sind. Die meisten Wirtschafts- und Marktdaten zeigen Trends, daher besteht der Zweck der Differenzierung darin, Trends oder saisonale Strukturen zu entfernen.

[Saisonalität](/seasonality) oder wenn Daten regelmäßige und vorhersehbare Muster zeigen, die sich über ein Kalenderjahr wiederholen, könnte das Regressionsmodell negativ beeinflussen. Wenn ein Trend auftritt und keine Stationarität offensichtlich ist, können viele der Berechnungen während des gesamten Prozesses nicht mit großer Effizienz durchgeführt werden.

> Ein einmaliger Schock wirkt sich unendlich auf nachfolgende Werte eines ARIMA-Modells in der Zukunft aus. Daher lebt das Erbe der Finanzkrise in den heutigen autoregressiven Modellen weiter.

>

## Besondere Überlegungen

ARIMA-Modelle basieren auf der Annahme, dass vergangene Werte einen gewissen Resteffekt auf aktuelle oder zukünftige Werte haben. Beispielsweise würde ein Investor, der ein ARIMA-Modell zur Prognose von Aktienkursen verwendet, davon ausgehen, dass neue Käufer und Verkäufer dieser Aktie von den jüngsten Markttransaktionen beeinflusst werden, wenn er entscheidet, wie viel er für das Wertpapier anbietet oder akzeptiert.

Obwohl diese Annahme unter vielen Umständen gelten wird, ist dies nicht immer der Fall. Beispielsweise waren sich die meisten Anleger in den Jahren vor der Finanzkrise 2008 nicht der Risiken bewusst, die von den großen Portfolios an [hypothekenbesicherten Wertpapieren](/mbs) (MBS) ausgehen, die von vielen Finanzunternehmen gehalten werden.

Während dieser Zeiten hätte ein Investor, der ein autoregressives Modell zur Vorhersage der Wertentwicklung von US-Finanzaktien verwendet, guten Grund gehabt, einen anhaltenden Trend stabiler oder steigender Aktienkurse in diesem Sektor vorherzusagen. Als jedoch öffentlich bekannt wurde, dass vielen Finanzinstituten das Risiko eines bevorstehenden Zusammenbruchs drohte, machten sich die Anleger plötzlich weniger Gedanken über die jüngsten Kurse dieser Aktien und viel mehr über das zugrunde liegende Risiko. Daher hat der Markt Finanzaktien schnell auf ein viel niedrigeres Niveau neu bewertet, eine Bewegung, die ein autoregressives Modell völlig durcheinander gebracht hätte.

## Häufig gestellte Fragen

### Wofür wird ARIMA verwendet?

ARIMA ist eine Methode zur Vorhersage oder Vorhersage zukünftiger Ergebnisse auf der Grundlage einer historischen Zeitreihe. Es basiert auf dem statistischen Konzept der seriellen Korrelation, bei der vergangene Datenpunkte zukünftige Datenpunkte beeinflussen.

### Was sind die Unterschiede zwischen autoregressiven und gleitenden Durchschnittsmodellen?

ARIMA kombiniert autoregressive Merkmale mit denen von gleitenden Durchschnitten. Ein autoregressiver AR(1)-Prozess ist beispielsweise einer, bei dem der aktuelle Wert auf dem unmittelbar vorhergehenden Wert basiert, während ein AR(2)-Prozess einer ist, bei dem der aktuelle Wert auf den vorherigen zwei Werten basiert. Ein gleitender Durchschnitt ist eine Berechnung, die zur Analyse von Datenpunkten verwendet wird, indem eine Reihe von Durchschnittswerten verschiedener Teilmengen des vollständigen Datensatzes erstellt wird, um den Einfluss von Ausreißern auszugleichen. Als Ergebnis dieser Kombination von Techniken können ARIMA-Modelle bei der Erstellung von Prognosen Trends, Zyklen, Saisonalität und andere nicht statische Datentypen berücksichtigen.

### Wie funktioniert die ARIMA-Prognose?

Die ARIMA-Prognose wird durch Einfügen von Zeitreihendaten für die interessierende Variable erreicht. Eine statistische Software identifiziert die geeignete Anzahl von Verzögerungen oder das Ausmaß der Differenzierung, die auf die Daten angewendet werden soll, und prüft auf Stationarität. Es gibt dann die Ergebnisse aus, die oft ähnlich wie bei einem multiplen linearen Regressionsmodell interpretiert werden.

## Höhepunkte

- Modelle des autoregressiven integrierten gleitenden Durchschnitts (ARIMA) sagen zukünftige Werte basierend auf vergangenen Werten voraus.

- ARIMA verwendet verzögerte gleitende Durchschnitte, um Zeitreihendaten zu glätten.

- Sie werden häufig in der technischen Analyse verwendet, um zukünftige Wertpapierpreise vorherzusagen.

- Autoregressive Modelle gehen implizit davon aus, dass die Zukunft der Vergangenheit ähneln wird.

- Daher können sie sich unter bestimmten Marktbedingungen wie Finanzkrisen oder Zeiten schnellen technologischen Wandels als ungenau erweisen.

