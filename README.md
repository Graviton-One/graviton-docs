# Introduction to Graviton

![](https://miro.medium.com/max/6400/1*elIGyZ2JhOOfvYeEh-Gstw.png)

_**NB: The GTON token on ETH has been launched. This is the only correct GTON token: 0x01e0e2e61f554ecaaec0cc933e739ad90f24a86d \(**_[_**https://etherscan.io/address/0x01e0e2e61f554ecaaec0cc933e739ad90f24a86d**_](https://etherscan.io/address/0x01e0e2e61f554ecaaec0cc933e739ad90f24a86d)_**\) Please beware of copycat/scam tokens.**_

_VentuaryLab presents a novel inter-chain concept that combines a liquidity incentivization system for wrapped tokens with a bridge aggregator as part of its infrastructure._

## Intro & issues of the DeFi Space <a id="b286"></a>

For the last three years, we at VentuaryLab have been observing the evolving Web3 space and developing DeFi products, uncovering major constraints that hinder the truly borderless inDeFi experience and liquidity growth.

Two years ago, VentuaryLab stood at the origins of USD Neutrino, or [USDN](https://coinmarketcap.com/ru/currencies/neutrino-usd/) \(currently owned and managed by Waves.Exchange\), the first stablecoin on Waves. The experience of expanding Waves tokens beyond their native ecosystem involved researching other networks in an effort to establish liquidity and traction there. Apart from tech-layer obstacles connected with the necessity to provide a decentralised way of porting a Waves-based token onto other networks, the inter-chain growth of tokens had been restrained by the unwillingness of the new communities to acknowledge new products and give them endorsement and initial liquidity.

It so happens that in the DeFi space of today, most opportunity lies with Ethereum. It provides a vast range of DeFi solutions and has ample liquidity, albeit hindered by exorbitant gas fees and frequent network congestion. However, in recent months many alternative blockchain networks and ecosystems have shown remarkable progress and growth, offering comparable or even superior services but significantly more affordable in terms of transaction costs. It became obvious that DeFi is not limited to Ethereum, which only preserves the dominance in this space by inertia. Nevertheless, the shift to alternative networks is hampered by complicated, multi-step user experience and insufficient liquidity of tokens wrapped in blockchains other than Ethereum, which is one of the key factors influencing the prosperity of  inter-chain DeFi.

During the past year, VentuaryLab has been focused on in-depth R&D in the field of inter-chain communication. We have developed [Gravity](http://gravity.tech), a leading-edge technology that establishes a solid foundation for multi-purpose inter-chain applications and gateways, such as [SuSy](https://susy.gravity.tech/). One of the potential applications of such technologies is to simplify for the regular users of Ethereum the process of interaction with DeFi services in other chains, while allowing them to remain within the comfort of their existing accounts and tools they’re accustomed to. Using our open-source developments, you can gain unhindered access to inter-chain DeFi, or just test and see whether a certain blockchain ecosystem is in line with your individual use case without having to buy native tokens on CEXes or install new wallets.

This past years’ experience contributed to the discovery of the most pressing DeFi industry problems and ways of solving them.

The first issue is, non-surprisingly, the fragmentation of DeFi communities. Due to the divided nature of the DeFi industry, projects and services are largely isolated within their ecosystems. This means that gaining traction and becoming noticeable outside the boundaries of the native ecosystem requires substantial, focused efforts on behalf of the project’s initiators.

Thus, we are confident that a tool that would allow to kickstart tokenized projects in other networks could be beneficial for the entire industry.

The second issue is the lack of cross-chain technological connectedness and seamlessness, which becomes especially apparent when a newly wrapped token needs to gain traction and liquidity in a destination chain.

## Graviton as a solution that opens new horizons <a id="50f8"></a>

Graviton aspires to be a universal wrapped tokens’ liquidity incentivization solution that aims to aggregate multiple cross-chain bridges, provide seamless access to a diverse range of blockchains via Ethereum mirror accounts, and create a reward-based economy around wrapped assets.

Graviton's end goal is to unite the communities of different blockchain projects: e.g. chains, AMMs, farms, tokens; and provide them with governance tools for boosting liquidity and increasing yield generation for their favorite wrapped digital asset on a destination chain.

## Under the hood <a id="fed8"></a>

Graviton consists of:

* The MegaBridge — a cross chain bridge aggregator that combines bridges such as multichain.xyz \(evm &lt;-&gt; evm\), ren \(btc/doge &lt;-&gt; evm\), gravity \(solana/waves/polka &lt;-&gt; evm\) and others
* LP incentivization solution that creates a reward-based economy around wrapped assets \(see Catalyst\)
* "Mirror accounts" for Ethereum-account owners to let them effortlessly access a wide range of alternative chains

The Graviton system, which will serve as an aggregator of multiple bridge solutions, would allow for the expansion of the concept of wrapped tokens, ultimately being another important step in achieving full inter-chain composability.

## Reward-based economy around wrapped tokens <a id="b7b1"></a>

Incentives are what the Graviton system is driven by. Reward-based economy around LP rewards farmed elsewhere is powered by [GTON](https://etherscan.io/address/0x01e0e2e61f554ecaaec0cc933e739ad90f24a86d), Graviton’s governance token. [GTON](https://etherscan.io/address/0x01e0e2e61f554ecaaec0cc933e739ad90f24a86d) has straightforward utility:

* Selecting LP tokens from pools with wrapped tokens to be included in the incentivisation programs \(Catalyst & Boost\), with the aim of increasing the liquidity and TVL of your favorite project
* As payment for fees to execute different operations within Graviton for instance wrapping or unwrapping tokens
* Token buyback via fees collected from trades and its redistribution among stakers
* Governance tool to influence Graviton updates, new products and parameters, and operational management

## Tokenomics <a id="bd37"></a>

The total supply of [GTON](https://etherscan.io/address/0x01e0e2e61f554ecaaec0cc933e739ad90f24a86d) is capped at 21 million tokens. Its unlocking occurs according to a slowly decaying, deflationary model. The original GTONs will first become claimable on the Fantom blockchain, however by using [multichain](https://multichain.xyz/).xyz, Gravity SuSy, RenVM or other bridges, the holders of GTONs will be able to swap their claimed GTONs into other blockchain networks, such as BSC, Ethereum, Heco, Waves, Avalanche, Tron, Polka or Solana.

## Treasury <a id="f3f9"></a>

Treasury is a multisig contract controlled by the team and the first supporters of Graviton, selected among the top players of the DeFi space. Treasury stores all the undistributed [GTON](https://etherscan.io/address/0x01e0e2e61f554ecaaec0cc933e739ad90f24a86d) allocations, LP-GTON tokens and stablecoins deposited during the Early Birds period to provide initial liquidity for GTON. In the strict sense, Treasury deposits are not withdrawable. However, in case the holders of Graviton tokens vote to withdraw their deposits via governance, the withdrawal can be arranged.

The deposit option is available for the initial supporters of Graviton willing to provide initial liquidity for the [GTON](https://etherscan.io/address/0x01e0e2e61f554ecaaec0cc933e739ad90f24a86d) token and enable its price discovery — early backers, or early birds. In order to achieve sustainable growth, the team is planning to seek contributions by strategic partners and investors later, when the token has a price and a market cap.

Treasury serves as a [GTON](https://etherscan.io/address/0x01e0e2e61f554ecaaec0cc933e739ad90f24a86d) collateral and allows for price discovery prior to the start of the token emission. It is also aimed to provide AMM initial liquidity at the IDO stage which starts right after the early-bird deposit period.

## Allocations <a id="dfa2"></a>

The [GTON](https://etherscan.io/address/0x01e0e2e61f554ecaaec0cc933e739ad90f24a86d) allocation lineup includes several roles which are assigned with particular shares of [GTON](https://etherscan.io/address/0x01e0e2e61f554ecaaec0cc933e739ad90f24a86d) total supply. They are indicated in the table below:

![](https://miro.medium.com/max/3200/0*aGVZDAt0cBHlmlq2)

For all the roles within Graviton, there will be token vesting according to the schedule.

![](https://miro.medium.com/max/3200/0*Cw4tWnNtcBy-gg1O)

**Early birds** will receive tokens right after the end of EB via daily tranches, according to a decaying unlocking formula: 1st week: 5%, 1st year: 75%, etc

**Core contributors** — those who are involved with the project development e.g. project founder, developers, multisig signers, as well as investment, technical, and legal advisors, will also have vesting identical to EB formula, which starts in three months after the end of EB.

In addition, there are allocations for LP, Backers, and Operations. **LPs** are allocations for incentivization of wrapped tokens via reward programs such as Catalyst & Boost. **Ops** — these are infrastructure investments \(oracles/bridges\), airdrops, bug bounties, audits and ambassadors. **Backers** is a special allocation for single sided IDOs and [GTON](https://etherscan.io/address/0x01e0e2e61f554ecaaec0cc933e739ad90f24a86d) initial liquidity for IDOs.

All of those allocations are locked in the Treasury indefinitely and will be unlocked in small portions for growth and engagement purposes identified by team, governance and multisig.

## EB <a id="fafa"></a>

To work as an incentivization instrument, the token should have liquidity, volumes, and attractiveness for traders from the beginning.

Early birds, also dubbed as early backers, are the early supporters of the Graviton system participating in accumulation of the initial liquidity in stablecoins as a financial foundation for [GTON](https://etherscan.io/address/0x01e0e2e61f554ecaaec0cc933e739ad90f24a86d) tokenomics.

* Early-bird period lasts for 2 weeks before the launch
* Allocation — 10%
* Liquidity is supplied to the Treasury contract based on Gnosis Safe Multisig

At the end of the EB stage, the initial capitalisation is established and a starting price is determined via a price discovery approach before the token is listed on DEX AMMs. Thus, [GTON](https://etherscan.io/address/0x01e0e2e61f554ecaaec0cc933e739ad90f24a86d) token will instantly gain liquidity volume and attractiveness for traders.

At its core, Graviton treasury uses Ethereum as a primary blockchain, with a range of 8 preselected liquid USD-pegged stablecoins. Treasury early backers \(or, as we call them, early birds\) can deposit a stablecoin into the treasury by transferring it to a multisig contract based on Gnosis Safe. As soon as the event of the deposit happens, it is registered by the oracles of the Gravity network and transmitted to the farm smart contract on the Fantom blockchain.

In the smart contract system on the Fantom network, the addresses of early backers from Ethereum are mapped and their current “impact” is recorded in the Treasury. For each blockchain time interval, a new share of Graviton tokens \($GTON\) is being unlocked and proportionally distributed among the early backers. At the end of the early-bird period, the impact of each early-bird contributor is calculated, which is proportional to the amount of deposited stablecoins.

Impacts represent the contributors’ shares of the early-bird allocation, i.e. how many GTONs will be allocated to them.

* Let’s say Treasury contains _$2 mln_ in stablecoins.
* A contributor’s deposit is _$100к._
* The contributor receives _\($100k/$2mln\)\*2.1mln GTON = 105k GTON._

## Early backers vs LPs <a id="3c50"></a>

What are the advantages of being EB versus a regular liquidity provider?

Early birds determine the initial [GTON](https://etherscan.io/address/0x01e0e2e61f554ecaaec0cc933e739ad90f24a86d) price and its capitalization. Being directly involved with the price discovery process, they receive the most optimal price offer for GTON. EBs can access the best conditions with the highest upside potential. Moreover, EBs receive a guaranteed and undiluted amount of [GTON](https://etherscan.io/address/0x01e0e2e61f554ecaaec0cc933e739ad90f24a86d) throughout the whole unlocking period.

In contrast, being an LP provider implies participation in the constantly launching time-limited Catalyst programs. Graviton is not a classical farm, there are no popular pairs like ETH/USDT, BNB/BUSD as on other farms. Instead, Graviton focuses on the emerging and growing projects and their tokens, currently having liquidity only on one chain, such as Ethereum, Solana, BSC, Waves, or Fantom. Liquidity incentivization programs are limited in time \(1–2 weeks\) and aimed primarily at the initial bootstrapping of a project in its non-native chains, rather than a long-term farming solution with a free token distribution.

Therefore, LP farming on Graviton should not be considered a long-term passive income source. The approach of temporary liquidity boosting campaigns requires agile management of funds and monitoring of the market situation to shift between AMMs for LP when the time is right. On the contrary, while contributing to the Treasury as EB, the generated yield can be deemed a long-term return on a deposit.

## SPI <a id="5d74"></a>

SPI is a token allocation assigned for Strategic Partners & Investors. This category can involve:

* Blockchain ecosystems: Fantom, Waves, Binance Smart Chain, Ethereum, Solana, Polygon, Avalanche, Polkadot, Heco etc.
* VC and labs of CEXes
* VCs with inhouse market making teams
* VCs seeking opportunities to increase the liquidity of their supported projects \(via Catalyst program\)
* Blockchain protocols, ecosystems, AMMs, farms and other projects which join us in our goal to ensure liquidity of all tokens in various ecosystems and create user-friendly cross-chain experience

All SPI deals will be announced and made after the early-bird period is completed. For such kind of investment deals, having a market cap evaluation is crucial, which will be established after the conclusion of the early-bird period and the beginning of the [GTON](https://etherscan.io/address/0x01e0e2e61f554ecaaec0cc933e739ad90f24a86d) circulation. SPIs have the same vesting period and the unlocking occurs by the same formula as for early birds, starting in two weeks after the deal is closed. SPI deals can be made within one or several years since the start of Graviton.

## Catalyst & Boost <a id="9f25"></a>

Graviton Catalyst is a platform that offers primary incentives and sustainable support for **wrapped tokens’ liquidity provision.** Graviton Catalyst can help a variety of tokenized blockchain projects, such as protocols, AMMs and farms, to expand onto non-native networks incorporated into Graviton by incentivizing liquidity and drawing communities’ attention across ecosystems. The communities of participating projects are invited to get involved in short-term and middle-term programs that incentivize bootstrapping of liquidity for recently emerged wrapped tokens by providing extra LP rewards. Those who enter the pools as LPs, Graviton rewards with GTON.

The Catalyst programs are limited in time by **two to three weeks,** and reweighting of the LP rewards’ allocation points occurs every week. For rewarding liquidity providers under the Catalyst program, **12%** of the total [GTON](https://etherscan.io/address/0x01e0e2e61f554ecaaec0cc933e739ad90f24a86d) supply is allocated. Members of a community can stake their [GTON](https://etherscan.io/address/0x01e0e2e61f554ecaaec0cc933e739ad90f24a86d) into governance to nominate their favorite project for participation in the Graviton Catalyst program and increase the staking yield of its LP tokens.

Once a project finishes participating in the Catalyst program, the incentivization for a particular LP token can be reinstated through the Graviton **Boost program,** in case of continued interest on behalf of the community.

![](https://miro.medium.com/max/3200/0*H0bCGO32_SAnRDhp)

Leveraging the already established integrations with AMMs, bridge solutions, and blockchain networks, Graviton will evolve organically through inbound integrations and partnerships. Establishing SPI deals with large ecosystem players will help in boosting liquidity and onboarding new projects to Catalyst. Due to its blockchain- and bridge-agnostic approach, Graviton aims to become a universal hub for inter-chain liquidity and activity.

