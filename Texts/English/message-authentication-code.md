---
keywords: Personal Finance,Banking
title: Message Authentication Code (MAC)
description: A message authentication code (MAC), or tag, is a security code that is composed in by the client of a computer to access accounts or gateways.
---

# Message Authentication Code (MAC)
## What Is a Message Authentication Code?

A message authentication code (MAC), or **tag,** is a security code that is composed in by the client of a computer to access accounts or entries. This code is appended to the message or request sent by the client. Message authentication codes (MACs) appended to the message must be recognized by the getting system to grant the client access.

## Understanding Message Authentication Code (MAC)

Message authentication codes (MACs) are ordinarily utilized in [electronic funds transfers](/electronic-funds-move act) (EFTs) to keep up with data integrity. They affirm that a message is bona fide; that it truly comes, at the end of the day, from the stated shipper, and hasn't undergone any changes on the way. A verifier who likewise has the key can utilize it to recognize changes to the substance of the message being referred to.

Message authentication codes are normally required to access any sort of financial account. Banks, brokerage firms, trust companies, and some other deposit, investment, or insurance company that offers online access can utilize these codes. They are an indispensable component of financial cryptography.

## Algorithms Used to Generate MACs

Three algorithms normally involve a MAC: a key generation algorithm, a signing algorithm and a confirming algorithm. The key generation algorithm picks a key at random. The signing algorithm sends a tag when given the key and the message. The checking algorithm is utilized to confirm the credibility of the message when given the key and tag; it will return a message of **accepted** in the event that the message and tag are legitimate and unaltered, however if not, it will return a message of **rejected.**

For instance, the source communicates something specific, for example, an EFT, through the MAC algorithm, which creates a key and joins a MAC data tag to the message. The beneficiary receives the message, runs it back through the MAC algorithm with a similar key, and gets a subsequent data tag. They will then, at that point, compare this MAC data tag with the first appended to the message when it was communicated. In the event that the code is something very similar at the two finishes, the beneficiary can securely accept that the data integrity of the message is flawless. If not, nonetheless, it means that the message was altered, messed with, or manufactured.

Nonetheless, the actual message ought to contain a few data that guarantees that this message must be sent once. For instance, a one-time MAC, timestamp, or sequence number could be utilized to guarantee that the message must be sent once. Any other way, the system could be powerless against a replay attack, in which an attacker blocks the message after it has been decoded and retransmits it sometime in the not too distant future, recreating the original outcomes and penetrating the system.

## Message Integrity Codes (MICs)

Sometimes, the term message integrity code (MIC) will be utilized rather than MAC. This is most frequently done in the communications industry, where MAC generally means media access control address (MAC address). In any case, MIC can likewise be utilized to allude to **message digest,** which doesn't involve secret keys in a similar way as a MAC, and can't offer a similar level of security minus any additional encryption.
