---
keywords: Trading,Technical Analysis
title: T Distribution
description: AT-fördelning är en typ av sannolikhetsfunktion som är lämplig för att uppskatta populationsparametrar för små urvalsstorlekar eller okända varianser.
---

# T Distribution
## Vad är en T-distribution?

T-fördelningen, även känd som Elevens t-fördelning, är en typ av [sannolikhetsfördelning](/probabilitydistribution) som liknar normalfördelningen med sin klockform men har tyngre svansar. T-fördelningar har större chans för extrema värden än normala fördelningar, därav de fetare svansarna.

## Vad säger en T-distribution dig?

Svanstyngd bestäms av en parameter för T-fördelningen som kallas [frihetsgrader](/degrees-of-freedom),. med mindre värden som ger tyngre svansar, och med högre värden gör T-fördelningen att likna en standardnormalfördelning med medelvärdet 0 och en standardavvikelse på 1. T-distribution är också känd som "Student's T Distribution."

<!--7D50237348822D30DFF69E0C32EC0A76-->

När ett urval av n observationer tas från en normalfördelad population med medelvärde M och standardavvikelse D, kommer urvalets medelvärde, m, och urvalets standardavvikelse, d, att skilja sig från M och D på grund av urvalets slumpmässighet.

En z-poäng kan beräknas med populationens standardavvikelse som Z = (x – M)/D, och detta värde har normalfördelningen med medelvärde 0 och standardavvikelse 1. Men när man använder den uppskattade standardavvikelsen, en t-poäng beräknas som T = (m – M)/{d/sqrt(n)}, gör skillnaden mellan d och D fördelningen till en T-fördelning med (n - 1) frihetsgrader snarare än normalfördelningen med medelvärde 0 och standardavvikelse 1.

## Exempel på hur man använder en T-distribution

Ta följande exempel för hur t-fördelningar används i statistisk analys. Kom först ihåg att ett konfidensintervall för medelvärdet är ett värdeintervall, beräknat från data, menat att fånga ett "populationsmedelvärde". Detta intervall är m +- t*d/sqrt(n), där t är ett kritiskt värde från T-fördelningen.

Till exempel är ett 95 % konfidensintervall för medelavkastningen för Dow Jones Industrial Average under de 27 handelsdagarna före 2001-11-9 -0,33 %, (+/- 2,055) * 1,07 / sqrt(27), ger en (beständig) medelavkastning som något tal mellan -0,75% och +0,09%. Siffran 2,055, mängden standardfel att justera efter, hittas från T-fördelningen.

Eftersom T-fördelningen har fetare svansar än en normalfördelning, kan den användas som en modell för finansiell avkastning som uppvisar överskott av kurtosis, vilket kommer att möjliggöra en mer realistisk beräkning av Value at Risk ( [VaR](/var) ) i sådana fall.

## Skillnaden mellan en T-fördelning och en normalfördelning

Normalfördelningar används när befolkningsfördelningen antas vara normal. T-fördelningen liknar normalfördelningen, bara med fetare svansar. Båda utgår från en normalfördelad befolkning. T-fördelningar har högre kurtos än normalfördelningar. Sannolikheten att få värden väldigt långt från medelvärdet är större med en T-fördelning än en normalfördelning.

## Begränsningar för att använda en T-distribution

T-fördelningen kan skeva exaktheten i förhållande till normalfördelningen. Dess brist uppstår bara när det finns ett behov av perfekt normalitet. T-fördelningen bör endast användas när populationens standardavvikelse inte är känd. Om populationens standardavvikelse är känd och urvalsstorleken är tillräckligt stor, bör normalfördelningen användas för bättre resultat.

## Höjdpunkter

- T-fördelningen är en kontinuerlig sannolikhetsfördelning av z-poängen när den uppskattade standardavvikelsen används i nämnaren snarare än den sanna standardavvikelsen.

– T-fördelningen är liksom normalfördelningen klockformad och symmetrisk, men den har tyngre svansar, vilket gör att den tenderar att producera värden som faller långt från medelvärdet.

– T-tester används i statistik för att uppskatta signifikans.

