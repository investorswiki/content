---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: Box-Jenkins módel
description: Box-Jenkins líkanið er stærðfræðilegt líkan hannað til að spá fyrir um gögn úr tiltekinni tímaröð.
---

# Box-Jenkins módel
## Hvað er Box-Jenkins fyrirmyndin?

Box-Jenkins líkanið er stærðfræðilegt líkan hannað til að spá fyrir um gagnasvið byggt á inntakum frá tiltekinni [tímaröð](/timeseries). Box-Jenkins líkanið getur greint nokkrar mismunandi gerðir af tímaraðargögnum í spáskyni.

Aðferðafræði þess notar mun á milli gagnapunkta til að ákvarða niðurstöður. Aðferðafræðin gerir líkaninu kleift að bera kennsl á þróun með því að nota sjálfvirka afturhvarf, hreyfanlegt meðaltal og árstíðabundinn mun til að búa til spár.

[Sjálfvirkt samþætt hreyfanleg meðaltal (ARIMA) líkön](/autoregressive-integrated-moving-average-arima) eru eins konar Box-Jenkins líkan. Hugtökin ARIMA og Box-Jenkins eru stundum notuð til skiptis.

## Að skilja Box-Jenkins líkanið

Box-Jenkins líkön eru notuð til að [spá](/forecasting) fyrir um margs konar væntanleg gagnapunkta eða gagnasvið, þar á meðal viðskiptagögn og framtíðaröryggisverð.

Box-Jenkins líkanið var búið til af tveimur stærðfræðingum: George Box og Gwilym Jenkins. Stærðfræðingarnir tveir ræddu hugtökin sem samanstanda af þessu líkani í 1970 útgáfu sem heitir "Time Series Analysis: Forecasting and Control."

Mat á breytum Box-Jenkins líkansins getur verið mjög flókið. Þess vegna, svipað og önnur tímaraðar aðhvarfslíkön, næst besti árangurinn venjulega með því að nota forritanlegan hugbúnað. Box-Jenkins líkanið hentar einnig almennt best fyrir skammtímaspár upp á 18 mánuði eða skemur.

##Box-Jenkins aðferðafræði

Box-Jenkins líkanið getur verið eitt af nokkrum tímaraðargreiningarlíkönum sem spámaður mun lenda í þegar hann notar forritaðan spáhugbúnað. Í mörgum tilfellum verður hugbúnaðurinn forritaður þannig að hann notar sjálfkrafa bestu spáaðferðina sem er byggð á þeim [tímaraðargögnum](/timeseries) sem spáð er fyrir um. Sagt er að Box-Jenkins sé besti kosturinn fyrir gagnasöfn sem eru að mestu leyti stöðug og hafa litla [sveiflu](/volatility).

Box-Jenkins líkanið spáir gögnum með því að nota þrjár meginreglur: sjálfvirka aðhvarf, mismun og hlaupandi meðaltal. Þessar þrjár meginreglur eru þekktar sem p, d og q, í sömu röð. hver meginregla er notuð í Box-Jenkins greiningu; saman eru þær sýndar sem ARIMA (p, d, q).

Sjálfvirk aðhvarfsferlið (p) prófar gögnin fyrir kyrrstöðustig þeirra. Ef gögnin sem notuð eru eru kyrrstæð getur það einfaldað spáferlið. Ef gögnin sem verið er að nota eru óstöðug þarf að skipta þeim á milli (d). Gögnin eru einnig prófuð með tilliti til hlaupandi meðaltals passa (sem er gert í hluta q greiningarferlisins). Á heildina litið undirbýr fyrstu greining gagna þau fyrir spá með því að ákvarða færibreyturnar (p, d og q), sem síðan er beitt til að þróa spá.

> Einu sinni áfall mun hafa áhrif á síðari gildi Box-Jenkins líkans óendanlega inn í framtíðina. Þess vegna lifir arfleifð fjármálakreppunnar áfram í sjálfvirkum líkönum nútímans.

>

## Autoregressive Integrated Moving Average (ARIMA)

Box-Jenkins er tegund af sjálfvirkt samþætt hreyfanleg meðaltal (ARIMA) líkan sem mælir styrk einnar háðrar breytu miðað við aðrar breytilegar breytur. Markmið líkansins er að spá fyrir um framtíðarhreyfingar verðbréfa eða fjármálamarkaða með því að skoða muninn á verðmætum í flokknum í stað raungilda.

Hægt er að skilja ARIMA líkan með því að útlista hvern hluta þess á eftirfarandi hátt:

- [Sjálfvirk aðhvarf (AR)](/autoregressive) : vísar til líkans sem sýnir breytta breytu sem dregur aftur úr eigin töfum, eða fyrri, gildum.

- Innbyggt (I): táknar mismun á hráum athugunum til að leyfa tímaröðinni að verða kyrrstæðar, þ.e. gagnagildum er skipt út fyrir mismuninn á gagnagildunum og fyrri gildum.

- [Hreyfanlegt meðaltal (MA)](/movingaverage) : felur í sér ósjálfstæði á milli athugunar og afgangsskekkju úr hreyfanlegu meðaltalslíkani sem notað er við tafir athuganir.

## Spá um hlutabréfaverð

Ein notkun fyrir Box-Jenkins Model greiningu er að spá fyrir um [hlutabréfaverð](/stock). Þessi greining er venjulega byggð upp og kóðað í gegnum R hugbúnað. Niðurstöðugreiningin í logaritmískri niðurstöðu, sem hægt er að nota á gagnasettið til að búa til spáð verð fyrir tiltekinn tíma í framtíðinni.

ARIMA líkön eru byggð á þeirri forsendu að fyrri gildi hafi einhver afgangsáhrif á núverandi eða framtíðargildi. Til dæmis myndi fjárfestir sem notar ARIMA líkan til að spá fyrir um hlutabréfaverð gera ráð fyrir að nýir kaupendur og seljendur þess hlutabréfs séu fyrir áhrifum af nýlegum markaðsviðskiptum þegar hann ákveður hversu mikið á að bjóða eða þiggja fyrir verðbréfið.

Þrátt fyrir að þessi forsenda muni gilda undir mörgum mismunandi kringumstæðum er hún ekki alltaf rétt. Til dæmis, á árunum fyrir fjármálakreppuna 2008, voru flestir fjárfestar ekki meðvitaðir um áhættuna sem stafar af stórum eignasöfnum [veðtryggðra verðbréfa](/mbs) (MBS) í eigu margra fjármálafyrirtækja.

Á þeim tímum hefði fjárfestir sem notar sjálfvirkt líkan til að spá fyrir um frammistöðu bandarískra fjármálafyrirtækja haft góða ástæðu til að spá fyrir um áframhaldandi þróun stöðugs eða hækkandi hlutabréfaverðs í þeim geira. Hins vegar, þegar það varð almenningur vitað að margar fjármálastofnanir væru í hættu á yfirvofandi hruni, urðu fjárfestar skyndilega minni áhyggjufullir af nýlegu verði þessara hlutabréfa og mun meiri áhyggjur af undirliggjandi áhættuáhættu þeirra.

Þess vegna er markaðurinn hratt endurmetinn fjármálahlutabréfum í mun lægra stig, hreyfing sem hefði algjörlega ruglað sjálfvirkt líkan.

##Hápunktar

- Sjálfvirkt samþætt hreyfanleg meðaltal (ARIMA) líkön eru eins konar Box-Jenkins líkan.

- Box-Jenkins líkanið hentar best til að spá innan 18 mánaða eða skemur tímaramma.

- Aðferðafræðin byggir á þeirri forsendu að fyrri atburðir hafi áhrif á framtíðina.

- Box-Jenkins líkanið er spáaðferðafræði sem notar aðhvarfsrannsóknir á tímaraðagögnum.

