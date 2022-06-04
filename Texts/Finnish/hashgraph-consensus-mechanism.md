---
keywords: Investing,Cryptocurrency,Blockchain
title: Hashgraph Consensus
description: Hashgraph-konsensus toimii eri tavalla kuin tunnetuimmat lohkoketjukonsensusmekanismit. Lue lisää siitä ja miten se toimii.
---

# Hashgraph Consensus
## Mikä on Hashgraph Consensus?

Hashgraph-konsensus on vaihtoehto - tai seuraavan sukupolven - blockchain-konsensusmekanismien takana olevalle teknologialle. Sen sijaan, että käytettäisiin suurten verkkojen laskentatehoa tapahtumien tarkistamiseen, tapahtumat tallennetaan ja vahvistetaan solmuviestintää käyttävän protokollan kautta.

Hashgraph on hajautettu pääkirja, samalla tavalla kuin lohkoketju. Se tallentaa tietoja, suojaa ne salauksella, rajoittaa pääsyä ja käyttää tallennettuja tietoja varmentamiseen. Hashgraph-verkko saavuttaa kuitenkin konsensuksen paljon eri tavalla kuin lohkoketju.

Hashgraph-konsensus saavutetaan käyttämällä käsitteitä, joita kutsutaan "juoruiksi", "juoruiksi juoruiksi" ja virtuaaliseksi äänestämiseksi. Järjestelmän suunnittelijat raportoivat, että se ratkaisee konsensuksen rakentamisalgoritmeille ominaiset ongelmat , kuten [työntodistuksen (](/algorithm) [PoW](/proof-work) ), paremman nopeuden ja tehokkaamman.

> Hashgraph-konsensus – juorut, juorut juoruista ja virtuaalinen äänestys – on mekanismi, jota Hederan hajautettu pääkirja käyttää tapahtumien vahvistamiseen ja vahvistamiseen.

>

## Hashgraph-konsensuksen ymmärtäminen

Hashgraph on vaihtoehto blockchainille. Lohkoketjun tapaan se tallentaa tietoja ja salaa sen. Tapahtumatiedoille luodaan tiiviste, ja uusia tapahtumia tai tietoja lisätään ja niiden pohjalle rakennetaan. Lohkoketju on kuitenkin pääkirja, joka koostuu tietolohkoista. Jokainen lohko linkitetään edelliseen lohkoon käyttämällä sen tietoja, jotka validaattoriverkosto vahvistaa seuraavan lohkon luomiseksi. Tämä prosessi luo yhden ketjun. Hashgraph ei ole yksi ketju – kaikki tiedot säilytetään salatussa reskontrassa, ja jokainen käyttäjä osallistuu validointiprosessiin, ei vain validaattorit.

Esimerkiksi Alice luo tapahtuman Bobin kanssa, ja kaikki hänen tuntemansa tiedot annetaan hänelle. Bob tekee sitten kaupan Krisin kanssa. Kaikki Bobin tiedot välitetään Krisille. Kris käy kauppaa Elin kanssa, ja kaikki, mitä hän tietää, siirretään. Tämä jatkuu koko verkoston ajan, ja ketju juoruilee pääasiassa tapahtumista. Jokainen solmu tietää sen, mitä kaikki muut solmut tietävät, joten laskennallista validointia ei tarvita.

Kun juorut leviävät käyttäjältä käyttäjälle, verkko käyttää algoritmeja ja automaatiota varmistaakseen, että hashgraph-reskontin tila on päivitetty ja sama.

### Juoru

Tietoa datasta kutsutaan "juoruksi". Tapahtuman sisältämä tietorakenne on:

- Aikaleima

- Enemmän tapahtumia tai nollia

- Kaksi tiivistettä ylätason säilöistä

- Salattu allekirjoitus.

Kaksi tiivistettä ovat viimeisiä tapahtumia kahdesta synkronointisolmusta, jotka vertaavat tietojaan. Solmut luovat jatkuvasti tapahtumia ja synkronoivat.

> Hashgraph – pääkirja – on tehokkaampi kuin lohkoketju, koska energiaa ei hukata lohkoihin, joita ei hyväksytä. Kaikki tiedot säilytetään hashgraphissa.

>

### Juoruja juoruista

Tapahtumatietoja koskevia tietoja kutsutaan "juoruiksi juoruiksi". Tiedot synkronoidaan hashgraph-verkossa käyttämällä tapahtumaa, jota kutsutaan "juorujen synkronoimiseksi". Juorujen synkronointi on "juorutapahtumien" yhteinen historia hashgrafissa. Tällä tavalla tietoja ei voida muuttaa tai peukaloida, ja asiasta vallitsee yksimielisyys.

### Virtuaaliäänestys

Virtuaaliäänestys tapahtuu, kun solmut vertaavat tapahtumia ja pääsevät yhteisymmärrykseen äänestysalgoritmin avulla. Näin se toimii – tapahtumalle määritetään aikaleima, kun solmu vastaanottaa sen. Kun se siirtyy verkon muihin solmuihin, sille osoitetaan aikaleima, joka on mediaani kaikista verkon solmujen vastaanottamista aikaleimoista kyseiselle tapahtumalle. Mediaani toimii äänestyksen tuloksena. Tämä luo reilumman tapahtumajärjestelmän kuin lohkoketju, koska verkko päättää, ei yksi solmu.

### Vikasietoisuus

Kuten useimmissa hajautetuissa kirjanpidossa ja lohkoketjussa, on aina mahdollisuus, että verkoston osallistuja ei ole rehellinen. Tiedonsiirrossa tai verkon latenssissa saattaa olla viiveitä, minkä vuoksi solmut eivät kommunikoi kunnolla.

Konsensusmekanismit on suunniteltu käsittelemään näitä vikoja asettamalla vikasietokriteerit. Kehittäjien on otettava huomioon huonot toimijat, huonot yhteydet, verkon latenssi ja muut verkko-ongelmat ja otettava ne huomioon. Hashgraph-konsensus voi sietää, että kolmasosa verkosta toimii haitallisesti. Sen kerrotaan olevan asynkroninen bysanttilainen vikasietoinen – korkein tietoturvataso – mikä tarkoittaa, että verkon rehelliset solmut jatkavat toimintaansa, vaikka huonoja toimijoita olisikin.

## Miten Hashgraph eroaa Blockchainista?

Hashgraph on tietorakenne, joka ylläpitää kirjaa siitä, kuka kertoi kenelle mitä ja missä järjestyksessä he tekivät sen. Se on juorutapahtumien yhteistyöhistoria, kun osallistujat lisäävät ja jakavat tietoja, mikä vahvistaa tapahtumat paljon nopeammin kuin lohkoketju.

Blockchain lisää aiemmat tapahtumatiedot uusiin tapahtumatietoihin ja salaa ne. Osapuolten välisten liiketoimien vahvistamiseen tarvitaan kolmas osapuoli. Hashgraph ei tarvitse tätä hidasta prosessia juoruprotokollan vuoksi.

> Hashgraph-konsensus on paljon nopeampi kuin blockchain-konsensusmekanismit, ja keskimääräiset tapahtuman vahvistusajat ovat sekunneissa minuuttien sijaan.

>

Bitcoinilla ja monilla muilla kryptovaluutoilla on ongelmia viestien ajoituksen kanssa. Hashgraphin asynkroninen bysanttilainen vikasietokyky kuitenkin voittaa viestien ajoituksen ongelman olettaen, että kadonneet tai viivästyneet viestit pääsevät lopulta määränpäähänsä.

Jos esimerkiksi kaksi tapahtumaa tapahtuu samanaikaisesti, lohkoketjuverkko valitsee, missä järjestyksessä tapahtumat tapahtuivat. Joissakin lohkoketjuissa transaktiomaksut asettavat vahvistuksen etusijalle. Muut verkot voivat päättää, mikä tapahtuma vahvistetaan sen perusteella, kuinka monta merkkiä validaattori on panostanut. Näissä lohkoketjuissa yksi solmu vaikuttaa tulokseen.

Hashgraph-konsensus eliminoi yhden solmun tai solmuryhmän vaikutuksen tapahtumiin. Koska jokaisessa tapahtumassa on aikaleima ja jokainen tapahtuma välitetään koko verkkoon, tapahtuman ajoitusongelmat ratkaistaan.

## Kohokohdat

- Hashgraph-hajautettu pääkirjajärjestelmä ei ole saanut laajaa hyväksyntää kryptoyhteisössä.

- Hashgraph-konsensus käyttää konsensuksen luomiseen tietoa tiedoista eikä itse sisällöstä.

- Hashgraphin ensisijaista tietoa kutsutaan "juoruksi" ja toissijaista tietoa "juoruksi".

## UKK

### Miten Hashgraph Consensus toimii?

Hashgraph-konsensus toimii konsensusaikaleimojen ja "juorujen" avulla, jolloin jokainen solmu välittää kaiken, mitä se tietää, satunnaisille solmuille "juorutapahtumissa".

### Mikä on Hashgraph Consensus?

Hashgraph Consensus on mekanismi, jota käytetään hajautetussa hashgraph-reskontrassa tapahtumien vahvistamiseen.

### Korvaako Hashgraph Blockchainin?

Hashgraph on suunniteltu lohkoketjuteknologian parannukseksi ja sitä markkinoidaan, mutta jää nähtäväksi, korvaako se sen. Sillä ei ole vielä niin paljon kehittäjien kiinnostusta ja omaksumista kuin blockchain-teknologia.

