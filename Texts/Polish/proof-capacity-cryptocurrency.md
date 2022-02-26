---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Dowód pojemności (kryptowaluta)
description: Proof of Capacity to mechanizm konsensusu, który wykorzystuje miejsce na dysku twardym węzła wydobywczego do decydowania o prawach wydobycia w sieci blockchain.
---

# Dowód pojemności (kryptowaluta)
## Co to jest dowód pojemności (PoC) dla kryptowalut?

Proof of Capacity (PoC) to algorytm [mechanizmu konsensusu](/consensus-mechanism-cryptocurrency) stosowany w blockchainach, który umożliwia [urządzeniom kopania](/bitcoin-mining) w sieci wykorzystanie dostępnego miejsca na dysku twardym do decydowania o prawach kopania i walidacji transakcji. Jest to w przeciwieństwie do wykorzystywania mocy obliczeniowej urządzenia wydobywczego (jak w algorytmie [proof of work](/proof-work) ) lub stawki górnika w kryptowalutach (jak w algorytmie [proof of stake](/proof-stake-pos) ).

## Zrozumienie dowodu pojemności

Proof of Capacity pojawił się jako jedno z wielu alternatywnych rozwiązań problemu wysokiego zużycia energii w systemach PoW (PoW) i gromadzenia kryptowalut w systemach PoS.

Dowód pojemności pozwala urządzeniom górniczym, znanym również jako węzły, w sieci [blockchain](/blockchain) wykorzystać pustą przestrzeń na dysku twardym do kopania dostępnych [kryptowalut](/cryptocurrency).

Zamiast wielokrotnie zmieniać liczby w nagłówku bloku i wielokrotnie haszować wartość rozwiązania, jak w systemie PoW, PoC przechowuje listę możliwych rozwiązań na dysku twardym urządzenia wydobywczego jeszcze przed rozpoczęciem wydobycia.

Im większy dysk twardy, im więcej możliwych wartości rozwiązań można przechowywać na dysku twardym, tym większe szanse, że górnik ma dopasować wymaganą wartość skrótu ze swojej listy, co skutkuje większą szansą na wygranie nagrody za wydobycie.

Aby wyciągnąć analogię, jeśli nagrody w loterii opierają się na dopasowaniu największej liczby liczb na zwycięskim kuponie, to gracz z dłuższą listą możliwych rozwiązań będzie miał większe szanse na wygraną. Dodatkowo gracz może wielokrotnie korzystać z numerów bloków losu.

[Burstcoin](/burstcoin) to kryptowaluta wykorzystująca system dowodu zdolności. Inne monety, które go używają, to Storj, Chia i SpaceMint.

## Jak działa PoC: kreślenie i wydobywanie

Protokół sprawdzania pojemności obejmuje dwuetapowy proces, który obejmuje kreślenie i eksplorację.

Najpierw wykreślany jest dysk twardy: lista wszystkich możliwych wartości [jednorazowych](/nonce) jest tworzona przez powtarzające się haszowanie danych, w tym konta górnika. Każdy taki numer jednorazowy zawiera 8192 hashy, które są ponumerowane od 0 do 8191. Wszystkie hashy są łączone w „miarki”, co oznacza, że sąsiednie hashy są łączone w parę. Na przykład, hash 0 i 1 stanowią scoop 0, hash 2 i 3 stanowią hash 1 i tak dalej.

Drugi krok obejmuje właściwe ćwiczenie górnicze, podczas którego górnik oblicza liczbę czerpaków. Na przykład, jeśli górnik rozpocznie działalność wydobywczą i wygeneruje miarka numer 38, górnik przejdzie następnie do miarki numer 38 jednorazowo 1 i użyje danych miarki do obliczenia wartości terminu.

Proces jest powtarzany w celu obliczenia ostatecznego terminu dla każdego zdarzenia przechowywanego na dysku twardym górnika. Po obliczeniu wszystkich terminów górnik wybiera ten z terminem minimalnym.

Termin oznacza czas w sekundach, który musi upłynąć od wykucia ostatniego bloku, zanim górnik będzie mógł wykuć nowy blok. Jeśli nikt inny nie sfałszował bloku w tym czasie, górnik może sfałszować blok i odebrać nagrodę za blok.

Na przykład, jeśli górnik X ustali minimalny termin 36 sekund i żaden inny górnik nie będzie w stanie sfałszować bloku w ciągu następnych 36 sekund, X zapewni sobie szansę na sfałszowanie następnego bloku i zostanie nagrodzony.

## Plusy i minusy dowodu pojemności

PoC ma kilka zalet w porównaniu z systemami PoW i PoS, a także kilka ważnych wad, które obejmują:

<h5><a href="">TTT</a></h5>

## Przegląd najważniejszych wydarzeń

- Główną zaletą systemu PoC jest jego wydajność w porównaniu z systemami proof-of-work (PoW) i proof-of-stake (PoS).

- Blockchainy, które działają na podstawie dowodu pojemności, obejmują Storj, Burst, Chia i SpaceMint.

- Systemy uwierzytelniania Proof of Capacity (PoC) wykorzystują wolne miejsce na dysku twardym urządzenia do przechowywania rozwiązań problemu z haszowaniem kryptowaluty.

