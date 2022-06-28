---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Crypto,Strategy and Education
title: Karma Zaman Kilidi Sözleşmesi (HTLC)
description: Karma Zaman Kilidi Sözleşmesi (HTLC). Ödeme kanallarını değiştirebilen akıllı sözleşmeler oluşturmak için kullanılan özel bir özelliği ifade eder.
---

# Karma Zaman Kilidi Sözleşmesi (HTLC)
Hashed TimeLock Sözleşmesi (HTLC) terimi, ödeme kanallarını değiştirebilen [akıllı sözleşmeler oluşturmak için kullanılan özel bir özelliği ifade eder.](/smart-contract) Teknik olarak, HTLC özelliği, iki kullanıcı arasında zamana bağlı işlemlerin uygulanmasını sağlar. Uygulamada, bir HTLC işleminin alıcısı, belirli bir zaman çerçevesi (blok sayısı) içinde kriptografik bir kanıt sunarak ödemeyi onaylamalıdır. Alıcı ödemeyi kaybeder veya talep edemezse, para asıl gönderene iade edilecektir.

HTLC özelliği hem çift yönlü hem de yönlendirmeli ödeme kanallarında uygulanarak, herhangi bir aracıya güven duymadan çeşitli kanallar üzerinden güvenli fon transferine olanak tanır.

HTLC'yi standart kripto para birimi işlemlerinden ayıran iki temel unsur vardır:

- Hashlock: Belirli bir veri parçası kamuya açıklanıncaya kadar (kriptografik kanıt olarak) fonların harcanmasını kısıtlayan bir işlev. Bu tür kanıtlar, hashlock'un ön görüntüsü olarak da ifade edilebilir. Ön görüntü, hashlock'u oluşturmak ve daha sonra fonlarının kilidini açmak için kullanılan bilgi parçasıdır.

- Zaman Kilidi: Gelecekte belirli bir zamana (veya blok yüksekliğine) kadar para harcamasını kısıtlayan bir işlevdir. Bu, örneğin, CheckLockTimeVerify veya CheckSequenceVerify gibi işlevler kullanılarak Bitcoin'de elde edilebilir.

Bitcoin Lightning Network, Hashed Timelocked Sözleşmelerin en popüler kullanım durumları arasındadır. HTLC'yi ödeme kanallarına uygulayarak, fonlar, herhangi bir güven düzeyi gerektirmeden, birbirine bağlı ödeme kanalları aracılığıyla kullanıcıdan kullanıcıya aktarılabilir. Bu işlem ağ yönlendirme olarak bilinir. Bir ödeme kanalı aracılığıyla doğrudan bağlı olmasalar bile Alice'in Carol ile para alışverişi yapmasına olanak tanır. HTLC'ler, Alice'in fonlarını ağın diğer katılımcıları (örneğin, Bob) aracılığıyla Carol'a göndermesine olanak tanır - ve hashlock ve zaman kilidi özellikleri Bob'un fonları ele geçirmemesini sağlar.

HTLC'ler Lightning Network'te kullanılmasının yanı sıra zincirler arası [atomik takaslar](/atomic-swaps),. finansal akıllı sözleşmeler ve emanet ve çok daha fazlası gibi diğer bağlamlarda da faydalı olabilir.

## Öne Çıkanlar

- HTLC'leri kullanan ödemeler koşulludur ve bu nedenle blok zinciri işlemleri için verimlilik avantajları vardır. Bu özellik, HTLC'leri yıldırım ağı tarafından kullanılan temel bir araç haline getirir.

- Bu tür bir akıllı sözleşme, bir ödemenin alıcısının belirli bir süre içinde kabul etmesini veya kaybetmesini gerektirir.

- Karma bir zaman kilidi sözleşmesi (HTLC), kriptografik bir parola kullanan zamana dayalı bir emanet oluşturarak merkezi olmayan akıllı sözleşmelerde karşı taraf riskini azaltır.

## SSS

### Akıllı Sözleşme Maliyeti Ne Kadardır?

Ethereum blok zincirinde, akıllı bir sözleşme dağıtımı, Gwei'ye (daha düşük bir ether değeri) mal olan gaz alır. Sözleşmenin karmaşıklığına bağlı olarak, akıllı bir sözleşmeyi dağıtmak milyarlarca Gwei'ye mal olabilir. Basit bir takas gibi daha az karmaşık sözleşmeler çok daha ucuzdur.

### Akıllı Sözleşme Nedir?

Akıllı sözleşme, belirli koşullar karşılandığında yürütülen bir blok zincirinde depolanan bir programdır.

### Zaman Kilidi Sözleşmesi Nedir?

Zaman kilidi sözleşmesi, belirli bir zamanda bir işlem yürüten bir blok zincirine gömülü akıllı bir sözleşmedir. Hashed timelock sözleşmelerinde ve belirli ödeme sürelerinin gerekli olduğu ödeme kanallarında kullanılırlar.

### Bitcoin'in Akıllı Sözleşmeleri Var mı?

Başlangıçta, Bitcoin'in blok zinciri akıllı sözleşmeleri yürütemedi. Bununla birlikte, 2021'deki Taproot yükseltmesi, blok zincirinin işlemlerde akıllı sözleşmeleri kullanmasına izin verdi.

