# Interchain Treasury Farming Architecture

_Graviton governance is set in motion through treasury farming, a novel DAO concept that revolves around self-financing of decentralized development and issuance of a governance token. This page briefly describes the mechanics of farming as it unfolds in the Treasury of the Graviton project._ 

At its core, Graviton treasury uses Ethereum as a primary blockchain, with a range of 14 preselected liquid USD-pegged [stablecoins](https://debank.com/ranking/stablecoin). Treasury backers can deposit a stablecoin into the treasury by transferring it to a multisig contract based on [Gnosis Safe](https://gnosis-safe.io/). As soon as the event of the deposit happens, it is registered by the oracles of [the Gravity network](https://gravity.tech/) and transmitted to the farm smart contract on the [Fantom blockchain](https://fantom.foundation/). 

In the smart contract system on the Fantom network, the addresses of backers from Ethereum are mapped and their current “impact” is recorded in the Treasury. For each blockchain time interval, a share of newly mined Graviton tokens \($GTON\) is being proportionally distributed among the backers. The total supply of GTON is capped at 21 million tokens. The additional parameters that influence GTON distribution can be decided by voting of consuls: the delegates who have been vested with governance power by the holders of GTON, according to the principles of liquid democracy.

The original GTONs will first become available on the Fantom blockchain, however by using [multi-chain](https://multichain.xyz/), Gravity SuSy, or other bridges, the holders of GTONs will be able to swap those into other blockchain networks, such as BSC, Ethereum, Heco, Waves, Avalanche, Tron, Polka or Solana. The holders will be able to freely choose what bridges to use for swapping, depending on their needs.

As a simple example, we present the emission cycle of farming with two users:

![](https://lh3.googleusercontent.com/RxreU8jH3_MADp6A_QUQln1ur8uZBmshBweT9id9LOP2FF3SMfrZy0Kha2bLIPaf91NzKS1sqSzvOepCVqZvuIYtdqpq2lOQByV-sWK4SCC4I_SeoPiV7QBZDnu2qqhjE4hRZA74)

At any time, the existing backers can add more to their treasury balance, thus increasing their current share and diluting the share of future farming rewards paid out to the upcoming users. The smart contract takes into account any changes in the balances, and recalculates the distribution proportions for the minted tokens accordingly. It is worth noting that after the early bird period, the shares of early backers from farming are no longer diluted and remain fixed even with the influx of new backers. 

In the strict sense, Treasury deposits are not withdrawable. However, in case the holders of Graviton tokens vote to withdraw their deposits via governance, the withdrawal can be arranged.

The Treasury is intended to serve as a long-term source of financing for the project, its developers, token liquidity, or other project-related purposes where financial costs are unavoidable. In addition to providing seed-stage funding for the project while distributing governance tokens among the most active and involved community members, a key function of Treasury farming is to build an integral foundation for a sustainable financial architecture of Graviton in the future, revolving around providing initial liquidity for GTON.

![](https://lh6.googleusercontent.com/999r39jGp7RvLLE1494ZnOR3kkmSRFAeFaDzJ4LUJ8Cp4VCkhuHiY5lV4-j06zo8vTcxmsFg-AW7ENBVAkr4jMKR0IYMPulCcZKLVhh7ILFIPQcu_E99NusxiKO9hC6yzytaUsgL)

The primary goal of Graviton is still the same: to create a mechanism that stimulates the development of cross-chain integrations at the level of digital assets, which is only possible with further advancement of the wrapped tokens’ concept. We think that cross-chain is not a buzzword, but a major technical debt of the industry that needs to be addressed in order to open this space for new synergetic trading, product, and investment strategies that involve users across as many integrated ecosystems as possible.

Farm source code: [https://github.com/Graviton-One/graviton-treasury/tree/develop](https://github.com/Graviton-One/graviton-treasury/tree/develop)

