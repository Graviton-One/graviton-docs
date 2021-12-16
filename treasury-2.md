# Interchain Treasury Architecture

![](<.gitbook/assets/image (6).png>)

_Graviton governance and initial liquidity is set in motion through treasury farming, a novel concept that revolves around automatically bootstrapping liquidity and issuing a governance token. This page briefly describes the mechanics of farming as it unfolds in the Treasury of the Graviton project._&#x20;

![](<.gitbook/assets/image (4).png>)

At its core, Graviton treasury uses Ethereum as a primary blockchain, with a range of 8 preselected liquid USD-pegged [stablecoins](https://debank.com/ranking/stablecoin). Treasury participants can deposit a stablecoin into the treasury by transferring it to a multisig contract based on [Gnosis Safe](https://gnosis-safe.io). As soon as the event of the deposit happens, it is registered by oracles and transmitted to the farm smart contract on the [Fantom blockchain](https://fantom.foundation).&#x20;

In the smart contract system on the Fantom network, the addresses of backers from Ethereum are mapped and their current “impact” is recorded in the Treasury. For each blockchain time interval, a share of new Graviton tokens ($GTON) is being unlocked and proportionally distributed among the backers. The total supply of GTON is capped at 21 million tokens.&#x20;

The original GTONs will first become available on the Fantom blockchain, however by using [multi-chain](https://multichain.xyz), Gravity SuSy, or other bridges, the holders of GTONs will be able to swap those into other blockchain networks, such as BSC, Ethereum, Heco, Waves, Avalanche, Tron, Polka or Solana. The holders will be able to freely choose what bridges to use for swapping, depending on their needs.

In the strict sense, Treasury deposits are not withdrawable. However, in case the holders of Graviton tokens vote to withdraw their deposits via governance, the withdrawal can be arranged.

The Treasury is primarily intended to serve as a source of initial liquidity for GTON and for its price discovery via forming an initial market cap. A key function of Treasury farming is to build an integral foundation for a sustainable financial architecture of Graviton in the future, revolving around providing initial liquidity for GTON.

The primary goal of Graviton is still the same: to create a mechanism that stimulates the development of cross-chain integrations at the level of digital assets, which is only possible with further advancement of the wrapped tokens’ concept. We think that cross-chain is not a buzzword, but a major technical debt of the industry that needs to be addressed in order to open this space for new synergetic trading, product, and investment strategies that involve users across as many integrated ecosystems as possible.

Farm source code: [https://github.com/Graviton-One/graviton-treasury/tree/develop](https://github.com/Graviton-One/graviton-treasury/tree/develop)
