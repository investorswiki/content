---
keywords: Trading,Options and Derivatives Trading,Options and Derivatives
title: Preismodell für binomiale Optionen
description: Ein binomiales Optionspreismodell ist eine Optionsbewertungsmethode, die ein iteratives Verfahren verwendet und die Knotenspezifikation in einem festgelegten Zeitraum zulässt.
---

# Preismodell für binomiale Optionen
## Was ist das binomiale Optionspreismodell?

Das binomiale Optionspreismodell ist eine 1979 entwickelte [Optionsbewertungsmethode](/valuation). Das binomiale Optionspreismodell verwendet ein iteratives Verfahren, das die Angabe von Knoten oder Zeitpunkten während der Zeitspanne zwischen dem Bewertungsdatum und dem Verfallsdatum der [Option](/expiration-date) [ermöglicht](/expiration-date).

Das Modell reduziert die Möglichkeiten von Preisänderungen und schließt die Möglichkeit von [Arbitrage aus](/arbitrage). Ein vereinfachtes Beispiel eines [Binomialbaums](/binomial_tree) könnte etwa so aussehen:

<!--87C9D3D79FF63D08201E6E848035602D-->

## Grundlagen des binomialen Optionspreismodells

Bei binomialen Optionspreismodellen wird davon ausgegangen, dass es zwei mögliche Ergebnisse gibt – daher der binomiale Teil des Modells. Bei einem Preismodell sind die beiden Ergebnisse eine Bewegung nach oben oder eine Bewegung nach unten. Der Hauptvorteil eines binomialen Optionspreismodells besteht darin, dass es mathematisch einfach ist. Diese Modelle können jedoch in einem Mehrperiodenmodell komplex werden.

Im Gegensatz zum [Black-Scholes-Modell](/blackscholes),. das ein numerisches Ergebnis basierend auf Eingaben liefert, ermöglicht das Binomialmodell die Berechnung des Vermögenswerts und die Option für mehrere Perioden sowie die Bandbreite möglicher Ergebnisse für jede Periode (siehe unten).

Der Vorteil dieser Mehrperiodenansicht besteht darin, dass der Benutzer die Veränderung des Vermögenspreises von Periode zu Periode visualisieren und die Option basierend auf Entscheidungen, die zu verschiedenen Zeitpunkten getroffen wurden, bewerten kann. Für eine US-basierte [Option](/americanoption),. die jederzeit vor dem [Ablaufdatum ausgeübt werden kann](/expirationdate),. kann das Binomialmodell Aufschluss darüber geben, wann die Ausübung der Option ratsam sein kann und wann sie für längere Zeiträume gehalten werden sollte.

Durch Betrachten des [Binomialbaums](/binomial_tree) der Werte kann ein Trader im Voraus bestimmen, wann eine Entscheidung über eine [Ausübung getroffen](/exercise) werden kann. Bei einem positiven Wert der Option besteht die Möglichkeit der Ausübung, bei einem Wert kleiner null sollte die Option länger gehalten werden.

## Preisberechnung mit dem Binomialmodell

Die grundlegende Methode zur Berechnung des binomialen Optionsmodells besteht darin, für jeden Zeitraum die gleiche Wahrscheinlichkeit für Erfolg und Misserfolg zu verwenden, bis die Option ausläuft. Ein Händler kann jedoch unterschiedliche Wahrscheinlichkeiten für jeden Zeitraum einbeziehen, basierend auf neuen Informationen, die er im Laufe der Zeit erhält.

Ein Binomialbaum ist ein nützliches Hilfsmittel bei der Preisfindung für [amerikanische Optionen](/americanoption) und [eingebettete Optionen](/embeddedoption). Seine Einfachheit ist sein Vor- und Nachteil zugleich. Der Baum lässt sich leicht mechanisch modellieren, aber das Problem liegt in den möglichen Werten, die der zugrunde liegende Vermögenswert in einem bestimmten Zeitraum annehmen kann. In einem Binomialbaummodell kann der zugrunde liegende Vermögenswert nur genau einen von zwei möglichen Werten wert sein, was nicht realistisch ist, da Vermögenswerte innerhalb eines bestimmten Bereichs eine beliebige Anzahl von Werten wert sein können.

Beispielsweise kann eine 50/50-Wahrscheinlichkeit bestehen, dass der Kurs des zugrunde liegenden Vermögenswerts in einer Periode um 30 Prozent steigen oder fallen kann. Für die zweite Periode kann die Wahrscheinlichkeit, dass der Kurs des Basiswerts steigt, jedoch auf 70/30 steigen.

Wenn ein Investor beispielsweise eine [Ölquelle bewertet](/exploratory-well),. ist sich dieser Investor nicht sicher, wie hoch der Wert dieser Ölquelle ist, aber es besteht eine 50/50-Wahrscheinlichkeit, dass der Preis steigen wird. Wenn die Ölpreise in Periode 1 steigen, wodurch die Ölquelle wertvoller wird und die [Fundamentaldaten des Marktes](/fundamentals) nun auf einen anhaltenden Anstieg der Ölpreise hindeuten, kann die Wahrscheinlichkeit einer weiteren Preissteigerung jetzt 70 Prozent betragen. Das Binomialmodell ermöglicht diese Flexibilität; das Black-Scholes-Modell nicht.

<!--94DBA31F9D3220C6052579D485B8A416-->

## Beispiel aus der Praxis für ein binomiales Optionspreismodell

Ein vereinfachtes Beispiel eines [Binomialbaums](/binomial_tree) hat nur einen Schritt. Angenommen, es gibt eine Aktie mit einem Preis von 100 US-Dollar pro Aktie. In einem Monat wird der Preis dieser Aktie um 10 $ steigen oder um 10 $ fallen, wodurch diese Situation entsteht:

- **Aktienkurs** = 100 $

- **Aktienkurs in einem Monat (Up-State)** = 110 $

- **Aktienkurs in einem Monat (unterer Zustand)** = 90 $

Nehmen wir als Nächstes an, dass für diese Aktie eine Kaufoption verfügbar ist, die in einem Monat ausläuft und einen Ausübungspreis von 100 US-Dollar hat. Im Up-Zustand ist diese Call-Option 10 $ wert, und im Down-Zustand ist sie 0 $ wert. Das Binomialmodell kann berechnen, welchen Preis die Kaufoption heute haben sollte.

Nehmen Sie zur Vereinfachung an, dass ein Investor eine halbe Aktie kauft und eine Call-Option schreibt oder verkauft. Die Gesamtinvestition entspricht heute dem Preis einer halben Aktie abzüglich des Optionspreises, und die möglichen Auszahlungen am Monatsende sind:

- **Kosten heute** = $50 - Optionspreis

- **Portfoliowert** (Up-State) = 55 $ - max (110 $ - 100 $, 0) = 45 $

- **Portfoliowert** (Down-Status) = 45 $ - max(90 $ - 100 $, 0) = 45 $

Die Auszahlung des Portfolios ist gleich, egal wie sich der Aktienkurs bewegt. Angesichts dieses Ergebnisses und unter der Annahme, dass keine Arbitragemöglichkeiten bestehen, sollte ein Anleger im Laufe des Monats den risikofreien Zinssatz verdienen. Die heutigen Kosten müssen gleich der Abzinsung zum risikofreien Zinssatz für einen Monat sein. Die zu lösende Gleichung lautet also:

- **Optionspreis** = $50 - $45 xe ^ (-risikofreier Zinssatz x T), wobei e die mathematische Konstante 2,7183 ist.

Unter der Annahme, dass der risikofreie Zinssatz 3 % pro Jahr beträgt und T gleich 0,0833 (eins dividiert durch 12) ist, beträgt der Preis der Call-Option heute 5,11 $.

Das binomiale Optionspreismodell bietet Optionsverkäufern zwei Vorteile gegenüber dem Black-Scholes-Modell. Der erste ist seine Einfachheit, die weniger Fehler in der kommerziellen Anwendung zulässt. Der zweite ist der iterative Betrieb, der die Preise zeitnah anpasst, um die Möglichkeit für Käufer zu verringern, Arbitrage-Strategien auszuführen.

Da es beispielsweise einen Strom von Bewertungen für ein [Derivat](/derivative) für jeden Knoten in einer Zeitspanne bereitstellt, ist es nützlich für die Bewertung von Derivaten wie amerikanischen Optionen, die jederzeit zwischen dem Kaufdatum und dem Ablaufdatum ausgeführt werden können. Es ist auch viel einfacher als andere Preismodelle wie das Black-Scholes-Modell.

## Höhepunkte

- Das Modell ist intuitiv und wird in der Praxis häufiger verwendet als das bekannte Black-Scholes-Modell.

- Bei dem Modell gibt es bei jeder Iteration zwei mögliche Ergebnisse – eine Bewegung nach oben oder eine Bewegung nach unten, die einem Binomialbaum folgen.

- Das binomiale Optionspreismodell bewertet Optionen unter Verwendung eines iterativen Ansatzes, der mehrere Perioden verwendet, um amerikanische Optionen zu bewerten.

