---
keywords: Investing,Cryptocurrency,Blockchain
title: Blok (blok Bitcoin)
description: Bloki to struktury danych w bazie danych, w których dane transakcji kryptowalut są trwale rejestrowane; raz napisane, nie może być zmieniane ani usuwane.
---

# Blok (blok Bitcoin)
## Co to jest blok (blok łańcucha bloków)?

Bloki to struktury danych w bazie danych blockchain, w których dane transakcyjne w blockchainie kryptowaluty są trwale rejestrowane. Blok rejestruje niektóre lub wszystkie najnowsze transakcje, które nie zostały jeszcze zatwierdzone przez sieć. Po zweryfikowaniu danych blok jest zamykany. Następnie tworzony jest nowy blok do wprowadzania i walidacji nowych transakcji.

Blok jest zatem trwałym magazynem zapisów, których po zapisaniu nie można zmienić ani usunąć.

## Jak działa blok (blok łańcucha bloków)

Sieć [blockchain](/blockchain) jest świadkiem wielu działań transakcyjnych. W przypadku stosowania w kryptowalutach prowadzenie rejestru tych transakcji pomaga systemowi śledzić, ile zostało lub nie zostało wykorzystane i które strony były zaangażowane. Transakcje dokonane w danym okresie zapisywane są w pliku zwanym blokiem, który jest podstawą sieci blockchain.

Blok przechowuje informacje. W bloku znajduje się wiele informacji, ale nie zajmuje on dużej ilości miejsca do przechowywania. Bloki zazwyczaj zawierają te elementy, ale mogą się różnić w zależności od typu:

- **Magiczny numer**: Liczba zawierająca określone wartości, które identyfikują ten blok jako część sieci określonej kryptowaluty.

- **Rozmiar bloku**: Ustawia limit rozmiaru bloku, dzięki czemu można w nim zapisać tylko określoną ilość informacji.

- **Nagłówek bloku**: Zawiera informacje o bloku.

- **Licznik transakcji**: Liczba reprezentująca liczbę transakcji przechowywanych w bloku.

- **Transakcje**: Lista wszystkich transakcji w ramach bloku.

Element transakcji jest największy, ponieważ zawiera najwięcej informacji. Po rozmiarze pamięci następuje nagłówek bloku, który zawiera następujące podelementy:

- **Wersja**: Używana wersja kryptowaluty.

- **Hash poprzedniego bloku**: Zawiera hash (zaszyfrowany numer) nagłówka poprzedniego bloku.

- **Hash Merkle root**: Hash transakcji w [drzewie Merkle](/merkle-tree) bieżącego bloku.

- **Czas**: Znacznik czasu umieszczenia bloku w łańcuchu bloków.

- **Bity**: Ocena trudności hasha docelowego, oznaczająca trudność w rozwiązaniu jednorazówki.

- **Nonce**: zaszyfrowany numer, który górnik musi rozwiązać, aby zweryfikować blok i zamknąć go.

Jedna 32-bitowa liczba w nagłówku nazywana jest jednorazową liczbą — program do wyszukiwania używa liczb losowych do „odgadnięcia” liczby jednorazowej w [hashu](/hash). Gdy jednorazowa liczba jest weryfikowana, hasz jest rozwiązywany, gdy odgadnie się jednorazową liczbę lub liczbę mniejszą od niej. Następnie sieć zamyka ten blok, generuje nowy z nagłówkiem i proces się powtarza.

do osiągnięcia konsensusu wykorzystywane są różne mechanizmy; najpopularniejszy w przypadku kryptowalut jest [dowód pracy](/proof-work) (PoW), przy czym dowód stawki (PoS) staje się coraz bardziej ze względu na mniejsze zużycie energii w porównaniu z PoW.

## Związek górnictwa z blokami

Mining to termin używany do rozwiązywania liczby, która jest jednorazową, jedyną liczbą, którą można zmienić w nagłówku bloku. Jest to również proces, z którego korzysta sieć kryptowaluty, jeśli w protokole używany jest dowód pracy.

Kopanie kryptowalut jest powszechnie uważane za złożony problem matematyczny; w rzeczywistości jest to liczba losowa generowana przez mieszanie. Haszowanie to proces szyfrowania informacji przy użyciu metody szyfrowania używanej przez kryptowalutę. Na przykład Bitcoin używa SHA256 do swojego algorytmu szyfrowania. Aby górnik mógł wygenerować „zwycięską” liczbę, program wydobywczy musi użyć SHA 256 do mieszania liczb losowych i umieszczenia ich w jednorazowych, aby sprawdzić, czy jest to dopasowanie.

> Rozwiązanie losowej liczby losowej w protokole proof-of-work pochłania tyle energii i mocy obliczeniowej. Do jego utrzymania potrzebna jest rozległa sieć górników i wystarczająca ilość energii, aby zasilić mały kraj.

>

Trudność polega na tym, że wszystkie poprzednie nagłówki bloków są szyfrowane losowo. Stąd bieżący nagłówek bloku jest losowo wygenerowaną zaszyfrowaną liczbą na podstawie losowo wygenerowanych zaszyfrowanych numerów poprzednich bloków i informacji z bieżącego bloku.

## Inne zastosowania Block i Blockchain

Ponieważ większość definicji łańcucha bloków odnosi się do Bitcoin, ponieważ była to pierwsza kryptowaluta, która z niej korzystała, wiele osób kojarzy bloki i łańcuchy bloków z Bitcoinem. Jednak inne kryptowaluty również wykorzystują bloki i łańcuchy bloków. Należy zauważyć, że sieć Ethereum ma kryptowalutę zwaną ether, która również wykorzystuje bloki i blockchain.

Jednak Ethereum i jego blockchain zostały zaprojektowane do wielu zastosowań, które wykraczają poza kryptowalutę. Na przykład za pomocą Ethereum opracowano niezamienne tokeny, inteligentne kontrakty, zdecentralizowane aplikacje finansowe i wiele innych.

##Przegląd najważniejszych wydarzeń

- Bloki i łańcuchy bloków nie są wykorzystywane wyłącznie przez kryptowaluty. Mają też wiele innych zastosowań.

- Bloki są identyfikowane za pomocą długich liczb, które zawierają zaszyfrowane informacje o transakcjach z poprzednich bloków oraz informacje o nowych transakcjach.

- Bloki i zawarte w nich informacje muszą zostać zweryfikowane przez sieć przed utworzeniem nowych bloków.

- Blok to miejsce w łańcuchu bloków, w którym informacje są przechowywane i szyfrowane.

##FAQ

### Co to jest blockchain w prostych słowach?

Blockchain to baza danych, która przechowuje i szyfruje informacje w sposób połączony, dzięki czemu poprzednie informacje nie mogą zostać zmienione, a grupa weryfikuje wszelkie wpisy przed ich sfinalizowaniem poprzez konsensus – porozumienie, że dane są poprawne.

### Do czego służą łańcuchy bloków?

Blockchainy są używane w kryptowalutach, zdecentralizowanych aplikacjach finansowych, niezamiennych tokenach, a coraz więcej zastosowań jest stale rozwijanych.

### Jak powstaje blok łańcucha bloków?

Bloki są tworzone, gdy górnicy lub walidatory bloków pomyślnie weryfikują zaszyfrowane informacje w nagłówku bloku, co powoduje utworzenie nowego bloku.

