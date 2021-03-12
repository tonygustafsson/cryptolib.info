---
layout: default.hbs
title: How to use Uniswap
description: Uniswap is one of the most popular decentralized exchanges today, but is not always that easy to use.
mainImage: img/guides/uniswap/uniswap.webp
author: Tony Gustafsson
created: 2021-03-12
modified: 2021-03-12
---

# Uniswap

![Uniswap](../img/guides/uniswap/uniswap.webp 'Uniswap')

Uniswap is by far the largest [decentralized exchange](/market/exchanges.html) today. The fact that it is decentralized means that there is no central body that charges fees or handles orders, deposits or withdrawals. It is a free market between those who buy, sell and those who offer liquidity through special pools.

Uniswap is [Ethereum](/cryptocurrencies/ethereum.html) only, and all ERC-20 tokens on it. It also requires an Ethereum wallet, such as [Metamask](/guides/metamask.html), WalletConnect, Coinbase Wallet, Fortmatic or Portis.

Metamask is the most common wallet, and if it is the one you intend to use, we recommend that you [first understand how Metamask works](/guides/metamask.html).

## Table of Contents

-   [Pricing](#how-does-pricing-work)
-   [Fees](#fees)
-   [Finding tokens](#finding-tokens)
-   [Buying](#buying)
-   [Selling](#selling)
-   [More information](#more-information)

## How does pricing work?

Uniswap does not have an order book like a normal exchange. They also do not check prices via a third party, or an [oracle](/technology/oracles.html). Instead, they use a technology called _Automatic liquidity protocols_. In short, it is about being able to automatically generate a price between two currencies with the help of [smart contracts](/technology/smart-contracts.html).

Anyone can set up liquidity pools between two currencies. For example, 50% ETH and 50% REN, and this balance will always be maintained, acting as pools people can buy from. When you take currency out of the REN pool, prices are affected because supply changes. It creates a system that consists of those who provide liquidity, those who buy and those who sell - completely without a central body.

![Uniswap](../img/guides/uniswap/uniswap-liquidity-pools.webp 'Uniswap')
_In a liquidity pool, there must always be an equal amount of each trading pair_

## Fees

Those who contribute to the liquidity pools need an incentive to contribute, therefore the fees go from those who buy and sell to them. Today, the fee is 0.3% of each trade, but it may be reduced in the future.

Unfortunately, the 0.3% fee is not the only fee, but you also need to pay [Ethereum](/cryptocurrencies/ethereum.html) miners to validate your transaction. The price for this varies based on the load on the network, as well as how much you are willing to pay.

Usually, the best option is to choose the fastest and most expensive option when it comes to transaction fees on Uniswap because a slow transaction is often interrupted. And an interrupted transaction does not give you the fee back. Most often, an interrupted trade is due to the price having changed too much before the transaction had time to be validated.

Another thing to keep in mind is that you influence the price of currencies by buying and selling. If you trade currencies that have very small liquidity pools, it may happen that your trade affects the price so much that Uniswap says _STOP!_ It may open up for other traders to catch up with you if they see that prices will change.

### Slippage example

You exchange ETH for REN and pay 0.02 ETH in transaction fees. It is announced on the Ethereum network that the transaction needs to be validated. Someone else detects this and can calculate (with robots of course) that it will increase the value of REN because you buy so much. They can then quickly make their own order on REN but pay 0.05 ETH in transaction fee, which means that miners will probably prioritize their transaction. What then? Well, the prices of REN have time to change before your purchase goes through. Slippage then occurs. Fortunately, Uniswap does not allow too much of a possibility for slippage.

## Finding tokens

You can find most tokens on Uniswap by clicking on the list with the "Select a token" button. There are thousands to choose from. But if your token is _not_ listed here, you can possibly find it by searching for your token on [CoinGecko](https://www.coingecko.com), clicking on the "Markets" tab and clicking on the Uniswap pair.

![Uniswap](../img/guides/uniswap/uniswap7.webp 'Uniswap')
_Here you see a long list of tokens to swap between on Uniswap_

A last resort is to find out your token's contract address, which you can get either at [CoinGecko](https://www.coingecko.com) or [EtherScan](https://etherscan.io/). You then visit:

```
https://app.uniswap.org/#/swap?outputCurrency=[CONTRACT-ADDRESS]
```

## Buying

Visit https://app.uniswap.org/ and click on "Connect Wallet".

![Uniswap](../img/guides/uniswap/uniswap1.webp 'Uniswap')

Then select which wallet you want to use, for example [Metamask](/guides/metamask.html). If you have Metamask installed, it will ask for a password if you have not used it for a while. Select the account you want to connect with and tap Next. Accept the signature - this costs nothing.

![Uniswap](../img/guides/uniswap/uniswap2.webp 'Uniswap')

Now the screen changes to something similar to the above. You see how much you convert _from_ and how much you will get. "Minimum received" means that it takes slippage into account. If you accept that the price can be changed 1% up or down from the time you place the order until it goes through, this shows the least you can get. You can change the slip tolerance on the gear at the top right.

When you are ready, click "Swap".

![Uniswap](../img/guides/uniswap/uniswap3.webp 'Uniswap')

You now see a summary of it all. When you are ready, click "Confirm Swap", after which your wallet should open automatically.

![Uniswap](../img/guides/uniswap/uniswap4.webp 'Uniswap')

If you use Metamask, it will look something like this. Other wallets look different but follow roughly the same concept. If you want to know more about Metamask and what you should think about, check out the [Metamask Guide](/guides/metamask.html).

The important thing here is to make sure that you pay enough in transaction fee (Gas fee) for the transaction to go through. Again, this is the fee for miners on the Ethereum network. The fees for those who hold the liquidity pools have already been deducted. Click on "EDIT" next to "Gas fee" to change your fee - choose the fastest and most expensive if you want to be sure that it goes through. But of course you do not want to pay too much, especially if you buy for smaller amounts. Then it may be a good idea to wait a bit.

## Selling

To sell, for example, TRAC to ETH, select the currencies in _from_ and _to_. And choose how much you want to swap.

![Uniswap](../img/guides/uniswap/uniswap5.webp 'Uniswap')

Selling tokens actually works in the same way as buying tokens. Because it's about exchanging tokens between each other. The difference occurs if you want to exchange one ERC-20 token for Ethereum, or if you want to exchange one ERC-20 token for another ERC-20 token. What you then have to do is first agree that Uniswap has the right to withdraw this currency from your account. This is a transaction on the Ethereum network and therefore costs a fee. But this only happens the first time you sell a currency, then it costs nothing to sell the same currency again.

You will meet the sign below if you use Metamask. You can change your transaction fee if you wish. Then click "Confirm". This may take about a minute, but do not panic if it takes longer than that.

![Uniswap](../img/guides/uniswap/uniswap6.webp 'Uniswap')

When it is ready, it says "Approved" on Uniswap and you can then select "Swap". Then follow the same procedure as [when you buy](#buying).

## More information

-   https://uniswap.org/faq/
-   https://academy.binance.com/en/articles/what-is-an-automated-market-maker-amm
-   https://nightlycrypto.medium.com/what-the-heck-is-an-automated-market-maker-amm-3adb753ea5c7
