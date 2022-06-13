# Summary
* Owner: Tej
* Week 37: 05/30-06/03
* Total: 41 hours
* Overtime: 0 hours

# Time Table
| date  | start time  | end time | duration  |  note |
|---|---|---|---|---|
| 05/30  | 11:00  | 19:00  | 8 | Had a discussion on Vault staker functionality and other unit tests failing on the repo to be fixed. Implemented the function to calculate the vault and staker's current reward to be claimed. This can be also used for frontend side to display the current claimable reward amount. |
| 05/31  | 10:00  | 19:00  | 9 | Worked on the collateral calculation for vault stakers. The current mechanism doesn't support the vault staker's colalteral, only supports the vault collateral. It will prevent for vault staker to withdraw his collateral from the expired vault. |
| 06/01  | 09:00  | 18:00  | 9 | Worked on the solution to resolve the vault staker's collatersl withdrawal issue. |
| 06/02  | 10:00  | 18:00  | 8 | Updated the ICollateral contract to resolve the staker's collateral withdrawl issue. The staker's collateral to be withdrew is checked when withdrawing it through getValutStakerBalance function that returns the current staker's collateral balance of the vault. |
| 06/03  | 11:00  | 18:00  | 7 | Implemetned releaseStakerCollateral function on IColletarl contract, which transfers the staker's collateral to staker if the staked vault was expired. |
