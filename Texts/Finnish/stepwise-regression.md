---
keywords: Investing,Fundamental Analysis
title: Vaiheittainen regressio
description: Vaiheittainen regressio sisältää riippumattomien muuttujien valinnan käytettäväksi mallissa, joka perustuu iteratiiviseen muuttujien lisäämis- tai poistoprosessiin.
---

# Vaiheittainen regressio
## Mikä on vaiheittainen regressio?

[regressiomallin](/regression) vaiheittainen iteratiivinen rakentaminen, joka sisältää riippumattomien muuttujien valinnan käytettäväksi lopullisessa mallissa. Se sisältää mahdollisten selittävien muuttujien lisäämisen tai poistamisen peräkkäin ja tilastollisen merkitsevyyden testaamisen jokaisen iteraation jälkeen.

Tilastollisten ohjelmistopakettien saatavuus mahdollistaa vaiheittaisen regression jopa satojen muuttujien malleissa.

## Vaiheittaisen regression tyypit

Asteittaisen regression perimmäisenä tavoitteena on löytää sarjan testien avulla (esim. F-testit, [t-testit](/t-test) ) joukko riippumattomia muuttujia, jotka vaikuttavat merkittävästi riippuvaiseen muuttujaan. Tämä tehdään tietokoneilla iteroinnin kautta, joka on prosessi, jossa tuloksiin tai päätöksiin päästään käymällä läpi toistuvia analyysikierroksia tai -jaksoja. Testien automaattinen suorittaminen tilastollisten ohjelmistopakettien avulla säästää aikaa ja vähentää virheitä.

Vaiheittainen regressio voidaan saavuttaa joko kokeilemalla yhtä riippumatonta muuttujaa kerrallaan ja sisällyttämällä se regressiomalliin, jos se on [tilastollisesti merkitsevä](/statistically_significant),. tai sisällyttämällä kaikki mahdolliset riippumattomat muuttujat malliin ja eliminoimalla ne, jotka eivät ole tilastollisesti merkitseviä. Jotkut käyttävät molempien menetelmien yhdistelmää, ja siksi vaiheittaiseen regressioon on kolme lähestymistapaa:

1. **Eteenpäin tapahtuva valinta** alkaa ilman muuttujia mallissa, testaa jokaisen muuttujan, kun se lisätään malliin, ja säilyttää sitten tilastollisesti merkittävimmiksi katsotut muuttujat - toistaen prosessia, kunnes tulokset ovat optimaaliset.

1. **Taaksepäin tapahtuva eliminointi** alkaa riippumattomien muuttujien joukolla, poistetaan yksi kerrallaan ja testataan sitten, onko poistettu muuttuja tilastollisesti merkitsevä.

1. **Kaksisuuntainen eliminointi** on yhdistelmä kahdesta ensimmäisestä menetelmästä, jotka testaavat, mitkä muuttujat tulisi sisällyttää tai jättää pois.

## Esimerkki

Esimerkki vaiheittaisesta regressiosta taaksepäin eliminointimenetelmällä olisi yritys ymmärtää tehtaan energiankäyttöä käyttämällä muuttujia, kuten laitteiden käyttöaika, laitteiden ikä, henkilöstön koko, ulkolämpötilat ja vuodenaika. Malli sisältää kaikki muuttujat – sitten jokainen poistetaan yksi kerrallaan sen määrittämiseksi, mikä on tilastollisesti vähiten merkitsevä. Loppujen lopuksi malli saattaa näyttää, että vuodenaika ja lämpötilat ovat merkittävimmät, mikä mahdollisesti viittaa siihen, että tehtaan energiankulutuksen huippu on silloin, kun ilmastointilaitteen käyttö on korkeimmillaan.

## Vaiheittaisen regression rajoitukset

Regressioanalyysiä, sekä lineaarista että monimuuttujaa, käytetään nykyään laajalti taloustieteessä ja sijoitusmaailmassa. Ajatuksena on usein löytää aiemmin olemassa olevia malleja, jotka saattavat toistua myös tulevaisuudessa. Yksinkertainen lineaarinen regressio voi esimerkiksi tarkastella [hinta-tulos-suhteita](/price-earningsratio) ja osakkeiden tuottoa useiden vuosien ajalta sen määrittämiseksi, tarjoavatko osakkeet, joilla on alhainen P/E-suhde (riippumaton muuttuja), korkeampaa tuottoa (riippuvainen muuttuja). Tämän lähestymistavan ongelmana on, että markkinaolosuhteet muuttuvat usein ja menneisyydessä olleet suhteet eivät välttämättä pidä paikkaansa nykyisyydessä tai tulevaisuudessa.

Samaan aikaan vaiheittaisella regressioprosessilla on monia kritiikkiä ja jopa kehotuksia lopettaa menetelmän käyttö kokonaan. Tilastotyöntekijät panevat merkille lähestymistavan useita haittoja, mukaan lukien virheelliset tulokset, itse prosessin luontainen harha ja tarve merkittävään laskentatehoon monimutkaisten regressiomallien kehittämiseksi iteroinnin avulla.

## Kohokohdat

- Vaiheittaisella regressiolla on kuitenkin varjopuolensa, sillä se on lähestymistapa, joka sovittaa tiedot malliin halutun tuloksen saavuttamiseksi.

- Taaksepäin tapahtuva eliminointimenetelmä alkaa täydellä mallilla, joka on ladattu useilla muuttujilla, ja poistaa sitten yhden muuttujan testatakseen sen tärkeyttä suhteessa kokonaistuloksiin.

- Portaittainen regressio on menetelmä, joka tutkii iteratiivisesti kunkin riippumattoman muuttujan tilastollista merkitsevyyttä lineaarisessa regressiomallissa.

- Eteenpäin valitseva lähestymistapa alkaa tyhjästä ja lisää jokaisen uuden muuttujan asteittain testaten tilastollista merkitsevyyttä.

