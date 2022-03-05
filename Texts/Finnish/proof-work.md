---
keywords: Investing,Cryptocurrency,Bitcoin
title: Todistus työstä (PoW)
description: Todistus työstä kuvaa prosessia, joka mahdollistaa bitcoin-verkon pysymisen vahvana tehden louhintaprosessista tai tapahtumien kirjaamisesta vaikeaa.
---

# Todistus työstä (PoW)
## Mikä on työtodistus (PoW)?

Proof of work (PoW) kuvaa järjestelmää, joka vaatii merkittävän, mutta toteuttamiskelpoisen määrän vaivaa estääkseen laskentatehon turhaa tai haitallista käyttöä, kuten roskapostien lähettämistä tai palvelunestohyökkäysten käynnistämistä. Hal Finney muokkasi konseptin digitaalisen rahan turvaamiseen vuonna 2004 "uudelleenkäytettävän työn todisteen" avulla käyttämällä SHA-256-hajautusalgoritmia.

Vuonna 2009 käyttöönoton jälkeen Bitcoinista tuli ensimmäinen laajalti hyväksytty sovellus Finneyn PoW-ideasta (Finney oli myös ensimmäisen bitcoin-tapahtuman vastaanottaja). Todistaminen työstä on myös monien muiden kryptavaluuttojen perusta [,](/cryptocurrency) [mikä](/cryptocurrency) mahdollistaa turvallisen, hajautetun konsensuksen.

## Työtodistuksen ymmärtäminen

Tämä selitys keskittyy todisteisiin työstä sen toimiessa [bitcoin -](/bitcoin) verkossa. Bitcoin on digitaalinen valuutta, jota tukee eräänlainen [hajautettu pääkirja](/distributed-ledger-technology-dlt),. joka tunnetaan nimellä " [lohkoketju](/blockchain) ". Tämä reskontra sisältää tietueen kaikista bitcoin-tapahtumista, jotka on järjestetty peräkkäisiin "lohkoihin", joten kukaan käyttäjä ei saa käyttää omistustaan kahdesti. Peukaloinnin estämiseksi pääkirja on julkinen tai "jaettu"; muut käyttäjät hylkäävät muutetun version nopeasti.

Käytännössä käyttäjät havaitsevat peukaloinnin [tiivisteillä](/hash),. pitkillä numerosarjoilla, jotka toimivat todisteena työstä. Laita tietty tietojoukko hash-funktion kautta (bitcoin käyttää SHA-256:ta), ja se luo vain yhden hajautusarvon. Kuitenkin "lumivyöryefektin" vuoksi pienikin muutos mihin tahansa alkuperäisen datan osioon johtaa täysin tunnistamattomaan tiivisteeseen. Riippumatta alkuperäisen tietojoukon koosta, tietyn funktion luoma hash on samanpituinen. Hajautus on yksisuuntainen toiminto: sitä ei voida käyttää alkuperäisen tiedon hankkimiseen, vain sen tarkistamiseen, että tiivisteen luoneet tiedot vastaavat alkuperäisiä tietoja.

Minkä tahansa hashin luominen bitcoin-tapahtumien sarjalle olisi triviaalia nykyaikaiselle tietokoneelle, joten prosessin muuttamiseksi "työksi" bitcoin-verkko asettaa tietyn "vaikeusasteen". Tämä asetus on säädetty niin, että uusi lohko " [louhitaan](/bitcoin-mining) " - lisätään lohkoketjuun luomalla kelvollinen hajautus - noin 10 minuutin välein. Vaikeus asetetaan määrittämällä ["tavoite" tiivisteelle](/target-hash) : mitä pienempi tavoite on, sitä pienempi on kelvollisten tiivisteiden joukko ja sitä vaikeampaa on luoda sellainen. Käytännössä tämä tarkoittaa tiivistettä, joka alkaa hyvin pitkällä nollajonolla.

> Todiste työstä luotiin alun perin ehdotukseksi ratkaisuksi kasvavaan roskapostiongelmaan.

>

## Erityisiä huomioita

Koska tietty tietojoukko voi luoda vain yhden tiivisteen, kuinka kaivostyöntekijät varmistavat, että he luovat tiivisteen tavoitteen alapuolelle? Ne muuttavat syötettä lisäämällä kokonaisluvun, jota kutsutaan [nonce](/nonce) ("kerran käytetty numero"). Kun kelvollinen hash on löydetty, se lähetetään verkkoon ja lohko lisätään lohkoketjuun.

Kaivostoiminta on kilpailullinen prosessi, mutta se on enemmän arpajaisia kuin kilpailua. Keskimäärin joku tuottaa hyväksyttävän todistuksen työstä kymmenen minuutin välein, mutta kuka se on, on kenen tahansa arvattavissa. Kaivostyöntekijät kerääntyvät yhteen lisätäkseen mahdollisuuksiaan louhia lohkoja, mikä tuottaa transaktiomaksuja ja rajoitetun ajan palkkion vastikään luoduista bitcoineista.

Todistaminen työstä tekee lohkoketjun minkä tahansa osan muuttamisen erittäin vaikeaksi, koska tällainen muutos vaatisi kaikkien myöhempien lohkojen louhimista uudelleen. Se myös vaikeuttaa käyttäjän tai käyttäjäryhmän monopolisoida verkon laskentatehoa, koska hash-toimintojen suorittamiseen tarvittavat koneet ja teho ovat kalliita.

> Jos osa kaivosverkostoa alkaa hyväksyä vaihtoehtoista todistusta työstä, sitä kutsutaan [kovaksi haarukkaksi](/hard-fork).

>

## Esimerkki työtodistuksesta

Työn todistaminen edellyttää, että tietokone osallistuu satunnaisesti hajautustoimintoihin, kunnes se saavuttaa tulosteen, jossa on oikea vähimmäismäärä alkunollia. Esimerkiksi 4. joulukuuta 2020 louhitun lohkon #660000 hash on 00000000000000000008eddcaf078f12c69a439dde30dbb5aac3d9d94e9c18f6. Lohkopalkkio onnistuneesta hashista oli 6,25 BTC.

Tämä lohko sisältää aina 745 tapahtumaa, joihin liittyy hieman yli 1 666 bitcoinia, sekä edellisen lohkon otsikon. Jos joku yrittäisi muuttaa tapahtuman määrää jopa 0,000001 bitcoinilla, tuloksena oleva hash olisi tunnistamaton ja verkko hylkäsi huijausyrityksen.

## Työtodistuksia koskevat usein kysytyt kysymykset

### Mitä työtodistus tarkoittaa?

PoW edellyttää verkon solmujen osoittavan todisteita siitä, että ne ovat käyttäneet laskentatehoa (eli työtä), jotta päästään hajautetusti yksimielisyyteen ja estetään huonoja toimijoita ohittamasta verkkoa.

### Kuinka työtodistus vahvistaa kryptotapahtuman?

Itse työ on mielivaltaista. Bitcoinille se sisältää SHA-256-hajautusalgoritmien iteraatioita. Hajautuskierroksen "voittaja" kuitenkin kokoaa ja tallentaa tapahtumat mempoolista seuraavaan lohkoon. Koska "voittaja" valitaan satunnaisesti suhteessa tehtyyn työhön, se kannustaa kaikkia verkossa toimimaan rehellisesti ja kirjaamaan vain todellisia tapahtumia.

### Miksi kryptovaluutat tarvitsevat todisteita työstä?

Koska ne ovat suunnittelultaan hajautettuja ja vertaisverkkoja, lohkoketjut, kuten kryptovaluuttaverkot, vaativat jonkin tavan saavuttaa sekä konsensus että turvallisuus. Työn todistaminen on yksi tällainen menetelmä, joka tekee liian resurssiintensiivisestä verkon ohittamisesta. On myös muita todistusmekanismeja, jotka ovat vähemmän resurssiintensiivisiä, mutta joilla on muita haittoja tai puutteita, kuten [proof](/proof-stake-pos) [of stake (PoS)](/proof-stake-pos) ja [todistus palamisesta](/proof-burn-cryptocurrency). Ilman todistusmekanismia verkko ja siihen tallennetut tiedot olisivat alttiina hyökkäyksille tai varkauksille.

### Käyttääkö Bitcoin työtodistusta?

Joo. Se käyttää SHA-256-hajautustoimintoon perustuvaa PoW-algoritmia tapahtumien validointiin ja vahvistamiseen sekä uusien bitcoinien liikkeeseen laskemiseen.

### Miten Todistus panoksesta (PoS) eroaa PoW:sta?

PoS on konsensusmekanismi, joka määrittää satunnaisesti solmun, joka louhii tai vahvistaa lohkotapahtumat sen mukaan, kuinka monta kolikkoa kyseisessä solmussa on. Mitä enemmän rahakkeita lompakossa on, sitä enemmän kaivosvoimaa sille myönnetään. Vaikka PoS on paljon vähemmän resurssiintensiivinen, siinä on useita muita puutteita, mukaan lukien suurempi mahdollisuus [51 %:n hyökkäykseen](/51-attack) pienemmissä altcoineissa ja kannustimet hamstrata tokeneita ja olla käyttämättä niitä.

## Kohokohdat

- Proof of Stake (POS) oli yksi useista uusista konsensusmekanismeista, jotka luotiin vaihtoehtona työn todistamiselle.

- Proof of work (PoW) on hajautettu konsensusmekanismi, joka edellyttää verkon jäsenten ponnistelua mielivaltaisen matemaattisen pulman ratkaisemiseksi, jotta kukaan ei pääse pelaamaan järjestelmää.

- Työn todistaminen mittakaavassa vaatii valtavia määriä energiaa, joka vain lisääntyy, kun verkostoon tulee lisää kaivostyöläisiä.

- Työtodistuksen ansiosta Bitcoin- ja muut kryptovaluuttatapahtumat voidaan käsitellä peer-to-peer turvallisesti ilman luotettavan kolmannen osapuolen tarvetta.

- Todistusta työstä käytetään laajalti kryptovaluutan louhinnassa, transaktioiden validoinnissa ja uusien tokenien louhinnassa.

