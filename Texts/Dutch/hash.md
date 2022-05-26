---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: Hash
description: Hash. Output produceret af en hash-funktion efter et stykke data er kortlagt. Kan også omtales som hashværdi, hashkode eller digest.
---

# Hash
I [kryptografi](/cryptography) refererer ordet hash til det output, der produceres af en hash-funktion, efter at et stykke data er sendt (kortlagt) gennem det. Ud over blot hash, kan output produceret af hash-funktioner også omtales som hash-værdi, hash-kode eller digest.

For bedre at forstå, hvad en hash er, er det værd at diskutere, hvad der er hash-funktioner, og hvordan de fungerer.

Hash-funktioner er matematiske [algoritmer](/algorithm),. der konverterer en inputværdi af enhver størrelse til et output (hash) af fast størrelse. I de fleste tilfælde består output af et hexadecimalt tal. Dette betyder, at hashen ofte betegnes som en kombination af tal (0 til 9) og bogstaver (a til f).

For eksempel, hvis vi bruger ordet "Binance" som inputværdien og kortlægger det gennem en SHA-256 hashfunktion, vil outputværdien (eller hash) returneret være:

f1624fcc63b615ac0e95daf9ab78434ec2e8ffe402144dc631b055f711225191

Bemærk, at det er ligegyldigt, hvor mange gange vi udfører denne handling, outputtet vil altid være det samme (så længe inputtet ikke ændres).

På den anden side vil enhver mindre ændring af input få hash-funktionen til at returnere en helt anden hash som output. Hvis vi for eksempel indsender ordet "binance" i stedet for "Binance", ville vi have følgende hash som resultat:

59bba357145ca539dcd1ac957abc1ec5833319ddcae7f5e8b5da0c36624784b2

Hashes er nyttige til at verificere gyldigheden af visse oplysninger uden at afsløre, hvad informationen er. I praksis kan hash-funktioner anvendes på forskellige scenarier. Nogle få use cases omfatter databaseopslag, analyser af store filer og datahåndtering.

Når det kombineres med kryptografiske teknikker, har vi de såkaldte kryptografiske hash-funktioner. Disse bruges i vid udstrækning inden for informationssikkerhed og er en væsentlig del af de fleste blockchain-netværk.

For eksempel har Bitcoin blockchain mange operationer, der involverer hashing, og disse er afgørende i processen med minedrift.

##Højdepunkter

- En hash er en funktion, der opfylder de krypterede krav, der er nødvendige for at løse en blockchain-beregning.

- En hash, som en nonce eller en løsning, er rygraden i blockchain-netværket.

- En hash er udviklet baseret på informationen i blokoverskriften.

- Hashes er af en fast længde, da det gør det næsten umuligt at gætte længden af hashen, hvis nogen forsøgte at knække blockchainen.

- De samme data vil altid producere den samme hash-værdi.

##Ofte stillede spørgsmål

### Hvordan beregnes en hashværdi?

En hash-funktion bruger komplekse matematiske algoritmer, der konverterer data af vilkårlig længde til data med fast længde (for eksempel 256 tegn). Hvis du ændrer en bit hvor som helst i de originale data, ændres hele hashværdien, hvilket gør den nyttig til at verificere pålideligheden af digitale filer og andre data.

### Hvad bruges hashes til i blockchains?

Hashes bruges i flere dele af et blockchain-system. For det første indeholder hver blok hashen af [blokoverskriften](/block-header-cryptocurrency) for den forrige blok, hvilket sikrer, at der ikke er blevet manipuleret med noget, efterhånden som nye blokke tilføjes. Cryptocurrency mining ved hjælp af [proof-of-work](/proof-work) (PoW) anvender desuden hashing af tilfældigt genererede tal for at nå frem til en specifik hashed værdi, der indeholder en række foranstillede nuller. Denne vilkårlige funktion er ressourcekrævende, hvilket gør det svært for en dårlig aktør at overhale netværket.

### Hvad er en hash-funktion?

Hash-funktioner er matematiske funktioner, der transformerer eller "kortlægger" et givet sæt data til en bitstreng af fast størrelse, også kendt som "hash-værdien".

