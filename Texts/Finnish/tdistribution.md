---
keywords: Trading,Technical Analysis
title: T Jakelu
description: AT-jakauma on eräänlainen todennäköisyysfunktio, joka soveltuu populaation parametrien arvioimiseen pienille otoskokoille tai tuntemattomille varianssille.
---

# T Jakelu
## Mikä on T-jakelu?

T-jakauma, joka tunnetaan myös nimellä Studentin t-jakauma, on eräänlainen [todennäköisyysjakauma](/probabilitydistribution),. joka on samanlainen kuin normaalijakauma kellomuodoltaan, mutta jolla on raskaammat häntät. T-jakaumilla on suurempi mahdollisuus saada ääriarvoja kuin normaalijakaumilla, joten lihavammat hännät.

## Mitä T-jakelu kertoo sinulle?

Hännän raskaus määräytyy T-jakauman parametrilla, jota kutsutaan [vapausasteiksi.](/degrees-of-freedom) Pienemmät arvot antavat painavampia häntäjä ja suuremmat arvot tekevät T-jakaumasta muistuttavan normaalia normaalijakaumaa, jonka keskiarvo on 0 ja keskihajonna 1. T-jakelu tunnetaan myös nimellä "Student's T Distribution".

<!--7D50237348822D30DFF69E0C32EC0A76-->

Kun n havainnon näyte otetaan normaalijakautuneesta populaatiosta, jonka keskiarvo on M ja keskihajonta D, näytteen keskiarvo m ja näytteen keskihajonta d eroavat M:stä ja D:stä näytteen satunnaisuuden vuoksi.

Z-piste voidaan laskea populaation keskihajonnan avulla Z = (x – M)/D, ja tällä arvolla on normaalijakauma keskiarvolla 0 ja keskihajonnalla 1. Mutta kun käytetään arvioitua keskihajontaa, t-piste lasketaan kaavalla T = (m – M)/{d/sqrt(n)}, d:n ja D:n ero tekee jakaumasta T-jakauman, jossa on (n - 1) vapausaste, eikä normaalijakauman, jonka keskiarvo on 0 ja keskihajonta 1.

## Esimerkki T-jakelun käyttämisestä

Otetaan seuraava esimerkki kuinka t-jakaumia käytetään tilastollisessa analyysissä. Ensinnäkin muista, että keskiarvon luottamusväli on tiedoista laskettu arvoalue, jonka tarkoituksena on kaapata ”populaation” keskiarvo. Tämä väli on m +- t*d/sqrt(n), missä t on kriittinen arvo T-jakaumasta.

Esimerkiksi 95 %:n luottamusväli Dow Jones Industrial Averagen keskimääräiselle tuotolle 27 kaupankäyntipäivänä ennen 9/11/2001 on -0,33 % (+/- 2,055) * 1,07 / m²(27), antaa (pysyvä) keskimääräinen tuotto jonakin numerona välillä -0,75 % ja +0,09 %. T-jakaumasta löytyy luku 2,055, standardivirheiden määrä, jonka mukaan on sovitettava.

Koska T-jakaumalla on paksumpi häntä kuin normaalijakaumassa, sitä voidaan käyttää mallina taloudelliselle tuotolle, jossa on ylimääräistä kurtoosia, mikä mahdollistaa realistisemman Value at Risk ( [VaR](/var) ) laskennan tällaisissa tapauksissa.

## Ero T-jakelun ja normaalijakelun välillä

Normaalijakaumia käytetään, kun populaatiojakauman oletetaan olevan normaali. T-jakauma on samanlainen kuin normaalijakauma, vain lihavammilla hännillä. Molemmat olettavat normaalisti jakautuneen populaation. T-jakaumilla on suurempi kurtoosi kuin normaalijakaumilla. Todennäköisyys saada arvot hyvin kaukana keskiarvosta on suurempi T-jakaumalla kuin normaalijakaumalla.

## T-jakelun käytön rajoitukset

T-jakauma voi vääristää tarkkuutta suhteessa normaalijakaumaan. Sen puute ilmenee vain silloin, kun tarvitaan täydellistä normaalia. T-jakaumaa tulisi käyttää vain, kun populaation keskihajontaa ei tunneta. Jos populaation keskihajonnan tunnetaan ja otoskoko on riittävän suuri, tulee parempien tulosten saamiseksi käyttää normaalijakaumaa.

## Kohokohdat

- T-jakauma on z-pisteen jatkuva todennäköisyysjakauma, kun nimittäjässä käytetään arvioitua keskihajontaa todellisen keskihajonnan sijaan.

- T-jakauma, kuten normaalijakauma, on kellomainen ja symmetrinen, mutta siinä on raskaammat häntät, mikä tarkoittaa, että se pyrkii tuottamaan arvoja, jotka putoavat kaukana sen keskiarvosta.

- T-testejä käytetään tilastoissa merkitsevyyden arvioimiseen.

