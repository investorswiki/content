---
keywords: Investing,Cryptocurrency,Altcoins
title: Kohde Hash
description: Kohdehajautus vaikeuttaa kryptovaluutan louhintaa käyttämällä proof-of-work (PoW) -lohkoketjujärjestelmää.
---

# Kohde Hash
## Mikä on kohdehajautus?

Kryptovaluutan louhinnassa kohdehajautus on numeerinen arvo, joka tiivistetyn [lohkon otsikon](/block-header-cryptocurrency) on oltava pienempi tai yhtä suuri, jotta kaivostyöntekijälle voidaan myöntää uusi lohko. Lohkootsikot tunnistavat yksittäiset lohkot lohkoketjussa.

Kryptovaluutan louhinta tarkoittaa kryptovaluutan keräämistä palkkiona tekemästäsi työstä. Tämän työn luonteena on varmistaa tietyn kryptovaluutan liiketoimien laillisuus. Tällä tavalla kryptovaluuttakaivostyöntekijät ovat pohjimmiltaan tilintarkastajia. Kun louhit, voit ansaita kryptovaluuttaa ilman, että sinun tarvitsee laittaa rahaa siihen.

Kohdehajautusarvoa käytetään syötteen vaikeusasteen määrittämisessä ja sitä voidaan säätää sen varmistamiseksi, että lohkot käsitellään tehokkaasti. Esimerkiksi kohdehajautusarvoja käytetään kryptovaluutoissa, jotka käyttävät proof-of-work (PoW) -järjestelmää asettamaan nykyisen [kaivosvaikeuden](/difficulty-cryptocurrencies) [y](/difficulty-cryptocurrencies) (mukaan lukien Bitcoin). Jos kryptovaluutta käyttää louhintaan eri järjestelmää, se ei välttämättä vaadi kohdehajautusta.

## Kuinka kohdehajautus toimii

[Kryptovaluutat](/cryptocurrency) luottavat lohkoketjujen käyttöön, jotka sisältävät kaikkien kryptovaluuttojen tapahtumien historian [.](/blockchain) Nämä tapahtumat on [tiivistetty](/hash) tai kryptografisesti koodattu sarjaksi aakkosnumeerisia merkkejä. Hashing sisältää minkä tahansa pituisen tietojonon ottamisen ja sen suorittamisen algoritmin läpi, jolloin saadaan kiinteäpituinen tulos. Tulos on aina samanpituinen riippumatta siitä, kuinka suuri tai pieni syöte on (vaikka hashin permutaatioiden määrä on tähtitieteellisesti suuri). Jokainen lohko sisältää edellisen lohkootsikon tiivisteen.

Lohkoketjun validointia ja koodausta kutsutaan [kaivostoiminnaksi](/bitcoin-mining). Kaivostoimintaan kuuluu tietokoneiden käyttö hajautusalgoritmien suorittamiseen viimeisimmän lohkon käsittelemiseksi; tiedot, jotka käyttäjä tarvitsee kaivokseen, löytyvät lohkon otsikosta. Kryptovaluuttaverkko asettaa tälle tiivisteelle tavoitearvon, jota kutsutaan kohdehajaksi, ja kaivostyöntekijät yrittävät määrittää, mikä tämä arvo on testaamalla kaikkia mahdollisia arvoja.

Lohkon otsikko sisältää lohkon versionumeron, aikaleiman, edellisessä lohkossa käytetyn tiivisteen, [Merkle Roo](/merkle-root-cryptocurrency) [t :n tiivisteen](/merkle-root-cryptocurrency),. [nonce](/nonce) :n ja kohdehajasteen. Lohko luodaan ottamalla lohkon sisällön hajautusarvo, lisäämällä satunnainen numerojono (nonce) ja tiivistämällä lohko uudelleen.

Jos hash täyttää kohteen vaatimuksen, lohko lisätään lohkoketjuun. Ratkaisujen pyöräilyä noncen arvaamiseksi kutsutaan [todisteeksi työstä](/proof-work) (PoW), ja kaivostyöntekijälle, joka pystyy löytämään arvon, myönnetään lohko ja maksetaan kryptovaluuttana.

## Erityisiä huomioita

### Kohdista hajautus Bitcoinille

Bitcoin käyttää SHA-256 hash-algoritmia. Tämä algoritmi luo todennettavissa olevia satunnaislukuja tavalla, joka vaatii ennustettavan määrän tietokoneen käsittelytehoa.

Lohkon louhinta vaatii kaivostyöntekijän tuottamaan arvon (nonce), joka tiivistyksen (salakirjoituskoodauksen) jälkeen on pienempi tai yhtä suuri kuin viimeisimmässä bitcoin-verkon hyväksymässä lohkossa käytetty arvo. Tämä luku on välillä 0 - (pienin vaihtoehto) ja 256 bittiä (suurin vaihtoehto), mutta se ei todennäköisesti koskaan ole suurin luku.

Koska kohdehaja voi olla valtava määrä, kaivostyöntekijän on ehkä testattava suuri määrä arvoja ennen onnistumista. Epäonnistuneen kaivostyöntekijän on odotettava seuraavaa lohkoa (siksi kaivostyöntekijöitä, jotka löytävät hash-ratkaisun, verrataan kilpailun tai loton voittajiin).

Tavoitetiivistettä säädetään ajoittain. Uuden kohteen luomiseen käytetyillä hash-funktioilla on erityisiä ominaisuuksia, jotka on suunniteltu tekemään lohkoketjusta (ja sen kryptovaluuttasta) turvallinen. Tämä prosessi on deterministinen, mikä tarkoittaa, että se tuottaa saman tuloksen joka kerta, kun samaa syötettä käytetään. Se on riittävän nopea, jotta hajautuksen palauttaminen syötteelle ei kestä liian kauan. Se tekee myös syötteen määrittämisestä erittäin vaikeaa, varsinkin suurille numeroille, ja tekee pienet muutokset syötteeseen johtavat hyvin erilaiseen hajautustulokseen.

## Kohokohdat

- Kohdehajautusarvoja käytetään kryptovaluutoissa, jotka käyttävät proof-of-work (PoW) -järjestelmää nykyisen kaivosvaikeuden asettamiseen (mukaan lukien Bitcoin); jos kryptovaluutta käyttää erilaista järjestelmää louhintaan, se ei välttämättä vaadi kohdehajautusta.

- Kryptovaluutan louhinnassa kohdehajautus on numeerinen arvo, joka tiivistetyn lohkootsikon (jota käytetään lohkoketjun yksittäisten lohkojen tunnistamiseen) on oltava pienempi tai yhtä suuri, jotta kaivostyöntekijälle voidaan myöntää uusi lohko.

- Bitcoin-verkko säätää louhinnan vaikeutta nostamalla tai laskemalla kohdehajautusarvoa, jotta uusien lohkojen välillä säilyisi keskimäärin 10 minuutin väli.

