---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: Box-Jenkins-Modell
description: Das Box-Jenkins-Modell ist ein mathematisches Modell zur Vorhersage von Daten aus einer bestimmten Zeitreihe.
---

# Box-Jenkins-Modell
## Was ist das Box-Jenkins-Modell?

Das Box-Jenkins-Modell ist ein mathematisches Modell zur Vorhersage von Datenbereichen basierend auf Eingaben aus einer bestimmten [Zeitreihe](/timeseries). Das Box-Jenkins-Modell kann mehrere verschiedene Arten von Zeitreihendaten für Prognosezwecke analysieren.

Seine Methodik verwendet Unterschiede zwischen Datenpunkten, um Ergebnisse zu bestimmen. Die Methodik ermöglicht es dem Modell, Trends mithilfe von Autoregression, gleitenden Durchschnitten und saisonaler Differenzierung zu identifizieren, um Prognosen zu erstellen.

[Modelle des autoregressiven integrierten gleitenden Durchschnitts (ARIMA)](/autoregressive-integrated-moving-average-arima) sind eine Form des Box-Jenkins-Modells. Die Begriffe ARIMA und Box-Jenkins werden manchmal synonym verwendet.

## Verständnis des Box-Jenkins-Modells

Box-Jenkins-Modelle werden zur [Vorhersage](/forecasting) einer Vielzahl erwarteter Datenpunkte oder Datenbereiche verwendet, einschließlich Geschäftsdaten und zukünftiger Wertpapierkurse.

Das Box-Jenkins-Modell wurde von zwei Mathematikern entwickelt: George Box und Gwilym Jenkins. Die beiden Mathematiker diskutierten die Konzepte, die dieses Modell umfassen, in einer 1970 erschienenen Veröffentlichung mit dem Titel „Time Series Analysis: Forecasting and Control“.

Schätzungen der Parameter des Box-Jenkins-Modells können sehr kompliziert sein. Daher werden, ähnlich wie bei anderen Zeitreihen-Regressionsmodellen, die besten Ergebnisse typischerweise durch die Verwendung programmierbarer Software erzielt. Das Box-Jenkins-Modell eignet sich im Allgemeinen auch am besten für kurzfristige Prognosen von 18 Monaten oder weniger.

## Box-Jenkins-Methodik

Das Box-Jenkins-Modell kann eines von mehreren Zeitreihenanalysemodellen sein, denen ein Prognostiker begegnen wird, wenn er programmierte Prognosesoftware verwendet. In vielen Fällen wird die Software so programmiert, dass sie basierend auf den zu prognostizierenden [Zeitreihendaten automatisch die am besten geeignete](/timeseries) Prognosemethodik verwendet. Box-Jenkins gilt als erste Wahl für Datensätze, die größtenteils stabil sind und eine geringe [Volatilität aufweisen](/volatility).

Das Box-Jenkins-Modell prognostiziert Daten anhand von drei Prinzipien: Autoregression, Differenzierung und gleitender Durchschnitt. Diese drei Prinzipien sind als p, d bzw. q bekannt. Jedes Prinzip wird in der Box-Jenkins-Analyse verwendet; zusammen werden sie gemeinsam als ARIMA (p, d, q) angezeigt.

Der Autoregressionsprozess (p) testet die Daten auf ihren Grad an Stationarität. Wenn die verwendeten Daten stationär sind, kann dies den Prognoseprozess vereinfachen. Wenn die verwendeten Daten nicht stationär sind, müssen sie differenziert werden (d). Die Daten werden auch auf ihre Anpassung an den gleitenden Durchschnitt getestet (was in Teil q des Analyseprozesses erfolgt). Insgesamt bereitet die anfängliche Analyse der Daten diese für die Prognose vor, indem die Parameter (p, d und q) bestimmt werden, die dann zur Entwicklung einer Prognose verwendet werden.

> Ein einmaliger Schock wirkt sich unendlich auf nachfolgende Werte eines Box-Jenkins-Modells in der Zukunft aus. Daher lebt das Erbe der Finanzkrise in den heutigen autoregressiven Modellen weiter.

>

## Autoregressiver integrierter gleitender Durchschnitt (ARIMA)

Box-Jenkins ist eine Art autoregressives integriertes gleitendes Durchschnittsmodell (ARIMA), das die Stärke einer abhängigen Variablen im Verhältnis zu anderen sich ändernden Variablen misst. Ziel des Modells ist es, zukünftige Wertpapier- oder Finanzmarktbewegungen vorherzusagen, indem die Unterschiede zwischen Werten in der Reihe untersucht werden, anstatt durch tatsächliche Werte.

Ein ARIMA-Modell kann verstanden werden, indem jede seiner Komponenten wie folgt beschrieben wird:

- [Autoregression (AR)](/autoregressive) : bezieht sich auf ein Modell, das eine sich ändernde Variable zeigt, die auf ihre eigenen verzögerten oder früheren Werte zurückgeht.

- Integriert (I): stellt die Differenzierung von Rohbeobachtungen dar, um zu ermöglichen, dass die Zeitreihe stationär wird, dh Datenwerte werden durch die Differenz zwischen den Datenwerten und den vorherigen Werten ersetzt.

- [Gleitender Durchschnitt (MA)](/movingaverage) : beinhaltet die Abhängigkeit zwischen einer Beobachtung und einem Restfehler aus einem gleitenden Durchschnittsmodell, das auf verzögerte Beobachtungen angewendet wird.

## Prognose von Aktienkursen

Eine Anwendung für die Analyse des Box-Jenkins-Modells ist die Prognose [von Aktienkursen](/stock). Diese Analyse wird in der Regel mithilfe von R-Software erstellt und codiert. Die Analyse führt zu einem logarithmischen Ergebnis, das auf den Datensatz angewendet werden kann, um die prognostizierten Preise für einen bestimmten Zeitraum in der Zukunft zu generieren.

ARIMA-Modelle basieren auf der Annahme, dass vergangene Werte einen gewissen Resteffekt auf aktuelle oder zukünftige Werte haben. Beispielsweise würde ein Investor, der ein ARIMA-Modell zur Prognose von Aktienkursen verwendet, davon ausgehen, dass neue Käufer und Verkäufer dieser Aktie von den jüngsten Markttransaktionen beeinflusst werden, wenn er entscheidet, wie viel er für das Wertpapier anbietet oder akzeptiert.

Obwohl diese Annahme unter vielen verschiedenen Umständen gelten wird, ist sie nicht immer wahr. Beispielsweise waren sich die meisten Anleger in den Jahren vor der Finanzkrise 2008 nicht der Risiken bewusst, die von den großen Portfolios an [hypothekenbesicherten Wertpapieren](/mbs) (MBS) ausgehen, die von vielen Finanzunternehmen gehalten werden.

Während dieser Zeiten hätte ein Investor, der ein autoregressives Modell zur Vorhersage der Wertentwicklung von US-Finanzaktien verwendet, guten Grund gehabt, einen anhaltenden Trend stabiler oder steigender Aktienkurse in diesem Sektor vorherzusagen. Als jedoch öffentlich bekannt wurde, dass vielen Finanzinstituten das Risiko eines bevorstehenden Zusammenbruchs drohte, machten sich die Anleger plötzlich weniger Gedanken über die jüngsten Kurse dieser Aktien und viel mehr über das zugrunde liegende Risiko.

Daher hat der Markt Finanzaktien schnell auf ein viel niedrigeres Niveau neu bewertet, eine Bewegung, die ein autoregressives Modell völlig durcheinander gebracht hätte.

## Höhepunkte

- Modelle des autoregressiven integrierten gleitenden Durchschnitts (ARIMA) sind eine Form des Box-Jenkins-Modells.

- Das Box-Jenkins-Modell eignet sich am besten für Prognosen innerhalb von Zeiträumen von 18 Monaten oder weniger.

- Die Methodik basiert auf der Annahme, dass vergangene Ereignisse zukünftige beeinflussen.

- Das Box-Jenkins-Modell ist eine Prognosemethode, die Regressionsstudien auf Zeitreihendaten verwendet.

