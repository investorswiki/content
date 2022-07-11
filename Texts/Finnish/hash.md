---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: Hash
description: Hash. Hajautusfunktion tuottama tulos sen jälkeen, kun tieto on kartoitettu. Voidaan kutsua myös hash-arvoksi, hash-koodiksi tai tiivisteeksi.
---

# Hash
Salaustekniikassa sana [hash](/cryptography) viittaa tulosteen, jonka hash-funktio tuottaa sen jälkeen, kun tieto on lähetetty (kartoitettu) sen kautta. Hajautusfunktioiden tuottamaa tulosta voidaan kutsua myös hash-arvoksi, hash-koodiksi tai tiivisteeksi.

Jotta ymmärtäisit paremmin, mitä hash on, kannattaa keskustella siitä, mitä hash-funktiot ovat ja miten ne toimivat.

Hash-funktiot ovat matemaattisia [algoritmeja](/algorithm),. jotka muuntavat minkä tahansa koon syötearvon kiinteän kokoiseksi tulosteeksi (hash). Useimmissa tapauksissa tulos koostuu heksadesimaaliluvusta. Tämä tarkoittaa, että tiiviste merkitään usein numeroiden (0–9) ja kirjainten (a–f) yhdistelmänä.

Jos esimerkiksi käytämme syöttöarvona sanaa "Binance" ja yhdistämme sen SHA-256-tiivistefunktion kautta, palautettava tulosarvo (tai hash) on:

f1624fcc63b615ac0e95daf9ab78434ec2e8ffe402144dc631b055f711225191

Huomaa, että ei ole väliä kuinka monta kertaa suoritamme tämän toiminnon, tulos on aina sama (niin kauan kuin syöte ei muutu).

Toisaalta mikä tahansa pieni muutos syötteeseen saa tiivistefunktion palauttamaan täysin erilaisen tiivisteen tulosteena. Jos esimerkiksi lähetämme sanan "binance" sanan "Binance" sijaan, tuloksena olisi seuraava hash:

59bba357145ca539dcd1ac957abc1ec5833319ddcae7f5e8b5da0c36624784b2

Hashista on hyötyä tiettyjen tietojen oikeellisuuden tarkistamisessa paljastamatta, mitä tieto on. Käytännössä hash-funktioita voidaan soveltaa erilaisiin skenaarioihin. Muutamia käyttötapauksia ovat tietokantahaut, suurten tiedostojen analyysit ja tietojen hallinta.

Yhdistettynä salaustekniikoihin meillä on ns. kryptografiset hajautusfunktiot. Näitä käytetään laajasti tietoturvassa ja ne ovat olennainen osa useimpia lohkoketjuverkkoja.

Esimerkiksi Bitcoin-lohkoketjussa on monia toimintoja, joihin liittyy hajautus, ja nämä ovat tärkeitä louhintaprosessissa.

## Kohokohdat

- Hash on funktio, joka täyttää salatut vaatimukset, joita tarvitaan lohkoketjun laskennan ratkaisemiseksi.

- Hash, kuten nonce tai ratkaisu, on blockchain-verkon selkäranka.

- Hash on kehitetty lohkootsikon sisältämien tietojen perusteella.

- Hashit ovat kiinteän pituisia, koska on lähes mahdotonta arvata tiivisteen pituutta, jos joku yrittäisi murtaa lohkoketjun.

- Sama data tuottaa aina saman hajautusarvon.

## UKK

### Miten hash-arvo lasketaan?

Hajautusfunktio käyttää monimutkaisia matemaattisia algoritmeja, jotka muuntavat mielivaltaisen pituiset tiedot kiinteän pituisiksi tiedoiksi (esimerkiksi 256 merkkiä). Jos muutat yhtä bittiä missä tahansa alkuperäisessä tiedossa, koko hash-arvo muuttuu, mikä tekee siitä hyödyllisen digitaalisten tiedostojen ja muiden tietojen oikeellisuuden tarkistamisessa.

### Mihin tiivisteitä käytetään lohkoketjuissa?

Hasheja käytetään useissa lohkoketjujärjestelmän osissa. Ensinnäkin jokainen lohko sisältää edellisen lohkon lohkootsikon tiivisteen [,](/block-header-cryptocurrency) mikä varmistaa, että mitään ei ole peukaloitu, kun uusia lohkoja lisätään. Salausvaluutan louhinta [proof-of-](/proof-work) workin (PoW) avulla hyödyntää lisäksi satunnaisesti luotujen lukujen hajautusarvoa, jotta saadaan tietty hajautusarvo, joka sisältää sarjan etunollia. Tämä mielivaltainen toiminto on resurssivaltainen, mikä tekee huonon toimijan vaikeaksi ohittaa verkkoa.

### Mikä on hajautusfunktio?

Hash-funktiot ovat matemaattisia toimintoja, jotka muuntavat tai "kartoivat" tietyn tietojoukon kiinteän kokoiseksi bittijonoksi, joka tunnetaan myös nimellä "hash-arvo".

