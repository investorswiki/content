---
keywords: Crypto
title: Filtr Blooma
description: Filtr Blooma. Struktura danych, która może być wykorzystana do poinformowania użytkownika, czy dana pozycja jest częścią zestawu pozycji
---

# Filtr Blooma
Filtr Bloom to struktura danych, której można użyć do poinformowania użytkownika, czy dana pozycja jest częścią zestawu. Chociaż nie może powiedzieć z całą pewnością, czy element jest w zestawie, może z całą pewnością stwierdzić, czy element nie jest.

Stworzone przez Burtona Howarda Blooma w 1970 roku filtry Blooma stanowią atrakcyjną ofertę dla szeregu zastosowań ze względu na ich wydajność w wykorzystaniu przestrzeni. W niektórych kryptowalutach (w szczególności Bitcoin) odgrywają one integralną rolę w Uproszczonej Weryfikacji Płatności lub SPV.

Korzystając z klienta SPV, użytkownicy mogą wchodzić w interakcje z siecią Bitcoin bez uruchamiania pełnego węzła. Pełne węzły mają określone wymagania dotyczące pamięci i obliczeń, które sprawiają, że są niewygodne w działaniu na urządzeniach o niskim poborze mocy, takich jak smartfony. Z drugiej strony klienci SPV po prostu wysyłają zapytania do pełnych węzłów w celu uzyskania informacji dotyczących portfela (portfeli) użytkownika.

Najprostszym rozwiązaniem przekazywania tych danych użytkownikowi byłoby uświadomienie wszystkim węzłom kluczy klienta, tak aby przesyłane były do nich tylko istotne transakcje. Ewidentnie jest to rozwiązanie kiepskie, ponieważ prywatność klienta zostałaby poświęcona. Z drugiej strony pobieranie wszystkich transakcji tylko w celu odrzucenia większości z nich byłoby marnowaniem przepustowości. Wprowadź filtry Bloom.

Zilustrujmy. Załóżmy, że klient, Alice, ma transakcję o wysokiej wartości, o której nie chce, aby Bob, który uruchamia pełny węzeł, był świadomy. Konstruuje filtr Bloom, który zilustrujemy jako siatkę 10x1:

Przekazuje interesujące ją dane transakcji przez dwie różne funkcje haszujące, które wyprowadzają dwie liczby od 0 do 9. Nazwijmy je 4 i 7. Wysyła filtr do Boba.

Patrząc na tę siatkę, nie masz pojęcia, jakie dane Alicja przekazała do filtra. Gdybyś miał zestaw, w którym były zawarte dane, mógłbyś je zahaszować i porównać z filtrem – jeśli jest dopasowanie, istnieje możliwość, że była to informacja, o którą prosiła Alicja.

W tym samym czasie prawdopodobnie będzie wiele danych wejściowych, które będą mapowane na 4 i 7, więc Bob nie może określić, jaką częścią danych interesuje się Alicja. Po prostu zwraca wszystkie dopasowania, a Alice filtruje je na swoim końcu.

Jest to oczywiście rażące uproszczenie, ale demonstruje koncepcję: filtry Bloom zaciemniają prawdziwe interesy klienta. Nie jest to idealna metoda (nadal istnieją obawy o jej prywatność), ale jest ulepszeniem w stosunku do nieekranowanego żądania do węzła.

