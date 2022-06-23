---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: Kutu-Jenkins Modeli
description: Box-Jenkins Modeli, belirli bir zaman serisinden verileri tahmin etmek için tasarlanmış matematiksel bir modeldir.
---

# Kutu-Jenkins Modeli
## Box-Jenkins Modeli Nedir?

[zaman serisinden](/timeseries) gelen girdilere dayalı olarak veri aralıklarını tahmin etmek için tasarlanmış matematiksel bir modeldir . Box-Jenkins Modeli, tahmin amaçları için birkaç farklı zaman serisi verisini analiz edebilir.

Metodolojisi, sonuçları belirlemek için veri noktaları arasındaki farklılıkları kullanır. Metodoloji, modelin tahminler oluşturmak için otoregresyon, hareketli ortalamalar ve mevsimsel farkları kullanarak eğilimleri belirlemesine olanak tanır.

[Otoregresif entegre hareketli ortalama (ARIMA) modelleri](/autoregressive-integrated-moving-average-arima),. Box-Jenkins modelinin bir şeklidir. ARIMA ve Box-Jenkins terimleri bazen birbirinin yerine kullanılır.

## Box-Jenkins Modelini Anlama

Box-Jenkins Modelleri, iş verileri ve gelecekteki güvenlik fiyatları dahil olmak üzere çeşitli beklenen veri noktalarını veya veri aralıklarını tahmin [etmek için kullanılır.](/forecasting)

Box-Jenkins Modeli iki matematikçi tarafından oluşturuldu: George Box ve Gwilym Jenkins. İki matematikçi, "Zaman Serisi Analizi: Tahmin ve Kontrol" adlı 1970 yayınında bu modeli oluşturan kavramları tartıştı.

Box-Jenkins Modelinin parametrelerinin tahminleri çok karmaşık olabilir. Bu nedenle, diğer zaman serisi regresyon modellerine benzer şekilde, en iyi sonuçlar tipik olarak programlanabilir yazılımların kullanılmasıyla elde edilecektir. Box-Jenkins Modeli ayrıca genellikle 18 ay veya daha kısa süreli kısa vadeli tahminler için en uygunudur.

##Box-Jenkins Metodolojisi

Box-Jenkins Modeli, bir tahmincinin programlanmış tahmin yazılımını kullanırken karşılaşacağı birkaç zaman serisi analiz modelinden biri olabilir. Çoğu durumda yazılım, tahmin edilecek [zaman serisi](/timeseries) verilerine dayalı olarak en uygun tahmin metodolojisini otomatik olarak kullanacak şekilde programlanacaktır . Box-Jenkins'in çoğunlukla kararlı ve düşük [volatiliteye](/volatility) sahip veri kümeleri için en iyi seçim olduğu bildiriliyor .

Box-Jenkins Modeli, verileri üç ilke kullanarak tahmin eder: otoregresyon, fark alma ve hareketli ortalama. Bu üç ilke sırasıyla p, d ve q olarak bilinir. her ilke Box-Jenkins analizinde kullanılır; birlikte, topluca ARIMA (p, d, q) olarak gösterilirler.

Otoregresyon (p) işlemi, verileri durağanlık düzeyi açısından test eder. Kullanılan veriler durağan ise, tahmin sürecini basitleştirebilir. Kullanılan veri durağan değilse, farkının alınması gerekecektir (d). Veriler ayrıca hareketli ortalama uyumu için test edilir (analiz sürecinin q kısmında yapılır). Genel olarak, verilerin ilk analizi, daha sonra bir tahmin geliştirmek için uygulanan parametreleri (p, d ve q) belirleyerek onu tahmin için hazırlar.

> Tek seferlik bir şok, Box-Jenkins modelinin sonraki değerlerini gelecekte sonsuza kadar etkileyecektir. Bu nedenle, finansal krizin mirası, günümüzün otoregresif modellerinde yaşamaya devam etmektedir.

>

## Otoregresif Entegre Hareketli Ortalama (ARIMA)

Box-Jenkins, bir bağımlı değişkenin gücünü diğer değişen değişkenlere göre ölçen bir tür otoregresif entegre hareketli ortalama (ARIMA) modelidir. Modelin amacı, gerçek değerler yerine serideki değerler arasındaki farkları inceleyerek gelecekteki menkul kıymetler veya finansal piyasa hareketlerini tahmin etmektir.

Bir ARIMA modeli, bileşenlerinin her biri aşağıdaki şekilde özetlenerek anlaşılabilir:

- [Otoregresyon (AR)](/autoregressive) : kendi gecikmeli veya önceki değerlerine göre gerileyen değişen bir değişkeni gösteren bir modeli ifade eder.

- Entegre (I): Zaman serilerinin durağan hale gelmesine izin vermek için ham gözlemlerin farkını temsil eder, yani veri değerlerinin yerini, veri değerleri ile önceki değerler arasındaki fark alır.

- [Hareketli ortalama (MA)](/movingaverage) : Bir gözlem ile gecikmeli gözlemlere uygulanan hareketli ortalama modelinden kalan bir hata arasındaki bağımlılığı içerir.

## Hisse Senedi Fiyatlarını Tahmin Etme

[hisse senedi](/stock) fiyatlarını tahmin etmektir . Bu analiz tipik olarak R yazılımı aracılığıyla oluşturulur ve kodlanır. Gelecekte belirli bir süre için tahmin edilen fiyatları oluşturmak için veri kümesine uygulanabilen logaritmik bir çıktıda sonuç analizi.

ARIMA modelleri, geçmiş değerlerin mevcut veya gelecekteki değerler üzerinde bir miktar kalıntı etkisi olduğu varsayımına dayanmaktadır. Örneğin, hisse senedi fiyatlarını tahmin etmek için bir ARIMA modeli kullanan bir yatırımcı, menkul kıymet için ne kadar teklif veya kabul edeceğine karar verirken, o hisse senedinin yeni alıcı ve satıcılarının son piyasa işlemlerinden etkilendiğini varsayacaktır.

Bu varsayım birçok farklı koşulda geçerli olsa da, her zaman doğru değildir. Örneğin, 2008 Mali Krizinden önceki yıllarda, yatırımcıların çoğu, birçok finans firması tarafından tutulan geniş [ipoteğe dayalı menkul kıymetler (MBS) portföylerinin yarattığı risklerin farkında değildi.](/mbs)

O zamanlarda, ABD finansal hisse senetlerinin performansını tahmin etmek için otoregresif bir model kullanan bir yatırımcı, o sektörde devam eden istikrarlı veya yükselen hisse senedi fiyatları eğilimini tahmin etmek için iyi bir nedene sahip olurdu. Bununla birlikte, birçok finansal kurumun yakın bir çöküş riskiyle karşı karşıya olduğu kamuoyuna duyurulduğunda, yatırımcılar aniden bu hisse senetlerinin son fiyatlarıyla daha az ve altta yatan risk maruziyetleriyle çok daha fazla ilgilenmeye başladılar.

Bu nedenle, piyasa, finansal stokları çok daha düşük bir seviyeye hızla yeniden değerlendirir, bu, otoregresif bir modeli tamamen şaşırtacak bir harekettir.

##Öne çıkanlar

- Otoregresif entegre hareketli ortalama (ARIMA) modelleri, Box-Jenkins modelinin bir şeklidir.

- Box-Jenkins Modeli, en çok 18 ay veya daha kısa zaman dilimlerinde tahmin yapmak için uygundur.

- Metodoloji, geçmişteki olayların gelecektekileri etkilediği varsayımına dayanmaktadır.

- Box-Jenkins Modeli, zaman serisi verileri üzerinde regresyon çalışmalarını kullanan bir tahmin metodolojisidir.

