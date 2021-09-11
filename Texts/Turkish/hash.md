---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: Doğramak
description: Doğramak. Bir veri parçası eşlendikten sonra bir karma işlevi tarafından üretilen çıktı. Hash değeri, hash kodu veya özet olarak da ifade edilebilir.
---

# Doğramak
Kriptografide , hash [kelimesi](/cryptography),. bir veri parçası gönderildikten (haritalandıktan) sonra bir hash fonksiyonu tarafından üretilen çıktıyı ifade eder. Basitçe hash dışında, hash fonksiyonları tarafından üretilen çıktıya hash değeri, hash kodu veya özet olarak da atıfta bulunulabilir.

Hash'in ne olduğunu daha iyi anlamak için hash fonksiyonlarının ne olduğunu ve nasıl çalıştıklarını tartışmaya değer.

Hash fonksiyonları, herhangi bir boyuttaki bir girdi değerini sabit boyutlu bir çıktıya (hash) dönüştüren matematiksel [algoritmalardır .](/algorithm) Çoğu durumda, çıktı onaltılık bir sayıdan oluşur. Bu, hash'in genellikle sayıların (0 ila 9) ve harflerin (a ila f) bir kombinasyonu olarak gösterildiği anlamına gelir.

Örneğin, girdi değeri olarak "Binance" kelimesini kullanırsak ve onu bir SHA-256 karma işleviyle eşlersek, döndürülen çıktı değeri (veya karma) şöyle olacaktır:

f1624fcc63b615ac0e95daf9ab78434ec2e8ffe402144dc631b055f711225191

Bu eylemi kaç kez yaptığımızın önemi olmadığını unutmayın, çıktı her zaman aynı olacaktır (giriş değişmediği sürece).

Öte yandan, girdide yapılacak herhangi bir küçük değişiklik, hash fonksiyonunun çıktı olarak tamamen farklı bir hash döndürmesine neden olacaktır. Örneğin, "Binance" yerine "binance" kelimesini gönderirsek, sonuç olarak aşağıdaki hash'i elde ederiz:

59bba357145ca539dcd1ac957abc1ec5833319ddcae7f5e8b5da0c36624784b2

Karmalar, bilgilerin ne olduğunu açıklamadan belirli bilgilerin geçerliliğini doğrulamak için kullanışlıdır. Pratikte, hash fonksiyonları çeşitli senaryolara uygulanabilir. Birkaç kullanım örneği, veritabanı aramalarını, büyük dosya analizlerini ve veri yönetimini içerir.

Kriptografik tekniklerle birleştirildiğinde, sözde kriptografik hash fonksiyonlarına sahibiz. Bunlar, bilgi güvenliğinde yaygın olarak kullanılmaktadır ve çoğu blok zinciri ağının önemli bir parçasıdır.

Örneğin, Bitcoin blok zincirinin karma içeren birçok işlemi vardır ve bunlar madencilik sürecinde çok önemlidir.

## Öne Çıkanlar

- Karma, bir blok zinciri hesaplaması için çözmek için gereken şifreli talepleri karşılayan bir işlevdir.

- Karma, nonce veya çözüm gibi, blok zinciri ağının belkemiğidir.

- Blok başlığında bulunan bilgilere dayalı olarak bir karma geliştirilir.

- Biri blok zinciri kırmaya çalışıyorsa, hash'in uzunluğunu tahmin etmeyi neredeyse imkansız hale getirdiğinden, hash'ler sabit bir uzunluktadır.

- Aynı veriler her zaman aynı karma değeri üretecektir.

## SSS

### Hash Değeri Nasıl Hesaplanır?

Bir karma işlevi, rastgele uzunluktaki verileri sabit uzunluktaki (örneğin, 256 karakter) verilere dönüştüren karmaşık matematiksel algoritmalar kullanır. Orijinal verilerde herhangi bir yerde bir bit değiştirirseniz, tüm karma değer değişir, bu da dijital dosyaların ve diğer verilerin aslına uygunluğunu doğrulamak için kullanışlı hale getirir.

### Blok Zincirlerinde Hash'ler Ne İçin Kullanılır?

Hash'ler, bir blockchain sisteminin çeşitli bölümlerinde kullanılır. İlk olarak, her blok önceki bloğun [blok başlığının](/block-header-cryptocurrency) karmasını içerir ve yeni bloklar eklenirken hiçbir şeyin değiştirilmemesini sağlar. [Proof-of-work (PoW)](/proof-work) kullanan kripto para madenciliği , ayrıca, bir dizi baştaki sıfır içeren belirli bir karma değere ulaşmak için rastgele oluşturulmuş sayıların karmasını kullanır. Bu keyfi işlev, kaynak yoğundur ve kötü bir oyuncunun ağı ele geçirmesini zorlaştırır.

### Hash Fonksiyonu Nedir?

Karma işlevleri, belirli bir veri kümesini "karma değeri" olarak da bilinen sabit boyutlu bir bit dizisine dönüştüren veya "eşleyen" matematiksel işlevlerdir.

