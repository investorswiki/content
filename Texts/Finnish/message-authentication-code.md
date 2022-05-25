---
keywords: Personal Finance,Banking
title: Viestin todennuskoodi (MAC)
description: Viestin todennuskoodi (MAC) tai tunniste on suojakoodi, jonka tietokoneen käyttäjä kirjoittaa käyttääkseen tilejä tai portaaleja.
---

# Viestin todennuskoodi (MAC)
## Mikä on viestin todennuskoodi?

Viestin todennuskoodi (MAC) tai **tag,** on suojakoodi, jonka tietokoneen käyttäjä kirjoittaa päästäkseen tileille tai portaaleihin. Tämä koodi on liitetty käyttäjän lähettämään viestiin tai pyyntöön. Vastaanottavan järjestelmän on tunnistettava viestiin liitetyt MAC-koodit, jotta käyttäjälle voidaan myöntää pääsy.

## Viestin todennuskoodin (MAC) ymmärtäminen

Viestitunnistuskoodeja (MAC) käytetään yleisesti [sähköisissä varojen siirroissa](/electronic-funds-transfer-act) (EFT) tietojen eheyden ylläpitämiseksi. he vahvistavat, että viesti on aito; että se todella tulee, toisin sanoen ilmoitetulta lähettäjältä, eikä siihen ole tehty mitään muutoksia matkalla. Todentaja, jolla on myös avain, voi sen avulla tunnistaa kyseisen viestin sisällön muutokset.

Viestien todennuskoodeja tarvitaan yleensä kaikenlaisille rahoitustileille pääsyyn. Pankit, pankkiiriliikkeet, säätiöyhtiöt ja muut talletus-, sijoitus- tai vakuutusyhtiöt, jotka tarjoavat online-käyttöä, voivat käyttää näitä koodeja. Ne ovat tärkeä osa rahoitussalausta.

## MAC:ien luomiseen käytetyt algoritmit

Kolme algoritmia tyypillisesti käsittävät MAC:n: avaimen generointialgoritmin, allekirjoitusalgoritmin ja varmistusalgoritmin. Avaimen luontialgoritmi valitsee avaimen sattumanvaraisesti. Allekirjoitusalgoritmi lähettää tunnisteen, kun sille annetaan avain ja viesti. varmistusalgoritmia käytetään varmistamaan viestin aitous, kun sille annetaan avain ja tunniste; se palauttaa viestin **hyväksytty**, jos viesti ja tunniste ovat aitoja ja muuttamattomia, mutta muussa tapauksessa se palauttaa viestin **hylätty.**

Esimerkiksi lähettäjä lähettää viestin, kuten EFT:n, MAC-algoritmin kautta, joka luo avaimen ja liittää viestiin MAC-datatunnisteen. Vastaanottaja saa viestin, ajaa sen takaisin MAC-algoritmin läpi samalla avaimella ja saa toisen datatunnisteen. Sitten he vertaavat tätä MAC-datatunnistetta ensimmäiseen, joka oli liitetty viestiin sen lähetyshetkellä. Jos koodi on sama molemmissa päissä, vastaanottaja voi turvallisesti olettaa, että viestin tietojen eheys on ehjä. Jos ei, se tarkoittaa, että viestiä on muutettu, peukaloitu tai väärennetty.

Itse viestin tulee kuitenkin sisältää tietoja, jotka varmistavat, että tämä viesti voidaan lähettää vain kerran. Esimerkiksi kertaluonteista MAC:ia, aikaleimaa tai järjestysnumeroa voidaan käyttää takaamaan, että viesti voidaan lähettää vain kerran. Muuten järjestelmä voi olla alttiina toistohyökkäykselle, jossa hyökkääjä sieppaa viestin sen jälkeen, kun se on purettu, ja lähettää sen myöhemmin uudelleen kopioiden alkuperäiset tulokset ja tunkeutuen järjestelmään.

## Viestin eheyskoodit (MIC)

Joskus termiä viestin eheyskoodi (MIC) käytetään MAC:n sijaan. Tämä tehdään useimmiten viestintäteollisuudessa, jossa MAC tarkoittaa perinteisesti median pääsynhallintaosoitetta (MAC-osoite). MIC:tä voidaan kuitenkin käyttää myös viittaamaan **viestin tiivistelmään**, joka ei käytä salaisia avaimia samalla tavalla kuin MAC, eikä se voi tarjota samaa suojaustasoa ilman lisäsalausta.

