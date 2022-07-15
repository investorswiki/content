---
keywords: Crypto
title: Ubrugt transaktionsoutput (UTXO)
description: Ubrugt transaktionsoutput (UTXO). Et output oprettet i en transaktion, som skal refereres til i en fremtidig transaktion for at bruge midler.
---

# Ubrugt transaktionsoutput (UTXO)
Et ubrugt transaktionsoutput (UTXO) refererer til et transaktionsoutput, der kan bruges som input i en ny transaktion. I det væsentlige definerer UTXO'er, hvor hver blockchain-transaktion starter og slutter. UTXO-modellen er et grundlæggende element i Bitcoin og mange andre kryptovalutaer.

Med andre ord er kryptovalutatransaktioner lavet af input og output. Hver gang der foretages en transaktion, tager en bruger en eller flere UTXO'er til at fungere som input(er). Dernæst giver brugeren deres digitale signatur for at bekræfte ejerskab over inputs, hvilket til sidst resulterer i output. De forbrugte UTXO'er betragtes nu som "brugte" og kan ikke længere bruges. I mellemtiden bliver output fra transaktionen til nye UTXO'er - som kan bruges i en ny transaktion senere.

Dette er nok bedre forklaret med et eksempel. Alice har 0,45 BTC i sin pung. Dette er ikke en brøkdel af en mønt, som vi måske forestiller os det. Det er snarere en samling UTXO'er. Specifikt to UTXO'er værd 0,4 BTC og 0,05 BTC - output fra tidligere transaktioner. Lad os nu forestille os, at Alice skal foretage en betaling til Bob på 0,3 BTC.

Hendes eneste mulighed her er at bryde 0,4 BTC-enheden op og sende 0,3 BTC til Bob og 0,1 BTC tilbage til sig selv. Hun ville normalt tilbagekræve mindre end 0,1 BTC på grund af minegebyrer, men lad os forenkle og udelade minearbejderen.

Alice opretter en transaktion, der i det væsentlige siger til netværket: tag min 0,4 BTC UTXO som input, bryd den op, send 0,3 BTC af den til Bobs adresse og returner 0,1 BTC til min adresse. 0,4 BTC er nu et brugt output og kan ikke genbruges. I mellemtiden er to nye UTXO'er blevet oprettet (0,3 BTC og 0,1 BTC).

Bemærk, at vi har brudt en UTXO op i dette eksempel, men hvis Alice skulle betale 0,42 BTC, kunne hun lige så nemt have kombineret sine 0,4 BTC med yderligere 0,05 BTC for at producere en UTXO værd 0,42 BTC, mens hun havde returneret 0,03 BTC til sig selv.

Sammenfattende fungerer UTXO-modellen som protokollens mekanisme til at holde styr på, hvor mønter er på et givet tidspunkt. På en måde fungerer de meget som checks: de er rettet til bestemte brugere (eller rettere, deres offentlige [adresser](/address) ). UTXO'er kan ikke bruges delvist - i stedet skal nye checks oprettes fra den gamle og videregives i overensstemmelse hermed.

