---
keywords: Investing,Cryptocurrency,Altcoins
title: Mål Hash
description: En target-hash angiver vanskeligheden for cryptocurrency-mining ved hjælp af et proof-of-work (PoW) blockchain-system.
---

# Mål Hash
## Hvad er en Target Hash?

I cryptocurrency-mining er en target-hash en numerisk værdi, som en hashed [blokoverskrift](/block-header-cryptocurrency) skal være mindre end eller lig med, for at en ny blok kan tildeles en minearbejder. Blokoverskrifter identificerer individuelle blokke i en blockchain.

Mining med kryptovaluta refererer til processen med at indsamle kryptovaluta som en belønning for det arbejde, du udfører. Arten af dette arbejde er at verificere legitimiteten af en given kryptovalutas transaktioner. På denne måde er cryptocurrency-minearbejdere i det væsentlige revisorer. Når du mine, kan du tjene cryptocurrency uden at skulle lægge penge ned for det.

Målhashen bruges til at bestemme sværhedsgraden af input og kan justeres for at sikre, at blokke behandles effektivt. For eksempel bruges target-hashes i kryptovalutaer, der bruger et proof-of-work (PoW)-system til at indstille den aktuelle [minedriftssvære](/difficulty-cryptocurrencies) [y](/difficulty-cryptocurrencies) (inklusive Bitcoin). Hvis en kryptovaluta bruger et andet system til minedrift, kræver det muligvis ikke en målhash.

## Sådan fungerer en målhash

[Kryptovalutaer](/cryptocurrency) er afhængige af brugen af [blockchains](/blockchain),. der indeholder historien om alle den kryptovaluta's transaktioner. Disse transaktioner [hashes](/hash) eller kodes kryptografisk til en række alfanumeriske tegn. Hashing involverer at tage en datastreng af enhver længde og køre den gennem en algoritme for at producere et output med en fast længde. Outputtet vil altid have samme længde, uanset hvor stort eller lille inputtet er (selvom antallet af permutationer af en hash er astronomisk stort). Hver blok vil indeholde hashen fra den forrige blokoverskrift.

Validering og kodning af blockchain kaldes [minedrift](/bitcoin-mining). Mining involverer brugen af computere til at køre hashing-algoritmer for at behandle den seneste blok; den information, som en bruger skal bruge, findes i blokkens header. Kryptovaluta-netværket sætter en målværdi for denne hash - kaldet target-hash - og minearbejdere forsøger at bestemme, hvad denne værdi er ved at teste alle mulige værdier.

Blokhovedet indeholder blokversionsnummeret, et tidsstempel, hashen brugt i den forrige blok, hashen for [Merkle Root](/merkle-root-cryptocurrency) [t](/merkle-root-cryptocurrency),. [nonce](/nonce) og målhash. Blokken genereres ved at tage hashen af blokindholdet, tilføje en tilfældig række af tal (nonce) og hashe blokken igen.

Hvis hashen opfylder målets krav, tilføjes blokken til blockchain. At cykle gennem løsninger for at gætte nonce omtales som [proof of work](/proof-work) (PoW), og minearbejderen, der er i stand til at finde værdien, tildeles blokken og betales i kryptovaluta.

## Særlige overvejelser

### Målhash for Bitcoin

Bitcoin bruger SHA-256 hash-algoritmen. Denne algoritme genererer verificerbart tilfældige tal på en måde, der kræver en forudsigelig mængde computerprocessorkraft.

Mining af en blok kræver, at minearbejderen producerer en værdi (en nonce), der efter at være blevet hashed (kryptografisk kodet), er mindre end eller lig med den, der blev brugt i den seneste blok, der er accepteret af bitcoin-netværket. Dette tal er mellem 0- (den mindste mulighed) og 256-bit (den største mulighed), men det er usandsynligt, at det nogensinde vil være det maksimale antal.

Fordi target-hashen kan være et stort antal, kan minearbejderen være nødt til at teste et stort antal værdier, før det lykkes. En mislykket minearbejder skal vente på den næste blok (hvilket er grunden til, at minearbejdere, der finder en hash-løsning, sammenlignes med vindere af et løb eller lotteriet).

Målhashen justeres med jævne mellemrum. De hash-funktioner, der bruges til at generere det nye mål, har specifikke egenskaber designet til at gøre blockchainen (og dens kryptovaluta) sikker. Denne proces er deterministisk, hvilket betyder, at den vil producere det samme resultat, hver gang det samme input bruges. Det er hurtigt nok til ikke at tage for lang tid at returnere en hash til input. Det gør også det meget vanskeligt at bestemme inputtet, især for store tal, og små ændringer i inputtet resulterer i et meget anderledes hashoutput.

## Højdepunkter

- Target hashes bruges i kryptovalutaer, der bruger et proof-of-work (PoW)-system til at indstille den aktuelle minedrift (inklusive Bitcoin); hvis en kryptovaluta bruger et andet system til minedrift, kræver det muligvis ikke en target-hash.

- I cryptocurrency-mining er en target-hash en numerisk værdi, som en hashed blokheader (som bruges til at identificere individuelle blokke i en blockchain) skal være mindre end eller lig med, for at en ny blok kan tildeles en minearbejder.

- Bitcoin-netværket justerer sværhedsgraden af minedrift ved at hæve eller sænke target-hashen for at bevare et gennemsnitligt 10-minutters interval mellem nye blokke.

