---
keywords: Business,Corporate Finance and Accounting,Financial Ratios
title: Standardafvigelsesberegning
description: Hvad er standardafvigelse? Standardafvigelse er en metrik, der måler variabiliteten af et værdipapirs afkast over tid. Det kan bruges til at måle volatilitet
---

# Standardafvigelsesberegning
## Hvad er standardafvigelse?

Standardafvigelse er en metrik, der måler variabiliteten af et [værdipapirs](/security) afkast over tid. Det kan bruges til at måle [volatilitet](/volatility) baseret på tidligere resultater og sammenligne et fremtidigt afkast med tidligere afkast. Standardafvigelse kan også kvantificere fordelingen af afkast af individuelle porteføljer og kan bruges på forskellige typer aktiver, herunder [obligationer](/bond),. råvarer og kryptovaluta. Denne artikel fokuserer dog på aktier.

Standardafvigelse viser, hvor langt en akties afkast er fra dets gennemsnitlige afkast i en periode, og kan også afgøre, om et afkast for en bestemt periode er en outlier. Det er nyttigt at anvende i tider med volatilitet i en børsnoteret virksomheds aktiekurs, da store op- og nedsving i løbet af en kort periode kan hjælpe med at bestemme investeringsrisiko versus afkast.

## Sådan beregnes standardafvigelse ved hjælp af et regneark (eksempel: Apple)

At forstå standardafvigelse betyder først at forstå varians, fordi standardafvigelse, matematisk set, er kvadratroden af varians. Varians viser, hvor langt hvert afkast er fra gennemsnittet eller gennemsnittet af sættet af afkastdata.

Et tal større end 0 indikerer, at afkastene i et sæt er fjernt fra gennemsnittet og langt fra hinanden, mens et tal væsentligt større end 0 tyder på at være meget længere fra gennemsnittet. Fordi variansen af dataene er kvadreret, bringer standardafvigelsen dataene tilbage til den samme måleenhed (i tilfælde af aktier, procent) ved at tage kvadratroden.

**Bemærk**: Standardafvigelse er repræsenteret i formler ved σ, det græske lille bogstav for sigma.

Den mest effektive måde at beregne standardafvigelse på, især med et stort sæt data såsom daglige aktiekurser, er via regneark. Nedenfor er et eksempel på beregning af standardafvigelsen for Apples aktieafkast over en tremåneders periode.

**Trin 1**: Indsaml daglige data, der går tilbage over en periode på tre måneder. Dette svarer nogenlunde til omkring 20 dage om måneden, og den første dag fungerer som basispris ved beregning af den første procentvise ændring. Beregn den daglige procentvise ændring for Apples aktie, og udtryk dataene i procenter. **Bemærk**: Formlen vises i cellen såvel som i feltområdet i øverste venstre hjørne af regnearket. Apples lukkekurs (udtrykt i amerikanske dollars) tegner sig for justeringer, herunder opdelinger, udbytter og/eller kapitalgevinstudlodninger.

**Trin 2**: Beregn gennemsnittet af afkastene ved hjælp af AVERAGE-funktionen.

**Trin 3**: Beregn variansen af afkastene ved hjælp af VAR-funktionen.

**Trin 4**: Beregn standardafvigelsen for afkastene ved hjælp af STDAV-funktionen. **Bemærk**: Gennemsnittet og standardafvigelsen er udtrykt i procent, mens variansen er et decimaltal.

## Sådan fortolkes standardafvigelse

I eksemplet ovenfor for Apple viser dataene, at det gennemsnitlige afkast for tremånedersperioden var 0,08 procent. Variansen viser afstanden mellem rækken af tal og gennemsnittet. Men standardafvigelsen viser præcis, hvor langt afkastet er fra gennemsnittet. Med standardafvigelse på 1,91 procent tyder det på, at intervallet er plus eller minus 1,91 procentpoint fra gennemsnittet, hvilket betyder, at Apples afkast har en tendens til at variere fra -1,83 procent til 1,99 procent.

### Standardafvigelse som sandsynlighed i normalfordeling

Standardafvigelse kan bedst illustreres via normalfordelingsmønsteret for sandsynlighed, som giver et statistisk billede af, hvor standardafvigelsen kan være. I normalfordelingen har de fleste af scenarierne i sandsynlighed en tendens til at forekomme tættere på gennemsnittet. Sjældnere tilfælde har en tendens til at forekomme udad, mod de områder, der flader, kendt som haler.

I grafen nedenfor er en normalfordeling formet som en klokke, deraf dens kaldenavn klokkekurven, hvor midten af kurven repræsenterer middelværdien. Tallene, der er anført vandret under grafen, er kendt som z-scores, som går fra -3 til 3. De er standardafvigelsespunkter og artikuleres anderledes end standardafvigelsesformlen, som er udtrykt i procent.

Normalfordelingsberegningen kan give sandsynligheder for, hvilke parametre potentielle afkast kan være. Lad os sige, at en daytrader forventer, at Apples aktie stiger med 5 procent dagen efter at have rapporteret rekordindtjening og omsætning for det seneste rapporterede kvartal. Hvad er sandsynligheden for, at aktien vil give et afkast på 5 procent næste dag?

Z-kode formlen kan vise, hvor afkastet ville være på normalfordelingsgrafen.

Ved at tilslutte Apples forventede afkast, gennemsnit og standardafvigelse taget fra ovenstående regneark:

> (5% - 0,08%) / 1,91% = 2,57 standardafvigelser over gennemsnittet.

Et potentielt afkast på 5 procent på Apples aktie ville være 2,57 standardafvigelser over gennemsnittet, hvilket falder mellem 2 og 3 standardafvigelser fra gennemsnittet. Statistisk set indikerer det en 2,28 procents sandsynlighed for at opnå det forventede afkast på 5 procent. Den 2,28 procent sandsynlighed udledes ved at trække 95,44 procent fra 100 procent, og forskellen (4,56 procent) divideres derefter med to på grund af de lige store sandsynlighedsbeløb på hver side (negativ og positiv) af den symmetriske linje i normalfordelingsgrafen . Under alle omstændigheder ville en daglig gevinst på 5 procent på Apples aktier ikke være almindelig.

En anden måde at fortolke normalfordelingen på er at sige, at sandsynligheden for, at Apples afkast (i et interval på -1,83 procent og 1,99 procent) falder inden for -1 og 1 standardafvigelse fra gennemsnittet, er 68,26 procent. Sandsynligheden for en standardafvigelse mellem -2 og 2 er 95,44 procent, og mellem -3 og 3 er den 99,74 procent.

## Hvordan er standardafvigelse relateret til volatilitet?

Standardafvigelse kan vise, hvordan et afkast forholder sig til gennemsnittet. En høj standardafvigelse ville indikere høj volatilitet, og et afkast, der er større end standardafvigelsesintervallet, tyder på, at det er en outlier. En række op- og nedsving uden for dette interval i en periode vil også indikere høj volatilitet.

##Højdepunkter

- Det beregnes som kvadratroden af variansen.

- Standardafvigelse, i finans, bruges ofte som et mål for en relativ risiko ved et aktiv.

- Standardafvigelse måler spredningen af et datasæt i forhold til dets middelværdi.

- En volatil aktie har en høj standardafvigelse, mens afvigelsen for en stabil blue-chip aktie normalt er ret lav.

- Som en ulempe beregner standardafvigelsen al usikkerhed som risiko, selv når det er til investorens favør – såsom afkast over gennemsnittet.

##Ofte stillede spørgsmål

### Hvad betyder en høj standardafvigelse?

En stor standardafvigelse indikerer, at der er stor varians i de observerede data omkring middelværdien. Dette indikerer, at de observerede data er ret spredte. En lille eller lav standardafvigelse ville i stedet indikere, at meget af de observerede data er klynget tæt omkring middelværdien.

### Hvorfor er standardafvigelse vigtig?

Standardafvigelse er vigtig, fordi den kan hjælpe brugerne med at vurdere risikoen. Overvej en investeringsmulighed med et gennemsnitligt årligt afkast på 10 % om året. Dette gennemsnit blev dog afledt af de seneste tre års afkast på 50 %, -15 % og -5 %. Ved at beregne standardafvigelsen og forstå din lave sandsynlighed for rent faktisk at have et gennemsnit på 10 % i et givet år, er du bedre rustet til at træffe informerede beslutninger og erkende den underliggende risiko.

### Hvad fortæller standardafvigelsen dig?

Standardafvigelse beskriver, hvor spredt et datasæt er. Den sammenligner hvert datapunkt med gennemsnittet af alle datapunkter, og standardafvigelsen returnerer en beregnet værdi, der beskriver, om datapunkterne er tæt på hinanden, eller om de er spredt ud. I en normalfordeling fortæller standardafvigelsen dig, hvor langt værdierne er fra middelværdien.

### Hvordan beregner du standardafvigelse?

Standardafvigelsen beregnes som kvadratroden af variansen. alternativt beregnes det ved at finde middelværdien af et datasæt, finde forskellen mellem hvert datapunkt og gennemsnittet, kvadrere forskellene, lægge dem sammen, dividere med antallet af punkter i datasættet mindre end 1 og finde kvadratrod.

### Hvordan finder du standardafvigelsen hurtigt?

Hvis du ser på fordelingen af nogle observerede data visuelt, kan du se, om formen er relativt tynd vs. fed. Fede fordelinger har større standardafvigelser. Alternativt har Excel indbygget standardafvigelsesfunktioner afhængigt af datasættet.

