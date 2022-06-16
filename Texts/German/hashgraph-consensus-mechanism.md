---
keywords: Investing,Cryptocurrency,Blockchain
title: Hashgraph-Konsens
description: Der Hashgraph-Konsens funktioniert anders als bekanntere Blockchain-Konsensmechanismen. Erfahren Sie mehr darüber und wie es funktioniert.
---

# Hashgraph-Konsens
## Was ist Hashgraph-Konsens?

Der Hashgraph-Konsens ist eine Alternative zu – oder die nächste Generation – der Technologie hinter den Blockchain-Konsensmechanismen. Anstatt die Rechenleistung großer Netzwerke zu verwenden, um Transaktionen zu verifizieren, werden Transaktionen über ein Protokoll aufgezeichnet und bestätigt, das die Knotenkommunikation verwendet.

Ein Hashgraph ist ein dezentrales Ledger, ähnlich wie eine Blockchain. Es speichert Informationen, sichert sie mit Kryptografie, beschränkt den Zugriff und verwendet die gespeicherten Daten als Verifizierung. Ein Hashgraph-Netzwerk erreicht jedoch einen Konsens auf ganz andere Weise als eine Blockchain.

Hashgraph-Konsens wird mithilfe von Konzepten erreicht, die „Klatsch“, „Klatsch über Klatsch“ und virtuelle Abstimmungen genannt werden. Entwickler des Systems berichten, dass es die Probleme löst, die konsensbildenden [Algorithmen](/algorithm) wie [Proof of Work](/proof-work) (PoW) im Hinblick auf eine bessere Geschwindigkeit und höhere Effizienz innewohnen.

> Hashgraph-Konsens – Klatsch, Klatsch über Klatsch und virtuelle Abstimmung – ist der Mechanismus, den das verteilte Hauptbuch von Hedera verwendet, um Transaktionen zu validieren und zu bestätigen.

>

## Hashgraph-Konsens verstehen

Hashgraph ist eine Alternative zu Blockchain. Ähnlich einer Blockchain speichert sie Daten und verschlüsselt sie. Für Transaktionsinformationen wird ein Hash generiert, und neue Transaktionen oder Daten werden hinzugefügt und darauf aufgebaut. Eine Blockchain ist jedoch ein Hauptbuch, das aus Datenblöcken besteht. Jeder Block wird mit seinen Daten mit dem vorherigen Block verknüpft, die von einem Netzwerk von Validatoren verifiziert werden, um den nächsten Block zu erstellen. Dieser Prozess erstellt eine Kette. Ein Hashgraph ist keine Kette – alle Informationen werden in einem verschlüsselten Hauptbuch aufbewahrt, und jeder Benutzer nimmt am Validierungsprozess teil, nicht nur die Validatoren.

Zum Beispiel erstellt Alice eine Transaktion mit Bob und alle Informationen, die sie kennt, werden ihm gegeben. Bob macht dann eine Transaktion mit Kris. Alle Informationen, die Bob hat, werden Kris mitgeteilt. Kris handelt mit Eli und alles, was sie weiß, wird übertragen. Dies setzt sich im gesamten Netzwerk fort, wobei die Kette im Wesentlichen über die stattfindenden Ereignisse klatscht. Jeder Knoten weiß, was alle anderen Knoten wissen, sodass keine rechnerische Validierung erforderlich ist.

Während sich der Klatsch von Benutzer zu Benutzer verbreitet, verwendet das Netzwerk Algorithmen und Automatisierung, um sicherzustellen, dass der Status des Hashgraph-Ledgers aktualisiert und gleich bleibt.

### Tratsch

Informationen über Daten werden als „Klatsch“ bezeichnet. Die in einer Transaktion enthaltenen Datenstrukturen sind:

- Ein Zeitstempel

- Mehr Transaktionen oder Nullen

- Zwei Hashes aus den übergeordneten Containern

- Eine verschlüsselte Signatur.

Die beiden Hashes sind die letzten Ereignisse von zwei Synchronisierungsknoten, die ihre Informationen vergleichen. Knoten erstellen kontinuierlich Ereignisse und synchronisieren.

> Hashgraph – das Ledger – ist effizienter als Blockchain, da keine Energie für Blöcke verschwendet wird, die nicht akzeptiert werden. Alle Informationen werden in einem Hashgraph festgehalten.

>

### Klatsch über Klatsch

Informationen über Transaktionsdaten werden als „Klatsch über Klatsch“ bezeichnet. Informationen werden im Hashgraph-Netzwerk mithilfe eines Ereignisses namens „Gossip Sync“ synchronisiert. Eine Gossip-Synchronisation ist eine gemeinsame Geschichte von „Gossip-Ereignissen“ im gesamten Hashgraph. Auf diese Weise können Daten nicht verändert oder manipuliert werden und es herrscht Konsens.

### Virtuelle Abstimmung

Eine virtuelle Abstimmung findet statt, wenn die Knoten Ereignisse vergleichen und über einen Abstimmungsalgorithmus einen Konsens erzielen. So funktioniert es: Einer Transaktion wird ein Zeitstempel zugewiesen, wenn ein Knoten ihn empfängt. Bei der Weiterleitung an die anderen Knoten im Netzwerk wird ihm ein Zeitstempel zugewiesen, der ein Medianwert aller Zeitstempel für diese Transaktion ist, die von den Knoten im Netzwerk empfangen wurden. Als Ergebnis der Abstimmung gilt der Median. Dies schafft ein faireres Transaktionssystem als eine Blockchain, da das Netzwerk entscheidet, nicht ein Knoten.

### Fehlertoleranz

Wie bei den meisten Distributed Ledgers und Blockchain besteht immer die Möglichkeit, dass ein Teilnehmer im Netzwerk nicht ehrlich ist. Es kann zu Verzögerungen bei der Kommunikation oder Netzwerklatenz kommen, die dazu führen, dass Knoten nicht ordnungsgemäß kommunizieren.

Konsensmechanismen sollen mit diesen Fehlern umgehen, indem sie Fehlertoleranzkriterien festlegen. Entwickler müssen schlechte Akteure, schlechte Verbindungen, Netzwerklatenz und andere Netzwerkprobleme berücksichtigen und berücksichtigen. Der Hashgraph-Konsens kann tolerieren, dass ein Drittel des Netzwerks böswillig handelt. Berichten zufolge ist es asynchron byzantinisch fehlertolerant – die höchste Sicherheitsstufe – was bedeutet, dass ehrliche Knoten in einem Netzwerk auch dann weiterarbeiten, wenn es schlechte Akteure gibt.

## Wie unterscheidet sich Hashgraph von Blockchain?

Hashgraph ist eine Datenstruktur, die Aufzeichnungen darüber führt, wer wem was und in welcher Reihenfolge gesagt hat. Es ist eine kollaborative Geschichte von Klatschereignissen, bei denen die Teilnehmer Informationen hinzufügen und austauschen, wodurch Transaktionen viel schneller als eine Blockchain validiert werden.

Blockchain fügt frühere Transaktionsinformationen zu neuen Transaktionsinformationen hinzu und verschlüsselt sie. Ein Dritter wird benötigt, um die Transaktionen zwischen den Parteien zu validieren. Hashgraph benötigt diesen langsamen Prozess aufgrund des Gossip-Protokolls nicht.

> Hashgraph-Konsens ist viel schneller als Blockchain-Konsensmechanismen, mit durchschnittlichen Transaktionsbestätigungszeiten in Sekunden statt in Minuten.

>

Bitcoin und viele andere Kryptowährungen haben Probleme mit dem Nachrichtentiming. Die asynchrone byzantinische Fehlertoleranz von Hashgraph überwindet jedoch das Problem des Nachrichten-Timings, indem sie davon ausgeht, dass verlorene oder verzögerte Nachrichten schließlich ihr Ziel erreichen.

Wenn beispielsweise zwei Transaktionen gleichzeitig stattfinden, wählt ein Blockchain-Netzwerk aus, in welcher Reihenfolge die Transaktionen stattgefunden haben. In einigen Blockchains priorisieren Transaktionsgebühren die Bestätigung. Andere Netzwerke entscheiden möglicherweise, welche Transaktion bestätigt wird, basierend darauf, wie viele Token ein Validierer eingesetzt hat. In diesen Blockchains beeinflusst ein Knoten das Ergebnis.

Der Hashgraph-Konsens eliminiert den Einfluss, den ein Knoten oder eine Gruppe von Knoten auf Transaktionen haben kann. Da jede Transaktion mit einem Zeitstempel versehen ist und jede Transaktion an das gesamte Netzwerk kommuniziert wird, werden Transaktions-Timing-Probleme gelöst.

## Höhepunkte

- Das Hashgraph-Distributed-Ledger-System hat in der Krypto-Community keine breite Akzeptanz gefunden.

- Der Hashgraph-Konsens verwendet Informationen über Informationen und nicht den Inhalt selbst, um einen Konsens zu schaffen.

- Primäre Informationen im Hashgraph werden als „Klatsch“ und sekundäre Informationen als „Klatsch über Klatsch“ bezeichnet.

## FAQ

### Wie funktioniert der Hashgraph-Konsens?

Der Hashgraph-Konsens funktioniert mit Konsens-Zeitstempeln und „Klatsch“, bei dem jeder Knoten alles, was er weiß, an zufällige Knoten in „Klatsch-Ereignissen“ kommuniziert.

### Was ist Hashgraph-Konsens?

Hashgraph Consensus ist ein Mechanismus, der in einem verteilten Hashgraph-Ledger verwendet wird, um Transaktionen zu validieren.

### Wird Hashgraph Blockchain ersetzen?

Hashgraph ist als Verbesserung der Blockchain-Technologie konzipiert und vermarktet, aber ob es sie ersetzen wird, bleibt abzuwarten. Es hat noch nicht so viel Entwicklerinteresse und Akzeptanz wie die Blockchain-Technologie.

