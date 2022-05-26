---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: Model Box-Jenkins
description: Model Box-Jenkins ialah model matematik yang direka untuk meramal data daripada siri masa tertentu.
---

# Model Box-Jenkins
## Apakah Model Box-Jenkins?

Model Box-Jenkins ialah model matematik yang direka untuk meramalkan julat data berdasarkan input daripada [siri masa tertentu](/timeseries). Model Box-Jenkins boleh menganalisis beberapa jenis data siri masa yang berbeza untuk tujuan ramalan.

Metodologinya menggunakan perbezaan antara titik data untuk menentukan hasil. Metodologi membolehkan model mengenal pasti aliran menggunakan autoregresi, purata bergerak dan perbezaan bermusim untuk menjana ramalan.

[Model purata bergerak bersepadu autoregresif (ARIMA)](/autoregressive-integrated-moving-average-arima) ialah satu bentuk model Box-Jenkins. Istilah ARIMA dan Box-Jenkins kadangkala digunakan secara bergantian.

## Memahami Model Box-Jenkins

Model Box-Jenkins digunakan untuk [meramalkan](/forecasting) pelbagai titik data atau julat data yang dijangka, termasuk data perniagaan dan harga keselamatan masa hadapan.

Model Box-Jenkins dicipta oleh dua ahli matematik: George Box dan Gwilym Jenkins. Kedua-dua ahli matematik membincangkan konsep yang membentuk model ini dalam penerbitan 1970 yang dipanggil "Analisis Siri Masa: Ramalan dan Kawalan."

Anggaran parameter Model Box-Jenkins boleh menjadi sangat rumit. Oleh itu, sama seperti model regresi siri masa yang lain, keputusan terbaik biasanya akan dicapai melalui penggunaan perisian boleh atur cara. Model Box-Jenkins juga biasanya paling sesuai untuk ramalan jangka pendek selama 18 bulan atau kurang.

##Metodologi Box-Jenkins

Model Box-Jenkins mungkin salah satu daripada beberapa model analisis siri masa yang akan dihadapi oleh peramal apabila menggunakan perisian ramalan yang diprogramkan. Dalam kebanyakan kes, perisian akan diprogramkan untuk secara automatik menggunakan metodologi ramalan yang paling sesuai berdasarkan data [siri masa yang](/timeseries) akan diramalkan. Box-Jenkins dilaporkan menjadi pilihan utama untuk set data yang kebanyakannya stabil dan mempunyai [turun naik yang rendah](/volatility).

Model Box-Jenkins meramalkan data menggunakan tiga prinsip: autoregresi, pembezaan dan purata bergerak. Ketiga-tiga prinsip ini dikenali sebagai p, d, dan q, masing-masing. setiap prinsip digunakan dalam analisis Box-Jenkins; bersama-sama, mereka secara kolektif ditunjukkan sebagai ARIMA (p, d, q).

Proses autoregresi (p) menguji data untuk tahap pegunnya. Jika data yang digunakan adalah pegun, ia boleh memudahkan proses ramalan. Jika data yang digunakan tidak pegun ia perlu dibezakan (d). Data juga diuji untuk kesesuaian purata bergeraknya (yang dilakukan dalam bahagian q proses analisis). Secara keseluruhan, analisis awal data menyediakannya untuk peramalan dengan menentukan parameter (p, d, dan q), yang kemudiannya digunakan untuk membangunkan ramalan.

> Kejutan sekali sahaja akan menjejaskan nilai seterusnya bagi model Box-Jenkins secara tidak terhingga pada masa hadapan. Oleh itu, legasi krisis kewangan kekal dalam model autoregresif hari ini.

>

## Purata Pergerakan Bersepadu Autoregresif (ARIMA)

Box-Jenkins ialah sejenis model purata bergerak bersepadu autoregresif (ARIMA) yang mengukur kekuatan satu pembolehubah bersandar berbanding pembolehubah berubah yang lain. Matlamat model adalah untuk meramalkan sekuriti masa depan atau pergerakan pasaran kewangan dengan mengkaji perbezaan antara nilai dalam siri dan bukannya melalui nilai sebenar.

Model ARIMA boleh difahami dengan menggariskan setiap komponennya seperti berikut:

- [Autoregression (AR)](/autoregressive) : merujuk kepada model yang menunjukkan pembolehubah yang berubah-ubah yang mundur pada nilai tertinggalnya sendiri, atau sebelumnya.

- Bersepadu (I): mewakili perbezaan pemerhatian mentah untuk membolehkan siri masa menjadi pegun, iaitu, nilai data digantikan dengan perbezaan antara nilai data dan nilai sebelumnya.

- [Purata bergerak (MA)](/movingaverage) : menggabungkan pergantungan antara pemerhatian dan ralat baki daripada model purata bergerak yang digunakan untuk pemerhatian ketinggalan.

## Ramalan Harga Saham

Satu kegunaan untuk analisis Model Box-Jenkins adalah untuk meramalkan harga [saham](/stock). Analisis ini biasanya dibina dan dikodkan melalui perisian R. Analisis keputusan dalam hasil logaritma, yang boleh digunakan pada set data untuk menjana harga ramalan untuk tempoh masa tertentu pada masa hadapan.

Model ARIMA adalah berdasarkan andaian bahawa nilai masa lalu mempunyai beberapa kesan sisa pada nilai semasa atau masa hadapan. Sebagai contoh, pelabur yang menggunakan model ARIMA untuk meramalkan harga saham akan menganggap bahawa pembeli dan penjual baharu saham tersebut dipengaruhi oleh urus niaga pasaran baru-baru ini apabila memutuskan amaun yang akan ditawarkan atau diterima untuk keselamatan.

Walaupun andaian ini akan berlaku dalam banyak keadaan yang berbeza, ia tidak selalunya benar. Sebagai contoh, pada tahun-tahun sebelum Krisis Kewangan 2008, kebanyakan pelabur tidak menyedari risiko yang ditimbulkan oleh portfolio besar [sekuriti bersandarkan gadai janji](/mbs) (MBS) yang dipegang oleh banyak firma kewangan.

Pada masa itu, pelabur yang menggunakan model autoregresif untuk meramalkan prestasi saham kewangan AS mempunyai alasan yang kukuh untuk meramalkan trend berterusan harga saham yang stabil atau meningkat dalam sektor itu. Walau bagaimanapun, sebaik sahaja diketahui umum bahawa banyak institusi kewangan menghadapi risiko kehancuran yang pasti, pelabur tiba-tiba menjadi kurang prihatin dengan harga saham ini baru-baru ini dan lebih bimbang dengan pendedahan risiko asasnya.

Oleh itu, pasaran menilai semula saham kewangan dengan pantas ke tahap yang lebih rendah, satu langkah yang akan mengelirukan model autoregresif.

##Sorotan

- Model purata bergerak bersepadu autoregresif (ARIMA) ialah satu bentuk model Box-Jenkins.

- Model Box-Jenkins paling sesuai untuk ramalan dalam tempoh masa 18 bulan atau kurang.

- Metodologi adalah berdasarkan andaian bahawa kejadian masa lalu mempengaruhi masa depan.

- Model Box-Jenkins ialah metodologi peramalan menggunakan kajian regresi pada data siri masa.

