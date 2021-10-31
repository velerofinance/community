---
title: Add $ilk to Liquidations 2.0 Framework - $date_MONTH_DD,_YYYY
summary: This poll proposes system parameters which could be used to initialize $ilk with the Liquidations 2.0 Framework.
discussion_link: $risk_link
vote_type: Plurality Voting
categories:
   - Auctions
   - Risk Variable
options:
   0: Abstain
   1: Yes
   2: No
start_date: $YYYY-MM-DDT16:00:00
end_date: $YYYY-MM-DDT16:00:00
---
# Poll: Add $ilk to Liquidations 2.0 Framework - $date_MONTH_DD,_YYYY

The Governance Facilitators have placed a Governance Poll into the voting system on behalf of the VeleroDAO mandated actors. This Governance Poll will be active for three days beginning on $date_DAY,_MONTH_DD at 16:00 UTC.

**This is a binary vote.**
- **You may vote for a single option.**
- **You should vote for the option which you prefer.**
- **If you would accept either option, you should vote 'Abstain'.**

## Review

This poll allows the VeleroDAO governance community to signal their support or opposition to adding $ilk to the Liquidations 2.0 Framework in the Velero Protocol with the parameters below:

**Auction Price**
* Auction Price Function (`calc`): $auction_price_function
   * Price Change Multiplier (`cut`): $price_change_multiplier
   * Price Change Interval (`step`): $price_change_interval
* Auction Price Multiplier (`buf`): $auction_price_multiplier

**Limits**
* Local Liquidation Limit (`ilk.hole`): $local_liquidation_limit
* Maximum Auction Drawdown (`cusp`): $maximum_auction_drawdown
* Maximum Auction Duration (`tail`): $maximum_auction_duration
* Breaker Price Tolerance (`tolerance`): $breaker_price_tolerance

**Incentives**
* Proportional Kick Incentive (`chip`): $proportional_kick_incentive
* Flat Kick Incentive (`tip`): $flat_kick_incentive

---

Please review the following [Risk Evaluation]($risk_link) containing information about $ilk to inform your position before voting.

## Outcomes

**If the votes for the 'Yes' option exceed the votes for the 'No' option, then the following actions will be taken:**
* $ilk will be added to the Liquidations 2.0 System by a future executive vote as the Protocol Engineering Core Unit's schedule allows.
* It is expected that this executive vote will take place within 30 days of this poll passing, absent external factors.
* If the executive vote passes, then these changes will become active in the Velero Protocol after the GSM Pause Delay has expired.

**If the votes for the 'No' option equal or exceed the votes for the 'Yes' option, then no further action will be taken at this time.**

---
