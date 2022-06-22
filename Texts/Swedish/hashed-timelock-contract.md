---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Crypto,Strategy and Education
title: Hashed Timelock Contract (HTLC)
description: Hashed TimeLock-kontrakt (HTLC). Avser en speciell funktion som används för att skapa smarta kontrakt som kan modifiera betalningskanaler.
---

# Hashed Timelock Contract (HTLC)
Termen Hashed TimeLock Contract (HTLC) syftar på en speciell funktion som används för att skapa [smarta kontrakt](/smart-contract) som kan modifiera betalningskanaler. Tekniskt sett möjliggör HTLC-funktionen implementering av tidsbundna transaktioner mellan två användare. I praktiken måste mottagaren av en HTLC-transaktion bekräfta betalningen genom att skicka in ett kryptografiskt bevis inom en angiven tidsram (antal block). Om mottagaren förlorar eller misslyckas med att göra anspråk på betalningen kommer pengarna att returneras till den ursprungliga avsändaren.

HTLC-funktionen används i både dubbelriktade och dirigerade betalningskanaler för att möjliggöra säkra överföringar av pengar över olika kanaler, utan att behöva förtroende för någon av mellanhänderna.

Det finns två nyckelelement som skiljer HTLC från vanliga kryptovalutatransaktioner, som är:

- Hashlock: en funktion som begränsar utgifterna för pengar tills en viss del av data offentliggörs (som ett kryptografiskt bevis). Sådant bevis kan också kallas förbilden av hashlocket. Förbilden är helt enkelt den information som används för att generera hashlocket och för att senare låsa upp dess medel.

- Timelock: är en funktion som begränsar utgifterna för pengar till en viss tidpunkt (eller blockhöjd) i framtiden. Det kan uppnås i Bitcoin, till exempel genom att använda funktioner som CheckLockTimeVerify eller CheckSequenceVerify.

Bitcoin Lightning Network är bland de mest populära användningsfallen av hashed Timelocked Contracts. Genom att implementera HTLC i betalningskanaler kan pengar överföras från användare till användare genom sammanlänkade betalningskanaler, utan att det krävs någon nivå av förtroende. Denna process är känd som nätverksrouting. Det gör att Alice kan byta pengar med Carol även om de inte är direkt anslutna via en betalningskanal. HTLC gör det möjligt för Alice att skicka sina pengar till Carol genom andra deltagare i nätverket (t.ex. Bob) - och hashlock- och timelock-funktionerna säkerställer att Bob inte kan fånga upp pengarna.

Förutom att användas på Lightning Network, kan HTLC:er också vara användbara i andra sammanhang, såsom cross-chain [atomic swaps](/atomic-swaps),. finansiella smarta kontrakt och deposition, och mycket mer.

## Höjdpunkter

– Betalningar med HTLC är villkorade och har därför effektivitetsfördelar för blockchain-transaktioner. Denna egenskap gör HTLC till ett grundläggande verktyg som används av lightning-nätverket.

– Den här typen av smarta kontrakt kräver att mottagaren av en betalning bekräftar den inom en viss tid eller förverkar den.

- Ett hashed timelock-kontrakt (HTLC) minskar motpartsrisken i decentraliserade smarta kontrakt genom att effektivt skapa en tidsbaserad deposition som använder en kryptografisk lösenfras.

## Vanliga frågor

### Hur mycket kostar ett smart kontrakt?

På Ethereum blockchain tar en smart kontraktsinstallation gas, vilket kostar Gwei (en lägre valör av eter). Beroende på kontraktets komplexitet kan det kosta miljarder Gwei att implementera ett smart kontrakt. Mindre komplexa kontrakt som ett enkelt byte är mycket billigare.

### Vad är ett smart kontrakt?

Ett smart kontrakt är ett program lagrat på en blockchain som körs när specifika villkor är uppfyllda.

### Vad är ett Timelock-kontrakt?

Ett timelock-kontrakt är ett smart kontrakt inbäddat i en blockkedja som utför en transaktion vid en specifik tidpunkt. De används i hashade timelock-kontrakt och betalningskanaler där specifika betalningstider behövs.

### Har Bitcoin smarta kontrakt?

Till en början kunde inte Bitcoins blockchain utföra smarta kontrakt. Taproot-uppgraderingen 2021 gjorde det dock möjligt för blockkedjan att använda smarta kontrakt i transaktioner.

