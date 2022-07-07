---
keywords: Economy,Economics,Behavioral Economics
title: Taaksepäin induktio
description: Peliteoriassa taaksepäin induktio on prosessi, jossa päätellään taaksepäin ongelman tai skenaarion lopusta optimaalisten toimien sarjan päättelemiseksi.
---

# Taaksepäin induktio
## Mikä on taaksepäin induktio?

Taaksepäin induktio [peliteoriassa](/gametheory) on iteratiivinen päättelyprosessi ajassa taaksepäin, ongelman tai tilanteen lopusta, äärellisen laajan muodon ja peräkkäisten pelien ratkaisemiseksi ja optimaalisten toimintojen sarjan päättelemiseksi.

## Taaksepäin induktio selitetty

Taaksepäin induktiota on käytetty pelien ratkaisemiseen siitä lähtien, kun John von Neumann ja Oskar Morgenstern perustivat peliteorian akateemiseksi aineeksi julkaistessaan kirjansa **Pelien teoria ja taloudellinen käyttäytyminen** vuonna 1944.

Pelin jokaisessa vaiheessa taaksepäin induktio määrittää pelin viimeisen liikkeen tekevän pelaajan optimaalisen strategian. Tämän jälkeen viimeiseksi liikkuvan pelaajan optimaalinen toiminta määritetään ottaen huomioon viimeisen pelaajan toiminta. Tämä prosessi jatkuu taaksepäin, kunnes kullekin ajankohdalle on määritetty paras toimenpide. Käytännössä määritetään alkuperäisen pelin jokaisen alipelin [Nash-tasapaino .](/nash-equilibrium)

Taaksepäin induktiosta päätellyt tulokset eivät kuitenkaan usein pysty ennustamaan todellista ihmisen leikkimistä. Kokeelliset tutkimukset ovat osoittaneet, että "rationaalista" käyttäytymistä (kuten peliteoria ennustaa) esiintyy harvoin tosielämässä. Irrationaaliset pelaajat voivat itse asiassa saada suurempia voittoja kuin taaksepäin induktio ennusti, kuten [tuhatjalkaisessa pelissä](/centipede-game) on kuvattu .

Satajalkaisessa pelissä kaksi pelaajaa saavat vuorotellen mahdollisuuden ottaa suuremman osuuden kasvavasta rahapotista tai siirtää potin toiselle pelaajalle. Voitot on järjestetty siten, että jos potti siirretään vastustajalle ja vastustaja ottaa potin seuraavalla kierroksella, saa hieman vähemmän kuin jos olisi ottanut potin tällä kierroksella. Peli päättyy heti, kun pelaaja ottaa kätkön, jolloin hän saa suuremman osan ja toinen pelaaja saa pienemmän osan.

## Esimerkki taaksepäin induktiosta

Oletetaan esimerkiksi, että Izaz menee ensin ja hänen on päätettävä, pitäisikö heidän "ottaa" vai "välittää" kätkö, joka on tällä hetkellä 2 dollaria. Jos he ottavat, Izaz ja Jian saavat kumpikin 1 dollarin, mutta jos Izaz läpäisee, Jianin on nyt tehtävä päätös ottamista tai hyväksymisestä. Jos Jian ottaa, he saavat 3 dollaria (eli edellinen 2 dollari + 1 dollari) ja Izaz 0 dollaria. Mutta jos Jian läpäisee, Izaz saa nyt päättää ottaako vai siirtääkö hän ja niin edelleen. Jos molemmat pelaajat päättävät aina läpäistä, he saavat kukin 100 dollarin voiton pelin lopussa.

Pelin pointti on, jos Izaz ja Jian molemmat tekevät yhteistyötä ja jatkavat syöttöä pelin loppuun asti, he saavat maksimivoiton 100 dollaria kumpikin. Mutta jos he eivät luota toiseen pelaajaan ja odottavat hänen "ottavan" ensimmäisellä tilaisuudella, Nash-tasapaino ennustaa, että pelaajat ottavat pienimmän mahdollisen vaatimuksen (tässä tapauksessa $1).

Tämän pelin Nash-tasapaino, jossa kenelläkään pelaajalla ei ole kannustinta poiketa valitsemastaan strategiasta vastustajan valinnan jälkeen, ehdottaa, että ensimmäinen pelaaja ottaisi potin pelin aivan ensimmäisellä kierroksella. Todellisuudessa suhteellisen harvat pelaajat tekevät niin. Tämän seurauksena he saavat suuremman voiton kuin tasapainoanalyysin ennustama voitto.

## Peräkkäisten pelien ratkaiseminen taaksepäin induktiolla

Alla on yksinkertainen peräkkäinen peli kahden pelaajan välillä. Tarrat, joissa on Player 1 ja Player 2, ovat tietojoukkoja pelaajille yksi tai kaksi. Puun alaosassa suluissa olevat numerot ovat kunkin pisteen voittoja. Peli on myös peräkkäinen, joten pelaaja 1 tekee ensimmäisen päätöksen (vasen tai oikea) ja pelaaja 2 tekee päätöksensä Pelaajan 1 jälkeen (ylös tai alas).

<!--360C571136D68BDF7B1BE984014B1A1C-->

Taaksepäin induktio, kuten kaikki peliteoria, käyttää rationaalisuuden ja maksimoimisen oletuksia, mikä tarkoittaa, että pelaaja 2 maksimoi voittonsa missä tahansa tilanteessa. Kummassakin tietojoukossa meillä on kaksi vaihtoehtoa, yhteensä neljä. Poistamalla valinnat, joita pelaaja 2 ei valitse, voimme kaventaa puutamme. Tällä tavalla merkitsemme sinisellä viivat, jotka maksimoivat pelaajan voiton annetulla tietojoukolla.

<!--E78C02A07C982A1B447ED0D16A9FCE40-->

Tämän vähennyksen jälkeen pelaaja 1 voi maksimoida voittonsa nyt, kun pelaaja 2:n valinnat ovat tiedossa. Tuloksena on tasapaino, joka löydetään induktiolla taaksepäin, kun pelaaja 1 valitsee "oikea" ja pelaaja 2 valitsee "ylös". Alla on ratkaisu peliin, jossa tasapainopolku on lihavoitu.

<!--4DEC4364358F0D1CB7D219006F74D652-->

Voit esimerkiksi helposti perustaa yllä olevan kaltaisen pelin käyttämällä yrityksiä pelaajina. Tämä peli voi sisältää [tuotejulkaisuskenaarioita](/rollout). Jos yritys 1 haluaisi julkaista tuotteen, mitä yritys 2 voisi tehdä vastauksena? Julkaiseeko Yritys 2 samanlaisen kilpailevan tuotteen? Ennustelemalla tämän uuden tuotteen myyntiä eri skenaarioissa voimme luoda pelin ennustamaan, miten tapahtumat voivat kehittyä [.](/forecasting) Alla on esimerkki tällaisen pelin mallista.

<!--D102F649421403ABDBD56A5C1B29CF03-->

