---
layout: default.hbs
title: IOTA
description: A solution for the Internet of Things based on DAG technology, which promises to solve the problem of scalability. With free and free transactions, microtransactions are made possible in a way that has not been possible before.
mainImage: img/iota.webp
author: Tony Gustafsson
created: 2019-07-29
modified: 2019-07-29
---

# IOTA

![IOTA](../img/iota.webp 'IOTA')

Official webpage https://www.iota.org/

IOTA was created in 2017 by the IOTA Foundation, and has a clear focus on the Internet of Things (IoT). Their vision is for machines to be able to communicate with other machines, and perform transactions between them. For example, the car should be able to pay customs and fees automatically and the coffee machine should be able to buy new capsules when they start to run out.

For this to work, it is believed that a transaction must be free, to enable microtransactions. It must also be fast, and given that IoT will involve billions of machines in the future, it is not possible to base the network on [Proof of Work](/technology/proof-of-work.html) and [blockchains](/technology/blockchains.html). Therefore, they chose a technique called Tangle, but which is their variant of [directed acyclic graphs](/technology/directed-acyclic-graphs.html).

Free transactions mean in theory that the network can be abused and filled with unwanted transactions that burden the network. To resolve this, each transaction must validate two other, randomly selected, transactions. This is done with a little Proof of Work work, which of course costs the CPU and thus electricity.

This is one of the shortcomings, as small IoT devices often have limited CPU power and memory. It is also not possible to offer [smart contracts](/technology/smart-contracts.html) due to the choice of Directed Acyclic Graphs (DAG). This is something you are now trying to solve with a project called [Qubic](https://qubic.iota.org/).

Qubic is intended to delegate smart contracts to specific nodes. These nodes, or [oracles](/technology/oracles.html) as they are sometimes called, can take measurements from physical reality and introduce them to their decentralized network. They can also execute something similar to smart contracts. Smart contracts combined with free transactions are something that is new to the crypto world, and is enormously powerful. For the first time, millions of smaller transactions can be sent that do not load the network, but rather contribute to it (DAGs become faster the more transactions that fill the network, instead of the other way around).

Since its inception, IOTA has been criticized for being centralized, as it had its own nodes in the network that validated transactions. This has now been abandoned to the extent that independent nodes and a decentralized system that monitors that everything goes right on the network

## Advantages

-   Their DAG solution solves the problem of scalability. Fast, and completely free transactions. With a network that gets faster the more transactions, instead of the other way around.
-   Strong community and organization.
-   Really strong partnerships.
-   Quantum computer safe technology. Quantum computers can be a threat to ordinary blockchains and all that mining is called. Something that can not affect a network that can only create transactions by validating other people's transactions.
-   Qubic can be really interesting with smart contracts in combination with microtransactions.

## Disadvantages

-   Less centralized than before, but still not what you can call decentralized.
-   Technically complex and slightly difficult for developers.
-   No smart contracts. Although Qubic is said to solve this problem, there is still a lot of mystery about how this will work. And no one sees that it can be done completely decentralized.
-   DAGs are still less proven than blockchains. The risk of security holes is considered to be greater.
-   No support for anonymous / secret transactions.

## Buying

They can buy BNB (Binance Coin) with a credit card at [Binance](https://www.binance.com) and then buy IOTA for these.

## Current price (CoinGecko)

<script src="https://widgets.coingecko.com/coingecko-coin-ticker-widget.js"></script>

<coingecko-coin-ticker-widget currency="usd" coin-id="iota" locale="en"></coingecko-coin-ticker-widget>
