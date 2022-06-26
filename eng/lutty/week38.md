# Summary

* Owner: lutty
* Week 38: 04/17-04/23
* Total: 30 hours
* Overtime: 0 hours

# Time Table

| date | start time | end time | duration | note                                                                                                                                  |
|------|------------|----------|----------|---------------------------------------------------------------------------------------------------------------------------------------|
| 4/17 | 16:00      | 18:30    | 2.5      | try using aws memorydb to replace redis cluster                                                                                       |
| 4/17 | 20:00      | 23:30    | 3.5      | benchmark aws memorydb, the test result is that the performance is seriously lower than expected                                      |
| 4/18 | 10:00      | 12:00    | 2        | try switch test aws elasticache, decide shard 1 switch to elasticache replace redis cluster                                           |
| 4/18 | 14:00      | 16:00    | 2        | sync shard1 statedb to elasticache                                                                                                    |
| 4/18 | 14:00      | 18:00    | 4        | research how to disable shard0 related logic in shard1                                                                                |
| 4/19 | 11:00      | 15:00    | 3        | sync shard 1 data from leveldb to tikv                                                                                                |
| 4/19 | 15:00      | 16:00    | 1        | sync shard 1 statedb from tikv to elasticache                                                                                         |
| 4/20 | 10:00      | 16:00    | 5        | write and test to disable shard0 sync on shard 1                                                                                      |
| 4/21 | 00:00      | 01:00    | 1        | fix bug: reader can get master lock on shard 0                                                                                        |
| 4/23 | 16:00      | 19:00    | 3.0      | RPC testing on Shard1 of new explorer cluster. [LOG](https://docs.google.com/document/d/16gwflnqIjAkaPNCqqmSH6VHVWWNKFkAhS69l1mLLA9s) |
| 4/23 | 21:00      | 24:00    | 3.0      | fix bug: some api bug on rpc test                                                                                                     |