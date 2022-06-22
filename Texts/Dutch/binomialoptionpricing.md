---
keywords: Trading,Options and Derivatives Trading,Options and Derivatives
title: Binomial Option prismodel
description: En binomial option prissætningsmodel er en option værdiansættelsesmetode, der bruger en iterativ procedure og giver mulighed for nodespecifikationen i en fastsat periode.
---

# Binomial Option prismodel
## Hvad er prismodellen for binomiale optioner?

Den binomiale option-prissætningsmodel er en [værdiansættelsesmetode for optioner udviklet i 1979. Den binomiale option-prissætningsmodel bruger en iterativ procedure, der giver mulighed for specifikation af noder eller](/valuation) [tidspunkter](/expiration-date) i tidsrummet mellem værdiansættelsesdatoen og optionens [udløbsdato](/expiration-date).

Modellen reducerer mulighederne for prisændringer og fjerner muligheden for [arbitrage](/arbitrage). Et forenklet eksempel på et [binomialtræ](/binomial_tree) kan se sådan ud:

<!--87C9D3D79FF63D08201E6E848035602D-->

## Grundlæggende om prismodellen for binomial optioner

Med binomiale optionsprismodeller er antagelserne, at der er to mulige udfald - derfor den binomiale del af modellen. Med en prismodel er de to resultater en bevægelse op eller en bevægelse ned. Den største fordel ved en binomial optionsprismodel er, at de er matematisk enkle. Alligevel kan disse modeller blive komplekse i en multi-periode model.

I modsætning til [Black-Scholes-modellen](/blackscholes),. som giver et numerisk resultat baseret på input, giver den binomiale model mulighed for beregning af aktivet og mulighed for flere perioder sammen med rækken af mulige resultater for hver periode (se nedenfor).

Fordelen ved denne multi-periodevisning er, at brugeren kan visualisere ændringen i aktivprisen fra periode til periode og evaluere muligheden baseret på beslutninger truffet på forskellige tidspunkter. For en amerikansk-baseret [option](/americanoption),. som kan udnyttes til enhver tid før [udløbsdatoen](/expirationdate),. kan den binomiale model give indsigt i, hvornår det kan være tilrådeligt at udnytte optionen, og hvornår den bør holdes i længere perioder.

Ved at se på det [binomiale værditræ](/binomial_tree) kan en erhvervsdrivende på forhånd bestemme, hvornår en beslutning om en [øvelse](/exercise) kan finde sted. Hvis optionen har en positiv værdi, er der mulighed for udnyttelse, hvorimod, hvis optionen har en værdi mindre end nul, bør den holdes i længere perioder.

## Beregning af pris med den binomiale model

Den grundlæggende metode til at beregne den binomiale option-model er at bruge den samme sandsynlighed hver periode for succes og fiasko, indtil optionen udløber. En erhvervsdrivende kan dog inkorporere forskellige sandsynligheder for hver periode baseret på nye oplysninger, der er opnået efterhånden som tiden går.

Et binomialtræ er et nyttigt værktøj, når du prissætter [amerikanske optioner](/americanoption) og [indlejrede optioner](/embeddedoption). Dens enkelhed er dens fordel og ulempe på samme tid. Træet er nemt at modellere mekanisk, men problemet ligger i, at de mulige værdier af det underliggende aktiv kan tage på en periode. I en binomial træmodel kan det underliggende aktiv kun være værd præcis én af to mulige værdier, hvilket ikke er realistisk, da aktiver kan være et vilkårligt antal værdier værd inden for et givet interval.

For eksempel kan der være en 50/50 chance for, at den underliggende aktivpris kan stige eller falde med 30 procent i en periode. I anden periode kan sandsynligheden for, at den underliggende aktivpris stiger, dog vokse til 70/30.

For eksempel, hvis en investor vurderer en [oliebrønd](/exploratory-well),. er denne investor ikke sikker på, hvad værdien af den oliebrønd er, men der er en 50/50 chance for, at prisen vil stige. Hvis oliepriserne stiger i periode 1, hvilket gør olieboringen mere værdifuld, og markedsfundamentalerne [nu](/fundamentals) peger på fortsatte stigninger i oliepriserne, kan sandsynligheden for yderligere prisstigning nu være 70 procent. Den binomiale model giver mulighed for denne fleksibilitet; det gør Black-Scholes-modellen ikke.

<!--94DBA31F9D3220C6052579D485B8A416-->

## Real-World Eksempel på binomial option prismodel

Et forenklet eksempel på et [binomialtræ](/binomial_tree) har kun ét trin. Antag, at der er en aktie, der er prissat til $100 pr. Om en måned vil prisen på denne aktie stige med $10 eller falde med $10, hvilket skaber denne situation:

- **Lagerpris** = 100 USD

- **Aktiekurs i en måned (op tilstand)** = 110 USD

- **Aktiekurs på én måned (nedadgående tilstand)** = 90 USD

Antag dernæst, at der er en call-option tilgængelig på denne aktie, der udløber om en måned og har en strejkepris på $100. I op-tilstand er denne call-option $10 værd, og i ned-tilstand er den $0 værd. Den binomiale model kan beregne, hvad prisen på købsoptionen skal være i dag.

Antag for forenklingsformål, at en investor køber en halv aktie af aktier og skriver eller sælger en købsoption. Den samlede investering i dag er prisen på en halv aktie minus prisen på optionen, og de mulige udbetalinger i slutningen af måneden er:

- **Pris i dag** = $50 - option pris

- **Porteføljeværdi** (op tilstand) = 55 USD - maks. (110 USD - 100 USD, 0) = 45 USD

- **Porteføljeværdi** (nedadgående tilstand) = 45 USD - maks. (90 USD - 100 USD, 0) = 45 USD

Porteføljeudbyttet er lige meget, uanset hvordan aktiekursen bevæger sig. Givet dette resultat, forudsat at der ikke er nogen arbitragemuligheder, bør en investor tjene den risikofrie rente i løbet af måneden. Omkostningerne i dag skal svare til udbetalingen tilbagediskonteret med risikofri kurs i en måned. Ligningen der skal løses er således:

- **Optionspris** = $50 - $45 xe ^ (-risikofri rate x T), hvor e er den matematiske konstant 2,7183.

Hvis vi antager, at den risikofrie rente er 3% om året, og T er lig med 0,0833 (en divideret med 12), så er prisen på call-optionen i dag $5,11.

Den binomiale option prismodel præsenterer to fordele for option sælgere i forhold til Black-Scholes modellen. Den første er dens enkelhed, som giver mulighed for færre fejl i den kommercielle applikation. Den anden er dens iterative operation, som justerer priserne rettidigt for at reducere muligheden for købere til at udføre arbitragestrategier.

For eksempel, da det giver en strøm af værdiansættelser for et [derivat](/derivative) for hver node i et tidsrum, er det nyttigt til værdiansættelse af derivater såsom amerikanske optioner - som kan udføres når som helst mellem købsdatoen og udløbsdatoen. Det er også meget enklere end andre prismodeller såsom Black-Scholes-modellen.

##Højdepunkter

- Modellen er intuitiv og bruges hyppigere i praksis end den velkendte Black-Scholes-model.

- Med modellen er der to mulige udfald med hver iteration - en bevægelse op eller en bevægelse ned, der følger et binomialtræ.

- Den binomiale model for prisfastsættelse af optioner værdisætter optioner ved hjælp af en iterativ tilgang, der bruger flere perioder til at værdiansætte amerikanske optioner.

