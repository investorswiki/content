---
keywords: Investing,Cryptocurrency,Blockchain
title: Hyperledger-kangas
description: Hyperledger Fabric on alusta erilaisten lohkoketjupohjaisten tuotteiden, ratkaisujen ja sovellusten rakentamiseen yrityskäyttöön.
---

# Hyperledger-kangas
## Mikä on Hyperledger-kangas?

[Hyperledger](/blockchain) Fabric on modulaarinen lohkoketjukehys , joka toimii perustana lohkoketjupohjaisten tuotteiden, ratkaisujen ja sovellusten kehittämiselle käyttämällä plug-and-play-komponentteja, jotka on tarkoitettu yksityisten yritysten käyttöön.

Hyperledger Fabricin aloittivat Digital Asset ja IBM, ja se on nyt noussut alojen välisenä yhteistyöhankkeena, jota tällä hetkellä isännöi Linux Foundation. Useista Hyperledger-projekteista Fabric oli ensimmäinen, joka poistui "inkubaatio"-vaiheesta ja saavutti "aktiivisen" vaiheen maaliskuussa 2017.

## Kuinka Hyperledger Fabric toimii

Perinteiset blockchain-verkot eivät voi tukea yksityisiä liiketoimia ja luottamuksellisia sopimuksia, jotka ovat yrityksille äärimmäisen tärkeitä. Hyperledger Fabric suunniteltiin vastauksena tähän modulaariseksi, skaalautuvaksi ja turvalliseksi perustaksi teollisten lohkoketjuratkaisujen tarjoamiselle.

Hyperledger Fabric on avoimen lähdekoodin lohkoketjun moottori ja se huolehtii tärkeimmistä ominaisuuksista lohkoketjun arvioimiseksi ja käyttämiseksi yrityskäyttöön.

Yksityisissä teollisuusverkoissa osallistujan todennettavissa oleva henkilöllisyys on ensisijainen vaatimus. Hyperledger Fabric tukee jäsenyyksiä luvan perusteella; kaikilla verkoston osallistujilla on oltava tiedossa oleva henkilöllisyys. Monia liiketoiminta-aloja, kuten terveydenhuoltoa ja rahoitusta, sitovat tietosuojasäännökset, jotka velvoittavat ylläpitämään tietoja eri osallistujista ja heidän pääsystään eri tietopisteisiin. Kangas tukee tällaista lupaperusteista jäsenyyttä.

### Modulaarinen arkkitehtuuri

Hyperledger Fabricin modulaarinen arkkitehtuuri jakaa tapahtumien käsittelyn työnkulun kolmeen eri vaiheeseen: [älykkäät sopimukset](/smart-contracts),. joita kutsutaan ketjukoodiksi, jotka sisältävät hajautetun logiikan käsittelyn ja järjestelmän hyväksymisen, tapahtumajärjestyksen sekä tapahtuman validoinnin ja sitoumuksen. Tämä erottelu tarjoaa useita etuja:

- Pienempi määrä luottamustasoja ja varmennusta, joka pitää verkon ja käsittelyn häiriöttömänä

- Parannettu verkon skaalautuvuus

- Parempi kokonaissuorituskyky

Lisäksi Hyperledger Fabric -tuki eri komponenttien plug-and-play-toiminnolle mahdollistaa olemassa olevien ominaisuuksien helpon uudelleenkäytön ja eri moduulien valmiin integroinnin. Jos esimerkiksi toiminto on jo olemassa, joka vahvistaa osallistujan henkilöllisyyden, yritystason verkon on yksinkertaisesti kytkettävä ja käytettävä tämä olemassa oleva moduuli uudelleen sen sijaan, että se rakentaisi saman toiminnon tyhjästä.

Verkoston osallistujilla on kolme erillistä roolia:

- Kannattaja

- Sitoutunut

- Suostuvainen

Lyhyesti sanottuna tapahtumaehdotus toimitetaan hyväksyjän vertaiselle edeltäkäsin määritellyn hyväksymiskäytännön mukaisesti vaadittavien hyväksyjien lukumäärästä. Sen jälkeen, kun vahvistaja(t) ovat antaneet riittävän vahvistuksen, tapahtumaerä tai -lohko toimitetaan toimittajille. Sitouttajat vahvistavat, että hyväksymiskäytäntöä on noudatettu ja että ristiriitaisia tapahtumia ei ole. Kun molemmat tarkistukset on tehty, tapahtumat sitoutuvat pääkirjaan.

<!--6376536357DF4ADC77E5CAB266DCF459-->

Kuvan lähde: IBM

Koska vain vahvistusohjeet – kuten allekirjoitukset ja luku-/kirjoitusjoukot – lähetetään verkon yli, verkon skaalautuvuus ja suorituskyky paranevat. Vain hyväksyjillä ja sitojilla on pääsy tapahtumaan, ja turvallisuus paranee, kun harvemmalla osallistujamäärällä on pääsy tärkeisiin tietopisteisiin.

## Esimerkki Hyperledger-kankaasta

Oletetaan, että valmistaja haluaa toimittaa suklaata tietylle jälleenmyyjälle tai vähittäiskauppiaiden markkinoille (eli kaikille yhdysvaltalaisille vähittäiskauppiaille) tietyllä hinnalla, mutta ei halua paljastaa tätä hintaa muilla markkinoilla (eli kiinalaisille vähittäismyyjille).

Koska tuotteen liikkeessä voi olla muita osapuolia, kuten tullia, varustamoa ja rahoituspankkia, yksityinen hinta saattaa paljastua kaikille osapuolille, jos kaupan tukena käytetään lohkoketjuteknologian perusversiota.

Hyperledger Fabric korjaa tämän ongelman pitämällä yksityiset tapahtumat yksityisinä verkossa; vain osallistujat, jotka tarvitsevat tiedon, ovat tietoisia tarvittavista yksityiskohdista. Tietojen osiointi lohkoketjussa mahdollistaa tiettyjen datapisteiden pääsyn vain niille osapuolille, jotka tarvitsevat tiedon.

## Hyperledger-kankaan kritiikki

Kryptoinnostuksen huippumerkki murtui vuonna 2018 bitcoinin hinnan romahtamisen jälkeen (joka saavutti huippunsa 17. joulukuuta 2017). Ylioptimistiset väitteet uuden teknologian arvosta korvattiin skeptisyydellä, ja siihen liittyvät teknologiat, mukaan lukien Hyperledger, kärsivät myös tästä skeptisyydestä.

### Hyperledger Fabricin kilpailijat

Hyperledger Fabric kilpailee muiden Hyperledger-projektien kanssa, kuten Iroha, Indy ja Sawtooth. Se kilpailee myös R3:n Cordan kanssa, joka on myös yksityinen, lupapohjainen DLT.

Blockchain-palveluyritys Chainstack julkaisi tammikuussa 2020 paperin, joka osoittaa, että Cordan kehitys on ollut historiallisesti korkeampaa kuin Fabricin kehitys, vaikka kudoskehitys ohitti Cordan kehityksen vuoden 2019 kolmannella neljänneksellä, kun Fabric siirtyi GitHubiin.

Chainstack-raportti osoittaa, että vaikka Fabricin parissa työskentelee kolme kertaa enemmän kehittäjiä, Cordan kehittäjät lisäsivät koodia yli kaksi kertaa enemmän, ja Fabric-kehittäjät käyttävät paljon vähemmän koodia kehittäjää kohti kuin Cordan kehittäjät.

### Hyperledger-kangas ei ole lohkoketju eikä se ole tehokas

Useat Hyperledger Fabricin kritiikit huomauttavat, että lupiin perustuva yksityinen lohkoketju, jossa on Hyperledger Fabricin ominaisuudet, ei ole lohkoketju, ja nykyiset ei-blockchain-tekniikat ovat paljon halvempia ja tarjoavat saman verran turvallisuutta. Cointelegraphin Stuart Popejoy esitti tapauksen näin:

>

> Kankaan arkkitehtuuri on paljon monimutkaisempi kuin mikään blockchain-alusta, mutta se on myös vähemmän turvallinen peukalointia ja hyökkäyksiä vastaan. Luulisi, että "yksityinen" lohkoketju tarjoaisi ainakin skaalautuvuutta ja suorituskykyä, mutta Fabric epäonnistuu myös tässä. Yksinkertaisesti sanottuna Fabricille rakennetut pilotit kohtaavat monimutkaisen ja epävarman käyttöönoton, jota ei voida skaalata heidän liiketoimintansa kanssa .

>

Hyperledger Fabricia on myös kritisoitu joustavuuden puutteesta. Pariisin Sorbonnen tutkijaryhmä ja Australian kansallinen tiedevirasto CSIRO - Data61 havaitsivat, että merkittävät verkkoviiveet heikensivät kankaan luotettavuutta: "[B]viivästyttämällä lohkon leviämistä osoitimme, että Hyperledger Fabric ei tarjoa riittäviä yhtenäisyystakuita käytettäväksi kriittisissä ympäristöissä. "

## Hyperledger Fabric 2.0 julkaistiin tammikuussa 2020

Tammikuussa 2020 Hyperledger Fabric 2.0 julkaistiin vastaamaan joihinkin olemassa oleviin kritiikkiin. Techcrunchin Ron Millerin mukaan "suurimmat päivitykset sisältävät osapuolten välisen sopimuksen pakottamista ennen kuin uusia tietoja voidaan lisätä kirjanpitoon, mikä tunnetaan älykkäiden sopimusten hajautettuna hallintana."

Vaikka päivitys ei ole suuri muutos Fabricin yksinkertaisuudessa tai soveltuvuudessa, se osoittaa, että kryptovaluuttateollisuudessa edistytään edelleen vuonna 2018 tapahtuneen kryptomanian jälkeen. Seuraavien 5–10 vuoden aikana se on odotetaan, että yrityksen lohkoketju löytää epäilemättä oikean käytön.

## Kohokohdat

- Hyperledger on yritystason avoimen lähdekoodin hajautettu pääkirjakehys, jonka Linux Foundation julkaisi joulukuussa 2015.

- Koska Hyperledger Fabric on yksityinen ja vaatii käyttöoikeuden, yritykset voivat erotella tietoja (kuten hintoja) ja tapahtumia voidaan nopeuttaa, koska verkon solmujen määrä vähenee.

- Fabric 2.0 julkaistiin tammikuussa 2020. Tämän version pääominaisuuksia ovat nopeammat tapahtumat, päivitetty älysopimustekniikka ja virtaviivaistettu tiedonjako.

- Fabric on erittäin modulaarinen, hajautettu pääkirjateknologia (DLT) -alusta, jonka IBM on suunnitellut teollisuusyrityskäyttöön.

