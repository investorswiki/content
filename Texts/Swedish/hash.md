---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: Hash
description: Hash. Utdata som produceras av en hashfunktion efter att en bit data har mappats. Kan också hänvisas till som hashvärde, hashkod eller sammanfattning.
---

# Hash
I [kryptografi](/cryptography) hänvisar ordet hash till utdata som produceras av en hashfunktion efter att en bit data har skickats (mappats) genom den. Annat än bara hash kan utdata som produceras av hashfunktioner också hänvisas till som hashvärde, hashkod eller sammanfattning.

För att bättre förstå vad en hash är, är det värt att diskutera vad som är hashfunktioner och hur de fungerar.

Hash-funktioner är matematiska [algoritmer](/algorithm) som omvandlar ett indatavärde av valfri storlek till en utdata (hash) med fast storlek. I de flesta fall består utdata av ett hexadecimalt tal. Detta betyder att hashen ofta betecknas som en kombination av siffror (0 till 9) och bokstäver (a till f).

Till exempel, om vi använder ordet "Binance" som indatavärde och mappar det genom en SHA-256 hashfunktion, kommer utdatavärdet (eller hashen) som returneras att vara:

f1624fcc63b615ac0e95daf9ab78434ec2e8ffe402144dc631b055f711225191

Observera att det inte spelar någon roll hur många gånger vi utför den här åtgärden, utgången kommer alltid att vara densamma (så länge ingången inte ändras).

Å andra sidan kommer varje mindre förändring av ingången att göra att hash-funktionen returnerar en helt annan hash som utdata. Om vi till exempel skickar in ordet "binance" istället för "Binance" skulle vi få följande hash som resultat:

59bba357145ca539dcd1ac957abc1ec5833319ddcae7f5e8b5da0c36624784b2

Hashes är användbara för att verifiera giltigheten av viss information, utan att avslöja vad informationen är. I praktiken kan hashfunktioner tillämpas på olika scenarier. Några få användningsfall inkluderar databassökningar, analyser av stora filer och datahantering.

I kombination med kryptografiska tekniker har vi de så kallade kryptografiska hashfunktionerna. Dessa används flitigt inom informationssäkerhet och är en viktig del av de flesta blockkedjenätverk.

Bitcoin blockchain har till exempel många operationer som involverar hashing, och dessa är avgörande i gruvprocessen.

## Höjdpunkter

– En hash är en funktion som möter de krypterade krav som behövs för att lösa för en blockchain-beräkning.

– En hash, som en nonce eller en lösning, är ryggraden i blockchain-nätverket.

- En hash utvecklas baserat på informationen som finns i blockhuvudet.

- Hashen har en fast längd eftersom det gör det nästan omöjligt att gissa längden på hashen om någon försökte knäcka blockkedjan.

– Samma data kommer alltid att producera samma hashade värde.

## Vanliga frågor

### Hur beräknas ett hashvärde?

En hashfunktion använder komplexa matematiska algoritmer som omvandlar data av godtycklig längd till data med fast längd (till exempel 256 tecken). Om du ändrar en bit var som helst i originaldatan ändras hela hashvärdet, vilket gör det användbart för att verifiera tillförlitligheten hos digitala filer och annan data.

### Vad används hash för i blockkedjor?

Hashes används i flera delar av ett blockchain-system. Först innehåller varje block hashen för [blockhuvudet](/block-header-cryptocurrency) för det föregående blocket, vilket säkerställer att inget har manipulerats när nya block läggs till. Utvinning av kryptovaluta med hjälp av [proof-of-work](/proof-work) (PoW) använder dessutom hash av slumpmässigt genererade tal för att komma fram till ett specifikt hashat värde som innehåller en serie inledande nollor. Denna godtyckliga funktion är resurskrävande, vilket gör det svårt för en dålig aktör att ta sig om nätverket.

### Vad är en hash-funktion?

Hashfunktioner är matematiska funktioner som omvandlar eller "mappar" en given datauppsättning till en bitsträng med fast storlek, även känd som "hashvärdet".

