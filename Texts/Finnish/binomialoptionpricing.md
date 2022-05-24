---
keywords: Trading,Options and Derivatives Trading,Options and Derivatives
title: Binomiaalinen optiohinnoittelumalli
description: Binomiaalinen optiohinnoittelumalli on optioiden arvostusmenetelmä, joka käyttää iteratiivista menettelyä ja sallii solmun määrittelyn tietyn ajanjakson aikana.
---

# Binomiaalinen optiohinnoittelumalli
## Mikä on binomiaalinen optiohinnoittelumalli?

Binomiaalinen optiohinnoittelumalli on vuonna 1979 kehitetty optioiden [arvostusmenetelmä](/valuation). Binomiaalisen optioiden hinnoittelumallissa käytetään iteratiivista menettelyä, joka mahdollistaa solmupisteiden tai ajankohtien määrittämisen arvostuspäivän ja option [vanhenemispäivän](/expiration-date) [välisenä aikana](/expiration-date).

Malli vähentää hinnanmuutosmahdollisuuksia ja poistaa [arbitraasin mahdollisuuden](/arbitrage). Yksinkertaistettu esimerkki [binomipuusta](/binomial_tree) saattaa näyttää tältä:

<!--87C9D3D79FF63D08201E6E848035602D-->

## Binomiaalisen optiohinnoittelumallin perusteet

Binomin optiohintamalleissa oletetaan, että on kaksi mahdollista lopputulosta – siis mallin binomiaalinen osa. Hinnoittelumallissa kaksi tulosta ovat nousu ylös tai lasku. Binomin optiohinnoittelumallin suurin etu on, että ne ovat matemaattisesti yksinkertaisia. Silti näistä malleista voi tulla monimutkaisia monijaksoisessa mallissa.

Toisin kuin [Black-Scholes-malli](/blackscholes),. joka tarjoaa numeerisen tuloksen syötteiden perusteella, binomimalli mahdollistaa omaisuuden ja vaihtoehdon laskemisen useille jaksoille sekä mahdollisten tulosten vaihteluvälin kullekin jaksolle (katso alla).

Tämän monijaksonäkymän etuna on, että käyttäjä voi visualisoida omaisuuden hinnan muutoksen jaksoittain ja arvioida vaihtoehtoa eri ajankohtina tehtyjen päätösten perusteella. Yhdysvaltoihin perustuvalle [optiolle](/americanoption),. joka voidaan käyttää milloin tahansa ennen [voimassaolon päättymispäivää](/expirationdate),. binomimalli voi antaa käsityksen siitä, milloin option käyttäminen voi olla suositeltavaa ja milloin se pitäisi pitää pidempään.

Tarkastelemalla arvojen [binomipuuta](/binomial_tree) elinkeinonharjoittaja voi määrittää etukäteen, milloin päätös [harjoituksesta](/exercise) saattaa tapahtua. Jos optiolla on positiivinen arvo, se on mahdollista toteuttaa, kun taas jos option arvo on alle nolla, se tulee pitää pidempään.

## Hinnan laskeminen binomiaalimallilla

Binomiaalisen optiomallin peruslaskentatapa on käyttää samaa todennäköisyyttä jokaisella onnistumis- ja epäonnistumisjaksolla, kunnes optio vanhenee. Elinkeinonharjoittaja voi kuitenkin sisällyttää kullekin ajanjaksolle erilaisia todennäköisyyksiä ajan kuluessa saatujen uusien tietojen perusteella.

Binomipuu on hyödyllinen työkalu hinnoitettaessa [amerikkalaisia optioita](/americanoption) ja [upotettuja vaihtoehtoja](/embeddedoption). Sen yksinkertaisuus on sen etu ja haitta yhtä aikaa. Puu on helppo mallintaa mekaanisesti, mutta ongelma on siinä, että kohde-etuuden mahdolliset arvot voivat kestää yhden ajanjakson. Binomipuumallissa kohde-etuuden arvo voi olla vain yksi kahdesta mahdollisesta arvosta, mikä ei ole realistista, koska omaisuus voi olla minkä tahansa arvoisen arvoinen millä tahansa tietyllä alueella.

Esimerkiksi voi olla 50/50 todennäköisyys, että kohde-etuuden hinta voi nousta tai laskea 30 prosenttia yhden jakson aikana. Toisella jaksolla todennäköisyys kohde-etuuden hinnan nousulle voi kuitenkin kasvaa 70/30.

Jos sijoittaja esimerkiksi arvioi [öljykaivoa](/exploratory-well),. kyseinen sijoittaja ei ole varma, mikä öljyportaan arvo on, mutta todennäköisyys, että hinta nousee, on 50/50. Jos öljyn hinta nousee kaudella 1, mikä tekee öljystä arvokkaampaa ja markkinoiden [perustekijät](/fundamentals) viittaavat nyt öljyn hinnan jatkuvaan nousuun, todennäköisyys hinnannousulle voi olla nyt 70 prosenttia. Binomimalli mahdollistaa tämän joustavuuden; Black-Scholes malli ei.

<!--94DBA31F9D3220C6052579D485B8A416-->

## Tosimaailman esimerkki binomiaalisesta optiohinnoittelumallista

Yksinkertaistettu esimerkki [binomipuusta](/binomial_tree) sisältää vain yhden askeleen. Oletetaan, että on osake, jonka hinta on 100 dollaria osakkeelta. Kuukaudessa tämän osakkeen hinta nousee 10 dollarilla tai laskee 10 dollarilla, mikä aiheuttaa seuraavan tilanteen:

- **osakehinta** = 100 dollaria

- **Osakehinta kuukaudessa (ylempi tila)** = 110 dollaria

- **Osakehinta kuukaudessa (alempi tila)** = 90 dollaria

Oletetaan seuraavaksi, että tälle osakkeelle on saatavilla osto-optio, joka vanhenee kuukauden kuluttua ja jonka lunastushinta on 100 dollaria. Ylös-tilassa tämän osto-option arvo on 10 dollaria ja alas-tilassa sen arvo on 0 dollaria. Binomimallilla voidaan laskea, mikä osto-option hinta pitäisi olla tänään.

Yksinkertaistamisen vuoksi oletetaan, että sijoittaja ostaa puolet osakkeista ja kirjoittaa tai myy yhden osto-option. Kokonaissijoitus on tänään puolen osakkeen hinta vähennettynä option hinnalla, ja mahdolliset voitot kuun lopussa ovat:

- **Hinta tänään** = 50 $ - optiohinta

- **Portfolion arvo** (ylempi tila) = 55 $ - maksimi (110 $ - 100 $, 0) = 45 $

- **Portfolion arvo** (alhainen tila) = 45 $ - maksimi(90 $ - 100 $, 0) = 45 $

Salkun tuotto on sama riippumatta siitä, miten osakekurssi liikkuu. Tämän tuloksen perusteella sijoittajan tulisi ansaita riskitön korko kuukauden aikana, mikäli arbitraasimahdollisuuksia ei ole. Tämän päivän kustannusten on oltava yhtä suuri kuin yhden kuukauden riskittömällä korolla diskontattu voitto. Ratkaistava yhtälö on näin:

- **Optiohinta** = 50 $ - 45 $ xe ^ (-riskitön korko x T), jossa e on matemaattinen vakio 2,7183.

Olettaen, että riskitön korko on 3 % vuodessa ja T on 0,0833 (yksi jaettuna 12:lla), osto-option hinta on tänään 5,11 dollaria.

Binomiaalinen optiohinnoittelumalli tarjoaa kaksi etua optioiden myyjille Black-Scholes-malliin verrattuna. Ensimmäinen on sen yksinkertaisuus, joka mahdollistaa vähemmän virheitä kaupallisessa sovelluksessa. Toinen on sen iteratiivinen toiminta, joka säätää hintoja oikea-aikaisesti vähentämään ostajien mahdollisuuksia toteuttaa arbitraasistrategioita.

Esimerkiksi, koska se tarjoaa joukon arvostustuloksia [johdannaisille](/derivative) jokaiselle solmulle tietyn ajanjakson aikana, se on hyödyllinen arvostettaessa johdannaisia, kuten amerikkalaisia optioita, jotka voidaan suorittaa milloin tahansa ostopäivän ja vanhenemispäivän välillä. Se on myös paljon yksinkertaisempi kuin muut hinnoittelumallit, kuten Black-Scholes-malli.

##Kohokohdat

- Malli on intuitiivinen ja sitä käytetään useammin käytännössä kuin tunnettua Black-Scholes-mallia.

- Mallilla on kaksi mahdollista lopputulosta jokaisella iteraatiolla – siirtyminen ylös tai alas, jotka seuraavat binomipuuta.

- Binomiaalinen optiohinnoittelumalli arvostaa optiot käyttämällä iteratiivista lähestymistapaa, jossa käytetään useita jaksoja amerikkalaisten optioiden arvostamiseen.

