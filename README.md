# Oracle Blockchain Intro

A **blockchain** is a system for maintaining distributed ledgers of facts and the history of the ledger’s updates.

A blockchain is a continuously **growing list of records, called blocks**, which are linked and secured using cryptography.

**Chaincodes** define the data schema in the ledger, initialize it, **perform updates** when triggered by applications, and respond to queries.

Chaincodes can also **post events** that allow applications to be notified and perform downstream operations.

**Channels** partition and isolate peers and ledger data to provide private and confidential transactions on the blockchain network. Members define and structure channels to allow specific peers to conduct private and confidential transactions that other members on the same blockchain network can't see or access. Each channel includes peers, the shared ledger, chaincodes instantiated on the channel, and one or more ordering service nodes.

**Peer nodes** contain a **copy of the ledger** and write transactions to the ledger.

These nodes can also **endorse transactions**.

**REST proxy nodes** map an application identity to a blockchain member, which allows users and applications to call the Oracle Blockchain Platform REST APIs.
