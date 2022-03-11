---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: Autoregressive Integrated Moving Average (ARIMA)
description: Sjálfvirkt samþætt hreyfanlegt meðaltal (ARIMA) er tölfræðigreiningarlíkan sem nýtir tímaraðargögn til að spá fyrir um framtíðarþróun.
---

# Autoregressive Integrated Moving Average (ARIMA)
## Hvað er sjálfvirkt samþætt hreyfanlegt meðaltal (ARIMA)?

Sjálfvirkt samþætt hreyfanlegt meðaltal, eða ARIMA, er tölfræðileg greiningarlíkan sem notar [tímaraðir gögn](/timeseries) til að annað hvort skilja gagnasettið betur eða spá fyrir um framtíðarþróun.

Tölfræðilíkan er sjálfvirkt ef það spáir fyrir um framtíðargildi byggt á fyrri gildum. Til dæmis gæti ARIMA líkan leitast við að spá fyrir um framtíðarverð hlutabréfa byggt á fyrri afkomu eða spá fyrir um tekjur fyrirtækis byggt á fyrri tímabilum.

## Að skilja sjálfvirkt samþætt hreyfanlegt meðaltal (ARIMA)

Sjálfvirkt samþætt hreyfanlegt meðaltalslíkan er form [aðhvarfsgreiningar](/regression) sem metur styrk einnar háðrar breytu miðað við aðrar breytast breytur. Markmið líkansins er að spá fyrir um framtíðarhreyfingar verðbréfa eða fjármálamarkaða með því að skoða muninn á verðmætum í flokknum í stað raungilda.

Hægt er að skilja ARIMA líkan með því að útlista hvern hluta þess á eftirfarandi hátt:

- [Sjálfvirk aðhvarf (AR)](/autoregressive) : vísar til líkans sem sýnir breytta breytu sem dregur aftur úr eigin töfum, eða fyrri, gildum.

- **Samþætt (I):** táknar muninn á hráum athugunum til að leyfa tímaröðinni að verða kyrrstæðar (þ.e. gagnagildum er skipt út fyrir muninn á gagnagildunum og fyrri gildum).

- [Hreyfanlegt meðaltal (MA)](/movingaverage) : felur í sér ósjálfstæði á milli athugunar og afgangsskekkju úr hreyfanlegu meðaltalslíkani sem notað er við tafir athuganir.

## ARIMA færibreytur

Hver hluti í ARIMA virkar sem færibreyta með staðlaðri nótnaskrift. Fyrir ARIMA líkön væri staðlað merking ARIMA með p, d og q, þar sem heiltölugildi koma í stað færibreytanna til að gefa til kynna hvers konar ARIMA líkan er notað. Hægt er að skilgreina færibreyturnar sem:

- **p**: fjöldi töfathugana í líkaninu; einnig þekkt sem töfröð.

- **d**: fjöldi skipta sem óunnar athuganir eru mismunandi; einnig þekkt sem gráðu mismunarins.

- q: stærð meðaltalsgluggans á hreyfingu; einnig þekkt sem röð hlaupandi meðaltals.

Í [línulegu aðhvarfslíkani](/nonlinear-regression) er til dæmis fjöldi og gerð hugtaka innifalin. 0 gildi, sem hægt er að nota sem færibreytu, myndi þýða að tiltekinn hluti ætti ekki að nota í líkaninu. Þannig er hægt að smíða ARIMA líkanið til að framkvæma virkni ARMA líkans, eða jafnvel einföld AR, I eða MA líkan.

> Vegna þess að ARIMA líkön eru flókin og virka best á mjög stórum gagnasöfnum, eru tölvualgrím og vélanámstækni notuð til að reikna þau.

>

## Autoregressive Integrated Moving Average (ARIMA) og kyrrstöðu

Í sjálfvirkt samþættu hreyfanlegu meðaltalslíkani eru gögnin mismunandi til að gera þau kyrrstæð. Líkan sem sýnir kyrrstöðu er líkan sem sýnir að gögnin eru stöðug með tímanum. Flest efnahags- og markaðsgögn sýna þróun, svo tilgangurinn með aðgreiningu er að fjarlægja allar þróunarstefnur eða árstíðabundin uppbygging.

[Árstíðasveifla](/seasonality),. eða þegar gögn sýna reglulega og fyrirsjáanleg mynstur sem endurtaka sig á almanaksári, gæti haft neikvæð áhrif á aðhvarfslíkanið. Ef stefna birtist og kyrrstaða er ekki augljós er ekki hægt að gera margar útreikninga í gegnum ferlið með mikilli skilvirkni.

> Eitt sinn áfall mun hafa áhrif á síðari gildi ARIMA líkans óendanlega inn í framtíðina. Þess vegna lifir arfleifð fjármálakreppunnar áfram í sjálfvirkum líkönum nútímans.

>

## Sérstök atriði

ARIMA líkön eru byggð á þeirri forsendu að fyrri gildi hafi einhver afgangsáhrif á núverandi eða framtíðargildi. Til dæmis myndi fjárfestir sem notar ARIMA líkan til að spá fyrir um hlutabréfaverð gera ráð fyrir að nýir kaupendur og seljendur þess hlutabréfs séu fyrir áhrifum af nýlegum markaðsviðskiptum þegar hann ákveður hversu mikið á að bjóða eða þiggja fyrir verðbréfið.

Þrátt fyrir að þessi forsenda standist undir mörgum kringumstæðum er þetta ekki alltaf raunin. Til dæmis, á árunum fyrir fjármálakreppuna 2008, voru flestir fjárfestar ekki meðvitaðir um áhættuna sem stafar af stórum eignasöfnum [veðtryggðra verðbréfa](/mbs) (MBS) í eigu margra fjármálafyrirtækja.

Á þeim tímum hefði fjárfestir sem notar sjálfvirkt líkan til að spá fyrir um frammistöðu bandarískra fjármálafyrirtækja haft góða ástæðu til að spá fyrir um áframhaldandi þróun stöðugs eða hækkandi hlutabréfaverðs í þeim geira. Hins vegar, þegar það varð almenningur vitað að margar fjármálastofnanir væru í hættu á yfirvofandi hruni, urðu fjárfestar skyndilega minni áhyggjufullir af nýlegu verði þessara hlutabréfa og mun meiri áhyggjur af undirliggjandi áhættuáhættu þeirra. Þess vegna er markaðurinn hratt endurmetinn fjármálahlutabréfum í mun lægra stig, hreyfing sem hefði algjörlega ruglað sjálfvirkt líkan.

## Algengar spurningar

### Til hvers er ARIMA notað?

ARIMA er aðferð til að spá fyrir um eða spá fyrir um framtíðarútkomu byggða á sögulegri tímaröð. Það er byggt á tölfræðilegu hugmyndinni um raðfylgni, þar sem fyrri gagnapunktar hafa áhrif á framtíðargagnapunkta.

### Hver er munurinn á sjálfvirkri líkönum og hreyfanlegu meðaltali?

ARIMA sameinar sjálfvirka eiginleika með hreyfanlegum meðaltölum. AR(1) sjálfvirkt ferli, til dæmis, er það þar sem núverandi gildi er byggt á gildinu á undan, en AR(2) ferli er ferli þar sem núverandi gildi er byggt á fyrri tveimur gildum. Hreyfanlegt meðaltal er útreikningur sem notaður er til að greina gagnapunkta með því að búa til röð meðaltala mismunandi undirmengi af heildar gagnamenginu til að jafna út áhrif útlægra. Sem afleiðing af þessari samsetningu aðferða geta ARIMA líkön tekið tillit til þróunar, lotu, árstíðarsveiflu og annarra gagna sem ekki eru kyrrstæður við spár.

### Hvernig virkar ARIMA spá?

ARIMA spá er náð með því að setja inn tímaraðagögn fyrir breytuna sem vekur áhuga. Tölfræðihugbúnaður mun bera kennsl á viðeigandi fjölda töfa eða magn mismuna sem á að nota á gögnin og athuga hvort kyrrstaða sé. Það mun síðan gefa út niðurstöðurnar, sem oft eru túlkaðar á svipaðan hátt og margfalds línulegs aðhvarfslíkans.

##Hápunktar

- Sjálfvirkt samþætt hreyfanleg meðaltal (ARIMA) líkön spá fyrir um framtíðargildi byggt á fyrri gildum.

- ARIMA notar seinkun hreyfanleg meðaltöl til að jafna tímaraðargögn.

- Þau eru mikið notuð í tæknigreiningu til að spá fyrir um verð á verðbréfum í framtíðinni.

- Sjálfvirk líkön gera óbeint ráð fyrir því að framtíðin muni líkjast fortíðinni.

- Þess vegna geta þær reynst ónákvæmar við ákveðnar markaðsaðstæður, eins og fjármálakreppur eða tímabil örra tæknibreytinga.

