---
keywords: Personal Finance,Banking
title: Meldingsautentiseringskode (MAC)
description: En meldingsautentiseringskode (MAC), eller tag, er en sikkerhetskode som skrives inn av brukeren av en datamaskin for å få tilgang til kontoer eller portaler.
---

# Meldingsautentiseringskode (MAC)
## Hva er en meldingsgodkjenningskode?

En meldingsautentiseringskode (MAC), eller **tag,** er en sikkerhetskode som skrives inn av brukeren av en datamaskin for å få tilgang til kontoer eller portaler. Denne koden er vedlagt meldingen eller forespørselen sendt av brukeren. Meldingsautentiseringskoder (MAC-er) knyttet til meldingen må gjenkjennes av mottakersystemet for å gi brukeren tilgang.

## Forstå meldingsautentiseringskode (MAC)

Meldingsautentiseringskoder (MAC) brukes ofte i [elektroniske pengeoverføringer](/electronic-funds-transfer-act) (EFT) for å opprettholde informasjonsintegritet. de bekrefter at en melding er autentisk; at den virkelig kommer, med andre ord, fra oppgitt avsender, og ikke har gjennomgått noen endringer underveis. En verifikator som også har nøkkelen kan bruke den til å identifisere endringer i innholdet i den aktuelle meldingen.

Meldingsautentiseringskoder kreves vanligvis for å få tilgang til enhver form for finanskonto. Banker, meglerfirmaer, trustselskaper og andre innskudds-, investerings- eller forsikringsselskaper som tilbyr nettilgang kan bruke disse kodene. De er en viktig komponent i finansiell kryptografi.

## Algoritmer som brukes til å generere MAC-er

Tre algoritmer omfatter vanligvis en MAC: en nøkkelgenereringsalgoritme, en signeringsalgoritme og en verifiseringsalgoritme. Nøkkelgenereringsalgoritmen velger en nøkkel tilfeldig. Signeringsalgoritmen sender en tag når du får nøkkelen og meldingen. bekreftelsesalgoritmen brukes til å verifisere ektheten til meldingen når nøkkelen og merkelappen er gitt; den vil returnere en melding om **godkjent** hvis meldingen og taggen er autentiske og uendret, men ellers vil den returnere en melding om **avvist.**

For eksempel sender avsenderen en melding, for eksempel en EFT, gjennom MAC-algoritmen, som genererer en nøkkel og fester en MAC-datakode til meldingen. Mottakeren får meldingen, kjører den tilbake gjennom MAC-algoritmen med den samme nøkkelen, og får en andre datakode. De vil da sammenligne denne MAC-data-taggen med den første som ble knyttet til meldingen da den ble overført. Hvis koden er lik i begge ender, kan mottakeren trygt anta at dataintegriteten til meldingen er intakt. Hvis ikke, betyr det imidlertid at meldingen ble endret, tuklet med eller forfalsket.

Selve meldingen bør imidlertid inneholde noen data som sikrer at denne meldingen kun kan sendes én gang. For eksempel kan en engangs-MAC, tidsstempel eller sekvensnummer brukes for å garantere at meldingen bare kan sendes én gang. Ellers kan systemet være sårbart for et replay-angrep, der en angriper fanger opp meldingen etter at den har blitt dekodet og sender den på nytt på et senere tidspunkt, replikerer de originale resultatene og infiltrerer systemet.

## Meldingsintegritetskoder (MICs)

Noen ganger vil begrepet meldingsintegritetskode (MIC) brukes i stedet for MAC. Dette gjøres oftest i kommunikasjonsbransjen, hvor MAC tradisjonelt betyr medietilgangskontrolladresse (MAC-adresse). Imidlertid kan MIC også brukes til å referere til **meldingssammendrag** som ikke bruker hemmelige nøkler på samme måte som en MAC, og ikke kan tilby samme sikkerhetsnivå uten ytterligere kryptering.

