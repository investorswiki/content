---
keywords: Crypto
title: Niewykorzystane dane wyjściowe transakcji (UTXO)
description: Niewykorzystane dane wyjściowe transakcji (UTXO). Dane wyjściowe utworzone w transakcji, do których należy się odwołać w przyszłej transakcji, aby wydać środki.
---

# Niewykorzystane dane wyjściowe transakcji (UTXO)
Niewykorzystane dane wyjściowe transakcji (UTXO) odnoszą się do danych wyjściowych transakcji, które można wykorzystać jako dane wejściowe w nowej transakcji. Zasadniczo UTXO określają, gdzie każda transakcja blockchain zaczyna się i kończy. Model UTXO to fundamentalny element Bitcoina i wielu innych kryptowalut.

Innymi słowy, transakcje kryptowalutowe składają się z wejść i wyjść. Za każdym razem, gdy dokonywana jest transakcja, użytkownik przyjmuje jeden lub więcej UTXO, aby służyły jako dane wejściowe. Następnie użytkownik dostarcza swój podpis cyfrowy, aby potwierdzić własność danych wejściowych, co ostatecznie skutkuje danymi wyjściowymi. Zużyte UTXO są teraz uważane za „zużyte” i nie można ich już używać. Tymczasem dane wyjściowe z transakcji stają się nowymi UTXO – które później można wykorzystać w nowej transakcji.

Można to prawdopodobnie lepiej wyjaśnić na przykładzie. Alicja ma w portfelu 0,45 BTC. To nie jest ułamek monety, jak moglibyśmy to konceptualizować. To raczej zbiór UTXO. W szczególności dwa UTXO o wartości 0,4 BTC i 0,05 BTC – dane wyjściowe z poprzednich transakcji. Teraz wyobraźmy sobie, że Alicja musi zapłacić Bobowi 0,3 BTC.

Jej jedyną opcją jest rozbicie jednostki 0,4 BTC i wysłanie 0,3 BTC do Boba i 0,1 BTC z powrotem do siebie. Normalnie odzyskałaby mniej niż 0,1 BTC z powodu opłat za wydobycie, ale uprośćmy i pomińmy górnika.

Alicja tworzy transakcję, która zasadniczo mówi sieci: weź moje 0,4 BTC UTXO jako dane wejściowe, podziel je, wyślij 0,3 BTC na adres Boba i zwróć 0,1 BTC na mój adres. 0,4 BTC to teraz zużyty wynik i nie można go ponownie wykorzystać. W międzyczasie powstały dwa nowe UTXO (0,3 BTC i 0,1 BTC).

Zauważ, że w tym przykładzie rozbiliśmy UTXO, ale gdyby Alicja musiała zapłacić 0,42 BTC, równie dobrze mogłaby połączyć swoje 0,4 BTC z innym 0,05 BTC, aby wyprodukować UTXO o wartości 0,42 BTC, przy jednoczesnym zwróceniu sobie 0,03 BTC.

Podsumowując, model UTXO służy jako mechanizm protokołu do śledzenia, gdzie w danym momencie znajdują się monety. W pewnym sensie działają one podobnie jak czeki: są skierowane do określonych użytkowników (a raczej ich [adresów publicznych](/address) ). UTXO nie można wydać w części – zamiast tego należy utworzyć nowe czeki ze starego i odpowiednio przekazać je dalej.

