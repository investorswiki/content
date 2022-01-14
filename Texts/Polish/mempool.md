---
keywords: Crypto
title: Mempool
description: Mempool. Mechanizm węzła służący do śledzenia niepotwierdzonych transakcji, które węzeł widział (ale nie zostały jeszcze dodane do bloku).
---

# Mempool
Mempool (skrócenie pamięci i puli) to mechanizm węzła kryptowaluty do przechowywania informacji o niepotwierdzonych transakcjach. Działa jak poczekalnia dla transakcji, które nie zostały jeszcze ujęte w [bloku](/block).

Kiedy transakcja jest rozgłaszana, jest wysyłana z węzła do jego partnerów, którzy następnie przekazują ją do swoich partnerów. Trwa to do momentu, gdy transakcja zostanie szeroko rozpowszechniona, gotowa dla górników do dodania jej do bloku. Ważne jest, aby ta strefa buforowa istniała, ponieważ transakcje nie są natychmiast dodawane do łańcucha bloków.

Węzły przeprowadzą serię kontroli, aby upewnić się, że transakcja jest ważna – tj. weryfikując, czy podpisy są poprawne, dane wyjściowe nie przekraczają danych wejściowych, a fundusze nie zostały jeszcze wydane. Jeśli nie spełnia tych warunków, zostaje odrzucony.

Często mówimy o mempool, ale należy zauważyć, że nie ma uniwersalnej puli współdzielonej przez wszystkie węzły. Każdy z nich jest inaczej skonfigurowany i odbiera transakcje w różnym czasie. Urządzenia niższej klasy z ograniczonymi zasobami mogą poświęcać tylko niewielką ilość pamięci na rejestrowanie transakcji, podczas gdy urządzenia wyższej klasy mogą poświęcać znacznie więcej.

Ponieważ górnicy są motywowani głównie zyskami, transakcje z wyższymi opłatami to te, które najprawdopodobniej zostaną najpierw odrzucone z pamięci, gdy zostaną potwierdzone. Dokładne oszacowanie opłat jest trudne, szczególnie gdy powierzchnia bloków jest ograniczona, a popyt wysoki, ale mempool stanowi punkt wyjścia.

Aby oszacować opłaty, można spojrzeć na bieżące niepotwierdzone transakcje. Jest zrozumiałe, że użytkownicy nie powinni przepłacać w czasach niskiej przepustowości. Nie powinni też płacić za mało terminowe transakcje w godzinach szczytu, ponieważ może upłynąć trochę czasu, zanim zostanie to potwierdzone. Biorąc pod uwagę rozpiętość opłat w danym momencie, mogą zgadywać, jak szybko ich transakcja zostanie uwzględniona.

