Veles Core integration/staging repository
=====================================

[![Build Status](https://travis-ci.org/PIVX-Project/PIVX.svg?branch=master)](https://travis-ci.org/PIVX-Project/PIVX) [![GitHub version](https://badge.fury.io/gh/PIVX-Project%2FPIVX.svg)](https://badge.fury.io/gh/PIVX-Project%2FPIVX)

Veles is an open source crypto-currency focused on fast private transactions with low transaction fees & environmental footprint.  It utilizes a custom Proof of Stake protocol for securing its network and uses an innovative variable seesaw reward mechanism that dynamically balances 90% of its block reward size between masternodes and staking nodes and 10% dedicated for staking. 
- Anonymized transactions using Privatesend.
- Fast transactions featuring guaranteed zero confirmation transactions using SwiftNode.

More information at [veles.network](http://www.veles.network)

### Coin Specs
<table>
<tr><td>Algo</td><td>Quark</td></tr>
<tr><td>Block Time</td><td>60 Seconds</td></tr>
<tr><td>Difficulty Retargeting</td><td>Every Block</td></tr>
<tr><td>Max Coin Supply (PoS Phase, Pre Infinite)</td><td>12 500 000 VLS</td></tr>
<tr><td>Premine</td><td>375 000 VLS*</td></tr>
<tr><td>Block maturity</td><td>60 minutes</td></tr>
</table>

### PoW Rewards Breakdown

<table>
<th>Block Height</th><th>Masternodes</th><th>Miner</th>
<tr><td>2-200</td><td>90% (225 VLS)</td><td>10% (25 VLS)</td></tr>
</table>

### PoS Rewards Breakdown

<table>
<th>Phase</th><th>Block Height</th><th>Reward</th><th>Masternode</th><th>Staking</th>
<tr><td>Phase 1</td><td>1-25000</td><td>1 VLS</td>
<tr><td>Phase 2</td><td>50001-75000</td><td>16 VLS</td>
<tr><td>Phase 3</td><td>75001-250000</td><td>13 VLS</td>
<tr><td>Phase 4</td><td>250001-150000</td><td>6 VLS</td>
<tr><td>Phase 5</td><td>150001-200000</td><td>3 VLS</td>
</table>
