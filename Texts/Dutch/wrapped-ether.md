---
keywords: Crypto
title: Indpakket ether (WETH)
description: Indpakket Ether (WETH). ERC-20-token, der repræsenterer Ether i et 1:1-forhold. Det giver brugere mulighed for at handle ETH til ERC-20 tokens på decentraliserede platforme.
---

# Indpakket ether (WETH)
Wrapped Ether (WETH) henviser til den [ERC-20-](/erc-20) kompatible version af ether (indpakning af ether med andre ERC-standarder er også muligt). WETH kan oprettes ved at sende ether til en smart kontrakt, hvor etheren er sat på hold, og til gengæld modtager WETH ERC-20-tokenet i forholdet 1:1. Denne WETH kan bagefter sendes tilbage til den samme smarte kontrakt for at blive "udpakket" eller indløst tilbage til den originale ether i et 1:1-forhold.

Ether, der er den oprindelige valuta på Ethereum blockchain, blev oprettet før ERC-20 standarden og andre standarder blev implementeret; Derfor er ether ikke i sig selv ERC-20-kompatibel og kan ikke ombyttes direkte til andre ERC-20-tokens på en decentral måde uden formidling af en betroet tredjepart eller tilføjelse af komplekse tekniske implementeringer. I stedet for at implementere to grænseflader (en for ether og en anden for ERC-20-tokens) inden for den samme smarte kontrakt, der fører til unødvendig kompleksitet, besluttede udviklere at "pakke" ether for at opgradere den til ERC-20-standarden for bekvemt at håndtere WETH og andre ERC-20'er inden for samme kontrakt. Indpakning af ether giver mulighed for direkte, problemfri udveksling mellem ether og ERC-20-tokens uden behov for en betroet tredjepart og uden at pådrage sig unødvendige risici såsom uventede fejl under transaktioner som følge af komplekse implementeringer. Mange Ethereum-baserede [decentraliserede applikationer (dApps)](/decentralized-applications-dapps) såsom [decentraliserede udvekslingsplatforme](/decentralized-exchange) bruger WETH i stedet for ether for at lette den direkte og decentraliserede peer-to-peer-handel mellem ether i "indpakket form" og ERC-20-tokens under samme tekniske standard. Den seneste udvikling forsøger at have en kanonisk WETH-standard, der kan bruges af alle Ethereum-baserede dApps.

