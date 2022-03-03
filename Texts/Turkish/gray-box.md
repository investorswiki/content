---
keywords: Investing,Laws and Regulations,Cybersecurity
title: Gri Kutu
description: Gri kutu, dahili çalışmaları hakkında sınırlı bilgiye sahip yazılımın test edilmesidir.
---

# Gri Kutu
## Gri Kutu Nedir?

Gri kutu, yazılımın dahili işleyişi hakkında sınırlı bilgi sahibi olduğu durumlarda test edilmesi anlamına gelir. Gri kutu testi, bir hedefin güvenlik ağının güçlü ve zayıf yönlerini belirlemek için bilgisayar korsanının sınırlı bilgi kullanması gereken etik bir bilgisayar korsanlığı tekniğidir.

## Gri Kutuları Anlama

Gri kutu, test cihazının yazılım kodunun dahili mantığını ve yapısını incelediği beyaz kutu testi ile test cihazının yazılımın kodu hakkında hiçbir şey bilmediği [kara kutu testinin melezidir.](/blackbox) Gri kutu testini anlamak için önce kara kutu testini ve beyaz kutu testini anlamamız gerekir.

### Kara Kutu ve Beyaz Kutu Testi

Kara kutu testi, kullanıcı tarafından yapılan girdilerden ve bu girdiler göz önüne alındığında yazılımın hangi çıktıyı ürettiğinden başka bir şeye bakmaz. Kara kutu testi, herhangi bir programlama dili bilgisi veya diğer teknik detaylar gerektirmez. Sistem testi ve kabul testlerinde kullanılan bir üst düzey test türüdür. Yazılım mühendisleri, kara kutu testi gerçekleştirmek için bir yazılım gereksinimi belirtimi (SRS) belgesine ihtiyaç duyar. Bu test , kara kutu test cihazının çıktıların girdilerden nasıl üretildiğini bilmediği bir [son kullanıcı perspektifi alır.](/end-user)

Beyaz kutu testi, ilgili programlama dili de dahil olmak üzere yazılım oluşturmak için kullanılan teknikler ve platformlar hakkında derinlemesine bilgi gerektirir. Birim testi ve gösterge testinde kullanılan düşük seviyeli bir test türüdür. Yazılım mühendislerinin, kaynak kodunu anlayabilmeleri için uygulamayı oluşturmak için kullanılan programlama dilini anlamaları gerekir. Beyaz kutu testinin birincil amaçları, güvenliği güçlendirmek, girdi ve çıktıların uygulamada nasıl aktığını incelemek ve tasarım ile kullanılabilirliği geliştirmektir. Beyaz kutu test cihazı, belirli bir girdiden beklenen çıktıyı almadığında, sonucun düzeltilmesi gereken bir hata olduğu düşünülür.

## Gri Kutu Testi Nasıl Çalışır?

Gri kutu testi, her birinin tek başına elde edebileceğinden daha iyi bir sonuç elde etmek için hem siyah hem de beyaz kutu testinin önemli bileşenlerini içerir. Hem son kullanıcılar hem de geliştiriciler, bir uygulamanın kaynak kodu hakkında sınırlı (kısmi) bilgiyle gri kutu testi gerçekleştirir. Gri kutu testi manuel veya otomatik olabilir. Kara kutu testinden daha kapsamlı ve daha fazla zaman alıcıdır, ancak beyaz kutu testi kadar kapsamlı veya zaman alıcı değildir. Gri kutu test cihazları, ayrıntılı tasarım belgeleri gerektirir.

Gri kutu testi, girdileri, çıktıları, ana yolları ve alt işlevleri tanımlamayı içerir. Daha sonra alt işlevler için girdiler ve çıktılar geliştirmeye, alt işlevler için test senaryoları yürütmeye ve bu sonuçları doğrulamaya geçer.

## Gri Kutu Örneği

Gri kutu test cihazı, bir web sitesindeki bağlantıları kontrol edebilir ve düzeltebilir. Bir bağlantı çalışmazsa, testçi bağlantının çalışmasını sağlamak için [HTML kodunu](/html) değiştirir, ardından bağlantının çalışıp çalışmadığını görmek için kullanıcı arayüzünü yeniden kontrol eder. Gri kutu test cihazı, çevrimiçi bir hesap makinesini de test edebilir. Test cihazı, girdileri (1+1, 2*2, 5-4 ve 15/3 gibi matematiksel formüller) tanımlar ve ardından hesap makinesinin bu girdilere göre doğru çıktıları sağlayıp sağlamadığını kontrol eder. Gri kutu test cihazının hesap makinesinin HTML koduna erişimi vardır ve herhangi bir hata tespit edilirse bunu değiştirebilir.

Gri kutu testi, hem uygulamanın kullanıcı arayüzüne veya sunum katmanına hem de dahili çalışmalarına veya koduna bakar. Esas olarak entegrasyon testi ve sızma testinde kullanılır ancak [algoritma](/algorithm) testi için uygun değildir. Gri kutu testi genellikle matris testi, [regresyon](/regression) testi, ortogonal dizi testi ve model testi gibi teknikler aracılığıyla bir uygulamanın kullanıcı arayüzünü, güvenliğini veya çevrimiçi işlevselliğini test etmek için kullanılır. Gri kutu test cihazlarının bağlama özgü sorunları belirlemesi daha olasıdır.

“Gri”, test cihazının uygulamanın dahili çalışmalarını görme konusundaki kısmi yeteneğini ifade eder. “Beyaz”, yazılımın iç işleyişini arayüzünden görme yeteneğini ifade eder ve “siyah”, yazılımın iç işleyişini görememeyi ifade eder. Gri kutu testi bazen yarı saydam test olarak adlandırılırken, beyaz kutu testi bazen net test olarak adlandırılır ve kara kutu testi opak test olarak da adlandırılabilir.

## Öne Çıkanlar

- Gri kutu testi, esasen beyaz kutu (tam bilgi) ve kara kutu (bilgisiz) metodolojilerinin bir karışımıdır.

- Gri kutu testi, yazılım hatalarını keşfetmeye veya temeldeki yazılım hakkında bazı sınırlı bilgilerin önceden bilindiği açıklardan yararlanmaya yönelik bir tekniktir.

- Bu "etik korsanlık" biçimi, yazılım geliştiricilerin, kötü niyetli saldırganların bu açıklardan yararlanmasını önlemek için düzeltmeler ve yamalar oluşturmasına olanak tanır.

