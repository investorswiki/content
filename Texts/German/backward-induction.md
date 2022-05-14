---
keywords: Economy,Economics,Behavioral Economics
title: Rückwirkende Induktion
description: In der Spieltheorie ist die Rückwärtsinduktion der Vorgang, bei dem vom Ende eines Problems oder Szenarios rückwärts auf eine Abfolge optimaler Aktionen geschlossen wird.
---

# Rückwirkende Induktion
## Was ist Rückwärtsinduktion?

Rückwärtsinduktion in [der Spieltheorie](/gametheory) ist ein iterativer Prozess des zeitlichen Rückwärtsdenkens vom Ende eines Problems oder einer Situation, um endlich umfangreiche Form- und sequentielle Spiele zu lösen und eine Abfolge optimaler Aktionen abzuleiten.

## Rückwärtsinduktion erklärt

Die Rückwärtsinduktion wird zur Lösung von Spielen verwendet, seit John von Neumann und Oskar Morgenstern die Spieltheorie als akademisches Fach etablierten, als sie 1944 ihr Buch **Theory of Games and Economic Behavior** veröffentlichten.

In jeder Phase des Spiels bestimmt die Rückwärtsinduktion die optimale Strategie des Spielers, der den letzten Zug im Spiel macht. Dann wird die optimale Aktion des vorletzten sich bewegenden Spielers bestimmt, wobei die Aktion des letzten Spielers als gegeben angenommen wird. Dieser Prozess wird rückwärts fortgesetzt, bis die beste Aktion für jeden Zeitpunkt bestimmt wurde. Tatsächlich bestimmt man das [Nash-Gleichgewicht](/nash-equilibrium) jedes Teilspiels des ursprünglichen Spiels.

Die aus der Rückwärtsinduktion abgeleiteten Ergebnisse können jedoch häufig das tatsächliche menschliche Spiel nicht vorhersagen. Experimentelle Studien haben gezeigt, dass „rationales“ Verhalten (wie von der Spieltheorie vorhergesagt) im wirklichen Leben selten gezeigt wird. Irrationale Spieler können am Ende tatsächlich höhere Auszahlungen erhalten, als durch Rückwärtsinduktion vorhergesagt, wie im [Tausendfüßlerspiel veranschaulicht](/centipede-game).

Beim Tausendfüßlerspiel haben zwei Spieler abwechselnd die Chance, einen größeren Anteil an einem wachsenden Geldtopf zu nehmen oder den Topf an den anderen Spieler weiterzugeben. Die Auszahlungen sind so angeordnet, dass man, wenn der Pot an seinen Gegner weitergegeben wird und der Gegner den Pot in der nächsten Runde nimmt, etwas weniger erhält, als wenn man den Pot in dieser Runde genommen hätte. Das Spiel endet, sobald ein Spieler den Vorrat nimmt, wobei dieser Spieler den größeren Teil und der andere Spieler den kleineren Teil erhält.

## Beispiel für Rückwärtsinduktion

Nehmen wir zum Beispiel an, Izaz geht zuerst und muss entscheiden, ob er den Vorrat, der sich derzeit auf 2 $ beläuft, „nehmen“ oder „weitergeben“ soll. Wenn sie nehmen, dann bekommen Izaz und Jian jeweils 1 $, aber wenn Izaz passt, muss Jian die Entscheidung treffen, ob sie nehmen oder passen. Wenn Jian nimmt, bekommt er 3 $ (dh den vorherigen Vorrat von 2 $ + 1 $) und Izaz bekommt 0 $. Aber wenn Jian passt, muss Izaz jetzt entscheiden, ob er nimmt oder passt und so weiter. Wenn beide Spieler immer passen, erhalten sie am Ende des Spiels jeweils eine Auszahlung von 100 $.

Der Punkt des Spiels ist, wenn Izaz und Jian beide kooperieren und bis zum Ende des Spiels passen, erhalten sie die maximale Auszahlung von jeweils 100 $. Aber wenn sie dem anderen Spieler misstrauen und erwarten, dass er bei der ersten Gelegenheit „nimmt“, sagt das Nash-Gleichgewicht voraus, dass die Spieler den geringstmöglichen Anspruch erheben werden (in diesem Fall 1 $).

Das Nash-Gleichgewicht dieses Spiels, bei dem kein Spieler einen Anreiz hat, von seiner gewählten Strategie abzuweichen, nachdem er die Wahl eines Gegners berücksichtigt hat, legt nahe, dass der erste Spieler den Pot in der allerersten Runde des Spiels gewinnen würde. In Wirklichkeit tun dies jedoch relativ wenige Spieler. Als Ergebnis erhalten sie eine höhere Auszahlung als die von der Gleichgewichtsanalyse vorhergesagte Auszahlung.

## Sequentielle Spiele mit Rückwärtsinduktion lösen

Unten ist ein einfaches sequentielles Spiel zwischen zwei Spielern. Die Bezeichnungen mit Spieler 1 und Spieler 2 darin sind die Informationssätze für Spieler eins bzw. zwei. Die Zahlen in den Klammern am Ende des Baums sind die Auszahlungen an jedem jeweiligen Punkt. Das Spiel ist auch sequentiell, also trifft Spieler 1 die erste Entscheidung (links oder rechts) und Spieler 2 trifft seine Entscheidung nach Spieler 1 (oben oder unten).

<!--360C571136D68BDF7B1BE984014B1A1C-->

Die Rückwärtsinduktion verwendet, wie alle Spieltheorien, die Annahmen von Rationalität und Maximierung, was bedeutet, dass Spieler 2 seine Auszahlung in jeder gegebenen Situation maximieren wird. Bei jedem Informationssatz haben wir zwei Möglichkeiten, insgesamt vier. Indem wir die Auswahlmöglichkeiten eliminieren, die Spieler 2 nicht wählen wird, können wir unseren Baum eingrenzen. Auf diese Weise markieren wir die Linien blau, die die Auszahlung des Spielers bei den gegebenen Informationen maximieren.

<!--E78C02A07C982A1B447ED0D16A9FCE40-->

Nach dieser Reduzierung kann Spieler 1 seine Auszahlungen jetzt maximieren, da die Entscheidungen von Spieler 2 bekannt sind. Das Ergebnis ist ein Gleichgewicht, das durch Rückwärtsinduktion gefunden wird, indem Spieler 1 „rechts“ wählt und Spieler 2 „oben“ wählt. Unten ist die Lösung des Spiels mit dem fettgedruckten Gleichgewichtspfad.

<!--4DEC4364358F0D1CB7D219006F74D652-->

Beispielsweise könnte man leicht ein ähnliches Spiel wie das obige erstellen, indem man Unternehmen als Spieler verwendet. Dieses Spiel könnte [Produktveröffentlichungsszenarien beinhalten](/rollout). Was könnte Unternehmen 2 tun, wenn Unternehmen 1 ein Produkt veröffentlichen möchte? Wird Unternehmen 2 ein ähnliches Konkurrenzprodukt herausbringen? Indem wir den Verkauf dieses neuen Produkts in verschiedenen Szenarien [prognostizieren](/forecasting),. können wir ein Spiel aufstellen, um vorherzusagen, wie sich die Ereignisse entwickeln könnten. Unten ist ein Beispiel dafür, wie man ein solches Spiel modellieren könnte.

<!--D102F649421403ABDBD56A5C1B29CF03-->

