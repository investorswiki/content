---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: Box-Jenkins modell
description: Box-Jenkins-modellen är en matematisk modell utformad för att prognostisera data från en specificerad tidsserie.
---

# Box-Jenkins modell
## Vad är Box-Jenkins-modellen?

Box-Jenkins-modellen är en matematisk modell utformad för att förutsäga dataintervall baserat på indata från en specificerad [tidsserie](/timeseries). Box-Jenkins-modellen kan analysera flera olika typer av tidsseriedata för prognosändamål.

Dess metodik använder skillnader mellan datapunkter för att bestämma utfall. Metoden gör det möjligt för modellen att identifiera trender med hjälp av autoregression, glidande medelvärden och säsongsmässiga skillnader för att generera prognoser.

[Autoregressivt integrerat glidande medelvärde (ARIMA) modeller](/autoregressive-integrated-moving-average-arima) är en form av Box-Jenkins modell. Termerna ARIMA och Box-Jenkins används ibland omväxlande.

## Förstå Box-Jenkins-modellen

Box-Jenkins-modeller används för att [prognostisera](/forecasting) en mängd förväntade datapunkter eller dataintervall, inklusive affärsdata och framtida säkerhetspriser.

Box-Jenkins-modellen skapades av två matematiker: George Box och Gwilym Jenkins. De två matematikerna diskuterade begreppen som utgör denna modell i en publikation från 1970 som heter "Time Series Analysis: Forecasting and Control."

Uppskattningar av parametrarna för Box-Jenkins-modellen kan vara mycket komplicerade. Därför, i likhet med andra tidsserieregressionsmodeller, kommer de bästa resultaten vanligtvis att uppnås genom användning av programmerbar programvara. Box-Jenkins-modellen är också generellt sett bäst lämpad för kortsiktiga prognoser på 18 månader eller mindre.

##Box-Jenkins metodik

Box-Jenkins-modellen kan vara en av flera tidsserieanalysmodeller som en prognosmakare kommer att stöta på när de använder programmerad prognosmjukvara. I många fall kommer programvaran att programmeras för att automatiskt använda den bästa prognosmetoden baserat på [tidsseriedata](/timeseries) som ska prognostiseras. Box-Jenkins rapporteras vara ett toppval för datamängder som mestadels är stabila och har låg [volatilitet](/volatility).

Box-Jenkins-modellen förutser data utifrån tre principer: autoregression, differens och glidande medelvärde. Dessa tre principer är kända som p, d respektive q. varje princip används i Box-Jenkins analys; tillsammans visas de tillsammans som ARIMA (p, d, q).

Autoregression (p)-processen testar data för dess stationaritetsnivå. Om data som används är stationära kan det förenkla prognosprocessen. Om den data som används är icke-stationär måste den göras skillnad (d). Data testas också för dess glidande medelvärde (vilket görs i del q av analysprocessen). Sammantaget förbereder den initiala analysen av data den för prognos genom att bestämma parametrarna (p, d och q), som sedan används för att utveckla en prognos.

> En engångschock kommer att påverka efterföljande värden för en Box-Jenkins-modell oändligt in i framtiden. Därför lever arvet från finanskrisen vidare i dagens autoregressiva modeller.

>

## Autoregressive Integrated Moving Average (ARIMA)

Box-Jenkins är en typ av autoregressiv integrerad glidande medelvärde (ARIMA) modell som mäter styrkan hos en beroende variabel i förhållande till andra förändrade variabler. Modellens mål är att förutsäga framtida värdepappers- eller finansmarknadsrörelser genom att undersöka skillnaderna mellan värden i serien istället för genom faktiska värden.

En ARIMA-modell kan förstås genom att beskriva var och en av dess komponenter enligt följande:

- [Autoregression (AR)](/autoregressive) : hänvisar till en modell som visar en föränderlig variabel som regresserar på sina egna fördröjda eller tidigare värden.

- Integrerad (I): representerar skillnaden mellan råobservationer för att tillåta att tidsserien blir stationär, dvs. datavärden ersätts av skillnaden mellan datavärdena och de tidigare värdena.

- [Glidande medelvärde (MA)](/movingaverage) : inkluderar beroendet mellan en observation och ett kvarvarande fel från en glidande medelvärde som tillämpas på fördröjda observationer.

## Prognostisera aktiekurser

En användning för Box-Jenkins modellanalys är att prognostisera [aktiekurser](/stock). Denna analys byggs vanligtvis ut och kodas genom R-programvara. Resultatanalysen i ett logaritmiskt utfall, som kan appliceras på datamängden för att generera de prognostiserade priserna för en viss tidsperiod i framtiden.

ARIMA-modeller är baserade på antagandet att tidigare värden har en viss resteffekt på nuvarande eller framtida värden. Till exempel skulle en investerare som använder en ARIMA-modell för att prognostisera aktiekurser anta att nya köpare och säljare av den aktien påverkas av de senaste marknadstransaktionerna när de bestämmer hur mycket de ska erbjuda eller acceptera för värdepapperet.

Även om detta antagande kommer att gälla under många olika omständigheter, är det inte alltid sant. Till exempel, under åren före finanskrisen 2008, var de flesta investerare inte medvetna om riskerna med de stora portföljerna av [inteckningsskyddade värdepapper](/mbs) (MBS) som innehas av många finansiella företag.

Under dessa tider skulle en investerare som använder en autoregressiv modell för att förutsäga utvecklingen för amerikanska finansaktier ha haft goda skäl att förutsäga en pågående trend med stabila eller stigande aktiekurser i den sektorn. Men när det väl blev allmänt känt att många finansiella institutioner riskerade att kollapsa, blev investerare plötsligt mindre bekymrade över dessa aktiers senaste priser och mycket mer bekymrade över deras underliggande riskexponering.

Därför omvärderas marknaden snabbt finansiella aktier till en mycket lägre nivå, ett drag som helt skulle ha förvirrat en autoregressiv modell.

##Höjdpunkter

- Autoregressivt integrerat glidande medelvärde (ARIMA) modeller är en form av Box-Jenkins modell.

- Box-Jenkins-modellen är bäst lämpad för prognoser inom tidsramar på 18 månader eller mindre.

– Metodiken bygger på antagandet att tidigare händelser påverkar framtida.

- Box-Jenkins-modellen är en prognosmetodik som använder regressionsstudier på tidsseriedata.

