---
keywords: Investing,Cryptocurrency,Bitcoin
title: Dowód pracy (PoW)
description: Dowód pracy opisuje proces, który pozwala sieci bitcoin pozostać solidną, utrudniając proces wydobywania lub rejestrowania transakcji.
---

# Dowód pracy (PoW)
## Co to jest dowód pracy (PoW)?

Dowód pracy (PoW) opisuje system, który wymaga znacznego, ale wykonalnego wysiłku, aby powstrzymać niepoważne lub złośliwe wykorzystanie mocy obliczeniowej, takie jak wysyłanie wiadomości spamowych lub przeprowadzanie ataków typu „odmowa usługi”. Koncepcja została następnie dostosowana do zabezpieczania cyfrowych pieniędzy przez Hala Finneya w 2004 r. poprzez pomysł „wielokrotnego użytku dowodu pracy” przy użyciu algorytmu mieszającego SHA-256.

Po wprowadzeniu w 2009 r. Bitcoin stał się pierwszym szeroko przyjętym zastosowaniem pomysłu Finney'a PoW (Finney był także odbiorcą pierwszej transakcji bitcoinowej). [Dowód](/cryptocurrency) pracy stanowi również podstawę wielu innych [kryptowalut](/cryptocurrency),. pozwalając na bezpieczny, zdecentralizowany konsensus.

## Zrozumienie dowodu pracy

To wyjaśnienie skupi się na dowodach pracy, jak działa w sieci [bitcoin](/bitcoin). Bitcoin to cyfrowa waluta oparta na rodzaju [rozproszonej księgi rachunkowej](/distributed-ledger-technology-dlt) znanej jako „ [łańcuch bloków](/blockchain) ”. Ta księga zawiera zapis wszystkich transakcji bitcoin, ułożonych w sekwencyjne „bloki”, tak aby żaden użytkownik nie mógł dwukrotnie wydać swoich zasobów. Aby zapobiec manipulacjom, księga jest publiczna lub „rozpowszechniona”; zmieniona wersja zostałaby szybko odrzucona przez innych użytkowników.

Sposób, w jaki użytkownicy wykrywają manipulacje w praktyce, polega na użyciu [skrótów](/hash),. długich ciągów liczb, które służą jako dowód pracy. Umieść dany zestaw danych przez funkcję skrótu (bitcoin używa SHA-256) i wygeneruje tylko jeden skrót. Jednak ze względu na „efekt lawinowy”, nawet niewielka zmiana dowolnej części oryginalnych danych spowoduje całkowicie nierozpoznawalny skrót. Bez względu na rozmiar oryginalnego zestawu danych, skrót wygenerowany przez daną funkcję będzie miał taką samą długość. Skrót jest funkcją jednokierunkową: nie można go użyć do uzyskania oryginalnych danych, a jedynie do sprawdzenia, czy dane, które wygenerowały skrót, są zgodne z oryginalnymi danymi.

Generowanie dowolnego skrótu dla zestawu transakcji bitcoin byłoby trywialne dla współczesnego komputera, więc aby zamienić ten proces w „pracę”, sieć bitcoin ustala pewien poziom „trudności”. To ustawienie jest dostosowywane tak, aby nowy blok był „ [wydobywany](/bitcoin-mining) ” — dodawany do łańcucha bloków poprzez wygenerowanie prawidłowego skrótu — mniej więcej co 10 minut. Trudność w ustawianiu jest osiągana poprzez ustalenie [„celu” dla hasha](/target-hash) : im niższy cel, tym mniejszy zestaw poprawnych hashów i tym trudniej go wygenerować. W praktyce oznacza to skrót rozpoczynający się bardzo długim ciągiem zer.

> Dowód pracy został początkowo stworzony jako proponowane rozwiązanie narastającego problemu spamu.

>

## Uwagi specjalne

Skoro dany zestaw danych może wygenerować tylko jeden hash, w jaki sposób górnicy mogą upewnić się, że generują hash poniżej celu? Zmieniają dane wejściowe, dodając liczbę całkowitą, zwaną [jednorazową](/nonce) ("liczba użyta raz"). Po znalezieniu prawidłowego skrótu jest on transmitowany do sieci, a blok jest dodawany do łańcucha bloków.

Wydobycie to konkurencyjny proces, ale jest to bardziej loteria niż wyścig. Średnio co dziesięć minut ktoś będzie generował akceptowalne dowody pracy, ale kto to będzie, nie wiadomo. Górnicy łączą siły, aby zwiększyć swoje szanse na wydobycie bloków, co generuje opłaty transakcyjne i, przez ograniczony czas, nagrodę w postaci nowo utworzonych bitcoinów.

Dowód pracy sprawia, że niezwykle trudno jest zmienić jakikolwiek aspekt łańcucha bloków, ponieważ taka zmiana wymagałaby ponownego wydobycia wszystkich kolejnych bloków. Utrudnia to również użytkownikowi lub grupie użytkowników zmonopolizowanie mocy obliczeniowej sieci, ponieważ maszyny i moc wymagana do wykonania funkcji skrótu są drogie.

> Jeśli część sieci wydobywczej zaczyna akceptować alternatywny dowód pracy, nazywa się to [hard forkiem](/hard-fork).

>

## Przykład dowodu pracy

Dowód pracy wymaga, aby komputer losowo angażował się w funkcje mieszające, dopóki nie dotrze do wyjścia z prawidłową minimalną liczbą zer wiodących. Na przykład hash dla bloku #660000, wydobytego 4 grudnia 2020 r., to 000000000000000000008eddcaf078f12c69a439dde30dbb5aac3d9d94e9c18f6. Nagroda blokowa za ten udany hash wyniosła 6,25 BTC.

Ten blok będzie zawsze zawierał 745 transakcji obejmujących nieco ponad 1666 bitcoinów, a także nagłówek poprzedniego bloku. Gdyby ktoś próbował zmienić kwotę transakcji nawet o 0,000001 bitcoina, powstały hash byłby nierozpoznawalny, a sieć odrzuciłaby próbę oszustwa.

## Najczęściej zadawane pytania dotyczące dowodu pracy

### Co oznacza dowód pracy?

PoW wymaga, aby węzły w sieci dostarczyły dowodów na to, że wykorzystały moc obliczeniową (tj. pracę), aby osiągnąć konsensus w sposób zdecentralizowany i zapobiec przejęciu sieci przez złych aktorów.

### W jaki sposób dowód pracy potwierdza transakcję kryptograficzną?

Sama praca jest arbitralna. W przypadku Bitcoina obejmuje iteracje algorytmów haszujących SHA-256. Jednak „zwycięzca” rundy haszowania agreguje i zapisuje transakcje z pamięci do następnego bloku. Ponieważ „zwycięzca” jest wybierany losowo proporcjonalnie do wykonanej pracy, zachęca wszystkich w sieci do uczciwego działania i rejestrowania tylko prawdziwych transakcji.

### Dlaczego kryptowaluty potrzebują dowodu pracy?

Ponieważ są one z założenia zdecentralizowane i peer-to-peer, blockchainy, takie jak sieci kryptowalut, wymagają pewnego sposobu osiągnięcia zarówno konsensusu, jak i bezpieczeństwa. Dowód pracy jest jedną z takich metod, która sprawia, że próba przejęcia sieci jest zbyt zasobożerna. Istnieją również inne mechanizmy dowodowe, które wymagają mniej zasobów, ale mają inne wady lub wady, takie jak [dowód](/proof-stake-pos) [stawki (PoS)](/proof-stake-pos) i [dowód palenia](/proof-burn-cryptocurrency). Bez mechanizmu dowodowego sieć i przechowywane w niej dane byłyby podatne na atak lub kradzież.

### Czy Bitcoin wykorzystuje dowód pracy?

TAk. Wykorzystuje algorytm PoW oparty na funkcji haszującej SHA-256 w celu walidacji i potwierdzania transakcji oraz wprowadzania do obiegu nowych bitcoinów.

### Czym Proof of Stake (PoS) różni się od PoW?

PoS to mechanizm konsensusu, który losowo przypisuje węzeł, który będzie kopał lub weryfikował transakcje blokowe w zależności od liczby monet, które przechowuje ten węzeł. Im więcej żetonów znajduje się w portfelu, tym więcej mocy wydobywczej jest mu efektywnie przyznawane. Chociaż PoS jest znacznie mniej zasobochłonny, ma kilka innych wad, w tym większą szansę na [atak 51%](/51-attack) w mniejszych altcoinach i zachęty do gromadzenia tokenów i nieużywania ich.

## Przegląd najważniejszych wydarzeń

- Proof of Stake (POS) był jednym z kilku nowatorskich mechanizmów konsensusu stworzonych jako alternatywa dla dowodu pracy.

- Proof of work (PoW) to zdecentralizowany mechanizm konsensusu, który wymaga od członków sieci wkładania wysiłku w rozwiązanie arbitralnej matematycznej zagadki, aby uniemożliwić komukolwiek granie w system.

- Dowód pracy na dużą skalę wymaga ogromnych ilości energii, która rośnie wraz z dołączaniem do sieci większej liczby górników.

- Ze względu na dowód pracy, Bitcoin i inne transakcje kryptowalutowe mogą być przetwarzane peer-to-peer w bezpieczny sposób, bez potrzeby korzystania z zaufanej strony trzeciej.

- Dowód pracy jest szeroko stosowany w wydobywaniu kryptowalut, do walidacji transakcji i wydobywania nowych tokenów.

