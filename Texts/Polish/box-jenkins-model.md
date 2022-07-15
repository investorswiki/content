---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: Model Box-Jenkins
description: Model Boxa-Jenkinsa to model matematyczny przeznaczony do prognozowania danych z określonego szeregu czasowego.
---

# Model Box-Jenkins
## Czym jest model Box-Jenkinsa?

Model Boxa-Jenkinsa to model matematyczny przeznaczony do prognozowania zakresów danych na podstawie danych wejściowych z określonego [szeregu czasowego](/timeseries). Model Boxa-Jenkinsa może analizować kilka różnych typów danych szeregów czasowych do celów prognostycznych.

Jego metodologia wykorzystuje różnice między punktami danych w celu określenia wyników. Metodologia pozwala modelowi identyfikować trendy przy użyciu autoregresji, średnich kroczących i różnicowania sezonowego w celu generowania prognoz.

[Modele autoregresywnej zintegrowanej średniej ruchomej (ARIMA)](/autoregressive-integrated-moving-average-arima) są formą modelu Boxa-Jenkinsa. Terminy ARIMA i Box-Jenkins są czasami używane zamiennie.

## Zrozumienie modelu Box-Jenkinsa

Modele Box-Jenkinsa służą do [prognozowania](/forecasting) różnych oczekiwanych punktów danych lub zakresów danych, w tym danych biznesowych i przyszłych cen zabezpieczeń.

Model Box-Jenkins został stworzony przez dwóch matematyków: George Box i Gwilym Jenkins. Obaj matematycy omówili koncepcje składające się na ten model w publikacji z 1970 roku zatytułowanej „Analiza szeregów czasowych: prognozowanie i kontrola”.

Estymacja parametrów modelu Boxa-Jenkinsa może być bardzo skomplikowana. Dlatego, podobnie jak w przypadku innych modeli regresji szeregów czasowych, najlepsze wyniki zazwyczaj uzyskuje się przy użyciu programowalnego oprogramowania. Model Boxa-Jenkinsa najlepiej nadaje się również do prognozowania krótkoterminowego trwającego 18 miesięcy lub mniej.

##Metodologia Box-Jenkinsa

Model Boxa-Jenkinsa może być jednym z kilku modeli analizy szeregów czasowych, z jakimi prognostyk spotka się podczas korzystania z zaprogramowanego oprogramowania prognostycznego. W wielu przypadkach oprogramowanie zostanie zaprogramowane tak, aby automatycznie korzystało z najlepiej dopasowanej metodologii prognozowania na podstawie prognozowanych danych [szeregów czasowych .](/timeseries) Box-Jenkins jest uważany za najlepszy wybór w przypadku zestawów danych, które są w większości stabilne i charakteryzują się niską [zmiennością](/volatility).

Model Boxa-Jenkinsa prognozuje dane przy użyciu trzech zasad: autoregresji, różnicowania i średniej ruchomej. Te trzy zasady są znane odpowiednio jako p, d i q. każda zasada jest stosowana w analizie Box-Jenkinsa; razem są one razem pokazane jako ARIMA (p, d, q).

Proces autoregresji (p) testuje dane pod kątem ich poziomu stacjonarności. Jeśli używane dane są stacjonarne, może to uprościć proces prognozowania. Jeśli używane dane są niestacjonarne, należy je rozróżnić (d). Dane są również testowane pod kątem dopasowania średniej ruchomej (co jest wykonywane w części q procesu analizy). Ogólnie rzecz biorąc, wstępna analiza danych przygotowuje je do prognozowania poprzez określenie parametrów (p, d i q), które są następnie stosowane do opracowania prognozy.

> Jednorazowy szok wpłynie w nieskończoność na kolejne wartości modelu Box-Jenkinsa w przyszłość. Dlatego w dzisiejszych modelach autoregresyjnych spuścizna kryzysu finansowego jest żywa.

>

## Autoregresyjna zintegrowana średnia ruchoma (ARIMA)

Box-Jenkins to typ autoregresyjnej zintegrowanej średniej ruchomej (ARIMA), który mierzy siłę jednej zmiennej zależnej w stosunku do innych zmiennych zmiennych. Celem modelu jest przewidywanie przyszłych ruchów papierów wartościowych lub rynków finansowych poprzez badanie różnic między wartościami w serii, a nie poprzez wartości rzeczywiste.

Model ARIMA można zrozumieć, przedstawiając każdy z jego elementów w następujący sposób:

- [Autoregresja (AR)](/autoregressive) : odnosi się do modelu, który pokazuje zmieniającą się zmienną, która ulega regresji według własnych opóźnionych lub wcześniejszych wartości.

- Zintegrowany (I): reprezentuje zróżnicowanie surowych obserwacji, aby szeregi czasowe stały się stacjonarne, tj. wartości danych są zastępowane różnicą między wartościami danych a poprzednimi wartościami.

- [Średnia ruchoma (MA)](/movingaverage) : zawiera zależność między obserwacją a błędem resztowym z modelu średniej ruchomej zastosowanego do obserwacji opóźnionych.

## Prognozowanie cen akcji

Jednym z zastosowań analizy modelu Box-Jenkinsa jest prognozowanie cen [akcji](/stock). Ta analiza jest zwykle tworzona i kodowana za pomocą oprogramowania R. Analiza wyników w wyniku logarytmicznym, który można zastosować do zbioru danych w celu wygenerowania prognozowanych cen na określony czas w przyszłości.

Modele ARIMA opierają się na założeniu, że przeszłe wartości mają pewien wpływ rezydualny na obecne lub przyszłe wartości. Na przykład inwestor korzystający z modelu ARIMA do prognozowania cen akcji zakłada, że nowi kupujący i sprzedający te akcje są pod wpływem ostatnich transakcji rynkowych przy podejmowaniu decyzji o tym, ile zaoferować lub przyjąć za papier wartościowy.

Chociaż to założenie będzie się sprawdzać w wielu różnych okolicznościach, nie zawsze jest prawdziwe. Na przykład w latach poprzedzających kryzys finansowy w 2008 r. większość inwestorów nie była świadoma zagrożeń, jakie stwarzają duże portfele [papierów wartościowych zabezpieczonych hipoteką](/mbs) (MBS) posiadane przez wiele firm finansowych.

W tamtych czasach inwestor stosujący model autoregresyjny do przewidywania wyników amerykańskich akcji finansowych miałby dobry powód, by przewidywać trwający trend stabilnych lub rosnących cen akcji w tym sektorze. Jednak, gdy do wiadomości publicznej dotarło, że wiele instytucji finansowych jest zagrożonych nieuchronnym upadkiem, inwestorzy nagle mniej przejmowali się ostatnimi cenami tych akcji, a znacznie bardziej ich ekspozycją na ryzyko bazowe.

W związku z tym rynek szybko przeszacowuje akcje finansowe do znacznie niższego poziomu, co całkowicie pomieszałoby model autoregresyjny.

##Przegląd najważniejszych wydarzeń

- Modele autoregresywnej zintegrowanej średniej ruchomej (ARIMA) są formą modelu Box-Jenkinsa.

- Model Boxa-Jenkinsa najlepiej nadaje się do prognozowania w ramach czasowych 18 miesięcy lub krótszych.

- Metodologia opiera się na założeniu, że przeszłe wydarzenia wpływają na przyszłe.

- Model Boxa-Jenkinsa to metodologia prognozowania wykorzystująca badania regresji na danych szeregów czasowych.

