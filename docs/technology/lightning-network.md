---
layout: default.hbs
title: Lightning Network
description: A layer-2 solution for Bitcoin and Litecoin, among others, which solves the problem of scalability. Transactions no longer take place on the layer-1 chain, only the result of the layer-2 chain is stored.
mainImage: img/lightning-network.webp
author: Tony Gustafsson
created: 2021-03-09
modified: 2021-03-09
---

# Lightning Network

![Lightning Network](/img/lightning-network.webp 'Lightning Network')

Lightning Network is a payment network located on top of [blockchains](/technology/blockchains.html) such as [Bitcoin](/cryptocurrencies/bitcoin.html) and [Litecoin](/cryptocurrencies/litecoin.html), and is therefore called a layer-2 solution. The proposal was developed by Joseph Poon and Thaddeus Dryja in 2015 and came out as a beta in 2018.

The purpose of Lightning Network is to solve the problem of scalability. It provides extremely cheap and fast transactions, which makes it possible to pay with Bitcoin for a coffee or send microtransactions. The technology is not intended for larger transactions because the security is not as high as on the underlying blockchain.

Today, [Bitcoin](/cryptocurrencies/bitcoin.html) is mostly a way to store value, a bit like a savings account. But when Lightning Network is ready, it makes it possible to let Bitcoin be a real currency that is used everyday, to buy coffee, a hamburger or pay for a parking space.

## Advantages

-   Increased integrity as all transactions between two parties are not saved publicly on a chain.
-   Fast transactions, usually under the minute, often in a few milliseconds (instead after 10+ minutes).
-   Cheap transactions, it usually costs a penny.
-   The number of simultaneous transactions. There is really no upper limit, which means that the system can compete with VISA and MasterCard.

## Disadvantages

-   Not really ready for use yet, still experimental, despite the development going on since 2015.
-   Both parties must be online for the transaction to go through.
-   Lower security than on the block chain.
-   As the development has been slow, there has been competition from other solutions where Bitcoin's value rests on other blockchains instead, such as [Wrapped Bitcoin (wBTC)](https://wbtc.network/) on [Ethereum](/cryptocurrencies/ethereum.html) and RenBTC at [REN](https://renproject.io/).

## How it works

Payment channels are created between two parties. A sum of BTC is dedicated to the channel on the blockchain (layer 1), and only when one of the partners exits the payment channel, the cost is charged "for real". Before that, it is information that only the two parties know about, but of course no one can spend money he does not have.

You can also send money to parties you do not have a directly set-up payment channel to through a routing protocol similar to [TOR](https://www.torproject.org/download/). Each person who creates a payment channel chooses what it will cost to send money through the channel - but if it is too expensive, people will of course choose a different route. In general, it is very cheap, even to make a payment through many parties / nodes.

![Lightning Network Test network](/img/lightning-network-nodes.webp 'Lightning Network Test network')
_An example of a routed Lightning Network_

## Support

Today, there is unfortunately poor support for the technology, but if you are a little knowledgeable about technology, it is absolutely possible to use it today. Wallets that support the technology include [Wallet of Satoshi](https://www.walletofsatoshi.com/), [Breez](https://breez.technology/), [BLW](https://lightning-wallet.com/) and [Eclair](https://play.google.com/store/apps/details?id=fr.acinq.eclair.wallet.mainnet2).

Marketplaces that support the Lightning Network include [Bitfinex](https://www.bitfinex.com/), [OkEx](https://www.okex.com/) and [River Financial](https://river.com/).

More information:

-   [Understanding the Lightning Network](https://bitcoinmagazine.com/technical/understanding-the-lightning-network-part-building-a-bidirectional-payment-channel-1464710791)
-   [Lightning Network](https://lightning.network/)
