---
keywords: Crypto
title: Bloom Filter
description: Bloom Filter. A data structure which can be utilized to illuminate the client whether a particular thing is part of a set of things
---

# Bloom Filter
A Bloom filter is a data structure that can be utilized to illuminate the client whether a particular thing is part of a set. However it can't say with certainty whether an element is in the set, it can say with certainty on the off chance that the element isn't.
Made by Burton Howard Bloom in 1970, Bloom filters are an alluring offering for a scope of applications due to their proficiency in space utilization. In some cryptographic forms of money (most eminently Bitcoin), they play a fundamental job in Simplified Payment Verification, or SPV.
In utilizing a SPV client, users can connect with the Bitcoin network without running a full node. Full nodes accompany certain storage and computational requirements that make them clumsy to run on low-fueled gadgets like cell phones. SPV clients, then again, basically question full nodes for data applicable to the client's wallet(s).
The most clear solution to transfer this data to the client would be by making full nodes aware of the client's keys, with the goal that main relevant transactions are shipped off them. Obviously, this is a disappointing solution as the client's privacy would be forfeited. Then again, downloading all transactions just to dispose of the majority of them would be a misuse of bandwidth. Enter Bloom filters.
How about we outline. Assume that a client, Alice, has a high-esteem transaction she doesn't need Bob, who runs a full node, to know about. She develops a Bloom filter, which we'll delineate as a 10x1 grid:

She passes the transaction data she is keen on through two different hash capabilities, which yields two numbers somewhere in the range of 0 and 9. We should call them 4 and 7. She sends the filter to Bob.

Taking a gander at this grid, you have no clue about what data Alice has passed to the filter. In the event that you had a set where the data was contained, you would have the option to hash it and compare it with the filter - assuming there's a match, there's a possibility that it was the data that Alice requested.
Simultaneously, there's probably going to be many sources of info that will guide to 4 and 7, so Bob can't figure out which part of the data Alice is keen on. He basically returns all of the matches, and Alice filters them on her end.
This is, of course, a gross distortion, however it shows the concept: Bloom filters muddle the true interests of the client. It's anything but a perfect method (there are still worries over its privacy), yet it's an improvement over an unshielded request to a node.
