---
keywords: Investing,Cryptocurrency,Blockchain
title: Konsensus hashgrafowy
description: Konsensus Hashgraph działa inaczej niż bardziej znane mechanizmy konsensusu blockchain. Dowiedz się więcej o tym i jak to działa.
---

# Konsensus hashgrafowy
## Co to jest konsensus Hashgraph?

Konsensus Hashgraph jest alternatywą lub następną generacją technologii stojącej za mechanizmami konsensusu blockchain. Zamiast wykorzystywać moc obliczeniową dużych sieci do weryfikacji transakcji, transakcje są rejestrowane i potwierdzane za pomocą protokołu wykorzystującego komunikację węzłową.

Hashgraph jest zdecentralizowaną księgą, podobnie jak blockchain. Przechowuje informacje, zabezpiecza je kryptografią, ogranicza dostęp i wykorzystuje przechowywane dane do weryfikacji. Jednak sieć hashgrafowa osiąga konsensus w znacznie inny sposób niż blockchain.

Konsensus hashgrafowy osiąga się za pomocą pojęć zwanych „plotkami”, „plotkami o plotkach” i wirtualnym głosowaniem. Projektanci systemu informują, że rozwiązuje on problemy nieodłącznie związane z [algorytmami](/algorithm) budowania konsensusu , takimi jak [dowód pracy](/proof-work) (PoW), pod względem większej szybkości i wyższej wydajności.

> Konsensus hashgrafowy — plotki, plotki na temat plotek i wirtualne głosowanie — to mechanizm, który wykorzystuje księga rozproszona Hedera do walidacji i potwierdzania transakcji.

>

## Zrozumienie konsensusu Hashgraph

Hashgraph jest alternatywą dla blockchain. Podobnie jak blockchain przechowuje dane i je szyfruje. Dla informacji o transakcji generowany jest skrót, a nowe transakcje lub dane są dodawane i budowane na ich podstawie. Jednak blockchain to księga składająca się z bloków danych. Każdy blok jest połączony z poprzednim blokiem za pomocą swoich danych, weryfikowanych przez sieć walidatorów w celu utworzenia następnego bloku. Ten proces tworzy jeden łańcuch. Hashgraph to nie jeden łańcuch — wszystkie informacje są przechowywane w zaszyfrowanej księdze, a w procesie walidacji uczestniczy każdy użytkownik, a nie tylko walidatory.

Na przykład Alicja tworzy transakcję z Bobem i wszystkie informacje, które zna, są mu przekazywane. Bob następnie dokonuje transakcji z Kris. Wszystkie informacje, które Bob przekazuje Krisowi. Kris dokonuje transakcji z Elim i wszystko, co wie, zostaje przeniesione. Trwa to w całej sieci, a łańcuch zasadniczo plotkuje o zachodzących wydarzeniach. Każdy węzeł wie to, co wiedzą wszystkie inne węzły, więc nie ma potrzeby walidacji obliczeniowej.

W miarę rozprzestrzeniania się plotek od użytkownika do użytkownika, sieć wykorzystuje algorytmy i automatyzację, aby zapewnić, że stan księgi hashgrafowej jest aktualizowany i to samo.

### Plotki

Informacje o danych nazywane są „plotkami”. Struktura danych zawarta w transakcji to:

- Znacznik czasu

- Więcej transakcji lub zer

- Dwa skróty z kontenerów nadrzędnych

- Zaszyfrowany podpis.

Dwa skróty to ostatnie zdarzenia z dwóch węzłów synchronizacji, które porównują swoje informacje. Węzły nieustannie tworzą zdarzenia i synchronizują się.

> Hashgraph — księga — jest bardziej wydajny niż blockchain, ponieważ nie marnuje się energii na bloki, które nie są akceptowane. Wszystkie informacje są przechowywane w hashgrafie.

>

### Plotki o plotkach

Informacje o danych transakcyjnych nazywane są „plotkami o plotkach”. Informacje są synchronizowane w sieci hashgraph za pomocą zdarzenia zwanego „synchronizacją plotek”. Synchronizacja plotek to wspólna historia „wydarzeń plotkarskich” w hashgrafie. W ten sposób dane nie mogą być zmieniane ani manipulowane i istnieje konsensus.

### Wirtualne Głosowanie

Głosowanie wirtualne ma miejsce, gdy węzły porównują zdarzenia i osiągają konsensus za pomocą algorytmu głosowania. Oto jak to działa — transakcja jest przypisywana znacznikiem czasu, gdy węzeł ją otrzymuje. Gdy przechodzi do innych węzłów w sieci, jest mu przypisywany znacznik czasu, który jest medianą wszystkich znaczników czasu dla tej transakcji odebranych przez węzły w sieci. Mediana działa w wyniku głosowania. Stwarza to bardziej sprawiedliwy system transakcji niż blockchain, ponieważ decyduje sieć, a nie jeden węzeł.

### Tolerancja błędów

Podobnie jak w przypadku większości rozproszonych rejestrów i blockchain, zawsze istnieje szansa, że uczestnik sieci nie jest uczciwy. Mogą występować opóźnienia w komunikacji lub opóźnienia sieci, które powodują, że węzły nie komunikują się prawidłowo.

Mechanizmy konsensusu są zaprojektowane tak, aby radzić sobie z tymi błędami poprzez ustalenie kryteriów tolerancji błędów. Deweloperzy muszą wziąć pod uwagę i uwzględnić złych aktorów, złe połączenia, opóźnienia w sieci i inne problemy z siecią. Konsensus Hashgraph może tolerować złośliwe działanie jednej trzeciej sieci. Podobno jest asynchroniczna, bizantyjska odporna na awarie — najwyższy poziom bezpieczeństwa — co oznacza, że uczciwe węzły w sieci nadal działają, nawet jeśli występują źli aktorzy.

## Czym różni się Hashgraph od Blockchain?

Hashgraph to struktura danych, która przechowuje zapisy tego, kto komu powiedział i w jakiej kolejności. Jest to wspólna historia plotek, w których uczestnicy dodają i dzielą się informacjami, co weryfikuje transakcje znacznie szybciej niż blockchain.

Blockchain dodaje informacje o poprzednich transakcjach do nowych informacji o transakcji i szyfruje je. Do weryfikacji transakcji między stronami potrzebna jest strona trzecia. Hashgraph nie potrzebuje tego powolnego procesu ze względu na protokół plotkowania.

> Konsensus Hashgraph jest znacznie szybszy niż mechanizmy konsensusu blockchain, ze średnim czasem potwierdzenia transakcji w sekundach, a nie minutach.

>

Bitcoin i wiele innych kryptowalut ma problemy z synchronizacją wiadomości. Jednak asynchroniczna bizantyjska tolerancja błędów hashgraph pokonuje problem synchronizacji wiadomości, zakładając, że zagubione lub opóźnione wiadomości ostatecznie dotrą do swoich miejsc docelowych.

Na przykład, jeśli dwie transakcje występują jednocześnie, sieć blockchain wybiera kolejność transakcji. W niektórych łańcuchach blokowych opłaty transakcyjne traktują priorytetowo potwierdzenie. Inne sieci mogą zdecydować, która transakcja zostanie potwierdzona na podstawie liczby postawionych tokenów przez weryfikatora. W tych łańcuchach blokowych jeden węzeł wpływa na wynik.

Konsensus Hashgraph eliminuje wpływ, jaki jeden węzeł lub grupa węzłów może mieć na transakcje. Ponieważ każda transakcja ma znacznik czasu, a każda transakcja jest przekazywana do całej sieci, problemy z czasem transakcji są rozwiązywane.

## Przegląd najważniejszych wydarzeń

- System rozproszonej księgi hashgraph nie został szeroko przyjęty przez społeczność kryptograficzną.

- Konsensus Hashgraph wykorzystuje informacje o informacjach, a nie samą treść, aby stworzyć konsensus.

- Podstawowe informacje w hashgrafie nazywane są „plotkami”, a informacje drugorzędne to „plotki o plotkach”.

## FAQ

### Jak działa konsensus Hashgraph?

Konsensus Hashgraph działa przy użyciu znaczników czasu konsensusu i „plotek”, w których każdy węzeł komunikuje wszystko, co wie, losowym węzłom w „zdarzeniach plotek”.

### Co to jest konsensus Hashgraph?

Konsensus Hashgraph to mechanizm używany w rozproszonej księdze hashgraph do walidacji transakcji.

### Czy Hashgraph zastąpi Blockchain?

Hashgraph ma być – i sprzedawany jako – ulepszenie technologii blockchain, ale czy go zastąpi, dopiero się okaże. Nie cieszy się jeszcze tak dużym zainteresowaniem i przyjęciem przez programistów, jak technologia blockchain.

