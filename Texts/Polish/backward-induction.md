---
keywords: Economy,Economics,Behavioral Economics
title: Indukcja wsteczna
description: W teorii gier indukcja wsteczna to proces wnioskowania wstecz od końca problemu lub scenariusza w celu wywnioskowania sekwencji optymalnych działań.
---

# Indukcja wsteczna
## Co to jest indukcja wsteczna?

Indukcja wsteczna w [teorii gier](/gametheory) to iteracyjny proces wnioskowania wstecz w czasie, od końca problemu lub sytuacji, w celu rozwiązania skończonych, rozległych gier w formie i sekwencyjnych oraz wywnioskowania sekwencji optymalnych działań.

## Wyjaśnienie indukcji wstecznej

Indukcja wsteczna jest używana do rozwiązywania gier, odkąd John von Neumann i Oskar Morgenstern uznali teorię gier za przedmiot akademicki, kiedy opublikowali swoją książkę **Teoria gier i zachowania ekonomiczne** w 1944 roku.

Na każdym etapie gry indukcja wsteczna określa optymalną strategię gracza, który wykonuje ostatni ruch w grze. Następnie określa się optymalną akcję przedostatniego poruszającego się gracza, biorąc pod uwagę akcję ostatniego gracza. Ten proces jest kontynuowany wstecz, aż zostanie określona najlepsza akcja dla każdego punktu w czasie. W rzeczywistości jeden z nich określa [równowagę Nasha](/nash-equilibrium) dla każdej podgry w oryginalnej grze.

Jednak wyniki wywnioskowane z indukcji wstecznej często nie pozwalają przewidzieć rzeczywistej gry człowieka. Badania eksperymentalne wykazały, że „racjonalne” zachowanie (jak przewiduje teoria gier) rzadko występuje w prawdziwym życiu. Irracjonalni gracze mogą w rzeczywistości uzyskać wyższe wypłaty niż przewidywano przez indukcję wsteczną, jak pokazano w [grze stonogi](/centipede-game).

W grze stonogi dwóch graczy na przemian ma szansę wziąć większą część rosnącej puli pieniędzy lub przekazać pulę drugiemu graczowi. Wypłaty są ułożone w taki sposób, że jeśli pula zostanie przekazana przeciwnikowi, a przeciwnik zbierze pulę w następnej rundzie, otrzymasz nieco mniej, niż gdybyś wziął pulę w tej rundzie. Gra kończy się, gdy tylko gracz weźmie skrytkę, przy czym ten gracz otrzymuje większą część, a drugi gracz mniejszą część.

## Przykład indukcji wstecznej

Jako przykład załóżmy, że Izaz idzie pierwszy i musi zdecydować, czy powinien „wziąć” czy „przekazać” skrytkę, która obecnie wynosi 2 USD. Jeśli spasują, to Izaz i Jian dostaną po 1 dolara, ale jeśli Izaz spasuje, decyzja o przyjęciu lub spasowaniu musi być teraz podjęta przez Jiana. Jeśli Jian zgarnie, otrzyma 3$ (tj. poprzedni zapas 2$ + 1$), a Izaz otrzyma 0$. Ale jeśli Jian zda, Izaz może teraz zdecydować, czy wziąć, czy spasować, i tak dalej. Jeśli obaj gracze zawsze zdecydują się spasować, każdy z nich otrzyma na koniec gry wypłatę w wysokości 100 USD.

Sedno gry polega na tym, że jeśli Izaz i Jian współpracują ze sobą i nadal pasują do końca gry, otrzymują maksymalną wypłatę w wysokości 100 dolarów każdy. Ale jeśli nie ufają drugiemu graczowi i oczekują, że „wziął” przy pierwszej okazji, równowaga Nasha przewiduje, że gracze przyjmą najniższe możliwe roszczenie (1 USD w tym przypadku).

Równowaga Nasha w tej grze, w której żaden gracz nie ma motywacji do odstąpienia od wybranej strategii po rozważeniu wyboru przeciwnika, sugeruje, że pierwszy gracz zgarnął pulę już w pierwszej rundzie gry. Jednak w rzeczywistości robi to stosunkowo niewielu graczy. W rezultacie uzyskują wyższą wypłatę niż wypłata przewidziana w analizie równowagi.

## Rozwiązywanie gier sekwencyjnych za pomocą indukcji wstecznej

Poniżej znajduje się prosta gra sekwencyjna pomiędzy dwoma graczami. Etykiety z Graczem 1 i Graczem 2 w nich są zestawami informacji dla graczy odpowiednio jednego lub dwóch. Liczby w nawiasach na dole drzewa są wypłatami w każdym odpowiednim punkcie. Gra jest również sekwencyjna, więc Gracz 1 podejmuje pierwszą decyzję (w lewo lub w prawo), a Gracz 2 podejmuje decyzję po Graczu 1 (w górę lub w dół).

<!--360C571136D68BDF7B1BE984014B1A1C-->

Indukcja wsteczna, jak każda teoria gier, wykorzystuje założenia racjonalności i maksymalizacji, co oznacza, że gracz 2 zmaksymalizuje swoją wypłatę w każdej sytuacji. W każdym zestawie informacji mamy dwie możliwości, w sumie cztery. Eliminując wybory, których gracz 2 nie wybierze, możemy zawęzić nasze drzewo. W ten sposób oznaczymy na niebiesko linie, które maksymalizują wypłatę gracza przy danym zestawie informacji.

<!--E78C02A07C982A1B447ED0D16A9FCE40-->

Po tej redukcji, Gracz 1 może zmaksymalizować swoje wypłaty teraz, gdy wybory Gracza 2 są znane. Rezultatem jest równowaga znaleziona przez indukcję wsteczną, gdy Gracz 1 wybiera „prawo”, a Gracz 2 wybiera „w górę”. Poniżej znajduje się rozwiązanie gry z pogrubioną ścieżką równowagi.

<!--4DEC4364358F0D1CB7D219006F74D652-->

Na przykład można łatwo ustawić grę podobną do powyższej, używając firm jako graczy. Ta gra może zawierać scenariusze [wydania produktu .](/rollout) Jeśli Firma 1 chciałaby wypuścić produkt, co mogłaby zrobić Firma 2 w odpowiedzi? Czy firma 2 wyda podobny konkurencyjny produkt? Prognozując sprzedaż tego nowego produktu w różnych scenariuszach, możemy skonfigurować grę, aby przewidzieć, jak mogą się [potoczyć](/forecasting) wydarzenia. Poniżej przykład, jak można zamodelować taką grę.

<!--D102F649421403ABDBD56A5C1B29CF03-->

