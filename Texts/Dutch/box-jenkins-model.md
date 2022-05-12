---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: Box-Jenkins model
description: Box-Jenkins-modellen er en matematisk model designet til at forudsige data fra en specificeret tidsserie.
---

# Box-Jenkins model
## Hvad er Box-Jenkins-modellen?

Box-Jenkins-modellen er en matematisk model designet til at forudsige dataområder baseret på input fra en specificeret [tidsserie](/timeseries). Box-Jenkins modellen kan analysere flere forskellige typer tidsseriedata til prognoseformål.

Dens metodologi bruger forskelle mellem datapunkter til at bestemme resultater. Metoden gør det muligt for modellen at identificere tendenser ved hjælp af autoregression, glidende gennemsnit og sæsonbestemte forskelle til at generere prognoser.

[Autoregressivt integreret glidende gennemsnit (ARIMA) modeller](/autoregressive-integrated-moving-average-arima) er en form for Box-Jenkins model. Begreberne ARIMA og Box-Jenkins bruges nogle gange i flæng.

## Forstå Box-Jenkins-modellen

Box-Jenkins-modeller bruges til at [forudsige](/forecasting) en række forventede datapunkter eller dataområder, herunder forretningsdata og fremtidige sikkerhedspriser.

Box-Jenkins-modellen blev skabt af to matematikere: George Box og Gwilym Jenkins. De to matematikere diskuterede de begreber, der udgør denne model, i en publikation fra 1970 kaldet "Time Series Analysis: Forecasting and Control."

Estimater af parametrene for Box-Jenkins modellen kan være meget komplicerede. Derfor vil de bedste resultater, i lighed med andre tidsserieregressionsmodeller, typisk opnås ved brug af programmerbar software. Box-Jenkins-modellen er også generelt bedst egnet til kortsigtede prognoser på 18 måneder eller mindre.

##Box-Jenkins metode

Box-Jenkins-modellen kan være en af flere tidsserieanalysemodeller, som en prognosemager vil støde på, når de bruger programmeret prognosesoftware. I mange tilfælde vil softwaren blive programmeret til automatisk at bruge den bedst passende prognosemetode baseret på de [tidsseriedata](/timeseries),. der skal prognoses. Box-Jenkins rapporteres at være et topvalg for datasæt, der for det meste er stabile og har lav [volatilitet](/volatility).

Box-Jenkins-modellen forudsiger data ved hjælp af tre principper: autoregression, differentiering og glidende gennemsnit. Disse tre principper er kendt som henholdsvis p, d og q. hvert princip bruges i Box-Jenkins analysen; tilsammen vises de samlet som ARIMA (p, d, q).

Autoregression (p) processen tester dataene for deres stationaritetsniveau. Hvis de anvendte data er stationære, kan det forenkle prognoseprocessen. Hvis de anvendte data er ikke-stationære, skal de differentieres (d). Dataene testes også for deres glidende gennemsnitstilpasning (hvilket udføres i del q af analyseprocessen). Generelt forbereder den indledende analyse af dataene dem til prognose ved at bestemme parametrene (p, d og q), som derefter anvendes til at udvikle en prognose.

> Et engangschok vil påvirke efterfølgende værdier af en Box-Jenkins-model uendeligt ud i fremtiden. Derfor lever arven fra finanskrisen videre i nutidens autoregressive modeller.

>

## Autoregressive Integrated Moving Average (ARIMA)

Box-Jenkins er en type autoregressiv integreret glidende gennemsnit (ARIMA) model, der måler styrken af en afhængig variabel i forhold til andre skiftende variable. Modellens mål er at forudsige fremtidige værdipapirer eller finansielle markedsbevægelser ved at undersøge forskellene mellem værdier i serien i stedet for gennem faktiske værdier.

En ARIMA-model kan forstås ved at skitsere hver af dens komponenter som følger:

- [Autoregression (AR)](/autoregressive) : refererer til en model, der viser en skiftende variabel, der regresserer på sine egne forsinkede eller tidligere værdier.

- Integreret (I): repræsenterer forskellen mellem rå observationer for at tillade tidsserien at blive stationær, dvs. dataværdier erstattes af forskellen mellem dataværdierne og de tidligere værdier.

- [Glidende gennemsnit (MA)](/movingaverage) : inkorporerer afhængigheden mellem en observation og en resterende fejl fra en glidende gennemsnitsmodel anvendt på forsinkede observationer.

## Forecasting af aktiekurser

En anvendelse af Box-Jenkins modelanalyse er at forudsige [aktiekurser](/stock). Denne analyse er typisk bygget ud og kodet gennem R-software. Resultatanalysen i et logaritmisk udfald, som kan anvendes på datasættet for at generere de forventede priser for en bestemt periode i fremtiden.

ARIMA-modeller er baseret på den antagelse, at tidligere værdier har en resteffekt på nuværende eller fremtidige værdier. For eksempel vil en investor, der bruger en ARIMA-model til at forudsige aktiekurser, antage, at nye købere og sælgere af denne aktie er påvirket af de seneste markedstransaktioner, når de beslutter, hvor meget der skal tilbydes eller accepteres for værdipapiret.

Selvom denne antagelse vil holde under mange forskellige omstændigheder, er den ikke altid sand. For eksempel var de fleste investorer i årene forud for finanskrisen i 2008 ikke klar over de risici, som de store porteføljer af [pantesikrede værdipapirer](/mbs) (MBS) indehaves af mange finansielle virksomheder.

I disse tider ville en investor, der brugte en autoregressiv model til at forudsige resultaterne af amerikanske finansielle aktier, have haft god grund til at forudsige en vedvarende trend med stabile eller stigende aktiekurser i den pågældende sektor. Men da det blev offentligt kendt, at mange finansielle institutioner var i risiko for forestående kollaps, blev investorerne pludselig mindre bekymrede over disse aktiers seneste kurser og langt mere bekymrede over deres underliggende risikoeksponering.

Derfor omvurderes markedet hurtigt finansielle aktier til et meget lavere niveau, et skridt, der ville have fuldstændig forvirret en autoregressiv model.

##Højdepunkter

- Autoregressive, integrerede glidende gennemsnit (ARIMA) modeller er en form for Box-Jenkins model.

- Box-Jenkins-modellen er bedst egnet til prognoser inden for tidsrammer på 18 måneder eller mindre.

- Metoden er baseret på den antagelse, at tidligere hændelser påvirker fremtidige.

- Box-Jenkins-modellen er en prognosemetode, der bruger regressionsstudier på tidsseriedata.

