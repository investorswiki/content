---
keywords: Investing,Cryptocurrency,Blockchain
title: Hyperledger stof
description: Hyperledger Fabric er en platform til at bygge forskellige blockchain-baserede produkter, løsninger og applikationer til forretningsbrug.
---

# Hyperledger stof
## Hvad er Hyperledger-stof?

Hyperledger Fabric er en modulær [blockchain](/blockchain) -ramme, der fungerer som grundlag for udvikling af blockchain-baserede produkter, løsninger og applikationer ved hjælp af plug-and-play-komponenter, der er beregnet til brug i private virksomheder.

Hyperledger Fabric blev initieret af Digital Asset og IBM og er nu opstået som et samarbejde på tværs af brancher, som i øjeblikket hostes af Linux Foundation. Blandt de adskillige Hyperledger-projekter var Fabric det første, der forlod "inkubationsstadiet" og opnåede det "aktive" stadium i marts 2017.

## Sådan fungerer Hyperledger-stof

Traditionelle blockchain-netværk kan ikke understøtte private transaktioner og fortrolige kontrakter, der er af yderste vigtighed for virksomheder. Hyperledger Fabric blev designet som svar på dette som et modulært, skalerbart og sikkert grundlag for at tilbyde industrielle blockchain-løsninger.

Hyperledger Fabric er open source-motoren til blockchain og tager sig af de vigtigste funktioner til evaluering og brug af blockchain til forretningsbrug.

Inden for private industrielle netværk er en deltagers verificerbare identitet et primært krav. Hyperledger Fabric understøtter medlemskaber baseret på tilladelse; alle netværksdeltagere skal have kendte identiteter. Mange erhvervssektorer, såsom sundhedspleje og finans, er bundet af databeskyttelsesforordninger, der påbyder at vedligeholde data om de forskellige deltagere og deres respektive adgang til forskellige datapunkter. Fabric understøtter et sådant tilladelsesbaseret medlemskab.

### Modulær arkitektur

Den modulære arkitektur i Hyperledger Fabric adskiller transaktionsbehandlings-workflowet i tre forskellige faser: [smarte kontrakter](/smart-contracts) kaldet kædekode, der omfatter den distribuerede logiske behandling og aftale af systemet, transaktionsbestilling og transaktionsvalidering og -forpligtelse. Denne adskillelse giver flere fordele:

- Et reduceret antal tillidsniveauer og verifikation, der holder netværket og behandlingen fri for rod

- Forbedret netværksskalerbarhed

- Bedre generel præstation

Derudover tillader Hyperledger Fabrics understøttelse af plug-and-play af forskellige komponenter let genbrug af eksisterende funktioner og færdiglavet integration af forskellige moduler. For eksempel, hvis der allerede findes en funktion, der verificerer deltagerens identitet, skal et netværk på virksomhedsniveau blot tilslutte og genbruge dette eksisterende modul i stedet for at bygge den samme funktion fra bunden.

Deltagerne på netværket har tre forskellige roller:

- Endosser

- Kommitter

-Konsenter

I en nøddeskal forelægges transaktionsforslaget til endosser-peeren i henhold til den foruddefinerede godkendelsespolitik om antallet af endossører, der kræves. Efter tilstrækkelige påtegninger fra endossør(erne), leveres en batch eller blok af transaktioner til committeren(erne). Committers validerer, at godkendelsespolitikken blev fulgt, og at der ikke er nogen modstridende transaktioner. Når begge kontroller er foretaget, er transaktionerne forpligtet til hovedbogen.

<!--6376536357DF4ADC77E5CAB266DCF459-->

Billedkilde: IBM

Da kun bekræftende instruktioner – såsom signaturer og læse/skrivesæt – sendes på tværs af netværket, forbedres netværkets skalerbarhed og ydeevne. Kun endorsers og committers har adgang til transaktionen, og sikkerheden er forbedret med et færre antal deltagere, der har adgang til nøgledatapunkter.

## Eksempel på Hyperledger Fabric

Antag, at der er en producent, der ønsker at sende chokolade til en specifik forhandler eller marked af detailhandlere (dvs. alle amerikanske detailhandlere) til en bestemt pris, men som ikke ønsker at afsløre denne pris på andre markeder (dvs. kinesiske detailhandlere).

Da bevægelsen af produktet kan involvere andre parter, såsom toldvæsen, et rederi og en finansieringsbank, kan den private pris blive afsløret for alle involverede parter, hvis en grundlæggende version af blockchain-teknologi bruges til at understøtte denne transaktion.

Hyperledger Fabric løser dette problem ved at holde private transaktioner private på netværket; kun deltagere, der har brug for at vide, er klar over de nødvendige detaljer. Dataopdeling på blockchain tillader, at specifikke datapunkter kun er tilgængelige for de parter, der har brug for at vide det.

## Kritik af Hyperledger-stof

Højvandsmærket for krypto-entusiasme brød i 2018 efter kollapset af prisen på bitcoin (som nåede sit højdepunkt den 17. december 2017). Overoptimistiske påstande om værdien af den nye teknologi blev erstattet med skepsis, og relaterede teknologier, herunder Hyperledger, led også under denne skepsis.

### Hyperledger Fabrics konkurrenter

Hyperledger Fabric konkurrerer med andre Hyperledger-projekter som Iroha, Indy og Sawtooth. Den konkurrerer også med R3's Corda, som også er en privat, tilladelsesbaseret DLT.

Blockchain-servicefirmaet Chainstack offentliggjorde et papir i januar 2020 , der viser, at udviklingen i Corda har været historisk højere end udviklingen i Fabric, selvom Fabric-udviklingen passerede Cordas i 3. kvartal 2019, da Fabric skiftede til GitHub.

Chainstack-rapporten viser, at mens der er tre gange så mange udviklere, der arbejder på Fabric, har Corda-udviklere ydet mere end to gange så mange kodebidrag, og Fabric-udviklere pusher langt mindre kode pr. udvikler end Cordas udviklere.

### Hyperledger-stof er ikke blockchain og er ikke effektivt

Flere kritikpunkter af Hyperledger Fabric peger på, at en tilladelsesbaseret, privat blockchain med Hyperledger Fabrics funktioner ikke er en blockchain, og nuværende ikke-blockchain-teknologier er langt billigere og leverer den samme mængde sikkerhed. Cointelegraphs Stuart Popejoy formulerede sagen sådan:

>

> Fabrics arkitektur er langt mere kompleks end nogen blockchain-platform, samtidig med at den er mindre sikker mod manipulation og angreb. Man skulle tro, at en "privat" blockchain i det mindste ville tilbyde skalerbarhed og ydeevne, men Fabric fejler også her. Enkelt sagt vil piloter bygget på Fabric stå over for en kompleks og usikker implementering, som ikke vil være i stand til at skalere med deres virksomheder .

>

Hyperledger Fabric er også blevet kritiseret for manglende robusthed. Et team af forskere fra Sorbonne i Paris og CSIRO - Data61, Australiens nationale videnskabsagentur, fandt ud af, at betydelige netværksforsinkelser reducerede pålideligheden af Fabric: "[Ved at forsinke blokudbredelsen viste vi, at Hyperledger Fabric ikke giver tilstrækkelige konsistensgarantier skal implementeres i kritiske miljøer. "

## Hyperledger Fabric 2.0 udgivet i januar 2020

I januar 2020 blev Hyperledger Fabric 2.0 udgivet for at imødegå nogle af de eksisterende kritikpunkter. Ifølge Ron Miller hos Techcrunch, "De største opdateringer involverer at tvinge enighed mellem parterne, før nogen ny data kan tilføjes til hovedbogen, kendt som decentraliseret styring af de smarte kontrakter."

Selvom opdateringen ikke er en markant ændring i enkelheden eller anvendeligheden af Fabric, viser den, at der fortsat sker fremskridt i kryptovalutaindustrien ud over kryptomanien, der opstod i 2018. I løbet af de næste fem til ti år er det forventede, at enterprise blockchain utvivlsomt vil finde sin rette brug.

##Højdepunkter

- Hyperledger er en virksomhedskvalitet, open source distribueret ledger-ramme, lanceret af Linux Foundation i december 2015.

- Fordi Hyperledger Fabric er privat og kræver adgangstilladelse, kan virksomheder adskille information (som priser), plus transaktioner kan fremskyndes, fordi antallet af noder på netværket reduceres.

- Fabric 2.0 blev udgivet i januar 2020. Hovedfunktionerne i denne version er hurtigere transaktioner, opdateret smart kontraktteknologi og strømlinet datadeling.

- Fabric er en meget modulær, decentraliseret Ledger Technology-platform (DLT), der er designet af IBM til industriel virksomhedsbrug.

