---
keywords: Crypto
title: Bergbau
description: Bergbau. Die Überprüfung von Transaktionen in einem Blockchain-Netzwerk, bei dem Transaktionen als Einträge in das Blockchain-Ledger aufgenommen werden.
---

# Bergbau
Mining ist der Prozess, durch den [Kryptowährungstransaktionen](/cryptocurrency) gesammelt, verifiziert und in einem digitalen Hauptbuch, bekannt als [Blockchain , aufgezeichnet werden](/blockchain). Die Arbeit der Miner ist für die Aufrechterhaltung der Integrität des Netzwerks unerlässlich und auch für die Einführung neuer Coins in das System verantwortlich.

Innerhalb des traditionellen Bankensystems wird Fiat-Währung von Finanzinstituten und Regierungsbehörden gedruckt und verteilt – aber für die meisten Kryptowährungen liegt die Ausgabe neuer Coins nicht in den Händen zentralisierter Einheiten. Stattdessen werden neue Kryptowährungseinheiten durch den Mining-Prozess generiert, der einem vordefinierten Satz von Regeln folgt, die durch das zugrunde liegende Protokoll festgelegt werden. Während das Protokoll die primären Regeln definiert, skizzieren die sogenannten Konsensalgorithmen, wie diese Regeln befolgt werden (z. B. während der Validierung von Transaktionen).

Am Beispiel von Bitcoin werden die am Mining-Prozess beteiligten Teilnehmer als Mining-Knoten (oder einfach nur Miner) bezeichnet und spielen eine Schlüsselrolle für die Sicherheit des Blockchain-Netzwerks. Die Aufgabe eines Miners besteht darin, unbestätigte Transaktionen aus dem Speicherpool zu sammeln und sie in einem [Kandidatenblock zu organisieren](/candidate-block),. den sie zu validieren versuchen.

Beim Erstellen eines Kandidatenblocks schließt ein Miner eine Transaktion ein, bei der er [die Blockbelohnung](/block-reward) an sich selbst sendet. Diese Transaktion wird als Coinbase-Transaktion bezeichnet und ist oft die erste, die in einem Block aufgezeichnet wird.

Nachdem die Liste der unbestätigten Transaktionen erstellt wurde, wird jede Transaktion gehasht und ihre Ausgaben werden in Paaren organisiert. Diese Paare werden dann gehasht, wodurch neue Ausgaben entstehen, die ebenfalls in Paaren organisiert und erneut gehasht werden. Der Vorgang wird wiederholt, bis ein einzelner Hash erzeugt wird, der als Root-Hash oder [Merkle-Tree-](/merkle-tree) Wurzel bezeichnet wird.

Der Root-Hash wird dann mit dem Hash des zuvor bestätigten Blocks kombiniert, zusammen mit einer Pseudo-Zufallszahl namens [Nonce](/nonce) (plus einigen anderen Parametern). Diese Elemente werden dann gehasht, wodurch der Block-Hash für diesen Kandidatenblock erzeugt wird.

Der Miner wird jedoch nur erfolgreich sein, wenn die resultierende Ausgabe (Block-Hash) für seinen Kandidatenblock unter einem vorbestimmten Wert (Ziel) liegt. Folglich basiert der Prozess auf Trial-and-Error und sie müssen zahlreiche Hash-Funktionen mit unterschiedlichen Nonces ausführen, um ein gültiges Ergebnis zu finden. Der erste Miner, der einen gültigen Hash findet, validiert seinen Kandidatenblock und erhält die Blockbelohnung. Der gesamte Vorgang dauert im Durchschnitt zehn Minuten.

Sobald ein Block validiert ist, wird er der Blockchain hinzugefügt und die Miner beginnen mit der Arbeit am nächsten Block. Der von Minern produzierte gültige Hash fungiert als Beweis für ihre Arbeit, und deshalb wird der Bitcoin-Konsensalgorithmus Proof of Work genannt. Jeder bestätigte Block hat einen eindeutigen Block-Hash, der als Kennung dient.

Die [Blockbelohnung](/block-reward) wird durch das Bitcoin-Protokoll definiert und verringert sich alle 210.000 Blöcke (etwa vier Jahre). Anfangs betrug die Blockbelohnung 50 BTC und beträgt jetzt 12,5 BTC.

