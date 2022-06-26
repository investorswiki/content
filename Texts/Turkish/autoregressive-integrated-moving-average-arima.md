---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: Otoregresif Entegre Hareketli Ortalama (ARIMA)
description: Otoregresif entegre hareketli ortalama (ARIMA), gelecekteki eğilimleri tahmin etmek için zaman serisi verilerini kullanan istatistiksel bir analiz modelidir.
---

# Otoregresif Entegre Hareketli Ortalama (ARIMA)
## Otoregresif Entegre Hareketli Ortalama (ARIMA) Nedir?

veri setini daha iyi anlamak veya gelecekteki eğilimleri tahmin etmek için [zaman serisi verilerini](/timeseries) kullanan istatistiksel bir analiz modelidir .

Bir istatistiksel model, geçmiş değerlere dayalı olarak gelecekteki değerleri tahmin ederse, otoregresiftir. Örneğin, bir ARIMA modeli, bir hisse senedinin geçmiş performansına dayalı olarak gelecekteki fiyatlarını tahmin etmeye veya geçmiş dönemlere dayalı olarak bir şirketin kazançlarını tahmin etmeye çalışabilir.

## Otoregresif Entegre Hareketli Ortalamayı (ARIMA) Anlama

Bir otoregresif entegre hareketli ortalama modeli, bir bağımlı değişkenin gücünü diğer değişen değişkenlere göre ölçen bir [regresyon analizi biçimidir.](/regression) Modelin amacı, gerçek değerler yerine serideki değerler arasındaki farkları inceleyerek gelecekteki menkul kıymetler veya finansal piyasa hareketlerini tahmin etmektir.

Bir ARIMA modeli, bileşenlerinin her biri aşağıdaki şekilde özetlenerek anlaşılabilir:

- [Otoregresyon (AR)](/autoregressive) : kendi gecikmeli veya önceki değerlerine göre gerileyen değişen bir değişkeni gösteren bir modeli ifade eder.

- **Entegre (I):** zaman serisinin durağan hale gelmesine izin vermek için ham gözlemlerin farkını temsil eder (yani, veri değerleri, veri değerleri ile önceki değerler arasındaki farkla değiştirilir).

- [Hareketli ortalama (MA)](/movingaverage) : Bir gözlem ile gecikmeli gözlemlere uygulanan hareketli ortalama modelinden kalan hata arasındaki bağımlılığı içerir.

## ARIMA Parametreleri

ARIMA'daki her bileşen, standart bir gösterime sahip bir parametre olarak işlev görür. ARIMA modelleri için standart bir gösterim, kullanılan ARIMA modelinin türünü belirtmek için tamsayı değerlerinin parametrelerin yerine geçtiği p, d ve q ile ARIMA olacaktır. Parametreler şu şekilde tanımlanabilir:

- **p**: modeldeki gecikme gözlemlerinin sayısı; gecikme sırası olarak da bilinir.

- **d**: ham gözlemlerin fark edilme sayısı; farklılık derecesi olarak da bilinir.

- q: hareketli ortalama penceresinin boyutu; hareketli ortalamanın sırası olarak da bilinir.

[Doğrusal](/nonlinear-regression) bir regresyon modelinde, örneğin, terimlerin sayısı ve türü dahil edilir. Parametre olarak kullanılabilen 0 değeri, modelde belirli bir bileşenin kullanılmaması gerektiği anlamına gelir. Bu şekilde, ARIMA modeli, bir ARMA modelinin veya hatta basit AR, I veya MA modellerinin işlevini yerine getirmek için oluşturulabilir.

> ARIMA modelleri karmaşık olduğundan ve çok büyük veri kümelerinde en iyi şekilde çalıştığından, bunları hesaplamak için bilgisayar algoritmaları ve makine öğrenme teknikleri kullanılır.

>

## Otoregresif Entegre Hareketli Ortalama (ARIMA) ve Durağanlık

Otoregresif entegre hareketli ortalama modelinde, durağan hale getirmek için veriler farklılaştırılır. Durağanlığı gösteren bir model, verilerde zaman içinde sabitlik olduğunu gösteren bir modeldir. Çoğu ekonomik veri ve piyasa verisi eğilimleri gösterir, bu nedenle farklılaştırmanın amacı herhangi bir eğilimi veya mevsimsel yapıyı ortadan kaldırmaktır.

[Mevsimsellik](/seasonality) veya veriler bir takvim yılı boyunca tekrar eden düzenli ve öngörülebilir modeller gösterdiğinde, regresyon modelini olumsuz etkileyebilir. Bir eğilim ortaya çıkarsa ve durağanlık belirgin değilse, süreç boyunca birçok hesaplama büyük bir verimlilikle yapılamaz.

> Bir kerelik bir şok, bir ARIMA modelinin sonraki değerlerini geleceğe sonsuza kadar etkileyecektir. Bu nedenle, finansal krizin mirası, günümüzün otoregresif modellerinde yaşamaya devam etmektedir.

>

## Özel Hususlar

ARIMA modelleri, geçmiş değerlerin mevcut veya gelecekteki değerler üzerinde bir miktar kalıntı etkisi olduğu varsayımına dayanmaktadır. Örneğin, hisse senedi fiyatlarını tahmin etmek için bir ARIMA modeli kullanan bir yatırımcı, menkul kıymet için ne kadar teklif veya kabul edeceğine karar verirken, o hisse senedinin yeni alıcı ve satıcılarının son piyasa işlemlerinden etkilendiğini varsayacaktır.

Bu varsayım birçok durumda geçerli olsa da, durum her zaman böyle değildir. Örneğin, 2008 Mali Krizinden önceki yıllarda, yatırımcıların çoğu, birçok finans firması tarafından tutulan geniş [ipoteğe dayalı menkul kıymetler (MBS) portföylerinin yarattığı risklerin farkında değildi.](/mbs)

O zamanlarda, ABD finansal hisse senetlerinin performansını tahmin etmek için otoregresif bir model kullanan bir yatırımcı, o sektörde devam eden istikrarlı veya yükselen hisse senedi fiyatları eğilimini tahmin etmek için iyi bir nedene sahip olacaktı. Bununla birlikte, birçok finansal kurumun yakın bir çöküş riskiyle karşı karşıya olduğu kamuoyuna duyurulduğunda, yatırımcılar aniden bu hisse senetlerinin son fiyatlarıyla daha az ve altta yatan risk maruziyetleriyle çok daha fazla ilgilenmeye başladılar. Bu nedenle, piyasa, finansal stokları çok daha düşük bir seviyeye hızla yeniden değerlendirir, bu, otoregresif bir modeli tamamen şaşırtacak bir harekettir.

## Sıkça Sorulan Sorular

### ARIMA ne için kullanılır?

ARIMA, geçmiş zaman serilerine dayalı olarak gelecekteki sonuçları tahmin etmek veya tahmin etmek için bir yöntemdir. Geçmiş veri noktalarının gelecekteki veri noktalarını etkilediği istatistiksel seri korelasyon kavramına dayanır.

### Otoregresif ve hareketli ortalama modelleri arasındaki farklar nelerdir?

ARIMA, otoregresif özellikleri hareketli ortalamalarınkilerle birleştirir. Örneğin, bir AR(1) otoregresif süreci, mevcut değerin hemen önceki değere dayandığı bir süreç iken, bir AR(2) süreci, mevcut değerin önceki iki değere dayandığı bir süreçtir. Hareketli ortalama, aykırı değerlerin etkisini yumuşatmak için tam veri kümesinin farklı alt kümelerinin bir dizi ortalamasını oluşturarak veri noktalarını analiz etmek için kullanılan bir hesaplamadır. Bu tekniklerin birleşiminin bir sonucu olarak, ARIMA modelleri, tahminler yaparken eğilimleri, döngüleri, mevsimselliği ve diğer statik olmayan veri türlerini hesaba katabilir.

### ARIMA tahmini nasıl çalışır?

ARIMA tahmini, ilgilenilen değişken için zaman serisi verilerinin eklenmesiyle elde edilir. İstatistiksel yazılım, verilere uygulanacak uygun gecikme sayısını veya fark miktarını belirleyecek ve durağanlığı kontrol edecektir. Daha sonra, genellikle çoklu doğrusal regresyon modeline benzer şekilde yorumlanan sonuçları çıkaracaktır.

##Öne çıkanlar

- Otoregresif entegre hareketli ortalama (ARIMA) modelleri, geçmiş değerlere dayalı olarak gelecekteki değerleri tahmin eder.

- ARIMA, zaman serisi verilerini yumuşatmak için gecikmeli hareketli ortalamaları kullanır.

- Gelecekteki menkul kıymet fiyatlarını tahmin etmek için teknik analizde yaygın olarak kullanılırlar.

- Otoregresif modeller, dolaylı olarak geleceğin geçmişe benzeyeceğini varsayar.

- Bu nedenle, finansal krizler veya hızlı teknolojik değişim dönemleri gibi belirli piyasa koşullarında yanlış olduklarını kanıtlayabilirler.

