# Graviton Governance Framework

![](https://miro.medium.com/max/1400/1\*YvAo9pqpy7aX0XWxb4XrpQ@2x.png)

## Two kinds of GTON balance: in application and in your wallet <a href="24b9" id="24b9"></a>

For simplicity, we separate token balances into two categories:

* Wallet Balance. This is the amount of liquid GTON token on a user’s account/crypto wallet. This GTON can be directly transferred between accounts and used on exchanges or other external DeFi services.
* Application Balance. This is GTON locked within the Graviton system and its smart contracts. In order to withdraw tokens from Application Balance to Wallet Balance, a user can call the _withdraw_ option. GTON can be withdrawn to all integrated blockchain networks. In order to add GTON into the system, you can do a _deposit_ in either of the subsystems of Graviton. The Application Balance also includes GTON allocations for EB, SPI, as well as all tokens allocated as a reward for LP mining or governance staking (which is necessary for voting). This balance can either be fully available for withdrawal or locked for a certain period (EB / SPI vested allocations).To establish a more fair governance process, the team’s allocation will not participate in voting unless this possibility is proposed and approved separately as a protocol update.

Your Application Balance represents the number of votes you have while participating in governance for accepting or rejecting token holders’ proposals.

## Protocol Governance vs Operational Governance <a href="db35" id="db35"></a>

We propose to distinguish between two types of project management that can happen through voting by token holders:

* Protocol Governance. This relates to managing treasury funds, updating the protocol’s inner logic, or integrating new functionality. The flow that initiates a consideration of such proposals begins with an initiative from either the community or the team. Subsequently, a specification/description of the proposal should be finalized and presented to the token holders, with the final adoption and implementation of changes executed through multisig voting.
* Operational Governance. This is represented by template proposals that can be initiated and voted on directly by any GTON token holder. The results of such voting are automatically introduced into the system without the need for a multisig approval. This type of voting is applicable only to the submission of projects for participation in the Catalyst program, the integration of new blockchain networks, or decentralized exchanges/bridges.

![](https://miro.medium.com/max/1400/1\*wOo7BfxCPagTA7mcEtVRQQ@2x.png)

This governance approach is rather flexible in use and it makes the protocol resistant to governance attacks, while remaining sufficiently agile in fine-tuning APYs and activating/reactivating LP farming programs for different projects.

For instance, to vote for a system parameter, the total allocation for all Catalyst programs could be 100 thousand GTONs per week for all programs. The adjustment of the total allocation can take place through Protocol Governance. If the community decides to apply initially to boost LP for a particular pool or reactivate one (for instance, LP-Pancake-FTM-BNB), its allocation for participation in Catalyst will be determined through staking of GTON in governance and voting for the project.
