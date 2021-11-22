---
keywords: Trading,Options and Derivatives Trading,Options and Derivatives
title: Dwumianowy model wyceny opcji
description: Dwumianowy model wyceny opcji to metoda wyceny opcji, która wykorzystuje procedurę iteracyjną i pozwala na określenie węzła w ustalonym okresie.
---

# Dwumianowy model wyceny opcji
## Co to jest dwumianowy model wyceny opcji?

Dwumianowy model wyceny opcji to metoda [wyceny opcji](/valuation) opracowana w 1979 roku. Dwumianowy model wyceny opcji wykorzystuje procedurę iteracyjną, pozwalającą na określenie węzłów lub punktów w czasie w przedziale czasu między datą wyceny a datą [wygaśnięcia](/expiration-date) [opcji](/expiration-date).

Model ogranicza możliwości zmian cen i eliminuje możliwość [arbitrażu](/arbitrage). Uproszczony przykład [drzewa dwumianowego](/binomial_tree) może wyglądać mniej więcej tak:

<!--87C9D3D79FF63D08201E6E848035602D-->

## Podstawy dwumianowego modelu wyceny opcji

W przypadku dwumianowych modeli cen opcji zakłada się, że możliwe są dwa wyniki — stąd dwumianowa część modelu. W przypadku modelu cenowego dwa wyniki to ruch w górę lub ruch w dół. Główną zaletą dwumianowego modelu wyceny opcji jest to, że są one matematycznie proste. Jednak modele te mogą stać się złożone w modelu wielookresowym.

W przeciwieństwie do modelu [Blacka-Scholesa](/blackscholes),. który zapewnia wynik liczbowy na podstawie danych wejściowych, model dwumianowy pozwala na obliczenie aktywa i opcji dla wielu okresów wraz z zakresem możliwych wyników dla każdego okresu (patrz poniżej).

Zaletą tego wielookresowego widoku jest to, że użytkownik może wizualizować zmianę ceny aktywów z okresu na okres i oceniać opcję na podstawie decyzji podjętych w różnych momentach. W przypadku [opcji](/americanoption) z siedzibą w USA , którą można zrealizować w dowolnym momencie przed [datą wygaśnięcia](/expirationdate),. model dwumianowy może zapewnić wgląd w to, kiedy wykonanie opcji może być wskazane, a kiedy należy ją utrzymywać przez dłuższe okresy.

Patrząc na [dwumianowe drzewo](/binomial_tree) wartości, trader może z góry określić, kiedy może nastąpić decyzja dotycząca [ćwiczenia .](/exercise) Jeśli opcja ma wartość dodatnią, istnieje możliwość wykonania, natomiast jeśli opcja ma wartość mniejszą od zera, powinna być utrzymana przez dłuższe okresy.

## Obliczanie ceny za pomocą modelu dwumianowego

Podstawową metodą obliczania dwumianowego modelu opcji jest wykorzystanie tego samego prawdopodobieństwa w każdym okresie sukcesu i niepowodzenia aż do wygaśnięcia opcji. Trader może jednak uwzględnić różne prawdopodobieństwa dla każdego okresu w oparciu o nowe informacje uzyskane w miarę upływu czasu.

Drzewo dwumianowe jest użytecznym narzędziem przy wycenie [opcji amerykańskich](/americanoption) i opcji [wbudowanych](/embeddedoption). Jego prostota jest jednocześnie jego zaletą i wadą. Drzewo jest łatwe do wymodelowania mechanicznie, ale problem tkwi w możliwych wartościach bazowego zasobu, które mogą zająć w jednym okresie czasu. W modelu drzewa dwumianowego zasób bazowy może być wart dokładnie tylko jednej z dwóch możliwych wartości, co nie jest realistyczne, ponieważ aktywa mogą być warte dowolną liczbę wartości w danym zakresie.

Na przykład może istnieć szansa 50/50, że cena aktywów bazowych może wzrosnąć lub spaść o 30 procent w jednym okresie. Jednak w drugim okresie prawdopodobieństwo wzrostu ceny aktywów bazowych może wzrosnąć do 70/30.

Na przykład, jeśli inwestor wycenia [szyb naftowy](/exploratory-well),. nie jest on pewien, jaka jest wartość tego szybu naftowego, ale istnieje szansa 50/50, że cena wzrośnie. Jeśli ceny ropy wzrosną w okresie 1, co spowoduje, że szyb naftowy stanie się bardziej wartościowy, a [fundamenty rynku](/fundamentals) wskazują teraz na ciągły wzrost cen ropy, prawdopodobieństwo dalszej aprecjacji ceny może teraz wynosić 70 procent. Model dwumianowy pozwala na tę elastyczność; model Blacka-Scholesa nie.

<!--94DBA31F9D3220C6052579D485B8A416-->

## Prawdziwy przykład dwumianowego modelu wyceny opcji

Uproszczony przykład [drzewa dwumianowego](/binomial_tree) ma tylko jeden krok. Załóżmy, że istnieje akcja, której cena wynosi 100 USD za akcję. W ciągu miesiąca cena tych akcji wzrośnie o 10 USD lub spadnie o 10 USD, tworząc taką sytuację:

- **Cena magazynowa** = $100

- **Cena magazynowa w ciągu jednego miesiąca (stan w górę)** = 110 USD

- **Cena akcji w ciągu jednego miesiąca (stan w dół)** = 90 USD

Następnie załóżmy, że dla tych akcji dostępna jest opcja kupna, która wygasa za miesiąc i ma cenę wykonania 100 USD. W stanie up ta opcja call jest warta 10 USD, a w stanie down jest warta 0 USD. Model dwumianowy może obliczyć, jaka powinna być cena opcji kupna dzisiaj.

Dla uproszczenia załóżmy, że inwestor kupuje połowę akcji i wystawia lub sprzedaje jedną opcję kupna. Całkowita inwestycja dzisiaj to cena pół akcji pomniejszona o cenę opcji, a możliwe wypłaty na koniec miesiąca to:

- **Koszt dzisiaj** = 50 USD - cena opcji

- **Wartość portfela** (stan górny) = 55 USD - maks. (110 USD - 100 USD, 0) = 45 USD

- **Wartość portfela** (stan nieaktywny) = 45 USD - maks. (90 USD - 100 USD, 0) = 45 USD

Spłata portfela jest równa bez względu na to, jak porusza się cena akcji. Biorąc pod uwagę ten wynik, zakładając brak możliwości arbitrażu, inwestor powinien w ciągu miesiąca uzyskać stopę wolną od ryzyka. Dzisiejszy koszt musi być równy spłacie zdyskontowanej według stopy wolnej od ryzyka przez jeden miesiąc. Równanie do rozwiązania to:

- **Cena opcji** = 50 USD - 45 USD xe ^ (-stawka wolna od ryzyka x T), gdzie e jest stałą matematyczną 2,7183.

Zakładając, że stopa wolna od ryzyka wynosi 3% rocznie, a T wynosi 0,0833 (jedno podzielone przez 12), wówczas cena opcji kupna dzisiaj wynosi 5,11 USD.

Dwumianowy model wyceny opcji ma dwie zalety dla sprzedających opcje w porównaniu z modelem Blacka-Scholesa. Pierwszym jest jego prostota, która pozwala na mniej błędów w aplikacji komercyjnej. Drugim jest działanie iteracyjne, które w odpowiednim czasie dostosowuje ceny, aby zmniejszyć możliwość realizacji strategii arbitrażowych przez kupujących.

Na przykład, ponieważ zapewnia strumień wycen [instrumentu pochodnego](/derivative) dla każdego węzła w określonym przedziale czasu, jest przydatny do wyceny instrumentów pochodnych, takich jak opcje amerykańskie, które można wykonać w dowolnym momencie między datą zakupu a datą wygaśnięcia. Jest również znacznie prostszy niż inne modele wyceny, takie jak model Blacka-Scholesa.

##Przegląd najważniejszych wydarzeń

- Model jest intuicyjny i stosowany w praktyce częściej niż znany model Blacka-Scholesa.

- W modelu istnieją dwa możliwe wyniki w każdej iteracji — ruch w górę lub ruch w dół, które następują po drzewie dwumianowym.

- Dwumianowy model wyceny opcji wycenia opcje przy użyciu podejścia iteracyjnego wykorzystującego wiele okresów do wyceny opcji amerykańskich.

