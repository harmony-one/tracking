# Summary
* Owner: Mirror
* Week 3: 08/30-08/30
* Total: 10 hours
* Overtime: 2 hours

# Time Table
| date  | start time  | end time | duration  |  note |
|---|---|---|---|---|
| 08/24  | 13:00  | 16:00  | 3  | Request from Jenya for http API of Explorer V2. Setup different . HTTP API https://h.api.explorer.pops.one - points to port 3000 Test URL https://h.api.explorer.pops.one/v0/shard/0/block/number/0 WS API (Current , used by frontend)https://api.explorer.pops.one - points to port 3001. added the extra h.api url to avoid interruption to testnet services/dev hackathon. Can clean-up later if required. https://github.com/pops-one/explorer-v2-devops/pull/3 |
| 08/25  | 13:00  | 16:00  | 3  | Continued to work on popsnet new config. Setup new webtropia machines + build process for quick deploy + pm2 for quick process management. Tried a few different configs - pangaea/testnet  |
| 08/26  | 13:00  | 16:00  | 3  | POPSNET. Got help from Soph to understand the epoch configs. Updated the config. Was able to propose Block 1. But not able to confirm (BLS errors due to Modulo 2 (2 shard)). Fixed. Able to propose blocks, but not able to finalize. https://gist.github.com/mirrormirage0/49e8e3543858327f38710128ac5f2067. Need to debug further. Reported on discord for help. Bootnode connecting to too many nodes https://gist.github.com/mirrormirage0/91e32537c04fe5a639926913b30c48e2 .   |
| 08/27  | 13:00  | 16:00  | 3  | As per request from RJ+Soph, redirected s0.b.hmny.io traffic to s0.pops.one (NVME box). Tested end-points. contract deployment + transactions. Monitored the traffic. Notified developers on discord + telegram. Configured a backup endpoint for indexers/heavy load. Updated harmony docs - use s0.b.hmny.io for developers, use https://api.s0.backup1.b.hmny.io for indexers. https://discord.com/channels/532383335348043777/743472509231562885/880751500144553994  |

Week 4 Aug - Total hrs: 12
