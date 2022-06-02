---
keywords: Crypto
title: BEP-95
description: BEP-95. BEP-95 ist ein Binance Evolution Proposal, der einen Echtzeit-Brennmechanismus in Binance Smart Chain einführt. Es macht die BNB-Tokenomik dynamischer und dezentralisierter.
---

# BEP-95
BEP-95 ist ein Binance Evolution Proposal, der einen Echtzeit-Brennmechanismus in Binance Smart Chain einführt. Es wurde eingeführt, um die Tokenomik von BNB noch dynamischer zu machen und das Netzwerk weiter zu dezentralisieren.

Mit BEP-95 wird das Netzwerk ein festes Verhältnis der Gasgebühren jedes Blocks verbrennen, die die Validatoren erheben. Das genaue Verhältnis wird über die Governance-Mechanismen von BSC festgelegt. Die Verbrennungen werden auch dann stattfinden, wenn BSC sein Ziel von 100 Millionen BNB erreicht hat. Durch die Reduzierung des BNB-Angebots wird der Preis der Münze nach oben gedrückt. Der BEP kann auch die Anzahl der empfangenen BNB-Delegatoren und -Validatoren verringern. Bei steigendem Preisdruck könnte jedoch auch der Fiat-Wert steigen, was eine Verringerung der Coins ausgleicht.

Um dies technisch umzusetzen, erhebt das Netzwerk die Gasgebühren jedes Blocks und teilt sie auf zwei intelligente Verträge auf:

**1. Systemprämienvertrag.** 1/16 der Gasgebühren gehen in den Systemprämienvertrag ein, bis dieser maximal 100 BNB erreicht. Diese Münzen werden als kettenübergreifende Paketsubventionen verwendet.

**2. ValidatorSet-Vertrag.** Alle anderen Gasgebühren werden in den ValidatorSet-Vertrag aufgenommen und täglich über die Binance Chain mit Delegierern und Validierern geteilt.

Um einen Burn durchzuführen, verfügt der ValidatorSet-Vertrag über eine BurnRatio-Variable. Nach Abschluss jedes Blocks unterzeichnet ein Validator eine Transaktion, die seine Gasgebühren an die Smart Contracts überweist. Die Einzahlungsfunktion enthält eine Brennlogik, die die einfache Formel auslöst: BurnRatio * gasFee. Diese Summe wird dann an die Brennadresse überwiesen. Das BurnRatio wird zunächst auf 10 % eingestellt.

BSC-Validatoren können über Vorschläge zur Änderung des BurnRatio-Betrags abstimmen. Dieser Governance-Mechanismus findet auf Binance Chain statt, und jedes Community-Mitglied kann einen Vorschlag zur Überprüfung mit einer Mindesteinzahlung von 2.000 BNB einreichen. Alle BNB, die hinter einem Vorschlag und in einer Abstimmung stehen, werden zurückgegeben, nachdem eine Entscheidung getroffen wurde. Das Quorum ist bei 50 % erreicht, und die Änderung wird sofort über die kettenübergreifende Kommunikation implementiert.

