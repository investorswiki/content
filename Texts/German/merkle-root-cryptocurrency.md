---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Merkle Root (Kryptowährung)
description: Ein Merkle-Stamm enthält Informationen über jeden einzelnen Transaktions-Hash, der sich jemals auf einem bestimmten Block in einer Blockchain befand.
---

# Merkle Root (Kryptowährung)
## Was ist eine Merkle-Wurzel?

Eine Merkle-Root ist der [Hash](/hash) aller Hashes aller Transaktionen, die Teil eines Blocks in einem [Blockchain](/blockchain) -Netzwerk sind.

## Eine Merkle-Wurzel verstehen

Eine Blockchain besteht aus verschiedenen Blöcken, die miteinander verknüpft sind (daher der Name Blockchain). Ein Hash-Baum oder der [Merkle-Baum](/merkle-tree) codiert die Blockchain-Daten auf effiziente und sichere Weise. Es ermöglicht die schnelle Überprüfung von Blockchain-Daten sowie die schnelle Übertragung großer Datenmengen von einem Computerknoten zum anderen im Peer-to-Peer-Blockchain-Netzwerk.

Jeder Transaktion, die im Blockchain-Netzwerk stattfindet, ist ein Hash zugeordnet. Diese Hashes werden jedoch nicht in einer sequentiellen Reihenfolge auf dem Block gespeichert, sondern in Form einer baumartigen Struktur, sodass jeder Hash mit seinem Elternteil verknüpft ist, indem eine baumartige Eltern-Kind-Beziehung folgt.

Da in einem bestimmten Block zahlreiche Transaktionen gespeichert sind, werden alle Transaktions-Hashes im Block ebenfalls gehasht, was zu einer Merkle-Wurzel führt.

Betrachten Sie zum Beispiel einen Block mit sieben Transaktionen. Auf der untersten Ebene (Blattebene genannt) gibt es vier Transaktions-Hashes. Auf der Ebene eins über der Blattebene gibt es zwei Transaktions-Hashes, von denen jeder mit zwei Hashes verbunden ist, die sich auf der Blattebene darunter befinden. Ganz oben (Ebene zwei) befindet sich der letzte Transaktions-Hash namens Root, der sich mit den beiden Hashes darunter (auf Ebene eins) verbindet.

Tatsächlich erhalten Sie einen umgekehrten Binärbaum, bei dem jeder Knoten des Baums nur mit zwei darunter liegenden Knoten verbunden ist (daher der Name "Binärbaum"). Es hat oben einen Root-Hash, der mit zwei Hashes auf Ebene eins verbunden ist, von denen jeder wiederum mit den beiden Hashes auf Ebene drei (Blattebene) verbunden ist, und die Struktur wird abhängig von der Anzahl der Transaktions-Hashes fortgesetzt.

<!--AAFEB15A7406E8DD3ABDD652D7C85823-->

Das Hashing beginnt bei den Knoten der untersten Ebene (Blattebene), und alle vier Hashes sind im Hash der Knoten enthalten, die damit auf Ebene eins verknüpft sind. In ähnlicher Weise wird das Hashing auf Ebene eins fortgesetzt, was dazu führt, dass Hashes von Hashes höhere Ebenen erreichen, bis es den einzelnen Top-Root-Hash erreicht.

Dieser Root-Hash wird als Merkle-Root bezeichnet und enthält aufgrund der baumartigen Verknüpfung von Hashes alle Informationen zu jedem einzelnen Transaktions-Hash, der auf dem Block existiert. Es bietet einen Single-Point-Hash-Wert, der es ermöglicht, alles zu validieren, was in diesem Block vorhanden ist.

Wenn man beispielsweise eine Transaktion verifizieren muss, die angeblich aus Block Nr. 137 stammt, muss nur der Merkle-Baum des Blocks überprüft werden, ohne sich Gedanken darüber machen zu müssen, irgendetwas auf anderen Blöcken in der Blockchain zu verifizieren, wie Block Nr. 136 oder Block Nr. 138.

<!--4861E8697637B7236BF11AA57D958059-->

Geben Sie den Merkle-Stamm ein, was die Überprüfung weiter beschleunigt. Da es alle Informationen über den gesamten Baum enthält, muss man nur diesen Transaktions-Hash und seinen Geschwisterknoten (falls vorhanden) überprüfen und dann nach oben fortfahren, bis er die Spitze erreicht.

Im Wesentlichen reduzieren der Merkle-Baum und der Merkle-Root-Mechanismus die durchzuführenden Hash-Stufen erheblich, was eine schnellere Überprüfung und Transaktionen ermöglicht.

## Höhepunkte

- Merkle Roots sind von zentraler Bedeutung für die Berechnung, die erforderlich ist, um Kryptowährungen wie Bitcoin und Ether zu verwalten.

- Merkle Roots werden in Kryptowährung verwendet, um sicherzustellen, dass Datenblöcke, die zwischen Peers in einem Peer-to-Peer-Netzwerk ausgetauscht werden, vollständig, unbeschädigt und unverändert sind.

- Eine Merkle-Wurzel ist ein einfacher mathematischer Weg, um die Daten eines Merkle-Baums zu verifizieren.

