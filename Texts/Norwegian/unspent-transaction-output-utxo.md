---
keywords: Crypto
title: Ubrukt transaksjonsutgang (UTXO)
description: Ubrukt transaksjonsutgang (UTXO). En utgang opprettet i en transaksjon, som må refereres til i en fremtidig transaksjon for å bruke midler.
---

# Ubrukt transaksjonsutgang (UTXO)
En ubrukt transaksjonsutgang (UTXO) refererer til en transaksjonsutgang som kan brukes som input i en ny transaksjon. I hovedsak definerer UTXOer hvor hver blokkjedetransaksjon starter og slutter. UTXO-modellen er et grunnleggende element i Bitcoin og mange andre kryptovalutaer.

Med andre ord, kryptovalutatransaksjoner er laget av innganger og utganger. Hver gang en transaksjon utføres, tar en bruker en eller flere UTXOer for å tjene som input(er). Deretter gir brukeren sin digitale signatur for å bekrefte eierskap over inngangene, som til slutt resulterer i utganger. UTXO-ene som forbrukes anses nå som "brukt", og kan ikke lenger brukes. I mellomtiden blir utdataene fra transaksjonen nye UTXOer – som kan brukes i en ny transaksjon senere.

Dette er nok bedre forklart med et eksempel. Alice har 0,45 BTC i lommeboken. Dette er ikke en brøkdel av en mynt slik vi kan begrepsfeste det. Det er snarere en samling UTXO-er. Nærmere bestemt to UTXO-er verdt 0,4 BTC og 0,05 BTC - utganger fra tidligere transaksjoner. La oss nå forestille oss at Alice må foreta en betaling til Bob på 0,3 BTC.

Hennes eneste mulighet her er å bryte opp 0,4 BTC-enheten og sende 0,3 BTC til Bob, og 0,1 BTC tilbake til seg selv. Hun ville normalt kreve tilbake mindre enn 0,1 BTC på grunn av gruveavgifter, men la oss forenkle og utelate gruvearbeideren.

Alice oppretter en transaksjon som i hovedsak sier til nettverket: ta min 0,4 BTC UTXO som en inngang, del den opp, send 0,3 BTC av den til Bobs adresse og returner 0,1 BTC til adressen min. 0,4 BTC er nå en brukt utgang, og kan ikke gjenbrukes. I mellomtiden har to nye UTXOer blitt opprettet (0,3 BTC og 0,1 BTC).

Legg merke til at vi brøt opp en UTXO i dette eksemplet, men hvis Alice måtte betale 0,42 BTC, kunne hun like gjerne kombinert sine 0,4 BTC med ytterligere 0,05 BTC for å produsere en UTXO verdt 0,42 BTC, mens hun returnerte 0,03 BTC til seg selv.

Oppsummert fungerer UTXO-modellen som protokollens mekanisme for å holde styr på hvor mynter er til enhver tid. På en måte fungerer de omtrent som sjekker: de er adressert til bestemte brukere (eller rettere sagt, deres offentlige [adresser](/address) ). UTXO-er kan ikke brukes delvis - i stedet må nye sjekker opprettes fra den gamle og sendes videre deretter.

