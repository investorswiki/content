---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: merkle puu
description: merkle puu. Tapa järjestää ja jäsentää suuria tietomääriä, jotta se on helpompi käsitellä. Hajautuspohjainen tietorakenne.
---

# merkle puu
Merkle-puu on tapa järjestää ja jäsentää suuria tietomääriä, jotta sen käsittely on helpompaa. Kryptovaluutan ja [lohkoketjun](/blockchain) tapauksessa Merkle-puuta käytetään tapahtumatietojen jäsentämiseen resursseja vähemmän vaativalla tavalla.

Kun kryptovaluuttatapahtuma tehdään Merkle-puurakenteessa, se tiivistetään ja sille annetaan sitten vastaava hajautusarvo. Kun jokainen tapahtuma on tiivistetty Merkle-puussa, tuotetut tiivistearvot yhdistetään toiseen hash-arvoon ja tiivistetään sitten uudelleen. Esimerkiksi hajautusarvot "AB" ja "AC" yhdistetään luomaan "ABC".

Tätä hajautusarvojen yhdistämisprosessia toistetaan, kunnes lopullinen hajautusarvo on tuotettu. Lopullinen hash-arvo, Merkle-juuri, tarjoaa yhteenvedon kaikista sen sisältämistä tapahtumista. Merklen juuriyhteenveto lisätään sitten lohkon otsikkoon.

####Tietoturva

Merkle-puurakenne tarjoaa helposti käytettävän tietueen [lohkon tapahtumista](/block). Joten on erittäin helppoa tarkistaa, onko lohkon tietoja muutettu tai peukaloitu. Tämä on totta, koska mikä tahansa muutos tapahtumaan (tai mihin tahansa muuhun asiaan liittyvään dataan) Merkle-puussa johtaisi täysin erilaiseen vastaavaan Merkle-juureen.

#### Resurssien tehokas käyttö

Jos kryptovaluutat eivät käyttäisi Merkle-puita, jokainen varmistuspyyntö edellyttäisi valtavien tietomäärien lähettämistä verkon yli. Tapahtumatietojen strukturointi Merkle-puuhun on paljon tehokkaampaa resurssien käyttöä. Tapahtuman vahvistaminen ei vaadi täydellistä kopiota reskontrasta, koska tiivistetyt tapahtumatiedot voidaan varmentaa Merkle-juuressa, mikä vaatii paljon vähemmän informaation lähettämistä solmujen yli ja siten vähemmän laskentatehoa tietojen yleisen eheyden analysoimiseksi.

Toisin sanoen Merkle-puurakenne antaa käyttäjille mahdollisuuden varmistaa, että yksittäinen tapahtuma on sisällytetty lohkoon ilman, että heidän tarvitsee käydä läpi koko lohkoketjun latausprosessia. Tekniikka on tärkeä työkalu kryptovaluutoille tapahtumatietojen järjestämisessä ja toiminnassa yhtä tehokkaasti kuin ne toimivat. Ilman Merkle-puita on todennäköistä, että suurempi resurssien kysyntä johtaisi siihen , että verkkoon osallistuisi vähemmän [solmuja .](/node)

