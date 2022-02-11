---
keywords: Crypto
title: Blok Calon
description: Blok Calon. Blok sementara yang dibuat oleh nod perlombongan (penambang) untuk ditambahkan pada blok untuk menerima ganjaran blok.
---

# Blok Calon
Dalam beberapa perkataan, blok calon ialah blok yang nod perlombongan (penambang) cuba lombong untuk menerima ganjaran blok. Jadi blok calon boleh digambarkan sebagai blok sementara yang akan sama ada disahkan atau dibuang oleh rangkaian. Penambang bersaing antara satu sama lain untuk mengesahkan blok seterusnya dan menambahnya pada blok, tetapi pertama, mereka perlu mencipta blok calon untuk menyertai pertandingan perlombongan.

Blok calon dicipta oleh pelombong dengan mengumpul dan mengatur berbilang transaksi yang belum disahkan daripada kumpulan memori. Urus niaga kemudiannya dicincang untuk membentuk struktur [pokok Merkle](/merkle-tree),. yang akhirnya akan menghasilkan akar Merkle (atau cincang akar). Akar Merkle ialah cincang tunggal yang mewakili semua cincang sebelumnya bagi pokok itu, dan oleh itu, semua urus niaga yang disertakan dalam blok tertentu itu.

Cincang akar - bersama cincang blok sebelumnya dan nombor rawak yang dipanggil [nonce](/nonce) - kemudian dimasukkan ke dalam pengepala blok. Pengepala blok kemudiannya dicincang oleh pelombong, menghasilkan output berdasarkan komponen tersebut (cincang akar, cincang blok sebelumnya dan tidak) serta beberapa elemen lain. Output yang terhasil ialah cincang blok dan akan berfungsi sebagai pengecam unik bagi blok yang baru dijana (blok calon).

Untuk dianggap sah, output (hash blok) mesti bermula dengan bilangan sifar tertentu (kurang daripada nilai sasaran yang ditakrifkan oleh protokol). Ini bermakna proses perlombongan adalah berdasarkan pelbagai percubaan (percubaan dan ralat) kerana nod perlombongan perlu melaksanakan pelbagai fungsi pencincangan dengan nilai nonce yang berbeza sehingga cincangan blok yang sah akhirnya dihasilkan. Hash blok yang dihasilkan adalah yang membuktikan bahawa pelombong melakukan kerjanya (oleh itu Bukti Kerja).

Selepas pelombong menemui cincang blok yang sah, blok calon mereka akan disiarkan ke seluruh nod rangkaian, yang akan mengesahkan ketulenan cincang itu. Jika semuanya baik, blok calon kemudiannya akan direkodkan ke dalam blockchain. Pada ketika ini, setiap nod yang mengesahkan mengemas kini salinan data blockchain untuk mencerminkan blok yang dilombong baru-baru ini, dan pelombong akan mendapat ganjaran blok.

