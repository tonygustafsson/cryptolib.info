---
layout: default.hbs
title: Directed acyclic graphs (DAGs)
description: DAGs is a technology that promises faster transactions than blockchains and is successfully used by cryptocurrencies such as IOTA and NANO.
mainImage: img/dag.webp
author: Tony Gustafsson
created: 2019-07-22
modified: 2021-03-01
---

# Directed acyclic graphs (DAG)

![Directed acyclic graphs](/img/dag.webp 'Directed acyclic graphs')

Directed Acyclic Graph (DAG) is a challenger to the [blockchain](/technology/blockchains.html), which seeks to solve the problem of expensive transaction fees, slow transactions and poor scalability. Blockchains themselves have solutions such as layer-2 technologies (Ex [Lightning Network](/technology/lightning-network.html)), sharding and [Proof of Stake](/technology/proof-of-stake.html), but so far no one has reached speeds similar to those seen on DAG-based networks.

The concept itself is not new, but came to be known in the cryptosphere with [IOTA](/cryptocurrencies/iota.html), which is still the largest DAG currency. Even before that, there were currencies like Byteball with similar technology.

The speed and way of validating make the technology great for smaller devices, such as the Internet of Things (IoT) devices.

## How it works

In blockchains each transaction is in a block together with many other transactions, which are processed sequentially. In DAG-based projects, transactions are validated separately, and can do so asynchronously. That is, several transactions can be validated simultaneously.

To have their transaction validated, you need to validate two other, randomly selected transactions. Validation is usually done with a little [Proof of Work](/technology/proof-of-work.html). This method makes it unsustainable to misuse the network, as someone who spams the network helps to validate rather than overthrow. It also means that the transaction time actually becomes faster the more transactions that are processed - ie the opposite of blockchains.

Because of this, there is no room for miners in DAG-based currencies. There is therefore no one who needs to get a reward for work done, because you do the work yourself when you send your transaction. Therefore, the transaction fee is completely free, which provides new opportunities for microtransactions.

Each node in the network has its own blockchain, you could say. If an incorrect or false transaction is detected, the chain will spin off and continue where the last valid transaction was.

![DAG-graf](/img/dag-graph.webp 'DAG-graf')

Blockchains are secure because the encryption algorithms are secure. But a threat you can see on the horizon is quantum computers, which are extremely fast at guessing checksums in comparison to ordinary computers. You will probably find a solution to that problem when it's time, but DAG-based solutions are already protected.

## Weaknesses

Part of the criticism of DAG is that it is not as secure as blockchains, where all nodes know all transactions. This may be true in some cases, but if we are to have currencies that can be used for real, with transaction times almost in real time, some sacrifices are required. In a large DAG network, that's enough.

Another weakness is that it becomes impossible to handle [smart contracts](/technology/smart-contracts.html) in a chain where the order of the transactions does not have to be the same according to all the nodes in the network.

## Block Lattice

![Blockgitter](/img/block-lattice.webp 'Blockgitter')

Some currencies, such as [NANO](/cryptocurrencies/nano.html) and VITE, have solved the problem of [smart contracts](/technology/smart-contracts.html) by using a block lattice. It is still DAG-based technology, but there you split transactions into two different events. An event for money to be sent, and an event for money to be received. Then you can suddenly know the order of the transactions, even though the network is asynchronous.

## Hashgraphs

![Hashgraf](/img/hashgraph.webp 'Hashgraf')

Another DAG-based technology is hash graphs, which are used by, for example, Hedera Hashgraph and Tolar HashNET, is a kind of gossip protocol. Instead of a node sending a transaction communicating with two other nodes and validating their transactions, all events are communicated to two parties. The whole history and nothing less. And they in turn tell everything it knows to two parties. So it around it goes.

It creates a fast and decentralized network. It also provides the opportunity for smart contracts.
