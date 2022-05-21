---
keywords: Business,Corporate Finance and Accounting,Financial Analysis
title: Dopasowanie
description: Nadmierne dopasowanie to błąd modelowania, który występuje, gdy funkcja jest zbyt ściśle dopasowana do ograniczonego zestawu punktów danych.
---

# Dopasowanie
## Co to jest nadmierne dopasowanie?

Nadmierne dopasowanie to błąd modelowania w statystykach, który występuje, gdy funkcja jest zbyt ściśle dopasowana do ograniczonego zestawu punktów danych. W rezultacie model jest użyteczny tylko w odniesieniu do początkowego zbioru danych, a nie do jakichkolwiek innych zbiorów danych.

Nadmierne dopasowanie modelu na ogół przybiera formę nadmiernie złożonego modelu w celu wyjaśnienia specyfiki w badanych danych. W rzeczywistości często badane dane zawierają pewien stopień błędu lub przypadkowy szum. Tak więc próba dostosowania modelu do nieco niedokładnych danych może spowodować jego zainfekowanie znacznymi błędami i zmniejszenie jego mocy predykcyjnej.

## Zrozumienie nadmiernego dopasowania

Na przykład powszechnym problemem jest używanie [algorytmów komputerowych](/algorithm) do przeszukiwania obszernych baz danych historycznych danych rynkowych w celu znalezienia wzorców. Biorąc pod uwagę wystarczającą ilość badań, często możliwe jest opracowanie skomplikowanych twierdzeń, które wydają się przewidywać zwroty na [giełdzie](/stockmarket) z dużą dokładnością.

Jednak w przypadku zastosowania do danych poza próbą takie twierdzenia mogą prawdopodobnie okazać się jedynie nadmiernym dopasowaniem modelu do tego, co w rzeczywistości było przypadkowymi zdarzeniami. We wszystkich przypadkach ważne jest, aby przetestować model z danymi, które znajdują się poza próbą użytą do jego opracowania.

## Jak zapobiegać nadmiernemu dopasowaniu

Sposoby zapobiegania nadmiernemu dopasowaniu obejmują weryfikację krzyżową, w której dane używane do uczenia modelu są cięte na fałdy lub partycje, a model jest uruchamiany dla każdego fałdu. Następnie uśrednia się ogólny szacunek błędu. Inne metody obejmują tworzenie zestawów: predykcje są łączone z co najmniej dwóch oddzielnych modeli, powiększanie danych, w którym dostępny zestaw danych jest zróżnicowany, oraz upraszczanie danych, w którym model jest uproszczony, aby uniknąć nadmiernego dopasowania.

> Specjaliści ds. finansów muszą być zawsze świadomi niebezpieczeństw związanych z przesadnym lub niedostatecznym dopasowaniem modelu opartego na ograniczonych danych. Idealny model powinien być zrównoważony.

>

## Nadmiar w uczeniu maszynowym

Overfitting jest również czynnikiem w uczeniu maszynowym. Może się pojawić, gdy komputer został nauczony skanowania w poszukiwaniu określonych danych w jedną stronę, ale gdy ten sam proces zostanie zastosowany do nowego zestawu danych, wyniki są nieprawidłowe. Wynika to z błędów w zbudowanym modelu, ponieważ prawdopodobnie wykazuje on niską stronniczość i dużą wariancję. Model mógł mieć nadmiarowe lub nakładające się funkcje, przez co stał się niepotrzebnie skomplikowany, a przez to nieskuteczny.

## Nadmiar a Niedopasowanie

Przesadnie dopasowany model może być zbyt skomplikowany, przez co nieskuteczny. Ale model może być również niedostatecznie dopasowany, co oznacza, że jest zbyt prosty, ze zbyt małą liczbą funkcji i zbyt małą ilością danych, aby zbudować skuteczny model. Model overfit ma niską stronniczość i wysoką wariancję, podczas gdy model niedopasowany jest odwrotnie — ma wysokie stronniczość i niską wariancję. Dodanie większej liczby funkcji do zbyt prostego modelu może pomóc ograniczyć stronniczość.

## Przykład nadmiernego dopasowania

Na przykład uniwersytet, w którym wskaźnik porzucania college'u jest wyższy niż oczekiwany, postanawia stworzyć model do przewidywania prawdopodobieństwa, że kandydat przejdzie przez całą drogę do ukończenia studiów.

Aby to zrobić, uniwersytet szkoli model z zestawu danych 5000 kandydatów i ich wyników. Następnie uruchamia model na oryginalnym zbiorze danych — grupie 5000 kandydatów — a model przewiduje wynik z 98% dokładnością. Ale aby przetestować jego dokładność, uruchomili również model na drugim zbiorze danych — o 5000 więcej kandydatów. Jednak tym razem model jest dokładny tylko w 50%, ponieważ model był zbyt ściśle dopasowany do wąskiego podzbioru danych, w tym przypadku pierwszych 5000 aplikacji.

##Przegląd najważniejszych wydarzeń

- Overfitting to błąd, który występuje w modelowaniu danych w wyniku zbyt bliskiego dopasowania określonej funkcji do minimalnego zestawu punktów danych.

- Kiedy model został skompromitowany przez overfitting, model może stracić swoją wartość jako narzędzie predykcyjne do inwestowania.

- Model danych może być również niedostatecznie dopasowany, co oznacza, że jest zbyt prosty, ze zbyt małą liczbą punktów danych, aby był skuteczny.

- Specjaliści finansowi są narażeni na ryzyko przesadnego dopasowania modelu opartego na ograniczonych danych i uzyskania błędnych wyników.

- Nadmierne dopasowanie jest częstszym problemem niż niedopasowanie i zwykle pojawia się w wyniku próby uniknięcia nadmiernego dopasowania.

