---
keywords: Investing,Cryptocurrency,Blockchain
title: Hyperledger-Fabric
description: Hyperledger Fabric ist eine Plattform zum Erstellen verschiedener Blockchain-basierter Produkte, Lösungen und Anwendungen für den geschäftlichen Gebrauch.
---

# Hyperledger-Fabric
## Was ist Hyperledger Fabric?

Hyperledger Fabric ist ein modulares [Blockchain](/blockchain) -Framework, das als Grundlage für die Entwicklung blockkettenbasierter Produkte, Lösungen und Anwendungen mit Plug-and-Play-Komponenten dient, die für den Einsatz in Privatunternehmen bestimmt sind.

Hyperledger Fabric wurde von Digital Asset und IBM initiiert und hat sich nun zu einem branchenübergreifenden Gemeinschaftsunternehmen entwickelt, das derzeit von der Linux Foundation gehostet wird. Unter den mehreren Hyperledger-Projekten war Fabric das erste, das die „Inkubationsphase“ verließ und im März 2017 die „aktive“ Phase erreichte.

## Funktionsweise von Hyperledger Fabric

Herkömmliche Blockchain-Netzwerke können keine privaten Transaktionen und vertraulichen Verträge unterstützen, die für Unternehmen von größter Bedeutung sind. Hyperledger Fabric wurde als Antwort darauf als modulare, skalierbare und sichere Grundlage für das Angebot industrieller Blockchain-Lösungen konzipiert.

Hyperledger Fabric ist die Open-Source-Engine für Blockchain und kümmert sich um die wichtigsten Funktionen zur Bewertung und Nutzung von Blockchain für geschäftliche Anwendungsfälle.

Innerhalb privater industrieller Netzwerke ist die überprüfbare Identität eines Teilnehmers eine primäre Anforderung. Hyperledger Fabric unterstützt Mitgliedschaften basierend auf Berechtigungen; alle Netzwerkteilnehmer müssen bekannte Identitäten haben. Viele Wirtschaftszweige, wie das Gesundheitswesen und das Finanzwesen, sind an Datenschutzbestimmungen gebunden, die die Pflege von Daten über die verschiedenen Teilnehmer und ihren jeweiligen Zugriff auf verschiedene Datenpunkte vorschreiben. Fabric unterstützt eine solche berechtigungsbasierte Mitgliedschaft.

### Modulare Architektur

Die modulare Architektur von Hyperledger Fabric trennt den Transaktionsverarbeitungs-Workflow in drei verschiedene Phasen: [Smart Contracts](/smart-contracts),. genannt Chaincode, die die verteilte Logikverarbeitung und -vereinbarung des Systems, die Transaktionsbestellung sowie die Transaktionsvalidierung und -zusage umfassen. Diese Trennung bietet mehrere Vorteile:

- Eine reduzierte Anzahl von Vertrauensstufen und Überprüfungen, die das Netzwerk und die Verarbeitung übersichtlich halten

- Verbesserte Skalierbarkeit des Netzwerks

- Bessere Gesamtleistung

Darüber hinaus ermöglicht die Unterstützung von Hyperledger Fabric für Plug-and-Play verschiedener Komponenten die einfache Wiederverwendung bestehender Funktionen und die vorgefertigte Integration verschiedener Module. Wenn beispielsweise bereits eine Funktion vorhanden ist, die die Identität des Teilnehmers überprüft, muss ein Netzwerk auf Unternehmensebene dieses vorhandene Modul einfach anschließen und wiederverwenden, anstatt dieselbe Funktion von Grund auf neu zu erstellen.

Die Teilnehmer im Netzwerk haben drei unterschiedliche Rollen:

- Indossant

- Beauftragter

- Zustimmung

Kurz gesagt, der Transaktionsvorschlag wird dem Endorser-Peer gemäß der vordefinierten Endorsement-Richtlinie über die Anzahl der erforderlichen Endorser vorgelegt. Nach ausreichenden Indossierungen durch den/die Indossanten wird ein Batch oder Block von Transaktionen an den/die Committer geliefert. Die Committer bestätigen, dass die Endorsement-Richtlinie befolgt wurde und dass es keine widersprüchlichen Transaktionen gibt. Sobald beide Prüfungen durchgeführt wurden, werden die Transaktionen in das Hauptbuch übernommen.

<!--6376536357DF4ADC77E5CAB266DCF459-->

Bildquelle: IBM

Da nur Bestätigungsanweisungen – wie Signaturen und Lese-/Schreibsätze – über das Netzwerk gesendet werden, wird die Skalierbarkeit und Leistung des Netzwerks verbessert. Nur Endorser und Committer haben Zugriff auf die Transaktion, und die Sicherheit wird verbessert, da weniger Teilnehmer Zugriff auf wichtige Datenpunkte haben.

## Beispiel für Hyperledger Fabric

Angenommen, es gibt einen Hersteller, der Schokolade zu einem bestimmten Preis an einen bestimmten Einzelhändler oder Markt von Einzelhändlern (dh alle US-Einzelhändler) liefern möchte, diesen Preis jedoch nicht auf anderen Märkten (dh chinesischen Einzelhändlern) offenlegen möchte.

Da an der Bewegung des Produkts andere Parteien wie der Zoll, eine Reederei und eine finanzierende Bank beteiligt sein können, kann der private Preis allen beteiligten Parteien offengelegt werden, wenn eine Basisversion der Blockchain-Technologie zur Unterstützung dieser Transaktion verwendet wird.

Hyperledger Fabric behebt dieses Problem, indem es private Transaktionen im Netzwerk privat hält; Nur die Teilnehmer, die es wissen müssen, sind sich der notwendigen Details bewusst. Die Datenpartitionierung in der Blockchain ermöglicht den Zugriff auf bestimmte Datenpunkte nur für die Parteien, die dies wissen müssen.

## Kritik an Hyperledger Fabric

Die Hochwassermarke des Krypto-Enthusiasmus wurde 2018 nach dem Zusammenbruch des Bitcoin-Preises (der am 17. Dezember 2017 seinen Höhepunkt erreichte) durchbrochen. Überoptimistische Behauptungen über den Wert der neuen Technologie wurden durch Skepsis ersetzt, und verwandte Technologien, einschließlich Hyperledger, litten ebenfalls unter dieser Skepsis.

### Die Konkurrenten von Hyperledger Fabric

Hyperledger Fabric konkurriert mit anderen Hyperledger-Projekten wie Iroha, Indy und Sawtooth. Es konkurriert auch mit Corda von R3, das ebenfalls ein privates, genehmigungsbasiertes DLT ist.

Das Blockchain-Dienstleistungsunternehmen Chainstack veröffentlichte im Januar 2020 ein Papier , das zeigt, dass die Entwicklung bei Corda historisch höher war als die Entwicklung bei Fabric, obwohl die Entwicklung von Fabric die von Corda im dritten Quartal 2019 überholte, als Fabric zu GitHub wechselte.

Der Chainstack-Bericht zeigt, dass, obwohl dreimal so viele Entwickler an Fabric arbeiten, Corda-Entwickler mehr als doppelt so viele Codebeiträge geleistet haben und Fabric-Entwickler weit weniger Code pro Entwickler pushen als die Entwickler von Corda.

### Hyperledger Fabric ist keine Blockchain und nicht effizient

Mehrere Kritiker von Hyperledger Fabric weisen darauf hin, dass eine berechtigungsbasierte, private Blockchain mit den Funktionen von Hyperledger Fabric keine Blockchain ist und aktuelle Nicht-Blockchain-Technologien weitaus kostengünstiger sind und das gleiche Maß an Sicherheit bieten. Stuart Popejoy von Cointelegraph drückte den Fall so aus:

>

> Die Architektur von Fabric ist weitaus komplexer als jede Blockchain-Plattform und gleichzeitig weniger sicher gegen Manipulationen und Angriffe. Man sollte meinen, dass eine „private“ Blockchain zumindest Skalierbarkeit und Leistung bieten würde, aber auch hier versagt Fabric. Einfach ausgedrückt, Piloten, die auf Fabric basieren, werden mit einer komplexen und unsicheren Bereitstellung konfrontiert, die nicht mit ihrem Unternehmen skalieren kann .

>

Hyperledger Fabric wurde auch wegen mangelnder Widerstandsfähigkeit kritisiert. Ein Forscherteam der Sorbonne in Paris und CSIRO – Data61, Australiens nationaler Wissenschaftsagentur, stellte fest, dass erhebliche Netzwerkverzögerungen die Zuverlässigkeit von Fabric verringerten: „[B]y delaying block propagation, we demonstrierte, dass Hyperledger Fabric keine ausreichenden Konsistenzgarantien bietet zum Einsatz in kritischen Umgebungen. "

## Hyperledger Fabric 2.0 veröffentlicht im Januar 2020

Im Januar 2020 wurde Hyperledger Fabric 2.0 veröffentlicht, um einige der bestehenden Kritikpunkte anzugehen. Laut Ron Miller von Techcrunch „bestehen die größten Aktualisierungen darin, eine Einigung zwischen den Parteien zu erzwingen, bevor neue Daten in das Ledger aufgenommen werden können, was als dezentrale Governance der Smart Contracts bekannt ist.“

Obwohl das Update keine grundlegende Veränderung in der Einfachheit oder Anwendbarkeit von Fabric darstellt, zeigt es doch, dass in der Kryptowährungsbranche über die Krypto-Manie von 2018 hinaus weiterhin Fortschritte erzielt werden. In den nächsten fünf bis zehn Jahren ist es so erwartet, dass die Unternehmens-Blockchain zweifellos ihre angemessene Verwendung finden wird.

## Höhepunkte

- Hyperledger ist ein verteiltes Open-Source-Ledger-Framework der Enterprise-Klasse, das im Dezember 2015 von der Linux Foundation eingeführt wurde.

- Da Hyperledger Fabric privat ist und eine Zugriffsberechtigung erfordert, können Unternehmen Informationen (wie Preise) trennen und Transaktionen können beschleunigt werden, da die Anzahl der Knoten im Netzwerk reduziert wird.

- Fabric 2.0 wurde im Januar 2020 veröffentlicht. Die Hauptmerkmale dieser Version sind schnellere Transaktionen, aktualisierte intelligente Vertragstechnologie und optimierter Datenaustausch.

- Fabric ist eine hochmodulare, dezentralisierte Ledger-Technologie (DLT)-Plattform, die von IBM für den Einsatz in Industrieunternehmen entwickelt wurde.

