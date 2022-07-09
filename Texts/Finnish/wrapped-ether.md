---
keywords: Crypto
title: Kääritty eetteri (WETH)
description: Kääritty eetteri (WETH). ERC-20-merkki, joka edustaa eetteriä suhteessa 1:1. Sen avulla käyttäjät voivat vaihtaa ETH:ta ERC-20-tokeneihin hajautetuilla alustoilla.
---

# Kääritty eetteri (WETH)
Wrapped Ether (WETH) viittaa [ERC-20-](/erc-20) yhteensopivaan eetterin versioon (eetterin kääriminen muiden ERC-standardien kanssa on myös mahdollista). WETH voidaan luoda lähettämällä eetteri älykkääseen sopimukseen, jossa eetteri asetetaan pitoon, ja se puolestaan vastaanottaa WETH ERC-20 -tokenin suhteessa 1:1. Tämä WETH voidaan myöhemmin lähettää takaisin samaan älysopimukseen "purkaa" tai lunastaa takaisin alkuperäiseen eetteriin suhteessa 1:1.

Ether, joka on Ethereum-lohkoketjun alkuperäinen valuutta, luotiin ennen kuin ERC-20-standardi ja muut standardit otettiin käyttöön; Tästä syystä eetteri itsessään ei ole ERC-20-yhteensopiva, eikä sitä voida vaihtaa suoraan muihin ERC-20-tokeneihin hajautetusti ilman luotettavan kolmannen osapuolen välitystä tai monimutkaisten teknisten toteutusten lisäämistä. Sen sijaan, että ottaisivat käyttöön kaksi rajapintaa (yksi eetterille ja toinen ERC-20-tokeneille) samassa älykkäässä sopimuksessa, mikä johtaisi tarpeettomiin monimutkaisiin toimiin, kehittäjät päättivät "kääriä" eetterin päivittääkseen sen ERC-20-standardiin, jotta se käsittelee kätevästi WETH- ja muut ERC-20:t samassa sopimuksessa. Eetterin kääriminen mahdollistaa suoran, saumattoman vaihdon eetterin ja ERC-20-tokenien välillä ilman, että tarvitaan luotettavaa kolmatta osapuolta ja ilman tarpeettomia riskejä, kuten monimutkaisista toteutuksista johtuvia odottamattomia virheitä tapahtumien aikana. Monet Ethereum-pohjaiset [hajautetut sovellukset (dApps)](/decentralized-applications-dapps),. kuten [hajautetut](/decentralized-exchange) vaihtoalustat, käyttävät WETH:ää eetterin sijasta helpottaakseen suoraa ja hajautettua vertaiskauppaa "pakattu muodossa" olevan eetterin ja ERC-20-tokenien välillä saman teknisen standardin mukaisesti. Viimeaikaiset kehitystyöt yrittävät saada kanonista WETH-standardia, jota kaikki Ethereum-pohjaiset dAppit voisivat käyttää.

