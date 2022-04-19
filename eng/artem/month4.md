# Summary
* Owner: Artem

# deliverables
| date     | deliverables                                                                                                                               |
|----------|--------------------------------------------------------------------------------------------------------------------------------------------|
| 19.04.22 | WIP: Adding Prometheus metrics to explorer backend api, testing metrics                                                                    |
| 18.04.22 | Added limit and offset params to GET /holders endpoint (explorer backend PR#40); Added filter by block_number for internal transactions;   |
| 15.04.22 | Support: created workaround for issue with Community DAO Gnosis Safe account                                                               |
| 14.04.22 | Support: debugging issue with Gnosis Safe creation using 1wallet; issue was fixed on 1wallet side;                                         |
| 13.04.22 | Research safe-cli tool to manual create gnosis safe transactions                                                                           |
| 12.04.22 | Created workaround for metamask safe with outdated nonce param                                                                             |
| 11.04.22 | Debug waiting for execute multisig transactions for users using metamask                                                                   |
| 08.04.22 | Implemented internal values in transactions list, released on production (backend PR #39, client PR#164)                                   |
| 07.04.22 | Working on internal transaction values displayed in transactions list                                                                      |
| 06.04.22 | Get ERC20 balances from node RPC only when user toggle dropdown (PR #145); Started development UI for detailed info of internal txs values |
| 05.04.22 | Fixed issue with tx input utf8 text verification (PR #162); Updated google tags addresses list;                                            |
| 04.04.22 | Released updated Metrics using Metrics DAO data; Research of "multicall" transaction type inner logic                                      |
| 01.04.22 | Improved Metrics DAO queries; Removed unused logs index from indexer backend scheme;                                                       |
| 31.03.22 | Solved RDS issue with index; Added data provided from Metrics DAO (Wallets count, txs count) to explorer backend, created PR (#35)         |
| 30.03.22 | Searching the causes of performance problem with RDS, testing potential solutions                                                          |
| 29.03.22 | Bridge frontend features: add custom destination address, tokens amount                                                                    |
| 28.03.22 | Working on bridge UI: bridging scenario screens, tokens select, confirmation screen                                                        |
| 25.03.22 | Implementing Bridge page UI for trustless bridge app                                                                                       |
| 24.03.22 | Started integration of Trustless bridge frontend app with 1Wallet and Metamask                                                             |
| 23.03.22 | Debugging missing contract in production table, found issue and fixed (0x0d625029e21540abdfafa3bfc6fd44fb4e0a66d0);                        |
| 22.03.22 | Fixed not necessary contract symbol limit of 10 characters (explorer backend PR #32)                                                       |
| 21.03.22 | Working on trustless bridge UI client; updated wallets counter on production DB;                                                           |
