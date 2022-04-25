---
keywords: Personal Finance,Banking
title: Nachrichtenauthentifizierungscode (MAC)
description: Ein Message Authentication Code (MAC) oder Tag ist ein Sicherheitscode, der vom Benutzer eines Computers eingegeben wird, um auf Konten oder Portale zuzugreifen.
---

# Nachrichtenauthentifizierungscode (MAC)
## Was ist ein Nachrichtenauthentifizierungscode?

Ein Message Authentication Code (MAC) oder **Tag** ist ein Sicherheitscode, der vom Benutzer eines Computers eingegeben wird, um auf Konten oder Portale zuzugreifen. Dieser Code wird an die vom Benutzer gesendete Nachricht oder Anfrage angehängt. Nachrichtenauthentifizierungscodes (MACs), die an die Nachricht angehängt sind, müssen vom empfangenden System erkannt werden, um dem Benutzer Zugriff zu gewähren.

## Message Authentication Code (MAC) verstehen

Message Authentication Codes (MACs) werden üblicherweise bei [elektronischen Geldtransfers](/electronic-funds-transfer-act) (EFTs) verwendet, um die Informationsintegrität zu wahren. Sie bestätigen, dass eine Nachricht authentisch ist; dass es wirklich vom angegebenen Absender kommt und unterwegs keine Veränderungen erfahren hat. Ein Verifizierer, der auch im Besitz des Schlüssels ist, kann ihn verwenden, um Änderungen am Inhalt der betreffenden Nachricht zu erkennen.

Nachrichtenauthentifizierungscodes sind normalerweise erforderlich, um auf jede Art von Finanzkonto zugreifen zu können. Diese Codes können von Banken, Maklerfirmen, Treuhandgesellschaften und allen anderen Depot-, Anlage- oder Versicherungsunternehmen verwendet werden, die einen Online-Zugang anbieten. Sie sind ein wesentlicher Bestandteil der Finanzkryptographie.

## Algorithmen zum Generieren von MACs

Drei Algorithmen umfassen typischerweise einen MAC: einen Schlüsselgenerierungsalgorithmus, einen Signaturalgorithmus und einen Verifizierungsalgorithmus. Der Schlüsselerzeugungsalgorithmus wählt zufällig einen Schlüssel aus. Der Signaturalgorithmus sendet ein Tag, wenn ihm der Schlüssel und die Nachricht übergeben werden. Der Verifizierungsalgorithmus wird verwendet, um die Authentizität der Nachricht zu verifizieren, wenn der Schlüssel und das Tag gegeben werden; Es wird eine Nachricht von **akzeptiert** zurückgegeben, wenn die Nachricht und das Tag authentisch und unverändert sind, aber andernfalls wird eine Nachricht von **abgelehnt** zurückgegeben.

Beispielsweise sendet der Absender eine Nachricht, wie z. B. eine EFT, über den MAC-Algorithmus, der einen Schlüssel generiert und ein MAC-Daten-Tag an die Nachricht anfügt. Der Empfänger erhält die Nachricht, lässt sie mit demselben Schlüssel durch den MAC-Algorithmus laufen und erhält ein zweites Daten-Tag. Sie vergleichen dann dieses MAC-Daten-Tag mit dem ersten, das an die Nachricht angehängt wurde, als sie übertragen wurde. Wenn der Code an beiden Enden gleich ist, kann der Empfänger sicher davon ausgehen, dass die Datenintegrität der Nachricht intakt ist. Wenn nicht, bedeutet dies jedoch, dass die Nachricht geändert, manipuliert oder gefälscht wurde.

Die Nachricht selbst sollte jedoch einige Daten enthalten, die sicherstellen, dass diese Nachricht nur einmal gesendet werden kann. Beispielsweise könnte ein einmaliger MAC, Zeitstempel oder eine Sequenznummer verwendet werden, um zu garantieren, dass die Nachricht nur einmal gesendet werden kann. Andernfalls könnte das System anfällig für einen Replay-Angriff sein, bei dem ein Angreifer die Nachricht nach der Decodierung abfängt und zu einem späteren Zeitpunkt erneut überträgt, die ursprünglichen Ergebnisse repliziert und das System infiltriert.

## Nachrichtenintegritätscodes (MICs)

Manchmal wird statt MAC auch der Begriff Message Integrity Code (MIC) verwendet. Dies geschieht am häufigsten in der Kommunikationsbranche, wo MAC traditionell Media Access Control Address (MAC-Adresse) bedeutet. MIC kann jedoch auch verwendet werden, um sich auf **Message Digest** zu beziehen, das geheime Schlüssel nicht auf die gleiche Weise wie ein MAC verwendet und ohne weitere Verschlüsselung nicht das gleiche Sicherheitsniveau bieten kann.

