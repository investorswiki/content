---
keywords: Crypto
title: çiçek filtresi
description: Çiçek Filtresi. Belirli bir öğenin bir dizi öğenin parçası olup olmadığını kullanıcıya bildirmek için kullanılabilecek bir veri yapısı
---

# çiçek filtresi
Bloom filtresi, kullanıcıya belirli bir öğenin bir kümenin parçası olup olmadığını bildirmek için kullanılabilen bir veri yapısıdır. Bir elemanın kümede olup olmadığını kesin olarak söyleyemese de, elemanın olmadığını kesin olarak söyleyebilir.

1970 yılında Burton Howard Bloom tarafından oluşturulan Bloom filtreleri, alan kullanımındaki verimlilikleri nedeniyle bir dizi uygulama için çekici bir tekliftir. Bazı kripto para birimlerinde (en önemlisi Bitcoin), Basitleştirilmiş Ödeme Doğrulaması veya SPV'de ayrılmaz bir rol oynarlar.

Bir SPV istemcisi kullanırken, kullanıcılar tam bir düğüm çalıştırmadan Bitcoin ağı ile etkileşime girebilir. Tam düğümler, akıllı telefonlar gibi düşük güçlü cihazlarda çalıştırılmalarını zorlaştıran belirli depolama ve hesaplama gereksinimleriyle birlikte gelir. Diğer yandan SPV istemcileri, kullanıcının cüzdan(lar)ıyla ilgili bilgiler için tam düğümleri sorgular.

Bu verileri kullanıcıya aktarmanın en basit çözümü, tüm düğümleri müşterinin anahtarlarından haberdar etmek ve böylece onlara yalnızca ilgili işlemlerin gönderilmesini sağlamak olacaktır. Açıkçası, müşterinin mahremiyeti feda edileceğinden, bu bir standart altı çözümdür. Öte yandan, tüm işlemleri yalnızca çoğunu atmak için indirmek bant genişliği kaybı olacaktır. Bloom filtrelerini girin.

Örneklendirelim. Bir müşterinin, Alice'in, tam bir düğüm çalıştıran Bob'un farkında olmasını istemediği yüksek değerli bir işlemi olduğunu varsayalım. 10x1'lik bir ızgara olarak göstereceğimiz bir Bloom filtresi oluşturuyor:

İlgilendiği işlem verilerini 0 ile 9 arasında iki sayı veren iki farklı hash fonksiyonundan geçirir. Onlara 4 ve 7 diyelim. Filtreyi Bob'a gönderir.

Bu ızgaraya baktığınızda, Alice'in filtreye hangi verileri ilettiği hakkında hiçbir fikriniz yok. Verilerin bulunduğu bir kümeniz olsaydı, onu hash edebilir ve filtreyle karşılaştırabilirsiniz – eğer bir eşleşme varsa, bunun Alice'in istediği bilgi olma olasılığı vardır.

Aynı zamanda, 4 ve 7 ile eşlenecek birçok girdi olması muhtemeldir, bu nedenle Bob, Alice'in verilerin hangi kısmıyla ilgilendiğini belirleyemez. Tüm eşleşmeleri geri veriyor ve Alice onları kendi tarafında filtreliyor.

Bu, elbette, büyük bir basitleştirmedir, ancak şu konsepti ortaya koymaktadır: Bloom filtreleri, müşterinin gerçek çıkarlarını gizler. Bu mükemmel bir yöntem değil (hâlâ mahremiyetiyle ilgili endişeler var), ancak bir düğüme yönelik korumasız bir istek üzerinde bir gelişme.

