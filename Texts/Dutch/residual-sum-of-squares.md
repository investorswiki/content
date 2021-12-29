---
keywords: Investing,Fundamental Analysis
title: Residual Sum of Squares (RSS)
description: Residual sum of squares (RSS) er en statistisk teknik, der bruges til at måle variansen i et datasæt, som ikke er forklaret af regressionsmodellen.
---

# Residual Sum of Squares (RSS)
## Hvad er den resterende sum af kvadrater (RSS)?

Residual sum of squares (RSS) er en statistisk teknik, der bruges til at måle mængden af [varians](/variance) i et datasæt, som ikke forklares af selve en regressionsmodel. I stedet estimerer den variansen i residualerne eller [fejltermen](/errorterm).

[Lineær regression](/regression) er en måling, der hjælper med at bestemme styrken af forholdet mellem en afhængig variabel og en eller flere andre faktorer, kendt som uafhængige eller forklarende variable.

## Forstå den resterende sum af kvadrater

Generelt er [summen af kvadrater](/sum-of-squares) en statistisk teknik, der bruges i regressionsanalyse til at bestemme spredningen af datapunkter. I en regressionsanalyse er målet at bestemme, hvor godt en dataserie kan tilpasses til en funktion, der kan være med til at forklare, hvordan dataserien blev genereret. Summen af kvadrater bruges som en matematisk måde at finde den funktion, der [bedst passer](/line-of-best-fit) (varierer mindst) ud fra dataene.

RSS'en måler mængden af tilbageværende fejl mellem regressionsfunktionen og datasættet, efter at modellen er blevet kørt. Et mindre RSS-tal repræsenterer en regressionsfunktion, der passer godt til dataene.

RSS, også kendt som summen af kvadrerede residualer, bestemmer i det væsentlige, hvor godt en regressionsmodel forklarer eller repræsenterer dataene i modellen.

## Sådan beregnes den resterende sum af kvadrater

>

> RSS = **∑**^n^~i=1~ (**yi** - **f**(**xi**))^2^

>

>

>Hvor:

>

>

> y~i~ = den i^te^ værdi af den variabel, der skal forudsiges

>

>

> **f**(x~i~) = forudsagt værdi af y~i~

>

>

> n = øvre grænse for summering

>

## Residual Sum of Squares (RSS) vs. Residual Standard Error (RSE)

Den resterende standardfejl (RSE) er et andet statistisk udtryk, der bruges til at beskrive forskellen i [standardafvigelser](/standarddeviation) af observerede værdier versus forudsagte værdier som vist ved punkter i en regressionsanalyse. Det er et [goodness-of-fit-](/goodness-of-fit) mål, der kan bruges til at analysere, hvor godt et sæt datapunkter passer med den faktiske model.

RSE beregnes ved at dividere RSS med antallet af observationer i stikprøven minus 2 og derefter tage kvadratroden: RSE = [RSS/(n-2)]^1/2^

## Særlige overvejelser

Finansmarkederne er i stigende grad blevet mere kvantitativt drevne; som sådan, på jagt efter en fordel, bruger mange investorer avancerede statistiske teknikker til at hjælpe med deres beslutninger. Big data, machine learning og kunstig intelligens-applikationer nødvendiggør yderligere brugen af statistiske egenskaber til at vejlede moderne investeringsstrategier. Den resterende sum af kvadrater – eller RSS-statistik – er en af mange statistiske egenskaber, der nyder en renæssance.

Statistiske modeller bruges af investorer og porteføljeforvaltere til at spore en investerings pris og bruge disse data til at forudsige fremtidige bevægelser. Undersøgelsen - kaldet regressionsanalyse - kan involvere at analysere forholdet i prisbevægelser mellem en vare og aktierne i virksomheder, der er involveret i at producere varen.

> At finde restsummen af kvadrater (RSS) i hånden kan være svært og tidskrævende. Fordi det involverer en masse subtraktion, kvadrering og summering, kan beregningerne være tilbøjelige til fejl. Af denne grund kan du vælge at bruge software, såsom Excel, til at udføre beregningerne.

>

Enhver model kan have afvigelser mellem de forudsagte værdier og faktiske resultater. Selvom varianserne kan forklares af regressionsanalysen, repræsenterer RSS de varianser eller fejl, der ikke er forklaret.

Da en tilstrækkelig kompleks regressionsfunktion kan laves til at passe tæt til stort set ethvert datasæt, er yderligere undersøgelse nødvendig for at bestemme, om regressionsfunktionen faktisk er nyttig til at forklare variansen af datasættet.

Typisk er en mindre eller lavere værdi for RSS dog ideel i enhver model, da det betyder, at der er mindre variation i datasættet. Med andre ord, jo lavere summen af kvadrerede residualer er, jo bedre er regressionsmodellen til at forklare dataene.

## Eksempel på den resterende sum af kvadrater

For en simpel (men langvarig) demonstration af RSS-beregningen skal du overveje den velkendte sammenhæng mellem et lands forbrugerforbrug og dets [BNP](/gdp). Følgende diagram afspejler de offentliggjorte værdier af [ventende](/consumer-spending) [forbrugere](/consumer-spending) og bruttonationalprodukt for de 27 stater i Den Europæiske Union fra 2020.

<h5><a href="">TTT</a></h5>

Verdensbanken, 2020.

Forbrugsforbrug og BNP har en stærk positiv sammenhæng, og det er muligt at forudsige et lands BNP baseret på forbrugerforbrug (CS). Ved at bruge formlen for en [bedst passende linje](/line-of-best-fit) kan dette forhold tilnærmes som:

>

> BNP = 1,3232 x CS + 10447

>

Enhederne for både BNP og forbrugsudgifter er i millioner af amerikanske dollars.

Denne formel er meget nøjagtig til de fleste formål, men den er ikke perfekt på grund af de individuelle variationer i hvert lands økonomi. Følgende diagram sammenligner det forventede BNP for hvert land, baseret på formlen ovenfor, og det faktiske BNP som registreret af Verdensbanken.

<h5><a href="">TTT</a></h5>

Verdensbanken, 2020.

Kolonnen til højre angiver de resterende kvadrater - den kvadrerede forskel mellem hver projekteret værdi og dens faktiske værdi. Tallene ser store ud, men deres sum er faktisk lavere end RSS for enhver anden mulig trendlinje. Hvis en anden linje havde en lavere RSS for disse datapunkter, ville den linje være den linje, der passer bedst.

##Højdepunkter

- En værdi på nul betyder, at din model passer perfekt.

- RSS'en bruges af finansanalytikere til at vurdere gyldigheden af deres økonometriske modeller.

- Residualsummen af kvadrater (RSS) måler variansniveauet i fejlleddet eller residualerne af en regressionsmodel.

- Statistiske modeller bruges af investorer og porteføljeforvaltere til at spore en investerings pris og bruge disse data til at forudsige fremtidige bevægelser.

- Jo mindre den resterende sum af kvadrater er, jo bedre passer din model til dine data; jo større restsum af kvadrater, jo dårligere passer din model til dine data.

##Ofte stillede spørgsmål

### Er RSS det samme som summen af kvadratisk estimat af fejl (SSE)?

Den resterende sum af kvadrater (RSS) er også kendt som summen af kvadratisk estimat af fejl (SSE).

### Hvad er forskellen mellem den resterende sum af kvadrater og total sum af kvadrater?

Den totale sum af kvadrater (TSS) måler, hvor stor variation der er i de observerede data, mens den resterende sum af kvadrater måler variationen i fejlen mellem de observerede data og modellerede værdier. I statistik sammenlignes værdierne for den resterende sum af kvadrater og den samlede sum af kvadrater (TSS) ofte med hinanden.

### Er den resterende sum af kvadrater det samme som R-kvadrat?

Residualsummen af kvadrater (RSS) er den absolutte mængde af forklaret variation, hvorimod R-kvadrat er den absolutte mængde variation som en andel af den samlede variation.

### Kan en resterende sum af kvadrater være nul?

Restsummen af kvadrater kan være nul. Jo mindre den resterende sum af kvadrater er, jo bedre passer din model til dine data; jo større restsum af kvadrater, jo dårligere passer din model til dine data. En værdi på nul betyder, at din model passer perfekt.

