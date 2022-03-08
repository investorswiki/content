---
keywords: Crypto
title: Puolittaminen
description: Puolittaminen. Kun krypto-omaisuuden lohkopalkkio putoaa puoleen siitä, mikä se oli aiemmin; tätä käytetään luomaan laskeva liikkeeseenlaskuprosentti.
---

# Puolittaminen
Kryptovaluutta-avaruudessa termi puolittaminen viittaa prosessiin, joka vähentää uusien kolikoiden liikkeeseenlaskunopeutta. Tarkemmin sanottuna puolittaminen on kaivostyöläisille myönnettävän kokonaistuen säännöllistä pienentämistä. Puolittaminen varmistaa, että kryptoomaisuus noudattaa tasaista liikkeeseenlaskunopeutta, kunnes sen [enimmäistarjonta](/maximum-supply) lopulta saavutetaan.

Mitä tulee Bitcoiniin, uutisrahoja luodaan jatkuvasti osana [lohkopalkkiota](/block-reward) (joka koostuu lohkotuesta ja transaktiomaksuista). Joten joka kerta, kun kaivosmies onnistuneesti "löydä" ja vahvistaa uuden [lohkon](/block),. hän ansaitsee vasta luotuja kolikoita korvauksena työstään.

Joten [louhintaprosessi](/mining) tuo uusia [Bitcoineja](/bitcoin) järjestelmään, ja tämä tapahtuu ennustettavassa ja kontrolloidussa tahdissa. Uusia Bitcoin-lohkoja louhitaan keskimäärin 10 minuutin välein, ja lohkotuki seuraa hallittua hajoamisnopeutta. Puolittaminen on siis se, mikä varmistaa sen, että lohkotuki pienenee 50 % joka 210 000 lohko (noin neljän vuoden välein).

[Genesis-lohkosta](/genesis-block) alkaen Bitcoinin lohkotuki asetettiin alun perin 50 BTC:ksi. Sitten se pienennettiin 25 BTC:hen vuonna 2012 ja 12,5:een BTC:hen vuonna 2016. Seuraavan puolittumisen odotetaan tapahtuvan toukokuussa 2020, jolloin lohkotuen määrä pienenee 6,25 BTC:hen. Kun 32 puolittumista on tapahtunut, prosessi pysähtyy eikä Bitcoineja enää luoda. Tässä vaiheessa 21 miljoonan BTC:n enimmäistarjonta saavutetaan.

[Seuraa Bitcoinin puolittamista](/halving)

Puolittaminen on tärkeä osa Bitcoin-protokollaa, ja koska koodi on avoimen lähdekoodin, kuka tahansa voi nähdä sen. Esimerkiksi Bitcoin Core -toteutus on saatavilla [GitHubissa](/github),. ja yksi lohkotuen määrittelevistä koodiosista näyttää tältä:

CAmount GetBlockSubsidy(int nHeight, const Consensus::Params & consensusParams)

{

int puolittaminen = nKorkeus / consensusParams.nSubsidyHalvingInterval;

// Pakota lohkopalkkio nollaan, kun siirto oikealle on määrittelemätön.

jos (puolikkaat >= 64)

paluu 0;

CAmäärä nTuki = 50 * KOLIKKO;

// Tuki puolitetaan 210 000 lohkon välein, mikä tapahtuu noin 4 vuoden välein.

nTuki >>= puolittaminen;

palauttaa nSubsidy;

}

