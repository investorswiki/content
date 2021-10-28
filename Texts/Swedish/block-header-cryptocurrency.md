---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: Blockrubrik (kryptovaluta)
description: blockhuvud. Ett avsnitt i ett block som innehåller metadata och en sammanfattning av blockets transaktioner. Detta är informationen som hashas vid gruvdrift.
---

# Blockrubrik (kryptovaluta)
Blockhuvudet är en sektion i ett [block](/block) som fungerar som en sammanfattning av resten av blocket. Den består av all [metadata](/metadata) – som tid och [svårighet](/difficulty) när blocket bröts [,](/mining) Merkle [-roten](/merkle-tree) för de inkluderade transaktionerna och [nonce](/nonce). Det föregående blockets [hash finns också närvarande](/hash),. vilket är det som gör att vi kan skapa "kedjan" av block. I huvudsak innehåller blockhuvudet all data som inte är själva listan över råtransaktioner.

En blockrubrik är vad gruvarbetarna hash för att försöka göra blocket giltigt. Detta är mycket effektivare än att hasha hela blocket, som kan bestå av tusentals transaktioner. Det skulle vara mycket mer besvärligt för en gruvarbetare att ändra nonce och att rehash ett helt 2MB block för varje försök. Jämför detta med att hasha Bitcoins blockrubriker, till exempel, som har en fast längd på 80 byte.

Blockhuvuden är bra ur gruvsynpunkt, men på grund av sin lilla storlek är de också idealiska för lätta kunder. Bitcoin blockchain är för stor för enheter som smartphones att lagra. Om kedjan hade 100 000 1MB-block skulle du förbruka 100 GB utrymme. Men med bara blockhuvudena för samma block skulle du bara ta upp 0,008 GB eller 8 MB.

På detta sätt kan enheter med mindre bandbredd eller lagringsutrymme fortfarande utföra en viss grad av validering. Eftersom Merkle-roten kapslar in alla transaktioner kan de senare kontrollera om en transaktion ingick i ett visst block. Detta kommer till en kostnad – användaren måste fortfarande förlita sig på en tredje part för att förse dem med nödvändig information. Med det sagt är lätta klienter att föredra framför ett system där användarna inte utför någon verifiering alls.

##Höjdpunkter

- De hashas för att skapa ett bevis på arbete för gruvbelöningar.

- Blockhuvuden identifierar enskilda block i en blockkedja.

- Blocken är skiktade vertikalt, med början med "genesis-blocket."

– Bitcoinversionsnumret hjälper dig att hålla reda på ändringar i protokollet.

- Varje blockhuvud innehåller tre uppsättningar blockmetadata och flera enskilda komponenter.

