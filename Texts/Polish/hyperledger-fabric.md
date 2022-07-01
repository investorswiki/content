---
keywords: Investing,Cryptocurrency,Blockchain
title: Tkanina Hyperledger
description: Hyperledger Fabric to platforma do tworzenia różnych produktów, rozwiązań i aplikacji opartych na technologii blockchain do użytku biznesowego.
---

# Tkanina Hyperledger
## Co to jest tkanina Hyperledger?

Hyperledger Fabric to modułowa struktura [blockchain](/blockchain),. która działa jako podstawa do tworzenia produktów, rozwiązań i aplikacji opartych na blockchain przy użyciu komponentów typu plug-and-play, które są przeznaczone do użytku w prywatnych przedsiębiorstwach.

Hyperledger Fabric został zainicjowany przez Digital Asset i IBM i wyłonił się jako wspólne przedsięwzięcie międzybranżowe, którego gospodarzem jest obecnie Linux Foundation. Spośród kilku projektów Hyperledger, Fabric jako pierwszy wyszedł z etapu „inkubacji” i osiągnął etap „aktywny” w marcu 2017 roku.

## Jak działa tkanina Hyperledger

Tradycyjne sieci blockchain nie mogą obsługiwać transakcji prywatnych i poufnych umów, które mają ogromne znaczenie dla firm. Hyperledger Fabric został zaprojektowany w odpowiedzi na to jako modułowa, skalowalna i bezpieczna podstawa do oferowania przemysłowych rozwiązań blockchain.

Hyperledger Fabric to silnik typu open source dla blockchain, który zajmuje się najważniejszymi funkcjami oceny i wykorzystania blockchain w biznesowych przypadkach użycia.

W prywatnych sieciach przemysłowych weryfikowalna tożsamość uczestnika jest podstawowym wymogiem. Hyperledger Fabric obsługuje członkostwa na podstawie uprawnień; wszyscy uczestnicy sieci muszą mieć znane tożsamości. Wiele sektorów biznesowych, takich jak opieka zdrowotna i finanse, podlega przepisom o ochronie danych, które nakazują przechowywanie danych o różnych uczestnikach i ich odpowiedni dostęp do różnych punktów danych. Fabric obsługuje takie członkostwo oparte na uprawnieniach.

### Architektura modułowa

Modułowa architektura Hyperledger Fabric dzieli przepływ pracy przetwarzania transakcji na trzy różne etapy: [inteligentne kontrakty](/smart-contracts) zwane kodem łańcuchowym, które obejmują przetwarzanie i uzgadnianie logiki rozproszonej systemu, porządkowanie transakcji oraz weryfikację i zaangażowanie transakcji. Ta segregacja oferuje wiele korzyści:

- Zmniejszona liczba poziomów zaufania i weryfikacji, dzięki czemu sieć i przetwarzanie są wolne od bałaganu

- Poprawiona skalowalność sieci

- Lepsza ogólna wydajność

Dodatkowo, wsparcie Hyperledger Fabric dla plug-and-play różnych komponentów pozwala na łatwe ponowne wykorzystanie istniejących funkcji i gotową integrację różnych modułów. Na przykład, jeśli istnieje już funkcja, która weryfikuje tożsamość uczestnika, sieć na poziomie przedsiębiorstwa musi po prostu podłączyć i ponownie wykorzystać ten istniejący moduł, zamiast budować tę samą funkcję od podstaw.

Uczestnicy sieci pełnią trzy różne role:

- Potwierdzający

- Zatwierdzający

- Zgoda

W skrócie, propozycja transakcji jest przesyłana do partnera indosacyjnego zgodnie z wcześniej zdefiniowaną polityką indosacyjną dotyczącą wymaganej liczby indosantów. Po wystarczających indosach ze strony indosanta (-ów), partia lub blok transakcji jest dostarczany do indosatora (-ów). Zatwierdzający potwierdzają, że przestrzegano zasad zatwierdzania i że nie ma sprzecznych transakcji. Po wykonaniu obu kontroli transakcje są zapisywane w księdze.

<!--6376536357DF4ADC77E5CAB266DCF459-->

Źródło obrazu: IBM

Ponieważ tylko instrukcje potwierdzające — takie jak podpisy i zestaw do odczytu/zapisu — są przesyłane przez sieć, zwiększa się skalowalność i wydajność sieci. Dostęp do transakcji mają tylko osoby zatwierdzające i zatwierdzające, a bezpieczeństwo poprawia się, ponieważ mniejsza liczba uczestników ma dostęp do kluczowych punktów danych.

## Przykład tkaniny Hyperledger

Załóżmy, że istnieje producent, który chce wysyłać czekoladki do określonego sprzedawcy detalicznego lub na rynek detaliczny (tj. do wszystkich detalistów w USA) po określonej cenie, ale nie chce ujawniać tej ceny na innych rynkach (tj. detaliści w Chinach).

Ponieważ ruch produktu może obejmować inne strony, takie jak organy celne, firma spedycyjna i bank finansujący, prywatna cena może zostać ujawniona wszystkim zaangażowanym stronom, jeśli do obsługi tej transakcji zostanie użyta podstawowa wersja technologii blockchain.

Hyperledger Fabric rozwiązuje ten problem, zachowując prywatne transakcje w sieci jako prywatne; tylko uczestnicy, którzy muszą wiedzieć, są świadomi niezbędnych szczegółów. Partycjonowanie danych w łańcuchu bloków umożliwia dostęp do określonych punktów danych tylko stronom, które muszą o tym wiedzieć.

## Krytyka tkaniny Hyperledger

Szczytowy znak krypto-entuzjazmu załamał się w 2018 r. po załamaniu się ceny bitcoina (która osiągnęła swój szczyt 17 grudnia 2017 r.). Nadmiernie optymistyczne twierdzenia o wartości nowej technologii zostały zastąpione sceptycyzmem, a technologie powiązane, w tym Hyperledger, również ucierpiały na tym sceptycyzmie.

### Konkurenci Hyperledger Fabric

Hyperledger Fabric konkuruje z innymi projektami Hyperledger, takimi jak Iroha, Indy i Sawtooth. Konkuruje również z Cordą R3, która jest również prywatnym DLT opartym na zezwoleniach.

Firma usługowa Blockchain, Chainstack, opublikowała w styczniu 2020 r. artykuł , który pokazuje, że rozwój w Corda był historycznie wyższy niż rozwój w Fabric, chociaż rozwój Fabric przeszedł Cordę w trzecim kwartale 2019 roku, kiedy Fabric przełączył się na GitHub.

Raport Chainstack pokazuje, że podczas gdy nad Fabric pracuje trzy razy więcej programistów, programiści Cordy wnieśli ponad dwa razy więcej kodu, a programiści Fabric wrzucają znacznie mniej kodu na programistę niż programiści Cordy.

### Hyperledger Fabric nie jest blockchainem i nie jest wydajna

Kilku krytyków Hyperledger Fabric wskazuje, że oparty na uprawnieniach, prywatny blockchain z funkcjami Hyperledger Fabric nie jest blockchainem, a obecne technologie inne niż blockchain są znacznie tańsze i zapewniają taki sam poziom bezpieczeństwa. Stuart Popejoy z Cointelegraph przedstawił tę sprawę tak:

>

> Architektura Fabric jest znacznie bardziej złożona niż jakakolwiek platforma blockchain, a jednocześnie jest mniej zabezpieczona przed manipulacją i atakami. Można by pomyśleć, że „prywatny” blockchain zapewni przynajmniej skalowalność i wydajność, ale tutaj również Fabric zawodzi. Mówiąc najprościej, programy pilotażowe zbudowane na platformie Fabric będą musiały stawić czoła złożonemu i niezabezpieczonemu wdrożeniu, którego nie będzie można skalować wraz z ich działalnością .

>

Hyperledger Fabric został również skrytykowany za brak odporności. Zespół naukowców z Sorbony w Paryżu i CSIRO – Data61, australijskiej krajowej agencji naukowej, stwierdził, że znaczne opóźnienia sieci zmniejszają niezawodność Fabric: „[B]o opóźniając propagację bloków, wykazaliśmy, że Hyperledger Fabric nie zapewnia wystarczających gwarancji spójności do wdrożenia w krytycznych środowiskach ” .

## Hyperledger Fabric 2.0 wydany w styczniu 2020 r.

W styczniu 2020 r. wydano Hyperledger Fabric 2.0, aby odpowiedzieć na niektóre z istniejących zarzutów. Według Rona Millera z Techcrunch: „Największe aktualizacje obejmują wymuszenie porozumienia między stronami, zanim jakiekolwiek nowe dane zostaną dodane do księgi, co jest znane jako zdecentralizowane zarządzanie inteligentnymi kontraktami”.

Chociaż aktualizacja nie jest radykalną zmianą w prostocie lub zastosowaniu Fabric, pokazuje, że w branży kryptowalut nadal dokonuje się postęp poza kryptomania, która miała miejsce w 2018 roku. W ciągu następnych pięciu do dziesięciu lat będzie spodziewał się, że korporacyjny blockchain bez wątpienia znajdzie swoje właściwe zastosowanie.

## Przegląd najważniejszych wydarzeń

— Hyperledger to platforma księgi rozproszonej klasy korporacyjnej o otwartym kodzie źródłowym, uruchomiona przez Linux Foundation w grudniu 2015 r.

- Ponieważ Hyperledger Fabric jest prywatny i wymaga pozwolenia na dostęp, firmy mogą segregować informacje (takie jak ceny), a transakcje mogą być przyspieszane, ponieważ liczba węzłów w sieci jest zmniejszona.

- Fabric 2.0 został wydany w styczniu 2020 r. Główne cechy tej wersji to szybsze transakcje, zaktualizowana technologia inteligentnych kontraktów i usprawnione udostępnianie danych.

- Fabric to wysoce modułowa, zdecentralizowana platforma technologii księgi głównej (DLT), zaprojektowana przez IBM do użytku w przedsiębiorstwach przemysłowych.

