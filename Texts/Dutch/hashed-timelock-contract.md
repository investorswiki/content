---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Crypto,Strategy and Education
title: Hashed Timelock Contract (HTLC)
description: Hashed TimeLock-kontrakt (HTLC). Henviser til en speciel funktion, der bruges til at skabe smarte kontrakter, der er i stand til at ændre betalingskanaler.
---

# Hashed Timelock Contract (HTLC)
Udtrykket Hashed TimeLock Contract (HTLC) refererer til en speciel funktion, der bruges til at skabe [smarte kontrakter](/smart-contract),. der er i stand til at ændre betalingskanaler. Teknisk set muliggør HTLC-funktionen implementering af tidsbestemte transaktioner mellem to brugere. I praksis skal modtageren af en HTLC-transaktion bekræfte betalingen ved at indsende et kryptografisk bevis inden for en specificeret tidsramme (antal blokke). Hvis modtageren mister eller undlader at kræve betalingen, vil pengene blive returneret til den oprindelige afsender.

HTLC-funktionen anvendes i både tovejs- og rutede betalingskanaler for at tillade sikre overførsler af penge over forskellige kanaler uden at kræve tillid til nogen af formidlerne.

Der er to nøgleelementer, der adskiller HTLC fra standard cryptocurrency-transaktioner, som er:

- Hashlock: en funktion, der begrænser brugen af midler, indtil et bestemt stykke data offentliggøres (som et kryptografisk bevis). Et sådant bevis kan også omtales som forbilledet af hashlocket. Forbilledet er simpelthen det stykke information, der bruges til at generere hashlocket og senere låse dets midler op.

- Timelock: er en funktion, der begrænser forbruget af midler indtil et bestemt tidspunkt (eller blokhøjde) i fremtiden. Det kan opnås i Bitcoin, for eksempel ved hjælp af funktioner som CheckLockTimeVerify eller CheckSequenceVerify.

Bitcoin Lightning Network er blandt de mest populære brugssager af hashed timelocked-kontrakter. Ved at implementere HTLC i betalingskanaler, kan midler overføres fra bruger til bruger gennem indbyrdes forbundne betalingskanaler, uden at det kræver nogen grad af tillid. Denne proces er kendt som netværksrouting. Det giver Alice mulighed for at udveksle penge med Carol, selvom de ikke er direkte forbundet via en betalingskanal. HTLC'er gør det muligt for Alice at sende sine penge til Carol gennem andre deltagere i netværket (f.eks. Bob) - og hashlock- og timelock-funktionerne sikrer, at Bob ikke kan opsnappe pengene.

Udover at blive brugt på Lightning Network, kan HTLC'er også være nyttige i andre sammenhænge, såsom cross-chain [atomic swaps](/atomic-swaps),. finansielle smarte kontrakter og escrow og meget mere.

##Højdepunkter

- Betalinger ved hjælp af HTLC'er er betingede og har derfor effektivitetsfordele for blockchain-transaktioner. Denne egenskab gør HTLC'er til et grundlæggende værktøj, der bruges af lynnetværket.

- Denne type smart kontrakt kræver, at modtageren af en betaling anerkender den inden for en vis periode eller mister den.

- En hashed timelock-kontrakt (HTLC) reducerer modpartsrisikoen i decentraliserede smarte kontrakter ved effektivt at skabe en tidsbaseret escrow, der bruger en kryptografisk adgangssætning.

##Ofte stillede spørgsmål

### Hvor meget koster en smart kontrakt?

På Ethereum blockchain tager en smart kontraktimplementering gas, hvilket koster Gwei (en lavere betegnelse for ether). Afhængigt af kontraktens kompleksitet kan det koste milliarder af Gwei at implementere en smart kontrakt. Mindre komplekse kontrakter som en simpel udveksling er meget billigere.

### Hvad er en smart kontrakt?

En smart kontrakt er et program, der er gemt på en blockchain, der udføres, når specifikke betingelser er opfyldt.

### Hvad er en Timelock-kontrakt?

En timelock-kontrakt er en smart kontrakt indlejret i en blockchain, der udfører en transaktion på et bestemt tidspunkt. De bruges i hashed timelock-kontrakter og betalingskanaler, hvor der er behov for specifikke betalingstider.

### Har Bitcoin smarte kontrakter?

I første omgang var Bitcoins blockchain ikke i stand til at udføre smarte kontrakter. Taproot-opgraderingen i 2021 tillod dog blockchain at bruge smarte kontrakter i transaktioner.

