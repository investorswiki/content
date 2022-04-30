---
keywords: Crypto
title: Insvept eter (WETH)
description: Inlindad eter (WETH). ERC-20-token som representerar Ether i förhållandet 1:1. Det tillåter användare att handla ETH till ERC-20-tokens på decentraliserade plattformar.
---

# Insvept eter (WETH)
Wrapped Ether (WETH) hänvisar till den [ERC-20-](/erc-20) kompatibla versionen av eter (inpackning av eter med andra ERC-standarder är också möjligt). WETH kan skapas genom att skicka eter till ett smart kontrakt där etern placeras på is, i sin tur får WETH ERC-20-token i förhållandet 1:1. Denna WETH kan sedan skickas tillbaka till samma smarta kontrakt för att "packas upp" eller lösas in tillbaka för den ursprungliga etern i ett förhållande på 1:1.

Ether, som är den ursprungliga valutan på Ethereum-blockkedjan, skapades innan ERC-20-standarden och andra standarder implementerades; därför är eter i sig inte ERC-20-kompatibelt och kan inte bytas direkt mot andra ERC-20-tokens på ett decentraliserat sätt utan medling av en pålitlig tredje part eller tillägg av komplexa tekniska implementeringar. Istället för att implementera två gränssnitt (ett för eter och ett annat för ERC-20-tokens) inom samma smarta kontrakt som leder till onödig komplexitet, bestämde sig utvecklare för att "linda" eter för att uppgradera den till ERC-20-standarden för att bekvämt hantera WETH och andra ERC-20 inom samma kontrakt. Inpackning av eter möjliggör ett direkt, sömlöst utbyte mellan eter och ERC-20-tokens utan behov av en pålitlig tredje part och utan att det uppstår onödiga risker som oväntade fel under transaktioner som är ett resultat av komplexa implementeringar. Många Ethereum-baserade [decentraliserade applikationer (dApps)](/decentralized-applications-dapps) som [decentraliserade](/decentralized-exchange) börsplattformar använder WETH i stället för eter för att underlätta direkt och decentraliserad peer-to-peer-handel mellan eter i "inpackad form" och ERC-20-tokens under samma tekniska standard. Den senaste utvecklingen försöker ha en kanonisk WETH-standard som kan användas av alla Ethereum-baserade dApps.

