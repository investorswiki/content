---
keywords: Trading,Technical Analysis,Technical Analysis Basic Education
title: backtesting
description: Backtesting utvärderar effektiviteten av en handelsstrategi genom att köra den mot historiska data för att se hur det skulle ha gått.
---

# backtesting
## Vad är backtesting?

Backtesting är den allmänna metoden för att se hur bra en strategi eller modell skulle ha fungerat i [efterhand](/expost). Backtesting bedömer lönsamheten för en [handelsstrategi](/trading-strategy) genom att upptäcka hur den skulle fungera med historiska data. Om backtesting fungerar kan handlare och analytiker ha förtroendet att använda det framöver.

## Förstå Backtesting

Backtesting tillåter en handlare att simulera en handelsstrategi med hjälp av [historiska data](/historical-returns) för att generera resultat och analysera risker och lönsamhet innan de riskerar något faktiskt kapital.

Ett väl genomfört backtest som ger positiva resultat försäkrar [handlare](/trader) om att strategin är i grunden sund och sannolikt kommer att ge vinster när den implementeras i verkligheten. Däremot kommer ett väl genomfört backtest som ger suboptimala resultat att få handlare att ändra eller förkasta strategin.

> Särskilt komplicerade handelsstrategier, såsom strategier implementerade av automatiserade handelssystem, är mycket beroende av backtesting för att bevisa sitt värde, eftersom de är för svårbegripliga för att utvärdera något annat.

>

Så länge en handelsidé kan kvantifieras kan den backtestas. Vissa handlare och investerare kan söka expertis hos en kvalificerad programmerare för att utveckla idén till en testbar form. Vanligtvis involverar detta en programmerare som kodar idén till det proprietära språket som är värd [för](/trading-platform) [handelsplattformen](/trading-platform).

Programmeraren kan inkorporera användardefinierade indatavariabler som gör att handlaren kan "tweaka" systemet. Ett exempel på detta skulle vara i det [enkla glidande](/sma) medelvärdet (SMA) crossover-systemet. Handlaren skulle kunna mata in (eller ändra) längden på de två glidande medelvärden som används i systemet. Handlaren kunde sedan backtesta för att avgöra vilka längder av glidande medelvärden som skulle ha presterat bäst på historiska data.

## Det ideala backtesting-scenariot

Det ideala backtestet väljer exempeldata från en relevant tidsperiod med en varaktighet som speglar en mängd olika marknadsförhållanden. På så sätt kan man bättre bedöma om resultatet av backtestet representerar en lyckoträff eller sund handel.

Den historiska datamängden måste innehålla ett verkligt [representativt urval](/representative-sample) av aktier, inklusive de från företag som så småningom gick i [konkurs](/bankruptcy) eller såldes eller likviderades. Alternativet, inklusive endast data från historiska aktier som fortfarande finns kvar idag, kommer att ge artificiellt hög avkastning i backtesting.

Ett backtest bör överväga alla handelskostnader, hur obetydliga de än är, eftersom dessa kan läggas ihop under loppet av backtesting-perioden och drastiskt påverka utseendet på en strategis lönsamhet. Handlare bör se till att deras backtesting-programvara står för dessa kostnader.

Utomprovstestning och framåtprestandatestning ger ytterligare bekräftelse angående ett systems effektivitet och kan visa ett systems verkliga färger innan riktiga pengar är på gång. En stark [korrelation](/correlation) mellan backtesting, out-of-samp och forward prestationstestresultat är avgörande för att bestämma lönsamheten för ett handelssystem.

## Backtesting vs. Framåtprestandatestning

Framåtprestandatestning, även känd som [pappershandel](/papertrade),. förser handlare med ytterligare en uppsättning out-of-sample data för att utvärdera ett system. Framåtprestandatestning är en simulering av faktisk handel och innebär att följa systemets logik på en livemarknad. Det kallas också för pappershandel eftersom alla affärer endast utförs på papper; det vill säga transaktioner och utträden dokumenteras tillsammans med eventuell vinst eller förlust för systemet, men inga riktiga affärer utförs.

En viktig aspekt av framåtprestandatestning är att följa systemets logik exakt; annars blir det svårt, för att inte säga omöjligt, att exakt utvärdera detta steg i processen. Handlare bör vara ärliga om alla handelsinträden och utträden och undvika beteenden som [körsbärsplockningsaffärer](/cherrypicking) eller att inte inkludera en handel på papper som rationaliserar att "jag skulle aldrig ha tagit den handeln." Om handeln skulle ha skett enligt systemets logik bör den dokumenteras och utvärderas.

## Backtesting vs. Scenariosanalys

Medan backtesting använder faktiska historiska data för att testa för passform eller framgång, använder [scenarioanalys hypotetiska data som simulerar olika möjliga utfall.](/scenario_analysis) Till exempel kommer scenarioanalys att simulera specifika förändringar i värdena på portföljens värdepapper eller nyckelfaktorer som äger rum, såsom en förändring i [räntan](/interestrate).

Scenarioanalys används vanligtvis för att uppskatta förändringar i en [portföljs](/portfolio) värde som svar på en ogynnsam händelse och kan användas för att undersöka ett teoretiskt värsta scenario.

## Några fallgropar med backtesting

För att backtesting ska ge meningsfulla resultat måste handlare utveckla sina strategier och testa dem i god tro och undvika partiskhet så mycket som möjligt. Det betyder att strategin bör utvecklas utan att förlita sig på data som används i backtesting.

Det är svårare än det verkar. Handlare bygger i allmänhet strategier baserade på historiska data. De måste vara strikta med att testa med andra datamängder än de de tränar sina modeller på. Annars kommer backtestet att ge lysande resultat som inte betyder något.

På liknande sätt måste handlare undvika datamuddring, där de testar ett brett utbud av hypotetiska strategier mot samma uppsättning data, vilket också kommer att ge framgångar som misslyckas på [realtidsmarknader](/real_time) eftersom det finns många ogiltiga strategier som skulle slå marknaden över en specifik tidsperiod av en slump.

Ett sätt att kompensera för tendensen till att data muddra eller cherry-plocka är att använda en strategi som lyckas i den relevanta, eller in-sample, tidsperioden och backtesta den med data från en annan, eller out-of-sample, tidsperiod . Om backtests inom och utanför urvalet ger liknande resultat, är det mer sannolikt att de bevisas giltiga.

##Höjdpunkter

– Den underliggande teorin är att varje strategi som fungerade bra tidigare sannolikt kommer att fungera bra i framtiden, och omvänt kommer varje strategi som fungerade dåligt tidigare sannolikt att fungera dåligt i framtiden.

- Backtesting bedömer lönsamheten hos en handelsstrategi eller prismodell genom att upptäcka hur den skulle ha utspelat sig i efterhand med hjälp av historiska data.

- När du testar en idé på historisk data är det fördelaktigt att reservera en tidsperiod med historisk data för teständamål. Om det lyckas kan testa det på alternativa tidsperioder eller data utanför urvalet hjälpa till att bekräfta dess potentiella livskraft.

