---
keywords: Crypto
title: Oracle
description: Oracle. En datakilde eller feed fra en tredjepart som brukes til å bestemme utfall for smarte kontrakter.
---

# Oracle
Et orakel kan defineres på flere forskjellige måter, i henhold til konteksten. Innenfor blokkjedesammenheng er et orakel i utgangspunktet en datakilde som brukes som en bro mellom smarte kontrakter og andre eksterne kilder.

Mer spesifikt er et orakel en agent som ikke bare kommuniserer med eksterne datakilder, men også verifiserer og autentiserer at dataene som oppgis er nøyaktige. Dermed er orakler ansvarlige for å gi viktig og pålitelig informasjon til smarte kontrakter, som igjen utfører visse oppgaver.

Betydningen av orakler er avhengig av det faktum at smarte blokkjedekontrakter bare er i stand til å få tilgang til dataene som finnes i deres eget digitale nettverk. Derfor trengs orakler som et kommunikasjonsinstrument som "oversetter" hendelser fra den virkelige verden (ikke-deterministiske data) til digitale verdier som gjenkjennes av smarte kontrakter (deterministiske data).

Blockchain-orakler kan klassifiseres i henhold til deres brukstilfelle. De vanligste typene er:

- Hardware Oracles: Integrerer med fysiske systemer og teknologier, og gir virkelige data for smarte kontrakter. For eksempel kan maskinvareorakler kommunisere med RFID-sensorer som brukes i ulike bransjer (bil, farmasøytisk, forsyningskjede, etc.)

- Software Oracles: mest brukt; hente online data fra eksterne programmer og web-APIer – som markedspriser, flystatus og værdata.

- Konsensus-orakler: slags desentraliserte orakler som samler inn store mengder data fra et bestemt antall andre orakler, etter spesifikke metoder for å bestemme gyldigheten og nøyaktigheten til data som samles inn. Konsensus-orakler brukes i prediksjonsmarkeder, som Augur og Gnosis.

- Inbound Oracles: overfører eksterne data til smarte kontrakter eller programvareorakler. Kan konfigureres som et sett med "hvis"-retningslinjer (f.eks. "hvis en eiendel treffer en bestemt pris, legg inn en kjøpsordre").

- Outbound Oracles: overfører smarte kontraktsdata til eksterne systemer, noe som gjør det mulig for smarte kontrakter å kommunisere med ikke-blokkjedekilder.

Generelt består et blockchain-orakel av en tredjeparts datakilde som er avhengig av ekstern tillatelse for å fungere ordentlig, noe som betyr at de vanligvis er et verktøy levert av sentraliserte enheter. Derfor ender de fleste orakler opp med å ofre de desentraliserte egenskapene til de smarte kontraktene.

### Oracle-problemet

Avhengig av dataene levert av de sentraliserte oraklene, vil smarte kontrakter utføre forskjellige funksjoner, noe som betyr at orakler har enorm makt over smarte kontrakter. Dette er kjent som Oracle Problem, som oppstår som en tillitskonflikt som sentraliserte tredjeparts orakler bringer til tillitsløse smarte kontrakter og blokkjedesystemer.

Selv om desentraliserte orakler, som konsensus-oraklene, kan presentere en mulig løsning, er det fortsatt mange utfordringer som må overvinnes, siden desentraliserte orakelnettverk er ganske vanskelige å implementere på en sikker, funksjonell og tillitsløs måte.

