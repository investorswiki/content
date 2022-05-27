---
keywords: Business,Corporate Finance and Accounting,Financial Analysis
title: Binomial Dreifing
description: Tvínómadreifingin er líkindadreifing sem tekur saman líkurnar á því að gildi taki annað af tveimur sjálfstæðum gildum.
---

# Binomial Dreifing
## Hver er tvínefnadreifingin?

Tvínefnadreifingin er [líkindadreifing](/probabilitydistribution) sem dregur saman líkurnar á því að gildi taki annað af tveimur sjálfstæðum gildum samkvæmt tilteknu setti af breytum eða forsendum.

Undirliggjandi forsendur tvínefnadreifingarinnar eru að það sé aðeins ein niðurstaða fyrir hverja tilraun, að hver rannsókn hafi sömu líkur á árangri og að hver tilraun sé [gagnkvæm útilokuð](/mutuallyexclusive) eða óháð hver annarri.

## Skilningur á tvíliðadreifingu

Tvínefnadreifingin er algeng [stakdreifing](/discrete-distribution) sem notuð er í tölfræði, öfugt við samfellda dreifingu, eins og [normaldreifingu](/normaldistribution). Þetta er vegna þess að tvínafnadreifingin telur aðeins tvö ríki, venjulega táknuð sem 1 (fyrir árangur) eða 0 (fyrir mistök) miðað við fjölda tilrauna í gögnunum. Tvínefnadreifingin táknar þannig líkurnar á x árangri í n tilraunum, gefið árangurslíkur p fyrir hverja tilraun.

Binomial dreifing tekur saman fjölda prófana, eða athuganir þegar hver rannsókn hefur sömu líkur á að ná einu tilteknu gildi. Tvínefnadreifingin ákvarðar líkurnar á því að fylgjast með tilteknum fjölda árangursríkra niðurstaðna í tilteknum fjölda tilrauna.

Tvínefnadreifingin er oft notuð í félagsvísindatölfræði sem byggingareining fyrir líkön fyrir tvískipta útkomubreytur, eins og hvort repúblikani eða demókrati muni vinna komandi kosningar eða hvort einstaklingur muni deyja innan tiltekins tíma osfrv.

## Greining tvíliðadreifingar

Vænt gildi, eða meðaltal, tvínafna dreifingar, er reiknað út með því að margfalda fjölda tilrauna (n) með líkum á árangri (p), eða nx p.

Til dæmis er væntanlegt gildi fjölda hausa í 100 tilraunum með höfuð og sögur 50, eða (100 * 0,5). Annað algengt dæmi um tvínefnadreifingu er með því að áætla líkurnar á árangri fyrir vítaskot í körfubolta þar sem 1 = karfa er gerð og 0 = missa.

Tvínómadreifingarformúlan er reiknuð út sem:

>

> P~(x:n,p)~ = ~n~C~x~ xp^x^(1-p)^nx^

>

hvar:

- n er fjöldi tilrauna (tilvika)

- X er fjöldi árangursríkra prófana

- p er líkur á árangri í einni tilraun

- nCx er samsetning n og x. Samsetning er fjöldi leiða til að velja sýnishorn af x þáttum úr mengi n aðskildra hluta þar sem röð skiptir ekki máli og skiptingar eru ekki leyfðar. Athugaðu að nCx=n!/(r!(n−r)!), þar sem ! er þáttaskil (svo, 4! = 4 x 3 x 2 x 1)

Meðaltal tvínómadreifingarinnar er np og dreifni tvíliðadreifingarinnar er np (1 − p). Þegar p = 0,5 er dreifingin samhverf í kringum meðaltalið. Þegar p > 0,5 skekkist dreifingin til vinstri. Þegar p < 0,5 skekkist dreifingin til hægri.

Tvínómadreifingin er summa af röð margra óháðra og eins dreifðra Bernoulli rannsókna. Í Bernoulli rannsókn er sagt að tilraunin sé tilviljunarkennd og getur aðeins haft tvær mögulegar niðurstöður: árangur eða mistök.

Til dæmis telst það vera Bernoulli réttarhöld að fletta mynt; hver prufa getur aðeins tekið eitt af tveimur gildum (höfuð eða hala), hver árangur hefur sömu líkur (líkur á að snúa höfði eru 0,5), og niðurstöður einnar tilraunar hafa ekki áhrif á niðurstöður annarrar. Bernoulli dreifingin er sértilfelli af tvínefnadreifingunni þar sem fjöldi prófana n = 1.

## Dæmi um tvíliðadreifingu

Tvínefnadreifingin er reiknuð út með því að margfalda líkurnar á velgengni hækkaðar í veldi fjölda árangurs og líkur á bilun hækkaðar í krafti mismunsins á fjölda árangurs og fjölda tilrauna. Margfaldaðu síðan vöruna með samsetningunni á milli fjölda prófana og fjölda árangurs.

Gerum til dæmis ráð fyrir að spilavíti hafi búið til nýjan leik þar sem þátttakendur geta lagt veðmál á fjölda hausa eða hala í tilteknum fjölda myntsleppinga. Gerum ráð fyrir að þátttakandi vilji leggja $10 veðmál um að það verði nákvæmlega sex höfuð í 20 myntsleppingum. Þátttakandinn vill reikna út líkurnar á því að þetta gerist og nota því útreikninginn fyrir tvínefnadreifingu.

Líkurnar voru reiknaðar sem: (20! / (6! * (20 - 6)!)) * (0,50)^(6) * (1 - 0,50) ^ (20 - 6). þar af leiðandi eru líkurnar á því að nákvæmlega sex hausar komi fyrir í 20 myntflötum 0,037, eða 3,7%. Áætlað gildi var 10 höfuð í þessu tilfelli, þannig að þátttakandinn gerði lélegt veðmál.

##Hápunktar

- Tvínefnadreifingin er líkindadreifing sem dregur saman líkurnar á því að gildi taki annað af tveimur sjálfstæðum gildum samkvæmt tilteknu setti af breytum eða forsendum.

- Undirliggjandi forsendur tvínefnadreifingarinnar eru að það sé aðeins ein niðurstaða fyrir hverja tilraun, að hver tilraun hafi sömu líkur á árangri og að hver tilraun sé innbyrðis útilokuð eða óháð hver annarri.

- Tvínómadreifingin er algeng stakdreifing sem notuð er í tölfræði, öfugt við samfellda dreifingu, eins og normaldreifingu.

