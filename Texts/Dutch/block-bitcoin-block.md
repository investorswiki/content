---
keywords: Investing,Cryptocurrency,Blockchain
title: Blok (Bitcoin Block)
description: Blokke er datastrukturer i en database, hvor cryptocurrency transaktionsdata er permanent registreret; når den er skrevet, kan den ikke ændres eller fjernes.
---

# Blok (Bitcoin Block)
## Hvad er en blok (Blockchain Block)?

Blokke er datastrukturer i blockchain-databasen, hvor transaktionsdata i en cryptocurrency blockchain registreres permanent. En blok registrerer nogle eller alle de seneste transaktioner, der endnu ikke er valideret af netværket. Når dataene er valideret, lukkes blokken. Derefter oprettes en ny blok for nye transaktioner, der skal indgå og valideres.

En blok er således et permanent lager af poster, der, når de først er skrevet, ikke kan ændres eller fjernes.

## Hvordan en blok (Blockchain Block) fungerer

Et [blockchain](/blockchain) -netværk er vidne til en stor transaktionsaktivitet. Når det bruges i kryptovaluta, hjælper det at vedligeholde en registrering af disse transaktioner systemet med at spore, hvor meget der blev brugt eller ikke blev brugt, og hvilke parter der var involveret. De transaktioner, der foretages i en given periode, registreres i en fil kaldet en blok, som er grundlaget for blockchain-netværket.

En blok gemmer information. Der er mange stykker information inkluderet i en blok, men den optager ikke en stor mængde lagerplads. Blokke indeholder generelt disse elementer, men det kan variere mellem forskellige typer:

- **Magisk nummer**: Et tal, der indeholder specifikke værdier, der identificerer den blok som en del af en bestemt kryptovalutas netværk.

- **Blokstørrelse**: Indstiller størrelsesgrænsen på blokken, så der kun kan skrives en bestemt mængde information i den.

- **Blokhoved**: Indeholder information om blokken.

- **Transaktionstæller**: Et tal, der repræsenterer, hvor mange transaktioner der er gemt i blokken.

- **Transaktioner**: En liste over alle transaktioner inden for en blok.

Transaktionselementet er det største, fordi det indeholder flest oplysninger. Den efterfølges i lagerstørrelse af blokoverskriften, som inkluderer disse underelementer:

- **Version**: Den cryptocurrency-version, der bruges.

- **Forrige blokhash**: Indeholder en hash (krypteret nummer) af den forrige bloks overskrift.

- **Hash Merkle-rod**: Hash af transaktioner i [Merkle-træet](/merkle-tree) i den aktuelle blok.

- **Tid**: Et tidsstempel til at placere blokken i blockchain.

- **Bits**: Sværhedsgraden af målhashen, der angiver vanskeligheden ved at løse nonce.

- **Nonce**: Det krypterede nummer, som en minearbejder skal løse for at bekræfte blokeringen og lukke den.

Et 32-bit tal i overskriften kaldes en nonce - mineprogrammet bruger tilfældige tal til at "gætte" nonce i [hashen](/hash). Når en nonce er verificeret, løses hashen, når nonce, eller et tal mindre end det, gættes. Derefter lukker netværket den blok, genererer en ny med en header, og processen gentages.

forskellige mekanismer bruges til at nå en konsensus; den mest populære for cryptocurrency er [proof-of-work](/proof-work) (PoW), hvor proof-of-stake (PoS) bliver mere på grund af det reducerede energiforbrug sammenlignet med PoW.

## Minedriftens forhold til blokke

Mining er det udtryk, der bruges til at løse det tal, der er nonce, det eneste tal, der kan ændres i en blokoverskrift. Det er også den proces, kryptovalutaens netværk bruger, hvis der bruges proof-of-work i protokollen.

Udvinding af kryptovaluta menes almindeligvis at være et komplekst matematisk problem; det er faktisk et tilfældigt tal genereret gennem hashing. Hashing er processen med at kryptere information ved hjælp af den krypteringsmetode, som en kryptovaluta bruger. For eksempel bruger Bitcoin SHA256 til sin krypteringsalgoritme. For at en minearbejder kan generere det "vindende" nummer, skal mineprogrammet bruge SHA 256 til at hash tilfældige tal og placere dem i nonce for at se, om det er et match.

> At løse den tilfældige tal-hash under proof-of-work-protokollen er det, der kræver så meget energi og regnekraft. Et omfattende netværk af minearbejdere og nok energi til at drive et lille land er nødvendigt for at holde det i gang.

>

Vanskeligheden ligger i, at alle tidligere blokoverskrifter er krypteret tilfældigt. Derfor er den aktuelle blokoverskrift et tilfældigt genereret krypteret tal baseret på de tilfældigt genererede krypterede antal af tidligere blokke og information fra den aktuelle blok.

## Andre blok- og blockchain-anvendelser

Fordi de fleste blockchain-definitioner refererer til Bitcoin, fordi det var den første kryptovaluta, der brugte en, forbinder mange mennesker blokke og blockchains med Bitcoin. Andre kryptovalutaer bruger dog også blokke og blockchains. Det er vigtigt at bemærke, at Ethereums netværk har en kryptovaluta kaldet ether, der også bruger blokke og blockchain.

Ethereum og dets blockchain blev dog designet til flere anvendelser, der strækker sig til meget mere end kryptovaluta. For eksempel er ikke-fungible tokens, smarte kontrakter, decentraliserede finansieringsapplikationer og mere blevet udviklet ved hjælp af Ethereum.

##Højdepunkter

- Blokke og blockchains bruges ikke udelukkende af kryptovalutaer. De har også mange andre anvendelsesmuligheder.

- Blokke identificeres med lange tal, der inkluderer krypteret transaktionsinformation fra tidligere blokke og nye transaktionsoplysninger.

- Blokke og informationerne i dem skal verificeres af et netværk, før nye blokke kan oprettes.

- En blok er et sted i en blockchain, hvor information opbevares og krypteres.

##Ofte stillede spørgsmål

### Hvad er Blockchain i simple ord?

En blockchain er en database, der lagrer og krypterer information på en sammenkædet måde, så tidligere information ikke kan ændres, og en gruppe verificerer alle indtastninger, før de afsluttes gennem en konsensus - en aftale om, at dataene er korrekte.

### Hvad bruges blockchains til?

Blockchains bruges i kryptovaluta, decentraliserede finansieringsapplikationer, ikke-fungible tokens, med flere anvendelser konstant under udvikling.

### Hvordan skabes en Blockchain-blok?

Blokke oprettes, når minearbejdere eller blokvalidatorer med succes validerer den krypterede information i blockheaderen, hvilket beder om oprettelse af en ny blok.

