---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Crypto,Strategy and Education
title: Hashed Timelock Contract (HTLC)
description: Hashed TimeLock-kontrakt (HTLC). Refererer til en spesiell funksjon som brukes til å lage smarte kontrakter som er i stand til å endre betalingskanaler.
---

# Hashed Timelock Contract (HTLC)
Begrepet Hashed TimeLock Contract (HTLC) refererer til en spesiell funksjon som brukes til å lage [smarte kontrakter](/smart-contract) som er i stand til å endre betalingskanaler. Teknisk sett muliggjør HTLC-funksjonen implementering av tidsbestemte transaksjoner mellom to brukere. I praksis må mottakeren av en HTLC-transaksjon bekrefte betalingen ved å sende inn et kryptografisk bevis innen en spesifisert tidsramme (antall blokker). Hvis mottakeren mister eller unnlater å kreve betalingen, vil midlene bli returnert til den opprinnelige avsenderen.

HTLC-funksjonen brukes i både toveis og rutede betalingskanaler for å tillate sikre overføringer av midler over ulike kanaler, uten å kreve tillit til noen av mellomleddene.

Det er to nøkkelelementer som skiller HTLC fra standard kryptovalutatransaksjoner, som er:

- Hashlock: en funksjon som begrenser bruken av midler inntil en viss del av data blir offentliggjort (som et kryptografisk bevis). Slike bevis kan også bli referert til som forhåndsbildet av hashlocken. Forbildet er ganske enkelt informasjonen som brukes til å generere hashlocken, og for senere å låse opp midlene.

- Timelock: er en funksjon som begrenser bruken av midler til et bestemt tidspunkt (eller blokkhøyde) i fremtiden. Det kan oppnås i Bitcoin, for eksempel ved å bruke funksjoner som CheckLockTimeVerify eller CheckSequenceVerify.

Bitcoin Lightning Network er blant de mest populære brukstilfellene av hashed timelocked-kontrakter. Ved å implementere HTLC i betalingskanaler, kan midler transaksjoneres fra bruker til bruker gjennom sammenkoblede betalingskanaler, uten at det krever noe tillitsnivå. Denne prosessen er kjent som nettverksruting. Det lar Alice utveksle midler med Carol selv om de ikke er direkte koblet gjennom en betalingskanal. HTLC gjør det mulig for Alice å sende pengene sine til Carol gjennom andre deltakere i nettverket (f.eks. Bob) - og hashlock- og timelock-funksjonene sikrer at Bob ikke kan avskjære midlene.

I tillegg til å bli brukt på Lightning Network, kan HTLC-er også være nyttige i andre sammenhenger, for eksempel krysskjedede atombytteavtaler [,](/atomic-swaps) finansielle smarte kontrakter og deponering, og mye mer.

## Høydepunkter

- Betalinger ved hjelp av HTLC-er er betingede og har dermed effektivitetsfordeler for blokkjedetransaksjoner. Denne egenskapen gjør HTLC-er til et grunnleggende verktøy som brukes av lynnettverket.

– Denne typen smarte kontrakter krever at mottakeren av en betaling bekrefter den innen en viss tidsperiode eller taper den.

- En hashed timelock-kontrakt (HTLC) reduserer motpartsrisikoen i desentraliserte smarte kontrakter ved å effektivt lage en tidsbasert deponering som bruker en kryptografisk passordfrase.

## FAQ

### Hvor mye koster en smart kontrakt?

På Ethereum-blokkjeden tar en smart kontraktdistribusjon gass, noe som koster Gwei (en lavere pålydende eter). Avhengig av kompleksiteten til kontrakten, kan det koste milliarder av Gwei å distribuere en smart kontrakt. Mindre komplekse kontrakter som en enkel utveksling er mye billigere.

### Hva er en smart kontrakt?

En smart kontrakt er et program lagret på en blokkjede som kjøres når spesifikke betingelser er oppfylt.

### Hva er en Timelock-kontrakt?

En timelock-kontrakt er en smart kontrakt innebygd i en blokkjede som utfører en transaksjon på et bestemt tidspunkt. De brukes i hashed timelock-kontrakter og betalingskanaler der spesifikke betalingstider er nødvendige.

### Har Bitcoin smarte kontrakter?

I utgangspunktet var ikke Bitcoins blokkjede i stand til å utføre smarte kontrakter. Taproot-oppgraderingen i 2021 tillot imidlertid blokkjeden å bruke smarte kontrakter i transaksjoner.

