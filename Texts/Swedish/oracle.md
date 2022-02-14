---
keywords: Crypto
title: Orakel
description: Orakel. En datakälla eller flöde från en tredje part som används för att fastställa utfall för smarta kontrakt.
---

# Orakel
Ett orakel kan definieras på flera olika sätt, beroende på sammanhanget. Inom blockchain-sammanhang är ett orakel i grunden en datakälla som används som en brygga mellan smarta kontrakt och andra externa källor.

Mer specifikt är ett orakel en agent som inte bara kommunicerar med externa datakällor utan också verifierar och autentiserar att data som tillhandahålls är korrekta. Således är orakel ansvariga för att tillhandahålla viktig och pålitlig information till smarta kontrakt, som i sin tur utför vissa uppgifter.

Vikten av orakel bygger på det faktum att blockchain-smarta kontrakt endast kan komma åt den data som finns i deras eget digitala nätverk. Därför behövs orakel som ett kommunikationsinstrument som "översätter" verkliga händelser (icke-deterministiska data) till digitala värden som känns igen av smarta kontrakt (deterministiska data).

Blockchain-orakel kan klassificeras enligt deras användningsfall. De vanligaste typerna är:

- Hardware Oracles: Integreras med fysiska system och teknologier och tillhandahåller verklig data för smarta kontrakt. Till exempel kan hårdvaruorakel kommunicera med RFID-sensorer som används i olika industrier (bil, läkemedel, leveranskedja, etc.)

- Programvara Oracles: mest använda; hämta onlinedata från externa program och webb-API:er - såsom marknadspriser, flygstatus och väderdata.

- Consensus Oracles: sorts decentraliserade orakel som samlar in stora mängder data från ett visst antal andra orakel, enligt specifika metoder för att bestämma giltigheten och riktigheten av insamlade data. Konsensusorakel används i plattformar för förutsägelsemarknader, såsom Augur och Gnosis.

- Inkommande Oracles: överför extern data till smarta kontrakt eller programvaruorakel. Kan konfigureras som en uppsättning "om"-riktlinjer (t.ex. "om en tillgång når ett visst pris, lägg en köporder").

- Outbound Oracles: överför smarta kontraktsdata till externa system, vilket gör det möjligt för smarta kontrakt att kommunicera med icke-blockchain-källor.

I allmänhet består ett blockchain-orakel av en tredjepartsdatakälla som är beroende av extern tillstånd för att fungera korrekt, vilket innebär att de vanligtvis är ett verktyg som tillhandahålls av centraliserade enheter. Därför slutar de flesta orakel med att offra de decentraliserade egenskaperna hos de smarta kontrakten.

### Oracle-problemet

Beroende på data som tillhandahålls av de centraliserade oraklen, kommer smarta kontrakt att utföra olika funktioner, vilket innebär att orakel har enorm makt över smarta kontrakt. Detta är känt som Oracle-problemet, som uppstår som en förtroendekonflikt som centraliserade tredjeparts-orakel leder till förtroendelösa smarta kontrakt och blockkedjesystem.

Även om decentraliserade orakel, såsom konsensusoraklen, kan utgöra en möjlig lösning, finns det fortfarande många utmaningar att övervinna, eftersom decentraliserade orakelnätverk är ganska svåra att implementera på ett säkert, funktionellt och tillitslöst sätt.

