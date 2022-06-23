---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: Block-Header (Kryptowährung)
description: Kopfzeile blockieren. Ein Abschnitt in einem Block, der Metadaten und eine Zusammenfassung der Transaktionen des Blocks enthält. Dies sind die Informationen, die beim Mining gehasht werden.
---

# Block-Header (Kryptowährung)
Der Blockheader ist ein Abschnitt in einem [Block](/block),. der als Zusammenfassung des Rests des Blocks dient. Es setzt sich aus allen [Metadaten zusammen](/metadata) – wie dem Zeitpunkt und der [Schwierigkeit ,](/difficulty) wann der Block [abgebaut](/mining) wurde, dem [Merkle-Wurzel](/merkle-tree) der enthaltenen Transaktionen und der [Nonce](/nonce). Ebenfalls vorhanden ist der [Hash des vorherigen Blocks](/hash),. der es uns ermöglicht, die „Kette“ von Blöcken zu erstellen. Im Wesentlichen enthält der Block-Header alle Daten, die nicht die Liste der Rohtransaktionen selbst sind.

Ein Block-Header ist das, was die Miner hashen, um zu versuchen, den Block gültig zu machen. Dies ist viel effizienter als das Hashen des gesamten Blocks, der aus Tausenden von Transaktionen bestehen kann. Es wäre für einen Miner weitaus umständlicher, die Nonce zu ändern und für jeden Versuch einen ganzen 2-MB-Block erneut zu hashen. Vergleichen Sie dies beispielsweise mit dem Hashing der Blockheader von Bitcoin, die eine feste Länge von 80 Bytes haben.

Block-Header sind aus Mining-Sicht großartig, aber aufgrund ihrer geringen Größe sind sie auch ideal für Light-Clients. Die Bitcoin-Blockchain ist zu groß, um sie auf Geräten wie Smartphones zu speichern. Wenn die Kette 100.000 1-MB-Blöcke hätte, würden Sie 100 GB Speicherplatz verbrauchen. Aber mit nur den Blockheadern für dieselben Blöcke würden Sie nur 0,008 GB oder 8 MB belegen.

Auf diese Weise können Geräte mit weniger Bandbreite oder Speicherplatz immer noch ein gewisses Maß an Validierung durchführen. Da die Merkle-Root alle Transaktionen kapselt, können sie später überprüfen, ob eine Transaktion in einem bestimmten Block enthalten war. Dies ist mit Kosten verbunden – der Benutzer muss sich immer noch auf einen Dritten verlassen, der ihm die erforderlichen Informationen zur Verfügung stellt. Trotzdem sind Light-Clients einem System vorzuziehen, bei dem die Benutzer überhaupt keine Überprüfung durchführen.

## Höhepunkte

- Sie werden gehasht, um einen Arbeitsnachweis für Mining-Belohnungen zu erstellen.

- Blockheader identifizieren einzelne Blöcke in einer Blockchain.

- Die Blöcke sind vertikal geschichtet, beginnend mit dem „Genesis-Block“.

- Die Bitcoin-Versionsnummer hilft Ihnen, Änderungen im Protokoll nachzuverfolgen.

- Jeder Block-Header enthält drei Sätze von Block-Metadaten und mehrere einzelne Komponenten.

