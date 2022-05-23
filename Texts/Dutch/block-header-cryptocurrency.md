---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: Blokoverskrift (kryptovaluta)
description: blok overskrift. Et afsnit i en blok, der indeholder metadata og en oversigt over blokkens transaktioner. Dette er den information, der hashes ved minedrift.
---

# Blokoverskrift (kryptovaluta)
Blokhovedet er et afsnit i en [blok](/block),. der fungerer som en oversigt over resten af blokken. Den består af alle [metadata](/metadata) – såsom tidspunktet og [sværhedsgraden](/difficulty),. da blokken blev [udvundet](/mining),. [Merkle-roden](/merkle-tree) af de inkluderede transaktioner og [nonce](/nonce). Også til stede er den forrige bloks [hash](/hash),. som er det, der giver os mulighed for at skabe "kæden" af blokke. I det væsentlige indeholder blokoverskriften alle data, der ikke er selve listen over råtransaktioner.

En blokoverskrift er, hvad minearbejderne hash for at forsøge at gøre blokken gyldig. Dette er meget mere effektivt end at hashe hele blokken, som kan bestå af tusindvis af transaktioner. Det ville være langt mere besværligt for en minearbejder at ændre nonce og at rehash en hel 2MB blok for hvert forsøg. Sammenlign dette med for eksempel hashing af Bitcoins blokoverskrifter, som har en fast længde på 80 bytes.

Blokhoveder er fantastiske fra et minedriftssynspunkt, men på grund af deres lille størrelse er de også ideelle til lette klienter. Bitcoin blockchain er for stor til, at enheder som smartphones kan opbevares. Hvis kæden havde 100.000 1 MB blokke, ville du forbruge 100 GB plads. Men med kun blokoverskrifterne for de samme blokke, ville du kun fylde 0,008 GB eller 8 MB.

På denne måde kan enheder med mindre båndbredde eller lagerplads stadig udføre en vis grad af validering. Fordi Merkle-roden indkapsler alle transaktionerne, kan de senere kontrollere, om en transaktion var inkluderet i en bestemt blok. Dette koster noget – brugeren skal stadig stole på, at en tredjepart giver dem de nødvendige oplysninger. Med det sagt er light-klienter at foretrække frem for et system, hvor brugerne slet ikke udfører nogen verifikation.

##Højdepunkter

- De er hashed for at skabe et bevis på arbejde for minedriftsbelønninger.

- Blokoverskrifter identificerer individuelle blokke i en blockchain.

- Blokkene er lagdelt lodret, begyndende med "genese-blokken."

- Bitcoin-versionsnummeret hjælper dig med at holde styr på ændringer i protokollen.

- Hver blokoverskrift indeholder tre sæt blokmetadata og flere individuelle komponenter.

