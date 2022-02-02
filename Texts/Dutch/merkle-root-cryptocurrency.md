---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Merkle Root (kryptovaluta)
description: En Merkle-rod indeholder information om hver enkelt transaktionshash, der nogensinde har været på en bestemt blok i en blockchain.
---

# Merkle Root (kryptovaluta)
## Hvad er en Merkle-rod?

En Merkle-rod er [hashen](/hash) af alle hasherne af alle de transaktioner, der er en del af en blok i et [blockchain](/blockchain) -netværk.

## Forstå en Merkle-rod

En blockchain består af forskellige blokke, der er forbundet med hinanden (deraf navnet blockchain). Et hash-træ, eller [Merkle-træet](/merkle-tree),. koder blockchain-dataene på en effektiv og sikker måde. Det muliggør hurtig verifikation af blockchain-data samt hurtig flytning af store mængder data fra den ene computernode til den anden på peer-to-peer blockchain-netværket.

Hver transaktion, der finder sted på blockchain-netværket, har en hash tilknyttet. Disse hashes gemmes dog ikke i en sekventiel rækkefølge på blokken, snarere i form af en trælignende struktur, således at hver hash er knyttet til sin forælder efter en forældre-barn trælignende relation.

Da der er talrige transaktioner gemt på en bestemt blok, hashes alle transaktions-hasherne i blokken også, hvilket resulterer i en Merkle-rod.

Overvej for eksempel en blok med syv transaktioner. På det laveste niveau (kaldet bladniveauet) vil der være fire transaktions-hash. På niveau et over leaf-niveauet vil der være to transaktions-hashes, som hver vil forbinde til to hashes, der er under dem på leaf-niveauet. Øverst (niveau to) vil der være den sidste transaktions-hash kaldet root, og den vil forbinde til de to hashes under den (på niveau et).

Effektivt får du et binært træ på hovedet, hvor hver knude i træet kun forbindes til to knudepunkter under det (deraf navnet "binært træ"). Den har en root-hash øverst, som forbinder til to hashes på niveau et, som hver igen forbinder til de to hashes på niveau tre (blad-niveau), og strukturen fortsætter afhængigt af antallet af transaktions-hash.

<!--AAFEB15A7406E8DD3ABDD652D7C85823-->

Hashing starter på det laveste niveau (bladniveau) noder, og alle fire hashes er inkluderet i hashen af noder, der er knyttet til det på niveau et. På samme måde fortsætter hash på niveau et, hvilket fører til, at hashes af hashes når til højere niveauer, indtil det når den enkelte toprod-hash.

Denne root-hash kaldes Merkle-roden, og på grund af den trælignende kobling af hash indeholder den al information om hver enkelt transaktions-hash, der findes på blokken. Det tilbyder en enkeltpunkts hashværdi, der gør det muligt at validere alt, der er til stede på den blok.

For eksempel, hvis man skal verificere en transaktion, der hævder at være kommet fra blok #137, behøver de kun at tjekke blokkens Merkle-træ uden at bekymre sig om at verificere noget på andre blokke på blockchain, som blok #136 eller blok # 138.

<!--4861E8697637B7236BF11AA57D958059-->

Indtast Merkle-roden, som yderligere fremskynder verifikationen. Da det bærer al information om hele træet, behøver man kun at verificere den transaktions-hash, dens søskende-node (hvis den findes), og derefter fortsætte opad, indtil den når toppen.

I det væsentlige reducerer Merkle-træet og Merkle-rodmekanismen betydeligt niveauerne af hashing, der skal udføres, hvilket muliggør hurtigere verifikation og transaktioner.

## Højdepunkter

- Merkle-rødder er centrale for den beregning, der kræves for at vedligeholde kryptovalutaer som bitcoin og ether.

- Merkle-rødder bruges i kryptovaluta for at sikre, at datablokke, der sendes mellem peers på et peer-to-peer-netværk, er hele, ubeskadigede og uændrede.

- En Merkle-rod er en simpel matematisk måde at verificere dataene på et Merkle-træ på.

