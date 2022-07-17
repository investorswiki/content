---
keywords: Crypto
title: Mempool
description: Mempool. Mekanisme nod untuk menjejaki urus niaga yang tidak disahkan yang telah dilihat oleh nod (tetapi belum lagi ditambahkan pada blok).
---

# Mempool
Mempool (penguncupan memori dan kumpulan) ialah mekanisme nod mata wang kripto untuk menyimpan maklumat mengenai transaksi yang tidak disahkan. Ia bertindak sebagai semacam ruang menunggu untuk urus niaga yang belum dimasukkan ke dalam [blok](/block).

Apabila transaksi disiarkan, ia dihantar dari nod kepada rakan sebayanya, yang kemudiannya akan menyampaikannya kepada rakan sebaya mereka. Ini berterusan sehingga urus niaga telah disebarkan secara meluas, sedia untuk pelombong menambahkannya pada blok. Adalah penting bahawa zon penampan ini wujud, kerana urus niaga tidak ditambahkan pada rantaian blok dengan serta-merta.

Nod akan menjalankan satu siri semakan untuk memastikan bahawa transaksi itu sah – iaitu, mengesahkan bahawa tandatangan adalah betul, output tidak melebihi input dan dana belum lagi dibelanjakan. Jika ia gagal memenuhi syarat ini, ia ditolak.

Kita sering bercakap tentang mempool, tetapi harus diingat bahawa tidak ada kolam universal yang dikongsi oleh semua nod. Setiap satu dikonfigurasikan secara berbeza dan menerima transaksi pada masa yang berbeza. Peranti yang lebih rendah dengan sumber terhad mungkin hanya mendedikasikan sejumlah kecil memori untuk urus niaga log, manakala peranti yang lebih tinggi mungkin menumpukan lebih banyak.

Oleh kerana pelombong didorong terutamanya oleh keuntungan, urus niaga dengan bayaran yang lebih tinggi adalah yang paling mungkin dibuang daripada mempool terlebih dahulu apabila ia disahkan. Menganggarkan yuran dengan tepat adalah sukar, terutamanya apabila ruang blok terhad, dan permintaan tinggi, tetapi mempool menyediakan titik permulaan.

Untuk menganggarkan yuran, seseorang boleh melihat kepada transaksi semasa yang belum disahkan. Adalah wajar bahawa pengguna tidak sepatutnya membayar lebih dalam masa pemprosesan rendah. Mereka juga tidak sepatutnya membayar lebih rendah untuk transaksi sensitif masa pada waktu puncak, kerana mungkin agak lama sebelum ia disahkan. Dengan mengambil kira penyebaran yuran pada masa tertentu, mereka boleh membuat tekaan terpelajar tentang seberapa cepat transaksi mereka akan disertakan.

