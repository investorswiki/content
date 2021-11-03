---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: Merkle træ
description: Merkle træ. En måde at organisere og strukturere store mængder data på for at gøre det mere ligetil at behandle. En hash-baseret datastruktur.
---

# Merkle træ
Et Merkle-træ er en måde at organisere og strukturere store mængder data på for at gøre det mere ligetil at behandle. I tilfælde af cryptocurrency og [blockchain](/blockchain) bruges Merkle-træet til at strukturere transaktionsdata på en måde, der er mindre ressourcekrævende.

Når en kryptovaluta-transaktion foretages i en Merkle-træstruktur, hashes den og får derefter en tilsvarende hashværdi. Efter hver transaktion er hashed i Merkle-træet, parres de producerede hashværdier med en anden hashværdi og derefter hash igen. For eksempel kombineres hashværdierne 'AB' og 'AC' for at skabe 'ABC'.

Denne proces med parring af hashværdier gentages, indtil en endelig hashværdi er produceret. Den endelige hashværdi, Merkle-roden, giver en oversigt over alle de transaktioner, den indeholder. Merkle-rodresuméet indsættes derefter i blokoverskriften.

#### Datasikkerhed

En Merkle-træstruktur giver en let tilgængelig registrering af transaktionerne i en [blok](/block). Så det er meget nemt at kontrollere, om dataene i en blok er blevet ændret eller manipuleret med. Dette er sandt, fordi enhver ændring af en transaktion (eller andre relaterede data) i Merkle-træet ville føre til en helt anden tilsvarende Merkle-rod.

#### Effektiv brug af ressourcer

Hvis kryptovalutaer ikke brugte Merkle-træer, ville enhver verifikationsanmodning involvere enorme mængder information, der blev sendt på tværs af netværket. At strukturere transaktionsdata i et Merkle-træ er en langt mere effektiv brug af ressourcer. Validering af en transaktion kræver ikke en komplet kopi af hovedbogen, da de hasherede transaktionsdata kan verificeres i en Merkle-rod, hvilket kræver, at meget mindre information sendes på tværs af knudepunkterne og dermed mindre computerkraft til at analysere den overordnede dataintegritet.

Med andre ord, en Merkle træstruktur gør det muligt for brugere at verificere, at en individuel transaktion er inkluderet i en blok uden at skulle gennemgå processen med at downloade hele blockchain. Teknologien er et vigtigt værktøj for kryptovalutaer til at organisere transaktionsdata og fungere så effektivt, som de gør. Uden Merkle-træer er det sandsynligt, at den større efterspørgsel efter ressourcer vil resultere i, at færre [noder](/node) deltager i netværket.

