---
keywords: Investing,Fundamental Analysis
title: Restsumma av kvadrater (RSS)
description: Residualsumman av kvadrater (RSS) är en statistisk teknik som används för att mäta variansen i en datamängd som inte förklaras av regressionsmodellen.
---

# Restsumma av kvadrater (RSS)
## Vad är den resterande summan av kvadrater (RSS)?

Residualsumman av kvadrater (RSS) är en statistisk teknik som används för att mäta mängden [varians](/variance) i en datamängd som inte förklaras av en regressionsmodell i sig. Istället uppskattar den variansen i residualerna eller [feltermen](/errorterm).

[Linjär regression](/regression) är ett mått som hjälper till att bestämma styrkan i sambandet mellan en beroende variabel och en eller flera andra faktorer, så kallade oberoende eller förklarande variabler.

## Förstå den återstående summan av kvadrater

I allmänna termer är [summan av kvadrater](/sum-of-squares) en statistisk teknik som används i regressionsanalys för att bestämma spridningen av datapunkter. I en regressionsanalys är målet att bestämma hur väl en dataserie kan anpassas till en funktion som kan hjälpa till att förklara hur dataserien genererades. Summan av kvadrater används som ett matematiskt sätt att hitta den funktion som [bäst passar](/line-of-best-fit) (varierar minst) från data.

RSS mäter mängden fel som återstår mellan regressionsfunktionen och datamängden efter att modellen har körts. En mindre RSS-siffra representerar en regressionsfunktion som är väl anpassad till data.

RSS, även känd som summan av kvadrerade residualer, avgör i huvudsak hur väl en regressionsmodell förklarar eller representerar data i modellen.

## Hur man beräknar restsumman av kvadrater

>

> RSS = **∑**^n^~i=1~ (**yi** - **f**(**xi**))^2^

>

>

> Var:

>

>

> y~i~ = det i^te^ värdet för variabeln som ska förutsägas

>

>

> **f**(x~i~) = förutsagt värde på y~i~

>

>

> n = övre gräns för summering

>

## Residual Sum of Squares (RSS) vs. Residual Standard Error (RSE)

Det återstående standardfelet (RSE) är en annan statistisk term som används för att beskriva skillnaden i [standardavvikelser](/standarddeviation) för observerade värden kontra förutsagda värden som visas av punkter i en regressionsanalys. Det är ett [bra](/goodness-of-fit) mått som kan användas för att analysera hur väl en uppsättning datapunkter passar med den faktiska modellen.

RSE beräknas genom att dividera RSS med antalet observationer i urvalet minus 2 och sedan ta kvadratroten: RSE = [RSS/(n-2)]^1/2^

## Särskilda överväganden

Finansmarknaderna har blivit mer kvantitativt styrda; som sådan, i jakten på en fördel, använder många investerare avancerade statistiska tekniker för att hjälpa till i sina beslut. Big data, maskininlärning och artificiell intelligens kräver vidare användningen av statistiska egenskaper för att vägleda samtida investeringsstrategier. Restsumman av kvadrater – eller RSS-statistik – är en av många statistiska egenskaper som får en renässans.

Statistiska modeller används av investerare och portföljförvaltare för att spåra en investeringspris och använda dessa data för att förutsäga framtida rörelser. Studien - kallad regressionsanalys - kan innebära att analysera förhållandet i prisrörelser mellan en vara och aktierna i företag som är engagerade i att producera varan.

> Att hitta restsumman av kvadrater (RSS) för hand kan vara svårt och tidskrävande. Eftersom det innebär mycket att subtrahera, kvadrera och summera, kan beräkningarna vara benägna att göra fel. Av denna anledning kan du välja att använda programvara, som Excel, för att göra beräkningarna.

>

Alla modeller kan ha avvikelser mellan de förutsagda värdena och faktiska resultat. Även om varianserna kan förklaras av regressionsanalysen, representerar RSS de varianser eller fel som inte förklaras.

Eftersom en tillräckligt komplex regressionsfunktion kan göras för att passa praktiskt taget vilken datauppsättning som helst, är ytterligare studier nödvändig för att avgöra om regressionsfunktionen faktiskt är användbar för att förklara variansen i datamängden.

Vanligtvis är dock ett mindre eller lägre värde för RSS idealiskt i alla modeller eftersom det betyder att det finns mindre variation i datamängden. Med andra ord, ju lägre summan av kvadrerade residualer är, desto bättre är regressionsmodellen på att förklara data.

## Exempel på restsumman av kvadrater

För en enkel (men lång) demonstration av RSS-beräkningen, överväg det välkända sambandet mellan ett lands konsumtionsutgifter och dess [BNP](/gdp). Följande diagram återspeglar de publicerade värdena för [konsumenternas](/consumer-spending) [väntande](/consumer-spending) och bruttonationalprodukten för de 27 delstaterna i Europeiska unionen, från och med 2020.

<h5><a href="">TTT</a></h5>

Världsbanken, 2020.

Konsumentutgifter och BNP har en stark positiv korrelation, och det är möjligt att förutsäga ett lands BNP baserat på konsumentutgifter (CS). Med hjälp av formeln för en [linje som passar bäst](/line-of-best-fit) kan detta förhållande uppskattas som:

>

> BNP = 1,3232 x CS + 10447

>

Enheterna för både BNP och konsumtionsutgifter är i miljoner amerikanska dollar.

Denna formel är mycket exakt för de flesta ändamål, men den är inte perfekt på grund av de individuella variationerna i varje lands ekonomi. Följande diagram jämför den prognostiserade BNP för varje land, baserat på formeln ovan, och den faktiska BNP som registrerats av Världsbanken.

<h5><a href="">TTT</a></h5>

Världsbanken, 2020.

Kolumnen till höger indikerar kvarvarande kvadrater – den kvadratiska skillnaden mellan varje projicerat värde och dess faktiska värde. Siffrorna verkar stora, men deras summa är faktiskt lägre än RSS för någon annan möjlig trendlinje. Om en annan linje hade en lägre RSS för dessa datapunkter, skulle den linjen vara den linje som passar bäst.

##Höjdpunkter

- Ett värde på noll betyder att din modell passar perfekt.

- RSS används av finansanalytiker för att uppskatta giltigheten av deras ekonometriska modeller.

- Residualsumman av kvadrater (RSS) mäter variansnivån i feltermen, eller residualerna, för en regressionsmodell.

- Statistiska modeller används av investerare och portföljförvaltare för att spåra en investerings pris och använda dessa data för att förutsäga framtida rörelser.

- Ju mindre restsumman av kvadrater, desto bättre passar din modell dina data; ju större restsumman av kvadrater, desto sämre passar din modell dina data.

##FAQ

### Är RSS detsamma som summan av kvadratisk uppskattning av fel (SSE)?

Residualsumman av kvadrater (RSS) är också känd som summan av kvadratisk uppskattning av fel (SSE).

### Vad är skillnaden mellan den resterande summan av kvadrater och den totala summan av kvadrater?

Totalsumman av kvadrater (TSS) mäter hur mycket variation det finns i de observerade data, medan den resterande summan av kvadrater mäter variationen i felet mellan de observerade data och modellerade värden. I statistik jämförs ofta värdena för restsumman av kvadrater och totalsumman av kvadrater (TSS) med varandra.

### Är den återstående summan av kvadrater densamma som R-kvadrat?

Residualsumman av kvadrater (RSS) är den absoluta mängden förklarad variation, medan R-kvadrat är den absoluta mängden variation som en andel av den totala variationen.

### Kan en restsumma av kvadrater vara noll?

Restsumman av kvadrater kan vara noll. Ju mindre restsumman av kvadrater, desto bättre passar din modell dina data; ju större restsumman av kvadrater, desto sämre passar din modell dina data. Ett värde på noll betyder att din modell passar perfekt.

