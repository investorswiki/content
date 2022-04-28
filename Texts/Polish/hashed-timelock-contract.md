---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Crypto,Strategy and Education
title: Umowa haszowana na czas (HTLC)
description: Zaszyfrowany kontrakt TimeLock (HTLC). Odnosi się do specjalnej funkcji, która służy do tworzenia inteligentnych kontraktów, które mogą modyfikować kanały płatności.
---

# Umowa haszowana na czas (HTLC)
Termin Hashed TimeLock Contract (HTLC) odnosi się do specjalnej funkcji, która służy do tworzenia [inteligentnych kontraktów](/smart-contract),. które mogą modyfikować kanały płatności. Z technicznego punktu widzenia funkcja HTLC umożliwia implementację transakcji czasowych między dwoma użytkownikami. W praktyce odbiorca transakcji HTLC musi potwierdzić płatność poprzez złożenie dowodu kryptograficznego w określonym czasie (liczba bloków). Jeśli odbiorca zrezygnuje lub nie zażąda płatności, środki zostaną zwrócone pierwotnemu nadawcy.

Funkcja HTLC jest stosowana zarówno w dwukierunkowych, jak i kierowanych kanałach płatności, aby umożliwić bezpieczne transfery środków różnymi kanałami, bez konieczności zaufania do żadnego z pośredników.

Istnieją dwa kluczowe elementy, które odróżniają HTLC od standardowych transakcji kryptowalutowych, którymi są:

- Hashlock: funkcja, która ogranicza wydawanie środków do czasu publicznego ujawnienia pewnej części danych (jako dowód kryptograficzny). Taki dowód może być również określany jako wstępny obraz hashlocka. Wstępny obraz to po prostu informacja, która służy do wygenerowania hashlocka, a następnie odblokowania jego funduszy.

- Blokada czasowa: to funkcja, która ogranicza wydawanie środków do określonego czasu (lub wysokości bloku) w przyszłości. Można to osiągnąć w Bitcoin, na przykład za pomocą funkcji takich jak CheckLockTimeVerify lub CheckSequenceVerify.

Bitcoin Lightning Network jest jednym z najpopularniejszych przypadków użycia kontraktów haszowanych czasowo zablokowanych. Dzięki wdrożeniu HTLC w kanałach płatniczych środki mogą być przekazywane od użytkownika do użytkownika za pośrednictwem połączonych kanałów płatniczych, bez konieczności posiadania jakiegokolwiek poziomu zaufania. Ten proces jest znany jako routing sieciowy. Pozwala Alice na wymianę środków z Carol, nawet jeśli nie są one bezpośrednio połączone kanałem płatności. HTLC umożliwia Alicji wysyłanie jej funduszy do Carol za pośrednictwem innych uczestników sieci (np. Boba), a funkcje hashlock i timelock zapewniają, że Bob nie może przechwycić funduszy.

Oprócz zastosowania w sieci Lightning Network, HTLC mogą być również przydatne w innych kontekstach, takich jak cross-chain [atomic swaps](/atomic-swaps),. finansowe inteligentne kontrakty i depozyty i wiele innych.

## Przegląd najważniejszych wydarzeń

- Płatności za pomocą HTLC są warunkowe, a więc przynoszą korzyści w zakresie wydajności transakcji blockchain. Ta właściwość sprawia, że HTLC są podstawowym narzędziem używanym przez sieć piorunową.

- Ten rodzaj inteligentnej umowy wymaga od odbiorcy płatności potwierdzenia jej w określonym czasie lub jej rezygnacji.

- Zaszyfrowany kontrakt na blokadę czasową (HTLC) zmniejsza ryzyko kontrahenta w zdecentralizowanych inteligentnych kontraktach, skutecznie tworząc depozyt oparty na czasie, który wykorzystuje hasło kryptograficzne.

## FAQ

### Ile kosztuje inteligentny kontrakt?

W blockchainie Ethereum wdrożenie inteligentnego kontraktu wymaga gazu, który kosztuje Gwei (niższe oznaczenie eteru). W zależności od złożoności kontraktu wdrożenie inteligentnego kontraktu może kosztować miliardy Gwei. Mniej skomplikowane kontrakty, jak zwykła wymiana, są znacznie tańsze.

### Co to jest inteligentny kontrakt?

Inteligentny kontrakt to program przechowywany w łańcuchu bloków, który jest wykonywany po spełnieniu określonych warunków.

### Co to jest umowa na blokadę czasu?

Kontrakt na blokadę czasową to inteligentna umowa osadzona w łańcuchu bloków, która wykonuje transakcję w określonym czasie. Są one używane w umowach haszowanych na blokady czasowe i kanałach płatności, w których potrzebne są określone terminy płatności.

### Czy Bitcoin ma inteligentne kontrakty?

Początkowo blockchain Bitcoina nie był w stanie realizować inteligentnych kontraktów. Jednak aktualizacja Taproot w 2021 r. pozwoliła blockchainowi na wykorzystanie inteligentnych kontraktów w transakcjach.

