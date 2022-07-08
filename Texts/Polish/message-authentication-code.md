---
keywords: Personal Finance,Banking
title: Kod uwierzytelniania wiadomości (MAC)
description: Kod uwierzytelniania wiadomości (MAC) lub tag to kod zabezpieczający, który jest wpisywany przez użytkownika komputera w celu uzyskania dostępu do kont lub portali.
---

# Kod uwierzytelniania wiadomości (MAC)
## Co to jest kod uwierzytelniania wiadomości?

Kod uwierzytelniania wiadomości (MAC) lub **tag** to kod zabezpieczający, który jest wpisywany przez użytkownika komputera w celu uzyskania dostępu do kont lub portali. Ten kod jest dołączony do wiadomości lub żądania wysłanego przez użytkownika. Kody uwierzytelniania wiadomości (MAC) dołączone do wiadomości muszą być rozpoznawane przez system odbierający, aby umożliwić użytkownikowi dostęp.

## Zrozumienie kodu uwierzytelniania wiadomości (MAC)

Kody uwierzytelniania wiadomości (MAC) są powszechnie używane w [elektronicznych transferach funduszy](/electronic-funds-transfer-act) (EFT) w celu zachowania integralności informacji. potwierdzają autentyczność wiadomości; że rzeczywiście pochodzi, innymi słowy, od podanego nadawcy i nie przeszła żadnych zmian po drodze. Weryfikator, który również posiada klucz, może go użyć do zidentyfikowania zmian w treści danej wiadomości.

Kody uwierzytelniające wiadomości są zwykle wymagane w celu uzyskania dostępu do dowolnego konta finansowego. Banki, firmy maklerskie, firmy powiernicze i wszelkie inne firmy depozytowe, inwestycyjne lub ubezpieczeniowe oferujące dostęp online mogą stosować te kody. Są istotnym elementem kryptografii finansowej.

## Algorytmy używane do generowania adresów MAC

Trzy algorytmy zazwyczaj obejmują MAC: algorytm generowania klucza, algorytm podpisywania i algorytm weryfikacji. Algorytm generowania klucza wybiera klucz losowo. Algorytm podpisywania wysyła tag po podaniu klucza i wiadomości. algorytm weryfikacji służy do weryfikacji autentyczności wiadomości po podaniu klucza i znacznika; zwróci wiadomość **accepted**, jeśli wiadomość i tag są autentyczne i niezmienione, ale w przeciwnym razie zwróci wiadomość **rejected**.

Na przykład nadawca wysyła wiadomość, taką jak EFT, za pomocą algorytmu MAC, który generuje klucz i dołącza do wiadomości znacznik danych MAC. Odbiorca otrzymuje wiadomość, przepuszcza ją z powrotem przez algorytm MAC z tym samym kluczem i otrzymuje drugi znacznik danych. Następnie porównają ten znacznik danych MAC z pierwszym dołączonym do wiadomości w momencie jej transmisji. Jeśli kod jest taki sam na obu końcach, odbiorca może bezpiecznie założyć, że integralność danych wiadomości jest nienaruszona. Jeśli nie, oznacza to jednak, że wiadomość została zmieniona, przerobiona lub sfałszowana.

Jednak sama wiadomość powinna zawierać pewne dane, które zapewniają, że wiadomość ta może zostać wysłana tylko raz. Na przykład jednorazowy adres MAC, znacznik czasu lub numer sekwencyjny można wykorzystać do zagwarantowania, że wiadomość może zostać wysłana tylko raz. W przeciwnym razie system może być podatny na atak polegający na powtórzeniu, w którym osoba atakująca przechwyci wiadomość po jej zdekodowaniu i ponownie ją prześle w późniejszym czasie, replikując oryginalne wyniki i infiltrując system.

## Kody integralności wiadomości (MIC)

Czasami zamiast MAC będzie używany termin kod integralności wiadomości (MIC). Najczęściej odbywa się to w branży komunikacyjnej, gdzie MAC tradycyjnie oznacza adres kontroli dostępu do mediów (adres MAC). Jednak MIC może być również używany w odniesieniu do **streszczenia wiadomości**, który nie używa tajnych kluczy w taki sam sposób jak MAC i nie może oferować tego samego poziomu bezpieczeństwa bez dalszego szyfrowania.

