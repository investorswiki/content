---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Merkle Root (Cryptocurrency)
description: Akar Merkle mengandungi maklumat tentang setiap cincang urus niaga yang pernah ada pada blok tertentu dalam rantaian blok.
---

# Merkle Root (Cryptocurrency)
## Apakah itu Merkle Root?

Akar Merkle ialah [cincang](/hash) bagi semua cincang bagi semua urus niaga yang merupakan sebahagian daripada blok dalam rangkaian [blok](/blockchain).

## Memahami Akar Merkle

Blockchain terdiri daripada pelbagai blok yang dikaitkan antara satu sama lain (oleh itu dinamakan blockchain). Pokok hash, atau [pokok Merkle](/merkle-tree),. mengekod data blokchain dengan cara yang cekap dan selamat. Ia membolehkan pengesahan cepat data blockchain, serta pergerakan pantas sejumlah besar data dari satu nod komputer ke satu lagi pada rangkaian blockchain peer-to-peer.

Setiap transaksi yang berlaku pada rangkaian blockchain mempunyai cincangan yang dikaitkan dengannya. Walau bagaimanapun, cincang ini tidak disimpan dalam susunan berurutan pada blok, sebaliknya dalam bentuk struktur seperti pokok supaya setiap cincang dipautkan kepada induknya mengikut perhubungan seperti pokok induk-anak.

Memandangkan terdapat banyak transaksi yang disimpan pada blok tertentu, semua cincang transaksi dalam blok itu juga dicincang, yang menghasilkan akar Merkle.

Sebagai contoh, pertimbangkan blok tujuh transaksi. Pada peringkat terendah (dipanggil peringkat daun), akan terdapat empat cincang transaksi. Pada tahap satu di atas peringkat daun, akan terdapat dua cincang transaksi, setiap satunya akan bersambung kepada dua cincang yang berada di bawahnya pada peringkat daun. Di bahagian atas (tahap dua), akan terdapat cincangan transaksi terakhir yang dipanggil akar, dan ia akan menyambung kepada dua cincang di bawahnya (pada tahap satu).

Secara berkesan, anda mendapat pokok binari terbalik, dengan setiap nod pokok itu bersambung kepada hanya dua nod di bawahnya (oleh itu dinamakan "pokok binari"). Ia mempunyai satu cincangan akar di bahagian atas, yang bersambung kepada dua cincang pada tahap satu, setiap satunya sekali lagi bersambung kepada dua cincang pada tahap tiga (peringkat daun), dan struktur berterusan bergantung pada bilangan cincang transaksi.

<!--AAFEB15A7406E8DD3ABDD652D7C85823-->

Pencincangan bermula pada nod peringkat terendah (paras daun), dan keempat-empat cincang dimasukkan dalam cincang nod yang dipautkan padanya pada tahap satu. Begitu juga, pencincangan berterusan pada tahap satu, yang membawa kepada cincangan cincang mencapai tahap yang lebih tinggi, sehingga ia mencapai cincang akar atas tunggal.

Cincang akar ini dipanggil akar Merkle, dan disebabkan kaitan cincang seperti pokok, ia mengandungi semua maklumat tentang setiap cincang transaksi tunggal yang wujud pada blok. Ia menawarkan nilai cincang satu titik yang membolehkan mengesahkan semua yang ada pada blok itu.

Sebagai contoh, jika seseorang itu perlu mengesahkan transaksi yang mendakwa berasal dari blok #137, mereka hanya perlu menyemak pepohon Merkle blok itu, tanpa perlu risau tentang mengesahkan apa-apa pada mana-mana blok lain pada blockchain, seperti blok #136 atau blok # 138.

<!--4861E8697637B7236BF11AA57D958059-->

Masukkan akar Merkle, yang mempercepatkan lagi pengesahan. Memandangkan ia membawa semua maklumat tentang keseluruhan pokok, seseorang hanya perlu mengesahkan cincang transaksi itu, nod adik-beradiknya (jika wujud), dan kemudian teruskan ke atas sehingga ia mencapai bahagian atas.

Pada asasnya, pokok Merkle dan mekanisme akar Merkle mengurangkan tahap pencincangan yang perlu dilakukan dengan ketara, membolehkan pengesahan dan transaksi yang lebih pantas.

##Sorotan

- Akar Merkle adalah penting kepada pengiraan yang diperlukan untuk mengekalkan mata wang kripto seperti bitcoin dan eter.

- Akar Merkle digunakan dalam mata wang kripto untuk memastikan blok data yang dihantar antara rakan sebaya pada rangkaian rakan ke rakan adalah utuh, tidak rosak dan tidak diubah.

- Akar Merkle ialah cara matematik yang mudah untuk mengesahkan data pada pokok Merkle.

