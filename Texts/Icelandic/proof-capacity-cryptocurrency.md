---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Sönnun á getu (dulkóðunargjaldmiðill)
description: Proof of Capacity er samstöðukerfi sem notar harða diskinn í námuhnút til að ákveða netið námuréttinn á blockchain.
---

# Sönnun á getu (dulkóðunargjaldmiðill)
## Hvað er sönnun á getu (PoC) fyrir dulritunargjaldmiðla?

Sönnun á afkastagetu (PoC) er algrím sem notað er í blokkakeðjum sem gerir [námuvinnslutækjum](/consensus-mechanism-cryptocurrency) [á](/bitcoin-mining) netinu kleift að nota tiltækt pláss á harða disknum til að ákveða námuréttindi og staðfesta viðskipti. Þetta er í mótsögn við að nota reiknikraft námubúnaðarins (eins og í reikniritinu fyrir [sönnun á vinnu](/proof-work) ) eða hlut námumannsins í dulritunargjaldmiðlum (eins og í reikniritinu fyrir [sönnun á hlut](/proof-stake-pos) ).

## Skilningur á sönnun á getu

Sönnun á afkastagetu hefur komið fram sem ein af mörgum vallausnum á vandamálinu með mikilli orkunotkun í sönnunargögnum (PoW) kerfum og dulritunargjaldmiðilssöfnun í sönnun á hlut (PoS) kerfum.

Sönnun á afkastagetu gerir námuvinnslutækjum, einnig þekkt sem hnútar, á [blockchain](/blockchain) netinu kleift að nota tómt pláss á harða disknum sínum til að ná tiltækum [dulritunargjaldmiðlum](/cryptocurrency).

Í stað þess að breyta tölunum í blokkarhausnum ítrekað og endurtekið kjötkássa fyrir lausnargildið eins og í PoW kerfi, virkar PoC með því að geyma lista yfir mögulegar lausnir á harða diskinum í námuvinnslutækinu jafnvel áður en námuvinnslan hefst.

Því stærri sem harði diskurinn er, því fleiri möguleg lausnargildi sem maður getur geymt á harða disknum, því meiri líkur eru á að námuverkamaður passi við tilskilið kjötkássagildi af listanum sínum, sem leiðir til fleiri möguleika á að vinna námuvinnsluverðlaunin.

Til að draga upp hliðstæðu, ef lottóverðlaun eru byggð á því að passa við flestar tölur á vinningsmiðanum, þá mun leikmaður með lengri lista yfir mögulegar lausnir eiga betri möguleika á að vinna. Að auki er spilaranum heimilt að halda áfram að nota blokkanúmer lottómiða aftur og aftur ítrekað.

[Burstcoin](/burstcoin) er dulritunargjaldmiðill sem notar sönnunargetukerfi. Aðrar mynt sem nota það eru Storj, Chia og SpaceMint.

## Hvernig PoC virkar: samsæri og námuvinnsla

Samskiptareglur um sönnun á getu felur í sér tveggja þrepa ferli sem felur í sér samsæri og námuvinnslu.

Í fyrsta lagi er harði diskurinn teiknaður: listi yfir öll möguleg [ógild](/nonce) gildi eru búin til með endurtekinni hashing á gögnum, þar á meðal reikning námuverkamanns. Hver slík ómerking inniheldur 8192 kjötkássa, sem eru númeruð frá 0 til 8191. Öll kjötkássa eru pöruð í "scoops", sem þýðir að aðliggjandi kjötkássa eru sameinuð til að mynda par af tveimur. Til dæmis, kjötkássa 0 og 1 eru scoop 0, kjötkássa 2 og 3 eru kjötkássa 1, og svo framvegis.

Annað skrefið felur í sér raunverulega námuæfingu, þar sem námumaður reiknar út númer. Til dæmis, ef námumaður byrjar námuvinnsluna og býr til ausu númer 38, myndi námumaðurinn fara í ausu númer 38 af nonce 1 og nota gögn þess ausa til að reikna út frestgildi.

Ferlið er endurtekið til að reikna út frestinn fyrir hvern ótíma sem haldið er á harða diski námumannsins. Eftir útreikning á öllum frestunum er sá sem hefur lágmarksfrestinn valinn af námuverkamanninum.

Frestur táknar tímalengd í sekúndum sem þarf að líða frá því síðasta blokk var falsuð áður en námumaður fær að falsa nýja blokk. Ef enginn annar hefur falsað blokk innan þessa tíma getur námumaðurinn falsað blokk og krafist blokkarverðlaunanna.

Til dæmis, ef námumaður X kemur með lágmarksfrest upp á 36 sekúndur og engir aðrir námumenn geta falsað kubbinn á næstu 36 sekúndum, mun X tryggja sér möguleika á að falsa næstu blokk og fá verðlaun.

## Kostir og gallar við sönnun á getu

PoC hefur nokkra kosti fram yfir PoW og PoS kerfi, auk nokkurra mikilvægra ókosta sem fela í sér:

<h5><a href="">TTT</a></h5>

##Hápunktar

- Helsti ávinningur PoC kerfis er skilvirkni þess samanborið við sönnunargögn (PoW) og sönnunargögn (PoS) kerfi.

- Blockchains sem keyra á sönnun fyrir getu eru meðal annars Storj, Burst, Chia og SpaceMint.

- Sannvottunarkerfi til að sannreyna getu (PoC) nota aukapláss á harða diski tækisins til að geyma lausnir á dulritunargjaldmiðils-hashing vandamáli.

