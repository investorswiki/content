---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: Box-Jenkinsin malli
description: Box-Jenkins-malli on matemaattinen malli, joka on suunniteltu ennustamaan tietyn aikasarjan tietoja.
---

# Box-Jenkinsin malli
## Mikä on Box-Jenkinsin malli?

[aikasarjan](/timeseries) syötteiden perusteella . Box-Jenkins-malli voi analysoida useita erityyppisiä aikasarjatietoja ennustetarkoituksiin.

Sen metodologia käyttää datapisteiden välisiä eroja tulosten määrittämiseen. Metodologian avulla malli voi tunnistaa trendit käyttämällä autoregressiota, liukuvat keskiarvot ja kausivaihtelut ennusteiden luomiseksi.

[Autoregressiiviset integroidut liukuvat keskiarvomallit (ARIMA)](/autoregressive-integrated-moving-average-arima) ovat Box-Jenkins-mallin muoto. Termejä ARIMA ja Box-Jenkins käytetään joskus vaihtokelpoisina.

## Box-Jenkinsin mallin ymmärtäminen

Box-Jenkins-malleja käytetään useiden odotettavissa olevien datapisteiden tai tietoalueiden [ennustamiseen , mukaan lukien yritystiedot ja tulevat tietoturvahinnat.](/forecasting)

Box-Jenkinsin mallin loi kaksi matemaatikkoa: George Box ja Gwilym Jenkins. Kaksi matemaatikkoa keskustelivat tämän mallin käsitteistä vuoden 1970 julkaisussa nimeltä "Time Series Analysis: Forecasting and Control".

Box-Jenkins-mallin parametrien arvioinnit voivat olla hyvin monimutkaisia. Siksi, kuten muissakin aikasarjaregressiomalleissa, parhaat tulokset saavutetaan tyypillisesti ohjelmoitavien ohjelmistojen avulla. Box-Jenkins-malli soveltuu myös yleensä parhaiten lyhyen aikavälin ennusteisiin, jotka ovat enintään 18 kuukautta.

##Box-Jenkinsin metodologia

Box-Jenkins-malli voi olla yksi useista aikasarjaanalyysimalleista, joita ennustaja kohtaa ohjelmoitua ennusteohjelmistoa käyttäessään. Monissa tapauksissa ohjelmisto ohjelmoidaan automaattisesti käyttämään parhaiten sopivaa ennustemenetelmää ennustettavien [aikasarjatietojen](/timeseries) perusteella. Box-Jenkinsin on raportoitu olevan paras valinta tietojoukoille, jotka ovat enimmäkseen vakaita ja joilla on alhainen [volatiliteetti](/volatility).

Box-Jenkinsin malli ennustaa dataa käyttämällä kolmea periaatetta: autoregressio, erotus ja liukuva keskiarvo. Nämä kolme periaatetta tunnetaan nimellä p, d ja q. kutakin periaatetta käytetään Box-Jenkins-analyysissä; yhdessä, ne esitetään kollektiivisesti ARIMA-na (p, d, q).

Autoregressio (p) -prosessi testaa datan stationaarisuuden tason. Jos käytettävä data on paikallaan, se voi yksinkertaistaa ennustamisprosessia. Jos käytettävä data on ei-stationaarista, se on erotettava (d). Datasta testataan myös sen liukuvan keskiarvon sopivuus (mikä tehdään analyysiprosessin osassa q). Kaiken kaikkiaan tietojen alustava analyysi valmistelee sen ennustamista varten määrittämällä parametrit (p, d ja q), joita sitten käytetään ennusteen laatimiseen.

> Kertaluonteinen shokki vaikuttaa Box-Jenkins-mallin myöhempiin arvoihin loputtomasti tulevaisuuteen. Siksi finanssikriisin perintö elää edelleen nykypäivän autoregressiivisissä malleissa.

>

## Autoregressiivinen integroitu liukuva keskiarvo (ARIMA)

Box-Jenkins on eräänlainen autoregressiivinen integroitu liukuva keskiarvo (ARIMA) -malli, joka mittaa yhden riippuvan muuttujan voimakkuuden suhteessa muihin muuttuviin muuttujiin. Mallin tavoitteena on ennustaa tulevia arvopaperi- tai rahoitusmarkkinoiden liikkeitä tarkastelemalla sarjan arvojen välisiä eroja todellisten arvojen sijaan.

ARIMA-malli voidaan ymmärtää hahmottelemalla kukin sen komponenteista seuraavasti:

- [Autoregressio (AR)](/autoregressive) : viittaa malliin, joka näyttää muuttuvan muuttujan, joka taantuu omiin viivästyneisiin tai aikaisempiin arvoihinsa.

- Integroitu (I): edustaa raakahavaintojen erottelua, jotta aikasarjat pysyvät paikallaan, eli data-arvot korvataan data-arvojen ja aikaisempien arvojen erolla.

- [Liukuva keskiarvo (MA)](/movingaverage) : sisältää havainnon ja viivästyneisiin havaintoihin sovelletun liukuvan keskiarvon mallin jäännösvirheen välisen riippuvuuden.

## Osakehintojen ennustaminen

Yksi Box-Jenkins-mallianalyysin käyttötarkoitus on [osakekurssien ennustaminen](/stock). Tämä analyysi on tyypillisesti rakennettu ja koodattu R-ohjelmiston avulla. Tulosten analyysi logaritmisella tuloksella, jota voidaan soveltaa tietojoukkoon luomaan ennustetut hinnat tietylle ajanjaksolle tulevaisuudessa.

ARIMA-mallit perustuvat olettamukseen, että menneillä arvoilla on jonkin verran jäännösvaikutusta nykyisiin tai tuleviin arvoihin. Esimerkiksi sijoittaja, joka käyttää ARIMA-mallia osakkeiden hintojen ennustamiseen, olettaisi, että viimeaikaiset markkinatapahtumat vaikuttavat kyseisen osakkeen uusiin ostajiin ja myyjiin päättäessään, kuinka paljon arvopaperia tarjotaan tai hyväksytään.

Vaikka tämä oletus pätee monissa eri olosuhteissa, se ei aina pidä paikkaansa. Esimerkiksi vuoden 2008 finanssikriisiä edeltävinä vuosina useimmat sijoittajat eivät olleet tietoisia riskeistä, joita monien rahoitusyritysten hallussa olevat suuret [asuntolainavakuudelliset arvopaperisalkut (MBS) aiheuttavat.](/mbs)

Noina aikoina sijoittajalla, joka käytti autoregressiivistä mallia ennustaakseen Yhdysvaltain rahoitusosakkeiden kehitystä, olisi ollut hyvä syy ennustaa jatkuvaa vakaata tai nousevaa osakekurssitrendiä kyseisellä sektorilla. Kun kuitenkin tuli julkisuuteen, että monet rahoituslaitokset olivat vaarassa romahtaa, sijoittajat alkoivat yhtäkkiä vähemmän välittää näiden osakkeiden viimeaikaisista hinnoista ja paljon enemmän niiden taustalla olevista riskeistä.

Siksi markkinat arvostetaan nopeasti uudelleen rahoitusosakkeet paljon alemmalle tasolle, mikä olisi hämmentänyt autoregressiivisen mallin täysin.

##Kohokohdat

- Autoregressiiviset integroidut liikkuvat keskiarvot (ARIMA) ovat Box-Jenkins-mallin muoto.

- Box-Jenkins-malli soveltuu parhaiten ennustamiseen 18 kuukauden tai sitä lyhyemmän aikakehyksen sisällä.

- Metodologia perustuu olettamukseen, että menneet tapahtumat vaikuttavat tuleviin.

- Box-Jenkins-malli on ennustemenetelmä, jossa käytetään aikasarjatietojen regressiotutkimuksia.

