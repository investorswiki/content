---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Kapazitätsnachweis (Kryptowährung)
description: Proof of Capacity ist ein Konsensmechanismus, der den Festplattenspeicher eines Mining-Knotens verwendet, um über die Mining-Rechte im Blockchain-Netzwerk zu entscheiden.
---

# Kapazitätsnachweis (Kryptowährung)
## Was ist ein Kapazitätsnachweis (PoC) für Kryptowährungen?

Proof of Capacity (PoC) ist ein [Konsensmechanismus -](/consensus-mechanism-cryptocurrency) Algorithmus, der in Blockchains verwendet wird und es [Mining-](/bitcoin-mining) Geräten im Netzwerk ermöglicht, ihren verfügbaren Festplattenspeicher zu nutzen, um über Mining-Rechte zu entscheiden und Transaktionen zu validieren. Dies steht im Gegensatz zur Verwendung der Rechenleistung des Mining-Geräts (wie beim [Proof-of-Work](/proof-work) -Algorithmus) oder des Anteils des Miners an den Kryptowährungen (wie beim [Proof-of-Stake -](/proof-stake-pos) Algorithmus).

## Kapazitätsnachweis verstehen

Der Kapazitätsnachweis hat sich als eine der vielen alternativen Lösungen für das Problem des hohen Energieverbrauchs in Proof-of-Work-Systemen (PoW) und des Hortens von Kryptowährung in Proof-of-Stake-Systemen (PoS) herausgestellt.

Der Kapazitätsnachweis ermöglicht es den Mining-Geräten, auch bekannt als Nodes, im [Blockchain](/blockchain) -Netzwerk, leeren Speicherplatz auf ihrer Festplatte zu nutzen, um die verfügbaren [Kryptowährungen abzubauen](/cryptocurrency).

Anstatt wie in einem PoW-System die Zahlen im Block-Header wiederholt zu ändern und den Lösungswert wiederholt zu hashen, funktioniert PoC, indem es eine Liste möglicher Lösungen auf der Festplatte des Mining-Geräts speichert, noch bevor die Mining-Aktivität beginnt.

Je größer die Festplatte, desto mehr mögliche Lösungswerte kann man auf der Festplatte speichern, desto mehr Chancen hat ein Miner, den erforderlichen Hash-Wert aus seiner Liste zu finden, was zu mehr Chancen führt, die Mining-Belohnung zu gewinnen.

Um eine Analogie zu ziehen: Wenn Lotteriebelohnungen darauf basieren, dass die meisten Zahlen auf dem Gewinnschein übereinstimmen, dann hat ein Spieler mit einer längeren Liste möglicher Lösungen bessere Gewinnchancen. Darüber hinaus ist es dem Spieler erlaubt, die Lottoschein-Blocknummern immer wieder wiederholt zu verwenden.

[Burstcoin](/burstcoin) ist eine Kryptowährung, die ein Proof-of-Capacity-System verwendet. Andere Münzen, die es verwenden, sind Storj, Chia und SpaceMint.

## So funktioniert PoC: Plotten und Mining

Das Proof-of-Capacity-Protokoll umfasst einen zweistufigen Prozess, der Plotting und Mining umfasst.

Zuerst wird die Festplatte geplottet: Die Liste aller möglichen [Nonce](/nonce) -Werte wird durch wiederholtes Hashing von Daten erstellt, einschließlich eines Miner-Kontos. Jede dieser Nonce enthält 8192 Hashes, die von 0 bis 8191 nummeriert sind. Alle Hashes werden zu „Scoops“ gepaart, was bedeutet, dass benachbarte Hashes kombiniert werden, um ein Zweierpaar zu bilden. Beispielsweise bilden Hash 0 und 1 Scoop 0, Hash 2 und 3 bilden Hash 1 und so weiter.

Der zweite Schritt beinhaltet die eigentliche Mining-Übung, bei der ein Miner eine Scoop-Nummer berechnet. Wenn beispielsweise ein Miner mit der Mining-Aktivität beginnt und eine Scoop-Nummer 38 generiert, würde der Miner dann zu Scoop-Nummer 38 von Nonce 1 gehen und die Daten dieser Scoop verwenden, um einen Fristwert zu berechnen.

Der Prozess wird wiederholt, um die Frist für jede Nonce zu berechnen, die auf der Festplatte des Miners gehalten wird. Nach der Berechnung aller Fristen wird diejenige mit der Mindestfrist vom Miner ausgewählt.

Eine Frist stellt die Zeitdauer in Sekunden dar, die vergehen muss, seit der letzte Block geschmiedet wurde, bevor ein Miner einen neuen Block schmieden darf. Wenn innerhalb dieser Zeit niemand sonst einen Block geschmiedet hat, kann der Miner einen Block schmieden und die Blockbelohnung beanspruchen.

Wenn zum Beispiel Miner X eine Mindestfrist von 36 Sekunden hat und kein anderer Miner den Block innerhalb der nächsten 36 Sekunden schmieden kann, sichert sich X die Chance, den nächsten Block zu schmieden und dafür belohnt zu werden.

## Vor- und Nachteile des Kapazitätsnachweises

PoC hat mehrere Vorteile gegenüber PoW- und PoS-Systemen sowie einige wichtige Nachteile, darunter:

<h5><a href="">TTT</a></h5>

## Höhepunkte

- Der Hauptvorteil eines PoC-Systems ist seine Effizienz im Vergleich zu Proof-of-Work (PoW)- und Proof-of-Stake (PoS)-Systemen.

- Zu den Blockchains, die auf Kapazitätsnachweis laufen, gehören Storj, Burst, Chia und SpaceMint.

- PoC-Authentifizierungssysteme (Proof of Capacity) verwenden freien Speicherplatz auf der Festplatte eines Geräts, um Lösungen für ein Problem mit dem Hashing von Kryptowährungen zu speichern.

