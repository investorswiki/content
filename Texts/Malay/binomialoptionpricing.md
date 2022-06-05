---
keywords: Trading,Options and Derivatives Trading,Options and Derivatives
title: Model Harga Opsyen Binomial
description: Model penentuan harga opsyen binomial ialah kaedah penilaian pilihan yang menggunakan prosedur berulang dan membenarkan spesifikasi nod dalam tempoh yang ditetapkan.
---

# Model Harga Opsyen Binomial
## Apakah Model Harga Opsyen Binomial?

Model penentuan harga opsyen binomial ialah kaedah [penilaian opsyen](/valuation) yang dibangunkan pada tahun 1979. Model penentuan harga opsyen binomial menggunakan prosedur berulang, membenarkan spesifikasi nod, atau titik dalam masa, dalam tempoh masa antara tarikh penilaian dan tarikh [tamat](/expiration-date) [tempoh opsyen](/expiration-date).

Model ini mengurangkan kemungkinan perubahan harga dan menghapuskan kemungkinan [arbitraj](/arbitrage). Contoh ringkas [pokok binomial](/binomial_tree) mungkin kelihatan seperti ini:

<!--87C9D3D79FF63D08201E6E848035602D-->

## Asas Model Harga Opsyen Binomial

Dengan model harga opsyen binomial, andaian ialah terdapat dua kemungkinan hasil—oleh itu, bahagian binomial model. Dengan model penetapan harga, kedua-dua hasil itu ialah naik atau turun. Kelebihan utama model penentuan harga opsyen binomial ialah model tersebut mudah secara matematik. Namun model ini boleh menjadi kompleks dalam model berbilang tempoh.

Berbeza dengan model [Black-Scholes](/blackscholes),. yang memberikan hasil berangka berdasarkan input, model binomial membenarkan pengiraan aset dan pilihan untuk berbilang tempoh bersama-sama dengan julat hasil yang mungkin untuk setiap tempoh (lihat di bawah).

Kelebihan paparan berbilang tempoh ini ialah pengguna boleh menggambarkan perubahan dalam harga aset dari satu tempoh ke satu tempoh dan menilai pilihan berdasarkan keputusan yang dibuat pada masa yang berbeza. Untuk [pilihan](/americanoption) yang berpangkalan di AS , yang boleh dilaksanakan pada bila-bila masa sebelum [tarikh tamat tempoh](/expirationdate),. model binomial boleh memberikan gambaran tentang bila menggunakan pilihan itu mungkin dinasihatkan dan bila ia perlu dipegang untuk tempoh yang lebih lama.

Dengan melihat [pokok nilai binomial](/binomial_tree),. seorang peniaga boleh menentukan terlebih dahulu apabila keputusan mengenai sesuatu [latihan](/exercise) mungkin berlaku. Jika opsyen mempunyai nilai positif, terdapat kemungkinan untuk dilaksanakan manakala, jika opsyen mempunyai nilai kurang daripada sifar, ia harus dipegang untuk tempoh yang lebih lama.

## Mengira Harga dengan Model Binomial

Kaedah asas pengiraan model opsyen binomial adalah menggunakan kebarangkalian yang sama setiap tempoh untuk kejayaan dan kegagalan sehingga pilihan tamat. Walau bagaimanapun, seorang peniaga boleh menggabungkan kebarangkalian yang berbeza untuk setiap tempoh berdasarkan maklumat baharu yang diperolehi seiring dengan berlalunya masa.

Pokok binomial ialah alat yang berguna apabila menetapkan harga [pilihan Amerika](/americanoption) dan pilihan [terbenam](/embeddedoption). Kesederhanaannya adalah kelebihan dan kekurangannya pada masa yang sama. Pokok ini mudah untuk dimodelkan secara mekanikal, tetapi masalahnya terletak pada kemungkinan nilai aset asas yang boleh diambil dalam satu tempoh masa. Dalam model pokok binomial, aset asas hanya boleh bernilai tepat satu daripada dua nilai yang mungkin, yang tidak realistik, kerana aset boleh bernilai sebarang bilangan nilai dalam mana-mana julat tertentu.

Sebagai contoh, mungkin terdapat peluang 50/50 bahawa harga aset asas boleh meningkat atau menurun sebanyak 30 peratus dalam satu tempoh. Walau bagaimanapun, untuk tempoh kedua, kebarangkalian harga aset asas akan meningkat mungkin meningkat kepada 70/30.

Contohnya, jika pelabur menilai [telaga minyak](/exploratory-well),. pelabur itu tidak pasti nilai telaga minyak itu, tetapi terdapat kemungkinan 50/50 harga akan naik. Jika harga minyak naik dalam Tempoh 1 menjadikan telaga minyak lebih berharga dan [asas pasaran](/fundamentals) kini menunjukkan kenaikan berterusan harga minyak, kebarangkalian kenaikan harga selanjutnya mungkin 70 peratus. Model binomial membolehkan fleksibiliti ini; model Black-Scholes tidak.

<!--94DBA31F9D3220C6052579D485B8A416-->

## Contoh Dunia Sebenar Model Harga Opsyen Binomial

Contoh ringkas bagi [pokok binomial](/binomial_tree) hanya mempunyai satu langkah. Andaikan terdapat saham yang berharga $100 sesaham. Dalam satu bulan, harga saham ini akan naik sebanyak $10 atau turun sebanyak $10, mewujudkan keadaan ini:

- **Harga saham** = $100

- **Harga saham dalam satu bulan (keadaan atas)** = $110

- **Harga saham dalam satu bulan (keadaan bawah)** = $90

Seterusnya, andaikan terdapat pilihan panggilan tersedia pada saham ini yang tamat tempoh dalam satu bulan dan mempunyai harga mogok sebanyak $100. Dalam keadaan atas, pilihan panggilan ini bernilai $10 dan dalam keadaan bawah, ia bernilai $0. Model binomial boleh mengira berapa harga pilihan panggilan sepatutnya hari ini.

Untuk tujuan penyederhanaan, andaikan pelabur membeli setengah bahagian saham dan menulis atau menjual satu pilihan panggilan. Jumlah pelaburan hari ini ialah harga separuh saham ditolak harga pilihan, dan kemungkinan hasil pada akhir bulan ialah:

- **Kos hari ini** = $50 - harga pilihan

- **Nilai portfolio** (keadaan atas) = $55 - maks ($110 - $100, 0) = $45

- **Nilai portfolio** (keadaan bawah) = $45 - maks($90 - $100, 0) = $45

Bayaran portfolio adalah sama tidak kira bagaimana harga saham bergerak. Memandangkan keputusan ini, dengan mengandaikan tiada peluang arbitraj, pelabur harus memperoleh kadar bebas risiko sepanjang bulan itu. Kos hari ini mestilah sama dengan bayaran yang didiskaun pada kadar bebas risiko selama satu bulan. Persamaan yang perlu diselesaikan ialah:

- **Harga opsyen** = $50 - $45 xe ^ (-kadar bebas risiko x T), dengan e ialah pemalar matematik 2.7183.

Dengan mengandaikan kadar bebas risiko ialah 3% setahun, dan T bersamaan dengan 0.0833 (satu dibahagikan dengan 12), maka harga pilihan panggilan hari ini ialah $5.11.

Model penetapan harga opsyen binomial memberikan dua kelebihan untuk penjual opsyen berbanding model Black-Scholes. Yang pertama ialah kesederhanaannya, yang membolehkan lebih sedikit ralat dalam aplikasi komersial. Yang kedua ialah operasi berulangnya, yang melaraskan harga tepat pada masanya untuk mengurangkan peluang pembeli untuk melaksanakan strategi arbitraj.

Sebagai contoh, kerana ia menyediakan aliran penilaian untuk [derivatif](/derivative) untuk setiap nod dalam jangka masa tertentu, ia berguna untuk menilai derivatif seperti pilihan Amerika—yang boleh dilaksanakan pada bila-bila masa antara tarikh pembelian dan tarikh tamat tempoh. Ia juga jauh lebih mudah daripada model harga lain seperti model Black-Scholes.

##Sorotan

- Model ini intuitif dan digunakan lebih kerap dalam amalan berbanding model Black-Scholes yang terkenal.

- Dengan model, terdapat dua kemungkinan hasil dengan setiap lelaran—pergerakan ke atas atau ke bawah yang mengikuti pokok binomial.

- Model penentuan harga opsyen binomial menilai pilihan menggunakan pendekatan berulang menggunakan berbilang tempoh untuk menilai pilihan Amerika.

