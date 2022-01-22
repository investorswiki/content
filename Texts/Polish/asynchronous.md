---
keywords: Crypto
title: Asynchroniczny
description: asynchroniczny. Zdarzenia w systemach elektronicznych, które nie zachodzą w tym samym czasie lub nie przebiegają szybko, lub zachodzą niezależnie od głównego przepływu programu.
---

# Asynchroniczny
Zgłoszenie społeczności - Autor: **Caner Taçoğlu**

Asynchroniczny oznacza, że nie jest równoczesny lub nie dzieje się w tym samym czasie lub prędkości. W informatyce asynchronia odnosi się do występowania zdarzeń niezależnych od programu głównego.

W systemie asynchronicznym operacje nie są koordynowane przez globalny sygnał zegarowy, ale raczej przez zdarzenia (zmiany w systemie). Niezawodne działanie systemów asynchronicznych nie jest uzależnione od zewnętrznych sygnałów lub komunikatów.

Systemy asynchroniczne są często projektowane z wykorzystaniem struktury modułowej. W takich systemach każdy moduł może działać niezależnie i ma możliwość komunikacji z innymi modułami. Te połączone ze sobą moduły tworzą razem działający system.

Komunikacja asynchroniczna ma miejsce wtedy, gdy dane mogą być przesyłane nieregularnie, zamiast w stałym strumieniu. Typowe przykłady to poczta e-mail lub fora internetowe, na których uczestnicy wysyłają wiadomości w różnym czasie.

Łańcuchy bloków mogą być sieciami asynchronicznymi lub półsynchronicznymi.

Sieci asynchroniczne nie dostarczają węzłom żadnych informacji zwrotnych o stanie przesyłanych informacji, co może prowadzić do tego, że węzły mają różne poglądy na ogólny stan sieci. Zasadniczo węzły nie muszą czekać, aż inne węzły otrzymają swoje komunikaty, co może zwiększyć przepustowość transakcji.

Sieci półsynchroniczne mają na celu zapewnienie, że nigdy nie dojdzie do podziału w globalnym stanie sieci. Jeśli sieć jest podzielona na partycje, konsensus między węzłami zostanie spowolniony, dopóki nie zostanie przywrócony.

Asynchroniczne lub półsynchroniczne sieci blockchain mogą być projektowane w celu nadania priorytetu spójności lub dostępności. Jeśli sieć chce ustalić priorytety dostępności, wszystkie transakcje są dodawane bez przestojów. Jeśli sieć chce nadać priorytet spójności, niektóre transakcje mogą nie zostać przetworzone lub wstrzymane, dopóki wszystkie poprzednie transakcje nie zostaną potwierdzone.

Niektóre projekty blockchain wykorzystują implementację Byzantine Fault Tolerance (BFT) o nazwie Asynchronous Byzantine Fault Tolerance (aBFT). Matematycznie gwarantuje, że konsensus zostanie ostatecznie osiągnięty, nawet jeśli atakujący kontroluje prawie jedną trzecią sieci. Asynchroniczny w tym kontekście oznacza, że nie przyjmuje się żadnych założeń dotyczących taktowania.

