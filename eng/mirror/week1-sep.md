# Summary
* Owner: Mirror
* Week 1 of Sep: 08/31-09/05
* Total: 2 hours
* Overtime: 0 hours

# Time Table
| date  | start time  | end time | duration  |  note |
|---|---|---|---|---|
| 03/09 | 18:00 |  20:00 | 2  | PagerDuty alert #14419 . Testnet Node S23 is not accessible via SSH. Connectivity dropped to 64%. Ping response is fine. Was able to SSH in after reboot. Verified node is in sync. Second alert #14420 - Beacon node out of sync. Beacon chain is stuck at Block 14449442.  number of peer nodes connected is very low. did a speed-test to measure network. Speed is fine. Tried restarting node. Didnt work. Took a backup of beacon db from s24. Copied to S23 and restarted. BeaconDB caught up. verified with hmy and watchdog.  Connectivity is back up to 81%. Additionally, s23 has an outdated version of the binary. v7141, all other nodes are on v7158. updated https://harmonyone.pagerduty.com/incidents/PV8H7N3 . Fixed port 9500 on s0nvme (watchdog error) | 

Week 1 of Sep - Total hrs: 2
