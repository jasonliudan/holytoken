# Holyheld 🙏

We are actively working on a mobile-first, DeFi-friendly financial services app. We are working on the service that will be the easiest way to trade, store, send, and earn interest on your crypto in a simple wallet with a debit card.

Our goal is to create the smoothest crypto trading on decentralized exchanges, as well cheapest fiat off/on-ramp with our experimental tokenomics. In the long term, we imagine a neobank that will take the best of both worlds, from traditional finance — existing infrastructure, and DeFi — best profit-maximizing strategies and convenient crypto trading exposure.

Stake and earn HOLY at the https://app.holyheld.com

## Pre-Launch Phase

The pre-launch phase is the launch of the HOLY token via a liquidity mining program. Early adopters will be able to mine the token while staking other DeFi LP tokens or by providing liquidity. At this stage, HOLY has no monetary value and is worthless. Please do not consider it as an investment opportunity. It focuses on creating strong HOLY liquidity, kickstarting Yield Treasury, and supporting early supporters.

Going further, when we will launch the app, HOLY will play a crucial role in the unique fees offering available in the app. The interest generated by staked assets will only be used for one purpose: to buyback HOLY used to pay for fiat off/on-ramp services, as well as trading fees. Generated interest will be stored in the Yield Treasury, operated by the team. Before the service launch, no accrued interest shall be used.

## Audits

None. Contributors have given their best efforts to ensure the security of these contracts, but make no guarantees. It is a probability - not just a possibility - that there are bugs. That said, minimal changes were made to the staking/distribution contracts that have seen hundreds of millions flow through them via SNX, YFI, and YFI derivatives. The [HolyKnight](https://github.com/Holyheld/holy-contracts/blob/master/contracts/HolyKnight.sol) contract logic is excessively simple as well. We prioritized staked assets' security first and foremost. If you feel uncomfortable with these disclosures, don't stake or hold HOLY.

## Post-Launch Phase

During the post-launch phase, all early token holders will be able to use their HOLY tokens to enjoy gas-free and fee-free banking service on the Holyheld app. Also, all accrued yield stored in the Yield Treasury during the initial phase will be used to buyback tokens and cover the fees for the users.

At this point, we will stop our liquidity mining program, and the only way to earn the remaining 70% or 56,000,000 HOLY will be through our trade-mining program for active trading and app usage. We will release more details as we get closer to the launch date, but the period of the trade-mining program will be a minimum of 3 years. It means that the annual inflation rate of the token will decrease by 3,432%.

## Distribution

There will only ever be 100,000,000 HOLY tokens. [Holy Token](https://github.com/Holyheld/holy-contracts/blob/master/contracts/HolyToken.sol) contract does not have mint function.

- 80% of the total supply or 80,000,000 HOLY will be reserved for liquidity mining during the pre-launch phase, and trade mining during the post-launch phase. We explain more about our distribution curve further in the article.

- 10% of the total supply or 10,000,000 HOLY will be reserved for the Holyheld current and future employees. This reserve will be vested at a 2% per week unlock rate with a 2-month delay. Meaning that the unlock period will only start in November 2020. Also, an additional KPI is set in the unlock contract. To have a weekly unlock, Holyheld has to achieve an ATH (All-time high) value of TVL (Total Value Locked) in the HOLY. Weekly snapshot is taken to compare the previous week ATH value of TVL and the current week. If the target is met — then tokens can be unlocked. If the target is not met — no tokens will be unlocked this week. A new attempt will be made the following week. This unique KPI feature is aligned with the long-term development of the service and ensures that the team is incentified to continue working for the benefit of Holyheld consumers.

- 10% of the total supply or 10,000,000 HOLY will be reserved for operational and marketing expenses. This reserve will also be vested at a 2% per week unlock rate. Supporting the transparency spirit of DeFi, we will announce all major operational costs in advance.

## Adjustion of the Rewards Distribution Weights
There has been an update on the rewards distribution weights according to the [latest community updates](https://medium.com/holyheld/first-community-updates-fc2ab74b638b)

## Stake yCRV tokens

Your first mining option will be staking [yCRV](https://uniswap.info/token/0xdf5e0e81dff6faf3a7e52ba697820c5e32d806a8) tokens. To get HOLY rewards, one will have to stake obtained yCRV tokens. This pool will generate 35% of available rewards or 8,400,000 HOLY. This option is launched because yUSD is the most credible stablecoin farming with very high APY. It’s also hard to farm, as one needs to have other stablecoins first. To generate interest, Holyheld will auto-stake yCRV  in the yCurve vault on Yearn Finance to obtain yyCRV LP tokens. Since all accumulated during the pre-launch phase yield will be used solely to buyback the tokens and facilitate service fees, the proposal suggests this pool having big rewards.

## Provide liquidity

Your second mining option will be by staking HOLY-ETH UNI-V2 LP tokens. To get HOLY rewards, one will have to provide liquidity to the Uniswap pool, and stake obtained LP tokens. This pool will generate 50% of available rewards or 12,000,000 HOLY. This is a community managed pool. For the rewards to start accruing, the community will have to farm enough HOLY first to create a liquidity pool on Uniswap. This option is launched to ensure the sustainable and smooth growth of the Holyheld ecosystem before and post product launch.

## Stake popular DeFi LP tokens

Your third mining option will be staking popular DeFi LP tokens. To facilitate fair distribution across the DeFi community, we will support the staking of major DeFi LP tokens. To be precise, our community will be able to stake the following LP tokens: [UNI-ETH](https://uniswap.info/pair/0xd3d2e2692501a5c9ca623199d38826e513033a17), [YFI-ETH](https://uniswap.info/pair/0x2fdbadf3c4d5a8666bc06645b8358ab803996e28), [LINK-ETH](https://uniswap.info/pair/0xa2107fa5b38d9bbd2c461d6edf11b11a50f6b974), [LEND-ETH](https://uniswap.info/pair/0xab3f9bf1d81ddb224a2014e98b238638824bcf20), [AMPL-ETH](https://uniswap.info/pair/0xc5be99a02c6857f9eac67bbce58df5572498f40c), [SNX-ETH](https://uniswap.info/pair/0x43ae24960e5534731fc831386c07755a2dc33d47), [COMP-ETH](https://uniswap.info/pair/0xcffdded873554f362ac02f8fb1f02e5ada10516f), and [MKR-ETH](https://uniswap.info/pair/0xc2adda861f89bbb333c90c492cb837741916a225). To get HOLY rewards, one will have to provide liquidity to the above-mentioned pools to get UNI-V2 LP tokens, and later stake obtained LP tokens. This option will generate accumulatively 15% of available rewards or 3,600,000 HOLY or 450,000 HOLY per pair.

## Deployed Contracts

[HolyToken](https://etherscan.io/token/0x39eae99e685906ff1c11a962a743440d0a1a6e09) - The Holyheld token

[HolyKnight](https://etherscan.io/address/0x5D33dE3E540b289f9340D059907ED648c9E7AaDD) - Holy Knight, contract to manage the LP staking

[HolderTVLLock](https://etherscan.io/address/0xe292dc1095b96809913bc00ff06d95fdffaae43a) - Holder contract for team tokens, vested weekly with TVL value all-time-high condition

[HolderTimelock](https://etherscan.io/address/0xfea2cc041fb9e1bd73b8deb6b79aa96c712383d9) - Holder contract to reserve tokens for trade mining after launch

[HolderVesting](https://etherscan.io/address/0x6074Aabb7eA337403DC9dfF4217fe7d533B5E459) - Holder contract for operations vested for 1 year.

## Attributions

Much of this codebase is modified from existing works, including:

[Compound](https://compound.finance) - Jumping off point for token code and governance

[Synthetix](https://synthetix.io) - Rewards staking contract

[YEarn](https://yearn.finance)/[YFI](https://ygov.finance) - Initial fair distribution implementation
