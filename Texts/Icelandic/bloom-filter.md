---
keywords: Crypto
title: Blómstra sía
description: Blómstra sía. Gagnauppbygging sem hægt er að nota til að upplýsa notandann um hvort tiltekinn hlutur sé hluti af hlutum
---

# Blómstra sía
Bloom sía er gagnauppbygging sem hægt er að nota til að upplýsa notandann um hvort tiltekinn hlutur sé hluti af mengi. Þó það geti ekki sagt með vissu hvort þáttur sé í menginu, getur hún sagt með vissu hvort þátturinn er það ekki.

Búið til af Burton Howard Bloom árið 1970, Bloom síur eru aðlaðandi tilboð fyrir margs konar notkun vegna skilvirkni þeirra í plássnotkun. Í sumum dulritunargjaldmiðlum (einkum Bitcoin) gegna þeir mikilvægu hlutverki í Simplified Payment Verification, eða SPV.

Með því að nota SPV viðskiptavin geta notendur haft samskipti við Bitcoin netið án þess að keyra fullan hnút. Fullir hnútar eru með ákveðnar kröfur um geymslu og útreikninga sem gera þá ómeðhöndlaða til að keyra á litlum tækjum eins og snjallsímum. SPV viðskiptavinir, aftur á móti, spyrja einfaldlega um alla hnúta til að fá upplýsingar sem tengjast veski/veski notandans.

Einfaldasta lausnin til að miðla þessum gögnum til notandans væri með því að gera fulla hnúta meðvitaða um lykla viðskiptavinarins, þannig að aðeins viðeigandi færslur eru sendar til þeirra. Augljóslega er þetta undirmálslausn þar sem friðhelgi viðskiptavinarins yrði fórnað. Á hinn bóginn væri það sóun á bandbreidd að hlaða niður öllum viðskiptum eingöngu til að farga meirihluta þeirra. Sláðu inn Bloom síur.

Við skulum sýna. Segjum sem svo að viðskiptavinur, Alice, sé með verðmæta viðskipti sem hún vill ekki að Bob, sem rekur heilan hnút, sé meðvitaður um. Hún smíðar Bloom síu, sem við munum sýna sem 10x1 rist:

Hún sendir færslugögnin sem hún hefur áhuga á í gegnum tvær mismunandi kjötkássaaðgerðir, sem gefa út tvær tölur á milli 0 og 9. Við skulum kalla þær 4 og 7. Hún sendir síuna til Bob.

Þegar þú horfir á þetta rist hefurðu ekki hugmynd um hvaða gögn Alice hefur sent til síunnar. Ef þú værir með sett þar sem gögnin innihéldu gætirðu hassað þau og borið saman við síuna – ef það er samsvörun er möguleiki á að það hafi verið upplýsingarnar sem Alice bað um.

Á sama tíma er líklegt að það séu mörg inntak sem munu varpa til 4 og 7, svo Bob getur ekki ákveðið hvaða hluta gagna Alice hefur áhuga á. Hann skilar einfaldlega öllum eldspýtunum og Alice síar þær á enda hennar.

Þetta er auðvitað gróf ofureinföldun, en hún sýnir hugmyndina: Bloom-síur torvelda raunverulega hagsmuni viðskiptavinarins. Það er ekki fullkomin aðferð (það eru enn áhyggjur af friðhelgi einkalífsins), en það er framför yfir óvarða beiðni til hnút.

