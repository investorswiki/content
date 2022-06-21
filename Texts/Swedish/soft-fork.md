---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: mjuk gaffel
description: En soft fork är en ändring av mjukvaruprotokollet där endast tidigare giltiga block/transaktioner görs ogiltiga.
---

# mjuk gaffel
## Vad är en mjuk gaffel?

Inom [blockchain](/blockchain) -teknik är en soft fork en förändring av mjukvaruprotokollet där endast tidigare giltiga transaktionsblock görs ogiltiga. Eftersom gamla noder kommer att känna igen de nya blocken som giltiga, är en mjuk gaffel bakåtkompatibel. Den här typen av gaffel kräver bara en majoritet av gruvarbetarna som uppgraderar för att upprätthålla de nya reglerna, till skillnad från en [hård gaffel](/hard-fork) som kräver att alla noder uppgraderar och kommer överens om den nya versionen.

## Förstå användningen av Soft Forks

Nya transaktionstyper kan ofta läggas till som mjuka gafflar, vilket endast kräver att deltagarna (t.ex. avsändare och mottagare) och gruvarbetare förstår den nya transaktionstypen. Detta görs genom att få den nya transaktionen att framstå för äldre kunder som en "betala-till-alla"-transaktion (av en speciell form) och få gruvarbetarna att gå med på att avvisa blockeringar inklusive dessa transaktioner om inte transaktionen valideras enligt de nya reglerna. Detta är hur pay-to-script hash (P2SH) lades till [bitcoin](/bitcoin).

<!--EBEA97D1328C14134D5D1DA0AA69478A-->

En mjuk gaffel kan också uppstå ibland på grund av en tillfällig divergens i blockkedjan när gruvarbetare som använder icke-uppgraderade noder bryter mot en ny konsensusregel som deras noder inte känner till.

Mjuka gafflar kräver inga noder för att uppgradera för att bibehålla konsensus, eftersom alla block med de nya mjuka ingafflade reglerna också följer de gamla reglerna, därför accepterar gamla kunder dem. Mjuka gafflar kan inte vändas utan en hård gaffel eftersom en mjuk gaffel per definition bara tillåter uppsättningen av giltiga block att vara en riktig delmängd av vad som var giltig förgaffel. Om användare uppgraderar till en post-soft fork-klient och av någon anledning en majoritet av gruvarbetare byter tillbaka till pre-soft fork-klienten, skulle användarna av post-soft fork-klienten bryta konsensus så snart ett block kom som inte följde sina kunders nya regler. För att en mjuk gaffel ska fungera måste en majoritet av gruvkraften köra en klient som känner igen gaffeln. Ju fler gruvarbetare som accepterar de nya reglerna, desto säkrare är nätverket efter gaffel. Om du har 3/4 av gruvarbetarna som känner igen gaffeln, är det inte garanterat att 1/4 skapade block följer de nya reglerna. Dessa 1/4-block kommer att vara giltiga för gamla noder som inte är medvetna om de nya reglerna, men de kommer att ignoreras av nya noder.

Mjuka gafflar har använts på blockkedjorna bitcoin och [ethereum](/ethereum),. bland annat, för att implementera nya och uppgraderade funktioner som är bakåtkompatibla.

