---
keywords: Investing,Fundamental Analysis
title: regresja krokowa
description: Regresja krokowa polega na wyborze zmiennych niezależnych do wykorzystania w modelu w oparciu o iteracyjny proces dodawania lub usuwania zmiennych.
---

# regresja krokowa
## Co to jest regresja krokowa?

Regresja krokowa to krok po kroku iteracyjna konstrukcja modelu [regresji](/regression),. która obejmuje wybór zmiennych niezależnych do wykorzystania w ostatecznym modelu. Polega na dodawaniu lub usuwaniu kolejno potencjalnych zmiennych objaśniających i testowaniu istotności statystycznej po każdej iteracji.

Dostępność pakietów oprogramowania statystycznego umożliwia regresję krokową, nawet w modelach z setkami zmiennych.

## Rodzaje regresji krokowej

Podstawowym celem regresji krokowej jest, poprzez serię testów (np. testy F, testy [t](/t-test) ), znalezienie zestawu zmiennych niezależnych, które znacząco wpływają na zmienną zależną. Odbywa się to z komputerami poprzez iterację, która jest procesem dochodzenia do wyników lub decyzji poprzez przechodzenie przez powtarzające się rundy lub cykle analizy. Automatyczne przeprowadzanie testów za pomocą pakietów oprogramowania statystycznego ma tę zaletę, że oszczędza czas i ogranicza błędy.

Regresję krokową można osiągnąć albo przez wypróbowanie jednej zmiennej niezależnej na raz i uwzględnienie jej w modelu regresji, jeśli jest ona [istotna statystycznie](/statistically_significant),. albo przez uwzględnienie w modelu wszystkich potencjalnych zmiennych niezależnych i wyeliminowanie tych, które nie są istotne statystycznie. Niektórzy stosują kombinację obu metod i dlatego istnieją trzy podejścia do regresji krokowej:

1. **Wybór w przód** rozpoczyna się bez zmiennych w modelu, testuje każdą zmienną dodawaną do modelu, a następnie zachowuje te, które są uważane za najbardziej istotne statystycznie — powtarzając proces, aż wyniki będą optymalne.

1. **Eliminacja wsteczna** zaczyna się od zestawu niezależnych zmiennych, usuwając je pojedynczo, a następnie sprawdzając, czy usunięta zmienna jest statystycznie istotna.

1. **Dwukierunkowa eliminacja** to połączenie dwóch pierwszych metod, które sprawdzają, które zmienne należy uwzględnić lub wykluczyć.

## przykład

Przykładem regresji krokowej przy użyciu metody eliminacji wstecznej byłaby próba zrozumienia zużycia energii w fabryce przy użyciu zmiennych, takich jak czas pracy sprzętu, wiek sprzętu, wielkość personelu, temperatury na zewnątrz i pora roku. Model obejmuje wszystkie zmienne — następnie każda z nich jest usuwana pojedynczo, aby określić, która jest najmniej istotna statystycznie. Ostatecznie model może pokazać, że pora roku i temperatury mają największe znaczenie, co może sugerować, że szczytowe zużycie energii w fabryce przypada na okres największego wykorzystania klimatyzatora.

## Ograniczenia regresji krokowej

Analiza regresji, zarówno liniowa, jak i wielowymiarowa, jest obecnie szeroko stosowana w świecie ekonomii i inwestycji. Często chodzi o znalezienie wzorców, które istniały w przeszłości, a które mogą się powtórzyć w przyszłości. Na przykład prosta regresja liniowa może przyjrzeć się wskaźnikom [ceny do zysków](/price-earningsratio) i zwrotom z akcji na przestrzeni wielu lat, aby określić, czy akcje o niskim wskaźniku P/E (zmienna niezależna) oferują wyższe stopy zwrotu (zmienna zależna). Problem z tym podejściem polega na tym, że warunki rynkowe często się zmieniają, a relacje, które utrzymywały się w przeszłości, niekoniecznie są prawdziwe w teraźniejszości lub przyszłości.

Tymczasem proces regresji krokowej ma wielu krytyków, a nawet wzywa się do całkowitego zaprzestania stosowania tej metody. Statystycy zauważają kilka wad tego podejścia, w tym nieprawidłowe wyniki, nieodłączną stronniczość samego procesu oraz konieczność posiadania znacznej mocy obliczeniowej do opracowania złożonych modeli regresji poprzez iterację.

##Przegląd najważniejszych wydarzeń

- Regresja krokowa ma jednak swoje wady, ponieważ jest to podejście polegające na dopasowaniu danych do modelu w celu osiągnięcia pożądanego rezultatu.

- Metoda eliminacji wstecznej rozpoczyna się od pełnego modelu załadowanego kilkoma zmiennymi, a następnie usuwa jedną zmienną w celu przetestowania jej ważności w odniesieniu do wyników ogólnych.

- Regresja krokowa to metoda, która iteracyjnie bada istotność statystyczną każdej zmiennej niezależnej w modelu regresji liniowej.

- Podejście do selekcji w przód zaczyna się od zera i dodaje każdą nową zmienną stopniowo, testując istotność statystyczną.

