---
keywords: Investing,Cryptocurrency,Blockchain
title: Block (Bitcoin Block)
description: Lohkot ovat tietokannan tietorakenteita, joihin kryptovaluuttatapahtumatiedot tallennetaan pysyvästi; kerran kirjoitettua sitä ei voi muuttaa tai poistaa.
---

# Block (Bitcoin Block)
## Mikä on lohko (Blockchain Block)?

Lohkot ovat lohkoketjutietokannan tietorakenteita, joihin kryptovaluuttalohkoketjun tapahtumatiedot tallennetaan pysyvästi. Lohko tallentaa osan tai kaikki viimeisimmät tapahtumat, joita verkko ei ole vielä vahvistanut. Kun tiedot on vahvistettu, lohko suljetaan. Sitten luodaan uusi lohko uusille tapahtumille, jotka tehdään ja vahvistetaan.

Lohko on siis pysyvä tietueiden varasto, jota ei voi muuttaa tai poistaa kerran kirjoitettuaan.

## Kuinka lohko (Blockchain Block) toimii

Lohkoketjuverkosto on todistamassa suurta transaktiotoimintaa [.](/blockchain) Kun niitä käytetään kryptovaluutoissa, kirjaaminen näistä tapahtumista auttaa järjestelmää seuraamaan, kuinka paljon niitä käytettiin tai ei käytetty ja mitkä osapuolet olivat mukana. Tietyn ajanjakson aikana tehdyt tapahtumat tallennetaan lohkoksi kutsuttuun tiedostoon, joka on lohkoketjuverkoston perusta.

Lohko tallentaa tietoa. Lohkoon sisältyy monia tietoja, mutta se ei vie paljon tallennustilaa. Lohkot sisältävät yleensä nämä elementit, mutta ne voivat vaihdella eri tyyppien mukaan:

- **Maaginen numero**: Numero, joka sisältää tietyt arvot, jotka tunnistavat kyseisen lohkon osaksi tietyn kryptovaluutan verkkoa.

- **Blocksize**: Asettaa lohkon kokorajoituksen siten, että siihen voidaan kirjoittaa vain tietty määrä tietoa.

- **Block header**: Sisältää tietoja lohkosta.

- **Tapahtumalaskuri**: Numero, joka ilmaisee, kuinka monta tapahtumaa lohkoon on tallennettu.

- **Tapahtumat**: Luettelo kaikista lohkon tapahtumista.

Tapahtumaelementti on suurin, koska se sisältää eniten tietoa. Sitä seuraa tallennuskoossa lohkootsikko, joka sisältää seuraavat alielementit:

- **Versio**: Käytetty kryptovaluuttaversio.

- **Edellinen lohko hash**: Sisältää edellisen lohkon otsikon tiivisteen (salatun numeron).

- **Hash Merkle-juuri**: Tapahtuman tiiviste nykyisen lohkon [Merkle-puussa .](/merkle-tree)

- **Aika**: Aikaleima lohkon sijoittamiseksi lohkoketjuun.

- **Bits**: Kohdehajautuksen vaikeusluokitus, joka ilmaisee vaikeutta ratkaista epäkohta.

- **Nonce**: Salattu numero, joka kaivostyöntekijän on ratkaistava lohkon vahvistamiseksi ja sen sulkemiseksi.

Yhtä 32-bittistä numeroa otsikossa kutsutaan nonceksi – kaivosohjelma käyttää satunnaisia lukuja "arvaamaan" tiivisteen nonce- [arvon](/hash). Kun nonce on varmistettu, hash ratkaistaan, kun nonce tai sitä pienempi luku arvataan. Sitten verkko sulkee kyseisen lohkon, luo uuden, jossa on otsikko, ja prosessi toistuu.

eri mekanismeja käytetään yhteisymmärrykseen pääsemiseksi; Suosituin kryptovaluutoista on [proof-of-work](/proof-work) (PoW), ja proof-of-stake (PoS) on yhä suositumpi, koska energiankulutus on pienempi kuin PoW.

## Kaivostoiminnan suhde lohkoihin

Louhinta on termi, jota käytetään ratkaisemaan numero, joka on nonce, ainoa luku, jota voidaan muuttaa lohkon otsikossa. Se on myös prosessi, jota kryptovaluutan verkko käyttää, jos protokollassa käytetään työtodistusta.

Kryptovaluutan louhintaa pidetään yleisesti monimutkaisena matemaattisena ongelmana; se on itse asiassa satunnaisluku, joka on luotu tiivistämällä. Hashing on prosessi, jossa tiedot salataan kryptovaluutan käyttämällä salausmenetelmällä. Esimerkiksi Bitcoin käyttää SHA256:ta salausalgoritmiinsa. Jotta kaivostyöntekijä generoisi "voittonumeron", kaivosohjelman on käytettävä SHA 256:ta satunnaislukujen tiivistämiseen ja sijoittamiseen nonce-lukuihin nähdäkseen, onko se täsmäävä.

> Satunnaislukuhajasteen ratkaiseminen proof-of-work-protokollalla vie niin paljon energiaa ja laskentatehoa. Laaja kaivostyöntekijöiden verkosto ja tarpeeksi energiaa pienelle maalle tarvitaan sen ylläpitämiseksi.

>

Vaikeus piilee siinä, että kaikki aiemmat lohkootsikot salataan satunnaisesti. Siten nykyinen lohkon otsikko on satunnaisesti generoitu salattu numero, joka perustuu edellisten lohkojen satunnaisesti generoituihin salattuihin lukuihin ja nykyisen lohkon tietoon.

## Muut Block- ja Blockchain-käytöt

Koska useimmat lohkoketjun määritelmät viittaavat Bitcoiniin, koska se oli ensimmäinen kryptovaluutta, joka käytti sitä, monet ihmiset yhdistävät lohkot ja lohkoketjut Bitcoiniin. Kuitenkin myös muut kryptovaluutat käyttävät lohkoja ja lohkoketjuja. On tärkeää huomata, että Ethereumin verkossa on kryptovaluutta nimeltä eetteri, joka käyttää myös lohkoja ja lohkoketjua.

Ethereum ja sen lohkoketju on kuitenkin suunniteltu useisiin käyttötarkoituksiin, jotka ulottuvat paljon muuhunkin kuin kryptovaluuttaan. Ethereumin avulla on kehitetty esimerkiksi ei-korjattavia tokeneita, älykkäitä sopimuksia, hajautettuja rahoitussovelluksia ja paljon muuta.

##Kohokohdat

- Lohkoja ja lohkoketjuja eivät käytä yksinomaan kryptovaluutat. Niillä on myös monia muita käyttötarkoituksia.

- Lohkot tunnistetaan pitkillä numeroilla, jotka sisältävät salattuja tapahtumatietoja aiemmista lohkoista ja uusia tapahtumatietoja.

- Lohkot ja niiden sisältämät tiedot on tarkistettava verkon toimesta ennen kuin uusia lohkoja voidaan luoda.

- Lohko on paikka lohkoketjussa, johon tiedot tallennetaan ja salataan.

##UKK

### Mikä on Blockchain yksinkertaisilla sanoilla?

Lohkoketju on tietokanta, joka tallentaa ja salaa tiedot linkitetyllä tavalla, jotta aiempia tietoja ei voida muuttaa, ja ryhmä tarkistaa mahdolliset merkinnät ennen kuin ne on viimeistelty konsensuksella - sopimuksen tietojen oikeellisuudesta.

### Mihin lohkoketjuja käytetään?

Lohkoketjuja käytetään kryptovaluutoissa, hajautetuissa rahoitussovelluksissa, ei-vaihtokelpoisissa tokeneissa, ja lisää käyttötarkoituksia kehitetään jatkuvasti.

### Kuinka Blockchain-lohko luodaan?

Lohkoja luodaan, kun kaivostyöntekijät tai lohkon tarkistajat vahvistavat onnistuneesti lohkootsikon salatut tiedot, mikä kehottaa luomaan uuden lohkon.

