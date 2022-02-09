---
keywords: Business,Corporate Finance and Accounting,Financial Ratios
title: Standardavviksberegning
description: Hva er standardavvik? Standardavvik er en beregning som måler variasjonen i et verdipapirs avkastning over tid. Den kan brukes til å måle volatilitet
---

# Standardavviksberegning
## Hva er standardavvik?

Standardavvik er en beregning som måler variasjonen i et [verdipapirs](/security) avkastning over tid. Den kan brukes til å måle [volatilitet](/volatility) basert på tidligere resultater og sammenligne en fremtidig avkastning med tidligere avkastning. Standardavvik kan også kvantifisere fordelingen av avkastningen til individuelle porteføljer, og kan brukes på ulike typer eiendeler, inkludert [obligasjoner](/bond),. råvarer og kryptovaluta. Denne artikkelen fokuserer imidlertid på aksjer.

Standardavvik viser hvor langt en aksjes avkastning er fra dens gjennomsnittlige avkastning for en periode, og kan også avgjøre om en avkastning for en viss periode er en uteligger. Det er nyttig å bruke i tider med volatilitet i et børsnotert selskaps aksjekurs, da store opp- og nedsvingninger i løpet av en kort periode kan bidra til å bestemme investeringsrisiko kontra belønning.

## Hvordan beregne standardavvik ved hjelp av et regneark (eksempel: Apple)

Å forstå standardavvik betyr først å forstå varians fordi standardavvik, matematisk sett, er kvadratroten av varians. Varians viser hvor langt hver avkastning er fra gjennomsnittet, eller gjennomsnittet, av settet med avkastningsdata.

Et tall større enn 0 indikerer at avkastningen i et sett er fjernt fra gjennomsnittet og langt fra hverandre, mens et tall som er betydelig større enn 0 antyder å være mye lenger fra gjennomsnittet. Fordi variansen til dataene er kvadrert, bringer standardavvik dataene tilbake til samme måleenhet (i tilfelle av aksjer, prosent) ved å ta kvadratroten.

**Merk**: Standardavvik er representert i formler med σ, den greske små bokstaven for sigma.

Den mest effektive måten å beregne standardavvik på, spesielt med et stort sett med data som daglige aksjekurser, er via regneark. Nedenfor er et eksempel på beregning av standardavviket til Apples aksjeavkastning over en tremånedersperiode.

**Trinn 1**: Samle inn daglige data som går tilbake over en tremånedersperiode. Dette tilsvarer omtrent 20 dager per måned, og den første dagen fungerer som basispris ved beregning av den første prosentvise endringen. Beregn daglig endring i prosent for Apples aksjer, og uttrykk dataene i prosent. **Merk**: Formelen vises i cellen så vel som i feltområdet øverst til venstre i regnearket. Apples sluttaksjekurs (uttrykt i amerikanske dollar) står for justeringer, inkludert splittelser, utbytte og/eller kapitalgevinstdistribusjoner.

**Trinn 2**: Beregn gjennomsnittet av avkastningen ved å bruke AVERAGE-funksjonen.

**Trinn 3**: Beregn variansen til avkastningen ved å bruke VAR-funksjonen.

**Trinn 4**: Beregn standardavviket for avkastningen ved å bruke STDEV-funksjonen. **Merk**: Gjennomsnittet og standardavviket er uttrykt i prosent, mens variansen er et desimaltall.

## Hvordan tolke standardavvik

I eksemplet ovenfor for Apple viser dataene at gjennomsnittlig avkastning for tremånedersperioden var 0,08 prosent. Variansen viser avstanden til rekkevidden av tall fra gjennomsnittet. Men standardavviket viser nøyaktig hvor langt avkastningen er fra gjennomsnittet. Med standardavvik på 1,91 prosent, antyder det at området er pluss eller minus 1,91 prosentpoeng fra gjennomsnittet, noe som betyr at Apples avkastning har en tendens til å variere fra -1,83 prosent til 1,99 prosent.

### Standardavvik som sannsynlighet i normalfordeling

Standardavvik kan best illustreres via normalfordelingsmønsteret for sannsynlighet, som gir en statistisk oversikt over hvor standardavviket kan være. I normalfordelingen har de fleste scenarioene i sannsynlighet en tendens til å forekomme nærmere gjennomsnittet. Sjeldnere tilfeller har en tendens til å forekomme utover, mot områdene som flater ut kjent som haler.

I grafen nedenfor er en normalfordeling formet som en klokke, derav kallenavnet klokkekurven, med midten av kurven som representerer gjennomsnittet. Tallene som er oppført horisontalt under grafen er kjent som z-score, som varierer fra -3 til 3. De er standardavvikspoeng og artikuleres annerledes enn standardavviksformelen, som er uttrykt i prosent.

Normalfordelingsberegningen kan gi sannsynligheter for hvilke parametere potensielle avkastninger kan være. La oss si at en daytrader anslår at Apples aksjer øker med 5 prosent dagen etter rapportering av rekordinntekter og -inntekter for det siste rapporterte kvartalet. Hva er sannsynligheten for at aksjen vil gi en avkastning på 5 prosent neste dag?

Z-kodeformelen kan vise hvor avkastningen vil være på normalfordelingsgrafen.

Ved å koble til Apples forventede avkastning, gjennomsnitt og standardavvik hentet fra regnearket ovenfor:

> (5 % - 0,08 %) / 1,91 % = 2,57 standardavvik over gjennomsnittet.

En potensiell avkastning på 5 prosent på Apples aksjer vil være 2,57 standardavvik over gjennomsnittet, og falle mellom 2 og 3 standardavvik fra gjennomsnittet. Statistisk sett indikerer det 2,28 prosent sannsynlighet for å oppnå anslått 5 prosent avkastning. At 2,28 prosent sannsynlighet er utledet ved å trekke 95,44 prosent fra 100 prosent, og forskjellen (4,56 prosent) blir deretter delt på to på grunn av de like store sannsynlighetene på hver side (negativ og positiv) av den symmetriske linjen i normalfordelingsgrafen . Uansett ville en daglig gevinst på 5 prosent på Apples aksjer ikke vært vanlig.

En annen måte å tolke normalfordelingen på er å si at sannsynligheten for at Apples avkastning (i et område på -1,83 prosent og 1,99 prosent) faller innenfor -1 og 1 standardavvik fra gjennomsnittet er 68,26 prosent. Sannsynligheten for et standardavvik mellom -2 og 2 er 95,44 prosent, og mellom -3 og 3 er den 99,74 prosent.

## Hvordan er standardavvik relatert til volatilitet?

Standardavvik kan vise hvordan en avkastning forholder seg til gjennomsnittet. Et høyt standardavvik vil indikere høy volatilitet, og en avkastning som er større enn standardavviksområdet antyder at det er en outlier. En serie opp og ned svingninger utenfor dette området i en periode vil også indikere høy volatilitet.

## Høydepunkter

– Det beregnes som kvadratroten av variansen.

– Standardavvik, i finans, brukes ofte som et mål på en relativ risiko ved en eiendel.

- Standardavvik måler spredningen av et datasett i forhold til gjennomsnittet.

– En flyktig aksje har et høyt standardavvik, mens avviket til en stabil blue-chip aksje vanligvis er ganske lavt.

– Som en ulempe beregner standardavviket all usikkerhet som risiko, selv når det er i investorens favør—som avkastning over gjennomsnittet.

## FAQ

### Hva betyr et høyt standardavvik?

Et stort standardavvik indikerer at det er mye variasjon i de observerte dataene rundt gjennomsnittet. Dette indikerer at dataene som er observert er ganske spredt. Et lite eller lavt standardavvik vil i stedet indikere at mye av dataene som er observert er gruppert tett rundt gjennomsnittet.

### Hvorfor er standardavvik viktig?

Standardavvik er viktig fordi det kan hjelpe brukere med å vurdere risiko. Vurder et investeringsalternativ med en gjennomsnittlig årlig avkastning på 10 % per år. Dette gjennomsnittet ble imidlertid utledet fra de siste tre års avkastning på 50 %, -15 % og -5 %. Ved å beregne standardavviket og forstå din lave sannsynlighet for faktisk gjennomsnittlig 10 % i et gitt år, er du bedre rustet til å ta informerte beslutninger og gjenkjenne underliggende risiko.

### Hva forteller standardavvik deg?

Standardavvik beskriver hvor spredt et sett med data er. Den sammenligner hvert datapunkt med gjennomsnittet av alle datapunkter, og standardavviket returnerer en beregnet verdi som beskriver om datapunktene er i umiddelbar nærhet eller om de er spredt utover. I en normalfordeling forteller standardavviket hvor langt verdiene er fra gjennomsnittet.

### Hvordan beregner du standardavvik?

Standardavvik beregnes som kvadratroten av variansen. Alternativt beregnes det ved å finne gjennomsnittet av et datasett, finne forskjellen mellom hvert datapunkt og gjennomsnittet, kvadrere forskjellene, legge dem sammen, dividere med antall punkter i datasettet minus 1, og finne kvadratet rot.

### Hvordan finner du standardavviket raskt?

Hvis du ser på fordelingen av noen observerte data visuelt, kan du se om formen er relativt tynn vs. fett. Fetere fordelinger har større standardavvik. Alternativt har Excel innebygd standardavviksfunksjoner avhengig av datasettet.

