---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: Merkle träd
description: Merkle träd. Ett sätt att organisera och strukturera stora mängder data för att göra det enklare att bearbeta. En hash-baserad datastruktur.
---

# Merkle träd
Ett Merkle-träd är ett sätt att organisera och strukturera stora mängder data för att göra det enklare att bearbeta. När det gäller kryptovaluta och [blockchain](/blockchain) används Merkle-trädet för att strukturera transaktionsdata på ett sätt som är mindre resurskrävande.

När en kryptovalutatransaktion görs i en Merkle-trädstruktur hashas den och får sedan ett motsvarande hashvärde. Efter att varje transaktion hashas i Merkle-trädet, paras hashvärdena som produceras med ett annat hashvärde och hashas sedan igen. Till exempel kombineras hash-värdena 'AB' och 'AC' för att skapa 'ABC'.

Denna process att para ihop hashvärden upprepas tills ett slutligt hashvärde produceras. Det slutliga hashvärdet, Merkle-roten, ger en sammanfattning av alla transaktioner den innehåller. Merkle rotsammanfattningen infogas sedan i blockhuvudet.

#### Datasäkerhet

En Merkle-trädstruktur ger en lättillgänglig registrering av transaktionerna i ett [block](/block). Så det är väldigt enkelt att kontrollera om data i ett block har ändrats eller manipulerats. Detta är sant eftersom varje ändring av en transaktion (eller någon annan relaterad data) i Merkle-trädet skulle leda till en helt annan motsvarande Merkle-rot.

#### Effektiv användning av resurser

Om kryptovalutor inte använde Merkle-träd, skulle varje verifieringsförfrågan innebära enorma mängder information som skickas över nätverket. Att strukturera transaktionsdata i ett Merkle-träd är en mycket effektivare användning av resurser. Validering av en transaktion kräver inte en fullständig kopia av huvudboken eftersom hashade transaktionsdata kan verifieras i en Merkle-rot, vilket kräver mycket mindre information som skickas över noderna och därmed mindre datorkraft för att analysera den övergripande dataintegriteten.

Med andra ord, en Merkle-trädstruktur gör det möjligt för användare att verifiera att en enskild transaktion har inkluderats i ett block utan att behöva gå igenom processen att ladda ner hela blockkedjan. Tekniken är ett viktigt verktyg för kryptovalutor att organisera transaktionsdata och fungera lika effektivt som de gör. Utan Merkle-träd är det troligt att den större efterfrågan på resurser skulle leda till att färre [noder](/node) deltar i nätverket.

