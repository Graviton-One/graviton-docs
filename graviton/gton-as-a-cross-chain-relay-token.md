# GTON as a multichain relay token

_In this article, we explain_ [_GTON’s_](https://v1.graviton.one/gton) _use as a proxy token for pairing wrapped tokens with liquid assets on destination chains, enabling an interconnected system of pools with fast and low-slippage token swaps._

![](https://miro.medium.com/max/1400/0\*D-D6QtEk-zShHTVA)

## Token in the middle… <a href="#6e59" id="6e59"></a>

[Bancor’s](https://storage.googleapis.com/website-bancor/2018/04/01ba8253-bancor\_protocol\_whitepaper\_en.pdf) original idea of the “relay token” [$BNT](https://www.coingecko.com/en/coins/bancor-network#markets) was groundbreaking, but a bit ahead of its time and therefore did not find much traction. Nowadays, we observe a growing demand for cross-chain technologies and tokens in DeFI, and it might be time to revive this approach in the form of a cross-chain relay token.

![Anton Bukov’s (@k06a) presentation about 1inch routing](https://miro.medium.com/max/1400/0\*Q\_Hmxd9AbvqdEApy)

At its core, [$GTON](https://www.coingecko.com/en/coins/graviton#markets) is being developed as a relay token playing a similar role as $BNT in Bancor, but why adopt an early approach which was not particularly successful?

At this point of DeFi evolution, with a multitude of new competing blockchains, a wide adoption of cross-chain technologies is essential for the synergetic growth of the industry. In the meantime, the demand for wrapped assets is growing, and hence the demand for their liquidity.

The concept of LP [**liquidity mining**](https://www.youtube.com/watch?v=cizLhxSKrAc) and [**farming**](https://www.youtube.com/watch?v=ClnnLI1SClA) has become well-known among DeFi users and is currently an optimal strategy for incentivizing them to make important actions. All popular chains have AMM dApps with LP rewards as the basis.

Therefore, we strongly believe that the current state of the market and technology demonstrates a renewed interest in the “token-in-the-middle” concept, as we now possess all the necessary pieces to finally make this approach useful for a wide audience while also stimulating the growth of the token itself through network effects.

_Within such a system, LP produces a network effect when the more liquidity is added to a single pool, the more liquid the overall system becomes due to being interconnected. Increasing liquidity is always beneficial because it decreases slippage for buying/selling, and since the relay token plays an important role in that, its value also increases._

## How does a relay token (RT) work? <a href="#6093" id="6093"></a>

Let’s review a system with three tokens: X, ETH and RT.

> Token X has a large liquidity in pair with the RT token. If in turn the RT token has enough liquidity to ETH, it is **easy to buy/sell** X for ETH **via RT** in two transactions: **X -> RT -> ETH**.

This means that _increasing liquidity for all RT pairs is increasing liquidity for proxy pairs as well_.

Within such a system, LP produces a network effect when the more liquidity is added to a single pool, the more liquid the overall system becomes due to being interconnected. Increasing liquidity is always beneficial because it decreases slippage for buying/selling, and since the relay token plays an important role in that, its value also increases.

## What is a cross-chain relay token? <a href="#618f" id="618f"></a>

![](https://miro.medium.com/max/1400/0\*lpADx8MpBJMjVUso)

If a token only exists on a single chain, it **cannot be traded/used** on another chain. To make this possible, **cross-chain bridges** are necessary that can **wrap** assets onto other chains. However, **wrapped assets** are worthless for traders unless they become added to AMM DEXes and acquire enough liquidity.

So, an asset with a large liquidity for native tokens/stablecoins on different destination chains and liquid AMM pairs for wrapped assets are two necessary components for solving liquidity issues of wrapped assets.

_Exactly the same logic of Relay Token utility is applicable for all non liquid in DeFi assets such as CEX tokens, new projects and wrapped tokens (already well described in this article)._

_This is the main goal that_ [_$GTON_](https://v1.graviton.one/gton) _solves by being at the very core of the Graviton’s cross-chain LP reward system._

## A token in the middle <a href="#f98b" id="f98b"></a>

Above_,_ the use of GTON as an AMM relay token was considered, which allows one to trade wrapped assets with minimal slippage, provided that the incentives are set up properly, i.e. the users have sufficient motivation to participate in LP farming by putting liquidity into GTON pairs with wrapped tokens, stablecoins, and native tokens.

Another GTON use case, as a so-called cross-chain relay token, consists of exchanging a native token on one blockchain into a native token on another blockchain, without involving a bridge for making cross-chain swaps.

## Mirror Accounts <a href="#75a1" id="75a1"></a>

Most DeFi users have an account on the Ethereum network with some amount of Ethereum on it. Imagine a situation when such a user discovers the Fantom network and becomes interested in trying what it has to offer. Despite the fact that Fantom is an EVM chain, which means that a user can utilize their existing account via Metamask for signing transactions and connect to the Fantom network in one click, one problem remains: **while their Fantom balance has no FTM tokens, the user is unable to make transactions**.

In theory, FTM could just be bought on a centralized exchange (CEX) and brought to the native chain, but not all exchanges support this functionality.

_The problem of over-complicated user experience is very pressing in the field of DeFi cross-chain and one of the most frequently mentioned problems in our_ [_poll_](https://twitter.com/OneGraviton/status/1408090152799453193?s=20)_._

So, when the user has funds on Ethereum and is curious to explore a non-EVM blockchain (e.g. Solana, Tron, Cardano, Polkadot, Cosmos), the problem of user experience becomes even more pronounced: first and foremost, they need to create an account on the desired chain and fill it with the native tokens for paying fees.

The “mirror account” concept developed by the Graviton team is a product solution that will greatly simplify the user’s experience and their ability to use other popular blockchain networks by solving the problem of decentralized purchase of the native token in a destination chain, and then **automatically creating an account** which can be controlled by singing from an already existing Metamask Ethereum account. To do that, the Mirror Account service within the Graviton project stores a map of user accounts in various networks.

Note that focusing on Ethereum accounts is just the starting point because this concept can work in all directions. In addition, we have already seen a lot of users with other blockchain networks (BSC, Solana, Polygon, etc.) as their first platform.

As an example, the rest of this article describes buying the native token in Solana, a destination blockchain, by spending the native token of the original blockchain network.

## Relay Token <a href="#107f" id="107f"></a>

On each of the integrated blockchains, the GTON token has [AMM DEX pools](https://www.youtube.com/watch?v=cizLhxSKrAc) for their native tokens. For providing **liquidity to the GTON token** in these pools, a **reward** is paid out ([see LP farming](https://forum.graviton.one/t/staking-farming-allocations-distribution/51/14)). For example, on the Ethereum blockchain, there is a GTON pool to ETH (on Uniswap), on the Solana blockchain, there is a pool to SOL (on Serum), and on Polygon and Fantom, respectively, to MATIC and FTM.Cross-chain Swap: $ETH -> $SOL (**EVM <-> non-EVM**)

![](https://miro.medium.com/max/1400/1\*ekcAUaplIOxlWLeSCIRzgA@2x.png)

When a user from the Ethereum network makes a deposit converting ETH on Ethereum into SOL on Solana, a few operations take place:

1. _ETH is sold for GTON on an AMM pool in the Ethereum network._
2. _GTON is immediately locked on smart contracts of the Graviton system (Mirror Account)._
3. _The oracles notice this event and signal it to Mirror Account’s smart contracts on the Solana side. There, in turn, an equivalent amount of GTON is unlocked and sold for SOL in an AMM pool on the Solana blockchain._
4. _The purchased native tokens of the Solana blockchain are transferred to the user’s account._

It is important to note that price oracles are not required in such a system, since the rate is determined automatically when buying and selling GTON in AMM pools on the corresponding chains. However, it still needs reliabl oracles that will read events from one blockchain and signal them to another, such as, for example, [Gravity Oracles](https://gravity.tech), [Band Protocol](https://bandprotocol.com) or [Chainlink](https://chain.link).Cross-chain Swap: $BNB -> $MATIC (**EVM <-> EVM**)

![](https://miro.medium.com/max/1400/0\*shLUnaI2M-TVT9cU)

This protocol works both between EVM and non-EVM (Ethereum <-> Solana) networks supported by Graviton, and between EVM and EVM (bsc <-> polygon) and even non-EVM and non-EVM (Solana <-> Waves / Tron) blockchains.Cross-chain Swap: $TRX -> $SOL (**non-EVM <-> non-EVM**)

![](https://miro.medium.com/max/1400/1\*3tjUHZU9IWPkrpviR1ABsw@2x.png)

_Thus, the GTON token plays an important role as a_ _**Relay Token**_ _for the cross-chain DeFi by allowing users not only to wrap assets, but also to convert native tokens into different chains. This is one of the main goals that_ [_$GTON_](https://v1.graviton.one/gton) _solves by being the “in-the-middle” token of the Graviton’s system._

### Revenue for GTON holders <a href="#b01a" id="b01a"></a>

As you can see, the proposed system that implements cross-chain swaps without any direct swap transactions can be monetized via the relay token (GTON) itself. For example, a minor fee of around 0.01 GTON plus 0.01% of the transaction amount can be subtracted from every transaction with GTON. The accrued fees will then be sent to the governance stakers of GTON.
