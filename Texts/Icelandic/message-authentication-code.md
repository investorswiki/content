---
keywords: Personal Finance,Banking
title: Message Authentication Code (MAC)
description: Auðkenningarkóði skilaboða (MAC), eða merki, er öryggiskóði sem er sleginn inn af notanda tölvu til að fá aðgang að reikningum eða gáttum.
---

# Message Authentication Code (MAC)
## Hvað er auðkenningarkóði skilaboða?

Auðkenningarkóði skilaboða (MAC), eða **merki,** er öryggiskóði sem notandi tölvunnar slærð inn til að fá aðgang að reikningum eða gáttum. Þessi kóði fylgir skilaboðunum eða beiðninni sem notandinn sendir. Skilaboðaauðkenningarkóðar (MAC) sem fylgja skilaboðunum verða að vera viðurkenndir af móttökukerfinu til að veita notanda aðgang.

## Skilningur á auðkenningarkóða skilaboða (MAC)

Skilaboðaauðkenningarkóðar (MAC) eru almennt notaðir í [rafrænum millifærslum](/electronic-funds-transfer-act) (EFT) til að viðhalda heiðarleika upplýsinga. Þeir staðfesta að skilaboð séu ósvikin; að það komi í raun, með öðrum orðum, frá tilgreindum sendanda og hafi ekki tekið neinum breytingum á leiðinni. Sannprófandi sem einnig hefur lykilinn getur notað hann til að bera kennsl á breytingar á innihaldi viðkomandi skeytis.

Skilaboðaauðkenningarkóðar eru venjulega nauðsynlegir til að fá aðgang að hvers kyns fjárhagsreikningi. Bankar, verðbréfafyrirtæki, fjárvörslufyrirtæki og önnur innláns-, fjárfestingar- eða tryggingafyrirtæki sem bjóða upp á netaðgang geta notað þessa kóða. Þau eru mikilvægur þáttur í dulmáli fjármála.

## Reiknirit notað til að búa til MAC

Þrjú reiknirit samanstanda venjulega af MAC: lyklamyndunaralgrími, undirritunaralgrími og sannprófunaralgrími. Lyklamyndunaralgrím velur lykil af handahófi. Undirritunaralgrímið sendir merki þegar hann gefur lykilinn og skilaboðin. Staðfestingaralgrímið er notað til að sannreyna áreiðanleika skilaboðanna þegar lykillinn og merkið er gefið; það mun skila skilaboðum um **samþykkt** ef skilaboðin og merkið eru ósvikin og óbreytt, en að öðrum kosti mun það skila skilaboðum um **hafnað.**

Sendandi sendir til dæmis skilaboð, eins og EFT, í gegnum MAC reikniritið, sem býr til lykil og setur MAC gagnamerki við skilaboðin. Viðtakandinn fær skilaboðin, keyrir þau aftur í gegnum MAC reikniritið með sama lykli og fær annað gagnamerki. Þeir munu síðan bera þetta MAC gagnamerki saman við það fyrsta sem er fest við skilaboðin þegar þau voru send. Ef kóðinn er sá sami í báða enda getur viðtakandinn örugglega gengið út frá því að gagnaheilleiki skilaboðanna sé ósnortinn. Ef ekki þýðir það hins vegar að skilaboðunum hafi verið breytt, átt við eða falsað.

Hins vegar ætti skeytið sjálft að innihalda nokkur gögn sem tryggja að aðeins sé hægt að senda þessi skilaboð einu sinni. Til dæmis væri hægt að nota einu sinni MAC, tímastimpil eða raðnúmer til að tryggja að aðeins sé hægt að senda skilaboðin einu sinni. Annars gæti kerfið verið viðkvæmt fyrir endurspilunarárás, þar sem árásarmaður grípur skilaboðin eftir að þau hafa verið afkóðuð og sendir þau aftur síðar, endurtekur upprunalegu niðurstöðurnar og síast inn í kerfið.

## Skilaboðsheilleikakóðar (MIC)

Stundum verður hugtakið Message Integrity Code (MIC) notað í stað MAC. Þetta er oftast gert í fjarskiptaiðnaðinum, þar sem MAC þýðir venjulega fjölmiðlaaðgangsstýringarfang (MAC vistfang). Hins vegar er einnig hægt að nota MIC til að vísa til **skilaboðasamdráttar** sem notar ekki leynilykla á sama hátt og MAC og getur ekki boðið upp á sama öryggisstig án frekari dulkóðunar.

