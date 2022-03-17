---
keywords: Crypto
title: Oracle
description: Oracle. En datakilde eller feed fra en tredjepart, der bruges til at bestemme resultater for smarte kontrakter.
---

# Oracle
Et orakel kan defineres på flere forskellige måder afhængigt af konteksten. Indenfor blockchain-konteksten er et orakel dybest set en datakilde, der bruges som bro mellem smarte kontrakter og andre eksterne kilder.

Mere specifikt er et orakel en agent, der ikke kun kommunikerer med eksterne datakilder, men også verificerer og autentificerer, at de data, der leveres, er nøjagtige. Orakler er således ansvarlige for at levere vital og pålidelig information til smarte kontrakter, som igen udfører visse opgaver.

Betydningen af orakler er afhængig af, at blockchain smarte kontrakter kun er i stand til at få adgang til de data, der er indeholdt i deres eget digitale netværk. Derfor er der brug for orakler som et kommunikationsinstrument, der "oversætter" begivenheder i den virkelige verden (ikke-deterministiske data) til digitale værdier, der genkendes af smarte kontrakter (deterministiske data).

Blockchain-orakler kan klassificeres i henhold til deres anvendelsestilfælde. De mest almindelige typer er:

- Hardware Oracles: Integrerer med fysiske systemer og teknologier og leverer data fra den virkelige verden til smarte kontrakter. For eksempel kan hardware-orakler kommunikere med RFID-sensorer, der bruges i forskellige industrier (biler, medicinalvarer, forsyningskæder osv.)

- Software Oracles: mest almindeligt brugt; hente online data fra eksterne programmer og web-API'er - såsom markedspriser, flystatus og vejrdata.

- Konsensus-orakler: en slags decentraliserede orakler, der indsamler store mængder data fra et bestemt antal andre orakler, efter specifikke metoder til at bestemme gyldigheden og nøjagtigheden af de indsamlede data. Konsensus-orakler bliver brugt i forudsigelsesmarkedsplatforme, såsom Augur og Gnosis.

- Indgående Oracles: overfører eksterne data til smarte kontrakter eller software-orakler. Kan konfigureres som et sæt "hvis" retningslinjer (f.eks. "hvis et aktiv rammer en bestemt pris, afgiv en købsordre").

- Outbound Oracles: overfører smarte kontraktdata til eksterne systemer, hvilket gør det muligt for smarte kontrakter at kommunikere med ikke-blockchain-kilder.

Generelt består et blockchain-orakel af en tredjeparts datakilde, der er afhængig af ekstern tilladelse til at fungere korrekt, hvilket betyder, at de normalt er et værktøj, der leveres af centraliserede enheder. Derfor ender de fleste orakler med at ofre de decentrale egenskaber ved de smarte kontrakter.

### Oracle-problemet

Afhængigt af de data, der leveres af de centraliserede orakler, vil smarte kontrakter udføre forskellige funktioner, hvilket betyder, at orakler har enorm magt over smarte kontrakter. Dette er kendt som Oracle-problemet, som opstår som en tillidskonflikt, som centraliserede tredjeparts-orakler bringer tillidsløse smarte kontrakter og blockchain-systemer.

Selvom decentraliserede orakler, såsom konsensus-oraklerne, kan være en mulig løsning, er der stadig mange udfordringer, der skal overvindes, eftersom decentraliserede orakelnetværk er ret vanskelige at implementere på en sikker, funktionel og tillidsfri måde.

