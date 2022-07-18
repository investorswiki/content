---
keywords: Personal Finance,Banking
title: Mesaj Doğrulama Kodu (MAC)
description: Mesaj doğrulama kodu (MAC) veya etiketi, hesaplara veya portallara erişmek için bir bilgisayar kullanıcısı tarafından yazılan bir güvenlik kodudur.
---

# Mesaj Doğrulama Kodu (MAC)
## Mesaj Doğrulama Kodu Nedir?

Mesaj doğrulama kodu (MAC) veya **etiket**, hesaplara veya portallara erişmek için bilgisayar kullanıcısı tarafından yazılan bir güvenlik kodudur. Bu kod, kullanıcı tarafından gönderilen mesaja veya isteğe eklenir. Mesaja eklenen mesaj doğrulama kodları (MAC'ler), kullanıcıya erişim izni vermek için alıcı sistem tarafından tanınmalıdır.

## İleti Kimlik Doğrulama Kodunu (MAC) Anlama

bilgi bütünlüğünü korumak için [elektronik fon transferlerinde (EFT'ler)](/electronic-funds-transfer-act) yaygın olarak kullanılır . bir mesajın gerçek olduğunu onaylarlar; başka bir deyişle, gerçekten belirtilen göndericiden geldiğini ve yolda herhangi bir değişikliğe uğramadığını. Anahtara da sahip olan bir doğrulayıcı, söz konusu mesajın içeriğindeki değişiklikleri belirlemek için anahtarı kullanabilir.

Mesaj doğrulama kodları genellikle herhangi bir finansal hesaba erişmek için gereklidir. Bankalar, aracı kurumlar, tröst şirketleri ve çevrimiçi erişim sunan diğer mevduat, yatırım veya sigorta şirketleri bu kodları kullanabilir. Bunlar finansal kriptografinin hayati bir bileşenidir.

## MAC Oluşturmak için Kullanılan Algoritmalar

Üç algoritma tipik olarak bir MAC içerir: bir anahtar oluşturma algoritması, bir imzalama algoritması ve bir doğrulama algoritması. Anahtar oluşturma algoritması rastgele bir anahtar seçer. İmzalama algoritması, anahtar ve mesaj verildiğinde bir etiket gönderir. doğrulama algoritması, anahtar ve etiket verildiğinde mesajın gerçekliğini doğrulamak için kullanılır; mesaj ve etiket gerçek ve değiştirilmemişse **kabul edildi** mesajını döndürür, aksi takdirde **reddedildi** mesajını döndürür.

Örneğin gönderici, bir anahtar oluşturan ve mesaja bir MAC veri etiketi ekleyen MAC algoritması aracılığıyla EFT gibi bir mesaj gönderir. Alıcı mesajı alır, aynı anahtarla MAC algoritması üzerinden geri çalıştırır ve ikinci bir veri etiketi alır. Daha sonra bu MAC veri etiketini, iletilirken mesaja eklenen ilk etiketle karşılaştıracaklar. Kod her iki uçta da aynıysa, alıcı mesajın veri bütünlüğünün bozulmamış olduğunu güvenle kabul edebilir. Ancak değilse, mesajın değiştirildiği, kurcalandığı veya sahte olduğu anlamına gelir.

Ancak, mesajın kendisi, bu mesajın yalnızca bir kez gönderilmesini sağlayan bazı verileri içermelidir. Örneğin, mesajın yalnızca bir kez gönderilebileceğini garanti etmek için tek seferlik bir MAC, zaman damgası veya sıra numarası kullanılabilir. Aksi takdirde, sistem, bir saldırganın mesajın kodu çözüldükten sonra araya girip daha sonra yeniden ileterek, orijinal sonuçları çoğaltarak ve sisteme sızdığı bir yeniden yürütme saldırısına karşı savunmasız olabilir.

## Mesaj Bütünlük Kodları (MIC'ler)

Bazen, MAC yerine mesaj bütünlüğü kodu (MIC) terimi kullanılacaktır. Bu genellikle MAC'in geleneksel olarak medya erişim kontrol adresi (MAC adresi) anlamına geldiği iletişim endüstrisinde yapılır. Bununla birlikte, MIC, gizli anahtarları bir MAC ile aynı şekilde kullanmayan ve daha fazla şifreleme olmadan aynı düzeyde güvenlik sunamayan **mesaj özetine** atıfta bulunmak için de kullanılabilir.

