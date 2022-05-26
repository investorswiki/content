---
keywords: Crypto
title: Gossip Protocol
description: Gossip Protocol. Erityinen menetelmä asynkroniseen vertaisviestintään hajautetun järjestelmän tietokonesolmujen välillä.
---

# Gossip Protocol
Termi juoruprotokolla viittaa tietyntyyppiseen P2P (peer-to-peer) -viestintään, joka tapahtuu tietokoneiden ja muiden digitaalisten laitteiden välillä. Termin kolikon inspiraationa on ollut juorujen perinteinen muoto, joka on yleinen sosiaalisissa ryhmissä.

Tietojenkäsittelytieteen kontekstissa juoruprotokolla liittyy eräänlaiseen viestintään, joka tapahtuu, kun dataa siirretään eri tietokonesolmujen kautta, jotka ovat osa hajautettua verkkoa. Kuten nimestä voi päätellä, juoruprotokollaviestintä tapahtuu, kun tietoa lähetetään tietokoneelta toiselle, kunnes se lopulta leviää kaikkialle verkossa. Tällä hetkellä Gossip-protokollasta on useita muunnelmia, joita voidaan soveltaa erilaisiin skenaarioihin käyttäjän tai organisaation tarpeista riippuen.

Szegedin yliopiston professori Márk Jelasityn mukaan juorujen ilmentymistä on kahta päätyyppiä: tiedon levittäminen ja tiedon yhdistäminen. Nämä kaksi tyyppiä ovat suuren mittakaavan hajautettujen järjestelmien avainelementtejä.

Toisaalta juorujen levittäminen, joka tunnetaan myös nimellä multicast, liittyy perinteiseen tiedonjakelutapaan (yksi verkkosolmu kerrallaan). Toisaalta juorujen aggregointiprotokollat käsittelevät dataa, eli ne ensin tiivistävät tiedot ja sitten jakavat sen (tämän tyyppistä juoruviestintää voidaan kutsua myös hajautetuksi tiedon louhinnaksi).

Mielenkiintoinen esimerkki hajautetusta järjestelmästä, joka käyttää juoruprotokollaa, on Leemon Bairdin vuonna 2016 luoma Hashgraph. Se on hajautettu pääkirjatekniikka, joka käyttää asynkronista Byzantine Fault Tolerance (aBFT) -konsensusalgoritmia. Hashgraph-verkon solmut keräävät ja tiivistävät tietoja tapahtumista ja muista tapahtumista ja levittävät tämän tiedon muille satunnaisesti valituille naapurisolmuille. Joten lohkojen ketjun rakentamisen sijaan Hashgraph-verkko rakentaa tapahtumapuun, johon kaikki tiedot tallennetaan (dataa ei koskaan hylätä).

