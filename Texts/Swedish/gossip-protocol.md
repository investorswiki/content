---
keywords: Crypto
title: Skvallerprotokoll
description: Skvallerprotokoll. En speciell metod för asynkron peer-to-peer-kommunikation mellan datornoder i ett distribuerat system.
---

# Skvallerprotokoll
Termen skvallerprotokoll syftar på en specifik typ av P2P-kommunikation (peer-to-peer) som sker mellan datorer och andra digitala enheter. Myntningen av begreppet inspirerades av den konventionella formen av skvaller som är vanlig inom sociala grupper.

I datavetenskapssammanhang är skvallerprotokoll relaterat till en sorts kommunikation som sker när data överförs genom olika datornoder, som ingår i ett distribuerat nätverk. Som namnet antyder sker en skvallerprotokollkommunikation när information sänds från en dator till en annan tills den så småningom sprids över hela nätverket. För närvarande finns det många varianter av Gossip-protokollet som kan tillämpas på olika scenarier beroende på användarens eller organisationens behov.

Enligt professor Márk Jelasity från universitetet i Szeged finns det två huvudtyper av skvallermanifestationer: informationsspridning och informationsaggregation. Dessa två typer är nyckelelement i distribuerade system i stor skala.

Å ena sidan avser skvallerspridning, även känd som multicast, det traditionella sättet att distribuera data (en nätverksnod i taget). Å andra sidan är de aggregerande skvallerprotokollen de som bearbetar data, dvs som först sammanfattar information och sedan distribuerar den (denna typ av skvallerkommunikation kan också kallas distribuerad datautvinning).

Ett intressant exempel på ett distribuerat system som använder ett skvallerprotokoll är Hashgraph som skapades av Leemon Baird 2016. Det är en distribuerad ledger-teknologi som använder en asynkron bysantinsk feltolerans (aBFT) konsensusalgoritm. Noderna i ett Hashgraph-nätverk samlar in och sammanfattar information om transaktioner och andra händelser och sprider dessa data till andra grannoder som väljs slumpmässigt. Så istället för att bygga en kedja av block bygger Hashgraph-nätverket ett träd av händelser där all information registreras (ingen data kasseras någonsin).

