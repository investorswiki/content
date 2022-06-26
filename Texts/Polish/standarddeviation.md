---
keywords: Business,Corporate Finance and Accounting,Financial Ratios
title: Obliczanie odchylenia standardowego
description: Co to jest odchylenie standardowe? Odchylenie standardowe to metryka, która mierzy zmienność zwrotów z papieru wartościowego w czasie. Może być używany do pomiaru zmienności
---

# Obliczanie odchylenia standardowego
## Co to jest odchylenie standardowe?

Odchylenie standardowe to metryka, która mierzy zmienność zwrotów [z papieru wartościowego w](/security) czasie. Może być używany do pomiaru [zmienności](/volatility) na podstawie wyników w przeszłości i porównywania przyszłych zwrotów z poprzednimi. Odchylenie standardowe może również określać ilościowo rozkład zwrotów poszczególnych portfeli i może być stosowane do różnych rodzajów aktywów, w tym [obligacji](/bond),. towarów i kryptowalut. Ten artykuł skupia się jednak na akcjach.

Odchylenie standardowe pokazuje, jak daleko jest zwrot z akcji od jego średniego zwrotu w danym okresie, a także może określić, czy zwrot za dany okres jest wartością odstającą. Przydatne jest zastosowanie w okresach zmienności ceny akcji spółki giełdowej, ponieważ duże wahania w górę i w dół w krótkim okresie mogą pomóc w ustaleniu ryzyka inwestycyjnego w stosunku do zysku.

## Jak obliczyć odchylenie standardowe za pomocą arkusza kalkulacyjnego (przykład: Apple)

Zrozumienie odchylenia standardowego oznacza najpierw zrozumienie wariancji, ponieważ odchylenie standardowe, z matematycznego punktu widzenia, jest pierwiastkiem kwadratowym z wariancji. Wariancja pokazuje, jak daleko każdy zwrot jest od średniej lub średniej zestawu danych zwrotu.

Liczba większa niż 0 wskazuje, że zwroty w zestawie są odległe od średniej i daleko od siebie, podczas gdy liczba znacznie większa niż 0 sugeruje, że są znacznie dalej od średniej. Ponieważ wariancja danych jest podnoszona do kwadratu, odchylenie standardowe przywraca dane do tej samej jednostki miary (w przypadku zasobów, procent), wyciągając pierwiastek kwadratowy.

**Uwaga**: Odchylenie standardowe jest reprezentowane we wzorach przez σ, grecką małą literę oznaczającą sigma.

Najskuteczniejszym sposobem obliczenia odchylenia standardowego, zwłaszcza w przypadku dużego zestawu danych, takich jak dzienne ceny akcji, jest arkusz kalkulacyjny. Poniżej znajduje się przykład obliczenia odchylenia standardowego stóp zwrotu z akcji Apple w okresie trzech miesięcy.

**Krok 1**: Zbierz dzienne dane z okresu trzech miesięcy. Odpowiada to mniej więcej około 20 dniom w miesiącu, a pierwszy dzień służy jako cena bazowa przy obliczaniu pierwszej zmiany procentowej. Oblicz dzienną zmianę procentową akcji Apple i wyrażaj dane w procentach. **Uwaga**: formuła jest wyświetlana w komórce oraz w polu w lewym górnym rogu arkusza kalkulacyjnego. Cena zamknięcia akcji Apple (wyrażona w dolarach amerykańskich) uwzględnia korekty, w tym podziały, dywidendy i/lub dystrybucję zysków kapitałowych.

**Krok 2**: Oblicz średnią zwrotów za pomocą funkcji ŚREDNIA.

**Krok 3**: oblicz wariancję zwrotów za pomocą funkcji WARIANCJA.

**Krok 4**: oblicz odchylenie standardowe zwrotów za pomocą funkcji ODCH.STANDARDOWE. **Uwaga**: Średnia i odchylenie standardowe są wyrażone w procentach, natomiast wariancja jest liczbą dziesiętną.

## Jak interpretować odchylenie standardowe

W powyższym przykładzie dla Apple dane pokazują, że średni zwrot za okres trzech miesięcy wyniósł 0,08 procent. Wariancja pokazuje odległość zakresu liczb od średniej. Ale odchylenie standardowe pokazuje dokładnie, jak daleko są zwroty od średniej. Przy odchyleniu standardowym na poziomie 1,91 procent sugeruje to, że zakres wynosi plus-minus 1,91 punktu procentowego od średniej, co oznacza, że zwroty Apple zwykle wahają się od -1,83 procent do 1,99 procent.

### Odchylenie standardowe jako prawdopodobieństwo w rozkładzie normalnym

Odchylenie standardowe można najlepiej zilustrować za pomocą wzorca rozkładu normalnego dla prawdopodobieństwa, który daje statystyczny obraz tego, gdzie może znajdować się odchylenie standardowe. W rozkładzie normalnym większość scenariuszy prawdopodobieństwa ma tendencję do występowania bliżej średniej. Rzadsze przypadki mają tendencję do występowania na zewnątrz, w kierunku obszarów, które spłaszczają się jako ogony.

Na poniższym wykresie rozkład normalny ma kształt dzwonu, stąd jego przydomek krzywa dzwonowa, przy czym środek krzywej reprezentuje średnią. Liczby wymienione poziomo pod wykresem są znane jako z-scores, które mieszczą się w zakresie od -3 do 3. Są to punkty odchylenia standardowego i są wyrażane inaczej niż formuła odchylenia standardowego, która jest wyrażona w procentach.

Obliczenie rozkładu normalnego może dostarczyć prawdopodobieństwa, według jakich parametrów mogą być potencjalne zwroty. Powiedzmy, że daytrader prognozuje, że akcje Apple'a zwiększą się o 5 procent dzień po zgłoszeniu rekordowych zarobków i przychodów za ostatni raportowany kwartał. Jakie jest prawdopodobieństwo, że następnego dnia akcje przyniosą 5-procentowy zwrot?

Formuła kodu z może pokazać, gdzie byłby zwrot na wykresie rozkładu normalnego.

Podłączając przewidywany zwrot Apple, średnią i odchylenie standardowe zaczerpnięte z powyższego arkusza kalkulacyjnego:

> (5% - 0,08%) / 1,91% = 2,57 Odchylenie standardowe powyżej średniej.

Potencjalny 5-procentowy zwrot z akcji Apple wyniósłby 2,57 odchylenia standardowego powyżej średniej, co stanowiłoby od 2 do 3 odchyleń standardowych od średniej. Statystycznie oznacza to 2,28-procentowe prawdopodobieństwo osiągnięcia przewidywanego 5-procentowego zwrotu. Prawdopodobieństwo 2,28 procent uzyskuje się przez odjęcie 95,44 procent od 100 procent, a następnie różnicę (4,56 procent) dzieli się przez dwa ze względu na równe wartości prawdopodobieństwa po każdej stronie (ujemnej i dodatniej) linii symetrycznej na wykresie rozkładu normalnego . W każdym razie 5-procentowy dzienny zysk na akcjach Apple nie byłby powszechny.

Innym sposobem interpretacji rozkładu normalnego jest stwierdzenie, że prawdopodobieństwo zwrotu Apple (w przedziale od -1,83 procent do 1,99 procent) mieszczącego się w przedziale od -1 do 1 odchylenia standardowego od średniej wynosi 68,26 procent. Prawdopodobieństwo odchylenia standardowego między -2 a 2 wynosi 95,44 procent, a między -3 a 3 99,74 procent.

## Jak odchylenie standardowe ma się do zmienności?

Odchylenie standardowe może pokazać, jak zwrot odnosi się do średniej. Wysokie odchylenie standardowe wskazywałoby na dużą zmienność, a zwrot większy niż zakres odchylenia standardowego sugeruje, że jest to wartość odstająca. Seria wahań w górę iw dół poza tym zakresem przez pewien okres również wskazywałaby na dużą zmienność.

## Przegląd najważniejszych wydarzeń

- Jest obliczany jako pierwiastek kwadratowy z wariancji.

- Odchylenie standardowe w finansach jest często używane jako miara względnego ryzyka aktywów.

- Odchylenie standardowe mierzy rozproszenie zbioru danych w stosunku do jego średniej.

- Zmienne akcje mają wysokie odchylenie standardowe, podczas gdy odchylenie stabilnych akcji blue chipów jest zwykle raczej niskie.

- Wadą jest to, że odchylenie standardowe oblicza całą niepewność jako ryzyko, nawet jeśli jest to korzystne dla inwestora – np. ponadprzeciętne stopy zwrotu.

## FAQ

### Co oznacza wysokie odchylenie standardowe?

Duże odchylenie standardowe wskazuje na dużą zmienność obserwowanych danych wokół średniej. Wskazuje to, że zaobserwowane dane są dość rozproszone. Małe lub niskie odchylenie standardowe wskazywałoby zamiast tego, że większość obserwowanych danych jest ściśle skupiona wokół średniej.

### Dlaczego odchylenie standardowe jest ważne?

Odchylenie standardowe jest ważne, ponieważ może pomóc użytkownikom w ocenie ryzyka. Rozważ opcję inwestycyjną ze średnim rocznym zwrotem 10% rocznie. Jednak ta średnia została wyprowadzona z ostatnich trzech lat zwrotów 50%, -15% i -5%. Obliczając odchylenie standardowe i rozumiejąc swoje niskie prawdopodobieństwo faktycznego uzyskania średniej 10% w danym roku, jesteś lepiej uzbrojony do podejmowania świadomych decyzji i rozpoznawania ryzyka.

### Co mówi Ci odchylenie standardowe?

Odchylenie standardowe opisuje, jak rozproszony jest zbiór danych. Porównuje każdy punkt danych ze średnią wszystkich punktów danych, a odchylenie standardowe zwraca obliczoną wartość, która opisuje, czy punkty danych znajdują się blisko siebie, czy są rozłożone. W rozkładzie normalnym odchylenie standardowe mówi, jak daleko wartości są od średniej.

### Jak obliczyć odchylenie standardowe?

Odchylenie standardowe jest obliczane jako pierwiastek kwadratowy z wariancji. Alternatywnie, oblicza się ją, znajdując średnią zestawu danych, znajdując różnicę każdego punktu danych do średniej, podnosząc różnice do kwadratu, dodając je do siebie, dzieląc przez liczbę punktów w zestawie danych minus 1 i znajdując kwadrat źródło.

### Jak szybko znaleźć odchylenie standardowe?

Jeśli spojrzysz na rozkład niektórych zaobserwowanych danych wizualnie, możesz zobaczyć, czy kształt jest stosunkowo chudy w porównaniu z grubym. Rozkłady grubsze mają większe odchylenia standardowe. Alternatywnie Excel ma wbudowane funkcje odchylenia standardowego w zależności od zestawu danych.

