---
keywords: Crypto
title: Speicher
description: Speicher. Der Mechanismus eines Knotens, um unbestätigte Transaktionen zu verfolgen, die der Knoten gesehen hat (aber noch nicht zu einem Block hinzugefügt wurde).
---

# Speicher
Ein Mempool (eine Kontraktion von Speicher und Pool) ist der Mechanismus eines Kryptowährungsknotens zum Speichern von Informationen über unbestätigte Transaktionen. Er fungiert als eine Art Wartezimmer für Transaktionen, die noch nicht in einen [Block aufgenommen wurden](/block).

Wenn eine Transaktion gesendet wird, wird sie von einem Knoten an seine Peers gesendet, die sie dann an ihre Peers weiterleiten. Dies wird fortgesetzt, bis die Transaktion weit verbreitet ist und Miner sie einem Block hinzufügen können. Es ist wichtig, dass diese Pufferzone existiert, da Transaktionen nicht sofort zur Blockchain hinzugefügt werden.

Die Knoten führen eine Reihe von Prüfungen durch, um sicherzustellen, dass die Transaktion gültig ist – dh sie überprüfen, ob die Signaturen korrekt sind, die Ausgaben die Eingaben nicht überschreiten und die Gelder nicht bereits ausgegeben wurden. Erfüllt er diese Bedingungen nicht, wird er zurückgewiesen.

Wir sprechen oft vom Mempool, aber es sollte beachtet werden, dass es keinen universellen Pool gibt, der von allen Nodes geteilt wird. Jeder ist anders konfiguriert und empfängt Transaktionen zu unterschiedlichen Zeiten. Geräte der unteren Preisklasse mit begrenzten Ressourcen widmen der Protokollierung von Transaktionen möglicherweise nur wenig Speicher, während Geräte der höheren Preisklasse möglicherweise erheblich mehr Speicher bereitstellen.

Da Bergleute hauptsächlich durch Gewinne motiviert sind, werden Transaktionen mit höheren Gebühren am wahrscheinlichsten zuerst aus dem Mempool verworfen, wenn sie bestätigt werden. Die genaue Schätzung der Gebühren ist schwierig, insbesondere wenn der Blockplatz begrenzt und die Nachfrage hoch ist, aber der Mempool bietet einen Ausgangspunkt.

Um die Gebühren abzuschätzen, kann man sich die aktuellen unbestätigten Transaktionen ansehen. Es liegt nahe, dass Benutzer in Zeiten mit geringem Durchsatz nicht zu viel bezahlen sollten. Sie sollten auch nicht für zeitkritische Transaktionen zu Spitzenzeiten zu wenig zahlen, da es eine Weile dauern kann, bis sie bestätigt werden. Indem sie die Verteilung der Gebühren zu einem bestimmten Zeitpunkt berücksichtigen, können sie eine fundierte Schätzung abgeben, wie schnell ihre Transaktion aufgenommen wird.

