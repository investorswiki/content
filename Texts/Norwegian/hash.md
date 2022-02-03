---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: Hash
description: Hash. Utdataene som produseres av en hash-funksjon etter at et datastykke er kartlagt. Kan også bli referert til som hash-verdi, hash-kode eller sammendrag.
---

# Hash
I [kryptografi](/cryptography) refererer ordet hash til utdataene som produseres av en hash-funksjon etter at et stykke data er sendt (kartlagt) gjennom den. Annet enn bare hash, kan utdataene som produseres av hash-funksjoner også refereres til som hash-verdi, hash-kode eller digest.

For bedre å forstå hva en hash er, er det verdt å diskutere hva som er hash-funksjoner og hvordan de fungerer.

Hash-funksjoner er matematiske [algoritmer](/algorithm) som konverterer en inngangsverdi av en hvilken som helst størrelse til en utdata (hash) med fast størrelse. I de fleste tilfeller består utgangen av et heksadesimalt tall. Dette betyr at hashen ofte betegnes som en kombinasjon av tall (0 til 9) og bokstaver (a til f).

For eksempel, hvis vi bruker ordet "Binance" som inngangsverdi, og kartlegger det gjennom en SHA-256 hash-funksjon, vil utgangsverdien (eller hashen) som returneres:

f1624fcc63b615ac0e95daf9ab78434ec2e8ffe402144dc631b055f711225191

Merk at det ikke spiller noen rolle hvor mange ganger vi utfører denne handlingen, utdata vil alltid være det samme (så lenge inngangen ikke endres).

På den annen side vil enhver mindre endring av inngangen føre til at hash-funksjonen returnerer en helt annen hash som utgangen. For eksempel, hvis vi sender inn ordet "binance" i stedet for "Binance", vil vi ha følgende hash som resultat:

59bba357145ca539dcd1ac957abc1ec5833319ddcae7f5e8b5da0c36624784b2

Hashes er nyttige for å verifisere gyldigheten av viss informasjon, uten å avsløre hva informasjonen er. I praksis kan hash-funksjoner brukes på ulike scenarier. Noen få brukstilfeller inkluderer databaseoppslag, analyser av store filer og databehandling.

Kombinert med kryptografiske teknikker har vi de såkalte kryptografiske hash-funksjonene. Disse er mye brukt i informasjonssikkerhet og er en viktig del av de fleste blokkjedenettverk.

For eksempel har Bitcoin blockchain mange operasjoner som involverer hashing, og disse er avgjørende i prosessen med gruvedrift.

## Høydepunkter

– En hash er en funksjon som oppfyller de krypterte kravene som trengs for å løse en blokkjedeberegning.

– En hash, som en nonce eller en løsning, er ryggraden i blokkjedenettverket.

- En hash er utviklet basert på informasjonen som finnes i blokkhodet.

- Hash har en fast lengde siden det gjør det nesten umulig å gjette lengden på hashen hvis noen prøvde å knekke blokkjeden.

– De samme dataene vil alltid produsere samme hashverdi.

## FAQ

### Hvordan beregnes en hash-verdi?

En hash-funksjon bruker komplekse matematiske algoritmer som konverterer data av vilkårlig lengde til data med fast lengde (for eksempel 256 tegn). Hvis du endrer én bit hvor som helst i de originale dataene, endres hele hash-verdien, noe som gjør den nyttig for å verifisere påliteligheten til digitale filer og andre data.

### Hva brukes hashes til i blokkjeder?

Hashes brukes i flere deler av et blokkjedesystem. For det første inneholder hver blokk hashen til [blokkoverskriften](/block-header-cryptocurrency) til den forrige blokken, og sikrer at ingenting har blitt tuklet med når nye blokker legges til. Utvinning av kryptovaluta ved bruk av [proof-of-work](/proof-work) (PoW) benytter dessuten hashing av tilfeldig genererte tall for å komme frem til en spesifikk hash-verdi som inneholder en serie av ledende nuller. Denne vilkårlige funksjonen er ressurskrevende, noe som gjør det vanskelig for en dårlig aktør å overta nettverket.

### Hva er en hash-funksjon?

Hash-funksjoner er matematiske funksjoner som transformerer eller "karter" et gitt sett med data til en bitstreng med fast størrelse, også kjent som "hash-verdien".

