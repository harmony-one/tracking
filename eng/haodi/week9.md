# Summary
* Owner: haodi
* Week 5: 09/27-10/03
* Total: 7.5 hours
* Status: Unpaid

# Time Table
| date  | start time  | end time | duration  |  note |
|---|---|---|---|---|
| 09/27 | 16:00 | 17:00 | 1.0 | completed the expansion of the explorer nodes disk and data migration of DO shard1-3, and checked the RPC interface after the expansion |
| 09/28 | 21:00 | 22:30 | 1.5 | bruno requires the creation of three new spaces in the gov app: Harmony Creative DAO, Harmony Developer DAO, and Harmony Incubator DAO. The voting rules are the same as Harmony Community DAO. The code was adapted to support the voting rules of the new space, and the relevant configuration of the new space was added in the background. After completing the adaptation, the voting test was carried out and launched |
| 10/01 | 12:30 | 17:30 | 5.0 | the harmony gov dapp received user feedback that it could not open the voting result page. After investigation, it was found that the interface for obtaining the number of stuck ONEs returned a 414 status code. After the query, it was found that the address was too long because of the too many parameters of the GET request and was rejected by the backend server. Need to be changed to a POST request. Since snapshot.js only supports GET to initiate interface calls, you need to fork the warehouse to implement the POST function by yourself. After the completion of the development work, the test was carried out, and the launch was completed after the multi-scenario test was passed |