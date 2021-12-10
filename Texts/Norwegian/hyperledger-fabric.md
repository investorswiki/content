---
keywords: Investing,Cryptocurrency,Blockchain
title: Hyperledger-stoff
description: Hyperledger Fabric er en plattform for å bygge ulike blokkjedebaserte produkter, løsninger og applikasjoner for forretningsbruk.
---

# Hyperledger-stoff
## Hva er Hyperledger-stoff?

Hyperledger Fabric er et modulært [blockchain -](/blockchain) rammeverk som fungerer som et grunnlag for å utvikle blokkjedebaserte produkter, løsninger og applikasjoner ved bruk av plug-and-play-komponenter som er rettet mot bruk i private virksomheter.

Hyperledger Fabric ble initiert av Digital Asset og IBM og har nå dukket opp som et samarbeidsprosjekt på tvers av industri, som for tiden er vert for Linux Foundation. Blant de flere Hyperledger-prosjektene var Fabric det første som gikk ut av "inkubasjonsstadiet" og oppnådde det "aktive" stadiet i mars 2017.

## Hvordan Hyperledger-stoff fungerer

Tradisjonelle blokkjedenettverk kan ikke støtte private transaksjoner og konfidensielle kontrakter som er av største betydning for bedrifter. Hyperledger Fabric ble designet som svar på dette som et modulært, skalerbart og sikkert grunnlag for å tilby industrielle blokkjedeløsninger.

Hyperledger Fabric er åpen kildekode-motoren for blokkjede og tar seg av de viktigste funksjonene for å evaluere og bruke blokkjede for forretningsbruk.

Innenfor private industrielle nettverk er verifiserbar identitet til en deltaker et primært krav. Hyperledger Fabric støtter medlemskap basert på tillatelse; alle nettverksdeltakere må ha kjente identiteter. Mange næringssektorer, som helsevesen og finans, er bundet av databeskyttelsesforskrifter som pålegger å vedlikeholde data om de ulike deltakerne og deres respektive tilgang til ulike datapunkter. Fabric støtter slik tillatelsesbasert medlemskap.

### Modulær arkitektur

Den modulære arkitekturen til Hyperledger Fabric deler arbeidsflyten for transaksjonsbehandling i tre forskjellige stadier: [smarte kontrakter](/smart-contracts) kalt kjedekode som omfatter distribuert logikkbehandling og avtale av systemet, transaksjonsbestilling og transaksjonsvalidering og forpliktelse. Denne segregeringen gir flere fordeler:

- Et redusert antall tillitsnivåer og verifisering som holder nettverket og behandlingen ryddig

- Forbedret nettverksskalerbarhet

- Bedre ytelse totalt sett

I tillegg tillater Hyperledger Fabrics støtte for plug-and-play av ulike komponenter enkel gjenbruk av eksisterende funksjoner og ferdig integrasjon av ulike moduler. For eksempel, hvis en funksjon allerede eksisterer som bekrefter deltakerens identitet, må et nettverk på bedriftsnivå ganske enkelt koble til og gjenbruke denne eksisterende modulen i stedet for å bygge den samme funksjonen fra bunnen av.

Deltakerne i nettverket har tre distinkte roller:

- Endosser

- Kommitter

- Konsenter

I et nøtteskall sendes transaksjonsforslaget til endosser-kollegaen i henhold til den forhåndsdefinerte godkjenningspolicyen om antall påkrevde endorsers. Etter tilstrekkelige påtegninger fra endossøren(e), leveres en batch eller blokk med transaksjoner til committeren(e). Kommittere bekrefter at godkjenningspolicyen ble fulgt og at det ikke er noen motstridende transaksjoner. Når begge kontrollene er utført, blir transaksjonene forpliktet til reskontroen.

<!--6376536357DF4ADC77E5CAB266DCF459-->

Bildekilde: IBM

Siden bare bekreftende instruksjoner – som signaturer og lese-/skrivesett – sendes over nettverket, forbedres skalerbarheten og ytelsen til nettverket. Kun påtegnere og formidlere har tilgang til transaksjonen, og sikkerheten er forbedret med et færre antall deltakere som har tilgang til nøkkeldatapunkter.

## Eksempel på Hyperledger Fabric

Anta at det er en produsent som ønsker å sende sjokolade til en spesifikk forhandler eller marked av forhandlere (dvs. alle amerikanske forhandlere) til en bestemt pris, men som ikke ønsker å avsløre den prisen i andre markeder (dvs. kinesiske forhandlere).

Siden bevegelsen av produktet kan involvere andre parter, som tollvesenet, et rederi og en finansieringsbank, kan den private prisen bli avslørt for alle involverte parter hvis en grunnleggende versjon av blokkjedeteknologi brukes til å støtte denne transaksjonen.

Hyperledger Fabric løser dette problemet ved å holde private transaksjoner private på nettverket; kun deltakere som trenger å vite er klar over de nødvendige detaljene. Datapartisjonering på blokkjeden gjør at spesifikke datapunkter bare er tilgjengelige for partene som trenger å vite det.

## Kritikk av Hyperledger-stoff

Høyvannsmerket for krypto-entusiasme brøt i 2018 etter kollapsen av prisen på bitcoin (som nådde toppen 17. desember 2017). Overoptimistiske påstander om verdien av den nye teknologien ble erstattet med skepsis, og relaterte teknologier, inkludert Hyperledger, led også av denne skepsisen.

### Hyperledger Fabrics konkurrenter

Hyperledger Fabric konkurrerer med andre Hyperledger-prosjekter som Iroha, Indy og Sawtooth. Den konkurrerer også med R3s Corda, som også er en privat, tillatelsesbasert DLT.

Blockchain-servicefirmaet Chainstack publiserte en artikkel i januar 2020 som viser at utviklingen i Corda har vært historisk høyere enn utviklingen i Fabric, selv om Fabric-utviklingen passerte Cordas i 3. kvartal 2019 da Fabric byttet til GitHub.

Chainstack-rapporten viser at mens det er tre ganger så mange utviklere som jobber med Fabric, ga Corda-utviklere mer enn to ganger så mange kodebidrag, og Fabric-utviklere pusher langt mindre kode per utvikler enn Cordas utviklere.

### Hyperledger-stoff er ikke blokkjede og er ikke effektivt

Flere kritikker av Hyperledger Fabric påpeker at en tillatelsesbasert, privat blokkjede med Hyperledger Fabrics funksjoner ikke er en blokkjede, og dagens ikke-blokkjedeteknologier er langt rimeligere og gir samme sikkerhet. Cointelegraphs Stuart Popejoy sa saken slik:

>

> Fabrics arkitektur er langt mer kompleks enn noen blokkjedeplattform, samtidig som den er mindre sikker mot tukling og angrep. Du skulle tro at en "privat" blokkjede i det minste ville tilby skalerbarhet og ytelse, men Fabric feiler også her. Enkelt sagt vil piloter bygget på Fabric møte en kompleks og usikker distribusjon som ikke vil kunne skaleres med virksomhetene deres .

>

Hyperledger Fabric har også blitt kritisert for manglende spenst. Et team av forskere fra Sorbonne i Paris og CSIRO - Data61, Australias nasjonale vitenskapsbyrå, fant at betydelige nettverksforsinkelser reduserte påliteligheten til Fabric: "[Ved å forsinke blokkutbredelse, viste vi at Hyperledger Fabric ikke gir tilstrekkelige konsistensgarantier skal distribueres i kritiske miljøer. "

## Hyperledger Fabric 2.0 utgitt i januar 2020

I januar 2020 ble Hyperledger Fabric 2.0 utgitt for å ta opp noen av de eksisterende kritikkene. I følge Ron Miller ved Techcrunch, "De største oppdateringene innebærer å tvinge fram enighet mellom partene før noen nye data kan legges til hovedboken, kjent som desentralisert styring av smarte kontrakter."

Selv om oppdateringen ikke er en endring i enkelheten eller anvendeligheten til Fabric, viser den at det fortsetter å gjøres fremskritt i kryptovalutaindustrien utover kryptomanien som skjedde i 2018. I løpet av de neste fem til ti årene er det forventet at enterprise blockchain utvilsomt vil finne riktig bruk.

## Høydepunkter

- Hyperledger er et distribuert hovedbok-rammeverk i bedriftsklasse lansert av Linux Foundation i desember 2015.

– Fordi Hyperledger Fabric er privat og krever tillatelse for å få tilgang, kan bedrifter separere informasjon (som priser), pluss at transaksjoner kan fremskyndes fordi antall noder på nettverket reduseres.

– Fabric 2.0 ble utgitt i januar 2020. Hovedtrekkene i denne versjonen er raskere transaksjoner, oppdatert smart kontraktsteknologi og strømlinjeformet datadeling.

- Fabric er en svært modulær, desentralisert Ledger Technology (DLT)-plattform som ble designet av IBM for industriell bruk.

