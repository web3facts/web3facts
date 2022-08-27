There are several steps involved in adding a transaction to a [Proof of Work](#WhatIsProofOfWork) [Blockchain](#WhatIsABlockchain):
1.   A user sends a transaction request to a [Node](#WhatIsANode) on the network
2.   The [Node](#WhatIsANode) adds the request to a list of pending transaction stored in its memory (called the mempool)
3.   The [Node](#WhatIsANode) broadcasts the request to the rest of the network
4.   Miners read the pending transactions from a [Node](#WhatIsANode)'s mempool
5.   Miners select a pending transaction to process (usually higher value transactions are prioritized)
6.   Miners process the transaction, involving [Proof of Work](#WhatIsProofOfWork)
7.   Miners send the transaction along with the proof to a [Node](#WhatIsANode)
8.   The [Node](#WhatIsANode) verifies the transaction and accepts or declines it
9.   If accepted, the users pays the [miner](#WhatIsMining) a fee (called [GAS](#WhatIsGAS))
10.  If accepted, the transaction is added to the [Node](#WhatIsANode)s [Blockchain](#WhatIsABlockchain)
11.  If accepted, the balance of the associated Accounts is updated within the [Node](#WhatIsANode)'s [global state](#globalstate)
12.  If accepted, the verified transaction is broadcast to the rest of the network

In [Proof of Stake](#WhatIsProofOfStake) networks steps 4 to 7 differ in that a [miner](#WhatIsMining) (called a validator)
is randomly selected by the network to validate the Block.

The average time taken to add a transaction ranges from seconds to hours, depending on the cryptocurrency
network involved.

Transactions can also involve [Smart Contracts](#WhatIsASmartContract), in which the transaction will store
additional information that will be processed by the [Smart Contract](#WhatIsASmartContract). This will typically
require more [GAS](#WhatIsGAS) than a standard transaction.

-   [Bitcoin - How Transactions Work](https://www.bitcoin.com/get-started/how-bitcoin-transactions-work/)
-   [Ethereum - Transactions](https://ethereum.org/en/developers/docs/transactions/)
-   [Coinmarketcap - How Long Does a Bitcoin Transaction Take](https://coinmarketcap.com/alexandria/article/how-long-does-a-bitcoin-transaction-take)
-   [Coindesk - How to Check your Ethereum Transaction](https://www.coindesk.com/learn/how-to-check-your-ethereum-transaction/#:~:text=On%20average%2C%20it%20usually%20takes,network%20congestion%20at%20the%20time.)
