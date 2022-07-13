---
keywords: Trading,Technical Analysis
title: Dystrybucja T
description: Rozkład AT jest rodzajem funkcji prawdopodobieństwa, która jest odpowiednia do szacowania parametrów populacji dla małych rozmiarów próbek lub nieznanych wariancji.
---

# Dystrybucja T
## Co to jest dystrybucja T?

Rozkład T, znany również jako rozkład t Studenta, jest rodzajem [rozkładu prawdopodobieństwa](/probabilitydistribution),. który jest podobny do rozkładu normalnego o kształcie dzwonu, ale ma ciężkie ogony. Rozkłady T mają większą szansę na wartości ekstremalne niż rozkłady normalne, stąd grubsze ogony.

## Co mówi ci dystrybucja T?

Ciężkość ogona jest określana przez parametr rozkładu T zwany [stopniami swobody](/degrees-of-freedom),. przy czym mniejsze wartości dają cięższe ogony, a przy wyższych wartościach sprawia, że rozkład T przypomina standardowy rozkład normalny ze średnią 0, a odchylenie standardowe z 1. Rozkład T jest również znany jako „Rozkład T Studenta”.

<!--7D50237348822D30DFF69E0C32EC0A76-->

Gdy próbka n obserwacji jest pobierana z populacji o rozkładzie normalnym o średniej M i odchyleniu standardowym D, średnia próbki m i odchylenie standardowe próbki d będą różnić się od M i D ze względu na losowość próby.

Z-score można obliczyć z odchyleniem standardowym populacji jako Z = (x – M)/D, a ta wartość ma rozkład normalny ze średnią 0 i odchyleniem standardowym 1. Ale przy użyciu szacowanego odchylenia standardowego, wynik t oblicza się jako T = (m – M)/{d/sqrt(n)}, różnica między d i D sprawia, że rozkład jest rozkładem T z (n - 1) stopniami swobody, a nie rozkładem normalnym ze średnią 0 i odchylenie standardowe 1.

## Przykład korzystania z T-Dystrybucji

Poniższy przykład pokazuje, w jaki sposób rozkłady t są wykorzystywane w analizie statystycznej. Po pierwsze, pamiętaj, że przedział ufności dla średniej to zakres wartości obliczonych na podstawie danych, mających na celu uchwycenie średniej „populacji”. Ten przedział to m +- t*d/sqrt(n), gdzie t jest wartością krytyczną z rozkładu T.

Na przykład 95% przedział ufności dla średniego zwrotu Dow Jones Industrial Average w ciągu 27 dni handlowych przed 11.09.2001 wynosi -0,33%, (+/- 2,055) * 1,07 / sqrt(27), dając (trwały) średni zwrot jako pewną liczbę między -0,75% a +0,09%. Liczba 2,055, czyli ilość błędów standardowych do skorygowania, znajduje się w rozkładzie T.

Ponieważ rozkład T ma grubsze ogony niż rozkład normalny, można go wykorzystać jako model dla zwrotów finansowych wykazujących nadmierną kurtozę, co pozwoli na bardziej realistyczne obliczenie wartości zagrożonej ( [VaR](/var) ) w takich przypadkach.

## Różnica między rozkładem T a rozkładem normalnym

Rozkłady normalne są używane, gdy zakłada się, że rozkład populacji jest normalny. Rozkład T jest podobny do rozkładu normalnego, tylko z grubszymi ogonami. Oba zakładają populację o rozkładzie normalnym. Rozkłady T mają wyższą kurtozę niż rozkłady normalne. Prawdopodobieństwo uzyskania wartości bardzo odległych od średniej jest większe przy rozkładzie T niż przy rozkładzie normalnym.

## Ograniczenia korzystania z dystrybucji T

Rozkład T może pochylić dokładność w stosunku do rozkładu normalnego. Jego wada pojawia się tylko wtedy, gdy istnieje potrzeba idealnej normalności. Rozkład T powinien być stosowany tylko wtedy, gdy nie jest znane odchylenie standardowe populacji. Jeśli znane jest odchylenie standardowe populacji, a wielkość próby jest wystarczająco duża, w celu uzyskania lepszych wyników należy zastosować rozkład normalny.

##Przegląd najważniejszych wydarzeń

- Rozkład T jest ciągłym rozkładem prawdopodobieństwa z-score, gdy szacowane odchylenie standardowe jest używane w mianowniku, a nie prawdziwe odchylenie standardowe.

- Rozkład T, podobnie jak rozkład normalny, ma kształt dzwonu i jest symetryczny, ale ma ciężkie ogony, co oznacza, że ma tendencję do generowania wartości znacznie odbiegających od średniej.

- Testy T są używane w statystyce do oszacowania istotności.

