---
keywords: Crypto
title: Membelah dua
description: Membelah dua. Apabila ganjaran blok aset kripto, turun kepada separuh daripada nilai sebelumnya; ini digunakan untuk mencipta kadar terbitan yang mereput.
---

# Membelah dua
Dalam ruang mata wang kripto, istilah halving merujuk kepada proses yang mengurangkan kadar pengeluaran syiling baharu. Lebih tepat lagi, separuh adalah pengurangan berkala subsidi blok yang diberikan kepada pelombong. Halving memastikan bahawa aset kripto akan mengikut kadar terbitan yang stabil sehingga [bekalan maksimumnya](/maximum-supply) akhirnya dicapai.

Mengenai Bitcoin, syiling berita dijana secara berterusan sebagai sebahagian daripada [ganjaran blok](/block-reward) (yang terdiri daripada subsidi blok ditambah yuran transaksi). Oleh itu, setiap kali pelombong berjaya "menemui" dan mengesahkan [blok baharu](/block),. mereka memperoleh syiling yang baru dibuat sebagai pampasan untuk kerja mereka.

Jadi proses [perlombongan](/mining) adalah apa yang memperkenalkan [Bitcoins baharu](/bitcoin) ke dalam sistem, dan ini dilakukan pada kadar yang boleh diramal dan terkawal. Blok Bitcoin baharu dilombong, secara purata, setiap 10 minit, dan subsidi blok mengikut kadar pereputan terkawal. Sehubungan itu, pengurangan separuh adalah yang memastikan bahawa subsidi blok akan berkurangan sebanyak 50% setiap 210,000 blok (kira-kira setiap empat tahun).

Bermula pada [blok genesis](/genesis-block),. subsidi blok Bitcoin pada mulanya ditetapkan sebagai 50 BTC. Kemudian, ia dikurangkan kepada 25 BTC pada 2012, dan kepada 12.5 BTC pada 2016. Pemotongan separuh berikut dijangka berlaku sekitar Mei 2020, mengurangkan subsidi blok kepada 6.25 BTC. Sebaik sahaja 32 halving telah berlaku, proses berhenti dan tiada lagi Bitcoin akan dibuat. Pada ketika ini, bekalan maksimum sebanyak 21 juta BTC akan dicapai.

[Ikuti bersama dengan Bitcoin Halving](/halving)

Halving adalah bahagian penting dalam protokol Bitcoin dan, memandangkan kod tersebut adalah sumber terbuka, sesiapa sahaja boleh melihatnya. Sebagai contoh, pelaksanaan Teras Bitcoin tersedia di [GitHub](/github),. dan salah satu bahagian kod yang mentakrifkan subsidi blok kelihatan seperti ini:

CAmount GetBlockSubsidy(int nHeight, const Consensus::Params& consensusParams)

{

int halvings = nKetinggian / consensusParams.nSubsidyHalvingInterval;

// Paksa ganjaran blok kepada sifar apabila anjakan kanan tidak ditentukan.

jika (separuh >= 64)

pulangan 0;

CAmount nSubsidi = 50 * SYILING;

// Subsidi dipotong separuh setiap 210,000 blok yang akan berlaku kira-kira setiap 4 tahun.

nSubsidi >>= separuh;

pulangan nSubsidi;

}

