---
keywords: Business,Corporate Finance and Accounting,Financial Analysis
title: Overmontering
description: Overtilpasning er en modelleringsfeil som oppstår når en funksjon er for tett tilpasset et begrenset sett med datapunkter.
---

# Overmontering
## Hva er overfitting?

Overtilpasning er en modelleringsfeil i statistikk som oppstår når en funksjon er for nært justert til et begrenset sett med datapunkter. Som et resultat er modellen nyttig kun med referanse til dets opprinnelige datasett, og ikke til andre datasett.

Overfitting av modellen tar vanligvis form av å lage en altfor kompleks modell for å forklare særegenheter i dataene som studeres. I virkeligheten har dataene som ofte er studert en viss grad av feil eller tilfeldig støy i seg. Dermed kan forsøk på å få modellen til å samsvare for nært til litt unøyaktige data infisere modellen med betydelige feil og redusere dens prediksjonskraft.

## Forstå overfitting

Et vanlig problem er for eksempel å bruke datamaskinalgoritmer [til](/algorithm) å søke i omfattende databaser med historiske markedsdata for å finne mønstre. Gitt nok studier, er det ofte mulig å utvikle forseggjorte teoremer som ser ut til å forutsi avkastning i [aksjemarkedet](/stockmarket) med stor nøyaktighet.

Men når de brukes på data utenfor utvalget, kan slike teoremer sannsynligvis vise seg å være bare overtilpasning av en modell til det som i virkeligheten var tilfeldige hendelser. I alle tilfeller er det viktig å teste en modell mot data som er utenfor utvalget som ble brukt til å utvikle den.

## Hvordan forhindre overtilpasning

Måter å forhindre overtilpasning inkluderer kryssvalidering, der dataene som brukes til trening av modellen kuttes i folder eller partisjoner og modellen kjøres for hver fold. Deretter beregnes gjennomsnittet av det totale feilestimatet. Andre metoder inkluderer ensembling: spådommer kombineres fra minst to separate modeller, dataforsterkning, der det tilgjengelige datasettet er laget for å se mangfoldig ut, og dataforenkling, der modellen er strømlinjeformet for å unngå overtilpasning.

> Finansielle fagfolk må alltid være klar over farene ved å over- eller undertilpasse en modell basert på begrensede data. Den ideelle modellen bør være balansert.

>

## Overfitting i maskinlæring

Overtilpasning er også en faktor i maskinlæring. Det kan dukke opp når en maskin har blitt lært opp til å skanne etter spesifikke data én vei, men når den samme prosessen brukes på et nytt sett med data, er resultatene feil. Dette er på grunn av feil i modellen som ble bygget, da den sannsynligvis viser lav skjevhet og høy varians. Modellen kan ha hatt overflødige eller overlappende funksjoner, noe som resulterte i at den ble unødvendig komplisert og derfor ineffektiv.

## Overfitting vs. Undertilpasning

En modell som er overmontert kan være for komplisert, noe som gjør den ineffektiv. Men en modell kan også være undermontert, noe som betyr at den er for enkel, med for få funksjoner og for lite data til å bygge en effektiv modell. En overfit-modell har lav skjevhet og høy varians, mens en underfit-modell er det motsatte - den har høy bias og lav varians. Å legge til flere funksjoner i en for enkel modell kan bidra til å begrense skjevhet.

## Eksempel på overmontering

For eksempel, et universitet som ser en frafallsrate på høyskoler som er høyere enn det det ønsker, bestemmer seg for å lage en modell for å forutsi sannsynligheten for at en søker vil klare seg hele veien frem til eksamen.

For å gjøre dette trener universitetet en modell fra et datasett med 5000 søkere og deres utfall. Den kjører deretter modellen på det originale datasettet – gruppen på 5000 søkere – og modellen forutsier resultatet med 98 % nøyaktighet. Men for å teste nøyaktigheten, kjører de også modellen på et andre datasett – 5000 flere søkere. Denne gangen er modellen imidlertid bare 50 % nøyaktig, siden modellen var for tett tilpasset et smalt dataundersett, i dette tilfellet de første 5000 applikasjonene.

##Høydepunkter

- Overtilpasning er en feil som oppstår i datamodellering som et resultat av at en bestemt funksjon er for tett på linje med et minimalt sett med datapunkter.

– Når en modell har blitt kompromittert av overfitting, kan modellen miste sin verdi som et prediktivt verktøy for å investere.

– En datamodell kan også være undermontert, noe som betyr at den er for enkel, med for få datapunkter til å være effektiv.

– Finansfolk står i fare for å overfitte en modell basert på begrensede data og ende opp med resultater som er mangelfulle.

- Overtilpasning er et hyppigere problem enn undertilpasning og oppstår typisk som et resultat av forsøk på å unngå overtilpasning.

