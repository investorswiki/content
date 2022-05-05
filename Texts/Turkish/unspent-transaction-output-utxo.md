---
keywords: Crypto
title: Harcanmamış İşlem Çıktısı (UTXO)
description: Harcanmamış İşlem Çıktısı (UTXO). Bir işlemde yaratılan ve fonları harcamak için gelecekteki bir işlemde referans alınması gereken bir çıktı.
---

# Harcanmamış İşlem Çıktısı (UTXO)
Harcanmamış bir işlem çıktısı (UTXO), yeni bir işlemde girdi olarak kullanılabilecek bir işlem çıktısını ifade eder. Özünde, UTXO'lar her blok zinciri işleminin nerede başladığını ve bittiğini tanımlar. UTXO modeli, Bitcoin ve diğer birçok kripto para biriminin temel bir unsurudur.

Diğer bir deyişle kripto para işlemleri girdi ve çıktılardan oluşmaktadır. Her işlem yapıldığında, kullanıcı girdi(ler) olarak hizmet etmek için bir veya daha fazla UTXO alır. Daha sonra, kullanıcı, girdiler üzerindeki mülkiyeti onaylamak için dijital imzasını sağlar ve sonunda çıktılarla sonuçlanır. Tüketilen UTXO'lar artık "harcanmış" olarak kabul edilir ve artık kullanılamaz. Bu arada, işlemden elde edilen çıktılar, daha sonra yeni bir işlemde harcanabilecek yeni UTXO'lar haline gelir.

Bu muhtemelen bir örnekle daha iyi açıklanmıştır. Alice'in cüzdanında 0.45 BTC var. Bu, kavramsallaştırabileceğimiz gibi bir madalyonun bir parçası değil. Daha çok UTXO'ların bir koleksiyonudur. Spesifik olarak, 0,4 BTC ve 0,05 BTC değerinde iki UTXO – geçmiş işlemlerden çıktılar. Şimdi Alice'in Bob'a 0,3 BTC'lik bir ödeme yapması gerektiğini düşünelim.

Buradaki tek seçeneği 0,4 BTC birimini parçalamak ve Bob'a 0,3 BTC ve kendisine 0,1 BTC göndermek. Normalde madencilik ücretleri nedeniyle 0,1 BTC'den daha azını geri alırdı, ancak madenciyi basitleştirip bırakalım.

Alice, esasen ağa şunu söyleyen bir işlem yaratır: Girdi olarak 0,4 BTC UTXO'mu alın, bölün, 0,3 BTC'yi Bob'un adresine gönderin ve 0,1 BTC'yi adresime iade edin. 0,4 BTC artık harcanmış bir çıktıdır ve yeniden kullanılamaz. Bu arada, iki yeni UTXO oluşturuldu (0,3 BTC ve 0,1 BTC).

Bu örnekte bir UTXO'yu ayırdığımızı unutmayın, ancak Alice 0,42 BTC ödemek zorunda olsaydı, 0,4 BTC'sini başka bir 0,05 BTC ile kolayca birleştirip 0,42 BTC değerinde bir UTXO üretebilir ve kendisine 0,03 BTC geri verebilirdi.

Özetle, UTXO modeli, herhangi bir zamanda nerede olan madeni paraları takip etmek için protokolün mekanizması olarak hizmet eder. Bir anlamda, çeklere çok benzerler: belirli kullanıcılara (veya daha doğrusu genel [adreslerine](/address) ) yöneliktirler. UTXO'lar kısmen harcanamaz - bunun yerine, eskisinden yeni çekler oluşturulmalı ve buna göre iletilmelidir.

