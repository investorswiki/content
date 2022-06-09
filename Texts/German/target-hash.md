---
keywords: Investing,Cryptocurrency,Altcoins
title: Ziel-Hash
description: Ein Ziel-Hash legt die Schwierigkeit für das Kryptowährungs-Mining mit einem Proof-of-Work (PoW)-Blockchain-System fest.
---

# Ziel-Hash
## Was ist ein Ziel-Hash?

Beim Kryptowährungs-Mining ist ein Ziel-Hash ein numerischer Wert, der kleiner oder gleich einem gehashten [Block-Header](/block-header-cryptocurrency) sein muss, damit ein neuer Block an einen Miner vergeben wird. Blockheader identifizieren einzelne Blöcke in einer Blockchain.

Kryptowährungs-Mining bezieht sich auf den Prozess des Sammelns von Kryptowährung als Belohnung für die Arbeit, die Sie erledigen. Die Art dieser Arbeit besteht darin, die Legitimität der Transaktionen einer bestimmten Kryptowährung zu überprüfen. Auf diese Weise sind Kryptowährungsschürfer im Wesentlichen Prüfer. Wenn Sie minen, können Sie Kryptowährung verdienen, ohne dafür Geld einzahlen zu müssen.

Der Ziel-Hash wird zur Bestimmung der Schwierigkeit der Eingabe verwendet und kann angepasst werden, um sicherzustellen, dass Blöcke effizient verarbeitet werden. Beispielsweise werden Ziel-Hashes in Kryptowährungen verwendet, die ein Proof-of-Work (PoW)-System verwenden, um die aktuelle [Mining](/difficulty-cryptocurrencies) [-Schwierigkeit](/difficulty-cryptocurrencies) (einschließlich Bitcoin) festzulegen. Wenn eine Kryptowährung ein anderes System zum Schürfen verwendet, ist möglicherweise kein Ziel-Hash erforderlich.

## Wie ein Ziel-Hash funktioniert

[Kryptowährungen](/cryptocurrency) beruhen auf der Verwendung von [Blockchains](/blockchain),. die den Verlauf aller Transaktionen dieser Kryptowährung enthalten. Diese Transaktionen werden in eine Reihe von alphanumerischen Zeichen [gehasht](/hash) oder kryptografisch codiert. Beim Hashing wird eine Datenfolge beliebiger Länge genommen und durch einen Algorithmus geleitet, um eine Ausgabe mit fester Länge zu erzeugen. Die Ausgabe hat immer die gleiche Länge, unabhängig davon, wie groß oder klein die Eingabe ist (obwohl die Anzahl der Permutationen eines Hashs astronomisch groß ist). Jeder Block enthält den Hash des vorherigen Blockheaders.

Das Validieren und Kodieren der Blockchain wird als [Mining bezeichnet](/bitcoin-mining). Mining beinhaltet die Verwendung von Computern, um Hashing-Algorithmen auszuführen, um den neuesten Block zu verarbeiten; Die Informationen, die ein Benutzer zum Schürfen benötigt, befinden sich im Header des Blocks. Das Kryptowährungsnetzwerk legt einen Zielwert für diesen Hash fest – den so genannten Ziel-Hash – und Miner versuchen, diesen Wert zu bestimmen, indem sie alle möglichen Werte testen.

Der Blockheader enthält die Blockversionsnummer, einen Zeitstempel, den im vorherigen Block verwendeten Hash, den Hash des [Merkle Root](/merkle-root-cryptocurrency) [,](/merkle-root-cryptocurrency) die [Nonce](/nonce) und den Ziel-Hash. Der Block wird generiert, indem der Hash des Blockinhalts genommen, eine zufällige Zahlenfolge (die Nonce) hinzugefügt und der Block erneut gehasht wird.

Wenn der Hash die Anforderung des Ziels erfüllt, wird der Block zur Blockchain hinzugefügt. Das Durchlaufen von Lösungen, um die Nonce zu erraten, wird als [Proof of Work](/proof-work) (PoW) bezeichnet, und der Miner, der in der Lage ist, den Wert zu finden, erhält den Block und wird in Kryptowährung bezahlt.

## Besondere Überlegungen

### Ziel-Hash für Bitcoin

Bitcoin verwendet den SHA-256-Hash-Algorithmus. Dieser Algorithmus generiert nachweislich Zufallszahlen auf eine Weise, die eine vorhersehbare Menge an Rechenleistung des Computers erfordert.

Beim Mining eines Blocks muss der Miner einen Wert (eine Nonce) erzeugen, der nach dem Hashing (kryptographisch codiert) kleiner oder gleich dem Wert ist, der im letzten vom Bitcoin-Netzwerk akzeptierten Block verwendet wurde. Diese Zahl liegt zwischen 0- (die kleinste Option) und 256-Bit (die größte Option), ist aber wahrscheinlich nie die maximale Zahl.

Da der Ziel-Hash eine große Zahl sein kann, muss der Miner möglicherweise eine große Anzahl von Werten testen, bevor er erfolgreich ist. Ein erfolgloser Miner muss auf den nächsten Block warten (weshalb Miner, die eine Hash-Lösung finden, mit Gewinnern eines Rennens oder der Lotterie verglichen werden).

Der Ziel-Hash wird regelmäßig angepasst. Die Hash-Funktionen, die zum Generieren des neuen Ziels verwendet werden, haben spezifische Eigenschaften, die darauf ausgelegt sind, die Blockchain (und ihre Kryptowährung) sicher zu machen. Dieser Prozess ist deterministisch, was bedeutet, dass er jedes Mal dasselbe Ergebnis liefert, wenn dieselbe Eingabe verwendet wird. Es ist schnell genug, um nicht zu lange zu dauern, um einen Hash für die Eingabe zurückzugeben. Es macht auch die Bestimmung der Eingabe sehr schwierig, insbesondere bei großen Zahlen, und führt dazu, dass kleine Änderungen an der Eingabe zu einer sehr unterschiedlichen Hash-Ausgabe führen.

## Höhepunkte

- Ziel-Hashes werden in Kryptowährungen verwendet, die ein Proof-of-Work (PoW)-System verwenden, um die aktuelle Mining-Schwierigkeit festzulegen (einschließlich Bitcoin); Wenn eine Kryptowährung ein anderes System zum Schürfen verwendet, ist möglicherweise kein Ziel-Hash erforderlich.

- Beim Kryptowährungs-Mining ist ein Ziel-Hash ein numerischer Wert, den ein gehashter Block-Header (der zur Identifizierung einzelner Blöcke in einer Blockchain verwendet wird) kleiner oder gleich sein muss, damit ein neuer Block an einen Miner vergeben wird.

- Das Bitcoin-Netzwerk passt die Schwierigkeit des Schürfens an, indem es den Ziel-Hash erhöht oder verringert, um ein durchschnittliches 10-Minuten-Intervall zwischen neuen Blöcken beizubehalten.

