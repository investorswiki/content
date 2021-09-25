---
keywords: Crypto
title: Innpakket eter (WETH)
description: Innpakket eter (WETH). ERC-20-token som representerer Ether i forholdet 1:1. Det lar brukere handle ETH til ERC-20-tokens på desentraliserte plattformer.
---

# Innpakket eter (WETH)
Wrapped Ether (WETH) refererer til den [ERC-20-](/erc-20) kompatible versjonen av eter (innpakning av eter med andre ERC-standarder er også mulig). WETH kan opprettes ved å sende eter til en smart kontrakt der eteren settes på vent, og mottar i sin tur WETH ERC-20-tokenet i forholdet 1:1. Denne WETH kan etterpå sendes tilbake til den samme smarte kontrakten for å "pakkes ut" eller innløses tilbake for den originale eteren i forholdet 1:1.

Ether, som er den opprinnelige valutaen på Ethereum-blokkjeden, ble opprettet før ERC-20-standarden og andre standarder ble implementert; Derfor er ether i seg selv ikke ERC-20-kompatibel og kan ikke byttes direkte mot andre ERC-20-tokens på en desentralisert måte uten formidling av en pålitelig tredjepart eller tillegg av komplekse tekniske implementeringer. I stedet for å implementere to grensesnitt (ett for eter og et annet for ERC-20-tokens) innenfor den samme smarte kontrakten som fører til unødvendig kompleksitet, bestemte utviklerne seg for å "pakke inn" eter for å oppgradere den til ERC-20-standarden for å enkelt håndtere WETH og andre ERC-20-er innenfor samme kontrakt. Innpakning av eter tillater direkte, sømløs utveksling mellom eter og ERC-20-tokens uten behov for en pålitelig tredjepart og uten å pådra seg unødvendige risikoer som uventede feil under transaksjoner som følge av komplekse implementeringer. Mange Ethereum-baserte [desentraliserte applikasjoner (dApps)](/decentralized-applications-dapps) som [desentraliserte utvekslingsplattformer](/decentralized-exchange) bruker WETH i stedet for eter for å lette direkte og desentralisert peer-to-peer-handel mellom eter i "innpakket form" og ERC-20-tokens under samme tekniske standard. Nylig utvikling prøver å ha en kanonisk WETH-standard som kan brukes av alle Ethereum-baserte dApps.

