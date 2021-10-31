---
keywords: Crypto
title: BEP-95
description: BEP-95. BEP-95 er et Binance Evolution-forslag som introduserer en sanntidsbrenningsmekanisme til Binance Smart Chain. Det gjør BNB tokenomics mer dynamisk og desentralisert.
---

# BEP-95
BEP-95 er et Binance Evolution-forslag som introduserer en sanntidsbrenningsmekanisme til Binance Smart Chain. Det har blitt introdusert for å gjøre BNBs tokenomics enda mer dynamisk og ytterligere desentralisere nettverket.

Med BEP-95 vil nettverket brenne et fast forhold mellom hver blokks gassavgifter som validatorer samler inn. Det nøyaktige forholdet vil bli bestemt via BSCs styringsmekanismer. Forbrenningene vil finne sted selv etter at BSC har nådd målet sitt på 100 millioner BNB. Ved å redusere tilbudet av BNB legges det et press oppover på myntens pris. BEP kan også redusere antallet BNB-delegatorer og validatorer som mottas. Med oppadgående prispress kan imidlertid fiat-verdien også øke, og kompensere for eventuell reduksjon i mynter.

For å implementere dette teknisk, samler nettverket inn gassavgiftene til hver blokk og deler mellom to smarte kontrakter:

**en. Systembelønningskontrakt.** 1/16 av gassavgiftene vil gå inn i systembelønningskontrakten til den når maksimalt 100 BNB. Disse myntene vil bli brukt som pakkesubsidier på tvers av kjeder.

**2. ValidatorSet-kontrakt.** Alle andre gassavgifter vil gå inn i ValidatorSet-kontrakten og deles daglig med delegatorer og validatorer via Binance Chain.

For å utføre en brenning har ValidatorSet-kontrakten en burnRatio-variabel. Etter å ha fullført hver blokk, vil en validator signere en transaksjon som overfører gassavgiftene til de smarte kontraktene. Innskuddsfunksjonen inneholder brennende logikk som utløser den enkle formelen: burnRatio * gasFee. Denne summen vil da bli overført til brenneadressen. Brennforholdet vil i utgangspunktet bli satt til 10 %.

BSC Validatorer vil kunne stemme via forslag om å endre burnRatio-beløpet. Denne styringsmekanismen forekommer på Binance Chain, og ethvert fellesskapsmedlem kan sende inn et forslag til vurdering med et minimumsinnskudd på 2000 BNB. Alle BNB satset bak et forslag og i en avstemning blir returnert etter at vedtak er tatt. Quorum nås ved 50 %, og endringen vil bli implementert via tverrkjedekommunikasjon umiddelbart.

