---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: drzewo merkle
description: merkle drzewo. Sposób organizowania i strukturyzowania dużych ilości danych w celu uproszczenia ich przetwarzania. Struktura danych oparta na hashach.
---

# drzewo merkle
Drzewo Merkle to sposób organizowania i strukturyzowania dużych ilości danych, aby ułatwić ich przetwarzanie. W przypadku kryptowalut i [blockchain](/blockchain) drzewo Merkle służy do strukturyzowania danych transakcyjnych w sposób mniej obciążający zasoby.

Gdy transakcja kryptowalutowa jest dokonywana w strukturze drzewa Merkle, jest ona haszowana, a następnie przypisywana równoważnej wartości hashującej. Po zahaszowaniu każdej transakcji w drzewie Merkle, wytworzone wartości haszowania są sparowane z inną wartością haszowania, a następnie ponownie haszowane. Na przykład wartości skrótu „AB” i „AC” są łączone w celu utworzenia „ABC”.

Ten proces parowania wartości skrótu jest powtarzany do momentu wygenerowania ostatecznej wartości skrótu. Ostateczna wartość skrótu, korzeń Merkle'a, zawiera podsumowanie wszystkich zawartych w nim transakcji. Podsumowanie główne Merkle jest następnie wstawiane do nagłówka bloku.

####Ochrona danych

Struktura drzewa Merkle zapewnia łatwy dostęp do rejestru transakcji w [bloku](/block). Tak więc bardzo łatwo jest sprawdzić, czy dane w bloku zostały zmienione lub zmodyfikowane. Jest to prawdą, ponieważ każda zmiana transakcji (lub jakichkolwiek innych powiązanych danych) w drzewie Merkle prowadziłaby do zupełnie innego odpowiadającego korzenia Merkle.

#### Efektywne wykorzystanie zasobów

Gdyby kryptowaluty nie wykorzystywały drzew Merkle, każde żądanie weryfikacji wiązałoby się z przesyłaniem ogromnych ilości informacji przez sieć. Strukturyzacja danych transakcyjnych w drzewie Merkle to znacznie bardziej efektywne wykorzystanie zasobów. Walidacja transakcji nie wymaga pełnej kopii księgi, ponieważ zaszyfrowane dane transakcji można zweryfikować w katalogu głównym Merkle, co wymaga znacznie mniej informacji przesyłanych przez węzły, a tym samym mniejszej mocy obliczeniowej do analizy ogólnej integralności danych.

Innymi słowy, struktura drzewa Merkle umożliwia użytkownikom weryfikację, czy pojedyncza transakcja została uwzględniona w bloku, bez konieczności przechodzenia przez proces pobierania całego łańcucha bloków. Technologia jest ważnym narzędziem dla kryptowalut do organizowania danych transakcyjnych i funkcjonowania tak samo wydajnie, jak one. Bez drzew Merkle prawdopodobnie większe zapotrzebowanie na zasoby skutkowałoby mniejszą liczbą [węzłów](/node) uczestniczących w sieci.

