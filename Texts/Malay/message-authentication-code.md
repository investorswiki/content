---
keywords: Personal Finance,Banking
title: Kod Pengesahan Mesej (MAC)
description: Kod pengesahan mesej (MAC), atau teg, ialah kod keselamatan yang ditaip oleh pengguna komputer untuk mengakses akaun atau portal.
---

# Kod Pengesahan Mesej (MAC)
## Apakah Kod Pengesahan Mesej?

Kod pengesahan mesej (MAC), atau **tag,** ialah kod keselamatan yang ditaip oleh pengguna komputer untuk mengakses akaun atau portal. Kod ini dilampirkan pada mesej atau permintaan yang dihantar oleh pengguna. Kod pengesahan mesej (MAC) yang dilampirkan pada mesej mesti diiktiraf oleh sistem penerima untuk memberikan akses kepada pengguna.

## Memahami Kod Pengesahan Mesej (MAC)

Kod pengesahan mesej (MAC) biasanya digunakan dalam [pemindahan dana elektronik](/electronic-funds-transfer-act) (EFT) untuk mengekalkan integriti maklumat. mereka mengesahkan bahawa mesej adalah sahih; bahawa ia benar-benar datang, dengan kata lain, daripada pengirim yang dinyatakan, dan tidak mengalami sebarang perubahan dalam perjalanan. Pengesah yang juga memiliki kunci boleh menggunakannya untuk mengenal pasti perubahan pada kandungan mesej yang dipersoalkan.

Kod pengesahan mesej biasanya diperlukan untuk mengakses sebarang jenis akaun kewangan. Bank, firma pembrokeran, syarikat amanah dan mana-mana deposit, pelaburan atau syarikat insurans lain yang menawarkan akses dalam talian boleh menggunakan kod ini. Mereka adalah komponen penting dalam kriptografi kewangan.

## Algoritma Digunakan untuk Menjana MAC

Tiga algoritma biasanya terdiri daripada MAC: algoritma penjanaan kunci, algoritma tandatangan dan algoritma pengesahan. Algoritma penjanaan kunci memilih kunci secara rawak. Algoritma tandatangan menghantar tag apabila diberi kunci dan mesej. algoritma pengesahan digunakan untuk mengesahkan ketulenan mesej apabila diberi kunci dan teg; ia akan mengembalikan mesej **diterima** jika mesej dan teg adalah sahih dan tidak diubah, tetapi sebaliknya, ia akan mengembalikan mesej **ditolak.**

Sebagai contoh, pengirim menghantar mesej, seperti EFT, melalui algoritma MAC, yang menjana kunci dan melampirkan teg data MAC pada mesej. Penerima mendapat mesej, menjalankannya kembali melalui algoritma MAC dengan kunci yang sama dan mendapat teg data kedua. Mereka kemudiannya akan membandingkan teg data MAC ini dengan yang pertama dilampirkan pada mesej apabila ia dihantar. Jika kod adalah sama di kedua-dua hujungnya, penerima boleh mengandaikan dengan selamat bahawa integriti data mesej adalah utuh. Walau bagaimanapun, jika tidak, ini bermakna mesej itu telah diubah, diusik atau dipalsukan.

Walau bagaimanapun, mesej itu sendiri harus mengandungi beberapa data yang memastikan bahawa mesej ini hanya boleh dihantar sekali. Contohnya, MAC, cap masa atau nombor jujukan sekali boleh digunakan untuk menjamin bahawa mesej hanya boleh dihantar sekali. Jika tidak, sistem boleh terdedah kepada serangan ulang tayang, di mana penyerang memintas mesej selepas dinyahkod dan menghantarnya semula pada masa yang lain, mereplikasi keputusan asal dan menyusup ke dalam sistem.

## Kod Integriti Mesej (MIC)

Kadangkala, istilah kod integriti mesej (MIC) akan digunakan dan bukannya MAC. Ini paling kerap dilakukan dalam industri komunikasi, di mana MAC secara tradisinya bermaksud alamat kawalan akses media (alamat MAC). Walau bagaimanapun, MIC juga boleh digunakan untuk merujuk kepada **digest mesej,** yang tidak menggunakan kunci rahsia dengan cara yang sama seperti MAC, dan tidak boleh menawarkan tahap keselamatan yang sama tanpa penyulitan lanjut.

