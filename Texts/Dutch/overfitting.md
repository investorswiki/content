---
keywords: Business,Corporate Finance and Accounting,Financial Analysis
title: Overfitting
description: Overfitting er en modelleringsfejl, der opstår, når en funktion passer for tæt til et begrænset sæt datapunkter.
---

# Overfitting
## Hvad er overfitting?

Overtilpasning er en modelleringsfejl i statistik, der opstår, når en funktion er for tæt på linje med et begrænset sæt datapunkter. Som et resultat heraf er modellen kun nyttig med henvisning til dets oprindelige datasæt og ikke til andre datasæt.

Overtilpasning af modellen tager generelt form af at lave en alt for kompleks model til at forklare særheder i de undersøgte data. I virkeligheden har de undersøgte data ofte en vis grad af fejl eller tilfældig støj i sig. Forsøg på at få modellen til at passe for tæt til lidt unøjagtige data kan derfor inficere modellen med væsentlige fejl og reducere dens forudsigelsesevne.

## Forståelse af overfitting

For eksempel er et almindeligt problem at bruge computeralgoritmer [til](/algorithm) at søge i omfattende databaser med historiske markedsdata for at finde mønstre. Givet tilstrækkelige undersøgelser, er det ofte muligt at udvikle komplicerede teoremer, der ser ud til at forudsige afkast på [aktiemarkedet](/stockmarket) med tæt nøjagtighed.

Men når de anvendes på data uden for stikprøven, kan sådanne teoremer sandsynligvis vise sig blot at være overtilpasning af en model til, hvad der i virkeligheden kun var tilfældige hændelser. I alle tilfælde er det vigtigt at teste en model mod data, der er uden for den prøve, der er brugt til at udvikle den.

## Sådan forhindrer du overpasning

Måder at forhindre overfitting på omfatter krydsvalidering, hvor de data, der bruges til træning af modellen, hugges i folder eller skillevægge, og modellen køres for hver fold. Derefter beregnes gennemsnittet af det samlede fejlestimat. Andre metoder omfatter ensembling: forudsigelser kombineres fra mindst to separate modeller, dataforøgelse, hvor det tilgængelige datasæt er lavet til at se forskelligt ud, og dataforenkling, hvor modellen er strømlinet for at undgå overfitting.

> Finansielle fagfolk skal altid være opmærksomme på farerne ved at over- eller undermontere en model baseret på begrænsede data. Den ideelle model skal være afbalanceret.

>

## Overfitting i Machine Learning

Overfitting er også en faktor i maskinlæring. Det kan opstå, når en maskine er blevet lært at scanne efter specifikke data på én måde, men når den samme proces anvendes på et nyt sæt data, er resultaterne forkerte. Dette er på grund af fejl i den model, der blev bygget, da den sandsynligvis viser lav bias og høj varians. Modellen kan have haft overflødige eller overlappende funktioner, hvilket resulterer i, at den er blevet unødvendigt kompliceret og derfor ineffektiv.

## Overfitting vs. Underfitting

En model, der er overmonteret, kan være for kompliceret, hvilket gør den ineffektiv. Men en model kan også være undermonteret, hvilket betyder, at den er for enkel, med for få funktioner og for lidt data til at bygge en effektiv model. En overfit-model har lav bias og høj varians, mens en underfit-model er det modsatte - den har høj bias og lav varians. Tilføjelse af flere funktioner til en for simpel model kan hjælpe med at begrænse skævhed.

## Eksempel på overfitting

For eksempel beslutter et universitet, der oplever en frafaldsprocent, der er højere end det, det gerne vil have, at skabe en model til at forudsige sandsynligheden for, at en ansøger vil klare sig hele vejen frem til eksamen.

For at gøre dette træner universitetet en model fra et datasæt med 5.000 ansøgere og deres resultater. Den kører derefter modellen på det originale datasæt – gruppen på 5.000 ansøgere – og modellen forudsiger resultatet med 98 % nøjagtighed. Men for at teste dens nøjagtighed kører de også modellen på et andet datasæt - 5.000 flere ansøgere. Denne gang er modellen dog kun 50 % nøjagtig, da modellen var for tæt tilpasset et snævert dataundersæt, i dette tilfælde de første 5.000 applikationer.

## Højdepunkter

- Overfitting er en fejl, der opstår i datamodellering som et resultat af, at en bestemt funktion er for tæt på et minimalt sæt af datapunkter.

- Når en model er blevet kompromitteret af overfitting, kan modellen miste sin værdi som et forudsigelsesværktøj til at investere.

- En datamodel kan også være undermonteret, hvilket betyder, at den er for enkel med for få datapunkter til at være effektiv.

- Finansielle fagfolk risikerer at overfitte en model baseret på begrænsede data og ende med resultater, der er mangelfulde.

- Overfitting er et hyppigere problem end underfitting og opstår typisk som følge af forsøg på at undgå overfitting.

