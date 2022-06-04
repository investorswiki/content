---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Todiste kapasiteetista ( kryptovaluutta )
description: Proof of Capacity on konsensusmekanismi, joka käyttää kaivossolmun kiintolevytilaa päättääkseen kaivosoikeudet blockchain-verkossa.
---

# Todiste kapasiteetista ( kryptovaluutta )
## Mikä on kapasiteetin todiste (PoC) kryptovaluutoille?

Kapasiteetin todiste (PoC) on lohkoketjuissa käytetty [konsensusmekanismialgoritmi,](/consensus-mechanism-cryptocurrency) jonka avulla verkon [kaivoslaitteet](/bitcoin-mining) voivat käyttää käytettävissä olevaa kiintolevytilaa kaivosoikeuksien päättämiseen ja tapahtumien vahvistamiseen. Tämä on ristiriidassa kaivoslaitteen laskentatehon käyttämiselle (kuten [proof of work](/proof-work) -algoritmissa) tai kaivosmiehen osuukselle kryptovaluutoissa (kuten [panoksen todistamisalgoritmissa](/proof-stake-pos) ).

## Kapasiteetin todisteiden ymmärtäminen

Kapasiteetin todistaminen nousi yhdeksi monista vaihtoehtoisista ratkaisuista korkean energiankulutuksen ongelmaan proof of work (PoW) -järjestelmissä ja kryptovaluuttojen hamstraamiseen panostodistusjärjestelmissä (PoS).

Kapasiteetin todistus antaa lohkoketjuverkon kaivoslaitteiden, joita kutsutaan myös solmuiksi, [käyttää](/blockchain) kiintolevynsä tyhjää tilaa käytettävissä olevien [kryptovaluuttojen louhimiseen](/cryptocurrency).

Sen sijaan, että lohkootsikon numeroita muutetaan toistuvasti ja ratkaisuarvoa hajautettaisiin toistuvasti, kuten PoW-järjestelmässä, PoC toimii tallentamalla luettelon mahdollisista ratkaisuista kaivoslaitteen kiintolevylle jo ennen kaivostoiminnan alkamista.

Mitä suurempi kiintolevy on, sitä enemmän mahdollisia ratkaisuarvoja voidaan tallentaa kiintolevylle, sitä enemmän kaivostyöntekijällä on mahdollisuuksia löytää vaadittu hash-arvo luettelostaan, jolloin on enemmän mahdollisuuksia voittaa kaivospalkinto.

Vertailun vuoksi voidaan todeta, että jos lottopalkinnot perustuvat useimpien voittolipun numeroiden yhteensovittamiseen, niin pelaajalla, jolla on pidempi luettelo mahdollisista ratkaisuista, on paremmat mahdollisuudet voittaa. Lisäksi pelaaja saa käyttää arpajaisten lohkonumeroita yhä uudelleen ja uudelleen toistuvasti.

[Burstcoin](/burstcoin) on kryptovaluutta, joka käyttää kapasiteettitodistusjärjestelmää. Muita sitä käyttäviä kolikoita ovat Storj, Chia ja SpaceMint.

## Miten PoC toimii: Piirustus ja louhinta

Kapasiteetin todisteprotokolla sisältää kaksivaiheisen prosessin, joka sisältää piirtämisen ja louhinnan.

Ensin kiintolevy piirretään: luettelo kaikista mahdollisista [nonce-](/nonce) arvoista luodaan tietojen toistuvan hajautustoiminnon avulla, mukaan lukien kaivostilin. Jokainen tällainen nonce sisältää 8192 tiivistettä, jotka on numeroitu välillä 0 - 8191. Kaikki tiivisteet yhdistetään "kauhaksi", mikä tarkoittaa, että vierekkäiset tiivisteet yhdistetään kahden pariksi. Esimerkiksi hash 0 ja 1 muodostavat kauhan 0, hash 2 ja 3 muodostavat hash 1: n ja niin edelleen.

Toinen vaihe sisältää varsinaisen kaivosharjoituksen, jonka aikana kaivosmies laskee kauhaluvun. Jos esimerkiksi kaivosmies aloittaa kaivostoiminnan ja luo kauhan numeron 38, kaivosmies siirtyisi sitten nonce 1:n kauhaan numero 38 ja laskee määräajan arvon tämän kauhan tietojen perusteella.

Prosessi toistetaan määräajan laskemiseksi jokaiselle kaivostyöntekijän kiintolevyllä pidetylle poikkeamalle. Kaikkien määräaikojen laskemisen jälkeen kaivosmies valitsee sen, jolla on vähimmäismääräaika.

Määräaika edustaa aikaa sekunteina, jonka täytyy kulua viimeisestä kappaleesta, ennen kuin kaivostyöntekijä saa takoa uuden kappaleen. Jos kukaan muu ei ole väärentänyt lohkoa tänä aikana, kaivosmies voi väärentää lohkon ja lunastaa lohkopalkkion.

Jos esimerkiksi kaivostyöntekijä X ehdottaa 36 sekunnin vähimmäismääräaikaa eikä kukaan muu kaivostyölä voi väärentää lohkoa seuraavan 36 sekunnin kuluessa, X varmistaa mahdollisuuden väärentää seuraava lohko ja saada palkkion.

## Kapasiteetin todistamisen plussat ja miinukset

PoC:lla on useita etuja PoW- ja PoS-järjestelmiin verrattuna sekä joitain tärkeitä haittoja, kuten:

<h5><a href="">TTT</a></h5>

## Kohokohdat

- PoC-järjestelmän tärkein etu on sen tehokkuus verrattuna proof-of-work (PoW) ja proof-of-stake (PoS) järjestelmiin.

- Kapasiteettitodistuksella toimivia lohkoketjuja ovat Storj, Burst, Chia ja SpaceMint.

- Kapasiteetin todisteet (PoC) -todennusjärjestelmät käyttävät laitteen kiintolevyn vapaata tilaa tallentaakseen ratkaisuja kryptovaluutan hajautusongelmaan.

