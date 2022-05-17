---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: Autoregressiivinen integroitu liukuva keskiarvo (ARIMA)
description: Autoregressiivinen integroitu liukuva keskiarvo (ARIMA) on tilastollinen analyysimalli, joka hyödyntää aikasarjatietoja tulevaisuuden trendien ennustamiseen.
---

# Autoregressiivinen integroitu liukuva keskiarvo (ARIMA)
## Mikä on autoregressiivinen integroitu liukuva keskiarvo (ARIMA)?

Autoregressiivinen integroitu liukuva keskiarvo eli ARIMA on tilastollinen analyysimalli, joka käyttää [aikasarjatietoja](/timeseries) joko ymmärtääkseen paremmin tietojoukkoa tai ennustaakseen tulevaisuuden trendejä.

Tilastollinen malli on autoregressiivinen, jos se ennustaa tulevia arvoja menneiden arvojen perusteella. ARIMA-malli saattaa esimerkiksi pyrkiä ennustamaan osakkeen tulevia hintoja sen aiemman kehityksen perusteella tai ennustaa yrityksen tulosta menneiden ajanjaksojen perusteella.

## Autoregressiivisen integroidun liukuvan keskiarvon (ARIMA) ymmärtäminen

Autoregressiivinen integroitu liukuva keskiarvomalli on eräänlainen [regressioanalyysi](/regression),. joka mittaa yhden riippuvan muuttujan voimakkuuden suhteessa muihin muuttuviin muuttujiin. Mallin tavoitteena on ennustaa tulevia arvopaperi- tai rahoitusmarkkinoiden liikkeitä tarkastelemalla sarjan arvojen välisiä eroja todellisten arvojen sijaan.

ARIMA-malli voidaan ymmärtää hahmottelemalla kukin sen komponenteista seuraavasti:

- [Autoregressio (AR)](/autoregressive) : viittaa malliin, joka näyttää muuttuvan muuttujan, joka taantuu omiin viivästyneisiin tai aikaisempiin arvoihinsa.

- **Integroitu (I):** edustaa raakahavaintojen eroa, jotta aikasarjat voivat muuttua paikallaan (eli data-arvot korvataan data-arvojen ja aikaisempien arvojen erolla).

- [Liukuva keskiarvo (MA)](/movingaverage) : sisältää havainnon ja viivästyneisiin havaintoihin sovelletun liukuvan keskiarvon mallin jäännösvirheen välisen riippuvuuden.

## ARIMA-parametrit

Jokainen ARIMA-komponentti toimii parametrina vakiomerkinnällä. ARIMA-malleissa vakiomerkintä olisi ARIMA, jossa on p, d ja q, joissa kokonaislukuarvot korvaavat parametrit osoittaen käytetyn ARIMA-mallin tyypin. Parametrit voidaan määritellä seuraavasti:

- **p**: viivehavaintojen määrä mallissa; tunnetaan myös viivejärjestyksenä.

- **d**: kuinka monta kertaa raakahavainnot eroavat toisistaan; tunnetaan myös erotuksen asteena.

- q: liukuvan keskiarvon ikkunan koko; tunnetaan myös liukuvan keskiarvon järjestyksenä.

Esimerkiksi [lineaarisessa regressiomallissa](/nonlinear-regression) termien lukumäärä ja tyyppi otetaan mukaan. 0-arvo, jota voidaan käyttää parametrina, tarkoittaisi, että tiettyä komponenttia ei tulisi käyttää mallissa. Tällä tavalla ARIMA-malli voidaan rakentaa suorittamaan ARMA-mallin tai jopa yksinkertaisten AR-, I- tai MA-mallien tehtävää.

> Koska ARIMA-mallit ovat monimutkaisia ja toimivat parhaiten erittäin suurilla tietojoukoilla, niiden laskemiseen käytetään tietokonealgoritmeja ja koneoppimistekniikoita.

>

## Autoregressiivinen integroitu liukuva keskiarvo (ARIMA) ja stationaarisuus

Autoregressiivisessä integroidussa liukuvassa keskiarvomallissa tiedot erotetaan, jotta se pysyy paikallaan. Malli, joka näyttää stationaarisuuden, on malli, joka osoittaa, että tiedoissa on pysyvyyttä ajan kuluessa. Useimmat talous- ja markkinatiedot osoittavat trendejä, joten erottelun tarkoituksena on poistaa kaikki trendit tai kausirakenteet.

[Kausiluontoisuus](/seasonality) tai se, että tiedoissa näkyy säännöllisiä ja ennustettavia malleja, jotka toistuvat kalenterivuoden aikana, voivat vaikuttaa negatiivisesti regressiomalliin. Jos suuntaus ilmaantuu ja stationaarisuus ei ole ilmeistä, monia prosessin aikana suoritettavia laskelmia ei voida tehdä erittäin tehokkaasti.

> Kertaluonteinen shokki vaikuttaa ARIMA-mallin myöhempiin arvoihin loputtomasti tulevaisuuteen. Siksi finanssikriisin perintö elää edelleen nykypäivän autoregressiivisissä malleissa.

>

## Erityisiä huomioita

ARIMA-mallit perustuvat olettamukseen, että menneillä arvoilla on jonkin verran jäännösvaikutusta nykyisiin tai tuleviin arvoihin. Esimerkiksi sijoittaja, joka käyttää ARIMA-mallia osakkeiden hintojen ennustamiseen, olettaisi, että viimeaikaiset markkinatapahtumat vaikuttavat kyseisen osakkeen uusiin ostajiin ja myyjiin päättäessään, kuinka paljon arvopaperia tarjotaan tai hyväksytään.

Vaikka tämä oletus pätee monissa olosuhteissa, näin ei aina ole. Esimerkiksi vuoden 2008 finanssikriisiä edeltävinä vuosina useimmat sijoittajat eivät olleet tietoisia riskeistä, joita monien rahoitusyritysten hallussa olevat suuret [asuntolainavakuudelliset arvopaperisalkut (MBS) aiheuttavat.](/mbs)

Noina aikoina sijoittajalla, joka käytti autoregressiivistä mallia ennustaakseen Yhdysvaltain rahoitusosakkeiden kehitystä, olisi ollut hyvä syy ennustaa jatkuvaa vakaata tai nousevaa osakekurssitrendiä kyseisellä sektorilla. Kun kuitenkin tuli julkisuuteen, että monet rahoituslaitokset olivat vaarassa romahtaa, sijoittajat alkoivat yhtäkkiä vähemmän välittää näiden osakkeiden viimeaikaisista hinnoista ja paljon enemmän niiden taustalla olevista riskeistä. Siksi markkinat arvostetaan nopeasti uudelleen rahoitusosakkeet paljon alemmalle tasolle, mikä olisi hämmentänyt autoregressiivisen mallin täysin.

## Usein Kysytyt Kysymykset

### Mihin ARIMAa käytetään?

ARIMA on menetelmä ennustaa tai ennustaa tulevia tuloksia historiallisen aikasarjan perusteella. Se perustuu sarjakorrelaation tilastolliseen käsitteeseen, jossa menneet datapisteet vaikuttavat tuleviin tietopisteisiin.

### Mitä eroa on autoregressiivisten ja liukuvan keskiarvon mallien välillä?

ARIMA yhdistää autoregressiiviset ominaisuudet liukuvien keskiarvojen ominaisuuksiin. Esimerkiksi AR(1)-autoregressiivinen prosessi on sellainen, jossa nykyinen arvo perustuu välittömästi edeltävään arvoon, kun taas AR(2)-prosessi on sellainen, jossa nykyinen arvo perustuu kahteen edelliseen arvoon. Liukuva keskiarvo on laskelma, jota käytetään datapisteiden analysointiin luomalla sarja keskiarvoja koko tietojoukon eri osajoukoista poikkeavien arvojen tasoittamiseksi. Tämän tekniikoiden yhdistelmän ansiosta ARIMA-mallit voivat ottaa ennusteita tehdessään huomioon trendit, syklit, kausivaihtelun ja muun ei-staattisen datan.

### Miten ARIMA-ennuste toimii?

ARIMA-ennuste saadaan aikaan liittämällä aikasarjatiedot kiinnostavasta muuttujasta. Tilastoohjelmisto tunnistaa dataan sovellettavien viiveiden tai erotuksen määrän ja tarkistaa stationaarisuuden. Sitten se tulostaa tulokset, jotka usein tulkitaan samalla tavalla kuin moninkertaisen lineaarisen regressiomallin.

##Kohokohdat

- Autoregressiiviset integroidut liikkuvat keskiarvot (ARIMA) -mallit ennustavat tulevaisuuden arvoja menneiden arvojen perusteella.

- ARIMA käyttää viivästyneitä liukuvia keskiarvoja aikasarjatietojen tasoittamiseen.

- Niitä käytetään laajasti teknisessä analyysissä arvioimaan arvopaperien tulevia hintoja.

- Autoregressiiviset mallit olettavat implisiittisesti, että tulevaisuus muistuttaa menneisyyttä.

- Siksi ne voivat osoittautua epätarkiksi tietyissä markkinaolosuhteissa, kuten rahoituskriisien tai nopean teknologian muutoksen aikoina.

