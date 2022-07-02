---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: Zintegrowana autoregresyjna średnia krocząca (ARIMA)
description: Autoregresywna zintegrowana średnia ruchoma (ARIMA) to model analizy statystycznej, który wykorzystuje dane szeregów czasowych do prognozowania przyszłych trendów.
---

# Zintegrowana autoregresyjna średnia krocząca (ARIMA)
## Co to jest autoregresyjna zintegrowana średnia krocząca (ARIMA)?

Autoregresywna zintegrowana średnia ruchoma (ARIMA) to model analizy statystycznej, który wykorzystuje [dane szeregów czasowych](/timeseries) do lepszego zrozumienia zestawu danych lub przewidywania przyszłych trendów.

Model statystyczny jest autoregresyjny, jeśli przewiduje przyszłe wartości na podstawie wartości przeszłych. Na przykład model ARIMA może przewidywać przyszłe ceny akcji na podstawie ich przeszłych wyników lub prognozować zarobki firmy na podstawie poprzednich okresów.

## Zrozumienie autoregresyjnej zintegrowanej średniej ruchomej (ARIMA)

Autoregresywny zintegrowany model średniej ruchomej jest formą [analizy regresji,](/regression) która mierzy siłę jednej zmiennej zależnej w stosunku do innych zmiennych zmieniających się. Celem modelu jest przewidywanie przyszłych ruchów papierów wartościowych lub rynków finansowych poprzez badanie różnic między wartościami w serii, a nie poprzez wartości rzeczywiste.

Model ARIMA można zrozumieć, przedstawiając każdy z jego elementów w następujący sposób:

- [Autoregresja (AR)](/autoregressive) : odnosi się do modelu, który pokazuje zmieniającą się zmienną, która ulega regresji według własnych opóźnionych lub wcześniejszych wartości.

- **Zintegrowany (I):** reprezentuje zróżnicowanie surowych obserwacji, aby szeregi czasowe stały się stacjonarne (tj. wartości danych są zastępowane różnicą między wartościami danych a poprzednimi wartościami).

- [Średnia ruchoma (MA)](/movingaverage) : zawiera zależność między obserwacją a błędem resztowym z modelu średniej ruchomej zastosowanego do obserwacji opóźnionych.

## Parametry ARIMA

Każdy składnik w ARIMA funkcjonuje jako parametr ze standardową notacją. W przypadku modeli ARIMA standardową notacją będzie ARIMA z p, d i q, gdzie wartości całkowite zastępują parametry, aby wskazać typ zastosowanego modelu ARIMA. Parametry można zdefiniować jako:

- **p**: liczba obserwacji opóźnień w modelu; znany również jako kolejność opóźnień.

- **d**: ile razy surowe obserwacje są różnicowane; znany również jako stopień zróżnicowania.

- q: rozmiar okna średniej ruchomej; znany również jako rząd średniej ruchomej.

Na przykład w modelu [regresji liniowej uwzględniana jest liczba i rodzaj terminów.](/nonlinear-regression) Wartość 0, która może być użyta jako parametr, oznaczałaby, że dany składnik nie powinien być używany w modelu. W ten sposób model ARIMA może być skonstruowany do pełnienia funkcji modelu ARMA, a nawet prostych modeli AR, I lub MA.

> Ponieważ modele ARIMA są skomplikowane i działają najlepiej na bardzo dużych zbiorach danych, do ich obliczania wykorzystywane są algorytmy komputerowe i techniki uczenia maszynowego.

>

## Autoregresywna zintegrowana średnia ruchoma (ARIMA) i stacjonarność

W autoregresyjnym zintegrowanym modelu średniej ruchomej dane są różnicowane w celu uczynienia go stacjonarnym. Model, który pokazuje stacjonarność, to taki, który pokazuje, że dane są niezmienne w czasie. Większość danych ekonomicznych i rynkowych pokazuje trendy, więc celem różnicowania jest usunięcie wszelkich trendów lub struktur sezonowych.

[Sezonowość](/seasonality) lub gdy dane wykazują regularne i przewidywalne wzorce, które powtarzają się w ciągu roku kalendarzowego, może negatywnie wpłynąć na model regresji. Jeśli pojawia się trend, a stacjonarność nie jest widoczna, wielu obliczeń w całym procesie nie można wykonać z dużą skutecznością.

> Jednorazowy szok wpłynie w nieskończoność na kolejne wartości modelu ARIMA w przyszłości. Dlatego w dzisiejszych modelach autoregresyjnych spuścizna kryzysu finansowego jest żywa.

>

## Uwagi specjalne

Modele ARIMA opierają się na założeniu, że przeszłe wartości mają pewien wpływ rezydualny na obecne lub przyszłe wartości. Na przykład inwestor korzystający z modelu ARIMA do prognozowania cen akcji zakłada, że nowi kupujący i sprzedający te akcje są pod wpływem ostatnich transakcji rynkowych przy podejmowaniu decyzji o tym, ile zaoferować lub przyjąć za papier wartościowy.

Chociaż to założenie będzie się sprawdzać w wielu okolicznościach, nie zawsze tak jest. Na przykład w latach poprzedzających kryzys finansowy w 2008 r. większość inwestorów nie była świadoma zagrożeń, jakie stwarzają duże portfele [papierów wartościowych zabezpieczonych hipoteką](/mbs) (MBS) posiadane przez wiele firm finansowych.

W tamtych czasach inwestor stosujący model autoregresyjny do przewidywania wyników amerykańskich akcji finansowych miałby dobry powód, by przewidywać trwający trend stabilnych lub rosnących cen akcji w tym sektorze. Jednak, gdy do wiadomości publicznej dotarło, że wiele instytucji finansowych jest zagrożonych nieuchronnym upadkiem, inwestorzy nagle mniej przejmowali się ostatnimi cenami tych akcji, a znacznie bardziej ich ekspozycją na ryzyko bazowe. W związku z tym rynek szybko przeszacowuje akcje finansowe do znacznie niższego poziomu, co całkowicie pomieszałoby model autoregresyjny.

## Często Zadawane Pytania

### Do czego służy ARIMA?

ARIMA to metoda prognozowania lub przewidywania przyszłych wyników na podstawie historycznych szeregów czasowych. Opiera się na statystycznej koncepcji korelacji szeregowej, w której przeszłe punkty danych wpływają na przyszłe punkty danych.

### Jakie są różnice między modelami autoregresji i średniej ruchomej?

ARIMA łączy cechy autoregresji z cechami średnich ruchomych. Na przykład proces autoregresyjny AR(1) to taki, w którym bieżąca wartość jest oparta na bezpośrednio poprzedzającej wartości, podczas gdy proces AR(2) to taki, w którym bieżąca wartość jest oparta na dwóch poprzednich wartościach. Średnia ruchoma to obliczenie używane do analizy punktów danych poprzez tworzenie serii średnich różnych podzbiorów pełnego zestawu danych w celu wygładzenia wpływu wartości odstających. W wyniku tej kombinacji technik modele ARIMA mogą uwzględniać trendy, cykle, sezonowość i inne niestatyczne typy danych podczas tworzenia prognoz.

### Jak działa prognozowanie ARIMA?

Prognozowanie ARIMA jest osiągane przez wprowadzenie danych szeregów czasowych dla zmiennej będącej przedmiotem zainteresowania. Oprogramowanie statystyczne zidentyfikuje odpowiednią liczbę opóźnień lub wielkość różnicowania, które należy zastosować do danych i sprawdzi stacjonarność. Następnie wyświetli wyniki, które często są interpretowane podobnie do modelu regresji liniowej wielokrotnej.

##Przegląd najważniejszych wydarzeń

- Modele autoregresyjnej zintegrowanej średniej ruchomej (ARIMA) przewidują przyszłe wartości na podstawie wartości przeszłych.

- ARIMA wykorzystuje opóźnione średnie kroczące do wygładzania danych szeregów czasowych.

- Są szeroko stosowane w analizie technicznej do prognozowania przyszłych cen papierów wartościowych.

- Modele autoregresyjne zakładają domyślnie, że przyszłość będzie przypominać przeszłość.

- Dlatego mogą okazać się niedokładne w pewnych warunkach rynkowych, takich jak kryzysy finansowe czy okresy szybkich zmian technologicznych.

