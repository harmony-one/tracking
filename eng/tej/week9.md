# Summary
* Owner: Tej
* Week 9: 11/15-11/19
* Total: 39 hours
* Overtime: 0 hours

# Time Table
| date  | start time  | end time | duration  |  note |
|---|---|---|---|---|
| 11/15  | 11:00  | 18:00  | 7  | Worked on deployment script issue investigation. |
| 11/16  | 10:00  | 18:00  | 8  | Found the reason of the deployment script issue. Reentrancy guard I added for the security causes the initialize function issue. Working on it. |
| 11/17  | 10:00  | 18:00  | 8  | Working on deployment script issue. Finding the solution. |
| 11/18  | 11:00  | 19:00  | 8  | Working on the same issue. Tried to implement the reentrancy guard without the openzeppelin libray but it doesn't work. |
| 11/19  | 10:00  | 18:00  | 8  | Found out the issue on deployment script. The reason is the contract size. The contract size is 24k+. Need to make the big update regarding the contract architecture to reduce its size.  |