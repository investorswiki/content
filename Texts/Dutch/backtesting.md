---
keywords: Trading,Technical Analysis,Technical Analysis Basic Education
title: backtesting
description: Backtesting evaluerer effektiviteten af en handelsstrategi ved at køre den mod historiske data for at se, hvordan den ville have klaret sig.
---

# backtesting
## Hvad er backtesting?

Backtesting er den generelle metode til at se, hvor godt en strategi eller model ville have klaret sig [ex-post](/expost). Backtesting vurderer levedygtigheden af en [handelsstrategi](/trading-strategy) ved at finde ud af, hvordan den ville fungere ved hjælp af historiske data. Hvis backtesting virker, kan handlende og analytikere have tillid til at ansætte det fremover.

## Forstå backtesting

Backtesting giver en erhvervsdrivende mulighed for at simulere en handelsstrategi ved hjælp af [historiske data](/historical-returns) til at generere resultater og analysere risiko og rentabilitet, før han risikerer faktisk kapital.

En veludført backtest, der giver positive resultater, forsikrer [handlende](/trader) om, at strategien er grundlæggende sund og sandsynligvis vil give overskud, når den implementeres i virkeligheden. I modsætning hertil vil en veludført backtest, der giver suboptimale resultater, få handlende til at ændre eller afvise strategien.

> Særligt komplicerede handelsstrategier, såsom strategier implementeret af automatiserede handelssystemer, er stærkt afhængige af backtesting for at bevise deres værd, da de er for mystiske til at vurdere andet.

>

Så længe en handelsidé kan kvantificeres, kan den backtestes. Nogle handlende og investorer kan søge ekspertise hos en kvalificeret programmør for at udvikle ideen til en testbar form. Typisk involverer dette en programmør, der koder ideen til det proprietære sprog, der hostes af [handelsplatformen](/trading-platform) [.](/trading-platform)

Programmøren kan inkorporere brugerdefinerede inputvariabler, der tillader den erhvervsdrivende at "tweake" systemet. Et eksempel på dette ville være i det [simple glidende gennemsnit](/sma) (SMA) crossover-system. Den erhvervsdrivende ville være i stand til at indtaste (eller ændre) længderne af de to glidende gennemsnit, der bruges i systemet. Den erhvervsdrivende kunne derefter backteste for at bestemme, hvilke længder af glidende gennemsnit der ville have præsteret bedst på de historiske data.

## Det ideelle backtesting-scenarie

Den ideelle backtest vælger eksempeldata fra en relevant tidsperiode af en varighed, der afspejler en række forskellige markedsforhold. På denne måde kan man bedre vurdere, om resultaterne af backtesten repræsenterer et lykketræf eller sund handel.

Det historiske datasæt skal omfatte et reelt [repræsentativt udsnit](/representative-sample) af aktier, herunder aktier fra virksomheder, der til sidst gik [konkurs](/bankruptcy) eller blev solgt eller likvideret. Alternativet, der kun inkluderer data fra historiske aktier, der stadig findes i dag, vil give kunstigt høje afkast i backtesting.

En backtest bør overveje alle handelsomkostninger, uanset hvor ubetydelige de end er, da disse kan lægges sammen i løbet af backtesting-perioden og drastisk påvirke udseendet af en strategis rentabilitet. Handlende bør sikre, at deres backtesting-software står for disse omkostninger.

Test uden for stikprøven og fremadrettet præstationstest giver yderligere bekræftelse af et systems effektivitet og kan vise et systems sande farver, før rigtige penge er på spil. En stærk [korrelation](/correlation) mellem backtesting, out-of-sample og forward performance testresultater er afgørende for at bestemme levedygtigheden af et handelssystem.

## Backtesting vs. Fremadrettet præstationstest

Fremadrettet præstationstest, også kendt som [papirhandel](/papertrade),. giver handlende et andet sæt data uden for stikprøven, som de kan evaluere et system på. Forward performance test er en simulering af faktisk handel og involverer at følge systemets logik på et live marked. Det kaldes også papirhandel, da alle handler kun udføres på papir; det vil sige, at handelsindgange og -afgange dokumenteres sammen med eventuelle overskud eller tab for systemet, men der udføres ingen reelle handler.

Et vigtigt aspekt af fremadrettet præstationstest er at følge systemets logik nøjagtigt; ellers bliver det svært, hvis ikke umuligt, nøjagtigt at evaluere dette trin i processen. Handlende bør være ærlige om enhver handelsindgang og -udgang og undgå adfærd såsom [cherry-picking](/cherrypicking) handler eller ikke inkludere en handel på papir, der rationaliserer, at "jeg ville aldrig have taget den handel." Hvis handlen ville være sket efter systemets logik, bør den dokumenteres og evalueres.

## Backtesting vs. Scenarieanalyse

Mens backtesting bruger faktiske historiske data til at teste for pasform eller succes, gør [scenarieanalyse](/scenario_analysis) brug af hypotetiske data, der simulerer forskellige mulige resultater. For eksempel vil scenarieanalyse simulere specifikke ændringer i værdierne af porteføljens værdipapirer eller nøglefaktorer, der finder sted, såsom en ændring i [renten](/interestrate).

Scenarieanalyse bruges almindeligvis til at estimere ændringer i en [porteføljes](/portfolio) værdi som reaktion på en ugunstig begivenhed og kan bruges til at undersøge et teoretisk worst-case-scenarie.

## Nogle faldgruber ved backtesting

For at backtesting skal give meningsfulde resultater, skal handlende udvikle deres strategier og teste dem i god tro og undgå bias så meget som muligt. Det betyder, at strategien skal udvikles uden at være afhængig af de data, der bruges i backtesting.

Det er sværere end det ser ud til. Traders bygger generelt strategier baseret på historiske data. De skal være strenge med at teste med andre datasæt end dem, de træner deres modeller på. Ellers vil backtesten producere glødende resultater, der ikke betyder noget.

Tilsvarende skal handlende undgå dataudmudring, hvor de tester en lang række hypotetiske strategier mod det samme sæt data, hvilket også vil producere succeser, der mislykkes på [realtidsmarkeder](/real_time),. fordi der er mange ugyldige strategier, der ville slå markedet over en bestemt tidsrum tilfældigt.

En måde at kompensere for tendensen til dataudgravning eller cherry-pick er at bruge en strategi, der lykkes i den relevante eller in-sample, tidsperiode og backteste den med data fra en anden, eller out-of-sample, tidsperiode . Hvis in-sample og out-of-sample backtests giver lignende resultater, er der større sandsynlighed for, at de er bevist gyldige.

##Højdepunkter

- Den underliggende teori er, at enhver strategi, der fungerede godt i fortiden, sandsynligvis vil fungere godt i fremtiden, og omvendt vil enhver strategi, der har fungeret dårligt i fortiden, sandsynligvis klare sig dårligt i fremtiden.

- Backtesting vurderer levedygtigheden af en handelsstrategi eller prismodel ved at opdage, hvordan den ville have udspillet sig retrospektivt ved hjælp af historiske data.

- Når du tester en idé på historiske data, er det en fordel at reservere en tidsperiode med historiske data til testformål. Hvis det lykkes, kan test af det på alternative tidsperioder eller data uden for stikprøven hjælpe med at bekræfte dets potentielle levedygtighed.

