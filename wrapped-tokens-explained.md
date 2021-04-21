# Wrapped Tokens Explained

The DeFi ecosystem originated within Ethereum, and despite tremendous fees, most liquidity and project building are still situated there. A key technical solution that stimulated the influx of capital into DeFi was the so-called AMM DEX, or automated market-making decentralized exchanges. The most inventive underlying concept of AMM DEX is an LP token, which is essentially an asset that represents the share of a liquidity provider in a liquidity pool of some AMM service.

### LP tokens structure

The inner workings of liquidity pools on AMMs are as follows. A pool, as a storage of tokens that enables instant exchanges, is formed from several assets, most often two, which tend to have identical volumes. When setting up liquidity for a token pair on any AMM exchange, pools have what is called a [Base token and a Quote token](https://dodoex.github.io/docs/docs/pmmDetails). As an example: for the USDN / BNB token pair on PancakeSwap, USDN is the Base token, while BNB is the Quote token. In a blockchain where a pool is located, either the native token of the platform \(eth, bnb, waves, ht, ftm\) or a liquid stablecoin \(dai, usdn, usdt, busd, husd\) usually acts as the Quote token. The Base token is usually either a token of some project issued on the blockchain, or “wrapped” into it through a cross-chain bridge from another platform.

Example 1: Gravity-wrapped gwUSDN \(Waves as origin chain\) / BNB \(native token of BSC\) on Bakery Swap

[https://bscscan.com/address/0x57d2879fa09fbc93d0b21122819a408a52a2ddaa\#internaltx](https://bscscan.com/address/0x57d2879fa09fbc93d0b21122819a408a52a2ddaa#internaltx)

Example 2: multichain.xyz wrapped DPI \(eth as origin chain\) / BNB \(native token of BSC\) on Pancake Swap

[https://bscscan.com/token/0x069784dd0e8326c849075270c14903b77a416cc2](https://bscscan.com/token/0x069784dd0e8326c849075270c14903b77a416cc2)

Typically the dollar equivalent value of the base and quote tokens in a pool are equal, otherwise an arbitrage opportunity occurs and this imbalance is quickly corrected. 

In total, there are four attributes associated with each LP token: blockchain, AMM service, base token and quote token. The number of tokens itself represents the share of an LP holder in an AMM pool.

### Cross-chain bridges

DeFi tokens are typically deployed onto a single blockchain network: the origin network which provides the technological foundation for DeFi services of a project and / or where the token is issued. However, the isolation of such a token from other blockchain ecosystems and communities can hinder the potential growth of its liquidity. The incentive to expand the exposure and open the access to DeFi projects for traders and investors of various ecosystems has been pushing forward the development of the interchain DeFi industry, which began in 2020 and still continues to advance.

One of the results of interchain DeFi’s evolution is the proliferation of gateways or bridges. As of today, a multitude of large blockchain projects have released their own gateway solutions: two prominent examples are Bridges from Binance Smart Chain, or the Wormhole bridge from Solana. Also, a few projects that specialize on cross-chain swaps have been recently gaining popularity: [multichain.xyz](http://multichain.xyz), [ren project](https://renproject.io/), and [Gravity protocol](http://gravity.tech).

Different gateway solutions have their own advantages and disadvantages, and vary in the level of decentralization, community support, capitalization, swap time, supported ecosystems and tokens, and fees.

Now, any token that was issued via an interchain bridge falls into the wrapped token category. Let us further expand on why just issuing a wrapped token is not sufficient to make it usable within a destination ecosystem. 

### Wrapped Tokens Liquidity

A recently wrapped token issued via a bridge does not itself carry any value in the target chain \(the chain that it was wrapped into\), since no one, except for the issuer, has any means of buying and trading it. In order for the wrapped token to become functionally useful, it first needs to be listed on a DeFi service that operates within the target chain, such as an AMM exchange. 

The standard route that one can take to integrate a wrap token into any AMM service is to create a liquidity pool for an actively used quote token on the target chain, for example, the native token \(eth, bnb, waves, ht, ftm\) or a stablecoin \(dai, usdn, usdt, busd, husd\).

As soon as such a pool is created, it immediately adds the following utilities to the token: it becomes liquid in the target chain \(meaning that it can now be sold or bought\) and arbitrage opportunities are now available between the two blockchain systems, since in the origin chain the asset can be either more or less expensive than in the target chain, which encourages traders to profit on trading operations and cross-chain swaps.

There always remains a chicken and egg problem though: the low liquidity of a wrapped token in the target chain creates a high slippage when buying or selling it, and this leads to a shortage of trading volumes, which makes it less attractive for traders to add the wrapped token into pools. This inefficiency is usually very slow to resolve over time, because a critical mass of early adopters and affiliates needs to arise first, which, through the network effect, can finally lead to an increase in liquidity and volumes.

In order to boost this process of liquidity growth, extra incentives are necessary, for example, in the form of farming rewards for providing liquidity. This is partially solved by the likes of CAKE and CRV, but in case of wrapped tokens, LP farming rewards are often not farmable from the get-go and require additional approvals and verifications. However, if participants are provided with proper rewards for creating and staking WT LP on various AMM services, this inevitably leads to an increase in volume and exposure of wrapped assets in new ecosystems. This is the main aim of Graviton, as it unites ecosystems, DEXes, and DeFi projects around a common mission -- to boost liquidity and hence the overall adoption of wrapped tokens.

