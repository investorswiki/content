---
keywords: Business,Corporate Finance and Accounting,Financial Analysis
title: Överanpassning
description: Överanpassning är ett modelleringsfel som uppstår när en funktion är för nära anpassad till en begränsad uppsättning datapunkter.
---

# Överanpassning
## Vad är övermontering?

Överanpassning är ett modelleringsfel i statistik som uppstår när en funktion är för nära inriktad med en begränsad uppsättning datapunkter. Som ett resultat är modellen användbar endast med avseende på dess initiala datamängd och inte till några andra datamängder.

Att överanpassa modellen tar i allmänhet formen av att man gör en alltför komplex modell för att förklara egenheter i de data som studeras. I verkligheten har data som studeras ofta en viss grad av fel eller slumpmässigt brus i sig. Således kan ett försök att få modellen att överensstämma för nära till något felaktiga data infektera modellen med väsentliga fel och minska dess prediktiva kraft.

## Förstå övermontering

Ett vanligt problem är till exempel att använda datoralgoritmer [för](/algorithm) att söka i omfattande databaser med historiska marknadsdata för att hitta mönster. Givet tillräckligt med studier är det ofta möjligt att utveckla utarbetade satser som verkar förutsäga avkastningen på [aktiemarknaden](/stockmarket) med stor noggrannhet.

Men när de tillämpas på data utanför urvalet, kan sådana satser sannolikt visa sig vara enbart överanpassning av en modell till vad som i verkligheten var bara slumpmässiga händelser. I alla fall är det viktigt att testa en modell mot data som ligger utanför det urval som används för att utveckla den.

## Hur man förhindrar övermontering

Sätt att förhindra överanpassning inkluderar korsvalidering, där data som används för att träna modellen kapas i veck eller partitioner och modellen körs för varje veck. Sedan beräknas ett medelvärde för den totala feluppskattningen. Andra metoder inkluderar ensembling: förutsägelser kombineras från minst två separata modeller, dataförstärkning, där den tillgängliga datamängden görs för att se mångsidig ut, och dataförenkling, där modellen strömlinjeformas för att undvika överanpassning.

> Finansiella proffs måste alltid vara medvetna om farorna med att över- eller undermontera en modell baserad på begränsad data. Den ideala modellen bör vara balanserad.

>

## Överanpassning i maskininlärning

Överanpassning är också en faktor i maskininlärning. Det kan uppstå när en maskin har lärt sig att skanna efter specifik data på ett sätt, men när samma process tillämpas på en ny uppsättning data är resultaten felaktiga. Detta beror på fel i modellen som byggdes, eftersom den sannolikt visar låg bias och hög varians. Modellen kan ha haft redundanta eller överlappande funktioner, vilket resulterade i att den blev onödigt komplicerad och därför ineffektiv.

## Övermontering vs. undermontering

En modell som är övermonterad kan vara för komplicerad, vilket gör den ineffektiv. Men en modell kan också vara undermonterad, vilket innebär att den är för enkel, med för få funktioner och för lite data för att bygga en effektiv modell. En overfit-modell har låg bias och hög varians, medan en underfit-modell är motsatsen – den har hög bias och låg varians. Att lägga till fler funktioner i en för enkel modell kan hjälpa till att begränsa fördomar.

## Övermonteringsexempel

Till exempel bestämmer ett universitet som ser ett avhopp från högskolor som är högre än vad det skulle vilja att det vill skapa en modell för att förutsäga sannolikheten att en sökande kommer att ta sig hela vägen fram till examen.

För att göra detta tränar universitetet en modell från ett dataset med 5 000 sökande och deras resultat. Den kör sedan modellen på den ursprungliga datamängden – gruppen på 5 000 sökande – och modellen förutsäger resultatet med 98 % noggrannhet. Men för att testa dess noggrannhet kör de också modellen på en andra datamängd – 5 000 fler sökande. Men den här gången är modellen bara 50 % korrekt, eftersom modellen var för nära anpassad till en smal dataundergrupp, i det här fallet de första 5 000 ansökningarna.

## Höjdpunkter

- Överanpassning är ett fel som uppstår i datamodellering som ett resultat av att en viss funktion är för nära en minimal uppsättning datapunkter.

– När en modell har äventyrats av överutrustning kan modellen förlora sitt värde som ett prediktivt verktyg för att investera.

– En datamodell kan också vara undermonterad, vilket innebär att den är för enkel, med för få datapunkter för att vara effektiv.

– Finansiella proffs riskerar att överanpassa en modell som bygger på begränsad data och att få resultat som är felaktiga.

– Överanpassning är ett vanligare problem än underpassning och uppstår vanligtvis som ett resultat av att man försöker undvika överanpassning.

