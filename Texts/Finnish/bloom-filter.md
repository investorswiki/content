---
keywords: Crypto
title: Bloom-suodatin
description: Bloom-suodatin. Tietorakenne, jota voidaan käyttää ilmoittamaan käyttäjälle, onko tietty kohde osa nimikejoukkoa
---

# Bloom-suodatin
Bloom-suodatin on tietorakenne, jota voidaan käyttää ilmoittamaan käyttäjälle, kuuluuko tietty kohde joukkoon. Vaikka se ei voi sanoa varmasti, onko elementti joukossa, se voi sanoa varmasti, jos elementti ei ole.

Burton Howard Bloomin vuonna 1970 luomat Bloom-suodattimet ovat houkutteleva tarjonta erilaisiin sovelluksiin tilankäytön tehokkuuden ansiosta. Joissakin kryptovaluutoissa (erityisesti Bitcoinissa) niillä on olennainen rooli yksinkertaistetussa maksuvahvistuksessa tai SPV:ssä.

Käytettäessä SPV-asiakasta käyttäjät voivat olla vuorovaikutuksessa Bitcoin-verkon kanssa ilman täyttä solmua. Täysin solmuihin liittyy tiettyjä tallennus- ja laskentavaatimuksia, jotka tekevät niistä hankalia toimia pienitehoisissa laitteissa, kuten älypuhelimissa. SPV-asiakkaat puolestaan yksinkertaisesti tiedustelevat täydellisiä solmuja saadakseen tietoja, jotka ovat olennaisia käyttäjän lompakoille.

Yksinkertaisin ratkaisu näiden tietojen välittämiseksi käyttäjälle olisi saada täydet solmut tietoisiksi asiakkaan avaimista, jotta heille lähetetään vain asiaankuuluvat tapahtumat. Ilmeisesti tämä on huono ratkaisu, koska asiakkaan yksityisyys uhrattaisiin. Toisaalta kaikkien tapahtumien lataaminen vain suurimman osan niistä hylkäämiseksi olisi kaistanleveyden hukkaa. Anna Bloom-suodattimet.

Havainnollistetaan. Oletetaan, että asiakkaalla, Alicella, on arvokas tapahtuma, josta hän ei halua täyttä solmua hoitavan Bobin olevan tietoinen. Hän rakentaa Bloom-suodattimen, jonka kuvaamme 10x1-ruudukona:

Hän välittää häntä kiinnostavat tapahtumatiedot kahden eri hash-funktion kautta, jotka tulostavat kaksi numeroa väliltä 0 ja 9. Kutsutaan niitä 4:ksi ja 7:ksi. Hän lähettää suodattimen Bobille.

Tätä ruudukkoa tarkasteltaessa sinulla ei ole aavistustakaan, mitä tietoja Alice on välittänyt suodattimelle. Jos sinulla olisi joukko, johon tiedot sisältyivät, voisit tiivistää sen ja verrata sitä suodattimeen – jos osuma löytyy, on mahdollista, että ne olivat Alice pyytämät tiedot.

Samaan aikaan on todennäköisesti monia syötteitä, jotka yhdistetään 4:ään ja 7:ään, joten Bob ei voi määrittää, mistä tiedoista Alice on kiinnostunut. Hän yksinkertaisesti palauttaa kaikki osumat, ja Alice suodattaa ne omasta päästään.

Tämä on tietysti karkea liiallinen yksinkertaistus, mutta se osoittaa konseptin: Bloom-suodattimet hämärtävät asiakkaan todelliset edut. Se ei ole täydellinen menetelmä (sen yksityisyyteen liittyy edelleen huolta), mutta se on parannus verrattuna suojaamattomaan pyyntöön solmulle.

