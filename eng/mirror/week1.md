# Summary
* Owner: Mirror Mirage
* Week 1: 08/01-08/08
* Total: 10 hours

# Time Table
| date  | start time  | end time | duration  |  note |
|---|---|---|---|---|
| 08/02  | 10:00  | 11:00  | 1  | Added Architecture diagram (Requested by Soph) . https://github.com/harmony-one/architecture-drawing/pull/4  & 5. Working with Soph to resolve github issue.  |
| 08/06  | 12:00  | 16:00  | 4  | Added Jenkins Build config for Testnet
https://github.com/harmony-one/jenkins/pull/62   & 63.

Tested SSR (Stop start restart)
1) indexertoken https://jenkins.harmony.one/job/explorer-v2-backend-ssr/19/console  
2) indexers https://jenkins.harmony.one/job/explorer-v2-backend-ssr/20/console  
3) apis https://jenkins.harmony.one/job/explorer-v2-backend-ssr/21/console  

Tested Jenkins BE Install
1) indexertoken https://jenkins.harmony.one/job/explorer-v2-backend-update/51/console  
2) indexers https://jenkins.harmony.one/job/explorer-v2-backend-update/52/console  
3) apis https://jenkins.harmony.one/job/explorer-v2-backend-update/53/console  

Created Jenkins API using my account, was able to trigger job build through curl commandline. https://jenkins.harmony.one/job/explorer-v2-backend-ssr/24/console 
Next step is configure uptimebot to call jenkins restart job. But for that, need a lower privilege user to be created for security sake.Discussed with Soph. Will be confirmed by next week after discussing with Leo. 

Summary of status - 
1) Jenkins jobs are tested for explorer V2 stop/start/restart/install and tested. 
2) Re-enabled cron job monitoring for now. Once Low priv user is created + API configured, will enable uptimerobot->Jenkins and disable cron  |
| 08/07  | 13:00  | 16:00  | 3  |  Testing of Aggregated Block Rewarding. Setup new node + created validator + Testing of whether validator earns rewards only at 64th blocks. Tested 3 scenarios for validator rewards , reported issues https://github.com/harmony-one/harmony/issues/3840#issuecomment-894698112 . Tested 2 scenarios for delegator rewards https://github.com/harmony-one/harmony/issues/3840#issuecomment-894710203  |
| 08/08  | 16:00  | 18:00  |  2 |  Continued testing for Agg block rewards. Conducted a training session for P-OPS to explain Explorer V2 component setup of testnet + jenkins + netlify. updated internal doc  |
