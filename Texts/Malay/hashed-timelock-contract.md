---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Crypto,Strategy and Education
title: Kontrak Kunci Masa Dicincang (HTLC)
description: Kontrak TimeLock Dicincang (HTLC). Merujuk kepada ciri khas yang digunakan untuk mencipta kontrak pintar yang mampu mengubah suai saluran pembayaran.
---

# Kontrak Kunci Masa Dicincang (HTLC)
Istilah Hashed TimeLock Contract (HTLC) merujuk kepada ciri khas yang digunakan untuk mencipta [kontrak pintar](/smart-contract) yang mampu mengubah suai saluran pembayaran. Secara teknikal, ciri HTLC membolehkan pelaksanaan transaksi terikat masa antara dua pengguna. Dalam amalan, penerima transaksi HTLC perlu mengakui pembayaran dengan menyerahkan bukti kriptografi dalam jangka masa tertentu (bilangan blok). Jika penerima kehilangan atau gagal menuntut bayaran, dana akan dikembalikan kepada pengirim asal.

Ciri HTLC digunakan dalam kedua-dua saluran pembayaran dwiarah dan dihalakan untuk membenarkan pemindahan dana yang selamat melalui pelbagai saluran, tanpa memerlukan kepercayaan pada mana-mana pengantara.

Terdapat dua elemen utama yang membezakan HTLC daripada transaksi mata wang kripto standard, iaitu:

- Hashlock: fungsi yang menyekat perbelanjaan dana sehingga sekeping data tertentu didedahkan secara terbuka (sebagai bukti kriptografi). Bukti sedemikian juga boleh dirujuk sebagai pra-imej cincang. Pra-imej hanyalah sekeping maklumat yang digunakan untuk menjana cincang, dan kemudian membuka kunci dananya.

- Kunci masa: ialah fungsi yang mengehadkan perbelanjaan dana sehingga masa tertentu (atau ketinggian blok) pada masa hadapan. Ia boleh dicapai dalam Bitcoin, contohnya, menggunakan fungsi seperti CheckLockTimeVerify atau CheckSequenceVerify.

Rangkaian Kilat Bitcoin adalah antara kes penggunaan Hashed Timelocked Contracts yang paling popular. Dengan melaksanakan HTLC ke dalam saluran pembayaran, dana boleh diurus niaga daripada pengguna ke pengguna melalui saluran pembayaran yang saling berkaitan, tanpa memerlukan sebarang tahap kepercayaan. Proses ini dikenali sebagai penghalaan rangkaian. Ia membolehkan Alice menukar dana dengan Carol walaupun mereka tidak disambungkan secara langsung melalui saluran pembayaran. HTLC membolehkan Alice menghantar dananya kepada Carol melalui peserta rangkaian lain (cth, Bob) - dan ciri pencincang dan kunci masa memastikan Bob tidak boleh memintas dana.

Selain digunakan pada Rangkaian Lightning, HTLC juga boleh berguna dalam konteks lain, seperti [pertukaran atom rantaian silang](/atomic-swaps),. kontrak pintar kewangan dan escrow, dan banyak lagi.

## Sorotan

- Pembayaran menggunakan HTTPS adalah bersyarat dan begitu juga dengan faedah kecekapan untuk transaksi blockchain. Sifat ini menjadikan HTTP sebagai alat asas yang digunakan oleh rangkaian kilat.

- Kontrak pintar jenis ini memerlukan penerima pembayaran untuk mengakuinya dalam tempoh masa tertentu atau kehilangannya.

- Kontrak kunci masa dicincang (HTLC) mengurangkan risiko rakan niaga dalam kontrak pintar terpencar dengan berkesan mencipta eskrow berasaskan masa yang menggunakan frasa laluan kriptografi.

## Soalan Lazim

### Berapakah Kos Kontrak Pintar?

Pada blockchain Ethereum, penggunaan kontrak pintar memerlukan gas, yang menelan kos Gwei (denominasi eter yang lebih rendah). Bergantung pada kerumitan kontrak, ia boleh menelan belanja berbilion-bilion Gwei untuk menggunakan kontrak pintar. Kontrak yang kurang kompleks seperti pertukaran mudah adalah lebih murah.

### Apakah Itu Kontrak Pintar?

Kontrak pintar ialah program yang disimpan pada blockchain yang dilaksanakan apabila syarat tertentu dipenuhi.

### Apakah Kontrak Timelock?

Kontrak kunci masa ialah kontrak pintar yang dibenamkan dalam rantaian blok yang melaksanakan transaksi pada masa tertentu. Ia digunakan dalam kontrak kunci masa yang dicincang dan saluran pembayaran yang memerlukan masa pembayaran tertentu.

### Adakah Bitcoin Mempunyai Kontrak Pintar?

Pada mulanya, blockchain Bitcoin tidak dapat melaksanakan kontrak pintar. Walau bagaimanapun, peningkatan Taproot pada tahun 2021 membenarkan blockchain menggunakan kontrak pintar dalam urus niaga.

