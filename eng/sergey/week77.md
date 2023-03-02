# Summary
* Owner: Sergey

# deliverables
| date  | deliverables |
|--- | ---|
| 02/06  | Working on .1.country - added twitter widget, added redirect for a search block, updated dependencies and removed webpack warnings which clogged application logs |
| 02/07  | Working on .1.country - v1.2 added new search page |
| 02/08  | Working on 1.country main page - several layout widgets and improve validation, Also working on the Open Widget Page - issue: User (as guest) can create and delete twitter widget (tweets stores on a backend) |
| 02/09  | Working on 1.country Fixing 1.county layout, Testing [Cross Shard bridge](https://cxone.harmony.one/)

**Refactoring**
The main goal, isolate a data layer from ui layer, make code easier to read, and modularity

D1DC client initialization - all logic by client migrated to Root Store
Domain Record Store - contains all logic by working with domain record, initial load, d1 dc1 params, validation and other
Wallet Store - contains all logic by working with user wallet, settings, connection, status and other
Added separate HomeSearchPage |
| 02/10  | Investigate how to integrate live stream app to .1.country: nginx or module federation |