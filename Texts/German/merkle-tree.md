---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: Merkle-Baum
description: Merkle-Baum. Eine Möglichkeit, große Datenmengen zu organisieren und zu strukturieren, um sie einfacher zu verarbeiten. Eine Hash-basierte Datenstruktur.
---

# Merkle-Baum
Ein Merkle-Baum ist eine Möglichkeit, große Datenmengen zu organisieren und zu strukturieren, um sie einfacher zu verarbeiten. Im Fall von Kryptowährung und [Blockchain](/blockchain) wird der Merkle-Baum verwendet, um Transaktionsdaten ressourcenschonender zu strukturieren.

Wenn eine Kryptowährungstransaktion in einer Merkle-Baumstruktur durchgeführt wird, wird sie gehasht und erhält dann einen äquivalenten Hashwert. Nachdem jede Transaktion im Merkle-Baum gehasht wurde, werden die erzeugten Hash-Werte mit einem anderen Hash-Wert gepaart und dann erneut gehasht. Beispielsweise werden die Hash-Werte „AB“ und „AC“ kombiniert, um „ABC“ zu erstellen.

Dieser Vorgang des Paarens von Hash-Werten wird wiederholt, bis ein endgültiger Hash-Wert erzeugt wird. Der finale Hashwert, die Merkle-Wurzel, liefert eine Zusammenfassung aller darin enthaltenen Transaktionen. Die Merkle-Root-Zusammenfassung wird dann in den Block-Header eingefügt.

#### Datensicherheit

Eine Merkle-Baumstruktur bietet eine leicht zugängliche Aufzeichnung der Transaktionen in einem [Block](/block). So lässt sich sehr einfach überprüfen, ob die Daten in einem Block verändert oder manipuliert wurden. Dies ist richtig, weil jede Änderung an einer Transaktion (oder anderen verwandten Daten) im Merkle-Baum zu einer völlig anderen entsprechenden Merkle-Wurzel führen würde.

#### Effizienter Ressourceneinsatz

Wenn Kryptowährungen keine Merkle-Bäume verwenden würden, würde jede Verifizierungsanfrage enorme Mengen an Informationen beinhalten, die über das Netzwerk gesendet werden. Die Strukturierung von Transaktionsdaten in einem Merkle-Baum ist eine weitaus effizientere Nutzung von Ressourcen. Die Validierung einer Transaktion erfordert keine vollständige Kopie des Hauptbuchs, da die gehashten Transaktionsdaten in einem Merkle-Root verifiziert werden können, was das Senden von viel weniger Informationen über die Knoten und somit weniger Rechenleistung zum Analysieren der gesamten Datenintegrität erfordert.

Mit anderen Worten, eine Merkle-Baumstruktur ermöglicht es Benutzern zu überprüfen, ob eine einzelne Transaktion in einen Block aufgenommen wurde, ohne den Prozess des Herunterladens der gesamten Blockchain durchlaufen zu müssen. Die Technologie ist ein wichtiges Werkzeug für Kryptowährungen, um Transaktionsdaten zu organisieren und so effizient zu funktionieren, wie sie es tun. Ohne Merkle-Bäume würde die größere Nachfrage nach Ressourcen wahrscheinlich dazu führen, dass weniger [Knoten](/node) am Netzwerk teilnehmen.

