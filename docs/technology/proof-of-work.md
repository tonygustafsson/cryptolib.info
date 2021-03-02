---
layout: default.hbs
title: Proof of Work (PoW)
description: A consensus model where miners perform costly calculations to calculate millions of checksums per second, and where the winner is rewarded in the currency of the currency.
mainImage: img/proof-of-work.jpg
author: Tony Gustafsson
created: 2019-07-22
modified: 2021-03-01
---

# Proof of Work (PoW)

![Proof of Work](../img/proof-of-work.jpg 'Proof of Work')

Proof of Work is a consensus model where all miners perform costly calculations, where processing power or graphics processing power is used to generate large numbers (guesses) per second, and whoever guesses right first "wins". They are thus rewarded with a prize. However, it is quick to verify that one of these guesses is correct, which makes the system excellent to use for cryptocurrencies such as [Bitcoin](/cryptocurrencies/bitcoin.html) and [Litecoin](/cryptocurrencies/litecoin.html).

However, Bitcoin was not the first to use this model. It was invented as early as 1993 by Cynthia Dwork and Moni Naor, but became known only in 2009 with Bitcoin.

## Hashes / Checksums

A "guess" is hash / checksum, which is a technical term for a relatively short string of letters and numbers. They are often used to produce a kind of summary on a file that can verify the authenticity of a file. It is also used to store users' passwords in a database, where you can hash the user's password when logging in and compare with what is in the database. If the database is compromised, the passwords cannot be read as it is a one-way encryption.

This is an example of a checksum on "This is a test", generated with SHA-256:

```
e6fa10085b270d8eaeeb21e037287e58e20e3a526950db97663d3d4072b8fc2e
```

## Difficulty

All miners in the Bitcoin network, for example, guess millions of checksums per second, which costs a lot of time and money in electricity, but whoever guesses correctly is thus rewarded with Bitcoins. It is the blocks header (that contains x number of transactions) that is being hashed. What should come out as a result is a hash that begins with 18 zeros. The number of zeros required changes after the 2016 block, which determines the difficulty level. The more computing power there is in the network, the higher the difficulty level. Something that is automatically regulated by the network.

It usually takes several minutes to calculate a hash that corresponds to the degree of difficulty. In the case of Bitcoin, it currently takes about 10 minutes, which also corresponds to the transaction time. It requires enormous amounts of energy to succeed, so you are currently rewarded with 12.5 Bitcoins (at the time of writing, it's about $625,000). But this is a sum that is halved at certain intervals. The next halving will take place in March 2024.

In the genesis of [Bitcoin](/cryptocurrencies/bitcoin.html), you could mine just fine on a regular computer - especially with one with a good graphics card. But when specially designed computers (ASICs - Application Specific Integrated Circuit) were created, which are exceptionally good at hashing, the difficulty increased rapidly. Today, therefore, it is basically impossible to succeed in cracking an acceptable hash in time with a regular computer.

![Mining farm](../img/mining-farm.jpg 'Mining farm') An example of a mining farm with ASICs, specially built to generate checksums.

The great thing about Proof of Work is that it is the previous block that is being hashed, and in this way you always insure the previous block (hence a chain with blocks is created, hence "[blockchain](/technology/blockchains.html)". It therefore becomes extremely difficult to fool the network with creating a new block and try to add that to the blockchain, since there are thousands of miners validating each other. Proof of Work is considered very secure. No one has so far managed to hack Bitcoin.

![Förklaring av Proof of Work](../img/proof-of-work-explanation.png 'Förklaring av Proof of Work')

The disadvantages are, of course, that it is slow and requires a lot of energy. Therefore, many modern cryptocurrencies are moving away from this consensus model, towards eg [Proof of Stake](/technology/proof-of-stake.html) or [DAGs](/technology/directed-acyclic-graphs.html). Much criticism has been leveled at Bitcoin because it has been calculated that the power to keep the network afloat requires as much electricity as the whole of Switzerland uses, or 0.5% of the entire world's electricity consumption. But of course you also have to ask yourself how much energy is required in the production and transport of gold, and also around the entire banking system.
