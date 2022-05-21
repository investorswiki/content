---
keywords: Personal Finance,Banking
title: Message Authentication Code (MAC)
description: En meddelelsesgodkendelseskode (MAC), eller tag, er en sikkerhedskode, der indtastes af brugeren af en computer for at få adgang til konti eller portaler.
---

# Message Authentication Code (MAC)
## Hvad er en meddelelsesgodkendelseskode?

En meddelelsesgodkendelseskode (MAC) eller **tag,** er en sikkerhedskode, der indtastes af brugeren af en computer for at få adgang til konti eller portaler. Denne kode er knyttet til meddelelsen eller anmodningen sendt af brugeren. Beskedgodkendelseskoder (MAC'er), der er knyttet til meddelelsen, skal genkendes af det modtagende system for at give brugeren adgang.

## Forstå Message Authentication Code (MAC)

bruges almindeligvis i [elektroniske pengeoverførsler](/electronic-funds-transfer-act) (EFT'er) for at opretholde informationsintegritet. De bekræfter, at en besked er autentisk; at det med andre ord virkelig kommer fra den angivne afsender og ikke har undergået nogen ændringer undervejs. En verifikator, som også er i besiddelse af nøglen, kan bruge den til at identificere ændringer i indholdet af den pågældende meddelelse.

Beskedgodkendelseskoder er normalt påkrævet for at få adgang til enhver form for finanskonto. Banker, mæglerfirmaer, trustselskaber og ethvert andet indskuds-, investerings- eller forsikringsselskab, der tilbyder onlineadgang, kan anvende disse koder. De er en vital komponent i finansiel kryptografi.

## Algoritmer, der bruges til at generere MAC'er

Tre algoritmer omfatter typisk en MAC: en nøglegenereringsalgoritme, en signeringsalgoritme og en verifikationsalgoritme. Nøglegenereringsalgoritmen vælger en nøgle tilfældigt. Signeringsalgoritmen sender et tag, når nøglen og beskeden gives. Verifikationsalgoritmen bruges til at verificere ægtheden af meddelelsen, når den får nøglen og mærket; det vil returnere en meddelelse om **accepteret**, hvis meddelelsen og tagget er autentiske og uændrede, men ellers vil det returnere en meddelelse om **afvist.**

For eksempel sender afsenderen en besked, såsom en EFT, gennem MAC-algoritmen, som genererer en nøgle og vedhæfter et MAC-datatag til beskeden. Modtageren får beskeden, kører den tilbage gennem MAC-algoritmen med den samme nøgle og får endnu et datamærke. De vil derefter sammenligne denne MAC-data-tag med den første, der er knyttet til beskeden, da den blev transmitteret. Hvis koden er den samme i begge ender, kan modtageren roligt antage, at meddelelsens dataintegritet er intakt. Hvis ikke, betyder det dog, at meddelelsen er blevet ændret, manipuleret med eller forfalsket.

Selve beskeden bør dog indeholde nogle data, der sikrer, at denne besked kun kan sendes én gang. For eksempel kan en engangs-MAC, et tidsstempel eller et sekvensnummer bruges til at garantere, at beskeden kun kan sendes én gang. Ellers kan systemet være sårbart over for et genafspilningsangreb, hvor en angriber opsnapper beskeden, efter den er blevet afkodet, og genudsender den på et senere tidspunkt, hvorved de originale resultater replikeres og infiltreres i systemet.

## Message Integrity Codes (MIC'er)

Nogle gange vil udtrykket message integrity code (MIC) blive brugt i stedet for MAC. Dette gøres oftest i kommunikationsbranchen, hvor MAC traditionelt betyder medieadgangskontroladresse (MAC-adresse). MIC kan dog også bruges til at henvise til **meddelelsessammenfatning**, som ikke bruger hemmelige nøgler på samme måde som en MAC og ikke kan tilbyde det samme sikkerhedsniveau uden yderligere kryptering.

