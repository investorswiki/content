---
keywords: Business,Corporate Finance and Accounting,Financial Ratios
title: Pengiraan Sisihan Piawai
description: Apakah Sisihan Piawai? Sisihan piawai ialah metrik yang mengukur kebolehubahan pulangan keselamatan dari semasa ke semasa. Ia boleh digunakan untuk mengukur turun naik
---

# Pengiraan Sisihan Piawai
## Apakah Sisihan Piawai?

Sisihan piawai ialah metrik yang mengukur kebolehubahan pulangan [keselamatan dari semasa ke semasa.](/security) Ia boleh digunakan untuk mengukur [turun naik](/volatility) berdasarkan prestasi lepas dan membandingkan pulangan masa hadapan dengan pulangan lalu. Sisihan piawai juga boleh mengukur pengagihan pulangan portfolio individu, dan boleh digunakan pada pelbagai jenis aset, termasuk [bon](/bond),. komoditi dan mata wang kripto. Artikel ini, bagaimanapun, memberi tumpuan kepada saham.

Sisihan piawai menunjukkan sejauh mana pulangan saham daripada pulangan purata untuk sesuatu tempoh, dan juga boleh menentukan sama ada pulangan untuk tempoh tertentu adalah outlier. Ia berguna untuk digunakan semasa masa turun naik dalam harga saham syarikat yang didagangkan secara terbuka, kerana ayunan naik dan turun yang besar dalam tempoh yang singkat boleh membantu menentukan risiko pelaburan berbanding ganjaran.

## Cara Mengira Sisihan Piawai Menggunakan Hamparan (Contoh: Apple)

Memahami sisihan piawai bermakna pertama memahami varians kerana sisihan piawai, secara matematik, ialah punca kuasa dua varians. Varians menunjukkan sejauh mana setiap pulangan daripada purata, atau min, set data pulangan.

Nombor yang lebih besar daripada 0 menunjukkan bahawa pulangan dalam set adalah jauh dari purata dan jauh antara satu sama lain, manakala nombor yang lebih besar daripada 0 menunjukkan lebih jauh daripada purata. Oleh kerana varians data adalah kuasa dua, sisihan piawai membawa data kembali ke unit ukuran yang sama (dalam kes stok, peratusan) dengan mengambil punca kuasa dua.

**Nota**: Sisihan piawai diwakili dalam formula oleh σ, huruf kecil Yunani untuk sigma.

Cara paling berkesan untuk mengira sisihan piawai, terutamanya dengan set data yang besar seperti harga saham harian, adalah melalui hamparan. Di bawah ialah contoh pengiraan sisihan piawai pulangan saham Apple dalam tempoh tiga bulan.

**Langkah 1**: Kumpul data harian kembali dalam tempoh tiga bulan. Ini secara kasarnya bersamaan dengan kira-kira 20 hari sebulan, dan hari pertama berfungsi sebagai harga asas dalam mengira perubahan peratusan pertama. Kira perubahan peratusan harian untuk saham Apple dan nyatakan data dalam istilah peratusan. **Nota**: Formula ditunjukkan dalam sel dan juga dalam kawasan medan di sudut kiri atas hamparan. Harga saham penutup Apple (dinyatakan dalam dolar AS) merangkumi pelarasan, termasuk pembahagian, dividen dan/atau pengagihan keuntungan modal.

**Langkah 2**: Kira purata pulangan menggunakan fungsi AVERAGE.

**Langkah 3**: Kira varians pulangan menggunakan fungsi VAR.

**Langkah 4**: Kira sisihan piawai pulangan menggunakan fungsi STDEV. **Nota**: Purata dan sisihan piawai dinyatakan sebagai peratusan, manakala varians ialah nombor perpuluhan.

## Cara Mentafsir Sisihan Piawai

Dalam contoh di atas untuk Apple, data menunjukkan bahawa pulangan purata untuk tempoh tiga bulan ialah 0.08 peratus. Varians menunjukkan jarak julat nombor daripada purata. Tetapi sisihan piawai menunjukkan dengan tepat berapa jauh pulangan daripada purata. Dengan sisihan piawai pada 1.91 peratus, ia menunjukkan bahawa julat adalah tambah atau tolak 1.91 mata peratusan daripada purata, bermakna pulangan Apple cenderung berkisar antara -1.83 peratus hingga 1.99 peratus.

### Sisihan Piawai sebagai Kebarangkalian dalam Taburan Normal

Sisihan piawai boleh digambarkan dengan baik melalui corak taburan normal untuk kebarangkalian, yang memberikan gambaran statistik di mana sisihan piawai mungkin. Dalam taburan normal, kebanyakan senario dalam kebarangkalian cenderung berlaku lebih hampir kepada min. Kejadian yang jarang berlaku cenderung berlaku ke arah luar, ke arah kawasan yang rata yang dikenali sebagai ekor.

Dalam graf di bawah, taburan normal berbentuk seperti loceng, oleh itu nama panggilannya sebagai lengkung loceng, dengan bahagian tengah lengkung mewakili min. Angka-angka yang disenaraikan secara mendatar di bawah graf dikenali sebagai skor-z, yang berjulat dari -3 hingga 3. Ia adalah titik sisihan piawai dan dinyatakan secara berbeza daripada formula sisihan piawai, yang dinyatakan sebagai peratusan.

Pengiraan taburan normal boleh memberikan kebarangkalian pada parameter mana potensi pulangan mungkin. Katakan seorang peniaga harian mengunjurkan saham Apple memperoleh 5 peratus sehari selepas melaporkan pendapatan dan hasil rekod untuk suku yang dilaporkan terkini. Apakah kebarangkalian stok akan mencatatkan pulangan 5 peratus pada hari berikutnya?

Formula kod-z boleh menunjukkan tempat pulangan pada graf taburan normal.

Dengan memasukkan unjuran pulangan, purata dan sisihan piawai Apple yang diambil daripada hamparan di atas:

> (5% - 0.08%) / 1.91% = 2.57 Sisihan Piawai Melebihi Purata.

Potensi pulangan 5 peratus pada saham Apple ialah 2.57 sisihan piawai melebihi purata, jatuh antara 2 dan 3 sisihan piawai daripada min. Secara statistik, ia menunjukkan kebarangkalian 2.28 peratus untuk mencapai unjuran pulangan 5 peratus. Kebarangkalian 2.28 peratus itu diperoleh dengan menolak 95.44 peratus daripada 100 peratus, dan perbezaan (4.56 peratus) kemudian dibahagikan dengan dua kerana jumlah kebarangkalian yang sama pada setiap sisi (negatif dan positif) garis simetri dalam graf taburan normal . Walau apa pun, keuntungan harian 5 peratus pada saham Apple bukanlah perkara biasa.

Satu lagi cara untuk mentafsir taburan normal ialah dengan mengatakan bahawa kebarangkalian Apple kembali (pada julat -1.83 peratus dan 1.99 peratus) berada dalam -1 dan 1 sisihan piawai daripada min ialah 68.26 peratus. Kebarangkalian sisihan piawai antara -2 dan 2 ialah 95.44 peratus, dan antara -3 dan 3, ia adalah 99.74 peratus.

## Bagaimanakah Sisihan Piawai Berkaitan dengan Kemeruapan?

Sisihan piawai boleh menunjukkan bagaimana pulangan berkaitan dengan purata. Sisihan piawai yang tinggi akan menunjukkan turun naik yang tinggi, dan pulangan yang lebih besar daripada julat sisihan piawai menunjukkan bahawa ia adalah outlier. Satu siri ayunan naik dan turun di luar julat itu untuk satu tempoh juga akan menunjukkan turun naik yang tinggi.

## Sorotan

- Ia dikira sebagai punca kuasa dua varians.

- Sisihan piawai, dalam kewangan, sering digunakan sebagai ukuran risiko relatif sesuatu aset.

- Sisihan piawai mengukur serakan set data berbanding minnya.

- Stok yang tidak menentu mempunyai sisihan piawai yang tinggi, manakala sisihan saham cip biru yang stabil biasanya agak rendah.

- Sebagai kelemahan, sisihan piawai mengira semua ketidakpastian sebagai risiko, walaupun apabila ia memihak kepada pelabur—seperti pulangan melebihi purata.

## Soalan Lazim

### Apakah Maksud Sisihan Piawai Tinggi?

Sisihan piawai yang besar menunjukkan bahawa terdapat banyak varians dalam data yang diperhatikan di sekitar min. Ini menunjukkan bahawa data yang diperhatikan agak tersebar. Sisihan piawai yang kecil atau rendah akan menunjukkan sebaliknya bahawa kebanyakan data yang diperhatikan dikelompokkan rapat di sekitar min.

### Mengapa Sisihan Piawai Penting?

Sisihan piawai adalah penting kerana ia boleh membantu pengguna menilai risiko. Pertimbangkan pilihan pelaburan dengan pulangan tahunan purata 10% setahun. Walau bagaimanapun, purata ini diperolehi daripada pulangan tiga tahun yang lalu sebanyak 50%, -15% dan -5%. Dengan mengira sisihan piawai dan memahami kemungkinan rendah anda untuk mencapai purata 10% dalam mana-mana tahun tertentu, anda lebih bersedia untuk membuat keputusan termaklum dan mengiktiraf risiko asas.

### Apakah Sisihan Piawai Beritahu Anda?

Sisihan piawai menerangkan cara penyebaran satu set data. Ia membandingkan setiap titik data kepada min semua titik data dan sisihan piawai mengembalikan nilai terkira yang menerangkan sama ada titik data berada dalam jarak yang hampir atau sama ada ia tersebar. Dalam taburan normal, sisihan piawai memberitahu anda sejauh mana nilai daripada min.

### Bagaimana Anda Mengira Sisihan Piawai?

Sisihan piawai dikira sebagai punca kuasa dua varians. Sebagai alternatif, ia dikira dengan mencari min bagi set data, mencari perbezaan setiap titik data kepada min, mengkuadratkan perbezaan, menambahnya bersama, membahagikan dengan bilangan titik dalam set data kurang 1, dan mencari kuasa dua. akar.

### Bagaimana Anda Mencari Sisihan Piawai dengan Cepat?

Jika anda melihat taburan beberapa data yang diperhatikan secara visual, anda boleh melihat sama ada bentuknya agak kurus berbanding gemuk. Taburan yang lebih gemuk mempunyai sisihan piawai yang lebih besar. Sebagai alternatif, Excel telah membina dalam fungsi sisihan piawai bergantung pada set data.

