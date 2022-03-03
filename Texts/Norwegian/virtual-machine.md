---
keywords: Crypto
title: Virtuell maskin
description: Virtuell maskin. Et emulert datasystem, eller et distribuert system som er designet for å gjenskape funksjonene til en datamaskins arkitektur.
---

# Virtuell maskin
En virtuell maskin (VM) er et program som emulerer et datasystem. Den har en virtuell CPU, minne og lagring og ser ut, fra utsiden, ikke ut til å være annerledes enn en fysisk maskin med samme maskinvare.

## Hvordan fungerer en virtuell maskin?

En virtuell maskin har et operativsystem, filer og applikasjoner. Den fungerer akkurat som en fysisk datamaskin; den kan være vert for nettsteder, kjøre programmer og eksistere på et nettverk med andre systemer. Hvis den vises på en skjerm, vises den virtuelle maskinen som et vindu som kjører i datamaskinens eget operativsystem.

Den har også en CPU, minne og lagring, men disse er simulerte, ikke fysiske. På grunn av dette kan flere virtuelle maskiner sameksistere på én server. Når dette skjer, bruker serveren et stykke programvare kalt en hypervisor for å administrere dem. Hypervisoren kartlegger VMs virtuelle maskinvare til de fysiske komponentene på serveren.

I dette scenariet kan en fysisk server ha to, tre, fire eller ti virtuelle maskiner som kjører på den. Antallet er imidlertid begrenset av ressursene til serveren – for mange VM-er vil føre til redusert ytelse.

## Hvorfor brukes virtuelle maskiner?

Virtuelle maskiner er sandkasser – deler av virtuelt rom hvor kode kan kjøres separat fra resten av systemet. Dette gjør VM-er ideelle for å teste ny programvare eller kjøre kode som kan være skadelig.

Den virtuelle maskinen kan kjøre et annet eller eldre operativsystem for å gjøre det mulig for en bruker å kjøre programvare som ikke fungerer på datamaskinens operativsystem. For eksempel kan noen bruke en VM til å kjøre et stykke Windows-programvare på en Linux-enhet. For å oppnå dette, ville de kjøre en virtuell maskin som kjører et Windows-operativsystem på deres Linux-system.

## Nøkkeleksempel: Ethereum Virtual Machine (EVM)

Nodene på Ethereum-nettverket kjører alle Ethereum Virtual Machine (EVM), som brukes til å utføre smarte kontrakter. Fordi dette skjer i en egen sandkasse, gir det betydelige sikkerhetsfordeler for Ethereum-plattformen, noe som gjør den immun mot DDoS (Distributed Denial of Service-angrep som er en god strategi for mange hackere.

