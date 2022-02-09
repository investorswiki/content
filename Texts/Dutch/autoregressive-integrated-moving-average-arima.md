---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: Autoregressive Integrated Moving Average (ARIMA)
description: Et autoregressivt integreret glidende gennemsnit (ARIMA) er en statistisk analysemodel, der udnytter tidsseriedata til at forudsige fremtidige tendenser.
---

# Autoregressive Integrated Moving Average (ARIMA)
## Hvad er et autoregressivt integreret glidende gennemsnit (ARIMA)?

Et autoregressivt integreret glidende gennemsnit, eller ARIMA, er en statistisk analysemodel, der bruger [tidsseriedata](/timeseries) til enten bedre at forstå datasættet eller til at forudsige fremtidige tendenser.

En statistisk model er autoregressiv, hvis den forudsiger fremtidige værdier baseret på tidligere værdier. For eksempel kan en ARIMA-model søge at forudsige en akties fremtidige priser baseret på dens tidligere præstationer eller forudsige en virksomheds indtjening baseret på tidligere perioder.

## Forstå Autoregressive Integrated Moving Average (ARIMA)

En autoregressiv integreret glidende gennemsnitsmodel er en form for [regressionsanalyse,](/regression) der måler styrken af en afhængig variabel i forhold til andre skiftende variable. Modellens mål er at forudsige fremtidige værdipapirer eller finansielle markedsbevægelser ved at undersøge forskellene mellem værdier i serien i stedet for gennem faktiske værdier.

En ARIMA-model kan forstås ved at skitsere hver af dens komponenter som følger:

- [Autoregression (AR)](/autoregressive) : refererer til en model, der viser en skiftende variabel, der regresserer på sine egne forsinkede eller tidligere værdier.

- **Integreret (I):** repræsenterer forskellen mellem råobservationer for at tillade, at tidsserien bliver stationær (dvs. dataværdier erstattes af forskellen mellem dataværdierne og de tidligere værdier).

- [Glidende gennemsnit (MA)](/movingaverage) : inkorporerer afhængigheden mellem en observation og en resterende fejl fra en glidende gennemsnitsmodel anvendt på forsinkede observationer.

## ARIMA-parametre

Hver komponent i ARIMA fungerer som en parameter med en standardnotation. For ARIMA-modeller ville en standardnotation være ARIMA med p, d og q, hvor heltalsværdier erstatter parametrene for at angive den anvendte type ARIMA-model. Parametrene kan defineres som:

- **p**: antallet af forsinkelsesobservationer i modellen; også kendt som lagrækkefølgen.

- **d**: antallet af gange, de rå observationer er afvigende; også kendt som graden af differens.

- q: størrelsen af vinduet med glidende gennemsnit; også kendt som rækkefølgen af det glidende gennemsnit.

I en [lineær regressionsmodel](/nonlinear-regression) indgår fx antallet og typen af led. En 0-værdi, som kan bruges som en parameter, vil betyde, at den pågældende komponent ikke skal bruges i modellen. På denne måde kan ARIMA-modellen konstrueres til at udføre funktionen af en ARMA-model eller endda simple AR-, I- eller MA-modeller.

> Fordi ARIMA-modeller er komplicerede og fungerer bedst på meget store datasæt, bruges computeralgoritmer og maskinlæringsteknikker til at beregne dem.

>

## Autoregressive Integrated Moving Average (ARIMA) og stationaritet

I en autoregressiv integreret glidende gennemsnitsmodel er dataene differentieret for at gøre dem stationære. En model, der viser stationaritet, er en, der viser, at dataene er konstante over tid. De fleste økonomiske data og markedsdata viser tendenser, så formålet med at skelne er at fjerne eventuelle tendenser eller sæsonbestemte strukturer.

[Sæsonbestemt](/seasonality),. eller når data viser regelmæssige og forudsigelige mønstre, der gentager sig over et kalenderår, kan påvirke regressionsmodellen negativt. Hvis der opstår en tendens, og stationaritet ikke er tydelig, kan mange af beregningerne gennem hele processen ikke udføres med stor effektivitet.

> Et engangschok vil påvirke efterfølgende værdier af en ARIMA-model uendeligt ud i fremtiden. Derfor lever arven fra finanskrisen videre i nutidens autoregressive modeller.

>

## Særlige overvejelser

ARIMA-modeller er baseret på den antagelse, at tidligere værdier har en resteffekt på nuværende eller fremtidige værdier. For eksempel vil en investor, der bruger en ARIMA-model til at forudsige aktiekurser, antage, at nye købere og sælgere af denne aktie er påvirket af de seneste markedstransaktioner, når de beslutter, hvor meget der skal tilbydes eller accepteres for værdipapiret.

Selvom denne antagelse vil holde under mange omstændigheder, er dette ikke altid tilfældet. For eksempel var de fleste investorer i årene forud for finanskrisen i 2008 ikke klar over de risici, som de store porteføljer af [pantesikrede værdipapirer](/mbs) (MBS) indehaves af mange finansielle virksomheder.

I disse tider ville en investor, der brugte en autoregressiv model til at forudsige resultaterne af amerikanske finansielle aktier, have haft god grund til at forudsige en vedvarende trend med stabile eller stigende aktiekurser i den pågældende sektor. Men da det blev offentligt kendt, at mange finansielle institutioner var i risiko for forestående kollaps, blev investorerne pludselig mindre bekymrede over disse aktiers seneste kurser og langt mere bekymrede over deres underliggende risikoeksponering. Derfor omvurderes markedet hurtigt finansielle aktier til et meget lavere niveau, et skridt, der ville have fuldstændig forvirret en autoregressiv model.

## Ofte stillede spørgsmål

### Hvad bruges ARIMA til?

ARIMA er en metode til at forudsige eller forudsige fremtidige resultater baseret på en historisk tidsserie. Det er baseret på det statistiske koncept om seriel korrelation, hvor tidligere datapunkter påvirker fremtidige datapunkter.

### Hvad er forskellene mellem autoregressive og glidende gennemsnitsmodeller?

ARIMA kombinerer autoregressive funktioner med glidende gennemsnit. En AR(1) autoregressiv proces er for eksempel en, hvor den aktuelle værdi er baseret på den umiddelbart foregående værdi, mens en AR(2) proces er en, hvor den aktuelle værdi er baseret på de to foregående værdier. Et glidende gennemsnit er en beregning, der bruges til at analysere datapunkter ved at skabe en række gennemsnit af forskellige delmængder af det fulde datasæt for at udjævne indflydelsen fra outliers. Som et resultat af denne kombination af teknikker kan ARIMA-modeller tage højde for tendenser, cyklusser, sæsonbestemte og andre ikke-statiske typer data, når de laver prognoser.

### Hvordan fungerer ARIMA-prognoser?

ARIMA-prognose opnås ved at indsætte tidsseriedata for variabelen af interesse. Statistisk software vil identificere det passende antal forsinkelser eller mængden af forskel, der skal anvendes på dataene, og kontrollere for stationaritet. Det vil derefter udlæse resultaterne, som ofte fortolkes på samme måde som en multipel lineær regressionsmodel.

##Højdepunkter

- Autoregressive, integrerede glidende gennemsnit (ARIMA) modeller forudsiger fremtidige værdier baseret på tidligere værdier.

- ARIMA gør brug af lagged glidende gennemsnit til at udjævne tidsseriedata.

- De er meget brugt i teknisk analyse til at forudsige fremtidige værdipapirpriser.

- Autoregressive modeller antager implicit, at fremtiden vil ligne fortiden.

- Derfor kan de vise sig unøjagtige under visse markedsforhold, såsom finansielle kriser eller perioder med hurtige teknologiske forandringer.

