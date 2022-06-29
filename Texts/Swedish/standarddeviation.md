---
keywords: Business,Corporate Finance and Accounting,Financial Ratios
title: Standardavvikelseberäkning
description: Vad är standardavvikelse? Standardavvikelse är ett mått som mäter variationen i ett värdepappers avkastning över tid. Den kan användas för att mäta volatilitet
---

# Standardavvikelseberäkning
## Vad är standardavvikelse?

Standardavvikelse är ett mått som mäter variationen i ett [värdepappers](/security) avkastning över tid. Den kan användas för att mäta [volatilitet](/volatility) baserat på tidigare resultat och jämföra en framtida avkastning med tidigare avkastning. Standardavvikelse kan också kvantifiera fördelningen av avkastningen för enskilda portföljer och kan användas på olika typer av tillgångar, inklusive [obligationer](/bond),. råvaror och kryptovaluta. Den här artikeln fokuserar dock på aktier.

Standardavvikelsen visar hur långt en akties avkastning är från dess genomsnittliga avkastning under en period, och kan också avgöra om en avkastning för en viss period är en extremvärde. Det är användbart att tillämpa under tider av volatilitet i ett börsnoterat företags aktiekurs, eftersom stora upp- och nedsvängningar under en kort period kan hjälpa till att avgöra investeringsrisk kontra avkastning.

## Hur man beräknar standardavvikelse med hjälp av ett kalkylblad (exempel: Apple)

Att förstå standardavvikelse innebär att först förstå varians eftersom standardavvikelse, matematiskt sett, är kvadratroten av varians. Varians visar hur långt varje avkastning är från genomsnittet, eller medelvärdet, av uppsättningen av avkastningsdata.

En siffra som är större än 0 indikerar att avkastningen i en uppsättning är avlägsen från genomsnittet och långt från varandra, medan ett tal som är betydligt större än 0 tyder på att det ligger mycket längre från genomsnittet. Eftersom variansen för data är kvadratisk, för standardavvikelsen data tillbaka till samma måttenhet (i fallet med aktier, procent) genom att ta kvadratroten.

**Obs**: Standardavvikelse representeras i formler av σ, den grekiska gemena bokstaven för sigma.

Det mest effektiva sättet att beräkna standardavvikelsen, särskilt med en stor uppsättning data som dagliga aktiekurser, är via kalkylblad. Nedan är ett exempel på beräkning av standardavvikelsen för Apples aktieavkastning under en tremånadersperiod.

**Steg 1**: Samla in daglig data som sträcker sig tillbaka över en tremånadersperiod. Detta motsvarar ungefär 20 dagar per månad, och den första dagen fungerar som baspris för att beräkna den första procentuella förändringen. Beräkna dagliga procentuella förändringar för Apples aktie och uttrycka data i procent. **Obs**: Formeln visas i cellen såväl som i fältområdet i det övre vänstra hörnet av kalkylarket. Apples stängningskurs (uttryckt i amerikanska dollar) står för justeringar, inklusive split, utdelningar och/eller kapitalvinstutdelningar.

**Steg 2**: Beräkna medelvärdet av avkastningen med funktionen AVERAGE.

**Steg 3**: Beräkna variansen för avkastningen med hjälp av VAR-funktionen.

**Steg 4**: Beräkna standardavvikelsen för avkastningen med hjälp av STDEV-funktionen. **Obs**: Medelvärdet och standardavvikelsen uttrycks i procent, medan variansen är ett decimaltal.

## Hur man tolkar standardavvikelse

I exemplet ovan för Apple visar data att den genomsnittliga avkastningen för tremånadersperioden var 0,08 procent. Variansen visar avståndet mellan siffrorna och medelvärdet. Men standardavvikelsen visar exakt hur långt avkastningen är från genomsnittet. Med standardavvikelsen på 1,91 procent tyder det på att intervallet är plus eller minus 1,91 procentenheter från genomsnittet, vilket innebär att Apples avkastning tenderar att variera från -1,83 procent till 1,99 procent.

### Standardavvikelse som sannolikhet i normalfördelning

Standardavvikelsen kan bäst illustreras via normalfördelningsmönstret för sannolikhet, vilket ger en statistisk bild av var standardavvikelsen kan finnas. I normalfördelningen tenderar de flesta scenarierna med sannolikhet att inträffa närmare medelvärdet. Mer sällsynta fall tenderar att förekomma utåt, mot de områden som plattar ut kallas svansar.

I grafen nedan är en normalfördelning formad som en klocka, därav dess smeknamn klockkurvan, där mitten av kurvan representerar medelvärdet. Siffrorna som listas horisontellt under grafen kallas z-poäng, som sträcker sig från -3 till 3. De är standardavvikelsepunkter och artikuleras annorlunda än standardavvikelsens formel, som uttrycks i procent.

Normalfördelningsberäkningen kan ge sannolikheter för vilka parametrar potentiell avkastning kan vara. Låt oss säga att en daytrader räknar med att Apples aktie stiger med 5 procent dagen efter att ha rapporterat rekordvinster och intäkter för det senaste kvartalet. Vad är sannolikheten för att aktien kommer att ge en avkastning på 5 procent nästa dag?

Z-kodformeln kan visa var avkastningen skulle vara på normalfördelningsgrafen.

Genom att koppla in Apples beräknade avkastning, medelvärde och standardavvikelse från ovanstående kalkylblad:

> (5% - 0,08%) / 1,91% = 2,57 standardavvikelser över genomsnittet.

En potentiell avkastning på 5 procent på Apples aktie skulle vara 2,57 standardavvikelser över genomsnittet, och falla mellan 2 och 3 standardavvikelser från medelvärdet. Statistiskt sett indikerar det en 2,28 procents sannolikhet att uppnå den prognostiserade avkastningen på 5 procent. Den 2,28 procents sannolikheten härleds genom att subtrahera 95,44 procent från 100 procent, och skillnaden (4,56 procent) divideras sedan med två på grund av lika stor sannolikhet på varje sida (negativ och positiv) av den symmetriska linjen i normalfördelningsgrafen . I vilket fall som helst skulle en daglig vinst på 5 procent på Apples aktier inte vara vanligt.

Ett annat sätt att tolka normalfördelningen är att säga att sannolikheten för att Apples avkastning (vid intervallet -1,83 procent och 1,99 procent) hamnar inom -1 och 1 standardavvikelse från medelvärdet är 68,26 procent. Sannolikheten för en standardavvikelse mellan -2 och 2 är 95,44 procent och mellan -3 och 3 är den 99,74 procent.

## Hur är standardavvikelsen relaterad till volatiliteten?

Standardavvikelse kan visa hur en avkastning förhåller sig till genomsnittet. En hög standardavvikelse skulle indikera hög volatilitet, och en avkastning som är större än standardavvikelsen tyder på att det är en extremvärde. En serie upp- och nedsvängningar utanför det intervallet under en period skulle också indikera hög volatilitet.

##Höjdpunkter

- Det beräknas som kvadratroten av variansen.

- Standardavvikelse, inom finans, används ofta som ett mått på en relativ risk i en tillgång.

- Standardavvikelse mäter spridningen av en datauppsättning i förhållande till dess medelvärde.

– En volatil aktie har en hög standardavvikelse, medan avvikelsen för en stabil blue-chip-aktie vanligtvis är ganska låg.

– Som en nackdel räknar standardavvikelsen ut all osäkerhet som risk, även när det är till investerarens fördel — som en avkastning över genomsnittet.

##FAQ

### Vad betyder en hög standardavvikelse?

En stor standardavvikelse indikerar att det finns en stor varians i de observerade data kring medelvärdet. Detta tyder på att de observerade uppgifterna är ganska spridda. En liten eller låg standardavvikelse skulle istället tyda på att mycket av de observerade data är klustrade tätt runt medelvärdet.

### Varför är standardavvikelse viktigt?

Standardavvikelse är viktig eftersom det kan hjälpa användare att bedöma risker. Överväg ett investeringsalternativ med en genomsnittlig årlig avkastning på 10 % per år. Detta genomsnitt härleddes dock från de senaste tre årens avkastning på 50 %, -15 % och -5 %. Genom att beräkna standardavvikelsen och förstå din låga sannolikhet att faktiskt vara i genomsnitt 10 % under ett enskilt år, är du bättre rustad att fatta välgrundade beslut och inse den underliggande risken.

### Vad säger standardavvikelsen dig?

Standardavvikelse beskriver hur spridd en uppsättning data är. Den jämför varje datapunkt med medelvärdet av alla datapunkter, och standardavvikelsen returnerar ett beräknat värde som beskriver om datapunkterna ligger i närheten eller om de är utspridda. I en normalfördelning talar standardavvikelsen om hur långt värdena är från medelvärdet.

### Hur beräknar du standardavvikelse?

Standardavvikelsen beräknas som kvadratroten av variansen. alternativt beräknas den genom att hitta medelvärdet för en datamängd, hitta skillnaden mellan varje datapunkt och medelvärdet, kvadrera skillnaderna, lägga ihop dem, dividera med antalet punkter i datamängden mindre än 1, och hitta kvadratrot.

### Hur hittar du standardavvikelsen snabbt?

Om du tittar på fördelningen av vissa observerade data visuellt kan du se om formen är relativt mager vs. fett. Fetare distributioner har större standardavvikelser. Alternativt har Excel inbyggda standardavvikelsefunktioner beroende på datamängden.

