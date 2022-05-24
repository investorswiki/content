---
keywords: Crypto
title: BEP-95
description: BEP-95. BEP-95 on Binance Evolution -ehdotus, joka esittelee reaaliaikaisen polttomekanismin Binance Smart Chainille. Se tekee BNB-tokenomiikasta dynaamisemman ja hajautetumman.
---

# BEP-95
BEP-95 on Binance Evolution -ehdotus, joka esittelee reaaliaikaisen polttomekanismin Binance Smart Chainille. Se on otettu käyttöön tehdäkseen BNB:n tokenomiikasta entistä dynaamisemman ja hajauttamaan verkkoa entisestään.

BEP-95:n avulla verkko polttaa kiinteän suhteen kunkin lohkon kaasumaksuista, jotka validaattorit keräävät. Tarkka suhdeluku määräytyy BSC:n hallintomekanismien kautta. Palovammat tapahtuvat senkin jälkeen, kun BSC on saavuttanut 100 miljoonan BNB:n tavoitetavoitteensa. Vähentämällä BNB:n tarjontaa kolikon hintaan kohdistuu nousupaineita. BEP voi myös vähentää vastaanotettujen BNB:n delegaattoreiden ja validoijien määrää. Hintapaineen myötä fiat-arvo voi kuitenkin myös nousta, mikä kompensoi kolikoiden laskun.

Tämän teknisen toteuttamiseksi verkko kerää kunkin lohkon kaasumaksut ja jakaa kahdelle älykkäälle sopimukselle:

**yksi. System Reward -sopimus.** 1/16 kaasumaksuista tulee System Reward -sopimukseen, kunnes se saavuttaa enintään 100 BNB. Näitä kolikoita käytetään ketjujen välisenä pakettitukena.

**2. ValidatorSet-sopimus.** Kaikki muut kaasumaksut sisällytetään ValidatorSet-sopimukseen ja jaetaan päivittäin delegaattoreiden ja validaattoreiden kanssa Binance Chainin kautta.

Polttoa varten ValidatorSet Contractissa on burnRatio-muuttuja. Kun jokainen lohko on viimeistelty, validaattori allekirjoittaa tapahtuman, joka siirtää kaasumaksunsa älykkäisiin sopimuksiin. Talletustoiminto sisältää polttologiikkaa, joka laukaisee yksinkertaisen kaavan: burnRatio * gasFee. Tämä summa siirretään sitten polttoosoitteeseen. Palamissuhde asetetaan aluksi 10 prosenttiin.

BSC Validators voi äänestää ehdotusten kautta polttosuhteen määrän muuttamiseksi. Tämä hallintomekanismi tapahtuu Binance Chainissa, ja kuka tahansa yhteisön jäsen voi lähettää ehdotuksen tarkistettavaksi vähintään 2 000 BNB:n talletuksella. Kaikki ehdotuksen takana ja äänestyksessä panostetut BNB:t palautetaan päätöksen tekemisen jälkeen. Päätösvaltaisuus saavutetaan 50 %:ssa ja muutos toteutetaan välittömästi ketjujen välisellä viestinnällä.

