---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Merkle Root (Kryptovaluutta)
description: Merkle-juuri sisältää tietoa jokaisesta yksittäisestä tapahtumahajautusarvosta, joka on koskaan ollut tietyssä lohkoketjun lohkossa.
---

# Merkle Root (Kryptovaluutta)
## Mikä on Merkle-juuri?

Merkle-juuri on kaikkien lohkoketjun lohkoon kuuluvien [tapahtumien](/blockchain) [hajautusarvo](/hash).

## Merklen juuren ymmärtäminen

Lohkoketju koostuu erilaisista lohkoista, jotka on linkitetty toisiinsa (tämä nimi lohkoketju). Hash-puu tai [Merkle-puu](/merkle-tree) koodaa lohkoketjun tiedot tehokkaalla ja turvallisella tavalla. Se mahdollistaa lohkoketjutietojen nopean varmentamisen sekä suurten tietomäärien nopean siirtämisen yhdestä tietokonesolmusta toiseen peer-to-peer blockchain -verkossa.

Jokaiseen blockchain-verkossa tapahtuvaan tapahtumaan liittyy hash. Näitä hajautusarvoja ei kuitenkaan tallenneta peräkkäisessä järjestyksessä lohkoon, vaan ne ovat puumaisen rakenteen muodossa siten, että jokainen hajautus on linkitetty emokseensa emo-lapsi-puun kaltaisen suhteen jälkeen.

Koska tiettyyn lohkoon on tallennettu lukuisia tapahtumia, myös kaikki lohkon tapahtumatiivisteet tiivistetään, mikä johtaa Merkle-juureen.

Harkitse esimerkiksi seitsemän tapahtuman lohkoa. Alimmalla tasolla (kutsutaan lehtitasoksi) on neljä tapahtumatiivistettä. Lehtitason yläpuolella olevalla tasolla on kaksi tapahtumatiivistettä, joista jokainen liittyy kahteen tiivisteeseen, jotka ovat niiden alapuolella lehtitasolla. Yläosassa (taso kaksi) on viimeinen tapahtuman tiiviste, jota kutsutaan juuriksi, ja se yhdistetään kahteen sen alapuolelle (tasolla yksi).

Käytännössä saat ylösalaisin käännetyn binääripuun, jossa jokainen puun solmu muodostaa yhteyden vain kahteen sen alapuolella olevaan solmuun (tästä syystä nimi "binääripuu"). Sen yläosassa on yksi juurihajautus, joka yhdistyy kahteen tason tiivisteeseen, joista kumpikin on jälleen yhteydessä kahteen tason kolmeen tiivisteeseen (lehtitasolla), ja rakenne jatkuu tapahtuman tiivistemäärän mukaan.

<!--AAFEB15A7406E8DD3ABDD652D7C85823-->

Hajautus alkaa alimman tason (lehtitason) solmuista, ja kaikki neljä tiivistettä sisältyvät siihen tasolla yksi linkitettyjen solmujen hajautusarvoon. Samoin tiivistys jatkuu tasolla yksi, mikä johtaa tiivisteiden tiivisteisiin, jotka ulottuvat korkeammille tasoille, kunnes se saavuttaa yhden yläjuuren tiivisteen.

Tätä juurihajautetta kutsutaan Merkle-juureksi, ja tiivisteiden puumaisen linkityksen vuoksi se sisältää kaikki tiedot jokaisesta lohkossa olevasta tapahtumahajautuskohdasta. Se tarjoaa yhden pisteen hajautusarvon, joka mahdollistaa kaiken kyseisessä lohkossa olevan validoinnin.

Jos esimerkiksi täytyy vahvistaa tapahtuma, jonka väitetään tulevan lohkosta #137, hänen tarvitsee vain tarkistaa lohkon Merkle-puu ilman huolta siitä, että lohkoketjun muissa lohkoissa, kuten lohkossa #136 tai #, tarkistetaan mitään. 138.

<!--4861E8697637B7236BF11AA57D958059-->

Anna Merkle-juuri, mikä nopeuttaa vahvistusta entisestään. Koska se kuljettaa kaikki tiedot koko puusta, tarvitsee vain varmistaa tapahtuman hash, sen sisarussolmu (jos sellainen on) ja jatkaa sitten ylöspäin, kunnes se saavuttaa huipun.

Merkle-puu ja Merkle-juurimekanismi vähentävät olennaisesti suoritettavan tiivistyksen määrää, mikä mahdollistaa nopeamman tarkistuksen ja tapahtumat.

##Kohokohdat

- Merklen juuret ovat keskeisiä kryptovaluuttojen, kuten bitcoinin ja eetterin, ylläpitoon tarvittavassa laskennassa.

- Merkle-juuria käytetään kryptovaluutoissa varmistamaan, että vertaisverkon vertaisverkkojen väliset tietolohkot ovat kokonaisia, vahingoittumattomia ja muuttumattomia.

- Merkle-juuri on yksinkertainen matemaattinen tapa tarkistaa Merkle-puun tiedot.

