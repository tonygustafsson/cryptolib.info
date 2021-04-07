---
layout: default.hbs
title: Oracles - Crypto services we can trust
description: A service that offers external data to smart contracts and blockchains in a reliable way.
mainImage: img/oracles.webp
author: Tony Gustafsson
created: 2020-08-03
modified: 2021-03-01
---

# Oracles

![Oracles](/img/oracles.webp 'Oracles')

An oracle is a service that can provide [smart contracts](/technology/smart-contracts.html) with external information from the real world. Smart contracts follow a given program code and when certain set goals are reached, they are executed. But they can never make decisions based on anything other than what is on the [blockchain](/technology/blockchains.html). This is a limitation that makes things like randomness in games, market information or other external services impossible.

If you want to create a contract that says that if Manchester United wins the game on Friday, those who have invested money in this will get a return. How should your contract know if they won or lost? And how do those who play know that they can trust the information that comes from the system? The whole point of blockchains is to not have to rely on any party.

This is where oracles come into the picture. It is a service that delivers reliable information from the world, in a way that does not require trust. They do not keep the information themselves, but oracle is the middle layer that retrieves the information, verifies and authenticates external data. For example, if a payment has been processed or if the temperature is above 25 degrees Celsius in Oslo.

## Security

In the end, the use of oracle services is always a risk. Should they provide incorrect information, the smart contracts can do nothing but follow them. If, for example, someone were to try to hack the information to trick the systems into believing that Manchester United lost, because he invested money in this, it is easier than hacking the blockchain in question.

To try to get out of these problems, one usually uses several data sources and several oracles in parallel. There are also methods to provide financial incentives not to cheat the system, as it punishes the bad guy. Hardware oracles (measuring instruments) can also prove the authenticity of their data through zero knowledge proofs, without actually showing how they arrived at the measured values.

![Informationsflöde för orakel](/img/oracles-info.webp 'Informationsflöde för orakel')

## Cost

Nothing is free, as it requires computing power and storage to succeed in this, and someone wants to be paid for their services. Usually, an oracle service has its own currency or token, which is required as a payment method to use their service. There is thus an integration between a blockchain and the oracle service in question. It also costs to use a smart contract (transaction fee).

Today, the cost can be too high to attract a large audience. Therefore, a lot of time and money is spent on developing new decentralized networks to make the systems faster and more cost-effective, without compromising security.

## Example of oracle services

-   [ChainLink](https://chain.link/)
-   [Augur](https://augur.net/)
-   [DOS Network](https://dos.network/)
