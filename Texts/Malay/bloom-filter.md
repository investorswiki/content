---
keywords: Crypto
title: Penapis Bloom
description: Penapis Bloom. Struktur data yang boleh digunakan untuk memberitahu pengguna sama ada item tertentu adalah sebahagian daripada set item
---

# Penapis Bloom
Penapis Bloom ialah struktur data yang boleh digunakan untuk memaklumkan pengguna sama ada item tertentu adalah sebahagian daripada set. Walaupun ia tidak boleh mengatakan dengan pasti sama ada sesuatu elemen berada dalam set, ia boleh mengatakan dengan pasti jika elemen itu tidak.

Dicipta oleh Burton Howard Bloom pada tahun 1970, penapis Bloom ialah tawaran yang menarik untuk pelbagai aplikasi kerana kecekapannya dalam penggunaan ruang. Dalam sesetengah mata wang kripto (terutamanya Bitcoin), mereka memainkan peranan penting dalam Pengesahan Pembayaran Mudah, atau SPV.

Dalam menggunakan klien SPV, pengguna boleh berinteraksi dengan rangkaian Bitcoin tanpa menjalankan nod penuh. Nod penuh disertakan dengan storan dan keperluan pengiraan tertentu yang menjadikannya sukar untuk dijalankan pada peranti berkuasa rendah seperti telefon pintar. Pelanggan SPV, sebaliknya, hanya menanyakan nod penuh untuk maklumat yang berkaitan dengan dompet pengguna.

Penyelesaian yang paling mudah untuk menyampaikan data ini kepada pengguna adalah dengan membuat nod penuh mengetahui kunci pelanggan, supaya hanya transaksi yang berkaitan dihantar kepada mereka. Jelas sekali, ini adalah penyelesaian yang rendah kerana privasi pelanggan akan dikorbankan. Sebaliknya, memuat turun semua urus niaga hanya untuk membuang sebahagian besar daripadanya akan menjadi pembaziran lebar jalur. Masukkan penapis Bloom.

Mari kita gambarkan. Katakan bahawa pelanggan, Alice, mempunyai transaksi bernilai tinggi yang dia tidak mahu Bob, yang menjalankan nod penuh, sedar. Dia membina penapis Bloom, yang akan kami gambarkan sebagai grid 10x1:

Dia menghantar data transaksi yang dia minati melalui dua fungsi cincang yang berbeza, yang mengeluarkan dua nombor antara 0 dan 9. Mari kita panggil mereka 4 dan 7. Dia menghantar penapis kepada Bob.

Melihat pada grid ini, anda tidak tahu apa data yang telah dihantar Alice kepada penapis. Jika anda mempunyai set di mana data itu terkandung, anda akan dapat mencincangnya dan membandingkannya dengan penapis – jika ada padanan, ada kemungkinan ia adalah maklumat yang diminta oleh Alice.

Pada masa yang sama, kemungkinan terdapat banyak input yang akan dipetakan kepada 4 dan 7, jadi Bob tidak dapat menentukan bahagian data yang Alice minati. Dia hanya memulangkan semua perlawanan, dan Alice menapisnya di hujungnya.

Ini, sudah tentu, penyederhanaan yang berlebihan, tetapi ia menunjukkan konsep: Penapis Bloom mengaburkan minat sebenar pelanggan. Ia bukan kaedah yang sempurna (masih terdapat kebimbangan mengenai privasinya), tetapi ia adalah penambahbaikan ke atas permintaan yang tidak dilindungi kepada nod.

