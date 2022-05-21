---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: Box-Jenkins modell
description: Box-Jenkins-modellen er en matematisk modell designet for å forutsi data fra en spesifisert tidsserie.
---

# Box-Jenkins modell
## Hva er Box-Jenkins-modellen?

Box-Jenkins-modellen er en matematisk modell designet for å forutsi dataområder basert på inndata fra en spesifisert [tidsserie](/timeseries). Box-Jenkins-modellen kan analysere flere forskjellige typer tidsseriedata for prognoseformål.

Metodikken bruker forskjeller mellom datapunkter for å bestemme utfall. Metodikken lar modellen identifisere trender ved å bruke autoregresjon, glidende gjennomsnitt og sesongforskjeller for å generere prognoser.

[Autoregressive integrerte glidende gjennomsnitt (ARIMA) modeller](/autoregressive-integrated-moving-average-arima) er en form for Box-Jenkins modell. Begrepene ARIMA og Box-Jenkins brukes noen ganger om hverandre.

## Forstå Box-Jenkins-modellen

Box-Jenkins-modeller brukes til å [forutsi](/forecasting) en rekke forventede datapunkter eller dataområder, inkludert forretningsdata og fremtidige sikkerhetspriser.

Box-Jenkins-modellen ble skapt av to matematikere: George Box og Gwilym Jenkins. De to matematikerne diskuterte konseptene som utgjør denne modellen i en publikasjon fra 1970 kalt "Time Series Analysis: Forecasting and Control."

Estimater av parametrene til Box-Jenkins-modellen kan være svært kompliserte. Derfor, i likhet med andre tidsserieregresjonsmodeller, vil de beste resultatene vanligvis oppnås ved bruk av programmerbar programvare. Box-Jenkins-modellen er også generelt best egnet for kortsiktige prognoser på 18 måneder eller mindre.

##Box-Jenkins metodikk

Box-Jenkins-modellen kan være en av flere tidsserieanalysemodeller en prognosemaker vil møte ved bruk av programmert prognoseprogramvare. I mange tilfeller vil programvaren bli programmert til automatisk å bruke den best passende prognosemetoden basert på [tidsseriedataene](/timeseries) som skal prognoseres. Box-Jenkins er rapportert å være et toppvalg for datasett som stort sett er stabile og har lav [volatilitet](/volatility).

Box-Jenkins-modellen prognoser data ved hjelp av tre prinsipper: autoregresjon, differensiering og glidende gjennomsnitt. Disse tre prinsippene er kjent som henholdsvis p, d og q. hvert prinsipp brukes i Box-Jenkins-analysen; sammen vises de samlet som ARIMA (p, d, q).

Autoregresjonsprosessen (p) tester dataene for stasjonaritetsnivået. Hvis dataene som brukes er stasjonære, kan det forenkle prognoseprosessen. Hvis dataene som brukes er ikke-stasjonære, må de differensieres (d). Dataene testes også for glidende gjennomsnittlig tilpasning (som gjøres i del q av analyseprosessen). Totalt sett forbereder innledende analyse av dataene dem for prognoser ved å bestemme parametrene (p, d og q), som deretter brukes for å utvikle en prognose.

> Et engangssjokk vil påvirke påfølgende verdier av en Box-Jenkins-modell uendelig inn i fremtiden. Derfor lever arven fra finanskrisen videre i dagens autoregressive modeller.

>

## Autoregressivt integrert glidende gjennomsnitt (ARIMA)

Box-Jenkins er en type autoregressiv integrert glidende gjennomsnitt (ARIMA) modell som måler styrken til en avhengig variabel i forhold til andre skiftende variabler. Modellens mål er å forutsi fremtidige verdipapir- eller finansmarkedsbevegelser ved å undersøke forskjellene mellom verdier i serien i stedet for gjennom faktiske verdier.

En ARIMA-modell kan forstås ved å skissere hver av komponentene som følger:

- [Autoregresjon (AR)](/autoregressive) : refererer til en modell som viser en skiftende variabel som regresserer på sine egne forsinket eller tidligere verdier.

- Integrert (I): representerer forskjellen mellom råobservasjoner for å tillate at tidsserien blir stasjonær, dvs. dataverdier erstattes av forskjellen mellom dataverdiene og de tidligere verdiene.

- [Glidende gjennomsnitt (MA)](/movingaverage) : inkorporerer avhengigheten mellom en observasjon og en gjenværende feil fra en glidende gjennomsnittsmodell brukt på forsinkede observasjoner.

## Prognose aksjekurser

En bruk for Box-Jenkins modellanalyse er å forutsi [aksjekurser](/stock). Denne analysen bygges vanligvis ut og kodes gjennom R-programvare. Resultatanalysen i et logaritmisk utfall, som kan brukes på datasettet for å generere de anslåtte prisene for en spesifisert tidsperiode i fremtiden.

ARIMA-modeller er basert på antakelsen om at tidligere verdier har en viss gjenværende effekt på nåværende eller fremtidige verdier. For eksempel vil en investor som bruker en ARIMA-modell for å forutsi aksjekurser anta at nye kjøpere og selgere av den aksjen er påvirket av nylige markedstransaksjoner når de bestemmer seg for hvor mye de skal tilby eller akseptere for verdipapiret.

Selv om denne antakelsen vil gjelde under mange forskjellige omstendigheter, er den ikke alltid sann. For eksempel, i årene før finanskrisen i 2008, var de fleste investorer ikke klar over risikoen som utgjøres av de store porteføljene av [pantesikrede verdipapirer](/mbs) (MBS) holdt av mange finansforetak.

I disse tider ville en investor som bruker en autoregressiv modell for å forutsi utviklingen til amerikanske finansaksjer ha hatt god grunn til å forutsi en pågående trend med stabile eller stigende aksjekurser i den sektoren. Men så snart det ble offentlig kjent at mange finansinstitusjoner var i fare for snarlig kollaps, ble investorene plutselig mindre opptatt av disse aksjenes siste kurs og langt mer opptatt av deres underliggende risikoeksponering.

Derfor revalueres markedet raskt finansielle aksjer til et mye lavere nivå, et trekk som ville ha fullstendig forvirret en autoregressiv modell.

##Høydepunkter

- Autoregressive integrerte glidende gjennomsnitt (ARIMA) modeller er en form for Box-Jenkins modell.

- Box-Jenkins-modellen er best egnet for prognoser innenfor tidsrammer på 18 måneder eller mindre.

– Metodikken er basert på antakelsen om at tidligere hendelser påvirker fremtidige.

– Box-Jenkins-modellen er en prognosemetodikk som bruker regresjonsstudier på tidsseriedata.

