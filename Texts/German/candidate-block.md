---
keywords: Crypto
title: Kandidatenblock
description: Kandidatenblock. Ein temporärer Block, der von einem Mining-Knoten (Miner) erstellt wird, um ihn der Blockchain hinzuzufügen, um die Blockbelohnungen zu erhalten.
---

# Kandidatenblock
Mit wenigen Worten, ein Kandidatenblock ist ein Block, den ein Mining-Knoten (Miner) zu minen versucht, um die Blockbelohnung zu erhalten. Ein Kandidatenblock kann also als temporärer Block beschrieben werden, der vom Netzwerk entweder validiert oder verworfen wird. Miner konkurrieren miteinander, um den nächsten Block zu validieren und ihn der Blockchain hinzuzufügen, aber zuerst müssen sie einen Kandidatenblock erstellen, um am Mining-Wettbewerb teilnehmen zu können.

Kandidatenblöcke werden von Minern erstellt, indem mehrere unbestätigte Transaktionen aus dem Speicherpool gesammelt und organisiert werden. Die Transaktionen werden dann gehasht, um eine [Merkle-Baumstruktur zu](/merkle-tree) bilden, die schließlich eine Merkle-Root (oder Root-Hash) erzeugt. Die Merkle-Wurzel ist ein einzelner Hash, der alle vorherigen Hashes dieses Baums und damit alle Transaktionen darstellt, die in diesem bestimmten Block enthalten waren.

Der Root-Hash wird dann zusammen mit dem Hash des vorherigen Blocks und einer Zufallszahl namens [Nonce](/nonce) in den Header des Blocks eingefügt. Der Block-Header wird dann vom Miner gehasht und generiert eine Ausgabe basierend auf diesen Komponenten (Root-Hash, Hash des vorherigen Blocks und Nonce) sowie einigen anderen Elementen. Die resultierende Ausgabe ist der Block-Hash und dient als eindeutige Kennung des neu generierten Blocks (Kandidatenblock).

Um als gültig zu gelten, muss die Ausgabe (Block-Hash) mit einer bestimmten Anzahl von Nullen beginnen (weniger als ein vom Protokoll definierter Zielwert). Dies bedeutet, dass der Mining-Prozess auf mehreren Versuchen (Versuch und Irrtum) basiert, da die Mining-Knoten eine Vielzahl von Hash-Funktionen mit unterschiedlichen Nonce-Werten ausführen müssen, bis schließlich ein gültiger Block-Hash erzeugt wird. Der produzierte Block-Hash beweist, dass der Miner seine Arbeit geleistet hat (daher Proof of Work).

Nachdem ein Miner einen gültigen Block-Hash gefunden hat, wird sein Kandidatenblock an den Rest der Knoten des Netzwerks gesendet, der die Authentizität des Hashs überprüft. Wenn alles gut ist, wird der Kandidatenblock dann in die Blockchain aufgenommen. An diesem Punkt aktualisiert jeder Validierungsknoten seine Kopie der Blockchain-Daten, um den zuletzt abgebauten Block widerzuspiegeln, und der Miner erhält die Blockbelohnung.

