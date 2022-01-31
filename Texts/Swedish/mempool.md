---
keywords: Crypto
title: Mempool
description: Mempool. En nods mekanism för att hålla reda på obekräftade transaktioner som noden har sett (men ännu inte lagts till i ett block).
---

# Mempool
En mempool (en sammandragning av minne och pool) är en kryptovalutanods mekanism för att lagra information om obekräftade transaktioner. Det fungerar som ett slags väntrum för transaktioner som ännu inte har inkluderats i ett [block](/block).

När en transaktion sänds skickas den från en nod till dess peers, som sedan skickar den vidare till sina peers. Detta fortsätter tills transaktionen har spridits brett, redo för gruvarbetare att lägga till den i ett block. Det är viktigt att denna buffertzon finns, eftersom transaktioner inte läggs till blockkedjan omedelbart.

Noder kommer att köra en serie kontroller för att säkerställa att transaktionen är giltig – dvs att verifiera att signaturerna är korrekta, att utdata inte överstiger indata och att pengar inte redan har spenderats. Om den inte uppfyller dessa villkor avvisas den.

Vi talar ofta om mempoolen, men det bör noteras att det inte finns någon universell pool som delas av alla noder. Var och en är konfigurerad på olika sätt och tar emot transaktioner vid olika tidpunkter. Lägre enheter med begränsade resurser kan bara ägna små mängder minne till att logga transaktioner, medan avancerade enheter kan ägna betydligt mer.

Eftersom gruvarbetare främst motiveras av vinster, är transaktioner med högre avgifter de som med största sannolikhet kasseras från mempoolen först när de har bekräftats. Att noggrant uppskatta avgifter är svårt, särskilt när blockutrymmet är begränsat och efterfrågan är hög, men mempoolen ger en utgångspunkt.

För att uppskatta avgifter kan man titta på de aktuella obekräftade transaktionerna. Det är naturligt att användare inte ska betala för mycket i tider med låg genomströmning. De ska inte heller underbetala för tidskänsliga transaktioner under högtrafik, eftersom det kan ta ett tag innan det blir bekräftat. Genom att ta hänsyn till spridningen av avgifter vid ett givet tillfälle kan de göra en välgrundad gissning om hur snabbt deras transaktion kommer att inkluderas.

