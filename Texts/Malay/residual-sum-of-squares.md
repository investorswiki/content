---
keywords: Investing,Fundamental Analysis
title: Jumlah Baki Kuasa Dua (RSS)
description: Jumlah sisa kuasa dua (RSS) ialah teknik statistik yang digunakan untuk mengukur varians dalam set data yang tidak dijelaskan oleh model regresi.
---

# Jumlah Baki Kuasa Dua (RSS)
## Apakah Jumlah Baki Kuasa Dua (RSS)?

Jumlah kuasa dua baki (RSS) ialah teknik statistik yang digunakan untuk mengukur jumlah [varians](/variance) dalam set data yang tidak dijelaskan oleh model regresi itu sendiri. Sebaliknya, ia menganggarkan varians dalam baki, atau [istilah ralat](/errorterm).

[Regresi linear](/regression) ialah pengukuran yang membantu menentukan kekuatan hubungan antara pembolehubah bersandar dan satu atau lebih faktor lain, yang dikenali sebagai pembolehubah bebas atau penjelasan.

## Memahami Jumlah Baki Kuasa Dua

Secara umum, [jumlah kuasa dua](/sum-of-squares) ialah teknik statistik yang digunakan dalam analisis regresi untuk menentukan serakan titik data. Dalam analisis regresi, matlamatnya adalah untuk menentukan sejauh mana siri data boleh dipasang pada fungsi yang mungkin membantu menjelaskan cara siri data dijana. Jumlah kuasa dua digunakan sebagai cara matematik untuk mencari fungsi yang [paling sesuai](/line-of-best-fit) (berbeza paling sedikit) daripada data.

RSS mengukur jumlah ralat yang tinggal di antara fungsi regresi dan set data selepas model dijalankan. Angka RSS yang lebih kecil mewakili fungsi regresi yang sesuai dengan data.

RSS, juga dikenali sebagai jumlah sisa kuasa dua, pada asasnya menentukan sejauh mana model regresi menerangkan atau mewakili data dalam model.

## Cara Mengira Jumlah Baki Kuasa Dua

>

> RSS = **∑**^n^~i=1~ (**yi** - **f**(**xi**))^2^

>

>

> Di mana:

>

>

> y~i~ = nilai i^th^ pembolehubah yang akan diramalkan

>

>

> **f**(x~i~) = nilai ramalan y~i~

>

>

> n = had atas penjumlahan

>

## Jumlah Baki Kuasa Dua (RSS) lwn. Ralat Standard Baki (RSE)

Ralat piawai sisa (RSE) ialah istilah statistik lain yang digunakan untuk menerangkan perbezaan [sisihan piawai](/standarddeviation) bagi nilai yang diperhatikan berbanding nilai yang diramalkan seperti yang ditunjukkan oleh mata dalam analisis regresi. Ia adalah ukuran [kebaikan](/goodness-of-fit) yang boleh digunakan untuk menganalisis sejauh mana set titik data sesuai dengan model sebenar.

RSE dikira dengan membahagikan RSS dengan bilangan pemerhatian dalam sampel kurang 2, dan kemudian mengambil punca kuasa dua: RSE = [RSS/(n-2)]^1/2^

## Pertimbangan Khas

Pasaran kewangan semakin menjadi lebih didorong secara kuantitatif; oleh itu, untuk mencari kelebihan, ramai pelabur menggunakan teknik statistik lanjutan untuk membantu dalam keputusan mereka. Data besar, pembelajaran mesin dan aplikasi kecerdasan buatan memerlukan lagi penggunaan sifat statistik untuk membimbing strategi pelaburan kontemporari. Jumlah baki kuasa dua—atau statistik RSS—adalah salah satu daripada banyak sifat statistik yang menikmati kebangkitan semula.

Model statistik digunakan oleh pelabur dan pengurus portfolio untuk menjejaki harga pelaburan dan menggunakan data tersebut untuk meramalkan pergerakan masa hadapan. Kajian itu—yang dipanggil analisis regresi—mungkin melibatkan menganalisis hubungan dalam pergerakan harga antara komoditi dan saham syarikat yang terlibat dalam mengeluarkan komoditi itu.

> Mencari jumlah baki kuasa dua (RSS) dengan tangan boleh menjadi sukar dan memakan masa. Kerana ia melibatkan banyak penolakan, kuasa dua dan penjumlahan, pengiraan boleh terdedah kepada ralat. Atas sebab ini, anda boleh memutuskan untuk menggunakan perisian, seperti Excel, untuk melakukan pengiraan.

>

Mana-mana model mungkin mempunyai variasi antara nilai yang diramalkan dan hasil sebenar. Walaupun varians mungkin dijelaskan oleh analisis regresi, RSS mewakili varians atau ralat yang tidak dijelaskan.

Memandangkan fungsi regresi yang cukup kompleks boleh dibuat agar sesuai dengan hampir mana-mana set data, kajian lanjut diperlukan untuk menentukan sama ada fungsi regresi, sebenarnya, berguna dalam menerangkan varians set data.

Lazimnya, walau bagaimanapun, nilai yang lebih kecil atau lebih rendah untuk RSS adalah sesuai dalam mana-mana model kerana ini bermakna terdapat kurang variasi dalam set data. Dalam erti kata lain, lebih rendah jumlah sisa kuasa dua, lebih baik model regresi menerangkan data.

## Contoh Jumlah Baki Kuasa Dua

Untuk demonstrasi mudah (tetapi panjang) pengiraan RSS, pertimbangkan korelasi yang terkenal antara perbelanjaan pengguna sesebuah negara dan [KDNKnya](/gdp). Carta berikut menggambarkan nilai yang diterbitkan bagi [pengguna yang](/consumer-spending) [belum selesai](/consumer-spending) dan Keluaran Dalam Negara Kasar untuk 27 negeri Kesatuan Eropah, pada 2020.

<h5><a href="">TTT</a></h5>

Bank Dunia, 2020.

Perbelanjaan pengguna dan KDNK mempunyai korelasi positif yang kuat, dan adalah mungkin untuk meramalkan KDNK negara berdasarkan perbelanjaan pengguna (CS). Menggunakan formula untuk [garisan paling sesuai](/line-of-best-fit),. perhubungan ini boleh dianggarkan sebagai:

>

> KDNK = 1.3232 x CS + 10447

>

Unit untuk KDNK dan Perbelanjaan Pengguna adalah dalam jutaan dolar AS.

Formula ini sangat tepat untuk kebanyakan tujuan, tetapi ia tidak sempurna, disebabkan oleh variasi individu dalam ekonomi setiap negara. Carta berikut membandingkan unjuran KDNK bagi setiap negara, berdasarkan formula di atas, dan KDNK sebenar seperti yang direkodkan oleh Bank Dunia.

<h5><a href="">TTT</a></h5>

Bank Dunia, 2020.

Lajur di sebelah kanan menunjukkan petak sisa–perbezaan kuasa dua antara setiap nilai unjuran dan nilai sebenar. Angka itu kelihatan besar, tetapi jumlahnya sebenarnya lebih rendah daripada RSS untuk mana-mana garis arah aliran lain yang mungkin. Jika baris yang berbeza mempunyai RSS yang lebih rendah untuk titik data ini, baris itu akan menjadi garisan yang paling sesuai.

## Sorotan

- Nilai sifar bermakna model anda sangat sesuai.

- RSS digunakan oleh penganalisis kewangan untuk menganggarkan kesahihan model ekonometrik mereka.

- Jumlah sisa kuasa dua (RSS) mengukur tahap varians dalam jangka ralat, atau baki, model regresi.

- Model statistik digunakan oleh pelabur dan pengurus portfolio untuk menjejaki harga pelaburan dan menggunakan data tersebut untuk meramalkan pergerakan masa hadapan.

- Lebih kecil jumlah baki kuasa dua, lebih baik model anda sesuai dengan data anda; lebih besar jumlah baki kuasa dua, lebih miskin model anda sesuai dengan data anda.

## Soalan Lazim

### Adakah RSS Sama dengan Jumlah Anggaran Kuasa Dua Ralat (SSE)?

Jumlah baki kuasa dua (RSS) juga dikenali sebagai jumlah anggaran ralat kuasa dua (SSE).

### Apakah Perbezaan Antara Jumlah Baki Kuasa Dua dan Jumlah Kuasa Dua?

Jumlah kuasa dua (TSS) mengukur berapa banyak variasi yang terdapat dalam data yang diperhatikan, manakala jumlah baki kuasa dua mengukur variasi dalam ralat antara data yang diperhatikan dan nilai model. Dalam statistik, nilai untuk jumlah baki kuasa dua dan jumlah kuasa dua (TSS) selalunya dibandingkan antara satu sama lain.

### Adakah Jumlah Baki Kuasa Dua Sama dengan R-Squared?

Jumlah baki kuasa dua (RSS) ialah jumlah mutlak variasi yang dijelaskan, manakala R-kuasa dua ialah jumlah mutlak variasi sebagai perkadaran jumlah variasi.

### Bolehkah Jumlah Baki Kuasa Dua Menjadi Sifar?

Jumlah baki kuasa dua boleh menjadi sifar. Lebih kecil jumlah baki kuasa dua, lebih baik model anda sesuai dengan data anda; lebih besar jumlah baki kuasa dua, lebih miskin model anda sesuai dengan data anda. Nilai sifar bermakna model anda sesuai.

