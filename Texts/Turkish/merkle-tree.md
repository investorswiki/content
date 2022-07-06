---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: merkle ağacı
description: merkep ağacı. İşlemeyi daha basit hale getirmek için büyük miktarda veriyi organize etmenin ve yapılandırmanın bir yolu. Karma tabanlı bir veri yapısı.
---

# merkle ağacı
Merkle ağacı, işlenmesini daha kolay hale getirmek için büyük miktarda veriyi organize etmenin ve yapılandırmanın bir yoludur. Kripto para birimi ve [blok zinciri söz konusu olduğunda](/blockchain),. Merkle ağacı, işlem verilerini kaynaklara daha az ihtiyaç duyacak şekilde yapılandırmak için kullanılır.

Bir Merkle ağacı yapısında bir kripto para birimi işlemi yapıldığında, hash edilir ve ardından eşdeğer bir hash değeri verilir. Merkle ağacında her işlem hash edildikten sonra üretilen hash değerleri başka bir hash değeri ile eşleştirilir ve ardından tekrar hashlenir. Örneğin, 'AB' ve 'AC' karma değerleri, 'ABC' oluşturmak için birleştirilir.

Bu hash değerleri eşleştirme işlemi, nihai bir hash değeri üretilene kadar tekrarlanır. Nihai karma değer olan Merkle kökü, içerdiği tüm işlemlerin bir özetini sağlar. Merkle kök özeti daha sonra blok başlığına eklenir.

####Veri güvenliği

Bir Merkle ağaç yapısı, bir [bloktaki işlemlerin erişimi kolay bir kaydını sağlar](/block). Bu nedenle, bir bloktaki verilerin değiştirilip değiştirilmediğini veya değiştirilip değiştirilmediğini kontrol etmek çok basittir. Bu doğrudur, çünkü Merkle ağacındaki bir işlemde (veya diğer ilgili verilerde) herhangi bir değişiklik, tamamen farklı bir karşılık gelen Merkle köküne yol açacaktır.

#### Kaynakların verimli kullanımı

Kripto para birimleri Merkle ağaçlarını kullanmasaydı, her doğrulama talebi ağ üzerinden çok büyük miktarda bilgi gönderilmesini gerektirirdi. Bir Merkle ağacında işlem verilerinin yapılandırılması, kaynakların çok daha verimli bir şekilde kullanılmasıdır. Karma işlem verileri bir Merkle kökünde doğrulanabileceğinden, düğümler arasında çok daha az bilgi gönderilmesini ve dolayısıyla genel veri bütünlüğünü analiz etmek için daha az bilgi işlem gücü gerektirdiğinden, bir işlemin doğrulanması defterin tam bir kopyasını gerektirmez.

Başka bir deyişle, bir Merkle ağaç yapısı, kullanıcıların tüm blok zincirini indirme sürecinden geçmek zorunda kalmadan bir bloğa bireysel bir işlemin dahil edildiğini doğrulamasını sağlar. Teknoloji, kripto para birimlerinin işlem verilerini organize etmesi ve olduğu kadar verimli çalışması için önemli bir araçtır. Merkle ağaçları olmadan, kaynaklara olan daha fazla talebin ağa daha az sayıda [düğüm](/node) katılmasıyla sonuçlanması muhtemeldir.

