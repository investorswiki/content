---
keywords: Investing,Fundamental Analysis
title: kademeli regresyon
description: Aşamalı regresyon, değişkenlerin eklenmesi veya çıkarılmasının yinelemeli bir sürecine dayanan bir modelde kullanılacak bağımsız değişkenlerin seçimini içerir.
---

# kademeli regresyon
## Adım Adım Regresyon Nedir?

, nihai bir modelde kullanılacak bağımsız değişkenlerin seçimini içeren bir [regresyon modelinin](/regression) adım adım yinelemeli yapısıdır . Potansiyel açıklayıcı değişkenlerin art arda eklenmesini veya çıkarılmasını ve her yinelemeden sonra istatistiksel anlamlılığın test edilmesini içerir.

İstatistiksel yazılım paketlerinin mevcudiyeti, yüzlerce değişkenli modellerde bile adım adım regresyonu mümkün kılar.

## Kademeli Regresyon Türleri

Kademeli regresyonun temel amacı, bir dizi test (örneğin F testleri, [t testleri](/t-test) ) aracılığıyla bağımlı değişkeni önemli ölçüde etkileyen bir dizi bağımsız değişken bulmaktır. Bu, bilgisayarlarla, tekrarlanan döngüler veya analiz döngülerinden geçerek sonuçlara veya kararlara ulaşma süreci olan yineleme yoluyla yapılır. İstatistiksel yazılım paketlerinin yardımıyla testleri otomatik olarak yapmak, zamandan tasarruf etme ve hataları sınırlama avantajına sahiptir.

Basamaklı regresyon, her seferinde bir bağımsız değişken deneyerek ve [istatistiksel olarak anlamlıysa onu regresyon modeline dahil ederek](/statistically_significant) veya tüm potansiyel bağımsız değişkenleri modele dahil ederek ve istatistiksel olarak anlamlı olmayanları eleyerek elde edilebilir. Bazıları her iki yöntemin bir kombinasyonunu kullanır ve bu nedenle adım adım regresyona yönelik üç yaklaşım vardır:

1. **İleriye doğru seçim** modelde hiçbir değişken olmadan başlar, modele eklenen her bir değişkeni test eder, ardından istatistiksel olarak en anlamlı kabul edilenleri tutar ve sonuçlar optimal olana kadar süreci tekrarlar.

1. **Geri eleme** bir dizi bağımsız değişkenle başlar, her seferinde bir tane silinir ve ardından kaldırılan değişkenin istatistiksel olarak anlamlı olup olmadığını test eder.

1. **İki yönlü eleme**, hangi değişkenlerin dahil edilmesi veya hariç tutulması gerektiğini test eden ilk iki yöntemin birleşimidir.

## örnek

Geriye doğru eleme yöntemini kullanan kademeli bir regresyon örneği, ekipman çalışma süresi, ekipman yaşı, personel boyutu, dışarıdaki sıcaklıklar ve yılın zamanı gibi değişkenleri kullanarak bir fabrikadaki enerji kullanımını anlama girişimi olabilir. Model, tüm değişkenleri içerir - daha sonra hangisinin istatistiksel olarak en az anlamlı olduğunu belirlemek için her biri birer birer kaldırılır. Sonuç olarak, model yılın zamanının ve sıcaklıkların en önemli olduğunu gösterebilir ve muhtemelen fabrikadaki en yüksek enerji tüketiminin klima kullanımının en yüksek olduğu zaman olduğunu düşündürür.

## Kademeli Regresyonun Sınırlamaları

Hem doğrusal hem de çok değişkenli regresyon analizi, bugün ekonomi ve yatırım dünyasında yaygın olarak kullanılmaktadır. Fikir genellikle geçmişte var olan ve gelecekte de tekrarlanabilecek kalıpları bulmaktır. Örneğin basit bir doğrusal regresyon, düşük F/K oranlarına (bağımsız değişken) sahip hisse senetlerinin daha yüksek getiriler (bağımlı değişken) sunup sunmadığını belirlemek için uzun yıllar boyunca [fiyat-kazanç oranlarına ve hisse senedi getirilerine bakabilir.](/price-earningsratio) Bu yaklaşımla ilgili sorun, piyasa koşullarının sıklıkla değişmesi ve geçmişte geçerli olan ilişkilerin şimdi veya gelecekte mutlaka geçerli olmamasıdır.

Bu arada, adım adım regresyon sürecinin birçok eleştirisi var ve hatta yöntemi kullanmayı tamamen bırakma çağrıları bile var. İstatistikçiler, yanlış sonuçlar, sürecin kendisinde doğal bir önyargı ve yineleme yoluyla karmaşık regresyon modelleri geliştirmek için önemli bilgi işlem gücünün gerekliliği dahil olmak üzere yaklaşımın birçok dezavantajına dikkat çekiyor.

##Öne çıkanlar

- Ancak, istenen sonucu elde etmek için verileri bir modele sığdıran bir yaklaşım olduğu için, kademeli regresyonun dezavantajları vardır.

- Geriye doğru eleme yöntemi, birkaç değişkenle yüklü tam bir modelle başlar ve ardından genel sonuçlara göre önemini test etmek için bir değişkeni kaldırır.

- Kademeli regresyon, doğrusal bir regresyon modelinde her bağımsız değişkenin istatistiksel önemini yinelemeli olarak inceleyen bir yöntemdir.

- İleri seçim yaklaşımı hiçbir şeyle başlar ve her yeni değişkeni aşamalı olarak ekleyerek istatistiksel anlamlılığı test eder.

