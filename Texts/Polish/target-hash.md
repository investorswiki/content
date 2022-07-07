---
keywords: Investing,Cryptocurrency,Altcoins
title: Docelowy hasz
description: Docelowy hash określa trudność w wydobywaniu kryptowaluty za pomocą systemu blockchain typu proof-of-work (PoW).
---

# Docelowy hasz
## Co to jest skrót docelowy?

W wydobywaniu kryptowalut, hash docelowy to wartość liczbowa, której [nagłówek haszowanego bloku](/block-header-cryptocurrency) musi być mniejszy lub równy, aby nowy blok został przyznany górnikowi. Nagłówki bloków identyfikują poszczególne bloki w łańcuchu bloków.

Kopanie kryptowalut odnosi się do procesu gromadzenia kryptowalut jako nagrody za wykonaną pracę. Istotą tej pracy jest weryfikacja legalności transakcji danej kryptowaluty. W ten sposób górnicy kryptowalut są zasadniczo audytorami. Kiedy wydobywasz, możesz zarabiać kryptowalutę bez konieczności odkładania na nią pieniędzy.

Skrót docelowy jest używany do określania trudności danych wejściowych i można go dostosować w celu zapewnienia wydajnego przetwarzania bloków. Na przykład, docelowe skróty są używane w kryptowalutach, które wykorzystują system proof-of-work (PoW) do ustawiania bieżącego [trudnego](/difficulty-cryptocurrencies) [y](/difficulty-cryptocurrencies) (w tym kopanie bitcoinów). Jeśli kryptowaluta używa do kopania innego systemu, może nie wymagać hasha docelowego.

## Jak działa skrót docelowy

[Kryptowaluty](/cryptocurrency) opierają się na wykorzystaniu łańcuchów [bloków](/blockchain),. które zawierają historię wszystkich transakcji tej kryptowaluty. Transakcje te są [haszowane](/hash) lub szyfrowane kryptograficznie w ciągu znaków alfanumerycznych. Haszowanie polega na pobraniu ciągu danych o dowolnej długości i przepuszczeniu go przez algorytm w celu uzyskania danych wyjściowych o stałej długości. Dane wyjściowe będą zawsze tej samej długości, niezależnie od tego, jak duże lub małe są dane wejściowe (chociaż liczba permutacji skrótu jest astronomicznie duża). Każdy blok będzie zawierał skrót poprzedniego nagłówka bloku.

Walidacja i kodowanie łańcucha bloków jest określane jako [wydobywanie](/bitcoin-mining). Wydobycie obejmuje wykorzystanie komputerów do uruchamiania algorytmów mieszających w celu przetworzenia najnowszego bloku; informacje, które użytkownik potrzebuje do wydobycia, znajdują się w nagłówku bloku. Sieć kryptowalut ustala wartość docelową tego skrótu — zwaną hashem docelowym — a górnicy próbują określić, jaka jest ta wartość, testując wszystkie możliwe wartości.

Nagłówek bloku zawiera numer wersji bloku, znacznik czasu, skrót użyty w poprzednim bloku, skrót [Merkle Root](/merkle-root-cryptocurrency) [,](/merkle-root-cryptocurrency) nonce [i](/nonce) docelowy hash. Blok jest generowany przez wzięcie skrótu zawartości bloku, dodanie losowego ciągu liczb (jednorazowych) i ponowne zahaszowanie bloku.

Jeśli hash spełnia wymagania celu, blok jest dodawany do łańcucha bloków. Przechodzenie przez rozwiązania w celu odgadnięcia jednorazowości jest określane mianem [dowodu pracy](/proof-work) (PoW), a górnik, który jest w stanie znaleźć wartość, jest nagradzany blokiem i opłacany w kryptowalucie.

## Uwagi specjalne

### Docelowy hash dla Bitcoina

Bitcoin wykorzystuje algorytm skrótu SHA-256. Algorytm ten generuje weryfikowalne liczby losowe w sposób, który wymaga przewidywalnej mocy obliczeniowej komputera.

Wydobycie bloku wymaga od górnika wytworzenia wartości (jednorazowej), która po zahaszowaniu (zakodowaniu kryptograficznym) jest mniejsza lub równa wartości użytej w ostatnim bloku akceptowanym przez sieć bitcoin. Ta liczba mieści się w zakresie od 0 (najmniejsza opcja) do 256 bitów (największa opcja), ale jest mało prawdopodobne, aby kiedykolwiek była liczbą maksymalną.

Ponieważ docelowy skrót może być ogromną liczbą, górnik może być zmuszony do przetestowania dużej liczby wartości, zanim odniesie sukces. Górnik, któremu nie powiodło się, musi czekać na kolejny blok (dlatego górnicy, którzy znajdą rozwiązanie haszujące, są porównywani do zwycięzców wyścigu lub loterii).

Skrót docelowy jest okresowo dostosowywany. Funkcje skrótu używane do generowania nowego celu mają określone właściwości zaprojektowane w celu zabezpieczenia łańcucha bloków (i jego kryptowaluty). Ten proces jest deterministyczny, co oznacza, że przy każdym użyciu tych samych danych wejściowych da ten sam wynik. Jest wystarczająco szybki, aby zwrócenie skrótu danych wejściowych nie trwało zbyt długo. Sprawia to również, że określanie danych wejściowych jest bardzo trudne, szczególnie w przypadku dużych liczb, i powoduje, że niewielkie zmiany danych wejściowych powodują bardzo różne wyniki mieszania.

##Przegląd najważniejszych wydarzeń

- Hasze docelowe są używane w kryptowalutach, które wykorzystują system proof-of-work (PoW) do ustawienia aktualnej trudności wydobycia (w tym Bitcoin); jeśli kryptowaluta używa do kopania innego systemu, może nie wymagać hasha docelowego.

- W wydobywaniu kryptowalut, hash docelowy to wartość liczbowa, której zaszyfrowany nagłówek bloku (używany do identyfikacji poszczególnych bloków w łańcuchu bloków) musi być mniejszy lub równy, aby nowy blok został przyznany górnikowi.

- Sieć Bitcoin dostosowuje trudność wydobycia, podnosząc lub obniżając docelowy hash, aby zachować średni 10-minutowy odstęp między nowymi blokami.

