---
description: Users can earn protocol revenue via staking LPFi.
---

# LPFi Staking (Preferred Shares)

### Revenue Sharing

LPFi can be staked to earn protocol revenue. The protocol revenue would consist of&#x20;

* Collateral Deposit Fee
* PSM Swap Fee
* zSOL LP Deposit Fee
* 10% of zSOL Stability Fee
* zSOL Treasury Staking Revenue

Initially, revenue that compounds (PSM Swap Fee, zSOL Treasury Staking Revenue) would remain untouched to encourage growth.

Collateral deposit fee, zSOL LP deposit fee, and 10% of zSOL stability fee would be **redeemed every last day of the month** and provided to LPFi staking pool for a month. As the total reward amount differs monthly, estimated APR might be volatile.

20% of protocol revenue would be directed to **LP Finance Inc.** , a maintainer of LP Finance protocol.&#x20;

### Unstaking Fee

In order to prevent short-term holders from earning revenue and purely rewarding long-term holders, unstaking penalty exists.&#x20;

| Staked Period                     | Unstaking Fee |
| --------------------------------- | ------------- |
| staking period < 7 days           | 10%           |
| 7 days<= staking period < 14 days | 5%            |
| 14 days<= staking period          | 0%            |

Unstaking penalty is burnt immediately when unstaked. For example, if you staked 100 LPFi but unstaked it in 2 days, you would be able to redeem 90 LPFi and 10 LPFi would be burnt.

After staking, if the user stakes or unstakes, the period is reset to 0 days.

This mechanism concentrates rewards on long-term holders, which would result in higher incentives.
