---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: Haszysz
description: Haszysz. Dane wyjściowe generowane przez funkcję skrótu po zmapowaniu części danych. Może być również określany jako wartość skrótu, kod skrótu lub skrót.
---

# Haszysz
W [kryptografii](/cryptography) słowo hash odnosi się do danych wyjściowych generowanych przez funkcję haszującą po przesłaniu (zmapowaniu) przez nią części danych. Poza haszowaniem dane wyjściowe generowane przez funkcje skrótu mogą być również określane jako wartość skrótu, kod skrótu lub skrót.

Aby lepiej zrozumieć, czym jest skrót, warto omówić, czym są funkcje skrótu i jak działają.

Funkcje skrótu to [algorytmy matematyczne,](/algorithm) które konwertują wartość wejściową dowolnego rozmiaru na wynik (skrót) o stałym rozmiarze. W większości przypadków dane wyjściowe składają się z liczby szesnastkowej. Oznacza to, że skrót jest często oznaczany jako kombinacja cyfr (od 0 do 9) i liter (od a do f).

Na przykład, jeśli użyjemy słowa „Binance” jako wartości wejściowej i zmapujemy ją za pomocą funkcji skrótu SHA-256, zwrócona wartość wyjściowa (lub hash) będzie:

f1624fcc63b615ac0e95daf9ab78434ec2e8ffe402144dc631b055f711225191

Zauważ, że nie ma znaczenia, ile razy wykonamy tę akcję, dane wyjściowe będą zawsze takie same (o ile dane wejściowe się nie zmienią).

Z drugiej strony każda drobna zmiana danych wejściowych spowoduje, że funkcja skrótu zwróci zupełnie inny skrót jako dane wyjściowe. Na przykład, jeśli prześlemy słowo „binance” zamiast „Binance”, otrzymamy następujący hash:

59bba357145ca539dcd1ac957abc1ec5833319ddcae7f5e8b5da0c36624784b2

Hasze są przydatne do weryfikowania ważności niektórych informacji, bez ujawniania, czym one są. W praktyce funkcje skrótu można zastosować do różnych scenariuszy. Kilka przypadków użycia obejmuje wyszukiwanie w bazach danych, analizy dużych plików i zarządzanie danymi.

W połączeniu z technikami kryptograficznymi mamy tzw. funkcje skrótu kryptograficznego. Są one szeroko stosowane w bezpieczeństwie informacji i stanowią istotną część większości sieci blockchain.

Na przykład blockchain Bitcoina ma wiele operacji, które obejmują hashowanie, a te są kluczowe w procesie kopania.

## Przegląd najważniejszych wydarzeń

- Hash to funkcja, która spełnia zaszyfrowane wymagania potrzebne do rozwiązania obliczeń blockchain.

- Hash, podobnie jak nonce lub rozwiązanie, jest kręgosłupem sieci blockchain.

- Hash jest tworzony na podstawie informacji zawartych w nagłówku bloku.

- Hasze mają ustaloną długość, ponieważ prawie niemożliwe jest odgadnięcie długości skrótu, jeśli ktoś próbował złamać blockchain.

- Te same dane zawsze dadzą tę samą zahaszowaną wartość.

## FAQ

### Jak obliczana jest wartość skrótu?

Funkcja skrótu wykorzystuje złożone algorytmy matematyczne, które konwertują dane o dowolnej długości na dane o stałej długości (na przykład 256 znaków). Jeśli zmienisz jeden bit w dowolnym miejscu oryginalnych danych, zmieni się cała wartość skrótu, co jest przydatne do weryfikacji wierności plików cyfrowych i innych danych.

### Do czego służą skróty w łańcuchach bloków?

Hasze są używane w kilku częściach systemu blockchain. Po pierwsze, każdy blok zawiera skrót [nagłówka bloku](/block-header-cryptocurrency) poprzedniego bloku, zapewniając, że nic nie zostało naruszone podczas dodawania nowych bloków. Co więcej, wydobywanie kryptowaluty za pomocą [proof-of-work](/proof-work) (PoW) wykorzystuje hashowanie losowo generowanych liczb w celu uzyskania określonej wartości haszowanej zawierającej szereg wiodących zer. Ta arbitralna funkcja wymaga dużych zasobów, co utrudnia przejęcie sieci przez złego aktora.

### Co to jest funkcja skrótu?

Funkcje skrótu to funkcje matematyczne, które przekształcają lub „mapują” dany zestaw danych na ciąg bitów o stałym rozmiarze, znany również jako „wartość skrótu”.

