---
keywords: Crypto
title: yarıya indirmek
description: Yarıya indirmek. Bir kripto varlığın blok ödülü eskisinin yarısına düştüğünde; bu, azalan bir ihraç oranı oluşturmak için kullanılır.
---

# yarıya indirmek
Kripto para birimi alanında, yarılanma terimi, yeni madeni paraların ihraç oranını azaltan bir süreci ifade eder. Daha doğrusu halving, madencilere sağlanan blok sübvansiyonunun dönemsel olarak azaltılmasıdır. Yarılanma, bir kripto varlığının sonunda [maksimum arzına](/maximum-supply) ulaşılana kadar sabit bir ihraç oranını izlemesini sağlar.

[blok ödülünün bir parçası olarak](/block-reward) (blok sübvansiyonu artı işlem ücretlerinden oluşan) haber paraları sürekli olarak üretiliyor . Bu nedenle, bir madenci her başarılı bir şekilde yeni bir [blok](/block) "keşfettiğinde" ve doğruladığında , çalışmalarının karşılığı olarak yeni oluşturulan paraları kazanırlar.

[Madencilik süreci](/mining),. sisteme yeni [Bitcoinleri](/bitcoin) sokan şeydir ve bu, öngörülebilir ve kontrollü bir hızda yapılır. Ortalama olarak her 10 dakikada bir yeni Bitcoin blokları çıkarılır ve blok sübvansiyonu kontrollü bir azalma oranını takip eder. Buna göre, yarılanma, blok sübvansiyonunun her 210.000 blokta (yaklaşık dört yılda bir) %50 oranında azalmasını sağlayan şeydir.

[Genesis bloğundan](/genesis-block) başlayarak , Bitcoin'in blok sübvansiyonu başlangıçta 50 BTC olarak belirlendi. Ardından, 2012'de 25 BTC'ye ve 2016'da 12,5 BTC'ye düşürüldü. Aşağıdaki yarılanmanın Mayıs 2020 civarında gerçekleşmesi ve blok sübvansiyonunun 6.25 BTC'ye düşürülmesi bekleniyor. 32 halving gerçekleştiğinde süreç durur ve daha fazla Bitcoin oluşturulmaz. Bu noktada maksimum 21 milyon BTC arzına ulaşılacak.

[Bitcoin Halving ile birlikte takip edin](/halving)

Yarılanma, Bitcoin protokolünün önemli bir parçasıdır ve kod açık kaynaklı olduğu için herkes onu görebilir. Örneğin, Bitcoin Core uygulaması [GitHub'da mevcuttur](/github) ve blok sübvansiyonunu tanımlayan kod bölümlerinden biri şöyle görünür:

CAmount GetBlockSubsidy(int nHeight, const Consensus::Params&consensusParams)

{

int halvings = nHeight / konsensüsParams.nSubsidyHalvingInterval;

// Sağa kaydırma tanımsız olduğunda blok ödülünü sıfıra zorla.

if (yarılar >= 64)

0 döndür;

CAmount nSubsidy = 50 * COIN;

// Sübvansiyon her 210.000 blokta yarı yarıya kesilir ve bu yaklaşık her 4 yılda bir gerçekleşir.

nSübvansiyon >>= yarılanmalar;

iade nSubsidy;

}

