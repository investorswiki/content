---
keywords: Crypto
title: Asynkron
description: asynkron. Händelser i elektroniska system som inte inträffar samtidigt eller hastighet, eller sker oberoende av huvudprogramflödet.
---

# Asynkron
Gemenskapsbidrag - Författare: **Caner Taçoğlu**

Asynkron betyder inte samtidigt, eller inte sker samtidigt eller hastighet. Inom datavetenskap avser asynkroni förekomsten av händelser som är oberoende av huvudprogrammet.

I ett asynkront system koordineras operationer inte av en global klocksignal, utan snarare händelser (förändringar i systemet). Asynkrona system är inte beroende av externa signaler eller meddelanden för sin tillförlitliga funktion.

Asynkrona system är ofta designade med ett modulärt ramverk. I sådana system kan varje modul fungera självständigt och har förmågan att kommunicera med andra moduler. Dessa sammankopplade moduler bildar sedan tillsammans ett fungerande system.

Asynkron kommunikation är när data kan överföras oregelbundet, istället för i en jämn ström. Vanliga exempel är e-post eller onlineforum, där deltagare skickar meddelanden vid olika tidpunkter.

Blockkedjor kan vara asynkrona eller semisynkrona nätverk.

Asynkrona nätverk förser inte noderna med någon återkoppling om status för den information som skickas, vilket kan leda till att noder har olika syn på nätverkets övergripande tillstånd. I huvudsak behöver noder inte vänta på att andra noder ska ta emot sina meddelanden, vilket kan öka transaktionsgenomströmningen.

Halvsynkrona nätverk syftar till att säkerställa att det aldrig sker en splittring i nätverkets globala tillstånd. Om nätverket är partitionerat kommer konsensus mellan noderna att sakta ner tills det återställs igen.

Asynkrona eller semisynkrona blockkedjenätverk kan utformas oavsett om de ska prioritera konsekvens eller tillgänglighet. Om nätverket vill prioritera tillgänglighet läggs alla transaktioner till utan några stillestånd. Om nätverket vill prioritera konsekvens kanske vissa transaktioner inte bearbetas eller stoppas förrän alla tidigare transaktioner har bekräftats.

Vissa blockchain-designer använder en implementering av Bysantine Fault Tolerance (BFT) som kallas Asynchronous Byzantine Fault Tolerance (aBFT). Det garanterar matematiskt att konsensus så småningom uppnås även om en angripare kontrollerar nästan en tredjedel av nätverket. Asynkron innebär i detta sammanhang att inga antaganden görs om timing.

