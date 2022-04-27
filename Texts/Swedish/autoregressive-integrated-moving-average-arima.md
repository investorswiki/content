---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: Autoregressive Integrated Moving Average (ARIMA)
description: Ett autoregressivt integrerat glidande medelvärde (ARIMA) är en statistisk analysmodell som utnyttjar tidsseriedata för att förutsäga framtida trender.
---

# Autoregressive Integrated Moving Average (ARIMA)
## Vad är ett autoregressivt integrerat glidande medelvärde (ARIMA)?

Ett autoregressivt integrerat glidande medelvärde, eller ARIMA, är en statistisk analysmodell som använder [tidsseriedata](/timeseries) för att antingen bättre förstå datamängden eller för att förutsäga framtida trender.

En statistisk modell är autoregressiv om den förutsäger framtida värden baserat på tidigare värden. Till exempel kan en ARIMA-modell försöka förutsäga en akties framtida priser baserat på dess tidigare resultat eller prognostisera ett företags resultat baserat på tidigare perioder.

## Förstå Autoregressive Integrated Moving Average (ARIMA)

En autoregressiv integrerad glidande medelvärdesmodell är en form av [regressionsanalys](/regression) som mäter styrkan hos en beroende variabel i förhållande till andra förändrade variabler. Modellens mål är att förutsäga framtida värdepappers- eller finansmarknadsrörelser genom att undersöka skillnaderna mellan värden i serien istället för genom faktiska värden.

En ARIMA-modell kan förstås genom att beskriva var och en av dess komponenter enligt följande:

- [Autoregression (AR)](/autoregressive) : hänvisar till en modell som visar en föränderlig variabel som regresserar på sina egna fördröjda eller tidigare värden.

- **Integrerad (I):** representerar skillnaden mellan obearbetade observationer för att tillåta tidsserien att bli stationär (dvs datavärden ersätts av skillnaden mellan datavärdena och de tidigare värdena).

- [Glidande medelvärde (MA)](/movingaverage) : inkluderar beroendet mellan en observation och ett kvarvarande fel från en glidande medelvärde som tillämpas på fördröjda observationer.

## ARIMA-parametrar

Varje komponent i ARIMA fungerar som en parameter med en standardnotation. För ARIMA-modeller skulle en standardnotation vara ARIMA med p, d och q, där heltalsvärden ersätter parametrarna för att indikera vilken typ av ARIMA-modell som används. Parametrarna kan definieras som:

- **p**: antalet fördröjningsobservationer i modellen; även känd som eftersläpningsordningen.

- **d**: antalet gånger som de obearbetade observationerna skiljer sig åt; även känd som graden av skillnad.

- q: storleken på fönstret för glidande medelvärde; även känd som ordningen för det glidande medelvärdet.

I en [linjär regressionsmodell](/nonlinear-regression) ingår till exempel antalet och typen av termer. Ett 0-värde, som kan användas som en parameter, skulle innebära att en viss komponent inte ska användas i modellen. På så sätt kan ARIMA-modellen konstrueras för att utföra funktionen av en ARMA-modell, eller till och med enkla AR-, I- eller MA-modeller.

> Eftersom ARIMA-modeller är komplicerade och fungerar bäst på mycket stora datamängder, används datoralgoritmer och maskininlärningstekniker för att beräkna dem.

>

## Autoregressivt integrerat rörligt medelvärde (ARIMA) och stationaritet

I en autoregressiv integrerad modell för glidande medelvärde är data differentierade för att göra dem stationära. En modell som visar stationaritet är en som visar att det finns konstanta data över tid. De flesta ekonomiska och marknadsdata visar trender, så syftet med skillnaden är att ta bort eventuella trender eller säsongsstrukturer.

[Säsongsvariationer](/seasonality),. eller när data visar regelbundna och förutsägbara mönster som upprepas under ett kalenderår, kan påverka regressionsmodellen negativt. Om en trend dyker upp och stationaritet inte är uppenbar, kan många av beräkningarna under hela processen inte göras med stor effektivitet.

> En engångschock kommer att påverka efterföljande värden för en ARIMA-modell oändligt in i framtiden. Därför lever arvet från finanskrisen vidare i dagens autoregressiva modeller.

>

## Särskilda överväganden

ARIMA-modeller är baserade på antagandet att tidigare värden har en viss resteffekt på nuvarande eller framtida värden. Till exempel skulle en investerare som använder en ARIMA-modell för att prognostisera aktiekurser anta att nya köpare och säljare av den aktien påverkas av de senaste marknadstransaktionerna när de bestämmer hur mycket de ska erbjuda eller acceptera för värdepapperet.

Även om detta antagande kommer att gälla under många omständigheter, är detta inte alltid fallet. Till exempel, under åren före finanskrisen 2008, var de flesta investerare inte medvetna om riskerna med de stora portföljerna av [inteckningsskyddade värdepapper](/mbs) (MBS) som innehas av många finansiella företag.

Under dessa tider skulle en investerare som använder en autoregressiv modell för att förutsäga utvecklingen för amerikanska finansaktier ha haft goda skäl att förutsäga en pågående trend med stabila eller stigande aktiekurser i den sektorn. Men när det väl blev allmänt känt att många finansiella institutioner riskerade att kollapsa, blev investerare plötsligt mindre bekymrade över dessa aktiers senaste priser och mycket mer bekymrade över deras underliggande riskexponering. Därför omvärderas marknaden snabbt finansiella aktier till en mycket lägre nivå, ett drag som helt skulle ha förvirrat en autoregressiv modell.

## Vanliga frågor

### Vad används ARIMA till?

ARIMA är en metod för att prognostisera eller förutsäga framtida utfall baserat på en historisk tidsserie. Den är baserad på det statistiska konceptet seriell korrelation, där tidigare datapunkter påverkar framtida datapunkter.

### Vilka är skillnaderna mellan modeller med autoregressiv och glidande medelvärde?

ARIMA kombinerar autoregressiva funktioner med glidande medelvärden. En AR(1)-autoregressiv process, till exempel, är en där det aktuella värdet är baserat på det omedelbart föregående värdet, medan en AR(2)-process är en där det aktuella värdet är baserat på de två föregående värdena. Ett glidande medelvärde är en beräkning som används för att analysera datapunkter genom att skapa en serie medelvärden av olika delmängder av den fullständiga datamängden för att jämna ut påverkan av extremvärden. Som ett resultat av denna kombination av tekniker kan ARIMA-modeller ta hänsyn till trender, cykler, säsongsvariationer och andra icke-statiska typer av data när de gör prognoser.

### Hur fungerar ARIMA-prognoser?

ARIMA-prognoser uppnås genom att plugga in tidsseriedata för variabeln av intresse. Statistisk programvara kommer att identifiera det lämpliga antalet fördröjningar eller mängden skillnader som ska tillämpas på data och kontrollera stationaritet. Den kommer sedan att mata ut resultaten, som ofta tolkas på samma sätt som en multipel linjär regressionsmodell.

##Höjdpunkter

- Autoregressiva integrerade glidande medelvärden (ARIMA) modeller förutsäger framtida värden baserat på tidigare värden.

- ARIMA använder sig av fördröjda glidande medelvärden för att jämna ut tidsseriedata.

– De används flitigt i teknisk analys för att prognostisera framtida värdepapperspriser.

– Autoregressiva modeller antar implicit att framtiden kommer att likna det förflutna.

– Därför kan de visa sig vara felaktiga under vissa marknadsförhållanden, såsom finansiella kriser eller perioder av snabba tekniska förändringar.

