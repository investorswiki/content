---
keywords: Crypto
title: Blok kandydacki
description: Blok Kandydatów. Tymczasowy blok utworzony przez węzeł wydobywczy (górnika), który zostanie dodany do łańcucha bloków, aby otrzymać nagrody za blok.
---

# Blok kandydacki
Krótko mówiąc, blok kandydujący to blok, który węzeł wydobywczy (górnik) próbuje wydobyć, aby otrzymać nagrodę za blok. Tak więc blok kandydujący może być opisany jako blok tymczasowy, który zostanie zweryfikowany lub odrzucony przez sieć. Górnicy konkurują ze sobą, aby zweryfikować kolejny blok i dodać go do łańcucha bloków, ale najpierw muszą stworzyć blok kandydujący, aby wziąć udział w konkursie górniczym.

Bloki kandydatów są tworzone przez górników poprzez zbieranie i organizowanie wielu niepotwierdzonych transakcji z puli pamięci. Transakcje są następnie haszowane, aby utworzyć strukturę [drzewa Merkle](/merkle-tree),. która ostatecznie wytworzy korzeń Merkle (lub hash root). Korzeń Merkle to pojedynczy skrót, który reprezentuje wszystkie poprzednie skróty tego drzewa, a zatem wszystkie transakcje, które zostały uwzględnione w tym konkretnym bloku.

Skrót główny - razem z hashem poprzedniego bloku i losową liczbą zwaną [nonce](/nonce) - jest następnie umieszczany w nagłówku bloku. Nagłówek bloku jest następnie haszowany przez górnika, generując dane wyjściowe na podstawie tych komponentów (hasz root, hash poprzedniego bloku i nonce) oraz kilka innych elementów. Wynikowy wynik to skrót bloku i będzie służył jako unikalny identyfikator nowo wygenerowanego bloku (bloku kandydata).

Aby zostać uznanym za ważny, wyjście (hash bloku) musi zaczynać się od pewnej liczby zer (mniej niż wartość docelowa zdefiniowana przez protokół). Oznacza to, że proces wydobycia opiera się na wielu próbach (próbach i błędach), ponieważ węzły wydobywcze muszą wykonać mnóstwo funkcji haszujących z różnymi wartościami jednorazowymi, aż w końcu zostanie wygenerowany prawidłowy hash bloku. Wytworzony hasz blokowy jest tym, co dowodzi, że górnik wykonał swoją pracę (stąd Proof of Work).

Gdy górnik znajdzie prawidłowy hash bloku, jego kandydujący blok zostanie rozesłany do pozostałych węzłów sieci, co zweryfikuje autentyczność hasha. Jeśli wszystko jest w porządku, blok kandydujący zostanie zapisany w łańcuchu bloków. W tym momencie każdy węzeł weryfikujący aktualizuje swoją kopię danych blockchain, aby odzwierciedlić ostatnio wydobyty blok, a górnik otrzyma nagrodę za blok.

