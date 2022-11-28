---
description: Users can earn protocol revenue via staking LPFi.
---

# LPFi Staking (Preferred Shares)

### Revenue Sharing

LPFi can be staked to earn protocol revenue. The protocol revenue would consist of&#x20;

* Collateral Deposit Fee
* PSM Swap Fee
* zSOL LP Deposit Fee
* Portion of zSOL Stability Fee
* zSOL Treasury Staking Revenue

Initially, solely the "Collateral Deposit Fee" would be collected, swapped to SOL, and distributed to LPFi staking pool.

Other revenue would be stored, and in the future, LP Finance DAO would decide how the revenue sharing should be structured.

### Unstaking Penalty

In order to prevent short-term holders from earning revenue and purely rewarding long-term holders, unstaking penalty exists.&#x20;

| Staked Period                      | Penalty |
| ---------------------------------- | ------- |
| staking period < 7 days            | 20%     |
| 7 days<= staking period < 14 days  | 10%     |
| 14 days<= staking period < 21 days | 5%      |
| 21 days<= staking period < 28 days | 2.5%    |
| 28 days <= staking period          | 0%      |

Unstaking penalty is burnt immediately when unstaked. For example, if you staked 100 LPFi but unstaked it in 2 days, you would be able to redeem 80 LPFi and 20 LPFi would be burnt.

After staking, if the user stakes or unstakes, the period is reset to 0 days.

This mechanism concentrates rewards on long-term holders, which would result in higher incentives.
