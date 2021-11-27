# Summary
* Owner: haodi
* Week 10: 10/11-10/17
* Total: 7.5 hours
* Status: Paid

# Time Table
| date  | start time  | end time | duration  |  note |
|---|---|---|---|---|
| 10/11 | 19:00 | 21:30 | 4.5 | the snapshot node of Shard1-3 has an insufficient disk alarm. Since the node is built on AWS LightSail, the disk cannot be directly expanded, and the instance specifications need to be upgraded. After evaluation, it was found that the current configuration CPU and memory utilization rate is low. If you upgrade the specifications in order to expand the disk capacity, additional costs will be incurred. Therefore, I tried to use external disks and data migration solutions, retaining the original instance specifications but achieving disk expansion. Since the instance needs to be reconfigured and data is migrated, it takes a lot of time |
| 10/13 | 08:00 | 09:00 | 1.0 | handle PagerDuty alarms, expand the disks of 2 mainnet nodes, and observe and test its subsequent stability |
| 10/16 | 01:00 | 02:00 | 1.0 | handle PagerDuty alarms, expand the disks of 2 mainnet nodes, and observe and test its subsequent stability |
| 10/16 | 03:00 | 04:00 | 1.0 | assist giv to check the branch of the governments dapp, update configuration, will use the main branch as the production environment, and the original branch as the test environment then |