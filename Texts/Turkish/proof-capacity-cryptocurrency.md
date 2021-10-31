---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Kapasite Kanıtı (Kripto Para Birimi)
description: Kapasite Kanıtı, blok zinciri ağındaki madencilik haklarına karar vermek için bir madencilik düğümünün sabit disk alanını kullanan bir fikir birliği mekanizmasıdır.
---

# Kapasite Kanıtı (Kripto Para Birimi)
## Kripto Para Birimleri için Kapasite Kanıtı (PoC) Nedir?

Kapasite kanıtı (PoC), ağdaki [madencilik](/bitcoin-mining) cihazlarının madencilik haklarına karar vermek ve işlemleri doğrulamak için mevcut sabit disk alanlarını kullanmalarına izin veren blok zincirlerde kullanılan bir [fikir birliği mekanizması](/consensus-mechanism-cryptocurrency) algoritmasıdır . Bu, madencilik cihazının hesaplama gücünü ( [prova of work](/proof-work) algoritmasında olduğu gibi) veya madencinin kripto para birimlerindeki hissesini ( [proof of stake](/proof-stake-pos) algoritmasında olduğu gibi) kullanmanın aksine.

## Kapasite Kanıtını Anlama

Kapasite kanıtı, iş kanıtı (PoW) sistemlerinde yüksek enerji tüketimi ve hisse kanıtı (PoS) sistemlerinde kripto para birimi biriktirme sorununa birçok alternatif çözümden biri olarak ortaya çıktı.

[blok zinciri ağındaki](/blockchain) düğümler olarak da bilinen madencilik cihazlarının, mevcut [kripto para birimlerini](/cryptocurrency) çıkarmak için sabit disklerindeki boş alanı kullanmalarına izin verir .

PoW sisteminde olduğu gibi blok başlığındaki sayıları tekrar tekrar değiştirmek ve çözüm değeri için tekrar tekrar karma yapmak yerine, PoC, madencilik faaliyeti başlamadan önce bile madencilik cihazının sabit diskinde olası çözümlerin bir listesini depolayarak çalışır.

Sabit disk ne kadar büyükse, sabit diskte saklanabilecek olası çözüm değerleri o kadar fazla olur, bir madencinin listesinden gerekli karma değeri eşleştirme şansı o kadar fazla olur ve bu da madencilik ödülünü kazanma şansını artırır.

Bir benzetme yapmak gerekirse, eğer piyango ödülleri kazanan biletteki en fazla sayıyı eşleştirmeye dayanıyorsa, daha uzun bir olası çözümler listesine sahip bir oyuncunun kazanma şansı daha yüksek olacaktır. Ek olarak, oyuncunun piyango bileti blok numaralarını tekrar tekrar kullanmasına izin verilir.

[Burstcoin](/burstcoin),. kapasite kanıtı sistemi kullanan bir kripto para birimidir. Bunu kullanan diğer paralar Storj, Chia ve SpaceMint'tir.

## PoC Nasıl Çalışır: Çizim ve Madencilik

Kapasite kanıtı protokolü, çizim ve madenciliği içeren iki aşamalı bir süreci içerir.

İlk olarak, sabit sürücü çizilir: tüm olası [nonce](/nonce) değerlerinin listesi, bir madenci hesabı da dahil olmak üzere verilerin tekrarlanan karma işlemiyle oluşturulur. Bu tür nonce'lerin her biri, 0'dan 8191'e kadar numaralandırılmış 8192 karma içerir. Tüm karmalar, "kepçe" şeklinde eşleştirilir, bu, bitişik karmaların bir çift oluşturacak şekilde birleştirildiği anlamına gelir. Örneğin, karma 0 ve 1, kepçe 0'ı, karma 2 ve 3, karma 1'i oluşturur vb.

İkinci adım, bir madencinin bir kepçe numarası hesapladığı gerçek madencilik alıştırmasını içerir. Örneğin, bir madenci madencilik faaliyetine başlar ve 38 numaralı bir kepçe oluşturursa, madenci daha sonra nonce 1'in 38 numaralı kepçesine gider ve bir son tarih değerini hesaplamak için o kepçenin verilerini kullanır.

İşlem, madencinin sabit diskinde tutulan her bir nonce için son tarihi hesaplamak için tekrarlanır. Tüm terminler hesaplandıktan sonra, madenci tarafından en az terminli olanı seçilir.

Bir son tarih, bir madencinin yeni bir blok oluşturmasına izin verilmeden önce son bloğun oluşturulmasından bu yana geçmesi gereken saniye cinsinden süreyi temsil eder. Bu süre içinde başka hiç kimse blok oluşturmadıysa, madenci bir blok oluşturabilir ve blok ödülünü talep edebilir.

Örneğin, X madenci en az 36 saniyelik bir son teslim tarihi belirlerse ve sonraki 36 saniye içinde başka hiçbir madenci bloğu taklit edemezse, X bir sonraki bloğu oluşturma ve ödüllendirilme şansını güvence altına alacaktır.

## Kapasite Kanıtının Artıları ve Eksileri

PoC, PoW ve PoS sistemlerine göre çeşitli avantajlara ve ayrıca aşağıdakileri içeren bazı önemli dezavantajlara sahiptir:

<h5><a href="">TTT</a></h5>

## Öne Çıkanlar

- PoC sisteminin ana faydası, iş kanıtı (PoW) ve hisse kanıtı (PoS) sistemlerine kıyasla verimliliğidir.

- Kapasite kanıtı üzerinde çalışan blok zincirleri arasında Storj, Burst, Chia ve SpaceMint bulunur.

- Kapasite kanıtı (PoC) kimlik doğrulama sistemleri, bir kripto para birimi karma sorununa çözüm depolamak için bir cihazın sabit diskinde boş alan kullanır.

