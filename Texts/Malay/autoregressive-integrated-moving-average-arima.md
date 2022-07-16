---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: Purata Pergerakan Bersepadu Autoregresif (ARIMA)
description: Purata pergerakan bersepadu autoregresif (ARIMA) ialah model analisis statistik yang memanfaatkan data siri masa untuk meramalkan arah aliran masa hadapan.
---

# Purata Pergerakan Bersepadu Autoregresif (ARIMA)
## Apakah Itu Purata Pergerakan Bersepadu Autoregresif (ARIMA)?

Purata bergerak bersepadu autoregresif, atau ARIMA, ialah model analisis statistik yang menggunakan [data siri masa](/timeseries) untuk sama ada memahami set data dengan lebih baik atau untuk meramalkan arah aliran masa hadapan.

Model statistik adalah autoregresif jika ia meramalkan nilai masa depan berdasarkan nilai masa lalu. Sebagai contoh, model ARIMA mungkin berusaha untuk meramalkan harga masa hadapan saham berdasarkan prestasi masa lalunya atau meramalkan pendapatan syarikat berdasarkan tempoh lalu.

## Memahami Purata Pergerakan Bersepadu Autoregresif (ARIMA)

Model purata bergerak bersepadu autoregresif ialah satu bentuk [analisis regresi](/regression) yang mengukur kekuatan satu pembolehubah bersandar berbanding pembolehubah berubah yang lain. Matlamat model adalah untuk meramalkan sekuriti masa depan atau pergerakan pasaran kewangan dengan mengkaji perbezaan antara nilai dalam siri dan bukannya melalui nilai sebenar.

Model ARIMA boleh difahami dengan menggariskan setiap komponennya seperti berikut:

- [Autoregression (AR)](/autoregressive) : merujuk kepada model yang menunjukkan pembolehubah yang berubah-ubah yang mundur pada nilai tertinggalnya sendiri, atau sebelumnya.

- **Bersepadu (I):** mewakili perbezaan pemerhatian mentah untuk membolehkan siri masa menjadi pegun (iaitu, nilai data digantikan dengan perbezaan antara nilai data dan nilai sebelumnya).

- [Purata bergerak (MA)](/movingaverage) : menggabungkan pergantungan antara pemerhatian dan ralat baki daripada model purata bergerak yang digunakan untuk pemerhatian ketinggalan.

## Parameter ARIMA

Setiap komponen dalam ARIMA berfungsi sebagai parameter dengan tatatanda standard. Untuk model ARIMA, tatatanda standard ialah ARIMA dengan p, d dan q, di mana nilai integer menggantikan parameter untuk menunjukkan jenis model ARIMA yang digunakan. Parameter boleh ditakrifkan sebagai:

- **p**: bilangan cerapan ketinggalan dalam model; juga dikenali sebagai urutan ketinggalan.

- **d**: bilangan kali pemerhatian mentah dibezakan; juga dikenali sebagai darjah pembezaan.

- q: saiz tetingkap purata bergerak; juga dikenali sebagai susunan purata bergerak.

Dalam model [regresi linear](/nonlinear-regression),. sebagai contoh, bilangan dan jenis istilah disertakan. Nilai 0, yang boleh digunakan sebagai parameter, bermakna komponen tertentu tidak boleh digunakan dalam model. Dengan cara ini, model ARIMA boleh dibina untuk melaksanakan fungsi model ARMA, atau model AR, I atau MA yang mudah.

> Oleh kerana model ARIMA adalah rumit dan berfungsi paling baik pada set data yang sangat besar, algoritma komputer dan teknik pembelajaran mesin digunakan untuk mengiranya.

>

## Purata Pergerakan Bersepadu Autoregresif (ARIMA) dan Pegun

Dalam model purata bergerak bersepadu autoregresif, data dibezakan untuk menjadikannya pegun. Model yang menunjukkan kepegunan ialah model yang menunjukkan terdapat ketekalan pada data dari semasa ke semasa. Kebanyakan data ekonomi dan pasaran menunjukkan arah aliran, jadi tujuan pembezaan adalah untuk mengalih keluar sebarang aliran atau struktur bermusim.

[Kemusim](/seasonality),. atau apabila data menunjukkan corak biasa dan boleh diramal yang berulang sepanjang tahun kalendar, boleh menjejaskan model regresi secara negatif. Jika trend muncul dan pegun tidak jelas, banyak pengiraan sepanjang proses tidak dapat dibuat dengan keberkesanan yang tinggi.

> Kejutan sekali sahaja akan menjejaskan nilai seterusnya bagi model ARIMA secara tidak terhingga pada masa hadapan. Oleh itu, legasi krisis kewangan kekal dalam model autoregresif hari ini.

>

## Pertimbangan Khas

Model ARIMA adalah berdasarkan andaian bahawa nilai masa lalu mempunyai beberapa kesan sisa pada nilai semasa atau masa hadapan. Sebagai contoh, pelabur yang menggunakan model ARIMA untuk meramalkan harga saham akan menganggap bahawa pembeli dan penjual baharu saham tersebut dipengaruhi oleh urus niaga pasaran baru-baru ini apabila memutuskan amaun yang akan ditawarkan atau diterima untuk keselamatan.

Walaupun andaian ini akan berlaku dalam banyak keadaan, ini tidak selalu berlaku. Sebagai contoh, pada tahun-tahun sebelum Krisis Kewangan 2008, kebanyakan pelabur tidak menyedari risiko yang ditimbulkan oleh portfolio besar [sekuriti bersandarkan gadai janji](/mbs) (MBS) yang dipegang oleh banyak firma kewangan.

Pada masa itu, pelabur yang menggunakan model autoregresif untuk meramalkan prestasi saham kewangan AS mempunyai alasan yang kukuh untuk meramalkan trend berterusan harga saham yang stabil atau meningkat dalam sektor itu. Walau bagaimanapun, sebaik sahaja diketahui umum bahawa banyak institusi kewangan menghadapi risiko kehancuran yang pasti, pelabur tiba-tiba menjadi kurang prihatin dengan harga saham ini baru-baru ini dan lebih bimbang dengan pendedahan risiko asasnya. Oleh itu, pasaran menilai semula saham kewangan dengan pantas ke tahap yang lebih rendah, satu langkah yang akan mengelirukan model autoregresif.

## Soalan Lazim

### ARIMA digunakan untuk apa?

ARIMA ialah kaedah untuk meramal atau meramal hasil masa hadapan berdasarkan siri masa sejarah. Ia berdasarkan konsep statistik korelasi bersiri, di mana titik data masa lalu mempengaruhi titik data masa depan.

### Apakah perbezaan antara model autoregresif dan purata bergerak?

ARIMA menggabungkan ciri autoregresif dengan purata bergerak. Proses autoregresif AR(1), sebagai contoh, ialah proses yang nilai semasa adalah berdasarkan nilai segera sebelumnya, manakala proses AR(2) ialah proses yang nilai semasa berdasarkan dua nilai sebelumnya. Purata bergerak ialah pengiraan yang digunakan untuk menganalisis titik data dengan mencipta satu siri purata subset berbeza bagi set data penuh untuk melicinkan pengaruh outlier. Hasil daripada gabungan teknik ini, model ARIMA boleh mengambil kira arah aliran, kitaran, bermusim dan jenis data bukan statik lain semasa membuat ramalan.

### Bagaimanakah ramalan ARIMA berfungsi?

Ramalan ARIMA dicapai dengan memasukkan data siri masa untuk pembolehubah minat. Perisian statistik akan mengenal pasti bilangan ketinggalan atau jumlah perbezaan yang sesuai untuk digunakan pada data dan menyemak pegun. Ia kemudian akan mengeluarkan keputusan, yang sering ditafsirkan sama dengan model regresi linear berganda.

##Sorotan

- Model purata bergerak bersepadu autoregresif (ARIMA) meramalkan nilai masa hadapan berdasarkan nilai masa lalu.

- ARIMA menggunakan purata bergerak tertinggal untuk melicinkan data siri masa.

- Ia digunakan secara meluas dalam analisis teknikal untuk meramalkan harga keselamatan masa hadapan.

- Model autoregresif secara tersirat menganggap bahawa masa depan akan menyerupai masa lalu.

- Oleh itu, mereka boleh membuktikan tidak tepat di bawah keadaan pasaran tertentu, seperti krisis kewangan atau tempoh perubahan teknologi yang pesat.

