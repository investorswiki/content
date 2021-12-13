---
keywords: Crypto
title: BEP-95
description: BEP-95. BEP-95 to propozycja Binance Evolution, która wprowadza mechanizm nagrywania w czasie rzeczywistym do Binance Smart Chain. To sprawia, że tokenomika BNB jest bardziej dynamiczna i zdecentralizowana.
---

# BEP-95
BEP-95 to propozycja Binance Evolution, która wprowadza mechanizm nagrywania w czasie rzeczywistym do Binance Smart Chain. Został wprowadzony, aby uczynić tokenomika BNB jeszcze bardziej dynamiczną i jeszcze bardziej zdecentralizować sieć.

Dzięki BEP-95 sieć będzie spalać stały współczynnik opłat za gaz pobieranych przez walidatorów każdego bloku. Dokładny stosunek zostanie określony za pomocą mechanizmów zarządzania BSC. Oparzenia będą miały miejsce nawet po osiągnięciu przez BSC docelowego celu 100 milionów BNB. Zmniejszając podaż BNB, wywierana jest presją zwyżkową na cenę monety. BEP może również zmniejszyć liczbę otrzymanych osób delegujących i walidatorów BNB. Jednak wraz z presją na wzrost cen może również wzrosnąć wartość fiducjarna, kompensując wszelkie spadki monet.

Aby to technicznie wdrożyć, sieć pobiera opłaty za gaz od każdego bloku i dzieli się na dwa inteligentne kontrakty:

**jeden. Kontrakt nagrody systemowej.** 1/16 opłaty za gaz wchodzi do Kontraktu nagrody systemowej, dopóki nie osiągnie maksimum 100 BNB. Monety te zostaną wykorzystane jako dotacje do pakietów międzyłańcuchowych.

**2. Umowa ValidatorSet.** Wszystkie inne opłaty za gaz zostaną włączone do umowy ValidatorSet i będą codziennie udostępniane osobom delegującym i walidatorom za pośrednictwem Binance Chain.

Aby przeprowadzić wypalanie, kontrakt ValidatorSet ma zmienną burnRatio. Po sfinalizowaniu każdego bloku, walidator podpisze transakcję przenosząc swoje opłaty za gaz na inteligentne kontrakty. Funkcja depozytu zawiera logikę spalania, która uruchamia prostą formułę: burnRatio * gasFee. Kwota ta zostanie następnie przekazana na adres nagrywania. BurnRatio będzie początkowo ustawione na 10%.

Walidatorzy BSC będą mogli głosować za pomocą propozycji zmiany kwoty burnRatio. Ten mechanizm zarządzania występuje w Binance Chain, a każdy członek społeczności może przesłać propozycję do przeglądu z minimalnym depozytem 2000 BNB. Wszystkie BNB postawione za propozycją i w głosowaniu są zwracane po podjęciu decyzji. Kworum zostaje osiągnięte na poziomie 50%, a zmiana zostanie natychmiast wdrożona za pośrednictwem komunikacji międzyłańcuchowej.

