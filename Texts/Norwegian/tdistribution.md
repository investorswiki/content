---
keywords: Trading,Technical Analysis
title: T Distribusjon
description: AT-fordeling er en type sannsynlighetsfunksjon som er passende for å estimere populasjonsparametere for små utvalgsstørrelser eller ukjente varianser.
---

# T Distribusjon
## Hva er en T-distribusjon?

T-fordelingen, også kjent som Studentens t-fordeling, er en type [sannsynlighetsfordeling](/probabilitydistribution) som ligner normalfordelingen med sin klokkeform, men har tyngre haler. T-fordelinger har større sjanse for ekstreme verdier enn normale fordelinger, derav de fetere halene.

## Hva forteller en T-distribusjon deg?

Haletyngden bestemmes av en parameter for T-fordelingen kalt [frihetsgrader](/degrees-of-freedom),. med mindre verdier som gir tyngre haler, og med høyere verdier som gjør at T-fordelingen minner om en standard normalfordeling med et gjennomsnitt på 0, og et standardavvik på 1. T-distribusjon er også kjent som "Students T-distribusjon."

<!--7D50237348822D30DFF69E0C32EC0A76-->

Når et utvalg av n observasjoner tas fra en normalfordelt populasjon med gjennomsnitt M og standardavvik D, vil utvalgets gjennomsnitt, m, og utvalgets standardavvik, d, avvike fra M og D på grunn av utvalgets tilfeldighet.

En z-score kan beregnes med populasjonsstandardavviket som Z = (x – M)/D, og denne verdien har normalfordelingen med gjennomsnitt 0 og standardavvik 1. Men ved bruk av estimert standardavvik, en t-score beregnes som T = (m – M)/{d/sqrt(n)}, gjør forskjellen mellom d og D fordelingen til en T-fordeling med (n - 1) frihetsgrader i stedet for normalfordelingen med gjennomsnitt 0 og standardavvik 1.

## Eksempel på hvordan man bruker en T-distribusjon

Ta følgende eksempel for hvordan t-fordelinger brukes i statistisk analyse. Først, husk at et konfidensintervall for gjennomsnittet er et verdiområde, beregnet fra dataene, ment å fange et "populasjonsmiddel". Dette intervallet er m +- t*d/sqrt(n), der t er en kritisk verdi fra T-fordelingen.

For eksempel er et 95 % konfidensintervall for gjennomsnittlig avkastning til Dow Jones Industrial Average i de 27 handelsdagene før 9/11/2001 -0,33 %, (+/- 2,055) * 1,07 / sqrt(27), gir en (vedvarende) gjennomsnittlig avkastning som et tall mellom -0,75 % og +0,09 %. Tallet 2.055, mengden standardfeil å justere etter, er funnet fra T-fordelingen.

Fordi T-fordelingen har fetere haler enn en normalfordeling, kan den brukes som en modell for økonomisk avkastning som viser overskytende kurtose, noe som vil gi mulighet for en mer realistisk beregning av Value at Risk ( [VaR](/var) ) i slike tilfeller.

## Forskjellen mellom en T-distribusjon og en normalfordeling

Normalfordelinger brukes når befolkningsfordelingen antas å være normal. T-fordelingen er lik normalfordelingen, bare med fetere haler. Begge forutsetter en normalfordelt befolkning. T-fordelinger har høyere kurtose enn normalfordelinger. Sannsynligheten for å få verdier veldig langt fra gjennomsnittet er større med en T-fordeling enn en normalfordeling.

## Begrensninger ved bruk av en T-distribusjon

T-fordelingen kan skjeve nøyaktigheten i forhold til normalfordelingen. Dens mangel oppstår bare når det er behov for perfekt normalitet. T-fordelingen skal kun brukes når populasjonsstandardavviket ikke er kjent. Hvis populasjonsstandardavviket er kjent og utvalgsstørrelsen er stor nok, bør normalfordelingen brukes for bedre resultater.

## Høydepunkter

- T-fordelingen er en kontinuerlig sannsynlighetsfordeling av z-skåren når det estimerte standardavviket brukes i nevneren i stedet for det sanne standardavviket.

– T-fordelingen er, i likhet med normalfordelingen, klokkeformet og symmetrisk, men den har tyngre haler, noe som betyr at den har en tendens til å produsere verdier som faller langt fra gjennomsnittet.

– T-tester brukes i statistikk for å estimere signifikans.

