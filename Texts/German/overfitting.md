---
keywords: Business,Corporate Finance and Accounting,Financial Analysis
title: Überanpassung
description: Überanpassung ist ein Modellierungsfehler, der auftritt, wenn eine Funktion zu genau an eine begrenzte Menge von Datenpunkten angepasst ist.
---

# Überanpassung
## Was ist Overfitting?

Überanpassung ist ein Modellierungsfehler in der Statistik, der auftritt, wenn eine Funktion zu eng an einer begrenzten Menge von Datenpunkten ausgerichtet ist. Infolgedessen ist das Modell nur in Bezug auf seinen ursprünglichen Datensatz und nicht auf andere Datensätze nützlich.

Eine Überanpassung des Modells nimmt im Allgemeinen die Form an, ein übermäßig komplexes Modell zu erstellen, um Eigenheiten in den untersuchten Daten zu erklären. In Wirklichkeit enthalten die oft untersuchten Daten ein gewisses Maß an Fehlern oder zufälligem Rauschen. Daher kann der Versuch, das Modell zu genau an leicht ungenaue Daten anzupassen, das Modell mit erheblichen Fehlern infizieren und seine Vorhersagekraft verringern.

## Overfitting verstehen

Ein häufiges Problem ist beispielsweise die Verwendung von Computeralgorithmen [,](/algorithm) um umfangreiche Datenbanken mit historischen Marktdaten zu durchsuchen, um Muster zu finden. Bei ausreichendem Studium ist es oft möglich, ausgefeilte Theoreme zu entwickeln, die die Renditen am [Aktienmarkt](/stockmarket) mit großer Genauigkeit vorherzusagen scheinen .

Wenn sie jedoch auf Daten außerhalb der Stichprobe angewendet werden, können sich solche Theoreme wahrscheinlich als bloße Überanpassung eines Modells an etwas erweisen, das in Wirklichkeit nur zufällige Ereignisse waren. In allen Fällen ist es wichtig, ein Modell mit Daten zu testen, die außerhalb der Stichprobe liegen, die zu seiner Entwicklung verwendet wurde.

## Wie man Überanpassung verhindert

Zu den Möglichkeiten, eine Überanpassung zu verhindern, gehört die Kreuzvalidierung, bei der die zum Trainieren des Modells verwendeten Daten in Falten oder Partitionen zerlegt werden und das Modell für jede Falte ausgeführt wird. Dann wird die Gesamtfehlerschätzung gemittelt. Andere Methoden umfassen Ensembling: Vorhersagen werden aus mindestens zwei separaten Modellen kombiniert, Datenerweiterung, bei der der verfügbare Datensatz so gestaltet wird, dass er vielfältig aussieht, und Datenvereinfachung, bei der das Modell gestrafft wird, um eine Überanpassung zu vermeiden.

> Finanzfachleute müssen sich immer der Gefahren einer Über- oder Unteranpassung eines Modells auf der Grundlage begrenzter Daten bewusst sein. Das ideale Modell sollte ausgewogen sein.

>

## Overfitting beim maschinellen Lernen

Overfitting ist auch ein Faktor beim maschinellen Lernen. Es kann vorkommen, dass einer Maschine beigebracht wurde, auf eine Weise nach bestimmten Daten zu scannen, aber wenn derselbe Prozess auf einen neuen Datensatz angewendet wird, sind die Ergebnisse falsch. Dies ist auf Fehler im erstellten Modell zurückzuführen, da es wahrscheinlich eine geringe Verzerrung und eine hohe Varianz aufweist. Das Modell hatte möglicherweise redundante oder sich überschneidende Merkmale, was dazu führte, dass es unnötig kompliziert und daher unwirksam wurde.

## Überanpassung vs. Unteranpassung

Ein überangepasstes Modell kann zu kompliziert sein, wodurch es unwirksam wird. Aber ein Modell kann auch unzureichend angepasst sein, d. h. es ist zu einfach, mit zu wenigen Funktionen und zu wenig Daten, um ein effektives Modell zu erstellen. Ein Overfit-Modell hat eine niedrige Verzerrung und eine hohe Varianz, während ein Underfit-Modell das Gegenteil ist – es hat eine hohe Verzerrung und eine niedrige Varianz. Das Hinzufügen weiterer Funktionen zu einem zu einfachen Modell kann dazu beitragen, Verzerrungen zu begrenzen.

## Beispiel für Überanpassung

Beispielsweise entscheidet sich eine Universität, deren Studienabbrecherquote höher ist als gewünscht, dafür, ein Modell zu erstellen, um die Wahrscheinlichkeit vorherzusagen, dass ein Bewerber es bis zum Abschluss schaffen wird.

Dazu trainiert die Universität ein Modell aus einem Datensatz von 5.000 Bewerbern und deren Ergebnissen. Anschließend wird das Modell auf dem ursprünglichen Datensatz – der Gruppe von 5.000 Bewerbern – ausgeführt, und das Modell sagt das Ergebnis mit einer Genauigkeit von 98 % voraus. Aber um seine Genauigkeit zu testen, führen sie das Modell auch mit einem zweiten Datensatz aus – 5.000 weitere Bewerber. Dieses Mal ist das Modell jedoch nur zu 50 % genau, da das Modell zu eng an eine enge Datenuntergruppe angepasst war, in diesem Fall an die ersten 5.000 Anwendungen.

## Höhepunkte

- Überanpassung ist ein Fehler, der bei der Datenmodellierung auftritt, wenn eine bestimmte Funktion zu eng an einem minimalen Satz von Datenpunkten ausgerichtet ist.

- Wenn ein Modell durch Überanpassung kompromittiert wurde, kann das Modell seinen Wert als Vorhersageinstrument für Investitionen verlieren.

- Ein Datenmodell kann auch unzureichend angepasst sein, was bedeutet, dass es zu einfach ist und zu wenige Datenpunkte enthält, um effektiv zu sein.

- Finanzfachleute laufen Gefahr, ein Modell auf der Grundlage begrenzter Daten zu überanpassen und am Ende fehlerhafte Ergebnisse zu erhalten.

- Overfitting ist ein häufigeres Problem als Underfitting und tritt typischerweise auf, wenn versucht wird, Overfitting zu vermeiden.

