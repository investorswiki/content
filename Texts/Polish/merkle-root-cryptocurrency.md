---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Korzeń Merkle (kryptowaluta)
description: Korzeń Merkle zawiera informacje o każdej pojedynczej transakcji, która kiedykolwiek znajdowała się w określonym bloku w łańcuchu bloków.
---

# Korzeń Merkle (kryptowaluta)
## Co to jest korzeń Merkle?

Korzeń Merkle to [skrót](/hash) wszystkich skrótów wszystkich transakcji, które są częścią bloku w sieci [blockchain](/blockchain).

## Zrozumienie korzenia Merkle

Blockchain składa się z różnych bloków, które są ze sobą powiązane (stąd nazwa blockchain). Drzewo hash, czyli [drzewo Merkle](/merkle-tree),. koduje dane blockchain w wydajny i bezpieczny sposób. Umożliwia szybką weryfikację danych blockchain, a także szybkie przenoszenie dużych ilości danych z jednego węzła komputerowego do drugiego w sieci blockchain typu peer-to-peer.

Każda transakcja zachodząca w sieci blockchain ma powiązany z nią hash. Jednak te skróty nie są przechowywane w kolejności sekwencyjnej w bloku, a raczej w formie struktury przypominającej drzewo, tak że każdy skrót jest połączony ze swoim rodzicem zgodnie z relacją podobną do drzewa rodzic-dziecko.

Ponieważ w danym bloku przechowywanych jest wiele transakcji, wszystkie skróty transakcji w tym bloku są również haszowane, co powoduje powstanie korzenia Merkle.

Rozważmy na przykład blok składający się z siedmiu transakcji. Na najniższym poziomie (nazywanym poziomem liścia) będą cztery skróty transakcji. Na pierwszym poziomie powyżej poziomu liścia będą dwa skróty transakcji, z których każdy będzie łączył się z dwoma skrótami znajdującymi się poniżej nich na poziomie liścia. Na górze (poziom drugi) znajduje się ostatni hash transakcji zwany rootem, który połączy się z dwoma hashami znajdującymi się poniżej (na poziomie pierwszym).

W efekcie otrzymujesz odwrócone drzewo binarne, w którym każdy węzeł drzewa łączy się tylko z dwoma węzłami poniżej (stąd nazwa „drzewo binarne”). Na górze znajduje się jeden skrót główny, który łączy się z dwoma skrótami na poziomie pierwszym, z których każdy ponownie łączy się z dwoma skrótami na poziomie trzecim (na poziomie liścia), a struktura jest kontynuowana w zależności od liczby skrótów transakcji.

<!--AAFEB15A7406E8DD3ABDD652D7C85823-->

Hashowanie rozpoczyna się na węzłach najniższego poziomu (na poziomie liścia), a wszystkie cztery skróty są zawarte w hashu węzłów, które są z nim połączone na poziomie pierwszym. Podobnie, haszowanie jest kontynuowane na poziomie pierwszym, co prowadzi do mieszania haszy osiągających wyższe poziomy, aż do osiągnięcia pojedynczego hashowania najwyższego roota.

Ten skrót główny nazywany jest korzeniem Merkle'a i ze względu na podobne do drzewa powiązanie skrótów zawiera wszystkie informacje o każdym haszu transakcji, który istnieje w bloku. Oferuje jednopunktową wartość skrótu, która umożliwia walidację wszystkiego, co jest obecne w tym bloku.

Na przykład, jeśli ktoś musi zweryfikować transakcję, która twierdzi, że pochodzi z bloku #137, wystarczy sprawdzić drzewo Merkle bloku, nie martwiąc się o weryfikację czegokolwiek na innych blokach w łańcuchu bloków, takich jak blok #136 lub blok # 138.

<!--4861E8697637B7236BF11AA57D958059-->

Wprowadź korzeń Merkle, co dodatkowo przyspiesza weryfikację. Ponieważ zawiera wszystkie informacje o całym drzewie, wystarczy zweryfikować hash transakcji, jego węzeł siostrzany (jeśli istnieje), a następnie przejść w górę, aż osiągnie szczyt.

Zasadniczo drzewo Merkle i mechanizm Merkle root znacznie zmniejszają poziomy haszowania, które należy wykonać, umożliwiając szybszą weryfikację i transakcje.

##Przegląd najważniejszych wydarzeń

- Korzenie Merkle są kluczowe dla obliczeń wymaganych do utrzymania kryptowalut, takich jak bitcoin i ether.

- Korzenie Merkle są używane w kryptowalutach, aby upewnić się, że bloki danych przekazywane między peerami w sieci peer-to-peer są całe, nieuszkodzone i niezmienione.

- Korzeń Merkle to prosty matematyczny sposób weryfikacji danych na drzewie Merkle.

