---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Merkle Kökü (Kripto Para Birimi)
description: Bir Merkle kökü, bir blok zincirinde belirli bir blokta bulunan her bir işlem karması hakkında bilgi içerir.
---

# Merkle Kökü (Kripto Para Birimi)
## Merkle Kökü Nedir?

Bir Merkle kökü, bir [blok zinciri](/blockchain) ağındaki bir bloğun parçası olan tüm işlemlerin tüm karmalarının karma [değeridir .](/hash)

## Merkle Kökünü Anlama

Bir blok zinciri, birbiriyle bağlantılı çeşitli bloklardan oluşur (dolayısıyla blok zinciri adı). Bir karma ağacı veya [Merkle ağacı](/merkle-tree),. blok zinciri verilerini verimli ve güvenli bir şekilde kodlar. Blok zinciri verilerinin hızlı bir şekilde doğrulanmasını ve büyük miktarda verinin eşler arası blok zinciri ağındaki bir bilgisayar düğümünden diğerine hızlı bir şekilde taşınmasını sağlar.

Blockchain ağında meydana gelen her işlemin kendisiyle ilişkili bir hash'i vardır. Bununla birlikte, bu karmalar blokta sıralı bir sırayla değil, ağaç benzeri bir yapı biçiminde depolanır, öyle ki her bir karma, bir ebeveyn-alt ağaç benzeri ilişkiyi takip ederek ebeveynine bağlanır.

Belirli bir blokta depolanan çok sayıda işlem olduğundan, bloktaki tüm işlem özetleri de özetlenir ve bu da bir Merkle kökü ile sonuçlanır.

Örneğin, yedi işlem bloğunu düşünün. En düşük seviyede (yaprak seviyesi olarak adlandırılır), dört işlem karması olacaktır. Yaprak seviyesinin üzerindeki bir seviyede, her biri yaprak seviyesinde kendi altındaki iki hash'e bağlanacak olan iki işlem hash'i olacaktır. En üstte (ikinci seviye), kök olarak adlandırılan son işlem hash'i olacak ve altındaki iki hash'e bağlanacak (birinci seviyede).

Etkili bir şekilde, ağacın her bir düğümünün altındaki yalnızca iki düğüme bağlandığı ters bir ikili ağaç elde edersiniz (dolayısıyla "ikili ağaç" adı). En üstte bir kök hash'i vardır, bu da birinci seviyede iki hash'e bağlanır, her biri seviye üç'te (yaprak seviyesi) iki hash'e bağlanır ve yapı, işlem hashlerinin sayısına bağlı olarak devam eder.

<!--AAFEB15A7406E8DD3ABDD652D7C85823-->

Karma, en düşük düzeydeki (yaprak düzeyindeki) düğümlerde başlar ve dört karmanın tümü, kendisine birinci düzeyde bağlı düğümlerin karma değerine dahil edilir. Benzer şekilde, hashing birinci seviyede devam eder, bu da hash hash'lerinin daha yüksek seviyelere ulaşmasına yol açar, ta ki tek üst kök hash'e ulaşana kadar.

Bu kök karma, Merkle kökü olarak adlandırılır ve karmaların ağaç benzeri bağlantısı nedeniyle, blokta bulunan her bir işlem karmasıyla ilgili tüm bilgileri içerir. Bu blokta bulunan her şeyin doğrulanmasını sağlayan tek noktalı bir karma değer sunar.

Örneğin, biri 137 numaralı bloktan geldiğini iddia eden bir işlemi doğrulamak zorundaysa, blok #136 veya blok # gibi blok zincirindeki diğer bloklarda herhangi bir şeyi doğrulama konusunda endişelenmeden, yalnızca bloğun Merkle ağacını kontrol etmesi gerekir. 138.

<!--4861E8697637B7236BF11AA57D958059-->

Doğrulamayı daha da hızlandıran Merkle kökünü girin. Tüm ağaçla ilgili tüm bilgileri taşıdığı için, yalnızca bu işlem karmasını, kardeş düğümünü (varsa) doğrulaması ve ardından en üste ulaşana kadar yukarı doğru ilerlemesi gerekir.

Esasen, Merkle ağacı ve Merkle kök mekanizması, gerçekleştirilecek karma düzeylerini önemli ölçüde azaltarak daha hızlı doğrulama ve işlemlere olanak tanır.

##Öne çıkanlar

- Merkle kökleri, bitcoin ve eter gibi kripto para birimlerini korumak için gereken hesaplamanın merkezinde yer alır.

- Eşler arası ağdaki eşler arasında geçen veri bloklarının eksiksiz, hasarsız ve değiştirilmemiş olduğundan emin olmak için kripto para biriminde Merkle kökleri kullanılır.

- Bir Merkle kökü, bir Merkle ağacındaki verileri doğrulamanın basit bir matematiksel yoludur.

