---
keywords: Crypto
title: Käyttämättömät tapahtumat (UTXO)
description: Käyttämätön tapahtumatulos (UTXO). Tapahtumassa luotu tulos, johon on viitattava tulevassa tapahtumassa varojen käyttämiseksi.
---

# Käyttämättömät tapahtumat (UTXO)
Käyttämätön tapahtumatuloste (UTXO) viittaa tapahtuman ulostuloon, jota voidaan käyttää syötteenä uudessa tapahtumassa. Pohjimmiltaan UTXO:t määrittelevät, missä kukin lohkoketjutapahtuma alkaa ja päättyy. UTXO-malli on Bitcoinin ja monien muiden kryptovaluuttojen peruselementti.

Toisin sanoen kryptovaluuttatapahtumat tehdään syötteistä ja lähdöistä. Aina kun tapahtuma suoritetaan, käyttäjä ottaa yhden tai useamman UTXO:n syötteenä. Seuraavaksi käyttäjä antaa digitaalisen allekirjoituksensa vahvistaakseen omistajuuden tuloihin, jotka lopulta johtavat ulostuloihin. Kulutetut UTXO:t katsotaan nyt "käytettyiksi", eikä niitä voi enää käyttää. Samaan aikaan tapahtuman lähdöistä tulee uusia UTXO:ita, jotka voidaan käyttää uuteen tapahtumaan myöhemmin.

Tämä on luultavasti paremmin selitettävissä esimerkillä. Alicella on lompakossa 0,45 BTC. Tämä ei ole kolikon murto-osa, kuten voisimme kuvitella. Se on pikemminkin UTXO-kokoelma. Tarkemmin sanottuna kaksi UTXO:ta, joiden arvo on 0,4 BTC ja 0,05 BTC – tulosteita aiemmista tapahtumista. Kuvitellaan nyt, että Alicen on suoritettava Bobille 0,3 BTC:n maksu.

Hänen ainoa vaihtoehtonsa tässä on hajottaa 0,4 BTC:n yksikkö ja lähettää 0,3 BTC Bobille ja 0,1 BTC takaisin itselleen. Hän vaatisi normaalisti takaisin alle 0,1 BTC:tä kaivosmaksujen vuoksi, mutta yksinkertaistetaan ja jätetään kaivostyöntekijä pois.

Alice luo transaktion, joka pohjimmiltaan sanoo verkolle: ota syötteeksi minun 0,4 BTC UTXO, hajoa se, lähetä siitä 0,3 BTC Bobin osoitteeseen ja palauta 0,1 BTC osoitteeni. 0,4 BTC on nyt käytetty, eikä sitä voi käyttää uudelleen. Sillä välin on luotu kaksi uutta UTXO:ta (0,3 BTC ja 0,1 BTC).

Huomaa, että hajoimme UTXO:n tässä esimerkissä, mutta jos Alice olisi joutunut maksamaan 0,42 BTC:tä, hän olisi yhtä helposti voinut yhdistää 0,4 BTC:n toiseen 0,05 BTC:hen tuottaakseen UTXO:n, jonka arvo on 0,42 BTC, samalla kun hän palauttaisi itselleen 0,03 BTC:n.

Yhteenvetona voidaan todeta, että UTXO-malli toimii protokollan mekanismina, jolla seurataan, missä kolikot kulloinkin ovat. Tietyssä mielessä ne toimivat paljon kuin sekit: ne on osoitettu tietyille käyttäjille (tai pikemminkin heidän julkisille [osoitteilleen](/address) ). UTXO:ta ei voi käyttää osittain – sen sijaan vanhasta on luotava uudet shekit ja siirrettävä ne eteenpäin.

