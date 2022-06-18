---
keywords: Trading,Technical Analysis
title: T Distribution
description: AT-fordeling er en type sandsynlighedsfunktion, der er passende til at estimere populationsparametre for små stikprøvestørrelser eller ukendte varianser.
---

# T Distribution
## Hvad er en T-distribution?

T-fordelingen, også kendt som Elevens t-fordeling, er en form for [sandsynlighedsfordeling](/probabilitydistribution),. der ligner normalfordelingen med sin klokkeform, men har tungere haler. T-fordelinger har større chance for ekstreme værdier end normale fordelinger, derfor de federe haler.

## Hvad fortæller en T-distribution dig?

Halevægten bestemmes af en parameter for T-fordelingen kaldet [frihedsgrader](/degrees-of-freedom),. hvor mindre værdier giver tungere haler, og med højere værdier får T-fordelingen til at ligne en standardnormalfordeling med et gennemsnit på 0 og en standardafvigelse på 1. T distribution er også kendt som "Student's T Distribution."

<!--7D50237348822D30DFF69E0C32EC0A76-->

Når en stikprøve på n observationer tages fra en normalfordelt population med middelværdi M og standardafvigelse D, vil prøvegennemsnittet, m, og prøvens standardafvigelse, d, afvige fra M og D på grund af stikprøvens tilfældighed.

En z-score kan beregnes med populationens standardafvigelse som Z = (x – M)/D, og denne værdi har normalfordelingen med middelværdi 0 og standardafvigelse 1. Men når man bruger den estimerede standardafvigelse, er en t-score beregnes som T = (m – M)/{d/sqrt(n)}, gør forskellen mellem d og D fordelingen til en T-fordeling med (n - 1) frihedsgrader frem for normalfordelingen med middelværdi 0 og standardafvigelse 1.

## Eksempel på hvordan man bruger en T-distribution

Tag følgende eksempel for, hvordan t-fordelinger bruges i statistisk analyse. Først skal du huske, at et konfidensinterval for middelværdien er et interval af værdier, beregnet ud fra dataene, beregnet til at fange en "populations"-middelværdi. Dette interval er m +- t*d/sqrt(n), hvor t er en kritisk værdi fra T-fordelingen.

For eksempel er et 95 % konfidensinterval for det gennemsnitlige afkast af Dow Jones Industrial Average i de 27 handelsdage før 9/11/2001 -0,33 %, (+/- 2,055) * 1,07 / sqrt(27), giver et (vedvarende) gennemsnitligt afkast som et tal mellem -0,75% og +0,09%. Tallet 2.055, mængden af standardfejl at justere efter, findes fra T-fordelingen.

Fordi T-fordelingen har federe haler end en normalfordeling, kan den bruges som en model for finansielle afkast, der udviser overskydende kurtosis, hvilket vil give mulighed for en mere realistisk beregning af Value at Risk ( [VaR](/var) ) i sådanne tilfælde.

## Forskellen mellem en T-fordeling og en normalfordeling

Normalfordelinger anvendes, når befolkningsfordelingen antages at være normal. T-fordelingen svarer til normalfordelingen, blot med federe haler. Begge antager en normalfordelt befolkning. T-fordelinger har højere kurtosis end normale fordelinger. Sandsynligheden for at få værdier meget langt fra middelværdien er større med en T-fordeling end en normalfordeling.

## Begrænsninger ved brug af en T-distribution

T-fordelingen kan skæve nøjagtigheden i forhold til normalfordelingen. Dens mangel opstår kun, når der er behov for perfekt normalitet. T-fordelingen bør kun anvendes, når populationens standardafvigelse ikke er kendt. Hvis populationens standardafvigelse er kendt, og stikprøvestørrelsen er stor nok, bør normalfordelingen bruges til bedre resultater.

## Højdepunkter

- T-fordelingen er en kontinuerlig sandsynlighedsfordeling af z-score, når den estimerede standardafvigelse bruges i nævneren frem for den sande standardafvigelse.

- T-fordelingen er ligesom normalfordelingen klokkeformet og symmetrisk, men den har tungere haler, hvilket betyder, at den har en tendens til at producere værdier, der falder langt fra dens middelværdi.

- T-test bruges i statistik til at estimere signifikans.

