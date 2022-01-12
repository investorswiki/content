---
keywords: Crypto
title: Aday Blok
description: Aday Blok. Blok ödüllerini almak için blok zincirine eklemek üzere bir madencilik düğümü (madenci) tarafından oluşturulan geçici bir blok.
---

# Aday Blok
Birkaç kelimeyle, aday blok, bir madencilik düğümünün (madenci) blok ödülünü almak için madenciliğe çalıştığı bir bloktur. Bu nedenle aday blok, ağ tarafından doğrulanacak veya atılacak geçici bir blok olarak tanımlanabilir. Madenciler bir sonraki bloğu doğrulamak ve blok zincirine eklemek için birbirleriyle rekabet eder, ancak önce madencilik yarışmasına katılmak için bir aday blok oluşturmaları gerekir.

Aday bloklar, bellek havuzundan birden fazla onaylanmamış işlemi toplayıp düzenleyerek madenciler tarafından oluşturulur. İşlemler daha sonra , sonunda bir Merkle kökü (veya kök karması) üretecek olan bir [Merkle ağaç yapısı oluşturmak için karma hale getirilir.](/merkle-tree) Merkle kökü, o ağacın önceki tüm karmalarını ve dolayısıyla o belirli bloğa dahil edilen tüm işlemleri temsil eden tek bir karmadır.

Kök hash - önceki bloğun hash'i ve [nonce adı verilen rasgele bir sayı ile birlikte](/nonce) - daha sonra bloğun başlığına konur. Blok başlığı daha sonra madenci tarafından hash edilir ve bu bileşenlere (kök hash, önceki bloğun hash'i ve nonce) artı birkaç diğer öğeye dayalı bir çıktı üretilir. Ortaya çıkan çıktı, blok hash'idir ve yeni oluşturulan bloğun (aday blok) benzersiz bir tanımlayıcısı olarak hizmet edecektir.

Geçerli olarak kabul edilmesi için, çıktının (blok hash) belirli sayıda sıfırla (protokol tarafından tanımlanan bir hedef değerden daha az) başlaması gerekir. Bu, madencilik düğümlerinin, sonunda geçerli bir blok karma üretilene kadar farklı nonce değerleriyle sayısız karma işlevi gerçekleştirmesi gerektiğinden, madencilik sürecinin birden fazla denemeye (deneme yanılma) dayandığı anlamına gelir. Üretilen blok hash, madencinin işini yaptığını kanıtlayan şeydir (dolayısıyla Proof of Work).

Bir madenci geçerli bir blok karması bulduktan sonra, aday blokları ağın geri kalan düğümlerine yayınlanacak ve bu da karmanın gerçekliğini doğrulayacaktır. Her şey yolundaysa, aday blok blok zincirine kaydedilecektir. Bu noktada, her doğrulama düğümü, en son çıkarılan bloğu yansıtmak için blok zinciri verilerinin kopyasını günceller ve madenci blok ödülünü alır.

