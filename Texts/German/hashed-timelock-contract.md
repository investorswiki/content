---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Crypto,Strategy and Education
title: Gehashter Timelock-Vertrag (HTLC)
description: Gehashter TimeLock-Vertrag (HTLC). Bezieht sich auf eine spezielle Funktion, die verwendet wird, um intelligente Verträge zu erstellen, die Zahlungskanäle ändern können.
---

# Gehashter Timelock-Vertrag (HTLC)
Der Begriff Hashed TimeLock Contract (HTLC) bezieht sich auf eine spezielle Funktion, die verwendet wird, um [Smart Contracts zu erstellen](/smart-contract),. die in der Lage sind, Zahlungskanäle zu modifizieren. Technisch gesehen ermöglicht die HTLC-Funktion die Implementierung von zeitgebundenen Transaktionen zwischen zwei Benutzern. In der Praxis muss der Empfänger einer HTLC-Transaktion die Zahlung bestätigen, indem er einen kryptografischen Beweis innerhalb eines bestimmten Zeitrahmens (Anzahl der Blöcke) einreicht. Wenn der Empfänger die Zahlung verfällt oder nicht einfordert, wird das Geld an den ursprünglichen Absender zurückerstattet.

Die HTLC-Funktion wird sowohl in bidirektionalen als auch in gerouteten Zahlungskanälen angewendet, um sichere Geldtransfers über verschiedene Kanäle zu ermöglichen, ohne Vertrauen in einen der Vermittler zu erfordern.

Es gibt zwei Schlüsselelemente, die HTLC von Standard-Kryptowährungstransaktionen unterscheiden:

- Hashlock: eine Funktion, die die Ausgabe von Geldern einschränkt, bis ein bestimmtes Datenelement öffentlich bekannt gegeben wird (als kryptografischer Beweis). Ein solcher Beweis kann auch als das Urbild des Hashlocks bezeichnet werden. Das Pre-Image ist einfach die Information, die verwendet wird, um den Hashlock zu generieren und später seine Gelder freizuschalten.

- Timelock: ist eine Funktion, die die Ausgabe von Geldern bis zu einem bestimmten Zeitpunkt (oder Blockhöhe) in der Zukunft einschränkt. Dies kann beispielsweise bei Bitcoin durch Funktionen wie CheckLockTimeVerify oder CheckSequenceVerify erreicht werden.

Das Bitcoin Lightning Network gehört zu den beliebtesten Anwendungsfällen von Hashed Timelocked Contracts. Durch die Implementierung von HTLC in Zahlungskanäle können Gelder von Benutzer zu Benutzer über miteinander verbundene Zahlungskanäle übertragen werden, ohne dass ein gewisses Maß an Vertrauen erforderlich ist. Dieser Vorgang wird als Netzwerk-Routing bezeichnet. Es ermöglicht Alice, Geld mit Carol auszutauschen, auch wenn sie nicht direkt über einen Zahlungskanal verbunden sind. HTLCs ermöglichen es Alice, ihre Gelder über andere Teilnehmer des Netzwerks (z. B. Bob) an Carol zu senden – und die Hashlock- und Timelock-Funktionen stellen sicher, dass Bob die Gelder nicht abfangen kann.

Neben der Verwendung im Lightning Network können HTLCs auch in anderen Kontexten nützlich sein, wie z. B. Cross-Chain- [Atomic-Swaps](/atomic-swaps),. Financial Smart Contracts und Escrow und vieles mehr.

## Höhepunkte

- Zahlungen mit HTLCs sind bedingt und haben daher Effizienzvorteile für Blockchain-Transaktionen. Diese Eigenschaft macht HTLCs zu einem grundlegenden Werkzeug, das vom Lightning-Netzwerk verwendet wird.

- Diese Art von Smart Contract erfordert, dass der Empfänger einer Zahlung diese innerhalb einer bestimmten Frist anerkennt oder verfällt.

- Ein gehashter Timelock-Vertrag (HTLC) reduziert das Kontrahentenrisiko in dezentralisierten Smart Contracts, indem er effektiv eine zeitbasierte Treuhand erstellt, die eine kryptografische Passphrase verwendet.

## FAQ

### Wie viel kostet ein Smart Contract?

Auf der Ethereum-Blockchain kostet eine Smart-Contract-Bereitstellung Gas, was Gwei (eine niedrigere Stückelung von Ether) kostet. Abhängig von der Komplexität des Vertrags kann es Milliarden von Gwei kosten, einen Smart Contract einzusetzen. Weniger komplexe Verträge wie ein einfacher Austausch sind viel billiger.

### Was ist ein Smart Contract?

Ein Smart Contract ist ein auf einer Blockchain gespeichertes Programm, das ausgeführt wird, wenn bestimmte Bedingungen erfüllt sind.

### Was ist ein Timelock-Vertrag?

Ein Timelock-Vertrag ist ein in eine Blockchain eingebetteter intelligenter Vertrag, der eine Transaktion zu einem bestimmten Zeitpunkt ausführt. Sie werden in Hash-Timelock-Verträgen und Zahlungskanälen verwendet, bei denen bestimmte Zahlungszeiten erforderlich sind.

### Hat Bitcoin Smart Contracts?

Anfangs war die Blockchain von Bitcoin nicht in der Lage, Smart Contracts auszuführen. Das Taproot-Upgrade im Jahr 2021 ermöglichte es der Blockchain jedoch, Smart Contracts in Transaktionen zu verwenden.

