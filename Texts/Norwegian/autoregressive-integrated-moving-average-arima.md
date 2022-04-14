---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: Autoregressivt integrert glidende gjennomsnitt (ARIMA)
description: Et autoregressivt integrert glidende gjennomsnitt (ARIMA) er en statistisk analysemodell som utnytter tidsseriedata for å forutsi fremtidige trender.
---

# Autoregressivt integrert glidende gjennomsnitt (ARIMA)
## Hva er et autoregressivt integrert glidende gjennomsnitt (ARIMA)?

Et autoregressivt integrert glidende gjennomsnitt, eller ARIMA, er en statistisk analysemodell som bruker [tidsseriedata for](/timeseries) å enten forstå datasettet bedre eller forutsi fremtidige trender.

En statistisk modell er autoregressiv hvis den forutsier fremtidige verdier basert på tidligere verdier. For eksempel kan en ARIMA-modell søke å forutsi en aksjes fremtidige priser basert på tidligere resultater eller prognose et selskaps inntjening basert på tidligere perioder.

## Forstå Autoregressive Integrated Moving Average (ARIMA)

En autoregressiv integrert glidende gjennomsnittsmodell er en form for [regresjonsanalyse](/regression) som måler styrken til en avhengig variabel i forhold til andre skiftende variabler. Modellens mål er å forutsi fremtidige verdipapir- eller finansmarkedsbevegelser ved å undersøke forskjellene mellom verdier i serien i stedet for gjennom faktiske verdier.

En ARIMA-modell kan forstås ved å skissere hver av komponentene som følger:

- [Autoregresjon (AR)](/autoregressive) : refererer til en modell som viser en skiftende variabel som regresserer på sine egne forsinket eller tidligere verdier.

- **Integrert (I):** representerer forskjellen mellom råobservasjoner for å tillate at tidsserien blir stasjonær (dvs. dataverdier erstattes av forskjellen mellom dataverdiene og de forrige verdiene).

- [Glidende gjennomsnitt (MA)](/movingaverage) : inkorporerer avhengigheten mellom en observasjon og en gjenværende feil fra en glidende gjennomsnittsmodell brukt på forsinkede observasjoner.

## ARIMA-parametre

Hver komponent i ARIMA fungerer som en parameter med standardnotasjon. For ARIMA-modeller vil en standardnotasjon være ARIMA med p, d og q, der heltallsverdier erstatter parameterne for å indikere typen ARIMA-modell som brukes. Parametrene kan defineres som:

- **p**: antall forsinkelsesobservasjoner i modellen; også kjent som lagrekkefølgen.

- **d**: antall ganger råobservasjonene er forskjellig; også kjent som graden av forskjell.

- q: størrelsen på det glidende gjennomsnittsvinduet; også kjent som rekkefølgen til det glidende gjennomsnittet.

I en [lineær regresjonsmodell](/nonlinear-regression) er for eksempel antall og type ledd inkludert. En 0-verdi, som kan brukes som en parameter, vil bety at en bestemt komponent ikke skal brukes i modellen. På denne måten kan ARIMA-modellen konstrueres for å utføre funksjonen til en ARMA-modell, eller til og med enkle AR-, I- eller MA-modeller.

> Fordi ARIMA-modeller er kompliserte og fungerer best på veldig store datasett, brukes datamaskinalgoritmer og maskinlæringsteknikker for å beregne dem.

>

## Autoregressiv integrert bevegelig gjennomsnitt (ARIMA) og stasjonaritet

I en autoregressiv integrert glidende gjennomsnittsmodell er dataene forskjellig for å gjøre dem stasjonære. En modell som viser stasjonaritet er en som viser at dataene er konstante over tid. De fleste økonomiske data og markedsdata viser trender, så hensikten med å skille er å fjerne eventuelle trender eller sesongmessige strukturer.

[Sesongvariasjoner](/seasonality),. eller når data viser regelmessige og forutsigbare mønstre som gjentar seg over et kalenderår, kan påvirke regresjonsmodellen negativt. Hvis en trend dukker opp og stasjonaritet ikke er tydelig, kan mange av beregningene gjennom hele prosessen ikke gjøres med stor effektivitet.

> Et engangssjokk vil påvirke påfølgende verdier av en ARIMA-modell uendelig inn i fremtiden. Derfor lever arven fra finanskrisen videre i dagens autoregressive modeller.

>

## Spesielle hensyn

ARIMA-modeller er basert på antakelsen om at tidligere verdier har en viss gjenværende effekt på nåværende eller fremtidige verdier. For eksempel vil en investor som bruker en ARIMA-modell for å forutsi aksjekurser anta at nye kjøpere og selgere av den aksjen er påvirket av nylige markedstransaksjoner når de bestemmer seg for hvor mye de skal tilby eller akseptere for verdipapiret.

Selv om denne antagelsen vil holde under mange omstendigheter, er dette ikke alltid tilfelle. For eksempel, i årene før finanskrisen i 2008, var de fleste investorer ikke klar over risikoen som utgjøres av de store porteføljene av [pantesikrede verdipapirer](/mbs) (MBS) holdt av mange finansforetak.

I disse tider ville en investor som bruker en autoregressiv modell for å forutsi utviklingen til amerikanske finansaksjer ha hatt god grunn til å forutsi en pågående trend med stabile eller stigende aksjekurser i den sektoren. Men så snart det ble offentlig kjent at mange finansinstitusjoner var i fare for snarlig kollaps, ble investorene plutselig mindre opptatt av disse aksjenes siste kurs og langt mer opptatt av deres underliggende risikoeksponering. Derfor revalueres markedet raskt finansielle aksjer til et mye lavere nivå, et trekk som ville ha fullstendig forvirret en autoregressiv modell.

## Ofte stilte spørsmål

### Hva brukes ARIMA til?

ARIMA er en metode for å forutsi eller forutsi fremtidige utfall basert på en historisk tidsserie. Den er basert på det statistiske konseptet seriell korrelasjon, der tidligere datapunkter påvirker fremtidige datapunkter.

### Hva er forskjellene mellom autoregressive og glidende gjennomsnittsmodeller?

ARIMA kombinerer autoregressive funksjoner med de for glidende gjennomsnitt. En AR(1) autoregressiv prosess, for eksempel, er en der gjeldende verdi er basert på den umiddelbart foregående verdien, mens en AR(2) prosess er en der den nåværende verdien er basert på de to foregående verdiene. Et glidende gjennomsnitt er en beregning som brukes til å analysere datapunkter ved å lage en serie gjennomsnitt av forskjellige delmengder av hele datasettet for å jevne ut påvirkningen fra uteliggere. Som et resultat av denne kombinasjonen av teknikker kan ARIMA-modeller ta hensyn til trender, sykluser, sesongvariasjoner og andre ikke-statiske typer data når de lager prognoser.

### Hvordan fungerer ARIMA-prognoser?

ARIMA-prognose oppnås ved å plugge inn tidsseriedata for variabelen av interesse. Statistisk programvare vil identifisere riktig antall etterslep eller mengden av forskjeller som skal brukes på dataene og sjekke for stasjonaritet. Den vil da gi ut resultatene, som ofte tolkes på samme måte som en multippel lineær regresjonsmodell.

##Høydepunkter

- Autoregressive integrerte glidende gjennomsnitt (ARIMA) modeller forutsier fremtidige verdier basert på tidligere verdier.

- ARIMA bruker forsinket glidende gjennomsnitt for å jevne ut tidsseriedata.

– De er mye brukt i teknisk analyse for å forutsi fremtidige verdipapirpriser.

– Autoregressive modeller antar implisitt at fremtiden vil ligne fortiden.

– Derfor kan de vise seg unøyaktige under visse markedsforhold, som finanskriser eller perioder med raske teknologiske endringer.

