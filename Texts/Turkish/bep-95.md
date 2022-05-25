---
keywords: Crypto
title: BEP-95
description: BEP-95. BEP-95, Binance Smart Chain&#39;e gerçek zamanlı bir yazma mekanizması sunan bir Binance Evrim Önerisidir. BNB belirteçlerini daha dinamik ve merkezi olmayan hale getirir.
---

# BEP-95
BEP-95, Binance Smart Chain'e gerçek zamanlı bir yazma mekanizması sunan bir Binance Evrim Önerisidir. BNB'nin tokenomiklerini daha da dinamik hale getirmek ve ağı daha fazla merkezsizleştirmek için tanıtıldı.

BEP-95 ile ağ, doğrulayıcıların topladığı her bloğun gaz ücretlerinin sabit bir oranını yakacaktır. Kesin oran, BSC'nin yönetişim mekanizmaları aracılığıyla belirlenecektir. Yakmalar, BSC'nin 100 milyon BNB hedef hedefine ulaşmasından sonra bile gerçekleşecek. BNB arzını azaltarak, madeni paranın fiyatına yukarı yönlü baskı uygulanır. BEP, alınan BNB delegelerinin ve doğrulayıcılarının miktarını da azaltabilir. Bununla birlikte, yukarı yönlü fiyat baskısı ile itibari değer de artabilir ve madeni paralardaki herhangi bir düşüşü dengeleyebilir.

Bunu teknik olarak uygulamak için ağ, her bloğun gaz ücretlerini toplar ve iki akıllı sözleşme arasında bölüştürür:

**bir. Sistem Ödül Sözleşmesi.** Gaz ücretlerinin 1/16'sı, maksimum 100 BNB'ye ulaşana kadar Sistem Ödül Sözleşmesine girecektir. Bu paralar zincirler arası paket sübvansiyonları olarak kullanılacaktır.

**2. ValidatorSet Sözleşmesi.** Diğer tüm gaz ücretleri ValidatorSet Sözleşmesine girecek ve Binance Chain aracılığıyla temsilciler ve doğrulayıcılarla günlük olarak paylaşılacaktır.

Bir yanık gerçekleştirmek için ValidatorSet Sözleşmesinin bir burnRatio değişkeni vardır. Her bloğu sonlandırdıktan sonra, bir doğrulayıcı, gaz ücretlerini akıllı sözleşmelere aktaran bir işlem imzalayacaktır. Para yatırma işlevi, basit formülü tetikleyen yazma mantığı içerir: burnRatio * gasFee. Bu miktar daha sonra yanma adresine aktarılacaktır. BurnRatio başlangıçta %10 olarak ayarlanacaktır.

BSC Doğrulayıcıları, burnRatio miktarını değiştirmek için teklifler aracılığıyla oy kullanabilecekler. Bu yönetişim mekanizması Binance Chain'de gerçekleşir ve herhangi bir topluluk üyesi, minimum 2.000 BNB depozito ile inceleme için bir teklif sunabilir. Tüm BNB bir teklifin arkasında ve oylamada bir karar verildikten sonra iade edilir. % 50'ye ulaşıldı ve değişiklik zincirler arası iletişim yoluyla hemen uygulanacaktır.

