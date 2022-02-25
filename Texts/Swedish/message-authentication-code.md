---
keywords: Personal Finance,Banking
title: Message Authentication Code (MAC)
description: En meddelandeautentiseringskod (MAC), eller tagg, är en säkerhetskod som skrivs in av användaren av en dator för att komma åt konton eller portaler.
---

# Message Authentication Code (MAC)
## Vad är en meddelandeautentiseringskod?

En meddelandeautentiseringskod (MAC), eller **tagg,** är en säkerhetskod som skrivs in av användaren av en dator för att komma åt konton eller portaler. Denna kod bifogas meddelandet eller begäran som skickas av användaren. Meddelandeautentiseringskoder (MAC) som är kopplade till meddelandet måste kännas igen av det mottagande systemet för att ge användaren åtkomst.

## Förstå meddelandeautentiseringskoden (MAC)

Meddelandeautentiseringskoder (MAC) används ofta i [elektroniska överföringar](/electronic-funds-transfer-act) (EFT) för att upprätthålla informationsintegritet. De bekräftar att ett meddelande är äkta; att den verkligen kommer, med andra ord, från den angivna avsändaren och inte har genomgått några förändringar på vägen. En verifierare som också har nyckeln kan använda den för att identifiera ändringar av innehållet i meddelandet i fråga.

Meddelandeautentiseringskoder krävs vanligtvis för att komma åt alla typer av finanskonton. Banker, mäklarfirmor, trustbolag och alla andra insättnings-, investerings- eller försäkringsbolag som erbjuder onlineåtkomst kan använda dessa koder. De är en viktig komponent i finansiell kryptografi.

## Algoritmer som används för att generera MAC

Tre algoritmer innefattar vanligtvis en MAC: en nyckelgenereringsalgoritm, en signeringsalgoritm och en verifieringsalgoritm. Nyckelgenereringsalgoritmen väljer en nyckel slumpmässigt. Signeringsalgoritmen skickar en tagg när nyckeln och meddelandet ges. Verifieringsalgoritmen används för att verifiera meddelandets äkthet när nyckeln och taggen ges; det kommer att returnera ett meddelande om **accepterat** om meddelandet och taggen är autentiska och oförändrade, men annars kommer det att returnera ett meddelande om **avvisad.**

Till exempel skickar avsändaren ett meddelande, såsom en EFT, genom MAC-algoritmen, som genererar en nyckel och bifogar en MAC-datatagg till meddelandet. Mottagaren får meddelandet, kör tillbaka det genom MAC-algoritmen med samma nyckel och får en andra datatagg. De kommer sedan att jämföra denna MAC-datatagg med den första som bifogas meddelandet när det överfördes. Om koden är densamma i båda ändarna kan mottagaren säkert anta att meddelandets dataintegritet är intakt. Om inte betyder det dock att meddelandet har ändrats, manipulerats eller förfalskats.

Själva meddelandet bör dock innehålla vissa data som säkerställer att detta meddelande bara kan skickas en gång. Till exempel kan en engångs-MAC, tidsstämpel eller sekvensnummer användas för att garantera att meddelandet bara kan skickas en gång. Annars kan systemet vara sårbart för en replay-attack, där en angripare fångar upp meddelandet efter att det har avkodats och återsänder det vid ett senare tillfälle, replikerar de ursprungliga resultaten och infiltrerar systemet.

## Meddelandeintegritetskoder (MIC)

Ibland kommer termen meddelandeintegritetskod (MIC) att användas istället för MAC. Detta görs oftast inom kommunikationsbranschen, där MAC traditionellt betyder media access control address (MAC-adress). MIC kan dock också användas för att referera till **meddelandesammandrag,** som inte använder hemliga nycklar på samma sätt som en MAC och inte kan erbjuda samma säkerhetsnivå utan ytterligare kryptering.

